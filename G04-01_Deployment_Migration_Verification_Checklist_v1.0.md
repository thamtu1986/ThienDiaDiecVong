# G04-01 – Deployment & Migration Verification Checklist v1.0

**Status:** LOCKED for Implementation Planning  
**Baseline:** Phase 04 Revised Draft 15 | DDL Approved – With Conditions | Implementation Pending  
**Reference:** Technology Stack v1.0 · Revised Draft 9 · Governance Lock Phase 04  
**Date locked:** 2026-11-13  

**Scope of this document**  
Checklist nghiệm thu deployment & migration. Không tuyên bố Implementation Validated, PIT Verified hay Production Approved.

**Governance**  
- Không sửa Design Lock, Revised Draft 9, Phase 01–03.  
- Không ALTER Phase 02/03 tables từ Phase 04.  
- Không mở Phase 05.  
- Không chạy QP-01…QP-89 trước khi G04-01 PASS.  
- Mọi thay đổi sau khóa → Change Request + version riêng.

---

## 0. Python vs PostgreSQL responsibility

| Component | Technology | Responsibility |
|---|---|---|
| Deployment Runner | Python 3.12+ | Orchestrate Phase 01→04 order, stop on error |
| Database Access | SQLAlchemy 2.x | Connections, transactions |
| Configuration | YAML + Pydantic v2 | Env validation |
| Migration Scripts | PostgreSQL SQL | Schema, constraints, triggers, SECURITY DEFINER |
| Verification Engine | Python + SQL | Run G04-01 assertions C1–C14 |
| Test Runner | Pytest | QP-01…QP-89 (after G04-01 PASS) |
| Evidence Generator | Python | PASS/FAIL/BLOCKED/NOT RUN + logs/checksums |
| Backup / Restore | pg_dump, pg_restore, pg_basebackup | Actual backup artifacts |

**Hard rule:** Trigger, constraint, atomic Promotion, concurrency control **remain in PostgreSQL**. Python must not re-implement them.

---

## 1. Pre-deployment (A1–A10)

| ID | Item | Pass criteria | Evidence |
|---|---|---|---|
| A1 | PostgreSQL version | **15+** major version matches test plan | `SELECT version();` |
| A2 | Target instance | Dev/staging only; not production | Inventory |
| A3 | Disk / WAL capacity | Space for data + archive + backup | `df -h`, settings |
| A4 | Extensions | **Only if DDL requires them.** `gen_random_uuid()` is core PG15 — **do not** require `pgcrypto` solely for UUID | `\dx` + DDL scan |
| A5 | Roles plan | See §3 Role hardening (beyond NOLOGIN/NOINHERIT) | `pg_roles`, membership queries |
| A6 | Migration order | Phase **01 → 02 → 03 → 04 Draft 15** only | Plan file |
| A7 | Schema drift guard | Version `phase04-draft15`; refuse re-run | DDL |
| A8 | Pre-migration backup | Globals + logical DB dump; restore drill on **test** cluster | Files + restore log |
| A9 | Rollback plan | Restore from backup; no ad-hoc reverse DDL | Documented steps |
| A10 | Maintenance window | Documented; connections drained if needed | Change ticket |

**Migration command (mandatory flags):**

```bash
psql -X -v ON_ERROR_STOP=1 \
  -U postgres \
  -d mftds_db \
  -f migrations/phase04/mftds_phase04_revised_draft_15.sql
```

- `-X` ignores `.psqlrc`  
- `ON_ERROR_STOP=1` aborts on first SQL error  
- Confirm script uses a single transaction boundary compatible with DDL used (no non-transactional ops that leave partial state without clear recovery)

---

## 2. Deployment order (B1–B11)

```
B1  Pre-migration backup (globals + logical; physical if live data)
B2  Apply Phase 01 DDL
B3  Smoke-check Phase 01 objects + roles
B4  Apply Phase 02 DDL
B5  Smoke-check instrument_id / bitemporal tables
B6  Apply Phase 03 DDL
B7  Smoke-check market_ohlcv + lineage columns
B8  Apply Phase 04 Revised Draft 15
B9  Verify schema_migrations contains phase04-draft15
B10 Role / privilege assertions (§3, C9–C12)
B11 Post-migration assertions C1–C14
```

Do not collapse phases into one untested “all-in-one” run until each phase has standalone evidence.

---

## 3. Role hardening (A5 detail)

| Check | Expected |
|---|---|
| `mftds_quality_owner` | `NOLOGIN`, not SUPERUSER, not replication, not bypassrls |
| `mftds_runtime` | `NOINHERIT`, not SUPERUSER, not replication, not bypassrls |
| Membership | Runtime **not** direct or recursive member of owner |
| SET ROLE | Runtime **cannot** `SET ROLE mftds_quality_owner` |
| Ownership | Runtime owns **no** controlled schema/table/sequence/function |
| Schema CREATE | Runtime has **no** CREATE on `mftds_quality` |
| Direct DML | Runtime has **no** INSERT/UPDATE/DELETE on controlled tables |
| Owner login | Owner cannot log in directly |

`NOINHERIT` alone is **not** sufficient.

---

## 4. Post-migration assertions (C1–C14)

| ID | Assertion | Expected |
|---|---|---|
| C1 | `schema_migrations` | Contains `phase04-draft15` |
| C2 | Schema owner | `mftds_quality` owned by `mftds_quality_owner` |
| C3 | Runtime privileges | No CREATE on schema; no direct DML on controlled tables |
| C4 | Entry points | Only approved SECURITY DEFINER functions GRANT EXECUTE to runtime |
| C5 / C10 | Function ACL | PUBLIC has no EXECUTE except explicitly approved exceptions |
| C11 | Default privileges | New functions under owner do **not** auto-grant EXECUTE to PUBLIC |
| C6 | Canonical mapping | Three fixed targets present |
| C7 | Migration guard | Second apply of Draft 15 **FAILS** |
| C8 / C12 | SECURITY DEFINER | Fixed `search_path`; trusted schemas not writable by runtime; `pg_temp` last if present; objects schema-qualified; call under hostile session `search_path` still safe |
| C9 | Role membership | Runtime cannot SET ROLE owner (session test, not catalog-only) |
| C13 | Backup restore | **Separate** pre-Phase 04 and post-Phase 04 drills (see §5) |
| C14 | WAL archive | Archive succeeds; restore drill on test instance (when WAL layer is in scope) |

**Session-based checks:** C9, C10/C11, C12 must include a real connection as `mftds_runtime` (or equivalent login role), not only `pg_catalog` queries.

---

## 5. Backup & restore

### 5.1 RPO/RTO

| Layer | RPO (target estimate) | RTO (target estimate) | Note |
|---|---|---|---|
| Logical (`pg_dump`) | Hours–days (schedule) | Minutes–hours | **Not verified commitment** |
| Physical + WAL | Minutes (archive lag dependent) | Minutes | Depends on I/O, size, network |
| PITR | Seconds–minutes | Minutes | Requires proven archive + drill |

Actual RPO/RTO = measured on **this** instance after drills. Do not treat table values as SLA.

### 5.2 Logical backup (mandatory for G04-01)

```bash
# Globals (roles, tablespaces)
pg_dumpall -U postgres --globals-only \
  -f data/backups/globals_$(date +%Y%m%d_%H%M).sql

# Database custom format
pg_dump -U postgres -Fc \
  -f data/backups/mftds_pre_phase04_$(date +%Y%m%d_%H%M).dump \
  mftds_db
```

### 5.3 Restore drill — **globals first**

```bash
# 1. Restore roles/tablespaces into TEST cluster
psql -U postgres -d postgres -v ON_ERROR_STOP=1 \
  -f data/backups/globals_YYYYMMDD_HHMM.sql

# 2. Create empty test database
createdb -U postgres mftds_restore_test

# 3. Restore database dump
pg_restore -U postgres -d mftds_restore_test \
  --clean --if-exists \
  data/backups/mftds_pre_phase04_YYYYMMDD_HHMM.dump
```

Without globals restore, owners/ACLs in the dump may not apply correctly.

### 5.4 Split assertions by restore point (C13)

| Restore point | Valid checks | Invalid checks |
|---|---|---|
| **Pre-Phase 04** | Phase 01–03 objects, roles, lineage columns as applicable | **Do not** require `phase04-draft15` in `schema_migrations` (table may not exist) |
| **Post-Phase 04** | `schema_migrations` contains `phase04-draft15`; C1–C12 | — |

### 5.5 WAL archive (when continuous archive is enabled)

Do **not** rely on bare:

```text
test ! -f ... && cp ...
```

Requirements:

- Dedicated archive script: checksum if target exists, write temp file, atomic rename.  
- `wal_level` / `archive_mode` require **restart** to take effect.  
- Service account write permission on archive dir.  
- Capacity monitoring + alert on archive failure.  
- `pg_stat_archiver` is partial evidence only.  
- PITR needs `restore_command`, recovery target, and a **restore drill on a test instance**.

C14 applies when WAL layer is in the deployment scope for this gate; otherwise mark C14 **NOT RUN** with explicit rationale (not PASS).

---

## 6. Acceptance matrix

| Gate | Condition |
|---|---|
| A1–A10 | Pre-deployment complete |
| B1–B11 | Deployment order correct |
| C1–C14 | All assertions PASS (or C14 NOT RUN with reason) |
| Restore Drill | Globals + DB restore succeeds on test instance |
| Migration Guard | Second apply rejected |
| Evidence Pack | Logs, SQL output, timestamps, checksums, backup paths |

**Verdict rules**

| Result | Meaning |
|---|---|
| **PASS** | All required conditions met with execution evidence |
| **FAIL** | Any required assertion failed or backup unrestorable |
| **BLOCKED** | Missing Phase 01–03 DDL, instance, or dependency |
| **NOT RUN** | Not executed — **must not** be recorded as PASS |

---

## 7. Evidence pack (minimum)

- Pre/post migration timestamps  
- `SELECT version();`  
- Migration logs (`psql -X -v ON_ERROR_STOP=1`)  
- Assertion query outputs C1–C14  
- Backup file paths + sizes + checksums  
- Restore drill log (pre and/or post as applicable)  
- Second-apply failure message for migration guard  

---

## 8. Project layout (Technology Stack v1.0)

```text
MFTDS/
├── configs/
│   ├── database.yaml
│   ├── deployment.yaml
│   └── roles.yaml
├── migrations/
│   ├── phase01/
│   ├── phase02/
│   ├── phase03/
│   └── phase04/
│       └── mftds_phase04_revised_draft_15.sql
├── src/mftds/
│   ├── deployment/     # runner, migration_guard, rollback
│   ├── database/       # connection, transaction
│   ├── verification/   # preflight, post_migration, assertions
│   ├── backup/         # logical, physical, restore orchestration
│   └── reporting/      # acceptance_report
├── tests/
│   ├── deployment/
│   ├── phase04/        # QP suites (after G04-01)
│   └── integration/
├── data/
│   ├── backups/
│   └── evidence/
├── docs/G04-01/
├── pyproject.toml
└── README.md
```

---

## 9. Implementation sequence (code)

1. **Python Foundation** — connection, YAML, Pydantic, logging, env guard  
2. **Deployment Runner** — version guard, Phase 01→04 order, fail-fast  
3. **G04-01 Verification** — assertions C1–C14  
4. **Backup & Recovery orchestration** — wrap pg tools; verify restore  
5. **QP Test Framework** — only after G04-01 PASS  
6. **Technical Acceptance Report**

**Start now:** Python Foundation + G04-01 Deployment Runner only.  
**Do not** start QP framework until G04-01 PASS.

---

## 10. OPEN TECHNICAL DECISION

| ID | Decision | Status |
|---|---|---|
| OTD-G04-01-ENV | PostgreSQL host: **Windows local** vs **Linux/VPS server** | **OPEN – must lock before connection/backup code** |

Affects: process control, paths, credentials, service account, `pg_basebackup`/`archive` layout, runner packaging.

---

## 11. Document status

| Item | Status |
|---|---|
| Migration order | Accepted |
| Pre-deployment checklist | Accepted (v1.0) |
| Backup architecture | Accepted with §5 clarifications |
| Role / privilege assertions | Accepted (§3, C9–C12) |
| Post-migration assertions | Accepted C1–C14 |
| G04-01 execution | **NOT STARTED** |
| G04-01 PASS | **NOT CLAIMED** |
| Phase 05 | NOT STARTED |
| QP-01…QP-89 | Blocked until G04-01 PASS |

**DDL Approved ≠ Implementation Validated ≠ PIT Verified ≠ Production Approved.**

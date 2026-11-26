# THỜI GIAN ĐẠO TỔ — THIÊN ĐỊA DIỆC VONG
## World Bible — v1.2 (Bản Dự Thảo Tích Hợp Kiến Trúc — Kế Thừa v1.0 & v1.1)

- **Trạng thái tài liệu:** `PHASE 5 INTEGRATION DRAFT — PREPARATION / WORKING BASELINE` (`DRAFT – AWAITING REVIEW`, `Canon: NOT LOCKED`)
- **Quyết định kiến trúc áp dụng:** `P1 + P2 + P3 — APPROVED WITH NOTES (3/3)` (giữ nguyên toàn bộ `Notes`, `Open Points`, `Deferred Items` và ranh giới không tự động mở rộng)
- **Chuỗi kế thừa phiên bản:** `World Bible v1.0` (`world_bible.md` v1.0) → `World Bible v1.1` (`world_bible.md` v1.1) → `World Bible v1.2` (`World Bible v1.2.md`)
- **Phạm vi tham khảo bên ngoài:** *Phàm Nhân Tu Tiên* và *Tiên Nghịch* chỉ dùng làm phân tích nguyên lý thiết kế tham chiếu (`Reference Analysis I` & `Reference Study II`); không sao chép tên gọi, phẩm cấp, công pháp, bảo vật, tình tiết hay cơ chế riêng vào *Thiên Địa Diệc Vong*.

---

## PHẦN 0 — GOVERNANCE, RANH GIỚI KIỂM SOÁT & QUY ƯỚC TRẠNG THÁI

### 0.1. Sổ trạng thái governance & ranh giới bảo toàn
* **World Bible v1.2:** Đã hoàn tất `Phase 1–3`, `Phase 4` (`P1`, `P2`, `P3` quyết định `APPROVED WITH NOTES` 3/3), và được ủy quyền triển khai `Phase 5 — Integration` ở phạm vi giới hạn (`P1–P3` kèm toàn bộ `Notes`, `Open Points`, `Deferred Items`). Không ghi đè trực tiếp `v1.0` hoặc `v1.1`.
* **World Bible v1.0 & v1.1:** Bảo toàn nguyên trạng nền tảng; kế thừa đầy đủ nội dung đã có trong tài liệu nguồn mà không tự suy diễn hoặc sửa đổi hồi tố.
* **Canon:** `NOT LOCKED`.
* **OD-01 – OD-12:** `OPEN — NOT CLOSED` (chưa đối chiếu toàn văn nguyên bản của cả 12 mục; không tự đóng).
* **GV-01 – GV-09:** `RECEIVED — NOT RATIFIED`.
* **Bản thảo & phân quyền chương:**
  * `C1–C25`: Protected baseline (không sửa đổi hồi tố).
  * `Stage 1 — Phá Thiên Chung`: `ENFORCED`.
  * `DSR-01–05`: `RATIFIED & ACTIVE`.
  * `C24`: `ACCEPTED — 2,089 UNITS` / Tên chương `Đường về dưới bóng chiều` (`APPROVED / NOT LOCKED`).
  * `C25`: `ACCEPTED — 2,064 UNITS` / Tên chương `Nơi Trú Khi Đêm Xuống` (`PROPOSED — PENDING APPROVAL / NOT LOCKED`).
  * `C26 — Draft 1`: `DRAFTED — NOT SUBMITTED FOR REVIEW` (không chỉnh sửa; `Gate B` chưa đếm chính xác; `Revision Round 1` chưa mở).
  * `C26 Writing Authorization`: `AUTHORIZED — C26 ONLY`.
  * `C27–C35`: `NOT AUTHORIZED`.
  * `Batch B`: `NOT STARTED`.

### 0.2. Phạm vi không được tự động mở rộng khi tích hợp P1–P3
Việc tích hợp `P1`, `P2`, `P3` theo trạng thái `APPROVED WITH NOTES` **không** tự động phê duyệt hoặc kích hoạt:
* Bất kỳ công pháp, kỹ pháp, thuật pháp, thần thông, bí thuật hay cấm thuật cụ thể nào.
* Số lượng năng lực, tốc độ học, tốc độ tu luyện, điều kiện đột phá, công thức định lượng hoặc mốc cảnh giới cụ thể của Lâm Tĩnh (`C16–C100` / `C26–C100`).
* Bất kỳ pháp bảo, bản mệnh pháp bảo, `Tích Kình`, trận pháp, phù lục, đan dược, linh thú/linh sủng hay chiến công cụ thể nào.
* Việc sửa đổi `CULT-04–05`, tự đóng `OD-01–OD-12`, khóa `World Bible` / `Canon`, hoặc cấp quyền viết cho `C27–C35`.

### 0.3. Nhãn trạng thái (Kế thừa v1.0 & v1.1)
* **`[ĐÃ CHỐT]` / `APPROVED – KIẾN TRÚC`:** Quyết định người dùng đã xác nhận hoặc kiến trúc/quy tắc đã được xác nhận ở cấp độ thiết kế; thông số định lượng hoặc cơ chế chưa chốt vẫn được kiểm soát chặt.
* **`[ĐỊNH HƯỚNG]` / `[ĐỀ XUẤT]` / `PROPOSED`:** Nguyên tắc hoặc phương án thiết kế đang trình bày để rà soát, chưa khóa làm quy tắc cuối cùng.
* **`SUPPORTED BY APPROVED RULES`:** Nội dung được hỗ trợ bởi một hoặc nhiều quy tắc đã duyệt (kèm mã tham chiếu đúng phạm vi).
* **`[CHƯA KHÓA]` / `OPEN QUESTION`:** Vấn đề cố ý để mở nhằm tránh khóa sớm bí mật, ép thông số hoặc tạo mâu thuẫn về sau.
* **`DRAFT – AWAITING REVIEW`:** Trạng thái bản thảo tài liệu đang chờ rà soát và xác nhận.

Không được tự động nâng một chi tiết từ `[ĐỀ XUẤT]` / `PROPOSED` hoặc `[CHƯA KHÓA]` / `OPEN QUESTION` (bao gồm các giả thuyết thiết kế) thành `[ĐÃ CHỐT]` / `APPROVED – KIẾN TRÚC`.

### 0.4. Các quyết định nền tảng đã chốt (Kế thừa v1.0 & v1.1)
1. Đại cục kết hợp ba trục:
   - **B — Kỷ Nguyên Bị Xóa:** Nền bí sử và cấu trúc thế giới.
   - **C — Chuông Trấn Thiên Kiếp:** Động cơ xung đột xuyên suốt.
   - **A — Nghịch Thiên Cải Mệnh:** Chiều sâu triết học và giới hạn của can thiệp thời gian – nhân quả.
2. Lâm Tĩnh là người thực tế, tính toán, cẩn trọng, lạnh lùng khi cần nhưng có giới hạn đạo đức riêng.
3. Kết thúc hướng đến vượt khỏi thiên địa, phải trả giá lớn.
4. Quy mô là trường thiên dài, nhiều giai đoạn và tầng thế giới.

### 0.5. Nguyên tắc thiết kế thế giới (Kế thừa v1.0 & v1.1)
- Thế giới phải có quy luật tồn tại độc lập với nhân vật chính.
- Mỗi khu vực cần có chức năng địa lý, kinh tế, chính trị và cốt truyện.
- Lịch sử không chỉ là danh sách triều đại; nó phải giải thích nguồn gốc các thiết chế, xung đột và điều cấm kỵ hiện tại.
- Không phải mọi cư dân đều biết thế giới có kỷ nguyên bị xóa hoặc đại kiếp chưa kết thúc.
- Các thế lực không được chia đơn giản thành chính – tà. Mỗi phe có lợi ích, lý tưởng, giới hạn và mâu thuẫn nội bộ.
- Pháp tắc thời gian không phải quyền năng sửa sai miễn phí.
- Bí mật lớn phải có dấu vết được gieo từ sớm, có nhiều cách diễn giải và có quá trình kiểm chứng.
- Quy mô vũ trụ chỉ mở rộng khi câu chuyện có nhu cầu; không đưa ra vô số tầng giới chỉ để phóng đại sức mạnh.
- Giả thuyết thiết kế không được ghi thành thông số chính thức trước khi được kiểm chứng và phê duyệt.

---

## PHẦN I — CẤU TRÚC VŨ TRỤ (KẾ THỪA v1.0 & v1.1)

### 1. Mô hình tổng thể
`PROPOSED` Vũ trụ truyện được gọi tạm là **Đại Thiên Giới**, gồm nhiều tầng không gian, khu vực và miền pháp tắc có quan hệ liên thông nhưng không nhất thiết nằm trên cùng một trục địa lý hoặc quyền lực.

Các thành phần chính:
1. **Hạ Giới:** Tập hợp các đại lục, hải vực và tiểu giới nơi phàm nhân cùng phần lớn tu sĩ ở các cảnh giới thấp sinh sống.
2. **Tiên Giới** *(tương ứng định hướng Thượng giới trong v1.0 với quy ước thuật ngữ v1.1)*: Tầng thế giới có điều kiện linh khí và cấu trúc pháp tắc cao hơn, nơi tồn tại hệ thống cảnh giới Tiên Giới.
3. **Cổ vực:** Những khu vực có cấu trúc không gian, thời gian hoặc pháp tắc bất thường, thường liên quan đến di tích và dấu vết của các kỷ nguyên trước.
4. **Ngoại tầng:** Phạm vi tồn tại nằm ngoài nhận thức và bản đồ thông thường của các giới hiện tại. Bản chất của nó chưa được xác định.

Quy ước thuật ngữ:
- **Hạ Giới** và **Tiên Giới** là hai phạm vi thế giới được sử dụng khi mô tả hệ thống cảnh giới.
- **Thượng giới** là cách gọi khái quát trong một số ngữ cảnh về tầng thế giới cao hơn; không tự động đồng nhất mọi cách sử dụng từ này với toàn bộ Tiên Giới.
- **Cổ vực** có thể nằm xen trong Hạ Giới, Tiên Giới hoặc vùng giao giới; không mặc nhiên là một tầng thế giới độc lập.
- **Ngoại tầng** chưa được xác nhận là một địa điểm vật lý, trạng thái tồn tại hay một miền pháp tắc riêng.

Việc mở rộng tầng thế giới không đồng nghĩa tự động tăng cảnh giới hoặc sức mạnh của mọi cư dân tại đó (một tu sĩ ở tầng cao vẫn có thể bị giới hạn bởi thương thế, tài nguyên, pháp tắc địa phương hoặc chính trị; một cổ vực có thể nguy hiểm với cả cường giả).

#### 1.1. Quan hệ giữa các tầng
- Hạ Giới và Tiên Giới có thể liên thông qua phi thăng lộ, cổ trận, khe nứt hoặc những chu kỳ mở cửa có điều kiện.
- Không phải mọi thông đạo đều ổn định; một số chỉ mở trong thời gian ngắn hoặc đòi hỏi cái giá lớn.
- Cổ vực có thể nằm xen trong Hạ Giới, Tiên Giới hoặc vùng giao giới; không nhất thiết là một "tầng" riêng biệt.
- Ngoại tầng chưa được xác nhận là nơi chốn vật lý, một trạng thái tồn tại hay một miền pháp tắc khác.

#### 1.2. Quy tắc mở rộng quy mô
Mỗi lần câu chuyện mở ra một tầng thế giới mới, cần trả lời:
1. Vì sao nhân vật có thể tiếp cận tầng này?
2. Điều gì ở đây khác căn bản so với tầng trước?
3. Ai kiểm soát lối vào và nguồn lực?
4. Những hiểu biết cũ nào bị chứng minh là sai hoặc thiếu?
5. Tầng mới tạo ra xung đột gì mà tầng cũ không thể giải quyết?

### 2. Không gian, thời gian và nhân quả

#### 2.1. Không gian
`PROPOSED` Không gian có thể bị chia cắt, uốn cong hoặc khóa bởi trận pháp, cấm chế và di tích cổ. Tuy nhiên, dịch chuyển không gian phải có điều kiện.

Quy tắc đề xuất:
- Khoảng cách địa lý vẫn có ý nghĩa; đi đường bộ, đường biển, phi hành và truyền tống có chi phí khác nhau.
- Truyền tống cần tọa độ hoặc mốc không gian đã được xác lập, năng lượng và độ ổn định của điểm đến.
- Trận pháp phong tỏa có thể chặn hoặc làm sai lệch tọa độ.
- Cổ vực có thể làm khoảng cách bên trong khác với khoảng cách bên ngoài.
- Không cho phép nhân vật tùy tiện "xé không gian" để bỏ qua mọi hành trình, trừ khi năng lực và cái giá đã được định nghĩa rõ.

#### 2.2. Thời gian
`PROPOSED` Thời gian có chiều vận hành phổ biến, nhưng tốc độ trôi có thể khác nhau tại một số vùng đặc biệt.

Quy tắc đề xuất:
- Mỗi khu vực có một mốc thời gian chuẩn dùng cho lịch sử, giao dịch và liên lạc.
- Vùng có dòng thời gian dị thường phải có ranh giới, điều kiện kích hoạt và mức sai lệch có thể đo hoặc ước lượng.
- Chênh lệch thời gian không tự tạo thêm tuổi thọ miễn phí: cơ thể, thần hồn và nhân quả vẫn có thể chịu hao tổn.
- Thời gian trong không gian nội tại của Phá Thiên Chung là cơ chế riêng (chi tiết cơ chế mở ở `WQ-12` / `WQ-13`, thiết kế tại `artifact_bible.md`), không đại diện cho mọi vùng thời gian dị thường.
- Không dùng du hành thời gian tùy ý để sửa lại sự kiện đã xảy ra. *(Liên quan: `WQ-05`, `WQ-06`)*

#### 2.3. Nhân quả
`PROPOSED` Nhân quả là quan hệ giữa hành động, điều kiện và hệ quả; không phải một vị thần toàn năng ghi sổ mọi hành vi. Nó biểu hiện qua các quy luật của thế giới và những ràng buộc có thể tích lũy.

Ba loại hệ quả nên phân biệt:
1. **Hệ quả trực tiếp:** Thương tích, mất tài nguyên, bị truy sát, thay đổi quyền lực.
2. **Hệ quả dây chuyền:** Một thay đổi làm biến động chuỗi sự kiện, quan hệ hoặc lợi ích của nhiều bên.
3. **Phản chấn pháp tắc:** Khi can thiệp vào thời gian hoặc cấu trúc vận hành của thế giới, sự bất ổn có thể xuất hiện ở chủ thể, khu vực hoặc thời điểm khác.

Không phải mọi hành động đều phải có "thiên phạt". Phản chấn chỉ xuất hiện khi có cơ chế cụ thể bị xâm phạm; nếu lạm dụng nó sẽ biến thành công cụ trừng phạt tùy tiện của tác giả. *(Liên quan: `WQ-05`, `WQ-06`)*

---

## PHẦN II — LỊCH SỬ VÀ KỶ NGUYÊN (KẾ THỪA v1.0 & v1.1)

### 3. Mô hình lịch sử lớn
`PROPOSED` Lịch sử được chia thành năm kỷ nguyên tạm thời. Tên gọi chính thức có thể thay đổi sau khi xây dựng timeline.

| Kỷ nguyên | Mô tả khái quát | Trạng thái |
| :--- | :--- | :--- |
| Kỷ Nguyên Khai Nguyên | Thế giới hình thành trật tự pháp tắc nền tảng; nguồn gốc thật chưa rõ | `OPEN QUESTION` |
| Kỷ Nguyên Cổ Đạo | Các nền văn minh tu hành đầu tiên phát triển; hiểu biết về thời gian và không gian đạt mức cao | `PROPOSED` |
| Kỷ Nguyên Đại Biến | Một biến cố làm đứt gãy trật tự cũ; các thế lực tranh chấp cách xử lý | `PROPOSED` |
| Kỷ Nguyên Bị Xóa | Một phần lịch sử, tên gọi, nhân vật và sự kiện bị loại khỏi chính sử hoặc bị biến dạng | `PROPOSED` |
| Kỷ Nguyên Hiện Tại | Các thế lực hiện tại xây dựng trật tự trên nền di tích và hậu quả của quá khứ | `PROPOSED` |

Không khóa ngay con số niên đại, thời lượng từng kỷ nguyên hoặc tên nhân vật lịch sử. Những yếu tố này cần được xác lập trong `timeline.md` sau khi cơ chế đại kiếp được duyệt. *(Liên quan: `WQ-01`, `WQ-02`)*

### 4. Kỷ Nguyên Bị Xóa

#### 4.1. Điều được xác lập ở cấp độ premise
- Một kỷ nguyên hoặc nền văn minh cổ từng tồn tại.
- Dấu vết của nó còn sót lại trong di tích, cấm địa, pháp bảo, văn tự và dị biến pháp tắc.
- Lịch sử hiện tại không phản ánh đầy đủ sự thật.
- Việc xóa lịch sử có liên quan đến đại biến cố và đại kiếp.

#### 4.2. Giả thuyết thiết kế đề xuất
`PROPOSED` Không nên để toàn bộ lịch sử bị xóa bởi một người duy nhất. Hợp lý hơn là có nhiều lớp che giấu:
- Một phần tư liệu bị hủy trong chiến tranh.
- Một phần bị các thế lực chiến thắng viết lại.
- Một phần bị phong ấn vì người đời sau không đủ khả năng chịu đựng hoặc hiểu biết.
- Một phần tự biến dạng do pháp tắc thời gian – nhân quả bị tổn thương.
- Một số cộng đồng vẫn giữ ký ức truyền khẩu nhưng không biết cách kiểm chứng.

Điều này tạo ra nhiều phiên bản lịch sử có mâu thuẫn, thay vì một cuốn "sách sự thật" được tìm thấy là giải quyết toàn bộ bí ẩn.

#### 4.3. Dấu vết trong hiện tại
Có thể gieo manh mối qua:
- Kiến trúc cổ không khớp với kỹ thuật xây dựng được ghi nhận.
- Bản đồ có vùng đất hoặc hải vực không còn tồn tại.
- Tên một số tinh tú, dòng sông, linh mạch xuất hiện trong văn tự cổ nhưng không có trong địa lý hiện tại.
- Công pháp có tầng vận hành bị khuyết.
- Cổ vật phản ứng với những nơi không được ghi trên bản đồ.
- Các truyền thuyết của những dân tộc xa nhau lại có chung một chi tiết không thể giải thích.
- Niên đại trong các di tích có sai lệch nhưng sai lệch theo một quy luật.

Mỗi manh mối cần có ít nhất hai cách diễn giải ban đầu. Không nên để nhân vật nhìn thấy một ký hiệu cổ rồi lập tức biết toàn bộ lịch sử.

#### 4.4. Câu hỏi chưa được khóa
1. Kỷ nguyên bị xóa có phải chính là kỷ nguyên đã tạo ra Phá Thiên Chung không?
2. Việc xóa lịch sử là chủ ý của người sống sót, cơ chế tự vệ của thiên địa hay hệ quả ngoài ý muốn?
3. Những người bị xóa khỏi lịch sử đã chết, bị phong ấn, chuyển sang trạng thái tồn tại khác hay chưa từng biến mất hoàn toàn?
4. Có ai trong hiện tại biết sự thật gần trọn vẹn không?
5. Lịch sử bị xóa để ngăn đại kiếp tái diễn, hay để che giấu trách nhiệm của một thế lực?

Các câu hỏi này phải được giải quyết theo từng tầng truyện, không giải đáp cùng lúc. *(Liên quan: `WQ-04`)*

### 5. Đại kiếp cổ xưa

#### 5.1. Định nghĩa làm việc
`PROPOSED` Đại kiếp là một biến cố quy mô vượt khỏi một quốc gia, đại lục hoặc tông môn, có khả năng làm thay đổi cấu trúc tồn tại của nhiều tầng thế giới. Nó chưa thực sự được giải quyết; trạng thái hiện tại chỉ là trì hoãn, phong ấn hoặc chuyển hóa.

`OPEN QUESTION` Đại kiếp là một thực thể, hiện tượng pháp tắc, chu kỳ vũ trụ, hậu quả của một hành động nghịch thiên hay tổ hợp nhiều yếu tố. *(Liên quan: `WQ-01`, `WQ-03`, `WQ-04`)*

#### 5.2. Mô hình đề xuất: "Vết Nứt Đại Đạo"
`PROPOSED` Một biến cố trong Kỷ Nguyên Cổ Đạo đã làm tổn thương sự liên kết giữa các pháp tắc nền tảng. Tổn thương này không nhất thiết là một vết nứt vật lý; nó có thể biểu hiện thành:
- Vùng thời gian trôi lệch.
- Không gian mất ổn định.
- Sinh linh hoặc vật thể bị lặp lại, biến dạng hay mất dấu.
- Linh mạch suy kiệt hoặc phát sinh năng lượng dị thường.
- Một số quy luật sinh tử, luân chuyển linh lực hoặc ký ức vận hành không còn nhất quán.

Các nền văn minh cổ đã tìm cách ngăn tổn thương lan rộng. Họ có thể đã thành công một phần, nhưng cái giá là sự sụp đổ của trật tự cũ và việc che giấu lịch sử.

Tên "Vết Nứt Đại Đạo" chỉ là thuật ngữ thiết kế; chưa phải tên canon của đại kiếp.

#### 5.3. Vì sao đại kiếp chưa kết thúc?
Một trong các mô hình sau có thể được chọn ở giai đoạn thiết kế sâu:
- **Phong ấn duy trì:** Đại kiếp bị giữ lại bởi một hệ thống phong ấn, nhưng phong ấn đang suy yếu.
- **Chuyển dịch hậu quả:** Tổn thương được phân tán sang nhiều vùng hoặc nhiều thời đại.
- **Chu kỳ tái phát:** Đại kiếp vận hành theo chu kỳ; mỗi lần tái phát mạnh hơn hoặc thay đổi hình thái.
- **Trạng thái bị trì hoãn:** Một hành động cổ xưa đã dừng quá trình, nhưng không giải quyết nguyên nhân gốc.

Không nên chọn tất cả cùng lúc nếu không có mô hình thống nhất. Có thể kết hợp hai cơ chế nếu giải thích được quan hệ nhân quả.

#### 5.4. Dấu hiệu tái phát theo cấp độ
| Cấp | Biểu hiện | Tác động |
| :--- | :--- | :--- |
| I — Dị tượng cục bộ | Mất phương hướng, thời gian sai lệch nhẹ, linh khí biến động | Dân thường và tu sĩ thấp tầng chịu ảnh hưởng |
| II — Dị biến khu vực | Cấm địa mở rộng, linh mạch rối loạn, sinh linh biến đổi | Tông môn và thành trì phải can thiệp |
| III — Đứt gãy liên giới | Thông đạo mất ổn định, vùng không gian bị cô lập | Đại lục và thế lực lớn bị cuốn vào |
| IV — Sụp đổ pháp tắc | Một số quy luật nền tảng không còn đáng tin cậy | Thượng giới và các cường giả buộc phải hành động |
| V — Đại kiếp toàn diện | Trật tự hiện tại đứng trước nguy cơ bị thay thế hoặc tan rã | Mọi thế lực phải lựa chọn |

Bảng này mô tả mức độ biểu hiện, không phải thang sức mạnh của quái vật.

#### 5.5. Vai trò của Phá Thiên Chung
`PROPOSED` Phá Thiên Chung có liên quan sâu đến đại kiếp và lịch sử bị xóa.

`OPEN QUESTION` Chiếc chuông là:
- Công cụ từng tham gia phong ấn.
- Mảnh vỡ của một pháp tắc.
- Chìa khóa mở hoặc đóng một cơ chế.
- Di vật của người từng tìm cách vượt khỏi thiên địa.
- Hoặc một vật có vai trò phức tạp hơn các giả thuyết trên.

Không xác nhận chiếc chuông là vật duy nhất có thể cứu thế giới. Cần có các phương án khác, dù không hoàn hảo, để các thế lực có lý do hành động độc lập. *(Liên quan: `WQ-13`)*

---

## PHẦN III — ĐỊA LÝ VÀ KHU VỰC (KẾ THỪA v1.0 & v1.1)

### 6. Cấu trúc địa lý theo tầng truyện

#### 6.1. Vùng duyên hải khởi đầu
`PROPOSED` Lâm Tĩnh xuất thân từ một làng chài hẻo lánh. Khu vực này cần được xây dựng như một vùng có đời sống kinh tế và địa lý hoàn chỉnh, không chỉ là phông nền cho cảnh nhặt được pháp bảo.

Cấu trúc gồm:
- Một làng chài nhỏ dựa vào đánh bắt ven bờ và trao đổi với thuyền buôn.
- Một cảng hoặc bến trung chuyển cách làng một hành trình có thể đo được.
- Một số đảo gần bờ, bãi đá, vùng nước xoáy và tuyến hải lưu.
- Một vùng biển xa có thời tiết khó lường, gắn với biến cố mở đầu.
- Một tuyến thương mại theo mùa; hoạt động đánh bắt, vận tải và giá cả thay đổi theo gió mùa.

Nguyên tắc liên tục:
- Khoảng cách từ làng đến cảng, đảo và vùng biển nguy hiểm phải được xác lập.
- Thời gian chèo thuyền, đi bộ hoặc thuê thuyền phải hợp lý.
- Bão, thủy triều, nguồn nước ngọt, lương thực, thương tích và vật liệu sinh tồn phải được theo dõi.
- Người dân không thể biết hoặc giải thích mọi hiện tượng bằng thuật ngữ tu tiên.

#### 6.2. Khu vực tu hành địa phương
`PROPOSED` Đây là vùng đầu tiên Lâm Tĩnh tiếp xúc với trật tự tu tiên có tổ chức.

Thành phần địa lý:
- Một dãy núi có linh mạch cấp thấp và trung bình.
- Một hoặc vài thành trấn nơi phàm nhân, thương nhân và tu sĩ cùng sinh sống.
- Phường thị trao đổi linh thạch, linh dược, công pháp phổ thông và pháp khí.
- Một số động phủ hoặc di tích nhỏ, có chủ sở hữu hoặc tranh chấp rõ ràng.
- Tuyến đường bộ và thủy lộ nối vùng duyên hải với trung tâm tu hành.

Chức năng truyện:
- Giới thiệu luật lệ, tài nguyên và phân tầng xã hội.
- Tạo xung đột về thân phận, quyền tiếp cận công pháp và nguồn lực.
- Cho thấy tông môn không phải nơi trú ẩn tuyệt đối.
- Là nơi các manh mối cổ đại đầu tiên xuất hiện ở quy mô có thể kiểm chứng.

#### 6.3. Đại lục
`PROPOSED` Đại lục không nên chỉ là bản đồ rộng hơn. Nó cần có nhiều trung tâm quyền lực và hệ sinh thái kinh tế – chính trị.

Các cấu phần:
- Vùng núi có linh mạch lớn, là căn cứ của đại tông môn.
- Đồng bằng và lưu vực sông do vương triều hoặc liên minh thành bang quản lý.
- Biên địa có tài nguyên khan hiếm, nơi các thế lực tranh chấp.
- Hải vực và thương cảng kết nối nhiều vùng.
- Cổ chiến trường hoặc cấm địa có nguồn gốc từ các biến cố lịch sử.

#### 6.4. Thượng giới
`PROPOSED` Thượng giới có mật độ linh khí và độ hoàn chỉnh pháp tắc cao hơn, nhưng không phải thiên đường.

Các đặc điểm cần có:
- Tài nguyên phong phú hơn nhưng cạnh tranh và rào cản cũng cao hơn.
- Thế lực cổ tộc, thánh địa và liên minh có lịch sử lâu dài.
- Một số tri thức về kỷ nguyên cũ được bảo tồn, nhưng có thể bị kiểm soát.
- Những vùng bị ảnh hưởng bởi đại kiếp có thể nguy hiểm hơn hạ giới.
- Tu sĩ phi thăng phải thích nghi với môi trường, quy tắc và trật tự quyền lực mới.

#### 6.5. Cấm vực cổ xưa
Cấm vực không chỉ là nơi có quái vật mạnh hoặc bảo vật quý. Mỗi cấm vực cần có:
- Nguồn gốc lịch sử.
- Quy luật dị thường.
- Lý do người đời không thể tùy tiện khai phá.
- Tài nguyên hoặc thông tin có giá trị.
- Hệ quả nếu khai mở sai cách.

Một cấm vực liên quan đến thời gian có thể khiến người vào đó mất ký ức, già đi, lặp lại một đoạn hành trình hoặc gặp dấu vết của những lựa chọn chưa xảy ra. Tuy nhiên, mỗi hiện tượng phải có quy tắc cụ thể và giới hạn rõ ràng. *(Liên quan: `WQ-07`)*

### 7. Bản đồ logic và quản lý khoảng cách
Chưa tạo bản đồ tọa độ canon trong phiên bản này. Khi xây dựng bản đồ, cần có tối thiểu các lớp:
1. **Địa hình:** Núi, sông, biển, đồng bằng, sa mạc, rừng, đảo.
2. **Hành chính:** Quốc gia, thành bang, lãnh địa, vùng tự trị.
3. **Tu hành:** Tông môn, gia tộc, phường thị, linh mạch, cấm địa.
4. **Giao thông:** Đường bộ, đường thủy, tuyến phi hành, truyền tống trận.
5. **Lịch sử:** Di tích, cổ chiến trường, vùng bị xóa khỏi bản đồ.
6. **Pháp tắc:** Vùng thời gian dị thường, không gian bất ổn, cấm chế.

Mỗi địa điểm trọng yếu cần một hồ sơ:

```yaml
location_id: LOC-XXX
name:
aliases: []
world_layer:
region:
relative_position:
terrain:
climate:
population:
main_settlements: []
controlling_factions: []
economic_base: []
cultivation_resources: []
transport_routes: []
travel_time_from:
  - destination:
      method:
      duration:
risks:
historical_events: []
time_anomalies: []
first_appearance:
canon_status: PROPOSED
open_questions: []
```

Không dùng khoảng cách "rất xa", "không lâu sau" hoặc "vài ngày đường" nếu nó ảnh hưởng trực tiếp đến timeline, cứu viện, truy đuổi hay hậu cần. *(Liên quan: `WQ-07`)*

---

## PHẦN IV — XÃ HỘI, KINH TẾ VÀ THẾ LỰC (KẾ THỪA v1.0 & v1.1)

### 8. Các tầng xã hội
`PROPOSED` Xã hội tu hành có ít nhất bốn nhóm, nhưng ranh giới không tuyệt đối:
1. **Phàm nhân:** Nông dân, ngư dân, thợ thủ công, thương nhân, quan lại và người lao động. Họ tạo ra lương thực, hàng hóa và nền tảng kinh tế.
2. **Tu sĩ tự do:** Tán tu, người hành nghề, hộ vệ, thầy thuốc, luyện khí sư, luyện đan sư và người buôn bán tài nguyên.
3. **Tổ chức tu hành:** Tông môn, gia tộc, học cung, quân đoàn và các hội nghề nghiệp.
4. **Thế lực siêu khu vực:** Vương triều lớn, liên minh, thánh địa, cổ tộc và tổ chức kiểm soát thông đạo hoặc tài nguyên chiến lược.

Không mặc định phàm nhân hoàn toàn bất lực. Họ có thể có quyền lực kinh tế, tri thức địa phương, mạng lưới thương mại hoặc số lượng đủ lớn để ảnh hưởng đến thế cục. Nhưng không được làm như thể một đội dân thường có thể tùy tiện đánh bại tu sĩ vượt xa họ.

### 9. Kinh tế và tài nguyên

#### 9.1. Nguyên tắc kinh tế
- Linh thạch là phương tiện trao đổi quan trọng nhưng không nhất thiết là đồng tiền duy nhất.
- Giá trị tài nguyên phụ thuộc độ khan hiếm, khả năng sử dụng, rủi ro khai thác, vận chuyển và quyền kiểm soát.
- Tông môn cần nguồn thu, nhân lực, hậu cần và mạng lưới trao đổi; không thể chỉ tồn tại nhờ "linh khí trời đất".
- Chiến tranh tiêu hao tài nguyên, làm gián đoạn thương mại và ảnh hưởng phàm nhân.
- Một tài nguyên quý phải có lý do khan hiếm và cơ chế khai thác cụ thể.

#### 9.2. Nhóm tài nguyên
| Nhóm | Ví dụ định hướng | Công dụng |
| :--- | :--- | :--- |
| Năng lượng | Linh thạch, linh mạch, tinh thạch dị năng | Tu luyện, trận pháp, vận hành pháp khí |
| Sinh trưởng | Linh dược, linh chủng, linh mộc | Luyện đan, chữa trị, vật liệu |
| Vật liệu | Khoáng thạch, linh kim, yêu thú tài liệu | Luyện khí, xây dựng, chế tạo |
| Tri thức | Công pháp, bí thuật, bản đồ, cổ văn | Tu luyện, nghiên cứu, định vị |
| Quyền tiếp cận | Suất vào bí cảnh, quyền khai mỏ, thông hành lệnh | Lợi thế chính trị và kinh tế |
| Di vật cổ | Pháp bảo, tàn quyển, vật phẩm kỷ nguyên cũ | Manh mối lịch sử, năng lực đặc thù |

#### 9.3. Kinh tế vùng duyên hải
Để giữ xuất phát điểm chân thực:
- Cá, muối, dầu, gỗ, dây thừng, vải buồm, nước ngọt và vật liệu sửa thuyền phải có giá trị thực tế.
- Thương nhân và chủ thuyền có thể tạo ảnh hưởng lớn tại vùng không có tông môn mạnh.
- Thời tiết và mùa vụ ảnh hưởng nguồn cung, giá cả và nợ nần.
- Linh vật biển hiếm có thể tạo xung đột giữa ngư dân, thương hội và tu sĩ, nhưng không nên khiến mọi hoạt động đánh cá đều xoay quanh bảo vật.

### 10. Các loại thế lực

#### 10.1. Tông môn
- Lợi ích: Thu nhận đệ tử, kiểm soát linh mạch, bảo vệ địa bàn, tích lũy công pháp và duy trì truyền thừa.
- Điểm yếu: Tranh quyền nội bộ, phụ thuộc tài nguyên, nghĩa vụ với đệ tử và địa bàn.
- Mâu thuẫn: Bảo vệ truyền thống hay cải cách; ưu tiên thiên tài hay ổn định; đóng cửa hay mở rộng.

#### 10.2. Gia tộc tu hành
- Lợi ích: Duy trì huyết mạch, tài sản, hôn ước và quyền kiểm soát lãnh địa.
- Điểm yếu: Cạnh tranh người thừa kế, giới hạn nhân tài, nợ ân tình và xung đột thế hệ.
- Mâu thuẫn: Lợi ích gia tộc đối lập với lựa chọn cá nhân.

#### 10.3. Vương triều / liên minh thế tục
- Lợi ích: Đất đai, thuế, nhân lực, an ninh, thương mại và tính chính danh.
- Điểm yếu: Phụ thuộc tu sĩ, quan liêu, biên giới và khủng hoảng kế vị.
- Mâu thuẫn: Quyền lực thế tục và quyền lực tu hành không luôn thống nhất.

#### 10.4. Thương hội
- Lợi ích: Tuyến vận tải, độc quyền hàng hóa, thông tin và tín dụng.
- Điểm yếu: Phụ thuộc an ninh, biến động giá và quan hệ với các thế lực lớn.
- Mâu thuẫn: Trung lập để tồn tại hay chọn phe để giành độc quyền.

#### 10.5. Tán tu và liên minh tự do
- Lợi ích: Tự chủ, tiếp cận tài nguyên và tránh sự kiểm soát của tổ chức lớn.
- Điểm yếu: Thiếu hậu cần, truyền thừa, bảo hộ và cơ chế giải quyết tranh chấp.
- Mâu thuẫn: Tự do cá nhân đối lập với nhu cầu liên kết để sinh tồn.

#### 10.6. Thế lực bị gọi là ma đạo
Không định nghĩa "ma đạo" chỉ bằng việc tàn ác. Danh xưng có thể là cách gọi của đối thủ hoặc một phân loại công pháp. Một thế lực bị gọi là ma đạo vẫn phải có cấu trúc, lợi ích, quy tắc nội bộ và những người có lý tưởng khác nhau.

#### 10.7. Cổ tộc / thánh địa
- Lợi ích: Kiểm soát di sản, tri thức, thông đạo và quyền diễn giải lịch sử.
- Điểm yếu: Bảo thủ, bí mật nội bộ, món nợ từ quá khứ và nguy cơ phụ thuộc vào cơ chế cổ.
- Mâu thuẫn: Bảo tồn trật tự hiện tại hay thừa nhận nó được xây dựng trên một sự thật sai lệch. *(Liên quan: `WQ-15`)*

### 11. Các phe liên quan đến đại kiếp
`PROPOSED` Không đặt tên chính thức cho phe phái cho đến khi xây dựng nhân vật và địa lý. Tạm chia theo lập trường:

| Lập trường | Mục tiêu | Rủi ro đạo đức |
| :--- | :--- | :--- |
| Duy trì phong ấn | Giữ thế giới hiện tại tồn tại càng lâu càng tốt | Hy sinh vùng biên hoặc thế hệ tương lai |
| Phá phong ấn | Chấm dứt cơ chế trì hoãn, chấp nhận biến động | Có thể gây đại họa tức thời |
| Khai thác đại kiếp | Dùng dị biến để tăng sức mạnh hoặc thay đổi trật tự | Biến sinh linh thành vật thí nghiệm |
| Khôi phục kỷ nguyên cũ | Phục hồi nền văn minh và tri thức đã mất | Có thể phủ nhận quyền tồn tại của thế giới hiện tại |
| Tìm con đường thứ ba | Giải quyết nguyên nhân gốc mà không lặp lại thảm họa | Đòi hỏi hy sinh, liên minh và tri thức chưa có |

Không phe nào được toàn tri. Mỗi phe chỉ biết một phần sự thật và có thể hành động sai dù mục tiêu ban đầu có lý. *(Liên quan: `WQ-15`)*

---

## PHẦN V — VĂN HÓA, TRI THỨC VÀ ĐỜI SỐNG (KẾ THỪA v1.0 & v1.1)

### 12. Tín ngưỡng và cách hiểu về thiên địa
- Phàm nhân có thể thờ thần biển, thần núi, tổ tiên hoặc các vị hộ mệnh địa phương.
- Tu sĩ có thể xem những tín ngưỡng ấy là tập tục dân gian, nhưng không mặc định tất cả đều vô căn cứ.
- Các tông môn có học thuyết riêng về thiên đạo, sinh tử, luân hồi và phi thăng.
- Lịch sử chính thống có thể khác nhau giữa các khu vực.
- Một số nghi lễ dân gian có thể lưu giữ mảnh ký ức của kỷ nguyên cũ mà người thực hành không hiểu nguồn gốc.

Không xác nhận có một vị thần tối cao đứng sau mọi hiện tượng. "Thiên đạo" có thể được hiểu là quy luật, ý chí, cơ chế hoặc tên gọi mà các trường phái dùng để diễn giải trật tự. *(Liên quan: `WQ-05`)*

### 13. Ngôn ngữ và tri thức
- Ngôn ngữ thông dụng có thể khác nhau giữa các đại lục; thương nhân, tông môn và quan lại duy trì ngôn ngữ giao dịch chung.
- Cổ văn không phải chỉ là chữ viết khó đọc; nó có thể mã hóa khái niệm, đơn vị đo hoặc cấu trúc pháp trận đã thất truyền.
- Tri thức không đồng đều. Một thợ đóng thuyền có thể hiểu thủy văn tốt hơn tu sĩ, trong khi tu sĩ hiểu linh mạch mà người phàm không nhận biết.
- Không để nhân vật có thể đọc mọi cổ văn chỉ vì là nhân vật chính.
- Bản dịch cổ văn phải có độ bất định và có thể bị diễn giải sai.

### 14. Đời sống và hậu cần
Các chi tiết sau phải được duy trì nhất quán:
- Lương thực, nước uống, nơi trú ẩn và phương tiện di chuyển.
- Chi phí chữa trị, phục hồi linh lực và sửa chữa pháp khí.
- Nơi ở, thân phận, giấy thông hành hoặc quy tắc vào thành.
- Thời gian nghỉ ngơi, thương thế và giới hạn thể lực.
- Tác động của chiến tranh, thiên tai, phong tỏa và đứt gãy thương mại đến dân thường.

Không cần mô tả mọi bữa ăn hay mọi khoản chi, nhưng các chi tiết hậu cần phải xuất hiện khi chúng ảnh hưởng đến quyết định hoặc kết quả.

---

## PHẦN VI — QUY TẮC LIÊN TỤC, HỆ THỐNG TU LUYỆN & CHIẾN LỰC (KẾ THỪA v1.0 & v1.1)

### 15. Những bất biến của thế giới
Các quy tắc này là nền tảng liên tục của tài liệu; trạng thái từng bất biến được xác định bằng các nhãn quản trị (`PROPOSED`, `SUPPORTED BY APPROVED RULES` kèm mã tham chiếu đã đối chiếu đúng phạm vi, hoặc `OPEN QUESTION`). Không mặc nhiên coi toàn bộ là đã duyệt chỉ vì nằm trong mục này:

1. **Khoảng cách có ý nghĩa:** Di chuyển cần thời gian, phương tiện và điều kiện. *(Trạng thái: `PROPOSED`)*
2. **Tài nguyên có nguồn gốc:** Vật phẩm không tự xuất hiện; khai thác và vận chuyển có chi phí. *(Trạng thái: `PROPOSED` — liên hệ cơ chế tài nguyên tại `15A.3`; không dùng quy tắc ngoại lực về nguồn năng lượng duy trì làm căn cứ chứng minh toàn bộ nguyên tắc này)*
3. **Thông tin có giới hạn:** Nhân vật chỉ biết điều họ được tiếp cận hoặc có thể suy luận. *(Trạng thái: `PROPOSED` — tham chiếu `CULT-06.2` trong phạm vi hẹp rằng quan sát và tính toán không bảo đảm dự đoán đúng; không dùng làm căn cứ xác lập toàn bộ nguyên tắc thông tin có giới hạn)*
4. **Quyền lực có cấu trúc:** Tông môn và thế lực cần hậu cần, lợi ích và giới hạn. *(Trạng thái: `PROPOSED`)*
5. **Thời gian có hậu quả:** Chênh lệch thời gian không xóa mọi hao tổn. *(Trạng thái: `PROPOSED` — liên kết cơ chế hệ quả/nhân quả)*
6. **Lịch sử có nhiều lớp:** Một nguồn tư liệu không đủ xác nhận toàn bộ sự thật. *(Trạng thái: `PROPOSED`)*
7. **Đại kiếp có cơ chế:** Dị tượng phải xuất phát từ quy luật hoặc nguyên nhân xác định. *(Trạng thái: `PROPOSED`)*
8. **Cấm vực có điều kiện:** Nguy hiểm không được tùy tiện tăng giảm để phục vụ tình tiết. *(Trạng thái: `PROPOSED`)*
9. **Pháp bảo có giới hạn:** Không năng lực nào được giải quyết mọi loại vấn đề. *(Trạng thái: `SUPPORTED BY APPROVED RULES` — tham chiếu `CULT-05.1–CULT-05.7` và Mục `15A.9`)*
10. **Nhân quả không phải công cụ tùy tiện:** Mỗi lần can thiệp phải có cơ chế và hệ quả tương ứng. *(Trạng thái: `PROPOSED` — liên kết quy tắc hậu quả/trách nhiệm của Lâm Tĩnh)*

### 15A. Hệ thống tu luyện, chiến lực và ứng dụng vào nhân vật chính

`APPROVED – KIẾN TRÚC` xác nhận khung nguyên lý và quy tắc thiết kế đã được duyệt; không đồng nghĩa với việc các thông số định lượng, cơ chế chi tiết, phẩm cấp, thời lượng hoặc công năng chưa được giải quyết trong các WQ đã trở thành canon. Cụ thể:

- `WQ-08` vẫn mở về tuổi thọ, điều kiện đột phá, tiểu cảnh giới và thời gian tu luyện.
- `WQ-09` vẫn mở về cơ chế và chi phí trì hoãn Tâm Ma.
- `WQ-10` vẫn mở về cơ chế vận hành từng cảnh giới.
- `WQ-11` vẫn mở về phẩm cấp pháp bảo.
- `WQ-13` vẫn mở về nguồn gốc, ý chí và công năng Phá Thiên Chung.
- `WQ-14` và `WQ-15` vẫn chưa được giải quyết chi tiết.
- `WQ-12` là giả thuyết thiết kế tách biệt (`OPEN QUESTION / DESIGN HYPOTHESIS`), không dùng làm thông số đã duyệt.

#### 15A.1. Nguyên lý tu luyện
`APPROVED – KIẾN TRÚC`

Tu luyện là quá trình biến đổi bản chất sinh mệnh, mở rộng nhận thức về Đạo và nâng cao khả năng chịu tải, vận dụng các quy luật của thiên địa.

Linh khí là nguồn nhiên liệu và vật chất hỗ trợ cho quá trình biến đổi đó, không phải bản chất của tu luyện.

Nguyên lý này tạo ra năm hệ quả bắt buộc:
1. **Linh khí không đồng nghĩa với cảnh giới:** Tích lũy linh khí đơn thuần không bảo đảm đột phá.
2. **Cảnh giới không đồng nghĩa với chiến lực:** Nền tảng, nhận thức, kinh nghiệm và khả năng vận dụng quy luật ảnh hưởng trực tiếp đến năng lực thực tế.
3. **Đột phá phải có biến đổi thực chất:** Phải có sự chuyển hóa tương ứng trong sinh mệnh, thần thức hoặc nhận thức về Đạo và pháp tắc.
4. **Năng lực có giới hạn chịu tải:** Vận dụng vượt quá khả năng chịu tải có thể gây phản phệ và tổn thương.
5. **Phá Thiên Chung không thay thế tu luyện:** Chuông có thể tạo cơ hội hoặc hỗ trợ tiếp cận quy luật, nhưng Lâm Tĩnh vẫn phải có năng lực tự thân để chịu đựng và khai thác cơ hội đó.

#### 15A.2. Hệ thống cảnh giới
`APPROVED – KIẾN TRÚC`

Hệ thống tu luyện hiện tại gồm Hạ Giới và Tiên Giới. Mỗi giới có hệ thống đại cảnh giới riêng.

##### 15A.2.1. Hạ Giới — 9 đại cảnh giới
| Thứ tự | Đại cảnh giới | Trọng tâm biến đổi |
| :--- | :--- | :--- |
| 1 | Luyện Thể | Cường hóa thân thể, khí huyết và khả năng chịu đựng |
| 2 | Luyện Khí | Hấp thu, luyện hóa và vận dụng linh khí |
| 3 | Trúc Cơ | Xây dựng nền tảng tu luyện ổn định |
| 4 | Kim Đan | Kết tinh và ổn định cấu trúc tu luyện |
| 5 | Nguyên Anh | Sinh mệnh và thần thức chuyển sang phương thức tồn tại mới |
| 6 | Hóa Thần | Thần thức biến đổi sâu sắc, bắt đầu nhận thức pháp tắc thế giới |
| 7 | Luyện Hư | Bắt đầu tiếp xúc và vận dụng hư không, quy luật |
| 8 | Hợp Thể | Hợp nhất thân thể, thần thức và con đường tu luyện |
| 9 | Đại Thừa | Đạt trạng thái sinh mệnh cao nhất có thể trong Hạ Giới |

##### 15A.2.2. Độ Kiếp — Ngưỡng chuyển tiếp
`APPROVED – KIẾN TRÚC`

Độ Kiếp không phải đại cảnh giới thứ mười. Đây là giai đoạn chuyển tiếp và khảo nghiệm giữa Đại Thừa và Tiên Giới, nhằm kiểm tra:
1. Khả năng chịu tải của thân thể, thần thức và sinh mệnh trước pháp tắc cấp cao hơn.
2. Đạo tâm, nhân quả và những lựa chọn đã tạo nên con đường tu luyện.
3. Mức độ tương thích với cấu trúc pháp tắc của Tiên Giới.

Độ Kiếp không bảo đảm phi thăng thành công. Các kết quả thất bại có thể gồm tử vong, đạo cơ tan vỡ, sinh mệnh phân rã hoặc chuyển hóa không hoàn chỉnh để lại tổn thương lâu dài.

##### 15A.2.3. Tiên Giới — 8 đại cảnh giới
| Thứ tự | Đại cảnh giới |
| :--- | :--- |
| 1 | Địa Tiên |
| 2 | Thiên Tiên |
| 3 | Chân Tiên |
| 4 | Huyền Tiên |
| 5 | Kim Tiên |
| 6 | Thái Ất |
| 7 | Đại La |
| 8 | Đạo Tổ |

Đạo Tổ là cảnh giới cao nhất trong hệ thống tu luyện Tiên Giới hiện tại. Không mặc nhiên xem Đạo Tổ là toàn tri, toàn năng hoặc tuyệt đối làm chủ mọi quy luật thời gian và nhân quả.

##### 15A.2.4. Trạng thái vượt khỏi thiên địa
`APPROVED – KIẾN TRÚC` về định hướng kết thúc; cơ chế thực hiện chưa khóa.

Vượt khỏi thiên địa là trạng thái tồn tại nằm ngoài hệ thống cảnh giới thông thường. Không được thiết kế thành đại cảnh giới thứ chín của Tiên Giới hoặc một cấp bậc tu luyện thông thường cao hơn Đạo Tổ.

##### 15A.2.5. Nguyên tắc phân chia tiểu cảnh giới
Không bắt buộc mọi đại cảnh giới phải có số lượng tiểu cảnh giới giống nhau. Có thể sử dụng các mốc sơ kỳ, trung kỳ, hậu kỳ và đỉnh phong khi phù hợp, nhưng không biến cách phân chia này thành công thức bắt buộc.

- Tuổi thọ, điều kiện đột phá, thời gian tu luyện và tiểu cảnh giới chi tiết thuộc `WQ-08`.
- Cơ chế biến đổi sinh mệnh, thần thức, năng lực và giới hạn của từng đại cảnh giới thuộc `WQ-10`.

#### 15A.3. Cơ chế linh khí
`APPROVED – KIẾN TRÚC`

##### 15A.3.1. Bản chất linh khí
Linh khí là nguồn năng lượng nền tảng tồn tại trong thiên địa. Sinh linh có thể hấp thu, luyện hóa và chuyển đổi linh khí để hỗ trợ tu luyện, chiến đấu, vận hành pháp bảo và trận pháp. Linh khí có thể khác nhau về:
- Mật độ.
- Độ tinh thuần.
- Thuộc tính.
- Độ ổn định.
- Khả năng tái tạo và bổ sung.

Linh khí có mật độ cao không nhất thiết là môi trường tu luyện tốt nhất. Linh khí không tương thích hoặc bất ổn có thể gây tổn thương cho chủ thể. Linh khí Tiên Giới không phải một nguồn năng lượng hoàn toàn tách biệt với linh khí Hạ Giới. Đây là trạng thái có mật độ, độ tinh thuần và cấu trúc pháp tắc cao hơn của cùng nền tảng năng lượng.

##### 15A.3.2. Chu trình sáu pha
Chu trình vận hành linh khí gồm sáu pha:
1. **Hấp thu:** Tiếp nhận linh khí từ môi trường hoặc nguồn năng lượng bên ngoài.
2. **Luyện hóa:** Chuyển linh khí thành dạng phù hợp với cấu trúc sinh mệnh hoặc phương thức vận dụng.
3. **Tích trữ:** Lưu giữ năng lượng đã luyện hóa trong cơ thể, đan điền hoặc phương tiện chứa phù hợp.
4. **Vận dụng:** Chuyển năng lượng thành công năng tu luyện, chiến đấu, phòng ngự hoặc vận hành ngoại lực.
5. **Tiêu hao:** Năng lượng bị tiêu thụ, thất thoát hoặc chuyển sang trạng thái khác trong quá trình vận hành.
6. **Hoàn trả:** Một phần năng lượng có thể trở lại môi trường hoặc chuyển sang trạng thái có khả năng tái sử dụng.

Đây là mô hình mô tả dòng năng lượng, không phải chuỗi bắt buộc phải diễn ra đầy đủ trong mọi hành động. Không phải toàn bộ năng lượng tiêu hao đều được hoàn trả nguyên vẹn hoặc ngay lập tức.

##### 15A.3.3. Ba đại lượng tài nguyên
Phải phân biệt:
- **Linh khí tồn lượng:** Lượng linh khí hiện có thể khai thác trong một khu vực.
- **Linh khí lưu chuyển:** Lượng linh khí đang vận động và trao đổi trong môi trường.
- **Linh khí tái tạo:** Lượng linh khí môi trường có thể bổ sung trong một khoảng thời gian.

Mô hình cân bằng tài nguyên mang tính khái niệm:

$$\Delta E = R + I - A - L$$

Trong đó:
- $E$: Lượng linh khí có thể khai thác ($\Delta E$ là biến động tồn lượng linh khí có thể khai thác trong khoảng thời gian xét).
- $R$: Lượng linh khí được tái tạo.
- $I$: Lượng linh khí bổ sung từ bên ngoài.
- $A$: Lượng linh khí bị khai thác.
- $L$: Lượng linh khí thất thoát hoặc chuyển sang trạng thái khó tái sử dụng.

**Quy ước thời gian và đơn vị:** Các đại lượng $R, I, A, L$ đều được tính trong cùng một khoảng thời gian xác định và cùng đơn vị quy đổi; $\Delta E$ phản ánh biến động tồn lượng khả dụng trong khoảng thời gian đó. Đây là công cụ quản lý và đánh giá tài nguyên trong thiết kế thế giới, không phải phương trình tức thời hay định luật vật lý tuyệt đối.

Hệ quả:
- Khai thác liên tục vượt quá khả năng tái tạo có thể khiến linh mạch suy kiệt.
- Đại chiến có thể làm linh khí khu vực hỗn loạn và khiến nơi đó không còn thích hợp cho tu luyện trong một thời gian.
- Khu vực suy kiệt không nhất thiết vĩnh viễn mất linh khí.
- Linh mạch ổn định là tài sản chiến lược và có thể trở thành nguyên nhân tranh chấp giữa các thế lực.

##### 15A.3.4. Ba trạng thái mất cân bằng
1. **Cạn kiệt linh khí:** Lượng linh khí có thể khai thác giảm mạnh do khai thác vượt quá khả năng tái tạo hoặc nguồn cung bị gián đoạn.
2. **Linh khí hỗn loạn:** Dòng linh khí mất ổn định, xung đột thuộc tính hoặc bị nhiễu loạn bởi dị biến, trận pháp và chiến đấu.
3. **Vượt ngưỡng chịu tải:** Chủ thể hấp thu hoặc vận dụng năng lượng vượt quá khả năng chịu tải của sinh mệnh, gây phản phệ.

Trạng thái thứ ba là vấn đề của chủ thể tu luyện, không đồng nhất với cạn kiệt tài nguyên môi trường.

##### 15A.3.5. Quan hệ với chu kỳ đại kiếp
Chu kỳ linh khí có thể trải qua bốn giai đoạn khái niệm:
- Hưng thịnh.
- Suy giảm.
- Hắc Triều.
- Tái lập.

Suy giảm linh khí không đồng nghĩa với Tuế Nguyệt Hắc Triều. Suy giảm có thể diễn ra dần dần, trong khi Hắc Triều là một biến cố có quy mô và cơ chế khác. Cơ chế tái lập linh khí sau Hắc Triều vẫn là `WQ-01`.

##### 15A.3.6. Giới hạn của Phá Thiên Chung
- Không gian nội tại có thể bảo tồn năng lượng và tài nguyên đã đưa vào, nhưng không tạo ra linh khí vô hạn.
- Cách ly thời gian có thể bảo vệ một số tài nguyên trước biến động bên ngoài, nhưng không miễn trừ mọi loại tổn hại.
- Vận dụng thời gian và không gian cần năng lượng, đồng thời tạo áp lực lên chủ thể.
- Vận dụng quy luật phụ thuộc cảnh giới, nhận thức và điều kiện thực tế.
- Phá Thiên Chung không thay thế khả năng chịu tải của Lâm Tĩnh.

#### 15A.4. Tâm Ma Tuế Nguyệt
`APPROVED – KIẾN TRÚC`

##### 15A.4.1. Định nghĩa
Tâm Ma Tuế Nguyệt là khảo nghiệm nội sinh xuất hiện tại một số ngưỡng chuyển hóa lớn của sinh mệnh. Khi sinh mệnh và thần thức tái cấu trúc để chịu tải pháp tắc cấp cao hơn, những dấu ấn ký ức, chấp niệm và dư âm nhân quả có ảnh hưởng thực chất đến con đường tu luyện có thể cộng hưởng với quy luật thời gian, hình thành khảo nghiệm.

Đây không phải:
- Hình phạt do một Thiên Đạo có ý chí áp đặt.
- Thiên Kiếp vật lý.
- Một bài kiểm tra đạo đức với đáp án đúng duy nhất.
- Tâm ma thông thường do tẩu hỏa nhập ma, bất ổn tinh thần hoặc ngoại lực quấy nhiễu.

Cơ chế nền tảng mang tính phổ quát đối với người tu luyện, nhưng biểu hiện và cường độ không giống nhau ở mọi người.

##### 15A.4.2. Ba thành phần cộng hưởng
1. **Ký ức:** Sự kiện thực tế đã xảy ra trong đời sống của chủ thể.
2. **Chấp niệm:** Sự ràng buộc, mâu thuẫn hoặc điều chưa được giải quyết có ảnh hưởng đến con đường của chủ thể.
3. **Dư âm nhân quả:** Những hệ quả từ lựa chọn trước đây vẫn đang tác động đến sinh mệnh hoặc con đường tu luyện.

Không phải mọi ký ức, chấp niệm hay nhân quả đều trở thành nội dung khảo nghiệm. Không phải mọi dư âm nhân quả đều là món nợ bắt buộc phải trả.

##### 15A.4.3. Chuỗi hình thành khảo nghiệm
Cơ chế gồm bốn bước:
1. **Ngưỡng chuyển hóa bắt đầu:** Sinh mệnh và thần thức tiến hành biến đổi ở cấp độ lớn.
2. **Cộng hưởng với thời gian:** Những dấu ấn liên quan trong chủ thể phản ứng với quy luật thời gian.
3. **Nội dung khảo nghiệm xuất hiện:** Ký ức, chấp niệm hoặc dư âm nhân quả được phơi lộ dưới hình thức khảo nghiệm.
4. **Kết quả:** Chủ thể có thể hoàn thành, đình trệ, chịu tổn thương hoặc thất bại trong quá trình chuyển hóa.

##### 15A.4.4. Các mốc khảo nghiệm chính
| Mốc | Trọng tâm khảo nghiệm |
| :--- | :--- |
| Kim Đan | Lựa chọn và cái giá đã trả |
| Nguyên Anh | Mất mát và bản sắc |
| Hóa Thần | Sự thật, nhân quả và giới hạn nhận thức |
| Độ Kiếp | Khảo nghiệm tổng hợp sinh mệnh, Đạo tâm và khả năng tương thích với pháp tắc cấp cao |

Không mặc định mỗi lần đột phá đều phát sinh một Tâm Ma Tuế Nguyệt mới. **Luyện Hư** và **Hợp Thể** không phát sinh một kỳ Tâm Ma Tuế Nguyệt độc lập mới. Hai cảnh giới này vẫn có thể xuất hiện:
- Bất ổn thần thức.
- Xung đột nội tại.
- Phản chấn khi tiếp xúc hư không và pháp tắc.
- Rủi ro trong quá trình hợp nhất thân thể, thần thức và con đường tu luyện.

##### 15A.4.5. Giới hạn của khảo nghiệm
- Ký ức thực có thể được tái hiện nhưng không thể bị sửa đổi.
- Những khả năng khác với sự kiện đã xảy ra chỉ là mô phỏng hoặc giả định, không phải dòng thời gian song song thực sự.
- Khảo nghiệm không cho phép viết lại lịch sử hoặc xóa bỏ nhân quả đã xác lập.
- Không có một đáp án đạo đức duy nhất cho mọi khảo nghiệm.
- Trọng tâm là khả năng nhận thức bản thân, đối diện lựa chọn và chịu trách nhiệm với hậu quả.

##### 15A.4.6. Mức độ tổn hại
Có thể chia thành ba mức khái niệm:
1. **Nhẹ hoặc một phần:** Dao động Đạo tâm, nhiễu loạn thần thức, giảm hiệu suất vận dụng năng lượng hoặc đình trệ đột phá.
2. **Nghiêm trọng:** Tổn thương sâu Đạo tâm, hao tổn tuổi thọ, tổn hại nền tảng hoặc mắc kẹt trong chấp niệm.
3. **Cực đoan:** Sinh mệnh sụp đổ, thần hồn tan rã, đạo cơ bị phá hủy hoặc chuyển hóa sai lệch để lại thương tổn lâu dài.

Mức độ biểu hiện không tỷ lệ tuyến tính với độ kịch tính bề ngoài của khảo nghiệm. Thất bại trong khảo nghiệm có thể khiến quá trình chuyển hóa đình trệ. Cưỡng ép đột phá trong tình trạng chưa giải quyết được vấn đề có thể tạo ra cảnh giới bất ổn hoặc tổn thương sâu hơn.

##### 15A.4.7. Hỗ trợ bên ngoài
Ngoại lực có thể:
- Ổn định thân thể.
- Hỗ trợ linh khí.
- Bảo vệ môi trường.
- Giảm một số nhiễu loạn bên ngoài.

Ngoại lực không thể thay chủ thể giải quyết mâu thuẫn nội tại hoặc đưa ra lựa chọn thay họ. Người khác có thể giúp chủ thể nhận ra vấn đề nhưng không thể hoàn thành quá trình tự đối diện thay chủ thể. Cưỡng ép phá khảo nghiệm có thể làm tổn thương thần thức hoặc tăng phản chấn.

##### 15A.4.8. Giới hạn của Phá Thiên Chung
Phá Thiên Chung có thể hỗ trợ nhận biết hoặc chống chịu một số biến động thời gian và pháp tắc. Nhưng nó không thể:
- Xóa ký ức hoặc mất mát.
- Xóa bỏ trách nhiệm với lựa chọn.
- Bảo đảm miễn nhiễm Tâm Ma Tuế Nguyệt.
- Luôn phân biệt hoàn hảo ký ức thực và mô phỏng.
- Hoàn thành khảo nghiệm thay Lâm Tĩnh.

##### 15A.4.9. Trì hoãn khảo nghiệm
Có thể trì hoãn hoặc tạm thời làm chậm một số quá trình chuyển hóa, nhưng khả năng này có giới hạn và kéo theo chi phí, rủi ro tích lũy. Cơ chế và mức chi phí cụ thể thuộc `WQ-09`.

#### 15A.5. Cảnh giới, nền tảng, căn cơ và độ ổn định
`APPROVED – KIẾN TRÚC`

- **Cảnh giới:** Tầng biến đổi bản chất sinh mệnh, thần thức và khả năng tiếp nhận, vận dụng quy luật.
- **Nền tảng tu luyện:** Tổng thể cấu trúc và mức độ hoàn thiện, đồng bộ của các thành phần tu hành tại cảnh giới hiện tại.
- **Căn cơ:** Chất lượng gốc rễ, độ bền vững và dư địa phát triển lâu dài của cấu trúc tu hành (tách bạch khỏi **Linh căn**, vốn là khả năng tương thích, hấp thu và luyện hóa linh khí ảnh hưởng hiệu suất và tốc độ tu luyện).
- **Độ ổn định:** Trạng thái cân bằng và khả năng chịu tải thực tế tại một thời điểm (biến thiên theo thương tổn, đột phá, phản phệ, tâm ma, cưỡng ép vận dụng).

Quy tắc nền `CULT-01.1 – CULT-01.3`:
- `CULT-01.1`: Cảnh giới không bảo đảm nền tảng tương xứng.
- `CULT-01.2`: Căn cơ không đồng nhất với hiệu suất tu luyện.
- `CULT-01.3`: Độ ổn định có thể thay đổi theo thời gian; đột phá sớm tạo nguy cơ giới hạn tiềm năng, tăng chi phí/thời gian bù đắp và có thể đòi hỏi tu sửa nền tảng tùy mức độ tổn hại, nhưng không mặc nhiên khóa trần cảnh giới vĩnh viễn.

#### 15A.6. Mô hình chiến lực
`APPROVED – KIẾN TRÚC`

Chiến lực không phải chỉ số tĩnh cố định trên người tu sĩ, mà là năng lực thực tế để đạt được một mục tiêu chiến đấu cụ thể trong một hoàn cảnh cụ thể.

Sáu mục tiêu / kết quả chiến đấu chuẩn:
1. **Đánh bại:** Khống chế, áp chế hoặc khiến đối phương mất khả năng chiến đấu hiệu quả.
2. **Tiêu diệt:** Triệt hạ hoàn toàn mục tiêu hoặc sinh mệnh đối địch.
3. **Cầm chân:** Giữ chân, kiềm chế hoặc trì hoãn đối phương trong phạm vi và thời gian cần thiết.
4. **Phá vây:** Xuyên thủng vòng vây, phong tỏa hoặc tuyến phòng thủ để thoát ra.
5. **Đoạt mục tiêu:** Chiếm giữ, bảo vệ hoặc đạt được mục tiêu/vật phẩm/vị trí cụ thể.
6. **Sinh tồn:** Duy trì sự sống và trạng thái đủ vận hành qua giao chiến hoặc hiểm cảnh.

Bốn lớp vận hành (không có trọng số cố định):
1. **Năng lực nền và giới hạn chịu tải:** Năng lực nền là những gì chủ thể có thể vận dụng trong điều kiện thông thường; trần chịu tải là giới hạn cao nhất mà chủ thể có thể tiếp nhận hoặc phát ra trước khi chịu tổn thương nghiêm trọng. Năng lượng tích trữ không đồng nghĩa với khả năng phát lực tức thời.
2. **Nhiên liệu và duy trì:** Lượng năng lượng tích trữ, hiệu suất chuyển hóa, mức tiêu hao và khả năng hồi phục/duy trì theo thời gian.
3. **Hiệu suất vận dụng:** Công pháp, kỹ thuật, thần thức và pháp tắc; khả năng chuyển năng lượng thành sát thương, phòng ngự, độ chính xác hoặc hiệu quả xuyên phá.
4. **Điều kiện chiến đấu:** Kinh nghiệm, thông tin, pháp bảo và trận pháp, địa hình, chuẩn bị và điều kiện giao chiến.

Nguyên lý nút thắt: Chiến lực thực tế bị giới hạn bởi nút thắt có ảnh hưởng trực tiếp đến mục tiêu chiến đấu trong tình huống cụ thể (phụ thuộc mục tiêu và phương thức chiến đấu). Không mặc định chiều yếu nhất luôn quyết định toàn bộ chiến lực. Ví dụ: pháp bảo mạnh nhưng thần thức không đủ điều khiển thì không khai thác được trọn vẹn; ngược lại, nếu một đòn quyết định đủ kết thúc trận chiến, khả năng hồi phục dài hạn có thể không phải nút thắt chính.

Quy tắc nền `CULT-02.1 – CULT-02.5`:
- `CULT-02.1`: Chiến lực là năng lực thực tế gắn với mục tiêu và hoàn cảnh cụ thể, không phải chỉ số tĩnh.
- `CULT-02.2`: Tách bạch năng lực nền, trần chịu tải và năng lượng tích trữ.
- `CULT-02.3`: Liên kết nhiên liệu, hiệu suất duy trì và hiệu suất vận dụng theo thời gian giao chiến.
- `CULT-02.4`: Điều kiện chiến đấu (thông tin, địa hình, chuẩn bị, ngoại lực) làm biến đổi tính khả thi của từng mục tiêu.
- `CULT-02.5`: Nút thắt quyết định thực lực phụ thuộc trực tiếp vào mục tiêu và phương thức chiến đấu, không phải chiều yếu nhất một cách máy móc.

#### 15A.7. Giới hạn chênh lệch cảnh giới
`APPROVED – KIẾN TRÚC`

Bốn mức chênh lệch:
1. **Chênh lệch nhỏ:** Có thể được bù đắp hoặc đảo ngược bằng nền tảng, kỹ thuật, kinh nghiệm và chuẩn bị.
2. **Chênh lệch trung bình:** Cần ưu thế chiến thuật, khắc chế, thông tin hoặc điều kiện giao chiến có lợi.
3. **Chênh lệch lớn:** Chiến thắng trực diện khó khăn, nhưng không bị cấm tuyệt đối. Có thể xuất hiện chiến thắng thực chiến hoặc sinh tử nếu có cơ chế và căn cứ thực chất.
4. **Chênh lệch mang tính tầng tồn tại:** Khác biệt về bản chất sinh mệnh và tầng pháp tắc. Kỹ thuật hoặc pháp bảo thông thường không thể tùy tiện xóa bỏ khoảng cách này.

Ba yếu tố điều chỉnh:
- Thương thế, cạn kiệt năng lượng và bất ổn làm giảm chiến lực thực tế nhưng không tự động làm giảm cảnh giới.
- Mục tiêu chiến đấu quyết định mức độ khả thi.
- Không gian, pháp tắc, địa hình và chuẩn bị có thể thay đổi điều kiện giao chiến nhưng không tự động xóa giới hạn chịu tải của chủ thể.

Không dùng số lượng đại cảnh giới chênh lệch làm thước đo duy nhất. Bản chất của ranh giới giữa hai cảnh giới cũng phải được xem xét.

Quy tắc nền `CULT-03.1 – CULT-03.5`:
- `CULT-03.1`: Đánh giá chênh lệch cảnh giới theo khung định tính, không phải công thức xác suất hoặc bảng điểm cố định.
- `CULT-03.2`: Mục tiêu chiến đấu quyết định tính khả thi; sinh tồn, cầm chân, phá vây, đoạt mục tiêu, đánh bại và tiêu diệt có mức độ khó khác nhau.
- `CULT-03.3`: Chênh lệch mang tính tầng tồn tại phản ánh khác biệt về bản chất sinh mệnh và tầng pháp tắc; kỹ thuật hoặc pháp bảo thông thường không thể tùy tiện xóa bỏ khoảng cách này.
- `CULT-03.4`: Thương thế, cạn kiệt năng lượng, phản phệ hoặc bất ổn làm giảm chiến lực thực tế nhưng không tự động làm giảm cảnh giới.
- `CULT-03.5`: Gây ảnh hưởng, cầm chân hoặc đạt mục tiêu gián tiếp không đồng nghĩa với chiến thắng trực diện hay chứng minh hai bên có chiến lực ngang nhau.

#### 15A.8. Quy tắc vượt cấp
`APPROVED – KIẾN TRÚC`

Ba cấp độ vượt cấp (mô tả kết quả chiến đấu, không phải ba cấp sức mạnh cố định):
| Cấp độ | Nội dung |
| :--- | :--- |
| Vượt cấp chiến thuật | Đạt mục tiêu như cầm chân, phá vây, sinh tồn hoặc đoạt mục tiêu mà không nhất thiết đánh bại đối thủ |
| Vượt cấp thực chiến | Đánh bại hoặc gây thương tổn nghiêm trọng cho đối thủ cảnh giới cao hơn trong giao chiến trực diện |
| Vượt cấp sinh tử | Tiêu diệt đối thủ cảnh giới cao hơn, tạo ra chiến thắng hoàn chỉnh và bước ngoặt lớn |

Hệ thống bảy quy tắc nền `CULT-04.1 – CULT-04.7` (phục vụ kiểm toán trực tiếp):
- **`CULT-04.1` (Căn cứ và cơ chế chiến thắng thực chất):** Điều kiện vượt cấp phải gắn với căn cứ và cơ chế thực chất trong giao chiến (nền tảng, kỹ thuật, pháp tắc, năng lực vận dụng, ngoại lực hoặc điều kiện chiến đấu), đồng thời phải nằm trong giới hạn chịu tải của chủ thể hoặc có cơ chế xử lý hợp lý đối với phần quá tải; không được dựa vào hào quang nhân vật chính hay hợp lý hóa cưỡng ép.
- **`CULT-04.2` (Điểm gãy thất bại cụ thể):** Vượt cấp thất bại phải có điểm gãy rõ ràng khi nền tảng/năng lượng/chịu tải chạm ngưỡng, điều kiện thất bại kích hoạt, hoặc thực lực/cơ chế không đủ vượt qua nút thắt mục tiêu.
- **`CULT-04.3` (Cái giá đáng kể theo khung thời gian):** Vượt cấp phải đi kèm cái giá đáng kể trong ít nhất một khung thời gian (tức thời/ngắn hạn, trung hạn hoặc dài hạn), có thể ảnh hưởng đến thân thể, thần thức, căn cơ, tài nguyên, quan hệ hoặc nhân quả; mức độ tổn thất không tăng tuyến tính máy móc theo số bậc cảnh giới.
- **`CULT-04.4` (Không là checklist cứng):** Các điều kiện vượt cấp không phải một danh sách kiểm tra cứng nhắc cố định mọi trận; tính khả thi phụ thuộc mục tiêu (*Đánh bại, Tiêu diệt, Cầm chân, Phá vây, Đoạt mục tiêu, Sinh tồn*) và hoàn cảnh giao chiến.
- **`CULT-04.5` (Đối thủ thích nghi và phản chế):** Đối thủ không đứng yên chịu đòn; đối thủ có khả năng nhận diện, thích nghi chiến thuật, điều chỉnh nhịp giao chiến hoặc phản chế khi tình huống diễn biến.
- **`CULT-04.6` (Thắng hoặc tiêu diệt đối thủ cao hơn một đại cảnh giới khi có căn cứ thực chất):** Khi lệch một đại cảnh giới, cho phép thắng trực diện hoặc tiêu diệt đối thủ nếu có căn cứ thực chất và điều kiện giao chiến tương ứng; không bắt buộc đối thủ phải bị trọng thương từ trước.
- **`CULT-04.7` (Bản chất ranh giới cảnh giới quan trọng hơn đếm số bậc):** Bản chất ranh giới giữa hai cảnh giới (mức chuyển hóa bản chất sinh mệnh, thần thức và tầng pháp tắc) quan trọng hơn việc chỉ đếm số bậc cảnh giới chênh lệch; áp dụng cùng ba cấp độ vượt cấp (*Vượt cấp chiến thuật, Vượt cấp thực chiến, Vượt cấp sinh tử*).

#### 15A.9. Pháp bảo và ngoại lực
`APPROVED – KIẾN TRÚC`

Hệ thống bảy quy tắc nền `CULT-05.1 – CULT-05.7` (đã duyệt; các mục triển khai `15A.9.3–15A.9.7` dưới đây đóng vai trò giải thích/hệ quả triển khai, không thay thế định nghĩa gốc của từng mã):
- **`CULT-05.1`:** Ngoại lực không thay thế cảnh giới và bản chất sinh mệnh.
- **`CULT-05.2`:** Phải phân biệt sức mạnh vốn có của ngoại lực, khả năng khai thác ngoại lực của chủ thể và giới hạn chịu tải của chủ thể.
- **`CULT-05.3`:** Ngoại lực có giới hạn chịu tải.
- **`CULT-05.4`:** Ngoại lực cần năng lượng để duy trì.
- **`CULT-05.5`:** Tính tương thích ảnh hưởng hiệu suất.
- **`CULT-05.6`:** Ngoại lực có thể làm thay đổi cục diện chiến đấu.
- **`CULT-05.7`:** Ngoại vật đặc thù có giới hạn riêng.

##### 15A.9.1. Nguyên lý
Ngoại lực có thể mở rộng năng lực chiến đấu hoặc tạo ra phương thức vận dụng mới, nhưng không mặc nhiên mở rộng bản chất sinh mệnh và giới hạn chịu tải của người sử dụng. Phải phân biệt:
- Sức mạnh vốn có của ngoại lực.
- Khả năng khai thác ngoại lực của chủ thể.
- Giới hạn chịu tải của chủ thể.

##### 15A.9.2. Sáu nhóm ngoại lực
1. Pháp khí và pháp bảo.
2. Trận pháp và cấm chế.
3. Đan dược và linh dược.
4. Tài nguyên và nguồn năng lượng.
5. Phù lục và vật phẩm tiêu hao.
6. Ngoại viện và sinh linh hỗ trợ.

Ngoại viện và sinh linh hỗ trợ có năng lực, giới hạn, lợi ích và ý chí riêng. Khế ước không biến họ thành công cụ tuyệt đối phục tùng.

##### 15A.9.3. Bốn giới hạn
1. **Giới hạn điều khiển:** Khả năng nhận biết, kiểm soát, ra lệnh và điều khiển ngoại lực. Một pháp bảo có thể sở hữu sức mạnh lớn nhưng chủ nhân không đủ thần thức hoặc kỹ năng để khai thác.
2. **Giới hạn chịu tải:** Khả năng của thân thể, thần thức và nền tảng tu luyện trong việc tiếp nhận, dẫn truyền hoặc phát ra năng lực. Việc sử dụng ngoại lực vượt quá khả năng chịu tải có thể gây phản phệ.
3. **Giới hạn năng lượng:** Ngoại lực có thể cần nguồn năng lượng để kích hoạt, duy trì hoặc phục hồi. Không mặc định mọi pháp bảo đều tự có nguồn năng lượng vô hạn.
4. **Giới hạn tương thích:** Hiệu quả phụ thuộc mức độ phù hợp giữa ngoại lực với người sử dụng, công pháp, thuộc tính năng lượng và điều kiện môi trường.

##### 15A.9.4. Năm dạng lợi thế
1. **Khuếch đại:** Tăng cường năng lực hoặc hiệu quả vốn có.
2. **Mở rộng:** Tạo thêm phạm vi, phương thức hoặc khả năng vận dụng mà chủ thể chưa thể thực hiện trực tiếp.
3. **Chuyển đổi:** Chuyển một loại năng lượng, trạng thái hoặc công năng sang dạng khác.
4. **Hỗ trợ:** Bảo vệ, ổn định, duy trì, phục hồi hoặc cải thiện điều kiện vận hành.
5. **Độc lập:** Tự thực hiện một số hiệu ứng theo cơ chế riêng mà không cần chủ nhân liên tục điều khiển.

Các dạng lợi thế này không đồng nghĩa với việc ngoại lực có thể thay thế bản chất sinh mệnh của chủ thể.

##### 15A.9.5. Ba cấp độ ngoại lực
- **Ngoại lực thông thường:** Phục vụ các nhu cầu tu luyện, chiến đấu, phòng ngự và hỗ trợ phổ biến.
- **Ngoại lực chiến lược:** Có thể ảnh hưởng đáng kể đến cục diện chiến đấu, địa bàn hoặc lợi ích của một thế lực.
- **Ngoại vật đặc thù:** Có khả năng tác động đến pháp tắc hoặc các cơ chế tồn tại ở cấp độ đặc biệt.

Ngoại vật đặc thù phải tuân thủ nguyên tắc giới hạn riêng tại quy tắc `CULT-05.7`. Sức mạnh đặc thù không đồng nghĩa với khả năng giải quyết mọi vấn đề.

##### 15A.9.6. Mức độ tự vận hành của pháp bảo
- **`A2` — Tự vận hành có điều kiện, tương đối phổ biến ở pháp bảo cao cấp:** Pháp bảo có thể thực hiện mệnh lệnh, phản ứng hoặc điều kiện đã được thiết lập trước trong phạm vi công năng của nó. Điều này không có nghĩa pháp bảo có ý thức độc lập.
- **`A3` — Linh trí hoặc ý thức, dành cho trường hợp đặc biệt:** Một số pháp bảo đặc biệt có thể sở hữu linh trí hoặc ý thức và khả năng đưa ra quyết định giới hạn. Không mặc định mọi pháp bảo cao cấp đều đạt đến `A3`.

##### 15A.9.7. Đan dược và cưỡng ép năng lực
Đan dược hoặc linh dược có thể tạm thời nâng cao năng lực vận hành, nhưng không xóa bỏ giới hạn chịu tải hoặc thay thế nền tảng tu luyện. Việc cưỡng ép sử dụng có thể gây:
- Phản phệ.
- Tổn thương nền tảng.
- Hao tổn tuổi thọ.
- Di chứng lâu dài.

##### 15A.9.8. Phá Thiên Chung
Phá Thiên Chung là ngoại vật đặc thù, nhưng không được miễn trừ các nguyên tắc:
- Không thay thế tu luyện của Lâm Tĩnh.
- Không tự động mở rộng giới hạn chịu tải.
- Không tạo năng lượng vô hạn.
- Không xóa bỏ mọi chi phí khi vận dụng thời gian, không gian và pháp tắc.
- Không giải quyết mọi loại xung đột.

Công năng, nguồn gốc, ý chí và giới hạn đầy đủ thuộc `WQ-13`, được thiết kế chuyên sâu trong `artifact_bible.md`. Tỷ lệ thời gian `1:10` tại tầng đầu của Phá Thiên Chung chỉ là `OPEN QUESTION / DESIGN HYPOTHESIS` thuộc `WQ-12`. Không được sử dụng như thông số đã duyệt trong tài liệu này. Quy tắc nền `CULT-05.1 – CULT-05.7`.

#### 15A.10. Ứng dụng vào Lâm Tĩnh
`APPROVED – KIẾN TRÚC`

Bốn trụ cột phát triển của Lâm Tĩnh:
1. **Tu luyện:** Ưu tiên xây dựng căn cơ, nền tảng và độ ổn định phù hợp với năng lực, điều kiện thực tế. Xuất phát điểm phàm nhân và linh căn không có ưu thế định mệnh khiến con đường của Lâm Tĩnh có thể chậm hơn, nhưng không khóa tiềm năng phát triển.
2. **Thực chiến:** Lựa chọn mục tiêu cụ thể trước khi giao chiến; khai thác thông tin, địa hình, điều kiện, ưu thế và nút thắt của đối thủ. Phong cách tính toán không loại bỏ khả năng Lâm Tĩnh chiến thắng trực diện bằng thực lực.
3. **Vượt cấp:** Giai đoạn đầu thiên về vượt cấp chiến thuật; giai đoạn phát triển tiếp theo có thể đạt vượt cấp thực chiến hoặc sinh tử, kể cả đối đầu với người cao hơn một đại cảnh giới khi có căn cứ thực chất và điều kiện phù hợp; luôn tuân thủ `CULT-04.1 – CULT-04.7` và chấp nhận cái giá tương ứng.
4. **Ngoại lực & Phá Thiên Chung:** Khai thác thực dụng, có tính toán và cân nhắc rủi ro; không lệ thuộc mù quáng và không dùng ngoại lực/chuông để xóa bỏ mọi giới hạn chịu tải hay nhân quả.

---

## PHẦN VII — HỒ SƠ CHUẨN, BÍ MẬT & QUY TRÌNH CANON (KẾ THỪA v1.0 & v1.1)

### 16. Hồ sơ chuẩn cho mỗi địa điểm
Mỗi địa điểm trọng yếu nên có một mục hoặc file riêng theo mẫu:

```yaml
location_id: LOC-XXX
name:
aliases: []
world_layer:
region:
relative_position:
terrain:
climate:
population:
main_settlements: []
controlling_factions: []
economic_base: []
cultivation_resources: []
transport_routes: []
travel_time_from:
  - destination:
      method:
      duration:
risks:
historical_events: []
time_anomalies: []
first_appearance:
canon_status: PROPOSED
open_questions: []
```

### 17. Hồ sơ chuẩn cho mỗi thế lực

```yaml
faction_id: FAC-XXX
name:
aliases: []
type:
territory:
public_goal:
actual_interests:
resources: []
power_base:
leadership:
internal_groups: []
allies: []
rivals: []
constraints: []
position_on_cataclysm:
knowledge_of_erased_epoch:
public_reputation:
first_appearance:
canon_status: PROPOSED
open_questions: []
```

### 18. Sổ đăng ký bí mật
Mỗi bí mật lớn cần có hồ sơ riêng:

| Trường | Nội dung cần ghi |
| :--- | :--- |
| Mystery ID | Mã định danh duy nhất |
| Câu hỏi trung tâm | Điều độc giả muốn biết |
| Sự thật dự kiến | Đáp án tác giả đang cân nhắc, có thể chưa khóa |
| Manh mối sớm | Dấu hiệu được gieo trước khi hé lộ |
| Giả thuyết sai | Cách hiểu hợp lý nhưng chưa đầy đủ |
| Người biết | Nhân vật / thế lực nắm từng phần thông tin |
| Thời điểm hé lộ | Quyển hoặc giai đoạn dự kiến |
| Hệ quả | Điều gì thay đổi sau khi biết sự thật |
| Trạng thái | `OPEN` / `PARTIAL` / `CONFIRMED` / `REVISED` |

Không ghi đáp án bí mật vào tài liệu công khai trong thế giới nếu nhân vật chưa thể biết. Cần phân biệt **sự thật của tác giả** với **tri thức của nhân vật** và **niềm tin của xã hội**.

### 19. Quy trình thay đổi canon
Khi thay đổi một yếu tố thế giới:
1. Xác định ID và tài liệu chịu ảnh hưởng.
2. Ghi rõ trạng thái trước và sau.
3. Kiểm tra ảnh hưởng đến địa lý, timeline, nhân vật, kinh tế, cảnh giới và các manh mối.
4. Kiểm tra các chương đã viết có bị mâu thuẫn không.
5. Nếu thay đổi có tác động lớn, tạo Change Request thay vì sửa âm thầm.
6. Chỉ cập nhật production sau khi được phê duyệt và qua kiểm tra.

Không sửa lịch sử thế giới để vá một lỗi nhỏ trong một chương nếu việc đó tạo ra nhiều lỗi lớn hơn.

---

## PHẦN VIII — KIẾN TRÚC TÍCH HỢP v1.2: P1, P2, P3 (`APPROVED WITH NOTES`)

### 20. P1 — Unified Realm Architecture (`APPROVED WITH NOTES`)
- **Nguyên tắc:** *One Realm Hierarchy — Multiple Independent Attributes*. Giữ nguyên thang đại cảnh giới từ `v1.0`/`v1.1` (`15A.2`), không tạo hệ cảnh giới cạnh tranh hoặc cảnh giới phụ từ `Phàm thể`, `Cảm Khí`, `viên mãn`, `lĩnh ngộ` hay `đạo hạnh`.
- **Sáu trục phân tầng độc lập:**
  1. `Major Realm` (Đại cảnh giới — trục chính theo `v1.1`).
  2. `Minor Realm` (Tiểu cảnh giới — chỉ dùng khi có căn cứ xác lập).
  3. `Cultivation State` (Trạng thái tu luyện hiện thời — ổn định, tiêu hao, suy yếu, đình trệ, hồi phục, mất kiểm soát...).
  4. `Foundation` (Nền tảng / Căn cơ — không đồng nhất với cảnh giới hay hiệu suất đơn thuần).
  5. `Comprehension` (Lĩnh ngộ — mức hiểu, nhận thức quy luật/phương pháp; không tự thay thế đột phá hay đủ năng lượng thi triển).
  6. `Mastery` (Đạo hạnh / Thành thạo — khả năng vận dụng thực tế, kinh nghiệm, thuần thục; không tự tăng cùng cảnh giới).
- **Notes & Open Points giữ mở:** Không biến 6 trục thành bảng stat RPG cộng điểm; hoãn giá trị cụ thể và tốc độ tiến cảnh của Lâm Tĩnh (`C16–C100` / `C26–C100`), định nghĩa chi tiết tiểu cảnh giới, điều kiện đột phá, tác động định tính/định lượng từng cảnh giới và tương tác cụ thể giữa các trục.

### 21. P2 — Ability Taxonomy (`APPROVED WITH NOTES`)
- **Nguyên tắc phân loại:** **1 Primary Classification + Secondary Tags + 1 Ability Record**. Mỗi năng lực có một loại chức năng chính, kèm `Secondary Tags` (không nhân bản sức mạnh) và một `Ability Record` duy nhất.
- **Năm nhóm Primary Classification:**
  1. **Công pháp (*Cultivation Method*):** Phương thức tu luyện, vận hành, tích lũy, điều hòa hoặc chuyển hóa nền tảng; không mặc định bao trùm chiêu thức chiến đấu/thần thông.
  2. **Kỹ pháp (*Practiced Technique*):** Kỹ thuật thực thi rèn luyện được (kiếm, quyền/chưởng/cận chiến, bộ pháp, điều khiển binh khí, kiểm soát lực, phòng thủ/né tránh, phối hợp); không mặc định siêu nhiên.
  3. **Thuật pháp (*Spell / Art*):** Phương thức thi triển tạo hiệu ứng cụ thể theo quy trình/điều kiện; không mặc định là thần thông.
  4. **Thần thông (*Special Ability*):** Năng lực đặc thù có bản chất/quy tắc riêng; không chỉ là thuật pháp mạnh hơn và không là ngoại lệ vô điều kiện.
  5. **Bí thuật (*Secret Technique*):** Phương thức đặc biệt gắn với điều kiện, giới hạn, chi phí hoặc hậu quả riêng; phân biệt với **Cấm thuật** (phân loại theo tính chất cấm đoán/nguy hiểm/hậu quả trong thế giới, tránh chuỗi phân cấp chồng chéo kiểu `Bí thuật > Cấm thuật > Thần thông > Cấm thần thông`).
- **Tách biệt hệ thống ngoài taxonomy:** Pháp bảo/binh khí/linh khí, linh thú/linh sủng, trận pháp/phù trận, phù lục, đan dược, nghề phụ (luyện đan/luyện khí/chế phù...), và tài nguyên/truyền thừa/cơ duyên quản lý theo nhóm chức năng riêng.
- **Ability Record & 5 câu hỏi trước khi mở rộng:** Các trường `ID / Name`, `Primary Classification`, `Secondary Tags`, `Origin / Source`, `Acquisition Requirements`, `Activation Method`, `Primary Effect`, `Range / Target`, `Duration`, `Cost`, `Limitation`, `Counterplay`, `Mastery / Development`, `Failure / Consequence`, `Canon Status`; kiểm tra 5 câu: *(1) Giải quyết vấn đề gì? (2) Vì sao thi triển được? (3) Điều kiện kích hoạt? (4) Khi nào thất bại? (5) Có năng lực khác cùng chức năng không?*
- **Notes & Open Points giữ mở:** Xử lý trường hợp lai (`hybrid`), phân biệt thường trực vs. kích hoạt, trường bắt buộc tối thiểu (`mandatory`), quy chuẩn tag/naming/versioning và phê duyệt từng năng lực cụ thể.

### 22. P3 — Power Balance & Stacking Architecture (`APPROVED WITH NOTES`)
- **Nguyên tắc:** *No Free Multiplication of Power*. Loại bỏ phép cộng tuyến tính (`Realm + Technique + Artifact + Secret + Formation + Spirit Beast`); đánh giá thực chiến theo ngữ cảnh (`Combat Effectiveness = Contextual Outcome`) qua 6 trục: `Position`, `Resources`, `Knowledge`, `Relationships`, `Capability`, `Danger`.
- **Tám loại chi phí (Power Cost Framework):** `Energy Cost`, `Physical Cost`, `Mental / Consciousness Cost`, `Material Cost`, `Time Cost`, `Risk Cost`, `Opportunity Cost`, `Consequence Cost` (chống *Cost Inflation*; phân biệt chi phí, nguy cơ và hậu quả kéo dài).
- **Khung vận hành / thời lượng (Duration & Activation):** `Instant`, `Sustained`, `Charged`, `Conditional`, `Passive`, `Triggered`, `Limited-use`, `Prepared` (cho phép kết hợp tag khi ghi rõ điều kiện bắt buộc, hỗ trợ, tiêu hao và điểm thất bại).
- **Mười quy tắc chống cộng dồn (`AS-01` – `AS-10`) & Tám lỗ hổng liên hệ thống (`L-01` – `L-08`):**
  - `AS-01` Duplicate Effects Control (`L-03 Duplicate Effect`)
  - `AS-02` Cost Integrity (`L-01 Cost Cancellation`)
  - `AS-03` Realm Gap Integrity (`L-05 Realm Bypass`)
  - `AS-04` Concurrent Operation Limit (`L-04 Parallel Operation` — kiểm soát tải điều khiển, độ chính xác, tranh chấp tài nguyên và rủi ro; không cấm cứng mọi phối hợp hợp lý)
  - `AS-05` Duration Integrity (`L-02 Duration Exploit`)
  - `AS-06` Compatibility Integrity
  - `AS-07` Consequence Integrity (`L-08 Consequence Reset`)
  - `AS-08` Resource Integrity (`L-06 Infinite Supply`)
  - `AS-09` Classification Integrity
  - `AS-10` `CULT-04–05` Compatibility
- **Counterplay & Bốn lớp Cross-System Exploit Audit:** Khung đối kháng (năng lượng, thời gian, phạm vi/địa hình, thông tin, cấu trúc, thực thi, điều kiện/chiến thuật đặc thù) và 4 lớp kiểm định bắt buộc: *Layer 1 — Individual Capability*, *Layer 2 — Pair Interaction*, *Layer 3 — Multi-System Stacking*, *Layer 4 — Sustained / Repeated Use*.
- **Notes & Open Points giữ mở:** Chưa khóa công thức tính chiến lực, trị số định lượng, ngưỡng vượt cấp cụ thể, quy tắc cộng hưởng từng phần, giới hạn số lượng mang/dùng đồng thời, hay phê duyệt từng pháp bảo/linh thú/trận pháp/bí thuật cụ thể.

---

## PHẦN IX — ĐỐI CHIẾU R3-01–R3-08, NGHIÊN CỨU THAM KHẢO & 10 MỤC UPDATE DRAFT

### 23. Đối chiếu `R3-01` – `R3-08` & Hàm ý từ `Reference Analysis I` / `Reference Study II`
- **Các điểm rà soát `R3-01` – `R3-08`:** `R3-01` (thống nhất realm, không tạo realm cạnh tranh), `R3-02` (tách cảnh giới, lĩnh ngộ, thành thạo), `R3-03` (taxonomy kỹ pháp/thuật pháp/combat), `R3-04` (ranh giới thần thông/bí thuật), `R3-05` (combat framework & chống cộng dồn), `R3-06` (phân chức năng trận pháp/pháp bảo), `R3-07` (phân loại nghề phụ/ngoại lực/tài nguyên), `R3-08` (mô hình chiến lực theo ngữ cảnh `P3`).
- **Hàm ý nghiên cứu tham khảo (`Reference Analysis I` & `Reference Study II` — `RS-II.1`–`RS-II.8`):** Chỉ rút nguyên lý cấu trúc (tích lũy có điều kiện, tài nguyên khan hiếm/đánh đổi, sinh tồn & chuẩn bị thực tế, biến đổi nhận thức/bản chất, kiểm soát tương tác 2 hệ thống / đa hệ thống / duy trì kéo dài). Không sao chép tên gọi, phẩm cấp, công pháp, pháp bảo, nhân vật, tình tiết hay cơ chế riêng từ *Phàm Nhân Tu Tiên* hoặc *Tiên Nghịch*.

### 24. Cấu trúc 10 mục Update Draft (`APPROVED WITH NOTES` — Framework / Preparation)
1. **01. Realm & Cultivation:** Thang đại cảnh giới `v1.1` + 6 trục độc lập `P1`; chống tạo realm cạnh tranh (`R3-01`, `RS-II.1`).
2. **02. Techniques, Spells & Supernatural:** Taxonomy `P2` 5 nhóm + `1 Primary + Secondary Tags + 1 Ability Record` + 5 câu hỏi kiểm tra (`R3-02`–`R3-04`, `RS-II.2`).
3. **03. Combat, Dueling & Tactics:** $\text{Combat} = \text{Ability} + \text{Execution} + \text{Decision} + \text{Context}$ + 8 chức năng chiến đấu (*Công kích, Phòng ngự, Di chuyển, Khống chế, Hỗ trợ, Cảm ứng, Phá giải, Sinh tồn*) tương thích `CULT-04–05` (`R3-03`, `R3-05`).
4. **04. Secret, Forbidden & Burst:** Phân định bí thuật và cấm thuật; yêu cầu đủ 7 yếu tố (điều kiện kích hoạt, hiệu quả, giới hạn, chi phí, hậu quả, nguy cơ thất bại, đối kháng) (`R3-04`, `P3`).
5. **05. Formations & Restrictions:** Phân loại theo chức năng chủ đạo (*Hộ trận, Công trận, Khốn trận, Mê trận, Cảm ứng trận, Tụ linh trận, Phong tỏa trận, Truy tung trận*) và cấu trúc/trận nhãn/vật liệu/nguồn cấp/điểm yếu/phá trận (`R3-06`, `RS-II.5`).
6. **06. Artifacts, Personal & Crafting:** Vòng đời 6 giai đoạn đề xuất (`Phôi/Vật liệu` → `Thành phẩm sơ cấp` → `Pháp khí` → `Linh khí` → `Bản mệnh pháp bảo` → `Phát triển/Hoàn thiện`); phân biệt *Sở hữu* ≠ *Làm chủ* ≠ *Phát huy tối đa* ≠ *Miễn chi phí* (`R3-06`, `RS-II.3`).
7. **07. Alchemy, Talismans & Professions:** Tách 3 lớp (*Nghề nghiệp — Phương pháp — Sản phẩm*); phù lục chuyển chi phí sang chuẩn bị, không miễn phí/vô hạn; đan dược có giới hạn hấp thụ, độc tính/tác dụng phụ, không xóa sạch mọi hậu quả (`R3-07`, `RS-II.6`).
8. **08. Spirit Beasts & Contracts:** Linh thú là sinh thể độc lập có nhu cầu sinh tồn, năng lực, ý chí riêng, quan hệ phát triển theo thời gian và quá trình trưởng thành riêng (`RS-II.4`); hoãn quy tắc khế ước chi tiết.
9. **09. Resources, Opportunities & Inheritance:** Tách 3 nhóm: *Tài nguyên* (`Resources`), *Cơ hội* (`Opportunity` — chuỗi *xuất hiện* ≠ *tiếp cận* ≠ *hiểu* ≠ *sử dụng được* ≠ *sinh lợi*), *Truyền thừa* (`Inheritance`) (`RS-II.6`).
10. **10. Balance & Progression:** 4 lớp tổng hợp (`Cultivation Capacity`, `Individual Capability`, `External Support`, `Situational Execution`) + `P1–P3` + `AS-01–AS-10` (`R3-05`, `R3-07`, `R3-08`, `RS-II.7`–`RS-II.8`); hoãn công thức, trị số và mốc tiến cảnh cụ thể.

---

## PHẦN X — SỔ THEO DÕI OPEN DESIGN (`OD-01` – `OD-12`) & CÁC LỰA CHỌN CÒN MỞ

### 25. Bảng theo dõi `OD-01` – `OD-12` (`OPEN — NOT CLOSED`)

| Mã OD | Chủ đề | Liên kết kiến trúc `P1–P3` / `v1.0–v1.1` | Trạng thái |
| :--- | :--- | :--- | :--- |
| **OD-01** | Cảnh giới | Thang `v1.1` thống nhất + 6 trục độc lập (`P1`) | `OPEN — NOT CLOSED` |
| **OD-02** | Con đường tu luyện Lâm Tĩnh | Theo trục thống nhất, tích lũy/trải nghiệm, hoãn tốc độ cụ thể | `OPEN — NOT CLOSED` |
| **OD-03** | Hệ công pháp | Định nghĩa chức năng tu luyện theo `P2`, không bao trùm mọi năng lực | `OPEN — NOT CLOSED` |
| **OD-04** | Hệ chiến đấu | `Combat Framework` theo ngữ cảnh, tương thích `CULT-04–05` | `OPEN — NOT CLOSED` |
| **OD-05** | Bí pháp | Phân định bí thuật/cấm thuật, 7 yếu tố chi phí/hậu quả/đối kháng | `OPEN — NOT CLOSED` |
| **OD-06** | Trận đạo | Chức năng chủ đạo, cấu trúc, nguồn cung, điểm yếu, phá trận | `OPEN — NOT CLOSED` |
| **OD-07** | Bản mệnh pháp bảo | Vòng đời 6 giai đoạn, tương thích, làm chủ, giới hạn cộng hưởng | `OPEN — NOT CLOSED` |
| **OD-08** | Nghề phụ | Tách nghề nghiệp / phương pháp / sản phẩm, giới hạn nguyên liệu & kỹ năng | `OPEN — NOT CLOSED` |
| **OD-09** | Linh thú | Sinh thể độc lập, ý chí, quan hệ, chi phí, giới hạn đồng hành | `OPEN — NOT CLOSED` |
| **OD-10** | Tốc độ phát triển | Tiến triển không đồng tốc, có độ trễ/điều kiện/hậu quả, không shortcut | `OPEN — NOT CLOSED` |
| **OD-11** | Tên gọi & thuật ngữ | `1 Primary Classification + Secondary Tags`, chống nhân bản năng lực | `OPEN — NOT CLOSED` |
| **OD-12** | World Bible Governance | Phân tầng trạng thái, kiểm soát nguồn/phiên bản/phê duyệt/canon | `OPEN — NOT CLOSED` |

*Thứ tự phụ thuộc tham khảo:* `OD-01` → `OD-02` → `OD-03 + OD-11` → `OD-04 + OD-05` → `OD-06 + OD-07` → `OD-08 + OD-09` → `OD-10` → `OD-12` (chỉ là trình tự đối chiếu tham khảo, không tự đóng hoặc sửa đổi `OD`).

### 26. Các lựa chọn thiết kế còn mở & danh sách việc trước khi khóa thế giới (Kế thừa v1.0 & v1.1)
- **Mô hình đại kiếp (`v1.0` Mục 20.1):** Phong ấn suy yếu / Hậu quả chuyển dịch / Chu kỳ tái phát / Kết hợp có thứ bậc (khuyến nghị `D`: một nguyên nhân gốc và cơ chế trì hoãn/phân tán liên kết nhân quả).
- **Cách lịch sử bị xóa (`v1.0` Mục 20.2):** Viết lại có chủ ý / Biến dạng pháp tắc / Kết hợp hai lớp (khuyến nghị `C`).
- **Mô hình thiên đạo (`v1.0` Mục 20.3):** Quy luật vô ý chí / Ý chí hoặc biểu hiện giống ý chí / Cơ chế bị tác động nhưng được diễn giải như ý chí (khuyến nghị `C`).
- **Cấu trúc tầng thế giới (`v1.0` Mục 20.4):** Hạ giới – Thượng giới – Ngoại tầng / Nhiều giới song song không thứ bậc tuyệt đối / Mô hình kết hợp mở rộng theo nhu cầu cốt truyện (khuyến nghị `C`).
- **Danh sách việc phải hoàn tất trước khi khóa thế giới (`v1.0` Mục 21):** (1) Chọn cơ chế chính xác của đại kiếp; (2) Chọn cơ chế xóa lịch sử; (3) Chọn mô hình thiên đạo; (4) Chốt mô hình tầng thế giới; (5) Đặt tên đại lục và vùng duyên hải mở đầu; (6) Lập bản đồ logic cho vùng mở đầu; (7) Thiết kế ít nhất ba thế lực có lợi ích xung đột tại khu vực đầu; (8) Xác định nguồn tài nguyên và tuyến giao thương chủ đạo; (9) Xác định lịch sử tối thiểu người dân địa phương biết; (10) Tách thông tin tác giả biết khỏi thông tin Lâm Tĩnh biết.

---

## PHẦN XI — TUYÊN BỐ TRẠNG THÁI

Tài liệu `World Bible v1.2.md` kế thừa đầy đủ cấu trúc và nội dung từ `world_bible.md` v1.0 và `world_bible.md` v1.1 (bao gồm Phần 0–VII và Mục `15A.1–15A.10`), tích hợp các đề xuất kiến trúc `P1–P3` (`APPROVED WITH NOTES`), đối chiếu `R3-01–R3-08`, hàm ý từ `Reference Analysis I` và `Reference Study II`, khung 10 mục `Update Draft`, và sổ theo dõi `OD-01–OD-12` (`OPEN — NOT CLOSED`).

- Các mô hình đề xuất, giả thuyết thiết kế và câu hỏi mở (`WQ-01–WQ-15`, `OD-01–OD-12`, `Notes`, `Open Points`, `Deferred Items`) giữ nguyên trạng thái kiểm soát, không tự động nâng thành canon khóa cứng.
- Không sửa đổi hồi tố `C1–C25`, không chỉnh sửa `C26 — Draft 1`, không mở rộng quyền viết sang `C27–C35`, và không ghi đè `World Bible v1.0` / `World Bible v1.1`.

**Trạng thái hiện tại:** `PHASE 5 INTEGRATION DRAFT — DRAFT – AWAITING REVIEW — CANON: NOT LOCKED`
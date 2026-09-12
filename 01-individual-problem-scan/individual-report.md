# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Nguyên Phong
- Mã học viên: 2A202602691
- Vai trò / bối cảnh: Sinh viên năm 3, intern mảng AI Y tế (AIE) — Trực tiếp tham gia khảo sát thực địa và hỗ trợ triển khai giải pháp thị giác máy tính tại các phòng khám đa khoa & trạm y tế cơ sở, chuyên sâu về mảng sàng lọc bệnh lý da liễu.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Túc trực tại phòng khám để cùng ngồi với bác sĩ, bấm giờ và ghi nhận từng bước trong quy trình khám da liễu thực tế.
  - Phỏng vấn nhanh bác sĩ đa khoa và người bệnh sau ca khám để nắm bắt điểm nghẽn và những điều họ thấy bất tiện nhất.
  - Thu thập, phân loại ảnh chụp thương tổn da từ điện thoại và máy soi da cầm tay; kiểm tra sơ loại chất lượng ảnh đầu vào (ảnh mờ, chói đèn, dính lông tóc).
  - Phối hợp với đội ngũ kỹ thuật AI để phản ánh trải nghiệm người dùng, đơn giản hóa giao diện ứng dụng hỗ trợ chẩn đoán cho bác sĩ dễ thao tác.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / Thiếu chuyên môn | Bác sĩ đa khoa tuyến xã/huyện bối rối khi phân biệt tổn thương da lành tính và ác tính (u hắc tố, ung thư tế bào đáy) | Bác sĩ, Bệnh nhân | Bấm giờ trung bình mất 15–20 phút/ca; 4/5 bác sĩ trạm y tế chia sẻ: "Gặp vết đốm sẫm màu loang lổ là rất ngại, không dám kết luận tại chỗ, thường chọn cách viết giấy chuyển viện cho chắc ăn". |
| 2 | AI có thể tốt hơn | Bác sĩ từ chối dùng phần mềm AI hỗ trợ nếu hệ thống chỉ trả về mỗi con số xác suất (%) mà không khoanh vùng rõ vết tổn thương | Bác sĩ lâm sàng | 8/10 bác sĩ được phỏng vấn từ chối dùng: "Máy báo 85% u ác tính mà không vẽ viền chỉ rõ chỗ nào thì ai dám tin, nhỡ máy bắt nhầm vào nốt tàn nhang bên cạnh thì sao?". |
| 3 | Lặp lại | Bác sĩ phải thao tác qua lại giữa quá nhiều ứng dụng và giấy tờ (HIS bệnh viện, Zalo nhận ảnh từ điện thoại, Google Drive, tài liệu PDF tra cứu) | Bác sĩ | Bấm giờ thực tế: Bác sĩ phải Alt-Tab chuyển đổi cửa sổ từ 4–5 lần trong một ca khám, tốn thêm ~3-4 phút chỉ để gom đủ ảnh và thông tin bệnh nhân. |
| 4 | Tốn thời gian | Đứt gãy từ lúc biết tên bệnh sang hướng xử trí: Chẩn đoán xong nhưng mất nhiều thời gian lục tìm phác đồ điều trị chuẩn | Bác sĩ | Mất 10–15 phút/ca để lục tìm lại các file PDF quyết định hướng dẫn của Bộ Y tế hoặc lật cuốn sổ tay da liễu để chép liều thuốc và chỉ định. |
| 5 | Pain từ người khác | Bệnh nhân tự tra Google/mạng xã hội trước khi đi khám rồi hoảng sợ nghĩ mình bị ung thư, bác sĩ mất nhiều thời gian giải thích | Bệnh nhân, Bác sĩ | 6/10 bệnh nhân bước vào phòng khám với tâm lý căng thẳng tột độ; bác sĩ phải mất 7–10 phút đầu ca chỉ để trấn an tinh thần và giải tỏa hiểu lầm cho người bệnh. |
| 6 | Lặp lại | Theo dõi sự tiến triển của vết thương tổn qua các lần tái khám bằng cách lục lại từng file ảnh cũ trong thư mục rồi so bằng mắt thường | Bác sĩ | Bác sĩ mất trung bình 4–5 phút mỗi ca tái khám để mở lại thư viện ảnh cũ, phóng to thu nhỏ trên màn hình máy tính để tự ước lượng xem vết sẫm màu có lan rộng không. |
| 7 | Pain từ người khác | Bác sĩ khó giải thích trực quan bờ viền và mức độ nguy hiểm của thương tổn, khiến người bệnh ngờ vực kết quả chẩn đoán | Bệnh nhân, Bác sĩ | Bệnh nhân hoang mang hỏi đi hỏi lại 3–4 lần: "Sao bác sĩ nhìn mắt thường mà khẳng định là lành tính?", ca khám bị kéo dài thêm 5 phút vì thiếu hình ảnh trực quan minh họa. |
| 8 | AI có thể tốt hơn | Nhiễu lông và tóc rậm rạp trên ảnh chụp lâm sàng (tay, chân, đầu) khiến mô hình thị giác máy tính nhận diện sai lệch ranh giới tổn thương | Kỹ sư AI, Bác sĩ | Khoảng 35% ảnh chụp thực tế dính nhiều lông tơ/tóc; mô hình phân đoạn (segmentation) bị bắt nhầm sợi lông làm viền khối u, chỉ số IoU sụt giảm nghiêm trọng từ 0.88 xuống còn 0.27. |
| 9 | Tốn thời gian | Chất lượng ảnh chụp da từ điện thoại của phòng khám không đồng đều (bị rung mờ, bóng chói đèn huỳnh quang), phải yêu cầu bệnh nhân chụp lại | Điều dưỡng, Bác sĩ | Thống kê tuần qua: 14/50 ảnh gửi lên (28%) bị chói lóa ánh đèn hoặc rung tay không dùng được, nhân viên y tế mất thêm 3–5 phút hướng dẫn chụp lại từ đầu. |
| 10 | AI có thể tốt hơn | Hệ thống AI chỉ phân tích ảnh đơn lẻ mà bỏ qua các thông tin lâm sàng thiết yếu (tuổi, giới tính, tiền sử tiếp xúc ánh nắng, thời gian xuất hiện tổn thương) | Bác sĩ, Bệnh nhân | 100% bác sĩ được hỏi khẳng định cùng một nốt dát đen ở người 20 tuổi mang ý nghĩa chẩn đoán khác hẳn ở người 70 tuổi; việc thiếu thông tin ngữ cảnh khiến AI rất dễ đưa ra nhận định sai lệch. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Gợi ý các điểm nghẽn thực tế khi triển khai phần mềm chẩn đoán hình ảnh da liễu tại phòng khám tuyến cơ sở ở Việt Nam."
- Ý dùng được: Vấn đề "bác sĩ không tin AI dạng hộp đen chỉ ném ra số % xác suất" và "sự đứt gãy giữa khâu nhận diện tên bệnh với khâu tra cứu phác đồ điều trị thực tế".
- Ý bỏ vì không phải pain thật: AI gợi ý "bác sĩ gặp khó khăn khi dùng giọng nói chuyển thành văn bản bệnh án (speech-to-text)" và "hệ thống chatbot tự động xếp lịch hẹn". Tôi bỏ các ý này vì thực tế đi phòng khám tuyến huyện/xã thấy máy tính trạm y tế khá cũ, không có micro xịn, họ quen gõ tay tóm tắt hoặc ghi sổ. Điểm nghẽn đau đầu nhất của họ là chuyên môn nhận diện thương tổn da và hướng xử trí lâm sàng, chứ không phải vấn đề đặt lịch hay nhập liệu giọng nói.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (đạt 10 dòng)
- [x] Dùng ít nhất 3/4 lăng kính (đủ cả 4 lăng kính)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Bác sĩ tuyến cơ sở thiếu công cụ thị giác trực quan (khoanh vùng ROI) và đứt gãy phác đồ điều trị khi sàng lọc bệnh da liễu | - Workflow khám lâm sàng rõ ràng từng bước.<br>- Đánh trúng nỗi sợ lớn nhất của bác sĩ: sợ đoán nhầm u ác tính và ngại AI hộp đen.<br>- Kết nối được trọn vẹn từ lúc soi ảnh đến lúc ra hướng xử trí. | Mức độ tiếp nhận và sẵn sàng thay đổi thói quen của các bác sĩ lớn tuổi tại trạm y tế. |
| 2 | Nhiễu lông/tóc trên ảnh lâm sàng phá vỡ ranh giới nhận diện tổn thương của mô hình phân đoạn | - Là bài toán kỹ thuật nhức nhối trực tiếp phá hủy độ chính xác của AI.<br>- Có bottleneck cụ thể ở khâu tiền xử lý ảnh thô.<br>- Giải quyết xong giúp cải thiện tức thì độ tin cậy của viền tổn thương. | Thuật toán lọc lông tự động có vô tình xóa nhầm các viền mạch máu mảnh hoặc chi tiết thật của khối u hay không. |
| 3 | Đứt gãy giữa chẩn đoán tên bệnh và tra cứu phác đồ điều trị chuẩn | - Giải quyết đúng điểm khựng kéo dài 10-15 phút của bác sĩ sau khi đã biết tên bệnh.<br>- Khép kín hành trình khám chữa bệnh, mang lại giá trị thực tế cho người bệnh.<br>- Có thể chuẩn hóa thành dữ liệu có cấu trúc. | Khối lượng dữ liệu phác đồ y khoa cần số hóa và quy trình cập nhật khi Bộ Y tế có văn bản mới. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Trợ lý thị giác lâm sàng hỗ trợ chẩn đoán và điều trị da liễu tuyến cơ sở (AI4Beauty End-to-End Assistant)

```text
Problem 1 câu:
Bác sĩ đa khoa tại trạm y tế cơ sở mất 15–20 phút/ca và dễ chẩn đoán sai hoặc vội vã chuyển viện các ca tổn thương da nghi ngờ ác tính, do các công cụ AI hiện nay chỉ trả về con số xác suất hộp đen (không khoanh vùng vị trí) và không kết nối trực tiếp với phác đồ điều trị chuẩn.

Actor:
Bác sĩ đa khoa / y sĩ tại trạm y tế xã, phòng khám đa khoa khu vực hoặc trung tâm y tế huyện.

Thời điểm / bối cảnh:
Trong ca khám lâm sàng trực tiếp khi người bệnh đến khám vì có nốt sần, vết loét, dát sắc tố bất thường trên da (nghi ngờ ung thư tế bào đáy, ung thư tế bào vảy, u hắc tố...).

Current workflow 3-7 bước:
1. Chụp ảnh tổn thương da bằng điện thoại hoặc dùng kính soi da cầm tay (1-2 phút).
2. Quan sát tổn thương bằng mắt thường, tự ước lượng theo cảm quan chủ quan (3-5 phút - dễ nhầm lẫn).
3. Do dự không chắc chắn, mở Google hoặc gọi điện hỏi đồng nghiệp tuyến trên (4-5 phút).
4. Phỏng đoán tên bệnh nhưng không có ranh giới viền rõ ràng để đối chiếu (2 phút).
5. Mở máy tính lục tìm phác đồ điều trị hoặc quyết định chuyển tuyến trong các file PDF rời rạc (4-5 phút).
6. Tư vấn, viết đơn thuốc hoặc kê giấy chuyển tuyến cho bệnh nhân (2-3 phút).

Bottleneck:
Bước 2 & 4 (Đánh giá bằng mắt cảm tính, thiếu công cụ thị giác trực quan chỉ rõ bờ viền và vùng nghi ngờ) và Bước 5 (Mất thời gian lục lọi phác đồ điều trị phù hợp).

Impact:
- Mỗi ca khám kéo dài 15–20 phút (trong khi tiêu chuẩn trạm y tế chỉ cho phép 5–7 phút/người).
- Tỉ lệ chuyển tuyến "phòng hờ" không cần thiết lên đến hơn 40%, gây tốn kém tiền bạc của người dân và quá tải cho bệnh viện chuyên khoa tuyến trên.
- Bác sĩ luôn trong trạng thái bất an vì sợ bỏ sót tổn thương ác tính.

Success metric:
- Thời gian từ lúc chụp ảnh đến khi có gợi ý chẩn đoán và phác đồ giảm từ 18 phút xuống dưới 4 phút/ca.
- Tỉ lệ bác sĩ đồng thuận với vùng tổn thương khoanh bởi AI (ROI Mask) đạt >= 85% trong thử nghiệm lâm sàng.
- 100% ca gợi ý chẩn đoán có đi kèm trích dẫn văn bản phác đồ chính thống của Bộ Y tế để bác sĩ kiểm tra ngay trên màn hình.

Non-AI alternative:
In tập bảng kiểm tiêu chuẩn ABCDE màu và cuốn sổ tay phác đồ da liễu để sẵn trên bàn khám.
Nhược điểm: Bác sĩ vẫn phải tự nhìn bằng mắt thường, rất dễ sót viền mờ ở các nốt nhỏ; tra cứu sách giấy vẫn chậm và không cập nhật được văn bản mới.

AI hypothesis:
Một quy trình kết hợp: Lọc nhiễu lông tóc -> Khoanh vùng tổn thương (DeepLabV3+) -> Phân loại bệnh (EfficientNet-B3) -> Ánh xạ phác đồ chuẩn từ cơ sở dữ liệu y tế. AI chỉ đóng vai trò "người chuẩn bị bản nháp trực quan", bác sĩ nhìn thấy viền khoanh và giữ quyền bấm duyệt cuối cùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 18 phút/ca

[1 Chụp ảnh tổn thương: 1.5']
→ [2 Soi mắt thường, nhớ tiêu chuẩn: 4.0']  <-- Cảm tính, thiếu tự tin
→ [3 Gọi đồng nghiệp / tra cứu mạng: 4.5']
→ [4 Phỏng đoán tên bệnh: 2.0']            <-- Hộp đen, không có ranh giới
→ [5 Tìm file PDF phác đồ Bộ Y tế: 4.0']   <-- Bottleneck tra cứu thủ công
→ [6 Kê đơn / viết giấy chuyển viện: 2.0']

FUTURE STATE — 3.5 phút/ca

[1 Tải ảnh lên giao diện AI4Beauty: 0.3']
→ [2 Khử lông tự động + Khoanh viền tổn thương (DeepLabV3+): 0.4']  <-- AI tạo Mask trực quan
→ [3 Nhận diện phân loại bệnh + Ánh xạ phác đồ chuẩn: 0.3']        <-- AI draft kết quả
→ [4 Bác sĩ đối chiếu vùng khoanh, tên bệnh & phác đồ: 1.5']       <-- Human Boundary (Bác sĩ duyệt)
→ [5 Bác sĩ chốt chẩn đoán, in hướng dẫn điều trị: 1.0']

Fallback: Nếu ảnh quá mờ hoặc độ tin cậy của AI < 60%, hệ thống cảnh báo "Không đủ điều kiện phân tích" và yêu cầu bác sĩ chuyển sang quy trình khám lâm sàng truyền thống.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Lọc nhiễu lông/tóc tự động trên ảnh tổn thương da trước khi phân đoạn (Digital Hair Removal)

```text
Problem 1 câu:
Mô hình thị giác máy tính chẩn đoán da liễu bị suy giảm độ chính xác nghiêm trọng (chỉ số IoU tụt từ 0.88 xuống 0.27) khi xử lý ảnh lâm sàng chứa nhiễu sợi lông/tóc rậm rạp che khuất ranh giới vết thương.

Actor:
Kỹ sư phát triển AI y tế / Bác sĩ phân tích ảnh lâm sàng.

Thời điểm / bối cảnh:
Giai đoạn tiền xử lý dữ liệu ảnh thô nhận từ điện thoại hoặc máy soi da trước khi đưa vào mô hình học sâu phân đoạn (segmentation).

Current workflow 3-7 bước:
1. Nhận ảnh chụp tổn thương thô từ phòng khám gửi lên (0.5 phút).
2. Nạp trực tiếp ảnh vào mô hình phân đoạn DeepLabV3+ (0.5 phút).
3. Mô hình nhận diện sợi lông đen là ranh giới tổn thương, tạo ra mặt nạ (Mask) bị răng cưa hoặc đứt đoạn (1.0 phút).
4. Kỹ sư hoặc bác sĩ phải mở công cụ đồ họa để tẩy xóa và vẽ lại viền Mask bằng tay (5.0 phút).

Bottleneck:
Bước 3 & 4 (Mô hình bị lừa bởi sợi lông khiến ranh giới tổn thương bị sai lệch hoàn toàn, buộc con người phải can thiệp vẽ lại thủ công).

Impact:
- Tốn thêm 5–7 phút cho mỗi bức ảnh dính lông chỉ để chỉnh sửa mask thủ công.
- Làm sai lệch nghiêm trọng các chỉ số hình học của khối u (chu vi, diện tích, độ bất đối xứng), trực tiếp dẫn đến việc phân loại nhầm giữa u lành và ung thư.

Success metric:
- Chỉ số trùng khớp ranh giới (IoU) trên tập dữ liệu ảnh dính lông tăng từ 0.27 lên >= 0.88.
- Tốc độ xử lý lọc lông tự động đạt < 0.4 giây/ảnh, giữ nguyên vẹn các vệt màu và cấu trúc vân da thật của thương tổn.
- Giảm 90% số ca cần con người phải ngồi vẽ lại viền mask bằng tay.

Non-AI alternative:
Yêu cầu điều dưỡng hoặc bác sĩ cạo sạch lông vùng da tổn thương trước khi chụp ảnh.
Nhược điểm: Làm bệnh nhân khó chịu, đau rát hoặc tăng nguy cơ trầy xước nhiễm trùng; tốn thêm 5–10 phút chuẩn bị cho mỗi ca.

AI hypothesis:
Áp dụng thuật toán xử lý ảnh hình thái học truyền thống (Biến thể DullRazor: Morphological Black Top-Hat + Adaptive Thresholding + Inpainting) để tự động xóa sạch sợi lông trước khi nạp vào mạng nơ-ron DeepLabV3+.

Quick gut:
[ ] No AI / process fix
[x] Rule (Computer Vision Filter)
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 7.0 phút

[1 Nhận ảnh thô dính lông: 0.5'] 
→ [2 Nạp vào mô hình phân đoạn: 0.5'] 
→ [3 Mô hình bắt nhầm lông, Mask bị đứt gãy: 1.0']  <-- Bottleneck kỹ thuật
→ [4 Dùng chuột ngồi tô sửa Mask bằng tay: 5.0']

FUTURE STATE — 0.8 phút

[1 Nhận ảnh thô dính lông: 0.2'] 
→ [2 Chạy bộ lọc CV xóa lông tự động (DullRazor): 0.1'] 
→ [3 DeepLabV3+ phân đoạn trên nền ảnh đã làm sạch: 0.3'] 
→ [4 Bác sĩ liếc mắt kiểm tra nhanh Mask chuẩn: 0.2']  <-- Human Boundary

Fallback: Luôn lưu và hiển thị ảnh gốc song song bên cạnh ảnh đã lọc lông; nếu thuật toán xóa lông làm mờ mất chi tiết viền thật, bác sĩ có thể click chuyển về xem ảnh gốc.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tự động ánh xạ phác đồ điều trị chuẩn hóa theo mã bệnh da liễu (Treatment Protocol Mapping)

```text
Problem 1 câu:
Bác sĩ tại tuyến cơ sở sau khi đã xác định được tên bệnh da liễu vẫn phải mất thêm 10–15 phút tra cứu thủ công qua nhiều văn bản PDF rời rạc để tìm phác đồ điều trị chuẩn và liều lượng thuốc phù hợp.

Actor:
Bác sĩ đa khoa khám chữa bệnh tại các cơ sở y tế ban đầu.

Thời điểm / bối cảnh:
Ngay sau khi có kết luận chẩn đoán về nhóm bệnh hoặc bệnh lý cụ thể của bệnh nhân (như Viêm da cơ địa, Dày sừng tiết bã, Ung thư biểu mô tế bào đáy...).

Current workflow 3-7 bước:
1. Xác định được tên bệnh da liễu (0.5 phút).
2. Mở trình duyệt web hoặc tìm tập tài liệu trên bàn (1.5 phút).
3. Gõ tìm kiếm tên bệnh trên Google hoặc lội tìm trong các file hướng dẫn của Bộ Y tế (5.0 phút).
4. Đọc lướt, chắt lọc phần phác đồ áp dụng được cho tuyến cơ sở (4.0 phút).
5. Soạn đơn thuốc, ghi chú liều dùng và căn dặn người bệnh (2.0 phút).

Bottleneck:
Bước 3 & 4 (Mất thời gian tra cứu và chọn lọc thông tin từ các nguồn tài liệu PDF dài hàng trăm trang không có cấu trúc tìm kiếm nhanh).

Impact:
- Lãng phí 10–15 phút/ca; khiến hàng dài bệnh nhân bên ngoài phải chờ đợi sốt ruột.
- Nguy cơ kê đơn theo thói quen cũ hoặc áp dụng phác đồ lỗi thời không đúng với hướng dẫn cập nhật của Bộ Y tế.

Success metric:
- Thời gian hiển thị phác đồ tóm tắt < 1.5 giây ngay khi chọn hoặc chốt tên bệnh.
- 100% phác đồ hiển thị có viện dẫn rõ ràng số hiệu quyết định lưu hành của Bộ Y tế hoặc Bệnh viện Da liễu Trung ương.
- 0% sai sót về liều lượng thuốc đầu tay đối với các bệnh da liễu thường gặp trong danh mục trạm y tế.

Non-AI alternative:
In sẵn cuốn sổ tay "Tổng hợp phác đồ điều trị 10 bệnh da liễu thường gặp" đặt ngay bàn khám.
Nhược điểm: Tra cứu giấy vẫn chậm chạp, dễ thất lạc, không thể tự cập nhật khi cơ quan quản lý ban hành hướng dẫn mới.

AI hypothesis:
Xây dựng cơ sở dữ liệu phác đồ chuẩn hóa dạng JSON có cấu trúc, sử dụng bộ quy tắc ánh xạ (Rule-based Mapping) trực tiếp từ mã phân loại bệnh của AI sang phác đồ tương ứng mà không dùng AI tạo sinh (để loại trừ hoàn toàn rủi ro bịa đặt thông tin y khoa).

Quick gut:
[ ] No AI / process fix
[x] Rule (Structured Mapping)
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 13 phút

[1 Xác nhận tên bệnh: 0.5'] 
→ [2 Mở máy tính / sổ tay: 1.5'] 
→ [3 Tìm kiếm văn bản phác đồ: 5.0']  <-- Bottleneck tra cứu
→ [4 Đọc và lọc thuốc phù hợp: 4.0'] 
→ [5 Soạn đơn thuốc: 2.0']

FUTURE STATE — 1.5 phút

[1 AI đưa mã bệnh dự đoán: 0.1'] 
→ [2 Rule-engine map sang JSON Phác đồ chuẩn của Bộ Y tế: 0.1'] a
→ [3 Bác sĩ đọc bảng tóm tắt phác đồ, liều dùng & nguồn trích dẫn: 1.0']  <-- Human Boundary
→ [4 Bác sĩ bấm duyệt đưa vào đơn thuốc: 0.3']

Fallback: Nếu bệnh nhân có bệnh nền đặc biệt hoặc mã bệnh nằm ngoài danh mục chuẩn hóa sẵn, hệ thống hiển thị nút "Tra cứu nhanh trên Cổng thông tin Cục Quản lý Khám chữa bệnh".
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**  
Problem Card #1: Trợ lý thị giác lâm sàng hỗ trợ chẩn đoán và điều trị da liễu tuyến cơ sở (AI4Beauty End-to-End Assistant).

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**  
Tôi chọn Card #1 vì nó giải quyết trọn vẹn điểm gãy nhức nhối nhất mà tôi trực tiếp quan sát thấy ở phòng khám: bác sĩ tuyến dưới không bao giờ dám tin một con số % xác suất lơ lửng nếu không nhìn thấy máy đang soi vào đâu, và kể cả khi biết bệnh thì họ vẫn bế tắc khâu phác đồ. Card này kết nối một luồng hoàn chỉnh từ ảnh chụp thô đến gợi ý điều trị, có số đo thời gian rõ ràng (giảm từ 18 phút xuống dưới 4 phút/ca) và phân định ranh giới rất an toàn: AI chỉ chuẩn bị bản nháp trực quan, bác sĩ giữ toàn quyền quyết định chuyên môn.

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**  
"Nếu AI khoanh vùng thương tổn (ROI) trông rất mượt mà và thuyết phục, nhưng thực chất lại nhận diện nhầm giữa hai mặt bệnh có biểu hiện bề mặt na ná nhau (ví dụ: ung thư tế bào đáy thể nông với vết chàm da thông thường), thì giao diện và cơ chế cảnh báo cần thiết kế thế nào để bác sĩ không bị hội chứng ỷ lại vào máy (automation bias) mà nhắm mắt duyệt bừa?"

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Ban đầu tôi bị quán tính kỹ thuật, chỉ chăm chăm đưa các chỉ số mô hình như IoU và F1-score vào metric thành công. AI phản biện rằng đối với bác sĩ lâm sàng, các chỉ số đó hoàn toàn vô nghĩa nếu không giải quyết được áp lực thời gian của phòng khám và rủi ro kiện tụng y khoa.
- Tôi sửa gì: Đưa chỉ số thời gian ca khám (< 4 phút) và tỉ lệ bác sĩ đồng thuận với Mask (>= 85%) lên hàng đầu, đồng thời bắt buộc mọi gợi ý phác đồ phải có trích dẫn số quyết định chính thức của Bộ Y tế để bảo vệ bác sĩ về mặt pháp lý.

---

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field (đã scan 10 problems)
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

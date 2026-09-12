# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Nguyên Phong
- Mã học viên: 2A202602691
- Nhóm: Nhóm 6 thành viên (Hà Mạnh Tuân, Đào Ngọc Bình Thiên, Nguyễn Hải Long, Đỗ Thái Sơn, Nguyễn Vũ Huy, Nguyễn Nguyên Phong)
- Candidate problem nhóm chọn: Literature Review & Research Gap Navigator — hỗ trợ người làm nghiên cứu tìm và kiểm chứng paper uy tín, lập evidence map, phát hiện candidate research gaps và lọc các gap phù hợp với dữ liệu, compute, thời gian cùng kỹ năng hiện có.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".a

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Điền 10 problems từ thực tế, đóng góp top 3 candidates (AI4Beauty, lọc nhiễu lông tóc, tra cứu phác đồ da liễu). | Đóng góp 3 trong số 18 candidate problems đầu vào cho bảng tổng hợp của nhóm (mục 16, 17, 18). |
| Pitch Problem Card | Pitch Card #1 (AI4Beauty) và chia sẻ trải nghiệm về việc bác sĩ từ chối AI nếu không có bằng chứng thị giác trực quan (ROI Mask). | Giúp nhóm thống nhất nguyên tắc: AI trong bất kỳ lĩnh vực nào cũng không được là "hộp đen", bắt buộc phải trích dẫn bằng chứng nguồn (provenance). |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện bài Literature Review của Tuân: "Làm sao đảm bảo AI không bịa ra research gap hoặc bỏ sót paper mới công bố tháng trước?". | Buộc nhóm phải bổ sung bước tìm kiếm phản chứng (counter-search) và tầng kiểm tra tính xác thực qua Crossref API. |
| Gom trùng / cluster | Cùng nhóm phân loại 18 ý tưởng thành 4 cụm; đưa bài tra cứu phác đồ của tôi vào Cụm A (Knowledge & evidence retrieval), 2 bài kỹ thuật vào Cụm D. | Thấy rõ điểm giao thoa giữa việc tra cứu phác đồ y tế và literature review: đều là nỗi đau tổng hợp thông tin phân mảnh và cần tính chính xác tuyệt đối của nguồn dẫn. |
| Chọn candidate problem | Phân tích tính khả thi giữa bài da liễu (impact lớn nhưng rủi ro y tế cao, khó pilot trong lab) với bài Literature Review (pain thật kéo dài >3 ngày của bạn Tuân, data mở có sẵn). | Chủ động đồng thuận lùi bài da liễu lại, dồn lực cùng nhóm chọn Literature Review vì nhóm có thể tự làm đối tượng kiểm chứng ngay trong lab. |
| Validation / research | Cùng nhóm rà soát 4 giải pháp hiện có (Google Scholar, Semantic Scholar API, Crossref API, Cochrane) và phân tích khoảng trống. | Đúc kết bài học cốt lõi: nhóm không dại gì đi build thêm một search engine nữa, mà phải tập trung vào khâu xác minh DOI và lọc gap theo nguồn lực. |
| Workflow nhóm | Cùng Tuân bóc tách 12 bước trong Current Workflow và thiết kế 11 bước trong Future Workflow. | Đóng góp bước Rule xác minh metadata/retraction tự động và chốt chặn con người (Human Boundary) ở khâu duyệt inclusion và chọn gap. |
| Problem Statement | Tham gia hoàn thiện bảng Problem Statement v0 và nâng cấp lên v1, siết lại tiêu chí Success Metric và Boundary. | Bổ sung quy định chặt chẽ: mỗi gap phải có ít nhất 2 paper hỗ trợ và 1 lượt search phản chứng; 100% citation phải xác minh được link gốc. |
| Rule / Workflow / Agent | Tham gia trả lời 5 câu hỏi chốt để lựa chọn kiến trúc công nghệ phù hợp. | Kiên quyết bảo vệ quan điểm chọn mức **Workflow** kết hợp Rule-based; chặn đứng ý tưởng làm Autonomous Agent tự hành đầy rủi ro. |
| Decision | Trực tiếp đánh giá 6 câu hỏi sẵn sàng trong bảng Final Decision. | Đồng thuận chốt quyết định **Not Yet** (thay vì Go sớm) để ưu tiên chạy pilot nhỏ trên corpus 50–100 paper và đo đếm benchmark trước khi code sản phẩm. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là mang tư duy 'chống hộp đen và kiểm soát rủi ro' từ bài toán y tế sang bài toán Literature Review: kiên quyết yêu cầu hệ thống phải có tầng Rule xác minh DOI qua Crossref và bắt buộc phải có bước search phản chứng (counter-search) trước khi đưa bất kỳ research gap nào vào danh sách gợi ý.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI gợi ý thêm góc nhìn về điểm nghẽn của bác sĩ tại phòng khám cơ sở. | Gợi ý trúng tâm lý bác sĩ e ngại AI hộp đen chỉ trả xác suất mà không có bằng chứng hình ảnh. | Gợi ý làm speech-to-text và chatbot tự động đặt lịch — hoàn toàn xa rời thực tế trang thiết bị trạm y tế nghèo nàn. | Gạt bỏ toàn bộ các ý hời hợt đó, tập trung vào bài toán thị giác lâm sàng, lọc lông tóc và tra cứu phác đồ. |
| Problem Card | Nhờ AI đóng vai chuyên gia phản biện điểm yếu của Problem Card #1. | Nhắc nhở rằng các chỉ số mô hình như IoU hay F1-score không phản ánh được giá trị thực tế tại phòng khám. | Không đưa ra được metric vận hành nào cụ thể cho bối cảnh khám chữa bệnh thực tế. | Tự đưa vào metric thời gian ca khám (< 4 phút) và quy định bắt buộc trích dẫn văn bản pháp quy Bộ Y tế. |
| Workflow | Nhờ AI hỗ trợ cấu trúc các bước chuẩn trong quy trình Systematic Literature Review (PRISMA). | Liệt kê nhanh các bước kinh điển từ query, screening, snowballing đến synthesis. | AI vẽ luồng thẳng tuột tự động hóa hoàn toàn, để AI tự đọc paper và tự tuyên bố research gap mà không cần con người. | Tự tay bổ sung các điểm nghẽn thực tế, đặt lằn ranh Human Boundary (duyệt inclusion và chốt gap) cùng nhánh Fallback khi dữ liệu mâu thuẫn. |
| Research | Dùng AI tra cứu nhanh thông số kỹ thuật của Semantic Scholar Graph API và Crossref REST API. | Tóm tắt nhanh các endpoint lấy metadata, citation count và DOI retrieval. | Tự bịa ra một số tính năng phân tích novelty tự động mà các API hiện tại chưa từng hỗ trợ (hallucination). | Tự mở link tài liệu chính thức của Semantic Scholar và Crossref để verify từng endpoint thực tế của hệ thống. |
| Problem Statement | Nhờ AI rà soát bản thảo v0 để chỉ ra các phát biểu mơ hồ hoặc giả định chưa được chứng minh. | Chỉ ra rằng việc tuyên bố "giúp tìm ra research gap mới" là quá rộng và không thể chứng minh tuyệt đối. | Đề xuất các metric viển vông như "độ chính xác phát hiện gap 98%". | Hạ tông bài toán xuống thành "candidate gaps có evidence và phản chứng", đồng thời siết metric theo tài nguyên khả thi (compute, data, time, skill). |
| Rule / Workflow / Agent | Hỏi AI ưu/nhược điểm khi dùng Autonomous Agent so với Workflow có kiểm soát cho bài toán nghiên cứu. | Phân tích rõ các nguy cơ của Agent: vòng lặp tìm kiếm vô tận (infinite loop), chi phí API cao và claim novelty ảo. | AI vẫn có xu hướng thiên vị khuyên nhóm thử làm Multi-agent system cho "đón đầu công nghệ". | Giữ vững lập trường chọn mức Workflow kết hợp Rule-based, ưu tiên tính minh bạch và khả năng kiểm chứng của con người. |
| Decision | Không dùng AI. | — | — | Nhóm tự thảo luận và chấm điểm 6 câu hỏi readiness, vì quyết định "Go" hay "Not Yet" phải xuất phát từ trách nhiệm và nhận thức rủi ro của con người. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Ban đầu khi bước vào buổi thảo luận nhóm, tôi mang theo 3 candidate problems về da liễu với tâm thế rất tự tin vì đó là những bài toán tôi trực tiếp quan sát khi đi thực địa phòng khám. Tuy nhiên, khi lắng nghe bài pitch của bạn Tuân về việc mất hơn 3 ngày ròng rã, lội qua 12 bước thủ công chỉ để tìm research gap cho đề tài nhận diện va chạm ô tô, tôi nhận ra bài toán Literature Review có tính cấp thiết và phù hợp với năng lực kiểm chứng của cả nhóm hơn nhiều. Trong quá trình bàn bạc, nhóm cũng từng bị cuốn vào bẫy solution-first khi có thành viên đòi xây dựng hẳn một con Autonomous Agent tự động search, tự đọc paper rồi tự kết luận đề tài mới cho 'ngầu'. Tôi đã dùng chính bài học e ngại AI hộp đen bên y tế để kéo nhóm lại: nếu để một con Agent tự do kết luận tính mới mà không có bằng chứng phản chứng thì nguy cơ hallucination sẽ làm hỏng toàn bộ hướng nghiên cứu của sinh viên. Dấu tay rõ nhất của tôi trong artifact cuối chính là việc kiên quyết đưa vào tầng Rule xác minh DOI qua Crossref và quy định bắt buộc phải có ít nhất một lượt search phản chứng (counter-search) trước khi đưa bất kỳ gap nào vào shortlist. Điều khó khăn nhất với cả nhóm khi viết Problem Statement v1 chính là lằn ranh Boundary — phải chấp nhận hạ mục tiêu xuống chỉ đề xuất 'candidate gaps' chứ AI không thể phán xét thay cho giảng viên hướng dẫn. Quyết định cuối cùng chọn 'Not Yet' thay vì 'Go' là một bài học đắt giá về sự trưởng thành: nhóm biết dũng cảm dừng lại để xây dựng benchmark và pilot nhỏ trên 50–100 paper thay vì vội vã đâm đầu vào code một hệ thống khi chưa có baseline định lượng vững chắc. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm thu thập log thời gian định lượng sớm hơn ngay từ khâu validation để không bị khựng lại ở bảng quyết định cuối cùng.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards (đã scan 10 problems ở phần 01)
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài (18 candidates → 4 clusters → 3 shortlist → 1 bài)
- [x] [15đ] Nhóm có workflow trước/sau (12 bước current → 11 bước future)
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ (chọn Not Yet có bằng chứng)
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

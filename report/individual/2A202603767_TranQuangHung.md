## 1. Thông tin học viên

- Họ tên: Trần Quang Hưng 
- MSSV: 2A202603767
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: G2
- Link repo nhóm: https://github.com/tqhungdl/K5-L3B-DAY02-G2-DiscoveryProblemFraming/

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đọc yêu cầu công việc, tôi muốn biết mục tiêu chính của những công việc cần làm mà không cần phải đọc toàn bộ yêu cầu công việc | Người làm việc | Mỗi tuần 5 tasks, mỗi task 30 phút |
| 2 | Tốn thời gian | Khi giao việc làm cho nhân viên mới, tôi muốn biết cách họ sẽ làm công việc được giao nhưng không có đủ thời gian để hỏi từng người một | Quản lý, teamlead | 10 nhân viên mới mỗi đợt tuyển, mỗi người cần 30-45 phút để hoàn thiện |
| 3 | Tốn thời gian | Khi hoàn thành công việc được giao, tôi muốn tổng hợp lại những thay đổi của team trong quá trình làm để đối chiếu với những ghi chú trong quá trình họp để đảm bảo công việc được hoàn thành đầy đủ | Quản lý | 30 phút mỗi lần cần đối chiếu, tính bằng tay từ công việc trước đã hoàn thành|
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi làm việc có nhiều công việc làm song song, dễ gây nhầm lẫn giữa các dự án khác nhau về mặt nội dụng, hạn xong việc, và nhân lực làm trong dự án đó | Quản lý, người làm việc | Xảy ra nhầm lẫn về nội dung trong cuộc họp, làm cuộc họp kéo dài thêm 30 phút để sửa nhầm lẫn |
| 5 | Lặp lại | Khi cần phải kiểm toán doanh thu cuối năm để khai báo thuế, tôi thường bỏ quên nhiều khoản chi tiêu nhỏ dẫn đến việc khai báo thuế bị sai | Chủ doanh nghiệp nhỏ, chủ cửa hàng bán lẻ | Gây phát sinh chi phí không cần thiết, đã gặp phải lỗi này vào kỳ khai báo trước |

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tóm tắt yêu cầu công việc (#1) | Vấn đề thực tiễn, có ảnh hưởng rõ rệt đến hiệu suất công việc | Vấn đề có nhiều cách giải quyết đơn giản hơn |
| 2 | Muốn biết cách nhân viên giải quyết yêu cầu công việc (#2) | Làm ảnh hưởng đến nhiều người, mất thời gian | Khó tiếp cận giải pháp hợp lý |
| 3 | Nhầm lẫn giữa nhiều dự án, công việc khác nhau (#4) | Gây ảnh hưởng đến nhiều người, ảnh hưởng nhiều đến công việc cần được làm | Phạm vi giải quyết rông |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi có yêu cầu công việc, tôi muốn có các bullet point ngắn gọn, để bắt đầu làm việc ngay mà không cần phải đọc yêu cầu nhiều lần |
| Actor | Người làm việc |
| Thời điểm / bối cảnh | Khi được giao việc |
| Quy trình hiện tại (3–7 bước) | 1. Nhận yêu cầu việc làm, 2. Đọc sơ lược qua yêu cầu, 3. Nghiên cứu về yêu cầu, 4. Lập ra bullet point các điểm quan trọng, 5. Bắt đầu làm việc |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3-4, mất 15-20 phút để giải quyết |
| Impact (nếu không giải thì sao) | Bắt đầu task được giao trễ 20 phút |
| Success metric (baseline → target) | Tổng thời gian kể từ lúc được giao task cho đến lúc bắt đầu làm giảm xuống dưới 15 phút |
| Phương án không dùng AI | Sử dụng template task cố định, có ghi thông tin chi tiết và thông tin quan trọng |
| Giả thuyết về AI (nếu có) | Sử dụng AI để tóm tắt nội dung công việc |
| Cảm nhận nhanh | Workflow |

```text
Hiện tại (30 phút)
1. Nhận task (5 phút) -> 2. Đọc sơ nội dung task (5 phút) -> 3. Nghiên cứu (15 phút)
-> 4. Lập bullet point (15 phút) -> 5. Bắt đầu task

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi giao việc cho nhân viên mới vào công ty, tôi muốn biết từng nhân viên sẽ giải quyết vấn đề được giao như thế nào, để hỗ trợ họ nếu cần thiết |
| Actor | Quản lý, teamlead |
| Thời điểm / bối cảnh | Khi giao việc cho nhân viên mới |
| Quy trình hiện tại (3–7 bước) | 1. Giao việc làm, 2. Hỏi nhân viên giải pháp của họ, 3. Giúp đỡ nhân viên mới, 4. Lặp lại cho mỗi nhân viên |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-3, mỗi lần hỏi và giúp đỡ mất khoảng 30 phút mỗi người |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian, không nắm bắt được công việc mỗi người |
| Success metric (baseline → target) | Giảm tổng thời gian hỗ trợ xuống dưới 10 phút mỗi người |
| Phương án không dùng AI | Yêu cầu nhân viên mới nêu hiểu biết và giải pháp cho công việc được giao |
| Giả thuyết về AI (nếu có) | Dùng AI để follow up với từng nhân viên |
| Cảm nhận nhanh | Rule|

```text
Hiện tại (35 phút mỗi người, 10 phút giao việc chung)
1. Giao task (10 phút) -> 2. Hỏi nhân viên (10 phút) -> 3. Giúp đỡ nhân viên (25 phút)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm nhiều dự án song song, tôi muốn biết rõ ràng nội dung giữa những dự án này, để tránh nhầm lẫn giữa nhiều dự án khác nhau |
| Actor | Quản lý |
| Thời điểm / bối cảnh | Khi làm nhiều dự án song song |
| Quy trình hiện tại (3–7 bước) | 1. Nhận task mới, 2. Họp tuyền truyền nội dung task, 3. Bắt đầu task, 4. Nhận một task khác, 5. Khi họp xảy ra nhầm lẫn giữa hai task được giao vì cùng một team |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, gây nhầm lẫn kéo dài cuộc họp thêm 30 phút |
| Impact (nếu không giải thì sao) | Mỗi cuộc họp có thêm task sẽ gây thêm nhầm lẫn làm mất nhiều thời gian |
| Success metric (baseline → target) | Hiện tượng nhầm lẫn các task cần được giảm thiểu |
| Phương án không dùng AI | Đề ra các bullet point rõ ràng với mỗi task khác nhau, cung cấp đầy đủ thông tin trước cuộc họp/đầu cuộc họp để hạn chế nhầm lẫn, sửa đổi nhầm lẫn sớm ngay khi phát hiện |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | Workflow|

```text
Hiện tại ()
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Vấn đề này xảy ra với nhiều người khá là thường xuyên
- Câu hỏi muốn nhóm phản biện: Làm sao để việc tóm tắt có thể làm nhanh hơn mà không dùng AI

### AI đã phản biện card #1 thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Viết bullet point là bottleneck chính | Đồng ý | Tính riêng lẻ thời gian làm từng việc |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Problem Card #1, #2 và #3 | Không được nhận |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Việc ghi chú có thể áp dụng sẵn template mà không cần dùng đến AI, thì tại sao vẫn cần phải dùng AI | Giúp đóng góp cho ý tưởng của bạn |
| Nhận phản biện | Câu hỏi tôi nhận được: Tại sao phải dùng đến một công cụ ngoài trong khi chatbot có thể làm quá tốt? | Tôi đã sửa gì: Thay đổi nhận xét giải pháp thành workflow |
| Gom cluster / cây OST | Cây OST | |
| Chọn candidate problem | Hỗ trợ team quyết định chọn thông qua đánh giá điểm shortlist | |
| Kiểm chứng / research | Hoàn thiện phần kiểm chứng | |
| Problem Statement | Viết problem statement v0 | |
| Mức can thiệp AI | Đánh giá và chốt mức can thiệp | |
| Quyết định | Thảo luận quyết định phương án Not Yet | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỏi thêm góc nhìn từ AI sau khi tự liệt kê vấn đề | AI giúp cho thêm một góc nhìn | Những ý tưởng AI đưa ra còn nông cạn | Yêu cầu AI đưa những vấn đề thực tiễn và sâu rộng hơn |
| CP2 Problem Card | Nhờ AI đóng vai PM hoài nghi để phản biện các card | Đánh giá giải pháp và phản biện chi tiết | Những đề xuất AI đưa ra còn quá rộng | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?** 
Có rất nhiều problem được đưa ra trên bề nổi nghe rất hay và có thể đào sâu hơn, nhưng trên thực chất chỉ cần sử dụng 1 hoặc 2 công cụ mới để giải quyết vấn đề

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, khi nhóm pitch vấn đề Ghi chú và Tóm tắt yêu cầu công việc, những vấn đề này nhóm đã cho rằng việc đưa mô hình AI vào để xử lý sẽ giải quyết vấn đề, tuy nhiên ý hiểu này các thành viên đã nhận ra có vấn đề và đã chọn một vấn đề khác thật sự cần giải quyết.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có, tôi pitch vấn đề dùng AI tóm tắt yêu cầu công việc và đã nhận lời phản biện "không thật sự cần xây dựng một model mới cho một vấn đề mà model AI hiện có đã có thể giải quyết được dễ dàng". Tôi đã ngẫm lại và thấy phản biện này hợp lý, đồng thời tôi nhận ra vấn đề này thực chất không có ảnh hưởng quá lớn đến actor.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Việc research khiến tôi nhận ra những vấn đề tôi đưa ra không phải là vấn đề lớn cấp bách cần xử lý trong môi trường làm việc, mà chỉ là những việc cần làm để hoàn thiện công việc.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất khi viết problem statement là những problem tôi đã đưa ra có tính phức tạp chưa đủ cao, làm quá trình viết problem statement bị lặp đi lặp lại, dẫn đến problem statement không được đa dạng.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại tôi sẽ thay đổi chủ đề những vấn đề tôi đề ra, để những vấn đề thực tiễn hơn, phức tạp hơn, và đề xuất được những vấn đề thật sự cần giải quyết. Tôi muốn phản biện nhóm mạnh hơn về mặt những công cụ khác đã tồn tại để giải quyết vấn đề.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Problem: Hành khách xe buýt vừa lỡ chuyến xe buýt và cần một tuyến đường khác để tiết kiệm thời gian. Quy trình: Hành khách xe buýt lỡ chuyến xe -> AI xem thời gian, vị trí hành khách và phân tích các tuyến đường -> AI tổng hợp thông tin so sánh và đưa cho hành khách -> Hành khách so sánh thời gian giữa mỗi tuyến đường AI cho -> Hành khách chọn chuyến đi mới. Metric: Cải thiện thời gian tìm kiếm, tra cứu và so sánh các tuyến xe khác nhau. Boundary: AI tổng hợp và tìm kiếm thông tin các tuyến xe buýt. Mức can thiệp AI: nếu AI không tìm được tuyến đường cho hành khách thì phải thông báo cho hành khách để họ xoay sở. Quyết định: Not yet vì còn cần phải thu thập dữ liệu thực tế trước khi đưa ra quyết định.

---

## 7. Tài liệu tham khảo

-

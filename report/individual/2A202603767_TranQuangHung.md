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
- Câu hỏi muốn nhóm phản biện: 

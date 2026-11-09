# Báo cáo cá nhân — 2A202603752_Nguyễn Tiến Đạt

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Tiến Đạt
- MSSV: 2A202603752
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: G2
- Link repo nhóm: https://github.com/tqhungdl/K5-L3B-DAY02-G2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story                                                                                                                                                                               | Ai chịu ảnh hưởng?     | Dấu hiệu thật                                                                                                                             |
| --: | --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Tốn thời gian                     | Khi thực hiện ghi chú cá nhân nhanh, tôi muốn ghi chú được nhất quán và liên kết được với các ghi chú liên quan, để không phải format, sửa và nối chúng thủ công.                       | Tôi/người dùng cá nhân | Việc ghi chú thực hiện nhanh nhưng quá trình format, sửa và liên kết các ghi chú với nhau tiêu tốn 30 phút mỗi ngày hoặc 2 tiếng mỗi tuần |
|   2 | Tốn thời gian                     | Khi theo dõi chi tiêu từ nhiều ứng dụng và hóa đơn đã chụp, tôi muốn biết đầy đủ các giao dịch và khoản đã chi, để kiểm soát ngân sách mà không phải dò lại thủ công.                   | Người dùng cá nhân     | Tần suất nhập liệu thấp dần, 30% giao dịch bị bỏ quên, tiêu tốn 10 phút mỗi ngày để tra soát và nhập.                                     |
|   3 | Lặp lại                           | Khi bắt đầu làm một bài tập, tôi muốn nắm rõ hạn nộp và các yêu cầu nằm rải rác trong LMS, chat và tài liệu môn học, để không bỏ sót đầu việc hoặc nộp sai định dạng.                   | Tôi/người học          | Với mỗi một bài tập, phải mở 4-5 lần, phải dò tài liệu hướng dẫn liên tục tiêu tốn khoảng 20 phút mỗi ngày.                               |
|   4 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn một chủ đề có nội dung nằm trong slide, ghi chú và tài liệu đọc, tôi muốn xác định được các ý liên quan với nhau, để không phải đọc lại nhiều lần và bỏ sót kiến thức trọng tâm. | Tôi/người học          | Mỗi buổi ôn phải mở 3–5 nguồn, mất khoảng 30–45 phút để đối chiếu và thường tra lại cùng một khái niệm 2–3 lầ                             |
|   5 | Pain từ người khác                | Khi làm bài code nhóm và thành viên hỏi tiến độ hoặc phần việc còn thiếu, tôi muốn nắm được ai đang phụ trách việc nào, để nhóm không phải hỏi đi hỏi lại hoặc bỏ sót đầu việc.         | Tôi và thành viên nhóm | Trong tuần phải hỏi đi kiểm tra tiến độ thủ công trên repo đối chiếu tin nhắn, kiểm tra tài liệu chia công việc tiêu tốn 30 phút mỗi lần. |
|   6 |                                   |                                                                                                                                                                                         |                        |                                                                                                                                           |
|   7 |                                   |                                                                                                                                                                                         |                        |                                                                                                                                           |
|   8 |                                   |                                                                                                                                                                                         |                        |                                                                                                                                           |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                             | Vì sao chọn                                                                                                   | Điều còn chưa chắc                                                                                        |
| ---: | ----------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
|    1 | Format và liên kết ghi chú cá nhân  | Tiêu tốn nhiều thời gian cho việc chỉnh sửa, liên kết nội dung, vốn là lợi thế của AI                         | Kiến trúc của công cụ, tránh việc AI phải đọc quá nhiều nội dung thừa ngoài ghi chú mới liên kết hiệu quả |
|    2 | Theo dõi tiến độ trên repo          | Tài liệu sẵn có, dễ đo lường hiệu suất, báo cáo vấn đề, kiểm tra bằng cách đọc code tốn nhiều thời gian.      | Cách setup để có thể đo lường tự động mỗi khi commit, tránh việc AI đọc toàn bộ code mỗi khi cần truy vấn |
|    3 | Theo dõi chi tiêu từ nhiều ứng dụng | Việc phải nhập thủ công tiêu tốn nhiều thời gian, bất tiện trong khi thông tin đã sẵn có dưới nhiều hình thức | Các app thanh toán có cho phép xem nội dung bằng API hay không                                            |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                          |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi thực hiện ghi chú cá nhân nhanh, tôi muốn ghi chú được nhất quán và liên kết được với các ghi chú liên quan, để không phải format, sửa và nối chúng thủ công. |
| Actor                                     | Người dùng                                                                                                                                                        |
| Thời điểm / bối cảnh                      | Ghi chú vào mọi thời điểm trong ngày, tổng hợp vào buổi tối hoặc cuối tuần                                                                                        |
| Quy trình hiện tại (3–7 bước)             | 1. Người dùng ghi chú nhanh 2. Đọc lại ghi chú và chỉnh sửa, sửa lỗi theo template 3. Liên kết với các ghi chú khác bằng từ khóa, thư mục, ...                    |
| Bottleneck (bước nào, mất bao nhiêu phút) | Đọc, chỉnh sửa và ghi chú mất khoảng 10 phút cho ghi chú 500 chữ                                                                                                  |
| Impact (nếu không giải thì sao)           | Mất khoảng 30 phút mỗi ngày nếu có khoảng 2000 chữ.                                                                                                               |
| Success metric (baseline → target)        | Thời gian điều chỉnh của người dùng giảm từ 30 phút xuống còn dưới 5 phút mỗi ngày, chủ yếu dành cho việc đọc.                                                    |
| Phương án không dùng AI                   | Sử dụng công cụ ghi chú như Obsidian, Notion, tạo sẵn template và điền theo, tự đọc các tài liệu khác để liên kết từ khóa hiệu quả.                               |
| Giả thuyết về AI (nếu có)                 | Tạo sẵn tempalte với mô tả cách dùng, AI đọc ghi chú và lựa chọn format theo template phù hợp, tìm hoặc tạo mới từ khóa để liên kết.                              |
| Cảm nhận nhanh                            | Agent                                                                                                                                                             |

Quy trình nháp hiện tại:

```text
[1 Ghi chú nhanh: 100 chữ/5 phút] -> [2 Chỉnh sửa theo template: 10'] <- BOTTLENECK -> [3 Liên kết bằng từ khóa: 5 phút]
```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                             |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story                                 | Khi cần cập nhật tiến độ bài code nhóm, tôi muốn đối chiếu được phần việc đã làm với người phụ trách, để nhóm không phải hỏi đi hỏi lại hoặc bỏ sót đầu việc.                        |
| Actor                                     | Tôi và thành viên nhóm                                                                                                                                                               |
| Thời điểm / bối cảnh                      | Khi cần rà soát tiến độ trong tuần hoặc trước khi cập nhật cho nhóm                                                                                                                  |
| Quy trình hiện tại (3–7 bước)             | 1. Mở repo để xem commit và phần việc đã làm · 2. Mở tin nhắn và tài liệu chia việc · 3. Đối chiếu người phụ trách với tiến độ trên repo · 4. Hỏi thành viên nếu còn thiếu thông tin |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đối chiếu repo, tin nhắn và tài liệu chia việc thủ công mất khoảng 30 phút mỗi lần kiểm tra                                                                                  |
| Impact (nếu không giải thì sao)           | Nhóm phải hỏi tiến độ nhiều lần và có thể bỏ sót đầu việc                                                                                                                            |
| Success metric (baseline → target)        | Thời gian mỗi lần kiểm tra giảm từ khoảng 30 phút xuống dưới 10 phút; ghi thời gian cho từng lượt kiểm tra trong 2 tuần                                                              |
| Phương án không dùng AI                   | Dùng một bảng task có người phụ trách, trạng thái và link PR/commit; mỗi thành viên cập nhật ngắn sau khi làm                                                                        |
| Giả thuyết về AI (nếu có)                 | AI đọc task và metadata của commit/PR để tạo nháp tiến độ, chỉ ra mục chưa rõ; thành viên xác nhận trước khi chia sẻ, không cần đọc toàn bộ code                                     |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                             |

Quy trình nháp hiện tại:

```text
[1 Mở repo, tin nhắn và tài liệu chia việc] -> [2 Đối chiếu người phụ trách với tiến độ: ~30'/lượt] <- BOTTLENECK -> [3 Hỏi thành viên để xác nhận phần còn thiếu]
```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                 |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story                                 | Khi theo dõi chi tiêu từ nhiều ứng dụng và hóa đơn đã chụp, tôi muốn biết đầy đủ các giao dịch và khoản đã chi, để kiểm soát ngân sách mà không phải dò lại thủ công.    |
| Actor                                     | Người dùng cá nhân                                                                                                                                                       |
| Thời điểm / bối cảnh                      | Sau khi thanh toán và khi rà soát chi tiêu cuối ngày                                                                                                                     |
| Quy trình hiện tại (3–7 bước)             | 1. Thanh toán qua các ứng dụng hoặc nhận hóa đơn · 2. Lưu hóa đơn bằng ảnh · 3. Mở lại ứng dụng và ảnh để dò giao dịch · 4. Nhập, phân loại và đối chiếu khoản chi       |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4, dò và nhập liệu thủ công mất khoảng 10 phút mỗi ngày; khoảng 30% giao dịch bị bỏ quên                                                                          |
| Impact (nếu không giải thì sao)           | Danh sách chi tiêu không đầy đủ nên khó biết ngân sách đã dùng bao nhiêu                                                                                                 |
| Success metric (baseline → target)        | Thời gian nhập và tra soát từ khoảng 10 phút/ngày xuống dưới 5 phút/ngày; giao dịch bị bỏ quên từ khoảng 30% xuống dưới 5%, đối chiếu với hóa đơn và sao kê trong 2 tuần |
| Phương án không dùng AI                   | Ghi chi tiêu vào một bảng tính ngay sau khi mua; dùng sao kê hoặc lịch sử giao dịch để kiểm tra lại                                                                      |
| Giả thuyết về AI (nếu có)                 | AI đọc ảnh hóa đơn để đề xuất số tiền, ngày và nhóm chi tiêu; người dùng kiểm tra và xác nhận trước khi lưu                                                              |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                 |

Quy trình nháp hiện tại:

```text
[1 Thanh toán qua nhiều ứng dụng, lưu hóa đơn] -> [2 Dò giao dịch và hóa đơn: ~10'/ngày] <- BOTTLENECK -> [3 Nhập, phân loại và đối chiếu khoản chi]
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Nhu cầu của bản thân, muốn nghiên cứu bài toán về kết nối từ khóa tự động hiệu quả.
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                | Đồng ý?         | Đã sửa gì                                                                             |
| --------------------------------------------------------------------------------- | --------------- | ------------------------------------------------------------------------------------- |
| Actor quá chung chung, chưa xác định nhóm người dùng cụ thể.                      | Có              | Sửa "người dùng" thành "nhóm người dùng thường xuyên ghi chú"                         |
| Quy trình hiện tại chưa được kiểm chứng bằng hành vi thực tế.                     | Đồng ý một phần | Hầu như những người có thói quen ghi chú đều đọc lại (trên internet)                  |
| Bottleneck gộp nhiều bước, chưa xác định bước tốn thời gian nhất.                 | Đồng ý một phần | Cần đo lường cụ thể hơn, thói quen ghi chú có thể khác nhau                           |
| Metric chỉ đo thời gian, chưa đo chất lượng ghi chú và độ chính xác của liên kết. | Không           |                                                                                       |
| Chưa chứng minh template và rule-based không giải quyết được vấn đề.              | Không           | Phục vụ cho những người ghi chú tốc độ cao, giảm bớt tác vụ sẽ giúp tập trung tốt hơn |
| Đề xuất AI Agent quá sớm khi chưa xác thực vấn đề và nhu cầu tự động hóa.         | Không           | Cộng đồng có nhu cầu từ trước khi AI phổ biến trên các diễn đàn                       |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       |                        |                   |                            |                                     |
| CP2 Problem Card               |                        |                   |                            |                                     |
| CP4 Research                   |                        |                   |                            |                                     |
| CP5 Quy trình                  |                        |                   |                            |                                     |
| CP5–6 Problem Statement        |                        |                   |                            |                                     |
| CP6 Mức can thiệp / quyết định |                        |                   |                            |                                     |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-

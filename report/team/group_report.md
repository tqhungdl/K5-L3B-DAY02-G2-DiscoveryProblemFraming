# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: G2
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Hưng | Tóm tắt yêu cầu công việc | Người làm việc | Tự bản thân tóm tắt lâu | "Có cần thiết phải tự thân tóm tắt không nếu dùng AI tóm tắt được (Đạt) |
| 2 | Hưng | Muốn biết cách nhân viên giải quyết yêu cầu công việc | Quản lý | Hỏi nhiều người |  |
| 3 | Hưng | Nhầm lẫn giữa nhiều dự án, công việc khác nhau | Quản lý, người làm việc | Nhiều dự án giống nhau dễ gây nhầm lẫn | |
| 4 | Đạt | Khi ghi chú nhanh, tôi muốn ghi chú nhất quán và liên kết được với ghi chú liên quan, để không phải format, sửa và nối thủ công | Người dùng cá nhân | Chỉnh sửa khoảng 10 phút cho 500 chữ | Tại sao không sử dụng sẵn các template và nhập vào? (Hưng) |
| 5 | Đạt | Khi rà soát tiến độ bài code nhóm, tôi muốn đối chiếu phần việc đã làm với người phụ trách, để tránh hỏi lại hoặc bỏ sót đầu việc | Tôi và thành viên nhóm | Đối chiếu repo, tin nhắn và tài liệu chia việc mất khoảng 30 phút/lượt | Tại sao không để thành viên tự báo cáo và chỉ xem xét khi gần deadline khi số lượng thành viên nhỏ? (Hải) |
| 6 | Đạt | Khi theo dõi chi tiêu từ nhiều ứng dụng và hóa đơn, tôi muốn biết đầy đủ các khoản đã chi, để kiểm soát ngân sách | Người dùng cá nhân | Tra soát và nhập liệu khoảng 10 phút/ngày; khoảng 30% giao dịch bị bỏ quên | Làm sao để các app có thể chia sẻ thông tin? (Hưng) |    
| 7 | Hải | Khi gặp ùn tắc lúc đang đi bằng phương tiện cá nhân, tôi muốn so sánh đi tiếp với đổi tuyến để chọn đường phù hợp trước khi qua điểm rẽ. | Người lái xe máy hoặc ô tô cá nhân | Mất thời gian so sánh giờ đến dự kiến và kiểm tra tuyến thay thế có phù hợp với phương tiện hay không. |  |
| 8 | Hải | Khi lỡ chuyến xe buýt vào giờ cao điểm, tôi muốn biết phải chờ bao lâu và có cách đi nào khác để chọn phương án phù hợp với giờ cần đến. | Hành khách vừa lỡ chuyến xe buýt | Phải tự tính thời gian đi bộ, chờ xe, ngồi xe và chuyển tuyến để biết phương án nào còn kịp bắt và đến đích lúc nào. |  |
| 9 | Hải | Khi đang xếp hàng trước một nút giao ùn tắc, tôi muốn ước lượng còn bao lâu mới qua được để cập nhật giờ đến và báo trước nếu có thể trễ. | Người đi xe máy hoặc ô tô đang xếp hàng trước nút giao | Khó ước lượng thời gian còn lại vì không nhìn hết hàng xe và mỗi lượt xe tiến được một đoạn khác nhau. |  |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
| ------- | ------------- | ------------- |
| A — Công việc | #1, #2, #3, #5 | Tổng hợp và theo dõi công việc từ nhiều nguồn. |
| B — Thông tin cá nhân | #4, #6 | Ghi nhận và tổng hợp dữ liệu cá nhân. |
| C — Di chuyển | #7, #8, #9 | So sánh và cập nhật phương án di chuyển. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME:
├── Opportunity A:
├── Opportunity B:
└── Opportunity C:
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
| --------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | ---: |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

**Phạm vi của nhóm G2:** Hành khách vừa lỡ chuyến xe buýt vào giờ cao điểm và cần quyết định nên chờ chuyến kế tiếp hay đổi lộ trình để kịp giờ đến.

### 3.1. Assumption Map

Điểm bằng chứng phản ánh thông tin có trước phỏng vấn. Điểm 1 là chưa có dữ liệu trực tiếp, điểm 2 là có một ghi nhận riêng lẻ hoặc thông tin gián tiếp, điểm 3 là có tài liệu về tính năng liên quan nhưng vẫn cần thử trong tình huống cụ thể.

|   # | Giả định                                                                                                                   | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 | Khi lỡ xe buýt và có giờ cần đến, hành khách thực sự cân nhắc giữa chờ chuyến sau và đổi lộ trình.                         | Value                                              |                5 |                      2 | Có                |
|   2 | Phần tốn thời gian nhất là so sánh giờ đến đích của các phương án vì phải tính cả đi bộ, chờ xe và chuyển tuyến.           | Usability                                          |                5 |                      1 | Có                |
|   3 | Hành khách có thể chọn nhanh bằng ứng dụng quen thuộc nếu thông tin chuyến sau rõ và vẫn kịp giờ đến đích.                 | Value                                              |                5 |                      2 | Có                |
|   4 | Tại điểm dừng đang xét, có thể tra đủ giờ xe, thời gian đi bộ và thông tin chuyển tuyến để biết phương án nào còn kịp bắt. | Feasibility                                        |                5 |                      3 | Có                |
|   5 | Hành khách có thể bỏ phương án dự kiến đến sớm hơn nếu phải đi bộ quá xa hoặc đổi tuyến quá nhiều.                         | Usability                                          |                4 |                      1 | Sau               |
|   6 | Nhóm có thể lặp lại việc tra cứu bằng các nguồn hiện có với công sức cập nhật chấp nhận được trong phạm vi thử nghiệm.     | Viability                                          |                3 |                      1 | Sau               |

**Giả định nhóm kiểm chứng trong buổi này:** Ba kịch bản mô phỏng tập trung vào giả định **1, 2 và 3**. Giả định **4** cần kiểm tra riêng bằng cách mở ứng dụng tại điểm dừng, đúng chiều đi và đúng khung giờ thử nghiệm.

### 3.2. Kiểm chứng

**Cách đã dùng trong bản minh họa:** Phỏng vấn bán cấu trúc mô phỏng. Thời gian ra quyết định tính từ lúc hành khách nhận ra đã lỡ chuyến đến lúc chốt cách đi tiếp. Thời gian đứng chờ xe được ghi riêng.

#### Interview P1

| Trường                                            | Nội dung                                                                                                                                                          |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | P1 — Sinh viên, thường đi xe buýt đến trường.                                                                                                                     |
| Câu nói đáng nhớ nhất (lời thoại mô phỏng)        | “Em thấy có tuyến khác, nhưng phải cộng thêm thời gian đi bộ và đổi xe mới biết có đáng chuyển không.”                                                            |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | P1 lỡ xe trên đường đi học buổi sáng. Chuyến kế tiếp theo lịch còn khoảng 15 phút. Tuyến thay thế yêu cầu đi sang trạm khác và đổi xe một lần.                    |
| Hiện đang xử lý bằng cách nào (workaround)?       | Tra chuyến kế tiếp, mở bản đồ để tìm tuyến khác, rồi tự so thời gian đi bộ, chờ và đổi xe. Cuối cùng chọn chờ vì tuyến thay thế dự kiến chỉ đến sớm hơn vài phút. |
| Mất bao lâu, bao lần?                             | Khoảng **6 phút để chốt** trong một ca mô phỏng. Mốc 15 phút là thời gian chờ theo lịch tại lúc bắt đầu tra cứu.                                                  |
| Insight / opportunity rút ra                      | Khi hai phương án có giờ đến gần nhau, hành khách cần thấy chênh lệch thời gian cùng số lần đổi xe để quyết định.                                                 |

#### Interview P2

| Trường                                            | Nội dung                                                                                                                                            |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | P2 — Nhân viên văn phòng, đi một tuyến quen thuộc vào buổi sáng.                                                                                    |
| Câu nói đáng nhớ nhất (lời thoại mô phỏng)        | “App báo chuyến sau sắp tới, giờ đến dự kiến vẫn kịp nên tôi đứng chờ luôn.”                                                                        |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | P2 lỡ xe trên đường đi làm. Ứng dụng hiển thị chuyến kế tiếp dự kiến đến trạm sau khoảng 5 phút và giờ đến nơi vẫn phù hợp.                         |
| Hiện đang xử lý bằng cách nào (workaround)?       | Mở ứng dụng quen thuộc, kiểm tra đúng chiều và giờ đến dự kiến, rồi chọn chờ tại trạm.                                                              |
| Mất bao lâu, bao lần?                             | Khoảng **2 phút để chốt** trong một ca mô phỏng.                                                                                                    |
| Insight / opportunity rút ra                      | Đây là ca phản bác giả định rằng lỡ xe luôn gây khó khăn. Khi thông tin chuyến sau rõ và vẫn kịp giờ, ứng dụng hiện tại có thể đủ để ra quyết định. |

#### Interview P3

| Trường                                            | Nội dung                                                                                                                                                          |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Người được hỏi (vai trò, không ghi tên thật)      | P3 — Người đi làm theo ca, cần đến đúng giờ giao ca.                                                                                                              |
| Câu nói đáng nhớ nhất (lời thoại mô phỏng)        | “Tuyến kia nhìn nhanh hơn, nhưng xe còn 4 phút tới trạm mà tôi phải đi bộ 7 phút mới tới.”                                                                        |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Sau khi lỡ xe, P3 thấy một tuyến thay thế dự kiến đến đích sớm hơn. Khi mở chỉ đường đến điểm đón, P3 phát hiện mình không thể tới trạm trước giờ xe dự kiến đến. |
| Hiện đang xử lý bằng cách nào (workaround)?       | Kiểm tra thời gian đi bộ tới trạm, loại chuyến không kịp bắt, rồi chọn một lộ trình khác có một lần chuyển tuyến.                                                 |
| Mất bao lâu, bao lần?                             | Khoảng **5 phút để chốt** trong một ca mô phỏng. P3 kiểm tra hai phương án thay thế.                                                                              |
| Insight / opportunity rút ra                      | Kiểm tra có kịp tới điểm đón và chuyển tuyến trước khi so sánh giờ đến đích.                                                                                      |

**Tổng hợp**

| Nguồn                      | Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                                    | Tín hiệu phản bác                                                                                                                                        |
| -------------------------- | ----------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Phỏng vấn                  |        3 kịch bản | P1 và P3 minh họa hai điểm khó: tính giờ đến cho cả hành trình và phát hiện chuyến thay thế không kịp bắt.                                                           | P2 chốt trong khoảng 2 phút bằng ứng dụng quen thuộc khi giờ chuyến sau rõ và vẫn kịp đến.                                                               |
| Research tài liệu sản phẩm |         3 công cụ | Google Maps cho biết một số điểm dừng hiển thị giờ theo lịch và một số có giờ cập nhật theo thời gian thực. Nguồn giờ ảnh hưởng đến cách đánh giá phương án sát giờ. | Các công cụ đã hỗ trợ nhiều thao tác tra tuyến, tra giờ hoặc theo dõi xe. Cần quan sát người dùng để biết bước nào vẫn gây khó khi dùng các công cụ này. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- **Ban đầu:** Hành khách lỡ chuyến xe buýt vào giờ cao điểm khó biết chuyến tiếp theo và các lựa chọn khác.
- **Bản thu hẹp đề xuất:** Khi vừa lỡ xe buýt vào giờ cao điểm, có giờ cần đến và phải cân nhắc nhiều cách đi, hành khách mất thời gian xác định **phương án nào còn kịp bắt và dự kiến đến đích lúc nào**, nhất là khi phải đi bộ sang trạm khác hoặc chuyển tuyến.
- **Lý do thu hẹp:** P2 minh họa trường hợp tra một chuyến là đủ. P3 minh họa trường hợp giờ đến dự kiến chỉ có ích khi hành khách kịp tới điểm đón. Khi kiểm chứng thực tế, đo **số phút từ lúc lỡ xe đến lúc chốt phương án khả thi** và ghi riêng ca thiếu thông tin để chốt. Các mốc 6, 2 và 5 phút là số liệu mô phỏng.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link                                                                                                         | Giải bước nào trong quy trình?                                                | Điểm mạnh                                                                                         | Khoảng trống / rủi ro                                                                                               | Bài học cho nhóm                                                                                               |
| ------------------------ | ------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Google Maps              | [Tài liệu tra giờ tàu và xe buýt](https://support.google.com/maps/answer/6142130?hl=en)                      | Tìm đường bằng phương tiện công cộng và tra giờ khởi hành.                    | Cho xem các lựa chọn tuyến và giờ đi. Một số điểm dừng có thông tin cập nhật theo thời gian thực. | Tùy điểm dừng, giờ hiển thị có thể là giờ theo lịch. Cần kiểm tra nguồn giờ khi đánh giá lượt chuyển tuyến sát giờ. | Phân biệt **giờ theo lịch** và **giờ cập nhật** khi so sánh phương án.                                         |
| BusMap Hà Nội            | [Trang ứng dụng trên Google Play](https://play.google.com/store/apps/details?hl=vi&id=com.t7.busmaphn)       | Tra tuyến, tìm hành trình kết hợp xe buýt và metro, xem giờ chờ và vị trí xe. | Tập hợp nhiều thông tin phục vụ hành trình công cộng trong cùng một ứng dụng.                     | Cần thử tại điểm dừng và khung giờ đã chọn để biết dữ liệu có đủ và mất bao lâu để so hai phương án.                | Dùng ứng dụng quen thuộc làm mốc so sánh và đo cả thời gian tra cứu lẫn thời gian chốt.                        |
| VinBus trên Xanh SM      | [Thông báo tính năng của VinBus](https://vinbus.vn/vi/thong-bao-ra-mat-dich-vu-vinbus-tren-ung-dung-xanh-sm) | Tra lịch, tìm trạm, chỉ đường tới trạm và theo dõi xe VinBus.                 | Có thể xem thông tin chuyến VinBus và đường đi tới điểm đón.                                      | Cần kiểm tra khả năng đối chiếu với tuyến do đơn vị khác vận hành trong cùng tình huống.                            | So **giờ hành khách có thể tới trạm** với **giờ xe dự kiến tới trạm** trước khi đánh dấu phương án là khả thi. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
|    1 |       |       |        |                      |         |
|    2 |       |       |        |                      |         |
|    3 |       |       |        |                      |         |
|    4 |       |       |        |                      |         |
|    5 |       |       |        |                      |         |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |       |               |         |
| Tổng thời gian       |       |               |         |
| Số bước thủ công     |       |               |         |
| Bottleneck chính     |       |               |         |
| Rủi ro mới phát sinh |       |               |         |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-

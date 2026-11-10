# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: G2
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi lỡ chuyến xe buýt vào giờ cao điểm, tôi muốn biết phải chờ bao lâu và có cách đi nào khác để chọn phương án phù hợp với giờ cần đến.
- Quyết định cuối: Not Yet

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

### 2.2. Cluster

| Cluster               | Các candidate  | Pattern chung                                  |
| --------------------- | -------------- | ---------------------------------------------- |
| A — Công việc         | #1, #2, #3, #5 | Tổng hợp và theo dõi công việc từ nhiều nguồn. |
| B — Thông tin cá nhân | #4, #6         | Ghi nhận và tổng hợp dữ liệu cá nhân.          |
| C — Di chuyển         | #7, #8, #9     | So sánh và cập nhật phương án di chuyển.       |

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

┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌───────────────────┐     ┌──────────────┐
│ Bước 1       │     │ Bước 2       │     │ Bước 3       │     │ Bước 4            │     │ Bước 5       │
│ Hành khách   │     │ Hành khách   │     │ Hành khách   │     │ Hành khách        │     │ Hành khách   │
│ trễ xe buýt  │ ──→ │ kiểm tra thời│ ──→ │ tìm tuyến    │ ──→ │ so sánh thời      │ ──→ │ chọn chuyến  │
│              │     │ gian chuyến  |     | thay thế     |     | gian và chi       |     │ đi mới       │
|              |     │ tiếp theo    │     |              │     │ phí của các tuyến │     |              |
└──────────────┘     └──────────────┘     └──────────────┘     └───────────────────┘     └──────────────┘ 

```

| Bước | Actor      | Input                                     | Output                     | Thời gian / tần suất | Ghi chú                    |
| ---: | ---------- | ----------------------------------------- | -------------------------- | -------------------- | -------------------------- |
|    1 | Hành khách | Thời gian và vị trí hiện tại              | Xác định đã lỡ xe          | 0,5 phút             | Phát sinh khi lỡ chuyến    |
|    2 | Hành khách | Số tuyến, lịch trình xe                   | Thời gian chờ dự kiến      | 1–2 phút             | Có thể có dao động lớn hơn |
|    3 | Hành khách | Điểm đến, bản đồ, tuyến xe khác           | Danh sách phương án        | 2–3 phút             |                            |
|    4 | Hành khách | Thời gian, chi phí, tình trạng giao thông | Phương án được ưu tiên     | 2–4 phút             |                            |
|    5 | Hành khách | Đã chọn phương án                         | Bắt đầu chờ hoặc di chuyển | 0,5 phút             |                            |

**Bottleneck chính: Bước 4**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌───────────────────┐     ┌──────────────┐
│ Bước 1       │     │ Bước 2       │     │ Bước 3       │     │ Bước 4            │     │ Bước 5       │
│ Hành khách   │     │ 🔵 AI phân tích │  | 🔵 AI cho   │     │ Hành khách        │     │ Hành khách   │
│ trễ xe buýt  │ ──→ │ các chuyến xe│ ──→ │ gợi ý tuyến  │ ──→ │ xem tuyến đường   │ ──→ │ chọn chuyến  │
│              │     │ và thời gian |     | đường mới    |     | được đề xuất      |     │ đi mới       │
|              |     │ mỗi chuyến   │     |              │     │ và chọn tùy ý     │     |              |
└──────────────┘     └──────────────┘     └──────────────┘     └───────────────────┘     └──────────────┘
                                                │
                                                ▼
                                          ↩️ Fallback:
                                          Nếu AI không tìm
                                          được tuyến đường
                                          thì sẽ thông báo 
                                          cho người dùng biết

```

### 4.3. Before / after

| Chỉ số               |                                  Trước |                                                         Sau (kỳ vọng) | Ghi chú                                  |
| -------------------- | -------------------------------------: | --------------------------------------------------------------------: | ---------------------------------------- |
| Số bước              |                                      5 |                                                                     5 | Giữ số bước nhưng giảm thao tác thủ công |
| Tổng thời gian       |                              7-10 phút |                                                                2 phút | Tính từ bước đầu tiên đến bước cuối cùng |
| Số bước thủ công     |                                      5 |                                                                     3 |                                          |
| Bottleneck chính     | Tìm kiếm và tự so sánh nhiều phương án |                            Phụ thuộc độ chính xác, độ mới của dữ liệu |                                          |
| Rủi ro mới phát sinh |            Đến muộn do quyết định chậm | AI đề xuất sai, ETA thiếu chính xác, dữ liệu giao thông chậm cập nhật |                                          |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung                                                                                                                                                                                          |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                                                  | Hành khách thường xuyên sử dụng xe buýt                                                                                                                                                           |
| **Quy trình**                                                              | 1. Hành khách vừa lỡ chuyến xe buýt, 2. Hành khách kiểm tra thời gian chuyến tiếp theo, 3. Hành khách tìm kiếm tuyến thay thế, 4. Hành khách so sánh thời gian và chi phí của các tuyến khác nhau |
| **Bottleneck**                                                             | Bước 3-4, mất khoảng 7-10 phút                                                                                                                                                                    |
| **Impact**                                                                 | Thời gian đưa ra quyết định có thể làm hành khách lỡ chuyến tối ưu tiếp theo                                                                                                                      |
| **Success Metric** (baseline → target, cách đo)                            | Giảm tổng thời gian từ lúc phát hiện lỡ xe buýt xuống còn 2 phút                                                                                                                                  |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI tổng hợp, so sánh và đề nghị thông tin các tuyến xe buýt, khi dữ liệu thiếu thì cần thông báo cho người dùng để họ tự quyết định                                                               |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ mơ hồ thấp, độ phức tạp cao

Vì sao:

- Độ mơ hồ thấp: Có các tiêu chí cố định: hành khách có kịp tới điểm đón không, có kịp chuyển tuyến không, giờ đến dự kiến có trước giờ cần đến không. Các lựa chọn có thể được so sánh theo thời gian, chi phí và số lần chuyển tuyến.
- Độ phức tạp cao: Việc đánh giá một hành trình cần kết hợp nhiều bước phụ thuộc nhau: đi bộ tới trạm → chờ xe → đi xe → chuyển tuyến nếu có → đi bộ tới đích.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm                           | Đủ khi nào                                               | Rủi ro                                  | Chọn?                        |
| ------------------------- | ---------------------------------------------------- | -------------------------------------------------------- | --------------------------------------- | ---------------------------- |
| **No AI** (sửa quy trình) | Ứng dụng có sẵn + checklist so sánh                  | Ít phương án, thông tin đủ rõ                            | Vẫn phải tự tính và đối chiếu các chặng | Dùng khi tra cứu đã đủ nhanh |
| **Rule**                  | Lọc chuyến bắt kịp → tính giờ đến → xếp theo ưu tiên | Có hành trình hợp lệ, dữ liệu đủ mới, tiêu chí rõ        | Dữ liệu cũ hoặc thiếu làm kết quả sai   | **Chọn để kiểm chứng**       |
| **Workflow**              | Rule tính/lọc → AI giải thích → người dùng chọn      | Cần diễn giải yêu cầu và lựa chọn bằng ngôn ngữ tự nhiên | AI diễn giải sai, thêm độ trễ           | Chưa cần                     |
| **Agent**                 | AI tự tìm nguồn, chọn công cụ, tìm thêm hành trình   | Khi bước tra cứu tiếp theo không định trước được         | Khó kiểm soát nguồn và thời gian xử lý  | Không chọn                   |

**Mức chọn:** Rule.

**Vì sao không chọn mức đơn giản hơn:** Với nhiều hành trình, checklist vẫn để hành khách tự cộng thời gian và kiểm tra từng lần chuyển tuyến; Rule có thể xử lý phần này bằng điều kiện cố định. Dù vậy, khó có thể đảm bảo danh sách hành trình hợp lệ và dữ liệu thời gian đủ tin cậy. Nhóm xem xét thêm cho người dùng việc vote xe có đúng giờ không để có thể cải thiện dần.

### 6.3. AI Canvas rút gọn

**Không áp dụng AI Canvas vì nhóm chọn Rule.** Trong phạm vi các hành trình đã có dữ liệu, việc kiểm tra bắt kịp chuyến, tính giờ đến và so sánh theo ưu tiên có thể thực hiện bằng công thức, điều kiện cố định; chưa cần AI dự đoán hoặc tạo nội dung. Giờ xe dự kiến được lấy từ nguồn đầu vào, còn tính đầy đủ và độ mới của dữ liệu cần được kiểm chứng riêng. Nếu dữ liệu sai thì AI không giúp gì hơn. AI có thể đóng vai trò như chatbot trả kết quả cho người dùng thay vì phải tự tìm kiếm, nhưng đó lại là bài toán khác, giờ nghĩ ra hơi muộn.

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                                                                                                                                                                                                                                                              |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                       | Hành khách vừa lỡ xe buýt giờ cao điểm, có giờ cần đến và phải cân nhắc chờ chuyến sau hoặc đổi lộ trình.                                                                                                                                                             |
| **Quy trình**                                   | Nhận ra lỡ xe → tra các hành trình → kiểm tra bắt kịp, giờ đến và chi phí → so sánh → chốt cách đi.                                                                                                                                                                   |
| **Bottleneck**                                  | Bước so sánh: tự đối chiếu thời gian đi bộ, chờ xe và chuyển tuyến để xác định phương án khả thi. Chưa có thời gian thực đo riêng cho bước này.                                                                                                                       |
| **Impact**                                      | Quyết định kéo dài có thể khiến hành khách bỏ lỡ phương án còn khả thi, đến muộn hoặc tốn thêm chi phí cho các loại hình di chuyển khác. Tần suất và mức ảnh hưởng chưa được đo trên người thật.                                                                      |
| **Success Metric** (baseline → target, cách đo) | Baseline thực đo: chưa có; Nên kiểm thử cùng bộ tình huống bằng ứng dụng + checklist và bằng Rule, bấm giờ từ lúc nhận ra lỡ xe đến khi chốt phương án, không tính chờ xe. Mục tiêu: tìm được phương án dưới 2 phút, lộ trình tìm được đáp ứng các yêu cầu đã cài đặt |
| **Boundary**                                    | Chỉ tính/lọc các hành trình hợp lệ có trong đầu vào; không tự tạo tuyến hoặc giờ xe, không cam kết đến đúng giờ. Thiếu dữ liệu cần thiết thì ghi chưa đủ thông tin để xác nhận khả thi; nêu nguồn và độ mới khi có. Hành khách quyết định cuối cùng.                  |
| **AI intervention point**                       | Không có: kiểm tra điều kiện, tính giờ đến và sắp xếp theo ưu tiên dùng logic cố định.                                                                                                                                                                                |
| **Mức chọn**                                    | Rule — chọn để kiểm chứng.                                                                                                                                                                                                                                            |
| **Rủi ro & người kiểm tra**                     | Dữ liệu cũ/thiếu, tính sai hoặc bỏ chặng chuyển tuyến. Đề xuất nhóm phân công người đối chiếu đầu ra với ca tính tay và kiểm tra nguồn dữ liệu; hành khách xác nhận điểm đi/đến, giờ cần đến và ưu tiên. Người dùng chủ động đánh giá bằng like/dislike cho đề xuất.  |

**Thay đổi so với v0 và lý do:**

| Trường         | v0                                          | v1                                                                | Vì sao đổi                                                                    |
| -------------- | ------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Actor          | Hành khách thường xuyên sử dụng xe buýt     | Thêm tình huống lỡ xe giờ cao điểm, có giờ cần đến                | Khớp phạm vi đã nêu ở CP4; chưa coi là phân khúc đã kiểm chứng.               |
| Bottleneck     | Bước 3–4, khoảng 7–10 phút                  | Tập trung bước so sánh, chưa gán số phút                          | Khớp bottleneck bước 4 ở CP5; thời gian v0 chưa nhất quán với bảng từng bước. |
| Success Metric | Giảm thời gian xuống 2 phút                 | Nêu baseline còn thiếu, cách đo, đối chứng và điều kiện chọn đúng | Không dùng mô phỏng làm baseline; nhanh hơn nhưng chọn sai thì không đạt.     |
| Boundary       | AI tổng hợp, so sánh; báo khi thiếu dữ liệu | Rule chỉ xử lý đầu vào có căn cứ, không cam kết đúng giờ          | Nhất quán với mức chọn; phân biệt tính đúng với dữ liệu đầu vào đáng tin cậy. |

**Tiêu chí đánh giá đầu ra của Rule (5 tiêu chí):**

Đánh giá trên các ca thử có đầu vào và kết quả đối chiếu rõ ràng. Kết quả đúng theo dữ liệu đầu vào không đồng nghĩa giờ xe ngoài thực tế chắc chắn đúng; khoảng dự phòng và ngưỡng dữ liệu được coi là cũ cần được nhóm quy định trước khi thử.

|   # | Tiêu chí                | Đạt khi                                                                                                                             | Không đạt khi                                                            |
| --: | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
|   1 | Kiểm tra bắt kịp        | Kiểm tra điểm đón và từng lần chuyển tuyến, gồm khoảng dự phòng đã quy định; khớp ca đối chiếu                                      | Đánh dấu bắt kịp dù không đủ thời gian theo đầu vào                      |
|   2 | Tính đủ hành trình      | Giờ đến khớp phép tính đối chiếu, đủ đi bộ/chờ/đi xe/chuyển tuyến, không cộng trùng                                                 | Thiếu chặng, cộng trùng hoặc tính sai giờ đến                            |
|   3 | Đúng ràng buộc          | Phương án được đánh dấu phù hợp đáp ứng giờ cần đến và các giới hạn đã khai báo; báo rõ nếu không có phương án đáp ứng              | Gắn nhãn phù hợp cho phương án vi phạm ràng buộc                         |
|   4 | Minh bạch dữ liệu       | Nêu nguồn và thời điểm cập nhật khi có; cảnh báo dữ liệu cũ theo ngưỡng đã chốt; không xác nhận khả thi khi thiếu dữ liệu cần thiết | Che giấu thông tin thiếu/cũ hoặc khẳng định khi chưa đủ căn cứ           |
|   5 | Thời gian ra quyết định | Dưới 2 phút và thấp hơn ứng dụng + checklist trên bộ tình huống đối chứng, đồng thời đáp ứng điều kiện chọn đúng ở metric           | Vượt ngưỡng, không nhanh hơn đối chứng hoặc chọn phương án sai ràng buộc |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                    | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng                                                                                           |
| --------------- | ---------------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                | Cao                                                   | Chưa biết Rule có giúp hơn ứng dụng + checklist hay không.                                                   |
| **Usability**   | Người dùng có hiểu kết quả Rule và cảnh báo dữ liệu không? | Trung bình                                            | Tiêu chí so sánh rõ, nhưng chưa thử với người dùng đang cần quyết định nhanh.                                |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?              | Cao                                                   | Logic có thể mô tả bằng quy tắc; khả năng lấy đủ dữ liệu giờ xe, đi bộ và chuyển tuyến chưa được kiểm chứng. |
| **Viability**   | Có hợp chi phí, quyền sử dụng dữ liệu không? Ai vận hành?  | Trung bình                                            | Chi trả cho chi phí sử dụng thông tin, lộ trình xe; có thể bù doanh thu bằng quảng cáo                       |

### 8.2. Kết luận

**Quyết định đề xuất để nhóm chốt:** Not Yet — cho giải pháp Rule.

**Lý do:** Value và Feasibility còn ở mức Cao nhưng có thể kiểm chứng trong phạm vi nhỏ. Chưa đủ cơ sở triển khai; cũng chưa có lý do bổ sung AI.

**Nếu Go — pilot nhỏ nhất:** Sau khi giảm các rủi ro Cao, thử Rule trên một hành trình quen thuộc và các lựa chọn thay thế, đối chiếu với ứng dụng + checklist theo tiêu chí mục 7.

**Nếu Not Yet — cần kiểm chứng gì trước:** Đề xuất trong 1 tuần: hỏi 2–3 người ngoài nhóm từng lỡ xe về lần gần nhất; đo thời gian ra quyết định; kiểm tra dữ liệu tại một điểm dừng, đúng chiều và khung giờ cao điểm. Xác định nguồn được phép sử dụng và người kiểm tra dữ liệu.

**Nếu No-Go — phương án thay thế:** Dùng ứng dụng có sẵn + checklist; không xây Rule riêng nếu cách này đã đáp ứng mục tiêu.

**Ngưỡng dừng đề xuất:** Sau 1 tuần, nếu vẫn không lấy đủ dữ liệu để kiểm tra bắt kịp chuyến thì dừng hướng Rule riêng, quay về ứng dụng + checklist. Khi thử đối chứng, nếu Rule không nhanh hơn hoặc không đạt mục tiêu dưới 2 phút thì chưa mở rộng; nếu có ca báo bắt kịp sai do logic thì dừng thử, sửa và kiểm tra lại trước khi tiếp tục.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có baseline thực sự của người dùng.
- Cần xây dựng metrics kỹ càng để đo lường hiệu quả thực tế.
- Xem xét tích hợp chatbot trong tương lai.

## 10. Tài liệu tham khảo

-

# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Nhóm AE
- Candidate problem nhóm chọn (1 câu): Giảm thời gian xử lý ticket cư dân có nội dung lặp lại bằng cách giúp nhân viên tìm hướng dẫn đã duyệt và chuẩn bị phản hồi.
- Quyết định cuối (Go / Not Yet / No-Go): Go — pilot giới hạn sau khi được phê duyệt dữ liệu và đo baseline.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Phạm Hoàng Huy | 2A202603836 | Nhóm trưởng | justcoffeee |
| 2 | Cấn Xuân Nghĩa | 2A202603805 | Thành viên | xuannghia2 |
| 3 | Mai Lê Bá Vương | 2A202603872 | Thành viên | bavuong2005 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Phạm Hoàng Huy | Mai Lê Bá Vương, Cấn Xuân Nghĩa | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Phạm Hoàng Huy | Mai Lê Bá Vương | Assumption map, snapshot hoặc survey |
| CP4 — Research | Phạm Hoàng Huy | Mai Lê Bá Vương | Bảng research có link |
| CP5 — Quy trình trước/sau | Cấn Xuân Nghĩa | Phạm Hoàng Huy | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Cấn Xuân Nghĩa | Phạm Hoàng Huy | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Mai Lê Bá Vương | Phạm Hoàng Huy | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Mai Lê Bá Vương | Phạm Hoàng Huy | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### PhamHoangHuy-2A202603836

**Phần việc phụ trách:**

- Tổng hợp CP3, thực hiện CP4 và tham gia phỏng vấn.
- Điều phối, phân chia công việc, hỗ trợ rà soát CP5 và đối chiếu với CP6.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Tổng hợp các candidate, câu hỏi phản biện, cluster, cây OST và bảng shortlist trong CP3; ghi lại bài toán ticket cư dân mà nhóm lựa chọn.
- Lập bảng giả định và xác định nội dung cần kiểm chứng; tham gia phỏng vấn, tổng hợp ba snapshot gồm hai nhân viên và một cư dân.
- Tổng hợp các tín hiệu về ticket lặp lại, khó tìm hướng dẫn và chờ phản hồi; làm rõ rằng các mốc 10 phút, 30 phút và một ngày khác tình huống, không phải baseline chung.
- Tìm hiểu các cách hỗ trợ ticket như mẫu trả lời, tra cứu hướng dẫn và AI soạn nháp; bảng research còn cần bổ sung đủ nguồn và tự kiểm tra link trước khi nộp.
- Hỗ trợ chỉnh CP5 từ bản tham khảo khác đề tài sang quy trình ticket cư dân: quy trình trước/sau, bottleneck, bảng before/after, boundary, fallback và Problem Statement v0. Có sử dụng AI hỗ trợ tổng hợp và rà soát; nội dung cần nhóm tự xác nhận.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo nhóm](report/team/group_report.md), mục 2: pitch, cluster, OST, shortlist và candidate được chọn; mục 3: giả định, kiểm chứng và research; mục 4–5: phần hỗ trợ chỉnh CP5.
- [Snapshot phỏng vấn #1](report/assets/cp4-interview-snapshot-1.md), [#2](report/assets/cp4-interview-snapshot-2.md), [#3](report/assets/cp4-interview-snapshot-3.md). 
- Các commit: `1fd2295` (pitch và cluster), `3c80ded` (phân công và snapshot CP4), `3bf44ba` (chỉnh CP5), `841da93` (cập nhật phản biện và giả định).
- [Báo cáo cá nhân](report/individual/2A202603836_PhamHoangHuy.md), mục 4–5: nhật ký đóng góp và sử dụng AI.

**Điều mình học được từ phần nhóm:**

- Cần phân biệt phản hồi chậm vì tra cứu khó với chậm vì chờ bộ phận chuyên trách; phải xác định đúng bước nghẽn trước khi đề xuất AI.
- Lời kể của từng người là tín hiệu để kiểm chứng tiếp, không thể lấy trung bình các tình huống khác nhau thành baseline. Metric cần có cách đo và kiểm tra cả chất lượng, không chỉ tốc độ.
- Kho hướng dẫn và mẫu trả lời có thể đã đủ cho một số yêu cầu; nếu thử AI thì cần nguồn còn hiệu lực, người duyệt và phương án quay về thủ công.


### CanXuanNghia-2A202603805

**Phần việc phụ trách:**

- CP5: Xây dựng quy trình As-Is, To-Be và Problem Statement v0 cho đề tài FactCheck AI.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Mô tả quy trình hiện tại gồm 6 bước và xác định bottleneck.

- Đề xuất quy trình tương lai, phân chia vai trò Rule, AI và con người.

- Xây dựng Boundary, Fallback và bảng so sánh Before/After.

- Viết Problem Statement v0 theo 6 trường và đề xuất các metric đánh giá.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- group_report.md: Mục 4 – Process Mapping và Mục 5 – Problem Statement.

- Sơ đồ As-Is, To-Be và bảng phân tích trong báo cáo CP5.


**Điều mình học được từ phần nhóm:**

- Mình học được cách xác định vấn đề trước khi đề xuất giải pháp, cách phân tích quy trình để tìm bottleneck và phân chia vai trò giữa Rule, AI và con người. Đồng thời, mình hiểu rằng cần có bằng chứng thực tế để đánh giá vấn đề và chứng minh giá trị của giải pháp AI.

### MaiLeBaVuong-2A202603872

**Phần việc phụ trách:**

- Hỗ trợ CP3 — hội tụ candidate, xây cluster/cây OST và bảng chấm điểm shortlist.
- Hỗ trợ CP4 — rà soát assumption map, kiểm chứng qua phỏng vấn và research giải pháp.
- Phụ trách CP6 — so sánh mức No AI/Rule/Workflow/Agent, Problem Statement v1, tiêu chí đánh giá và quyết định theo bốn rủi ro.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đề xuất thử Workflow có người duyệt cho bước tìm hướng dẫn phù hợp và soạn nháp phản hồi ticket lặp lại.
- Xác định boundary, phương án quay về xử lý thủ công, mục tiêu đo và ngưỡng dừng cho pilot giới hạn.
- Hoàn thiện quyết định Go cho pilot giới hạn, có điều kiện phê duyệt dữ liệu, đo baseline và ngưỡng dừng rõ ràng.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`, mục 6–8: ma trận, AI Canvas, Problem Statement v1, eval, bốn rủi ro và quyết định.
- `report/team/group_report.md`, mục 2.1, hàng candidate của Mai và Huy: chủ đề ticket cư dân cùng câu hỏi phản biện.
- `report/individual/2A202603872_MaiLeBaVuong.md`, mục 4–6: nhật ký tham gia, dùng AI và reflection.

**Điều mình học được từ phần nhóm:**

- Câu hỏi “làm cách nào xác nhận đã điều hướng đúng?” khiến mình bổ sung cách đo chất lượng chuyển ticket, còn câu hỏi về lúc hệ thống nghẽn nhắc mình phải có fallback thủ công. Go chỉ hợp lý trong phạm vi pilot nhỏ khi có người duyệt, dữ liệu được phép sử dụng và ngưỡng dừng rõ ràng.

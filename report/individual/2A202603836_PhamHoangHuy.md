# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Hoàng Huy
- MSSV: 2A202603836
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: Nhóm AE
- Link repo nhóm: https://github.com/justcoffeee/K5-L3B-DAY02-NhomAE-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi yêu cầu bài lab nằm trong nhiều file, tôi cần xác định nội dung chính | Học viên, trưởng nhóm | Thời gian trung bình cần phải đọc đề, đôi khi còn bỏ xót |
| 2 | Pain từ người khác | Khi chia tiền sau chuyến đi chơi, tôi muốn biết mình cần trả bao nhiêu tiền và trả cho những ai, để tránh chuyển tiền nhầm hoặc hỏi đi hỏi lại | Thành viên chuyến đi | Số lượng lượt hỏi, giao dịch sửa lại |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi đi tìm phòng trọ, tôi muốn tổng hợp lại những chi phí và các khoản cần chi trả của từng phòng một, để tiện theo dõi và có góc nhìn tổng thể về giá tiền phải chi trả | Người thuê nhà | Số lượt hỏi, các khoản phí bị bỏ sót |
| 4 | Lặp lại | Khi làm việc và nhận nhiều phản hồi về cùng một vấn đề của khách hàng, tôi muốn cung cấp giải pháp giúp giải quyết vấn đề đã thống nhất, để không phải tìm hoặc giải thích lại từ đầu | Nhân viên, khách hàng | Thời gian trả lời phản hồi, số lượng câu hỏi trùng lặp |
| 5 | Lặp lại | Khi học xong bài và cần làm bài tập về nhà, tôi muốn biết các bài tập sắp đến hạn, để không phải mở và kiểm tra từng môn học | Sinh viên | Số lượng thông tin phải kiểm tra, thời gian dành ra để kiểm tra |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

| # | Các ý tưởng AI đề xuất | Bỏ/ Nhận | Lí do |
|-|-|-|-|
| 1 | Khi tiếp tục làm bài sau một buổi họp, tôi muốn tìm lại quyết định cuối cùng và lý do lựa chọn, để không làm theo phương án đã bị bỏ. | Bỏ | Khi thảo luận bài đã đưa đầy đủ lí do nên không cần thiết phải làm phương án này |
| 2 | Khi chia tiền sau chuyến đi chơi, tôi muốn biết mình cần trả bao nhiêu tiền và trả cho những ai, để tránh chuyển tiền nhầm hoặc hỏi đi hỏi lại | Nhận | Vì mỗi lần đi chơi số lượng tiền chi trả khá nhiều nên cần trợ giúp tính toán và ghi lại cần phải trả cho những ai và trả bao nhiêu |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Khi yêu cầu bài lab nằm trong nhiều file, tôi cần xác định nội dung chính | Số lượng yêu cầu nhiều và nhiều file hướng dẫn nên cần trợ lí tổng hợp | Không có |
| 2 | Khi làm việc và nhận nhiều phản hồi về cùng một vấn đề của khách hàng, tôi muốn cung cấp giải pháp giúp giải quyết vấn đề đã thống nhất, để không phải tìm hoặc giải thích lại từ đầu | Cùng một lỗi nhưng cần hỗ trợ đi hỗ trợ lại rất tốn thời gian và cần tối ưu thời gian | Không có |
| 3 | Khi học xong bài và cần làm bài tập về nhà, tôi muốn biết các bài tập sắp đến hạn, để không phải mở và kiểm tra từng môn học | Số lượng bài tập nhiều và mỗi môn học có một deadline riêng | Không có |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi yêu cầu bài lab nằm trong nhiều file, tôi cần xác định nội dung chính |
| Actor | Nhóm trưởng phụ trách đọc và phân công/ Thành viên cần đảm bảo yêu cầu nội dung và format |
| Thời điểm / bối cảnh | Khi làm bài lab mới, trước khi phân công, kiểm tra lại |
| Quy trình hiện tại (3–7 bước) | 1. Mở README nắm tổng quát -> 2. Mở các file hướng dẫn có liên quan đề cập trong README -> 3. Đối chiếu tài liệu và ghi lại yêu cầu -> 4. Lập checklist, phân công công việc -> 5. Kiểm tra lại một lần nữa yêu cầu |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: đối chiếu cần xác nhận qua lại giữa các file, mất khoảng 30-40p |
| Impact (nếu không giải thì sao) | Thời gian đọc yêu cầu và đối chiếu quá dài dẫn đến ảnh hưởng đến phân công và thực hiện việc nhóm |
| Success metric (baseline → target) | Baseline: đo thời gian từ lúc mở đề đến lúc phân công. Target: Giảm thời gian đọc và đối chiếu tài liệu xuống còn 50% và không bỏ sót các yêu cầu công việc |
| Phương án không dùng AI | Ghi lại từng yêu cầu ra giấy mỗi khi đọc xong 1 file |
| Giả thuyết về AI (nếu có) | Dùng AI scan toàn bộ file và xuất ra file tổng hợp yêu cầu |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi học xong bài và cần làm bài tập về nhà, tôi muốn biết các bài tập sắp đến hạn, để không phải mở và kiểm tra từng môn học |
| Actor | Sinh viên |
| Thời điểm / bối cảnh | Sinh viên học nhiều môn và có nhiều bài tập cần hoàn thiện |
| Quy trình hiện tại (3–7 bước) | 1. Mở từng môn học, check bài tập và hạn nộp -> 2. Kiểm tra lại thông báo mới nhất trong nhóm -> 3. Đối chiếu và điều chỉnh deadline -> 4. Ghi danh sách bài tập cần làm và hạn -> 6. Sắp xếp thứ tự thực hiện |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2,3: cần mở nhiều môn học và đối chiếu nhiều môn dẫn đến dễ sai hoặc miss thông tin |
| Impact (nếu không giải thì sao) | Lặp đi lặp lại việc kiểm tra mỗi ngày, dễ bỏ sót bài tập, làm gấp và trễ hẹn |
| Success metric (baseline → target) | Baseline: Đo thời gian đến hạn trong 7 ngày và số lượng bài bị trễ/ làm gấp. Target: Giảm thiểu số lượng bài tập bị làm gấp/ bị miss, số lần check hạn | 
| Phương án không dùng AI | Ghi chú thời gian deadline ra giấy note |
| Giả thuyết về AI (nếu có) | Tổng hợp và reminder về các deadline sắp tới |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm việc và nhận nhiều phản hồi về cùng một vấn đề của khách hàng, tôi muốn cung cấp giải pháp giúp giải quyết vấn đề đã thống nhất, để không phải tìm hoặc giải thích lại từ đầu |
| Actor | Nhân viên, khách hàng |
| Thời điểm / bối cảnh | Nhân viên nhận nhiều phản hồi về cùng một vấn đề |
| Quy trình hiện tại (3–7 bước) | 1. Khách hàng viết ticket yêu cầu hỗ trợ -> 2. Bộ phận CSKH tiếp nhận thông tin -> 3. Chuyển thông tin đến các bộ phận liên quan -> 4. Kiểm tra, xử lý và hỗ trợ các ticket được nhận |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: Do lặp đi lặp lại các lỗi trùng lặp có thể làm ảnh hưởng đến hiệu suất công việc, nếu số lượng ticket tăng lên nhiều có thể ảnh hưởng đến cả thời gian phản hồi |
| Impact (nếu không giải thì sao) | Phản hồi khách hàng chậm, nhận đánh giá xấu |
| Success metric (baseline → target) | Baseline: Đo thời gian phản hồi, số lượng ticket trùng lặp về cùng một loại lỗi. Target: Giảm thời gian phản hồi, giảm số lượng ticket trùng lặp |
| Phương án không dùng AI | Các bộ phận phối hợp và xử lý các ticket |
| Giả thuyết về AI (nếu có) | AI sẽ hỗ trợ xử lý các trường hợp thông thường, các trường hợp đặc biệt sẽ được forward đến bộ phận chuyên trách |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số: 3
- Vì sao: Tính ứng dụng thực tiễn cao và giảm chi phí vận hành
- Câu hỏi muốn nhóm phản biện: Không có

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor quá rộng | CSKH và khách hàng đều bị ảnh hưởng. | Chọn nhân viên CSKH trực tiếp xử lý ticket làm actor chính; khách hàng là người hưởng lợi. Nêu thêm lĩnh vực hỗ trợ nếu có. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đã tham gia đánh giá | Chốt đề bài |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Forward trực tiếp thông tin vậy có nguy cơ bị lộ thông tin người dùng không? |  |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | Điều phối và phân chia công việc và đảm nhiệm CP3 | Phân chia công việc cho thành viên nhóm và hoàn thành CP3 |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-

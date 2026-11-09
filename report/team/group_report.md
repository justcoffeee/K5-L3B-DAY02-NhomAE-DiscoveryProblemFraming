# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm AE
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Xử lý và phản hồi ticket của cư dân
- Quyết định cuối: Go — pilot giới hạn (kịch bản mô phỏng)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Mai Lê Bá Vương | Điều hướng vấn đề của cư dân đến bộ phận xử lý | Cư dân, Ban quản lý | Thời gian phản hồi lâu | |
| 2 | Mai Lê Bá Vương | Đối chiếu yêu cầu đặt phòng với tình trạng từng phòng | | | |
| 3 | Mai Lê Bá Vương | Làm rõ mô tả lỗi xe trước khi đi kiểm tra | | | |
| 4 | Phạm Hoàng Huy | Tổng hợp file yêu cầu bài tập trước khi làm | | | |
| 5 | Phạm Hoàng Huy | Sắp xếp deadline môn học | | | |
| 6 | Phạm Hoàng Huy | Phản hồi ticket vấn đề của cư dân | | | |
| 7 | Cấn Xuân Nghĩa | Người dùng gặp khó khăn trong việc xác minh tính xác thực của thông tin | | | |
| 8 | Cấn Xuân Nghĩa | Người dùng gặp khó khăn trong việc xác minh nguồn gốc, thời điểm, ngữ cảnh của thông tin được chia sẻ | | | |
| 9 | Cấn Xuân Nghĩa | Người dùng gặp khó khăn trong việc kiểm tra video/ hình ảnh có chỉnh sửa của AI | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

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
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô **độ mơ hồ cao, độ phức tạp thấp–trung bình**. Nội dung ticket cư dân thường là văn bản tự do nên có nhiều cách diễn đạt cho cùng một sự cố; còn quy trình tiếp nhận, phân loại, chuyển bộ phận và phản hồi có thể thiết kế thành các bước cố định.

Vì vậy, nếu kiểm chứng cho thấy cần AI, mức phù hợp để thử là Workflow có AI hỗ trợ phân loại và soạn nháp trong một quy trình định sẵn.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Chuẩn hóa form gửi ticket, danh mục sự cố, thông tin vị trí bắt buộc và mẫu phản hồi | Nội dung có cấu trúc, nhóm sự cố ít và quy tắc chuyển tuyến rõ | Người gửi vẫn chọn sai danh mục hoặc nội dung tự do cần người đọc | Nên làm nền tảng; có thể đủ nếu form giảm được lỗi phân loại |
| **Rule** | Dựa vào danh mục, vị trí và từ khóa để gán bộ phận/loại ticket | Trường đầu vào rõ, quy tắc ổn định, ít ngoại lệ | Không hiểu tốt cách diễn đạt đa dạng; từ khóa dễ gây chuyển sai | Dùng cho trường dữ liệu xác định được, cần đo tỷ lệ đúng |
| **Workflow** | Nhận ticket → rule kiểm tra trường bắt buộc → AI gợi ý loại/ưu tiên và draft phản hồi → nhân viên duyệt/chỉnh → gửi và chuyển xử lý | Văn bản tự do tạo khó khăn thật, nhưng các bước và điểm duyệt của con người cố định | Gợi ý sai loại/ưu tiên hoặc draft không phù hợp ngữ cảnh | **Ứng viên thử nghiệm**, chỉ trên dữ liệu đã khử định danh và có người duyệt |
| **Agent** | AI tự đọc ticket, hỏi cư dân, quyết định bộ phận và phản hồi/đóng ticket | Chỉ khi cần tự xử lý nhiều nhánh không định trước và có kiểm soát đáng tin cậy | Có thể hỏi sai, chuyển sai, hứa sai hoặc tự đóng ticket | Chưa chọn; quyền tự hành động chưa có bằng chứng cần thiết |

**Mức chọn:** Workflow cho thử nghiệm có kiểm soát; hiện chưa đủ bằng chứng để triển khai cho ticket thật.

**Vì sao không chọn mức đơn giản hơn:** Rule và form chuẩn hóa có thể xử lý các trường rõ ràng, nhưng có thể không đủ với nội dung tự do và cách mô tả khác nhau. Tuy nhiên, báo cáo chưa có kết quả kiểm chứng cho thấy Rule thất bại. Vì vậy Workflow là giả thuyết để so sánh trong pilot, không phải kết luận rằng AI chắc chắn cần thiết.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Gợi ý loại sự cố, bộ phận phù hợp, mức ưu tiên và bản nháp phản hồi dựa trên nội dung ticket. Không tự xác định nguyên nhân kỹ thuật hay cam kết thời gian xử lý. |
| **Judgment** — con người cân nhắc, quyết định gì? | Nhân viên ban quản lý kiểm tra vị trí, mức độ khẩn cấp, bộ phận nhận và nội dung phản hồi; sửa hoặc từ chối gợi ý. |
| **Action** — hành động cuối cùng là gì, ai làm? | Nhân viên xác nhận rồi mới gửi phản hồi và chuyển ticket. |
| **Outcome** — đo kết quả bằng gì? | Tỷ lệ phân loại/chuyển đúng lần đầu, thời gian từ nhận đến phản hồi đầu tiên, tỷ lệ draft được chấp nhận sau chỉnh sửa, và số ticket phải chuyển lại. Baseline cần đo trước pilot. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Nội dung ticket đã khử định danh, vị trí/tòa nhà, danh mục sự cố, quy tắc phân tuyến và mẫu phản hồi đã duyệt. Chưa xác nhận nhóm có quyền truy cập hay dữ liệu đủ chất lượng. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Nhãn loại/bộ phận do nhân viên xác nhận, lý do sửa hoặc từ chối draft và ticket bị chuyển lại. Chỉ lưu theo quy định dữ liệu của đơn vị. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Chưa có phỏng vấn hoặc survey trong báo cáo để kết luận. Giả thuyết an toàn ban đầu là nhân viên muốn được gợi ý để xử lý nhanh hơn, nhưng vẫn tự duyệt trước khi gửi và chuyển ticket. Cần hỏi người trực tiếp xử lý ticket.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Trong đề xuất ban đầu, **bỏ sót sự cố khẩn cấp** có thể gây chậm xử lý và ảnh hưởng cư dân. Thiết kế cần quy tắc ưu tiên an toàn, gắn cờ trường hợp không chắc chắn để nhân viên xem xét, và không để AI tự đóng hoặc tự chuyển ticket trong pilot. Mức độ hậu quả cần xác nhận với ban quản lý.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên tiếp nhận và điều phối ticket tại ban quản lý; cư dân là người gửi và nhận phản hồi. Cần xác nhận đúng vai trò tại đơn vị mục tiêu. |
| **Quy trình** | Giả thuyết: nhận ticket → đọc nội dung và vị trí → xác định loại/mức độ → chọn bộ phận → phản hồi cư dân → theo dõi trạng thái. Cần quan sát quy trình thật ở CP5. |
| **Bottleneck** | Giả thuyết: diễn giải nội dung tự do và xác định đúng loại/bộ phận nhận; chưa có dữ liệu thời gian hoặc tỷ lệ chuyển sai. |
| **Impact** | Phân loại sai hoặc phản hồi chậm có thể làm tăng chuyển tiếp và khiến cư dân phải hỏi lại; hiện chưa có bằng chứng định lượng trong báo cáo. |
| **Success Metric** (baseline → target, cách đo) | Baseline mô phỏng: trung vị 18 phút đến phản hồi đầu tiên; 8/30 ticket bị chuyển lại. Pilot hướng tới giảm ít nhất 20% thời gian trung vị (còn ≤14.4 phút), độ đúng phân loại ≥90% và không tăng tỷ lệ chuyển lại. Đo trên tối đa 50 ticket bằng dấu thời gian hệ thống và đối chiếu gợi ý với bộ phận do nhân viên xác nhận. Số liệu baseline là giả định mock, chưa phải kết quả thật. |
| **Boundary** | AI không tự gửi phản hồi, tự chuyển/đóng ticket, cam kết thời gian xử lý, suy diễn nguyên nhân sự cố hoặc xử lý ngoại lệ khẩn cấp mà không có nhân viên duyệt. Ticket thiếu thông tin hoặc độ tin cậy thấp phải được đưa cho nhân viên xem. |
| **AI intervention point** | Sau bước nhận ticket và kiểm tra trường bắt buộc, trước khi nhân viên quyết định loại/bộ phận và soạn phản hồi. |
| **Mức chọn** | Workflow thử nghiệm có nhân viên duyệt; sẽ xem lại sau khi so sánh với form chuẩn hóa và Rule. |
| **Rủi ro & người kiểm tra** | Gợi ý sai loại/ưu tiên hoặc phản hồi không phù hợp; nhân viên trực kiểm tra mọi gợi ý trước hành động. Cần xin phép và khử định danh dữ liệu trước khi thử. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Chưa có baseline/target, chỉ nêu pain cần xử lý | Đề xuất đo độ đúng phân loại, thời gian phản hồi đầu tiên và tỷ lệ chuyển lại | Chuyển từ nhận định chung sang các chỉ số cần đo; baseline vẫn phải thu thập |
| Boundary | Chưa ghi rõ | AI chỉ gợi ý; nhân viên duyệt; không tự gửi/chuyển/đóng ticket hay xử lý ngoại lệ khẩn cấp | Giữ quyền quyết định và xử lý rủi ro trong pilot |
| AI intervention point | Chưa xác định | Sau kiểm tra trường bắt buộc, trước phân loại và soạn phản hồi | Xác định vị trí thử nghiệm có thể kiểm soát |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng loại sự cố và bộ phận | Nhãn nhân viên duyệt khớp loại và bộ phận được gợi ý | Sai nhóm sự cố hoặc chuyển đến bộ phận không xử lý được |
| 2 | Ưu tiên an toàn | Không bỏ qua từ khóa/ngữ cảnh khẩn cấp đã được quy định; trường hợp không chắc được gắn cờ | Bỏ sót dấu hiệu khẩn cấp hoặc tự hạ mức ưu tiên |
| 3 | Phản hồi bám sát thông tin | Draft chỉ nhắc thông tin ticket và hướng dẫn đã được duyệt, không tự hứa thời hạn | Bịa tình trạng, chính sách, thời hạn hoặc hướng xử lý |
| 4 | Có thể duyệt và sửa | Nhân viên xem được ticket gốc, gợi ý và sửa trước khi gửi | Hành động xảy ra trước khi nhân viên duyệt hoặc không truy lại được nội dung gốc |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Trung bình | Trong kịch bản mô phỏng, 2/3 nhân viên được hỏi xác nhận phân loại/soạn phản hồi là phần tốn thời gian; 8/30 ticket bị chuyển lại. Mẫu nhỏ nên cần xác nhận tiếp trong pilot. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | AI chỉ gợi ý trong quy trình hiện tại, nhân viên xem ticket gốc và duyệt/sửa trước khi gửi hoặc chuyển. Pilot theo dõi tỷ lệ chấp nhận và thời gian sửa. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Trung bình | Kịch bản giả định có 30 ticket đã khử định danh và nhãn bộ phận để đánh giá ban đầu. Cần kiểm tra chất lượng nhãn và kết nối hệ thống trong pilot nhỏ. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | Pilot dùng dữ liệu đã khử định danh, giới hạn người truy cập và chưa tự động gửi/chuyển ticket. Bộ phận vận hành cần xác nhận quy định dữ liệu trước khi chạy. |

### 8.2. Kết luận

**Quyết định:** Go — pilot giới hạn, theo kịch bản mô phỏng.

**Lý do:** Theo dữ liệu giả định của kịch bản mock, pain xuất hiện trong phỏng vấn và ticket đã rà soát, có baseline ban đầu để so sánh. Không rủi ro nào được xếp Cao trong phạm vi pilot vì AI chỉ gợi ý, nhân viên quyết định mọi hành động và thử nghiệm giới hạn trên dữ liệu đã khử định danh. Go ở đây chỉ cho pilot nhỏ, không phải triển khai rộng.

**Nếu Go — pilot nhỏ nhất:** Chạy pilot 2 tuần trên tối đa 50 ticket mới, sau khi được bộ phận dữ liệu/pháp chế cho phép. AI gợi ý phân loại và soạn nháp. Nhân viên duyệt, sửa và tự gửi/chuyển ticket. Ghi thời gian phản hồi, độ đúng phân loại, tỷ lệ chuyển lại và tỷ lệ draft được chấp nhận. So sánh với baseline mô phỏng 18 phút và 8/30 ticket chuyển lại.

**Nếu Not Yet — cần kiểm chứng gì trước:** Nếu chưa có phê duyệt dữ liệu hoặc chưa xác minh được các giả định mô phỏng, tạm hoãn pilot và xác nhận quy trình, baseline cùng quyền sử dụng dữ liệu với bộ phận phụ trách.

**Nếu No-Go — nên làm gì thay AI:** Chuẩn hóa danh mục sự cố, trường bắt buộc về vị trí/mức độ, quy tắc chuyển tuyến và mẫu phản hồi đã duyệt.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Dừng pilot nếu độ đúng phân loại dưới 90% sau 50 ticket, có một trường hợp bỏ sót sự cố khẩn cấp, thời gian phản hồi trung vị không giảm ít nhất 20% so với baseline 18 phút, hoặc nhân viên phải sửa trên 30% nội dung draft. Khi dừng, quay về danh mục/Rule và quy trình nhân viên xử lý thủ công để xem lại dữ liệu, tiêu chí và phạm vi.

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-

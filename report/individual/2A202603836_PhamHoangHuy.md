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
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: đối chiếu yêu cầu giữa các file. Ước lượng đã ghi: 30–40 phút/lần; cần bấm giờ xác minh, chưa phải baseline đo được. |
| Impact (nếu không giải thì sao) | Thời gian đọc yêu cầu và đối chiếu quá dài dẫn đến ảnh hưởng đến phân công và thực hiện việc nhóm |
| Success metric (baseline → target) | Baseline: đo thời gian từ lúc mở đề đến lúc phân công. Target: Giảm thời gian đọc và đối chiếu tài liệu xuống còn 50% và không bỏ sót các yêu cầu công việc |
| Phương án không dùng AI | Ghi lại từng yêu cầu ra giấy mỗi khi đọc xong 1 file |
| Giả thuyết về AI (nếu có) | Dùng AI scan toàn bộ file và xuất ra file tổng hợp yêu cầu |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text
[1. Đọc README để nắm tổng quan — chưa đo phút]
    ↓
[2. Mở và đọc các tài liệu hướng dẫn liên quan — chưa đo phút]
    ↓
[3. Đối chiếu, ghi lại yêu cầu — ước lượng 30–40 phút] ← BOTTLENECK
    ↓
[4. Lập checklist và phân công — chưa đo phút]
    ↓
[5. Đối chiếu checklist với đề một lần nữa — chưa đo phút]
```

**Tổng thời gian:** Chưa đo. Mốc 30–40 phút chỉ là ước lượng của bước 3, không phải tổng thời gian. Cần bấm giờ từng bước trong lần đọc đề tiếp theo.

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi học xong bài và cần làm bài tập về nhà, tôi muốn biết các bài tập sắp đến hạn, để không phải mở và kiểm tra từng môn học |
| Actor | Sinh viên |
| Thời điểm / bối cảnh | Sinh viên học nhiều môn và có nhiều bài tập cần hoàn thiện |
| Quy trình hiện tại (3–7 bước) | 1. Mở từng môn học, check bài tập và hạn nộp -> 2. Kiểm tra lại thông báo mới nhất trong nhóm -> 3. Đối chiếu và điều chỉnh deadline -> 4. Ghi danh sách bài tập cần làm và hạn -> 5. Sắp xếp thứ tự thực hiện |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: kiểm tra thông báo và đối chiếu deadline mới nhất giữa các nguồn. Chưa đo thời gian; cần ghi riêng từng bước và số môn/kênh đã kiểm tra. |
| Impact (nếu không giải thì sao) | Lặp đi lặp lại việc kiểm tra mỗi ngày, dễ bỏ sót bài tập, làm gấp và trễ hẹn |
| Success metric (baseline → target) | Baseline: Đo thời gian đến hạn trong 7 ngày và số lượng bài bị trễ/ làm gấp. Target: Giảm thiểu số lượng bài tập bị làm gấp/ bị miss, số lần check hạn | 
| Phương án không dùng AI | Ghi chú thời gian deadline ra giấy note |
| Giả thuyết về AI (nếu có) | Tổng hợp và reminder về các deadline sắp tới |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
[1. Mở từng môn, xem bài tập và hạn nộp — chưa đo phút]
    ↓
[2. Kiểm tra thông báo mới trong nhóm — chưa đo phút]
    ↓
[3. Đối chiếu, xác nhận deadline còn hiệu lực — chưa đo phút] ← BOTTLENECK
    ↓
[4. Ghi danh sách bài cần làm và hạn nộp — chưa đo phút]
    ↓
[5. Sắp xếp thứ tự thực hiện — chưa đo phút]
```

**Tổng thời gian:** Chưa đo. Bước 2 có thể làm tăng thời gian đối chiếu ở bước 3. Cần ghi số môn, số kênh thông báo và số phút từng bước qua các buổi tự học để xác nhận bottleneck.

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm việc và nhận nhiều phản hồi về cùng một vấn đề của khách hàng, tôi muốn cung cấp giải pháp giúp giải quyết vấn đề đã thống nhất, để không phải tìm hoặc giải thích lại từ đầu |
| Actor | Nhân viên, khách hàng |
| Thời điểm / bối cảnh | Nhân viên nhận nhiều phản hồi về cùng một vấn đề |
| Quy trình hiện tại (3–7 bước) | 1. Khách hàng gửi ticket → 2. CSKH đọc và làm rõ thông tin → 3. Xác định loại yêu cầu/bộ phận phụ trách → 4. Tìm hướng dẫn hoặc hỏi bộ phận chuyên trách → 5. Soạn và kiểm tra phản hồi → 6. Gửi phản hồi, chuyển xử lý và ghi nhận trạng thái. Đây là quy trình nháp cần người vận hành xác nhận. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết ở bước 4: tìm lại hướng dẫn và xác nhận cách xử lý các yêu cầu tương tự. Chưa đo thời gian đại diện; cần tách thời gian tra cứu khỏi thời gian chờ bộ phận khác. |
| Impact (nếu không giải thì sao) | Phản hồi khách hàng chậm, nhận đánh giá xấu |
| Success metric (baseline → target) | Baseline: Đo thời gian phản hồi, số lượng ticket trùng lặp về cùng một loại lỗi. Target: Giảm thời gian phản hồi, giảm số lượng ticket trùng lặp |
| Phương án không dùng AI | Các bộ phận phối hợp và xử lý các ticket |
| Giả thuyết về AI (nếu có) | AI sẽ hỗ trợ xử lý các trường hợp thông thường, các trường hợp đặc biệt sẽ được forward đến bộ phận chuyên trách |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[1. Khách hàng gửi ticket — chưa đo phút]
    ↓  Handoff: khách hàng → CSKH
[2. CSKH đọc, hỏi bổ sung nếu thiếu thông tin — chưa đo phút]
    ↓
[3. Xác định loại yêu cầu và bộ phận phụ trách — chưa đo phút]
    ↓
[4. Tìm hướng dẫn hoặc hỏi bộ phận chuyên trách — chưa đo phút] ← BOTTLENECK GIẢ THUYẾT
    ↓  Handoff khi cần: CSKH ↔ bộ phận chuyên trách
[5. Soạn và kiểm tra phản hồi — chưa đo phút]
    ↓
[6. Gửi phản hồi, chuyển xử lý và ghi nhận trạng thái — chưa đo phút]
```

**Tổng thời gian:** Chưa đo. Cần ghi riêng thời gian tra cứu, thời gian chờ chuyên trách và thời gian soạn/kiểm tra; phản hồi đầu tiên không đồng nghĩa sự cố đã được giải quyết. Quy trình cần được người trực tiếp xử lý ticket xác nhận.

### Card muốn pitch nhất

- Card số: 3
- Vì sao: Tính ứng dụng thực tiễn cao và giảm chi phí vận hành
- Câu hỏi muốn nhóm phản biện (đề xuất để chuẩn bị pitch, chưa ghi nhận là đã hỏi): Với ticket lặp lại, bước nghẽn thực sự là tìm hướng dẫn, soạn câu trả lời hay chờ bộ phận chuyên trách? Bằng chứng nào giúp phân biệt các nguyên nhân này, và kho hướng dẫn/mẫu trả lời không dùng AI đã đủ để cải thiện chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor quá rộng | CSKH và khách hàng đều bị ảnh hưởng. | Chọn nhân viên CSKH trực tiếp xử lý ticket làm actor chính; khách hàng là người hưởng lợi. Nêu thêm lĩnh vực hỗ trợ nếu có. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Bảng dưới đây tổng hợp phần việc có thể đối chiếu với báo cáo nhóm, phân công và lịch sử commit. Các nội dung tổng hợp/chỉnh sửa tài liệu có sử dụng AI hỗ trợ; không đồng nghĩa đã thực hiện thêm phỏng vấn hoặc chạy pilot.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đưa ra ba candidate và thảo luận chọn candidate chính | Candidate phản hồi ticket cư dân được đưa vào shortlist và trở thành chủ đề nhóm chọn. |
| Phản biện bài của bạn khác | Hỏi Vương: “Làm cách nào để xác nhận đã điều hướng đúng về bộ phận xử lý?”; hỏi cách cập nhật tình trạng phòng theo thời gian thực. Với hướng kiểm chứng thông tin của Nghĩa, đặt câu hỏi về tính cần thiết và phạm vi ứng dụng. | Làm rõ các điểm cần chứng minh về độ đúng, dữ liệu cập nhật và ranh giới sử dụng thông tin. |
| Nhận phản biện | Theo bảng pitch, Nghĩa hỏi: “Độ chính xác của phản hồi?”; Vương hỏi: “Nếu hệ thống nghẽn thì xử lý như nào?” | Khi hỗ trợ chỉnh CP5, tôi yêu cầu giữ bước nhân viên kiểm nguồn và duyệt nội dung, bổ sung cách đánh giá độ đúng bên cạnh thời gian, cùng fallback quay về mẫu trả lời/tra cứu thủ công khi AI sai hoặc lỗi. Phần này có tại mục 4–5 báo cáo nhóm. |
| Gom cluster / cây OST | Phụ trách CP3; tổng hợp ba cluster về tiếp nhận/làm rõ yêu cầu, tổng hợp/đối chiếu thông tin và kiểm chứng độ tin cậy. Dùng AI hỗ trợ rà soát cách trình bày cluster và outcome cho đề tài ticket cư dân. | Mục 2.2–2.3 trình bày các nhóm pain và một outcome chung. |
| Chọn candidate problem | Tổng hợp bảng shortlist, ghi candidate được chọn và lý do chọn/loại | Nhóm hội tụ về ticket cư dân, sau đó thu hẹp vào yêu cầu lặp lại và bước tìm hướng dẫn/chuẩn bị phản hồi. |
| Kiểm chứng / research | Tổng hợp ba snapshot đã lưu và bảng giả định, rà soát cách diễn giải thời gian được kể; tìm hiểu các hướng mẫu trả lời, phân loại và hỗ trợ soạn phản hồi với AI. Chưa có ghi nhận trong snapshot để khẳng định tôi trực tiếp thực hiện từng cuộc phỏng vấn. | Mục 3 và các file snapshot cung cấp tín hiệu định tính về yêu cầu lặp lại, chờ phản hồi và khó tìm thông tin. Không dùng các mốc 10 phút, 30 phút và một ngày làm một baseline chung. Bảng research hiện còn thiếu nguồn đối chiếu và cần hoàn thiện. |
| Quy trình nhóm | Điều phối, phân công checkpoint; hỗ trợ phần CP5 của Nghĩa. Dùng AI hỗ trợ chỉnh quy trình theo đề tài nhóm. | Mục 4 có quy trình hiện tại/tương lai, sơ đồ, actor/input/output, bottleneck, boundary và fallback. |
| Problem Statement | Hỗ trợ tổng hợp bản v0 theo sáu trường tại mục 5 và rà soát sự nhất quán với chủ đề ticket cư dân; bổ sung mục tiêu đề xuất, cách đo và giới hạn AI với AI hỗ trợ. | Bản v0 phân biệt lời kể, bottleneck giả thuyết và baseline chưa đo; nhân viên giữ quyền duyệt và thực hiện hành động. |
| Mức can thiệp AI | Rà soát phương án đơn giản hơn khi hỗ trợ CP5: kho hướng dẫn, mẫu phản hồi và Rule; đối chiếu với đề xuất Workflow trong CP6 do Vương phụ trách. | Giữ phương án không AI/Rule làm đối chứng; Workflow chỉ hỗ trợ tìm hướng dẫn và soạn nháp, không tự gửi hay đóng ticket.|
| Quyết định | Hỗ trợ theo phân công; kiểm tra phạm vi Go trong báo cáo và TEAM.md, đối chiếu với dữ liệu và các điều kiện còn thiếu. | Báo cáo hiện ghi Go cho pilot giới hạn sau khi được phê duyệt dữ liệu và đo baseline. Đây là đề xuất thử nghiệm, không phải pilot đã chạy hay hiệu quả đã đạt; phần quyết định chính do Vương phụ trách, cả nhóm cần xác nhận. |

---

## 5. Dùng AI

Nhật ký tổng hợp từ các trao đổi trong quá trình làm bài; các gợi ý, số liệu chưa đo và quyết định đề xuất vẫn cần tôi/nhóm tự kiểm tra, xác nhận.

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Xin thêm ý tưởng theo các lăng kính, đặc biệt là công việc lặp lại trong học tập, làm nhóm và hỗ trợ khách hàng. | Gợi các tình huống cụ thể, giúp phân biệt problem với giải pháp. | Các ý chỉ là gợi ý phổ biến, không chứng minh được pain hay tần suất thực tế của tôi. | Giữ ý chia tiền và các hướng đọc đề, deadline, ticket; bỏ ý tìm lại quyết định họp như đã ghi ở CP1. |
| CP2 Problem Card | Nhờ phản biện card, bổ sung quy trình nháp và câu hỏi chuẩn bị pitch. | Chỉ ra actor rộng, bottleneck chưa rõ, metric chưa đo; tách tra cứu, soạn phản hồi và xử lý lỗi gốc. | Quy trình và mục tiêu gợi ý chưa được xác nhận với người thực hiện; không thể dùng làm dữ liệu đo sẵn có. | Chọn card ticket để trao đổi tiếp, kiểm tra và chỉnh lại. Giữ sơ đồ ở trạng thái nháp, ghi thời gian chưa đo và xem mốc 30–40 phút là ước lượng cần xác minh. |
| CP4 Research | Tìm giải pháp hỗ trợ ticket, làm rõ assumption map, insight và bảng tổng hợp phỏng vấn. | Gợi các cách tiếp cận mẫu trả lời, phân loại, soạn nháp; cung cấp tài liệu Zendesk, Intercom, Freshdesk và Jira Service Management. | Ban đầu dùng ba tính năng của một nền tảng; AI mở nguồn không có nghĩa tôi đã tự kiểm. Không thể suy rộng ba lời kể thành baseline chung. | Yêu cầu thêm nền tảng khác và đối chiếu ba snapshot. Bảng research và số người trong báo cáo vẫn cần rà lại; cần tự mở link trước khi chốt, không ghi là đã dùng thử công cụ. |
| CP5 Quy trình | Kiểm tra và tổng hợp lại phần CP5 của Nghĩa và bổ sung quy trình trước/sau vào báo cáo nhóm. | Giúp thể hiện handoff, bottleneck, người duyệt, boundary và fallback. | Bản đầu dài; các bước tổng hợp chưa phải quy trình đã được người vận hành xác nhận. | Kiểm tra bổ sung phần CP5 |
| CP5–6 Problem Statement | Kiểm tra và tổng hợp rà soát và hỗ trợ chỉnh v0; đối chiếu actor, metric và boundary với v1 do Vương phụ trách. | Làm rõ baseline, target, cách đo và giới hạn quyền AI; nhắc đo chất lượng bên cạnh tốc độ. | Mục tiêu giảm 20% và ngưỡng chất lượng là đề xuất, chưa có thử nghiệm chứng minh phù hợp. | Giữ baseline chưa đo và ghi rõ mục tiêu thử nghiệm. Nhóm cần tự chốt v0/v1 và lý do thay đổi; không coi bản nháp là Problem Statement đã kiểm chứng. |
| CP6 Mức can thiệp / quyết định | Tham khảo phản biện về No AI/Rule/Workflow/Agent và điều kiện thử nghiệm | Nhắc so sánh kho hướng dẫn/mẫu trả lời trước khi chọn AI, giữ người duyệt và ngưỡng dừng. | Khuyến nghị Workflow/Go dễ bị hiểu là đã chứng minh khả thi dù chưa có baseline, so sánh thực nghiệm hoặc quyền dùng dữ liệu. | Khi hỗ trợ tổng hợp, giữ phạm vi đề xuất là pilot nhỏ có điều kiện. Cả nhóm cần tự xác nhận quyết định; chưa đủ điều kiện thì tạm hoãn, không ghi pilot đã chạy hay hiệu quả đã đạt. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

- Một số ý tưởng còn chưa có tính ứng dụng cao, actor quá lớn. Một số ý tưởng cũng khá hay nhưng hơi khó để thực thi vì không có kiến thức chuyên ngành nhiều

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

- Khi thảo luận về problem card của Vương, nhóm đã nghiên cứu kết quả trước khi hiểu vấn đề, Vương đã trình bày lại về card và nhóm đã nghiên cứu lại kết quả

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

- Tôi đã đổi ý sau khi bị phản biện về các triển khai candidate chung của nhóm. Tôi đã nghĩ chỉ cần RAG và hỏi đáp thông thường nhưng Vương đã phản biện và đề xuất dùng LLM với model nhỏ (một phương án có độ chính xác cao hơn và hỏi đáp tốt hơn)

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

- Có khá nhiều người cũng có problem như candidate nhóm đã chọn. Ấn tượng nhất là interview thứ 2, bạn đã kể thêm một số câu chuyện khó khăn khác trong quá trình interview.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

- Dễ bị lan man sang vấn đề khác.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

- Nên giới hạn rõ ràng ranh giới phạm vi problem xử lý, chọn đúng actor và problem, nghiên cứu thêm về cách xử lý problem. Phản biện nhóm mạnh hơn về tính ứng dụng và lợi nhuận của từng candidate.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

- Đầu tiên, mỗi thành viên trong nhóm chọn ra 3 candidate mà bản thân thành viên đó thấy ổn nhất để tiến hành thảo luận chọn đề tài chung. Quá trình thảo luận, từng thành viên trình bày phần trình bày của mình và chọn ra phương án khả thi nhất. Đánh giá phương án dựa trên các yếu tố như (thời gian giảm so với phương án hiện tại nếu áp dụng AI, kinh phí tăng/giảm so với phương án hiện tại, phản hồi của người dùng sau khi phương án áp dụng). Mức độ hỗ trợ của AI giới hạn, vẫn ưu tiên research và thảo luận lại. Quyết định cuối cùng đã chọn được phương án Go - pilot phù hợp nhất với 3 yếu tố so sánh (thời gian/ kinh phí/ phản hồi)

---

## 7. Tài liệu tham khảo

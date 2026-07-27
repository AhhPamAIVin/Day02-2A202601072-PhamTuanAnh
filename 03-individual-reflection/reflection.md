# 03 — Individual Reflection

## Đóng góp của Phạm Tuấn Anh trong nhóm

| Hoạt động               | Tôi đã làm gì?                                                                                                                           | Kết quả                                                                                                    |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Scan cá nhân            | Quan sát và đưa ra **9 problems** từ trải nghiệm học tập, công việc và cuộc sống hằng ngày                                               | Nhóm có thêm nhiều candidate để phân loại và lựa chọn                                                      |
| Top 3 Problem Cards     | Chọn và mô tả 3 vấn đề nổi bật theo các trường: người gặp vấn đề, workflow hiện tại, bottleneck và dấu hiệu thật                         | Có đủ nội dung để pitching và so sánh với các vấn đề của thành viên khác                                   |
| Pitch                   | Pitch vấn đề phòng chống lừa đảo qua cuộc gọi và tin nhắn, tập trung vào người cao tuổi, trẻ em và gia đình                              | Đề tài được nhóm đưa vào shortlist và lựa chọn làm bài toán chính                                          |
| Challenge               | Đặt câu hỏi về việc giải pháp có thực sự cần AI hay chỉ cần blacklist số điện thoại; đặt vấn đề về quyền riêng tư khi phân tích cuộc gọi | Nhóm thu hẹp giải pháp, không phụ thuộc hoàn toàn vào AI và bổ sung human boundary                         |
| Leader                  | Điều phối thảo luận, tổng hợp ý tưởng của 6 thành viên và hỗ trợ nhóm thống nhất phạm vi bài toán                                        | Nhóm chốt được problem statement, workflow, metric và hướng triển khai chung                               |
| Workflow                | Tham gia xây dựng current workflow và future workflow cho quá trình xác minh cuộc gọi lừa đảo                                            | Nhóm xác định được bottleneck là thời gian xác minh quá lâu so với tốc độ thao túng của kẻ lừa đảo         |
| Rule / Workflow / Agent | So sánh ba hướng triển khai và lập luận chọn **Workflow có AI hỗ trợ** cho MVP                                                           | Nhóm tránh xây dựng Agent quá rộng và khó kiểm soát ngay từ đầu                                            |
| Research                | Tìm hiểu các giải pháp như blacklist, spam detection, kiểm tra link và phân tích nội dung hội thoại                                      | Nhóm xác định khoảng trống của giải pháp hiện tại là khó phát hiện số mới và hành vi lừa đảo theo ngữ cảnh |
| Slide                   | Tổng hợp nội dung và xây dựng slide trình bày về problem, pain point, giải pháp, workflow và impact                                      | Nhóm có tài liệu trực quan để pitching và trình bày ý tưởng                                                |
| Thiết kế giao diện      | Đề xuất giao diện cảnh báo cuộc gọi, risk score và màn hình thông báo cho người thân                                                     | Giải pháp trở nên dễ hình dung hơn và có thể dùng làm prototype cho MVP                                    |

---

## Scan problem và Top 3 Problem Cards

Trong phần scan cá nhân, tôi đã đưa ra **9 vấn đề** từ các lăng kính như:

- Tốn thời gian.
- Công việc lặp lại.
- Phụ thuộc vào người khác.
- AI có thể xử lý tốt hơn.
- Dễ sai sót hoặc gây hậu quả nghiêm trọng.

Ba vấn đề tôi đánh giá cao nhất để pitching với nhóm gồm:

### Problem Card 1 — Phòng chống lừa đảo cho người cao tuổi

| Field                 | Nội dung                                                                                                       |
| --------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Actor**             | Người cao tuổi sử dụng điện thoại và người thân trong gia đình                                                 |
| **Workflow hiện tại** | Nhận cuộc gọi lạ → nghe nội dung → nghi ngờ → hỏi người thân → tìm kiếm hoặc gọi ngân hàng để xác minh         |
| **Bottleneck**        | Người cao tuổi khó phân biệt thông tin thật và giả, thường phải phụ thuộc vào người thân                       |
| **Dấu hiệu thật**     | Người cao tuổi thường là đối tượng bị giả danh công an, ngân hàng, nhà mạng hoặc người thân để lừa chuyển tiền |
| **Impact**            | Có thể gây mất tiền, lộ thông tin cá nhân, mất tài khoản và ảnh hưởng tâm lý                                   |
| **Khả năng dùng AI**  | AI có thể phân tích dấu hiệu trong nội dung cuộc gọi và đưa ra cảnh báo nhanh                                  |

### Problem Card 2 — Tìm tài liệu học tập

| Field                 | Nội dung                                                                                |
| --------------------- | --------------------------------------------------------------------------------------- |
| **Actor**             | Học sinh, sinh viên và người tự học                                                     |
| **Workflow hiện tại** | Xác định nội dung cần học → tìm kiếm Google → mở nhiều nguồn → đọc và đánh giá tài liệu |
| **Bottleneck**        | Tài liệu phân tán và chất lượng không đồng đều                                          |
| **Dấu hiệu thật**     | Người học có thể mất khoảng 10–15 phút để tìm tài liệu phù hợp                          |
| **Impact**            | Giảm thời gian học thực tế và có thể tiếp nhận tài liệu sai                             |
| **Khả năng dùng AI**  | AI hỗ trợ tìm kiếm, lọc và tóm tắt tài liệu                                             |

### Problem Card 3 — Review code

| Field                 | Nội dung                                                                   |
| --------------------- | -------------------------------------------------------------------------- |
| **Actor**             | Developer, PM hoặc thành viên cần hiểu source code                         |
| **Workflow hiện tại** | Mở code → đọc từng file → tìm luồng xử lý → xác định lỗi hoặc điểm cần sửa |
| **Bottleneck**        | Mất nhiều thời gian để hiểu flow, đặc biệt với code dài hoặc chưa quen     |
| **Dấu hiệu thật**     | Thời gian review phụ thuộc lớn vào độ dài và độ phức tạp của code          |
| **Impact**            | Làm chậm quá trình phát triển, review và sửa lỗi                           |
| **Khả năng dùng AI**  | AI có thể giải thích code, tóm tắt flow và gợi ý vấn đề                    |

Sau khi pitching và thảo luận, nhóm lựa chọn **Problem Card phòng chống lừa đảo** vì actor rõ, hậu quả lớn và có thể xây dựng workflow cùng metric cụ thể.

---

## Bảng dùng AI trong reflection

| Phase                   | Tôi dùng AI để làm gì?                                                                 | AI hữu ích ở đâu?                                                                             | AI sai/hời hợt ở đâu?                                                     | Tôi sửa gì                                                                              |
| ----------------------- | -------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Scan                    | Nhờ AI gợi ý cách phân loại các vấn đề theo lăng kính                                  | Giúp tôi nhóm các vấn đề thành tốn thời gian, lặp lại, phụ thuộc người khác và AI làm tốt hơn | Một số vấn đề AI đề xuất quá chung, không có actor hoặc dấu hiệu thật     | Chỉ giữ những vấn đề tôi hoặc người xung quanh đã thực sự gặp                           |
| Problem Card            | Nhờ AI chuyển mô tả ngắn thành actor, workflow, bottleneck và impact                   | Giúp cấu trúc ý tưởng rõ hơn để pitching                                                      | AI có xu hướng phóng đại impact hoặc tự thêm số liệu chưa được kiểm chứng | Bỏ số liệu không có nguồn và giữ lại các dấu hiệu nhóm thực sự quan sát được            |
| Pitch                   | Nhờ AI rút gọn phần trình bày về vấn đề lừa đảo                                        | Giúp phần pitch đi thẳng vào người dùng, pain point và hậu quả                                | Ban đầu AI tập trung quá nhiều vào công nghệ thay vì vấn đề               | Tôi sửa lại để bắt đầu từ người cao tuổi, trẻ em và gia đình                            |
| Workflow                | Nhờ AI chuyển mô tả thành current state và future state                                | Giúp nhìn rõ các bước và xác định nơi AI can thiệp                                            | AI ban đầu đề xuất hệ thống tự chặn và tự thông báo quá nhiều             | Nhóm giới hạn lại: AI cảnh báo, người dùng hoặc gia đình quyết định cuối cùng           |
| Research                | Nhờ AI gợi ý các loại giải pháp hiện có như blacklist, spam detection và link checking | Giúp nhóm biết cần so sánh với giải pháp non-AI trước khi build                               | AI có thể đưa ra claim về hiệu quả mà không có bằng chứng                 | Chỉ giữ các pattern và không sử dụng số liệu chưa được xác minh                         |
| Rule / Workflow / Agent | Nhờ AI phân tích giải pháp thuộc Rule, Workflow hay Agent                              | Giúp thấy blacklist phù hợp với Rule, còn phân tích nhiều lớp phù hợp với Workflow            | AI ban đầu gọi toàn bộ sản phẩm là Agent dù các bước đã được xác định sẵn | Nhóm chọn Workflow có AI hỗ trợ cho MVP, chưa chọn Agent tự chủ                         |
| Slide                   | Nhờ AI hỗ trợ sắp xếp nội dung pitch deck                                              | Giúp hình thành flow Problem → Solution → Workflow → Metric → Impact                          | Một số slide có quá nhiều chữ và mang tính quảng cáo                      | Tôi rút gọn nội dung và ưu tiên sơ đồ, mockup và thông tin có thể chứng minh            |
| Giao diện               | Nhờ AI gợi ý màn hình cảnh báo và dashboard gia đình                                   | Giúp hình dung prototype nhanh                                                                | Một số thiết kế tạo cảm giác theo dõi hoặc xâm phạm quyền riêng tư        | Tôi sửa theo hướng chỉ hiển thị thông tin cần thiết và yêu cầu sự đồng ý của người dùng |

---

## Mạch hiểu bài cá nhân

### 1. Problem

Người cao tuổi và trẻ em khó nhận biết các cuộc gọi hoặc tin nhắn lừa đảo. Khi cảm thấy nghi ngờ, họ thường phải gọi người thân, tìm kiếm trên Internet hoặc liên hệ ngân hàng để xác minh.

### 2. Workflow

Workflow hiện tại:

```text
Nhận cuộc gọi hoặc tin nhắn
→ Nghe hoặc đọc nội dung
→ Cảm thấy nghi ngờ
→ Hỏi người thân
→ Tìm kiếm hoặc gọi đơn vị chính thức
→ Xác định thật hay lừa đảo
```

Workflow kỳ vọng:

```text
Nhận cuộc gọi hoặc tin nhắn
→ Rule kiểm tra số điện thoại hoặc link
→ Cảnh báo lần 1
→ AI phân tích nội dung nếu người dùng tiếp tục
→ Tính risk score
→ Cảnh báo lần 2
→ Thông báo người thân khi rủi ro cao
→ Con người quyết định cuối cùng
```

### 3. Bottleneck

Bottleneck nằm ở việc người dùng mất khoảng **5–10 phút để xác minh**, trong khi kẻ lừa đảo có thể tạo áp lực và yêu cầu hành động chỉ trong **30–60 giây**.

### 4. Metric

Metric chính:

- Giảm thời gian đưa ra cảnh báo ban đầu xuống dưới 30 giây.
- Giảm số lần người dùng bấm vào link lừa đảo.
- Giảm số lần người dùng cung cấp OTP hoặc chuyển tiền sau cảnh báo.
- Theo dõi precision, recall, false positive và false negative của hệ thống.

### 5. Boundary

AI chỉ đưa ra cảnh báo và giải thích dấu hiệu rủi ro.

AI không:

- Tự khẳng định tuyệt đối một người là kẻ lừa đảo.
- Tự gửi toàn bộ nội dung cuộc gọi cho gia đình khi chưa được đồng ý.
- Tự chặn giao dịch ngân hàng.
- Tự quyết định thay người dùng.
- Tự lưu nội dung nhạy cảm không cần thiết.

### 6. Vì sao chọn Workflow

Nhóm chọn **Workflow có AI hỗ trợ**, không chọn Agent tự chủ hoàn toàn vì:

- Các bước xử lý đã tương đối rõ.
- Blacklist và kiểm tra link có thể sử dụng Rule.
- AI chỉ cần can thiệp ở bước phân tích nội dung và đánh giá mức độ rủi ro.
- Thông báo cho người thân được kích hoạt theo điều kiện định trước.
- Workflow dễ kiểm thử, đo lường và kiểm soát quyền riêng tư hơn Agent.
- Con người vẫn phải xác minh và quyết định cuối cùng.

### 7. Vì sao quyết định Go với scope nhỏ

Nhóm quyết định **Go với MVP scope nhỏ** vì:

- Problem có actor và impact rõ.
- Có thể mô phỏng bằng transcript hoặc audio mẫu.
- Có thể đo thời gian cảnh báo và độ chính xác.
- Chưa cần truy cập trực tiếp vào cuộc gọi thật.
- Có thể kiểm tra trước khả năng phân loại của Rule và AI.
- Nếu AI không tốt hơn baseline, nhóm có thể rollback về blacklist và rule-based warning.

---

## Bài học của tôi

- Việc đầu tiên không phải là nghĩ xem sẽ dùng model hoặc công nghệ nào, mà phải xác định đúng **ai đang gặp vấn đề, họ đang làm gì và điểm nghẽn nằm ở đâu**.
- Pain point cần có dấu hiệu thật. Một vấn đề nghe nghiêm trọng nhưng không có actor, workflow hoặc evidence thì vẫn chưa phải problem statement tốt.
- Problem tốt không phải problem nghe “AI” nhất, mà là problem có **workflow, bottleneck, impact và metric rõ ràng**.
- Vẽ workflow giúp tôi nhìn thấy phần nào có thể giải quyết bằng rule, phần nào thực sự cần AI và phần nào phải để con người quyết định.
- Không phải bài toán nào cũng cần AI. Ví dụ, blacklist số điện thoại và kiểm tra URL có thể giải quyết tốt bằng rule hoặc cơ sở dữ liệu.
- AI chỉ nên được đặt tại điểm mà nó tạo ra giá trị rõ ràng. Trong đề tài này, AI phù hợp với việc phân tích nội dung hội thoại và nhận diện các dấu hiệu thao túng theo ngữ cảnh.
- Agent không phải đích đến mặc định. AI Guardian có thể được mô tả là một hệ thống thông minh, nhưng MVP phù hợp hơn với Workflow vì các bước đã xác định và liên quan đến dữ liệu nhạy cảm.
- Metric “giảm thời gian xác minh từ 10 phút xuống dưới 30 giây” cần được đo bằng thử nghiệm, không nên chỉ coi đó là một claim.
- Giải pháp chống lừa đảo không chỉ có bài toán accuracy. Nếu cảnh báo quá nhiều, người dùng có thể bỏ qua tất cả cảnh báo.
- Quyền riêng tư là một phần của problem và solution, không phải nội dung bổ sung ở cuối. Hệ thống phân tích cuộc gọi phải có consent và giới hạn dữ liệu rõ ràng.
- Research không phải để copy sản phẩm đã có, mà để biết phần nào đã được giải quyết tốt và khoảng trống nào vẫn còn tồn tại.
- Là leader, tôi học được rằng chốt một đề tài không chỉ dựa trên ý tưởng hấp dẫn nhất mà cần cân bằng impact, tính khả thi, metric và phạm vi thời gian của nhóm.

---

## Nếu làm lại

```text
Nếu làm lại, tôi sẽ phỏng vấn nhiều người cao tuổi, phụ huynh và thành viên
gia đình hơn trước khi chốt metric 10 phút → 30 giây.

Tôi cũng sẽ ghi lại cụ thể từng tình huống lừa đảo mà họ từng gặp,
thời gian họ cần để nhận ra vấn đề, hành động họ đã thực hiện
và thời điểm người thân có thể can thiệp.

Bên cạnh đó, tôi sẽ xây dựng baseline Rule trước, gồm blacklist,
kiểm tra số quốc tế, từ khóa và URL nguy hiểm, rồi mới so sánh
xem AI có thực sự cải thiện precision, recall và thời gian cảnh báo hay không.

Tôi cũng sẽ thu hẹp MVP ngay từ đầu vào một tình huống cụ thể,
ví dụ cuộc gọi giả danh ngân hàng yêu cầu cung cấp OTP,
thay vì cố gắng xử lý đồng thời cuộc gọi, tin nhắn, game
và mọi nền tảng mạng xã hội.
```

---

_Bản nộp cá nhân — Day 02 Lab_

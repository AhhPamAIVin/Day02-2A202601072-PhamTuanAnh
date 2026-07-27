# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên             | Mã học viên | Vai trò trong nhóm |
| --: | --------------------- | ----------- | ------------------ |
|   1 | Phạm Tuấn Anh         | 2A202601072 | Leader             |
|   2 | Đào Bình Minh         | 2A202601364 | Thành viên         |
|   3 | Nguyễn Việt Đăng Khoa | 2A202601794 | Thành viên         |
|   4 | Tống Duy An           | 2A202601995 | Thành viên         |
|   5 | Ngô Trọng Bảo         | 2A202601024 | Thành viên         |
|   6 |                       |             | Thành viên         |

## Group convergence

Nhóm có **6 thành viên**, mỗi người chia sẻ khoảng 3 vấn đề quan sát được trong cuộc sống, học tập và công việc. Tổng cộng nhóm thu được khoảng **18 candidates**.

| Cluster                        | Candidate examples                                                                      | Pattern chung                                                                     |
| ------------------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Hỗ trợ họp và ghi chép         | Ghi biên bản họp, nhận diện action items, quy đổi thời gian nói miệng thành ngày cụ thể | Nội dung trong cuộc họp dễ bị ghi thiếu, sai hoặc mất nhiều thời gian tổng hợp    |
| Tìm kiếm và tổng hợp thông tin | Tìm tài liệu học tập, tìm lại code cũ, tìm thông tin khóa học, tìm cảm biến tương đương | Thông tin nằm rải rác ở nhiều nguồn, người dùng mất thời gian tìm và đối chiếu    |
| Hỗ trợ lập trình và công việc  | Review code, viết commit message, sắp xếp mức độ ưu tiên công việc                      | Các thao tác lặp lại làm mất thời gian và dễ sai sót                              |
| Hỗ trợ người cao tuổi          | Phòng chống lừa đảo, nhắc uống thuốc, thiết kế giao diện dễ sử dụng                     | Người cao tuổi gặp khó khăn khi sử dụng công nghệ và thường cần người khác hỗ trợ |
| Quản lý thông tin cá nhân      | Quá nhiều tab trình duyệt, thông báo dài khó xác định việc cần làm                      | Người dùng bị quá tải thông tin và khó xác định nội dung quan trọng               |

Danh sách vấn đề ban đầu của nhóm gồm:

- Mất thời gian ghi lại biên bản họp.
- Mất khoảng 10–15 phút để tìm tài liệu học tập.
- Mất thời gian review code và hiểu flow của chương trình.
- Người cao tuổi khó xác định tính hợp pháp của thông tin và dễ bị lừa đảo.
- Quá nhiều tab trình duyệt, khó tìm tab cần sử dụng.
- Mất thời gian nhớ lại nội dung để viết commit message.
- Khó sắp xếp mức độ ưu tiên công việc từ nhiều email.
- Người cao tuổi hoặc người mắc bệnh mãn tính quên uống thuốc.
- Ứng dụng di động chưa có thiết kế phù hợp với người cao tuổi.
- Nhân viên kỹ thuật mất thời gian tìm cảm biến có thông số tương đương.
- Học viên mới khó tìm và hiểu đúng thông tin của khóa học.
- Thông báo dài khiến người đọc không xác định được mình phải làm gì.
- Mất thời gian quy đổi các mốc thời gian nói miệng thành ngày cụ thể.
- Ghi thiếu hoặc sai action items trong cuộc họp.
- Tốc độ gõ không theo kịp tốc độ nói.
- Mất thời gian xem lại video họp dài 1,5–2 giờ.
- Sinh viên mất 20–40 phút để tìm lại cú pháp hoặc code cũ.

---

## Shortlist và score

Sau khi gom nhóm và thảo luận, nhóm chọn ra ba candidate có tiềm năng nhất để đánh giá.

| Candidate                         | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain |   Tổng |
| --------------------------------- | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | -----: |
| AI Guardian – Phòng chống lừa đảo |        5 |           5 |                5 |              5 |             4 |                  5 |                4 | **33** |
| AI Meeting Assistant              |        5 |           5 |                4 |              4 |             5 |                  5 |                5 | **33** |
| AI Search cho tài liệu học tập    |        5 |           4 |                4 |              4 |             5 |                  4 |                5 | **31** |

Nhóm chọn: **AI Guardian – Nền tảng AI phòng chống lừa đảo qua cuộc gọi và tin nhắn**.

### Vì sao chọn

- Đối tượng chịu ảnh hưởng rõ ràng: người cao tuổi, trẻ em và gia đình.
- Vấn đề có tác động trực tiếp đến tài sản, dữ liệu cá nhân và sự an toàn của người dùng.
- Quy trình trước và sau khi áp dụng giải pháp có thể mô tả rõ.
- Có thể đo thời gian xác minh, tỷ lệ cảnh báo và hành vi của người dùng.
- AI có khả năng tạo ra giá trị khác biệt so với blacklist số điện thoại thông thường.
- Bài toán có cả thành phần Rule, Workflow và Agent để nhóm so sánh.
- Có thể thu nhỏ thành MVP trong phạm vi lab.

### Vì sao không chọn các bài khác

- **AI Meeting Assistant:** workflow rõ và dễ làm trong lab nhưng thị trường đã có nhiều sản phẩm như Otter, Fireflies, Zoom AI và Microsoft Teams Copilot. Khả năng tạo khác biệt thấp hơn.
- **AI Search cho tài liệu học tập:** dễ triển khai nhưng impact chủ yếu là tiết kiệm thời gian, chưa nghiêm trọng bằng thiệt hại tài chính và tâm lý do lừa đảo.
- **Review code:** khó xây dựng metric chất lượng thống nhất vì kết quả phụ thuộc ngôn ngữ, độ dài và độ phức tạp của code.
- **Nhắc uống thuốc:** có ý nghĩa xã hội nhưng phần cốt lõi có thể được giải quyết bằng rule và reminder, chưa nhất thiết phải sử dụng AI.

---

## Quick validation

Nhóm thực hiện phỏng vấn nhanh người cao tuổi, phụ huynh và sinh viên để kiểm tra mức độ tồn tại của vấn đề.

> Lưu ý: Các con số dưới đây cần được thay bằng kết quả khảo sát thực tế của nhóm trước khi nộp.

| Nguồn                    | Số người | Tín hiệu xác nhận                                                                                             | Tín hiệu phản bác                                                   | Nhóm sửa problem thế nào                                                                 |
| ------------------------ | -------: | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Phỏng vấn người cao tuổi |        3 | 2/3 người từng nhận cuộc gọi tự xưng là công an, ngân hàng hoặc nhà mạng; đều phải gọi người thân để xác minh | 1 người nói thường không nghe số lạ                                 | Không chỉ chặn số lạ; tập trung hỗ trợ xác minh khi người dùng vẫn nghe máy              |
| Phỏng vấn phụ huynh      |        3 | 3/3 lo ngại trẻ bị dụ bấm link, cung cấp tài khoản hoặc mua vật phẩm trong game                               | Phụ huynh không muốn ứng dụng đọc toàn bộ nội dung riêng tư của trẻ | Chỉ phân tích tín hiệu rủi ro cần thiết và phải có cơ chế xin phép, giới hạn dữ liệu     |
| Mini poll trong lớp      |       10 | Nhiều người từng nhận cuộc gọi hoặc tin nhắn nghi ngờ lừa đảo                                                 | Một số người cho rằng blacklist và Google Search đã đủ              | Thu hẹp khác biệt sản phẩm vào phân tích nội dung và hỗ trợ gia đình theo thời gian thực |

Insight sau validation:

```text
Pain thật không chỉ nằm ở việc nhận được một cuộc gọi lạ.

Pain nằm ở việc người dùng không thể xác minh đủ nhanh trong 30–60 giây đầu,
trong khi kẻ lừa đảo liên tục tạo áp lực, đe dọa hoặc yêu cầu chuyển tiền.

Người cao tuổi và trẻ em thường phải phụ thuộc vào người thân,
nhưng gia đình không phải lúc nào cũng có mặt để hỗ trợ ngay.
```

---

## Research giải pháp

Nhóm tìm hiểu các hướng giải quyết đã tồn tại, không giả định rằng phải tự xây dựng toàn bộ hệ thống từ đầu.

| Nguồn / tool / case                        | Link                                                                         | Họ giải quyết phần nào?                           | Điểm mạnh                                                   | Khoảng trống / rủi ro                                                            | Bài học cho nhóm                                             |
| ------------------------------------------ | ---------------------------------------------------------------------------- | ------------------------------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Truecaller                                 | https://www.truecaller.com/                                                  | Nhận diện số gọi đến, spam và blacklist cộng đồng | Có cơ sở dữ liệu số điện thoại lớn, cảnh báo trước khi nghe | Phụ thuộc vào số đã từng được báo cáo; số mới hoặc VoIP có thể chưa bị phát hiện | Blacklist phù hợp cho lớp phòng thủ đầu tiên nhưng chưa đủ   |
| Google Phone – Caller ID & Spam Protection | https://support.google.com/phoneapp/answer/3459196                           | Cảnh báo cuộc gọi spam và số nghi ngờ             | Tích hợp trực tiếp trên một số điện thoại Android           | Chủ yếu đánh giá số gọi đến, chưa tập trung hỗ trợ gia đình                      | Có thể học cách thiết kế cảnh báo đơn giản, dễ hiểu          |
| Apple Silence Unknown Callers              | https://support.apple.com/guide/iphone/avoid-unwanted-calls-iph6c8e1e1b0/ios | Im lặng cuộc gọi từ số không xác định             | Đơn giản, bảo vệ người dùng khỏi số lạ                      | Có thể bỏ lỡ cuộc gọi hợp lệ; không phân tích nội dung                           | Chặn toàn bộ số lạ tạo nhiều false positive                  |
| Cổng cảnh báo an toàn thông tin Việt Nam   | https://canhbao.khonggianmang.vn/                                            | Tiếp nhận phản ánh và cảnh báo lừa đảo trực tuyến | Nguồn cảnh báo chính thống                                  | Người dùng vẫn phải chủ động tra cứu và đọc cảnh báo                             | Có thể dùng dữ liệu cảnh báo làm một nguồn cho risk score    |
| Google Safe Browsing                       | https://safebrowsing.google.com/                                             | Phát hiện website và link nguy hiểm               | Tốt cho kiểm tra URL độc hại                                | Không hiểu toàn bộ bối cảnh cuộc gọi hoặc tin nhắn                               | Link checking nên là một module riêng trong hệ thống         |
| Speech-to-Text                             | Không cố định nhà cung cấp                                                   | Chuyển giọng nói trong cuộc gọi thành văn bản     | Cho phép phân tích nội dung bằng mô hình ngôn ngữ           | Có độ trễ, sai accent, dữ liệu thoại nhạy cảm                                    | Cần xử lý cục bộ hoặc giảm tối đa dữ liệu gửi lên server     |
| LLM / Scam Classification                  | Không cố định nhà cung cấp                                                   | Phân tích câu nói, ý định và dấu hiệu thao túng   | Có thể nhận diện số mới dựa trên hành vi thay vì blacklist  | Có hallucination, false positive và chi phí xử lý                                | AI chỉ nên đưa ra cảnh báo, không thay người dùng quyết định |

Research takeaway:

```text
Không nên chỉ xây dựng một blacklist số điện thoại,
vì kẻ lừa đảo có thể sử dụng số mới, số quốc tế hoặc VoIP.

Hướng hợp lý hơn là phòng thủ nhiều lớp:

Rule kiểm tra số và link
→ Workflow phân tích tín hiệu
→ AI đánh giá nội dung
→ Cảnh báo người dùng
→ Thông báo cho người thân khi rủi ro cao.

Trong MVP, hệ thống không tự chặn hoặc tự can thiệp vào tài khoản ngân hàng.
Người dùng và gia đình vẫn là người đưa ra quyết định cuối cùng.
```

---

## Workflow before/after

File nhóm nộp kèm:

```text
02-group-problem-statement-workflow.png
02-group-problem-statement-workflow.pdf
hoặc
02-group-problem-statement-workflow.md
```

Nội dung workflow:

```text
CURRENT STATE — 7 bước, khoảng 5–10 phút

[1 Nhận cuộc gọi hoặc tin nhắn lạ]
→ [2 Người dùng tự đánh giá]
→ [3 Tiếp tục nghe hoặc đọc nội dung]
→ [4 Cảm thấy nghi ngờ]
→ [5 Gọi hỏi người thân]
→ [6 Tìm kiếm Google/Facebook hoặc gọi ngân hàng]
→ [7 Xác định thật hay lừa đảo]

Bottleneck:
Người dùng phải tự nhận diện dấu hiệu và tìm người hỗ trợ.

Trong khi quá trình xác minh mất 5–10 phút,
kẻ lừa đảo có thể tạo áp lực và yêu cầu hành động chỉ trong 30–60 giây.


FUTURE STATE — Phòng thủ 3 lớp, mục tiêu cảnh báo dưới 30 giây

[1 Nhận cuộc gọi hoặc tin nhắn]
→ [2 Rule kiểm tra số, đầu số, blacklist và link]
→ [3 Hiển thị cảnh báo lần 1 nếu có tín hiệu bất thường]
→ [4 Nếu người dùng vẫn tiếp tục, AI phân tích nội dung]
→ [5 Tính risk score và cảnh báo lần 2]
→ [6 Nếu rủi ro cao hoặc cảnh báo bị bỏ qua, thông báo người thân]
→ [7 Người dùng hoặc gia đình quyết định dừng và xác minh]

Fallback:
AI không chắc chắn
→ Hiển thị "Chưa thể xác minh"
→ Khuyến nghị không chuyển tiền, không đọc OTP và gọi lại qua kênh chính thức.

AI cảnh báo sai
→ Người dùng có thể bỏ qua cảnh báo
→ Báo cáo false positive để cải thiện hệ thống.

Bottleneck mới:
Người dùng hoặc người thân xác nhận quyết định cuối cùng.

Đây là bottleneck chấp nhận được vì AI không nên tự quyết định
một cuộc gọi chắc chắn là lừa đảo hoặc tự động chặn mọi cuộc gọi.
```

Before/after impact:

| Metric               |                                   Trước |                                           Sau kỳ vọng | Ghi chú                                |
| -------------------- | --------------------------------------: | ----------------------------------------------------: | -------------------------------------- |
| Thời gian xác minh   |                               5–10 phút |                   Dưới 30 giây để có cảnh báo ban đầu | Target chính                           |
| Nguồn hỗ trợ         | Google, Facebook, ngân hàng, người thân |                 Risk score và cảnh báo trong ứng dụng | Không loại bỏ hoàn toàn bước xác minh  |
| Phụ thuộc người thân |                                     Cao |                           Giảm, chỉ thông báo khi cần | Gia đình vẫn là human boundary         |
| Phát hiện số mới     |             Thấp nếu chỉ dùng blacklist |                         Có thể phát hiện qua nội dung | Cần kiểm chứng bằng dữ liệu thử nghiệm |
| Hành động nguy hiểm  |        Có thể xảy ra trước khi xác minh | Cảnh báo trước khi chuyển tiền, đọc OTP hoặc bấm link | Metric cần đo trong pilot              |
| Risk mới             |              Không có AI false positive |  Có false positive, false negative và rủi ro riêng tư | Cần consent và human review            |

---

## Problem Statement v0

| Field              | Nội dung                                                                                                                                                                                        |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**          | Người cao tuổi và trẻ em sử dụng điện thoại; thành viên gia đình là người cài đặt, quản lý và có thể chi trả cho ứng dụng.                                                                      |
| **Workflow**       | Nhận cuộc gọi hoặc tin nhắn lạ → nghe/đọc nội dung → cảm thấy nghi ngờ → hỏi người thân → tìm kiếm trên Internet hoặc gọi ngân hàng → quyết định có tiếp tục hay không.                         |
| **Bottleneck**     | Người dùng khó nhận ra dấu hiệu lừa đảo và mất khoảng 5–10 phút để xác minh, trong khi kẻ lừa đảo chỉ cần 30–60 giây để tạo áp lực.                                                             |
| **Impact**         | Người dùng có thể chuyển tiền, tiết lộ OTP, cung cấp dữ liệu cá nhân, bấm link độc hại hoặc mất tài khoản. Gia đình thường chỉ biết sau khi sự việc đã xảy ra.                                  |
| **Success Metric** | Giảm thời gian đưa ra cảnh báo ban đầu từ khoảng 10 phút xuống dưới 30 giây; giảm tỷ lệ bấm link, cung cấp OTP hoặc chuyển tiền sau cảnh báo.                                                   |
| **Boundary**       | AI không tự kết luận một người là tội phạm, không tự gửi nội dung cuộc gọi cho gia đình khi chưa có sự đồng ý, không tự chặn tài khoản ngân hàng và không thay người dùng quyết định cuối cùng. |

---

## Rule / Workflow / Agent

| Mức          | Phương án                                                                                                           | Khi nào đủ                                                                           | Rủi ro                                                                      | Chọn?                                                |
| ------------ | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------- | ---------------------------------------------------- |
| **Rule**     | Kiểm tra blacklist, số quốc tế, VoIP, từ khóa, URL nguy hiểm và quy tắc như “không cung cấp OTP”                    | Đủ với số đã được báo cáo, link đã biết hoặc mẫu lừa đảo đơn giản                    | Không phát hiện tốt số mới, cách nói mới hoặc ngữ cảnh phức tạp             | Không chọn làm toàn bộ, nhưng sử dụng ở lớp đầu tiên |
| **Workflow** | Kiểm tra số → chuyển giọng nói thành văn bản → phân tích nội dung → tính risk score → cảnh báo → thông báo gia đình | Hợp với MVP vì các bước và điều kiện đã xác định rõ                                  | Sai ở một bước có thể ảnh hưởng kết quả; cần xử lý độ trễ và quyền riêng tư | **Chọn cho MVP**                                     |
| **Agent**    | Tự chọn công cụ, truy vấn nhiều nguồn, hỏi người dùng, gọi người thân hoặc tự thực hiện hành động                   | Chỉ cần khi hệ thống phải tự lập kế hoạch và xử lý nhiều tình huống không định trước | Quá nhiều quyền, khó kiểm soát, có thể vi phạm riêng tư hoặc cảnh báo sai   | Chưa chọn trong MVP                                  |

Mức chọn:

```text
Workflow có AI hỗ trợ.

Không chọn Agent tự chủ hoàn toàn trong MVP.
```

Vì sao:

- Kiểm tra số điện thoại và link có thể dùng rule hoặc API.
- Quy trình xử lý cuộc gọi có các bước và điều kiện tương đối rõ.
- AI được sử dụng tại bước phân tích nội dung và đánh giá mức độ rủi ro.
- Việc thông báo người thân chỉ xảy ra khi đạt điều kiện đã định trước.
- Người dùng và gia đình vẫn là người đưa ra quyết định cuối cùng.
- Chưa cần agent tự lập kế hoạch hoặc tự thực hiện hành động nhạy cảm.
- Cách tiếp cận workflow dễ đo lường, kiểm thử và giới hạn quyền hơn.

---

## Problem Statement v1

| Field                            | Nội dung                                                                                                                                                                                                 |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                        | Người cao tuổi và trẻ em là người được bảo vệ; thành viên gia đình là người cài đặt, quản lý và nhận cảnh báo hỗ trợ.                                                                                    |
| **Workflow**                     | Cuộc gọi hoặc tin nhắn đến → kiểm tra số/link → cảnh báo lần 1 → phân tích nội dung nếu người dùng tiếp tục → cảnh báo lần 2 → thông báo người thân khi rủi ro cao.                                      |
| **Bottleneck**                   | Người dùng không nhận diện đủ nhanh các dấu hiệu giả danh, đe dọa, yêu cầu chuyển tiền, yêu cầu OTP hoặc gửi link lạ trong 30–60 giây đầu.                                                               |
| **Impact**                       | Có thể gây mất tiền, mất tài khoản, lộ dữ liệu cá nhân và ảnh hưởng tâm lý. Gia đình khó hỗ trợ trước khi hành động nguy hiểm xảy ra.                                                                    |
| **Success Metric**               | Cảnh báo rủi ro trong dưới 30 giây; giảm tỷ lệ bấm link lừa đảo; giảm tỷ lệ cung cấp OTP hoặc chuyển tiền sau cảnh báo; theo dõi precision, recall và false positive rate.                               |
| **Boundary**                     | Không tự nghe hoặc lưu toàn bộ cuộc gọi khi chưa được đồng ý; không tự gửi bản ghi đầy đủ cho người thân; không tự chặn giao dịch; không khẳng định tuyệt đối một cuộc gọi là lừa đảo.                   |
| **AI intervention point**        | Sau khi rule kiểm tra số/link và trong lúc người dùng tiếp tục tương tác với nội dung đáng ngờ. AI phân tích transcript hoặc tín hiệu đã được cho phép để tạo risk score.                                |
| **Mức chọn**                     | Workflow: rule kiểm tra tín hiệu cơ bản → AI phân tích nội dung → decision engine cảnh báo → người dùng hoặc gia đình xác minh.                                                                          |
| **Rủi ro & người thật kiểm tra** | Risk: cảnh báo nhầm, bỏ sót lừa đảo, sai transcript, độ trễ, lộ dữ liệu thoại. Người thật kiểm tra: người dùng hoặc gia đình xác minh qua kênh chính thức trước khi chuyển tiền hoặc cung cấp thông tin. |

---

## Final decision

Decision:

```text
Go với scope nhỏ:

Xây dựng MVP theo hướng Workflow có AI hỗ trợ,
không xây dựng Agent tự chủ hoàn toàn.
```

Pilot nhỏ nhất:

- Tập trung trước vào **cuộc gọi giả danh yêu cầu chuyển tiền hoặc cung cấp OTP**.
- Chưa cần tích hợp trực tiếp vào cuộc gọi thật trong phiên bản đầu.
- Chuẩn bị một tập audio hoặc transcript gồm:
  - Cuộc gọi bình thường.
  - Cuộc gọi nghi ngờ.
  - Cuộc gọi có dấu hiệu lừa đảo rõ.
- Rule kiểm tra các từ khóa và hành vi cơ bản.
- AI phân tích transcript và trả về:
  - Risk score.
  - Dấu hiệu phát hiện được.
  - Cảnh báo ngắn, dễ hiểu.
  - Hành động an toàn được đề xuất.
- Hiển thị cảnh báo trên giao diện mô phỏng.
- Mô phỏng thông báo cho thành viên gia đình.
- Không tự động gọi, nhắn hoặc gửi bản ghi thật trong pilot.

Metric của pilot:

- Thời gian từ khi nhận transcript đến khi hiển thị cảnh báo.
- Precision: trong các cảnh báo lừa đảo, bao nhiêu cảnh báo là đúng.
- Recall: trong các tình huống lừa đảo, hệ thống phát hiện được bao nhiêu.
- False positive rate.
- Số lần người thử nghiệm chọn không bấm link hoặc không cung cấp OTP sau cảnh báo.
- Mức độ dễ hiểu của cảnh báo.
- Mức độ người dùng tin tưởng nhưng không phụ thuộc mù quáng vào AI.

Exit / rollback:

- Nếu false positive quá cao, hạ hệ thống xuống mức “gợi ý xác minh” thay vì “cảnh báo nguy hiểm”.
- Nếu AI không phát hiện tốt hơn rule-based baseline, chỉ giữ blacklist, URL checker và bộ quy tắc an toàn.
- Nếu thời gian xử lý vượt quá mục tiêu, giảm độ phức tạp mô hình hoặc chỉ phân tích các đoạn hội thoại quan trọng.
- Nếu transcript sai làm thay đổi kết luận, không cho phép hệ thống đưa ra cảnh báo mức cao chỉ dựa trên transcript.
- Nếu người dùng không đồng ý chia sẻ nội dung thoại, hệ thống chỉ sử dụng lớp kiểm tra số và link.
- Nếu AI tạo thông tin không có trong cuộc gọi, không hiển thị phần giải thích đó cho người dùng.

Decision rationale:

- Problem xuất phát từ quan sát thực tế của thành viên trong nhóm.
- Actor, workflow, bottleneck và impact đều xác định được.
- Có thể so sánh rõ Rule, Workflow và Agent.
- AI được đặt tại một intervention point cụ thể.
- Không sử dụng AI cho những phần rule đã giải quyết tốt.
- Có human boundary rõ ràng.
- Có thể xây dựng bản mô phỏng trong phạm vi lab.
- Có metric kỹ thuật và metric hành vi để đánh giá.
- Có phương án fallback và rollback khi AI không đạt yêu cầu.

---

## Tóm tắt Problem Statement

```text
Người cao tuổi và trẻ em thường không thể nhận diện đủ nhanh
các cuộc gọi hoặc tin nhắn lừa đảo.

Quá trình tự xác minh có thể mất 5–10 phút,
trong khi kẻ lừa đảo chỉ cần 30–60 giây để tạo áp lực
và yêu cầu nạn nhân chuyển tiền, cung cấp OTP hoặc bấm link.

Nhóm đề xuất AI Guardian theo hướng Workflow phòng thủ nhiều lớp:

Rule kiểm tra số và link
→ AI phân tích nội dung
→ Cảnh báo theo risk score
→ Thông báo cho người thân khi cần
→ Con người xác minh và quyết định cuối cùng.

Mục tiêu là đưa ra cảnh báo ban đầu trong dưới 30 giây,
không tự động thay người dùng đưa ra quyết định nhạy cảm.
```

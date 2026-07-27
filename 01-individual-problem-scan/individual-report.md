# 01 — Individual Problem Scan

## Scan rộng

Em scan **9 problems**, vượt mức tối thiểu 5.

| #   | Lăng kính          | Problem quan sát được                           | Ai chịu ảnh hưởng?                  | Dấu hiệu thật                                                  |
| --- | ------------------ | ----------------------------------------------- | ----------------------------------- | -------------------------------------------------------------- |
| 1   | Lặp lại            | Quản lý công việc và học tập hằng ngày          | Sinh viên, người đi làm             | Mỗi ngày phải cập nhật và theo dõi nhiều đầu việc              |
| 2   | Tốn thời gian      | Dịch tài liệu tiếng Anh                         | Sinh viên, người đi làm             | Mất 30–60 phút để dịch và đọc hiểu một tài liệu                |
| 3   | Tốn thời gian      | Ghi biên bản họp                                | Sinh viên, nhóm dự án, doanh nghiệp | Mất 20–40 phút sau mỗi cuộc họp để tổng hợp                    |
| 4   | Tốn thời gian      | Tìm kiếm tài liệu phục vụ học tập và làm việc   | Sinh viên, người nghiên cứu         | Phải tìm trên nhiều nguồn, mất 20–30 phút/lần                  |
| 5   | Pain từ người khác | Cuộc gọi lừa đảo                                | Người sử dụng điện thoại            | Nhận nhiều cuộc gọi không rõ nguồn gốc, khó phân biệt thật giả |
| 6   | Lặp lại            | Sắp xếp và ưu tiên công việc                    | Sinh viên, nhân viên                | Thường xuyên thay đổi thứ tự ưu tiên khi có việc phát sinh     |
| 7   | Tốn thời gian      | Tìm đúng thông tin nhưng chưa chắc đã hiểu đúng | Sinh viên, người mới học            | Mất nhiều thời gian đọc nhưng vẫn phải tra cứu lại             |
| 8   | Tốn thời gian      | Đọc và tóm tắt tài liệu dài                     | Sinh viên, nhân viên văn phòng      | Một tài liệu dài có thể mất hơn 1 giờ để đọc                   |
| 9   | Pain từ người khác | Theo dõi tiến độ làm việc nhóm                  | Nhóm dự án                          | Phải hỏi từng thành viên hoặc kiểm tra nhiều nền tảng          |

Vì sao phần scan này mạnh:

- Có scan rộng trước khi chọn ý tưởng.
- Bao phủ đủ các lăng kính: lặp lại, tốn thời gian, AI có thể hỗ trợ và khó khăn từ người khác.
- Mỗi vấn đề đều xác định được actor và dấu hiệu thực tế.
- Xuất phát từ trải nghiệm hằng ngày thay vì nghĩ ngay đến giải pháp AI.

---

## Top 3

| Rank | Problem                                      | Vì sao chọn                                                   | Điều còn chưa chắc                        |
| ---- | -------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------- |
| 1    | Tìm đúng thông tin nhưng chưa chắc hiểu đúng | Pain phổ biến, AI có lợi thế lớn trong tìm kiếm và giải thích | Đo chất lượng câu trả lời như thế nào     |
| 2    | Ghi biên bản họp                             | Workflow rõ ràng, tiết kiệm nhiều thời gian                   | Độ chính xác khi nhận diện giọng nói      |
| 3    | Tìm kiếm tài liệu                            | Có nhu cầu lớn trong học tập và nghiên cứu                    | Chất lượng nguồn dữ liệu và mức độ đầy đủ |

---

# Problem Card #1 — Tìm đúng thông tin nhưng chưa chắc hiểu đúng

**Problem 1 câu:**  
Người học mất nhiều thời gian để tìm đúng thông tin và ngay cả khi đã tìm thấy vẫn chưa chắc hiểu đúng nội dung vì phải đọc từ nhiều nguồn khác nhau.

**Actor:**  
Sinh viên, người mới học hoặc người cần tìm hiểu một chủ đề mới.

**Thời điểm / bối cảnh:**  
Khi làm bài tập, nghiên cứu tài liệu hoặc tìm hiểu kiến thức phục vụ công việc.

**Current workflow:**

```text
1. Mở Google
2. Tìm kiếm từ khóa
3. Mở nhiều website
4. Đọc và so sánh thông tin
5. Tổng hợp lại
6. Nếu chưa hiểu → tiếp tục tìm kiếm
```

**Bottleneck:**  
Bước 4 và bước 6 chiếm nhiều thời gian nhất vì phải đọc nhiều nguồn nhưng vẫn chưa chắc hiểu đúng.

**Impact:**  
Mỗi lần tìm hiểu có thể mất từ 30–60 phút. Nếu tìm sai nguồn hoặc hiểu sai sẽ mất thêm thời gian kiểm chứng.

**Success metric:**

- Giảm thời gian tìm hiểu từ khoảng 45 phút xuống dưới 15 phút.
- Người dùng hiểu đúng nội dung sau lần tra cứu đầu tiên.

**Non-AI alternative:**

Google Search, Wikipedia hoặc tài liệu chính thức giúp tìm thông tin nhưng người dùng vẫn phải tự đọc, chọn lọc và tổng hợp.

**AI hypothesis:**

AI có thể tìm kiếm, tổng hợp nhiều nguồn và giải thích nội dung theo đúng ngữ cảnh, đồng thời trả lời các câu hỏi tiếp theo.

**Quick gut:**

Knowledge Assistant / RAG.

### Draft current workflow

```text
CURRENT STATE — 45 phút

[1 Google Search: 5']
→ [2 Đọc nhiều nguồn: 20']
→ [3 So sánh thông tin: 10']
→ [4 Tổng hợp: 5']
→ [5 Tra cứu lại nếu chưa hiểu: 5']
```

### Draft future workflow

```text
FUTURE STATE — 12 phút

[1 Đặt câu hỏi: 1']
→ [2 AI tìm kiếm & tổng hợp: 3']
→ [3 AI giải thích theo ngữ cảnh: 2']
→ [4 Người dùng đọc & hỏi tiếp: 6']

Fallback: AI trả lời chưa đủ → mở tài liệu gốc để kiểm chứng.
```

---

## Problem Cards #2 và #3 — tóm tắt

| Card              | Actor                       | Bottleneck                       | Metric                 | Quick gut    | Vì sao chưa chọn làm #1                            |
| ----------------- | --------------------------- | -------------------------------- | ---------------------- | ------------ | -------------------------------------------------- |
| Ghi biên bản họp  | Sinh viên, nhóm dự án       | Ghi chép và tóm tắt sau cuộc họp | 30 phút → dưới 10 phút | Workflow     | Phụ thuộc chất lượng ghi âm                        |
| Tìm kiếm tài liệu | Sinh viên, người nghiên cứu | Tìm trên nhiều nguồn và chọn lọc | 30 phút → dưới 10 phút | RAG / Search | Khá gần với Problem #1 nên phạm vi dễ bị chồng lấn |

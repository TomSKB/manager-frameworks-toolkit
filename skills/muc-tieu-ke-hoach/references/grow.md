# GROW Model

## Định nghĩa
Quy trình coaching/lập kế hoạch hành động theo 4 bước, đi từ mục tiêu tới hành động cụ thể:
- **Goal** — muốn đạt được điều gì.
- **Reality** — tình hình hiện tại, đã thử gì, rào cản gì.
- **Options** — các phương án khả thi để đi từ Reality tới Goal.
- **Will** (hoặc Way forward) — chốt lại 1 phương án thành cam kết hành động cụ thể, có deadline.

Đây là công cụ **đối thoại** (coaching 1-1 hoặc tự vấn), nên giữ giọng văn đặt câu hỏi dẫn dắt, không phán quyết áp đặt.

## Input cần thu thập
1. Goal — mục tiêu/khó khăn cần giải quyết (nếu còn mơ hồ, có thể gợi ý chạy qua SMART trước).
2. Reality — nếu người dùng chưa kể, hỏi khai thác: đã thử gì rồi, rào cản lớn nhất là gì, có nguồn lực gì sẵn có.

## Output — luôn theo đúng cấu trúc
```
## Goal — Mục tiêu
[Mục tiêu cụ thể]

## Reality — Hiện trạng
[Tình hình hiện tại, đã thử gì, rào cản chính]

## Options — Phương án khả thi
1. [Phương án 1 — ưu/nhược điểm ngắn]
2. [Phương án 2]
3. [Phương án 3]

## Will — Cam kết hành động
[Chọn 1 phương án, biến thành hành động cụ thể: ai làm, làm gì, khi nào xong, bước đầu tiên là gì]
```
Ở bước Options, Claude nên **chủ động đề xuất phương án** (ít nhất 3), không chỉ hỏi ngược lại người dùng.

## Ví dụ (rút gọn)
**Input**: "Tôi muốn cải thiện tỷ lệ giữ chân nhân viên trong team, hiện đang nghỉ nhiều quá mà chưa biết bắt đầu từ đâu."
- Goal: giảm tỷ lệ nghỉ việc trong team xuống mức chấp nhận được trong 2 quý tới.
- Reality: chưa có khảo sát exit interview có hệ thống, chưa rõ nguyên nhân chính.
- Options: (1) làm exit interview có cấu trúc cho 3 người nghỉ gần nhất, (2) khảo sát nhanh mức độ hài lòng của người còn lại, (3) rà lại chính sách đãi ngộ so với thị trường.
- Will: trong 2 tuần tới, thực hiện phương án (1) trước vì rẻ và nhanh nhất, tổng hợp kết quả rồi mới quyết định bước tiếp theo.

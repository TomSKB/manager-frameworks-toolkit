# Toyota 8-Step Practical Problem Solving

## Định nghĩa
Quy trình giải quyết vấn đề vận hành/chất lượng **lặp lại**, nhấn mạnh đào sâu nguyên nhân gốc và chuẩn hóa để không tái diễn (khác McKinsey 7-step — xem `mckinsey-7step.md` — vốn thiên về vấn đề chiến lược, ra quyết định một lần):

1. **Làm rõ vấn đề**.
2. **Chia nhỏ vấn đề**.
3. **Đặt mục tiêu khắc phục** (mức cải thiện mong muốn, có deadline).
4. **Phân tích nguyên nhân gốc** — thường dùng kỹ thuật "5 Whys" (hỏi "vì sao" liên tiếp 5 lần để đi từ triệu chứng tới nguyên nhân gốc).
5. **Đề ra biện pháp đối phó** (counter-measures) nhắm đúng nguyên nhân gốc, không chỉ xử lý triệu chứng.
6. **Triển khai biện pháp**.
7. **Xác nhận kết quả** — đo lại để chắc chắn vấn đề đã được giải quyết.
8. **Chuẩn hóa & chia sẻ thành công** — đưa vào quy trình chuẩn để không tái diễn, chia sẻ bài học cho các bộ phận khác.

## Input cần thu thập
Mô tả vấn đề vận hành lặp lại + tần suất/mức độ ảnh hưởng nếu có (bao nhiêu lần, ảnh hưởng gì). Nếu người dùng chưa nói rõ đây có "lặp lại" hay không, hỏi xác nhận — đây là tiêu chí chọn framework này thay vì McKinsey 7-step.

## Output — luôn theo đúng cấu trúc
```
## 1. Vấn đề
[Mô tả rõ]

## 2. Chia nhỏ vấn đề
[Các thành phần/khía cạnh của vấn đề]

## 3. Mục tiêu khắc phục
[Mức cải thiện mong muốn + deadline]

## 4. Phân tích nguyên nhân gốc (5 Whys)
Vì sao 1: ...
Vì sao 2: ...
Vì sao 3: ...
Vì sao 4: ...
Vì sao 5 (nguyên nhân gốc): ...

## 5. Biện pháp đối phó
[Nhắm đúng nguyên nhân gốc ở bước 4, không chỉ xử lý triệu chứng]

## 6. Kế hoạch triển khai
[Ai làm, khi nào]

## 7. Cách xác nhận kết quả
[Đo bằng chỉ số gì, khi nào đo lại]

## 8. Chuẩn hóa & lan tỏa
[Đưa vào quy trình/checklist chuẩn nào, chia sẻ cho bộ phận nào khác]
```

## Ví dụ (rút gọn, 5 Whys)
**Input**: "Đơn hàng giao trễ đã là lần thứ 3 trong tháng, tôi cần xử lý dứt điểm không để lặp lại."
- Vì sao 1: giao trễ vì đơn xuất kho chậm.
- Vì sao 2: xuất kho chậm vì thiếu người xác nhận đơn vào cuối ngày.
- Vì sao 3: thiếu người vì lịch ca chưa tính đến giờ cao điểm đơn hàng.
- Vì sao 4: lịch ca được lập cố định từ đầu tháng, không cập nhật theo mùa cao điểm.
- Vì sao 5 (gốc): chưa có quy trình rà soát lịch ca theo biến động đơn hàng thực tế.
- → Biện pháp: thêm bước rà soát lịch ca hàng tuần dựa trên dự báo đơn hàng, chuẩn hóa thành quy trình cố định.

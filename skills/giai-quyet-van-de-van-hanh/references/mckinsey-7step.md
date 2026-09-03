# McKinsey 7-Step Problem Solving

## Định nghĩa
Quy trình giải quyết vấn đề kinh doanh có cấu trúc, dùng cho vấn đề chiến lược/ra quyết định (không phải vấn đề vận hành lặp lại — xem `toyota-8step.md` cho trường hợp đó):

1. **Xác định vấn đề** — chốt 1 câu "vấn đề cốt lõi".
2. **Chia nhỏ vấn đề** — dựng cây vấn đề (issue tree) theo logic MECE (không chồng chéo, không bỏ sót).
3. **Sắp xếp thứ tự ưu tiên** — nhánh nào ảnh hưởng lớn nhất/dễ tác động nhất trước.
4. **Xây dựng kế hoạch phân tích** — với mỗi nhánh ưu tiên, cần phân tích gì, cần dữ liệu gì.
5. **Phân tích chuyên sâu** — đưa ra giả thuyết + cách kiểm chứng.
6. **Hệ thống hóa kết quả phân tích** — tổng hợp phát hiện.
7. **Đề xuất phương án giải quyết** — khuyến nghị hành động cụ thể.

## Input cần thu thập
Mô tả vấn đề kinh doanh (tốt nhất đã qua bước 5W2H trước — nếu chưa, có thể gợi ý chạy 5W2H trước khi vào bước 1). Dữ liệu/số liệu liên quan nếu người dùng có.

Nếu vấn đề thực ra đơn giản (1-2 nguyên nhân rõ ràng, không cần phân tích nhiều nhánh), **cảnh báo người dùng** rằng quy trình 7 bước có thể quá nặng — gợi ý 5W2H hoặc GROW là đủ.

## Output — luôn theo đúng cấu trúc
```
## 1. Vấn đề cốt lõi
[1 câu]

## 2. Cây vấn đề (chia nhỏ theo MECE)
- Nhánh A: ...
  - Nhánh A: ...
- Nhánh B: ...
- Nhánh C: ...

## 3. Ưu tiên
[Nhánh nào xử lý trước và vì sao]

## 4. Kế hoạch phân tích
[Với nhánh ưu tiên: cần phân tích gì, cần dữ liệu gì, ai/ở đâu có dữ liệu đó]

## 5. Giả thuyết & cách kiểm chứng
[Giả thuyết ban đầu cho nhánh ưu tiên + cách kiểm chứng nhanh]

## 6. Kết quả phân tích (tổng hợp)
[Phát hiện chính, dựa trên dữ liệu đã có hoặc giả định nêu rõ là giả định]

## 7. Đề xuất phương án
[Khuyến nghị hành động cụ thể, ai làm, ưu tiên nào trước]
```

## Ví dụ (rút gọn)
**Input**: "Doanh số quý này giảm 15% so với quý trước, chưa rõ vì sao, đã thử nhiều cách mà không cải thiện."
- Vấn đề cốt lõi: doanh số giảm 15% QoQ chưa xác định được nguyên nhân chính.
- Cây vấn đề: (A) do thị trường/đối thủ, (B) do vận hành nội bộ (sản phẩm, giá, kênh bán), (C) do đội sales (năng lực, động lực).
- Ưu tiên: kiểm tra nhánh B trước vì dễ kiểm chứng bằng dữ liệu nội bộ nhất.
- Kế hoạch phân tích: so sánh doanh số theo từng kênh/sản phẩm để xem giảm đều hay tập trung ở đâu.

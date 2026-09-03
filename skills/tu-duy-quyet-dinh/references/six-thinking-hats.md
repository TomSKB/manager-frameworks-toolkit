# Six Thinking Hats (Sáu chiếc mũ tư duy) — Edward de Bono

## Định nghĩa
Kỹ thuật nhìn một quyết định/vấn đề từ 6 góc độ tư duy riêng biệt, tránh việc tranh luận nhóm bị lệch về một hướng (thường là chỉ toàn rủi ro, hoặc chỉ toàn lạc quan):

| Mũ | Góc nhìn |
|---|---|
| Trắng | Dữ kiện, số liệu khách quan — "chúng ta biết gì, cần biết gì thêm?" |
| Đỏ | Cảm xúc, trực giác — "cảm giác của mọi người về việc này là gì?" |
| Đen | Rủi ro, hạn chế, phản biện — "điều gì có thể sai/thất bại?" |
| Vàng | Lợi ích, cơ hội, lạc quan có cơ sở — "điều gì tốt nếu việc này thành công?" |
| Xanh lá | Sáng tạo, phương án thay thế — "còn cách nào khác chưa nghĩ tới?" |
| Xanh dương | Điều phối, tổng hợp, kết luận — "vậy bước tiếp theo là gì?" |

## Input cần thu thập
1. Quyết định/vấn đề cụ thể cần đánh giá.
2. (Tùy chọn) các dữ kiện đã biết — nếu thiếu, mũ Trắng sẽ liệt kê câu hỏi cần xác minh thay vì tự bịa số liệu.
3. Nếu người dùng đang chuẩn bị **họp nhóm** (không phải tự mình quyết), output nên nghiêng về dạng agenda + câu hỏi gợi mở cho từng mũ, để cả nhóm cùng trả lời — không để Claude tự quyết hết thay nhóm.

## Output — luôn theo đúng cấu trúc
```
## ⚪ Mũ Trắng — Dữ kiện
[Những gì đã biết chắc; những gì còn thiếu cần xác minh]

## 🔴 Mũ Đỏ — Cảm xúc
[Phản ứng/cảm giác của các bên liên quan, kể cả trực giác chưa có cơ sở logic]

## ⚫ Mũ Đen — Rủi ro
[Những gì có thể sai, hạn chế, lý do nên cẩn trọng]

## 🟡 Mũ Vàng — Cơ hội
[Lợi ích, giá trị, lý do nên lạc quan]

## 🟢 Mũ Xanh lá — Phương án khác
[Ít nhất 1-2 hướng đi thay thế chưa được nghĩ tới]

## 🔵 Mũ Xanh dương — Kết luận
[Tổng hợp, khuyến nghị 1 hướng đi + việc cần làm tiếp theo]
```

## Ví dụ (rút gọn)
**Input**: "Tôi đang cân nhắc chuyển toàn bộ team support sang làm remote hoàn toàn."
- Trắng: chưa có số liệu về năng suất remote của team này — cần đo thử 1 tháng trước khi quyết định vĩnh viễn.
- Đen: có thể ảnh hưởng thời gian phản hồi khách hàng nếu team lệch múi giờ, khó onboard người mới.
- Vàng: tiết kiệm chi phí văn phòng, mở rộng được nguồn tuyển dụng ra ngoài thành phố.
- Xanh dương: đề xuất chạy pilot remote 1 tháng với 1 nhóm nhỏ trước khi áp dụng toàn team.

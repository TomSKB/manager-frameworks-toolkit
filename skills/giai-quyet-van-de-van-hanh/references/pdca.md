# PDCA (Plan-Do-Check-Act)

## Định nghĩa
Chu trình cải tiến liên tục của Deming, gồm 4 bước lặp đi lặp lại thành **vòng tròn không kết thúc** (không phải quy trình chạy 1 lần rồi xong như McKinsey 7-step hay Toyota 8-step — xem `mckinsey-7step.md`, `toyota-8step.md`). Áp dụng được cho bất kỳ quy mô cải tiến nào, từ 1 quy trình nhỏ (vd: cách sắp xếp ca trực) tới cả 1 hệ thống quản lý chất lượng:

1. **Plan (Lập kế hoạch)** — xác định vấn đề/cơ hội cải tiến, đặt mục tiêu cụ thể, đề ra thay đổi muốn thử nghiệm.
2. **Do (Thực hiện)** — triển khai thay đổi đó, thường ở quy mô nhỏ/thử nghiệm trước khi áp dụng đại trà.
3. **Check (Kiểm tra)** — đo kết quả thực tế so với mục tiêu đặt ra ở bước Plan, xem thay đổi có hiệu quả không.
4. **Act (Điều chỉnh)** — nếu hiệu quả: chuẩn hóa, nhân rộng thay đổi. Nếu chưa hiệu quả (hoặc còn hiệu quả hơn nữa): rút kinh nghiệm, quay lại Plan cho vòng lặp tiếp theo.

Điểm khác biệt cốt lõi với Toyota 8-step: PDCA là khung **đơn giản, tổng quát, lặp lại nhiều vòng** cho cải tiến liên tục (continuous improvement) — không bắt buộc đào sâu nguyên nhân gốc theo kỹ thuật cụ thể. Toyota 8-step là quy trình **chi tiết hơn, cấu trúc chặt hơn**, chuyên trị 1 vấn đề chất lượng/vận hành lặp lại cụ thể với bước phân tích nguyên nhân gốc rõ ràng (5 Whys). Có thể dùng nối tiếp: Toyota 8-step xử lý dứt điểm 1 sự cố, PDCA duy trì cải tiến liên tục sau đó.

## Input cần thu thập
Mô tả quy trình/hoạt động muốn cải tiến + mục tiêu cải tiến mong muốn (nếu người dùng chưa có mục tiêu cụ thể, gợi ý cùng đặt ra ở bước Plan). Nếu đây là vòng lặp thứ 2 trở đi (đã từng chạy PDCA cho việc này), hỏi kết quả vòng trước để bước Act có cơ sở.

Nếu vấn đề là 1 sự cố/lỗi cụ thể cần đào sâu nguyên nhân gốc ngay (không phải cải tiến dần dần theo chu kỳ), **cảnh báo người dùng** nên cân nhắc Toyota 8-step thay vì PDCA.

## Output — luôn theo đúng cấu trúc
```
## 1. Plan — Lập kế hoạch
- Vấn đề/cơ hội cải tiến: [...]
- Mục tiêu (cụ thể, đo lường được): [...]
- Thay đổi đề xuất thử nghiệm: [...]

## 2. Do — Thực hiện
- Cách triển khai (quy mô thử nghiệm, phạm vi áp dụng): [...]
- Ai làm, khi nào: [...]

## 3. Check — Kiểm tra
- Chỉ số đo lường: [...]
- Kết quả thực tế so với mục tiêu: [đã có dữ liệu thì điền, chưa có thì nêu rõ đây là dự kiến đo vào lúc nào]

## 4. Act — Điều chỉnh
- Nếu đạt mục tiêu: [cách chuẩn hóa/nhân rộng]
- Nếu chưa đạt: [rút kinh nghiệm gì, điều chỉnh gì cho vòng Plan tiếp theo]

## Vòng lặp tiếp theo
[Gợi ý nội dung Plan cho chu kỳ PDCA kế tiếp, nếu có]
```

## Ví dụ (rút gọn)
**Input**: "Muốn cải thiện thời gian phản hồi khách hàng qua email, hiện trung bình 24h, muốn giảm dần."
- Plan: mục tiêu giảm còn 12h trong 2 tuần thử nghiệm; thay đổi thử: phân công 1 người trực kiểm tra hộp thư mỗi 2 giờ thay vì cuối ngày.
- Do: áp dụng thử với 1 nhóm hỗ trợ (5 người) trong 2 tuần, bắt đầu từ thứ Hai tới.
- Check: đo thời gian phản hồi trung bình sau 2 tuần, so với mục tiêu 12h.
- Act: nếu đạt — áp dụng cho toàn bộ đội hỗ trợ, đưa vào quy định trực; nếu chưa đạt — xem lại tần suất kiểm tra hộp thư, thử tăng lên mỗi 1 giờ ở vòng PDCA kế tiếp.

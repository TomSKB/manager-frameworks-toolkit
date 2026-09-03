# 5 Whys — Toyota Production System

## Định nghĩa
Trong một số tài liệu tiếng Việt (bao gồm cuốn sách nguồn của bộ framework này), kỹ thuật này bị gọi nhầm là "Nguyên lý thứ nhất" — tên gọi chính xác và được dùng phổ biến quốc tế là 5 Whys.

Kỹ thuật đào sâu nguyên nhân gốc (root cause) của một vấn đề bằng cách hỏi liên tục "tại sao?" bắt đầu từ hiện tượng bề mặt, mỗi câu trả lời trở thành đối tượng cho câu hỏi "tại sao" tiếp theo, cho đến khi chạm tới nguyên nhân gốc có thể hành động được (actionable). Con số "5" chỉ là ước lượng kinh nghiệm — có thể dừng sớm hơn (3 lần) nếu đã chạm gốc, hoặc cần hỏi thêm nếu chuỗi nhân quả còn dài; không cố ép đủ đúng 5 lần.

Đây là công cụ đào theo **một chuỗi nhân-quả duy nhất** để tìm nguyên nhân gốc — khác với 5W2H (mô tả toàn diện một sự việc theo 7 khía cạnh, không đào sâu theo chiều dọc). 5 Whys thường được dùng *sau* khi đã dùng 5W2H hoặc một cách mô tả khác để xác định rõ vấn đề bề mặt là gì.

## Input cần thu thập
1. Vấn đề/hiện tượng bề mặt cụ thể, đã quan sát được (không phải suy đoán) — ví dụ "máy dừng hoạt động", "khách hàng huỷ đơn", "báo cáo nộp trễ". Nếu người dùng đưa vào một mô tả còn mơ hồ, nên đề xuất chạy 5W2H trước để chốt lại "What" rõ ràng, rồi mới đào 5 Whys.
2. Dữ kiện thực tế ở mỗi bước hỏi "tại sao" — Claude không tự suy diễn nguyên nhân bịa đặt. Nếu người dùng không có dữ kiện cho một bước, ghi rõ đây là *giả thuyết cần xác minh*, không mặc định là đúng.
3. Nguyên nhân gốc cuối chuỗi phải là thứ **tổ chức/cá nhân có thể hành động để sửa** (ví dụ "quy trình kiểm tra thiếu bước X", "không có checklist bàn giao") — nếu chuỗi hỏi dừng lại ở nguyên nhân không thể tác động được (ví dụ "vì con người luôn mắc sai lầm"), cần hỏi thêm ít nhất 1 lần "tại sao" nữa.

## Output — luôn theo đúng cấu trúc
```
## Vấn đề bề mặt
[Mô tả hiện tượng ban đầu, ngắn gọn 1 câu]

## Chuỗi 5 Whys
1. Tại sao [vấn đề bề mặt] xảy ra? → [Nguyên nhân 1] (Dữ kiện có/Giả thuyết cần xác minh)
2. Tại sao [Nguyên nhân 1] xảy ra? → [Nguyên nhân 2] (Dữ kiện có/Giả thuyết cần xác minh)
3. Tại sao [Nguyên nhân 2] xảy ra? → [Nguyên nhân 3] (Dữ kiện có/Giả thuyết cần xác minh)
4. Tại sao [Nguyên nhân 3] xảy ra? → [Nguyên nhân 4] (Dữ kiện có/Giả thuyết cần xác minh)
5. Tại sao [Nguyên nhân 4] xảy ra? → [Nguyên nhân gốc] (Dữ kiện có/Giả thuyết cần xác minh)

## Nguyên nhân gốc (root cause)
[Câu kết luận — phải là điều có thể hành động để sửa]

## Hành động khắc phục đề xuất
[1-3 hành động cụ thể nhắm thẳng vào nguyên nhân gốc, không phải vào triệu chứng bề mặt]
```
Nếu có bước nào trong chuỗi thực chất là *nhiều nguyên nhân song song* (ví dụ vấn đề xảy ra vì cả A và B), tách thành 2 nhánh riêng thay vì gộp gượng ép vào 1 chuỗi tuyến tính — nêu rõ cả hai nhánh đều cần xử lý.

## Ví dụ (rút gọn)
**Input**: "Đơn hàng của khách VIP tuần trước bị giao trễ 2 ngày."
1. Tại sao giao trễ? → Đơn vị vận chuyển nhận hàng trễ 1 ngày so với lịch. (Dữ kiện có)
2. Tại sao đơn vị vận chuyển nhận trễ? → Kho đóng gói xong nhưng không có ai gọi báo cho vận chuyển đến lấy. (Dữ kiện có)
3. Tại sao không ai gọi báo? → Quy trình hiện tại không có bước "xác nhận đã báo vận chuyển" bắt buộc. (Dữ kiện có)
4. Tại sao quy trình thiếu bước này? → Quy trình đóng gói được viết từ lúc công ty chỉ có 1 đơn vị vận chuyển duy nhất, chưa cập nhật khi thêm đối tác thứ hai. (Giả thuyết cần xác minh — hỏi lại người phụ trách kho)
- Nguyên nhân gốc: quy trình đóng gói-bàn giao chưa cập nhật theo mô hình nhiều đối tác vận chuyển, thiếu bước xác nhận bắt buộc.
- Hành động: thêm bước "xác nhận đã báo vận chuyển" bắt buộc vào checklist đóng gói, rà soát lại toàn bộ quy trình cho các đối tác vận chuyển mới.

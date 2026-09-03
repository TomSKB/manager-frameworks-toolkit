---
name: chan-doan-van-de
description: 'Điểm khởi đầu của bộ công cụ tư duy & phương pháp quản lý — dùng NGAY khi người quản lý mô tả vấn đề một cách mơ hồ, cảm tính, hoặc nói thẳng là chưa biết vấn đề của mình là gì (ví dụ: "team dạo này kỳ kỳ", "tôi thấy mệt mỏi với công việc quản lý", "có gì đó không ổn nhưng không biết bắt đầu từ đâu"). Skill này hỏi tối đa 2-3 câu để xác định đúng 1 trong 11 nhóm vấn đề quản lý (chiến lược, ra quyết định, mục tiêu & kế hoạch, vận hành, giao việc, động lực nhân sự, đánh giá & phản hồi, giao tiếp, xung đột & đàm phán, thời gian, xây dựng đội nhóm), giải thích ngắn gọn vấn đề đó là gì, rồi tự động tiếp tục sang đúng skill nhóm tương ứng để chọn và áp dụng framework cụ thể — người dùng không cần biết trước nên dùng framework nào. Luôn ưu tiên dùng skill này TRƯỚC các skill framework cụ thể khi input còn mơ hồ; nếu người dùng đã mô tả đủ rõ hoặc gọi thẳng tên 1 framework, có thể bỏ qua bước này.'
---

# Chẩn đoán vấn đề — Cổng vào của bộ công cụ Tư duy & Phương pháp Quản lý

## Vì sao skill này tồn tại

Người quản lý thường không đến với một vấn đề đã được gọi tên sẵn. Họ đến với một **triệu chứng**: "dạo này họp hành cứ sao sao ấy", "tôi thấy mệt mỏi với team này quá", "có gì đó không ổn nhưng không biết bắt đầu từ đâu". Nếu vội nhảy vào áp dụng một framework ngay, rất dễ chọn sai công cụ vì chưa hiểu đúng bản chất vấn đề.

Bộ công cụ này gồm 11 skill "nhóm chủ đề" (chiến lược, ra quyết định, mục tiêu & kế hoạch, vận hành, giao việc, động lực, đánh giá & phản hồi, giao tiếp, xung đột & đàm phán, thời gian, xây dựng đội nhóm), mỗi skill chứa vài framework liên quan và tự có bảng quyết định riêng để chọn đúng framework bên trong nhóm đó. Skill này là **cổng vào chung** — việc của nó chỉ là xác định đúng **nhóm chủ đề nào** phù hợp với triệu chứng người dùng mô tả, sau đó bàn giao cho đúng skill nhóm đó để nó tự chọn framework cụ thể. Nói cách khác: skill này làm việc của một "bác sĩ đa khoa" — quan sát triệu chứng và chuyển đúng chuyên khoa; skill nhóm chủ đề mới là nơi "chẩn đoán chuyên sâu và kê đơn".

## Luồng xử lý

1. **Đánh giá độ rõ ràng của input:**
   - **Input đã rõ ràng** — người dùng mô tả đúng một tình huống cụ thể, hoặc gọi thẳng tên 1 framework/1 nhóm chủ đề: xác định ngay nhóm chủ đề phù hợp (xem bảng 11 nhóm trong `references/nhom-van-de.md`), nói 1 câu ngắn xác nhận ("đây là vấn đề thuộc nhóm [tên nhóm]"), rồi chuyển thẳng sang bước 3. Không cần hỏi thêm.
   - **Input mơ hồ/cảm tính** — người dùng mô tả cảm giác chung chung, nhiều triệu chứng lẫn lộn, hoặc nói thẳng "tôi không biết vấn đề là gì": đọc `references/nhom-van-de.md` để lấy cây câu hỏi chẩn đoán theo từng nhóm triệu chứng, hỏi **tối đa 2-3 câu** để thu hẹp phạm vi (không phỏng vấn kiểu hỏi bệnh 20 câu — người dùng sẽ bỏ cuộc).
2. **Chốt và giải thích ngắn gọn:**
   1. Nêu tên nhóm chủ đề đã chốt (vd: "đây là vấn đề thuộc nhóm *Tạo động lực & Phát triển nhân sự*").
   2. 1-2 câu giải thích ngắn gọn vì sao đây là loại vấn đề đó, dựa trên chính mô tả của người dùng — không bịa thêm chi tiết ngoài những gì họ đã kể.
   3. Nếu vấn đề pha trộn 2 nhóm trở lên (khá phổ biến trong thực tế), nói rõ cả hai, chọn 1 nhóm chính để xử lý trước, nêu nhóm còn lại như bước tiếp theo.
3. **Bàn giao ngay cho skill nhóm tương ứng** — dựa vào tên nhóm đã chốt, tiếp tục ngay lập tức bằng cách coi như đang dùng skill của nhóm đó: đọc `SKILL.md` của skill đó (tên skill tương ứng có trong bảng ở `references/nhom-van-de.md`, ví dụ nhóm "Tạo động lực & Phát triển nhân sự" → skill `dong-luc-phat-trien-nhan-su`), rồi làm theo đúng "Luồng xử lý" và "Bảng quyết định" của skill đó để chọn & áp dụng framework cụ thể. **Không dừng lại chờ người dùng tự chọn framework hay tự gọi skill khác** — họ đến với skill chẩn đoán này chính là vì chưa biết nên dùng gì, nên việc bàn giao phải diễn ra liền mạch trong cùng một câu trả lời, không phải một lượt hỏi-đáp riêng.

## Nguyên tắc chung

- **Bước chẩn đoán không phải là thủ tục hình thức** — nếu người dùng đã nói rõ vấn đề hoặc gọi tên framework, đừng hỏi lại những gì đã biết.
- **Không hỏi những gì có thể suy luận hợp lý** từ mô tả của người dùng.
- Mục tiêu duy nhất của skill này là **định tuyến đúng nhóm chủ đề** — việc chọn framework cụ thể, thu thập input chi tiết, và tạo output là trách nhiệm của skill nhóm được bàn giao tới, không phải của skill này.
- Nếu người dùng chỉ hỏi "tôi nên dùng cách nào" mà chưa cần áp dụng ngay, vẫn có thể dừng lại sau khi nêu tên nhóm + framework khả năng cao nhất + lý do, chưa cần điền toàn bộ worksheet.

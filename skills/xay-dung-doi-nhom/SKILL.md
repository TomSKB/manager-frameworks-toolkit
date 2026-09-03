---
name: xay-dung-doi-nhom
description: 'PHẢI dùng skill này trước khi đưa bất kỳ lời khuyên quản lý đội nhóm nào khi team đang trong giai đoạn phát triển ban đầu hoặc đang chuyển đổi — áp dụng mô hình 5 giai đoạn phát triển nhóm của Tuckman (Forming - Storming - Norming - Performing - Adjourning) để chẩn đoán đúng team đang ở đâu trước khi chọn cách can thiệp. Kích hoạt khi: team/nhóm mới thành lập, các thành viên còn chưa ăn ý, còn dè dặt, chưa rõ vai trò; team đang có nhiều va chạm/xung đột nội bộ mang tính hệ thống ở giai đoạn đầu (tranh giành vai trò, phản đối quy trình, bất mãn lan rộng); người dùng muốn biết team mình đang ở giai đoạn phát triển nào để chọn đúng cách quản lý (không biết nên buông tay hay cần cầm tay chỉ việc); dự án/team sắp kết thúc, giải thể, hoặc thành viên chủ chốt sắp chuyển đi cần tổng kết/chuyển tiếp êm đẹp. Đừng tự bịa lời khuyên "trao quyền/buông tay" cho team còn non hoặc "cầm tay chỉ việc" cho team đã trưởng thành mà không chẩn đoán giai đoạn trước.'
---

# Xây Dựng & Phát Triển Đội Nhóm — Tuckman

## Vì sao phải chẩn đoán giai đoạn trước khi can thiệp

Một team không tĩnh — nó phát triển qua các giai đoạn, và **cách quản lý đúng ở giai đoạn này có thể phản tác dụng ở giai đoạn khác**. Buông tay, trao quyền quá sớm cho một team mới thành lập (đang Forming/Storming) khiến team càng rối vì thiếu định hướng vai trò/mục tiêu rõ ràng. Ngược lại, kiểm soát sát sao, cầm tay chỉ việc cho một team đã trưởng thành (đang Performing) khiến họ cảm thấy không được tin tưởng, giảm động lực.

Vì vậy, trước khi đưa ra bất kỳ hành động quản lý nào cho một tình huống đội nhóm, luôn xác định **team đang ở giai đoạn nào** trong 5 giai đoạn của Tuckman, rồi mới chọn hành động tương ứng — không nhảy thẳng vào kê đơn.

## Luồng xử lý

1. **Xác định team đang ở giai đoạn nào** dựa trên biểu hiện người dùng mô tả (mới lập bao lâu, không khí làm việc, có xung đột không, mức độ tự chủ, có thay đổi lớn gần đây không). Nếu người dùng đã mô tả đủ rõ (ví dụ "team mới lập tuần trước, còn dè dặt"), có thể chẩn đoán ngay không cần hỏi thêm.
2. **Đọc file `references/tuckman-stages.md`** để lấy đúng đặc điểm và hành động quản lý chuẩn cho từng giai đoạn.
3. **Thu thập thêm input nếu còn thiếu** — chỉ hỏi những gì thật sự cần để xác định đúng giai đoạn (xem mục "Input cần thu thập" trong reference), đừng hỏi thừa nếu đã đủ dữ kiện.
4. **Đưa ra chẩn đoán + hành động quản lý cụ thể** cho case đó, theo đúng cấu trúc output trong reference file — luôn gắn vào tình huống thật, không nói lý thuyết chung chung.
5. **Gợi ý bước tiếp theo** — ví dụ nếu đang chẩn đoán Storming, sau khi áp dụng hành động quản lý, gợi ý người dùng quay lại đánh giá sau một thời gian (2-3 tuần) xem team đã có dấu hiệu chuyển sang Norming chưa.

## Ranh giới hay bị nhầm

**Storming (Tuckman) vs xung đột cá nhân cần hòa giải (LEAPS)**: nếu xung đột chỉ xảy ra giữa 1-2 cá nhân cụ thể, xuất phát từ lý do cá nhân (hiểu lầm, cảm giác bị đối xử không công bằng giữa hai người) — đây là việc cần **hòa giải trực tiếp**, dùng skill "xung-dot-dam-phan" (framework LEAPS). Nếu va chạm mang tính **hệ thống của cả nhóm** khi mới hình thành hoặc đang tái cấu trúc (nhiều người cùng tranh cãi về vai trò, quy trình, cách làm việc chung) — đây là Storming bình thường trong quá trình phát triển nhóm, dùng Tuckman để biết cách dẫn dắt team qua giai đoạn này. Hai tình huống có thể xảy ra cùng lúc: một team đang Storming có thể có 1 cặp cá nhân xung đột gay gắt hơn hẳn phần còn lại — khi đó xử lý cả hai, dùng LEAPS cho cặp cá nhân đó song song với hành động quản lý Storming cho cả team.

## Nguyên tắc chung

- **Không hỏi thừa** những gì người dùng đã mô tả đủ rõ để xác định giai đoạn.
- **Không tự bịa biểu hiện** của team — nếu thiếu dữ kiện để chẩn đoán chắc chắn (ví dụ chưa rõ có xung đột hay chỉ đang trầm lắng bình thường), hỏi lại thay vì đoán đại.
- **Luôn gắn vào case cụ thể** của người dùng, không trả lời lý thuyết chung chung về 5 giai đoạn.
- **Nêu rõ đang chẩn đoán team ở giai đoạn nào và vì sao** ngay trong câu trả lời, để người dùng hiểu được logic và tự đánh giá được ở những lần sau.
- **Không giả định người dùng đã biết ý nghĩa của các ký hiệu/chữ viết tắt trong framework** — nhiều người dùng plugin này lần đầu, không có nền tảng quản lý. Khi output dùng ký hiệu viết tắt (ví dụ tên các trục/tầng/bước chỉ viết gọn 1-2 chữ), luôn giải thích ngắn gọn ý nghĩa ngay trong output, đừng chỉ giải thích khi được hỏi lại.

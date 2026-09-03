# SWOT Analysis

## Định nghĩa
Khung phân tích tổng quan để hỗ trợ ra quyết định, chia thành 4 ô trên 2 trục:
- **Trục nội bộ** (yếu tố bên trong tổ chức/dự án, tự kiểm soát được): **Strengths** (Điểm mạnh) và **Weaknesses** (Điểm yếu).
- **Trục bên ngoài** (yếu tố môi trường, không tự kiểm soát được): **Opportunities** (Cơ hội) và **Threats** (Nguy cơ/Thách thức).

Mục đích không chỉ là liệt kê 4 danh sách, mà là **đối chiếu chéo** giữa chúng để ra hành động: dùng Điểm mạnh để nắm bắt Cơ hội, dùng Điểm mạnh để né/giảm Nguy cơ, khắc phục Điểm yếu để không bỏ lỡ Cơ hội, và nhận diện Điểm yếu nào kết hợp với Nguy cơ nào tạo ra rủi ro lớn nhất cần phòng trước.

## Input cần thu thập
1. Chủ thể đang phân tích cụ thể là gì — một doanh nghiệp, một sản phẩm, một dự án, hay một quyết định cá nhân (SWOT áp dụng được cho mọi quy mô, cần biết rõ đang phân tích cái gì).
2. Bối cảnh/mục đích phân tích (chuẩn bị mở rộng, cân nhắc đầu tư, đánh giá trước một quyết định lớn...).
3. Bất kỳ dữ kiện nào người dùng đã biết về nội bộ (nguồn lực, năng lực, hạn chế) và bên ngoài (thị trường, đối thủ, xu hướng) — không bắt buộc đủ cả 4 ô ngay, Claude có thể hỏi khơi gợi phần thiếu, ưu tiên hỏi ô nào người dùng có vẻ chưa nghĩ tới.

Nếu người dùng chỉ có input mơ hồ về bên ngoài (thị trường, vĩ mô), có thể gợi ý dùng PESTEL trước để có dữ liệu đầu vào chất lượng hơn cho hai ô Opportunities/Threats, rồi quay lại hoàn thiện SWOT — nhưng không bắt buộc, nếu người dùng đã có đủ thông tin thì làm SWOT trực tiếp.

## Output — luôn theo đúng cấu trúc
```
| | Có lợi | Có hại |
|---|---|---|
| **Nội bộ** | **Strengths (Điểm mạnh)**<br>- ...<br>- ... | **Weaknesses (Điểm yếu)**<br>- ...<br>- ... |
| **Bên ngoài** | **Opportunities (Cơ hội)**<br>- ...<br>- ... | **Threats (Nguy cơ)**<br>- ...<br>- ... |

## Đối chiếu chéo (chiến lược hành động)
- **S-O** (dùng mạnh để nắm cơ hội): ...
- **S-T** (dùng mạnh để né/giảm nguy cơ): ...
- **W-O** (khắc phục yếu để không lỡ cơ hội): ...
- **W-T** (rủi ro lớn nhất cần phòng — yếu kết hợp nguy cơ): ...

## Khuyến nghị ưu tiên
[1-2 câu: trong 4 ô đối chiếu trên, nên ưu tiên hành động nào trước, vì sao]
```

## Ví dụ (rút gọn)
**Input**: "Tôi đang cân nhắc mở thêm một chi nhánh quán trà sữa ở khu gần trường đại học, quán hiện tại đang chạy ổn ở khu văn phòng."

- Strengths: đã có công thức/quy trình vận hành ổn định, thương hiệu đã có khách quen tin tưởng.
- Weaknesses: đội ngũ hiện tại chưa có kinh nghiệm vận hành 2 điểm bán cùng lúc, vốn lưu động còn mỏng.
- Opportunities: khu vực trường đại học có lượng khách trẻ đông, tần suất mua cao, giá thuê mặt bằng khu này thường thấp hơn khu văn phòng.
- Threats: khu vực gần trường thường đã có nhiều đối thủ cạnh tranh giá rẻ, khách sinh viên nhạy cảm về giá và ít trung thành thương hiệu hơn khách văn phòng.
- S-O: tận dụng quy trình vận hành sẵn có để mở nhanh, giữ giá cạnh tranh nhờ chi phí vận hành đã tối ưu.
- W-T: đội ngũ chưa quen vận hành đa điểm cộng với thị trường sinh viên vốn nhạy giá là rủi ro lớn nhất — nếu chi nhánh mới lỗ vì cạnh tranh giá, có thể ảnh hưởng ngược lại dòng tiền của quán chính.
- Khuyến nghị: nên giải quyết bài toán vốn lưu động và thử nghiệm quy mô nhỏ (pop-up hoặc menu rút gọn) trước khi cam kết mở chi nhánh đầy đủ.

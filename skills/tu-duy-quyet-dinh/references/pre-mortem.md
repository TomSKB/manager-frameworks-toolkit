# Pre-mortem (Diễn tập thất bại trước khi bắt đầu)

## Định nghĩa
Kỹ thuật rà soát rủi ro bằng cách **tưởng tượng dự án/quyết định đã thất bại thảm hại trong tương lai**, rồi truy ngược lại "vì sao nó thất bại" — thay vì hỏi "nó có thể thất bại vì sao" (dễ bị thiên kiến lạc quan chặn lại khi lập kế hoạch bình thường). Vì đã giả định thất bại là sự thật rồi mới đi tìm lý do, kỹ thuật này giúp mọi người (kể cả người vốn ngại nói ra rủi ro) dễ nêu ý kiến hơn.

Sau khi liệt kê các lý do thất bại tưởng tượng, phân loại chúng theo 3 nhóm ẩn dụ:

- **Hổ (Tigers)** — rủi ro **thật, nghiêm trọng, khả năng xảy ra cao** — cần có kế hoạch giảm thiểu ngay, đây là ưu tiên hàng đầu.
- **Hổ giấy (Paper Tigers)** — trông đáng sợ khi mới nghe nhưng thực ra **khả năng xảy ra thấp hoặc tác động nhỏ** — không nên đầu tư nhiều nguồn lực đối phó, chỉ cần theo dõi.
- **Con voi trong phòng (Elephants)** — rủi ro **ai cũng ngầm biết nhưng không ai dám nói ra công khai** (vấn đề nhạy cảm về con người, chính trị nội bộ, năng lực của một bên liên quan...) — bước quan trọng nhất của Pre-mortem là gọi tên được nhóm này, vì chúng thường bị bỏ qua trong họp lập kế hoạch thông thường.

## Input cần thu thập
1. Dự án/quyết định sắp triển khai, và mục tiêu thành công cụ thể của nó (để biết "thất bại" nghĩa là gì).
2. Mốc thời gian tưởng tượng nhìn lại (ví dụ "6 tháng sau", "sau khi ra mắt 1 quý") — giúp việc tưởng tượng cụ thể hơn thay vì chung chung.
3. Những người liên quan đến quyết định, nếu có (giúp gợi ý xem góc nhìn nào có thể đang bị bỏ sót, đặc biệt cho nhóm "Con voi trong phòng").

## Output — luôn theo đúng cấu trúc
```
## Chú thích 3 nhóm rủi ro
- **Hổ** = rủi ro thật, khả năng xảy ra cao, cần giảm thiểu ngay.
- **Hổ giấy** = nghe đáng sợ nhưng khả năng/tác động thấp, không cần ưu tiên nguồn lực.
- **Con voi trong phòng** = ai cũng ngầm biết nhưng chưa ai nói ra công khai — cần gọi tên rõ ràng.

## Giả định: [Tên dự án/quyết định] đã thất bại vào [mốc thời gian]
[Mô tả ngắn kịch bản thất bại tưởng tượng để làm bối cảnh]

## Danh sách lý do thất bại (đã phân loại)
| Lý do thất bại tưởng tượng | Phân loại | Vì sao xếp loại này |
|---|---|---|
| ... | Hổ / Hổ giấy / Con voi trong phòng | ... |

## Kế hoạch giảm thiểu — ưu tiên theo Hổ trước
[Với từng "Hổ", đề xuất hành động cụ thể giảm thiểu ngay từ bây giờ, trước khi dự án bắt đầu]

## Vấn đề cần nêu ra công khai (Con voi trong phòng)
[Nếu có, nêu rõ cần ai trao đổi với ai, theo cách nào để đưa vấn đề nhạy cảm này ra ánh sáng mà không gây xung đột không cần thiết]
```

## Ví dụ (rút gọn)
**Input**: "Chúng tôi sắp ra mắt một tính năng lớn sau 3 tháng phát triển, muốn rà soát rủi ro trước khi cam kết ngày ra mắt với ban lãnh đạo."

**Giả định**: tính năng đã ra mắt được 3 tháng và bị coi là thất bại — tỷ lệ dùng thấp, phải rollback.

| Lý do thất bại tưởng tượng | Phân loại | Vì sao |
|---|---|---|
| Hạ tầng không chịu được tải khi traffic tăng đột biến | Hổ | Đội hạ tầng đã cảnh báo nhưng chưa test tải thực tế |
| Đối thủ ra mắt tính năng tương tự trước 1 tuần | Hổ giấy | Dù đối thủ ra trước, sản phẩm của mình có khác biệt rõ, ảnh hưởng thực tế thấp |
| Một thành viên chủ chốt trong team backend có dấu hiệu sắp nghỉ việc nhưng chưa ai hỏi thẳng | Con voi trong phòng | Cả team đều cảm nhận được nhưng chưa ai dám hỏi công khai vì sợ "tự ứng nghiệm" |

**Kế hoạch giảm thiểu**: chạy load test thực tế trong 2 tuần tới trước khi chốt ngày ra mắt cứng với ban lãnh đạo. **Vấn đề cần nêu ra công khai**: quản lý trực tiếp nên trò chuyện riêng, thẳng thắn với thành viên đó trước khi lập kế hoạch phân công cho giai đoạn ra mắt, để không đặt cược thành công của dự án vào một rủi ro nhân sự chưa được xác nhận.

# Ma trận Eisenhower (Ma trận Khẩn cấp - Quan trọng)

## Định nghĩa
Công cụ sắp xếp ưu tiên công việc bằng cách phân loại từng đầu việc vào 1 trong 4 ô, theo 2 trục độc lập: **Khẩn cấp (Urgent)** — cần xử lý ngay hay có thể chờ, và **Quan trọng (Important)** — có ảnh hưởng lớn tới mục tiêu dài hạn hay không.

| | Khẩn cấp | Không khẩn cấp |
|---|---|---|
| **Quan trọng** | **Ô 1 — Làm ngay**: khủng hoảng, deadline sát, sự cố cần xử lý tức thời | **Ô 2 — Lên lịch làm**: lập kế hoạch, phát triển kỹ năng, xây dựng quan hệ, phòng ngừa rủi ro |
| **Không quan trọng** | **Ô 3 — Uỷ quyền**: việc "khẩn cấp" thực ra chỉ khẩn cấp với người khác, không phục vụ mục tiêu của mình | **Ô 4 — Loại bỏ**: việc giết thời gian, không tạo giá trị |

Ghi chú quan trọng cho từng ô:
- **Ô 1 (Khẩn cấp + Quan trọng)**: làm ngay, không bàn cãi. Nhưng nếu 1 người luôn sống ở ô này, đó là dấu hiệu thiếu kế hoạch từ trước (đáng lẽ nhiều việc ở đây có thể đã được xử lý từ Ô 2).
- **Ô 2 (Không khẩn cấp nhưng Quan trọng)**: đây là **ô hay bị bỏ quên nhất** vì nó không có deadline gấp gáp thúc ép, nhưng lại là ô **tạo ra giá trị dài hạn lớn nhất** — lập kế hoạch chiến lược, phát triển kỹ năng bản thân/đội nhóm, xây dựng quan hệ, chăm sóc sức khỏe, phòng ngừa rủi ro trước khi nó thành khủng hoảng. Người quản lý giỏi là người **chủ động dành thời gian cố định cho Ô 2** thay vì để nó bị Ô 1 và Ô 3 nuốt hết thời gian.
- **Ô 3 (Khẩn cấp nhưng Không quan trọng)**: nên **uỷ quyền cho người khác** nếu có thể. Đây là cái bẫy phổ biến nhất — nhiều việc "khẩn cấp" (tin nhắn, cuộc gọi, yêu cầu gấp của người khác) thực ra chỉ khẩn cấp *với người yêu cầu*, không phục vụ mục tiêu của chính mình. Nếu không có ai để uỷ quyền, ít nhất cần đặt giới hạn thời gian xử lý ngắn gọn, không để nó chiếm hết ngày.
- **Ô 4 (Không khẩn cấp + Không quan trọng)**: loại bỏ hoặc hạn chế tối đa (lướt mạng xã hội vô định, việc vặt không mục đích, họp không cần thiết).

Dùng khi một người/quản lý cảm thấy **quá tải**, luôn ở trạng thái "chữa cháy" mà không có thời gian cho việc quan trọng dài hạn, hoặc có danh sách to-do quá dài không biết bắt đầu từ đâu.

## Input cần thu thập
1. Danh sách các đầu việc hiện tại cần sắp xếp (nếu người dùng chỉ kể lan man, giúp họ liệt kê thành danh sách rõ từng việc).
2. Với mỗi việc còn mơ hồ về mức độ khẩn cấp/quan trọng: hỏi ngắn — việc này có deadline sát không (khẩn cấp)? việc này có ảnh hưởng tới mục tiêu lớn/hậu quả dài hạn nếu không làm không (quan trọng)?
3. Với việc rơi vào Ô 3: hỏi xem có ai trong team/xung quanh có thể nhận việc này không, để đưa gợi ý uỷ quyền cụ thể thay vì chung chung.

## Output — luôn theo đúng cấu trúc
```
## Ô 1 — Khẩn cấp & Quan trọng (Làm ngay)
- [Việc 1]
- [Việc 2]

## Ô 2 — Quan trọng, Không khẩn cấp (Lên lịch làm)
- [Việc 1] — gợi ý thời điểm/tần suất cố định để làm
- [Việc 2]

## Ô 3 — Khẩn cấp, Không quan trọng (Uỷ quyền)
- [Việc 1] — gợi ý uỷ quyền cho ai/cách xử lý nhanh nếu không uỷ quyền được
- [Việc 2]

## Ô 4 — Không khẩn cấp, Không quan trọng (Loại bỏ)
- [Việc 1]

## Nhận xét & gợi ý ưu tiên
[Chỉ ra pattern đáng chú ý — ví dụ: quá nhiều việc dồn ở Ô 1 và Ô 3, gần như không có thời gian cho Ô 2; đề xuất cụ thể nên dành bao nhiêu thời gian/tuần cố định cho Ô 2 để giảm dần việc rơi vào Ô 1 về sau]
```

## Ví dụ (rút gọn)
**Input**: "Tôi là trưởng phòng, ngày nào cũng bận tối mắt xử lý yêu cầu gấp của người khác, họp hành liên miên, mà kế hoạch phát triển đội ngũ tôi định làm từ đầu năm vẫn chưa động vào."

- Ô 1: Xử lý sự cố khách hàng đang khiếu nại gấp; hoàn thành báo cáo có deadline chiều nay.
- Ô 2: Xây kế hoạch phát triển kỹ năng cho đội (đang bị trì hoãn từ đầu năm); lập kế hoạch nhân sự quý tới; 1-1 định kỳ với từng nhân viên.
- Ô 3: Trả lời các yêu cầu "gấp" qua Slack từ phòng ban khác không liên quan trực tiếp mục tiêu của mình; tham gia một số cuộc họp cập nhật tình hình không cần quyết định gì từ mình — có thể cử phó phòng dự thay hoặc xin báo cáo tóm tắt.
- Ô 4: Đọc email quảng cáo, các cuộc họp không có agenda rõ ràng.
- Nhận xét: phần lớn thời gian đang bị Ô 1 và Ô 3 chiếm hết, Ô 2 gần như bằng 0 dù đây là việc tạo giá trị dài hạn lớn nhất — gợi ý chặn cố định 2 giờ mỗi tuần (ví dụ sáng thứ 2) chỉ để làm việc Ô 2, không nhận lịch họp vào khung đó.

# Kỹ thuật Pomodoro (Francesco Cirillo)

## Định nghĩa
Kỹ thuật quản lý thời gian chia công việc thành các **chu kỳ tập trung cao độ 25 phút**, gọi là "1 pomodoro":
- Sau mỗi pomodoro, nghỉ ngắn **5 phút**.
- Sau **4 pomodoro liên tiếp**, nghỉ dài hơn **15-30 phút** rồi mới bắt đầu chuỗi 4 pomodoro tiếp theo.

Nguyên tắc cốt lõi (không có thì không còn là Pomodoro):
1. **Trong 1 pomodoro, tuyệt đối không làm việc khác và không để bị gián đoạn** — chỉ 1 việc duy nhất đã chọn trước, tắt thông báo, không kiểm tra tin nhắn/email.
2. **Nếu bị gián đoạn** (ai đó hỏi, ý nghĩ việc khác chen ngang, thông báo bất khả kháng): **ghi lại ngay** (viết ra giấy/note việc đó hoặc ý nghĩ đó) rồi **quay lại việc đang làm ngay lập tức**, xử lý việc bị ghi chú đó sau khi hết pomodoro. Không dừng giữa chừng để giải quyết luôn — làm vậy phá vỡ chu kỳ.
3. **Không cộng dồn/nối gián đoạn vào giữa chu kỳ** — nếu một pomodoro bị phá vỡ nghiêm trọng (gián đoạn không thể trì hoãn, buộc phải dừng hẳn), pomodoro đó coi như không hợp lệ và phải **bắt đầu lại từ đầu** một pomodoro mới cho việc đó, không tính nửa chừng.
4. Mỗi pomodoro là đơn vị không thể chia nhỏ (nguyên tắc "the pomodoro is indivisible") — không rút ngắn xuống 20 phút hay kéo dài lên 30 phút tùy hứng giữa chừng.

Dùng để **chống trì hoãn** và **tăng khả năng tập trung** cho các việc cần sự tập trung sâu (deep work), hoặc các việc hay bị ngắt quãng bởi thông báo, tin nhắn, việc vặt xen ngang.

## Input cần thu thập
1. **Việc cụ thể sẽ làm trong (các) pomodoro** — phải là 1 việc rõ ràng, đã được chọn xong (nếu người dùng đang phân vân giữa nhiều việc, gợi ý dùng Eisenhower Matrix trước để chọn việc ưu tiên, rồi quay lại đây).
2. Ước lượng việc đó cần khoảng bao nhiêu pomodoro để hoàn thành (nếu người dùng chưa ước lượng, giúp họ ước lượng thô dựa trên độ phức tạp mô tả).
3. Những nguồn gây gián đoạn thường gặp của người dùng (thông báo điện thoại, đồng nghiệp, email...) — để đưa gợi ý loại bỏ cụ thể trước khi bắt đầu.

## Output — luôn theo đúng cấu trúc
```
## Việc sẽ làm
[Tên việc cụ thể, rõ ràng — 1 việc duy nhất]

## Kế hoạch pomodoro
- Số pomodoro ước tính: [X pomodoro] (mỗi pomodoro 25 phút, nghỉ 5 phút; sau mỗi 4 pomodoro nghỉ dài 15-30 phút)
- Lịch trình gợi ý:
  1. Pomodoro 1 (25p) → nghỉ 5p
  2. Pomodoro 2 (25p) → nghỉ 5p
  3. Pomodoro 3 (25p) → nghỉ 5p
  4. Pomodoro 4 (25p) → nghỉ dài 15-30p
  [lặp lại nếu cần nhiều hơn 4 pomodoro]

## Chuẩn bị trước khi bắt đầu
[Danh sách cụ thể: tắt thông báo gì, báo trước với ai, chuẩn bị giấy/note để ghi gián đoạn]

## Quy tắc xử lý gián đoạn trong lúc chạy
- Gián đoạn có thể trì hoãn → ghi lại vào [nơi ghi chú], quay lại việc ngay, xử lý sau khi hết pomodoro.
- Gián đoạn không thể trì hoãn (bắt buộc dừng hẳn) → pomodoro này tính là không hợp lệ, nghỉ ngắn rồi bắt đầu lại một pomodoro mới từ đầu cho việc này.
```

## Ví dụ (rút gọn)
**Input**: "Tôi cần viết xong bản báo cáo phân tích thị trường nhưng cứ mở lên là bị xao nhãng bởi Slack và email, làm 10 phút lại lướt điện thoại."

- Việc sẽ làm: Viết bản báo cáo phân tích thị trường (phần nội dung chính, chưa gồm rà soát cuối).
- Số pomodoro ước tính: 6 pomodoro (khoảng 3 giờ làm việc thực, chia làm 2 chuỗi 4 và 2).
- Lịch trình: Pomodoro 1-4 → nghỉ dài 20p → Pomodoro 5-6 → nghỉ ngắn.
- Chuẩn bị: tắt thông báo Slack và email, để điện thoại chế độ máy bay hoặc phòng khác, chuẩn bị 1 tờ giấy ghi "việc chen ngang".
- Quy tắc gián đoạn: nếu nhớ ra việc khác (vd "phải trả lời sếp") → ghi vào giấy, tiếp tục viết báo cáo, xử lý email đó ở giờ nghỉ dài; nếu có cuộc gọi khẩn không thể từ chối → dừng hẳn, pomodoro đó bỏ, nghỉ 5 phút rồi bắt đầu lại pomodoro mới.

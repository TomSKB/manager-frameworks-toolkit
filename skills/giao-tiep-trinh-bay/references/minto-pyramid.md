# Nguyên lý Kim Tự Tháp (Minto Pyramid Principle) — Barbara Minto

## Định nghĩa
Nguyên tắc cấu trúc một bài viết/báo cáo/thuyết trình theo hình kim tự tháp, đi từ **trên xuống** (top-down):
- **Đỉnh** — ý chính/kết luận/khuyến nghị, nêu **ngay từ đầu**, trước khi giải thích tại sao.
- **Tầng giữa** — các luận điểm hỗ trợ cho ý chính, nhóm theo logic (thường 3 nhóm, mỗi nhóm trả lời một khía cạnh khác nhau của câu hỏi "vì sao kết luận đó đúng").
- **Đáy** — dữ liệu/dẫn chứng/chi tiết cụ thể chứng minh từng luận điểm ở tầng giữa.

Nguyên tắc cốt lõi: **nói kết luận trước, giải thích sau** — ngược lại hoàn toàn với thói quen kể chuyện tuần tự (kể quá trình → dữ liệu → cuối cùng mới đến kết luận), vốn bắt người nghe/đọc phải tự chờ đến cuối mới biết "vậy rốt cuộc là sao". Người bận rộn (sếp, khách hàng, nhà đầu tư) thường chỉ có thời gian nghe/đọc phần đầu — nếu kết luận nằm ở cuối, thông điệp chính rất dễ bị bỏ lỡ.

Mỗi tầng trong kim tự tháp phải trả lời được câu hỏi mà tầng trên nó gợi ra (nguyên tắc "Vì sao?" — "Tại sao?"), và các ý ở cùng một tầng nên có logic loại trừ lẫn nhau, gộp lại đầy đủ (kiểu tư duy MECE — Mutually Exclusive, Collectively Exhaustive), không chồng chéo, không bỏ sót mảng lớn.

### Kỹ thuật mở đầu SCQA
SCQA (Situation - Complication - Question - Answer) **không phải một framework độc lập** — đây là **kỹ thuật mở đầu/dẫn nhập** thường dùng ngay trước khi nêu đỉnh kim tự tháp, để dẫn dắt người nghe/đọc đi đến kết luận một cách tự nhiên thay vì nói suông kết luận mà không có bối cảnh:

- **Situation (Bối cảnh)** — nêu một thực tế/bối cảnh chung mà người nghe/đọc đã biết và đồng ý, không gây tranh cãi. Mục đích là tạo điểm chung để bắt đầu.
- **Complication (Vướng mắc)** — một thay đổi/vấn đề/rủi ro mới xuất hiện làm xáo trộn bối cảnh ổn định đó — đây là lý do khiến người nghe/đọc cần quan tâm ngay bây giờ.
- **Question (Câu hỏi)** — câu hỏi tự nhiên bật ra từ vướng mắc đó (thường không cần nói thành lời, người nghe tự nghĩ ra: "vậy giờ phải làm sao?").
- **Answer (Câu trả lời)** — chính là **ý chính/kết luận ở đỉnh kim tự tháp**. SCQA kết thúc đúng vào chỗ kim tự tháp bắt đầu.

Nói cách khác: dùng SCQA để viết **đoạn mở đầu** của báo cáo/bài trình bày (vài câu), sau đó toàn bộ phần thân còn lại triển khai theo đúng cấu trúc kim tự tháp đầy đủ (luận điểm nhóm theo logic + dữ liệu chứng minh). Không dùng SCQA thay cho toàn bộ cấu trúc trình bày.

## Input cần thu thập
1. Ý chính/kết luận/khuyến nghị người dùng muốn truyền đạt (nếu người dùng chưa tự chốt được, hỏi thẳng: "nếu chỉ được nói 1 câu, bạn muốn người nghe nhớ điều gì?").
2. Đối tượng nghe/đọc (sếp, khách hàng, cả team...) — ảnh hưởng đến việc chọn luận điểm nào quan trọng nhất với họ.
3. Các luận điểm/lý do hỗ trợ và dữ liệu/dẫn chứng đã có — nếu người dùng kể lan man theo trình tự thời gian, Claude cần **tự sắp xếp lại** thành nhóm logic, không giữ nguyên thứ tự kể chuyện gốc.
4. Bối cảnh và vướng mắc (nếu cần viết đoạn mở đầu SCQA) — bối cảnh chung đã biết là gì, điều gì mới thay đổi khiến vấn đề trở nên cấp thiết.

## Output — luôn theo đúng cấu trúc
```
## Mở đầu (SCQA)
- Bối cảnh: [thực tế chung, không gây tranh cãi]
- Vướng mắc: [thay đổi/vấn đề mới phát sinh]
- Câu hỏi ngầm: [câu hỏi tự nhiên bật ra]
- Trả lời: [chính là ý chính bên dưới — nêu ngắn gọn ở đây để khép lại phần mở đầu]

## Đỉnh — Ý chính / Kết luận
[1-2 câu nêu thẳng kết luận/khuyến nghị chính, không rào đón]

## Luận điểm hỗ trợ (nhóm theo logic — MECE)
1. [Luận điểm 1 — trả lời "vì sao kết luận đúng" theo khía cạnh 1]
   - Dữ liệu/dẫn chứng: [...]
2. [Luận điểm 2 — khía cạnh khác, không trùng lặp luận điểm 1]
   - Dữ liệu/dẫn chứng: [...]
3. [Luận điểm 3 — khía cạnh còn lại]
   - Dữ liệu/dẫn chứng: [...]

## Kết
[1 câu nhắc lại ý chính + hành động/quyết định mong muốn từ người nghe]
```

## Ví dụ (rút gọn)
**Input**: "Tôi cần viết email cho sếp đề xuất chuyển nhà cung cấp dịch vụ cloud vì bên hiện tại tăng giá và hay downtime, nhưng tôi hơi ngại vì đây là thay đổi lớn."

**Output**:
- Mở đầu (SCQA): Bối cảnh — team đang dùng nhà cung cấp cloud A ổn định 2 năm qua. Vướng mắc — 3 tháng gần đây A tăng giá 30% và có 2 lần downtime ảnh hưởng khách hàng. Câu hỏi ngầm — có nên tiếp tục dùng A không? Trả lời — nên chuyển sang nhà cung cấp B trong quý tới.
- Đỉnh: Đề xuất chuyển toàn bộ hạ tầng sang nhà cung cấp B trong Q_ tới.
- Luận điểm 1 (Chi phí): B rẻ hơn 25% ở cùng cấu hình, dẫn chứng bảng báo giá đính kèm.
- Luận điểm 2 (Độ ổn định): B có SLA uptime 99.99% so với 99.9% hiện tại, dẫn chứng lịch sử downtime 2 quý gần nhất.
- Luận điểm 3 (Rủi ro chuyển đổi): đã có kế hoạch migrate từng phần trong 6 tuần để giảm rủi ro gián đoạn.
- Kết: Đề nghị sếp duyệt ngân sách và mốc thời gian bắt đầu migrate từ tuần sau.

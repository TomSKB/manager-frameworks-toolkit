# Chẩn đoán nhóm vấn đề (dùng khi input mơ hồ)

Dùng file này khi người dùng mô tả vấn đề một cách **mơ hồ/cảm tính** — không nêu rõ tên vấn đề, không map thẳng được vào 1 trong 11 nhóm chủ đề bên dưới. Ví dụ: "team dạo này kỳ kỳ", "tôi thấy mệt mỏi với công việc quản lý", "có gì đó không ổn nhưng không biết là gì".

Mục tiêu: hỏi **tối đa 2-3 câu**, đủ để xác định đúng 1 trong **11 nhóm chủ đề**, rồi chuyển sang skill tương ứng của nhóm đó để nó tự chọn framework cụ thể (mỗi skill nhóm đã có sẵn bảng quyết định riêng cho các framework bên trong nó — bạn không cần đoán tới tận framework cụ thể ở bước này).

Không dùng file này nếu người dùng đã mô tả đủ cụ thể (ví dụ nói thẳng "nhân viên tôi giao việc không làm" hoặc gọi tên 1 framework) — lúc đó xác định thẳng nhóm chủ đề phù hợp, không cần hỏi thêm.

## 11 nhóm chủ đề (skill tương ứng)

| Nhóm | Mô tả ngắn | Skill |
|---|---|---|
| Định hướng & Chiến lược | Không biết đi đâu, cần đánh giá thị trường/tổ chức/lợi thế cạnh tranh trước quyết định lớn | `dinh-huong-chien-luoc` |
| Tư duy & Ra quyết định | Có sự việc/quyết định chưa rõ nguyên nhân, thiếu toàn diện, hoặc không biết nên tiếp cận kiểu gì | `tu-duy-quyet-dinh` |
| Đặt mục tiêu & Lập kế hoạch | Mục tiêu mơ hồ, đội nhóm lệch hướng, thiếu kế hoạch hành động | `muc-tieu-ke-hoach` |
| Giải quyết vấn đề & Cải tiến vận hành | Sự cố/lỗi vận hành lặp lại, cần cải tiến liên tục, hoặc cần dẫn dắt 1 thay đổi lớn cấp tổ chức | `giai-quyet-van-de-van-hanh` |
| Giao việc & Quản lý công việc nhóm | Giao việc không hiệu quả, trách nhiệm chồng chéo trong dự án nhiều người, phân vân nên chỉ đạo sát hay trao quyền | `giao-viec-quan-ly-nhom` |
| Tạo động lực & Phát triển nhân sự | Nhân viên mất động lực, biết-muốn-làm-nhưng-không-làm-được, hoặc cần cải thiện giao tiếp/tự nhận thức trong nhóm | `dong-luc-phat-trien-nhan-su` |
| Đánh giá hiệu suất & Phản hồi | Cần chuẩn bị phỏng vấn/đánh giá thành tích, hoặc cần đưa phản hồi khó cho nhân viên | `danh-gia-phan-hoi` |
| Giao tiếp & Trình bày ý tưởng | Cần viết báo cáo/thuyết trình đi thẳng vào ý chính, dẫn dắt họp rút kinh nghiệm, hoặc nghi ngờ mâu thuẫn sâu hơn bề mặt | `giao-tiep-trinh-bay` |
| Giải quyết xung đột & Đàm phán | Mâu thuẫn giữa 2 người cần hoà giải, hoặc chuẩn bị/đang đàm phán lợi ích | `xung-dot-dam-phan` |
| Quản lý thời gian & Năng suất cá nhân | Hay trì hoãn/mất tập trung, hoặc quá tải không biết ưu tiên việc gì | `thoi-gian-nang-suat` |
| Xây dựng & Phát triển đội nhóm | Team mới chưa ăn ý, hoặc muốn biết team đang ở giai đoạn phát triển nào | `xay-dung-doi-nhom` |

## Cây câu hỏi thu hẹp theo nhóm triệu chứng gần nhất

### Nhóm triệu chứng 1 — "Có gì đó không ổn với một nhân viên/cả team, chuyện con người"
1. Vấn đề nằm ở **hiệu suất/kết quả công việc** hay ở **tinh thần/thái độ/hành vi**?
   - Hiệu suất, do giao việc chưa rõ (tiêu chuẩn/deadline/xác nhận hiểu) → **Giao việc & Quản lý công việc nhóm**.
   - Hiệu suất, do không biết cách làm dù đã hiểu rõ việc → **Đặt mục tiêu & Lập kế hoạch** (GROW).
   - Tinh thần/thái độ: hỏi tiếp — họ có vẻ **không muốn làm** (chán nản, thiếu chủ động) hay **muốn làm nhưng vẫn không làm được** (biết rõ, có động lực, nhưng hành vi/thói quen không xảy ra)?
     - Không muốn làm → **Tạo động lực & Phát triển nhân sự** (Maslow).
     - Muốn làm nhưng không làm được → **Tạo động lực & Phát triển nhân sự** (Fogg Behavior Model — vẫn cùng skill, chỉ khác framework bên trong).
2. Vấn đề là của **1 người cụ thể** hay **cả nhóm cùng lúc, mới hình thành/đang va chạm**?
   - Cả nhóm, mới hình thành hoặc đang va chạm vai trò/quy trình → **Xây dựng & Phát triển đội nhóm** (Tuckman).
   - Cả nhóm, mỗi người một hướng nhưng không phải do mới hình thành mà do thiếu đích chung theo kỳ → **Đặt mục tiêu & Lập kế hoạch** (OKR).

### Nhóm triệu chứng 2 — "Xung đột/mâu thuẫn giữa người với người, hoặc cần đàm phán"
1. Đây là **mâu thuẫn/xung đột cảm xúc** giữa 2 người cần hàn gắn trước, hay là **đàm phán lợi ích/điều khoản** (lương, hợp đồng, deal)?
   - Mâu thuẫn cảm xúc → **Giải quyết xung đột & Đàm phán** (LEAPS).
   - Đàm phán lợi ích → **Giải quyết xung đột & Đàm phán** (Getting to Yes/BATNA).
2. Nếu mâu thuẫn có vẻ **sâu hơn bề mặt hành vi** (khác biệt niềm tin/giá trị, không chỉ là 1 hành động cụ thể) → cân nhắc **Giao tiếp & Trình bày ý tưởng** (NLP Logical Levels) để xác định đúng tầng vấn đề trước khi hoà giải.

### Nhóm triệu chứng 3 — "Cần đưa đánh giá/phản hồi cho ai đó"
1. Đây là **đánh giá thành tích/chuẩn bị phỏng vấn** (kể lại 1 case đã xảy ra, có kết quả) hay là **phản hồi về 1 hành vi cần điều chỉnh** (đặc biệt phản hồi khó)?
   - Đánh giá thành tích/phỏng vấn → **Đánh giá hiệu suất & Phản hồi** (STAR).
   - Phản hồi hành vi cần điều chỉnh → **Đánh giá hiệu suất & Phản hồi** (SBI).

### Nhóm triệu chứng 4 — "Có gì đó không ổn với cách ra quyết định/họp hành/hiểu vấn đề"
1. Quyết định gần đây **thiếu cân nhắc** (bỏ sót góc nhìn/rủi ro) → **Tư duy & Ra quyết định** (Six Thinking Hats).
2. Có 1 **sự việc/sự cố cụ thể chưa rõ nguyên nhân** → **Tư duy & Ra quyết định** (5W2H để mô tả, hoặc 5 Whys nếu chỉ cần đào nguyên nhân gốc theo 1 chuỗi).
3. Vấn đề **phức tạp/hỗn loạn, không chắc nên tiếp cận kiểu gì** (thử nghiệm hay áp best-practice) → **Tư duy & Ra quyết định** (Cynefin).
4. Cần **so sánh hiện trạng với mục tiêu mong muốn** trước khi lập kế hoạch → **Tư duy & Ra quyết định** (Gap Analysis).
5. Cần **cấu trúc nhanh 1 lập luận/báo cáo ngắn** từ dữ kiện tới hành động → **Tư duy & Ra quyết định** (Sky-Rain-Umbrella).

### Nhóm triệu chứng 5 — "Cần viết/nói/trình bày điều gì đó cho rõ ràng, thuyết phục"
1. Cần viết báo cáo/email/thuyết trình đi thẳng vào ý chính → **Giao tiếp & Trình bày ý tưởng** (Minto Pyramid + SCQA).
2. Cần dẫn dắt 1 buổi họp rút kinh nghiệm/debrief sau dự án → **Giao tiếp & Trình bày ý tưởng** (ORID).

### Nhóm triệu chứng 6 — "Có một sự cố/vấn đề vận hành cụ thể, hoặc cần thay đổi lớn"
1. Sự cố **lặp lại nhiều lần** trong vận hành hàng ngày → **Giải quyết vấn đề & Cải tiến vận hành** (Toyota 8-step).
2. Vấn đề **kinh doanh/chiến lược phức tạp**, đã thử nhiều lần chưa dứt điểm → **Giải quyết vấn đề & Cải tiến vận hành** (McKinsey 7-step).
3. Cần **cải tiến liên tục 1 quy trình** theo chu kỳ (không phải 1 sự cố cụ thể) → **Giải quyết vấn đề & Cải tiến vận hành** (PDCA).
4. Cần **dẫn dắt 1 thay đổi lớn cấp tổ chức** (tái cấu trúc, chuyển đổi văn hoá) → **Giải quyết vấn đề & Cải tiến vận hành** (Kotter 8-step).

### Nhóm triệu chứng 7 — "Cần sắp xếp/ưu tiên công việc cho bản thân"
1. Quá tải, không biết ưu tiên việc gì → **Quản lý thời gian & Năng suất cá nhân** (Eisenhower Matrix).
2. Đã biết việc cần làm nhưng khó tập trung/hay bị gián đoạn → **Quản lý thời gian & Năng suất cá nhân** (Pomodoro).

### Nhóm triệu chứng 8 — "Có gì đó không ổn ở cấp tổ chức/hướng đi kinh doanh lớn hơn"
1. Mối lo từ **bên ngoài** (thị trường, đối thủ, kinh tế) → **Định hướng & Chiến lược** (PESTEL).
2. Mối lo từ **bên trong** (đội ngũ, cơ cấu, cách vận hành không ăn khớp) → **Định hướng & Chiến lược** (McKinsey 7S).
3. Cần đánh giá tổng quan **điểm mạnh/yếu/cơ hội/rủi ro** trước 1 quyết định → **Định hướng & Chiến lược** (SWOT).
4. Cần tìm **lợi thế cạnh tranh/tối ưu chi phí** trong chuỗi hoạt động → **Định hướng & Chiến lược** (Value Chain).
5. Chưa biết bắt đầu từ đâu, cần xây tầm nhìn/thông điệp → **Định hướng & Chiến lược** (Golden Circle).

## Nếu vẫn không rõ sau khi hỏi

Đọc lại bảng 11 nhóm ở trên và hỏi thẳng: "Nếu phải chọn 1 mô tả đúng nhất với tình huống của bạn trong các câu sau, bạn chọn câu nào: [liệt kê 4-5 dòng 'Mô tả ngắn' gần nhất từ bảng]?" — để người dùng tự chỉ ra, thay vì đoán thêm.

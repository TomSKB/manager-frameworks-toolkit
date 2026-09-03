---
name: giao-viec-quan-ly-nhom
description: 'LUÔN dùng khi người quản lý gặp vấn đề về giao việc và quản lý công việc nhóm. Gồm 3 framework: (1) 8 bước giao việc — dùng khi giao việc mà nhân viên không làm/làm sai/làm trễ; (2) Ma trận RACI — dùng khi 1 dự án nhiều người tham gia đang không rõ ai làm, ai chịu trách nhiệm cuối, ai cần được hỏi ý kiến, ai chỉ cần biết kết quả; (3) Situational Leadership (Hersey-Blanchard) — dùng khi phân vân nên chỉ đạo sát sao hay nên tin tưởng giao toàn quyền cho 1 nhân viên với 1 việc cụ thể. Luôn chẩn đoán đúng khái niệm trước khi chọn framework, không nhảy thẳng vào 1 framework khi vấn đề thật ra thuộc nhóm khác.'
---

# Giao Việc & Quản Lý Công Việc Nhóm

Người quản lý phân vân về giao việc thường rơi vào 1 trong 3 tình huống rất khác nhau: (1) đã giao 1 việc cụ thể cho 1 người nhưng kết quả không như ý, (2) 1 dự án có nhiều người tham gia đang bị chồng chéo trách nhiệm, hoặc (3) không chắc nên can thiệp sâu hay nên buông tay với 1 nhân viên. Ba framework trong skill này xử lý đúng 3 tình huống đó — chọn sai sẽ khiến người dùng nhận một câu trả lời đúng công cụ nhưng sai vấn đề.

## Luồng xử lý

1. **Xác định đúng loại vấn đề** — đọc kỹ mô tả của người dùng: đang nói về 1 việc/1 người (→ 8-bước-giao-việc hoặc Situational Leadership), hay về 1 dự án/nhiều người (→ RACI)? Nếu chưa rõ, hỏi lại 1 câu ngắn trước khi chọn framework, đừng đoán.
2. **Chọn framework** theo bảng quyết định bên dưới. Nếu vấn đề pha trộn (ví dụ vừa cần phân vai RACI cho dự án vừa cần giao từng phần việc cụ thể), nói rõ nên dùng framework nào trước, framework nào sau.
3. **Đọc file `references/<framework>.md`** tương ứng để lấy đúng định nghĩa, input cần hỏi và định dạng output chuẩn.
4. **Thu thập input còn thiếu** — chỉ hỏi những gì thật sự cần (xem mục "Input cần thu thập" trong từng reference file), không hỏi tràn lan nếu đã suy luận được từ mô tả của người dùng.
5. **Áp dụng vào case thật** — luôn điền tên việc, tên người, bối cảnh cụ thể của người dùng vào đúng cấu trúc output quy định, không trả lời lý thuyết chung chung.
6. **Gợi ý bước tiếp theo** nếu hợp lý — ví dụ sau khi dùng RACI phân vai cho cả dự án, hỏi người dùng có muốn dùng tiếp 8-bước-giao-việc để giao chi tiết từng đầu việc cho người R đã chốt không.

## Bảng quyết định

| Khái niệm vấn đề | Biểu hiện điển hình | Dùng framework | File reference |
|---|---|---|---|
| Giao việc không hiệu quả | Đã giao việc cho 1 người nhưng người đó không làm/làm sai/làm trễ | 8 bước giao việc (delegation) | `references/delegation-8step.md` |
| Trách nhiệm chồng chéo trong công việc nhiều người tham gia | Dự án/công việc có nhiều người liên quan, không rõ ai làm, ai quyết cuối, ai cần hỏi ý kiến, ai chỉ cần biết kết quả | Ma trận RACI | `references/raci.md` |
| Không chắc nên chỉ đạo sát hay nên trao quyền cho 1 nhân viên với 1 việc cụ thể | Phân vân giữa kiểm soát chặt và buông tay, sợ can thiệp quá sâu hoặc sợ buông quá sớm | Situational Leadership (Hersey-Blanchard) | `references/situational-leadership.md` |

## Ranh giới hay bị nhầm

- **8-bước-giao-việc vs RACI**: 8-bước-giao-việc là quy trình giao **1 việc cụ thể cho 1 người** thật kỹ — làm rõ tiêu chuẩn, thời hạn, xác nhận hai bên hiểu đúng như nhau. RACI là công cụ phân vai cho **1 dự án có nhiều người, nhiều đầu việc** — dùng trước, ở cấp tổng thể, để xác định "ai làm gì, ai quyết cuối". Thứ tự hợp lý khi vấn đề pha trộn cả hai: dùng RACI trước để chốt vai trò tổng thể, sau đó dùng 8-bước-giao-việc để giao chi tiết từng phần việc cho từng người R/A đã xác định.
- **8-bước-giao-việc vs Situational Leadership**: 8-bước-giao-việc tập trung vào **cách giao 1 việc cho rõ ràng** (nội dung, tiêu chuẩn, thời hạn). Situational Leadership giúp chọn **đúng mức độ can thiệp/phong cách lãnh đạo** tùy theo năng lực và sự tự tin của người nhận việc với việc đó. Nên dùng Situational Leadership **trước** để biết nên chỉ đạo sát hay buông tay, rồi mới dùng 8-bước-giao-việc để thực thi việc giao theo đúng mức độ can thiệp đã chọn (ví dụ ở mức S1 thì bước 2-3-4 của 8-bước-giao-việc cần chi tiết hơn hẳn so với ở mức S4).
- **8-bước-giao-việc vs Tháp Maslow** (thuộc skill khác — `dong-luc-phat-trien-nhan-su`): nếu vấn đề là nhân viên **không biết làm sao** (thiếu hướng dẫn/tiêu chuẩn/thời hạn rõ ràng) → dùng framework trong skill này. Nếu vấn đề là nhân viên **không muốn làm** (thiếu động lực dù đã hiểu rõ việc) → đó không phải vấn đề giao việc, chuyển sang skill "dong-luc-phat-trien-nhan-su" (Tháp Maslow) thay vì cố dùng framework ở đây.

## Nguyên tắc chung

- **Xác định đúng cấp độ vấn đề trước khi chọn framework** — 1 việc/1 người khác hẳn 1 dự án/nhiều người, đừng để người dùng tự đoán nhầm rồi áp sai công cụ.
- **Không hỏi những gì có thể suy luận hợp lý** từ mô tả của người dùng, nhưng cũng không tự bịa tên người, thời hạn, hoặc mức năng lực khi framework cần dữ liệu chính xác (đặc biệt là RACI và Situational Leadership) — những trường hợp này phải hỏi lại.
- **Luôn gắn framework vào case cụ thể** người dùng đưa ra, trả về đúng định dạng output quy định trong reference file, không trả lời lý thuyết chung chung.
- **Nêu rõ đang dùng framework nào và vì sao** ngay đầu câu trả lời (1 câu ngắn), để người dùng học được cách tự chọn framework cho lần sau.
- Khi vấn đề cần nối tiếp nhiều framework (RACI rồi tới 8-bước-giao-việc, hoặc Situational Leadership rồi tới 8-bước-giao-việc), nói rõ thứ tự và lý do, đừng chạy dồn cả 2-3 framework cùng lúc khi không ai yêu cầu.
- **Không giả định người dùng đã biết ý nghĩa của ký hiệu viết tắt** — nhiều người dùng skill này lần đầu, không có nền tảng quản lý dự án (ví dụ chính là stakeholder không rành kỹ thuật/quản lý được mời dùng plugin). Khi output có ký hiệu như R/A/C/I hay S1-S4, luôn giải thích ngắn gọn ngay trong output (xem mục "Chú thích ký hiệu" ở đầu file `references/raci.md`) — đừng chỉ giải thích trong đầu rồi đưa thẳng bảng ký hiệu ra mà không kèm chú thích.

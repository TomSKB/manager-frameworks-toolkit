---
name: thoi-gian-nang-suat
description: 'Quản lý thời gian & năng suất cá nhân: tự động áp dụng Pomodoro, Ma trận Eisenhower, GTD Weekly Review, hoặc Deep Work/Time-blocking khi người dùng vật lộn với tập trung hoặc ưu tiên công việc — không cần gọi đúng tên framework. Dùng khi: hay trì hoãn, dễ xao nhãng khi làm 1 việc cụ thể cần tập trung sâu (Pomodoro); quá tải, luôn "chữa cháy", to-do dài không biết ưu tiên gì (Eisenhower); quên trước quên sau, việc/email/dự án tồn đọng, cần rà soát định kỳ "làm sạch" hệ thống công việc (GTD Weekly Review); hoặc lịch bị họp hành/việc nông chiếm hết, không có khối thời gian dài để làm việc cần tư duy sâu (Deep Work/Time-blocking). Nhận cả gõ sai/viết tắt như "pomodoro", "eisenhower matrix", "gtd", "getting things done", "deep work", "time blocking". Luôn ưu tiên skill này thay vì tự đưa lời khuyên quản lý thời gian chung chung.'
---

# Quản lý thời gian & Năng suất cá nhân — Pomodoro, Ma trận Eisenhower, GTD Weekly Review, Deep Work/Time-blocking

## Vì sao 4 framework này đi chung một nhóm

Cả bốn đều giải quyết vấn đề năng suất cá nhân, nhưng ở các lớp khác nhau, nối tiếp nhau theo trình tự tự nhiên:

1. **GTD Weekly Review** — giải quyết bài toán **danh sách việc có đầy đủ và đáng tin cậy không**: trước khi ưu tiên hay tập trung làm bất cứ việc gì, cần chắc chắn không có việc/dự án nào đang bị bỏ sót hoặc quên theo dõi.
2. **Ma trận Eisenhower** — giải quyết bài toán **ưu tiên giữa nhiều việc**: trong danh sách đã đầy đủ đó, nên làm việc nào trước, việc nào lên lịch sau, việc nào uỷ quyền, việc nào bỏ hẳn.
3. **Deep Work/Time-blocking** — giải quyết bài toán **quy hoạch lịch ở cấp ngày/tuần**: đảm bảo có đủ khối thời gian liên tục, không bị họp hành/việc nông chia vụn, để thực sự làm những việc quan trọng vừa chọn ở bước trên.
4. **Kỹ thuật Pomodoro** — giải quyết bài toán **tập trung trong 1 phiên làm việc ngắn**: khi đã ngồi vào đúng khối thời gian đã lên lịch, làm sao giữ tập trung không bị gián đoạn liên tục.

Nói cách khác, trình tự đầy đủ khi cần dùng nối tiếp: GTD Weekly Review (đảm bảo danh sách đầy đủ) → Eisenhower Matrix (chọn việc quan trọng) → Deep Work/Time-blocking (lên lịch khối thời gian cho việc đó ở cấp tuần) → Pomodoro (thực sự ngồi làm trong từng phiên ngắn).

## Luồng xử lý

1. **Chọn framework** theo bảng quyết định dưới đây, dựa trên tình huống người dùng mô tả. Nếu tình huống chạm nhiều lớp cùng lúc (ví dụ vừa quên việc vừa quá tải vừa khó tập trung), nói rõ nên chạy framework nào trước theo đúng trình tự ở trên, đừng chạy dồn hết một lúc khi không ai yêu cầu.
2. **Đọc file `references/<framework>.md`** tương ứng để lấy đúng định nghĩa, nguyên tắc, input cần hỏi và định dạng output chuẩn.
3. **Thu thập input còn thiếu** — chỉ hỏi những gì thật sự cần (xem mục "Input cần thu thập" trong từng reference), đừng hỏi thừa nếu người dùng đã kể đủ trong mô tả ban đầu.
4. **Áp dụng vào case thật** của người dùng — luôn điền nội dung cụ thể (tên việc, thời lượng, người liên quan) vào template, không trả lời lý thuyết chung chung.
5. **Đưa output đúng định dạng** quy định trong reference file (bảng 4 ô cho Eisenhower Matrix, các bước Get Clear/Current/Creative cho GTD Weekly Review, lịch khối thời gian cho Deep Work/Time-blocking, hoặc lịch trình pomodoro cụ thể cho Pomodoro).
6. **Gợi ý bước tiếp theo** nếu hợp lý — ví dụ sau GTD Weekly Review có thể gợi ý chạy Eisenhower Matrix để ưu tiên danh sách vừa làm sạch; sau khi dùng Eisenhower Matrix chọn ra 1-2 việc ở Ô 1/Ô 2 cần tập trung làm, gợi ý Deep Work/Time-blocking nếu việc đó cần nhiều giờ liên tục, hoặc Pomodoro nếu chỉ cần 1 phiên tập trung ngắn.

## Bảng quyết định

| Khái niệm vấn đề | Biểu hiện điển hình | Dùng framework | File reference |
|---|---|---|---|
| Quên trước quên sau, hệ thống công việc bị tồn đọng | Cảm giác luôn có việc gì đó có thể đang bị bỏ sót, email/ghi chú/dự án tồn đọng không kiểm soát được, cần một nghi thức rà soát định kỳ | GTD Weekly Review | `references/gtd-weekly-review.md` |
| Quá tải, chưa biết ưu tiên gì | Có nhiều việc cùng lúc, không biết nên ưu tiên làm gì trước, luôn cảm thấy chỉ đang chữa cháy | Ma trận Eisenhower | `references/eisenhower-matrix.md` |
| Lịch bị chia vụn, không có khối thời gian dài để làm việc cần tư duy sâu | Cả ngày/tuần bị họp hành/việc nông chiếm hết, dù mỗi lúc vẫn tập trung được nhưng chưa bao giờ có nổi vài giờ liền để làm việc đòi hỏi tư duy sâu | Deep Work/Time-blocking | `references/deep-work-time-blocking.md` |
| Khó tập trung khi làm một việc cụ thể | Khó tập trung/hay bị gián đoạn khi làm 1 việc cụ thể cần sự tập trung sâu | Kỹ thuật Pomodoro | `references/pomodoro.md` |

## Ranh giới hay bị nhầm

- **Ma trận Eisenhower vs Pomodoro**: Eisenhower Matrix giải quyết bài toán **ưu tiên giữa nhiều việc** — nên làm việc nào trước, việc nào lên lịch, việc nào uỷ quyền, việc nào bỏ. Pomodoro giải quyết bài toán **tập trung khi đã chọn xong 1 việc cụ thể** để làm — không giúp chọn việc, chỉ giúp ngồi làm việc đó không bị xao nhãng. Hai framework **bổ trợ nhau theo trình tự**: dùng Eisenhower Matrix để **chọn** việc quan trọng cần làm trước (đặc biệt ưu tiên Ô 2 — quan trọng nhưng không khẩn cấp, vì đây là nơi tạo giá trị dài hạn lớn nhất nhưng dễ bị bỏ quên), rồi dùng Pomodoro để **thực sự ngồi làm** việc đó tới cùng. Nếu người dùng nói "tôi không biết nên làm gì trước" → Eisenhower Matrix; nếu nói "tôi biết phải làm gì rồi nhưng cứ ngồi vào là bị xao nhãng" → Pomodoro.
- **GTD Weekly Review vs Ma trận Eisenhower**: GTD Weekly Review trả lời câu hỏi **"danh sách việc của tôi đã đầy đủ và đáng tin cậy chưa"** — dùng khi nghi ngờ có việc/dự án đang bị bỏ sót hoặc quên theo dõi. Ma trận Eisenhower trả lời câu hỏi **"trong danh sách đã có, nên ưu tiên làm gì trước"** — giả định danh sách đã đầy đủ rồi mới sắp xếp. Nếu người dùng vừa "cảm giác quên việc gì đó" vừa "không biết ưu tiên gì", chạy GTD Weekly Review trước để làm sạch/đầy đủ danh sách, sau đó mới chạy Eisenhower Matrix để ưu tiên danh sách đó.
- **Deep Work/Time-blocking vs Pomodoro**: hai công cụ này dễ nhầm vì cùng nhắm tới "tập trung làm việc", nhưng khác cấp độ quy hoạch. Deep Work/Time-blocking quy hoạch ở cấp **ngày/tuần** — đảm bảo có tồn tại một khối thời gian đủ dài (1.5-4 giờ) để bắt đầu việc sâu, giải quyết vấn đề gốc là lịch bị họp hành chia vụn. Pomodoro hoạt động ở cấp **một phiên làm việc ngắn** (25 phút/lần) — giúp giữ tập trung trong khối thời gian đã có sẵn, không tự tạo ra khối thời gian mới. Nếu người dùng "không bao giờ có nổi 2 tiếng liền không bị họp chen ngang" → Deep Work/Time-blocking trước; nếu đã có sẵn khối thời gian nhưng vẫn hay xao nhãng trong lúc đó → Pomodoro là đủ.
- **Deep Work/Time-blocking vs Ma trận Eisenhower**: Eisenhower Matrix quyết định **nên làm việc gì** (chọn việc). Deep Work/Time-blocking quyết định **khi nào và bảo vệ thời gian ra sao** để thực sự làm việc đã chọn đó (quy hoạch lịch). Luôn dùng Eisenhower trước để biết việc nào xứng đáng một khối Deep Work, tránh dành hẳn 3 giờ liền quý giá cho một việc thực ra không quan trọng.

## Nguyên tắc chung

- **Không hỏi thừa** những gì người dùng đã nói rõ hoặc có thể suy luận hợp lý từ mô tả của họ.
- **Không tự bịa danh sách việc, deadline hay tên người** — nếu người dùng chưa liệt kê đủ việc cần sắp xếp (Eisenhower Matrix, GTD Weekly Review) hoặc chưa chọn rõ việc cần tập trung làm (Pomodoro, Deep Work/Time-blocking), phải hỏi lại chứ không suy diễn hay điền đại.
- **Luôn gắn framework vào case cụ thể** của người dùng, không trả lời lý thuyết chung chung.
- **Nêu rõ đang dùng framework nào và vì sao** trong 1 câu ngắn ở đầu câu trả lời, để người dùng học được cách tự chọn cho lần sau.
- Nếu người dùng chỉ hỏi tư vấn ("nên dùng Pomodoro hay Eisenhower cho trường hợp này?") mà chưa cần áp dụng ngay, có thể dừng lại sau khi chọn framework + giải thích lý do, chưa cần điền toàn bộ worksheet.
- **Không giả định người dùng đã biết ý nghĩa của các ký hiệu/chữ viết tắt trong framework** — nhiều người dùng plugin này lần đầu, không có nền tảng quản lý. Khi output dùng ký hiệu viết tắt (ví dụ tên các trục/tầng/bước chỉ viết gọn 1-2 chữ), luôn giải thích ngắn gọn ý nghĩa ngay trong output, đừng chỉ giải thích khi được hỏi lại.

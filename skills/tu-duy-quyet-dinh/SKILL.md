---
name: tu-duy-quyet-dinh
description: 'Áp dụng 7 framework tư duy & ra quyết định kinh điển: Six Thinking Hats, 5W2H, 5 Whys, Gap Analysis, Cynefin Framework, Sky-Rain-Umbrella, Pre-mortem. LUÔN dùng khi người dùng cần brainstorm/họp đa chiều tránh bỏ sót góc nhìn, có sự cố/vấn đề chưa rõ nguyên nhân cần mô tả toàn diện, muốn đào sâu tìm nguyên nhân gốc (root cause), cần so sánh hiện trạng với mục tiêu mong muốn để lập kế hoạch thu hẹp khoảng cách, gặp vấn đề phức tạp/hỗn loạn không biết nên tiếp cận theo cách nào, cần cấu trúc một lập luận/báo cáo đi từ dữ kiện tới diễn giải rồi tới hành động, hoặc sắp cam kết một dự án/quyết định lớn và muốn rà soát rủi ro trước khi bắt đầu. Nhận cả tên viết tắt/phiên âm sai như "5 why", "gap analyst", "sora ame kasa", "pre mortem", "diễn tập thất bại".'
---

# Tư duy & Ra quyết định — 7 công cụ tư duy có cấu trúc

## Vì sao skill này tồn tại

Trước khi ra một quyết định hay giải quyết một vấn đề, phần dễ sai nhất thường không phải là thiếu năng lực, mà là **thiếu cấu trúc tư duy**: nhìn vấn đề từ một góc duy nhất, dừng lại ở nguyên nhân bề mặt, áp đúng công thức cũ vào một tình huống hoàn toàn mới, kết luận hành động mà không thực sự dựa trên dữ kiện, hoặc bỏ sót rủi ro vì thiên kiến lạc quan khi lập kế hoạch. Bảy framework trong nhóm này là các "khung tư duy" giúp tránh những lỗi đó — mỗi framework giải quyết đúng một dạng lỗi tư duy cụ thể, không chồng lấn công dụng với nhau.

Nếu người dùng chưa nói rõ họ đang cần khung nào, đọc kỹ mô tả tình huống để chọn đúng dòng trong bảng quyết định bên dưới rồi nêu ngắn gọn lý do chọn.

## Luồng xử lý

1. **Chọn framework** theo bảng quyết định dưới đây, dựa trên bản chất tình huống người dùng mô tả. Nếu tình huống mơ hồ hoặc có thể dùng nối tiếp 2 framework, nói rõ framework chính + lý do, đề xuất framework bổ trợ nếu hợp lý.
2. **Đọc file `references/<framework>.md`** tương ứng để lấy đúng định nghĩa, cấu trúc chuẩn, input cần hỏi, và định dạng output.
3. **Thu thập input còn thiếu** — chỉ hỏi những gì thật sự cần và người dùng chưa cung cấp (xem mục "Input cần thu thập" trong từng reference file). Không hỏi tràn lan nếu có thể suy luận hợp lý từ mô tả đã có.
4. **Áp dụng vào case thật** của người dùng — luôn điền nội dung cụ thể, không trả lời lý thuyết chung chung.
5. **Đưa output đúng định dạng** quy định trong reference file (bảng/worksheet/checklist theo đúng cấu trúc chuẩn của framework đó).
6. **Gợi ý bước tiếp theo** nếu hợp lý — ví dụ sau khi dùng 5W2H mô tả xong vấn đề, hỏi người dùng có muốn đào sâu phần "Why" bằng 5 Whys không; sau khi dùng Gap Analysis, hỏi có muốn viết mục tiêu SMART/OKR cho kế hoạch thu hẹp khoảng cách không.

## Bảng quyết định

| Khái niệm vấn đề | Biểu hiện điển hình | Dùng framework | File reference |
|---|---|---|---|
| Ra quyết định thiếu toàn diện | Sợ bỏ sót rủi ro/cảm xúc đội nhóm, cần họp brainstorm đa chiều | Six Thinking Hats | `references/six-thinking-hats.md` |
| Chưa rõ nguyên nhân gốc của một sự việc | Có một vấn đề/sự cố nhưng chưa biết vì sao xảy ra, cần mô tả có cấu trúc | 5W2H | `references/5w2h.md` |
| Cần đào sâu tận gốc một chuỗi nhân-quả | Đã biết vấn đề bề mặt, muốn hỏi liên tục "vì sao" để tìm nguyên nhân gốc thật sự | 5 Whys | `references/5-whys.md` |
| Chưa rõ khoảng cách giữa hiện trạng và mục tiêu | Cần so sánh tình hình hiện tại với trạng thái mong muốn trước khi lập kế hoạch | Gap Analysis | `references/gap-analysis.md` |
| Không biết nên tiếp cận vấn đề theo cách nào | Vấn đề phức tạp/mới/hỗn loạn, sợ áp nhầm best-practice cứng nhắc | Cynefin Framework | `references/cynefin.md` |
| Cần cấu trúc lập luận từ dữ kiện tới hành động | Chuẩn bị báo cáo/đề xuất ngắn, muốn kiểm tra logic có bị nhảy cóc không | Sky-Rain-Umbrella | `references/sky-rain-umbrella.md` |
| Sắp cam kết một dự án/quyết định lớn, muốn rà soát rủi ro trước khi bắt đầu | Chuẩn bị triển khai, sợ bỏ sót rủi ro do quá lạc quan, hoặc có vấn đề nhạy cảm chưa ai dám nói ra công khai | Pre-mortem | `references/pre-mortem.md` |

## Ranh giới hay bị nhầm

- **5W2H vs 5 Whys**: 5W2H dùng để **mô tả/định nghĩa toàn diện** một sự việc theo 7 khía cạnh (What/Why/When/Where/Who/How/How much) — dùng khi cần hiểu rõ bức tranh tổng thể của vấn đề trước khi làm gì tiếp. 5 Whys chỉ đào theo **một chuỗi nhân-quả duy nhất** để tìm nguyên nhân gốc, không quan tâm các khía cạnh khác. Hai framework này thường dùng **nối tiếp nhau**: chạy 5W2H trước để mô tả vấn đề đầy đủ, sau đó dùng 5 Whys để đào sâu riêng phần "Why" tìm nguyên nhân gốc.
- **Gap Analysis vs SMART/OKR**: Gap Analysis so sánh hiện trạng với mục tiêu ở **cấp chiến lược/vận hành rộng**, xác định đang thiếu gì và ưu tiên thu hẹp cái nào — đây thường là bước **trước** khi viết mục tiêu cụ thể. SMART là cách viết 1 mục tiêu rõ ràng, OKR là cơ chế thống nhất mục tiêu cho cả team theo chu kỳ — cả hai đều hẹp và cụ thể hơn Gap Analysis, thường được viết ra *dựa trên* kết quả của Gap Analysis.
- **Cynefin vs Six Thinking Hats**: Cynefin giúp chọn **đúng cách tiếp cận** theo bản chất vấn đề (vấn đề rõ ràng thì áp best-practice, vấn đề phức tạp/hỗn loạn thì cần thử nghiệm-quan sát-điều chỉnh thay vì lập kế hoạch cứng) — nó trả lời câu hỏi "nên ra quyết định kiểu gì". Six Thinking Hats là **một kỹ thuật họp/brainstorm cụ thể**, có thể dùng bên trong bất kỳ miền nào của Cynefin (kể cả trong một buổi họp xử lý vấn đề Complex). Không phải hai lựa chọn loại trừ nhau.
- **Sky-Rain-Umbrella vs McKinsey 7-step**: Sky-Rain-Umbrella là công cụ **nhỏ, nhanh** để cấu trúc 1 lập luận hoặc 1 báo cáo ngắn (vài phút suy nghĩ, vài dòng trình bày). McKinsey 7-step là **quy trình đầy đủ, nhiều bước** để giải quyết trọn vẹn một vấn đề kinh doanh phức tạp (thu thập dữ liệu, phân tích, đề xuất phương án...). Đừng dùng Sky-Rain-Umbrella thay cho một quy trình giải quyết vấn đề đầy đủ, và đừng bắt người dùng chạy cả quy trình 7 bước chỉ để trình bày một lập luận ngắn.
- **Pre-mortem vs Six Thinking Hats (Mũ Đen)**: Mũ Đen trong Six Thinking Hats là **một góc nhìn trong số 6 góc** được rà soát nhanh trong cùng một buổi họp đa chiều — phù hợp khi cần rà soát toàn diện một quyết định đã tương đối rõ ràng. Pre-mortem là một **kỹ thuật đào sâu chuyên biệt về rủi ro**, dùng kỹ xảo tâm lý (giả định đã thất bại rồi mới hỏi lý do) để lôi ra cả những rủi ro nhạy cảm/khó nói (nhóm "Con voi trong phòng") mà một câu hỏi Mũ Đen thông thường khó khai thác được. Dùng Pre-mortem khi quyết định đủ lớn/rủi ro cao để xứng đáng một buổi rà soát riêng, không chỉ 1 góc nhìn trong Six Thinking Hats.
- **Pre-mortem vs Gap Analysis**: Gap Analysis so sánh **hiện trạng với mục tiêu mong muốn** để tìm khoảng cách cần thu hẹp — nhìn về phía trước một cách tích cực. Pre-mortem mô phỏng **một kịch bản thất bại cụ thể trong tương lai** để truy ngược nguyên nhân — mục đích là phòng ngừa rủi ro, không phải lập kế hoạch đạt mục tiêu. Có thể dùng nối tiếp: Gap Analysis để lập kế hoạch, Pre-mortem để rà soát lại kế hoạch đó trước khi triển khai.

## Nguyên tắc chung

- **Không tự bịa dữ kiện/số liệu** khi framework đó cần dữ liệu thật (5 Whys, Gap Analysis, Sky-Rain-Umbrella, Pre-mortem) — nếu thiếu, ghi rõ đây là giả thuyết/ước lượng cần xác minh, không mặc định là đúng.
- **Luôn gắn framework vào case cụ thể** người dùng đưa ra, không trả lời lý thuyết chung.
- **Nêu rõ đang dùng framework nào và vì sao** ngay đầu câu trả lời (1 câu ngắn), để người dùng học được cách tự chọn framework cho lần sau.
- Nếu người dùng chỉ hỏi "nên dùng framework nào" mà chưa cần áp dụng ngay, có thể dừng lại sau khi chọn framework + giải thích lý do, chưa cần điền toàn bộ output.
- Khi 2 framework hợp lý để dùng nối tiếp (ví dụ 5W2H → 5 Whys, Gap Analysis → SMART/OKR), luôn gợi ý bước tiếp theo thay vì dừng lại nửa chừng.
- **Không giả định người dùng đã biết ý nghĩa của các ký hiệu/chữ viết tắt trong framework** — nhiều người dùng plugin này lần đầu, không có nền tảng quản lý. Khi output dùng ký hiệu viết tắt (ví dụ tên các trục/tầng/bước chỉ viết gọn 1-2 chữ), luôn giải thích ngắn gọn ý nghĩa ngay trong output, đừng chỉ giải thích khi được hỏi lại.

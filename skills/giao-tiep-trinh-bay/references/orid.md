# ORID (Focused Conversation Method)

## Định nghĩa
Kỹ thuật dẫn dắt một cuộc thảo luận/họp rút kinh nghiệm (retrospective, debrief sau dự án/sự kiện/buổi họp lớn) qua 4 tầng câu hỏi tuần tự, đi từ khách quan đến hành động:
- **Objective (Khách quan)** — chuyện gì đã thực sự xảy ra? Chỉ hỏi **sự kiện/dữ kiện quan sát được**, chưa đánh giá đúng/sai, chưa hỏi cảm nhận.
- **Reflective (Phản ánh)** — mọi người cảm thấy thế nào khi việc đó xảy ra? Khoảnh khắc nào vui/căng thẳng/bất ngờ nhất?
- **Interpretive (Diễn giải)** — điều đó có ý nghĩa gì? Bài học rút ra là gì? Vì sao mọi việc diễn ra như vậy?
- **Decisional (Quyết định)** — từ bài học đó, lần sau sẽ làm gì khác đi? Quyết định/hành động cụ thể tiếp theo là gì?

Giá trị chính của ORID là **thứ tự bắt buộc phải đi theo tầng**, không nhảy cóc: nếu mở đầu cuộc họp rút kinh nghiệm bằng câu hỏi "ai làm sai" hoặc "chúng ta nên làm gì tiếp theo" ngay lập tức (nhảy thẳng vào Decisional hoặc Interpretive), cuộc họp rất dễ biến thành tranh cãi/đổ lỗi vì mỗi người đang dựa trên một phiên bản sự thật khác nhau. Bắt đầu từ Objective giúp cả nhóm **thống nhất về sự kiện khách quan trước**, rồi mới cùng đi tiếp lên các tầng cảm xúc → ý nghĩa → quyết định.

## Input cần thu thập
1. Dự án/sự kiện/buổi việc cần rút kinh nghiệm (tên, thời gian, quy mô).
2. Người tham gia thảo luận (chỉ 1 mình người dùng tự phản tư, hay là dẫn dắt cả nhóm họp).
3. Nếu là dẫn dắt họp nhóm: output nên ở dạng **bộ câu hỏi/agenda** để người dùng tự hỏi nhóm, không phải Claude tự trả lời thay nhóm.
4. Nếu người dùng đã kể sẵn một số sự kiện/cảm xúc/bài học lẫn lộn, Claude cần **phân loại lại** đúng vào 4 tầng, không giữ nguyên thứ tự kể ban đầu.

## Output — luôn theo đúng cấu trúc
```
## Objective — Sự kiện khách quan
Câu hỏi gợi mở:
- [Câu hỏi 1 — chỉ hỏi dữ kiện, vd: "chuyện gì đã xảy ra theo trình tự thời gian?"]
- [Câu hỏi 2]
Ghi nhận (nếu đã có thông tin): [liệt kê sự kiện, mốc thời gian, số liệu — không kèm đánh giá]

## Reflective — Cảm xúc, phản ứng
Câu hỏi gợi mở:
- [Câu hỏi 1 — vd: "khoảnh khắc nào khiến bạn/nhóm thấy hào hứng nhất? căng thẳng nhất?"]
- [Câu hỏi 2]
Ghi nhận (nếu đã có): [...]

## Interpretive — Ý nghĩa, bài học
Câu hỏi gợi mở:
- [Câu hỏi 1 — vd: "vì sao mọi việc diễn ra như vậy? điều gì quan trọng nhất rút ra được?"]
- [Câu hỏi 2]
Ghi nhận (nếu đã có): [...]

## Decisional — Quyết định, hành động tiếp theo
Câu hỏi gợi mở:
- [Câu hỏi 1 — vd: "lần sau chúng ta sẽ làm khác đi điều gì?"]
Kết luận: [1-2 hành động/quyết định cụ thể, ai làm, khi nào]
```

## Ví dụ (rút gọn)
**Input**: "Team tôi vừa launch một tính năng mới nhưng trễ deadline 2 tuần, muốn tổ chức họp retro mà sợ mọi người đổ lỗi qua lại."

**Output**:
- Objective: "Theo trình tự, dự án bắt đầu khi nào, mốc nào bị trễ đầu tiên, ai tham gia giai đoạn nào?" — ghi nhận thuần sự kiện, chưa đánh giá tốt/xấu.
- Reflective: "Giai đoạn nào cả team cảm thấy áp lực nhất? Có khoảnh khắc nào khiến mọi người mất tinh thần hoặc ngược lại rất hào hứng?"
- Interpretive: "Vì sao mốc đó bị trễ — do ước lượng sai, do phụ thuộc team khác, hay do thay đổi yêu cầu giữa chừng? Bài học lớn nhất là gì?"
- Decisional: "Lần dự án tới, chúng ta sẽ làm khác đi điều gì trong khâu ước lượng thời gian?" → Kết luận: thêm bước review estimate với tech lead trước khi commit deadline, áp dụng từ sprint tới.

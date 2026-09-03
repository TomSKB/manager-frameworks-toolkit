# Ma trận RACI

## Định nghĩa
Công cụ phân định vai trò của từng người liên quan trong 1 công việc/dự án có nhiều đầu việc và nhiều người tham gia, theo 4 loại vai trò:

- **R — Responsible (Thực hiện)**: người trực tiếp làm việc đó. Có thể có nhiều người R cho cùng 1 đầu việc.
- **A — Accountable (Chịu trách nhiệm cuối)**: người chịu trách nhiệm cuối cùng về kết quả, có quyền phê duyệt. **Chỉ nên có đúng 1 người A cho mỗi đầu việc** — đây là quy tắc quan trọng nhất của RACI, vi phạm quy tắc này (2 người A trở lên) chính là nguyên nhân phổ biến nhất gây chồng chéo trách nhiệm/đùn đẩy. A và R có thể là cùng 1 người nếu việc đó không cần tách vai trò.
- **C — Consulted (Được hỏi ý kiến)**: người có chuyên môn/liên quan cần được hỏi ý kiến **trước khi** quyết định — tương tác 2 chiều (hỏi và nhận phản hồi trước khi chốt).
- **I — Informed (Được thông báo)**: người cần biết kết quả/tiến độ nhưng không cần hỏi ý kiến trước — tương tác 1 chiều (thông báo sau khi đã quyết/đã làm xong).

## Input cần thu thập
1. Tên dự án/công việc tổng thể, và danh sách các đầu việc/hoạt động chính bên trong nó (chia nhỏ đủ để phân vai — không phân RACI cho 1 khối việc quá lớn, cũng không vụn tới mức từng thao tác nhỏ).
2. Danh sách người/vai trò liên quan (tên hoặc chức danh).
3. Bối cảnh vấn đề: đang chồng chéo/xung đột ở đâu (ví dụ "2 người cùng tưởng mình là người quyết cuối", "không ai dám ký duyệt", "một số người bị bỏ ngoài lề không biết chuyện").

Nếu người dùng chưa liệt kê đủ đầu việc hoặc đủ người liên quan, hỏi lại — RACI không thể lập chính xác nếu thiếu 1 trong 2 trục (việc x người) này.

## Output — luôn theo đúng cấu trúc

**Bắt buộc mở đầu bằng chú thích ký hiệu** — bảng RACI chỉ gồm 4 chữ cái, nếu không giải thích ngay thì người đọc lần đầu (đặc biệt người không có nền tảng quản lý dự án) sẽ không hiểu được chính output dành cho họ. Không giả định người dùng đã biết RACI là gì, kể cả khi họ là người yêu cầu dùng framework này.

```
## Chú thích ký hiệu
- **R = Responsible (Người thực hiện)** — trực tiếp làm việc đó.
- **A = Accountable (Người chịu trách nhiệm cuối)** — người duy nhất phê duyệt/chịu trách nhiệm về kết quả (chỉ nên có 1 người A cho mỗi đầu việc).
- **C = Consulted (Người được hỏi ý kiến)** — cần hỏi ý kiến trước khi quyết, có phản hồi 2 chiều.
- **I = Informed (Người được thông báo)** — chỉ cần biết kết quả sau khi đã quyết/đã xong, không cần hỏi trước.

## Ma trận RACI — [Tên dự án/công việc]

| Đầu việc | [Người/vai trò 1] | [Người/vai trò 2] | [Người/vai trò 3] | ... |
|---|---|---|---|---|
| [Đầu việc 1] | R | A | C | ... |
| [Đầu việc 2] | C | R | I | ... |
| ... | | | | |

## Kiểm tra lỗi thường gặp
- Đầu việc nào có nhiều hơn 1 người A? → [liệt kê, đây là điểm gây chồng chéo cần xử lý trước tiên]
- Đầu việc nào không có ai là A? → [liệt kê — nghĩa là chưa ai thực sự chịu trách nhiệm cuối]
- Đầu việc nào không có ai là R? → [liệt kê — nghĩa là chưa ai thực sự làm]
- Người nào bị quá tải vai trò A/R trên nhiều đầu việc cùng lúc? → [nếu có, cảnh báo nghẽn cổ chai]

## Đề xuất điều chỉnh
[Chốt lại cụ thể: đầu việc X nên để [tên] làm A duy nhất, vì lý do gì; đầu việc Y cần bổ sung ai vào C vì họ có chuyên môn/quyền lợi liên quan mà đang bị bỏ sót; v.v.]
```

## Ví dụ (rút gọn)
**Input**: "Dự án ra mắt sản phẩm mới, có Trưởng phòng Marketing, Trưởng phòng Sản phẩm, đội Kỹ thuật và CEO. Đang bị tình trạng cả Marketing và Sản phẩm đều nghĩ mình là người quyết cuối về thông điệp truyền thông, còn đội Kỹ thuật không biết gì về ngày ra mắt cho tới sát ngày."

| Đầu việc | Trưởng Marketing | Trưởng Sản phẩm | Đội Kỹ thuật | CEO |
|---|---|---|---|---|
| Xây thông điệp truyền thông | A, R | C | I | I |
| Hoàn thiện tính năng sản phẩm | I | A | R | I |
| Chốt ngày ra mắt | C | C | C | A |

**Lỗi phát hiện**: đầu việc "Xây thông điệp truyền thông" trước đó có cả 2 Trưởng phòng cùng nhận mình là A — đây chính là gốc rễ xung đột. **Đề xuất**: chốt Trưởng Marketing là A duy nhất cho thông điệp truyền thông (vì đây thuộc chuyên môn marketing), Trưởng Sản phẩm chuyển sang vai C (được hỏi ý kiến vì hiểu rõ tính năng); đồng thời đưa đội Kỹ thuật vào diện C (không phải I) ở bước "Chốt ngày ra mắt" vì ngày ra mắt ảnh hưởng trực tiếp tiến độ kỹ thuật của họ.

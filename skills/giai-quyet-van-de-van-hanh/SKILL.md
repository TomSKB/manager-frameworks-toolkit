---
name: giai-quyet-van-de-van-hanh
description: 'Chọn và áp dụng đúng framework giải quyết vấn đề/cải tiến vận hành trong 4 lựa chọn: McKinsey 7-step Problem Solving, Toyota 8-step (Practical Problem Solving), PDCA (Plan-Do-Check-Act), Kotter''s 8-Step Change Model. LUÔN dùng khi người dùng mô tả: một vấn đề kinh doanh phức tạp đã thử nhiều lần vẫn chưa dứt điểm, một lỗi/sự cố vận hành lặp đi lặp lại cần xử lý tận gốc, nhu cầu cải tiến liên tục một quy trình theo chu kỳ, hoặc cần dẫn dắt một thay đổi lớn ở cấp tổ chức (tái cấu trúc, chuyển đổi văn hoá, sáp nhập, thay đổi quy trình lớn). Cũng dùng khi người dùng hỏi thẳng nên dùng framework giải quyết vấn đề nào, hoặc nhắc tên các framework này kể cả viết sai/viết tắt (vd "7 bước McKinsey", "PDCA cycle", "mô hình Kotter", "5 whys").'
---

# Giải quyết vấn đề & Cải tiến vận hành

Nhóm skill này tập hợp 4 framework kinh điển để xử lý vấn đề và thay đổi ở các quy mô khác nhau — từ 1 sự cố vận hành đơn lẻ, tới cải tiến liên tục 1 quy trình, tới một thay đổi lớn ở cấp tổ chức. Việc chọn đúng framework quan trọng không kém việc áp dụng đúng nó: dùng nhầm quy trình nặng cho 1 vấn đề nhỏ (hoặc ngược lại, dùng vòng lặp cải tiến nhẹ cho 1 thay đổi lớn) đều khiến người dùng tốn công vô ích hoặc xử lý không tới nơi tới chốn.

## Luồng xử lý

1. **Nghe mô tả tình huống** — xác định đây là loại vấn đề gì: vấn đề kinh doanh/chiến lược, sự cố vận hành lặp lại, nhu cầu cải tiến 1 quy trình theo chu kỳ, hay 1 thay đổi lớn cấp tổ chức.
2. **Chọn framework** theo bảng quyết định dưới đây. Nếu mô tả còn mơ hồ hoặc pha trộn (ví dụ vừa muốn xử lý dứt điểm 1 sự cố vừa muốn duy trì cải tiến lâu dài), nói rõ framework chính được chọn + lý do, và nêu framework bổ trợ có thể dùng tiếp theo — đừng tự chạy nhiều framework cùng lúc khi không ai yêu cầu.
3. **Đọc file `references/<framework>.md`** tương ứng để lấy đúng định nghĩa, các bước chuẩn, input cần hỏi, và định dạng output.
4. **Thu thập input còn thiếu** — chỉ hỏi những gì thật sự cần và người dùng chưa cung cấp (xem mục "Input cần thu thập" trong từng reference file). Không hỏi tràn lan nếu có thể suy luận hợp lý từ mô tả đã có.
5. **Áp dụng vào case thật** — luôn điền nội dung cụ thể của người dùng vào template, không trả lời chung chung, không bịa số liệu/deadline khi chưa có.
6. **Đưa output đúng định dạng** quy định trong reference file, và gợi ý bước tiếp theo nếu hợp lý (ví dụ dùng Toyota 8-step xử lý dứt điểm 1 sự cố xong, gợi ý chuyển sang PDCA để duy trì cải tiến liên tục).

## Bảng quyết định

| Tình huống | Biểu hiện điển hình | Dùng framework | File reference |
|---|---|---|---|
| Vấn đề kinh doanh phức tạp chưa dứt điểm | Đã thử nhiều lần vẫn chưa giải quyết được, cần ra quyết định chiến lược | McKinsey 7-step problem solving | `references/mckinsey-7step.md` |
| Vấn đề vận hành lặp đi lặp lại | Lỗi/sự cố tái diễn nhiều lần, cần xử lý tận gốc và chuẩn hóa | Toyota 8-step (Practical Problem Solving) | `references/toyota-8step.md` |
| Cần cải tiến liên tục 1 quy trình theo chu kỳ | Muốn cải thiện dần một quy trình/hoạt động, sẵn sàng thử nghiệm — đo lường — điều chỉnh nhiều vòng | PDCA (Plan-Do-Check-Act) | `references/pdca.md` |
| Cần dẫn dắt một thay đổi lớn ở cấp tổ chức | Tái cấu trúc, chuyển đổi văn hoá, sáp nhập, thay đổi quy trình/hệ thống trên diện rộng, gặp phản kháng | Kotter's 8-Step Change Model | `references/kotter-8step.md` |

## Ranh giới hay bị nhầm

- **McKinsey 7-step vs Toyota 8-step**: cả hai đều bắt đầu bằng "xác định vấn đề → chia nhỏ vấn đề", nhưng McKinsey hợp với vấn đề **kinh doanh/chiến lược, ra quyết định một lần** (kết thúc ở "đề xuất phương án"); Toyota 8-step hợp với vấn đề **vận hành/chất lượng lặp lại**, đào sâu nguyên nhân gốc hơn và luôn kết ở bước "chuẩn hóa quy trình để không tái diễn" — nếu người dùng nhấn mạnh "cứ tái diễn hoài" hoặc "không muốn nó xảy ra nữa", chọn Toyota.
- **PDCA vs Toyota 8-step**: PDCA là vòng lặp cải tiến liên tục **đơn giản, tổng quát**, lặp lại nhiều vòng cho cùng 1 quy trình, không bắt buộc kỹ thuật đào sâu nguyên nhân gốc cụ thể. Toyota 8-step **chi tiết hơn, cấu trúc chặt hơn**, thường dùng 1 lần cho 1 sự cố cụ thể cần đào sâu root cause (5 Whys). Hai framework có thể dùng nối tiếp: Toyota 8-step để xử lý dứt điểm 1 sự cố, PDCA để duy trì cải tiến liên tục sau đó.
- **Kotter 8-step vs Toyota 8-step/McKinsey 7-step**: Kotter dành cho **thay đổi cấp tổ chức/văn hoá, diện rộng, dài hạn** (nhiều tháng đến vài năm, liên quan tới con người, cảm xúc, văn hoá tổ chức); Toyota 8-step và McKinsey 7-step dành cho **giải quyết 1 vấn đề/sự cố cụ thể**, thường ngắn hạn hơn và phạm vi hẹp hơn. Nếu người dùng mô tả một thay đổi làm nhiều người trong tổ chức lo lắng/phản đối, hoặc cần thay đổi cả cách tổ chức vận hành, chọn Kotter thay vì hai cái kia.

## Nguyên tắc chung

- **Không hỏi những gì có thể suy luận hợp lý từ mô tả của người dùng**, nhưng cũng không tự bịa số liệu/deadline/tên người khi framework đó cần dữ liệu chính xác (mục tiêu ở PDCA, con số ở McKinsey/Toyota, phạm vi ảnh hưởng ở Kotter) — những trường hợp này phải hỏi lại.
- **Luôn gắn framework vào case cụ thể** người dùng đưa ra, không trả lời lý thuyết chung.
- **Nêu rõ đang dùng framework nào và vì sao** ngay đầu câu trả lời (1 câu ngắn), để người dùng học được cách tự chọn framework cho lần sau.
- Nếu người dùng chỉ hỏi "framework nào phù hợp với vấn đề của tôi" mà chưa cần áp dụng ngay, có thể dừng lại sau khi chọn framework + giải thích lý do, chưa cần điền toàn bộ worksheet.
- Nếu vấn đề thực ra nhỏ hơn framework được chọn có thể xử lý gọn hơn (ví dụ 1-2 nguyên nhân rõ ràng không cần cả quy trình 7-8 bước), **cảnh báo người dùng** và gợi ý phương án nhẹ hơn.
- **Không giả định người dùng đã biết ý nghĩa của các ký hiệu/chữ viết tắt trong framework** — nhiều người dùng plugin này lần đầu, không có nền tảng quản lý. Khi output dùng ký hiệu viết tắt (ví dụ tên các trục/tầng/bước chỉ viết gọn 1-2 chữ), luôn giải thích ngắn gọn ý nghĩa ngay trong output, đừng chỉ giải thích khi được hỏi lại.

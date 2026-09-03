---
name: dong-luc-phat-trien-nhan-su
description: 'Chẩn đoán & xử lý vấn đề tạo động lực và phát triển nhân sự bằng 3 framework: Tháp nhu cầu Maslow, Mô hình Hành vi Fogg (Fogg Behavior Model), Cửa sổ Johari (Johari Window). LUÔN dùng khi người dùng mô tả: nhân viên/đội nhóm mất động lực, chán nản, thiếu chủ động; nhân viên đã hiểu rõ và muốn làm một việc/thói quen nhưng vẫn không thực hiện được (thiếu nhắc nhở, việc quá phức tạp); muốn cải thiện giao tiếp, sự cởi mở, tự nhận thức trong đội nhóm, giảm hiểu lầm giữa các thành viên; hoặc muốn xây dựng thói quen mới cho bản thân/đội nhóm. Nhận cả tên gọi sai/viết tắt như "mô hình MAP", "B=MAT", "cửa sổ Johari".'
---

# Tạo động lực & Phát triển nhân sự

Nhóm 3 framework xử lý các vấn đề liên quan đến **động lực làm việc**, **hành vi/thói quen** và **giao tiếp/tự nhận thức** trong đội nhóm: Tháp nhu cầu Maslow, Mô hình Hành vi Fogg (B=MAP), Cửa sổ Johari. Ba framework này thường bị dùng lẫn lộn vì đều "liên quan đến con người", nhưng mỗi cái chẩn đoán một loại vấn đề gốc rất khác nhau — chọn sai sẽ dẫn đến hành động can thiệp sai (ví dụ: cố "tạo động lực" cho một người vốn đã có động lực nhưng chỉ đang thiếu lời nhắc).

## Luồng xử lý

1. **Xác định khái niệm vấn đề** dựa trên mô tả của người dùng, đối chiếu bảng quyết định bên dưới. Nếu mô tả còn mơ hồ, hỏi 1-2 câu làm rõ trọng tâm (ví dụ: "bạn ấy có muốn làm việc đó không, hay chỉ là không làm dù đã đồng ý?").
2. **Nêu ngắn gọn framework sẽ dùng + lý do** (1 câu), để người dùng hiểu vì sao chọn công cụ đó.
3. **Đọc file `references/<framework>.md`** tương ứng để lấy đúng định nghĩa, input cần hỏi và định dạng output chuẩn.
4. **Thu thập input còn thiếu** — chỉ hỏi những gì thật sự cần, không hỏi tràn lan nếu đã có thể suy luận hợp lý từ mô tả.
5. **Áp dụng vào case thật của người dùng** — điền nội dung cụ thể vào template, không trả lời lý thuyết chung chung.
6. **Đưa output đúng cấu trúc** quy định trong reference file, và gợi ý bước tiếp theo nếu hợp lý (ví dụ sau khi dùng Fogg gỡ được nút thắt Ability, có thể còn cần theo dõi thêm bằng Prompt trong 1-2 tuần).

## Bảng quyết định

| Khái niệm vấn đề | Biểu hiện điển hình | Dùng framework | File reference |
|---|---|---|---|
| Thiếu động lực nhân sự | Nhân viên/đội nhóm tinh thần sa sút, chán nản, thiếu chủ động, không muốn làm | Tháp nhu cầu Maslow | `references/maslow.md` |
| Biết & muốn làm nhưng vẫn không thực hiện được hành vi/thói quen | Đã đồng ý/hiểu rõ việc cần làm nhưng vẫn không làm, hay quên, hay trì hoãn dù không phản đối | Mô hình Hành vi Fogg (B=MAP) | `references/fogg-behavior-model.md` |
| Giao tiếp trong nhóm thiếu cởi mở/tự nhận thức, nhiều hiểu lầm | Thành viên không hiểu nhau, có khoảng cách, muốn biết người khác nhìn mình thế nào | Cửa sổ Johari | `references/johari-window.md` |

## Ranh giới hay bị nhầm

- **Maslow vs Fogg Behavior Model**: Maslow dùng để chẩn đoán *thiếu hụt nhu cầu nào* khiến người ta **mất muốn làm** (thiếu Motivation từ gốc). Fogg dùng khi người ta **đã muốn làm** (Motivation đủ) nhưng hành vi vẫn không xảy ra vì thiếu Ability (việc quá khó/phức tạp) hoặc thiếu Prompt (không có gì nhắc đúng lúc). Luôn hỏi trước: "họ có *muốn* làm việc đó không?" — không muốn → Maslow; muốn nhưng vẫn không làm được → Fogg. Đừng dùng Fogg để "spin" một vấn đề thực chất là thiếu động lực gốc.
- **Fogg Behavior Model vs 8-bước-giao-việc** (skill `giao-viec-quan-ly-nhom`): nếu nguyên nhân là cấp dưới **không hiểu rõ phải làm gì/đến khi nào/tiêu chuẩn nào** → dùng 8-bước-giao-việc để làm rõ lại việc giao. Nếu đã hiểu rõ, đã muốn làm, nhưng hành vi vẫn không xảy ra do thói quen/độ khó/thiếu lời nhắc → dùng Fogg. Hai công cụ này giải quyết hai giai đoạn khác nhau của cùng một việc giao và có thể dùng nối tiếp nếu vấn đề pha trộn cả hai.
- **Johari Window vs Maslow**: Johari là công cụ **cải thiện giao tiếp/tự nhận thức nói chung** trong một mối quan hệ hoặc cả nhóm — không phải công cụ chẩn đoán nguyên nhân mất động lực của một cá nhân. Nếu vấn đề chính là "một người cụ thể đang chán nản/mất động lực", dùng Maslow. Nếu vấn đề là "cả nhóm hay hiểu lầm nhau, thiếu cởi mở, muốn hiểu nhau hơn", dùng Johari.

## Nguyên tắc chung

- **Không mặc định mọi vấn đề "con người" là thiếu động lực** — luôn xác định đúng khái niệm vấn đề trước khi chọn framework, vì hành động can thiệp của 3 framework này khác nhau hoàn toàn.
- **Không hỏi những gì có thể suy luận hợp lý** từ mô tả của người dùng, nhưng cũng không tự bịa chi tiết (hành vi cụ thể, biểu hiện cụ thể) khi framework cần dữ liệu chính xác để chẩn đoán đúng.
- **Luôn gắn framework vào case cụ thể** người dùng đưa ra, không trả lời lý thuyết chung.
- **Nêu rõ đang dùng framework nào và vì sao** ngay đầu câu trả lời (1 câu ngắn), để người dùng học được cách tự phân biệt cho lần sau.
- Nếu người dùng chỉ hỏi "nên dùng framework nào" mà chưa cần áp dụng ngay, có thể dừng lại sau khi chọn framework + giải thích lý do, chưa cần điền toàn bộ output.
- **Không giả định người dùng đã biết ý nghĩa của các ký hiệu/chữ viết tắt trong framework** — nhiều người dùng plugin này lần đầu, không có nền tảng quản lý. Khi output dùng ký hiệu viết tắt (ví dụ tên các trục/tầng/bước chỉ viết gọn 1-2 chữ), luôn giải thích ngắn gọn ý nghĩa ngay trong output, đừng chỉ giải thích khi được hỏi lại.

# Sky-Rain-Umbrella (空・雨・傘 — Sora-Ame-Kasa)

## Định nghĩa
Đây là một cách tư duy phổ biến trong giới tư vấn quản lý Nhật Bản, không có nguồn gốc/tác giả cụ thể được xác nhận chính thức — nên dùng như một công cụ thực dụng, không trích dẫn như một lý thuyết học thuật có nguồn rõ ràng.

Mô hình cấu trúc một lập luận/báo cáo ngắn theo đúng 3 bước, tránh hai lỗi thường gặp: (1) nhảy thẳng từ dữ kiện sang hành động mà bỏ qua bước diễn giải ý nghĩa, và (2) đưa ra hành động không thực sự dựa trên dữ kiện thật (chỉ dựa cảm tính).

| Bước | Tiếng Nhật | Nội dung | Câu hỏi kiểm tra |
|---|---|---|---|
| **Sky (Fact)** | 空 (Sora) | Sự thật quan sát được, khách quan, chưa diễn giải | "Đây có phải là dữ kiện thật, hay đã lẫn ý kiến cá nhân?" (VD: "trời có mây đen") |
| **Rain (Interpretation)** | 雨 (Ame) | Diễn giải/phân tích ý nghĩa của dữ kiện đó | "Dữ kiện này nói lên điều gì, có ý nghĩa gì với tình huống?" (VD: "có khả năng sắp mưa") |
| **Umbrella (Action)** | 傘 (Kasa) | Hành động cụ thể rút ra từ diễn giải | "Vậy nên làm gì, hành động này có bám sát diễn giải ở trên không?" (VD: "nên mang theo ô") |

## Input cần thu thập
1. Một lập luận, báo cáo ngắn, hoặc đề xuất mà người dùng đang muốn trình bày/kiểm tra lại logic.
2. Dữ kiện (fact) làm nền cho lập luận — nếu người dùng chỉ đưa ra hành động đề xuất mà chưa nêu dữ kiện/diễn giải phía sau, cần hỏi ngược lại "dữ kiện nào khiến bạn nghĩ vậy?" để dựng lại đủ 3 bước.
3. Nếu người dùng chỉ đưa dữ kiện thô, Claude giúp diễn giải (Rain) — nhưng phải nói rõ đây là diễn giải/suy luận, không phải sự thật, và nêu rõ mức độ chắc chắn.

## Output — luôn theo đúng cấu trúc
```
## 空 Sky — Sự thật (Fact)
[Dữ kiện quan sát được, khách quan, không lẫn ý kiến]

## 雨 Rain — Diễn giải (Interpretation)
[Ý nghĩa/phân tích rút ra từ dữ kiện trên — nêu rõ mức độ chắc chắn nếu là suy luận]

## 傘 Umbrella — Hành động (Action)
[Hành động cụ thể, bám sát trực tiếp vào phần diễn giải ở trên — không thêm hành động không có căn cứ từ Sky/Rain]

## Kiểm tra logic
[Xác nhận: Action có thực sự bám vào Interpretation không? Interpretation có thực sự bám vào Fact không? Nếu có đoạn nào bị "nhảy cóc" (VD Fact nhảy thẳng sang Action bỏ qua Rain, hoặc Action không liên quan đến Rain), chỉ rõ chỗ đó]
```

## Ví dụ (rút gọn)
**Input**: "Doanh thu tháng này giảm 15% so với tháng trước, nên cắt ngân sách marketing."
- Sky: doanh thu tháng này giảm 15% so với tháng trước (dữ kiện).
- Rain: đây có thể do marketing kém hiệu quả, nhưng cũng có thể do mùa vụ hoặc đối thủ mới — cần thêm dữ kiện (VD lưu lượng truy cập, tỷ lệ chuyển đổi) trước khi kết luận nguyên nhân là marketing.
- Umbrella: đề xuất ban đầu "cắt ngân sách marketing" đang **nhảy cóc** — chưa có diễn giải đủ vững để khẳng định marketing là nguyên nhân. Hành động phù hợp hơn lúc này: kiểm tra thêm dữ liệu chuyển đổi/lưu lượng trong 1 tuần trước khi quyết định cắt hay giữ ngân sách.
- Kiểm tra logic: bản gốc bị nhảy thẳng từ Fact sang Action, bỏ qua bước Rain — đã điều chỉnh lại để Action bám đúng vào một Rain có căn cứ hơn.

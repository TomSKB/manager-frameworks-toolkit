# Các Cấp độ Logic (NLP Logical Levels) — Robert Dilts

## Định nghĩa
Mô hình 6 tầng để chẩn đoán/thay đổi hành vi cá nhân hoặc tổ chức, đi từ cụ thể đến trừu tượng (dựa trên ý tưởng của Gregory Bateson, phổ biến trong NLP — Neuro-Linguistic Programming):

| Tầng | Câu hỏi trung tâm | Nội dung |
|---|---|---|
| Môi trường (Environment) | Ở đâu? Với ai? Điều kiện gì? | Bối cảnh vật lý/xã hội xung quanh |
| Hành vi (Behavior) | Làm gì? | Hành động cụ thể quan sát được |
| Năng lực (Capability) | Làm như thế nào? | Kỹ năng, chiến lược, cách thức thực hiện |
| Niềm tin & Giá trị (Beliefs & Values) | Vì sao làm? Điều gì quan trọng? | Lý do thúc đẩy, điều được coi trọng |
| Bản sắc (Identity) | Tôi/chúng ta là ai? | Vai trò, hình ảnh bản thân/tổ chức |
| Sứ mệnh/Tinh thần (Purpose) | Vì mục đích/ý nghĩa lớn hơn nào? | Kết nối với điều lớn hơn bản thân |

Nguyên tắc quan trọng nhất: **vấn đề nằm ở tầng nào thì cần chẩn đoán đúng tầng đó trước khi can thiệp**.
- Vấn đề ở tầng thấp (Môi trường/Hành vi — vd thiếu công cụ, quy trình chưa rõ) thường sửa được ngay bằng cách can thiệp ở **chính tầng đó hoặc tầng ngay trên** (thay đổi môi trường, hướng dẫn lại hành vi, đào tạo thêm năng lực).
- Nhưng nếu vấn đề *thực ra* nằm ở tầng cao hơn — ví dụ mâu thuẫn về **Niềm tin & Giá trị** (một người tin "làm việc nhanh quan trọng hơn làm kỹ", người khác tin ngược lại) hoặc về **Bản sắc** (một người tự nhận mình "không phải người giỏi giao tiếp" nên né tránh trình bày) — thì chỉ can thiệp ở tầng Hành vi/Môi trường (nhắc nhở, đổi quy trình, đổi chỗ ngồi...) sẽ **không hiệu quả lâu dài**, vì gốc rễ nằm ở tầng cao hơn chưa được động đến.

Vì vậy trước khi đề xuất giải pháp, luôn hỏi ngược lên từng tầng: hành vi này phục vụ năng lực gì, năng lực đó phục vụ niềm tin/giá trị gì, niềm tin đó gắn với bản sắc nào — cho đến khi thấy tầng nào là nơi mâu thuẫn/vấn đề thực sự nằm.

**Lưu ý về mức độ kiểm chứng**: mô hình này phổ biến trong các tài liệu về NLP/coaching và **không có cùng mức độ kiểm chứng khoa học thực nghiệm** như các mô hình tâm lý học hàn lâm (bản thân NLP nói chung bị giới học thuật đánh giá là thiếu bằng chứng thực nghiệm vững chắc) — nên dùng mô hình này như một **công cụ tư duy thực dụng** để đặt câu hỏi đúng tầng và tổ chức cuộc trò chuyện, không phải một lý thuyết khoa học đã được chứng minh.

## Input cần thu thập
1. Vấn đề/hành vi cụ thể đang quan sát được (tầng Hành vi là điểm khởi đầu dễ mô tả nhất).
2. Bối cảnh xảy ra (tầng Môi trường).
3. Nếu người dùng chỉ mô tả hành vi bề mặt, Claude cần **chủ động hỏi ngược lên** các tầng cao hơn (năng lực → niềm tin/giá trị → bản sắc → sứ mệnh) thay vì dừng lại ở hành vi, để tìm đúng tầng gốc rễ.
4. Không tự suy diễn niềm tin/bản sắc của người khác nếu chưa có đủ căn cứ — nêu rõ đây là **giả thuyết cần xác nhận lại** với người liên quan, không khẳng định chắc chắn.

## Output — luôn theo đúng cấu trúc
```
## Rà soát theo từng tầng
- Môi trường: [bối cảnh cụ thể]
- Hành vi: [hành vi/vấn đề quan sát được]
- Năng lực: [kỹ năng/chiến lược đang có hoặc đang thiếu]
- Niềm tin & Giá trị: [niềm tin/điều được coi trọng — có thể là giả thuyết cần xác nhận]
- Bản sắc: [vai trò/hình ảnh bản thân liên quan — có thể là giả thuyết]
- Sứ mệnh: [ý nghĩa lớn hơn liên quan, nếu có]

## Chẩn đoán: vấn đề thực sự nằm ở tầng nào?
[Nêu rõ tầng gốc rễ + lý do vì sao không phải các tầng thấp hơn]

## Đề xuất can thiệp
[Can thiệp đúng ở tầng đã chẩn đoán (hoặc tầng liền kề phía trên) — không đề xuất giải pháp ở tầng thấp hơn nếu vấn đề gốc nằm ở tầng cao]
```

## Ví dụ (rút gọn)
**Input**: "Một bạn trong team liên tục né tránh việc thuyết trình trước khách hàng dù đã được nhắc nhở và cử đi học kỹ năng thuyết trình rồi mà vẫn không cải thiện."

**Output**:
- Môi trường: các buổi họp khách hàng, có sự hiện diện của sếp và khách hàng lớn.
- Hành vi: né tránh nhận việc thuyết trình, tìm lý do đẩy cho người khác.
- Năng lực: đã được đào tạo kỹ năng thuyết trình, nhưng không áp dụng — cho thấy vấn đề không nằm ở tầng Năng lực.
- Niềm tin & Giá trị (giả thuyết cần xác nhận): có thể tin rằng "nói trước đám đông rất dễ mắc sai lầm và bị đánh giá".
- Bản sắc (giả thuyết cần xác nhận): có thể tự nhận mình "không phải người giỏi ăn nói" từ trước, nên học kỹ năng mới không đủ để thay đổi hành vi.
- Chẩn đoán: vấn đề nhiều khả năng nằm ở tầng Bản sắc/Niềm tin, không phải thiếu Năng lực — vì đã đào tạo mà vẫn né tránh.
- Đề xuất: thay vì cử đi học thêm khóa thuyết trình khác (can thiệp sai tầng), nên có buổi trò chuyện 1-1 để xác nhận giả thuyết trên, và nếu đúng, bắt đầu bằng việc giao những phần trình bày nhỏ, rủi ro thấp để dần xây lại niềm tin về bản thân trước khi giao việc thuyết trình lớn.

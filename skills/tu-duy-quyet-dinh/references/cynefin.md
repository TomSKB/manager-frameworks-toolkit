# Cynefin Framework — Dave Snowden

## Định nghĩa
Mô hình phân loại **bản chất của vấn đề/ngữ cảnh ra quyết định** thành 5 miền, giúp chọn đúng cách tiếp cận thay vì áp một công thức "best practice" cứng nhắc cho mọi loại vấn đề. Sai lầm phổ biến nhất mà Cynefin muốn ngăn: xử lý một vấn đề phức tạp/hỗn loạn bằng tư duy của vấn đề rõ ràng (lập kế hoạch chi tiết rồi thực thi đúng kế hoạch), dẫn tới thất bại vì thực tế thay đổi nhanh hơn kế hoạch.

| Miền | Đặc điểm quan hệ nhân-quả | Cách tiếp cận đúng |
|---|---|---|
| **Rõ ràng (Obvious/Clear)** | Nhân-quả hiển nhiên, ai cũng thấy giống nhau | Sense → Categorize → Respond. Áp dụng **best practice** đã được kiểm chứng |
| **Phức tạp có thể phân tích (Complicated)** | Nhân-quả tồn tại nhưng cần chuyên môn mới thấy được | Sense → Analyze → Respond. Nhờ **chuyên gia phân tích**, có nhiều **good practice** khả dĩ |
| **Phức tạp hỗn loạn (Complex)** | Nhân-quả chỉ nhìn rõ được sau khi nó đã xảy ra (retrospective), hệ thống có nhiều tác nhân tương tác khó đoán trước | Probe → Sense → Respond. Chạy **thử nghiệm nhỏ, an toàn để thất bại**, quan sát, rồi khuếch đại cái hiệu quả — **emergent practice** |
| **Hỗn loạn (Chaotic)** | Không có quan hệ nhân-quả nào nhận ra được lúc đó, tình huống khẩn cấp | Act → Sense → Respond. **Hành động ngay để ổn định tình hình trước**, phân tích nguyên nhân sau — **novel practice** |
| **Rối (Confused/Disorder)** | Chưa xác định được đang ở miền nào trong 4 miền trên, hoặc các bên liên quan tranh cãi vì mỗi người nhìn theo một miền khác nhau | Tách nhỏ vấn đề ra thành các phần, xếp từng phần vào đúng 1 trong 4 miền trên, xử lý riêng từng phần |

## Input cần thu thập
1. Mô tả vấn đề/tình huống cần ra quyết định.
2. Vấn đề này đã từng xảy ra trước đây chưa, có quy trình/best practice sẵn có để xử lý không?
3. Có chuyên gia/dữ liệu đủ để phân tích ra nguyên nhân-giải pháp không, hay tình huống đang thay đổi/mới đến mức chưa ai biết chắc điều gì sẽ xảy ra?
4. Có đang trong tình huống khẩn cấp cần hành động ngay không (ví dụ khủng hoảng, sự cố lớn)?

## Output — luôn theo đúng cấu trúc
```
## Phân loại miền
Miền: [Rõ ràng / Phức tạp có thể phân tích / Phức tạp hỗn loạn / Hỗn loạn / Rối]
Lý do xếp vào miền này: [Giải thích ngắn dựa trên đặc điểm nhân-quả của vấn đề]

## Cách tiếp cận phù hợp với miền này
[Mô tả cụ thể nên làm gì — best practice / nhờ chuyên gia phân tích / chạy thử nghiệm nhỏ / hành động ổn định trước / tách nhỏ vấn đề]

## Cảnh báo sai lầm cần tránh
[Cách tiếp cận SAI thường bị áp nhầm cho miền này — ví dụ áp kế hoạch chi tiết cứng nhắc cho vấn đề Complex, hoặc phân tích quá lâu cho vấn đề Chaotic]

## Bước tiếp theo cụ thể
[1-3 hành động cụ thể theo đúng cách tiếp cận của miền đã xác định]
```

## Ví dụ (rút gọn)
**Input**: "Chúng tôi ra mắt sản phẩm mới ở một thị trường hoàn toàn chưa từng bán, phản ứng khách hàng rất khó đoán."
- Miền: Phức tạp hỗn loạn (Complex) — thị trường mới, hành vi khách hàng chưa có dữ liệu lịch sử, nhiều yếu tố tương tác (đối thủ, văn hoá tiêu dùng, kênh phân phối) khó mô hình hoá trước.
- Cách tiếp cận: chạy thử nghiệm nhỏ ở 1-2 khu vực trước khi mở rộng toàn thị trường, thu thập phản hồi thực tế rồi điều chỉnh, thay vì lập kế hoạch marketing chi tiết 6 tháng rồi triển khai đồng loạt.
- Cảnh báo: đừng áp playbook ra mắt đã thành công ở thị trường cũ — đó là tư duy "Rõ ràng" bị áp nhầm vào tình huống "Phức tạp hỗn loạn".
- Bước tiếp theo: chọn 1 khu vực thí điểm, đặt ra 2-3 chỉ số quan sát sau 4 tuần, chuẩn bị sẵn phương án điều chỉnh nhanh.

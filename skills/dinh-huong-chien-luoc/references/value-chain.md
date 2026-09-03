# Value Chain (Chuỗi giá trị của Michael Porter)

## Định nghĩa
Khung phân tích chuỗi hoạt động bên trong tổ chức để tìm ra hoạt động nào đang **tạo ra giá trị cho khách hàng** và hoạt động nào đang **tạo ra chi phí** — từ đó xác định lợi thế cạnh tranh (khác biệt hóa hoặc dẫn đầu chi phí) nằm ở đâu trong toàn bộ chuỗi. Chia hoạt động thành 2 nhóm:

- **Hoạt động chính** (primary activities — trực tiếp tạo ra sản phẩm/dịch vụ và đưa đến tay khách hàng):
  - **Inbound Logistics** (Hậu cần đầu vào) — nhận, lưu kho, quản lý nguyên vật liệu/nguồn lực đầu vào.
  - **Operations** (Vận hành/Sản xuất) — chuyển đầu vào thành sản phẩm/dịch vụ hoàn chỉnh.
  - **Outbound Logistics** (Hậu cần đầu ra) — lưu kho, phân phối sản phẩm đến khách hàng.
  - **Marketing & Sales** (Marketing & Bán hàng) — truyền thông giá trị, thuyết phục khách hàng mua.
  - **Service** (Dịch vụ) — hỗ trợ sau bán, chăm sóc khách hàng, bảo hành.
- **Hoạt động hỗ trợ** (support activities — không trực tiếp tạo sản phẩm nhưng làm nền cho hoạt động chính vận hành tốt hơn):
  - **Procurement** (Thu mua) — mua nguyên vật liệu, thiết bị, dịch vụ đầu vào.
  - **Technology Development** (Phát triển công nghệ) — R&D, cải tiến quy trình/sản phẩm, hệ thống IT.
  - **Human Resource Management** (Quản trị nhân sự) — tuyển dụng, đào tạo, giữ chân nhân tài.
  - **Firm Infrastructure** (Cơ sở hạ tầng doanh nghiệp) — quản lý tổng thể, tài chính, pháp lý, hệ thống quản trị chung.

Nguyên lý cốt lõi: **Margin** (biên lợi nhuận) sinh ra từ chênh lệch giữa tổng giá trị chuỗi hoạt động tạo ra và tổng chi phí để vận hành chuỗi đó. Lợi thế cạnh tranh không nằm ở một hoạt động đơn lẻ mà ở cách các hoạt động **liên kết với nhau** — tối ưu một khâu có thể ảnh hưởng khâu khác.

## Input cần thu thập
1. Ngành nghề/mô hình kinh doanh cụ thể (sản xuất, bán lẻ, dịch vụ... — vì các hoạt động chính biểu hiện khác nhau tùy ngành).
2. Mục đích phân tích: đang muốn **cắt giảm chi phí** (dẫn đầu chi phí) hay **tạo khác biệt** để cạnh tranh (khác biệt hóa), hoặc chỉ đơn giản muốn rà soát toàn bộ hoạt động xem đang yếu ở khâu nào.
3. Mô tả hiện trạng vận hành theo từng khâu nếu có (không cần đủ hết, Claude có thể hỏi khơi gợi khâu nào chưa rõ, hoặc suy luận hợp lý từ mô tả chung về ngành).

Nếu người dùng vận hành mô hình dịch vụ thuần túy (không có hàng hóa vật lý), một số hoạt động chính có thể gộp lại hoặc biểu hiện khác (vd: Inbound/Outbound Logistics của dịch vụ tư vấn có thể là "thu thập thông tin khách hàng" và "bàn giao kết quả") — điều chỉnh linh hoạt theo ngữ cảnh, không áp cứng nhắc mô hình sản xuất truyền thống.

## Output — luôn theo đúng cấu trúc
```
## Hoạt động chính
| Hoạt động | Hiện trạng | Đang tạo giá trị hay đang tạo chi phí thừa? |
|---|---|---|
| Inbound Logistics | ... | ... |
| Operations | ... | ... |
| Outbound Logistics | ... | ... |
| Marketing & Sales | ... | ... |
| Service | ... | ... |

## Hoạt động hỗ trợ
| Hoạt động | Hiện trạng | Đang tạo giá trị hay đang tạo chi phí thừa? |
|---|---|---|
| Procurement | ... | ... |
| Technology Development | ... | ... |
| Human Resource Management | ... | ... |
| Firm Infrastructure | ... | ... |

## Điểm tạo lợi thế cạnh tranh rõ nhất
[Chỉ ra 1-2 hoạt động đang là nguồn lợi thế thật sự — khác biệt hóa hoặc chi phí thấp — so với đối thủ]

## Điểm cần tối ưu ngay
[Chỉ ra 1-2 hoạt động đang tốn chi phí/nguồn lực nhưng không tương xứng với giá trị tạo ra, kèm hướng xử lý]
```

## Ví dụ (rút gọn)
**Input**: "Tôi vận hành một xưởng may gia công nhỏ, đang cạnh tranh khó khăn vì giá thành cao hơn các xưởng khác cùng khu vực, muốn tìm ra khâu nào đang tốn chi phí không cần thiết."

- Inbound Logistics: nhập vải theo lô nhỏ từ nhiều nhà cung cấp lẻ, giá cao hơn mua sỉ.
- Operations: dây chuyền may vẫn theo quy trình thủ công từng công đoạn, năng suất/công nhân thấp hơn xưởng dùng chuyền công nghiệp.
- Outbound Logistics: giao hàng lẻ tẻ theo từng đơn nhỏ, chưa gộp chuyến.
- Procurement (hỗ trợ): mua nguyên phụ liệu chưa có hợp đồng dài hạn, phụ thuộc giá thị trường từng thời điểm.
- Điểm tạo lợi thế cạnh tranh rõ nhất: Operations — tay nghề công nhân cao, có thể nhận đơn hàng chi tiết/khó mà xưởng lớn không nhận, đây là hướng khác biệt hóa nên giữ và truyền thông rõ hơn thay vì cạnh tranh giá.
- Điểm cần tối ưu ngay: Inbound Logistics và Procurement — gộp đơn mua vải theo tháng, đàm phán hợp đồng dài hạn với 1-2 nhà cung cấp chính để giảm giá đầu vào, đây là nguồn chênh lệch chi phí lớn nhất so với đối thủ chứ không phải ở khâu sản xuất.

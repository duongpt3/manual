# Giới thiệu đơn hàng
Nhanh.vn giúp bạn dễ dàng theo dõi và thực hiện các đơn hàng. Tất cả các đơn đặt hàng, hàng tồn kho, nhà cung cấp và dữ liệu khách hàng của bạn được đồng bộ hóa và tích hợp đầy đủ trên một hệ thống.
Đơn hàng là nơi quản lý tất cả các đơn hàng online, đơn đặt hàng trước, đơn cần vận chuyển (đơn gửi hãng vận chuyển, cần thu hộ tiền COD).

## So sánh ĐƠN HÀNG và BÁN HÀNG

## Một số khái niệm trong Đơn hàng

### Trạng thái đơn hàng

## Các hoạt động của đơn hàng 
### Tạo đơn hàng 
**Đơn hàng có thể được tạo từ các nguồn sau:**

- Khách gọi điện thoại đến doanh nghiệp để đặt hàng > Nhân viên tự tạo đơn hàng
  - Doanh nghiệp vào tạo đơn hàng trong hệ thống, điền đấy đủ các thông tin khách hàng, báo cho khách về phí vận chuyển (nếu có).
  - Doanh nghiệp import đơn hàng để tạo nhiều đơn hàng cùng lúc lên hệ thống.
  
  ![](link)
  
- Đơn hàng đồng bộ từ phần mềm quản lý fanpage https://vpage.nhanh.vn

![](link)

- Đơn hàng do người mua đặt hàng từ website bán hàng của doanh nghiệp do Nhanh.vn cung cấp

![](link)

- Đơn hàng nhận từ API đồng bộ giữa Nhanh.vn với các sàn TMĐT (Lazada.vn, Shopee.vn, Tiki.vn, Sendo.vn, Vatgia.com, Adayroi.com)

![](link)

### Xử lý đơn hàng
**1. Quy trình đơn hàng**
Sau khi tạo đơn hàng, doanh nghiệp thực hiện các bước **Xác nhận đơn hàng > In hàng và đóng gói > Cho đơn hàng vào biên bản bàn giao > Vận chuyển > Đối soát (nếu có dùng hãng vận chuyển) và thanh toán** để hoàn thành xong đơn hàng thành công.
Doanh nghiệp xem thêm chi tiết Quy trình xử lý đơn hàng 
Lưu ý: Quy trình xử lý đơn hàng hiện tại trên nhanh là:

Doanh nghiệp tạo đơn.
Gửi đơn sang hãng vận chuyển.
Khi hãng vận chuyển thay đổi trạng thái -> Cập nhật lịch trình về Nhanh.
Khi đơn hàng giao Thành công hoặc Chuyển hoàn về, hãng vận chuyển đối soát với Nhanh.
Nhanh sẽ check các thông tin về khối lượng | tiền cần thu | giá cước (xem có phí vượt cân, có đúng với giá cước theo hợp đồng không) => Khớp các giá trị trên sẽ chốt đối soát với hãng vận chuyển, sau đó Nhanh sẽ chuyển lại tiền này cho doanh nghiệp.

Khi sử dụng vận chuyển trên Nhanh thì các bước 2,3,4 trên là do Nhanh làm, còn với doanh nghiệp Tự vận chuyển thì sẽ tự làm các bước đổi trạng thái, đối soát, chốt tiền.

**2. Xử lý đơn trùng** 
Tính năng này dùng để kiếm tra những đơn hàng của cùng một khách hàng. Từ đó doanh nghiệp có thể tiến hành gộp nhiều đơn thành một đơn cho khách hàng 

Để gộp đơn hàng, doanh nghiệp thực hiện như sau:

**Lưu ý:** Chỉ thực hiện gộp đơn hàng đối với những đơn hàng mà hãng vận chuyển chưa lấy hàng.

**3. Xử lý đổi trả đơn hàng**
Trường hợp khách hàng muốn trả hoặc đổi trả đơn hàng đã giao thành công thì doanh nghiệp thực hiện thao tác này.
Xem chi tiết các bước thực hiện [tại đây](link).

**4. Xử lý sửa và đơn hàng**
Đối với những đơn hàng chưa giao thành công doanh nghiệp có thể hủy và sửa thông tin đơn hàng, thay đổi sản phẩm, số lượng,... trong phần [Khiếu nại](link) đơn hàng. 


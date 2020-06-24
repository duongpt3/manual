# Quy trình xử lý đơn hàng

Quy trình xử lý đơn hàng của Nhanh.vn được mô tả theo sơ đồ sau:

![](link)

## 1. Thêm đơn hàng 
- Khách hàng đặt hàng trên website do Nhanh.vn cung cấp, hoặc website được tích hợp API của Nhanh, thì thông tin đơn hàng sẽ được chuyển đến phần mềm quản lý bán hàng Nhanh.vn.
- Khách đặt hàng tại các nguồn khác, nhân viên của cửa hàng sẽ kiểm tra tình trang sản phẩm còn tồn trong kho hay không. Nếu còn hàng, nhân viên sẽ nhập thông tin đơn hàng lên hệ thống. Trong cả 2 trường hợp đặt hàng trên website và từ nguồn khác, nếu hết hàng, nhân viên sẽ thông báo để khách hàng chọn sản phẩm khác. Xem thêm hướng dẫn sử dụng module Thêm đơn hàng [tại đây](link).
- Ngoài ra, doanh nghiệp cũng có thể thêm nhanh nhiều đơn hàng cùng lúc với tính năng [Import đơn hàng](link).
Những đơn hàng khi được tạo trên hệ thống sẽ có trạng thái là "Mới".

## 2. Xác nhận đơn hàng

Sau khi có danh sách đơn hàng, nhân viên sẽ gọi điện cho khách hàng để xác nhận đơn hàng đó. Thao tác như sau:

- Tại danh sách đơn hàng, nhân viên click vào trạng thái đơn hàng "Mới", hệ thống sẽ chuyển đơn hàng sang trạng thái "Đang xác nhận". Do đó trong trường hợp có nhiều nhân viên cùng xác nhận đơn hàng thì cũng không thể xảy ra việc xác nhận trùng đơn hàng.
- Nếu khách hàng đồng ý lấy hàng, nhân viên sẽ chuyển trạng thái đơn hàng đó sang "Đã xác nhận". Có 2 tùy chọn là "Lưu" và "Lưu và in", nhân viên chọn click "Lưu và In" thì đơn hàng đó sẽ tiếp tục chuyển sang trạng thái "Đang đóng gói sản phẩm".
- Nếu khách hàng không đồng ý lấy hàng, nhân viên chuyển trạng thái đơn hàng sang "Khách hủy" và lựa chọn lý do hủy đơn hàng.
- Doanh nghiệp có thể xem thêm hướng dẫn khâu xác nhận đơn hàng tại đây.

## 3. In hàng và đóng gói

- Với những đơn hàng đang ở trạng thái "Đang đóng gói sản phẩm", nhân viên kho sẽ tiến hành nhặt hàng cho những đơn đó, đóng gói và dán phiểu gửi (đã in ở bước 2) vào đơn hàng.
- Với những đơn hàng ở trạng thái "Đã xác nhận", nhân viên cũng có thể click để in phiếu gửi (có thể chọn nhiều đơn hàng để in cùng lúc).
- Doanh nghiệp có thể xem thêm hướng dẫn khâu nhặt hàng và đóng gói [tại đây](link).

## 4. Cho đơn hàng vào biên bản bàn giao
- Doanh nghiệp phân loại các đơn hàng theo hãng vận chuyển, sau đó tạo biên bản bàn giao cho từng hãng. Xem hướng dẫn tạo biên bản bàn giao vận đơn [tại đây](link).

## 5. Vận chuyển
- Sau khi đơn hàng đã được đóng gói và dán phiếu gửi thành công, nhân viên tiến hành gửi những đơn đó sang cho hãng vận chuyển. Doanh nghiệp có thể xem thêm hướng dẫn khâu vận chuyên [tại đây](link).
- Sau khi gửi đơn hàng sang hãng vận chuyển, bưu tá sẽ đến địa chỉ cửa hàng để lấy hàng và chuyển đi. Trong quá trình vận chuyển, doanh nghiệp có thể click vào đơn hàng để xem lịch trình chi tiết của đơn hàng.
- Nếu đơn hàng được chuyển thành công đến tay người nhận, đơn hàng được chuyển sang trạng thái "Thành công". Hệ thống tự động tạo phiếu xuất nhập kho và trừ số tồn của sản phẩm, cập nhật số tồn hiển thị trên web (đối với website do Nhanh cung cấp và website được tích hợp API của Nhanh), ghi nhận doanh thu cho doanh nghiệp. Với đơn hàng sử dụng hình thức giao hàng thu tiền hộ, Nhanh.vn sẽ đối soát và thanh toán lại tiền thu hộ cho doanh nghiệp.
- Nếu đơn hàng không đến được tay người nhận, hãng vận chuyển sẽ chuyển hoàn lại về cho doanh nghiệp.
- Doanh nghiệp cũng có thể xem thêm về quy trình vận hành của hãng vận chuyển [tại đây](link).

Quy trình vận chuyển của Nhanh.vn có 3 tab riêng để quản lý trạng thái đơn hàng, đó là "Vượt cân", "Giao hàng thất bại" và "Xác nhận chuyển hoàn" giúp doanh nghiệp quản lý đơn hàng ngay cả trong quá trình vận chuyển.

### 5.1. Vượt cân

Tab này thống kê những đơn hàng đang chuyển có khối lượng thực tế lớn hơn so với khối lượng mà doanh nghiệp đã khai báo. Người dùng click vào tab ![](link)  hoặc truy cập [tại đây](link).

### 5.2. Giao hàng thất bại

Tab này thống kê những đơn hàng có trạng thái "Thất bại" trong danh sách đơn hàng. Người dùng click vào tab ![](link) hoặc truy cập [tại đây](link). Đối với các đơn hàng thất bại, doanh nghiệp có thể khiếu nại bằng cách click nút thao tác nhanh ![](link) và chọn Khiếu nại.

### 5.3. Xác nhận chuyển hoàn

Tab này thống kê những đơn hàng đã giao thất bại và đang chuyển hoàn về cho doanh nghiệp, người dùng click vào tab ![](link) hoặc truy cập [tại đây](link).

## 6. Đối soát, thanh toán COD, chiết khấu
### 6.1. Nhanh.vn đối soát với hãng vận chuyển

Hãng vận chuyển sẽ tiền hành đối soát với Nhanh một ngày sau khi đơn Thành công hoặc Chuyển hoàn.

Lịch trình Hãng vận chuyển đối soát cho Nhanh.vn:
**Hãng vận chuyển** | **Viettel Post** | **Giaohangnhanh** | **Giaohangtietkiem** | **Vietnam Post**
------------ | ------------- | ------------- | ------------- | -------------
Ngày trả đối soát | Thứ 2, 4, 6 | Thứ 2, 4, 6 | Thứ 2, 4, 6 | Thứ 2, 3, 4, 5, 6

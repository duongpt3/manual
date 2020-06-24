# Trạng thái đơn hàng

Mỗi đơn hàng của khách hàng trên hệ thống sẽ nhận 01 trong các trạng thái sau :

- **Mới:**  Đơn hàng khách hàng đã đặt hàng chưa qua xử lý.
- **Đang xác nhận:**  Đơn hàng đang được nhân viên Chăm sóc khách hàng (gọi điện thoại) xác nhận với khách hàng.
- **Đã xác nhận:**  Đơn hàng đã được xác nhận thành công (khách hàng có mua hàng).
- **Đang đóng gói sản phẩm:**  Đơn hàng đang được nhặt hàng và đóng gói sản phẩm.
Đổi kho xuất hàng:  Đơn hàng được chuyển từ cửa hàng hết sản phẩm khách đặt sang cửa hàng còn tồn .
Chờ đi nhận:  Đơn hàng đã bắn sang hãng vận chuyển, chờ hãng vận chuyển tiếp nhận thông tin và nhận hàng.
Đang đi nhận:  Hãng vận chuyển đang nhận bàn giao đơn hàng từ doanh nghiệp.
Đã nhận hàng:  Đơn hàng đã được hãng vận chuyển tiếp nhận, đang chờ giao cho khách hàng.
Đang chuyển:  Đơn hàng đang được chuyển đi cho khách hàng.
Thành công:  Đơn hàng đã được giao thành công cho khách hàng.
Thất bại:  Đơn hàng chưa giao được cho khách hàng. (Có thể vì khách hàng bận, đi vắng, khách hẹn lại thời điểm khác giao hàng...)
Khách hủy:  Khách hàng hủy không lấy hàng nữa. Xem thêm tại đây.
Hệ thống hủy:  Đơn hàng đã bị hệ thống hủy tự động. Xem thêm tại đây.
Hết hàng:  Sản phẩm của khách đặt đã hết hàng.
Đang chuyển hoàn:  Những đơn hàng khách hàng hủy không muốn lấy sản phẩm nữa sẽ được hoàn trả về cho doanh nghiệp.
Đã chuyển hoàn:  Sau khi làm biên bản chuyển hoàn (hãng vận chuyển bàn giao lại hàng hóa cho doanh nghiệp), đơn hàng sẽ tự động chuyển sang trạng thái đã chuyển hoàn.​
(*) Lưu ý: ​Trên lịch trình của hãng vận chuyển, có thể hãng vận chuyển báo đã chuyển hoàn cho doanh nghiệp tuy nhiên trên hệ thống Nhanh.vn vẫn để ở trạng thái "Đang chuyển hoàn". 

Để tránh thất thoát hàng hóa qua quá trình vận chuyển. Khi doanh nghiệp nhận được sản phẩm thực tế hoàn lại từ hãng vận chuyển, doanh nghiệp cần đổi trạng thái thành "Đã chuyển hoàn" bằng cách: 

- Cách 01: Lập biên bản chuyển hoàn (biên bản bàn giao hàng hóa từ hãng vận chuyển -> doanh nghiệp).
- Cách 02: Cập nhật trạng thái "Đã chuyển hoàn" trên hệ thống. Đồng thời với thao tác đó, hệ thống tự động trừ đi số lượng sản phẩm "Đang tạm giữ" (để chuyển hàng) nhập lại vào kho/ cửa hàng đã xuất ra (số lượng nhập lại được tính vào trạng thái "Có thể bán").

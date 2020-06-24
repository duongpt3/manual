# Gói sản phẩm
**Tình huống:**

Bạn muốn lấy 2 sản phẩm Áo ngắn 003 và Quần ngắn 003 tạo thành một bộ quần áo để bán theo bộ, với giá do bạn quy định. Trường hợp này có 2 cách:
-  Khi bán hàng, chọn 2 sản phẩm, chiết khấu tay cho bằng với giá quy định
- Tạo gói sản phẩm (gồm 2 sản phẩm), khi bán hàng chỉ cần chọn gói sản phẩm là được.

**Quy trình sử dụng gói sản phẩm:**
* Tạo mới gói sản phẩm
* Add nhanh gói sản phẩm
* Bán gói sản phẩm
* Bung gói sản phẩm
## 1. Tạo mới gói sản phẩm tại đây:
Bản chất là lấy các sản phẩm đã có tồn tại 1 cửa hàng, ghép vào thành 1 gói sản phẩm.
Ví dụ: Tại Cửa hàng 1 có:
Áo ngắn 003: tồn 44 chiếc
Quần ngắn 003: tồn 8 chiếc

Tạo 5 gói sản phẩm có tên là Quần Áo ngắn 003, mỗi gói có 1 quần ngắn 003 và 1 áo ngắn 003.
Giá nhập gói: 150.000 đ
Giá bán gói: 250.000 đ

Khi đó hệ thống sẽ:
- Tạo phiếu Xuất [khác] gồm 5 Áo ngắn và 5 Quần ngắn 003
- Tạo phiếu Nhập [Nhà cung cấp] 5 gói sản phẩm Quần Áo ngắn 003, với giá nhập là tổng giá vốn của các sản phẩm trong gói (170.000 đ)

## 2. Thêm nhanh gói sản phẩm tại đây:
Bản chất là thêm số lượng cho các gói sản phẩm đã có, bằng cách ghép sản phẩm đang có tại cửa hàng, không nhập thêm sản phẩm.
Tương tự như Tạo gói sản phẩm, nhưng ở đây bạn không tạo gói mới mà chỉ thêm số lượng cho gói đã có trên hệ thống
Ví dụ: Add nhanh 3 gói sản phẩm Quần Áo ngắn 003, khi đó hệ thống cũng sẽ tạo phiếu Xuất [Khác] để trừ tồn 3 Áo ngắn và 3 Quần ngắn 003; đồng thời tạo phiếu Nhập [Nhà cung cấp] 3 gói sản phẩm Quần Áo ngắn 003, với giá nhập là tổng giá vốn của các sản phẩm trong gói (170.000 đ)

## 3. Nhập [Nhà cung cấp] gói sản phẩm
Hệ thống sẽ lấy theo giá nhập của gói sản phẩm mà bạn khai báo khi tạo gói (trong ví dụ trên, giá nhập gói sản phẩm Quần Áo ngắn 003 là 150.000 đ)

## 4. Bán gói sản phẩm
Hệ thống sẽ tạo phiếu Xuất bán và trừ tồn gói sản phẩm, không liên quan gì đến các sản phẩm trong gói nữa

## 5. Bung gói sản phẩm
Ngược lại với tạo gói sản phẩm. Hệ thống tạo phiếu Xuất [Khác] gói sản phẩm và Nhập [Khác] các sản phẩm trong gói

*NOTE:  
Gói sản phẩm chỉ áp dụng cho loại sản phẩm: thường, cân đo, nhiều đơn vị tính( chỉ áp dụng cho đơn vị tính nhỏ nhất)

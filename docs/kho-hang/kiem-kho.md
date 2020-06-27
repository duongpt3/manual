# Kiểm kho

Trong quá trình kinh doanh tất yếu xảy ra thất thoát, dẫn đến chênh lệch giữa số tồn kho thực tế bên ngoài và số tồn bên trong phần mềm bán hàng. Kiểm kho hàng hóa giúp bạn kiểm kê lại số lượng hàng hóa tồn kho thực tế so với số lượng tồn kho trên phần mềm, và cập nhật số lượng tồn kho thực thế lên phần mềm (bù trừ kiểm kho)

## Các loại kiểm kho
- Kiểm kho theo sản phẩm: Áp dụng khi doanh nghiệp cần kiểm đếm một (một số) mặt hàng nhất định, đã lên danh sách từ trước khi kiểm.
- Kiểm kho theo danh mục: Áp dụng khi doanh nghiệp cần kiểm đếm một hoặc một số mặt hàng trong cùng một danh mục sản phẩm. Khi bạn chọn loại kiểm kho này, hệ thống sẽ chỉ ghi nhận những sản phẩm trong danh mục đã chọn (nếu gõ tên sản phẩm hoặc dùng đầu đọc mã vạch sản phẩm ngoài danh mục thì hệ thống sẽ không ghi nhận)
- Kiểm kho toàn bộ: Áp dụng khi doanh nghiệp cần kiểm toàn bộ kho hàng/ cửa hàng. Trường hợp này, các sản phẩm không nằm trong danh sách kiểm sẽ được mặc định là không tồn (không còn) trong kho, số lượng kiểm kho bằng 0.

## Quy trình kiểm kho gồm 3 bước như sau

1. Thêm phiếu kiểm kho

2. Thêm sản phẩm cần kiểm kho vào phiếu

3. Tìm sản phẩm thiếu ( Với loại kiểm kho theo danh mục/ toàn bộ)

4. Bù trừ kiểm kho.

## Thêm phiếu kiểm kho

Bạn truy cập lần lượt vào Kho hàng / Kiểm kho / Thêm phiếu kiểm kho hoặc truy cập tại đây.

### Bước 1:
Chọn cửa hàng cần kiểm kho

### Bước 2: 
Chọn loại kiểm kho

### Bước 3
Ấn nút "Tiếp tục"

## Thêm sản phẩm kiểm kho

Bạn nhập sản phẩm cần kiểm kho vào trường Sản phẩm. Để nhập sản phẩm kiểm kho, có 02 cách như sau:

### 1.1. Nhập thủ công trực tiếp bằng tay vào hệ thống:

- Hệ thống cho phép nhập bằng Mã vạch sản phẩm/Mã sản phẩm/Tên sản phẩm.
- Sau khi hệ thống load tự động sản phẩm vào Danh sách sản phẩm kiểm kho, bạn cần cập nhật số lượng hàng tồn kho thực tế vào cột Số kiểm kho.
- Nếu doanh nghiệp dùng quét bằng mã vạch sản phẩm: Dùng đầu đọc mã vạch để quét mã vạch trên mỗi sản phẩm. Mỗi sản phẩm được tít qua, số lượng tồn kho thực tế sẽ được cập nhật luôn tại cột Số kiểm kho.
- Đối với loại kiểm kho theo danh mục, khi bạn nhập một sản phẩm không nằm trong danh mục đã chọn thì hệ thống sẽ báo Sản phẩm không thuộc danh mục đang kiểm kho để bạn chọn sản phẩm khác.
(*) Khuyến cáo: Bạn nên sử dụng phương án Quét bằng mã vạch sản phẩm để tránh nhầm lẫn, sai sót báo cáo về sau.

Giao diện làm việc khi nhập sản phẩm kiểm kho như hình bên dưới:

### 1.2. Import bằng file Excel: Click vào tab Import Excel để thực hiện thao tác Import kiểm kho bằng file Excel. Quy trình như sau

- Tải file mẫu import về
- Nhập tên sản phẩm/mã vạch/mã sản phẩm và số lượng sản phẩm tồn thực tế vào file import, sau đó save lại
- Import file Excel kiểm kho lên hệ thống.

Giao diện làm việc của Import kiểm kho như sau:

(*) Lưu ý: Trong quá trình nhập liệu sản phẩm kiểm kê, để tránh rủi ro cho doanh nghiệp, hệ thống sẽ tự động lưu lại phiếu kiểm kho sau mỗi một thao tác thêm sản phẩm vào phiếu của bạn.

## Tìm sản phẩm thiếu ( Với loại kiểm kho theo danh mục/ kiểm kho toàn bộ)

Trong quá trình kiểm kho sẽ có trường hợp, sản phẩm có số tồn trên hệ thống tuy nhiên khi đi kiểm thì không còn sản phẩm nào ( tức là đã bị mất hàng) thì trong phiếu kiểm kho bạn sẽ không thấy xuất hiện tên/ mã sản phẩm đó.

Đối với loại kiểm kho theo danh mục/ kiểm toàn bộ cửa hàng, bạn cần vào danh sách phiếu kiểm kho - ấn nút tìm sản phẩm thiếu . Khi click vào biểu tượng này hệ thống sẽ cho toàn bộ các các sản phẩm chưa được kiểm hoặc không có trong phiếu kiểm kho vào phiếu kiểm với số lượng tồn thực tế bằng 0.

Đây là 1 bước rất quan trọng, nếu bạn không ấn nút này => hệ thống sẽ không tính toán được lượng hàng thừa thiếu của các sản phẩm không được kiểm này.

## Bù trừ kiểm kho

Bù trừ kiểm kho là nghiệp vụ chuyển khớp số lượng chênh lệch giữa hệ thống và tồn thực tế sau khi được kiểm kho.

Bản chất là đưa số liệu tồn kho của sản phẩm trên hệ thống về đúng với số lượng tồn kho thực tế

Quy trình bù trừ kiểm kho được thực hiện như sau:

## Bước 1: Truy cập vào Danh sách phiếu kiểm kho, tìm đến phiếu kiểm kho cần tiến hành bù trừ

Tại Danh sách phiếu kiểm kho, bạn sẽ bắt gặp một số khái niệm như:

- Gộp phiếu kiểm kho: Chức năng này dùng để gộp các phiếu kiểm kho lại làm một, tuy nhiên chỉ gộp được khi:

+ Các phiếu phải cùng một cửa hàng và cùng 1 loại phiếu (sản phẩm / danh mục / toàn bộ)
+ Các phiếu chưa được làm phiếu bù trừ kiểm kho.

- Báo cáo: Click vào để xem chi tiết tổng số lượng sản phẩm thừa/thiếu trong mỗi lần kiểm kho
- Bù trừ kiểm kho: Dùng để cân bằng lại số tồn trên hệ thống sao cho giống với số tồn thực thế (bằng cách tạo các phiếu XNK Khác)

## Bước 2: Bù trừ kiểm kho

- Tại Danh sách phiếu kiểm kho, bạn click vào nút Bù trừ kiểm kho.
- Hệ thống sẽ hiển thị màn hình Thêm phiếu xuất nhập kho bù trừ thừa thiếu theo phiếu kiểm kho, bạn tiếp tục click vào Thêm phiếu XNK
- Lúc này, hệ thống sẽ tự động tạo 2 phiếu (Xuất kho và Nhập kho) để cân bằng lại số tồn.

## Bước 3: Kiểm tra lại việc Bù trừ kiểm kho

Sau khi bù trừ kiểm kho, bạn nên quay lại trang Danh sách phiếu kiểm kho để xem hệ thống đã tạo các phiếu Xuất/Nhập bù trừ kiểm kho chưa, và quay lại trang Danh sách sản phẩm để xem số tồn trên hệ thống đã khớp với số tồn thực tế vừa kiểm hay chưa.

Trên đây là toàn bộ quy trình kiểm kho trên Nhanh.vn, ngoài ra bạn cũng có thể tham khảo một số kinh nghiệm kiểm kho tại đây

Bạn có thể xem video hướng dẫn kiểm kho cân tồn tại đây

# Kinh nghiệm kiểm kho

## Kiểm tra và cập nhật lại đúng trạng thái cho đơn hàng

a, [Danh sách đơn hàng](https://new.nhanh.vn/order/manage/index)

- Đặc biệt là các đơn hàng loại “Tự vận chuyển”, anh/chị cần chắc chắn cập nhật đúng trạng thái đơn hàng để sản phẩm có trạng thái tồn đúng.

- Đối với các đơn hàng ở trạng thái “Chờ thu gom”, “Đang chuyển”, “Thất Bại”, “Đang chuyển hoàn”, sản phẩm trong đơn sẽ có trạng thái tồn là “Đang chuyển”, tức là không còn được tính là hàng còn nằm trong kho để có thể kiểm đếm đến nữa.

- Đối với đơn ở trạng thái “Đang chuyển hoàn”, a chị cần check xem có đơn nào hàng đã nhận về đến kho hay chưa. Nếu đã về đến kho, cần đổi sang trạng thái “Đã chuyển hoàn” để hệ thống ghi nhận lại hàng vào phần Tồn trong kho và kiểm đếm đến như một sản phẩm bình thường khác

- Đối với các đơn hàng ở trạng thái khác đã nêu (trừ trạng thái “Thành công”, “Đổi kho xuất hàng”), có thể hiểu tồn của sản phẩm vẫn đang nằm trong kho và cần kiểm đếm đến khi làm kiểm kho

b, Danh sách đơn hàng trên các Sàn TMĐT (Shopee, Lazada, Sendo, Tiki....)

- Tương tự với đơn hàng thường tạo trên Nhanh, các đơn hàng sàn thương mại điện tử cũng sẽ có trạng thái tương tự làm ảnh hưởng đến trạng thái tồn của sản phẩm

- Trước khi làm kiểm kho, a chị cần tạm dừng việc tải đơn hàng tự động (nếu có) bằng cách vào Cài Đặt > Đồng bộ sàn TMĐT sửa cài đặt đồng bộ đơn hàng sang “Đồng bộ thủ công”, sau đó chủ động tải đơn hàng từ sàn TMĐT về Nhanh.vn lần cuối.

- Check ở tab trả hàng, xem có đơn hàng nào đã hoàn về và nhận được, thì cần đổi trạng thái đơn hàng đó sang “Đã chuyển hoàn” để tồn của sản phẩm được ghi nhận vào Tồn trong kho để kiểm đếm.

## Kiểm tra, rà soát lại các phiếu chuyển kho, phiếu yêu cầu XNK chưa hoàn thiện Duyệt hoặc Xác nhận

Dành cho các doanh nghiệp sử dụng đến tính năng Chuyển kho (giữa 2 hay nhiều kho hàng trên Nhanh) hoặc Bán Chéo Doanh nghiệp (Cho phép bán hàng giữa 2 Doanh nghiệp cùng dùng Nhanh.vn)

Để check lại các phiếu yêu cầu XNK, bạn thao tác vào Kho hàng / Phiếu Yêu cầu XNK /Phiếu Yêu cầu XNK hoặc truy cập tại đây

VD: Với hành động Chuyển kho:

- Đối với kho xuất hàng, hành động “Duyệt” đồng nghĩa với việc trừ tồn ở kho

- Đối với kho nhận hàng, hành động “Xác nhận” đồng nghĩa với việc cộng thêm tồn vào kho

## Tính toán lại số Tạm giữ và Đang chuyển

### Trường hợp dùng Máy quét mã vạch

Máy quét mã vạch (đầu tít mã vạch) giúp quá trình kiểm kho được tiến hành một cách nhanh chóng và dễ dàng. Tuy nhiên, nếu bạn không đưa ra được một quy trình kiểm kho chặt chẽ, việc sai sót là khó tránh khỏi.

### Một số trường hợp mà đa số các doanh nghiệp hay gặp phải như sau:

- Tít 02 lần/sản phẩm: Do tít đúp vào sản phẩm. Khi đó hệ thống sẽ ghi nhận sản phẩm đó 02 lần tương đương với số lượng = 02 sản phẩm.
- File import thiếu sản phẩm: Khi tít mã vạch, nếu không đặt con trỏ chuột đúng cột mã vạch thì hệ thống sẽ không nhận được mã vạch sản phẩm. Do đó file import sẽ bị thiếu sản phẩm.
- Quét (tít) thiếu sản phẩm/khu vực nào đó. 
- Dán sai tem/In sai tem của sản phẩm: Tem mã vạch của sản phẩm này được dán cho sản phẩm kia, hệ thống không phân biệt được chính xác mã vạch được kiểm là của sản phẩm nào.
- Import 01 file nhiều lần.

### Cách khắc phục, giảm thiểu rủi ro kiểm kho

- Phân tách khu vực, đánh dấu khu vực/dãy hàng/kệ hàng trước khi kiểm kho.
- Mỗi phân khu nên kiểm bởi 01 file Import, tránh kiểm kho 02 khu vực trên 01 file Import kiểm kho.
- Đánh tên file kiểm kho theo khu vực kiểm để tránh trường hợp import nhầm file, import nhiều lần.
- Nên kiểm kê thủ công trước để so sánh với số lượng được ghi nhận thông qua máy quét (đầu tít) mã vạch, giảm thiểu tối đa sai sót về lượng.

### Rà soát lại hàng hóa sau kiểm kho

Sau khi kiểm kho, ghi nhận số lượng hàng hóa thất thoát, mất mát. Bạn nên kiểm tra lại để đảm bảo tính chính xác của kết quả kiểm kho.

#### Một số phương án được đề xuất kiểm tra như sau:

- Kiểm tra lại lịch sử import: Tại module Lịch sử Import, bạn rà soát lại lịch sử Import kiểm kho xem có import đủ/trùng file hay không ?

- Kiểm tra lại số tồn thực tế của các sản phẩm được báo chênh lệch (thừa/thiếu): Để loại trừ khả năng kiểm kê thủ công sai số lượng thực tế.
- Kiểm tra lại chi tiết xuất nhập kho (XNK):  Tại [Danh sách sản phẩm XNK](https://new.nhanh.vn/inventory/bill/index) bạn cần rà soát lại số lượng phiếu XNK được lập ra.

Nếu cùng một thời điểm, cùng một ngày, có số sản phẩm và số lượng sản phẩm XNK, nội dung ghi chú và mô tả giống nhau thì khả năng cùng 01 phiếu XNK được lập làm 02 lần (đúp phiếu).

Ví dụ: Chỉ có 02 sản phẩm có phát sinh xuất nhập kho nhưng có 02 người dùng (02 tài khoản) cùng lập phiếu, hệ thống sẽ ghi nhận số lượng sản phẩm là 04 sản phẩm. Khi kiểm kho, hệ thống báo thừa 02 sản phẩm.

#### Cách xử lý: 

- Xóa bớt 01 phiếu thừa hoặc làm thêm phiếu nhập/xuất bù trừ số lượng cho phiếu đã nhập/xuất đó.

- Kiểm tra lại số tồn trong Danh sách sản phẩm: Tại [Danh sách sản phẩm](https://new.nhanh.vn/product/item/index) kiểm tra lại trạng thái của sản phẩm.

Nếu sản phẩm đang ở trạng thái đang chuyển kho: Số tồn không ghi nhận vào hệ thống.
Nếu sản phẩm đang ở trạng thái lỗi/ ghi nhận mất hàng: Kiểm tra lại khu vực hàng lỗi để xác nhận lại số lượng tồn đúng.

- Kiểm tra lại trạng thái (duyệt/ chưa duyệt) của Danh sách phiếu yêu cầu XNK:

Kiểm tra lại tình trạng của toàn bộ các phiếu yêu cầu nhập xuất tới kho/cửa hàng đang kiểm. Nhiều trường hợp, trên thực tế kho/cửa hàng đang kiểm đã ghi nhận số lượng hàng nhập xuất, chuyển kho tuy nhiên chưa xác nhận lại trên phiếu XNK trên hệ thống, do đó hệ thống sẽ báo thừa khi kiểm kho và ngược lại.
- Bán hàng nhầm mã: Do thu ngân/bán hàng nhập sai mã, tên sản phẩm,...

Trường hợp này khá phổ biến trong các doanh nghiệp, đặc biệt là đối với các sản phẩm chia thuộc tính màu sắc, size số,...; sản phẩm tương tự nhau; tem mã vạch/mã sản phẩm bị mờ, biến dạng; và dán sai tem sản phẩm/ mã vạch của sản phẩm.
- Kiểm tra lại chi tiết XNK:

Tại [Báo cáo Chi tiết XNK](https://new.nhanh.vn/report/inventory/imex)  kiểm tra lại chi tiết số lượng sản phẩm xuất nhập kho, có thể do hệ thống thống kê sai sót.

Trường hợp đơn hàng đã được giao thành công nhưng trên hệ thống không cập nhật, số lượng xuất nhập kho không được trừ đi.

Khi đó cần truy cập [Danh sách đơn hàng](https://new.nhanh.vn/order/manage/index), lọc Đơn hàng thành công kiểm tra lại số lượng đơn hàng thành công có khớp với số lượng sản phẩm được xuất nhập kho hay không?

Hoặc truy cập [Danh sách hóa đơn bán hàng](https://new.nhanh.vn/pos/bill/index), kiểm tra lại số lượng sản phẩm trong toàn bộ hóa đơn và đối chiếu với số lượng hàng hóa XNK trong khoảng thời gian đó có khớp hay không?

Thông thường là khi đã có hóa đơn/ đã giao thành công hệ thống tự động trừ xuất nhập kho .

Rà soát lại xem các đơn hàng đã check đúng trạng thái chưa? Có đơn nào đã giao thành công mà lại check sai trạng thái là không thành công hay không?

- Chưa nhận hàng chuyển hoàn.

Tại  [Danh sách đơn hàng](https://new.nhanh.vn/order/manage/index) ,lọc các đơn hàng có trạng thái Đã chuyển hoàn và đối soát lại với bộ phận chịu trách nhiệm nhận hàng chuyển hoàn xem sản phẩm trên thực tế đã được chuyển hoàn hay chưa?

Thông thường khi hãng vận chuyển bàn giao hàng hóa cho Nhanh.vn, hệ thống vẫn để ở trạng thái "Đang chuyển hoàn". Chỉ khi nào doanh nghiệp nhận được bàn giao hàng hóa thực tế, mới đổi trạng thái đơn hàng sang "Đã chuyển hoàn" để loại bỏ sản phẩm khỏi Danh sách đang chuyển hàng trong Danh sách sản phẩm.

**Lưu ý:** Việc đổi trạng thái thủ công này, dễ gây thất thoát hàng hóa và khó kiếm soát. Bạn nên thận trọng với nghiệp vụ này.

## Câu hỏi thường gặp

| STT | Câu Hỏi | Giải Đáp |
|-----|---------|----------|
| 1 | Khi kiểm kho theo sản phẩm bằng file excel xong rồi, nhưng khách nhớ ra còn thiếu 1 sản phẩm chưa kiểm thay vì vào sửa phiếu kiểm kho có nút tắt nào đến phần thêm sản phẩm vào phiếu hay không? | Có nút thêm sản phẩm vào phiếu kiểm kho, nút bánh răng bên phải phiếu kiểm kho đó.|
| 2 | Khi kiểm kho phát hiện có chênh lệch giữa số tồn thực tế với số tồn trên hệ thống, thao tác như thế nào để sửa lại cho đúng? | Thêm thao tác bù trừ kiểm kho, rồi ấn Thêm Phiếu XNK. Xong |
| 3 | Nếu số tồn của sản phẩm nhỏ hơn hoặc lớn hơn số lượng nằm trong khoảng hạn mức tồn kho thì Nhanh.vn có 1 thông báo hay cảnh báo hay không? | Không có, chỉ xem trong hạn mức tồn thì có bôi đỏ sản phẩm |
| 4 | Khi hướng dẫn kiểm kho toàn bộ sản phẩm, nếu khách hàng quên tên 1 sản phẩm thì hệ thống sẽ tự hiểu sản phẩm đó có số kiểm kho như thế nào ạ? | Các sản phẩm không điền, sẽ hiện trong danh sách sản phẩm thiếu và số kiểm kho là 0. |
| 5 | Phiếu kiểm kho có mang lại lợi ích gì cho các cửa hàng? | check xem tồn thực tế và tồn trên phần mềm chênh lệch như thế nào. |






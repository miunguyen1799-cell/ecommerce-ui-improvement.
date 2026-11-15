# E-commerce UI Improvement

## 1. Giới thiệu

Website mô phỏng khu vực sản phẩm chăm sóc da nổi bật của một cửa hàng thương mại điện tử. Giao diện tập trung vào việc trình bày sản phẩm, giá khuyến mãi và nút thêm vào giỏ hàng trong bố cục rõ ràng, dễ xem trên nhiều thiết bị.

## 2. Website tham khảo

- Tên website: [Hasaki](https://hasaki.vn/)
- URL tham khảo: [Chiến dịch Siêu Sale Bùng Nổ](https://hasaki.vn/campaign/sieu-sale-bung-no)
- Khu vực đã khảo sát: khu vực danh sách sản phẩm khuyến mãi, thẻ sản phẩm, nhãn giảm giá, giá bán và bố cục lưới sản phẩm.

Giao diện trong bài là sản phẩm tự xây dựng để học tập, không sao chép nguyên bản nhận diện hoặc mã nguồn của website tham khảo.

## 3. Chức năng

- Hiển thị danh sách 4 sản phẩm chăm sóc da.
- Hiển thị thương hiệu, tên sản phẩm, giá bán, giá gốc và phần trăm giảm giá.
- Nút “Thêm vào giỏ” cho từng sản phẩm.
- Bố cục responsive: 4 cột trên desktop, 2 cột trên tablet và điện thoại.
- Hiển thị ảnh sản phẩm từ các URL hình ảnh đã cung cấp.
- Hiệu ứng hover trên thẻ sản phẩm và nút thao tác.

## 4. Công nghệ

- HTML5: xây dựng cấu trúc và nội dung trang.
- CSS3: tạo bố cục Grid, Flexbox, màu sắc, hiệu ứng và responsive.
- Không sử dụng framework hoặc thư viện JavaScript bên ngoài.

## 5. Cách chạy

Mở file [index.html](./index.html) bằng trình duyệt. Vì một số ảnh sản phẩm dùng URL bên ngoài, cần có kết nối Internet để tải đầy đủ hình ảnh.

## 6. Cải tiến đã thực hiện

### Vấn đề ban đầu

- Giao diện sản phẩm cần được tổ chức rõ hơn để người xem dễ so sánh.
- Thông tin giá ưu đãi và giá gốc chưa tạo đủ điểm nhấn.
- Cần hỗ trợ tốt hơn cho màn hình tablet và điện thoại.
- Hình ảnh sản phẩm cần được trình bày đồng nhất trong các thẻ.

### Thay đổi đã thực hiện

- Tạo lưới sản phẩm bằng CSS Grid với khoảng cách nhất quán.
- Dùng Flexbox trong thẻ sản phẩm để các nút nằm cân đối ở cuối thẻ.
- Làm nổi bật giá khuyến mãi bằng màu cam và nhãn giảm giá.
- Chuẩn hóa khung ảnh theo tỷ lệ vuông, sử dụng `object-fit: contain`.
- Bổ sung hiệu ứng hover, bo góc, bóng đổ và trạng thái focus cho nút.
- Thêm các breakpoint responsive cho desktop, tablet và mobile.
- Bổ sung `alt` cho hình ảnh và cấu trúc semantic cơ bản như `header`, `main`, `section`, `article`, `footer`.

## 7. Hỗ trợ từ AI

AI hỗ trợ phân tích cấu trúc giao diện, đề xuất cách tổ chức thẻ sản phẩm, cải thiện responsive CSS, tạo ảnh SVG mẫu ban đầu và kiểm tra lỗi HTML/CSS. Các URL hình ảnh sản phẩm được cập nhật theo ảnh do người thực hiện cung cấp.

Người thực hiện đã kiểm tra lại nội dung, tên sản phẩm, giá, đường dẫn ảnh, bố cục hiển thị trên trình duyệt và điều chỉnh ảnh cho từng thẻ sản phẩm.

## Thông tin học phần

**Phát triển ứng dụng WEB/TMĐT**  
TS Nguyễn Mạnh Tuấn – tuannm@ueh.edu.vn



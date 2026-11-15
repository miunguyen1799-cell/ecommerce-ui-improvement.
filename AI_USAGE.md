# AI Usage Log

## 1. Công cụ AI

- Công cụ: OpenAI Codex.
- Phạm vi sử dụng: hỗ trợ trong môi trường phát triển Visual Studio Code.

## 2. Mục đích sử dụng

- Phân tích yêu cầu và cấu trúc giao diện HTML/CSS.
- Đề xuất bố cục thẻ sản phẩm và cách tổ chức CSS responsive.
- Hỗ trợ tạo cấu trúc trang sản phẩm mẫu.
- Hỗ trợ sửa đường dẫn ảnh sản phẩm theo các URL được cung cấp.
- Kiểm tra lỗi HTML/CSS và xác nhận trang có thể mở trong trình duyệt.

## 3. Prompt đã sử dụng

Các yêu cầu chính đã sử dụng trong quá trình thực hiện:

1. Cung cấp cấu trúc HTML cho trang sản phẩm chăm sóc da.
2. Cung cấp CSS cho giao diện thẻ sản phẩm và responsive.
3. Cung cấp các URL ảnh sản phẩm để thay vào từng thẻ tương ứng.
4. Yêu cầu điều chỉnh lại ảnh khi ảnh trước đó không đúng sản phẩm.
5. Yêu cầu bổ sung nội dung mô tả dự án và nhật ký sử dụng AI.

## 4. Kết quả AI đề xuất

- Tạo giao diện gồm header, khu vực ưu đãi, lưới 4 sản phẩm và footer.
- Sử dụng CSS Grid cho bố cục sản phẩm.
- Sử dụng Flexbox để căn chỉnh nội dung trong từng thẻ.
- Thêm màu nhấn cho giá khuyến mãi và badge giảm giá.
- Thêm responsive breakpoint ở 1024px và 600px.
- Bổ sung hiệu ứng hover và trạng thái focus cho khả năng sử dụng tốt hơn.
- Cập nhật lần lượt ảnh cho sản phẩm L'Oreal, La Roche-Posay, CeraVe và Neutrogena theo URL được cung cấp.

## 5. Kiểm tra và điều chỉnh

- Đã mở [index.html](./index.html) trực tiếp bằng trình duyệt.
- Đã kiểm tra các sản phẩm, tên, giá và nút “Thêm vào giỏ”.
- Đã kiểm tra lại các ảnh sau mỗi lần thay URL.
- Đã kiểm tra lỗi HTML/CSS trong môi trường phát triển và không phát hiện lỗi.
- Một số URL ảnh là tài nguyên bên ngoài nên cần Internet để tải ảnh.
- AI không được dùng để quyết định nội dung học thuật cuối cùng; người thực hiện chịu trách nhiệm rà soát và chỉnh sửa tài liệu.

## 6. Phần tôi hiểu và có thể giải thích

- `product-grid` dùng CSS Grid để chia số cột theo kích thước màn hình.
- `product-card` dùng Flexbox theo chiều dọc để giữ bố cục nhất quán.
- `aspect-ratio: 1` tạo khung ảnh vuông.
- `object-fit: contain` giúp ảnh sản phẩm không bị méo hoặc cắt.
- Media query thay đổi số cột và khoảng cách trên tablet/mobile.
- Giá khuyến mãi, giá gốc và badge giảm giá được tách thành các phần tử riêng để dễ đọc và dễ chỉnh sửa.
- Thuộc tính `alt` giúp hình ảnh có mô tả khi không tải được và hỗ trợ khả năng tiếp cận.



# Sống Có Chủ Đích — Book Landing Page

Website tĩnh giới thiệu sách, được xây dựng bằng HTML5, CSS3 và Bootstrap 5. Giao diện tối giản, ưu tiên trải nghiệm đọc và responsive trên điện thoại, máy tính bảng, máy tính.

## Các phần của trang
- Header / navigation
- Book Overview
- Author
- Features
- Prices
- Download call-to-action
- Reader's Say
- Footer

## Công nghệ
- HTML5
- Bootstrap 5.3.3 (CDN)
- CSS3 với CSS custom properties và media queries
- Google Fonts (DM Sans, Playfair Display)

## Chạy dự án
1. Tải hoặc giải nén repository.
2. Mở `index.html` bằng trình duyệt, hoặc mở thư mục trong VS Code và dùng Live Server.
3. Cần kết nối Internet để tải Bootstrap, Google Fonts và ảnh tác giả từ các URL bên ngoài.

## Tùy chỉnh
- Chỉnh màu sắc, kiểu chữ, khoảng cách tại phần `:root` trong `css/style.css`.
- Chỉnh nội dung các phần trong `index.html`.
- Ảnh chân dung tác giả hiện dùng URL Unsplash; có thể thay bằng ảnh hợp lệ trong thư mục `images/`.
- Giá, tên tác giả, đánh giá và nội dung là dữ liệu minh họa cho bài tập. Nút mua/tải chưa kết nối chức năng thật.

## Kiểm tra responsive
Trong Chrome hoặc Edge:
1. Mở trang.
2. Nhấn `F12` hoặc `Ctrl + Shift + I`.
3. Bật Device Toolbar (`Ctrl + Shift + M`).
4. Thử các chiều rộng khoảng 375px, 768px, 1024px và 1440px.
5. Kiểm tra menu thu gọn, thẻ giá, hình bìa, không có cuộn ngang và nội dung không bị cắt.
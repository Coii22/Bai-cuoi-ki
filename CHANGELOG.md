## 23/11
## [Released]
### Thêm
- Tạo trang kết quả liên hệ `ket-qua.html` xử lý chuyển hướng khi gửi form liên hệ bằng phương thức `GET`.
- Thêm header điều hướng (`<header class="site-header">`), khu vực thông báo kết quả (`.result-panel`) và footer (`<footer class="site-footer">`) cho `ket-qua.html`, đồng bộ bảng màu dark-mode với `index.html`.
- Bổ sung kiểu hiển thị responsive cho trang kết quả trên màn hình tablet và điện thoại.
- Xây dựng cấu trúc trang chủ `index.html` gồm các khu vực: Sidebar hồ sơ và điều hướng, Giới thiệu, Kỹ năng, Học tập, Dự án, và Liên hệ.
- Thiết kế giao diện `css/style.css` với biến CSS (`:root`), giao diện tối (`#090d16`, `#111827`, `#162032`), màu nhấn cyan (`#06b6d4`) và amber (`#f59e0b`), hỗ trợ `focus-visible`, responsive (`1024px`, `768px`, `480px`) và `prefers-reduced-motion`.
- Thêm form liên hệ với các thuộc tính kiểm tra dữ liệu HTML5 (`required`, `minlength`, `maxlength`, `type="email"`) và `aria-describedby`.

### Thay đổi
- Tinh chỉnh bố cục thẻ dự án (`.project-card`) bằng Flexbox để các card cao đều nhau và đẩy liên kết GitHub xuống đáy; đặt tỷ lệ khung hình ảnh `aspect-ratio: 16 / 10` (`object-fit: cover`).
- Đổi chiều cao cố định của sidebar từ `height: 100vh` sang `min-height: 100vh` để tránh bị sát/tràn trên màn hình có chiều cao thấp.
- Bọc bảng học tập (`.study`) trong vùng cuộn ngang `.table-responsive` nhằm hiển thị ổn định hơn trên màn hình nhỏ.
- Chuyển các liên kết GitHub trong danh sách dự án từ thẻ `<span>` sang thẻ `<a>` có `target="_blank"` và `rel="noopener noreferrer"`.

### Lỗi 
- Khắc phục tình trạng báo lỗi `ERR_FILE_NOT_FOUND` khi chuyển trang do kiểm tra lại tên tệp (`index.html`, `ket-qua.html`) và vị trí thư mục tương đối.
- Sửa một số chi tiết trình bày, chính tả và khoảng trắng trong nội dung giới thiệu, học tập và form liên hệ.


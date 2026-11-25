# Nguyễn Văn Thế — Portfolio CV

Website Portfolio CV cá nhân giới thiệu bản thân,kỹ năng,quá trình học tập học kỳ 1 của em và các sản phẩm thực hành đầu tiên của sinh viên năm nhất ngành Công nghệ Thông tin — Trường Đại học Đại Nam.

## Các phần nội dung chính
- **Sidebar & Điều hướng:** Hiển thị thông tin cá nhân, ảnh đại diện, menu cuộn tới từng mục (`Giới thiệu`, `Kỹ năng`, `Dự án`, `Học tập`, `Liên hệ`) và thông tin bản quyền năm 2026.
- **Giới thiệu:** Tổng quan ngắn gọn về bản thân và lối dẫn nhanh tới danh sách dự án.
- **Kỹ năng:** Liệt kê các kỹ năng hiện tại về HTML5, CSS, Visual Studio Code, Git/GitHub và làm việc nhóm.
- **Học tập:** Bảng tóm tắt các học phần tiêu biểu ở HK1 (*Nhập môn Công nghệ Thông tin*, *Thiết kế web*) cùng sản phẩm tương ứng.
- **Dự án:** Trưng bày 2 dự án/nhóm bài tập nổi bật:
  1. **Portfolio CV cá nhân** (xây dựng bằng HTML và CSS).
  2. **Website thực hành HTML & CSS** (giao diện web cơ bản và Responsive Web Design).
- **Liên hệ & Form gửi lời nhắn:** Cung cấp thông tin liên hệ và biểu mẫu gửi lời nhắn (`action="ket-qua.html"`, `method="get"`) có kiểm tra độ dài ký tự và hỗ trợ trợ năng (`aria-describedby`).

## Công nghệ sử dụng
- **HTML5** (cấu trúc ngữ nghĩa: `<aside>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<form>`)
- **CSS** (liên kết qua `css/style.css`, bố cục lưới/cột và Responsive cơ bản)
- **Hình ảnh tĩnh** trong thư mục `assets/`

## Cấu trúc thư mục
```text
├── index.html
├── ket-qua.html
├── css/
│   └── style.css
└── assets/
    ├── du-an-1.svg
    ├── du-an-2.svg
    ├── du-an-3.svg
    └── 791975572_1060704449904978_7434436045093909714_n.jpg
     



## Thông tin tác giả      
Họ và tên: Nguyễn Văn Thế

Ngành / Lớp: Công nghệ Thông tin — Lớp CNTT 20-02

Trường: Đại học Đại Nam

Email: nguyenvanthe19062008@gmail.com

GitHub: github.com/Coii22


## Demo

1. **Mở URL & đối chiếu phiên bản:** Mở [https://coii22.github.io/Bai-cuoi-ki/](https://coii22.github.io/Bai-cuoi-ki/) trên trình duyệt và đối chiếu với kho mã nguồn [https://github.com/Coii22/Bai-cuoi-ki.git](https://github.com/Coii22/Bai-cuoi-ki.git) cùng mã commit/tag đã báo cáo (`c2b1aea`, `9d246c5` / `v0.1.0`, `b466198`).
2. **Đi qua phần chính:**
   - Giới thiệu thông tin cá nhân tại `.sidebar` và `#gioi-thieu`.
   - Xem phần kỹ năng (`.skills`) và bảng học tập (`.study`).
   - Chuyển nhanh tới `#du-an` bằng nút **"Xem dự án"** hoặc menu điều hướng, rà soát các thẻ dự án.
   - Nhập và gửi thử biểu mẫu tại `#lien-he` để kiểm tra luồng chuyển sang `ket-qua-lien-he.html`.
3. **Kiểm tra responsive:** Mở DevTools (`F12`), chuyển đổi giữa màn hình rộng (desktop) và màn hình hẹp (tablet, mobile) để minh họa `.sidebar` thay đổi vị trí, lưới cột co giãn và bảng `.study` cuộn ngang không gây tràn trang.



# xulytiengviet — GitHub Pages & Google Search Console

Trang gốc cho các dự án nghiên cứu, giáo dục, GIS/WebGIS và phần mềm mã nguồn mở thuộc tài khoản GitHub [xulytiengviet](https://github.com/xulytiengviet).

## Xác minh Google Search Console

- Tệp được chuẩn bị: [google052c9bd24ad20cdb.html](./google052c9bd24ad20cdb.html).
- Nội dung theo quy ước Google Site Verification API: `google-site-verification: google052c9bd24ad20cdb.html`.
- **Cần đối chiếu với tệp gốc tải từ Google Search Console**. Nếu Google cấp nội dung khác, phải thay bằng nội dung gốc không chỉnh sửa.
- Để tệp xuất hiện tại `https://xulytiengviet.github.io/google052c9bd24ad20cdb.html`, repository cần có tên **`xulytiengviet.github.io`** và GitHub Pages cần được cấu hình deploy từ `main` / `/(root)`.
- Repository hiện tại có tên `xulytiengviet`; nếu giữ tên này, GitHub Pages của repo sẽ dùng đường dẫn dự án `https://xulytiengviet.github.io/xulytiengviet/` thay vì phục vụ ở tên miền gốc.

### Các bước quản trị còn lại

1. Trong **Settings → General → Repository name**, đổi tên repository thành `xulytiengviet.github.io` (nếu muốn sử dụng chính repo này làm user site). **Lưu ý:** việc đổi tên sẽ không còn sử dụng repo này làm kho README hồ sơ GitHub đặc biệt.
2. Trong **Settings → Pages**, chọn **Deploy from a branch**, `main`, `/(root)` rồi lưu.
3. Mở trực tiếp `https://xulytiengviet.github.io/google052c9bd24ad20cdb.html` bằng cửa sổ ẩn danh. Phải thấy đúng một dòng xác minh.
4. Trên Google Search Console, kiểm tra property URL-prefix chính xác và nhấn **VERIFY**.
5. Trong **Security & Manual Actions → Security Issues**, kiểm tra/cải thiện các vấn đề bảo mật thực tế và gửi **Request Review** nếu cần. Xác minh quyền sở hữu **không tự động gỡ cảnh báo Safe Browsing**.

## Nguyên tắc an toàn

Trang `index.html` không tải JavaScript bên ngoài, không có đăng nhập, không yêu cầu mật khẩu, seed phrase hay khóa riêng, không kích hoạt giao dịch blockchain.

Tài liệu:
- [Google Search Console – Verify site ownership](https://support.google.com/webmasters/answer/9008080)
- [GitHub Pages – What is GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)

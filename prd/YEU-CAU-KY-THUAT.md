# Yêu cầu kỹ thuật

## Công nghệ

- HTML5, CSS3, JavaScript thuần (ES6).
- Bootstrap **5.3** nạp qua CDN (CSS và bundle JS).
- Không dùng framework JS, không dùng ngôn ngữ hoặc dịch vụ backend.

## Cấu trúc file

- Gộp toàn bộ vào **một file duy nhất**: `index.html`.
- CSS nằm trong thẻ `<style>`, JS nằm trong thẻ `<script>` ở cuối `<body>`.

## Yêu cầu chung

- Thẻ `<html lang="vi">`.
- Có `meta charset`, `meta viewport`, `title`, `meta description`.
- Mọi ảnh đều có thuộc tính `alt` mô tả rõ ràng.
- Responsive, thiết kế ưu tiên điện thoại (mobile first).
- Dùng thẻ ngữ nghĩa: `header`, `nav`, `main`, `section`, `footer`.
- Mỗi khu vực có `id` riêng để menu cuộn tới (`#gioi-thieu`, `#tien-ich`, `#phap-ly`, `#lien-he`).

## JavaScript

| Chức năng | Mô tả |
|-----------|-------|
| Cuộn mượt | Bấm menu hoặc nút CTA thì cuộn mượt tới khu vực tương ứng |
| Hiệu ứng hiện dần | Các khối nội dung mờ dần hiện ra khi cuộn tới (IntersectionObserver) |
| Kiểm tra form | Họ tên không rỗng; số điện thoại Việt Nam gồm 10 chữ số, bắt đầu bằng 0 |
| Thông báo | Hiển thị thông báo thành công, **không gửi dữ liệu đi đâu** |

## Hình ảnh

- Dùng ảnh placeholder từ `picsum.photos`, mỗi ảnh một seed khác nhau.
- Ghi chú trong code ở những vị trí cần thay ảnh thật.

## Tiêu chí hoàn thành

- [ ] Mở `index.html` chạy được ngay, không lỗi console.
- [ ] Hiển thị đúng ở chiều rộng 360px, 768px và 1280px.
- [ ] Menu thu gọn thành hamburger trên điện thoại.
- [ ] Form báo lỗi đúng khi nhập sai, báo thành công khi nhập đúng.
- [ ] Không có ảnh bị lỗi hoặc thiếu alt.

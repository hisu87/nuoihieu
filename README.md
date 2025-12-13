<div align="center">

# Nuoihieu

Giải Cứu Hiếu Dev • Noel 2025 🎄

[![License](https://img.shields.io/github/license/hisu87/nuoihieu)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hisu87/nuoihieu?style=social)](https://github.com/hisu87/nuoihieu)
[![Built with](https://img.shields.io/badge/Built%20with-HTML%2C%20TailwindCSS%2C%20Font%20Awesome-blue)](#tech-stack)

<br/>

🔗 Live: hisu87.github.io/nuoihieu/

<img src="assets/logo.png" alt="Nuoihieu Logo" width="200" />

</div>

## Tổng Quan

Nuoihieu là trang web holiday mini-project mang phong cách vui nhộn: hiệu ứng tuyết rơi, đèn led RGB, các section giới thiệu, kêu gọi donate, và nhiều tương tác nhỏ dễ thương. Dự án tối giản, chỉ một file `index.html` nên rất dễ chạy và tùy biến.

## Điểm Nổi Bật

- Hiệu ứng tuyết rơi và dải LED trang trí phong cách "dev gaming".
- Thiết kế hiện đại với TailwindCSS, icon từ Font Awesome.
- Phần trăm năng lượng, trạng thái động, và các nút CTA rõ ràng.
- Tối ưu chia sẻ link: đã thêm Open Graph + Twitter Card.
- Favicon và app icons: dùng `logo.png`, kèm biến thể 32×32.

## Tech Stack

- **HTML**: cấu trúc trang đơn giản, dễ chỉnh sửa.
- **TailwindCSS CDN**: styling utility-first, không cần build.
- **Font Awesome**: icon nhanh, đẹp.

## Bắt Đầu (Local)

Tuỳ nhu cầu, bạn có thể chạy trực tiếp hoặc tạo server tĩnh để đảm bảo preview chính xác.

### Cách A: Mở trực tiếp

1. Mở file `index.html` bằng trình duyệt.
2. Thích hợp để xem giao diện; một số thẻ social preview chỉ hoạt động trên server/public URL.

### Cách B: Chạy server tĩnh

Nếu có Python 3:

```bash
python -m http.server 5500
# Truy cập http://localhost:5500/
```

Hoặc dùng Node.js với `npx`:

```bash
npx serve . -p 5500
# Truy cập http://localhost:5500/
```

## Cấu Trúc & Tuỳ Biến

- `index.html`: nội dung chính, hiệu ứng, layout, meta tags.
- `logo.png`: favicon, og/twitter image, apple-touch-icon.
- `README.md`: tài liệu dự án.

Tuỳ biến title/description trong phần `<head>` nếu bạn muốn hiển thị nội dung khác khi chia sẻ.

## Chia Sẻ Link (Social Preview)

Dự án đã cấu hình đầy đủ:

- **Open Graph** (`og:title`, `og:description`, `og:image`, `og:url`, ...)
- **Twitter Card** (`summary_large_image` với `twitter:image`)
- **Canonical URL** để thống nhất preview: `hisu87.github.io/nuoihieu/`

Nếu bạn deploy ở domain khác, hãy cập nhật các thẻ URL tương ứng trong `index.html`.

## Deploy

- Recommend: Vercel/Netlify/GitHub Pages cho site tĩnh.
- Chỉ cần upload `index.html` và `logo.png` là có thể chạy.

## Đóng Góp

PRs và issues luôn được hoan nghênh. Bạn có ý tưởng hiệu ứng mới hoặc copywriting dí dỏm? Hãy mở issue hoặc gửi PR.

## License

Phân phối theo giấy phép trong file `LICENSE`. Xem badge ở đầu để biết loại license hiện tại.

---

Nếu bạn muốn, mình có thể thêm `og-image` chuyên dụng (kích thước lớn, bố cục đẹp hơn để share lên Facebook/Twitter), hoặc tạo script nhỏ để build favicon đa kích thước.

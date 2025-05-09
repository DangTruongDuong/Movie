# VuePhim 🎬

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D)](https://vuejs.org/) [![Build](https://img.shields.io/badge/Build-Passing-brightgreen)](https://github.com/your-username/vuephim) [![Version](https://img.shields.io/badge/Version-1.0.0-blue)](https://github.com/your-username/vuephim/releases)

**VuePhim** - Ứng dụng web Vue.js tích hợp [PhimAPI](https://phimapi.com/), mang đến trải nghiệm khám phá phim mượt mà với giao diện đẹp, bộ lọc thông minh, responsive tối ưu.

---

## Giới Thiệu

VuePhim là nền tảng front-end dành cho người yêu phim, hỗ trợ duyệt, lọc, tìm kiếm phim theo thể loại, quốc gia, năm phát hành. Thiết kế tinh tế, hiệu suất cao, VuePhim đưa thế giới phim ảnh đến bạn.

**Giá trị**: Giao diện điện ảnh, tốc độ nhanh, trải nghiệm liền mạch.

---

## Tính Năng Nổi Bật

```markdown
-------------------------
🌟 Danh sách phim động: Xem phim mới, Anime, Hành Động, Hoa Ngữ.
🌟 Lọc phim thông minh: Theo loại, thể loại, quốc gia, năm phát hành.
🌟 Tìm kiếm tức thì: Kết quả nhanh, phân trang (20 phim/trang).
🌟 Responsive: Tối ưu cho PC, tablet, điện thoại.
🌟 Hiệu ứng mượt: Slider tự cuộn, hover, spinner loading.
🌟 Chi tiết phim: Poster, thời lượng, ngôn ngữ, chất lượng.
-------------------------
```

---

## Cài Đặt

```markdown
=====================
🛠 Yêu cầu:
  - Node.js v14.x+
  - npm v6.x+
  - Git
🛠 Bước thực hiện:
  1. Clone: git clone https://github.com/DangTruongDuong/Movie.git
  2. Vào thư mục: cd vuephim
  3. Cài thư viện: npm install
  4. Chạy: npm run serve
  5. Truy cập: http://localhost:8080
=====================
```

---

## Hướng Dẫn Sử Dụng

```markdown
-------------------------
📖 Khám phá phim:
  - Trang chủ: Xem Phim Mới, Anime, Hoa Ngữ qua slider.
📖 Lọc phim:
  - Vào "Danh Sách Phim", chọn loại, thể loại, quốc gia, năm.
📖 Tìm kiếm:
  - Nhập từ khóa vào ô tìm kiếm trên navbar.
📖 Chi tiết phim:
  - Nhấn "Xem phim" để vào /movie/:slug.
-------------------------
```

---

## Công Nghệ Sử Dụng

| Công Nghệ     | Phiên Bản | Mục Đích            |
|---------------|-----------|---------------------|
| Vue.js        | 3.x       | Framework front-end |
| JavaScript    | ES6+      | Logic chính         |
| Axios         | 0.21.x    | Gọi API            |
| Vue Router    | 4.x       | Điều hướng SPA      |
| CSS3          | -         | Giao diện, hiệu ứng |

---

## Cấu Trúc Dự Án

| Thư Mục/File         | Mô Tả                           |
|----------------------|---------------------------------|
| `src/components/Trang-Chu.vue` | Trang chủ, slider, danh sách phim |
| `src/components/Danh-Sach-Phim.vue` | Danh sách phim, bộ lọc, tìm kiếm |
| `src/components/Navbar.vue`   | Thanh điều hướng                |
| `src/router/`        | Cấu hình Vue Router             |
| `src/App.vue`        | Component gốc                   |

---

## Đóng Góp

```markdown
=====================
🤝 Hướng dẫn:
  1. Fork repository.
  2. Tạo nhánh: git checkout -b feature/ten-tinh-nang
  3. Commit: git commit -m "Thêm XYZ"
  4. Push: git push origin feature/ten-tinh-nang
  5. Tạo Pull Request.
=====================
```

---

## Giấy Phép

Dự án sử dụng [Giấy phép MIT](LICENSE). Tự do sử dụng, chỉnh sửa, phân phối.

---

## Liên Hệ

```markdown
-------------------------
📬 Tác giả: [Đặng Trường Dương]
📬 Email: Dangtruongduong2102@gmail.com
📬 GitHub: [DangTruongDuong](https://github.com/DangTruongDuong)
📬 Tài liệu tham khảo: Youtube Hiếu Tutorial with live project, Nguyễn thanh bình
-------------------------
```

**VuePhim** - Khám phá phim ảnh đỉnh cao! Thử ngay, để lại ⭐ trên GitHub! 😊

VuePhim 🎬

VuePhim là ứng dụng web hiện đại, được xây dựng bằng Vue.js, cho phép người dùng khám phá, tìm kiếm và lọc phim từ API PhimAPI. Với giao diện responsive, hiệu ứng mượt mà và trải nghiệm người dùng tuyệt vời, VuePhim mang đến thế giới phim ảnh ngay trong tầm tay bạn! 🚀

Giới Thiệu
VuePhim là một nền tảng front-end dành cho người yêu phim, tích hợp API mạnh mẽ để hiển thị danh sách phim đa dạng theo thể loại, quốc gia và năm phát hành. Ứng dụng được thiết kế với giao diện trực quan, tốc độ tải nhanh, và hỗ trợ mọi thiết bị từ PC đến di động.
Tại sao chọn VuePhim?

Giao diện đẹp mắt, phong cách điện ảnh.
Bộ lọc phim thông minh, tìm kiếm tức thì.
Tối ưu hiệu suất với Vue.js và Axios.


Tính Năng Nổi Bật 🌟

Danh Sách Phim Động: Xem phim mới, phim theo thể loại (Hành Động, Anime, Tình Cảm) hoặc quốc gia (Việt Nam, Trung Quốc, Mỹ).
Lọc Phim Nâng Cao: Lựa chọn phim theo loại (Phim lẻ, Phim bộ), thể loại, quốc gia, và năm phát hành.
Tìm Kiếm Thông Minh: Tìm phim nhanh chóng với từ khóa, hiển thị tối đa 20 phim mỗi trang.
Giao Diện Responsive: Hoạt động hoàn hảo trên mọi thiết bị: PC, tablet, điện thoại.
Hiệu Ứng Mượt Mà: Slider tự cuộn, hiệu ứng hover, spinner loading đẹp mắt.
Chi Tiết Phim: Xem thông tin phim như poster, thời lượng, ngôn ngữ, chất lượng.


Hình Ảnh Minh Họa

Thêm GIF hoặc ảnh chụp màn hình để làm nổi bật giao diện!Ví dụ:Để thêm GIF, ghi lại thao tác (dùng ScreenToGif) và upload vào docs/demo.gif.


Cài Đặt 🛠
Yêu Cầu

Node.js: v14.x trở lên
npm: v6.x trở lên
Git: Để clone repository

Hướng Dẫn

Clone Repository  
git clone https://github.com/your-username/vuephim.git
cd vuephim


Cài Đặt Thư Viện  
npm install


Chạy Ứng Dụng  
npm run serve


Truy CậpMở trình duyệt và vào http://localhost:8080.



Hướng Dẫn Sử Dụng 📖

Khám Phá Phim  

Trang chủ hiển thị các danh mục phim nổi bật: Phim Mới, Anime, Phim Hoa Ngữ.
Dùng slider tự cuộn để xem phim hot.


Lọc Phim  

Vào trang Danh Sách Phim từ thanh điều hướng.
Chọn bộ lọc:
Loại: Phim lẻ, Phim bộ, Hoạt hình.
Thể loại: Hành Động, Tình Cảm, Kinh Dị, v.v.
Quốc gia: Việt Nam, Trung Quốc, Hàn Quốc, v.v.
Năm phát hành: 1970 đến nay.


Nhấn Lọc phim để xem kết quả.


Tìm Kiếm  

Nhập từ khóa vào ô tìm kiếm trên navbar.
Duyệt kết quả với phân trang (20 phim/trang).


Xem Chi Tiết  

Nhấn Xem phim trên thẻ phim để vào trang chi tiết (/movie/:slug).




Công Nghệ Sử Dụng 💻



Công Nghệ
Phiên Bản
Mục Đích



Vue.js
3.x
Framework front-end


JavaScript
ES6+
Lập trình logic


Axios
0.21.x
Gọi API HTTP


Vue Router
4.x
Điều hướng SPA


CSS3
-
Thiết kế giao diện, hiệu ứng



Cấu Trúc Dự Án 📂
vuephim/
├── public/                 # Tài nguyên tĩnh (favicon, index.html)
├── src/                    # Mã nguồn chính
│   ├── assets/             # Hình ảnh, CSS toàn cục
│   ├── components/         # Các component Vue
│   │   ├── HomePage.vue    # Trang chủ (slider, danh sách phim)
│   │   ├── MovieList.vue   # Trang danh sách phim (lọc, tìm kiếm)
│   │   └── Navbar.vue      # Thanh điều hướng
│   ├── router/             # Cấu hình Vue Router
│   └── App.vue             # Component gốc
├── package.json            # Dependencies và scripts
└── README.md               # Tài liệu này


Đóng Góp 🤝
Chúng tôi rất mong nhận được đóng góp từ cộng đồng! Để tham gia:

Fork repository này.
Tạo nhánh mới:  git checkout -b feature/ten-tinh-nang


Commit thay đổi:  git commit -m "Thêm tính năng XYZ"


Push lên nhánh:  git push origin feature/ten-tinh-nang


Tạo Pull Request trên GitHub.


Giấy Phép 📜
Dự án được phát hành dưới Giấy phép MIT. Bạn có thể tự do sử dụng, chỉnh sửa và phân phối.

Liên Hệ 📬

Tác giả: [Your Name]  
Email: your.email@example.com  
GitHub: your-username

VuePhim được tạo ra để mang niềm vui xem phim đến mọi người! Hãy thử ngay, để lại một ⭐ trên GitHub nếu bạn thích, và chia sẻ ý tưởng để cải thiện dự án! 😊

Ứng Dụng Xem Phim Vue 🎥

Một ứng dụng web hiện đại, responsive được xây dựng bằng Vue.js để khám phá, lọc và tìm kiếm phim sử dụng PhimAPI. Trải nghiệm giao diện mượt mà với hiệu ứng đẹp mắt và cảm giác điện ảnh! 🚀

📖 Giới Thiệu
Ứng Dụng Xem Phim Vue là một ứng dụng front-end được thiết kế dành cho những người yêu thích phim ảnh, giúp khám phá danh sách phim từ mới nhất đến các thể loại và quốc gia cụ thể. Sử dụng Vue.js và tích hợp với PhimAPI, ứng dụng mang đến trải nghiệm duyệt phim liền mạch với bộ lọc nâng cao và giao diện responsive.
🎯 Mục tiêu: Cung cấp một nền tảng trực quan để người dùng khám phá phim với giao diện đẹp, dễ sử dụng.

🌟 Tính Năng

🎬 Danh Sách Phim Động: Xem phim theo danh mục (Anime, Hành Động, Hoa Ngữ, v.v.) với dữ liệu thời gian thực từ API.
🔍 Lọc Phim Nâng Cao: Lọc phim theo loại, thể loại, quốc gia và năm phát hành.
🔎 Tìm Kiếm Nhanh: Tìm phim bằng từ khóa với kết quả tức thì.
📱 Responsive Design: Tối ưu cho máy tính, máy tính bảng và điện thoại.
✨ Hiệu Ứng Mượt Mà: Hiệu ứng hover, spinner loading, slider tự động cuộn.
🖼️ Thông Tin Phim: Xem poster, thời lượng, ngôn ngữ và chất lượng phim.
🧭 Điều Hướng Dễ Dàng: Trải nghiệm SPA với Vue Router.
⚡ Tải Nhanh: Tối ưu hóa API với Axios và Promise.all để gọi song song.


📸 Demo

Lưu ý: Thêm link demo hoặc GIF để giới thiệu ứng dụng!Ví dụ: Live DemoGIF minh họa:


🛠️ Cài Đặt
Làm theo các bước sau để chạy dự án trên máy local.
Yêu Cầu

💻 Node.js (phiên bản 14.x trở lên)
📦 npm (phiên bản 6.x trở lên)
🖥️ Git

Các Bước

Clone Repository  
git clone https://github.com/your-username/vue-movie-app.git
cd vue-movie-app


Cài Đặt Dependencies  
npm install


Chạy Server Phát Triển  
npm run serve


Mở Trong Trình DuyệtTruy cập http://localhost:8080 để xem ứng dụng! 🌐



🎮 Hướng Dẫn Sử Dụng

Duyệt Phim  

Trên trang chủ, khám phá các phần như Phim Mới, Anime Mới, Phim Hoa Ngữ, v.v.
Sử dụng slider tự cuộn để xem các phim nổi bật.


Lọc Phim  

Chuyển đến trang Danh Sách Phim qua thanh điều hướng.
Sử dụng các bộ lọc:
Loại Phim: Phim lẻ, Phim bộ, Hoạt hình, TV Shows.
Thể Loại: Hành Động, Tình Cảm, Kinh Dị, v.v.
Quốc Gia: Việt Nam, Trung Quốc, Mỹ, v.v.
Năm: Từ 1970 đến nay.


Nhấn Lọc phim để áp dụng bộ lọc.


Tìm Kiếm Phim  

Nhập từ khóa vào ô tìm kiếm trên thanh điều hướng.
Xem tối đa 20 phim mỗi trang với phân trang.


Xem Chi Tiết Phim  

Nhấn Xem phim trên thẻ phim để vào trang chi tiết (/movie/:slug).




🧑‍💻 Công Nghệ Sử Dụng



Công Nghệ
Phiên Bản
Mục Đích




3.x
Framework front-end



ES6+
Lập trình chính



0.21.x
Gọi API HTTP



4.x
Điều hướng SPA



3
Giao diện và hiệu ứng



📂 Cấu Trúc Dự Án
vue-movie-app/
├── public/                 # Tài nguyên tĩnh (favicon, index.html)
├── src/                    # Mã nguồn chính
│   ├── assets/             # Hình ảnh, CSS toàn cục
│   ├── components/         # Các component Vue
│   │   ├── HomePage.vue    # Trang chủ với slider và danh sách phim
│   │   ├── MovieList.vue   # Trang danh sách phim với bộ lọc
│   │   ├── RightSection.vue # Component bên phải trang chủ
│   │   └── Navbar.vue      # Thanh điều hướng
│   ├── router/             # Cấu hình Vue Router
│   └── App.vue             # Component gốc
├── package.json            # Dependencies và scripts
└── README.md               # Tài liệu này


🤝 Đóng Góp
Chúng tôi hoan nghênh mọi đóng góp để cải thiện dự án! Để tham gia:

Fork repository.
Tạo nhánh mới:  git checkout -b feature/ten-tinh-nang


Commit thay đổi:  git commit -m "Thêm tính năng XYZ"


Push lên nhánh:  git push origin feature/ten-tinh-nang


Tạo Pull Request trên GitHub.

Vui lòng đọc Hướng Dẫn Đóng Góp (nếu có) để biết thêm chi tiết.

📜 Giấy Phép
Dự án được cấp phép theo MIT License. Bạn có thể tự do sử dụng, chỉnh sửa và phân phối.

📬 Liên Hệ

Tác giả: [Tên bạn] (Thay bằng tên thật hoặc biệt danh)
Email: your.email@example.com
GitHub: your-username

Cảm ơn bạn đã quan tâm đến Ứng Dụng Xem Phim Vue! Nếu bạn thích dự án, hãy để lại một ⭐ trên GitHub! 😊

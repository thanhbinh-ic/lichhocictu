# Lịch Học Thông Minh (Smart Schedule)

**Lịch Học Thông Minh** là một ứng dụng web dạng PWA (Progressive Web App) gọn nhẹ, giao diện hiện đại, giúp sinh viên tra cứu, quản lý và theo dõi lịch học cá nhân một cách trực quan. Ứng dụng hỗ trợ trích xuất dữ liệu tự động từ cổng thông tin đào tạo sinh viên (đặc biệt tối ưu cho hệ thống `sinhvien.ictu.edu.vn`).

---

[![Vercel App](https://img.shields.io/badge/LIVE_DEMO-VERCEL_APP-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://lichhocictu.vercel.app/)

---

## Tính năng nổi bật

- ** Nhập lịch học đa dạng:**
  - **Dán mã HTML:** Copy trực tiếp toàn bộ nguồn trang HTML chứa bảng lịch học từ portal sinh viên và dán vào ứng dụng.
  - **Tải tệp tin (.txt / .html):** Hỗ trợ chọn và đọc trực tiếp file lưu lịch học từ bộ nhớ thiết bị.
- ** Hiển thị trực quan linh hoạt:**
  - **Thanh cuộn 7 ngày (Ribbon View):** Xem nhanh danh sách các ngày trong tuần hiện tại kèm chấm báo hiệu ngày có lịch học.
  - **Lịch tháng mở rộng (Accordion Calendar):** Lịch tháng tích hợp ngay trên thanh header, giúp chuyển đổi và chọn ngày nhanh chóng.
  - **Lọc theo ngày/tuần:** Dễ dàng lọc môn học theo ngày được chọn hoặc xem toàn bộ môn học trong tuần.
- ** Tùy chỉnh giờ tiết học:**
  - Cho phép cấu hình chi tiết khung giờ bắt đầu/kết thúc của từng tiết học.
  - Tích hợp sẵn mẫu **Giờ mùa hè** và **Giờ mùa đông**.
  - Kiểm tra và cảnh báo logic thời gian thông minh (tránh đè chồng khung giờ).
- ** Giao diện & Trải nghiệm (UX/UI):**
  - **3 chế độ giao diện:** Tự động (theo hệ thống) / Sáng (Light) / Tối (Dark Mode).
  - Tự động phân phối bảng màu phân biệt giữa các môn học.
  - Tương thích hoàn hảo với màn hình di động (iOS Safari & Android PWA support).
- ** Đồng bộ & Lưu trữ:**
  - Lưu dữ liệu lịch học và cấu hình thời gian tự động vào `localStorage` của trình duyệt, không lo mất dữ liệu khi làm mới trang.

---

## Công nghệ sử dụng

- **HTML5 & CSS3**: Cấu trúc ứng dụng và định dạng chuẩn Responsive.
- **Tailwind CSS (CDN)**: Framework CSS Utility-first cho giao diện hiện đại, tối ưu Dark Mode.
- **FontAwesome 6**: Hệ thống icon phong phú.
- **Google Fonts**: Font chữ *Plus Jakarta Sans* chuẩn hiển thị giao diện di động.
- **Vanilla JavaScript (ES6+)**: Xử lý logic đọc DOM HTML, DOMParser, FileReader API, quản lý `localStorage` và chuyển đổi chủ đề (Theme Switcher).

---

## Hướng dẫn cài đặt & Sử dụng

### 1. Sử dụng trực tiếp
Ứng dụng hoàn toàn chạy ở phía Client (Trình duyệt), không cần backend.
1. Tải tệp `index.html` (hoặc mở trực tiếp file HTML dự án).
2. Mở tệp bằng bất kỳ trình duyệt web nào (Chrome, Safari, Edge, Firefox,...).

### 2. Cách nhập lịch học
1. Truy cập trang tra cứu lịch học của trường (Ví dụ: `sinhvien.ictu.edu.vn/TraCuuLichHoc/Index`).
2. Nhấn `Ctrl + U` (trên máy tính) hoặc lưu trang về dưới dạng file `.html` / `.txt`.
3. Mở ứng dụng **Lịch Học Thông Minh** $\rightarrow$ Chọn **Nhập lịch học** (biểu tượng tệp tin/dán trên thanh tiêu đề):
   - **Cách 1:** Chọn **"Chọn file..."** và tải tệp `.txt` hoặc `.html` đã lưu từ máy.
   - **Cách 2:** Copy mã HTML chứa bảng lịch học và dán vào ô văn bản, sau đó nhấn **Trích xuất & Hiển thị**.

---

## Cấu hình tùy chọn

- **Chuyển đổi Chế độ Tối/Sáng:** Nhấn vào biểu tượng nửa hình tròn trên thanh Header để luân chuyển giữa các chế độ `Tự động System` $\rightarrow$ `Giao diện Sáng` $\rightarrow$ `Giao diện Tối`.
- **Cài đặt giờ tiết học:** Nhấn vào biểu tượng bộ lọc (Sliders) trên Header để điều chỉnh giờ từng tiết hoặc áp dụng nhanh mẫu giờ Mùa hè / Mùa đông.

---

## Giấy phép (License)

Dự án được phát triển nhằm mục đích phi thương mại, hỗ trợ cộng đồng sinh viên. Bạn có thể tự do chỉnh sửa và tùy biến mã nguồn theo nhu cầu cá nhân.

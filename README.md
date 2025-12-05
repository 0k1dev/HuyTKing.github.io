# 🏨 HỆ THỐNG QUẢN LÝ KHÁCH SẠN HOTEL HUYTKING

## 📋 Giới thiệu
Đồ án **Hệ thống quản lý khách sạn Hotel HKT** được phát triển để quản lý toàn diện các hoạt động của khách sạn, từ đặt phòng, check-in/out, thanh toán đến quản lý khách hàng và báo cáo.

## ✅ TÍNH NĂNG ĐÃ HOÀN THÀNH

### 🎯 Quản lý phòng
- [x] Hiển thị danh sách phòng với trạng thái trực quan
- [x] Thêm/sửa/xóa thông tin phòng
- [x] Phân loại phòng (Standard, Deluxe, Suite, VIP)
- [x] Quản lý giá phòng theo loại

### 📅 Quản lý đặt phòng
- [x] Đặt phòng trực tuyến
- [x] Check-in/Check-out tự động
- [x] Tính toán hóa đơn tự động
- [x] Quản lý lịch đặt phòng

### 👥 Quản lý khách hàng
- [x] Lưu trữ thông tin khách hàng
- [x] Lịch sử đặt phòng
- [x] Tìm kiếm khách hàng nhanh

### 💰 Quản lý thanh toán
- [x] Tính toán tự động giá phòng + dịch vụ
- [x] In hóa đơn chuyên nghiệp
- [x] Quản lý các phương thức thanh toán
- [x] Lịch sử thanh toán

### 📊 Báo cáo & Thống kê
- [x] Doanh thu theo ngày/tuần/tháng
- [x] Tỷ lệ lấp đầy phòng
- [x] Báo cáo khách hàng thường xuyên
- [x] Thống kê dịch vụ

### 👨‍💼 Phân quyền người dùng
- [x] Quản trị viên (Admin)
- [x] Lễ tân (Receptionist)

## 🛠 CÔNG NGHỆ SỬ DỤNG

### Frontend
- HTML5, CSS3, JavaScript
- Bootstrap 5
- Font Awesome icons
- Chart.js cho biểu đồ

### Backend
- PHP 8.x
- MySQL/SQLite Database
- RESTful API

### Development Tools
- XAMPP/WAMP Server
- Visual Studio Code
- Git & GitHub
- PHPDesktop (cho phiên bản portable)

```
📁 CẤU TRÚC DỰ ÁN
hotel-hkt/
├── api/ # API endpoints
├── assets/ # CSS, JS, images
├── config/ # Cấu hình database
├── models/ # Model PHP
├── views/ # Giao diện người dùng
│ ├── auth/ # Đăng nhập, đăng ký
│ ├── dashboard/ # Trang tổng quan
│ ├── rooms/ # Quản lý phòng
│ ├── bookings/ # Quản lý đặt phòng
│ ├── customers/ # Quản lý khách hàng
│ └── payments/ # Quản lý thanh toán
├── database.sql # Schema database
├── index.php # Router chính
└── README.md # Tài liệu dự án
```

## 🚀 HƯỚNG DẪN CÀI ĐẶT

### Cách 1: Chạy với XAMPP
1. Copy thư mục `hotel-hkt` vào `C:\xampp\htdocs\`
2. Khởi động XAMPP (Apache & MySQL)
3. Import file `database.sql` vào phpMyAdmin
4. Truy cập: `http://localhost/hotel-hkt/`

### Cách 2: Chạy Portable (không cần cài đặt)
1. Tải file `HotelHUYTKING-Portable.exe`
2. Chạy file, hệ thống tự động khởi động
3. Truy cập: `http://127.0.0.1:55000/`

### Cách 3: Chạy từ GitHub

# Clone repository
git clone https://github.com/0k1dev/HuyTKing.github.io
cd hotel-HKT

# Hoặc tải file ZIP
# Giải nén và chạy với XAMPP


## 🔐 THÔNG TIN ĐĂNG NHẬP MẶC ĐỊNH

### Quản trị viên
- **Quyền:** Full system access
- **Quyền:** Quản lý thanh toán, hóa đơn

## 🧪 KIỂM THỬ ĐÃ THỰC HIỆN

### Kiểm thử chức năng
- [x] Đăng nhập/đăng xuất
- [x] CRUD phòng
- [x] Đặt phòng & tính tiền
- [x] Check-in/Check-out
- [x] In hóa đơn
- [x] Phân quyền người dùng

### Kiểm thử hiệu năng
- [x] Tải trang < 2 giây
- [x] Xử lý 100+ bản ghi
- [x] Responsive trên mobile

### Kiểm thử bảo mật
- [x] SQL Injection prevention
- [x] XSS protection
- [x] Session management
- [x] Password hashing

## 👥 THÀNH VIÊN NHÓM

| STT | Họ và Tên | MSSV | Vai trò | Trường Đại Học|
|-----|-----------|------|---------|---------|
| 1 | Đinh Tấn Huy| QE200063 | Leader, Full Stack |FPTU - Quy Nhơn|

## 📅 TIẾN ĐỘ DỰ ÁN

### Giai đoạn 1: Phân tích & Thiết kế (Tuần 1-2)
- [x] Phân tích yêu cầu
- [x] Thiết kế database
- [x] Wireframe giao diện

### Giai đoạn 2: Phát triển (Tuần 3-6)
- [x] Backend API
- [x] Frontend giao diện
- [x] Kết nối database

### Giai đoạn 3: Kiểm thử (Tuần 7)
- [x] Unit testing
- [x] Integration testing
- [x] User acceptance testing

### Giai đoạn 4: Hoàn thiện (Tuần 8)
- [x] Fix bugs
- [x] Tối ưu hóa
- [x] Đóng gói sản phẩm

## 🎯 KẾT QUẢ ĐẠT ĐƯỢC

### Về mặt kỹ thuật
✅ **Hoàn thành 100%** các tính năng yêu cầu  
✅ **Database** được thiết kế tối ưu, chuẩn hóa  
✅ **Giao diện** thân thiện, responsive  
✅ **Hiệu năng** tốt, tải nhanh  
✅ **Bảo mật** đảm bảo  

### Về mặt học thuật
✅ **Áp dụng** kiến thức PHP, MySQL, HTML/CSS/JS  
✅ **Thực hành** quy trình phát triển phần mềm  
✅ **Rèn luyện** kỹ năng làm việc nhóm  
✅ **Hoàn thành** đúng thời hạn  

## 📞 HỖ TRỢ & LIÊN HỆ

### Giảng viên hướng dẫn
**Thầy/Cô:** 
**Email:**   
**Điện thoại:** 

### Nhóm phát triển
**Email:** dinhtanhuy547@gmail.com 
**GitHub:** https://github.com/0k1dev/HuyTKing.github.io  
**Website:** chạy ở local

## 📄 GIẤY PHÉP
Dự án được phát triển cho mục đích học tập.  
© 2025 Hotel HUYTKING Management System. All rights reserved.

## 🙏 LỜI CẢM ƠN
Xin chân thành cảm ơn:
- **Giảng viên hướng dẫn** đã tận tình chỉ bảo
- **Thầy/Cô bộ môn** đã cung cấp kiến thức nền tảng
- **Các bạn trong nhóm** đã cùng nhau nỗ lực hoàn thành
- **Gia đình** đã hỗ trợ và động viên

---

**🎉 ĐỒ ÁN ĐÃ HOÀN THÀNH THÀNH CÔNG!**  
*Cám ơn mọi người đã theo dõi và ủng hộ!* 🎊
```

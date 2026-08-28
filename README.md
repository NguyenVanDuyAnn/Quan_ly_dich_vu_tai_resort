> Website quản lý dịch vụ tại Resort được xây dựng bằng **PHP và MySQL**, hỗ trợ quản lý thông tin Resort, khách hàng, nhân viên và các dịch vụ liên quan.

## 📌 Giới thiệu

**Hệ thống quản lý dịch vụ tại Resort** là một ứng dụng web được xây dựng nhằm hỗ trợ quản lý và tổ chức các thông tin liên quan đến hoạt động của Resort.

Hệ thống tập trung vào việc quản lý các đối tượng chính như **Resort, khách hàng, nhân viên và dịch vụ**, đồng thời cung cấp các chức năng quản lý tài khoản, đánh giá và xử lý dữ liệu địa chỉ.

## 🎯 Mục tiêu dự án

* Xây dựng hệ thống quản lý thông tin Resort trên nền tảng web.
* Quản lý tập trung thông tin khách hàng và nhân viên.
* Quản lý thông tin Resort và các dịch vụ.
* Thực hiện các thao tác **CRUD** đối với dữ liệu.
* Xây dựng và sử dụng cơ sở dữ liệu quan hệ với **MySQL**.
* Áp dụng **AJAX** để xử lý việc lấy dữ liệu địa chỉ động.
* Xây dựng các chức năng liên quan đến tài khoản người dùng.
## 📸 Giao diện hệ thống

### Giao diện đăng ký
<img width="429" height="653" alt="image" src="https://github.com/user-attachments/assets/ec849fb0-e756-4266-9d1d-30b708dfb76d" />

### 🏠 Trang chủ
<img width="585" height="264" alt="image" src="https://github.com/user-attachments/assets/a636a1ed-6302-4554-823c-7318a8cc4a8e" />

### Giao diện đăng nhập

<img width="471" height="440" alt="image" src="https://github.com/user-attachments/assets/e13cc31d-5a8c-44cc-b427-5c7dc38b79e2" />

### Giao diện tìm kiếm
<img width="589" height="316" alt="image" src="https://github.com/user-attachments/assets/7a073324-0d80-4cb4-91cb-837626b53c8c" />

### Giao diện đánh giá phản hồi
<img width="586" height="219" alt="image" src="https://github.com/user-attachments/assets/c7bfe8ad-5f24-430f-8420-8b205b5e0eff" />

### Giao diện thông tin cá nhân
<img width="603" height="278" alt="image" src="https://github.com/user-attachments/assets/f87932e6-bda4-428e-9824-1f481e371d27" />

### Giao diện giao dịch
<img width="605" height="240" alt="image" src="https://github.com/user-attachments/assets/9abbeef3-bb1a-4d60-8bda-afb8828f9b84" />



## 🛠️ Công nghệ sử dụng

| Công nghệ      | Mục đích                         |
| -------------- | -------------------------------- |
| **PHP**        | Xây dựng chức năng phía máy chủ  |
| **MySQL**      | Quản lý cơ sở dữ liệu            |
| **HTML5**      | Xây dựng cấu trúc giao diện      |
| **CSS3**       | Thiết kế giao diện               |
| **JavaScript** | Xử lý tương tác phía trình duyệt |
| **AJAX**       | Lấy và cập nhật dữ liệu động     |

## ✨ Chức năng chính

### 🏨 Quản lý Resort

* Xem danh sách Resort
* Xem thông tin chi tiết Resort
* Thêm Resort
* Chỉnh sửa thông tin Resort
* Quản lý thông tin Resort

### 👤 Quản lý khách hàng

* Xem thông tin khách hàng
* Thêm khách hàng
* Chỉnh sửa thông tin khách hàng
* Xem chi tiết khách hàng
* Cập nhật thông tin khách hàng

### 👨‍💼 Quản lý nhân viên

* Xem thông tin nhân viên
* Thêm nhân viên
* Chỉnh sửa thông tin nhân viên
* Xem chi tiết nhân viên

### 🛎️ Quản lý dịch vụ

* Quản lý thông tin dịch vụ
* Thêm và cập nhật thông tin dịch vụ
* Hiển thị thông tin dịch vụ

### ⭐ Đánh giá

* Hỗ trợ chức năng đánh giá.
* Quản lý dữ liệu đánh giá của khách hàng.

### 📍 Quản lý địa chỉ

Hệ thống hỗ trợ xử lý dữ liệu địa chỉ theo cấp:

* Tỉnh / Thành phố
* Quận / Huyện
* Phường / Xã

AJAX được sử dụng để lấy dữ liệu địa chỉ tương ứng khi người dùng lựa chọn.

### 🔐 Quản lý tài khoản

* Đăng nhập
* Đăng xuất
* Đổi mật khẩu
* Đặt lại mật khẩu

## 🗄️ Cơ sở dữ liệu

Hệ thống sử dụng **MySQL** để lưu trữ và quản lý dữ liệu.

File cơ sở dữ liệu được cung cấp trong repository:

```text
quanly_resort.sql
```

Có thể sử dụng file này để tạo cơ sở dữ liệu và các bảng cần thiết cho hệ thống.

## 📂 Cấu trúc dự án

```text
Quan_ly_dich_vu_tai_resort/
│
├── ajax_get_district.php
├── ajax_get_wards.php
├── get_district.php
├── get_province.php
├── get_wards.php
│
├── ql_resort.php
├── them_resort.php
├── edit_resort.php
├── detail_resort.php
│
├── ThemKH.php
├── editkh.php
├── detailKH.php
├── capnhat_kh.php
│
├── ThemNV.php
├── editNV.php
├── detailNV.php
│
├── danhgia.php
├── change_password.php
├── password_resets.php
├── dangxuat.php
│
├── header.php
├── footer.php
│
├── quanly_resort.sql
└── ...
```

## ⚙️ Cài đặt và chạy dự án

### 1. Chuẩn bị môi trường

Cài đặt các công cụ cần thiết:

* PHP
* MySQL
* Apache hoặc XAMPP
* Trình duyệt web

### 2. Đưa source code vào Web Server

Nếu sử dụng XAMPP, đặt project vào:

```text
C:\xampp\htdocs\Quan_ly_dich_vu_tai_resort
```

Sau đó khởi động **Apache** và **MySQL** trong XAMPP.

### 3. Tạo cơ sở dữ liệu

Mở **phpMyAdmin** và:

1. Tạo database.
2. Import file:

```text
quanly_resort.sql
```

3. Kiểm tra các bảng đã được tạo thành công.

### 4. Cấu hình kết nối MySQL

Kiểm tra file PHP chứa thông tin kết nối cơ sở dữ liệu và cập nhật các thông tin phù hợp với môi trường trên máy.

```text
Host: localhost
Database: quany_resort.sql
```

## 📚 Kiến thức áp dụng

Thông qua dự án, các kiến thức sau được áp dụng:

* Lập trình web với PHP
* Cơ sở dữ liệu MySQL
* SQL và quản lý dữ liệu quan hệ
* CRUD
* Xử lý Form
* Quản lý Session và tài khoản
* AJAX
* JavaScript
* Kết nối giữa Frontend và Backend
* Xây dựng ứng dụng web sử dụng cơ sở dữ liệu

## 👨‍💻 Tác giả

**Nguyễn Văn Duy An**

⭐ Cảm ơn bạn đã quan tâm đến dự án!

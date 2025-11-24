# 📚 Electronic Bookstore Management System

> Hệ thống kinh doanh sách điện tử (Đồ án môn Phân tích & Thiết kế phần mềm).

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)

## 👥 Thành viên nhóm 7
| STT | Thành viên | Vai trò |
|-----|------------|---------|
| 1 | Dương Nhật Minh (Leader) | Fullstack, Quản lý chung |
| 2 | Nguyễn Thị Kiều Loan | Frontend, Tài liệu |
| 3 | **Hà Nam Khánh** | **Backend (Product/Cart), Database** |
| 4 | Đoàn Tiến Dũng | Tester, Tài liệu |

## 🚀 Tính năng chính

###👤 Khách Hàng (User)
Đăng ký, đăng nhập
Tìm kiếm sách, xem chi tiết sách
Thêm vào giỏ hàng, đặt hàng, thanh toán
Theo dõi trạng thái đơn hàng, hủy đơn hàng
###🛠️ Quản Trị Viên (Admin)
Quản lý sản phẩm: thêm, xóa, cập nhật sách
Quản lý đơn hàng: xem danh sách, xác nhận, hủy
Quản lý người dùng: khóa/mở khóa tài khoản
###📦 Thủ Kho (Store Keeper)
Xem danh sách hàng tồn kho
Cập nhật số lượng sách
Xem danh sách đơn hàng đã xác nhận
Xác nhận vận chuyển đơn hàng

###🚚 Người giao hàng (Shipper)
* **Vận đơn:** Xem danh sách đơn hàng được phân công.
* **Cập nhật trạng thái:** Chuyển trạng thái đơn hàng (Đang giao -> Giao thành công/Thất bại).

## 🛠 Công nghệ
* **Backend:** Spring Boot (MVC), Hibernate, Spring Data JPA.
* **Frontend:** Thymeleaf, Bootstrap 5.
* **Database:** MySQL (Có sử dụng Redis để cache).
* **Tools:** IntelliJ IDEA, Visual Paradigm (UML), Git.

## ⚙️ Cài đặt
1. Clone repo: `git clone https://github.com/Tobii1707/Web-quan-ly-thu-vien.git`
2. Import database: Chạy file `bookstore.sql` trong MySQL.
3. Cấu hình: Sửa file `application.properties` (username/password MySQL).
4. Run: Chạy `BookStoreApplication.java`.

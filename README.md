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

### 🛒 Khách hàng (User)
* **Mua sắm:** Tìm kiếm, lọc sách, quản lý giỏ hàng và thanh toán (Checkout).
* **Cá nhân:** Theo dõi lịch sử đơn hàng, cập nhật thông tin tài khoản.

### 🛠 Quản trị viên (Admin)
* **Dashboard:** Thống kê doanh thu, số lượng sách bán ra, quản lý tài khoản nhân viên.
* **Dữ liệu:** Quản lý danh mục sách, giá bán và chương trình khuyến mãi.

### 📦 Thủ kho (Inventory Manager)
* **Quản lý nhập hàng:** Tạo phiếu nhập sách, cập nhật số lượng tồn kho thực tế.
* **Kiểm kê:** Theo dõi sách sắp hết hàng để đề xuất nhập thêm.

### 🚚 Người giao hàng (Shipper)
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

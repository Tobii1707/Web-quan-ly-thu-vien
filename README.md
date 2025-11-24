# 📚 Electronic Bookstore Management System

> Hệ thống quản lý và kinh doanh sách điện tử trực tuyến. Đồ án môn Phân tích và Thiết kế Phần mềm - Đại học Phenikaa.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

## 📖 Giới thiệu
Dự án xây dựng một nền tảng thương mại điện tử phục vụ việc mua bán sách. Hệ thống áp dụng quy trình phát triển phần mềm chuẩn (Waterfall/Agile), tập trung vào việc phân tích yêu cầu, thiết kế hệ thống (UML) và hiện thực hóa bằng công nghệ Java Spring Boot.

## 🚀 Tính năng chính

### 🛒 Khách hàng (User)
* **Duyệt sản phẩm:** Tìm kiếm sách theo tên, tác giả, thể loại, khoảng giá.
* **Giỏ hàng (Shopping Cart):** Thêm/sửa/xóa sách trong giỏ, tự động tính tổng tiền.
* **Đặt hàng (Checkout):** Xử lý đơn hàng, lưu thông tin giao nhận.

### 🛠 Quản trị viên (Admin)
* **Quản lý Kho sách:** CRUD (Thêm, Xem, Sửa, Xóa) sách, cập nhật số lượng tồn kho.
* **Quản lý Danh mục:** Phân loại sách để khách hàng dễ tìm kiếm.
* **Thống kê:** Xem báo cáo doanh thu, số lượng sách bán ra.

## 🛠 Công nghệ & Kỹ thuật
* **Backend:** Java, Spring Boot (MVC Architecture).
* **Frontend:** Thymeleaf, Bootstrap 5, HTML/CSS.
* **Database:** MySQL.
* **Optimization:**
    * Sử dụng **Redis** để cache dữ liệu sách bán chạy (tối ưu tốc độ tải).
    * Nén ảnh WebP để giảm dung lượng tải trang.
* **Tools:** IntelliJ IDEA, Visual Paradigm (Vẽ UML), Git.

## 👥 Thành viên thực hiện (Nhóm 7)
| STT | Họ và tên | Mã sinh viên | Vai trò chính |
|-----|-----------|--------------|---------------|
| 1 | Dương Nhật Minh | 22010366 | Nhóm trưởng, Fullstack |
| 2 | Nguyễn Thị Kiều Loan | 22010278 | Frontend, Document |
| 3 | **Hà Nam Khánh** | **22010149** | **Backend, Database** |
| 4 | Đoàn Tiến Dũng | 22010133 | Tester, Document |

## ⚙️ Cài đặt và Chạy

1.  **Clone dự án:**
    ```bash
    git clone [https://github.com/Tobii1707/Web-quan-ly-thu-vien.git](https://github.com/Tobii1707/Web-quan-ly-thu-vien.git)
    ```
2.  **Cấu hình Database:** Import file `bookstore_db.sql` vào MySQL.
3.  **Chạy ứng dụng:** Mở project bằng IntelliJ IDEA và chạy file `BookStoreApplication.java`.
4.  **Truy cập:** `http://localhost:8080`

---
*Phenikaa University - 2025*

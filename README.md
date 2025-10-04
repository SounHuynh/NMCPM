<img width="490" height="579" alt="use case" src="https://github.com/user-attachments/assets/af19a931-9360-4e46-b0ad-0be580d77865" /># 🛠️ Software Engineering Project 

## 📌 Giới thiệu
Dự án này được phát triển trong môn **Nhập môn Công nghệ Phần mềm**.  
Mục tiêu là áp dụng quy trình phát triển phần mềm, từ **phân tích yêu cầu, thiết kế, lập trình, kiểm thử và triển khai**.  

## 👥 Thành viên nhóm
- Họ tên 1 – Huỳnh Nhật Sơn_N23DCPT102

## 💻 Công nghệ sử dụng
- Ngôn ngữ: JavaScript/ HTML.
- IDE: Visual Studio Code, Notepad
- CSDL: MySQL 
- Quản lý phiên bản: Git + GitHub
- Mô hình phát triển: Agile – Scrum  


Software Engineering Lab 

Lab 01 – Thiết lập môi trường & Quản lý dự án trên GitHub
•	Mục tiêu: Sinh viên làm quen với GitHub, Git, và công cụ lập trình.
•	Nội dung:
o	Tạo tài khoản GitHub, tạo repository riêng cho môn học.
o	Cấu hình Git (clone, commit, push, pull).
o	Cập nhật profile cá nhân trên README.md.
o	Upload bài tập đơn giản: file text giới thiệu bản thân.

Lab 01: Đề tài 1 – Shopping Cart:

Các use case chính:
👤Admin:

Thêm sản phẩm

Sửa sản phẩm

Xóa sản phẩm

🛒 Người dùng (Customer):

Tìm kiếm sản phẩm

Thêm sản phẩm vào giỏ hàng

Xóa sản phẩm khỏi giỏ hàng

Thay đổi số lượng sản phẩm trong giỏ hàng

## 📐 Thiết kế hệ thống
- **Use Case Diagram**: ![Use Case](./docs/usecase.png)
- **Sequence Diagram**: ![Sequence](./docs/sequence.png)
- **ERD (Entity Relationship Diagram)**: ![ERD](./docs/erd.png)

Jira quản lí dự án: https://huynhnhatson-n23dcpt102.atlassian.net/jira/software/projects/SM/boards/5/timeline.
 
Lab 02 – Phân tích yêu cầu & Thiết kế Use Case

1.1 Entity (6 bảng dữ liệu chính)
• Guest (Khách hàng)
• RoomType (Loại phòng)
• Room (Phòng cụ thể)
• Reservation (Đặt phòng)
• Payment (Thanh toán)
• Staff (Nhân viên/Lễ tân/Quản lý)

Mối quan hệ:
• Guest 1–N Reservation
• Reservation 1–N Payment
• RoomType 1–N Room
• Room 1–N Reservation
• Staff 1–N Reservation (lễ tân quản lý)


1.2 Biểu đồ UML Use Case:


1.3 Sequence UML

a) Luồng Đặt phòng online:


b) Luồng Check-in/Check-out (Lễ tân):


1.4 Thiết kế cơ sở dữ liệu (ERD):





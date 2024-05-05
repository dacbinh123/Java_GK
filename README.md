# Java-MidTerm

Báo cáo giữa kỳ của Hoàng Đắc Bình - 52100163

## SpringCommerceEssence

### Problem Statement


#### 1. Giải thích ngắn gọn về các nguyên tắc, mô hình phát triển phần mềm và thực tiễn đang được áp dụng.

- Nguyên tắc SOLID: Đảm bảo rằng các lớp và phương thức được thiết kế để có tính kế thừa, đơn trách nhiệm và thực thi nguyên tắc mở hoặc đóng.
- Mô hình MVC (Model-View-Controller):
Model: Đại diện cho dữ liệu và logic xử lý dữ liệu, chẳng hạn như các class quản lý sản phẩm, giỏ hàng, và đơn đặt hàng.
View: Đại diện cho giao diện người dùng, chẳng hạn, trang web hiển thị danh sách sản phẩm và giỏ hàng.
Controller: Chịu trách nhiệm điều phối sự tương tác giữa Model và View.
- Security (Spring Security):
Sử dụng Spring Security để đảm bảo an toàn cho ứng dụng, bao gồm quản lý xác thực và ủy quyền.
- Sử dụng Spring Boot để cung cấp cấu hình mặc định và hỗ trợ nhiều loại ứng dụng phức tạp.
- Sử dụng Thymeleaf để phát triển các trang web mà có thể được tùy chỉnh bởi nhà phát triển.
- Sử dụng Maven để quản lý các thư viện phụ thuộc và quản lý quy trình xây dựng và triển khai dự án.
- Sử dụng Lombok để tạo các lớp POJO (Plain Old Java Object) nhẹ hơn và đơn giản hóa mã.

#### 2. Giải thích ngắn gọn về cấu trúc mã.

- #### *Các thư mục gồm có*:
- src/main/java:
Chứa mã nguồn Java của ứng dụng. Đây là nơi bạn sẽ đặt các package và class của ứng dụng.
- src/main/resources:
Chứa các tài nguyên như file cấu hình, file tĩnh (ví dụ, hình ảnh, trang HTML), và các tài nguyên khác cần thiết cho ứng dụng.
File application.properties có thể nằm ở đây, chứa cấu hình như kết nối cơ sở dữ liệu, cấu hình HTTP, và các thuộc tính khác của ứng dụng.
- src/test/java:
Chứa mã nguồn Java cho các bài kiểm thử cho ứng dụng. Các class kiểm thử sẽ thường được tổ chức tương tự như class chúng kiểm thử trong src/main/java.
- src/test/resources:
Chứa các tài nguyên cần thiết cho việc kiểm thử. Điều này có thể bao gồm các file dữ liệu kiểm thử, file cấu hình kiểm thử, và các tài nguyên khác liên quan đến quá trình kiểm thử.
- pom.xml:
Là tệp cấu hình Maven, chứa thông tin về các phụ thuộc (dependencies) của dự án, cài đặt plugin Maven, và các cấu hình khác như phiên bản Java, packaging type, và các thông số khác liên quan đến quá trình biên dịch và xây dựng dự án.
- application.properties:
Là tệp cấu hình của ứng dụng. Nó chứa các thuộc tính được sử dụng trong ứng dụng, như thông tin kết nối cơ sở dữ liệu, cấu hình HTTP, và các cấu hình khác của ứng dụng.


#### 3.Tất cả các bước cần thiết để ứng dụng chạy trên máy máy tính local.

```
### Clone về máy tính
git clone https://github.com/dacbinh123/Java_GK.git

### Tạo cơ sở dữ liệu 
Tạo một cơ sở dữ liệu trong MySQL với tên là spring_shoppingcartdb2 để lưu trữ dữ liệu của ứng dụng. Có thể sử dụng MySQL Workbench hoặc XAMPP để tạo cơ sở dữ liệu.
Sau đó hãy import file spring_shoppingcartdb2.sql trong thư mục database để import dữ liệu vào cơ sở dữ liệu.

### Cấu hình lại file application.properties
Cấu hình các thông số kết nối cơ sở dữ liệu trong tệp application.properties của ứng dụng Spring Boot.

### Chạy file SpringShoppingCart2Application trong đường dẫn src/main/java/com/example/demo/
```
### Sau khi xong tất cả các bước trên thì ta truy cập vào http://localhost:8080/
### *Thông tin tài khoản đăng nhập*
- Manager

  username: manager1

  Password: 123
- employee

  
  username: employee1
  Password: 123












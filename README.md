Đóng vai là một chuyên gia DevOps, hãy giúp tôi tự động hóa quá trình đóng gói và triển khai dự án Java Web hiện tại lên máy chủ Tomcat.

Yêu cầu thực thi:
1. Biên dịch dự án: Mở terminal tại thư mục gốc của dự án này và chạy lệnh:
   mvn clean package
   Hãy chờ cho đến khi xuất hiện thông báo BUILD SUCCESS.

2. Xác định file: Tìm file .war vừa được tạo ra bên trong thư mục target/ của dự án (ví dụ: target/user-management.war).

3. Triển khai (Deploy): Copy file .war này vào thư mục webapps của Tomcat:
   - Thay đường dẫn Tomcat tương ứng trên máy tính của bạn (Ví dụ: C:\Tomcat 10.1\webapps hoặc /Library/Tomcat/webapps).

4. Khởi động Server: Sau khi copy thành công, điều hướng terminal tới thư mục bin của Tomcat và chạy script khởi động:
   - Windows: startup.bat
   - macOS/Linux: ./startup.sh

Hãy hiển thị danh sách câu lệnh hệ thống chi tiết trước khi chạy để tôi duyệt trước.

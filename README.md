Việc đưa các thông số (như cấu hình database, port, API key,...) vào `application.properties` thay vì viết trực tiếp
trong code Java mang lại các lợi ích sau:

- Dễ thay đổi cấu hình mà không cần sửa code, chỉ cần chỉnh file properties là xong.
- Giúp tách biệt giữa “code xử lý” và “cấu hình”, code sạch và dễ đọc hơn.
- Dễ quản lý theo từng môi trường (dev, test, prod) bằng các file properties khác nhau.
- Tránh phải build lại project mỗi khi thay đổi cấu hình.
- Tăng tính bảo mật và linh hoạt khi deploy ứng dụng.

Kết luận:
Đưa config vào `application.properties` giúp ứng dụng linh hoạt, dễ bảo trì và dễ triển khai hơn.

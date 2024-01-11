# Hướng dẫn build các package của đồ án
## Mô tả cấu trúc của đồ án: Đồ án được chia làm bốn phần vận hành tương ứng với 4 package:
-  Package backend: Server của đồ án sử dụng framework Spring chạy trên môi trường Java 20.
-  Package frontend_ai: Giao diện quản lý web sử dụng framework Vue
-  Package frontend_ui: Giao diện người dùng sử dụng framework Vue
-  Package databse: Dữ liệu toàn hệ thống sử dụng hệ quản trị cơ sở dữ liệu MySQL
## Các bước build chương trình
<ul>
  <li>Để khởi tạo cơ sở dữ liệu: Chạy script <strong>sump.sql</strong> trong thư mục database trên hệ quản trị cơ sở dữ liệu MySQL</li>
  <li>Để chạy backend: Mở thư mục backend trong ứng dụng chạy ngôn ngữ Java (môi trường Java 20) chạy file <strong>pom.xml</strong> sau đó chạy file <strong>BackendApplication.java</strong></li>
  <li>Để chạy giao diện người dùng: Mở thư mục frontend_ui, trong giao diện console chạy câu lệnh <strong>npm install</strong> sau đó chạy câu lệnh <strong>npm run start</strong>, giao diện được khởi chạy ở cổng 5173: <strong>http://127.0.0.1:5173/</strong> </li>
  <li>Để chạy giao diện quản lý: Mở thư mục frontend_ai, trong giao diện console chạy câu lệnh <strong>npm install</strong> sau đó chạy câu lệnh <strong>npm run start</strong>, giao diện được khởi chạy ở cổng 5174: <strong>http://127.0.0.1:5174/</strong> (nếu chạy giao diện quản lý trước thì cổng khởi chạy giao diện quản lý là 5173 và giao diện người dùng là 5174)</li>
</ul>

## Mở trình duyệt bất kì và đi đến <strong>http://127.0.0.1:5173/</strong> để khởi chạy ứng dụng

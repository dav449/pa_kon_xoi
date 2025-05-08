# 📚 Phần mềm Quản lý Hàng hóa bằng Quét Mã Vạch
# 📌 Giới thiệu:
Xây dựng một phần mềm đơn giản giúp quản lý hàng hóa trong kho thông qua việc quét mã vạch, nhằm hỗ trợ kiểm kê, kiểm soát số lượng, hạn sử dụng và cập nhật thông tin sản phẩm nhanh chóng, chính xác.
# 👥 Thành viên
  - Ta Cong Chien  23010209
  - Nguyen Van Tu  23010109
  - Nguyen Le Duc Anh 23010246
# 🧰 Công nghệ sử dụng
 • Ngôn ngữ lập trình: Python
 • Thư viện chính:
 • Tkinter: Tạo giao diện người dùng
 • SQLite3: Lưu trữ và truy vấn dữ liệu
 • OpenCV & pyzbar: Xử lý ảnh và quét mã vạch
 • IDE sử dụng: Visual Studio Code
 • Cơ sở dữ liệu: products.db
 # 🪛 CẤU TRÚC CHƯƠNG TRÌNH
 # Chương trình được chia thành các mô-đun:
 1. init_db.py
 • Khởi tạo cơ sở dữ liệu SQLite
 • Tạo bảng products và thêm dữ liệu mẫu
 • Các hàm xử lý dữ liệu như check_product, update_quantity, upsert_product
 2. scanner.py
 • Quét mã vạch từ ảnh hoặc webcam
 • Kiểm tra và cập nhật số lượng sản phẩm sau khi quét
 3. update_gui.py
 • Giao diện thêm/cập nhật sản phẩm với các trường: mã vạch, tên, số lượng, giá, hạn sử dụng
 • Thiết kế hiện đại, dễ sử dụng, có xác thực đầu vào và phản hồi người dùng
 4. main.py
 • Cho phép người dùng chọn chế độ hoạt động: quét từ webcam, quét từ ảnh, hay cập nhật dữ liệu

# AndrewSub v1.7.1

- Tách riêng từng candidate khi gửi OCR máy chủ, ngăn Google Docs gộp hoặc
  đẩy chữ của câu thoại cực ngắn sang khung kế bên.
- Áp dụng cùng giới hạn an toàn cho lượt cứu ảnh rỗng và làm sạch cuối.
- Không tái sử dụng checkpoint được tạo bởi cơ chế ghép nhiều ảnh cũ.
- Bỏ giới hạn 12 luồng OCR; ứng dụng chạy đúng số luồng máy chủ được cấu hình.

Đây là bản vá nhẹ, không thay đổi hay ghi đè dữ liệu dự án, tài khoản, khóa truy
cập, FFmpeg và các thành phần đã cài.

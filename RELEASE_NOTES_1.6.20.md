# AndrewSub v1.6.20

- Chuẩn hóa ID nội bộ và ID montage của OCR song song, giữ đúng thứ tự phụ đề dù các tài khoản hoàn thành lộn xộn.
- Cải thiện đồng thuận OCR cho track cùng nét, bảo vệ thoại ngắn thật và hạn chế vùng nghi ngờ tạo phụ đề lặp.
- Lượt làm sạch OCR tiếp tục dùng đúng pool tài khoản đang hoạt động.
- Không chạy lại các lỗi cấu hình hoặc đăng nhập; vẫn retry lỗi mạng, giới hạn và máy chủ tạm thời.
- Kết nối tới máy chủ tách âm hoặc OCR không phản hồi sẽ báo sớm hơn thay vì làm giao diện trông như bị treo.
- Khóa dịch vụ mới được bảo vệ tập trung khi lưu; không còn khóa Whisper đóng sẵn trong mã nguồn.
- Phiên bản bộ cài được lấy từ cùng nguồn phiên bản của ứng dụng.

Đây là bản vá nhẹ, không kèm model, FFmpeg hoặc dữ liệu người dùng.

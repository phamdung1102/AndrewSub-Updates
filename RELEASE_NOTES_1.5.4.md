# AndrewSub v1.5.4

## Tối ưu render

- Giữ nguyên luồng hình khi không chèn phụ đề cứng hoặc làm mờ; chỉ mã hóa lại âm thanh.
- Tự dùng NVIDIA NVENC khi khả dụng và chuyển sang CPU nếu GPU gặp lỗi.
- Hiển thị tốc độ xử lý, thời gian còn lại và tốc độ so với thời gian thực.
- Kiểm tra đủ luồng hình, âm thanh và đúng thời lượng trước khi công nhận file hoàn tất.

## Giao diện dự án dài

- Nạp bảng phụ đề lớn theo từng lô để cửa sổ tiếp tục phản hồi.
- Đọc thời lượng hàng nghìn file voice ở luồng nền.
- Hủy lượt nạp cũ khi đổi dự án, tránh dữ liệu chồng chéo.

Đã chạy toàn bộ 260 bài kiểm thử và thử nạp bảng 3.000 dòng thành công.

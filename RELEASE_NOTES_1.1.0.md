# AndrewSub AI 1.1.0

## Tách và nhận diện phụ đề

- Giới hạn montage Drive OCR ở tối đa 20 ảnh.
- Chỉ nhận một batch khi toàn bộ marker khớp đúng ID và đúng thứ tự.
- Batch lỗi tự chia đôi đến từng ảnh, luân phiên tối đa bốn tài khoản mà không chạy lại từ đầu.
- Checkpoint, ảnh kiểm tra và cấu hình batch được ràng buộc cùng một lần quét để tránh lệch ảnh–text.
- Mặt nạ chữ được ổn định theo thời gian; tín hiệu sáng chỉ tồn tại một frame không còn tạo track rác.
- Phụ đề nhanh tồn tại từ hai frame trở lên vẫn được giữ ở chế độ quét 20–25 FPS.

## Đồng bộ voice và video

- Không cắt khoảng lặng trong file voice.
- Voice dài có thể mượn khoảng trống lân cận và co giãn cục bộ đoạn video.
- Timeline video được dựng bằng một filter graph để giảm thời gian băm clip.

## Kiểm tra

- 190 kiểm thử tự động đã đạt.
- Đoạn lỗi thực tế của dự án kiểm tra giảm từ 16 track vụn xuống 12 track ổn định.

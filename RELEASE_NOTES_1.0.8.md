# AndrewSub AI v1.0.8

Phiên bản này tập trung sửa lỗi phụ đề OCR bị lặp, phân mảnh và lẫn ký tự ngoài tiếng Trung.

## Thay đổi

- Kết nối bộ ổn định mask 3 frame vào pipeline nhận diện thực tế.
- Yêu cầu tín hiệu ổn định hai frame để hạn chế track giả khi quét FPS cao.
- Giới hạn tốc độ quét tối đa 25 FPS.
- Đọc lại ảnh nghi lẫn nhiễu bằng ảnh tăng cường.
- Tự nhận diện timeline chủ yếu là tiếng Trung khi ngôn ngữ để tự động.
- Loại phần Latin/Cyrillic không hợp lệ trong dòng tiếng Trung.
- Gộp biến thể OCR gần nhau chỉ khi thời gian và nét chữ cùng khớp.
- Chọn kết quả theo đồng thuận của các dòng lân cận.

## Kiểm thử

- 181 kiểm thử tự động đã đạt.

## Cập nhật

Gói vá giữ đầy đủ nội dung của `v1.0.7` và thay thế ba thành phần OCR đã sửa trong `v1.0.8`.

# AndrewSub v1.7.0

## Cải thiện nhận diện phụ đề nhanh

- Giữ lại các candidate thoại cực ngắn nằm sát đầu hoặc cuối câu đã nhận diện để OCR xác nhận.
- Không còn loại câu một–hai chữ chỉ vì chạm biên thời gian khoảng vài chục mili giây.
- Candidate nằm sâu trong câu đã có vẫn được loại để tránh gửi OCR thừa.
- Sau OCR, nội dung và nét ảnh tiếp tục quyết định gộp bản lặp hay giữ thành câu riêng.

## Điều chỉnh vị trí phụ đề

- Bỏ bốn lựa chọn vị trí cố định cũ.
- Thay bằng hai thanh kéo `Trái ↔ phải` và `Lên ↕ xuống`.
- Kéo trực tiếp phụ đề trên preview sẽ cập nhật ngược lại hai thanh.
- Preview và video xuất dùng chung tọa độ tự do.

## Kiểm tra

- Đạt 304/304 bài kiểm tra tự động.
- Patch chỉ chứa mã ứng dụng và tài nguyên, không chứa dự án, thiết lập, tài khoản hay log.

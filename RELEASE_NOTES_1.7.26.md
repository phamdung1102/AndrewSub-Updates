AndrewSub v1.7.26

- Sửa luồng OCR máy chủ: dùng một adapter remote, để server tự phân phối worker/tài khoản.
- Nhận diện đúng lỗi client_rate_limited và cooldown thay vì retry/split batch vô ích.
- Thêm thống kê batch thực tế, retry, queue để đo nghẽn OCR rõ hơn.

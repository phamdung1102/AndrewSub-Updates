# AndrewSub v1.7.17

- Tối ưu OCR máy chủ: gom phụ đề ngắn vào batch lớn khi server hỗ trợ centered-v3.
- Giảm batch nhỏ 1-5 ảnh để tận dụng pool nhiều tài khoản và giảm thời gian chờ OCR.
- Pass kiểm tra phụ dùng batch lớn hơn, vẫn tự chia nhỏ khi batch lỗi marker.

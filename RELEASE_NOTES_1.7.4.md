# AndrewSub v1.7.4

- Tối ưu tốc độ OCR máy chủ: giữ batch 20 ảnh/lượt khi server hỗ trợ centered-v3.
- Không còn ép câu ngắn gửi từng ảnh riêng trên server OCR mới, giảm mạnh số request cho video dài.
- Client tự đọc capability server khi chạy OCR thật, không phụ thuộc thao tác kiểm tra kết nối trong Cài đặt.

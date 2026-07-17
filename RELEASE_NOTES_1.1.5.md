# AndrewSub 1.1.5

- Sửa lỗi ảnh nhận diện bị xé khi vùng phụ đề có chiều rộng hoặc chiều cao lẻ.
- Buộc FFmpeg giữ đúng kích thước vùng khoanh thay vì âm thầm làm tròn kích thước của video `yuv420p`.
- Ngăn bộ đọc raw frame lấy lấn dữ liệu của frame tiếp theo, nguyên nhân khiến OCR trả rỗng và bỏ sót hàng loạt phụ đề.
- Thêm kiểm thử hồi quy cho vùng nhận diện kích thước lẻ.

Kiểm thử:

- 202 bài test tự động đã qua.
- Chạy lại detector trên video lỗi 5 phút: 192 ảnh ứng viên nguyên vẹn, không còn ảnh bị xé lát.
- Gói patch đã được giải nén kiểm tra: đúng phiên bản `1.1.5` và có bản sửa `exact=1`.

SHA-256:

- `AndrewSub-Patch-1.1.5.zip`: `a3f59855edad39232587623acd81fec21440a3f44fdc0cc649a4d0faf56bae1b`
- `AndrewSub-Setup-1.1.5.exe`: `d7293e27c6a68a7a72f6bb98b5d29510e7d6c5706319054c99a981caa9dd9850`

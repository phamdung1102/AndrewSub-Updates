AndrewSub v1.7.19

- Sửa OCR máy chủ chỉ chạy 1 worker trong pipeline streaming; giờ dùng đúng số luồng cấu hình.
- Mặc định gửi OCR server 20 luồng.
- Chuyển kênh tự cập nhật sang GitHub Releases/latest để tránh raw cache.
- Sửa đọc settings UTF-8 BOM, tránh mất cấu hình khi file có BOM.

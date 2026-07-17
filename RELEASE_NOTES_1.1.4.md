# AndrewSub 1.1.4

- Tăng tốc xuất video bằng NVIDIA NVENC; tự kiểm tra encode thật và chuyển sang CPU nếu GPU lỗi.
- Gộp kéo hình cục bộ, trộn voice, âm nền, làm mờ sub gốc và đóng hard-sub vào một lượt FFmpeg.
- Nếu hình không thay đổi, giữ nguyên luồng video bằng stream-copy.
- Render thẳng ra thư mục đích bằng file tạm an toàn, không tạo rồi sao chép thêm một file video vài GB.
- Hiển thị tốc độ render và thời gian còn lại.
- Thêm bốn chế độ: Tự động, Nhanh, Cân bằng và Chất lượng cao.
- Giữ nguyên toàn bộ voice và cơ chế đồng bộ hiện có.

Kiểm thử:

- 201 bài test tự động đã qua.
- Đã kiểm thử FFmpeg thật với kéo hình + trộn âm và hard-sub + làm mờ.
- Đã cài thử installer sạch; xác nhận FFmpeg, updater và GPU NVIDIA hoạt động.

SHA-256:

- `AndrewSub-Patch-1.1.4.zip`: `8ac55cb177842575b0a717c6cde5f9feea0d229382000e98e17d6964186da096`
- `AndrewSub_Setup_1.1.4.exe`: `bd4dd71a911ab85afecf7a0f9c49a721445c9097071eb8397bb11d5bcb3f54e6`

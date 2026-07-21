# AndrewSub v1.5.2

- Tách cấu hình OmniVoice Server khỏi VietAuto, OpenAI, ElevenLabs và REST tùy chỉnh để không ghi đè API key hoặc endpoint khi chuyển nguồn.
- Đồng bộ danh sách giọng động qua `GET /voices`; tự cập nhật giọng trên giao diện và giữ sáu giọng OmniVoice dự phòng khi server chưa có catalog.
- Gửi đúng `voice_id` tới `POST /tts`, hỗ trợ các chế độ `auto`, `design` và `clone`.
- Bổ sung tự đánh thức máy chủ voice qua Wake URL; app chờ `/health` sẵn sàng rồi tiếp tục hàng đợi, không chạy lại từ đầu.
- Wake token và khóa OmniVoice Server được lưu bằng cơ chế bảo vệ bí mật của ứng dụng.
- Giao diện Cài đặt chỉ hiện nhóm trường của API đang chọn để tránh chồng chéo.

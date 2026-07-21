# AndrewSub 1.5.0

- Thêm hộp **Thiết lập quy trình hàng loạt** tại tab Dự án.
- Chọn riêng các bước: tách phụ đề, dịch, tạo voice và xuất video.
- Có mẫu nhanh: toàn bộ quy trình, chỉ tách và dịch, chỉ voice và xuất.
- Chọn nguồn chính/dự phòng cho tách sub, dịch và voice.
- Lỗi bước nào thì fallback và chạy lại từ đúng bước đó; không chạy lại từ đầu.
- Bỏ qua kết quả đã hợp lệ; nếu bước trước thay đổi thì tự làm mới các bước sau.
- Render GPU lỗi có thể chuyển sang CPU; dự án lỗi không chặn dự án kế tiếp.
- Lưu lịch sử nguồn fallback và báo cáo kết quả theo từng dự án.
- Giữ model VietAuto/ElevenLabs chính thức `eleven_v3`.
- Bổ sung nút áp dụng một giọng cho toàn bộ phụ đề.

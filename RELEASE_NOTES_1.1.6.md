# AndrewSub v1.1.6

## Đồng bộ voice

- Giữ nguyên tuyệt đối hình và timeline video; không kéo chậm hoặc giữ khung theo voice.
- Voice dài tự mượn khoảng trống trước/sau, tăng tốc giữ cao độ và mix overlap khi cần.
- Bảo vệ phần đuôi câu, đặc biệt voice cuối video; không cắt khoảng lặng trong file voice.
- Nút đồng bộ chỉ lập lịch voice, không băm hoặc retime video trung gian.

## Tăng tốc xuất video

- Loại bỏ graph `trim` / `tpad` / `concat` hàng trăm nhánh trong bước xuất cuối.
- Chế độ nhanh dùng NVIDIA NVENC preset `p1`.
- Khi không chèn phụ đề cứng hoặc làm mờ hình, ứng dụng copy nguyên luồng video và chỉ xử lý audio.

## Kiểm thử

- Toàn bộ 31 kiểm thử lõi đạt.
- Gói cập nhật đã kiểm tra không chứa dự án, tài khoản, token, credentials hoặc thiết lập cá nhân.

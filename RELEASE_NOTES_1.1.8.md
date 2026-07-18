# AndrewSub v1.1.8

## Nhận diện phụ đề HD/Full HD

- Quét dày để giữ các câu thoại xuất hiện nhanh.
- Không gộp candidate trước OCR; chỉ gộp sau khi nội dung, thời gian và nét ảnh cùng xác nhận.
- Giảm track lặp do rung nét hoặc antialias mà không chạy theo một số lượng câu mục tiêu.
- Làm sạch ký tự OCR nhiễu và cứu chọn lọc ảnh trống hoặc khoảng timeline đáng ngờ.

## OCR song song và checkpoint

- OCR bắt đầu ngay trong lúc detector vẫn tiếp tục quét video.
- Nhiều tài khoản xử lý đồng thời; kết quả ráp lại theo ID và sắp xếp theo timestamp.
- Lô cuối luôn được flush dù chưa đủ 20 ảnh.
- Tài khoản lỗi hoặc bị giới hạn được chuyển sang tài khoản còn hoạt động.
- Có thể thay tài khoản và tiếp tục từ checkpoint, không chạy lại toàn bộ.

## FFMS2 5.0 x64

- Kèm `ffms2.dll` và `ffmsindex.exe` chính thức.
- Tăng tốc preview, kéo timeline và chụp lại frame phục vụ sửa OCR.
- Lượt quét tuần tự toàn video vẫn dùng FFmpeg.
- Tự fallback về FFmpeg nếu FFMS2 không hoạt động.

## Kiểm thử

- 209/209 unit test đạt.
- Patch được áp dụng thử bằng updater thành công.
- FFMS2 trong payload đã index và đọc frame 1080x1920 thực tế thành công.

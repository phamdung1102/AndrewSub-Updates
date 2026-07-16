# AndrewSub AI v1.0.9

Phiên bản này ưu tiên không bỏ sót phụ đề hội thoại nhanh và sửa cửa sổ CMD xuất hiện khi ứng dụng quét video.

## Nhận diện phụ đề

- Giữ cơ chế mask ổn định 2/3 frame cho phụ đề thông thường.
- Bổ sung nhánh cứu hộ riêng cho hard-sub rõ nét chỉ tồn tại đúng một frame.
- Ứng viên một-frame được OCR xác nhận; kết quả rỗng hoặc nhiễu sẽ bị loại ở hậu kiểm.
- Không chạy lượt quét video thứ hai, tránh làm thời gian xử lý tăng gấp đôi.
- Tiếp tục áp dụng đồng thuận OCR tiếng Trung và gộp track lặp có ràng buộc hình ảnh/thời gian.

## Ẩn cửa sổ CMD

- Khôi phục `CREATE_NO_WINDOW` cho tiến trình FFmpeg dùng để stream vùng phụ đề.
- Dùng chung tùy chọn tiến trình ẩn cho VideoSubFinder và trình cài thành phần.
- Giữ launcher/updater chạy bằng `pythonw.exe` và không làm ẩn cửa sổ trình duyệt đăng nhập.

## Hiệu năng dự kiến

- Video sạch: thời gian thường tăng khoảng 5–15%.
- Video nền nhiễu hoặc có nhiều phụ đề chớp nhanh: có thể tăng khoảng 20–35% do OCR thêm ứng viên cứu hộ.
- Không quét lại toàn bộ video lần hai.

## Kiểm thử

- 182 kiểm thử tự động đã đạt.

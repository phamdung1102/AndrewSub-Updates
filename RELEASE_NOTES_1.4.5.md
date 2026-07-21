# AndrewSub 1.4.5

- Tăng tốc VietAuto/API voice: mặc định chạy 4 luồng.
- Mỗi lô voice API tối đa 5 câu để giảm thời gian chờ server.
- Vẫn xuất từng WAV riêng theo dòng để giữ khớp timeline/sub.
- VietAuto lấy project_id trước khi chạy song song để tránh lỗi nhiều luồng tạo project.

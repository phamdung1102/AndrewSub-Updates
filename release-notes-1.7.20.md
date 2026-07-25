AndrewSub v1.7.20

- Tối ưu gửi OCR máy chủ: không chờ batch 20 ảnh quá lâu.
- Batch phụ được flush nhanh 0.8-1.2s để scan local và OCR server chồng việc đều hơn.
- Logic gửi không phụ thuộc server đang có bao nhiêu tài khoản; server tự scale phía sau.

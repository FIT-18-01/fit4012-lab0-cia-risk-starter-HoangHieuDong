# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

## Assets
- Database lưu điểm sinh viên
- Tài khoản sinh viên và giảng viên
- Server hệ thống
- Website quản lý điểm

---

## CIA mapping
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

---

## Sự cố A
Rò rỉ thông tin điểm sinh viên

---

## Sự cố B
Sinh viên sửa điểm trái phép

---

## Sự cố C
Hệ thống bị sập, không truy cập được

---

## Phân tích sự cố B

Threat:
Hacker hoặc sinh viên lợi dụng lỗ hổng để thay đổi điểm

Vulnerability:
- Hệ thống không kiểm tra quyền truy cập chặt chẽ
- Không có cơ chế xác thực mạnh

Mitigation:
- Áp dụng xác thực mạnh (2FA)
- Phân quyền rõ ràng (RBAC)
- Ghi log và kiểm tra hoạt động bất thường

---

## Kết luận
Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào thực tế. Việc xác định threat và vulnerability giúp em nhìn rõ các rủi ro trong hệ thống.

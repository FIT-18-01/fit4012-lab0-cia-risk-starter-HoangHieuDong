# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Hiểu Đông  
**MSSV:** 1871020146  
**Lớp/Nhóm:** CNTT_18-01  

---

## Assets
- Dữ liệu người dùng (thông tin cá nhân, tài khoản, mật khẩu)
- Cơ sở dữ liệu hệ thống
- Hệ thống máy chủ (server) và ứng dụng

---

## CIA Mapping
- Incident A -> Confidentiality
- Incident B -> Integrity
- Incident C -> Availability

---

## Incident A
Rò rỉ dữ liệu người dùng (lộ thông tin cá nhân, tài khoản).

---

## Incident B
Dữ liệu bị sửa đổi trái phép (ví dụ: sửa điểm sinh viên).

---

## Incident C
Hệ thống bị gián đoạn, không thể truy cập.

---

## Threat
Hacker hoặc người dùng có ý đồ xấu tấn công để thay đổi dữ liệu.

---

## Vulnerability
- Không kiểm tra dữ liệu đầu vào
- Thiếu phân quyền truy cập
- Không bảo vệ dữ liệu đúng cách

---

## Mitigation
- Kiểm tra dữ liệu đầu vào (validation)
- Áp dụng phân quyền (RBAC)
- Mã hóa dữ liệu và dùng HTTPS
- Ghi log và giám sát hệ thống

---

## Reflection
Qua bài này, em hiểu rõ hơn về mô hình CIA và cách áp dụng trong thực tế. Việc xác định assets giúp tập trung bảo vệ các thành phần quan trọng. Em nhận thấy rằng các lỗ hổng nhỏ cũng có thể gây ra rủi ro lớn. Khi phân tích hệ thống, cần xem xét đầy đủ threat, vulnerability và mitigation.

---

## Bonus Flag
FIT4012{A-C-B-I-C-A}

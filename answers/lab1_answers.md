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
Rò rỉ dữ liệu người dùng (lộ thông tin cá nhân, tài khoản)

---

## Incident B
Dữ liệu bị sửa đổi trái phép (ví dụ: sửa điểm sinh viên)

---

## Incident C
Hệ thống bị gián đoạn, không thể truy cập

---

## Threat
Hacker hoặc người dùng có ý đồ xấu tấn công để thay đổi dữ liệu

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
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B trước vì việc sửa điểm ảnh hưởng trực tiếp đến tính chính xác của dữ liệu. Điều này có thể làm mất uy tín của hệ thống và gây ảnh hưởng đến sinh viên. Sau đó em sẽ xử lý các vấn đề liên quan đến bảo mật và khả năng truy cập để đảm bảo hệ thống hoạt động an toàn và ổn định.

---

## Bonus Flag
FIT4012{A-C-B-I-C-A}

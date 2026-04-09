# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Hiểu Đông

**MSSV:** 1871020146

**Lớp/Nhóm:** CNTT_18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu người dùng (thông tin cá nhân, tài khoản, mật khẩu)
- Asset 2:Cơ sở dữ liệu hệ thống
- Asset 3 (nếu có):Hệ thống máy chủ (server) và ứng dụng

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality (Rò rỉ dữ liệu, lộ thông tin người dùng)
- Sự cố B -> Integrity (Dữ liệu bị sửa đổi trái phép)
- Sự cố C -> Availability (Hệ thống bị gián đoạn, không truy cập được)

---

## 3. Phân tích sự cố B
- Threat: Hacker tấn công và thay đổi dữ liệu trong hệ thống (ví dụ: sửa điểm, sửa thông tin tài khoản)
- Vulnerability:
    Không kiểm tra dữ liệu đầu vào (input validation kém)
    Thiếu cơ chế phân quyền (authorization)
    Không mã hóa hoặc bảo vệ dữ liệu đúng cách
- Mitigation:
    Áp dụng kiểm tra dữ liệu đầu vào (validation, sanitization)
    Sử dụng phân quyền chặt chẽ (RBAC)
    Mã hóa dữ liệu và sử dụng HTTPS
    Ghi log và theo dõi thay đổi dữ liệu

---

## 4. Reflection
Qua bài này, em hiểu rõ hơn tầm quan trọng của việc bảo mật hệ thống thông tin. Việc xác định assets giúp tập trung bảo vệ những thành phần quan trọng nhất. Mô hình CIA là nền tảng để phân tích các rủi ro bảo mật một cách có hệ thống. Ngoài ra, em nhận thấy rằng các lỗ hổng nhỏ như thiếu kiểm tra dữ liệu đầu vào cũng có thể dẫn đến hậu quả nghiêm trọng. Do đó, việc thiết kế hệ thống cần đi kèm với các biện pháp bảo mật ngay từ đầu. Đây là kiến thức rất hữu ích cho việc phát triển phần mềm an toàn trong thực tế.



---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-C-B-I-C-A}


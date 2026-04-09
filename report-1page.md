# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện các tài sản quan trọng trong hệ thống lưu điểm.
- Hiểu và áp dụng mô hình CIA (Confidentiality, Integrity, Availability).
- Xác định threat, vulnerability và đề xuất mitigation.
- Làm quen với quy trình làm bài và nộp bài trên GitHub.

---

### 2. Cách làm
- Đọc bối cảnh hệ thống và sơ đồ context.
- Xác định các tài sản (assets) cần bảo vệ.
- Phân tích các sự cố theo CIA.
- Chọn một sự cố để phân tích sâu hơn (threat, vulnerability, mitigation).
- Hoàn thiện bài và commit/push lên GitHub.

---

### 3. Kết quả chính

#### Assets:
- Database lưu điểm sinh viên
- Tài khoản sinh viên và giảng viên
- Server hệ thống
- Website quản lý điểm

#### CIA mapping:
- Confidentiality: Bảo mật thông tin điểm và tài khoản người dùng
- Integrity: Đảm bảo điểm không bị sửa đổi trái phép
- Availability: Hệ thống luôn truy cập được khi cần

#### Sự cố A:
Rò rỉ thông tin điểm sinh viên → Vi phạm Confidentiality

#### Sự cố B:
Sinh viên sửa điểm trái phép → Vi phạm Integrity

#### Sự cố C:
Hệ thống bị sập, không truy cập được → Vi phạm Availability

---

### Phân tích sự cố B:

**Threat:**
- Hacker hoặc sinh viên lợi dụng lỗ hổng để thay đổi điểm

**Vulnerability:**
- Hệ thống không kiểm tra quyền truy cập chặt chẽ
- Không có cơ chế xác thực mạnh

**Mitigation:**
- Áp dụng xác thực mạnh (2FA)
- Phân quyền rõ ràng (RBAC)
- Ghi log và kiểm tra hoạt động bất thường

---

### 4. Kết luận ngắn
Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào thực tế. Việc xác định threat và vulnerability giúp em nhìn rõ các rủi ro trong hệ thống. Phần khó nhất là phân biệt giữa threat và vulnerability. Khi phân tích an toàn thông tin, cần hiểu rõ hệ thống và suy nghĩ như kẻ tấn công để tìm ra điểm yếu.

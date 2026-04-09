---
incident_a: Availability
incident_b: Integrity
incident_c: Confidentiality
threat: Ke xau truy cap trai phep de sua diem
vulnerability: Thieu xac thuc va khong ghi log
mitigation: Phan quyen chat che va ghi nhat ky
---

# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu chứa điểm của sinh viên.
- Tài khoản đăng nhập của giảng viên và sinh viên.

**CIA mapping:**
Sự cố A -> Availability
Sự cố B -> Integrity
Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Kẻ xấu truy cập trái phép để sửa điểm.
- Vulnerability: Hệ thống thiếu xác thực mạnh và không lưu log.
- Mitigation: Áp dụng phân quyền chặt chẽ và ghi nhật ký thay đổi.

### 4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về cách áp dụng mô hình CIA. Việc xác định đúng tài sản (assets) giúp đưa ra biện pháp khắc phục (mitigation) phù hợp nhất.

# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.

### 2. Cách làm
- Phân tích sự cố theo bộ ba CIA.

### 3. Kết quả chính
**Assets:**
- Asset 1: Cơ sở dữ liệu chứa điểm của sinh viên.
- Asset 2: Tài khoản đăng nhập của sinh viên và giảng viên.

**CIA mapping:**
- incident_a: Availability
- incident_b: Integrity
- incident_c: Confidentiality

**Phân tích sự cố B:**
- threat: Kẻ xấu truy cập trái phép để sửa điểm.
- vulnerability: Hệ thống thiếu xác thực mạnh và không lưu log.
- mitigation: Áp dụng phân quyền chặt chẽ và ghi nhật ký thay đổi.

### 4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về cách áp dụng mô hình CIA. Việc xác định đúng tài sản (assets) giúp đưa ra biện pháp khắc phục (mitigation) phù hợp nhất.

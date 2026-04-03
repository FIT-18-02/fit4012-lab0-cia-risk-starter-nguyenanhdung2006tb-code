# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm sinh viên
- Tài khoản đăng nhập của sinh viên và giảng viên
- Hệ thống đăng nhập

**CIA mapping:**
Sự cố A -> Availability
Sự cố B -> Integrity
Sự cố C -> Confidentiality

**Phân tích sự cố B:**
Threat:
Người không có quyền truy cập vào hệ thống và thay đổi điểm của sinh viên.

Vulnerability:
Hệ thống không có cơ chế kiểm soát quyền truy cập chặt chẽ hoặc không ghi log khi thay đổi điểm.

Mitigation:
Áp dụng phân quyền truy cập rõ ràng và lưu log khi có thay đổi điểm trong hệ thống.

### 4. Kết luận ngắn
Qua bài lab này em hiểu rõ hơn về mô hình CIA trong an toàn thông tin.
Em học được cách phân tích một sự cố bảo mật dựa trên threat, vulnerability và mitigation.
Phần khó nhất là xác định chính xác loại sự cố thuộc CIA nào.
Bài lab cũng giúp em làm quen với việc sử dụng GitHub để nhận và nộp bài.
Khi phân tích sự cố an toàn thông tin cần xác định đúng tài sản cần bảo vệ và rủi ro có thể xảy ra.

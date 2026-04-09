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
- **incident_a**: Availability (Hệ thống bị sập, không thể truy cập để xem điểm).
- **incident_b**: Integrity (Dữ liệu điểm bị thay đổi trái phép).
- **incident_c**: Confidentiality (Lộ thông tin điểm riêng tư của sinh viên).

**Phân tích sự cố B:**
- **threat**: Kẻ xấu hoặc sinh viên tìm cách xâm nhập trái phép để sửa điểm.
- **vulnerability**: Hệ thống không có xác thực 2 lớp và thiếu ghi log lịch sử chỉnh sửa.
- **mitigation**: Triển khai phân quyền nghiêm ngặt (RBAC) và ghi nhật ký hệ thống (System Logging).

### 4. Kết luận ngắn
Em đã hiểu cách áp dụng mô hình CIA vào thực tế để đánh giá rủi ro. Việc xác định đúng Asset và Vulnerability giúp đưa ra giải pháp Mitigation phù hợp hơn. Bài lab này giúp em làm quen với quy trình làm việc chuyên nghiệp trên GitHub.

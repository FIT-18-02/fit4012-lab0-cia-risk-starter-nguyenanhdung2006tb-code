# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện assets và hiểu mô hình CIA.
- Phân tích threat, vulnerability, mitigation.

### 2. Cách làm
- Đọc bối cảnh, xác định tài sản và phân tích sự cố.

### 3. Kết quả chính

#### Assets:
- Asset 1: Cơ sở dữ liệu điểm sinh viên.
- Asset 2: Tài khoản đăng nhập của sinh viên và giảng viên.
- Hình minh họa: ![Screenshot](https://via.placeholder.com/150)

#### Mapping CIA:
- incident_a: Availability (Sinh viên không đăng nhập được).
- incident_b: Integrity (Điểm bị sửa từ 8.0 xuống 5.0).
- incident_c: Confidentiality (Danh sách điểm bị lộ ra ngoài).

#### Phân tích sự cố B:
- threat: Người dùng không có quyền hoặc kẻ xấu tìm cách sửa điểm.
- vulnerability: Hệ thống thiếu kiểm soát quyền hạn và không có log ghi lại.
- mitigation: Áp dụng phân quyền chặt chẽ và ghi nhật ký thay đổi điểm.

### 4. Kết luận ngắn
Em đã học được cách phân tích rủi ro dựa trên mô hình CIA. Việc xác định đúng Asset giúp đưa ra các biện pháp Mitigation hiệu quả để bảo vệ hệ thống.

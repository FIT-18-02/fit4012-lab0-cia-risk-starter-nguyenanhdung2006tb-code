# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ và hiểu mô hình CIA.
- Phân tích Threat, Vulnerability và đưa ra Mitigation.

### 2. Cách làm
- Phân tích sự cố theo bộ ba CIA.
- Hoàn thiện báo cáo và nộp qua GitHub Actions.

### 3. Kết quả chính

#### Assets (Hình ảnh minh họa)
![Minh hoa 1](https://via.placeholder.com/150)
![Minh hoa 2](https://via.placeholder.com/150)


#### CIA Mapping
- **incident_a**: Availability (Hệ thống bị sập, không thể truy cập để xem điểm).
- **incident_c**: Confidentiality (Lộ thông tin điểm riêng tư của sinh viên).
- **incident_b**: Integrity (Dữ liệu điểm bị thay đổi trái phép).

#### Risk Analysis (Sự cố B)
- **threat**: Kẻ xấu hoặc sinh viên tìm cách xâm nhập trái phép để sửa điểm.
- **vulnerability**: Hệ thống không có xác thực 2 lớp và thiếu ghi log lịch sử chỉnh sửa.
- **mitigation**: Triển khai phân quyền nghiêm ngặt (RBAC) và ghi nhật ký hệ thống (System Logging).

### 4. Kết luận ngắn
Em đã hiểu cách áp dụng mô hình CIA vào thực tế để đánh giá rủi ro. Việc xác định đúng Asset và Vulnerability giúp đưa ra giải pháp Mitigation phù hợp hơn. Bài lab này giúp em làm quen với quy trình làm việc chuyên nghiệp trên GitHub.

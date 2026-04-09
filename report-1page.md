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
- Asset 1: Cơ sở dữ liệu chứa điểm của sinh viên.
- Asset 2: Tài khoản đăng nhập của giảng viên và sinh viên.

**CIA mapping:**
Sự cố A -> Availability
Sự cố B -> Integrity
Sự cố C -> Confidentiality

**Phân tích sự cố B:**

Threat:
Kẻ xấu hoặc sinh viên truy cập trái phép vào hệ thống để sửa điểm.

Vulnerability:
Hệ thống thiếu cơ chế xác thực mạnh và không lưu lại lịch sử chỉnh sửa (logging).

Mitigation:
Áp dụng phân quyền truy cập chặt chẽ và ghi nhật ký mọi thay đổi trong hệ thống.

### 4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về cách áp dụng mô hình CIA vào hệ thống thực tế. Phần khó nhất là phân biệt chính xác loại sự cố để tìm ra lỗ hổng. Khi phân tích sự cố an toàn thông tin, điều quan trọng nhất là phải xác định đúng tài sản (assets) bị ảnh hưởng để đưa ra biện pháp khắc phục (mitigation) phù hợp.

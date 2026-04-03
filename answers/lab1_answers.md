# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Anh Dũng

**MSSV:** 1871020167

**Lớp/Nhóm:** CNTT-18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu điểm sinh viên
- Asset 2: Tài khoản đăng nhập của sinh viên và giảng viên
- Asset 3 (nếu có): Hệ thống đăng nhập của website

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability (Khả năng truy cập)
- Sự cố B -> Integrity (Tính toàn vẹn dữ liệu)
- Sự cố C -> Confidentiality (Tính bảo mật)

---

## 3. Phân tích sự cố B
- Threat: Người không có quyền truy cập vào hệ thống và thay đổi điểm của sinh viên.
- Vulnerability: Hệ thống không có kiểm soát quyền truy cập chặt chẽ hoặc không ghi lại lịch sử thay đổi điểm.
- Mitigation: Áp dụng phân quyền truy cập rõ ràng và lưu log khi có thay đổi điểm.

---

## 4. Reflection
Viết 5-7 dòng.
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề về tính toàn vẹn dữ liệu trước.
Vì việc điểm số bị thay đổi có thể ảnh hưởng trực tiếp đến kết quả học tập của sinh viên.
Điều này cũng làm giảm sự tin tưởng vào hệ thống.
Sau đó em sẽ cải thiện khả năng truy cập của hệ thống và tăng cường bảo mật dữ liệu.
Một hệ thống ổn định và an toàn sẽ giúp sinh viên và giảng viên yên tâm sử dụng.


---

## 5. Bonus Flag
`FIT4012{A-A-B-I-C-C}`

Flag của em:FIT4012{A-A-B-I-C-C}


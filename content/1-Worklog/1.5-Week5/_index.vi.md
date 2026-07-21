---
title: "Worklog Tuần 5"
date: 2026-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Đi sâu vào bảo mật mạng bằng cách nghiên cứu cơ chế hoạt động của Security Group và Network ACLs.
* Triển khai mô hình Lab thực tế: Thiết lập sơ đồ mạng đa lớp, tạo máy chủ ảo EC2 và kiểm thử định tuyến qua NAT Gateway.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 |  Nghiên cứu cơ chế kiểm soát truy cập bằng Security Group, Network ACLs và công cụ trực quan VPC Resource Map. | 18/05/2026 | 20/05/2026 | |
| 3 |  Đăng ký slot làm việc thành công và được phê duyệt lên văn phòng công ty buổi đầu tiên. | 19/05/2026 | 19/05/2026 | |
| 4 |  Thực hành tự thiết lập mạng ảo hoàn chỉnh gồm: VPC, Subnet, IGW, Route Table và các bộ quy tắc Security Group. | 20/05/2026 | 22/05/2026 | https://000003.awsstudygroup.com/vi/3-prerequisite |
| 5 |  Phân bổ chính sách an toàn thông tin mạng bằng cách cấu hình Security Group. | 21/05/2026 | 22/05/2026 | |
| 6 |  Khởi tạo máy chủ EC2 Instance bên trong Subnet và kiểm thử luồng truyền dữ liệu qua NAT Gateway. | 22/05/2026 | 23/05/2026 | https://000003.awsstudygroup.com/vi/4-createec2server |

### Kết quả đạt được tuần 5:
* Phân biệt rõ ràng giữa Security Group (stateful - bảo mật mức Instance) và Network ACL (stateless - bảo mật mức Subnet).
* Sử dụng thành thạo VPC Resource Map để giám sát trực quan các mối liên kết tài nguyên mạng.
* Dựng thành công môi trường mạng thực tế, cài đặt EC2 Instance chạy hệ điều hành Linux trong Subnet bảo mật và định tuyến thành công kết nối Internet qua NAT Gateway.
---
title: "Worklog Tuần 9"
date: 2026-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:
* Tham gia Workshop xây dựng hệ thống có tính sẵn sàng cao (Highly Available Web Application).
* Tìm hiểu cơ chế định tuyến tên miền toàn cầu với Amazon Route53 và thực hành thao tác lệnh qua CLI nâng cao.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Lên văn phòng công ty làm việc và trao đổi tiến độ dự án. | 15/06/2026 | 15/06/2026 | |
| 3 | - Tham gia buổi chuyên đề (Workshop) kỹ thuật hướng dẫn xây dựng Web App tính sẵn sàng cao (High Availability). | 16/06/2026 | 18/06/2026 | https://cloudjourney.awsstudygroup.com |
| 4 | - Học giải pháp định tuyến lai Hybrid DNS liên kết hạ tầng doanh nghiệp và VPC thông qua Amazon Route53. | 17/06/2026 | 19/06/2026 | |
| 5 | - Tìm hiểu cách điều phối tài nguyên bằng công cụ dòng lệnh AWS CLI trên môi trường Linux (Ubuntu) và Windows. | 18/06/2026 | 20/06/2026 | |
| 6 | - Thực hành phân tích, thiết lập bản ghi và cấu hình quản lý tên miền trên Amazon Route53. | 19/06/2026 | 20/06/2026 | |

### Kết quả đạt được tuần 9:
* Nắm bắt mô hình kiến trúc High Availability (HA) phân tách tải trên Multi-AZ sử dụng Application Load Balancer.
* Hiểu cơ chế phân giải tên miền (DNS records: A, AAAA, CNAME, MX) và cách ánh xạ IP máy chủ lên Route53.
* Viết thành công các shell script tự động hóa tác vụ khởi tạo/đóng máy chủ ảo EC2 bằng các câu lệnh AWS CLI trên terminal.
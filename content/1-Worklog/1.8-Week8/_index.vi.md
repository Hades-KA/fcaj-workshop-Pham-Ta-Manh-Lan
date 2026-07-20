---
title: "Worklog Tuần 8"
date: 2026-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Học cách cấu hình và vận hành hệ thống cơ sở dữ liệu quan hệ Amazon RDS.
* Nghiên cứu cơ chế co giãn hạ tầng tính toán tự động qua EC2 Auto Scaling và giám sát hệ thống bằng Amazon CloudWatch.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu cách thiết lập, vận hành và quản lý hạ tầng cơ sở dữ liệu quan hệ với Amazon RDS. | 08/06/2026 | 10/06/2026 | |
| 3 | - Nghiên cứu giải pháp triển khai hạ tầng máy chủ ảo chi phí thấp cho dự án nhỏ bằng Amazon Lightsail. | 09/06/2026 | 11/06/2026 | |
| 4 | - Học cơ chế co giãn tài nguyên tự động nhằm tối ưu hiệu năng ứng dụng thông qua Amazon EC2 Auto Scaling. | 10/06/2026 | 12/06/2026 | |
| 5 | - Nghiên cứu hệ thống thu thập chỉ số và giám sát lịch sử hoạt động (metrics & logs) với Amazon CloudWatch. | 11/06/2026 | 13/06/2026 | |
| 6 | - Thực hành thiết lập ngưỡng cảnh báo (Alarm) để chủ động phát hiện sự cố hệ thống. | 12/06/2026 | 13/06/2026 | |

### Kết quả đạt được tuần 8:
* Khởi tạo thành công cơ sở dữ liệu MySQL trên Amazon RDS, kết nối và truy vấn thử nghiệm từ máy trạm EC2.
* Hiểu cách thức hoạt động của EC2 Auto Scaling (Scaling-out khi tải cao và Scaling-in khi rảnh rỗi).
* Biết cách cài đặt CloudWatch Agent để thu thập log hệ thống, đồng thời tự tạo các CloudWatch Alarms để cảnh báo qua email khi CPU sử dụng vượt quá 90%.
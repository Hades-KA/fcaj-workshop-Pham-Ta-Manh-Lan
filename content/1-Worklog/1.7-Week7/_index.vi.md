---
title: "Worklog Tuần 7"
date: 2026-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:
* Thực hành triển khai ứng dụng cơ bản lên máy chủ ảo Amazon EC2.
* Làm quen với trình soạn thảo trực tuyến Cloud9 và trải nghiệm dịch vụ lưu trữ Web tĩnh (Static Website Hosting) trên Amazon S3.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 |  Tham gia buổi họp và hoạt động định kỳ tại văn phòng công ty. | 01/06/2026 | 01/06/2026 | |
| 3 |  Nghiên cứu hướng dẫn cơ bản (Getting Started) và triển khai một web server đơn giản trên Amazon EC2. | 02/06/2026 | 04/06/2026 | |
| 4 |  Tìm hiểu giải pháp bảo mật trung gian giúp ứng dụng kết nối tài nguyên AWS an toàn thông qua IAM Role. | 03/06/2026 | 05/06/2026 | |
| 5 |  Trải nghiệm môi trường lập trình trực tuyến trên nền trình duyệt bằng AWS Cloud9. | 04/06/2026 | 05/06/2026 | |
| 6 |  Thực hành phân phối và lưu trữ web app dạng tĩnh (Static Website Hosting) sử dụng dịch vụ Amazon S3. | 05/06/2026 | 06/06/2026 | |

### Kết quả đạt được tuần 7:
* Deploy thành công mã nguồn Web Server lên EC2, cấu hình Inbound Rules cho phép người dùng bên ngoài truy cập qua cổng HTTP (Port 80).
* Hiểu cách liên kết bảo mật không cần lộ mã bảo mật (credentials) bằng cách gắn trực tiếp IAM Role vào máy chủ ảo.
* Biết cách sử dụng môi trường lập trình AWS Cloud9 để chỉnh sửa code trực tiếp từ trình duyệt web.
* Triển khai hoàn chỉnh tính năng Static Website Hosting trên S3 bucket, cấu hình Bucket Policy cấp quyền truy cập Public cho tệp tin HTML/CSS.
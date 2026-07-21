---
title: "Worklog Tuần 11"
date: 2026-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:
* Khắc phục triệt để các lỗi vận hành của hệ thống LunaGenZ sau khi đã chuyển lên AWS.
* Tập trung tối đa cho việc lập dự thảo Báo cáo thực tập tốt nghiệp: Hoàn thành phần thiết kế mô hình kiến trúc hạ tầng và các chương kỹ thuật chuyên môn.
* Chuẩn bị tệp dữ liệu Markdown và cấu trúc thư mục cho Workshop cá nhân.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 |  Rà soát lại toàn bộ cấu hình Live trên AWS, tối ưu hóa hiệu năng hệ thống LunaGenZ trước khi viết báo cáo. | 29/06/2026 | 01/07/2026 | |
| 3 |  Sử dụng bộ giả lập đám mây cục bộ Floci (AWS emulator chạy trên cổng 4566) để thực hiện kiểm thử luồng tích hợp (API Gateway, Lambda, S3, DynamoDB) và debug tính năng xuất file PDF ngay tại Localhost mà không tốn chi phí tài nguyên thật. | 30/06/2026 | 30/06/2026 |https://github.com/floci-io |
| 4 |  Trích xuất các dữ liệu thực tế và chụp màn hình cấu hình AWS (Security Groups, Route Table, Gateway) làm phụ lục báo cáo. | 01/07/2026 | 03/07/2026 | |
| 5 |  Tổng hợp phần nội dung báo cáo cá nhân và rà soát tính đồng bộ với phần tài liệu của các thành viên khác. | 02/07/2026 | 03/07/2026 | |
| 6 |  Phác thảo cấu trúc thư mục và chuẩn bị các file Markdown (.md) cho nội dung trang Workshop cá nhân. | 03/07/2026 | 04/07/2026 | |

### Kết quả đạt được tuần 11:
* Sử dụng thành thạo bộ giả lập Floci để test luồng dịch vụ cục bộ, giúp phát hiện nhanh các lỗi định tuyến dữ liệu giữa API và Lambda mà không làm phát sinh chi phí lab AWS.
* Hoàn thành phần lớn nội dung Báo cáo thực tập tốt nghiệp, trình bày chi tiết chương kiến trúc hạ tầng mạng và tích hợp dịch vụ.
* Biên tập xong bộ ảnh chụp thực tế từ AWS Console làm minh chứng trực quan hỗ trợ phụ lục báo cáo.
* Thiết lập thành công cấu trúc thư mục cho Workshop cá nhân trên môi trường Localhost.
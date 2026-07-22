---
title: "Worklog Tuần 9"
date: 2026-06-30
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:
* Tối ưu hóa hiệu năng hiển thị và giảm độ trễ (latency) cho ứng dụng bằng cách xây dựng cơ chế bộ nhớ đệm (cache) phía Client.
* Hoàn thiện thuật toán sinh màn chơi động (Dynamic Generation) và quản lý phiên chơi (Session Management).
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 3, 4 | Tối ưu hóa lưu trữ và Render dữ liệu phía Client: <br> - Xây dựng lưu trữ dữ liệu màn chơi Sudoku cục bộ bằng electron-store ngay sau khi nhận phản hồi từ Server. <br> - Xử lý thuật toán Redux: Hệ thống sẽ kiểm tra và render dữ liệu Sudoku từ bộ nhớ tạm của client trước. | 30/06/2026 | 01/07/2026 |  |
| 5, 6, 7 | Cập nhật hệ thống Tạo màn chơi: <br> - Logic phía Server: Triển khai thành công API tạo (generate) ma trận màn chơi Sudoku ngẫu nhiên theo các cấp độ trên Server. <br> - Quản lý Session: Xử lý logic khởi tạo phiên chơi (session) mới trên Server mỗi khi Client gửi request yêu cầu tạo màn, đảm bảo tính minh bạch và tránh gian lận. | 02/07/2026 | 04/07/2026 |  |

### Kết quả đạt được tuần 9:
* Tối ưu hóa hiệu năng Frontend, biết cách kết hợp hiệu quả giữa công cụ quản lý State (Redux) và giải pháp lưu trữ cục bộ (electron-store) trong các ứng dụng desktop/web.
* Hiểu sâu sắc hơn về kiến trúc Server-Authoritative trong lập trình game, đảm bảo mọi logic quan trọng (sinh dữ liệu, cấp session) đều phải do Server quyết định để bảo mật hệ thống.

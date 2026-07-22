---
title: "Worklog Tuần 7"
date: 2026-06-16
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu tuần 7:
* Hoàn thiện hệ thống API Backend cho Minigame (Sudoku) bằng kiến trúc Serverless (AWS Lambda).
* Xử lý các luồng giao dịch tài nguyên phức tạp, đảm bảo tính toàn vẹn dữ liệu trong cơ sở dữ liệu.
* Nghiên cứu và áp dụng các cơ chế chống gian lận (Anti-cheat) để bảo vệ hệ thống trước các hành vi can thiệp trái phép từ phía Client.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 3, 4 | Triển khai Chi tiết Hệ thống AWS Lambda cho chức năng minigame: <br> - Tạo API truy xuất danh sách màn chơi và Highscore cá nhân. <br> - Khởi tạo phiên chơi, xử lý trừ phí Sanity qua Transaction, sinh Seed/Map ngẫu nhiên. <br> - Xác thực kết quả, tính Rank Points dựa trên thời gian, xử lý hoàn phí hoặc cộng eCoin. <br> - Tạo API lấy dữ liệu BXH Toàn máy chủ và BXH Bạn bè. | 16/06/2026 | 17/06/2026 |  |
| 6, 7 | Phát triển Cơ chế Chống Gian Lận (Anti-cheat) & Tối ưu Luồng Chơi: <br> -Bảo mật Backend: ẩn hoàn toàn mảng đáp án khỏi payload gửi về Client. Chuyển toàn bộ logic check đáp án về xử lý kín trên Server để chống hack/soi code. <br> -Thêm logic kiểm tra thời gian hoàn thành màn chơi, tự động chặn và gắn cờ các request gửi lên API có thời gian vô lý <br>  | 19/06/2026 | 20/06/2026 |  |



### Kết quả đạt được tuần 7:
* Nâng cao tư duy thiết kế API an toàn (Secure API Design), biết cách áp dụng nguyên tắc không tin cậy dữ liệu từ Client (Never trust the client).
* Thành thạo cách sử dụng cơ chế Transaction trong cơ sở dữ liệu NoSQL để xử lý các giao dịch liên quan đến tiền tệ ảo (eCoin/Sanity) một cách nguyên vẹn (ACID compliance).
* Tích lũy kinh nghiệm thực chiến trong việc phân tích các lỗ hổng gian lận game cơ bản và tự xây dựng giải pháp phòng chống (Anti-cheat) hiệu quả.
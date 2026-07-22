---
title: "Worklog Tuần 10"
date: 2026-07-07
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 10:

* Hoàn thành các công việc được giao trong tuần.
* Thực hành và nắm vững các kiến thức liên quan đến AWS và dự án.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 3 | Xây dựng kiến trúc Generic Logging trên Redux cho Minigame: <br> -Thiết kế hệ thống Log: Tạo mới cấu trúc Redux để lưu trữ log thao tác của người chơi. <br> -Tích hợp vào Sudoku Component: Cập nhật Client Sudoku, kết nối với Redux để tự động làm sạch log  <br> (Clear Logs) khi bắt đầu session mới. | 07/07/2026 | 07/07/2026 |  |
| 4 | Tối ưu hoá Payload Anti-cheat (Zero-Trust) và tiết kiệm RCU DynamoDB: <br> - Tối ưu hoá Log Reducer: Thay đổi cơ chế lưu log từ dạng lịch sử tuần tự sang cơ chế ghi đè,giới hạn  <br> độ dài mảng log,giảm tải băng thông và tiết kiệm RCU khi nén gửi lên DynamoDB. | 08/07/2026 | 08/07/2026 |  |
| 5 | Cập nhật hệ thống Anti-cheat, kiến trúc Zero-trust & Đồng bộ dữ liệu Full-stack: <br> -  Tối ưu Anti-cheat đa lớp:Tích hợp thuật toán phân tích log nước đi dựa trên Timestamp. <br> -  Hoàn thiện API Quản lý Ván đấu: <br> +Xử lý kiểm tra tính đúng đắn của bàn cờ giữa trận, trừ và quản lý số lượt kiểm tra (checkCount) trực tiếp  <br> trên DB. <br> +Xử lý nộp bài, tính toán Rank Points, trả thưởng dựa trên thời gian và lượt check còn lại <br>  | 09/07/2026 | 11/07/2026 |  |


### Kết quả đạt được tuần 10:

* Nắm bắt và hoàn thành tốt các chỉ tiêu của tuần.
* Tích lũy thêm kinh nghiệm thực tế về triển khai và quản lý tài nguyên.

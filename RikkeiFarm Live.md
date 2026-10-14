# BÀI 1 – ƯỚC LƯỢNG PRODUCT BACKLOG

Họ tên: Nguyễn Tấn Du – Mã sinh viên: N25DTCN011

## Nhiệm vụ 1 – Kiểm tra dữ liệu trước khi ước lượng

| Mã Story | Đủ rõ | Cần làm rõ | Thông tin/câu hỏi còn thiếu |
|:--:|:--:|:--:|---|
| LS01 | ☐ | ☒ | Đến giờ bắt đầu, Story này có phải xử lý chuyển trạng thái phiên sang trạng thái khác không, hay chỉ hiển thị 'Sắp diễn ra'? |
| LS03 | ☐ | ☒ | Khi hai khách cùng đặt sản phẩm cuối cùng gần như đồng thời, đơn nào được giữ số lượng và đơn còn lại được xử lý thế nào? |

## Nhiệm vụ 2 – Product Backlog đã ước lượng

| Mã Story | Mức ưu tiên | Kết quả phiếu | SP cuối cùng | Lý do ngắn |
|:--:|:--:|:--:|:--:|---|
| LS01 | 1 | 3 - 3 - 5 - 3 | 3 | Phiếu 5 SP của Dev C do lo xử lý thời gian bắt đầu và chuyển trạng thái, nhưng PO xác nhận chỉ cần trạng thái 'Sắp diễn ra' nên phạm vi nhỏ lại. Vì vậy LS01 tương đương LS02 (3 SP). |
| LS02 | 2 | 3 - 3 - 3 - 3 | 3 | Reference Story; các phiếu đã trùng nhau. |
| LS03 | 3 | 5 - 8 - 8 - 5 | 8 | Phiếu lệch do khác nhau về đánh giá rủi ro: đặt đồng thời phải đảm bảo chỉ một đơn giữ được số lượng cuối, cộng thêm quy tắc giảm/hoàn tồn. Độ phức tạp và rủi ro lớn hơn hẳn LS02 nên chốt 8 SP. |

## Nhiệm vụ 3 – Phát hiện cách hiểu sai

Đề xuất '1 SP = 4 giờ' là sai vì Story Point là đơn vị ước lượng tương đối, đo độ lớn tổng hợp của Story (khối lượng, độ phức tạp và rủi ro) so với Reference Story, không đo thời gian; cùng 3 SP, thời gian thực hiện có thể khác nhau tùy người làm và bối cảnh. Thay vì đổi SP sang giờ, nhóm dùng Velocity – tổng SP các Story đã hoàn thành (đạt Definition of Done) trong các Sprint trước – để dự báo số SP có thể nhận trong Sprint tiếp theo và chọn Story cho Sprint Backlog tương ứng.

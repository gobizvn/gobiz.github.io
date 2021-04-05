# Quản lý request cho leader

## Đối tượng áp dụng

Dành cho việc quản lý các request công việc của các leader.

## Cách thức hoạt động

- Khi có việc cần tới leader xử lý thì tạo ticket và assign leader đó làm người xử lý. Các request này có thể đến từ vị trí nhân viên bất kỳ. Trong ticket cần nêu rõ lý do request và tại sao nó lại là cần thiết.
- Giám đốc dự án sẽ review, nếu request đó là cần xử lý sẽ đổi trạng thái sang Cần xử lý.
- Trong vòng 1 ngày làm việc, người nhận được request assign này phải trả lời thông tin:
    + thời gian dự kiến hoàn thành (thông qua việc chọn thời hạn hoàn thành)
    + trong trường hợp không thể hoàn thành đúng thời hạn đã commit, cần phải thông báo trước:
        * 1 tuần đối với những việc hẹn hoàn thành sau 1 tháng trở lên
        * 3 ngày làm việc đối với những việc hẹn hoàn thành sau 2 tuần cho đến 1 tháng
        * 1 ngày làm việc đối với những việc hẹn hoàn thành ngắn hơn 2 tuần
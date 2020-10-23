# Gobiz Performance Race

## Nội dung chương trình

Nhằm có thời gian để review lại kết quả công việc từng tháng để có thể có những phương án nâng cao hiệu suất làm việc.
Đồng thời có lý do để tặng cho những team có nhiều nỗ lực và đạt kết quả tốt những phần quà nho nhỏ, là nơi vinh danh các MVP (Most Valued Players - không phải Minimum Viable Product) 

### Thành phần team

Sẽ bao gồm tất cả dev, tester, techlead, BA, SM tham gia vào công việc của team đó.

### Thời gian áp dụng

Chương trình được áp dụng cho các team phát triển sản phẩm của Gobiz từ tháng 11/2020. Rule hiện tại đã được cập nhật so với bản tháng 10/2020 áp dụng trước cho 3 team để khắc phục một số yếu điểm trước đó.

## Cách thức thực hiện

### Mục tiêu & báo cáo hoàn thành
- Tuần cuối của tháng sẽ đặt mục tiêu và các chỉ số hoàn thành của mục tiêu gửi cho team.
    * Nội dung sẽ được gửi trước cho BA (BA sau đó có thể trao đổi trước với team) trước ngày thứ bảy tuần áp cuối của tháng (ví dụ tháng 11/2020 là 28/11/2020)
    * Nội dung mục tiêu và các chỉ số hoàn thành sẽ được trao đổi ở trong buổi review/plan ở tuần cuối cùng của tháng trước/đầu tháng sau (ví dụ tháng 11 là tuần từ 30/11-5/12).
- Tuần áp cuối của tháng, team làm report công việc tháng trong đó:    
    1. Những mục tiêu/tiêu chí đã hoàn thành. 
        * Bao gồm cả những việc phát sinh (nếu có)
        * Có thể diễn giải chi tiết hơn so với bảng mục tiêu/tiêu chí đặt ra ở đầu tháng        
    2. Những gì chưa làm được và đề xuất nếu có
        * Có thể nêu ra các khó khăn gặp phải của team (bao gồm cả khách quan và chủ quan)
- Người làm report có thể là thành viên bất kỳ trong team. Miễn tôi nhận được báo cáo đúng hạn.
    * Trong trường hợp nộp báo cáo muộn, mỗi ngày kể từ ngày làm việc cuối cùng của tuần yêu cầu nộp báo cáo trừ 5 điểm.

### Đánh giá
Việc đánh giá sẽ không tránh khỏi có những nhận xét mang tính chủ quan từ phía người đánh giá. Quyết định của người đánh giá là quyết định cuối cùng.
Mọi người có quyền góp ý để khắc phục những sai sót của tháng trước để cập nhật cho cách thực hiện ở tháng sau.

Thang điểm được tính trên các tiêu chí sau:

1. Khối lượng công việc
    - Tỉ lệ hoàn thành mục tiêu (%) * 50p (chỉ bao gồm những phần đã được deploy thành công trong tháng)
    - Tại buổi review cuối cùng, team review và phản biện, những chức năng có trải nghiệm dưới trung bình sẽ bị loại ra khỏi hạng mục hoàn thành         
    - Các công việc phát sinh: 0-10p
        * nếu không có việc phát sinh buộc phải làm thì mặc định nhận đủ 10p
        * nếu khối lượng phát sinh lớn hơn 20% so với mục tiêu, có thể đưa ra để thuyết phục người đánh giá để nhận tối đa lên đến 20p. Nếu khối lượng công việc phát sinh vượt quá 50% sẽ hủy mục tiêu ban đầu.
        * nếu khối lượng phát sinh buộc phải làm trong khoảng 20% so với mục tiêu, sẽ căn cứ vào lượng công việc không hoàn thành nếu thống kê chi tiết được. Nếu không thống kê chi tiết sẽ tính theo thang như sau:
            - hoàn thành toàn bộ: 10p
            - hoàn thành trên 50%: 6p
            - hoàn thành dưới 50%: 3p
2. Chất lượng
    * Đánh giá chất lượng (dựa trên trải nghiệm, giao diện, chức năng): 10p. Tại buổi review cuối cùng, team thực hiện demo điểm nổi bật về trải nghiệm cho những gì đã làm & phản biện đánh giá. Chỉ được điểm nếu có trải nghiệm được đánh giá tốt, từ trung bình trở xuống 0p.
    * Tình hình có bug trên Production: 10p (nếu không có bug level High trở lên), trừ dần theo nguyên tắc (không tính các bug do nguyên nhân phần cứng)
        - Critical: -10p
        - High: -5p
        - Việc report bug Production từ level Medium trở lên là bắt buộc trong vòng 3 ngày kể từ ngày phát hiện ra lỗi.
        - Với mỗi ngày báo cáo chậm trừ 1p, trừ không giới hạn.        
    * Dựa trên review được làm từ khảo sát chất lượng phục vụ của khách hàng hoặc bộ phận/phòng ban khác: 20p. Khi khảo sát sẽ cho đánh giá từ 1-5 sao và tính điểm theo tiêu chí như sau:
        * 1 sao: 0p
        * 1.5-2.5 sao: 3p
        * 3 sao: 5p, 3.5: 8p
        * 4 sao: 12p, 4.5: 16p
        * 5 sao: 20p

Các phần trên đánh giá tối đa được 110p/100p (đã bao gồm điểm cộng thêm tối đa 10p khi khối lượng phát sinh quá lớn)        

Ngoài ra team sẽ nhận được điểm thưởng nếu có:

1. Chuyên cần & kỷ luật: điểm thưởng 10p nếu:
    - Không có bất kỳ ai vi phạm đi muộn
    - Đi làm đầy đủ (làm việc từ xa tối đa 1 buổi/người/tháng, không tính nghỉ phép)
    - Không vi phạm bất kỳ hình thức kỷ luật khác
2. Tham gia các hoạt động khác như tổ chức đào tạo, sự kiện chia sẻ,... điểm cộng tùy trường hợp

### Khen thưởng & kỷ luật
- Nếu team đạt dưới 60p, yêu cầu team donate quỹ 500K (việc mỗi cá nhân donate bao nhiêu team tự quyết định)
- Nếu team đạt thấp hơn 30p sẽ kỷ luật không hoàn thành nhiệm vụ được giao.
- Team có thành tích tốt nhất/tháng và > 75p sẽ nhận được:
    * tiền mặt: 2M (tiền thưởng đến từ quỹ riêng của hoạt động này, cá nhân tôi donate toàn bộ phần thiếu)
    * kể cả không đạt 75p: vinh danh nội bộ Gobiz, đồng thời team đề cử 1 cá nhân có nhiều đóng góp nhất
    * cá nhân có nhiều đóng góp nhất: thưởng riêng 100k và vinh danh nội bộ Gobiz. Nếu công ty Vela có áp dụng hình thức vinh danh cá nhân thuộc bộ phận tháng đó sẽ đề cử cá nhân này. 

> Lưu ý: Điểm thành tích ở đây không mang tính quyết định đối với các kỳ review, nhưng những thành tích nổi bật của team và cá nhân sẽ có ảnh hưởng tích cực.
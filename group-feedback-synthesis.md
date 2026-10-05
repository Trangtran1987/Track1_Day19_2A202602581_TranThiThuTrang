# Tổng hợp feedback prototype của nhóm

> Tổng hợp ba phiên test có ghi nhận hành vi cụ thể: phiên Nguyễn Thị Hồng Nhung, Phan Thị Khánh Linh và Trần Thị Thu Trang facilitate. Báo cáo so sánh prototype của Phương Anh được dùng làm dữ kiện bổ sung ở cuối, không tính là một phiên test thứ tư vì không ghi riêng hành vi của một tester.

## Nội dung đối chiếu

| Nội dung đối chiếu | Feedback 1 — Tester phiên Nhung | Feedback 2 — Tester phiên Linh | Feedback 3 — Tester phiên Trang | Quy luật lặp lại (Pattern) hoặc điểm đối lập |
| --- | --- | --- | --- | --- |
| **First Action — Điểm chạm đầu tiên** | Xem lần lượt cả ba option; dừng lại sử dụng Option C đầu tiên vì thấy dễ hiểu, dễ dùng. | Mở notification AI trước Cloud 13, đọc nội dung được gợi ý và lý do đề xuất. | Bấm vào các nút lựa chọn và nhìn các ô lựa chọn trên màn hình. | Tester bắt đầu từ những điểm chạm khác nhau: chọn option, notification AI hoặc các nút trên giao diện. |
| **Major Breakdown — Điểm tắc nghẽn lớn nhất** | Ở Option B, do dự và phải đọc nhiều mới biết cần ôn nội dung gì. | AI bỏ sót điểm ① trong recommendation. Tester chưa lập tức nhận ra danh sách chưa đầy đủ; ghi chú chưa xác nhận rõ tester có mở “Xem tất cả” trong phiên hay không. | Nhiều lựa chọn làm tester lúng túng. | Có ma sát ở cách trình bày/lựa chọn (phiên Nhung và Trang); riêng phiên Linh cho thấy rủi ro recommendation AI không đầy đủ. |
| **Control Taken — Cách lấy lại quyền kiểm soát** | Đối chiếu nội dung AI với slide buổi 12; khi chưa hài lòng, hỏi AI lần nữa. | “Xem tất cả” được thiết kế để xem các điểm chưa hiểu ngoài recommendation và có thể phát hiện điểm ① bị bỏ sót. Phiếu ghi nhận chưa cho biết chắc tester đã sử dụng nút này hay chưa. | Dùng nút Back để quay lại từ đầu và thao tác lại. | Có các cách kiểm soát khác nhau: đối chiếu nguồn, xem toàn bộ danh sách hoặc quay lại thao tác. Chưa có bằng chứng cho thấy mọi tester đều chủ động kiểm tra tính đầy đủ của AI. |
| **Selected Option — Phương án được chọn** | **Option C** | **Option B** | **Option C** | Option C được chọn trong 2/3 phiên; Option B được chọn trong 1/3 phiên. |
| **Key Trade-off — Sự đánh đổi then chốt** | Chấp nhận tự ghi 3 note để đổi lấy giao diện dễ hiểu, dễ sử dụng. | Giảm công sức tự rà soát nhờ AI gợi ý, nhưng có rủi ro bỏ sót nội dung nếu phụ thuộc vào recommendation. | Sẵn sàng ghi lại câu hỏi để giao diện dễ sử dụng hơn. | Hai tester chọn C chấp nhận tự ghi nội dung để có trải nghiệm dễ dùng; tester chọn B ưu tiên tiết kiệm công sức nhưng đối mặt rủi ro AI bỏ sót. |

## Dữ kiện bổ sung từ báo cáo của Phương Anh

- **Guide Point AI:** phần giải thích khác biệt giữa các khái niệm còn khó hiểu; cần ngôn ngữ cơ bản và ví dụ thực tế hơn.
- **AI Notes Reviewer:** sắp xếp ghi chú giúp nội dung rõ ràng hơn, nhưng chưa đủ tạo ấn tượng.
- **Review 3 Points:** ý tưởng gợi ý nội dung cần ôn được đánh giá là hữu ích, nhưng người dùng có thể không thực sự ôn nếu còn tốn công.
- Báo cáo gợi ý hành trình **Organize → Understand → Review → Act** và nhấn mạnh cần giảm ma sát để người học thực sự hành động.

### Quyết định hành động tiếp theo của cả nhóm

- **Đúng một Next Change đề xuất:** Ở Option B, làm nút **“Xem tất cả điểm chưa hiểu”** hiển thị rõ ngay cạnh recommendation và nêu rõ recommendation chỉ là gợi ý, có thể chưa đầy đủ.
- **Dữ kiện thực tế dẫn đến đề xuất:** Tester phiên Linh nhận recommendation nhưng AI bỏ sót điểm ①; “Xem tất cả” là cơ chế được thiết kế để người học kiểm tra danh sách đầy đủ. Tester phiên Nhung phải đọc nhiều mới biết cần ôn gì ở Option B, còn tester phiên Trang lúng túng trước nhiều lựa chọn. Vì vậy, đường dẫn kiểm tra đầy đủ cần dễ nhận ra và ít gây thêm do dự.
- **Still Unproven:** Chưa chứng minh tester sẽ tự mở “Xem tất cả” khi không được nhắc, phát hiện và xử lý phần AI bỏ sót; chưa biết lời nhắc ôn có khiến người học thực sự quay lại và hoàn thành việc ôn tập hay không. Ba phiên test cũng chưa đủ để kết luận prototype giúp ghi chú dễ tìm lại hoặc cải thiện kết quả học lâu dài.
# Track1_Day19_2A202602581_TranThiThuTrang

Day 19 — Three prototypes, one next change

| Tệp | Nội dung |
|---|---|
| [three-option-design-sheet.md](three-option-design-sheet.md) | Hypothesis Problem, Option A/B/C, Comparison Contract, Human–AI Decision Table |
| [prototype-link.md](prototype-link.md) | Link prototype A/B/C chung của nhóm và cách dùng khi test |
| [prototype/index.html](prototype/index.html) | Mã nguồn prototype |
| [prototype-feedback-note.md](prototype-feedback-note.md) | Feedback Note của phiên do tôi facilitate |
| [group-feedback-synthesis.md](group-feedback-synthesis.md) | Tổng hợp feedback của cả nhóm |
| [ai-support-log.md](ai-support-log.md) | Nhật ký sử dụng AI |

---

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202602581
- **Họ tên:** Trần Thị Thu Trang
- **Tên nhóm:** NaCl
- **Case:** B — AI Notes: Personal Learning Notes

| Họ tên | MHV |
|---|---|
| Nguyễn Thị Hồng Nhung | 2A202602557 |
| Phan Thị Khánh Linh | 2A202602360 |
| Trần Thị Thu Trang | 2A202602581 |
| Hồ Hoàng Phương Anh | 2A202602460 |

## 2. Hypothesis Problem

> **Người học** khi học nội dung mới, nhiều khái niệm liên quan nhau, có ghi lại những phần chưa hiểu hoặc muốn xem lại, **nhưng ghi chép rời rạc, không có cấu trúc** nên sau đó **khó tìm lại và thường không quay lại xử lý** → đến phần học sau thì đã quên nội dung trước.

- **Nối với Day 17:** Day 17 ưu tiên điều tra Pain A (khó ghi nhận). Bốn Practice Notes cho thấy cả bốn người đều tự ghi nhận được, trong khi N2 và N4 có hậu quả rõ ở khâu sau khi ghi (khó tìm lại, quên xem lại) → nhóm chuyển trọng tâm sang Pain B, giữ nguyên case, actor, situation và JTBD.
- **Chưa biết:** nguyên nhân không quay lại (ghi lộn xộn, thiếu thời gian/động lực, hay không có gì nhắc); tần suất và công sức; tác động thật đến kết quả học.
- Chi tiết evidence: [three-option-design-sheet.md § 1](three-option-design-sheet.md#1-hypothesis-problem).

## 3. Three Solution Options

| | Option | Người–AI chia việc | Nguyên nhân đặt cược |
|---|---|---|---|
| **A** | [AI sắp xếp, người duyệt](https://ai-notes-reviewer.lovable.app/) | AI gom ghi chú rời thành danh sách điểm chưa hiểu có nguồn; người sửa và xác nhận trước khi lưu | Ghi chép lộn xộn, không tìm lại được |
| **B** | [AI nhắc ôn, người chọn](https://claude.ai/artifact/K8ySz6YsVtj23u3tQUiMRS) | Trước buổi học sau, AI gợi ý điểm cần ôn kèm lý do và mức liên quan; người chọn ôn ngay / để sau / bỏ qua | Quên, không có gì nhắc quay lại |
| **C** | [Người tự đánh dấu, AI hỗ trợ khi hỏi](https://guide-point-ai-73.lovable.app) | Người tự viết checklist; AI chỉ giải thích khi được hỏi, có trích slide; người tự đánh dấu đã hiểu | Quay lại nhưng không biết xử lý thế nào |

Cả ba dùng chung user, situation, task, nội dung mẫu và desired outcome; chỉ khác cơ chế. Mỗi option có một tình huống AI sai cài sẵn để quan sát khả năng phát hiện và phục hồi.

## 4. Đóng góp của tôi trong nhóm

- **Option phụ trách chính:** Option B.
- **Shared context:** Tôi xây dựng shared context cho Option B: trước buổi học sau, AI gợi ý điểm cần ôn kèm lý do và mức liên quan; người học chọn ôn ngay / để sau / bỏ qua. Mục tiêu là để người học chủ động lựa chọn hành động ôn tập và nhắc nhở để tránh việc quên xem lại.
- **Human–AI decisions:** Tôi xác định người học chủ động lựa chọn hành động ôn tập và tự quyết định khi nào đã hiểu.  AI sẽ gợi ý phần nội dung cần ôn tập dựa vào phần take note của người học, giải thích các nội dung khó hiểu trên slide gốc và có nhắc nhở ôn tập.
- **Phiên test tôi facilitate:** Tôi facilitate phiên test với bạn Hoàng Quốc Dũng (2A202602523). Tester trải nghiệm cả ba option A, B, C.
- **Tổng hợp feedback tôi tham gia:** Tester chọn Option C vì dễ hiểu, dễ sử dụng và chấp nhận tự viết tay 3 note. 
- **Phần AI hỗ trợ và phần tôi thực hiện:** AI hỗ trợ tôi xây dựng prototype; tôi phụ trách thiết kế luồng và nội dung. Khi giao diện AI tạo ra chưa đúng kỳ vọng, tôi mô tả yêu cầu chi tiết hơn để AI chỉnh sửa.

## 5. Prototype Feedback

- **Observation từ phiên tôi facilitate:** Tester xem cả ba option theo thứ tự A, B, C và dừng lại dùng Option C đầu tiên vì thấy dễ hiểu, dễ sử dụng. Ở Option B, tester do dự và phải đọc nhiều mới biết cần ôn gì. Tester chọn Option C, chấp nhận tự ghi 3 note; khi chưa hài lòng với câu trả lời, tester đối chiếu slide buổi 12 rồi hỏi AI lần nữa. Chi tiết tại [prototype-feedback-note.md](prototype-feedback-note.md).
- **Tổng hợp feedback của nhóm:** xem [group-feedback-synthesis.md](group-feedback-synthesis.md).
  - **Pattern:** Option C được chọn trong 2/3 phiên; người thử chấp nhận tự ghi nội dung để đổi lấy trải nghiệm dễ dùng. Các phiên cũng cho thấy ma sát khi phải hiểu nhiều lựa chọn hoặc tìm nội dung cần ôn.
  - **Khác biệt:** Tester phiên Linh chọn Option B để giảm công sức tự rà soát; tuy nhiên, AI bỏ sót một điểm chưa hiểu. Các tester cũng dùng cách khác nhau để lấy lại quyền kiểm soát: đối chiếu slide, xem toàn bộ danh sách hoặc quay lại thao tác.
- **Next Change đề xuất:** Làm nút **“Xem tất cả điểm chưa hiểu”** dễ nhận ra bên cạnh recommendation của Option B, đồng thời nói rõ gợi ý của AI có thể chưa đầy đủ. Đây là đề xuất rút ra từ feedback, chưa khẳng định là quyết định cuối cùng nhóm đã thống nhất.
- **Still Unproven:** Chưa biết người học có tự kiểm tra danh sách đầy đủ, phát hiện và xử lý phần AI bỏ sót hay không; cũng chưa chứng minh lời nhắc giúp họ thực sự quay lại ôn tập hoặc cải thiện khả năng ghi nhớ/kết quả học.

## 6. AI Support Log

Chi tiết: [ai-support-log.md](ai-support-log.md)

- **Công cụ và AI đã giúp gì:** Nhóm dùng Lovable để xây dựng prototype Option A/C và Claude Artifacts cho Option B. AI hỗ trợ làm rõ đề bài, tổng hợp evidence, đề xuất các option và bảng quyết định Human–AI, tạo mã prototype, nội dung/dữ liệu mẫu và canned output, cũng như khung tài liệu.
- **AI sai hoặc chưa phù hợp:** Giao diện AI tạo ra có lúc chưa đúng kỳ vọng về luồng và cách trình bày, cần mô tả lại cụ thể hơn. Các prototype dùng canned output, không kết nối AI thật nên không thể dùng để kết luận về độ chính xác của AI thật. Ngoài điểm chưa phù hợp về giao diện, chưa có lỗi cụ thể nào khác được ghi nhận trong log.
- **Tôi tự rà soát/chỉnh sửa:** Tôi phụ trách thiết kế luồng và nội dung Option B; khi giao diện chưa phù hợp, tôi bổ sung mô tả chi tiết để AI chỉnh sửa. Tôi cũng rà soát nội dung, cách chia quyền quyết định giữa người học và AI, và đối chiếu feedback tester với nguồn slide buổi 12. Chi tiết tại [ai-support-log.md](ai-support-log.md).
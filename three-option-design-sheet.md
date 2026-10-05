# Three-Option Design Sheet — Nhóm NaCl

- **Case:** B — AI Notes: Personal Learning Notes
- **Thành viên:** Nguyễn Thị Hồng Nhung (2A202602557) · Phan Thị Khánh Linh (2A202602360) · Trần Thị Thu Trang (2A202602581) · Hồ Hoàng Phương Anh (2A202602460)
- **Prototype:** [A](https://ai-notes-reviewer.lovable.app/) · [B](https://claude.ai/artifact/K8ySz6YsVtj23u3tQUiMRS) · [C](https://guide-point-ai-73.lovable.app) (chi tiết trong [prototype-link.md](prototype-link.md))

---

## 1. Hypothesis Problem

### 1.1. Giả thuyết Day 17

- **Situation:** Khi học một bài có nhiều kiến thức mới hoặc khó.
- **JTBD:** Khi học một bài có nhiều kiến thức mới, tôi muốn xác định và lưu giữ những điểm quan trọng/chưa hiểu để có thể ôn tập có trọng tâm.
- **Pain A — Khó ghi nhận:** khó vừa theo dõi bài vừa ghi nhận điểm quan trọng/chưa hiểu → bỏ sót hoặc quên.
- **Pain B — Không quay lại xử lý:** nhận ra mình chưa hiểu nhưng không quay lại xử lý.
- **Ưu tiên điều tra Day 17:** Pain A.

### 1.2. Evidence từ 4 Practice Notes

| Quan sát | N1 | N2 | N3 | N4 |
|---|:-:|:-:|:-:|:-:|
| Có ghi lại phần chưa hiểu/quan trọng để xử lý sau | ✔ | ✔ | ✔ | ✔ |
| Khó tìm lại nội dung đã ghi/đã học | – | ✔ | – | ✔ |
| Quên nội dung / quên xem lại | ✔ | ✔ | – | ✔ |
| Đã dùng AI trong quy trình ghi/học | – | ✔ | – | ✔ |

Trích dẫn và hành vi chính:
- **N2:** chụp màn hình → dùng AI chuyển thành văn bản → lưu file; ghi chép không có cấu trúc nên không rõ mình đã ghi gì, khó tìm lại → **quên xem lại**.
- **N3:** “Những chỗ chưa rõ, mình ghi lại để có thể hỏi thêm hoặc xem lại tài liệu sau.”
- **N4** (transcript, chưa đối chiếu audio): “mình sẽ càng về sau mình học thì mình sẽ càng quên những nội dung từ trước” — và khó tìm lại phần cần xem.
- **N1:** phần chưa hiểu được để lại nghiên cứu “khi có thời gian”.

### 1.3. Đối chiếu với giả thuyết

| Giả thuyết | Evidence | Kết luận |
|---|---|---|
| Pain A | Cả 4 người đều tự ghi nhận được; không ai kể bị bỏ sót vì không kịp ghi | **Yếu đi** — chạm điều kiện bác bỏ “learner đã có cách giải quyết” |
| Pain B | N2, N4 có hậu quả rõ (quên, khó tìm lại); N1, N3 có ghi để xử lý sau | **Được ủng hộ một phần** |

→ Giữ nguyên case, actor, situation và JTBD; **chuyển trọng tâm từ Pain A sang Pain B**.

### 1.4. Hypothesis Problem cho Day 18

> **Người học** khi học nội dung mới, nhiều khái niệm liên quan nhau, có ghi lại những phần chưa hiểu hoặc muốn xem lại, **nhưng ghi chép rời rạc, không có cấu trúc** nên sau đó **khó tìm lại và thường không quay lại xử lý** → đến phần học sau thì đã quên nội dung trước.

### 1.5. Still Unknown

1. **Nguyên nhân** không quay lại: ghi lộn xộn khó tìm, thiếu thời gian/động lực, hay không có gì nhắc?
2. **Tần suất** tình huống và **thời gian/công sức** mất khi tìm lại.
3. **Tác động thật** đến kết quả học.
4. N1, N3 có thực sự quay lại phần đã ghi không.
5. Thời điểm các câu chuyện (tiêu chí 7 ngày) và độ chính xác transcript N4.

> Đây là giả thuyết, **chưa được validated**. Bốn phỏng vấn luyện tập chỉ đủ để chọn hướng thử.

---

## 2. Ba Solution Options

**Critical interaction:** khoảnh khắc người học **quay lại với những điểm “chưa hiểu”** đã ghi từ buổi trước — tìm lại → xử lý → biết mình còn thiếu gì.

Mỗi option đặt cược vào một **nguyên nhân khác nhau** của việc không quay lại:

| | Option | Nguyên nhân đặt cược | Từ Parking Lot | Người phụ trách |
|---|---|---|---|---|
| **A** | **AI sắp xếp, người duyệt** — AI gom ghi chú rời thành danh sách “Điểm chưa hiểu” có cấu trúc, gắn nguồn; người sửa và xác nhận trước khi lưu | Ghi chép lộn xộn, không tìm lại được (N2, N4) | #1, #4 | |
| **B** | **AI nhắc ôn, người chọn** — trước buổi học sau, AI đề xuất điểm cần ôn kèm lý do và mức liên quan; người chọn ôn ngay / để sau / bỏ qua | Quên, không có gì nhắc quay lại (N2, N1) | #4 | |
| **C** | **Người tự đánh dấu, AI hỗ trợ khi hỏi** — người tự điền checklist điểm chưa hiểu; khi mở lại, bấm “Hỏi AI” để được giải thích có trích slide; người tự đánh dấu đã hiểu | Quay lại nhưng không biết xử lý thế nào (N1, N3, N4) | #3, #5 | |

### Khác biệt về cơ chế (không phải giao diện)

| | A | B | C |
|---|---|---|---|
| Ai **khởi động** việc quay lại? | Người | **AI** | Người |
| Ai **tổ chức** ghi chú? | **AI** | AI | **Người** |
| Ai **xử lý** điểm chưa hiểu? | Người | Người (theo gợi ý) | Người + **AI giải thích** |

```
AI chủ động nhiều ◄──────────────────────────────► Người chủ động nhiều
        A                       B                        C
```

---

## 3. Comparison Contract

| Yếu tố | Giống nhau ở A/B/C |
|---|---|
| **User** | Người học vừa học một buổi có nhiều khái niệm mới |
| **Situation** | 2 ngày sau buổi “Cloud 12 — Agent không phải Web App bình thường”; ngày mai học buổi 13 có dùng lại kiến thức này |
| **Task** | “Ngày mai bạn học buổi tiếp theo. Hãy xử lý những điểm bạn đã ghi là chưa hiểu từ buổi trước.” |
| **Content** | Cùng bộ ghi chú giả lập (synthetic data do nhóm tạo): 2 ảnh slide, 3 dòng text, 1 câu hỏi; gồm 3 điểm chưa hiểu: ① vì sao Agent chạy lâu bị giới hạn thời gian của gateway/proxy · ② vì sao Agent cần lưu trạng thái/lịch sử hội thoại · ③ vì sao gửi lại lịch sử hội thoại làm tăng token/chi phí |
| **Canned AI output** | Một bộ viết sẵn dùng chung, cùng chất lượng và độ dài |
| **Desired outcome** | Tester tìm lại được các điểm chưa hiểu, xử lý ít nhất 1 điểm, và biết mình còn điểm nào chưa xong |
| **Độ hoàn thiện** | Mỗi option 3 trạng thái, cùng visual components |
| **Chỉ được khác** | Cơ chế chia việc người–AI |

**Nguyên tắc chung cho cả ba option:**
1. AI không bao giờ xóa hay sửa ghi chú gốc.
2. Chỉ người học được đánh dấu “Đã hiểu”.
3. Mỗi option có đúng 1 tình huống AI sai được cài sẵn để quan sát khả năng phát hiện và phục hồi.

---

## 4. Human–AI Decision Table

| | **A — AI sắp xếp, người duyệt** | **B — AI nhắc ôn, người chọn** | **C — Người tự đánh dấu, AI hỗ trợ khi hỏi** |
|---|---|---|---|
| **Critical interaction** | Duyệt danh sách “Điểm chưa hiểu” do AI gom, trước khi lưu | Nhận lời nhắc “Trước buổi 13” và quyết định ôn điểm nào | Mở một điểm trong checklist, bấm “Hỏi AI”, tự đánh giá đã hiểu chưa |
| **Expectation** | “AI đã sắp xếp 6 ghi chú của bạn thành 3 điểm chưa hiểu. AI có thể xếp nhầm nhóm hoặc bỏ sót — hãy kiểm tra trước khi lưu.” AI không giải thích nội dung, không xóa ghi chú gốc. | “AI gợi ý dựa trên các điểm bạn đã đánh dấu và đề cương buổi 13. AI không biết bạn đã tự ôn ở nơi khác.” AI không chấm bạn đã hiểu chưa. | “AI chỉ giải thích dựa trên slide buổi 12 và có thể sai — hãy đối chiếu với slide được trích.” AI không tự thêm/xóa mục. |
| **Role & Agency** | **AI:** phân loại, gắn nguồn, đề xuất tên mục. **Người:** đổi tên, chuyển nhóm, xóa, thêm mục. **Quyết:** người — chỉ lưu khi bấm “Xác nhận”. | **AI:** chọn điểm, thứ tự, thời điểm nhắc. **Người:** chọn *Ôn ngay / Tối nay / Bỏ qua*, thêm điểm AI không gợi ý. **Quyết:** người. | **Người:** viết checklist, chọn điểm, quyết định hỏi AI, tự đánh dấu. **AI:** chỉ trả lời khi được gọi. **Quyết:** người. |
| **Evidence & Uncertainty** | Mỗi mục hiện “Từ ghi chú:” (nguồn gốc). Mục không chắc gắn “AI không chắc — kiểm tra lại”. Ghi chú không xếp được vào “Chưa phân loại”. | Mỗi gợi ý có lý do (vd: “Buổi 13 có phần ‘Lưu session cho Agent’ — liên quan điểm ②”) và mức “Liên quan cao” / “Có thể liên quan”. | Trả lời trích “Theo slide 8: …” kèm nút mở slide. Khi vượt ngoài slide: “Slide buổi 12 không nói rõ điều này — độ tin cậy thấp hơn.” |
| **Control & Recovery** | Sửa / xóa / gộp / chuyển từng mục · Hoàn tác · Xem ghi chú gốc · “Bỏ qua sắp xếp của AI” | Hoãn / bỏ qua từng gợi ý (không mất dữ liệu) · “Gợi ý này không đúng” · “Xem tất cả điểm chưa hiểu” · đổi/tắt giờ nhắc | “Giải thích cách khác” · “Chưa đúng/chưa rõ” · mở slide gốc · *Đã hiểu / Vẫn chưa hiểu / Hỏi giảng viên* (đổi lại được) |
| **Tình huống AI sai cài sẵn** | Xếp ghi chú “slide 9 — ví dụ chi phí token” vào nhóm ① thay vì ③ | Bỏ sót điểm ①; một gợi ý yếu gắn “Có thể liên quan” | Câu trả lời về ③ nằm ngoài slide, kèm cảnh báo độ tin cậy thấp |
| **Hành vi cần quan sát** | Tester phát hiện và chuyển ghi chú sai nhóm, hay xác nhận ngay | Tester đọc lý do/mức chắc, tìm ra ① qua “Xem tất cả”, hay chỉ làm theo gợi ý | Tester để ý cảnh báo, mở slide đối chiếu, hay tin ngay |

---

## 5. Trạng thái micro-prototype

| | S1 — Trước | S2 — AI can thiệp | S3 — Sau quyết định của người |
|---|---|---|---|
| **A** | 6 ghi chú rời, nút “Sắp xếp giúp tôi” | 3 nhóm + “Chưa phân loại”, nguồn từng mục, 1 nhãn “AI không chắc”, lỗi xếp nhầm cài sẵn; Sửa / Hoàn tác / Xác nhận | Danh sách đã lưu; mỗi điểm mở được ghi chú gốc, có nút “Đã hiểu” |
| **B** | Thông báo “Ngày mai học buổi 13 — có 2 điểm bạn nên xem lại trước” | Thẻ gợi ý có lý do + mức liên quan + *Ôn ngay / Tối nay / Bỏ qua*; link “Xem tất cả”; điểm ① bị bỏ sót | Ôn 1 điểm: ghi chú gốc + slide; “Đã hiểu / Vẫn chưa hiểu”; tổng kết lượt ôn |
| **C** | Checklist tự điền 3 mục, đều “Chưa hiểu” | “Hỏi AI” → trả lời có trích slide; mục ③ trả lời ngoài slide kèm cảnh báo; mở slide / giải thích cách khác / chưa đúng | Tự chọn *Đã hiểu / Vẫn chưa hiểu / Hỏi giảng viên*; checklist “1/3 đã hiểu” |

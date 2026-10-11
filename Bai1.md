# Bài làm: Chuẩn hóa nhịp Sprint của đội RikkeiGo

## Phần 1: Phân tích

| Quy tắc | Đúng/Sai | Vi phạm sự kiện/Artifact nào | Trụ cột bị ảnh hưởng | Hậu quả thực tế (hoặc lý do đúng) |
| :--- | :---: | :--- | :--- | :--- |
| **QT1.** Độ dài Sprint linh hoạt: tuần nhiều việc thì kéo dài 3–4 tuần, ít việc thì rút còn 1 tuần. | **Sai** | Sự kiện Sprint (tính chất khung thời gian cố định / Timebox) | Minh bạch | Đội phát triển mất nhịp làm việc ổn định, còn người dùng không thể biết trước thời điểm nhận bản cập nhật mới. |
| **QT2.** Cuối Sprint, đội trình diễn cho người dùng thử mọi thứ đã code, kể cả phần chưa kiểm thử, để họ thấy đội làm việc chăm chỉ. | **Sai** | Artifact Increment (tiêu chuẩn Definition of Done) và sự kiện Sprint Review | Minh bạch, Thanh tra | Người dùng liên tục gặp lỗi khi trải nghiệm, dẫn đến phản hồi bị sai lệch và làm giảm độ tin cậy của sản phẩm. |
| **QT3.** Sau buổi Sprint Review, Đức cập nhật lại Product Backlog dựa trên góp ý của người dùng thử. | **Đúng** | — | — | Product Owner tiếp nhận phản hồi thực tế từ Sprint Review để cập nhật Product Backlog là hoạt động chuẩn nhằm thích nghi sản phẩm. |
| **QT4.** Sprint vừa rồi không có sự cố nào nên đội bỏ buổi Sprint Retrospective cho đỡ tốn thời gian. | **Sai** | Sự kiện Sprint Retrospective | Thanh tra, Thích nghi | Đội không rà soát lại cách làm việc và chất lượng kỹ thuật, khiến những lỗi cũ tiếp tục lặp lại ở các Sprint sau. |

---

## Phần 2: Sửa lỗi

1. **QT1 (Độ dài Sprint):** Đội RikkeiGo thống nhất cố định độ dài Sprint là 2 tuần trong suốt quá trình phát triển để duy trì nhịp phát hành ổn định.
2. **QT2 (Nội dung trình diễn tại Sprint Review):** Đội chỉ trình diễn cho người dùng những phần việc đã hoàn tất kiểm thử và đáp ứng trọn vẹn Định nghĩa hoàn thành (Definition of Done).
3. **QT4 (Tổ chức Sprint Retrospective):** Đội RikkeiGo duy trì tổ chức Sprint Retrospective ở cuối mỗi Sprint để tìm nguyên nhân gốc rễ của các lỗi tồn đọng và cải tiến quy trình làm việc.

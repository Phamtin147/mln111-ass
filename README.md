# MLN111 - Ứng Dụng Ôn Tập: Học Thuyết Hình Thái Kinh Tế - Xã Hội

> Dự án bài tập / sản phẩm mini hỗ trợ học tập môn **Triết học Mác – Lênin (MLN111)** dành cho sinh viên.

---

## 🌟 Tính Năng Chính Của Ứng Dụng

1. **Thẻ Flashcards tương tác (Phong cách Quizlet):**
   - 10 thẻ lật 2 mặt (3D Flip Card) với hiệu ứng mượt mà.
   - Hỗ trợ phím tắt: **Space** (Lật thẻ), **Mũi tên Trái/Phải** (Chuyển thẻ).
   - Chức năng Xáo trộn thẻ ngẫu nhiên (**Shuffle**) và Bắt đầu lại (**Reset**).
   - Hiển thị danh mục tóm tắt toàn bộ 10 thuật ngữ.

2. **Bài thi trắc nghiệm tính điểm tự động (Quiz):**
   - 10 câu hỏi chuẩn bám sát đề thi Triết học Mác - Lênin.
   - Phản hồi đúng/sai tức thì với màu sắc trực quan (Xanh / Đỏ).
   - Có mục **Giải thích chi tiết** lý do vì sao đáp án đó đúng.
   - Đếm điểm theo thời gian thực và bắn pháo hoa ăn mừng (**Confetti**) khi đạt điểm cao.

3. **Sơ đồ tiến trình 5 Hình thái Kinh tế - Xã hội:**
   - Dòng thời gian trực quan từ *Cộng sản nguyên thủy* $\rightarrow$ *Chiếm hữu nô lệ* $\rightarrow$ *Phong kiến* $\rightarrow$ *Tư bản chủ nghĩa* $\rightarrow$ *Cộng sản chủ nghĩa*.
   - Phân tích rõ từng giai đoạn theo 3 yếu tố: **LLSX**, **QHSX**, **Kiến trúc thượng tầng**.
   - Mục đặc biệt: **Góc liên hệ thực tiễn Việt Nam** (giải thích việc bỏ qua chế độ TBCN).

4. **Tài liệu bỏ túi (Cheat Sheet lý thuyết cốt lõi):**
   - Tóm tắt 4 nội dung then chốt: Cấu trúc hình thái KT-XH, Quy luật QHSX phù hợp với trình độ LLSX, Mối quan hệ biện chứng CSHT - KTTT, Tính lịch sử - tự nhiên.

---

## 🚀 Hướng Dẫn Deploy Lên Surge (Miễn phí 100%)

Nếu bạn muốn deploy web lên mạng internet ngay trong 30 giây bằng **Surge**:

### Bước 1: Cài đặt Surge (nếu máy chưa có)
```bash
npm install --global surge
```

### Bước 2: Chạy lệnh deploy
Tại thư mục chứa dự án:
```bash
surge . mln111-triethoc.surge.sh
```
*(Bạn có thể thay `mln111-triethoc.surge.sh` bằng bất kỳ tên miền con nào bạn thích)*

---

## 🛠️ Công Nghệ Sử Dụng
- HTML5 / CSS3 / JavaScript thuần (ES6+)
- **Tailwind CSS CDN** cho giao diện hiện đại & responsive trên cả điện thoại và máy tính.
- **FontAwesome 6** & Google Fonts (Inter).
- **Canvas-Confetti** tạo hiệu ứng chúc mừng khi hoàn thành bài quiz.

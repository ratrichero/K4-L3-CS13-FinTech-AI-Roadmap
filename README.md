# K4-L3-CS13-FinTech-AI-Roadmap

**Khóa học:** AI in Action · Track 1 · Khóa 4  
**Nhóm thực hiện:** FinTech  
**Đề bài:** Đề 3 · RaViện — Trợ lý soạn nháp tóm tắt ra viện cho bác sĩ khoa nội  

---

## 1. Cấu trúc bài nộp trong Repository

- `FinTech_CS13.xlsx`: File bài làm chính với đầy đủ 8 sheet đã được điền và tự kiểm tra đạt chuẩn 8/8.
- `team/TEAM.md`: Danh sách thành viên, MSSV và phân công vai trò phụ trách (chuẩn template môn học).
- `report/team/2A202602560_TaVietCuong.md`: Báo cáo đóng góp cá nhân theo skeleton bổ sung của repo.
- `Slide_LanhDao.md`: Slide tóm tắt lộ trình 1 trang dành cho lãnh đạo (Nhiệm vụ 5).
- `Slide_LanhDao.html`: Bản thiết kế web slide 1 trang executive presentation.
- `.gitignore`: Loại trừ các file rác và file tạm lock của Excel.

---

## 2. Tóm tắt 3 câu hỏi cốt lõi của Lộ trình (AI Roadmap)

1. **Làm gì trước?**
   - **Ưu tiên số 1 (Rank 1):** Sửa lỗi nghiêm trọng liều insulin và tự động đối chiếu thuốc ra viện với y lệnh nội trú cuối cùng (Việc 2 - 9.03 điểm).
   - **Ưu tiên số 2 (Rank 2):** Soạn nháp diễn biến và chẩn đoán từ hồ sơ EMR để giảm 65% thời gian viết tóm tắt của bác sĩ (Việc 1 - 5.10 điểm).
   - **Việc không làm:** Mã hóa bệnh cho thanh toán bảo hiểm (Việc 6) vì bệnh viện đã có sẵn phần mềm chuyên dụng.

2. **Khi nào để AI tự làm nhiều hơn?**
   - **Mức 1 (Hỗ trợ có duyệt):** Khi bộ đề mở rộng 45 ca (thêm 5 ca insulin) đạt tỷ lệ quy về thực tế $\ge 95\%$, 0 lỗi nghiêm trọng, 0 tầng tụt, Kappa $\ge 0,80$. Dược sĩ lâm sàng công ty kiểm tra 20% bản nháp (ca insulin/thuốc nguy cơ), bác sĩ BV đọc và ký 100%. Chi phí 5.668 đ/việc, biên lợi nhuận 54,7%.
   - **Mức 2 (Tự động một phần):** Khi thử nghiệm 200 ca thật đạt tỷ lệ $\ge 96\%$, 0 lỗi thuốc nghiêm trọng lọt đến bác sĩ, tỷ lệ bác sĩ sửa nhiều $< 15\%$ trong 30 ngày. Dược sĩ lâm sàng giảm tỷ lệ duyệt xuống 10%, biên lợi nhuận tăng lên **60,7% (Đạt $\ge 60\%$)**.
   - **Mức 3 (Tự động có giám sát):** **Không làm** vì theo Luật AI số 134/2025/QH15 và Luật Khám bệnh, chữa bệnh, bác sĩ phải luôn đọc, chịu trách nhiệm chuyên môn và ký 100% hồ sơ xuất viện.

3. **Khi nào cần dừng?**
   - **Điều kiện dừng đã chọn:** Hết 3 tháng thử nghiệm: nếu bác sĩ phải sửa nhiều trên 30% bản nháp, HOẶC có 1 lỗi thuốc lọt đến người bệnh, THÌ dừng dự án ngay, không mở rộng sang khoa khác (nguy cơ hết tiền ở tháng 9).

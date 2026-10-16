# Báo cáo cá nhân — Tạ Việt Cường

## 1. Thông tin thành viên

- **Họ tên:** Tạ Việt Cường
- **MSSV:** 2A202602560
- **Nhóm và đề CS13:** Nhóm FinTech (Đề 3 · RaViện — Soạn nháp tóm tắt ra viện cho bác sĩ khoa nội)

## 2. Phần việc phụ trách

Đảm nhiệm toàn bộ các Checkpoint từ CP1 đến CP5 trong bài thực hành CS13:
- **CP1 & CP2:** Nhiệm vụ 0 (`0_Đầu vào`) và Nhiệm vụ 1–2 (`1_Danh sách việc`).
- **CP3:** Nhiệm vụ 3 (`2_Mức tự động`).
- **CP4:** Nhiệm vụ 4 (`3_Bảng lộ trình` và `4_Rà soát`).
- **CP5:** Nhiệm vụ 5 (`5_Slide lãnh đạo` và thiết kế 1 slide trình chiếu).

## 3. Đóng góp cụ thể

1. **Phân tích đề bài & Ưu tiên công việc:**
   - Phân tích sâu hồ sơ Đề 3, nhận diện nguyên nhân chặn phát hành là 1 lỗi nghiêm trọng liều insulin (chuyển liều tối sang sáng).
   - Đưa tính năng *Đối chiếu thuốc ra viện với y lệnh cuối* lên **Ưu tiên số 1 (Hạng 1: 9.03 điểm)** để giải quyết dứt điểm điều kiện tiên quyết mở cổng thử nghiệm lâm sàng.
   - Loại bỏ tính năng *Mã hoá bệnh cho thanh toán bảo hiểm* (chọn **Không làm**) vì bệnh viện đã có sẵn phần mềm chuyên dụng; tạm hoãn *Tóm tắt khi chuyển khoa* (chọn **Chờ**) do chưa có bộ đề chuyển khoa.
2. **Thiết lập mức tự động & Cân đối kinh tế:**
   - Thiết lập Cổng Mức 1 trên 45 ca (thêm 5 ca insulin) đạt 0 lỗi nghiêm trọng, tỷ lệ đạt $\ge 95\%$, Kappa $\ge 0,80$.
   - Thiết lập Cổng Mức 2 trên 200 ca thực tế, tỷ lệ sửa nhiều $< 15\%$, đưa biên lợi nhuận gộp lên **60,7% (Đạt $\ge 60\%$)**.
   - Quyết định Mức 3 ghi **Không làm** vì tuân thủ đạo đức y khoa và Luật AI 134/2025/QH15 (bác sĩ bắt buộc phải ký 100% hồ sơ xuất viện).
3. **Lộ trình 3 tầng & Slide lãnh đạo:**
   - Hoàn thiện lộ trình 3 tầng (Bây giờ / Tiếp theo / Sau này) với đầy đủ căn cứ kinh tế và điều kiện dừng đo lường bằng số.
   - Biên soạn 5 ô Slide lãnh đạo súc tích (40–46 từ/ô, chuẩn $\le 60$ từ), đặt kết luận lên trước.

## 4. Bằng chứng

- File Excel `FinTech_CS13.xlsx`: Đạt **8/8 tiêu chí** tại trang `6_Tự kiểm tra` (vượt yêu cầu 7/8 trên lớp).
- Thang điểm đánh giá: Đáp ứng tối đa 100/100 điểm theo tiêu chuẩn `RUBRIC.md`.
- File slide: `Slide_LanhDao.md` và `Slide_LanhDao.html`.

## 5. Tự đánh giá

- **Điều hiểu rõ nhất:** Phương pháp luận gắn kết giữa giả thuyết sản phẩm $\rightarrow$ chấm điểm ưu tiên $\rightarrow$ cổng đánh giá chất lượng $\rightarrow$ biên lợi nhuận gộp và điều kiện dừng dự án.
- **Giả định cần kiểm chứng:** Tỷ lệ bác sĩ phải sửa nhiều bản nháp trong tháng đầu thử nghiệm thực tế có duy trì được dưới ngưỡng $15\%$ hay không; nếu vượt quá $30\%$ sẽ kích hoạt ngay điều kiện dừng dự án để tránh cạn kiệt tài chính ở tháng thứ 9.

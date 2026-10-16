# CS13 – Lộ trình sản phẩm AI

**Nhóm: Comtamsuonbicha · Đề 3: RaViện**

## File bài làm

- [Comtamsuonbicha_CS13.xlsx](Comtamsuonbicha_CS13.xlsx): Nhiệm vụ 0–5, giữ mẫu và công thức đề 3.
- [Comtamsuonbicha_CS13_Slide.pptx](Comtamsuonbicha_CS13_Slide.pptx): 1 slide cho lãnh đạo.
- [team/TEAM.md](team/TEAM.md): thông tin thành viên.

## Quyết định chính

Sửa lỗi insulin, thêm 5 ca và chạy lại 45 ca trước pilot. Bác sĩ bệnh viện đọc và ký 100% bản nháp. Mức 1 có dược sĩ duyệt 100%; chỉ xét Mức 2 khi đủ cổng 600 ca và xác nhận tỷ lệ duyệt giảm còn 10% vẫn an toàn. Không làm mức tự gửi cho người bệnh.

Kinh tế từ đề: 11.668đ/việc và biên 6,66% khi dược sĩ duyệt 100%; 4.918đ/việc và biên 60,66% nếu duyệt 10%. Tỷ lệ duyệt tối đa để biên đạt 60% là 11,09%. Nếu thực tế cần duyệt nhiều hơn, duyệt đủ và tính lại giá, không cắt duyệt để đạt biên.

## Giả định và cách kiểm chứng

Số liệu bối cảnh, kết quả eval hiện có và 9 đầu vào kinh tế lấy từ hồ sơ giả định của khóa học. Điểm ưu tiên, các ngưỡng mới, tỷ lệ duyệt 10%, ngân sách trần 100 triệu/90 ngày và phân bổ nhân sự là **đề xuất**, chưa phải kết quả vận hành. Baseline thời gian lấy từ hồ sơ là 15–20 phút/bản; cần đo lại trên 100 ca so sánh cùng độ khó. Không ghi kết quả pilot giả.

Đề xuất trần ngân sách: khoảng 42 triệu biến phí (3.600 việc × 11.668đ), 50 triệu kỹ thuật, 8 triệu chuyên gia. Vòng 45 ca cần khoảng 22,84 giờ theo ngoại suy từ 20,3 giờ/40 ca, đặt lịch 24 giờ và xác nhận khả dụng với chuyên gia. Tập giữ kín 600 ca cần thêm khoảng 30 giờ kiểm thuốc ở giả định 3 phút/ca, thuộc chi phí duyệt. Định nghĩa “sửa nhiều” đề xuất: phải sửa nội dung lâm sàng hoặc viết lại >30% phần diễn biến; chuyên gia chốt rubric trước thu mẫu.

Ngày 30/60/90 tính từ ngày bắt đầu dự án. Điều kiện dừng >30% sửa nhiều tính ở cuối tháng thứ 3 **kể từ khi bắt đầu pilot**. Một lỗi thuốc lọt người bệnh: dừng ngay. 0 lỗi/600 ca chỉ cho cận trên xấp xỉ 0,5% theo quy tắc ba, không chứng minh không còn rủi ro. Quyền dùng dữ liệu và yêu cầu tuân thủ do pháp chế bệnh viện xác nhận trước pilot.

## Nguồn

- T1_D28.pdf: giả thuyết, điểm AI, cổng, điều kiện dừng và slide lãnh đạo.
- [Repo đề bài](https://github.com/tennguoisudung22012004/K4-L3-CS13-Comtamsuonbicha-AI-Roadmap): README, SUBMISSION, CHECKPOINTS, RUBRIC.
- Hồ sơ tình huống CS13, trang 6–7; CS13_Roadmap_De3.xlsx.

AI hỗ trợ đọc tài liệu, soạn bản đề xuất, điền file và kiểm tra tính toán. Thành viên cần rà soát, hiểu và xác nhận quyết định trước nộp.

## Nộp bài

Giải nén, tải các file lên repo nhóm (giữ thư mục team). Điền thông tin còn thiếu trong TEAM.md và xác nhận phân công thực tế. Mỗi thành viên nộp cùng link repo trên VLearn theo SUBMISSION.md.

Ghi chú tương thích: công thức kiểm tra chữ số và xếp hạng được viết lại dạng tương đương để tính ổn định trên nhiều phần mềm. Giữ công thức động, không ghi đè kết quả bằng số. File đã tính lại trên LibreOffice, tự kiểm tra đạt 8/8.

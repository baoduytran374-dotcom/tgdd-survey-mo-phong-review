# Dashboard mô phỏng bảng hỏi Qualtrics – Thế Giới Di Động (16–22 tuổi, TP.HCM)

Trang web tĩnh (1 file `index.html`, không cần cài đặt hay thư viện ngoài) mô phỏng toàn bộ bảng hỏi 29 câu (A1–H3), kèm logic Qualtrics, Phụ lục 1–3 và sơ đồ phân nhánh.

## Cách dùng
- Mặc định hiển thị **tất cả câu hỏi** để overview; điều kiện logic ghi dưới mỗi câu.
- Nút **Mô phỏng logic**: ẩn/hiện câu theo đáp án như Display Logic / End of Survey thật.
- 5 nút **kịch bản preview** điền sẵn các tình huống ở Phụ lục 2.
- Không câu nào bắt buộc trả lời. Dữ liệu chỉ nằm trong trình duyệt, không gửi đi đâu.

## Đưa lên GitHub + bật GitHub Pages
```bash
cd tgdd-survey-dashboard
git init
git add .
git commit -m "Add TGDD survey dashboard"
git branch -M main
git remote add origin https://github.com/<ten-ban>/<ten-repo>.git
git push -u origin main
```
Sau đó vào **Settings → Pages → Build and deployment**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm Save. Sau khoảng 1–2 phút trang sẽ có tại `https://<ten-ban>.github.io/<ten-repo>/`.

Mở thử trên máy: bấm đúp `index.html`.

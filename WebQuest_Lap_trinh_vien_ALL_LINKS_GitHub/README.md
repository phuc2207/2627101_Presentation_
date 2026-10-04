# WebQuest Tin học 10 – Lập trình viên giải cứu cửa hàng

Bản này sẵn sàng để đưa lên GitHub Pages.

## Cấu trúc
- `index.html`: giao diện và nội dung tĩnh.
- `styles.css`: giao diện responsive.
- `app.js`: dữ liệu 8 chặng, học liệu, biểu mẫu, rubric và tính điểm.
- `assets/Rubric_du_an.docx`: file rubric gốc dùng để đối chiếu/tải về.

## Điểm đã cập nhật
- Phân bổ 5 tuần × 2 tiết, tuần 5 chỉ báo cáo sản phẩm.
- Chặng 3 dùng Padlet: https://padlet.com/Pohuc/ban-se-at-cau-hoi-nao-e-lam-ro-quy-tac-giam-gia-trong-he-tho-s0246abo6cgwdo8e64x9
- Học liệu Drive được gắn theo từng chặng.
- Rubric mới: trình bày 9đ + sản phẩm 15đ + báo cáo 6đ = 30đ, quy về thang 10 bằng cách chia 3.
- Nộp sản phẩm cuối qua Google Form.

## Gắn Google Form nộp sản phẩm
Mở `app.js`, sửa dòng đầu:

```js
const FINAL_SUBMISSION_FORM_URL = "";
```

thành:

```js
const FINAL_SUBMISSION_FORM_URL = "https://docs.google.com/forms/.../viewform";
```

Nút nộp bài trên web sẽ tự hoạt động.

## Đưa lên GitHub Pages
1. Tạo repository mới.
2. Upload toàn bộ nội dung trong thư mục này, bao gồm thư mục `assets`.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Kiểm tra lại quyền chia sẻ các học liệu Google Drive: học sinh phải mở được bằng tài khoản phù hợp hoặc “Anyone with the link – Viewer”.


## Cập nhật bản FINAL
- Google Form nộp sản phẩm cuối đã được gắn trực tiếp vào website:
  https://forms.gle/Kjc7ism59AYpLVsC7
- Padlet Chặng 3 đã được gắn trực tiếp trong website.
- Rubric dự án dùng file `assets/Rubric_du_an.docx` và bảng rubric hiển thị ngay trên trang.
- Tiến độ dự án: 5 tuần × 2 tiết; tuần 5 dành cho báo cáo, chạy thử và nghiệm thu.
- Khi đưa lên GitHub Pages, upload toàn bộ nội dung của thư mục này, giữ nguyên cấu trúc `assets/`.

### GitHub Pages
1. Tạo repository mới.
2. Upload `index.html`, `styles.css`, `app.js`, `README.md` và thư mục `assets`.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch → main → /(root)**.
5. Lưu và chờ GitHub tạo đường dẫn website.


## Bản ALL LINKS
Website đã được đối chiếu lại với thư mục Drive:
https://drive.google.com/drive/folders/1U27RrJ71ou_mF-UYfKSmD6dyGmyXOwCs

- Google Form nộp sản phẩm cuối: https://forms.gle/Kjc7ism59AYpLVsC7
- Padlet Chặng 3: https://padlet.com/Pohuc/ban-se-at-cau-hoi-nao-e-lam-ro-quy-tac-giam-gia-trong-he-tho-s0246abo6cgwdo8e64x9
- Tất cả học liệu công khai cho học sinh đã được đưa vào `app.js` và hiển thị trong **Kho học liệu**.
- Các Google Form vé C1, C2, C3, C7 cũng xuất hiện trong **Biểu mẫu & Vé qua chặng**.
- Các tài liệu bí mật của GV không được nhúng vào bản GitHub công khai. Xem `LINKS_MANIFEST.md` để biết danh sách loại trừ.

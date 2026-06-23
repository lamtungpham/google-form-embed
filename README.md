# Google Form → Embed Đẹp

Công cụ tạo mã nhúng (embed) **đẹp & responsive** cho Google Form — dán link, xem trước trực tiếp, copy HTML để dán lên website/blog như viết bài.

## Cách dùng
1. Dán **link Google Form** vào ô đầu tiên.
2. Chỉnh tiêu đề / phụ đề / màu; kéo thanh **Chiều cao** cho vừa khít form ở khung xem trước.
3. Bấm **📋 Copy HTML** → dán vào bài viết bằng chế độ **Source/HTML (`</>`)** của trình soạn thảo.

## Host online miễn phí (GitHub Pages)
1. Tạo repo và đẩy nội dung thư mục này lên (giữ tên file `index.html`).
2. Repo → **Settings → Pages** → Source: nhánh `main` / thư mục `/(root)` → **Save**.
3. Sau ~1 phút, tool chạy tại `https://<tên-github>.github.io/<tên-repo>/`.

## Tính năng
- Nhận mọi dạng link Google Form (kể cả `?usp=header`, link `/edit`); cảnh báo nếu là link rút gọn `forms.gle`.
- **Responsive** — vừa mọi màn hình, điện thoại không tràn.
- 2 kiểu: **nhúng iframe** / **nút bấm mở tab mới** (cho form bắt đăng nhập).
- Xem trước trực tiếp + thanh chỉnh chiều cao.
- 5 tông màu (mặc định theo brand).

## Lưu ý
- Google Form khác domain nên trình duyệt **không tự đo được chiều cao** iframe — dùng thanh kéo chiều cao (có xem trước trực tiếp) để chỉnh cho khít.
- Form **bắt đăng nhập**: nên chọn kiểu **Nút bấm** (mở tab mới) để việc đăng nhập chạy ổn định.

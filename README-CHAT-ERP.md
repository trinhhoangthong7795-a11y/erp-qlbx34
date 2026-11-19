# QLBX Chat ERP 34 – GitHub Pages

Nhánh này triển khai riêng ứng dụng Chat ERP v1.5. Nhánh `main` và ứng dụng dashboard hiện tại không bị thay đổi.

## Files
- `index.html`: trang vào của Chat ERP
- `app.html`: mã nguồn ứng dụng Chat ERP v1.5
- `sw.js`, `manifest.webmanifest`: PWA assets

## Enable Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → chọn `qlbx-chat-erp34-pages`, folder `/(root)` → Save.

URL: https://trinhhoangthong7795-a11y.github.io/erp-qlbx34/

## Firebase
Thêm `trinhhoangthong7795-a11y.github.io` trong Firebase Console → Authentication → Settings → Authorized domains. Không thay Realtime Database Rules và không xóa dữ liệu Firebase cho bước này.

Sau khi Pages được bật, mở URL HTTPS trên Android Chrome để đăng nhập. Xóa dữ liệu trình duyệt/cache cũ nếu đã ghim PWA bản trước.

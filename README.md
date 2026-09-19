# Trang thông tin — Gia Đình Phật Tử Chánh Khánh Anh

Trang đích của mã QR in trên banner và standee của gia đình.
Chùa Khánh Vân.

## Nội dung repo

| File | Việc của nó |
|---|---|
| `index.html` | Toàn bộ trang. Một file duy nhất, đã gộp sẵn CSS, JS và ảnh. |
| `og-image.jpg` | Ảnh hiện ra khi dán link lên Facebook / Zalo. |
| `.nojekyll` | Bảo GitHub Pages đừng xử lý lại file. Đừng xoá. |

## Cách sửa nội dung

Mở `index.html` trên github.com, bấm biểu tượng bút chì, sửa, bấm
**Commit changes**. Khoảng một phút sau trang tự cập nhật.

Những chỗ hay phải sửa:

- **Giờ sinh hoạt** — tìm `2–5 giờ chiều`
- **Độ tuổi, địa chỉ, số điện thoại** — tìm `class="todo"`
- **Link đăng ký** — tìm `id="cta-dock"`, thay `href="#"` bằng link Google Form
- **Sự kiện sắp tới** — tìm `Đêm hội Trăng Rằm`
- **Ảnh** — tìm `class="shot"` và `class="cover"`

## QUAN TRỌNG — đừng đổi địa chỉ trang

Mã QR đã in trên banner trỏ thẳng vào địa chỉ này. Đổi tên repo, đổi
tài khoản, hay tắt GitHub Pages là mọi tấm banner đã in thành vô dụng.
Muốn chuyển sang tên miền riêng thì dùng mục **Settings → Pages →
Custom domain**, giữ nguyên repo — cách đó QR vẫn sống.

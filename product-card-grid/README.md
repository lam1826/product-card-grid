# Product Card Grid - CSS Flexbox

Bài thực hành xây dựng danh sách **4 thẻ sản phẩm** bằng CSS Flexbox.

## Yêu cầu đã thực hiện

- `display: flex` để dàn hàng các thẻ.
- `flex-wrap: wrap` để tự xuống dòng khi thiếu không gian.
- `gap: 20px` để tạo khoảng cách giữa các thẻ.
- `.product-card` dùng `flex: 1 1 calc(25% - 20px)` và `min-width: 220px`.
- Có hiệu ứng hover nâng thẻ lên nhẹ.
- Có thẻ `meta viewport` và CSS hỗ trợ màn hình điện thoại.

## Cấu trúc

```text
product-card-grid/
├── index.html
├── style.css
└── README.md
```

## Chạy thử

Mở `index.html` trong trình duyệt hoặc nhấp phải trong VS Code → **Open with Live Server**. Thay đổi chiều rộng cửa sổ để quan sát các thẻ tự động xuống dòng.

## Đưa lên GitHub

Tạo repository công khai `product-card-grid`, mở Terminal trong thư mục này và chạy:

```bash
git init
git branch -M main
git add .
git commit -m "Complete Flexbox product card grid practice"
git remote add origin https://github.com/USERNAME/product-card-grid.git
git push -u origin main
```

Thay `USERNAME` bằng tên GitHub của bạn. Bật **Settings → Pages → Deploy from a branch → main → /(root)**.

Sau khi triển khai, URL minh chứng sẽ có dạng:

`https://USERNAME.github.io/product-card-grid/`

*Đây là URL mẫu, chỉ hoạt động sau khi bạn tạo repo và bật GitHub Pages.*

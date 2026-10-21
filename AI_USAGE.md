# AI Usage Log

## 1. Công cụ AI
ChatGPT.

## 2. Mục đích
Hỗ trợ phân tích yêu cầu bài tập, phát triển ý tưởng cải tiến thẻ sản phẩm và giải thích cách tổ chức HTML/CSS.

## 3. Prompt đã sử dụng
“Bạn là chuyên viên UX/UI cho website thương mại điện tử. Đề xuất giao diện minh họa bằng HTML và CSS để cải tiến thẻ sản phẩm cho website bán mỹ phẩm. Giao diện cần có tối thiểu 4 sản phẩm, hình ảnh, tên, giá, nút thao tác, bố cục responsive cho desktop và mobile. Không dùng backend, cơ sở dữ liệu hoặc thư viện không cần thiết. Giải thích cấu trúc HTML và các nhóm CSS quan trọng.”

## 4. Tóm tắt đề xuất của AI
- Sử dụng lưới sản phẩm và các thẻ có cấu trúc nhất quán.
- Phân cấp rõ tên, giá, giá gốc, ưu đãi và đánh giá.
- Dùng media query để điều chỉnh số cột trên màn hình nhỏ.
- Giữ mã HTML và CSS ở hai tệp riêng biệt.

## 5. Kiểm tra và điều chỉnh
Sau khi mở trang trong trình duyệt, người thực hiện cần ghi lại các kiểm tra đã thực hiện và thay đổi cá nhân đã thực hiện. Không đánh dấu các bước này là hoàn tất trước khi thực sự kiểm tra.

## 6. Phần mã cần hiểu
- `index.html`: cấu trúc nội dung và các thành phần như header, danh mục, thẻ sản phẩm, nút thao tác.
- `style.css`: màu sắc, khoảng cách, kiểu chữ, lưới sản phẩm, trạng thái hover và responsive bằng `@media`.
- `.product-grid`: tạo lưới các thẻ sản phẩm.
- `@media (max-width: 600px)`: điều chỉnh bố cục cho màn hình điện thoại.

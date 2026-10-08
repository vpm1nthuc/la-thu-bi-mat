# Một chiếc hẹn cuối tuần

Trang web nhỏ để rủ anh đi chơi cuối tuần. Mở `index.html` trong trình duyệt để xem trực tiếp; không cần cài đặt hay chạy build.

## Cách hoạt động

- **Đi thuii**: mở chiếc vé hẹn bất ngờ và hiện hiệu ứng trái tim.
- Khi bấm **Đi thuii**, trang gửi email thông báo qua FormSubmit trước khi hiện lời xác nhận. Nếu gửi lỗi, người xem có thể bấm lại.
- **Khom đi**: sau mỗi lần bấm, nút đổi vị trí và nút **Đi thuii** lớn dần. Sau lần bấm thứ năm, **Khom đi** biến mất.
- Giao diện tự điều chỉnh cho điện thoại và tôn trọng cài đặt giảm chuyển động.
- Hình minh họa đứng yên để trang dễ nhìn hơn.

## Tùy chỉnh

- Nội dung lời mời và lời xác nhận: sửa trong `index.html`.
- Minh họa trên trang: `images/weekend-walk.png`; ảnh xem trước khi chia sẻ link: `images/share-preview.png`.
- Email nhận thông báo: FormSubmit cấp một mã nhận thư ẩn sau khi địa chỉ email được kích hoạt. Nếu đổi email, kích hoạt địa chỉ mới rồi thay hằng số `NOTIFICATION_ENDPOINT` gần đầu phần `<script>` trong `index.html` bằng đường dẫn mới dạng `https://formsubmit.co/ajax/<mã>`.
- Màu sắc và kích thước: sửa phần `<style>` trong `index.html`.
- Số lần nút **Khom đi** xuất hiện: sửa điều kiện `noClicks >= 5` cùng danh sách `noPositions` và `hints` trong `index.html`.

Trang này là HTML, CSS và JavaScript thuần, phù hợp để đăng từ nhánh `main` trên GitHub Pages tại `https://vpm1nthuc.github.io/loi-moi-cuoi-tuan/`.

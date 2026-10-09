# Lá thư bí mật

Trang web nhỏ để rủ anh đi chơi cuối tuần. Mở `index.html` trong trình duyệt để xem trực tiếp; không cần cài đặt hay chạy build.

## Cách hoạt động

- **Uki luông**: mở chiếc vé hẹn bất ngờ và hiện hiệu ứng trái tim.
- Khi bấm **Uki luông**, trang gửi email thông báo qua FormSubmit trước khi hiện lời xác nhận. Nếu gửi lỗi, người xem có thể bấm lại.
- **Bận ròi**: sau mỗi lần bấm, trang hiện một lời năn nỉ mới, nút đổi vị trí và nút **Uki luông** lớn dần. Sau lần bấm thứ năm, **Bận ròi** biến mất.
- Giao diện tự điều chỉnh cho điện thoại và tôn trọng cài đặt giảm chuyển động.
- Hình minh họa đứng yên để trang dễ nhìn hơn.

## Tùy chỉnh

- Nội dung lá thư và lời xác nhận: sửa trong `index.html`.
- Minh họa trên trang: `images/weekend-walk.png`.
- Trang không khai báo mô tả hoặc ảnh xem trước cho link. Ứng dụng nhắn tin vẫn có thể tự tạo thẻ xem trước từ tiêu đề trang hoặc lưu thẻ cũ trong bộ nhớ đệm; việc chỉ hiện link trần do ứng dụng nhắn tin quyết định.
- Email nhận thông báo: FormSubmit cấp một mã nhận thư ẩn sau khi địa chỉ email được kích hoạt. Nếu đổi email, kích hoạt địa chỉ mới rồi thay hằng số `NOTIFICATION_ENDPOINT` gần đầu phần `<script>` trong `index.html` bằng đường dẫn mới dạng `https://formsubmit.co/ajax/<mã>`.
- Màu sắc và kích thước: sửa phần `<style>` trong `index.html`.
- Các lời năn nỉ và số lần nút **Bận ròi** xuất hiện: sửa danh sách `pleas`, `noPositions` trong `index.html`.

Trang này là HTML, CSS và JavaScript thuần, phù hợp để đăng từ nhánh `main` trên GitHub Pages tại `https://vpm1nthuc.github.io/la-thu-bi-mat/`.

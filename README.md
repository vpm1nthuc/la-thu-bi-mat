# Một chiếc hẹn cuối tuần

Trang web nhỏ để rủ anh đi ăn cuối tuần. Mở `index.html` trong trình duyệt để xem trực tiếp; không cần cài đặt hay chạy build.

## Cách hoạt động

- **Đi thuii**: hiện lời xác nhận và hiệu ứng trái tim.
- **Khom đi**: sau mỗi lần bấm, nút đổi vị trí và nút **Đi thuii** lớn dần. Sau lần bấm thứ năm, **Khom đi** biến mất.
- Giao diện tự điều chỉnh cho điện thoại và tôn trọng cài đặt giảm chuyển động.

## Tùy chỉnh

- Nội dung lời mời và lời xác nhận: sửa trong `index.html`.
- Minh họa: `images/date-cats.png`.
- Màu sắc và kích thước: sửa phần `<style>` trong `index.html`.
- Số lần nút **Khom đi** xuất hiện: sửa điều kiện `noClicks >= 5` cùng danh sách `noPositions` và `hints` trong `index.html`.

Trang này là HTML, CSS và JavaScript thuần, phù hợp để đăng từ nhánh `main` trên GitHub Pages.

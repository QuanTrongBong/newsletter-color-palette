# Newsletter — hai bộ phối màu

Hai phiên bản cùng dùng bố cục newsletter responsive, Bootstrap 5.3.3 và stylesheet chung. Mỗi trang chọn một palette khác nhau bằng thuộc tính `data-palette`.

## Xem hai phiên bản

- [`index.html`](index.html) — đất ấm: terracotta, mận trầm, vàng mật ong và nền kem.
- [`version2.html`](version2.html) — đại dương: navy, teal, xanh chanh nhạt và nền sương xanh.
- [`palette-notes.md`](palette-notes.md) — bảng mã HEX, vai trò từng màu và ghi chú cảm nhận/tương phản.
- [`style.css`](style.css) — layout, minh họa CSS và biến màu cho hai phiên bản.

Mỗi trang có liên kết chuyển qua phiên bản còn lại. Mở `index.html` để bắt đầu; nhấn liên kết palette trong phần đầu hoặc chân trang để so sánh.

## Ghi chú về mẫu và palette

Tài liệu bài tập nói đến newsletter Trello offline, nhưng bộ file Trello đó không có trong workspace được cung cấp. Hai trang trong repo là một newsletter mẫu Boardroom với bố cục riêng, được phối thành hai palette để thực hành so sánh màu; không phải bản sao nguyên trạng của file newsletter Trello.

Các palette được ghi thành mã HEX và mô tả theo hướng phối màu tương đồng/đối lập trong `palette-notes.md`. Nếu lớp yêu cầu minh chứng lựa chọn trực tiếp bằng Adobe Color, có thể nhập các mã màu vào công cụ và chụp lại palette từ Adobe Color để nộp kèm.

## Chạy

Không cần build. Mở `index.html` hoặc `version2.html` trong trình duyệt. Bootstrap được nạp từ CDN nên cần kết nối Internet để lấy stylesheet Bootstrap; CSS tùy chỉnh nằm trong `style.css`.

# Newsletter — ghi chú phối màu

Hai trang dùng chung một bố cục newsletter responsive và một stylesheet; thuộc tính `data-palette` đổi toàn bộ biến màu.

## Phiên bản 1 — Đất ấm (`index.html`)

| Vai trò | HEX |
| --- | --- |
| Chủ đạo — đất nung | `#A54132` |
| Chủ đạo đậm — hover | `#823629` |
| Phụ — mận trầm | `#4E3542` |
| Nhấn — vàng mật ong | `#F2BD67` |
| Nền nội dung — kem ấm | `#F8ECDF` |
| Chữ chính | `#302720` |

**Cảm nhận:** ấm áp, gần gũi và giàu năng lượng. Đỏ đất là điểm tập trung trên tiêu đề và nút; mận trầm tạo chiều sâu; vàng ấm làm điểm nhấn, còn nền kem giúp nội dung dài dễ đọc. Bảng màu lấy nhóm màu ấm làm chủ đạo, phối các sắc độ sáng/tối và một màu mận tương phản để tạo thứ bậc, thay vì dùng nhiều màu bão hòa cùng lúc.

## Phiên bản 2 — Đại dương (`version2.html`)

| Vai trò | HEX |
| --- | --- |
| Chủ đạo — xanh navy | `#154C66` |
| Chủ đạo đậm — hover | `#10384E` |
| Phụ — xanh teal | `#176F73` |
| Nhấn — xanh chanh nhạt | `#D5E4A4` |
| Nền nội dung — sương xanh | `#E2EFF0` |
| Chữ chính | `#172B38` |

**Cảm nhận:** bình tĩnh, đáng tin cậy và chuyên nghiệp. Navy dùng cho tiêu đề/nút chính, teal phân biệt nội dung phụ, xanh chanh nhạt tạo điểm nhấn nhẹ mà không làm rối. Navy và teal tạo nền tương đồng về sắc xanh; màu nhấn sáng tạo tương phản vừa đủ, khác rõ với bảng màu đất ấm của bản đầu.

## Tương phản và ứng dụng màu

- Chữ trắng trên màu chủ đạo của CTA và phần minh họa tương phản cao; màu nhấn vàng/xanh chanh dùng chữ tối, không đặt chữ trắng trực tiếp lên nền nhấn.
- Chữ nội dung dùng màu tối trên nền sáng; màu phụ chỉ sử dụng cho liên kết, nhãn hoặc mảng trang trí có độ tương phản phù hợp.
- Cả hai trang dùng cùng thứ tự nội dung: header, hero, lời chào, ba bài viết nổi bật, CTA và footer. Nhờ vậy có thể so sánh tác động của màu sắc mà không bị nhiễu bởi khác biệt bố cục.
- CSS Bootstrap 5.3.3 cung cấp grid responsive; CSS tùy chỉnh giữ cùng cấu trúc và thay đổi palette qua custom properties.

## Gợi ý trình bày

Mở lần lượt `index.html` và `version2.html` để so sánh. Hai bảng màu được xây dựng theo các nguyên tắc phối màu tương đồng/tương phản thường có trong Adobe Color; nếu khóa học yêu cầu minh chứng trực tiếp từ Adobe Color, mở công cụ, nhập các HEX ở trên, chọn quy tắc gần tương ứng và chụp ảnh palette làm minh chứng.

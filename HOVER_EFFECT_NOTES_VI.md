# Hiệu ứng viền khi hover

Đã thêm hiệu ứng viền điện chuyển động nhẹ cho `.stack-card` và `.project-card` trong `styles.css`.

- Hiệu ứng chỉ chạy khi rê chuột lên thẻ (hoặc focus bằng bàn phím).
- Viền là một đoạn sáng mảnh chạy quanh chu vi, không nhấp nháy liên tục khi không tương tác.
- Màu lấy theo accent của từng thẻ: xanh lam, cyan/xanh ngọc, vàng hoặc tím.
- Tôn trọng `prefers-reduced-motion` để giảm chuyển động cho người dùng cần hạn chế animation.

## Lưu ý quan trọng

Hiệu ứng hover này dùng được trên portfolio website (`hieu-commits.github.io`) vì website có CSS riêng. GitHub Profile README (`github.com/hieu-commits`) không cho phép chạy CSS tùy chỉnh hoặc JavaScript để tạo hiệu ứng hover cho hình ảnh/card. README có thể hiển thị ảnh tĩnh hoặc GIF tự chạy, nhưng GIF không thể chỉ bắt đầu chạy khi di chuột vào.

Để cập nhật website, thay file `styles.css` trong repository `hieu-commits.github.io` bằng file trong gói này, rồi commit và push.

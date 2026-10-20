# 💐 Món Quà 20/10 - Happy Vietnamese Women's Day

Trang web thiệp hoa mừng ngày Phụ Nữ Việt Nam 20/10 với hiệu ứng thị giác và âm thanh sống động, mượt mà.

## ✨ Tính Năng Nổi Bật

- **Màn hình mở đầu tương tác:** Nút cảm ứng vân tay và hoa tulip nảy mầm phát sáng với hiệu ứng ấn giữ để mở quà.
- **Bó hoa phát sáng 3D:** 11 bông hoa tulip cách điệu nở rộ, hiệu ứng sao băng, hạt sáng lấp lánh và chú thỏ nhảy múa.
- **Nhạc nền:** Tự động phát ca khúc *"Dành Cho Em"*.
- **Lá thư tâm tình:** Phong thư mở ra với tiêu đề, nội dung lời chúc hiển thị bằng hiệu ứng gõ chữ (typewriter) cùng chữ ký.
- **Kỷ niệm ảnh bay (Photo Float):** Khi nhấn "Tiếp tục", các bức ảnh kỷ niệm sẽ bay bồng bềnh từ dưới lên, hỗ trợ nhấn giữ để bắt và kéo thả vị trí ảnh.
- **Hoạt động độc lập (Offline):** Toàn bộ hình ảnh, âm thanh, CSS và JS được đóng gói cục bộ không phụ thuộc server ngoài.

## 🚀 Cách Sử Dụng

1. Clone repository về máy:
   ```bash
   git clone https://github.com/giaphung2k1/20-10-gift.git
   ```
2. Mở trực tiếp file `index.html` bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox, Safari) hoặc chạy qua XAMPP:
   ```
   http://localhost/20-10/index.html
   ```

## 📂 Cấu Trúc Dự Án

```
├── index.html                 # Giao diện chính của món quà
├── css/
│   └── index.css              # Toàn bộ hiệu ứng, hoạt ảnh và tạo hình CSS
├── js/
│   ├── index.js               # Logic tương tác, âm thanh và hiệu ứng
│   └── previewDB.js           # IndexedDB logic
├── assets/
│   ├── audio/                 # Nhạc nền (danhchoem.mp3)
│   ├── fonts/                 # Phông chữ tùy biến
│   ├── images/                # Hình ảnh bó hoa, nơ, thỏ nhảy, nền
│   └── photos/                # Hình ảnh kỷ niệm bay
└── gift_data.json             # Dữ liệu lời chúc và cấu hình quà tặng
```

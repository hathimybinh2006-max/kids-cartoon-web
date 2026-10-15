# KidsToon - Website Xem Phim Hoạt Hình Tuyển Chọn Cho Thiếu Nhi

Dự án thiết kế và phát triển giao diện website xem phim hoạt hình cho thiếu nhi, đáp ứng các tiêu chuẩn về an toàn nội dung, giao diện thân thiện và cấu trúc hiện đại.

---

## 🌟 Tính Năng & Tiêu Chí Đáp Ứng

### 1. Mức cơ bản
- **Header:** Logo thương hiệu ở góc trái, thanh tìm kiếm phim và các liên kết điều hướng (`head-links`).
- **Bố cục nội dung (Content):**
  - **Left Content:** Menu danh sách các tập phim hoạt hình chọn lọc kèm thumbnail, thời lượng và số lượt xem.
  - **Right Content:** Khu vực phát video chính, mặc định hiển thị video đầu tiên kèm tiêu đề, thông tin lượt xem và tóm tắt nội dung.
- **Footer:** Hiển thị thông tin bản quyền, tôn chỉ nội dung lành mạnh và các liên kết phụ trợ.

### 2. Mức trung bình
- **Định dạng văn bản & liên kết:** Bỏ gạch chân mặc định (`text-decoration: none`), rê chuột (hover) vào liên kết sẽ tự động in đậm (`font-weight: bold`) và đổi màu nổi bật.
- **Header cố định (Fixed Header):** Áp dụng `position: fixed; top: 0; left: 0; width: 100%;` giúp thanh điều hướng luôn nằm ở đầu màn hình khi cuộn trang, kết hợp với `padding-top` trên `body` tránh bị che khuất nội dung.

### 3. Mức nâng cao
- **Đa phương tiện phong phú:**
  - Nhúng video hoạt hình chất lượng cao qua YouTube với thẻ `<iframe>` (tỉ lệ chuẩn 16:9 responsive).
  - Tích hợp thêm trình phát video HTML5 chuẩn W3C bằng thẻ `<video>` kèm điều khiển playback đầy đủ.
- **Responsive Web Design:** Tối ưu hiển thị mượt mà trên nhiều thiết bị:
  - **Desktop / Laptop (>1024px):** Layout 2 cột song song (Left content bên trái, Right content bên phải).
  - **Tablet (<=1024px):** Layout tự động căn chỉnh, ưu tiên video player lên đầu và danh sách phim dạng lưới gọn gàng.
  - **Mobile (<=768px):** Header linh hoạt 2 tầng, danh sách phim xếp chồng dọc tối ưu cho thao tác chạm vuốt.

---

## 📁 Cấu Trúc Dự Án

```
kids-cartoon-web/
├── index.html        # Cấu trúc HTML5 ngữ nghĩa và nội dung
├── style.css         # Định dạng giao diện, hiệu ứng hover, fixed header và responsive
└── README.md         # Tài liệu giới thiệu và hướng dẫn dự án
```

---

## 🚀 Hướng Dẫn Xem Thử

1. Mở trực tiếp tệp `index.html` bằng trình duyệt web (Google Chrome, Microsoft Edge, Firefox,...).
2. Cuộn trang lên xuống để xem hiệu ứng thanh điều hướng bám đỉnh (`fixed header`).
3. Rê chuột vào các liên kết menu và danh sách video để xem hiệu ứng chuyển màu và in đậm.
4. Nhấn vào các tập phim trong danh sách để chọn xem tập tương ứng.

# Fashion Store - Website Bán Quần Áo

Trang web thương mại điện tử bán quần áo thời trang với giao diện hiện đại, responsive và SEO-friendly.

## 🌟 Tính Năng

### Chức Năng Chính
- ✅ Trang chủ với slider hero, danh mục sản phẩm, sản phẩm nổi bật
- ✅ Trang danh sách sản phẩm với bộ lọc đa dạng
- ✅ Trang chi tiết sản phẩm với gallery ảnh, chọn size/màu
- ✅ Giỏ hàng với quản lý số lượng, tính tổng tự động
- ✅ Responsive design - hoạt động tốt trên mọi thiết bị
- ✅ SEO-friendly với meta tags đầy đủ
- ✅ Mock data để demo dữ liệu

### Tính Năng Nâng Cao
- 🔍 Tìm kiếm sản phẩm
- 🏷️ Lọc theo danh mục, giá, đánh giá, trạng thái
- 📊 Sắp xếp sản phẩm (tên, giá, đánh giá, mới nhất)
- 🛒 Giỏ hàng với localStorage
- 💳 Form thanh toán chi tiết
- ⭐ Đánh giá và nhận xét sản phẩm
- 📱 Mobile menu responsive
- 🔝 Nút back to top
- 🎨 Toast notifications
- 📧 Form đăng ký nhận tin

## 📁 Cấu Trúc Thư Mục

```
New folder/
│
├── index.html              # Trang chủ
├── products.html           # Trang danh sách sản phẩm
├── product-detail.html     # Trang chi tiết sản phẩm
├── cart.html              # Trang giỏ hàng
│
├── css/
│   └── styles.css         # CSS chính (responsive)
│
├── js/
│   ├── data.js           # Mock data
│   └── app.js            # JavaScript chính
│
├── images/               # Thư mục chứa hình ảnh
└── assets/               # Tài nguyên khác
```

## 🚀 Hướng Dẫn Sử Dụng

### Cách 1: Mở trực tiếp
1. Mở file `index.html` bằng trình duyệt web
2. Duyệt qua các trang khác nhau

### Cách 2: Sử dụng Live Server (Khuyến nghị)
1. Cài đặt Live Server extension trong VS Code
2. Right-click vào `index.html`
3. Chọn "Open with Live Server"

### Cách 3: Sử dụng Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Truy cập: http://localhost:8000
```

## 🎨 Thiết Kế UI/UX

### Màu Sắc Chính
- **Primary Color**: #2c3e50 (Xanh đậm)
- **Secondary Color**: #e74c3c (Đỏ)
- **Accent Color**: #3498db (Xanh dương)
- **Text**: #333 (Đen nhạt)

### Typography
- **Font Chính**: Inter (Sans-serif)
- **Font Heading**: Playfair Display (Serif)

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 📦 Mock Data

Dữ liệu demo bao gồm:
- **18 sản phẩm** với nhiều danh mục khác nhau
- **6 danh mục**: Áo Nam, Quần Nam, Áo Nữ, Váy, Phụ Kiện, Giày Dép
- **3 banner** cho slider
- **3 testimonials** từ khách hàng
- Hình ảnh sử dụng từ Unsplash

## 🛠️ Công Nghệ Sử Dụng

- **HTML5**: Cấu trúc trang web semantic
- **CSS3**: Styling với Flexbox, Grid, Animations
- **JavaScript (Vanilla)**: Logic và tương tác
- **Font Awesome**: Icons
- **Google Fonts**: Typography
- **LocalStorage**: Lưu trữ giỏ hàng

## ✨ Tính Năng SEO

- ✅ Meta tags đầy đủ (title, description, keywords)
- ✅ Open Graph tags cho chia sẻ mạng xã hội
- ✅ Semantic HTML5
- ✅ Alt text cho tất cả hình ảnh
- ✅ Breadcrumb navigation
- ✅ Structured data ready
- ✅ Mobile-friendly design

## 📱 Responsive Features

### Mobile (< 768px)
- Hamburger menu
- Full-width layouts
- Touch-friendly buttons
- Simplified navigation
- Optimized images

### Tablet (768px - 1024px)
- 2-column product grid
- Adapted navigation
- Optimized spacing

### Desktop (> 1024px)
- 4-column product grid
- Hover effects
- Fixed navigation
- Full features

## 🔧 Customization

### Thay đổi màu sắc
Chỉnh sửa CSS variables trong `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    /* ... */
}
```

### Thêm sản phẩm
Chỉnh sửa file `js/data.js` và thêm object mới vào array `products`:
```javascript
{
    id: 19,
    name: "Tên sản phẩm",
    price: 299000,
    // ...
}
```

### Thay đổi hình ảnh
- Thay URL trong `data.js`
- Hoặc thêm hình vào thư mục `images/` và cập nhật đường dẫn

## 🐛 Xử Lý Lỗi

### Giỏ hàng không cập nhật
- Xóa localStorage: `localStorage.clear()`
- Refresh trang

### Hình ảnh không hiển thị
- Kiểm tra kết nối internet
- URLs sử dụng Unsplash cần internet

### JavaScript không chạy
- Kiểm tra console của browser (F12)
- Đảm bảo files JS được load đúng thứ tự

## 📈 Cải Tiến Trong Tương Lai

- [ ] Tích hợp backend API
- [ ] User authentication
- [ ] Payment gateway
- [ ] Wishlist functionality
- [ ] Product comparison
- [ ] Live chat support
- [ ] Product reviews system
- [ ] Multi-language support
- [ ] Dark mode
- [ ] Advanced filters

## 📄 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

Developed by Fashion Team

## 🤝 Đóng Góp

Mọi đóng góp đều được chào đón! Hãy tạo pull request hoặc báo cáo issues.

## 📞 Liên Hệ

- Email: support@fashion.com
- Hotline: 1900 1234

---

**Note**: Đây là project demo với mock data. Để sử dụng trong production, cần tích hợp với backend thực tế và cơ sở dữ liệu.

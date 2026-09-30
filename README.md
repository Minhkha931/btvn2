# MOON COFFEE - Responsive Website

Website tĩnh responsive phát triển từ BTVN01 bằng HTML5 và CSS3.

## 1. Danh sách trang HTML

Các trang chính:

1. `index.html` - Trang chủ
2. `menu.html` - Menu
3. `product.html` - Sản phẩm + chi tiết sản phẩm
4. `services.html` - Dịch vụ
5. `gallery.html` - Không gian / thư viện hình ảnh
6. `blog.html` - Coffee Blog
7. `about.html` - Về MOON
8. `contact.html` - Liên hệ

Các bài Blog chi tiết:

- `blog-espresso.html`
- `blog-cappuccino.html`
- `blog-matcha.html`
- `blog-coffeehouse.html`
- `blog-peach-tea.html`
- `blog-tiramisu.html`

Tổng cộng project có hơn 08 trang HTML và trang chủ có tên chính xác là `index.html`.

## 2. Công nghệ sử dụng

- HTML5 Semantic: `header`, `nav`, `main`, `section`, `article`, `footer`, `figure`, `form`
- CSS3
- Flexbox
- CSS Grid
- CSS Media Queries
- Responsive cho Desktop / Tablet / Mobile

## 3. Components đã có

- Header + Logo
- Navigation giữa các trang
- Hero / Page Banner
- Section
- Product/Menu/Service/Blog/Gallery Grid
- Card
- Button / Link
- Form liên hệ
- Footer

## 4. Responsive

Website có các breakpoint chính trong `css/style.css`:

- Desktop: bố cục nhiều cột
- Tablet: grid giảm còn 2-3 cột tùy khu vực, navigation tự xuống dòng
- Mobile: grid 1 cột, navigation 2 cột, form và các khu vực chia cột chuyển thành 1 cột

Ảnh dùng `max-width: 100%` và `object-fit: cover` để hạn chế méo/tràn.
`body` có `overflow-x: hidden` để tránh thanh cuộn ngang không cần thiết.

## 5. Hình ảnh

Tên file được giữ đúng theo project gốc để tránh sai đường dẫn trên GitHub Pages:

- `images/coffee.jpg`
- `images/Cappuccino.jpg`
- `images/Caramel latte.jpg`
- `images/espresso.jpg`
- `images/latte.jpg`
- `images/matcha.jpg`
- `images/trà đào.jpg`
- `images/trà vải.jpg`
- `images/Matcha đá xay.jpg`
- `images/Tiramisu.jpg`
- `images/Cupcake.jpg`
- `images/shop.png`

Bản nộp này có sẵn ảnh minh họa tự tạo với đúng các tên trên để website không bị lỗi ảnh khi triển khai. Nếu thay bằng ảnh gốc/tải từ Internet, phải giữ đúng tên file hoặc sửa `src` tương ứng, đồng thời ghi nguồn thật ở README.

## 6. Nguồn tài liệu Blog

Các bài có sử dụng thông tin lịch sử bên ngoài đã ghi nguồn trực tiếp ở cuối bài:

- Espresso: Smithsonian Magazine - *The Long History of the Espresso Machine*
  - https://www.smithsonianmag.com/arts-culture/the-long-history-of-the-espresso-machine-126012814/
- Cappuccino: Encyclopaedia Britannica - *Cappuccino*
  - https://www.britannica.com/topic/cappuccino
- Matcha / văn hóa trà Nhật Bản: Japan National Tourism Organization
  - https://www.japan.travel/en/uk/inspiration/japanese-tea-culture/
- Tiramisu: Accademia del Tiramisù
  - https://www.accademiadeltiramisu.com/en/tiramisu-recipe/

Các đoạn giới thiệu về MOON COFFEE, dịch vụ, không gian và nội dung mô tả sản phẩm là nội dung biên soạn cho bài tập.

## 7. Đường dẫn

Website dùng đường dẫn tương đối, ví dụ:

- `css/style.css`
- `images/coffee.jpg`
- `menu.html`
- `product.html#espresso`

Điều này giúp project hoạt động khi triển khai bằng GitHub Pages.

## 8. GitHub Pages

1. Đưa toàn bộ nội dung project lên repository GitHub.
2. Bảo đảm `index.html` nằm ở thư mục gốc.
3. Vào `Settings` → `Pages`.
4. Chọn deploy từ branch chính (`main`) và thư mục root.
5. Mở URL GitHub Pages và kiểm tra toàn bộ menu, ảnh, form, blog và responsive.

URL website được lưu trong `website.txt`.

## 9. Checklist trước khi nộp

- [x] Có ít nhất 08 trang HTML
- [x] Trang chủ tên `index.html`
- [x] Có Header, Navigation, Hero/Banner, Section, Grid, Card, Button/Link, Footer
- [x] Có Semantic HTML5
- [x] Có Flexbox và CSS Grid
- [x] Có Media Queries
- [x] Có responsive Desktop / Tablet / Mobile
- [x] Có form liên hệ minh họa
- [x] Blog có bài chi tiết đọc được
- [x] Đường dẫn nội bộ dùng đường dẫn tương đối
- [x] Có thư mục `images/` với đúng tên file được HTML sử dụng
- [x] Có README.md
- [x] Có file `website.txt` trong project
- [ ] Sau khi upload GitHub: kiểm tra URL GitHub Pages thực tế hoạt động

## 10. Tác giả

Nguyễn Minh Kha

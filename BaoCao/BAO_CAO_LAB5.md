# BÁO CÁO RWD LAB 5 – MƠ STUDIO

## Giới thiệu
MƠ Studio là website boutique thời trang tối giản được xây dựng mới để vận dụng HTML5, CSS3, Bootstrap 5, JavaScript và Responsive Web Design.

## Công nghệ
HTML5, CSS3, Bootstrap 5.3, JavaScript ES6, CSS Grid, Flexbox, Media Queries, localStorage và ảnh tham khảo Pexels CDN.

## Chức năng
- Ba trang: Trang chủ, Về MƠ, Liên hệ.
- 8 sản phẩm render từ dữ liệu JavaScript.
- Tìm kiếm và lọc sản phẩm.
- Chuyển giao diện sáng/tối.
- Form liên hệ kiểm tra dữ liệu và lưu demo bằng localStorage.
- SEO cơ bản: title, description, Open Graph, favicon, robots.txt, sitemap.xml.

## Kiểm thử cần thực hiện
| Hạng mục | Kết quả thực tế | Minh chứng |
|---|---|---|
| Mobile 360–480px | Chưa kiểm thử | Bổ sung ảnh |
| Tablet 768px | Chưa kiểm thử | Bổ sung ảnh |
| Desktop 1200px+ | Chưa kiểm thử | Bổ sung ảnh |
| Lọc và tìm kiếm | Chưa kiểm thử | Bổ sung ảnh |
| Form validation | Chưa kiểm thử | Bổ sung ảnh |
| Lighthouse Mobile | Chưa chạy | Bổ sung báo cáo |
| Lighthouse Desktop | Chưa chạy | Bổ sung báo cáo |

## Kết quả nén ảnh thực tế

10 ảnh JPG đã được tải về và tối ưu bằng Pillow. Ảnh được chuyển sang RGB, xoay theo EXIF, resize theo kích thước hiển thị, lưu JPEG progressive với quality 82 và optimize.

| Tệp ảnh | Kích thước | Dung lượng |
|---|---:|---:|
| hero-editorial.jpg | 1600 × 2477 | 206,810 B |
| about-editorial.jpg | 1200 × 1671 | 102,529 B |
| blazer-look.jpg | 1000 × 1500 | 85,342 B |
| everyday-neutral.jpg | 1000 × 1500 | 112,753 B |
| casual-look.jpg | 1000 × 1500 | 146,242 B |
| midi-look.jpg | 1000 × 1500 | 181,254 B |
| shorts-look.jpg | 1000 × 1500 | 67,155 B |
| accessories-flatlay.jpg | 1100 × 1465 | 352,913 B |
| bag-accessories.jpg | 1000 × 667 | 69,936 B |
| editorial-flatlay.jpg | 1200 × 799 | 109,343 B |
| **Tổng cộng** | **10 ảnh JPG** | **1,434,277 B (~1.37 MiB)** |

Nguồn ảnh: `assets/img/optimized/IMAGE_SOURCES.txt`. Các tệp JPG đã được commit vào GitHub trong thư mục tối ưu. Đây là dung lượng sau nén; chưa có số liệu dung lượng ảnh gốc để tính phần trăm giảm.

## Kết luận
Dự án đã có cấu trúc website ba trang, giao diện responsive và tương tác JavaScript cơ bản. Cần chạy kiểm thử trên trình duyệt, lưu ảnh minh chứng và bổ sung kết quả Lighthouse thực tế trước khi nộp.


## Nguồn ảnh và tối ưu ảnh
Ảnh thật tải từ Pexels, sau đó được chuyển về JPG, giới hạn chiều rộng tối đa 1400px, nén JPEG quality 78, optimize và progressive bằng Pillow. Ảnh đầu ra được lưu trực tiếp trong `assets/img/optimized/`, website sử dụng đường dẫn tương đối tới tệp cục bộ.

Nguồn ảnh:
- Matheus Rodrigues: https://www.pexels.com/photo/woman-wearing-beige-blazer-in-studio-23531833/
- cottonbro studio: https://www.pexels.com/photo/studio-shot-of-fashion-model-9142805/
- Thirdman: https://www.pexels.com/photo/beautiful-woman-in-between-hanging-clothes-8484138/
- Matheus Rodrigues: https://www.pexels.com/photo/woman-wearing-beige-blazer-in-studio-23531832/
- Jonathan Borba: https://www.pexels.com/photo/studio-shot-of-a-woman-in-a-trendy-casual-outfit-19456445/
- rasul lotfi: https://www.pexels.com/photo/elegant-woman-in-minimalist-fashion-pose-31845548/
- Marcelo Verfe: https://www.pexels.com/photo/a-woman-wearing-a-beige-blazer-12951783/
- Mikhail Nilov: https://www.pexels.com/photo/a-pretty-woman-in-beige-long-sleeves-standing-7624799/
- elena_sher: https://www.pexels.com/photo/stylish-flat-lay-of-fashion-and-accessories-33482420/
- Tetiana Kotyk: https://www.pexels.com/photo/stylish-accessories-and-beauty-essentials-flat-lay-28973056/
- cottonbro studio: https://www.pexels.com/photo/flat-lay-of-clothing-and-accessories-3927390/

Pexels License: https://www.pexels.com/legal-pages/license/

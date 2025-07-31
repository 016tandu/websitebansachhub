# BÁO CÁO ĐỒ ÁN CUỐI KỲ

**HỌC PHẦN: LẬP TRÌNH WEB**

**ĐỀ TÀI: XÂY DỰNG WEBSITE BÁN SÁCH TĨNH**

---

**GIẢNG VIÊN HƯỚỚNG DẪN:** NGUYỄN QUANG TẤN

**SINH VIÊN THỰC HIỆN:** VÕ LÊ HOÀNG VÂN

**MSSV:** 221A010232

**LỚP:** K22.CNTTA

---

*TP. HỒ CHÍ MINH, NĂM 2025*

---

## **MỤC LỤC**

- **CHƯƠNG 1: TỔNG QUAN VỀ ĐỀ TÀI**
  - 1.1. Giới thiệu đề tài
  - 1.2. Mục tiêu của đề tài
  - 1.3. Phạm vi nghiên cứu
  - 1.4. Lợi ích của đề tài
- **CHƯƠNG 2: CƠ SỞ LÝ THUYẾT**
  - 2.1. Kiến thức thiết kế website
    - 2.1.1. HTML - Xây dựng cấu trúc trang web
    - 2.1.2. CSS - Thiết kế giao diện và bố cục
    - 2.1.3. JavaScript - Tạo tương tác phía người dùng
  - 2.2. Các công cụ phần mềm
- **CHƯƠNG 3: THIẾT KẾ WEBSITE**
  - 3.1. Bố cục và chức năng các trang
    - 3.1.1. Trang chủ (index.html)
    - 3.1.2. Trang sản phẩm (product.html)
    - 3.1.3. Trang giỏ hàng (cart.html)
    - 3.1.4. Trang đăng nhập và đăng ký
  - 3.2. Hình ảnh minh họa giao diện
- **CHƯƠNG 4: KẾT LUẬN**
- **TÀI LIỆU THAM KHẢO**

---

## **CHƯƠNG 1: TỔNG QUAN VỀ ĐỀ TÀI**

### **1.1. Giới thiệu đề tài**

Trong thời đại số, việc mua sắm trực tuyến đã trở thành một thói quen phổ biến. Website bán sách không chỉ là nơi để khách hàng tìm kiếm và mua sản phẩm mà còn là không gian để khám phá tri thức. Đề tài **"Xây dựng Website Bán Sách Tĩnh"** tập trung vào việc tạo ra một giao diện website bán sách chuyên nghiệp, trực quan và dễ sử dụng, dù không có hệ thống backend phức tạp. Website này đóng vai trò là một "showroom online", giới thiệu sản phẩm một cách hiệu quả đến người dùng.

### **1.2. Mục tiêu của đề tài**

- **Cung cấp thông tin chi tiết về sản phẩm:** Hiển thị các đầu sách một cách rõ ràng với đầy đủ thông tin như tên sách, tác giả, giá bán, và mô tả.
- **Nâng cao trải nghiệm người dùng:** Xây dựng giao diện thân thiện, logic, giúp người dùng dễ dàng tìm kiếm, xem thông tin và thực hiện các hành động trên trang.
- **Xây dựng giao diện thu hút, chuyên nghiệp:** Thiết kế một website có giao diện hiện đại, sạch sẽ, sử dụng hình ảnh chất lượng cao và hiệu ứng mượt mà để tạo ấn tượng tốt với khách hàng.

### **1.3. Phạm vi nghiên cứu**

- **Phạm vi nội dung:** Website là một trang tĩnh, tập trung vào việc hiển thị giao diện và trải nghiệm người dùng. Không có chức năng xử lý logic phía máy chủ như đặt hàng, thanh toán online, hay quản lý tài khoản người dùng. Dữ liệu sản phẩm được giả lập trực tiếp trong mã HTML.
- **Phạm vi kỹ thuật:**
  - Sử dụng **HTML5** để xây dựng cấu trúc.
  - Sử dụng **CSS3** (với Flexbox và Grid) để tạo bố cục và định dạng giao diện.
  - Sử dụng **JavaScript (Vanilla JS)** để xử lý các tương tác cơ bản như carousel, menu, và các hiệu ứng động khác.
  - Không sử dụng bất kỳ framework CSS (Bootstrap, Tailwind) hay thư viện JavaScript (jQuery, React) nào.

### **1.4. Lợi ích của đề tài**

- **Dễ dàng tiếp cận khách hàng:** Một website chuyên nghiệp giúp cửa hàng tiếp cận được lượng lớn khách hàng tiềm năng trên Internet.
- **Tiết kiệm chi phí:** Phát triển web tĩnh không đòi hỏi chi phí cho máy chủ backend, cơ sở dữ liệu và bảo trì hệ thống phức tạp.
- **Tăng uy tín thương hiệu:** Giao diện được đầu tư kỹ lưỡng giúp xây dựng hình ảnh chuyên nghiệp và đáng tin cậy cho cửa hàng.
- **Nền tảng để phát triển:** Từ phiên bản tĩnh này, có thể dễ dàng nâng cấp lên một website động hoàn chỉnh trong tương lai.

---

## **CHƯƠNG 2: CƠ SỞ LÝ THUYẾT**

### **2.1. Kiến thức thiết kế website**

Để xây dựng website này, các công nghệ nền tảng của lập trình web front-end đã được sử dụng.

#### **2.1.1. HTML - Xây dựng cấu trúc trang web**

HTML (HyperText Markup Language) là ngôn ngữ đánh dấu siêu văn bản, được sử dụng để tạo nên cấu trúc và các thành phần của một trang web. Trong dự án này, HTML5 được dùng để:

-   Định nghĩa các vùng chính của trang như `<header>`, `<footer>`, `<main>`, `<nav>`, `<section>`.
-   Hiển thị nội dung sản phẩm sách bao gồm hình ảnh (`<img>`), tiêu đề (`<h3>`), giá (`<span>`).
-   Tạo các liên kết điều hướng giữa các trang (`<a>`).

*Ví dụ: Cấu trúc một thẻ sản phẩm trong `index.html`*
```html
<!-- Product Card 1 -->
<div class="product-card style-1">
  <div class="product-image-container">
    <a href="product.html"
      ><img src="assets/10009.jpg" alt="Tên sách"
    /></a>
    <div class="discount-badge">Giảm 40%</div>
  </div>
  <div class="product-info">
    <div class="product-rating">★★★★★</div>
    <h3 class="product-title">
      <a href="product.html"
        >Tâm Thành và Lộc Đời (Kèm CD "Cuộc đời hoài phí")</a
      >
    </h3>
    <div class="product-price">
      <span class="original-price">150,000 đ</span>
      <span class="sale-price">90,000 đ</span>
    </div>
    <button class="add-to-cart-btn">CHỌN MUA</button>
  </div>
</div>
```

#### **2.1.2. CSS - Thiết kế giao diện và bố cục**

CSS (Cascading Style Sheets) được sử dụng để định dạng và tạo phong cách cho các phần tử HTML.

-   **Bố cục:** Sử dụng `Flexbox` và `Grid` để sắp xếp các thành phần một cách linh hoạt và khoa học, đảm bảo website hiển thị tốt trên nhiều kích thước màn hình (responsive).
-   **Định dạng:** Tùy chỉnh màu sắc, font chữ, khoảng cách để tạo ra một giao diện hài hòa, dễ đọc.
-   **Hiệu ứng:** Tạo các hiệu ứng đơn giản như `hover`, `transition` để tăng tính tương tác.

*Ví dụ: Một đoạn CSS định dạng cho thẻ sản phẩm*
```css
.product-card {
  background-color: #fff;
  border: 1px solid #eee;
  border-radius: 8px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  transition: box-shadow 0.3s ease;
}

.product-card:hover {
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
}

.product-info {
  padding: 15px;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}
```

#### **2.1.3. JavaScript - Tạo tương tác phía người dùng**

JavaScript được sử dụng để "thổi hồn" vào trang web, giúp nó trở nên sống động và có thể phản hồi lại các hành động của người dùng.

-   **Carousel/Slider:** Xử lý logic cho các khối trượt hình ảnh quảng cáo và sản phẩm.
-   **Dropdown và Menu:** Quản lý việc đóng/mở các menu thả xuống như menu ngôn ngữ và menu danh mục sản phẩm.
-   **Fetch API:** Tải động nội dung của `header.html` và `footer.html` vào các trang khác để tái sử dụng code.

*Ví dụ: Đoạn mã JavaScript để tải header và footer động*
```javascript
// Function to fetch and insert header/footer
function loadHeaderAndFooter() {
    // Fetch Header
    fetch('header.html')
        .then(response => response.text())
        .then(data => {
            document.getElementById('header').innerHTML = data;
        });

    // Fetch Footer
    fetch('footer.html')
        .then(response => response.text())
        .then(data => {
            document.getElementById('footer').innerHTML = data;
        });
}

// Load them on initial page load
loadHeaderAndFooter();
```

### **2.2. Các công cụ phần mềm**

-   **Visual Studio Code:** Trình soạn thảo mã nguồn chính được sử dụng, với các tiện ích mở rộng như Live Server để xem trước trang web theo thời gian thực.
-   **Trình duyệt web (Google Chrome, Firefox):** Để kiểm tra, gỡ lỗi (debug) và đảm bảo tính tương thích của website.
-   **Git & GitHub:** Để quản lý phiên bản mã nguồn và lưu trữ dự án.

---

## **CHƯƠNG 3: THIẾT KẾ WEBSITE**

### **3.1. Bố cục và chức năng các trang**

Website được cấu trúc từ nhiều trang con, mỗi trang đảm nhận một vai trò riêng biệt.

#### **3.1.1. Trang chủ (index.html)**

Đây là trang đầu tiên khách hàng nhìn thấy, có vai trò giới thiệu tổng quan và thu hút người dùng.
-   **Header:** Chứa logo, menu danh mục (dạng dropdown), thanh tìm kiếm, link đến trang đăng nhập/giỏ hàng và lựa chọn ngôn ngữ.
-   **Hero Section:** Gồm một carousel trình chiếu các banner quảng cáo lớn và các banner khuyến mãi nhỏ có thể nhấp vào để xem chi tiết.
-   **Product Sections:** Hiển thị các sản phẩm nổi bật theo từng danh mục như "Deal Hot - Giảm Sốc", "Sách Tiếng Việt", "Sách Giáo Khoa". Các khu vực này cũng sử dụng carousel để trình bày được nhiều sản phẩm.
-   **Footer:** Chứa thông tin về cửa hàng, chính sách, liên kết mạng xã hội và thông tin liên hệ.

#### **3.1.2. Trang sản phẩm (product.html)**

Trang này cung cấp thông tin chi tiết về một cuốn sách cụ thể khi người dùng nhấp vào từ trang chủ.
-   **Ảnh sản phẩm:** Hiển thị ảnh bìa sách với kích thước lớn.
-   **Thông tin chi tiết:** Tên sách, tác giả, đánh giá, giá bán.
-   **Mô tả:** Đoạn văn giới thiệu chi tiết về nội dung sách.
-   **Nút "Thêm vào giỏ hàng":** Kêu gọi hành động chính trên trang.

#### **3.1.3. Trang giỏ hàng (cart.html)**

Mô phỏng giỏ hàng của người dùng sau khi đã chọn một vài sản phẩm.
-   **Danh sách sản phẩm:** Liệt kê các sản phẩm đã thêm vào giỏ, bao gồm hình ảnh, tên, giá, số lượng.
-   **Tùy chỉnh số lượng:** Người dùng có thể thay đổi số lượng sản phẩm.
-   **Tổng kết đơn hàng:** Hiển thị tổng tiền tạm tính, phí vận chuyển và tổng cộng cuối cùng.
-   **Nút "Tiến hành thanh toán":** Điều hướng người dùng đến bước tiếp theo (trong một website động).

#### **3.1.4. Trang đăng nhập (login.html) và Đăng ký (register.html)**

Cung cấp giao diện cho phép người dùng nhập thông tin để đăng nhập hoặc tạo tài khoản mới. Các trang này chỉ bao gồm form nhập liệu và không có xử lý logic.

### **3.2. Hình ảnh minh họa giao diện**

*(Lưu ý: Đây là các placeholder. Bạn cần chụp ảnh màn hình giao diện website của mình và chèn vào đây.)*

**1. Giao diện Trang chủ**
> *[Chèn ảnh chụp màn hình trang chủ tại đây]*

**2. Giao diện Menu Danh mục**
> *[Chèn ảnh chụp màn hình menu danh mục khi đang mở tại đây]*

**3. Giao diện Trang Chi tiết Sản phẩm**
> *[Chèn ảnh chụp màn hình trang product.html tại đây]*

**4. Giao diện Trang Giỏ hàng**
> *[Chèn ảnh chụp màn hình trang cart.html tại đây]*

**5. Giao diện Trang Đăng nhập**
> *[Chèn ảnh chụp màn hình trang login.html tại đây]*

---

## **CHƯƠNG 4: KẾT LUẬN**

Đồ án **"Xây dựng Website Bán Sách Tĩnh"** đã hoàn thành các mục tiêu đề ra, tạo ra một sản phẩm website hoàn chỉnh về mặt giao diện người dùng. Bằng cách sử dụng các công nghệ nền tảng là **HTML, CSS và JavaScript**, dự án đã chứng minh rằng có thể xây dựng một trang web chuyên nghiệp, hiện đại và có trải nghiệm người dùng tốt mà không cần đến các framework phức tạp hay hệ thống backend.

-   **Ưu điểm:**
    -   Giao diện được thiết kế sạch sẽ, logic và thân thiện.
    -   Website có tốc độ tải nhanh, chi phí vận hành thấp.
    -   Mã nguồn được tổ chức tốt, dễ dàng bảo trì và nâng cấp.
    -   Là một nền tảng vững chắc để phát triển thành một hệ thống thương mại điện tử hoàn chỉnh.

-   **Hạn chế:**
    -   Vì là web tĩnh, các chức năng như tìm kiếm, lọc sản phẩm, giỏ hàng, thanh toán chỉ là mô phỏng.
    -   Việc cập nhật sản phẩm và nội dung phải thực hiện thủ công trong mã nguồn.

-   **Hướng phát triển:**
    -   Tích hợp backend (sử dụng Node.js, Python, hoặc PHP) để quản lý sản phẩm, đơn hàng và người dùng.
    -   Kết nối với cơ sở dữ liệu (MySQL, MongoDB) để lưu trữ dữ liệu một cách có hệ thống.
    -   Phát triển các tính năng nâng cao như thanh toán trực tuyến, gợi ý sản phẩm, hệ thống đánh giá của khách hàng.

Tóm lại, dự án là một bài thực hành hữu ích, giúp củng cố vững chắc kiến thức về lập trình front-end và là một bước đệm quan trọng cho các dự án web phức tạp hơn trong tương lai.

---

## **TÀI LIỆU THAM KHẢO**

-   W3Schools. (n.d.). *HTML, CSS, JavaScript Tutorials*. Truy cập tại: <https://www.w3schools.com>
-   Mozilla Developer Network (MDN). (n.d.). *Web Docs*. Truy cập tại: <https://developer.mozilla.org>
-   CSS-Tricks. (n.d.). *Guides, Articles, and Videos on CSS*. Truy cập tại: <https://css-tricks.com>
-   FreeCodeCamp. (n.d.). *Learn to code — for free*. Truy cập tại: <https://www.freecodecamp.org>

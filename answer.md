Phần A
#A1. 
    1. Khi người dùng truy cập shopee.vn và ấn enter, trình duyệt thực hiện các bước:
    B1: Nhập shopee.vn
    B2: Máy tìm địa chỉ IP của website
    B3: Kết nối tới server
    B4: Gửi yêu cầu xin dữ liệu
    B5: Server trả về dữ liệu, sau đó trình duyệt hiển thị trang web

    2. Trong DevTools của Chrome, tab Network hiển thị:
    - Danh sách các request
    - Status code của từng request 
    - Loại tài nguyên(Type)
    - Thời gian tải(Time)
    - Kích thước dữ liệu(Size)
    - Tổng thời gian load trang(finish)


#A2.
    Trang web dưới đây bị Google đánh giá SEO thấp vì lạm dụng <div>.
    Lỗi 1: Không dùng <header> cho phần đầu trang mà dùng <div>: <div class="header">
    Lỗi 2: Không dùng <nav> cho menu mà dùng <div class="menu">
    Lỗi 3: Không dùng <main> cho nội dung chính mà dùng <div class="main">
    Lỗi 4: Không dùng <article> cho sản phẩm mà dùng  <div class="product">
    Dùng <p> để chứa 1 đoạn văn thay vì <div class="price">25.990.000đ</div>
    Nên dùng <footer> thay vì <div class="footer">© 2026 ShopTLU</div>
    Sửa lại:
    <header>
        <div class="logo">ShopTLU</div>
        <nav>
            <a href="/">Trang chủ</a>
            <a href="/products">Sản phẩm</a>
        </nav>
    </header>

    <main>
       <article class="product">
        <h1>iPhone 16 Pro</h1>
        <p class="price">25.990.000đ</p>
        <img src="iphone.jpg" alt= "iPhone 16 Pro">
       </article>
    </main>

    <footer>
        <p>© 2026 ShopTLU</p>
    </footer>

#A3.
    Do thẻ <div> là thẻ block, chiếm cả dòng nên khi đóng thẻ </div> thì sẽ phải xuống dòng mới để viết, còn các thẻ <span> và <strong> là các thẻ inline, chỉ chiếm phần nội dung nằm trong thẻ nên khí đóng 2 thẻ này vẫn có thể viết tiếp nội dung nằm cạnh nhau trên dòng đó hoặc xuống dòng mới để viết. 
    Text art:
        Hộp 1
        Text A Text B
        Hộp 2
        Text C Text D
        Hộp 3

#A4.
    <thead>: Là phần đầu bảng, chứa tiêu đề cột
    <tbody>: Là phần nội dung chính của bảng, dùng để chứa dữ liệu chính của bảng
    <tfoot>: Là phần cuối bảng dùng để chứa các kết luận, thống kê, tổng kết của bảng
    KHÔNG NÊN dùng table để tạo layout trang web vì:
    - Table dùng để chứa dữ liệu bảng, không phải để chia layout web
    - Table phải load xong toàn bộ mới hiển thị đúng nên trang web sẽ bị tải chậm

#B3
    Lỗi 1 — Dòng 1 — <!DOCTYPE> thiếu "html" — Sửa thành <!DOCTYPE html>.
    Lỗi 2 — Dòng 2 — Thiếu thuộc tính lang cho thẻ <html> — Thêm lang="vi" (hoặc en) vào <html>.
    Lỗi 3 — Dòng 4 — Thẻ <title> không đóng — Đóng thẻ </title>
    Lỗi 4 — Dòng 5 — meta charset="utf8" thiếu dấu nối — Đổi thành meta charset="utf-8".
    Lỗi 5 — Dòng 8 — Thẻ <h1> không đóng — Sửa thành <h1>....</h1>
    Lỗi 6 — Dòng 12 — Thẻ <a> không đóng — Sửa thành <a>....</a>
    Lỗi 7 — Dòng 20 — img src=iphone.jpg thiếu dấu ngoặc kép quanh giá trị và không có alt — Sửa lại thành img src="iphone.jpg" alt="iPhone 16 Pro">.
    Lỗi 8 — Dòng 22 — Thẻ <b> và </p> bị lồng sai: <p>Giá: <b>25.990.000đ</p></b> — Sửa thứ tự đóng: <p>Giá: <b>25.990.000đ</b></p>.
    Lỗi 9 — Dòng 28 — Bảng thiếu <thead> và <tbody> — Thêm vào để chuẩn cấu trúc.
    Lỗi 10 — Dòng 40 — Dùng hai thẻ <main> lần sai, sai về ngữ nghĩa — Đổi thẻ phụ thành <aside>
    Lỗi 11 — Dòng 45 — Thẻ <footer> chứa <p> nhưng không đóng </p> — Thêm </p> trước </footer>.
    Lỗi 12 — Dòng 48 — Thẻ <html> không đóng — Thêm </html>

    


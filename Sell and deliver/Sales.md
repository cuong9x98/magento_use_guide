# Sale 
 - Giỏ hàng là trang quyết định trong việc khách hàng có mua sản phẩm hay không .Nên sẽ có nhiều configuration quan trọng trong trang này được magento thêm vào.
 ## 1.Point of Purchase
  - Tại phần này sẽ hướng dẫn các bạn các tùy chọn mua hàng.
### a.Mua hàng nhanh 
    - Thường khi mua hàng thì các bạn sẽ phải xác minh thông tin khi mua hàng để giúp khách hàng thuận tiện trong việc mua hàng magento hỗ trợ mua hàng nhanh bằng nút mua hàng nhanh dưới nút add to cart.
    - Đương nhiên để làm được điều đó khách hàng phải đăng nhập và đã xác minh phương thức thanh toán , hình thức vẫn chuyển.
    - Thiết lập: 
        + Các bạn vào Stores > Settings > Configuration.Tiếp theo Sales section và chọn Payment Methods. Tiếp theo là Recommended Solutions->Configure
        + Email Associated with PayPal Merchant Account (Optional)	: Email được liên kết tài khoản Paypal
        + API Authentication Methods	: Phương thức API
        + API Signature
        + API Username	:Tên người dùng API
        + API Password	: Mật khẩu API
        + API Signature	: Chữ ký API
        + Sandbox Mode	:chế độ Sanbox
        + API Uses Proxy	: API sử dụng Proxy
        + Enable this Solution	: Bật chế dộ 
        + Enable In-Context Checkout Experience
    => Bây giờ các bạn sẽ bật hết các chế dộ và nhập các thông tin cần thiết .Tiếp theo các bạn còn phải tạo tài khoản xác thực thanh toán Paypal nữa khá là mất công.
### b.Shopping Cart
    - Vâng tất nhiên rồi đây là cách mua cơ bản mà khách hàng sẽ thường được dùng.Phần này thì chắc các bạn biết hết rồi mình sẽ không nói nữa.
### c.Shopping Assistance
    - Trong Magento sẽ hỗ trợ khách hàng mua sắm như admin quản lí các đơn hàng và mình sẽ có file riêng về phần này trong thư mục bổ sung nói về menu Customer trong trang quản trị.
### d.Checkout 
    - Đây sẽ là trang thủ tục thanh toán.
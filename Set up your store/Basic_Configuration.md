# Basic Configuration 
## I.Store Admin
    - Quản trị viên cửa hàng của bạn là văn phòng hỗ trợ được bảo vệ bằng mật khẩu, nơi bạn, với tư cách là người bán, có thể thiết lập sản phẩm và chương trình khuyến mãi, quản lý đơn đặt hàng và thực hiện các tác vụ quản trị khác. Tất cả các tác vụ cấu hình cơ bản và các thao tác quản lý cửa hàng đều được thực hiện từ Admin.
    - Nếu bạn chọn Cho phép , Magento sẽ thu thập dữ liệu sử dụng để giúp cải thiện trải nghiệm người dùng của Quản trị viên cũng như các sản phẩm và dịch vụ liên quan. Bắt đầu với Magento Commerce 2.4.2, tính năng này cũng cho phép Hướng dẫn trong sản phẩm tương tác , cung cấp cho người dùng Quản trị viên trợ giúp và mẹo sử dụng sản phẩm tốt hơn từ trong Giao diện người dùng dành cho quản trị viên. Các nội dung như thông báo tính năng mới, hướng dẫn đi bộ, thông tin giới thiệu, mẹo công cụ, v.v. sẽ có sẵn thông qua tính năng này. Dữ liệu sử dụng không thể được sử dụng để xác định riêng bất kỳ quản trị viên nào. Bạn có thể thay đổi cài đặt này bất kỳ lúc nào từ cài đặt cấu hình Quản trị viên .
    => Khi bạn đăng nhập lần đầu thì sẽ có 1 thông báo xin phép bạn thu thập dữ liệu người quản trị.
## II.Store Details
    - Thông tin cơ bản cho cửa hàng của bạn bao gồm tên và địa chỉ cửa hàng, số điện thoại và địa chỉ email, xuất hiện trên email, hóa đơn và các thông tin liên lạc khác được gửi cho khách hàng của bạn.
    => Store -> Configfiguration -> Genenal -> ...
## III.Storefront Branding
    - Cho phép thay đổi giao diện của cửa hàng tải lên các biểu tượng yêu thích đó là : Logo ,footer 
    - Thay đổi logo : Admin-> Content->Design->Configuration.Tìm đến chế độ xem của hàng mà bạn muốn thay đổi -> chọn edit. Tìm vào mục Header sau đó upload ảnh mới sau đó lưu lại.
    -  Thêm thông báo chào mừng :  Admin-> Content->Design->Configuration.Tìm đến chế độ xem của hàng mà bạn muốn thay đổi -> chọn edit. Tìm vào mục wellcome text sửa lại là ok . Lưu lại .
    - Cập nhật thông báo bản quyền :  Admin-> Content->Design->Configuration.Tìm đến chế độ xem của hàng mà bạn muốn thay đổi -> chọn edit. Tìm vào mục  Footer -> Conpyright . Sau đó bạn sẽ sửa lại và lưu thôi.
    - Bật thông báo giới thiệu của hàng thử nghiệm: Cập nhật thông báo bản quyền :  Admin-> Content->Design->Configuration.Tìm đến chế độ xem của hàng mà bạn muốn thay đổi -> chọn edit. Chọn HTML Head -> Display Demo Store Notice -> bạn chỉnh sửa lại và lưu.
## IV.Website, Store,Stores and View
    - Tại đây sẽ giới thiệu 3 khái niệm chính trong 1 website magento là websites, Store, Store View.1 trang web có thể nhiều cửa hàng và 1 cửa hàng có thể có nhiều chế độ xem cửa hàng.
### 1.Websites
    - Các websitetrong magento sở hữu các IP và tên miền riêng biệt.
### 2.Store 
    - 1 Website sẽ có nhiều cửa hàng giống như 1 nhà phân phối có nhiều chi nhánh Hà Nội, HCM, Đà Nẵng. 
### 3.Store View
    - 1 Store sẽ có nhiều Store View giống như 1 chi nhánh có thể thay đổi nhiều giao diện : giao diện 8/3, tết, noel,sinh nhật,...
### Cách tạo 1 website mới : 
        + 1.Tạo 1 danh mục gốc.
        + 2.Tạo Website, go to Stores > Settings > All Stores . Chọn Create new website sau đó nhập các thông tin vào form sau đó lưu lại. 
        + 3.Tạo Store : Admin sidebar, go to Stores > Settings > All Stores. Bạn chọn Create Stote, tiếp theo chúng ta chọn Store cho Website nào và tên, Name,Code,Root Category.
        + 4.Store View : chúng ta làm tương tụ nhưng chỉ cần chọn Create Store View 
        + 5.Thay đổi URL cở sở trang web.Vào trong Store -> configuration ->Genenal ->Web. Sửa lại URL base và URL link base kể cả Secure base url.
        +6.Thêm mã cửa hàng vào URL cơ sở
        +7.Thay đổi URL cơ sở chế độ xem cửa hàng mặc định
        => Các bạn hoàn toàn có thể xem trong video của traning.
## V.B2B Capabilitiles
- Mình sẽ có file riêng về phần này.
## VI.Industry Compliance
- Magento cung cấp một loạt các khả năng bảo mật và quyền riêng tư đáp ứng các yêu cầu pháp lý và nguyên tắc ngành cho người bán trực tuyến. Một số do ngành thẻ thanh toán bắt buộc và một số khác do luật pháp yêu cầu, tùy thuộc vào vị trí của bạn.
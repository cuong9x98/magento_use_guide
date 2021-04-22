# Content 
 - Nội dung của bạn xác định các trang và yếu tố mà khách hàng nhìn thấy khi họ truy cập vào cửa hàng của bạn. Bạn có thể xác định các yếu tố cơ bản cho các trang của mình, chẳng hạn như văn bản và hình ảnh, cũng như các yếu tố nâng cao hơn cung cấp nội dung động và tương tác để nâng cao trải nghiệm mua sắm.

## 1.Các yếu tố quyết định nội dung.
    - 6 yếu tố quyết định đến nội dung trang web trong đó có 3 nội dung trong magento Commerce :
        + 1.Page
        + 2.Block
        + 3.Widget
        + 4.Page Hierarchy
        + 5.Dynamic Blocks
        + 6.Templates.
    1.Page
        - Là 1 khối bao gồm toàn bộ nội dung của 1 địa chị website.
    2.Block 
        - Một khối là đơn vị mô-đun của nội dung có thể được bố trí bất cứ nơi nào nhất trên trang. Các khối nội dung đôi khi được gọi là khối tĩnh hoặc khối CMS . Chúng có thể được sử dụng để hiển thị thông tin cố định như văn bản, hình ảnh và video nhúng cũng như thông tin động được cung cấp bởi tiện ích con hoặc bắt nguồn từ cơ sở dữ liệu hoặc nguồn khác. Hầu hết các phần tử trên trang chủ là các khối có thể dễ dàng quản lý.
    3.Widget
        - Tiện ích con là một đoạn mã giúp bạn có thể hiển thị nhiều loại nội dung và đặt nó tại các tham chiếu khối cụ thể trong cửa hàng của bạn. Nhiều hiển thị dữ liệu động, thời gian thực và tạo cơ hội cho khách hàng tương tác với cửa hàng của bạn. Công cụ Widget giúp bạn dễ dàng đặt một widget trong nội dung hiện có, chẳng hạn như các khối có hình ảnh và văn bản cũng như các yếu tố tương tác ở hầu hết mọi nơi trong cửa hàng của bạn.
        => Widget là 1 khỗi dữ liệu động khách hàng có thể thay đổi 1 cách dễ dàng và có thể áp dụng cho nhiều trang.

    => 3 yếu tố còn lại 
## 2.Thiết kế chủ đề.
### a.Cấu hình thiết kế.
    - Bạn sẽ vào Admin sidebar, go to Content > Design > Configuration 
    - Các bạn tìm vào Store view bạn click edit trong cột action 
    - Tiếp theo bạn có thể thay đổi theme trong thêm default -> Applied Theme.
    - Nếu theme được áp dụng cho 1  các thiết bị riêng biệt thì chúng ta dùng User Agent Rules.Bạn có thể thêm /(iPhone|iPod|iPad|Android)/i vào Searching và đặt cho theme blank sau đó lưu lại.Tiếp theo tại trang giao diện bạn sẽ mở màn mobile lên và reload lại sẽ thấy theme blank và khi bạn chuyển lại màn desktop rồi reload sẽ ra theme luma.
    - Các trường trong Congiguration:
        + Pagination Controls : Điều khiển số trang .go to Content > Design > Configuration Chọn action->Edit.Chọn Other Setting và Pagination
            +   Pagination Frame : Hiện thị số trang có thể bấm
            +   Pagination Frame Skip :Nó cho phép bạn bỏ qua số page bạn quy định ví dụ: bạn có 50 page bạn skip 10 page thì nó như thế này 1 ...11....50
            +   Anchor Text for Previous :thay thế kí tự lùi trang bằng đoạn text của mình nếu không có thì sẽ mặc định kí hiệu <
            +   Anchor Text for Next : thay thế kí tự sang trang bằng đoạn text của mình nếu không có thì sẽ mặc định kí hiệu >
        + HTML Head :
            +   Favicon Icon : Tải lên hình ảnh đồ họa nhỏ xuất hiện trong thanh địa chỉ và tab của trình duyệt. Các loại tệp được phép: ICO, PNG, APNG, GIF và JPG (JPEG). Không phải tất cả các trình duyệt đều hỗ trợ các định dạng này.=> Khi các bạn tìm kiếm trên trình duyệt thì thấy 1 số tiêu đề các trang web có hình ảnh chứ chính là nó ấy.
            +   Default Page Title : là tiêu đề mặc định các trang trên trình duyệt.Tiêu đề mặc định được sử dụng cho tất cả các trang, trừ khi tiêu đề khác được chỉ định cho các trang riêng lẻ.Tức là khách hàng tìm của hàng chúng ta trên trình duyệt sẽ hiện thị tiêu đều  này.
            +   Page Title Prefix
            +   Page Title Suffix
            +   Default Meta Description : Hỗ trợ tìm kiếm trang web của hàng trên trình duyệt của khách hàng.
            +   Default Meta Keywords : Hỗ trợ tìm kiếm trang web của hàng trên trình duyệt của khách hàng.
            +   Scripts and Style Sheets : Chứa các tập lệnh phải được đưa vào HTML trước <head>thẻ đóng . Ví dụ: bất kỳ JavaScript của bên thứ ba nào phải được đặt trước khi <body>thẻ có thể được nhập vào đây.Nói toạc ra là thêm link ccs hoặc js cho nó vuông.
            +   Display Demo Store Notice : Bật thông báo của hàng đang trong quá trình thử nghiệm.
        + HTML :
            +   Logo Image : Ảnh Logo
            +   Logo Attribute Width : chiều ngang ảnh
            +   Logo Attribute Width : Chiều cao ảnh.
        + Footer :
            +   Miscellaneous HTML : Hộp nhập liệu nơi bạn có thể tải các tập lệnh khác lên máy chủ phải được đặt ngay trước <body>thẻ đóng, sau footer
            +   Copyright : đoạn text yêu cầu bản quyền.
            +   Display Report Bugs Link :Bật tắt liên kết báo lỗi.
        + Watermarks : Hình mờ chống kể gian đánh cắp ảnh sản phẩm của bạn 
            + Base : Ảnh cơ sở
            + Thumbnail : hình nhở
            + Small : nhỏ
            +  Image Opacity : Độ mò của ảnh đơn vị %.
            + Image Size : Kích thước ảnh đơn vị px.
            + Image Possition : Vị trí ảnh 
        + Configuring Email Templates : Cấu hình mẫu email. Nó sẽ thêm logo và email của cửa hàng khi xuất mẫu logo.
            +  Logo Image: logo
            +  Logo Image Alt : nếu ko hiện thị thig hiển thị text này
            +  Logo Width: rộng
            +  Logo Height: cao
            + Header Template :Phần đầu  
            + Footer Template :Phần footer

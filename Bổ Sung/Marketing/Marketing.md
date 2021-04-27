# Marketting
## I.Catalog Price Rule
    + Là nơi chứa các quy tắc giá danh mục chiết khấu  theo nhiều tùy chọn khác nhau -> sau khi lưu thì chúng ta chạy lệnh php bin/magento indexer:reindex
## II.Cart Price Rules
    + Là quy định giá giỏ hàng tương tự như Catalog Price Rule nhưng ở đây chúng ta chỉnh giá ở trong giỏ hàng.
    => Chốt lại là phiếu giảm giá.
    +  Rule Name : tên của rule
    +  Description : Mô tả
    +  Active : Trạng thái
    +  Website : Cái này sẽ chạy ở đâu
    + Customer : Chạy cho nhóm khách hàng nào
    + Coupon : Có áp dụng với khách phiếu mua hàng không hay là có
    + Uses per Customer : Dùng cho mỗi khách hàng chỉ áp dụng cho khách đăng nhập
    + From : Thời gian bắt đầu
    + to : Thời gian kết thúc
    + Priority : Độ ưu tiên 
    + Public In RSS Feed :Công khai nguồn cấp RSS
    
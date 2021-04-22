# Configuration.
- Đây là nơi người quản trị có thể thiết lập các cài đặt của mình trên trang web. Là lập trình viên bản thân chúng ta chắc chắn phải biết đến tất cả các tab trong này để về sau khách hàng yêu cầu chỉnh sửa nào đó thì chúng ta có thể tìm ra cách nhanh nhất để giải quyết bài toán mà không cần phải customer lại.

## 1.GENERAL 
- Đây là những thiết lập chung cho người quản trị có thể làm được.

### a.General
- Chứa các thiết lập chung nhất bao gồm;
	+ Country Options : Tùy chọn Quốc gia xác định quốc gia nơi doanh nghiệp của bạn đặt trụ sở và các quốc gia mà từ đó bạn chấp nhận thanh toán.
		+ Default Country : Quốc gia mặc định.
		+ Alllow Countries : Các quốc giá khác bạn chấp nhận đơn đặt hàng.
		+ Zip/Postal Code is Optional for	:  nơi bạn tiến hành hoạt động kinh doanh không yêu cầu bao gồm mã ZIP hoặc mã bưu chính như một phần của địa chỉ đường phố.
		+ European Union Countries : quốc gia trong Liên minh Châu Âu nơi bạn tiến hành hoạt động kinh doanh.
		+ Top destinations	: ác quốc gia chính mà bạn nhắm mục tiêu để bán hàng.
	+ State Options : Lựa chọn trạng thái.
		+ State is Required for : Các quốc gia nơi bạn tiến hành hoạt động kinh doanh yêu cầu bao gồm khu vực hoặc tiểu bang trong địa chỉ bưu điện.
		+ Allow to Choose State if It is Optional for Country : Đối với các quốc gia không bắt buộc, hãy xác định xem trường Khu vực / Tiểu bang có được bao gồm trong địa chỉ bưu điện của khách hàng hay không.Có - Bao gồm trường Khu vực / Tiểu bang trong địa chỉ khách hàng, ngay cả khi quốc gia không yêu cầu.Không - Bỏ qua trường Khu vực / Tiểu bang khỏi địa chỉ khách hàng nếu quốc gia không yêu cầu.
	+ Locale Options : Chọn ngôn ngữ , múi giờ.
		+ Timezone : Múi giờ 
		+ Locale : Ngôn ngữ 
		+ Weught Unit: Đơn vị trọng lượng
		+ First Day of Week : Ngày đầu tuần. => Quy định ngày cuối tuần của hệ thống. 
		+ Weedkend Days : Ngày cuối tuần. => Quy định ngày cuối tuần của hệ thống.
	+ Store Information : Thông tin của cửa hàng. Các bạn có thể lấy thông tin  cửa hàng bằng cacsh làm theo đường dẫn: 	https://www.mageplaza.com/devdocs/how-get-store-information-magento-2.html. Các bạn có thể xem thông tin các bạn lưu lại ở đây bằng cách xem bản mẫu thư điện tử của magento Marketing->Email Templates-> Tại mục Template chọn bất kì bản mẫu nào sao đó bạn chạy lên và click vào  Preview Templates để xem trc lúc đó các bạn có thể xem thấy thông tin của store bạn vừa config.
		+ Store Name : Tên của hàng.
		+ Store Phone Number : Số điện thoại cửa hàng.
		+ Store Hours of Opreration : Giờ hoạt động của cửa hàng 
		+ Count try: Quốc gia.
		+ Region/State : Vùng tiểu bang 
		+ Zip/Postal Code: mã bưu điện
		+ City : tên thành phố
		+ Street Address: Địa chỉ thứ nhất của cửa hàng 
		+ Street Address line 2: Địa chỉ thứ hai của cửa hàng.
		+ VAT Number: Mã số thế .
	+ Single-Store Mode: Chế độ 1 của hàng 
		++ Enable Single- Store Mode : Bật chế độ 1 của hàng . Cài đặt này sẽ không có hiệu quả nếu cửa hàng có sẵn nhiều cửa hàng. 

### 3.Web
- Chứa các cài đặt 
	+ Url Option : 
		+ Add Store to Urls:  ?? 
		+ Auto-redirect to Base URL: Đây cho phép chuyển đến trang cơ sở nếu có 1 link bị hỏng?
	+ Search Engine Optimization : 
		+ Use Web Server Rewiriter : ???
	+ Base URLs : 
		+ Base URL : Địa chỉ trang web cơ sở.(Làm multi website)
		+ Base Link URL : Trình giữ chỗ chỗ cho URL cơ sở.(Làm multi website)
		+ Base URL for Static View Files :???
		+ Base URL for User Media Files: ???
h.
	+ Base URLs(Secure) :
		+ Secure Base URL: Địa chỉ gốc website nhưng được bảo mật bằng cách mã hóa SSL/TLS. URL phải kết túc bằng gạch chéo.(Làm multi website)
		+ Secure Base Link URL: Được sử dụng làm trình giữ chỗ cho URL cơ sở chạy qua kênh bảo mật. (Làm multi website)
		+ Secure Base URL for Static View Files : ???
		+ Secure Base URL for Media Files : ???
		+ Use Secure URLs on Storefront:Nếu miền của bạn có chứng chỉ bảo mật, bạn có thể chọn chạy mặt tiền cửa hàng, có hoặc không có mã hóa SSL. Tùy chọn:Có - URL lưu trữ bắt đầu bằng httpsđể cho biết rằng trang được phân phối bằng giao thức được mã hóa và bảo mật.Không - URL cửa hàng bắt đầu bằng httpđể chỉ ra rằng trang được phân phối mà không có giao thức bảo mật.
		+ Use Secure URLs in Admin : Nếu miền của bạn có chứng chỉ bảo mật, bạn có thể chọn chạy Quản trị viên cửa hàng, có hoặc không có mã hóa SSL. Tùy chọn:Có - URL quản trị bắt đầu bằng httpsđể chỉ ra rằng trang được phân phối bằng giao thức được mã hóa và bảo mật.Không - URL quản trị bắt đầu bằng httpđể chỉ ra rằng trang được phân phối mà không có giao thức bảo mật.Khi các URL bảo mật được bật cho cả cửa hàng và Quản trị viên, hai trường bổ sung sẽ xuất hiện để bật và định cấu hình HSTS.
		+ Offloader header: ???
	+ Defaul Page: 
		+ Default Web URL : Cho biết trang đích được liên kết với URL cơ sở. Điều này được đặt theo mặc định thành “cms” để chỉ ra một trang từ hệ thống quản lý nội dung của Magento. Bạn cũng có thể sử dụng một loại trang đích khác, chẳng hạn như blog. Ví dụ: nếu một blog được cài đặt trên máy chủ tại magento / blog, bạn có thể nhập tên của thư mục “blog” làm đường dẫn liên quan đến việc lựa chọn các trang. ???
		+ CMS Home Page : Để chọn trang chủ cho cửa hàng, chỉ cần chọn trang CMS từ danh sách. Theo mặc định, Trang chủ CMS liệt kê toàn bộ lựa chọn các trang CMS có sẵn cho cửa hàng của bạn.??
		+ Default No-Route URL:Chứa URL của trang mặc định mà bạn muốn xuất hiện khi 404 Page not Foundxảy ra lỗi. Giá trị mặc định là cms/noroute/index.
		+ CMS No Route Page : Xác định một trang CMS cụ thể mà bạn muốn xuất hiện khi xảy ra lỗi 404 Page Not Found. Trang mặc định là 404 Không tìm thấy.
		+ CMS No Cookie Page :Xác định một trang CMS cụ thể xuất hiện khi cookie không được bật cho trình duyệt. Trang này giải thích lý do tại sao sử dụng cookie và cách bật chúng cho từng trình duyệt. Trang mặc định là Bật Cookie. => Tức là bật thông báo cho phép sử dụng cookie từ phía người dùng áp dụng vào trang nào hoặc có thể không.
		+ Show Breadcrumbs for CMS Pages : Xác định xem đường dẫn breadcrumb có xuất hiện trên tất cả các trang CMS trong danh mục hay không. Tùy chọn: Có / Không. Breadcrumbs chính là các đường dẫn giúp cho người dùng xác định xem vị trí ở trang web ví dụ : Home > Category > Product A.k

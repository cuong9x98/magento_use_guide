# Configuration.
- Đây là nơi người quản trị có thể thiết lập các cài đặt của mình trên trang web. Là lập trình viên bản thân chúng ta chắc chắn phải biết đến tất cả các tab trong này để về sau khách hàng yêu cầu chỉnh sửa nào đó thì chúng ta có thể tìm ra cách nhanh nhất để giải quyết bài toán mà không cần phải customer lại.

## I.GENERAL 
- Đây là những thiết lập chung cho người quản trị có thể làm được.

### 1.General
- Chứa các thiết lập chung nhất bao gồm;
#### a.Country Options : 
- Tùy chọn Quốc gia xác định quốc gia nơi doanh nghiệp của bạn đặt trụ sở và các quốc gia mà từ đó bạn chấp nhận thanh toán.
    + Default Country : Quốc gia mặc định.Khi khách hàng đang ở trang shipping và sẽ được chọn quốc gia thì mặc định thẻ select đã chọn sẽ quốc gia mà bạn chọn mặc định.
    + Alllow Countries : Các quốc giá khác bạn chấp nhận đơn đặt hàng.->Khi khách hàng ở trang Shiping thì sẽ được chọn các đất nước do bạn quy định ở trường.
    + Zip/Postal Code is Optional for	:  nơi bạn tiến hành hoạt động kinh doanh không yêu cầu bao gồm mã ZIP hoặc mã bưu chính như một phần của địa chỉ đường phố.->Những nước mà bạn chọn thì khi khách hàng chọn những nước đó thì tự dộng mục Zip code của khách hàng không bặt buộc phải điền.
    + European Union Countries : quốc gia trong Liên minh Châu Âu nơi bạn tiến hành hoạt động kinh doanh.Bởi vì các quốc gia EU này có các quy tắc thuế khác nhau, tức là VAT. ???
    + Top destinations	: Các quốc gia chính mà bạn nhắm mục tiêu để bán hàng.Cho phép các quốc gia bạn cho sẽ được đưa lên đầu các quốc gia mà khách hàng chọn.
#### b.State Options :
- Lựa chọn trạng thái.
    + State is Required for : Các quốc gia mà quốc gia đó có các thành phố lớn tiểu bang.
    + Allow to Choose State if It is Optional for Country : Bật tắt hiện thêm trường thành phố tiểu bang trong trang shipping khi mà khách hàng chọn vào đất nước mà ta chọn ở mục State is Required for.Chú ý để hiện ra thì phải chọn No.
#### c.Locale Options :
- Chọn ngôn ngữ , múi giờ.
    + Timezone : Múi giờ -> Các bạn có thể xem thời gian các đơn hàng sẽ bị thay đổi khi ta chỉnh sửa lại múi giờ.
    + Locale : Ngôn ngữ -> Chưa rõ nhưng các bạn có thể xem việc đổi ngôn ngữ lúc chọn quốc gia ở trang shipping.
    + Weught Unit: Đơn vị trọng lượng-> Có thể xem khi tạo 1 sản phẩm đơn giản.
    + First Day of Week : Ngày đầu tuần. => Quy định ngày cuối tuần của hệ thống. 
    + Weedkend Days : Ngày cuối tuần. => Quy định ngày cuối tuần của hệ thống.
#### d.Store Information :
- Thông tin của cửa hàng. Các bạn có thể lấy thông tin  cửa hàng bằng cacsh làm theo đường dẫn: https://www.mageplaza.com/devdocs/how-get-store-information-magento-2.html. Các bạn có thể xem thông tin các bạn lưu lại ở đây bằng cách xem bản mẫu thư điện tử của magento Marketing->Email Templates-> Tại mục Template chọn bất kì bản mẫu nào sao đó bạn chạy lên và click vào  Preview Templates để xem trc lúc đó các bạn có thể xem thấy thông tin của store bạn vừa config.
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
#### e.Single-Store Mode:
- Chế độ 1 của hàng 
    + Enable Single- Store Mode : nếu bạn là chủ cửa hàng magento 2 có chế độ xem một cửa hàng và muốn loại bỏ chỉ báo phạm vi cho từng cấu hình, bạn có thể bật chế độ cửa hàng duy nhất, tức là chỉ chơi 1 store view. Cài đặt này sẽ không có hiệu quả nếu cửa hàng có sẵn nhiều cửa hàng. 

### 2.Web
#### a.Url Option : 
    + Add Store to Urls:  Trong trường hợp bạn có một cửa hàng đa ngôn ngữ và muốn thêm  Mã cửa hàng vào URL để làm cho chúng trông giống như yourdomain.com/en, yourdomain.com/fr, yourdomain.com/au, hãy làm theo các bước tiếp theo .
    + Auto-redirect to Base URL: Đây cho phép chuyển đến trang cơ sở nếu có 1 link bị hỏng?.Các bạn có thể vào Trong Marketing ->RewriteURL->Add URL Rewrite.Tại mục  Request Path bạn sẽ điền đường dẫn mới,và Target Path là đường dẫn cũ nếu đường dẫn cũ bị hỏng thì sẽ được thay bằng đường dẫn mới khi đó bạn vẫn có thể truy cập vào dường dẫn cũ thông qua đường dẫn mới.Cuối cùng các bạn chọn Redirect Type :301 rồi lưu lại.
#### b.Search Engine Optimization : 
    + Use Web Server Rewiriter : Mở chế độ viết lại URL chính là phầm mình nói ở trên.https://meetanshi.com/blog/magento-2-url-rewrite/#:~:text=See%20Magento%202%20URL%20Rewrite,Magento%202%20URL%20Rewrites%20table.
#### c.Base URLs : 
    + Base URL : Địa chỉ trang web cơ sở.(Làm multi website)
    + Base Link URL : Trình giữ chỗ chỗ cho URL cơ sở.(Làm multi website)
    + Base URL for Static View Files : Chỉ định vị trí thay thế cho URL cơ sở cho tệp chế độ xem tĩnh
    + Base URL for User Media Files: Chỉnh lại URL các file ảnh
#### d.Base URLs(Secure) :
    + Secure Base URL: Địa chỉ gốc website nhưng được bảo mật bằng cách mã hóa SSL/TLS. URL phải kết túc bằng gạch chéo.(Làm multi website)
    + Secure Base Link URL: Được sử dụng làm trình giữ chỗ cho URL cơ sở chạy qua kênh bảo mật. (Làm multi website)
    + Secure Base URL for Static View Files : tương tự
    + Secure Base URL for Media Files : tương tự
    + Use Secure URLs on Storefront:Nếu miền của bạn có chứng chỉ bảo mật, bạn có thể chọn chạy mặt tiền cửa hàng, có hoặc không có mã hóa SSL. Tùy chọn:Có - URL lưu trữ bắt đầu bằng httpsđể cho biết rằng trang được phân phối bằng giao thức được mã hóa và bảo mật.Không - URL cửa hàng bắt đầu bằng httpđể chỉ ra rằng trang được phân phối mà không có giao thức bảo mật.
    + Use Secure URLs in Admin : Nếu miền của bạn có chứng chỉ bảo mật, bạn có thể chọn chạy Quản trị viên cửa hàng, có hoặc không có mã hóa SSL. Tùy chọn:Có - URL quản trị bắt đầu bằng httpsđể chỉ ra rằng trang được phân phối bằng giao thức được mã hóa và bảo mật.Không - URL quản trị bắt đầu bằng httpđể chỉ ra rằng trang được phân phối mà không có giao thức bảo mật.Khi các URL bảo mật được bật cho cả cửa hàng và Quản trị viên, hai trường bổ sung sẽ xuất hiện để bật và định cấu hình HSTS.
    + Offloader header:  Để làm cho Magento TLS nhận biết được , một tiêu đề cụ thể có thể được gửi, chứa giao thức đã được ứng dụng khách sử dụng để kết nối.X-Forwarded-Prototiêu đề được sử dụng cho việc đó. Nó chứa httphoặc https. Magento sử dụng giá trị này để sử dụng lược đồ URL thích hợp trong các liên kết mà nó xây dựng
#### e.Defaul Page: 
    + Default Web URL : Cho biết trang đích được liên kết với URL cơ sở. Điều này được đặt theo mặc định thành “cms” để chỉ ra một trang từ hệ thống quản lý nội dung của Magento. Bạn cũng có thể sử dụng một loại trang đích khác, chẳng hạn như blog. Ví dụ: nếu một blog được cài đặt trên máy chủ tại magento / blog, bạn có thể nhập tên của thư mục “blog” làm đường dẫn liên quan đến việc lựa chọn các trang. ?? Khá khó hiểu bạn nào hiểu thì giải thích cho mình.
    + CMS Home Page : Thiết lập trang home page là trang do mình chọn. các bạn có thể thử thay đỗi rồi xem tragn home page ntn.
    + Default No-Route URL:Chứa URL của trang mặc định mà bạn muốn xuất hiện khi 404 Page not Foundxảy ra lỗi. Giá trị mặc định là cms/noroute/index.Các bạn có thể xem trong project magento module-cms file config.xml
    + CMS No Route Page : Nếu không tìm thấy trang thì sẽ xuất hiện trang này. Mặc định ở đây là 404.
    + CMS No Cookie Page :Xác định một trang CMS cụ thể xuất hiện khi cookie không được bật cho trình duyệt. Trang này giải thích lý do tại sao sử dụng cookie và cách bật chúng cho từng trình duyệt. Trang mặc định là Bật Cookie. => Tức là bật thông báo cho phép sử dụng cookie từ phía người dùng áp dụng vào trang nào hoặc có thể không.
    + Show Breadcrumbs for CMS Pages : Xác định xem đường dẫn breadcrumb có xuất hiện trên tất cả các trang CMS trong danh mục hay không. Tùy chọn: Có / Không. Breadcrumbs chính là các đường dẫn giúp cho người dùng xác định xem vị trí ở trang web ví dụ : Home > Category > Product A.k
#### f.Default Layouts
    + Default Product Layout :??
    + Default Category Layout :??
    + Default Page Layout:??
#### g.Default Cookie Settings
    + Cookie Lifetime : Thời gian sống của cookie.=>Nếu khách hàng mà đóng tab đi mà không quay lại trong thời gian cookie quy định thì dữ liệu khách hàng sẽ mất ví dụ là các sản phẩm trong giỏ hàng.
    + Cookie Path : Đường dẫn cookie
    + Cookie Domain :
    + Use HTTP Only : Chế độ chỉ dùng HTTP
    + Cookie Restriction Mode : Chế độ hạn chế cookie.
#### h.Session Validation Setting
- Phiên làm việc của cửa hàng
    + Validate REMOTE_ADDR :xác minh rằng địa chỉ IP của một yêu cầu khớp với những gì được lưu trữ trong biến $_SESSION.
    + Validate HTTP_VIA	: xác minh rằng địa chỉ proxy của một yêu cầu đến khớp với những gì được lưu trữ trong biến $_SESSION.
    + Validate HTTP_X_FORWARDED_FOR	: ác minh rằng địa chỉ được chuyển tiếp cho một yêu cầu khớp với những gì được lưu trữ trong biến $_SESSION.
    + Validate HTTP_USER_AGENT :xác minh rằng trình duyệt hoặc thiết bị được sử dụng để truy cập cửa hàng trong một phiên khớp với những gì được lưu trữ trong biến $_SESSION.
    => Có sử dụng các xác thực này không. 
#### i.Browser CApabilities Detection
    + Redirect to CMS-page if Cookies are Disabled	: Chuyển hướng đến trang CMS nếu Cookie bị Tắt
    + Show Notice if JavaScript is Disabled	: Hiển thị Thông báo nếu JavaScript bị Tắt	
    + Show Notice if Local Storage is Disabled: Hiển thị Thông báo nếu Bộ nhớ Cục bộ bị Tắt
### 3.Curency Setup.
#### a.Curency Options.
    + Base Curency : Đơn vị tiền cơ sỏ.Phạm vị toàn cửa hàng. Các bạn có thể xem lúc tạo sản phẩm ở mục giá sản phẩm thì đơn vị tiền tệ phụ thuộc vào trường này.
    + Default Display Currency : Hiện thị đơn vị ở store view.Chú ý bạn  phải chọn các đơn vị tiền cho phép trc r mới chọn tiền tệ hiện thị mặc định.??
    + Allowed Currencies :Các đơn vị tiền tệ được phép hiện thị ở store view.
#### b.Fix.io
    + API Key :Khóa được sử dụng để truy cập dịch vụ chuyển đổi thông qua tài khoản fixer.io của bạn
    + Connection Timeout in Seconds : thời gian kết nối phiên (đơn vị giây)
#### c.Currency Converter API
    + API Key :Khóa được sử dụng để truy cập dịch vụ chuyển đổi thông qua tài khoản fixer.io của bạn
    + Connection Timeout in Seconds : thời gian kết nối phiên (đơn vị giây)
#### d.Scheduled Import Settings
    + Enabled : Bật chế độ sắp xếp lịch tỷ giá tiền tệ.
    + Service : Chỉ định dịch vụ cung cấp dữ liệu cho quá trình nhập đã lên lịch Fixer.io hay API
    + Start Time : Thời gian bắt đầu.
    +Frequency: Tần suất cập nhật theo ngày hay tháng, năm.
    + Error Email Recipient	:Xác định địa chỉ email của từng người được thông báo qua email trong trường hợp có lỗi. Đối với nhiều người nhận, hãy phân tách từng mục nhập bằng dấu phẩy.
    + Error Email Sender :Xác định địa chỉ liên hệ cửa hàng xuất hiện với tư cách là người gửi email thông báo lỗi. Người gửi mặc định là Liên hệ chung.
    + Error Email Template :Chỉ định mẫu được sử dụng làm cơ sở của email thông báo lỗi. Mẫu mặc định là Cảnh báo cập nhật tiền tệ.
### 4.Store Email Addreses
#### a.General Contact
    + Sender Name:Tên người gửi
    + Sender Email:Email
#### b.Sales Representative
    + Sender Name:Tên người gửi
    + Sender Email:Email
#### c.Customer Support
    + Sender Name:Tên người gửi
    + Sender Email:Email
#### d.Custom Email 1
    + Sender Name:Tên người gửi
    + Sender Email:Email
#### e.Custom Email 2
    + Sender Name:Tên người gửi
    + Sender Email:Email
=> Các mục trên sẽ là bổ sung của Sale->Sale Email->Order ->New Order Confirmation Email Sender	. Tại đây chúng ta có thể lựa chọn các mục mà chúng ta đã ghi trước đó.Vậy ở mục này tương tác ntn thì bạn hãy xem ở mục Sale->Order->Chọn 1 đơn hàng xem phần view -> Xem đến phần Account Information sẽ thấy địa chỉ email và tên các bạn đã chọn. Các mục trên chỉ là khai báo các địa chỉ email để sẵn dùng thôi.
### 5.Contacs
#### a.Contac Us 
    + Đây là phẩn đóng mở trang contact ở frontend 
#### b.Email Options  
    + ???
### 6.Report
#### a.Dashboard : 
    + Year-To-Date Starts: Chỉ định tháng và ngày dựa vào đó các tính toán hàng năm.
    + Current Month Starts: Chỉ định ngày trong tháng được sử dụng trong tính toán để đánh dấu đầu tháng hiện tại.
#### b.General Options
    + Enable Reports	: bật tắt các loại báo cáo
    + Enable "Product View" Report	: bật tắt các loại báo cáo
    + Enable "Send Product Link To Friend" Report	: bật tắt các loại báo cáo
    + Enable "Add Product To Compare List" Report	: bật tắt các loại báo cáo
    + Enable "Product Added To Cart" Report	: bật tắt các loại báo cáo
    + Enable "Product Added To WishList" Report	: bật tắt các loại báo cáo
    + Enable "Share WishList" Repor: bật tắt các loại báo cáo
### 7.Conent Management
#### a.WYSIWYG Options
    - Trình chỉnh sửa WYSIWYG (What You See Is What You Get) được sử dụng để chỉnh sửa nội dung và xác định chính xác thứ hiển thị trong phần phụ trợ, sẽ hiển thị giống nhau trong giao diện người dùng. Nó loại bỏ sự cần thiết phải thiết kế trang và thêm văn bản thông qua mã HTML vốn trở nên phức tạp. Thay vào đó, bạn chỉ cần thêm những thứ và xem trước kết quả rằng nó sẽ được hiển thị như thế nào sau bản phát hành cuối cùng.
    => Nói thế này cho nó vuông là cái WYSIWYG chính là cái edit khi các bạn chỉnh sửa phần content của 1 page nào đó. Nếu bạn tắt WYSIWYG thì phần editor đó 'phèn' lắm .
    + Enable WYSIWYG Editor	:Bật chỉnh sửa WYSIWYG
    + WYSIWYG Editor	: Chọn trình chỉnh sửa
    + Use Static URLs for Media Content in WYSIWYG: Sử dụng URL tĩnh cho nội dung phương tiện trong WYSIWYG
### 8.New Relic Reporting ??
    - Các dự án Magento Commerce Cloud bao gồm quyền truy cập vào các dịch vụ New Relic sau đây để giúp quản lý, giám sát và khắc phục sự cố các ứng dụng và cơ sở hạ tầng của bạn bằng cách thu thập, xem và phân tích dữ liệu từ dự án Magento Commerce Cloud của bạn.
    + Tập trung vào các giao dịch cụ thể 
    + Giám sát truy vấn cơ sở dữ liệu
    + Bản đồ ứng dụng
    + Điểm Apdex 
#### a.General
    + Enable New Relic Integration	: bật relic
    + New Relic API URL	: 
    + Insights API URL	: 
    + New Relic Account ID	: id relic 
    + New Relic Application ID	:
    + New Relic API Key	:
    + Insights API Key	:
    + New Relic Application Name	:
    + Send Adminhtml and Frontend as Separate Apps:
#### b.Cron

### 9.Advanced Reporting
    - Báo cáo nâng cao
    => khi cái này được bật thì  trong Phần Report-> Advanced Reporting sẽ được bật, bạn click vào sẽ chuyển đến trang sẽ hiện thì ra các biểu đồ ...
## II.Catalog 
### 1.Catalog 
#### a.Product Fields Auto-Generation
    + Mask for SKU :
    + Mask for Mate Title :
    + Mask for Meta Keywork :
    + Mask for Meta Description : 
#### b.Storefront
    + List Mode	: Chọn dạng hiện thị là lưới hay danh sách ngay từ ban đầu
    + Products per Page on Grid Allowed Values	: Sản phẩm trên mỗi trang trong danh sách Giá trị được phép
    + Products per Page on Grid Default Value	:Sản phẩm trên mỗi trang trên danh sách Giá trị mặc định => mặc định hiện thị bao nhiêu sản phẩm
    + Products per Page on List Allowed Values	: ở frontend có cái khối Show 12 per page ấy nó là 1 select gồm các giá trị mình điền vào.
    + Products per Page on List Default Value	:
    + Product Listing Sort by	: Sắp xếp theo tiêu chí nào: tên, giá,..
    + Allow All Products per Page	:Cho phép tất cả các sản phẩm trên mỗi trang.
    + Remember Category Pagination	:Ghi nhớ phân trang danh mục
    + Use system value	:
    + Use Flat Catalog Category	:Bật chế độ dùng dữ liệu phẳng ko dùng eav nữa để có thể truy vấn nhanh hơn.
    + Use Flat Catalog Product	:Bật chế độ dùng dữ liệu phẳng ko dùng eav nữa để có thể truy vấn nhanh hơn.
    + Swatches per Product	: Các mẫu cho mỗi sản phẩm (mẫu ở đây chính là các thuộc tính sản phẩm ví dụ 1 sản phẩm áo có 10 size đi nhưng mình chỉ cho 5 size được phép hiển thị ở trang danh sách thôi thì mình điền 5. Nó cũng sẽ tương tự với màu)
    + Show Swatches in Product List	: Cho phép hiển thị các mẫu hay không
    + Show Swatch Tooltip: Hiển thị chú giải khi người dùng trỏ chuột đến các mẫu.
#### c.Product View
    + Enabled : Bật đánh giá sản phẩm
    + Allow Guests to Write Reviews : Cho phép khách hàng không login vẫn được đánh giá.
#### d.Product Alerts
    + Allow Alert When Product Price Changes : Thông báo khi giá sản phẩm thay đổi.
    + Price Alert Email Template : Chọn mẫu email
    + Allow Alert When Product Comes Back in Stock : thông báo khi sản phẩm quay lại (từ hết hàng thành có hàng)
    + Stock Alert Email Template : Chọn mẫu email
    + Alert Email Sender : Chọn người gửi
#### e.Product Alerts Run Settings
    - Sẽ hiển thị thêm trường product alert trong thêm sản phẩm.
    + Frequency	: Tần suất 
    + Start Time	: Thời gian bắt đầu 
    + Error Email Recipient	:  Người sẽ nhận email lỗi  
    + Error Email Sender	: Lỗi sẽ được gửi đến email nào
    + Error Email Template: Mẫu email báo lỗi.
#### f.Product Image Placeholders
    - Khi tạo sản phẩm mà người tạo ko cho ảnh vào thì đây là thứ mặc định chèn vào ảnh thay vì cái hình phèn logo magento
    + Base
    + Small
    + Swatch
    +Thumbnail
#### g.Recently Viewed/Compared Products
    + Synchronize widget products with backend storage	 : Cho phép mở tiện ích hiển thị sản phẩm xem và so sánh gần đây
    + Show for Current	 : Hiển thị ở đâu
    + Default Recently Viewed Products Count	 : Số lượng sản phẩm xem gần đây
    + Default Recently Compared Products Count	 : Số lượng sản phẩm so sánh
    + Lifetime of products in Recently Viewed Widget	 : Thời gian tồn tại sản phẩm xem gần đây
    + Lifetime of products in Recently Compared Widget : Thời gian tồn tại sản phẩm so sánh gần đây.
#### h.Product Video
    + YouTube API Key : Key api youtube	(https://www.youtube.com/watch?v=QsbUy9gToIM) -> làm theo hướng dẫn sẽ hiểu.
    + Autostart base video	: Video cơ sở tự động khởi động	
    + Show related video: Hiển thị video liên quan	
    + Auto restart video :Tự động khởi động lại video
#### i.Price
    + Phạm vi giá của tiền tệ cở sở.
#### j.Layered Navigation
    + Display Product Count	: Bật tắt hiện thị số lượng sản phẩm ở danh mục sản phẩm ở bên trái khi khách hàng vào trang danh mục sản phẩm.
    + Price Navigation Step Calculation : Điều  chỉnh các sản phẩm theo giá.
#### k.Catalog Search
    + Minimal Query Length	: chuỗi tìm kiếm ngắn nhất được phép
    + Maximum Query Length	: chuỗi tìm kiếm dài nhất được phép
    + Number of top search results to cache	: số lượng kết quả vào bộ nhớ cache
    + Search Engine	: Hệ thống tìm kiếm
    + Autocomplete Limit	:
    + Enable Search Recommendations	:Bật đề xuất tìm kiếm
    + Enable Search Suggestions	:Xác định xem các gợi ý tìm kiếm có xuất hiện các lỗi chính tả phổ biến hay không
    + Search Suggestions Count	:Hiển thị kết quả tìm kiếm tốí đa là số mình nhập vào, còn cái kia là kết quả tìm kiếm bỏ vào cache
    + Show Results Count for Each Suggestion: Hiện thì kết quả cho mỗi đề xuất.
#### m.Search Engine Optimization
    + Popular Search Terms	: Bật tắt cụm từ phổ biến -> hiển thị gợi ý trong thanh tìm kiếm  khi khách hàng tìm kiếm mà chỉ gõ có 1 hai từ thôi là ra gợi ý r .
    + Product URL Suffix	:nối đuôi url thêm .html
    + Category URL Suffix	:nối đuôi url thêm .html
    + Use Categories Path for Product URLs	:
    + Create Permanent Redirect for URLs if URL Key Changed	:
    + Generate "category/product" URL Rewrites	:
    + Page Title Separator	:
    + Use Canonical Link Meta Tag For Categories:Hiển thị đường dẫn gốc 
    + Use Canonical Link Meta Tag For Product: Hiển thị đường dẫn gốc
#### n.Category Top Navigation
    + Điều chỉnh độ sâu của menu với từng cấp độ khác nhau : https://docs.magento.com/user-guide/catalog/navigation-top.html
#### p.Downloadable Product Options
    + Order Item Status to Enable Downloads	: Xác định trạng thái sản phẩm cho phép tải xuống 
    + Default Maximum Number of Downloads	: Số lượt tải xuống tối đa mặc định.
    + Shareable	: Có cho phép khách hàng chia sẻ không
    + Default Sample Title	: Tiêu đề mẫu mặc định.
    + Default Link Title	: Tiêu đề liên kết mặc định.
    + Open Links in New Window	: Mở liên kết trong cửa sổ mới
    + Use Content-Disposition	: Sử dụng Nội dung-Bố trí	
    + Disable Guest Checkout if Cart Contains Downloadable Items:Tắt tính năng Thanh toán của Khách nếu Giỏ hàng Có Các mặt hàng Có thể Tải xuống
#### q.Date & Time Custom Options
    - Cho phép khách hàng chọn thời gian ship .Ok .
    + Use JavaScript Calendar : Dùng lịch của js
    + Date Fields Order	: Thứ tự trường ngày
    + Time Format	:Định dạng thời gian	
    + Year Range: Phạm vi năm
### 2.Inventory
#### a.Stock Options
    + Decrease Stock When Order is Placed : Nếu có thì sẽ giảm số lượng trong kho khi có đơn hàng được đặt
    + Set Items' Status to be In Stock When Order is Cancelled	:nếu có trả lại hàng về kho khi đơn hàng bị hủy
    + Display Out of Stock Products	:nếu có thì hiển thị sản phẩm hết hàng và thông báo nếu hàng quay lại.  
    + Only X left Threshold	:nếu có sẽ xuất hiện thông báo sản phẩm còn dưới x sản phẩm
    + Display Products Availability in Stock on Storefront	:Hỉên thị sản phẩm còn hàng hay hết hàng trên trang sản phẩm-> cái này với cái Display Out of Stock Products sẽ hiển thị ra chữ IN STOCK hay không.
    + Synchronize with Catalog: Đồng bộ hóa dữ liệu hàng tồn kho theo thay đổi danh mục.
#### b.Product Stock Options
    + Manage Stock	: 
    + Backorders	: Có 3 trạng thái :
        + No Backorders : Không chấp nhận đơn hàng tồn đọng khi sản phẩm hết hàng.
        + Allow Qty Below 0 : Để chấp nhận đơn đặt hàng tồn đọng khi số lượng giảm xuống dưới 0.
        + Allow Qty Below 0 and Notify Customer :Chấp nhận đơn đặt hàng tồn đọng khi số lượng giảm xuống dưới 0 và thông báo cho khách hàng rằng đơn hàng vẫn có thể được đặt.
    + Maximum Qty Allowed in Shopping Cart	:Số lượng tối đa trong giỏ hàng
    + Out-of-Stock Threshold	: Ngưỡng được cho là hết hàng
    + Minimum Qty Allowed in Shopping Cart	: Sô lượng tối thiểu trong giỏ hàng
    + Notify for Quantity Below	: Thông báo số lượng dưới
    + Enable Qty Increments	: Bật số lượng tăng Ví dụ: một mặt hàng được bán với số lượng 6 có thể được mua với số lượng 6, 12, 18, v.v.
    + Automatically Return Credit Memo Item to Stock: Tự động trả lại hàng khi báo ghi vào kho.
#### c.Admin bulk operations
    + Run asynchronously : ??
#### d.Distance Provider for Distance Based SSA
    - Tính toán khoảng cách bằng Google map hay mã bưu điện.
#### e.Google Distance Provider
    - nhập mã API để được sử dụng Google map
### 3.XML Sitemap  ?
#### a.Categories Options 
#### b.Product Options  
#### c.CMS Pages Options
#### d.Genneration Setting 
#### e.Sitemap File Limits 
#### f.Search Engine Submission Setinbg

### 4.RSS Feeds.
#### a.Rss Config
    + RSS (Thực sự Đơn giản Phân phối) là một định dạng dữ liệu dựa trên XML được sử dụng để phân phối thông tin trực tuyến. Khách hàng của bạn có thể đăng ký nguồn cấp dữ liệu RSS của bạn để tìm hiểu về các sản phẩm và chương trình khuyến mãi mới. RSS Feeds cũng có thể được sử dụng để xuất bản thông tin sản phẩm của bạn lên các trang web tổng hợp mua sắm và có thể được đưa vào các bản tin.
#### b.Wish List 
    + Khách hàng thường ngại mua sản phẩm của bạn và mất nhiều thời gian cân nhắc trước khi đặt hàng. Vì vậy, để thuận tiện hơn trong việc mua hàng trong lần tiếp theo, sẽ rất hữu ích nếu bạn tạo danh sách mong muốn trong đó khách hàng đã đăng ký có thể lưu tất cả các mặt hàng mong muốn và họ có thể thêm vào giỏ hàng bất kỳ lúc nào. Danh sách mong muốn được quản lý tốt trên trang tổng quan của tài khoản khách hàng.
#### c.Catalog
#### d.Order
    + Cho phép khách biết trạng thái đơn hàng.Trong mục myOrder.
### 5.Email to a Friend
#### a.Email Templates
    + Enabled	:  Có bật chức năng này hay không.
    + Select Email Template	: Mẫu email áp dụng cho chức năng này
    + Max Recipients	: Người nhận tối đa
    + Max Products Sent in 1 Hour	: số  sản phẩm tôi đa cho bạn bè
    + Limit Sending By: Giới hạn gửi địa chỉ ip hay cookie.
### .Security
#### 1.2FA
##### a.General
    + Enable Two Factor Auth : Bật xác thực 2 yếu tố
    + Force providers : Chọn nhà cung cấp xác thực 2 yếu tố.
##### b.Google Authenticator
    + Enable this provider	: Cho phép chế độ hoạt động
    + Enable "trust this device" option	: Chọn Google Authenticator là chế độ đáng tin cậy.
##### c.U2F Devices (Yubikey and others)
    + Enable this provider	: Cho phép chế độ hoạt động
    + Enable "trust this device" option	: Chọn U2F Devices là chế độ đáng tin cậy.
    => Các phần dưới là các chế độ khác.
#### 2.Google reCapcha
##### a.General
    + Google API website key: Điền mã API 
    + Google API secret key : Khóa API
    + reCaptcha type : Loại captcha
##### b.Backend
    + Hiện thị captcha bên trang quản trị
##### c.Frontend
    + Captcha bên frontend.
    + Enable	: Bật tắt chế độ
    + Invisible badge position	: vị trí captcha
    + Minimum score	: thời gian tối thiểu
    + Language Code	: ngôn ngữ
    + Use in login	: dùng cho login
    + Use in Forgot password	: dùng cho forgot password
    + Use in Contact	: Dùng cho Contact
    + Use in Create user	: Dùng cho create User
    + Use in Review	: Dùng cho Review
    + Use in PayPal PayflowPro payment form	: Dùng cho thanh toán
    + Use invisible ReCaptcha in newsletter	: Dùng bản tin 
    + Use in Send To Friend: Dùng cho gửi bạn bè.
## IV.Customer
### 1.Newsletter
#### a.Genneral Options
    + Enabled :  Bật tắt chế độ.
#### b.Subscription Options
    + Allow Guest Subscription	: Cho phép khách hàng đăng ký
    + Need to Confirm	: Cần xác nhận
    + Confirmation Email Sender	:  Email người gửi xác nhận
    + Confirmation Email Template	: mẫu email xác nhận
    + Success Email Sender	:  Người gửi email thành công 
    + Success Email Template	: Email người nhận thành công
    + Unsubscription Email Sender	: Người gửi email hủy đăng ký
    + Unsubscription Email Template: Mẫu email hủy đăng ký
### 2.Customer Configuration 
#### a.Account Sharing Options
    + Share Customer Accounts : Cho phép chia sẻ tài khoản.
    => Các tài khoản của khách hàng chỉ có trong phạm vi 1 trang web cụ thể nhưng magento có thể chia sang các web khách trong cùng của hàng.
#### b.Online Customers Options
    + Online Minutes Interval: Phiên hoạt động của khách hàng mặc định là 15p. Nếu khách hàng không hoạt động gì trong 15p thì sẽ tự động logout ra và khách phải đăng nhập lại các thông tin giở hàng chưa được lưu sẽ mất.
    + Customer Data Lifetime : Thời gian tồn tại dữ liệu khách hàng.=>nếu khách hàng không đóng tab mà không đăng nhập và không tương tác gì với web thì dữ liệu sẽ bị mất ví dụ các sản phẩm trong giỏ hàng
#### c.Create New Account Options
    + Enable Automatic Assignment to Customer Group	: Bật chỉ định tự động cho nhóm khách hàng.
    + Default Group : Nhóm mặc định
    + Default Value for Disable Automatic Group Changes Based on VAT ID	:Giá trị mặc định để vô hiệu hóa các thay đổi nhóm tự động dựa trên ID VAT
    + Show VAT Number on Storefront	:Hiển thị số VAT trên Mặt tiền cửa hàng
    + Default Email Domain	: Tên miền Email Mặc định
    + Default Welcome Email	:Email chào mừng mặc định=> Chào mừng đến với của hàng
    + Default Welcome Email Without Password	:Email chào mừng mặc định không có mật khẩu
    + Email Sender	: Chọn người gửi email.
    + Require Emails Confirmation	: Có yêu cầu xác nhận email không.
    + Confirmation Link Email	: Email liên kết xác nhận
    + Welcome Email	:Là email chào mừng sau email chào mừng mặc định 
    + Generate Human-Friendly Customer ID:Tạo id thân thiện.
#### d.Password Options
    + Password Reset Protection Type	: Chọn kiểu lấy đặt lại mật khẩu
    + Max Number of Password Reset Requests	: Số yêu cầu tối đặt lại mk
    + Min Time Between Password Reset Requests	: Thời gian ngắn nhất giữa 2 lần yêu cầu đặt lại mk
    + Forgot Email Template	: Form quên mk
    + Remind Email Template	: Form nhắc nhở
    + Reset Password Template	: Form đặt lại mk
    + Password Template Email Sender	: Email gửi cho khách đặt lại mk
    + Recovery Link Expiration Period (hours)	:  Thời gian tồn tại của link đặt lại mk
    + Enable Autocomplete on login/forgot password forms	: Bật tắt chế độ điền thông tin form.
    + Number of Required Character Classes	: số kí tự khác nhau trong mk
    + Maximum Login Failures to Lockout Account	: Số lần đăng nhập sai tối đã để khóa mk
    + Minimum Password Length	: Độ dài kí tự nhỏ nhất của mk
    + Lockout Time (minutes): Thời gian khóa mk.
#### e.Account Information Options
    + Change Email Template : Mẫu form chuyển đổi thông tin.
    + Change Email and Password Template : Mẫu form chuyển email và passwork
#### f.Name and Address Options
    + Number of Lines in a Street Address: Số dòng mà thông tin địa chỉ cho phép
    + Show Prefix : Có cho phép đặt tiền tố trc tên không vd: Mr , Mrs, ..
    + Prefix Dropdown Options	: Tiền tố sẽ được chọn dạng Dropdown các giá trị ngăn cách nhau bằng dấu ; vd Mr;Mrs;
    + Show Middle Name (initial): có cho khách hàng nhập tên đệm không.
    + Show Suffix : Có cho phép sự dụng hậu tố không.
    + Suffix Dropdown Options :Hậu tố sẽ được chọn dạng Dropdown các giá trị ngăn cách nhau bằng dấu ; vd Jr;Sr..;
    + Show Date of Birth : Có cho nhập ngày tháng năm sinh 
    + Show Tax/VAT Number : Có cho nhập mã số thuế.
    + Show Gender : Có cho nhập giới tính
    + Show Telephone : Có cho nhập sdt
    + Show Company : Có cho nhập tên công ty
    + Show Fax: Có cho nhập số Fax
    => Cho nhập ở đây là cho khách hàng  nhập thông tin của họ.
#### g.Login Options
    + Redirect Customer to Account Dashboard after Logging in : Chuyển hướng khách hàng đến trang tổng quan tài khoản sau đăng nhập.
#### h.Address Templates
    + Bạn có thể sửa đổi mẫu xác định định dạng của địa chỉ thanh toán và giao hàng của khách hàng xuất hiện trên hóa đơn đã in, lô hàng và tiền hoàn lại, cũng như trong sổ địa chỉ của tài khoản khách hàng.
#### i.CAPTCHA
    + Custome Captcha
    + Enable CAPTCHA on Storefront : bật captcha
    + Font : dùng font gì
    + Forms : Sửa dụng mẫu nào 
    + Displaying Mode : Hiện thị khi nào vd sau khi đăng nhập nhiều lần
    + Number of Unsuccessful Attempts to Login : Số lần đăng nhập thất bại cho phép hiện thị captcha
    + CAPTCHA Timeout (minutes): thời gian tồn tại captcha
    + Number of Symbols	:Số lượng kí captcha
    + Symbols Used in CAPTCHA	: Các kí hiệu được dùng trong captcha
    + Case Sensitive : trường hợp nhạy cảm.

### 3.Wish List
#### a.Genral Options
    + Enalble : Bật hay tắt
    + Show in Sidebar : Hiện thị trong thanh bên
#### b.Share Options
    + Email Sender : Người gửi
    + Email Templates : Mẫu email
    + Max Emails Allowed to be Sent :Số email gửi tối đa
    + Email Text Lenght Limit : Giới hạn độ dài
#### c.My Wish List
    + Display Wish List Summary : Hiện thị số mặt hàng mong muốn.
### 4.Promotions
#### a.Auto Generated Specific Coupon Codes
    + Code Length	: Độ dài mã phiếu giảm giá
    + Code Format	: Định dạng mã : Chữ hay số hay cả hai
    + Code Prefix	: Tiền tố trước
    + Code Suffix	: Tiền tố sau
    + Dash Every X Characters: Dấu gạch ngang dưới mọi chữ X
### 5.Persistent Shopping Cart
#### a.General Options
    + Bật tắt giở hàng liên tục
## V.Sales
### 1.Sales
#### a.General 
    + Hide Customer IP	: Có nên hiển thị IP của khách hàng không trong đơn hàng lô hàng hay thư báo.
#### b.Checkout Totals Sort Order 
    + Subtotal : Tổng
    + Discount : Giảm giá
    + Shipping : Chuyển hàng
    + Tax :Thuế
    + Fixed Product Tax	: Thuế sản phẩm cố định
    + Grand Total	: Tổng cộng
    => Sắp xếp các trường theo thứ tự
#### c.Reorder
    + Cho phép sắp xếp lại.
#### d.Allow Zero GrandTotal
    + Cho phép Zero GrandTotal cho Creditmemo	
#### e.Invoice and Packing Slip Design
    + Thiết kế phiếu đóng gói
#### f.Minimum Order Amount
    + Enable : Bật tắt chế độ số tiền hàng tối thiểu
    + Minimum Amount : số tiền tối thiểu
    + Include Discount Amount	: Có bao gồm số tiền chiết khấu không
    + Include Tax to Amount	: Có bao gồm tiền thuế không
    + Description Message	: Thông báo mô tả
    + Error to Show in Shopping Cart : lỗi hiển thị trong giỏ hàng
    + Validate Each Address Separately in Multi-address Checkout : Có xác thực từng địa chỉ trong thanh toán nhiều địa chỉ
    + Multi-address Description Message	: Thông báo mô tả đa địa chỉ
    + Multi-address Error to Show in Shopping Cart	: Lỗi nhiều địa chỉ hiển thị trên giỏ hàng.
#### g.Dashboard
    + Use Aggregated Data	: Có sử dụng dữ liệu tổng hợp không
#### h.Orders Cron Settings
    + Pending Payment Order Lifetime : Thời gian sống hóa đơn thanh toán chờ xử lí
#### i.Gift Options 
    + Allow Gift Messages on Order Level : Cho phép có tin nhắn quà tặng đơn hàng
    + Allow Gift Messages for Order Items : Cho phép tin nhắn quà tặng cho các mặt hàng đặt hàng.
#### j.Minimum Advertised Price
    + Enable MAP	: Bật MAP
    + Display Actual Price	: Hiển thị giá thực tế
    + Default Popup Text Message : Tin nhắn văn bản mặc định
    + Default "What's This" Text Message : Mặc định tin nhắn đây là gì.
#### k.Instant Purchase
    + Enable : Bật tắt chế độ mua ngay lập tức.
    + Button Text : Tạo nút buttton mua ngay
### 2.Sales Emails
    => Ở mục này sẽ là các setup email mặc định chuẩn bị sẵn và các mẫu email của cửa hàng các bạn có thể xem phần thư mục Marketing.
### 3.PDF Print-outs
    => Ở mục này chỉ có cho phép hiển thị id đơn hàng trong bản in pdf
### 4.Tax
#### a.Vertex Settings
    + Sử dụng liên kết với thuế Vertex
#### b.Tax Class
    + Tax Class for Shipping:Hạng thuế vận chuyển
    + Default Tax Class for Product	 : Hạng thuế sản phẩm
    + Default Tax Class for Customer:  Hạng thuế khách hàng
#### c.Calculation Settings
    + Tax Calculation Method Based On : Phương pháp tính thuế
    + Tax Calculation Based On	: Tính thuế dựa trên địa chỉ giao hàng hay địa chỉ thanh toán
    + Catalog Prices	: Giá mục hàng
    + Shipping Prices	: Giá vận chuyển có bao gồm thuế hay không  
    + Apply Customer Tax : Áp dụng thuế khách hàng sau giảm giá hay trc giảm giá
    + Apply Discount On Prices	: Giá chiết khấu có bao gồm thuế không 
    + Apply Tax On	: Áp dụng thuế tùy chỉnh giá
    + Enable Cross Border Trade	: Mở hoạt động thương mại xuyên biên giới
#### d.Default Tax Destination Calculation
    + Default Country : Quốc gia mặc định chọn điểm tính thuế.
    + Default Post Code	: Mã post mặc định
#### e.Price Display Settings
    + Display Product Prices In Catalog : Hiển thị giá sản phẩm trên danh mục có bao gồm thuế không
    + Display Shipping Prices	:Hiển thị giá vận chuyển có bao gồm thuế không
#### f.Shopping Cart Display Settings
    + Display Prices : hiện thị giá có bao gồm thuế không
    + Display Subtotal: Hiển thị tổng tiền có bao gồm thuế không
    + Display Shipping Amount: Hịển thị số tiền vận chuyển có bao gồm thuế không
    + Include Tax In Order Total: có bao gồm tổng số đơn đặt hàng không
    + Display Full Tax Summary : hiển thị đầy đủ tóm tắt thuế
    + Display Zero Tax Subtotal	: hiển thị tổng thuế không
#### g.Orders, Invoices, Credit Memos Display Settings
    + Tương tự như trên
#### h.Fixed Product Taxes
    + tương tự như trên.
### 5.Checkout
#### a.Checkout Options
    + Enable Onepage Checkout : Hiện thị trang checkout . Tắt cái này là coi như không vào được trang thanh toán.
    + Allow Guest Checkout	: Cho phép khách hàng thanh toán
    + Display Billing Address On : Hiển thị địa chỉ thanh toán.
    + Enable Terms and Conditions : Bật Điều khoản và Điều kiện	
    + Maximum Number of Items to Display in Order Summary : Số lượng mặt hàng tối đa để hiển thị trong tóm tắt đơn hàng
#### b.Shopping Cart
    + Quote Lifetime : Xác định giá sản phẩm có hiệu lực trong bao lâu mặc định 30 ngày.
    + After Adding a Product Redirect to Shopping Cart : Khi thêm sản phẩm vào giỏ hàng có chuyển hướng khách đến trang khác không
    + Number of Items to Display Pager	: số sản phẩm hiển thị trên 1 trang 
    + Show Cross-sell Items in the Shopping Cart : Cho phép hiện thị sản phẩm Cross-sell 
    + Grouped Product Image	: Hình sản phẩm được nhóm theo cách nào
    + Configurable Product Image : Hình ảnh sản phẩm có thể định cấu hình như thế nào.
#### c.My Cart Link
    + Display Cart Summary : Hiện thị số lượng mặt hàng trong giỏ hàng
#### d.Mini Cart
    + Display Mini Cart : Hiện thị giỏ hàng nhỏ -> chính là cái xe đẩy nhỏ nhỏ ấy nếu mình tắt nó thì khi click vào cái xe đẩy thì sẽ nhảy thẳng vào trang checkout luôn không phải nghĩ nhiều.
    + Number of Items to Display Scrollbar :Số lượng mục để hiển thị thanh cuộn -> quy định số sản phẩm hiện thị cho phép của cái giỏ hàng mini.
    + Maximum Number of Items to Display :Số lượng mục tối đa để hiển thị	
#### e.Payment Failed Emails.
    + Payment Failed Email Sender : Người gửi email thanh toán thất bại
    + Payment Failed Email Receiver	 : Người nhận email không thanh toán được
    + Payment Failed Template:mẫu thanh toán thất bại
    + Send Payment Failed Email Copy To	: gửi bản sao chép email thanh toán thất bại, 
    + Send Payment Failed Email Copy Method : Gửi Thanh toán Không thành công Phương thức Sao chép Email
### 6.Shipping Setting
#### a.Origin
    + Country : Quốc Gia
    + Region/State : Bang
    + ZIP/Postal Code	: Mã bưu điện
    + City : Thanh phố
    + Street Address: Địa chỉ.
#### b.Shipping Policy Parameters
    + Apply custom Shipping Policy	: Áp dụng chính sách giao hàng tùy chỉnh.
### 7.Multishipping Setting
    + Allow Shipping to Multiple Addresses :Cho phép vận chuyển nhiều địa chỉ
    + Maximum Qty Allowed for Shipping to Multiple Addresses : 	Số sản phẩm tối đa khi vận chuyển nhiều địa chỉ.
### 8.Google Api
    + Kích hoạt sử dụng api google
### 9.Payment Method
    + Chọn cách phương thức thanh toán điện tử : Paypal,Klarna,amazon pay
### 10.3D Secure
    + Bảo mật 3D 
### 11.Fraud Protection
    + Sử dụng chống gian lận của SIGNIFYD
### 12.Address Validation
    + Sử dụng xác thực địa chỉ Vertex.
### 13.Shipping methods
#### a.Flat Rate
    + Tỷ giá cố định là một khoản phí cố định, được xác định trước, có thể được áp dụng cho mỗi mặt hàng hoặc cho mỗi lô hàng. Tỷ giá cố định là một giải pháp vận chuyển đơn giản, đặc biệt là khi được sử dụng với bao bì tỷ giá cố định có sẵn từ một số hãng vận tải. Khi được bật, Tỷ lệ cố định sẽ xuất hiện dưới dạng một tùy chọn trong quá trình thanh toán. Vì không có nhà cung cấp dịch vụ cụ thể nào được chỉ định, bạn có thể sử dụng nhà cung cấp dịch vụ mà bạn lựa chọn.
#### b.Free Shipping
#### c.Table Rates
    + Phương pháp vận chuyển theo bảng giá tham chiếu đến một bảng dữ liệu để tính phí vận chuyển dựa trên sự kết hợp của các điều kiện, bao gồm:

    + Trọng lượng v. Điểm đến
    + Giá so với điểm đến
    + Số lượng mặt hàng so với Điểm đến

    Ví dụ: nếu kho hàng của bạn ở Los Angeles, thì chi phí vận chuyển đến San Diego sẽ thấp hơn so với gửi đến Vermont. Bạn có thể sử dụng vận chuyển theo bảng giá để chuyển khoản tiết kiệm cho khách hàng của mình.
#### d.UPS : 4 các dưới là custom phương thức thanh toán
#### e.USPS
#### f.FedEx
#### g.DHL
## VI.Yotpo
### 1.Review and Visual Marketing 
#### a.Setup : Phiên bản module
#### b.Widget Settings
    + Show Reviews Widget : Hiện thi Widget Review
    + Show star rating on category pages: Hiển thị đánh giá sao trên trang danh mục.
    + Show star rating on product pages	: Hiện thị đánh giá sao trên trang sản phẩm.
    + Show Q&A Bottom-line : Hiện thị Q&A
    + Hide Magento Reviews : Hiện thị Review
    + Enable Debug Mode	: Bật tắt debug mode
#### c.Sync Settings
    + Orders Sync From Date : Động bộ đơn hàng từ ngày ...
    + Orders Sync Limit	: Giới hạn đơn hàng đồng bộ là bao nhiêu
    + Orders Sync Statuses	: Trạng thái đơn hàng đồng bộ.
## VII.Dotdigital
### 1.Accounts
#### a.Setting 
    + Sử dụng API User
### 2.Chat Setting
    + Bật chế độ chat
### 3.Data Mapping
    + 
### 4.Sync Setting
#### a.Address Book Mapping
    + Allow non-subscribed contacts to be imported :  Cho phép nhập địa chỉ chưa đăng ký
    + Add Customers To	: Thêm khách 
    + Add Subscribers To :Thêm người đăng kí
    + Add Guests To	: Thêm khách
#### b.Sync
    + Customer Enabled: Kích hoạt khách hàng
    + Guest Enabled	: Khách thuê hoặc được mời được kích hoạt
    + Subscriber Enabled: Người đăng kí được kích hoạt
    + Order Enabled	: Kích hoạt đơn hàng
    + Wishlist Enabled :  Danh sách yêu thích được kích hoạt
    + Review Enabled : Đánh giá được kích hoạt
    + Catalog Enabled :  Danh mục được kích hoạt.
#### c.Create Address Book
    + Address Book Name : Tạo địa chỉ
    + Visibility : Chế độ hiện thị
### 5.Abandoned Cart 
    + Enrol abandoned cart to : Bật tắt giỏ hàng bị bỏ roi.
    + Enrol abandoned cart after : Giỏ hàng bị bỏ rơi sau bao lâu.
    => Abandoned Cart chính là khi mà khách hàng cho sản phẩm vào giở mà bỏ quên không thanh toán thì hệ thống sẽ gửi email cho khách hàng nhắc nhở khách hàng là có sản phẩm trong giỏ.
### 6.Automation 
#### a.Visitor action automation enrolment
    + Tự dộng hóa là cho phép hệ thống tự động tương tác với email của khách hàng mà không cần quản trị viên nhờ đó nắm bắt các hoạt động của khách hàng như sở thích, sinh nhật...
    + New Customer : được kích hoạt khi có khách hàng mới
    + New Subscriber : được kích hoạt khi có người đăng kí mới
    + First Customer Order : Được áp dụng cho khách hàng đầu tiên
    + Customer Order :  Được áp dụng cho khách hàng order có acccount
    + Guest Order :  Được áp dụng cho khách hàng order không có acccount
    + Approved Review	: Được áp dụng khi review được phê duyệt
    + New Wishlist: Được áp dụng khi có 1 danh sách yêu thích mới từ khách.
#### b.Order Status Automation Enrolment
    + Đây là thêm trạng thái hành động tự động của đơn hàng trong magento 2
#### c.Review Settings
    + Enabled : bật tắt
    + Allow review reminder for non-subscribed contacts : Cho phép nhắc nhở đánh giá những liên hệ chưa đăng ký.
    + Order Status : Trạng thái đơn hàng
    + Delay Period :  Thời gian trì hoãn ngày 
    + Campaign to send : Gửi chiến dịch 
    + Reviews Anchor : Cung cấp kí tự liên kết vd #review nó giống cái tab
#### d.Feefo Feedback Engine ??
    + Feefo Logon : Đăng nhập công cụ phản hồi
    + Reviews Per Product : Đánh giá mỗi sản phẩm .Điền số đánh giá trên mỗi sản phẩm.
    + Logo Template (Optional)	: Logo mẫu
    + Service Score URL : URL dịch vụ
    + Product Reviews URL :	 URL đánh giá sản phẩm
### 7.Dynamic Content(Nội dung động)
#### a.External Dynamic URLs
    + Secure code for dynamic URLs :
    + Cart Content URL : Nội dung giỏ hàng động
    + Coupon Codes URL	 : mã code url 
    + ???
#### b.Dynamic Products(Sản phẩm động)
    + Wishlist : Hiển thị dạng
    + Reviews :
    + Related Products : 
    + Tương tự ....
#### c.Manual Product Push 
    + tương tự ..
#### d.Fallback Products
    + Products : Điền id các sản phẩm ngăn các nhau bằng dấu phẩy.
### 8.Transactionnal Email(Email cho giao dịch)
    + Enabled :  bật tắt
    + Send Mode : chọn phương thức
    + Host : Chọn Host
    + Username : user name
    + Password : mk 
    + Port : cổng
    + Debug : có debug không
### 9.Email Templates
    + Tại đây sẽ setting các mẫu email mà chúng ta đã dùng ở các chức năng trc đó.
### 10.Configuration
#### a.Data Fields
    + Data fields calculation with status : Chỉ định dạng trạng thái đơn hàng
    + Brand Attribute : Thuộc tính thương hiệu.
#### b.Tracking (Theo dõi)
    + ROI Tracking : Theo dõi bằng ROI
    + Page Tracking : Theo dõi TRang
    + Web Behavior Tracking Profile Id	: id cấu hình theo dõi hành vi.
    => Theo dõi hành vi web cho phép bạn có cái nhìn sâu sắc hơn về cách khách hàng và khách truy cập tương tác với trang web của bạn.
#### c.Consent
    + Import subscribers with their consent information : Yêu cầu nhập thông tin vầ sự hài lòng của họ.
    + Consent text provided to your subscribers above the newsletter signup form : Văn bản đồng ý được cung cấp cho người đăng ký của bạn phía trên biểu mẫu đăng ký bản tin
    + Consent text provided on registration, account dashboard and checkout : Văn bản đồng ý được cung cấp trên đăng ký, trang tổng quan tài khoản và thanh toán
#### d.Transactional Data
    + Import Order With Status : Đơn hàng nhập có trạng thái là.
    + Order Custom Attributes : Thuộc tính tùy chọn của đơn hàng.Chọn thuộc tính đơn đặt hàng tùy chỉnh mà bạn muốn nhập với dữ liệu đơn đặt hàng của mình. Chọn nhiều bằng cách nhấn nút Ctrl trong khi chọn.
    + Product Attributes : Các) thuộc tính sản phẩm đã chọn sẽ được nhập theo đơn đặt hàng và đồng bộ hóa danh mục.
    + Include Product Custom Options In Order Sync : Bao gồm các tùy chọn tùy chỉnh của sản phẩm trong đồng bộ hóa đơn hàng
#### e.Abandoned Carts
    + Easy Email Capture (Checkout): Bật tính năng này nếu bạn có quy trình thanh toán cho phép khách truy cập nhập địa chỉ email của họ trong quá trình thanh toán, nhưng nó không cập nhật nội dung bảng báo giá
    + Easy Email Capture (Newsletter) : Bật tính năng này nếu bạn muốn cập nhật bảng báo giá với email được nhập vào Trường Email Bản tin.
    + Allow abandoned cart for non-subscribed contacts :Bật tính năng này nếu bạn muốn cho phép gửi email giỏ hàng bị bỏ rơi đến các liên hệ chưa chọn tham gia
    + Abandoned Cart Limit :Không gửi email giỏ hàng bị bỏ qua cho một liên hệ nếu họ đã nhận được email giỏ hàng bị bỏ rơi trước đó trong x giờ trước đó.
    + Link To Cart Enabled	: bật liên kết tới giỏ hàng
    + Link Text	:Vui lòng cung cấp văn bản liên kết. Nếu không có văn bản nào được cung cấp thì văn bản mặc định "Đưa Tôi Vào Giỏ Của Tôi" sẽ được sử dụng.
    + Cart URL :
Vui lòng cung cấp url giỏ hàng. Nếu không có url nào được cung cấp thì url thanh toán / giỏ hàng mặc định sẽ được sử dụng. Chỉ nhập url sau url cơ sở. Ví dụ đối với http://www.localhost.com/checkout/cart chỉ nhập thanh toán / giỏ hàng
    + Customer Login URL :Vui lòng cung cấp url đăng nhập của khách hàng. Nếu không có url nào được cung cấp thì url đăng nhập mặc định của khách hàng / tài khoản / thông tin đăng nhập sẽ được sử dụng. Chỉ nhập url sau url cơ sở. Ví dụ đối với http://www.localhost.com/customer/account/login chỉ nhập khách hàng / tài khoản / đăng nhập
#### f.Dynamic Content Styling
    + Các setting tạo nội dung động.
#### g.Dynamic Content
    + Product Link Text : Văn bản liên kết sản phẩm.
#### h.Admin
    + Disable Newsletter Success : Tắt bản tin thành công
    + Disable Customer Success : Tắt khách hàng thành công.
#### i.Catalog Sync Settings
    + Catalog Values : giá trị danh mục
    + Catalog Visibility : Hiện thị danh mục ở đây
    + Catalog Type	 :  Kiểu danh mục
#### j.Customer Preference
    + Show Preferences to Customer : Bật sự hài lòng của khách hàng
    + Show Addressbooks to Customer	: Hiện thị địa chỉ khách hàng
    + Show Data Fields To Customer?	 : Cho phép hiển thị các trường dữ liệu cho khác hàng
    + Data Fields To Show	: Hiển thị trường dữ liệu 
### 11.Developer 
#### a.Import Setting
    + Contact Sync Size	: Đồng bộ liên lạc kích thước
    + Transactional Data Sync Size :
    + Enable Subscribers Sales Data Sync :Cho phép khả năng đồng bộ hóa dữ liệu bán hàng của người đăng ký làm tăng tải máy chủ và thời gian đồng bộ hóa tổng thể.
    + Remove /pub directory from URLs : Bật tính năng này để xóa thư mục / pub khỏi URL hình ảnh trong đồng bộ hóa danh mục và dữ liệu thông tin chi tiết.
#### b.Sync Setting
    + Chạy các đồng bộ 
#### c.Debug
    + Chạy debug 
    + Đặt số giây mà api gọi lớn hơn sẽ được ghi lại.
#### d.OAUTH Credentials
    + Xác thực Magento OAuth dựa trên OAuth 1.0a , một tiêu chuẩn mở để xác thực API an toàn . OAuth là một cơ chế chuyển mã thông báo cho phép hệ thống kiểm soát ứng dụng của bên thứ ba nào có quyền truy cập vào dữ liệu nội bộ mà không tiết lộ hoặc lưu trữ bất kỳ ID người dùng hoặc mật khẩu nào.
#### e.Dynamic Page IP Restriction
    + Hạn chế IP các trang động 
#### f.
    + Manage Cron Timings là quản lí đặt thời gian lên lịch cho các công việc trong tương lai. Đây là các công việc :
    + Importer	
    + Contact	
    + Order	
    + Catalog	
    + Review And Wishlis
## VIII.Services
### 1.Magento Web API
#### a.SOAP Setting
    + Default Response Charset	: Bộ mã phản hồi mặc định
#### b.Web API Security
    + Allow Anonymous Guest Access	: Cho phép Quyền truy cập của Khách Ẩn danh. Tính năng này chỉ áp dụng cho các API CMS, Catalog và Store. Vui lòng tham khảo ý kiến ​​nhà phát triển của bạn để biết chi tiết về các rủi ro bảo mật tiềm ẩn.
### 2.Channels
    + Google Shopping ads Channel
### 3.OAuth 
#### a.Access Token Expiration
    + Customer Token Lifetime : Thời gian sống của token khách hàng
    + Admin Token Lifetime : Thời gian sống token quản trị viên
    => Mỗi liên kết Oauth sẽ có thời gian liên kết của nó
#### b.Cleanup Settings
    + Cleanup Probability : Tần suật dọn dẹp
    + Expiration Period : Thời gian dọn dẹp
#### c.Consumer Settings(Cài đặt người tiêu dùng)
    + Expiration Period : Thời gian tồn tại .Khóa / bí mật của người tiêu dùng sẽ hết hạn nếu không được sử dụng trong vòng X giây sau khi bắt đầu trao đổi mã thông báo Oauth.
    + OAuth consumer credentials HTTP Post maxredirects : 	
Số lần chuyển hướng tối đa cho thông tin đăng nhập của người tiêu dùng OAuth Đăng yêu cầu.
    + OAuth consumer credentials HTTP Post timeout :	
Hết thời gian chờ thông tin đăng nhập của người tiêu dùng OAuth Đăng yêu cầu trong vòng X giây.
#### d.Authentication Locks
    + Maximum Login Failures to Lock Out Account: Số lần login thất bại cho phép
    + Lockout Time (seconds) : Khoảng thời gian mở khóa tài khoản,
## XI.Advanced 
### 1.Admin
#### a.Admin User Emails
    + Forgot Password Email Template : Mẫu quên mật khẩu
    + Forgot and Reset Email Sender : Người gửi thư quên mật khẩu passwork
    + User Notification Template: sử dụng template thông báo nào
#### b.Startup Page
    + Startup Page : chọn trang vào đầu tiên khi đăng nhập xong.
#### c.Admin Base URL
    + Use Custom Admin URL : Cho phép tùy chỉnh URL Admin
    + Use Custom Admin Path	: Cho phép tùy chỉnh Path Admin
#### d.Security
    + Admin Account Sharing : nếu chọn đúng bạn có thể log vào nhiều máy tính cùng 1 tài khoản.
    + Password Reset Protection Type : Kiểu đặt lại mật khẩu.
    + Recovery Link Expiration Period (hours)	: Thời gian hết hạn của liên kết khôi phục.
    + Max Number of Password Reset Requests : Số request tối đa đạt lại mk
    + Min Time Between Password Reset Requests : Thời gian nhỏ nhất giữa 2 lần request đặt lại mk
    + Add Secret Key to URLs : Thêm khóa bí mật vào URL
    + Login is Case Sensitive : Đăng nhập vào trường hợp nhạy cảm.=> khái niệm "nhạy cảm" thôi cái này nói vuông nhất là nó sẽ không phân biệt chữ hoa chữ thường => Khuyên không nên dùng mk phải phân biệt chữ hoa chữ thường.
    + Admin Session Lifetime (seconds) : Thời gian sống của session. nếu dùng quá sẽ tự động logout. và phải log lại.
    + Maximum Login Failures to Lockout Account	: Số lần log sai tối đa.
    + Lockout Time (minutes) : Thời gain khóa tài khoản .
    + Password Lifetime (days)	 : Thời gian sống của mật khẩu.nó sẽ giống như mật khẩu ngân hàng Cứ 1 khoảng thời gian bạn phải thay đổi mk của mình mặc định ở đây là 90 day nên sau 90 hệ thống sẽ báo bạn phải thay đổi mk
    + Change Passwork : Chọn kiểu thay đổi.
#### e.Dashboard
    +Enable Charts	 : Bật biểu đồ ở trang điều khiển.
#### f.CAPTCHA
    + Ở sao cảm giác những phần này viết ở đâu rồi ấy. Quen thế cơ. Thôi bạn nào đọc thì nhớ r thì note lại cho các bạn khác .Còn mình viết lại vậy.
    + Enable CAPTCHA in Admin : Bật captcha ở quản trị viên
    + Font: Chọn Font
    + Form : Chọn Form
    + Displaying Mode : Chọn hiện thị khi nào, khi login thất bại nhiều lần hay thường xuyên
    + Number of Unsuccessful Attempts to Login : Số lần đăng nhập không thành công để hiển thị captcha
    + CAPTCHA Timeout (minutes)	 : Thời gian captcha
    + Number of Symbols : Số kí tụ
    + Symbols Used in CAPTCHA	: Các kí tự dùng cho captcha
    + Case Sensitive : Trường hợp nhạy cảm -> Nói toạc luôn là dùng chữ hoa hay không thôi.
#### g.Admin Usage
    + Enable Admin Usage Tracking : Theo dõi quản trị viên để thu thập dữ liệu thói quen của quản trị viên nhắm hướng đến tối ưu chức năng :D Không biết có thật không hay là theo dõi xem nó có làm đủ giờ không nữa :).
### 2.System
#### a.MySQL Message Queue Cleanup
    + Successful Messages Lifetime	 : Thời gian sống của thông báo thành công
    + Retry Messages In Progress After : Thời gian thử lại các tin nhắn sau đó.
    + Failed Messages Lifetime	: thời gian sống của tin thất bại
    + New Messages Lifetime	 : Thời gian sống của tin mới,
#### b.Cron(Nhiệm đã lên lịch)
    + Tạo lịch biểu mỗi lần
    + Lên lịch trước cho
    + Bỏ lỡ nếu không chạy trong	
    + Xóa lịch sử mỗi lần	
    + Thời gian sống lịch sử thành công
    + Thời gian sống lịch sử thất bại
    + Sử dụng quy trình riêng biệt
#### c.Mail Sending Settings
    + Disable Email Communications : Bật chế độ tắt thông báo qua email
    + Host : localhost
    + Port : cổng
    + Set Return-Path : Đặt đường dẫn trở lại.
#### d.Currency
    + Installed Currencies : Đơn vị tiền tệ đã cài đặt
#### e.Notifications
    + Use HTTPS to Get Feed : Dùng HTTPS cùng cấp dữ liệu.
    + Update Frequency	: Thời gian cập nhật tần số.
#### f.Backup Settings 
    + Backup : Cho phép backup database
#### g.Bulk Actions
    + Days Saved in Log : Số ngày lưu trong đăng nhập
#### h.Full Page Cache
    + Caching Application : Ứng dụng bộ nhớ đệm
    + TTL for public content : Thời gian tồn tại của bộ đệm nội dung công khai tính bằng giây. Nếu trường trống, giá trị mặc định 86400 sẽ được lưu.
#### i.Storage Configuration for Media
    + Media Storage : Phương tiện lưu trữ	
    + Environment Update Time	: Thời gian cập nhật môi trường	
#### j.Images Upload Configuration
    + Quality : Chất lượng theo %
    + Enable Frontend Resize : Bật tính năng thay đổi kích thước hình ảnh
    + Maximum Width : chiều ngang lớn nhất.
    + Maximum Height : Chiều cao lớn nhất.
#### k.Adobe Stock Integration
    + Enabled Adobe Stock : Bật Adobe
    + API Key : Key API
    + Client Secret	: Bí mật khách hàng.
### 3.Developer
#### a.Frontend Development Workflow
    + Chế độ biên dịch : biên dịch ít hơn phía khách hay admin
#### b.Developer Client Restrictions
    + IP được phép phân tách bằng dấu phẩy
#### c.Debug
    + Bật gợi ý về đường dẫn mẫu cho Mặt tiền cửa hàng
    +  Bật gợi ý về đường dẫn mẫu cho quản trị viên	
    + Thêm loại khối lớp vào gợi ý	
#### d.Templates Settings
    + Allow Symlinks	: Cho phép liên kêt tượng chưng
    + Minify Html	: Giảm thiểu html
#### e.Translate Inline
    + Enabled for Storefront : Bật mặt tiền của hàng.
    + Enabled for Admin : Dịch, khối và các bộ nhớ đệm đầu ra khác sẽ bị tắt cho cả bản dịch nội tuyến Storefront và Admin.
#### f.TranSrcipt Settings
    + Merge JavaScript Files : Ghép thư mục js
    + Enable JavaScript Bundling : Bật gói js
    + Minify JavaScript Files : Giảm thư mục js
    + Move JS code to the bottom of the page : Chuyển js phần dưới trang
    + Translation Strategy	: Dịch thuật
    + Log JS Errors to Session Storage : Ghi lỗi JS vào bộ nhớ phiên
    + Log JS Errors to Session Storage Key : Ghi các lỗi JS vào Khóa lưu trữ phiên	
#### g.CSS Setting
    + Merge CSS Files : Ghép file css
    + Minify CSS Files : Giảm file css
    + Use CSS critical path	: Sử dụng đường dẫn quan trọng CSS	
#### h.Image Processing Setting
    + Image Adapter : Chuyển đổi Ảnh
#### i.Caching Setting
    + Cache User Defined Attributes	: Thuộc tính do người dùng xác định trong bộ đệm	
#### k.Static Files Settings
    + Sign Static Files : Ký tệp tĩnh
#### m.Grid Setting
    + Asynchronous indexing	: Có lập chỉ mục không đồng bộ.
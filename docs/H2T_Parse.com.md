## Tài liệu mô tả Parse
Tài liệu này giới thiệu về dịch vụ bên thứ 3([Parse](https://Parse.com/)) mà nhóm H2TFC sử dụng để phát triển ứng dụng quản lý phân phối điểm bán hàng.

I. Các thành phần của [Parse](https://Parse.com/) hỗ trợ cho việc phát triển
--------------------------------------------
[Parse](https://Parse.com/) gồm 3 thành phần dùng để hỗ trợ cho việc phát triển ứng dụng(không cần phải quan tâm về việc bảo trì server hay kiến thức chuyên sâu về server)
 1. [Parse Core](https://parse.com/products/core) 
 
 	> Là thành phần đóng vai trò quan trọng, được xem như là cơ sở dữ liệu để các client từ phía ứng dụng có thể truy xuất và lưu trữ dữ liệu lên mà không cần phải có server, ngoài ra core còn cung cấp giao diện dashboard trực quan qua giao diện web giúp người dùng dễ dàng thao tác các chức năng mà Parse mang lại.
 2. [Parse Push](https://parse.com/products/push)
 
	> Dùng để gửi đi những tin nhắn, thông báo từ máy chủ Parse.com tới các máy con một cách dễ dàng.
 3. [Parse Analytics](https://parse.com/products/analytics)
 
	> Dùng để theo dõi các thông số hoạt động của ứng dụng tới server.

 II. Chi tiết giá cả của từng thành phần ở Parse
 
 Link tham khảo: https://parse.com/plans
 
 Bảng giá cả của các thành phần tại parse.com/plans (cập nhật ngày 16/04/2015)
 
 1. Parse Core
 
 >	* Parse.com là phần mềm bên thứ 3 cho phép sử dụng miễn phí và có khả năng tăng thêm dung lượng và số lượng truy cập bằng các đóng phí.
 >	* Tuy số lượng truy cập được ghi trên trang chủ của Parse.com là số lượng truy cập/s nhưng thật ra Parse.com tính số lượng truy cập/phút.
 >	> Nên ở đây khi sử dụng miễn phí nên 30 lượt truy cập/s = 1.800 lượt truy cập/phút.Ví dụ khi có 1.000 lượt truy cập cùng lúc vào máy chủ thì Parse.com vẫn có thể xử lý được nhưng trong 1s đó mà có 2.000 lượt truy cập thì sẽ có 200 lượt truy cập sẽ bị từ chối do khi sử dụng hạn mức miễn phí thì Parse.com chỉ chấp nhận 1.800 truy cập/phút.
 >	* Mức phí tối thiểu thành cho Parse Core:
 >	* Mức phí tối đa cho Parse Core:
 
 Nếu số lượng request mà vượt qua quá số lượng tối đa mà gói dịch vụ Parse có thể cung cấp thì khách hàng có thể trao đổi với nhân viên bên phía Parse để được tư vấn và giải quyết về vấn đề số lượng truy cập này.
 
 Tuy nhiên xin hãy lưu ý cho: 600 lượt truy cập/s là 1 con số rất lớn(36.000 lượt truy cập/phút) kèm với khả năng để tất cả nhân viên cùng làm tại một thời điểm là rất khó xảy ra.

 2. Parse Push
 
 3. Parse Analytics
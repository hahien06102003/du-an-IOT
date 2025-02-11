TÀI LIỆU ĐẶC TẢ PHẦN MỀM CHO
<Dự Án Vườn Thông Minh >
Biên soạn <Hà Ngọc Hiển- Nguyễn Ngọc Tùng- Nguyễn Hoàng Khánh Minh-Vũ Mạnh Tuấn- Nguyễn Trường Sơn >
<9/02/2025 >












BẢNG NỘI DUNG
Bảng nội dung	ii
1.Giới thiệu	1
1.1	Mục đích	1
1.2	Phạm vi	1
1.3	Đối tượng	1
2.	Mô tả tổng quan	2
3.	Yêu cầu người dùng	3
3.1	Điều khiển	3
3.2	Tự động hóa	4
3.3   Tiện nghi	5
4.	Yêu cầu chức năng	4
4.1	Điều khiển đèn	4
4.2	Điều khiển điều hòa	4
4.3	Hệ thống an ninh	4
5.	Yêu cầu phi chức năng	5
5.1	Hiệu suất	5
5.2	Bảo mật	5
5.3	Độ tin cậy	5
5.4	Giao diện	5
6.	Thiết kế hệ thống 	5
7.	Phân công công việc	5




LỊCH SỬ ĐIỀU CHỈNH
Name	Date	Lý do hiệu chỉnh	Version
			
			






1. GIỚI THIỆU
•	1.1 Mục đích: Tài liệu này mô tả chi tiết các yêu cầu và chức năng của phần mềm hệ thống vườn thông minh, nhằm cung cấp cơ sở cho việc thiết kế, phát triển, kiểm thử và triển khai hệ thống.
•	1.2 Phạm vi: Hệ thống vườn thông minh này tập trung vào các chức năng điều khiển đèn, hệ thống an ninh, quản lý năng lượng và các thiết bị tưới tiêu thông minh khác.
•	1.3 Đối tượng: Tài liệu này dành cho các nhà phát triển phần mềm, kỹ sư hệ thống, người kiểm thử, quản lý dự án, kiến trúc sư giải pháp, chuyên gia bảo mật và các bên liên quan khác.
2. MÔ TẢ TỔNG QUAN
Hệ thống vườn thông minh này cho phép người dùng điều khiển hệ thống có khả năng tự động hóa các tác vụ, giúp tiết kiệm năng lượng,và mang lại trải nghiệm sống tiện nghi, hiện đại cho người dùng.
3. YÊU CẦU NGƯỜI DÙNG
•	3.1 Điều khiển: Người dùng có thể dễ dàng điều khiển đèn.
•	3.2 Tự động hóa: Hệ thống có thể tự động bật/tắt đèn, điều hòa, hệ thống tưới cây dựa trên lịch trình, cảm biến.
•	3.3 Tiện nghi: Hệ thống giúp người dùng dễ dàng quản lý và tận hưởng không gian sống tiện nghi, thoải mái.
•	3.4 An ninh: Hệ thống cảnh báo khi có đột nhập, cháy, rò rỉ khí gas hoặc các sự cố khác.
4. YÊU CẦU CHỨC NĂNG
•	4.1 Điều khiển đèn: 
o	Bật/tắt đèn từ xa.
o	Điều chỉnh độ sáng đèn (%).
o	Hẹn giờ bật/tắt đèn (thời gian cụ thể).
o	Tự động bật/tắt đèn khi có người (sử dụng cảm biến chuyển động).
o	Tạo nhóm đèn và điều khiển nhóm.
o	Điều khiển đèn theo kịch bản (ví dụ: "chế độ xem phim", "chế độ ăn tối").
•	4.2 Điều khiển điều hòa: 
o	Bật/tắt điều hòa từ xa.
o	Điều chỉnh nhiệt độ (độ C).
o	Hẹn giờ bật/tắt điều hòa (thời gian cụ thể).
o	Điều chỉnh chế độ hoạt động (làm lạnh, sưởi ấm, thông gió).
o	Điều khiển điều hòa theo kịch bản.
•	4.3 Hệ thống an ninh: 
o	Cảm biến chuyển động (phát hiện chuyển động).
o	Cảm biến cửa/cửa sổ (phát hiện mở/đóng).
o	Cảm biến khói (phát hiện khói).
o	Hệ thống báo động (còi hú, thông báo đến điện thoại).
o	Xem camera trực tuyến (video real-time).
o	Lưu trữ và xem lại lịch sử video.
o	Nhận thông báo cảnh báo (ví dụ: có người lạ, cửa mở, khói).
      5. YÊU CẦU PHI CHỨC NĂNG
•	5.1 Hiệu suất: 
o	Thời gian phản hồi nhanh chóng (dưới 1 giây).
o	Hệ thống hoạt động ổn định, không bị gián đoạn.
o	Khả năng xử lý đồng thời nhiều yêu cầu.
o	Tối ưu hóa hiệu suất để giảm tải cho hệ thống.
•	5.2 Bảo mật: 
o	Dữ liệu người dùng được mã hóa và bảo mật.
o	Hệ thống chống lại các tấn công mạng (ví dụ: xâm nhập, DDoS).
o	Xác thực người dùng (ví dụ: đăng nhập, mật khẩu, xác thực hai yếu tố).
o	Phân quyền truy cập (ví dụ: người dùng, quản trị viên).
o	Kiểm tra bảo mật định kỳ.
•	5.3 Độ tin cậy: 
o	Hệ thống hoạt động liên tục, ít xảy ra lỗi.
o	Dữ liệu được sao lưu thường xuyên (ví dụ: hàng ngày).
o	Khả năng phục hồi sau sự cố (ví dụ: mất điện, lỗi phần cứng).
o	Hệ thống tự động giám sát và cảnh báo lỗi.
6. THIẾT KẾ HỆ THỐNG
•	6.1 Kiến trúc: 
o	Hệ thống sử dụng kiến trúc client-server.
o	Ứng dụng di động (client) và giao diện web (client) giao tiếp với server thông qua internet.
o	Server kết nối với các thiết bị thông minh qua mạng Wi-Fi, Zigbee, Z-Wave hoặc các giao thức khác.
o	Sử dụng kiến trúc microservices để tăng tính linh hoạt và khả năng mở rộng của hệ thống.
•	6.2 Giao diện: 
o	Ứng dụng di động: 
	Màn hình chính: Hiển thị trạng thái các thiết bị, các chức năng điều khiển nhanh.
	Màn hình điều khiển chi tiết: Điều khiển từng thiết bị cụ thể.
	Màn hình cài đặt: Cấu hình hệ thống, quản lý người dùng, tạo kịch bản tự động hóa.
	Màn hình thống kê: Hiển thị thống kê mức tiêu thụ năng lượng, lịch sử hoạt động.
7. PHÂN CÔNG CÔNG VIỆC
•	Trưởng nhóm (Quản lý dự án): [Tên thành viên] 
o	Chịu trách nhiệm quản lý tổng thể dự án, đảm bảo tiến độ và chất lượng công việc.
o	Điều phối các thành viên trong nhóm, giải quyết xung đột và đưa ra quyết định cuối cùng.
o	Liên lạc với khách hàng (nếu có) để thu thập yêu cầu và phản hồi.
•	Chuyên gia phân tích yêu cầu: [Tên thành viên] 
o	Thu thập và phân tích yêu cầu từ người dùng (ví dụ: các thành viên trong gia đình).
o	Xác định các tính năng cần thiết của hệ thống.
o	Viết tài liệu đặc tả yêu cầu chi tiết.
•	Chuyên gia thiết kế hệ thống: [Tên thành viên] 
o	Thiết kế kiến trúc tổng thể của hệ thống, bao gồm phần cứng và phần mềm.
o	Lựa chọn các thiết bị và công nghệ phù hợp.
o	Xây dựng sơ đồ kết nối và mô tả chi tiết các thành phần của hệ thống.
•	Lập trình viên: [Tên thành viên] 
o	Phát triển phần mềm điều khiển trung tâm và các ứng dụng di động.
o	Tích hợp các thiết bị và dịch vụ vào hệ thống.
o	Đảm bảo tính ổn định và bảo mật của hệ thống.
•	Chuyên gia kiểm thử: [Tên thành viên] 
o	Xây dựng các kịch bản kiểm thử để đảm bảo chất lượng của hệ thống.
o	Thực hiện kiểm thử và báo cáo lỗi.
o	Đề xuất các cải tiến để nâng cao chất lượng hệ thống.



# CS105 Đồ họa máy tính 


<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

| STT | Họ tên |
| :---: | --- |
| 1 | **PGS.TS. Lê Đình Duy** | 

## **Giới thiệu thành viên nhóm**
<!-- ### Thông tin liên hệ -->
| STT | MSSV | Họ tên |
|:--- | :-------|:----------|
|1|19521858|Võ Tuấn Minh|19521858@gm.uit.edu.vn|
|2|19521322|Huỳnh Ngọc Công Danh| 19521322@gm.uit.edu.vn|
|3|19520148|Đinh Hoàng Lộc|19520148@gm.uit.edu.vn|


# Đồ án: Mô phỏng hiệu ứng mưa
<h2>I.	GIỚI THIỆU ĐỀ TÀI	</h2>
<h3>1.1 Đặt vấn đề</h3>
Ngày nay, đồ họa máy tính không còn là điều quá đỗi lạ lẵm đối với người dùng PC, có thể dễ dàng thấy hình ảnh 2D cho tới 3D ở bất kỳ đâu. 
Đồ họa máy tính là phương pháp và công nghệ dùng trong việc chuyển đổi qua lại giữa dữ liệu và hình ảnh bằng máy tính. Đồ họa máy tính là một lĩnh vực của khoa học máy tính nghiên cứu về ở toán học, các thuật toán cũng như các kĩ thuật để cho phép tạo, hiển thị và điều khiển hình ảnh trên màn hình máy tính. 
Có rất nhiều phần mềm hỗ trợ cho thiết kế đồ họa 3D, trong đồ án này, nhóm sử dụng phầm mềm Blender 3D để xây dựng việc mô phỏng hiệu ứng trời mưa
<h3>1.2 Mục tiêu</h3>
Trong đề tài này, nhóm thực hiện việc tìm hiểu cách dùng Blender, cơ chế hoạt động, cách thay đổi thông số. Từ đó sẽ xây dựng hiệu ứng 3D mô phỏng trời mưa trên mặt đường và kết xuất thành video chuyển động. 



<h2>II.	GIỚI THIỆU CÔNG CỤ BLENDER 3D </h2>
<h3>2.1	Blender 3D là gì?</h3>
Blender là một bộ mã nguồn mở tạo vật thể 3D miễn phí. Nó hỗ trợ gần như là toàn bộ các phương tiện để tạo một mô hình 3D như mô hình hóa, lắp ráp, giả lập, tổng hợp và theo dõi chuyển động, ngay cả việc chỉnh sửa video và sáng tạo game. Những người sử dụng nâng cao còn có thể triển khai Blender API bằng Python script để tự điều chỉnh và tạo ra những công cụ chuyên dụng cho họ; thường là sẽ được thêm vào trong tính năng của Blender trong tương lai. Blender phù hợp cho những cá nhân, công ty nhỏ - những người mà được hưởng lợi từ quá trình phát triển đáp ứng và thống nhất của nó.
Blender có thể chạy được tốt trên đa nền tảng nhưng Linux, Window và macOS. Giao diện của nó sử dụng OpenGL để cung cấp cho người dùng một trải nghiệm nhất quán. Để kiểm tra tính tương thích nhất định của nó, thì danh sách các nền tảng được hỗ trợ có thể được xem trên trang chủ của Blender.
Là một dự án cộng đồng dưới sự cấp phép của GNU GPL, cộng đồng được trao quyền chỉnh sửa những thay đổi lớn và nhỏ trong code bas để tạo ra những tính năng mới sửa lỗi về responsive, và cải thiện việc sử dụng. Blender hoàn toàn miễn phí, nhưng nếu có thể đầu tư, tham gia và giúp cộng đồng phát triển Blender thì nó sẽ là phần mềm 3D của riêng bạn.
<h3>2.2	Tại sao nên sử dụng Blender?</h3>
Free: do được cấp phép bởi GNU GPL, và sở hữu bởi chính họ nên vì lý do đó Blender đã trở thành phần mềm mã nguồn mở và miễn phí mãi mãi
Powerful: Blender có thể làm được hầu hết các thao tác để tạo ra 1 mô hình 3D. Ngoài ra người dùng có thể tự điều chỉnh ra những công cụ phục vụ cho chính mình (customize) và Blender còn thể chạy được trên nhiều hệ điều hành như Windows, macOS và Linux.
Small: dung lượng chỉ có 250MB do các nhà phát triển đã cố gắng để không làm cho phần mềm trở nên nặng hơn bằng cách giới hạn các tác nhân làm cho phần mềm nặng hơn như các thư viện, DRM software, … và thay thế bằng các tài nguyên được tối giản làm cho Blender giảm được đáng kể kích thước khi cài đặt
A large and growing community of Blender user: có được một cộng đồng mạng hỗ trợ đông đảo, từ group trên mạng xã hội cho đến các forum.

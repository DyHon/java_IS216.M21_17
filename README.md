# <h1 align="center">Java_IS216_17<h1>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
  </a>

  <h3 align="center">UIT Stock Exchange</h3>

  <p align="center">
    Quản Lí Giao Dịch Chứng Khoán
    <br />
    <br />
    <br />
    <a href="https://coffee-huybui.vercel.app/">Xem Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="#muctieu">Mục tiêu đồ án</a>
    </li>
    <li>
      <a href="#dsthanhvien">Danh sách thành viên</a>
    </li>
    <li>
      <a href="#chucnang">Các chức năng</a>
    </li>
    <li><a href="#yeucau">Yêu cầu hệ thống</a></li>
    <li>
      <a href="#caidat">Cài đặt và sử dụng</a>
      <ul><a href="#setup">Setup môi trường</a></ul>
      <ul><a href="#start">Khởi động dự </a></ul>
    </li>
    <li><a href="#lienhe">Liên hệ</a></li>
    <li><a href="#banquyen">Bản quyền</a></li>
    <li><a href="#thamkhao">Tài liệu tham khảo</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## <h2 id="muctieu">Mục tiêu của đồ án</h2>
Đây là project của môn học Xây dựng hệ thống thông tin trên các Framework - UIT. Nội dung là tạo một trang web quản lý chuỗi bán lẻ cà phê và sách

Trang web phải đảm bảo được các mục tiêu:
- Giúp khách hàng mua hàng được nhanh chóng và đúng sản phẩm mình cần.
- Tiện lợi cho người bán hàng dễ dàng quản lý cửa hàng của mình.
- Giao diện đơn giản, load nhanh.
## <h2 id="dsthanhvien">Các thành viên tham gia project</h2>
 
| STT| Họ tên         | MSSV                 | FB                                                   |   SĐT     |     Nhiệm vụ    |   Đánh giá % |
|:--:|----------------|------------------------|----------------------------------------------------|-----------|-----------------|--------------|
| 1  | Nguyễn Thừa An Thái       | 19522192 |[An Thai](https://www.facebook.com/)         |000 |Trưởng nhóm      |     33.33       |
| 2  | Lê Duy Hoàng       | 19521533 |[Duy Hoàng](https://www.facebook.com/)           |000 |Code frontend    |     33.33       | 
| 3  | Huỳnh Kim Phát     | 19521992 |[Kim Phat](https://www.facebook.com/) |000 |Tester   |     33.33       |



### <h2 id="framework">Các Framework sử dụng</h2>

Trang web được xây dựng bởi các thư viện, framework hiện đại:
* Frontend: Java
* Backend: Java

# <h2 id="chucnang">Tóm tắt chức năng</h2>
- Khách hàng:<br/>
  + Đăng nhập, đăng ký, lấy lại mật khẩu
  + Mua và đặt 
  + Xem thông tin chứng khoán
  + Xem thông tin cơ bản của account khách hàng, cập nhật lại profile 
  + Tra cứu chứng khoán <br/>
- Admin:<br/>
  Thêm sửa xóa các mục sau:
  + Hóa đơn giao dịch,đơn hàng 
  + Tài khoản (account)
  + Danh sách khách hàng,nhân viên, quản lý
  + Danh sách các chứng khoán
  + Nhà cung cấp(công ty) <br/>
- Doanh số:<br/>
  + Kiểm tra được thông tin theo từng năm,tháng,ngày
  + Xuất thông tin báo cáo theo năm,tháng,ngày<br/>
- Quản lý sẽ được cấp mục sau:
  + Giao dịch,đơn hàng (<b>chỉ xem và hủy đơn hàng</b>)
  + Danh sách khách hàng (<b>chỉ xem</b>)
  + Danh sách nhân viên(<b>Thêm xóa sửa</b>)<br/>
- Bảng thống kê doanh thu sẽ được tự động cập nhật khi người dùng chọn ngày và xuất thông tin thành file excel đúng như người dùng thấy trên bảng kết quả. <br/>
- Khi admin muốn chuyển quản lý sang một cửa hàng khác thì tự động quản lý ở cửa hàng cũ sẽ không tồn tại quản lý. <br/>
- Tạo account tương ứng cho quản lý sẽ chỉ được lựa chọn các nhân viên chưa có tài khoản và tự động phân quyền theo các role đã được định sẵn. <br/>

# <h2 id="bonus">Chức năng Bonus</h2>
 + Mã hoá
 + Data cập nhật từng ngày

# <h2 id="yeucau">Yêu cầu hệ thống:</>
  Có JDK

# <h2 id="caidat">Cài đặt và sử dụng</h2>
## <h3 id="setup">Setup môi trường</h3>
1. Tải và cài jdk

2. Tải mySQL:
- Cách tải bằng docker:

Bước 1: Tải và cài docker desktop
- Link tải: [Docker](https://docs.docker.com/desktop/windows/install/)

Bước 2: Tải MySql trên docker:
- Chạy lệnh Run as administrator Powershell -> gõ lệnh:
```sh
   docker run --name MySQLDB -e MYSQL_ROOT_PASSWORD=1234 -p 3306:3306 -d mysql
   ```
- Sau khi docker đã tải mySQL thì bấm nút run để khởi động mySQL

3. Tải mySQL Workbench - Công cụ làm việc với CSDL mySQL
- Link tải: [mySQL Workbench](https://www.mysql.com/products/workbench/)

## <h2 id="lienhe">Liên hệ</h2>

Huỳnh KIm phát


# <h2 id="banquyen">Bản quyền</h3>
Copyright © 2021, HKP.
# <h2 id="thamkhao">Tài liệu tham khảo</h2> 
- https://www.w3schools.com/

`     `**BÀI THU HOẠCH HƯỚNG DẪN TÍCH HỢP VNPAY

BƯỚC 1:** Đăng ký tài khoản theo địa chỉ: **<https://sandbox.vnpayment.vn/devreg/>
![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.001.png)**

----------------------------------------------------------------------------------------------------------
### **Bước 2:** Truy cập vào email dùng để đăng ký tài khoản để xác nhận. Sau khi kích hoạt tài khoản, bạn sẽ nhận được một số thông tin cần thiết để cài đặt ở phần sau.
**
###
### **Cài đặt Plugin WooCommerceIPNURL**
**Bước 1:** Bạn tải plugin WooCommerceIPNURL 
**Bước 2:** Tại giao diện admin WordPress, bạn nhấn vào mục Plugins rồi kích hoạt plugin vừa tải như trong hình.

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.002.png)


### **Cấu hình Plugin WooCommerceIPNURL để kết nối tới VNPAY**
###
**Bước 1:** Bạn nhấn vào mục **Plugins** -> **Woocomerce** -> **Settings** -> **Payment–VNPAY** -> **Manage**. ![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.003.png)

**Bước 2:** Bạn cấu hình các thông số đã nhận được trong email (phần trên).

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.004.png)



Các thông tin cần lưu ý:

- **Enable/Disable:** Cho phép Bật/Tắt plugin. Nếu chọn tắt, website sẽ không hiển thị ví VNPAY trên trang thanh toán.
- **Tiêu đề:** Đặt tên cho cổng thanh toán để hiển thị cho khách hàng
- **Mô tả:** Hiển thị mô tả khi chọn loại thanh toán là VNPAY.
- **URL Khởi tạo giao dịch:** Khách hàng sẽ được chuyển sang URL này khi giao dịch với VNPAY(nhận trong email).
- **Terminal ID:** Mã website của merchant trên hệ thống VNPAY (nhận trong email)
- **Secret Key:** Chuỗi khóa bí mật được sử dụng để kiểm tra toàn vẹn dữ liệu khi hai hệ thống (website và VNPAY) trao đổi thông tin (nhận trong email).
- **Success Page:** Trang VNPAY trả về kết quả khi khách hàng thanh toán thành công, Show thông tin thanh toán cho KH.
- **Locale:** Ngôn ngữ thanh toán khi được sang cổng VNPAY

### **Kiểm tra tính năng thanh toán bằng VNPAY**
###
`    `Bạn hãy thử tạo đơn hàng, sau đó, chọn thanh toán với VNPAY. Lúc này, API của VNPAY sẽ được gọi để thực hiện quá trình thanh toán.

Tiếp theo, bạn chọn thanh toán bằng thẻ quốc tế hoặc thẻ nội địa (Hãy sử dụng các thẻ có sẵn để test).

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.005.png)



Chọn ngân hàng:

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.006.png)



Nhập thông tin thanh toán (thẻ test):

![cach-tich-hop-thanh-toan-vnpay-vao-website] ![cach-tich-hop-thanh-toan-vnpay-vao-website]

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.009.png) Sau khi thanh toán thành công, bạn vào trang quản trị VNPAY để kiểm tra kết quả (link đăng nhập được gửi trong email).

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.010.png)

![cach-tich-hop-thanh-toan-vnpay-vao-website](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.011.png)

Chạy file ví dụ mẫu:

![A white background with blue text

Description automatically generated](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.012.png)

![A screenshot of a computer

Description automatically generated](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.013.png)

![A screenshot of a computer

Description automatically generated](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.014.png)

![A screenshot of a computer

Description automatically generated](Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.015.png)

[cach-tich-hop-thanh-toan-vnpay-vao-website]: Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.007.png
[cach-tich-hop-thanh-toan-vnpay-vao-website]: Aspose.Words.bd86f65a-c84f-455f-ba01-2a1d9e1cfa18.008.png

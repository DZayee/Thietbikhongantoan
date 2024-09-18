## Cách sửa lỗi VNeID báo lỗi “Thiết bị của bạn không an toàn…”
App  VNeID mới cập nhật lên phiên bản 2.1.9 với các tính năng bảo mật nâng cao. Do đó điện thoại Android nào đã Unlock bootloader, bật gỡ lỗi usb, tùy chọn nhà phát triển đều không thể truy cập vào VNeID. Nếu điện thoại bạn đã mở khóa có nguy cơ bảo mật sẽ xuất hiện thông báo lỗi: Thiết bị của bạn không an  toàn, có rủi ro chứa mã độc.
 ## Mục lục bài viết
1 Sử dụng lại phiên bản VNeID 2.1.8 or cũ hơn <br/>
2 Tắt chế độ bật gỡ lỗi usb, tùy chọn nhà phát triển<br/>
3 Dùng phiên bản web của vneid https://vneid.gov.vn/<br/>
4 Các cách khác để truy cập VneID báo lỗi<br/>
# Géc go <br/>
# 1/ Sử dụng lại phiên bản VNeID 2.1.8 hoặc cũ hơn
Xóa cài đặt bản VneID 2.1.9 mới nhất đi, tắt tự động cập nhật trong CHPlay đi, rồi tải file apk vneid 2.1.8 (hoặc cũ hơn) trên về cài rồi xài bình thường.
Sau khi tải về bạn vào ứng dụng File hoặc File của bạn, tìm đến thư mục chưa file VNeID_2.1.8.apk, nhấp chọn rồi cài đăt. Đối với một số điện thoại cần tắt tính năng Không rõ nguồn gốc thì bạn mới cài được nhé.
![image](https://github.com/user-attachments/assets/aa7bacf9-70d9-484c-a625-1911b3482071)

# 2/ Tắt chế độ bật gỡ lỗi usb, tùy chọn nhà phát triển
Nếu đã unlock bootloader thì bạn cần phải lock lại thôi. Nhưng nếu không unlock mà vẫn báo lỗi thì bạn cần thực hiện các bước sau:
Nếu bạn vẫn muốn dùng VNeID 2.1.6 mới nhất, hãy thử kiểm tra xem điện thoại có đang bật gỡ lỗi USB không?, nếu có có thì hãy tắt tính năng này đi. Tùy điện thoại sẽ có mỗi cách bật/tắt gỡ lỗi USB khác nhau. Bạn tham khảo các cách sau:
+ Cài đặt -> Cài đặt bổ sung -> Tùy chọn nhà phát triển- > Gỡ lỗi USB
+ Cài đặt -> Hệ thống -> Tùy chọn nhà phát triển -> Gỡ lỗi USB
+ Cài đặt -> Khác -> Tùy chọn nhà phát triển -> Gỡ lỗi USB
+ Cài đặt -> Tùy chọn nhà phát triển -> Gỡ lỗi USB
+ Cài đặt -> Hệ thống -> Thông tin (Hoặc thông tin về điện thoại) -> Thông tin phần mềm -> Số hiệu bản tạo (Nhấn liên tục từ 5-7 lần) -> Quay trở lại mục Hệ thống sẽ xuất hiện Tùy chọn nhà phát triển -> Gỡ lỗi USB
  ![tat-go-loi-usb](https://github.com/user-attachments/assets/8426d862-a34a-45f9-81c9-f2be4f04d60f)
  <br/>
  Tiếp đến, bạn tắt luôn Tuỳ chọn nhà phát triển:
Cũng tương tự như tắt gỡ lỗi usb, mỗi điện thoại Android sẽ có cách tắt tùy chọn nhà phát triển khác nhau, bạn cứ vào Menu như ở trên là được:
+ Cài đặt -> Cài đặt bổ sung -> Tùy chọn nhà phát triển
+ Cài đặt -> Hệ thống -> Tùy chọn nhà phát triển
+ Cài đặt -> Khác -> Tùy chọn nhà phát triển
+ Cài đặt -> Tùy chọn nhà phát triển
+ Cài đặt -> Hệ thống -> Thông tin (Hoặc thông tin về điện thoại) -> Thông tin phần mềm -> Số hiệu bản tạo (Nhấn liên tục từ 5-7 lần) -> Quay trở lại mục Hệ thống sẽ xuất hiện Tùy chọn nhà phát triển
  ![tat-tuy-chon-nha-phat-trien](https://github.com/user-attachments/assets/0ba3eaf2-9f9f-4fb8-afd9-a4333ba02c7c)
  # 3/ Dùng phiên bản web của vneid https://vneid.gov.vn/
Đây là cách đơn giản mà an toàn nhất, bạn truy cập vào trang chính thống của  VNeID tại: https://vneid.gov.vn/
Sau đó chọn Đăng nhập, giao diện đăng nhập bạn nhập số CCCD và mật khẩu để truy cập các tính năng của VNeID
![02-06-2024-03-59-53-1](https://github.com/user-attachments/assets/bd4f8d10-39c2-42af-959c-37456b1db72e)

# 4/ Các cách khác để truy cập VneID báo lỗi
Ngoài ra còn một số cách để  sửa lỗi VNeID báo lỗi “Thiết bị của bạn không an toàn…” như:

Cài rom VS Pro phiên bản mới nhất (thấy TeamVS đồn mới update fix lỗi này). Có thể mất một chút phí mua bản quyền rom
Root máy: Sau khi root máy, bạn có thể dùng Magisk module can thiệp chỉnh sửa một chút trong system
Các cách này hơi nguy hiểm cho dân không chuyên, và thao tác sai cách là dễ lỗi máy.  <br/> Mình không khuyến khích các bạn áp dụng, nếu không sẽ bị mất hết dữ liệu
<br/>
Xin cảm ơn: Anonyviet


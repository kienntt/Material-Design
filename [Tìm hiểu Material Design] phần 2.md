# Tìm hiểu Material Design phần 2
  Tiếp nối phần 1 về những nguyên tắc căn bản trong Material Design, phần 2 sẽ nó về style guide trong Material, bao gồm màu sắc, icon, typography,...
## 1.Màu sắc và bảng màu 
  Hệ thống màu của Material sử dụng cách tiếp cận có tổ chức để áp dụng màu cho giao diện người dùng của bạn. Trong hệ thống này, màu chính và màu phụ thường được chọn để thể hiện thương hiệu của bạn. Các biến thể tối và ánh sáng của mỗi màu có thể được áp dụng cho giao diện người dùng của bạn theo các cách khác nhau. <br>
  Bảng màu bắt đầu từ màu chủ đạo và tiếp nối bởi dây màu để tạo nên một palette hoàn chỉnh cho Android, Web và ngay cả iOS. Google khuyến khích bạn nên sử dụng các mã màu 500 làm màu chính trong ứng dụng, còn lại là điểm nhấn.Tất cả màu sắc được thiết kế để đặt hài hòa với nhau.
  
<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1G9utlx7O2-lxBVs5e3BbWq7kbAdXMwOE%2Fcolor-colorsystem-usagepalettes-1.png">

Một ví dụ về bảng màu chính và phụ :
  1. Chỉ màu chính
  2. Chỉ màu phụ
  3. Biến thể ánh sáng và bóng tối


### Màu chính (hay màu chủ đạo)
  Màu chính là màu hiển thị thường xuyên nhất trên màn hình và các thành phần của ứng dụng.Nếu bạn không có màu phụ, màu chính của bạn cũng có thể được sử dụng để làm nổi bật các phần tử.
  Để tạo độ tương phản giữa các phần tử giao diện người dùng, chẳng hạn như phân biệt thanh ứng dụng hàng đầu từ thanh hệ thống, bạn có thể sử dụng các biến thể màu sáng hoặc tối của màu chính trên mỗi phần tử. Bạn cũng có thể sử dụng các biến thể để phân biệt các phần tử trong một thành phần, các biến thể khác nhau như vậy được sử dụng trên vùng chứa nút tác vụ nổi và biểu tượng bên trong nó.
  <br>
  
 [![Watch the video](https://media.giphy.com/media/5YiMQ7FbZs2CK2ylD5/giphy.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1_0WGypORQm2ttQ2EAY6W9Shc41yqsVSn%2Fcolor-colorsystem-schemecreation-primary-baseline-1a-v5.mp4)

### Màu phụ

  Màu phụ cung cấp nhiều cách để phân biệt sản phẩm của bạn. Có màu phụ là tùy chọn và nên được áp dụng một cách tiết kiệm để tạo điểm nhấn chọn các phần của giao diện người dùng của bạn.
  <br>
  Màu phụ có thể áp dụng tốt nhất cho :
  
    1. Nút tác vụ nổi
    2. Điều khiển lựa chọn, như thanh trượt và công tắc
    3. Đánh dấu văn bản đã chọn
    4. Thanh tiến độ
    5. Liên kết và tiêu đề
    
    
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F13Oed330QwZjx6LCPqXlIiWPzVI_fZZh8%2Fcolor-colorsystem-schemecreation-secondary-baseline-1.png">
  
### Top and bottom app bars
 Thanh ứng dụng trên và dưới sử dụng màu chính của ứng dụng. Thanh hệ thống có thể sử dụng biến thể màu tối hoặc sáng của màu chính để tách nội dung hệ thống khỏi nội dung trên thanh ứng dụng. Top bars sử dụng gam màu chính với mã màu 500 trong các bảng màu. Thanh hệ thống nên tối hơn một chút, khoảng mã 700.
 
 <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F14-9xXVeT33twoPmcfkgftEtP3QdRtDpm%2Fcolor-applyingcolorui-bars-differentiating-baseline.png">
  Để nhấn mạnh sự khác biệt giữa thanh ứng dụng và các bề mặt khác, hãy sử dụng màu phụ trên các thành phần lân cận .
  
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1TeQ0O5CvwY52_xe4UTvJG_fqFfBR2F7d%2Fcolor-applyingcolorui-bars-differentiating-reply.png">
  
  Màu chính (màu xanh 700) được sử dụng trên thanh ứng dụng phía dưới này và màu phụ (màu cam 500) được sử dụng trên nút tác vụ nổi.
  
 ### Sử dụng giá trị alpha với hệ màu RGBA
 Hệ màu RGBA được phát triển từ rgb(red, green, blue) thành một hệ màu đi kèm giá trị alpha rgba(red, green, blue, alpha). Giá trị alpha này được đánh số từ 0.0 đến 1.0, tương ứng với độ trong suốt (opacity) từ 0% đến 100%.

Để thể hiện mức độ quan trọng và thứ tự thông tin, bạn nên sử dụng những gam màu xám khác nhau dựa trên giá trị alpha. Giá trị alpha tiêu chuẩn cho text trên nền trắng là 0.87 cho màu đen (#000000). Đối với những đoạn text ít quan trọng hơn, bạn có thể sử dụng giá trị alpha là 0.54 (#000000).

<img src="https://img.idesign.vn/650x-/2015/10/black.jpg">

## 2. Typogaraphy
  Kể từ Android Ice Scream Sandwich, Google đã sử dụng font Roboto. Đây vẫn tiếp tục là tiêu chuẩn cho những ứng dụng chạy trên nền tảng của hãng.
  ### Font weight
  Roboto có 6 kiểu font: Thin, Light, Regular, Medium, Bold, Black tương ứng theo thứ tự từ mảnh nhất đến đậm nhất.
  ### Typography style
  Quá nhiều style và kích thước có thể làm hỏng sự cân bằng trong giao diện. Số lượng kích thước có thể đi cùng một cách hài hòa.

Tất nhiên, màu sắc nên đạt độ tương phản đủ để đọc dễ dàng. Quá ít sẽ làm mờ nội dung nhưng quá nhiều sẽ lại làm cho nội dung trở nên chói sáng và nhức mắt khi đọc. Hãy điều chỉnh và nhìn thật lâu cũng như nhờ đồng nghiệp nhìn thật lâu cho đến khi bạn tìm thấy độ tương phản giúp người dùng cảm thấy dễ chịu nhất.

<img src="https://img.idesign.vn/650x-/2015/10/typo01.jpg">

  ### Độ dài của dòng
  Độ dài tối ưu cho trải nghiệm đọc một đoạn văn trên màn hình là khoảng 60 kí tự/dòng. Đây là yếu tố vô hình nhưng rất quan trọng đối với text.
  
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1XJOxoakBnzdtPjP_jW3CiE2IW4KEv1TO%2Freadability-ideal-linelength.png">
  
  Đối với một dòng văn bản quá dài, người dùng sẽ khó có thể tìm được điểm bắt đầu dòng tiếp theo cũng như có được sự tập trung cao. Dài không phải là điều xấu nếu bạn muốn người dùng đọc lướt một thông tin. Người dùng sẽ tự điều chỉnh theo phương pháp đọc keyword nếu dòng văn bản dài. Tuy nhiên, hãy cố gắng giới hạn dưới 90 kí tự/dòng.

Một dòng văn bản quá ngắn, ngược lại, khiến người dùng phải di chuyển mắt nhiều hơn khi phải liên tục quay về đầu dòng. Một dòng văn bản quá ngắn có thể khiến người dùng cảm thấy áp lực và bỏ qua những chữ cuối cùng.
  


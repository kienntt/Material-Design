# Material-Design
  Material Design (tên mã là Quantum Paper) là một ngôn ngữ thiết kế được phát triển vào năm 2014 bởi Google. 
  Phong cách thiết kế Material Design nhắm đến những đường nét đơn giản, sử dụng nhiều mảng màu đậm nổi bật, các đối tượng đồ họa trong giao diện dường như: “trôi nổi” lên. Ngoài ra, nó còn bao gồm cả những hiệu ứng chuyển động tự nhiên khi các nút, menu hiện diện trên màn hình. Tất cả đều nhằm mang lại cho người dùng trải nghiệm mới mẻ hơn, thú vị hơn và gần giống đời thực hơn.
 
<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1Hfurrx3NHOuac_WreNWxG-2qdKjliIx_%2Fintro-illo-metaphor.png">

## Các yếu tố cơ bản
### 1. Không gian 3D

  Môi trường của material là không gian 3D được thể hiện bằng ánh sáng, bề mặt và đổ bóng.Tất cả các đối tượng đều có trục x,y,z. Trục z vuông góc với mặt phẳng của màn hình, trục z dương mở rộng về phía người xem, mỗi tấm material chiếm một vị trí riêng biệt dọc theo trục z và có độ dày tiêu chuẩn là 1dp.
  
<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-ZUJfcjFIdEVNN28%2Fwhatismaterial-environment-3d.png">

### 2. Ánh sáng và đổ bóng

#### Ánh sáng
Trong môi trường material, ánh sáng ảo chiếu sáng màn hình. Ánh sáng chính tạo bóng đổ sắc nét hơn, được gọi là bóng chính. Ánh sáng xung quanh xuất hiện từ tất cả các góc để tạo ra các bóng mềm, khuếch tán, được gọi là bóng môi trường xung quanh.Trong sự phát triển Android, bóng xảy ra khi nguồn sáng bị chặn bởi các tấm material tại các vị trí khác nhau dọc theo trục z. Trên trang web, bóng được vẽ bởi các thao tác chỉ trên trục Y. Ví dụ dưới đây cho thấy các tấm thẻ với chiều cao 6dp.

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1OUh2ErnYqT5D-NLaoGT7gE6UJoRc0E_x%2Flightshadows-1.png" width="350" alt="accessibility text">

Bóng được đổ bằng ánh sáng chính

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1sVM3CJoX1G8U558BnRJzNlVZR9XEm4US%2Flightshadows-2.png" width="350" alt="accessibility text">

Bóng được đổ bằng ánh sáng xung quanh

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1GX80Wn2YAy2ClCCzmNYY13ThhqL3FQw6%2Flightshadows-3.png" width="350" alt="accessibility text">

Bóng được đổ bằng ánh sáng chính và ánh áng xung quanh

#### Đổ bóng
Bởi vì bóng thể hiện mức độ cao giữa các bề mặt, chúng phải được sử dụng nhất quán trong toàn bộ sản phẩm của bạn.

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1FjW7ZT_MD39eQlLf2hy_hKwCvXmRe4qo%2Fshadowprinciples-do-1.png"  alt="accessibility text">

Kích thước bóng phản ánh độ cao. Các bề mặt ở độ cao cao hơn có các bóng lớn hơn, trong khi các bề mặt ở độ cao thấp hơn có các bóng nhỏ hơn.

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B6xUSjjSulxcLW9wYkdGUUdhTWc%2Fshadowprinciples-do-2.png"  alt="accessibility text">

#### Bóng và chuyển động 
Bóng cung cấp các dấu hiệu hữu ích về hướng di chuyển của bề mặt và khoảng cách giữa các bề mặt đang tăng hay giảm.
<video src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8wSqcLwbhFuNTI1RWpwa1VwV1E%2Fshadowsmotion-do-1a.mp4" width="320" height="200" controls preload></video>
### Chuyển động có ý nghĩa
        
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1kVVLIES2HDnnmqXgAvglbAK8a-oVEEh0%2Fintro-illo-motion.png">


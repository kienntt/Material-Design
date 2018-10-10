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

[![Watch the video](https://j.gifs.com/XoNZyV.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8wSqcLwbhFuNTI1RWpwa1VwV1E%2Fshadowsmotion-do-1a.mp4)

Khi một bề mặt thay đổi hình dạng hoặc tỷ lệ, nhưng độ cao của nó vẫn giữ nguyên, bóng của nó sẽ không thay đổi.

[![Watch the video](https://j.gifs.com/4RN1lJ.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8wSqcLwbhFuYmFPT3hZVjNWREU%2Fshadowsmotion-dont-1a.mp4)

Khi một bề mặt thay đổi độ cao của nó, bóng của nó sẽ thay đổi.

### 3. Các thuộc tính của material
  Material có đặc tính nhất định không thay đổi và những trạng thái vốn có. Hiểu được những đặc tính này sẽ giúp cho bạn thao tác các material theo một cách thức phù hợp với Material Design.

#### Nội dung
  Nội dung được hiển thị dưới mọi hình dạng và màu sắc trên Material. Nội dung không thêm độ dày cho material.
  
  [![Watch the video](https://j.gifs.com/kZpA96.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1xQcc7grFo-KO3yr2ba9XAmKmKasBNwa6%2Fmaterialcontent-shapecolor.mp4)
  
  Vật liệu có thể hiển thị bất kỳ hình dạng và màu sắc nào. Nội dung có thể hoạt động độc lập với Material, nhưng bị giới hạn trong giới hạn của Material

#### Thuộc tính vật lý
  Material là vật rắn . 
  
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1bQO9zhMloD3HtBikFXTYxmTLJ_zFRiIV%2Fmaterialsurfaceproperties-do-physical.png" width="350" alt="accessibility text">
  
  Sự kiện đầu vào chỉ ảnh hưởng đến bề mặt của material.

<img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1Rwp75SKdPmArFS5r8_WQsfAwJYzFsaYc%2Fmaterialsurfaceproperties-dont-passthrough.png" width="350" alt="accessibility text">

  Các sự kiện đầu vào không thể chuyển qua Material.
  
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-SlpSMkpDdVJKSEE%2Fwhatismaterial-properties-physical5.png" width="300" alt="accessibility text">
  <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B8v7jImPsDi-OWpqdE16bkt5LWc%2Fwhatismaterial-properties-physical6.png" width="300" alt="accessibility text">
  Nhiều phần tử Material không thể cùng một lúc trong không gian.
  
  [![Watch the video](https://j.gifs.com/32MzlO.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1ZFe2hECnZAtL0ZdtClzphYkGVT09jLO-%2Fmaterialproperties-clipping.mp4)
  
Vật liệu không thể đi qua vật liệu khác. Ví dụ, một bề mặt vật liệu không thể đi qua bề mặt Vật liệu khác khi thay đổi độ cao.

[![Watch the video](https://j.gifs.com/MQykQ5.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F13eGrsIXeBzDU7l_RFcHotsN8rpWd7kYQ%2Fmaterialsurfaceproperties-plane.mp4)

Material là một "vật chất vô định hình". Nó có thể thay đổi hình dáng kích thước

[![Watch the video](https://j.gifs.com/32Mz2x.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F19__QV-l261owIymJUFARLcV_uyBgwPDj%2Fmaterialproperties-join.mp4)

Material có thể tách thành nhiều phần, cũng có thể gộp lại thành một.

#### Chuyển động

[![Watch the video](https://j.gifs.com/yrKqoP.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1EUy2L0M-LyeNIu24-9GUUP5xvpzj2rjv%2Fmaterialmovement-appear.mp4)

Material có thể được sinh ra hoặc bị phá hủy một cách rất tự nhiên trong bất kì môi trường nào.

[![Watch the video](https://j.gifs.com/N9zlLp.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F192Oe3mMnPtaY3S4AlkQWMRoqtIN6zz4w%2Fmaterialmovement-anyaxis.mp4)

Material có thể di chuyển dọc theo bất kì trục nào.

[![Watch the video](https://j.gifs.com/32MzQx.gif)](https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F11Gpm653O4qC39MSQAyv9sWn16Bm6f4h6%2Fmaterialmovement-z-interaction.mp4)

Sự chuyển động của trục z tiêu biểu cho sự tương tác của người dùng với material




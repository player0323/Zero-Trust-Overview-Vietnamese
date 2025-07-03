<h1 align="center">Zero-Trust-Overview</h1>

<h2 align="center">zero trust overview, what is zero trust, tong quan zero trust</h2>

<p align="center">
  <img src="image/overview.PNG" width="600"/>
</p>
<div align="justify" style="line-height: 1.8; font-size: 16px;">

### Mô hình bảo mật Zero Trust

Mô hình bảo mật Zero Trust là một trong những xu hướng bảo mật hiện đại đang được hầu hết các doanh nghiệp lớn trên toàn cầu áp dụng rộng rãi như Cisco, Microsoft, Fortinet, Palo Alto... Hầu như tất cả các tổ chức bảo mật lớn trên thế giới đều đã triển khai.

Hẳn không khó để các bạn thấy được rằng các cuộc tấn công mạng ngày càng trở nên tinh vi và phức tạp hơn. Trong bối cảnh đó, các tổ chức cũng đã nhận ra rằng việc dựa vào ranh giới an toàn mạng nội bộ không còn đủ để bảo vệ dữ liệu và hệ thống của họ như trước nữa.

Do đó, việc phải xem xét lại cách tiếp cận bảo mật mạng là điều cấp thiết, và điều này dẫn tới sự ra đời của khái niệm **Zero Trust**.

Theo mình tìm hiểu, hiện tại các tổ chức và doanh nghiệp bảo mật lớn vẫn đang tiếp tục nghiên cứu và hoàn thiện mô hình này. Khả năng cao là trong những năm tới, mô hình **Zero Trust** sẽ còn phát triển mạnh, và chúng ta – những người làm trong lĩnh vực bảo mật – sẽ phải làm việc nhiều với nó. Đó cũng là lý do mình chọn chủ đề này để tìm hiểu trong bài hôm nay.

</div>

<p align="center">
  <img src="image/whyneedzerotrust.PNG" width="600"/>
</p>
<div align="justify" style="line-height: 1.8;font-size: 16px;">
  
### Tại sao lại cần Zero Trust

Trước khi công nghệ điện toán đám mây, làm việc từ xa và thiết bị cá nhân trở nên phổ biến, hầu hết các tổ chức đều vận hành trên một nền tảng bảo mật tập trung, 
Mô hình an ninh truyền thống nơi mà mọi thành phần bên trong mạng được mặc định là 'đáng tin cậy', và các mối đe dọa chủ yếu đến từ bên ngoài. Việc xây dựng các lớp phòng thủ tập trung tại biên mạng, như firewall hay hệ thống phát hiện xâm nhập (IDS), từng là tiêu chuẩn trong nhiều năm.

Tuy nhiên, mô hình này đang dần bộc lộ nhiều hạn chế trước sự thay đổi nhanh chóng của môi trường CNTT hiện đại

Theo mô hình bảo mật truyền thống, thường được gọi là "castle-and-moat" (lâu đài và hào nước), dựa trên ý tưởng rằng biên giới mạng là rào cản chính, và mọi thứ bên trong được coi là an toàn. Tuy nhiên, vấn đề của mô hình này là nếu một hacker xâm nhập được vào bên trong, họ có thể truy cập mọi thứ.

Ngược lại, Zero Trust không tin tưởng bất kỳ ai hoặc thiết bị nào, dù ở bên trong hay bên ngoài mạng. Mỗi yêu cầu truy cập đều phải được xác minh, giúp giảm thiểu rủi ro từ các cuộc tấn công nội bộ, như được ghi nhận.

</div>
<p align="center">
  <img src="image/whyneedzerotrust2.PNG" width="600"/>
</p>
<div align="justify" style="line-height: 1.8; font-size:16px;">
Trong thời đại ngày nay, nhân viên có thể ở bất kỳ đâu, từ quán cà phê đến phòng khách tại nhà. Họ sử dụng đám mây để lưu trữ tài liệu, truy cập ứng dụng, và thậm chí mang theo thiết bị cá nhân – laptop, điện thoại – để làm việc. Điều này làm mờ đi ranh giới mạng truyền thống mà chúng ta từng dựa vào, như tường lửa hay văn phòng cố định.
  
Điều đáng lo hơn là dữ liệu của chúng ta giờ đây không còn nằm yên trong máy chủ tại công ty. Nó phân tán khắp nơi – trên các dịch vụ lưu trữ như Google Drive, Microsoft Azure, hay thậm chí trong email cá nhân. Khi biên giới mạng không còn rõ ràng và dữ liệu trôi nổi như vậy, liệu chúng ta có thể tiếp tục tin tưởng rằng những gì bên trong hệ thống là an toàn? Câu trả lời là: Không.

Một vấn đề lớn hơn của mô hình cũ là lateral movement, tức là di chuyển ngang. Một khi mà kẻ tấn công nó lọt được vào bên trong rồi ấy thì chúng có thể tự do đi lại từ phòng này sang phòng khác để truy cập các tài nguyên quan trọng khác một cách khá là dễ dàng.

Đây chính là lý do Zero Trust ra đời – để bảo vệ từng mảnh dữ liệu, từng thiết bị, bất kể chúng ở đâu
– với triết lý cốt lõi là: **"🔐 no trust, Always Verify -Không tin tưởng, luôn xác minh "

  
</div>
<p align="center">
  <img src="image/whyneedzerotrust3.PNG" width="600"/>
</p>

<p align="center">
  <img src="image/whatiszerotrust.PNG" width="600"/>
</p>

<p align="center">
  <img src="coreprinciple.PNG" width="600"/>
</p>

<p align="center">
  <img src="image/implementation.png" width="600"/>
</p>

<p align="center">
  <img src="image/implementation2.png" width="600"/>
</p>

<p align="center">
  <img src="image/benefit.png" width="600"/>
</p>

<p align="center">
  <img src="image/ztnaoverrdvpn.png" width="600"/>
</p>

<p align="center">
  <img src="image/limitation.png" width="600"/>
</p>

<p align="center">
  <img src="image/currentstateofzerotrustimplementations.PNG" width="600"/>
</p>

<p align="center">
  <img src="image/feature.png" width="600"/>
</p>

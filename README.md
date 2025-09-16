<h1 align="center">Zero-Trust-Overview</h1>
<h2 align="center">Zero Trust Overview – Tổng quan về Zero Trust</h2>

<p align="center">
  <img src="image/overview.PNG" width="600"/>
</p>

---

## Mô hình bảo mật Zero Trust

Mô hình bảo mật **Zero Trust** là một trong những xu hướng bảo mật hiện đại đang được hầu hết các doanh nghiệp lớn trên toàn cầu áp dụng rộng rãi như Cisco, Microsoft, Fortinet, Palo Alto... Hầu như tất cả các tổ chức bảo mật lớn trên thế giới đều đã triển khai.

Các cuộc tấn công mạng ngày càng tinh vi và phức tạp hơn. Việc dựa vào ranh giới an toàn mạng nội bộ truyền thống không còn đủ để bảo vệ dữ liệu và hệ thống. Chính vì vậy, mô hình **Zero Trust** ra đời với triết lý:  

> **“Never trust, always verify – Không tin tưởng, luôn xác minh.”**

---

<p align="center">
  <img src="image/whyneedzerotrust.PNG" width="600"/>
</p>

## Tại sao lại cần Zero Trust?

Trước đây, mô hình an ninh truyền thống thường dựa trên khái niệm **castle-and-moat** (lâu đài và hào nước). Tất cả những gì bên trong được mặc định là an toàn, còn bên ngoài là nguy hiểm. Tuy nhiên, nếu hacker vượt qua được biên giới bảo mật, họ có thể tự do di chuyển bên trong hệ thống.

Zero Trust thay đổi hoàn toàn cách tiếp cận: **Không tin tưởng bất kỳ ai hoặc thiết bị nào, dù ở bên trong hay bên ngoài mạng.**  
Mỗi yêu cầu truy cập đều phải được xác minh liên tục.

<p align="center">
  <img src="image/whyneedzerotrust2.PNG" width="600"/>
</p>

Ngày nay, nhân viên làm việc từ xa, sử dụng thiết bị cá nhân, dữ liệu phân tán trên nhiều nền tảng (Google Drive, Azure, email cá nhân...). Điều này khiến ranh giới bảo mật truyền thống biến mất.  
Zero Trust đảm bảo dữ liệu và thiết bị được bảo vệ mọi lúc, mọi nơi.

> **Vấn đề lớn nhất của mô hình cũ:** *Lateral Movement* – kẻ tấn công có thể di chuyển ngang bên trong hệ thống sau khi xâm nhập thành công.

---

<p align="center">
  <img src="image/whatiszerotrust.PNG" width="600"/>
</p>

## Zero Trust là gì?

Zero Trust không chỉ là công nghệ, mà là một **triết lý bảo mật**.  
Mục tiêu: **Chỉ cho phép đúng người – đúng quyền – đúng dữ liệu – đúng lý do.**

Điểm quan trọng:  
- Người dùng dù trong văn phòng, ở nhà hay quán cà phê đều bị xem là có thể gây hại cho đến khi chứng minh được an toàn.  
- Sau khi xác thực, hệ thống vẫn tiếp tục kiểm tra và giới hạn quyền truy cập dựa trên ngữ cảnh.

---

<p align="center">
  <img src="image/coreprinciple.PNG" width="600"/>
</p>

## Nguyên tắc cốt lõi của Zero Trust

1. **Xác minh liên tục**: Kiểm tra danh tính, thiết bị, vị trí, hành vi người dùng.  
2. **Quyền truy cập tối thiểu (Least Privilege)**: Người dùng chỉ được cấp đúng quyền cần thiết.  
3. **Quản lý dựa trên chính sách (RBAC/ABAC)**: Phân quyền chi tiết theo vai trò và ngữ cảnh.  
4. **Giả định đã bị xâm nhập**: Thiết kế hệ thống luôn trong trạng thái cảnh giác, giám sát và phân đoạn để hạn chế ảnh hưởng.  

---

<p align="center">
  <img src="image/implementation.png" width="600"/>
</p>

## Triển khai Zero Trust

Việc triển khai Zero Trust yêu cầu kết hợp giữa **kỹ thuật và quy trình tổ chức**:  
- **Đánh giá & kiểm kê**: Xác định tài sản quan trọng, thiết bị, lỗ hổng.  
- **Xác định ranh giới tin cậy**: Phân đoạn mạng (micro-segmentation).  
- **Kiểm soát truy cập & xác thực**: MFA, sinh trắc học, Azure AD, Okta, Ping Identity.  
- **Giám sát & phân tích liên tục**: Splunk, Suricata, Microsoft Defender.  

---

<p align="center">
  <img src="image/benefit.png" width="600"/>
</p>

## Lợi ích

- Giảm nguy cơ **truy cập trái phép** và **lateral movement**.  
- Tăng khả năng **hiển thị và kiểm soát lưu lượng**.  
- Giúp tổ chức quản lý tài nguyên an toàn và linh hoạt hơn.

---

<p align="center">
  <img src="image/limitation.png" width="600"/>
</p>

## Hạn chế

- **Chi phí cao**: phần mềm, phần cứng, nhân sự, thời gian chuyển đổi.  
- **Độ phức tạp**: yêu cầu đồng bộ nhiều hệ thống (MFA, IAM, giám sát, phân vùng...).  
- **Ảnh hưởng hiệu suất**: tăng độ trễ, gây khó chịu cho người dùng.  
- **Thiếu chuẩn quốc tế thống nhất**: mỗi nhà cung cấp có một mô hình riêng → khó tích hợp.

---

<p align="center">
  <img src="image/currentstateofzerotrustimplementations.PNG" width="600"/>
</p>

## Thực trạng & xu hướng

- Khảo sát cho thấy nhiều tổ chức đã và đang triển khai Zero Trust, nhưng gặp khó khăn khi tích hợp.  
- Quy mô thị trường Zero Trust tăng nhanh: từ dưới **10 tỷ USD (2017)** lên **36.9 tỷ USD (2024)**.  
- Tốc độ tăng trưởng kép (CAGR) **16.6%** cho thấy Zero Trust là xu hướng tất yếu trong bảo mật.

---

## 📌 Tổng kết

- **Zero Trust không chỉ là công nghệ mà là một chiến lược bảo mật toàn diện.**  
- Triết lý cốt lõi: *“Không tin tưởng bất kỳ ai, luôn xác minh mọi thứ.”*  
- Đem lại khả năng bảo vệ mạnh mẽ trước các mối đe dọa hiện đại, đặc biệt trong bối cảnh **làm việc từ xa – dữ liệu phân tán – cloud computing**.  
- Tuy nhiên, triển khai Zero Trust **không hề đơn giản**: chi phí cao, phức tạp, ảnh hưởng đến hiệu suất nếu không được thiết kế đúng.  
- Trong tương lai, Zero Trust sẽ trở thành **chuẩn mực bảo mật** mà mọi doanh nghiệp đều phải tiếp cận.  

---

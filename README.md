<h1 align="center">Zero-Trust-Overview</h1>
<h2 align="center">Zero Trust Overview – What is Zero Trust – Tổng quan Zero Trust</h2>

<p align="center">
  <img src="image/overview.PNG" width="600"/>
</p>

---

## 🔐 Mô hình bảo mật Zero Trust

Mô hình bảo mật **Zero Trust** là một trong những xu hướng bảo mật hiện đại đang được hầu hết các doanh nghiệp lớn trên toàn cầu áp dụng như **Cisco, Microsoft, Fortinet, Palo Alto...**  

Hẳn không khó để các bạn thấy được rằng các cuộc tấn công mạng ngày càng trở nên tinh vi và phức tạp hơn. Trong bối cảnh đó, các tổ chức cũng đã nhận ra rằng việc dựa vào ranh giới an toàn mạng nội bộ **không còn đủ** để bảo vệ dữ liệu và hệ thống của họ như trước nữa.  

👉 Do đó, cần xem xét lại cách tiếp cận bảo mật – và điều này dẫn tới sự ra đời của **Zero Trust**.  

Theo mình tìm hiểu, các tổ chức bảo mật lớn vẫn đang tiếp tục nghiên cứu và hoàn thiện mô hình này. Trong những năm tới, Zero Trust chắc chắn sẽ phát triển mạnh và trở thành trọng tâm với tất cả chúng ta.

---

<p align="center">
  <img src="image/whyneedzerotrust.PNG" width="600"/>
</p>

## ❓ Tại sao lại cần Zero Trust

Trước khi công nghệ điện toán đám mây, làm việc từ xa và thiết bị cá nhân trở nên phổ biến, hầu hết các tổ chức đều vận hành trên một nền tảng bảo mật tập trung, Mô hình an ninh truyền thống nơi mà mọi thành phần bên trong mạng được mặc định là 'đáng tin cậy', và các mối đe dọa chủ yếu đến từ bên ngoài. Việc xây dựng các lớp phòng thủ tập trung tại biên mạng, như firewall hay hệ thống phát hiện xâm nhập (IDS), từng là tiêu chuẩn trong nhiều năm.

Tuy nhiên, mô hình này đang dần bộc lộ nhiều hạn chế trước sự thay đổi nhanh chóng của môi trường CNTT hiện đại

Theo mô hình bảo mật truyền thống, thường được gọi là "castle-and-moat" (lâu đài và hào nước), dựa trên ý tưởng rằng biên giới mạng là rào cản chính, và mọi thứ bên trong được coi là an toàn. Tuy nhiên, vấn đề của mô hình này là nếu một hacker xâm nhập được vào bên trong, họ có thể truy cập mọi thứ.

Ngược lại, Zero Trust không tin tưởng bất kỳ ai hoặc thiết bị nào, dù ở bên trong hay bên ngoài mạng. Mỗi yêu cầu truy cập đều phải được xác minh, giúp giảm thiểu rủi ro từ các cuộc tấn công nội bộ, như được ghi nhận.

⚡ **Zero Trust khác biệt ở chỗ:**  
Không tin tưởng bất kỳ ai, bất kỳ thiết bị nào (dù trong hay ngoài mạng). Mỗi yêu cầu truy cập đều phải **được xác minh lại**.  

> "No trust, Always Verify – Không tin tưởng, luôn xác minh"

---

<p align="center">
  <img src="image/whyneedzerotrust2.PNG" width="600"/>
</p>

### 📌 Thực trạng hiện nay

Trong thời đại ngày nay, nhân viên có thể ở bất kỳ đâu, từ quán cà phê đến phòng khách tại nhà. Họ sử dụng đám mây để lưu trữ tài liệu, truy cập ứng dụng, và thậm chí mang theo thiết bị cá nhân – laptop, điện thoại – để làm việc. Điều này làm mờ đi ranh giới mạng truyền thống mà chúng ta từng dựa vào, như tường lửa hay văn phòng cố định.
Điều đáng lo hơn là dữ liệu của chúng ta giờ đây không còn nằm yên trong máy chủ tại công ty. Nó phân tán khắp nơi – trên các dịch vụ lưu trữ như Google Drive, Microsoft Azure, hay thậm chí trong email cá nhân. Khi biên giới mạng không còn rõ ràng và dữ liệu trôi nổi như vậy, liệu chúng ta có thể tiếp tục tin tưởng rằng những gì bên trong hệ thống là an toàn? Câu trả lời là: Không.

Vấn đề lớn nhất là **di chuyển ngang (lateral movement)**. Một khi bị xâm nhập, kẻ tấn công có thể dễ dàng di chuyển và khai thác các tài nguyên khác.  

👉 Đây chính là lý do **Zero Trust** ra đời.  

---

<p align="center">
  <img src="image/whyneedzerotrust3.PNG" width="600"/>
</p>

### 📊 Thống kê (IBM 2024 Insider Threat Report)

- **83% tổ chức** báo cáo ít nhất 1 vụ tấn công nội bộ trong năm 2024.  
- Tổ chức bị **11–20 vụ tấn công nội bộ** tăng từ **4% (2023)** → **21% (2024)**.  

📌 Điều này phản ánh: **nguy cơ nội bộ tăng mạnh**, buộc tổ chức phải thay đổi cách bảo vệ.  

---

<p align="center">
  <img src="image/whatiszerotrust.PNG" width="600"/>
</p>

## 🔎 Vậy thì Zero Trust là gì?

- Zero Trust **không chỉ là công nghệ**, mà là **thay đổi tư duy bảo mật**.  
- Từ “xây pháo đài bất khả xâm phạm” → chuyển sang “xác minh liên tục”.  
- Mục tiêu: **đúng người – đúng quyền – đúng dữ liệu – đúng lý do**.  
- Nguyên tắc: *Never trust, always verify*.  

---

<p align="center">
  <img src="image/coreprinciple.PNG" width="600"/>
</p>

## ⚙️ Nguyên tắc cốt lõi

1. **Xác minh liên tục** (Continuous Verification)  
   - Kiểm tra: danh tính, thiết bị, vị trí, hành vi.  
   - Áp dụng **MFA, posture check, phân tích hành vi**.  

2. **Quyền truy cập tối thiểu (Least Privilege)**  
   - Chỉ cấp quyền cần thiết.  
   - RBAC, ABAC để kiểm soát chi tiết.  

3. **Giả định đã bị xâm nhập (Assume Breach)**  
   - Thiết kế hệ thống như thể đã có mối đe dọa.  
   - **Segmentation** để hạn chế thiệt hại.  

---

<p align="center">
  <img src="image/implementation.png" width="600"/>
</p>

## 🚀 Triển khai Zero Trust

- **Đánh giá & kiểm kê**: tài sản, thiết bị, dữ liệu.  
- **Xác định ranh giới tin cậy**: chia mạng thành vùng nhỏ.  
- **Kiểm soát truy cập & xác thực**: MFA, sinh trắc học, chính sách context-aware.  
- **Giám sát & phân tích liên tục**: AI/ML, SIEM, EDR, IDS.  

📌 Công cụ tham khảo:  
- Google BeyondCorp, Microsoft AIP, Zscaler ZPA  
- Azure AD, Okta, Ping Identity  
- Splunk, Suricata, Microsoft Defender  

---

<p align="center">
  <img src="image/benefit.png" width="600"/>
</p>

## ✅ Lợi ích

- Giảm thiểu rủi ro **xâm nhập và di chuyển ngang**.  
- **Tăng khả năng quan sát** nhờ micro-segmentation.  
- Nâng cao khả năng kiểm soát truy cập và dữ liệu.  

---

<p align="center">
  <img src="image/limitation.png" width="600"/>
</p>

## ⚠️ Hạn chế & Thách thức

- **Chi phí cao** (hạ tầng, nhân sự, thời gian).  
- **Trải nghiệm người dùng giảm** (MFA, posture check phức tạp).  
- **Quản lý khó khăn** (thiếu chuẩn quốc tế, nhiều vendor định nghĩa khác nhau).  
- **Xung đột lợi ích**: bảo mật vs hiệu năng.  

---

<p align="center">
  <img src="image/currentstateofzerotrustimplementations.PNG" width="600"/>
</p>

## 📈 Xu hướng và thị trường

- Quy mô thị trường Zero Trust **dưới 10 tỷ USD (2017)** → **36.9 tỷ USD (2024)**.  
- CAGR: **16.6%/năm** → thuộc top tăng trưởng cao trong ngành an ninh mạng.  
- Dự báo 2025–2030: **tiếp tục tăng trưởng mạnh mẽ**.  

---

## 📝 Tổng kết

Zero Trust **không phải là một sản phẩm**, mà là **một chiến lược bảo mật toàn diện**.  
Nó yêu cầu:  
- Sự phối hợp giữa **công nghệ – quy trình – con người**.  
- Đầu tư vào **xác thực đa yếu tố, segmentation, giám sát liên tục, AI/ML**.  
- Thay đổi tư duy từ “tin tưởng mặc định” sang “luôn xác minh”.  

👉 Trong tương lai gần, **Zero Trust sẽ trở thành tiêu chuẩn bảo mật bắt buộc**, đặc biệt với các tổ chức chuyển đổi số, làm việc từ xa, và quản lý dữ liệu phân tán.  

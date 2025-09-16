<div align="justify">
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

Zero Trust nó không chỉ là **công nghệ**, nó là một sự thay đổi trong cách suy nghĩ về bảo mật.

Mình chuyển từ việc cố xây một cái pháo đài bất khả xâm phạm sang một mô hình linh hoạt hơn, nơi mà mọi truy cập đều phải được kiểm tra liên tục, không có tin tưởng mặc định.

Mục tiêu thực tế của nó là chỉ cho phép đúng người dùng có đúng quyền truy cập vào đúng dữ liệu vì đúng lý do đó. 

Cái câu khẩu hiệu của nó là không bao giờ tin tưởng, luôn xác minh, never trust, always verify. Bất kể người dùng đang ở đâu, dù là trong văn phòng, ngồi quán cà phê, hay ở nhà đều bị đối xử như nhau. Đều bị coi là có khả năng gây hại cho đến khi chứng minh được là mình an toàn. Phải liên tục chứng minh danh tính và quyền truy cập mình.

Điều này có nghĩa là sau khi một người dùng hoặc thiết bị đã được xác thực (chứng minh được họ là ai), hệ thống sẽ thực hiện ủy quyền để xác định những tài nguyên cụ thể nào mà họ được phép truy cập và họ có thể làm gì với những tài nguyên đó

---

## Để đạt được những điều này , Zerotrust đặt ra một vài khái niệm trọng tâm:

<p align="center">
  <img src="image/coreprinciple.PNG" width="600"/>
</p>

## ⚙️ Nguyên tắc cốt lõi

1. **Xác minh liên tục** (Continuous Verification)
   
   - Kiểm tra: danh tính, thiết bị, vị trí, hành vi.  
   - Áp dụng **MFA, posture check, phân tích hành vi**.
     
Ví dụ: Mỗi khi một thiết bị hoặc người dùng yêu cầu truy cập vào tài nguyên, hệ thống sẽ khởi động quá trình kiểm tra theo từng bước sau: ví dụ như là thông tin đăng nhập, xác thực đa yếu tố, rồi kiểm tra cả tình trạng sức khỏe của cái thiết bị đang dùng để truy cập nữa. Hệ điều hành có mới nhất không? Có cài phần mình diệt virus không? Nó có đang chạy bình thường không? rồi vị trí địa lý, thời gian truy cập, hành vi người dùng có bất thường không?

Và quan trọng nhất là việc kiểm tra này nó diễn ra liên tục cho mỗi một yêu cầu truy cập tài nguyên chứ không phải chỉ một lần lúc đầu. Mỗi lần anh muốn mở một file, truy cập một ứng dụng, hệ thống lại đánh giá lại xem anh có còn đủ an toàn và có đúng quyền không. Nếu hệ thống phát hiện dấu hiệu bất thường (ví dụ như đăng nhập từ vị trí khác thường, thiết bị chưa từng đăng nhập trước đó), nó sẽ yêu cầu người dùng xác thực lại qua các phương pháp như MFA.

2. **Quyền truy cập tối thiểu (Least Privilege)**
   
   - Chỉ cấp quyền cần thiết.  
   - RBAC, ABAC để kiểm soát chi tiết.  

Hệ thống quản lý truy cập dựa trên vai trò (RBAC): Ví dụ như bạn chỉ cần đọc tài liệu thì bạn chỉ được phép đọc mà không có bất kỳ quyền chỉnh sữa hay xóa gì. Hoặc là một ví dụ rất phổ biến là trong việc cấp quyền cho các thành viên, vì người quản trị cảm thấy phức tạp khi phải cấp từng quyền cho từng người thì cấp thẳng quyền admin luôn cho nhanh. Đây là một hành động cực kỳ nguy hiểm gấy mất an toàn thông tin cho tổ chức.

Hệ thống truy cập dựa trên chính sách (ABAC): Định nghĩa: Quyết định cấp quyền dựa trên các thuộc tính (attribute) của người dùng, thiết bị, và ngữ cảnh truy cập (ví dụ: thời gian, vị trí, thiết bị, mức độ rủi ro). Ví dụ: Một chính sách có thể quy định rằng chỉ cho phép truy cập vào dữ liệu nhạy cảm từ các thiết bị đã đăng ký và được kiểm tra bảo mật, trong giờ hành chính làm việc từ 8h-16h.

3. **Giả định đã bị xâm nhập (Assume Breach)**
   
   - Thiết kế hệ thống như thể đã có mối đe dọa.  
   - **Segmentation** để hạn chế thiệt hại.  

Điều này nó buộc chúng ta phải làm hai việc chính. Một là phải phân đoạn segmentation mạng và người dùng thành các khu vực nhỏ độc lập với nhau. Để nếu một khu vực bị tấn công ấy thì thiệt hại nó sẽ được giới hạn trong khu vực đó thôi. không lan ra toàn bộ hệ thống. Cách tiếp cận này đảm bảo rằng ngay là khi một phân đoạn bị vi phạm, khả năng di chuyển ngang qua mạng của kẻ tấn công sẽ bị hạn chế đi rất nhiều.

---

<p align="center">
  <img src="image/implementation.png" width="600"/>
</p>

## 🚀 Triển khai Zero Trust

- **Đánh giá & kiểm kê**: tài sản, thiết bị, dữ liệu.
  
-> Tiến hành đánh giá kỹ lưỡng cơ sở hạ tầng mạng hiện có, xác định các tài sản quan trọng và các lỗ hổng tiềm ẩn. Bước này liên quan đến việc tạo một bản kiểm kê toàn diện về tất cả các thiết bị, người dùng và tài nguyên
  
- **Xác định ranh giới tin cậy**: chia mạng thành vùng nhỏ.

-> Xác định danh giới tin cậy trong mạng. Phân chia mạng thành các vùng nhỏ hơn, an toàn hơn. Những ranh giới này có thể dựa trên các yếu tố như hệ thống phân cấp phòng ban, độ nhạy cảm của dữ liệu hoặc vai trò của người dùng, kiểm soát truy cập và xác thực. Triển khai các cơ chế xác thực nâng cao, chẳng hạn như xác thực đa yếu tố và sinh chắc học để tăng cường kiểm soát truy cập
  
- **Kiểm soát truy cập & xác thực**: MFA, sinh trắc học, chính sách context-aware.

-> Kiểm soát truy cập và xác thực. Triển khai các cơ chế xác thực nâng cao, chẳng hạn như xác thực đa yếu tố và sinh chắc học để tăng cường kiểm soát truy cập. Ngoài ra, đưa ra các chính sách truy cập chi tiết dựa trên khái niệm list privilege, đảm bảo người dùng và thiết bị chỉ có thể truy cập các tài nguyên cần thiết cho nhiệm vụ của họ

- **Giám sát & phân tích liên tục**: AI/ML, SIEM, EDR, IDS.  

->Giám sát và phân tích liên tục. Triển khai các công cụ giám sát có thể theo dõi và phân tích hành vi của người dùng. Lưu lượng truy cập mạng và tình trạng thiết bị. Các thuật toán AI có thể giúp phát hiện các hoạt động bất thường và kích hoạt cảnh báo, đảm bảo phản ứng nhanh với các vi phạm bảo mật

📌 Công cụ tham khảo:  
- Google BeyondCorp, Microsoft AIP, Zscaler ZPA  
- Azure AD, Okta, Ping Identity  
- Splunk, Suricata, Microsoft Defender  

---

<p align="center">
  <img src="image/benefit.png" width="600"/>
</p>

## ✅ Lợi ích

Dựa trên bộ nguyên tắc và quyết cách triển khai của mình, việc áp dụng phương pháp Zerotrust mang lại một số lợi thế so với các mô hình bảo mật truyền thống. 

Thứ nhất, Zerotrust tăng cường khả năng bảo mật tổng thể bằng cách giả định rằng tất cả các thiết bị hoặc người dùng trong mạng đều không được tin tưởng. Bằng cách liên tục xác thực người dùng và thiết bị, nguy cơ truy cập trái phép hoặc di chuyển ngang sẽ giảm đáng kể.

Thứ hai, Zero trust. cho phép tăng khả năng hiển thị và kiểm soát lưu lượng mạng. Bằng cách phân đoạn mạng và sử dụng micro segmentation, các tổ chức có thể giám sát và quản lý tài nguyên mạng tốt hơn, hạn chế ảnh hưởng đến hệ thống khi bị tấn công.

---

<p align="center">
  <img src="image/limitation.png" width="600"/>
</p>

## ⚠️ Hạn chế & Thách thức

Tuy nhiên, mọi hình bảo mật đều có những khiếm khuyết. Dù Zero Trust mang lại những lợi ích đầy hứa hẹn, song việc triển khai nó cũng tiềm ẩn nhiều vấn đề nan giải. 

Zero trust không phải là chỉ cài phần mềm và cấu hình là xong mà nó là một mô hình kết hợp nhiều thành phần như định danh, xác thực đa yếu tố (MFA), kiểm soát truy cập theo ngữ cảnh, giám sát liên tục và phân vùng vi mô (micro-segmentation) ngoài ra còn cần hệ thống đồng bộ những dịch vụ này nữa. Chính vì sự kết hợp phức tạp và yêu cầu thay đổi toàn diện kiến trúc bảo mật, việc triển khai Zero Trust thường kéo theo chi phí rất lớn — bao gồm cả phần cứng, phần mềm, nhân sự kỹ thuật và thời gian chuyển đổi. 

Thì cũng vấn đề trên Zero Trust là một mô hình yêu cầu sự phối hợp chặt chẽ giữa nhiều thành phần bảo mật khác nhau. Tuy nhiên, trong thực tế, nhiều tổ chức triển khai gặp khó khăn vì đội ngũ bảo mật thiếu kinh nghiệm trong việc tích hợp toàn cục các hệ thống như xác thực, phân quyền, giám sát và phân vùng mạng. Điều này dẫn đến việc cấu hình rời rạc, thiếu tính nhất quán và dễ gây ra sai sót trong kiểm soát truy cập, làm giảm hiệu quả tổng thể của Zero Trust. 

Zero Trust yêu cầu xác minh liên tục từng kết nối, từng yêu cầu truy cập, bất kể người dùng hay thiết bị đang ở trong hay ngoài mạng nội bộ. Việc áp dụng các lớp bảo vệ như xác thực đa yếu tố (MFA), kiểm tra thiết bị, phân tích hành vi và định tuyến qua proxy ZTNA khiến quá trình truy cập trở nên phức tạp và mất thời gian hơn. Điều này có thể gây tăng độ trễ, ảnh hưởng đến trải nghiệm người dùng, đặc biệt trong các môi trường cần hiệu năng cao hoặc hệ thống thời gian thực. VD: hệ thống giao dịch tài chính Một vài mili giây delay có thể khiến mất dữ liệu hoặc giảm hiệu suất toàn hệ thống. 

Về mặt nhân viên : khi mà mọi người phải xác thực nhiều lần, nhiều bước liên tục mà lại còn gặp lỗi
  - Không quen MFA, bị từ chối truy cập do posture check => khó chịu. •
  - Nếu không được truyền thông rõ ràng, sẽ quay sang phá hoặc tìm cách lách.
    
Về mặt lãnh đạo / quản lý
  - Thường muốn “an toàn, nhưng không ảnh hưởng hiệu suất” – mâu thuẫn với triết lý Zero Trust.
  - Không hiểu độ sâu kỹ thuật => không cấp ngân sách đầy đủ, triển khai nửa vời.

Dù được nhiều tổ chức và nhà cung cấp quảng bá, Zero Trust hiện vẫn chưa có một bộ chuẩn kỹ thuật quốc tế nào thống nhất và bắt buộc. Mỗi nhà cung cấp đưa ra một định nghĩa, kiến trúc và giải pháp riêng, dẫn đến tình trạng khó tích hợp, thiếu tính tương thích và khó đánh giá hiệu quả toàn diện. Điều này khiến các tổ chức dễ triển khai theo kiểu mong manh , không nhất quán, và gặp khó khăn khi mở rộng hoặc chuyển đổi sang giải pháp khác trong tương lai. 

Zero trust hiện đại, trong tương lai cần đảm bảo sự cân bằng giữa bảo mật và trải nghiệm người dùng khi sử dụng Zerotrust là vấn đề cấp thiết đối với doanh nghiệp nhằm ngăn chặn những tác động tiêu cực của mô hình bảo mật này đến năng suất và quy trình làm việc của đội ngũ nhân sự

---

<p align="center">
  <img src="image/currentstateofzerotrustimplementations.PNG" width="600"/>
</p>
**Khảo sát mức độ triển khai của các công ty đầu năm 2025**
## 📈 Xu hướng và thị trường

<p align="center">
  <img src="image/feature.png" width="600"/>
</p>

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
</div>

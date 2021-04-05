---
title: Cách xài ReqView - Hướng dẫn mì ăn liền
categories: software-requirements tutorial
---

> Đây là assigment cho môn PTVQLYCPM.


## Danh sách các công cụ quản lý yêu cầu

Một số phần mềm thông dụng hỗ trợ quản lý yêu cầu:

- [IBM Rational RequisitePro][ibm-rational-requisitepro]. 
- [Jama Connect][jama-connect]. 
- [Modern Requirements][modern-requirements]. 
- [Accompa][accompa]. 
- [ReqSuite RM][reqsuite-rm].
- [Blueprint][blueprint].
- [ReqChecker][reqchecker]. 
- [Azure DevOps Server][azure-devops-server]. 
- [Requirements Hub][requirements-hub]. 

Các công cụ trên hỗ trợ rất nhiều quy trình, tính năng tùy chỉnh, bảo mật, đa ngôn ngữ, nền tảng, trực quan hóa, tương tác, … nên hầu như có tính phí và yêu cầu đăng ký tài khoản phức tạp. Dưới đây là một số công cụ đơn giản cho phép người dùng sử dụng trial miễn phí:

- [ReqView][reqview].
- [VNT-Software][vnt-software].
- [codeBeamer ALM][codebeamer-alm].
- [Visure Requirements][visure-requirements].
- [Jira Software][jira-software].
- [Enterprise Tester][enterprise-tester].
- [Intland Retina][intland-retina].

Phần demo sau sẽ sử dụng công cụ ReqView trên môi trường Windows 10 để thực hiện một số chức năng quản lý yêu cầu, nhờ những thiết lập đơn giản, giao diện trực quan, bao gồm mẫu tài liệu, hỗ trợ nhiều định dạng và tiêu chuẩn.

---
## **Hướng dẫn sử dụng ReqView sương sương**

### **Setup**

Đầu tiên, ta đăng ký tài khoản với email [tại đây][register].

Sau đó ta sẽ nhận được email ứng với tài khoản đã đăng ký với nội dung gồm [link tải file setup][setup] và file `license.lic` để kích hoạt bản quyền dùng thử trong vòng 14 ngày với các tính năng PRO. Ta tiến hành download 2 file này.

Sau khi download xong, chạy file ReqViewSetup.exe để cài đặt. Cài đặt xong, ta mở chương trình lên.

![Hình bị lỗi huhu :<][img2]

Màn hình chào mừng hiện ra, bấm “Accept & Continue”. Sau đó, điền một số thông tin cá nhân cơ bản rồi ấn “Agree”. 
 
![Hình bị lỗi huhu :<][img2]

ReqView có sẵn một project demo để làm mẫu cho những người mới bắt đầu. Chúng ta sẽ sử dụng project này để làm quen với phần mềm bằng cách ấn vào “Open Example”.
 
![Hình bị lỗi huhu :<][img3]

![Hình bị lỗi huhu :<][img4]

Đây là giao diện sử dụng chính của ReqView với menu bên trái là project hiện tại với các documents. Menu chính giữa là thông tin chi tiết của project. Còn menu bên phải hiển thị các tính năng bổ sung.

Trước khi bắt đầu, ta phải kích hoạt bản quyền của phần mềm bằng cách vào Help > Activate License. Cửa sổ browse hiện ra và ta browse tới file license.lic đã download trước đó. Đợi 3 giây cho phần mềm kiểm tra là ta có thể sử dụng thoải mái các tính năng trong vòng 14 ngày.

![Hình bị lỗi huhu :<][img5]
 
### **Thêm yêu cầu**
#### **Yêu cầu của stakeholder**
 
![Hình bị lỗi huhu :<][img6]

Từ thanh menu góc trên, ta chọn Project > Add Document.

![Hình bị lỗi huhu :<][img7]
 
Sau đó check vào `Predefined Template`. Bên dưới mục "DEMO", ta chọn `Stakeholder Requirements Specification (StRS)` từ danh sách xổ xuống. Sau đó nhấn `OK`.

![Hình bị lỗi huhu :<][img8]
 
Từ menu trái, chọn `StRS`. Sau đó, cuộn chuột ở menu giữa để kéo xuống đến phần “User requirements”. Nhấn vào sẽ thấy hiện ra menu nhỏ bên dưới. Click vào dấu mũi tên như trong hình để thêm yêu cầu.

![Hình bị lỗi huhu :<][img9]
 
Sau đó, điền đầy đủ thông tin về yêu cầu. Ta có thể nhấn vào ở cột Type ở hàng tương ứng để chọn loại cho yêu cầu như *functional requirement, non-functional requirement, …* Tương tự ta có thể bổ sung thông tin ở các cột **Source, Rationale, Priority, Status** nếu muốn.

![Hình bị lỗi huhu :<][img10]
 
#### **Yêu cầu phần mềm**

Lặp lại các bước tương tự như trên: từ menu trái, chọn `SRS`. Sau đó, cuộn chuột ở menu giữa để kéo xuống đến phần “Requirements”. Nhấn vào sẽ thấy hiện ra menu nhỏ bên dưới. Click vào dấu mũi tên phải để thêm yêu cầu. Sau đó, thêm thông tin chi tiết vào các cột.

Ở project demo, ta có thể thấy phần mềm đã cung cấp sẵn một số yêu cầu mẫu như: *External interfaces, Functions, Usability requirements, Performance requirements, Logical database requirements, Design constraints, Standards compliance, Software system attributes*.

![Hình bị lỗi huhu :<][img11]
 
###	**Mối quan hệ giữa các yêu cầu**

Để tiện lợi, ta sẽ chọn các yêu cầu tiếp tục từ bước trước để demo, bao gồm Create Document, Open File và Save Local File. Ta lần lượt ấn vào từng yêu cầu và tổ hợp phím `Ctrl` để chọn nhiều yêu cầu.

![Hình bị lỗi huhu :<][img12]
 
Ở menu phải, nhấn vào `Links` rồi nhấn vào biểu tượng mũi tên phải như trong hình, hoặc nhấn tổ hợp phím tắt `Ctrl + L`. Sau khi thực hiện thành công, ta sẽ thấy dưới các ID tương ứng sẽ có biểu tượng này.

![Hình bị lỗi huhu :<][img13]
 
Ở menu trái chọn `StRS`. Tại menu giữa, cuộn chuột đến nơi được liên kết, cụ thể ở đây là mục *Standard templates*, rồi nhấn vào. Sau đó, chọn `Links` ở menu trái và click vào biểu tưởng mũi tên như trong hình, hoặc nhấn tổ hợp phím tắt `Ctrl + Shift + L`. 

![Hình bị lỗi huhu :<][img14]
 
Lúc này pop-up hiện lên, ta chọn loại liên kết `Satisfaction` từ menu xổ xuống. Nhấn `OK` để hoàn tất.

![Hình bị lỗi huhu :<][img15]
 
Như vậy, ta đã tạo mối quan hệ giữa các yêu cầu thành công. Cụ thể ở đây là các yêu cầu *SRS-52, SRS-55, SRS-58* từ **SW Requirements** sẽ phải thỏa mãn yêu cầu *StRS-26* từ **Stakeholder Requirments**. 

![Hình bị lỗi huhu :<][img16]
 
Ta có thể chuyển nhanh đến các yêu cầu bằng cách nhấn vào đường liên kết. Ngoài ra, ta có thể click chuột phải để hiển thị thêm nhiều chức năng thay đổi, xóa, sửa, … trên các quan hệ này.

![Hình bị lỗi huhu :<][img17]
 
###	**Lịch sử thay đổi của các yêu cầu**

Tại menu giữa, ta chọn yêu cầu muốn xem thay đổi. Ở menu trái, chọn vào `History`, phần mềm sẽ hiện ra chi tiết lịch sử các thay đổi của yêu cầu.

![Hình bị lỗi huhu :<][img18]




[ibm-rational-requisitepro]: https://www.ibm.com/support/pages/rational-requisitepro-714
[jama-connect]: https://www.jamasoftware.com
[modern-requirements]: https://www.modernrequirements.com 
[accompa]: https://web.accompa.com
[reqsuite-rm]: https://www.osseno.com
[blueprint]: https://www.blueprintsys.com
[reqchecker]: https://reqchecker.eu
[azure-devops-server]: https://azure.microsoft.com/en-us/services/devops/server
[requirements-hub]: https://www.selecthub.com/requirementshub
[reqview]: https://www.reqview.com
[vnt-software]: https://vnt-software.com
[codebeamer-alm]: https://intland.com/codebeamer
[visure-requirements]: https://visuresolutions.com/requirements-management-tool
[jira-software]: https://www.atlassian.com/software/jira
[enterprise-tester]: (https://catchsoftware.com/enterprise-tester
[intland-retina]: https://intland.com/codebeamer-x
[register]: https://www.reqview.com/trial
[setup]: https://reqview.com/download.html

[img1]: assets/images/2021-04-04/Picture1.png
[img2]: assets/images/2021-04-04/Picture2.png
[img3]: assets/images/2021-04-04/Picture3.png
[img4]: assets/images/2021-04-04/Picture4.png
[img5]: assets/images/2021-04-04/Picture5.png
[img6]: assets/images/2021-04-04/Picture6.png
[img7]: assets/images/2021-04-04/Picture7.png
[img8]: assets/images/2021-04-04/Picture8.png
[img9]: assets/images/2021-04-04/Picture9.png
[img10]: assets/images/2021-04-04/Picture10.png
[img11]: assets/images/2021-04-04/Picture11.png
[img12]: assets/images/2021-04-04/Picture12.png
[img13]: assets/images/2021-04-04/Picture13.png
[img14]: assets/images/2021-04-04/Picture14.png
[img15]: assets/images/2021-04-04/Picture15.png
[img16]: assets/images/2021-04-04/Picture16.png
[img17]: assets/images/2021-04-04/Picture17.png
[img18]: assets/images/2021-04-04/Picture18.png


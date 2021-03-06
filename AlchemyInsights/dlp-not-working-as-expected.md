---
title: DLP không hoạt động như mong đợi
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: e96904e2f0da2fe1fafb3f8722465eaf22681b71
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507500"
---
# <a name="dlp-not-working-as-expected"></a>DLP không hoạt động như mong đợi

**Quan trọng**: trong những lần chưa từng thấy, chúng tôi đang thực hiện các bước để đảm bảo rằng dịch vụ SharePoint Online và OneDrive vẫn có sẵn cao-vui lòng truy cập [điều chỉnh tính năng tạm thời của SharePoint Online](https://aka.ms/ODSPAdjustments) để biết thêm thông tin.

 **Thiết lập DLP**

Bạn có vấn đề với **ngăn mất dữ liệu (DLP)** trong Office 365 không hoạt động như mong đợi? Nếu có, đảm bảo rằng **chính sách DLP** của bạn được thiết lập chính xác và dữ liệu của bạn chứa những gì **chính sách DLP** đang tìm kiếm khi nó được đánh giá.
  
Chính sách DLP cho phép bạn xác định và bảo vệ thông tin nhạy cảm trong tổ chức của bạn. Thiết lập chính sách DLP, sử dụng thông tin [ở đây](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).
  
 **Chính sách DLP nào tìm kiếm**
  
Khi sử dụng các **loại thông tin nhạy cảm tích hợp** trong Trung tâm bảo mật và tuân thủ, chính sách DLP tìm các mẫu và yếu tố cụ thể khi phát hiện các loại nhạy cảm.
  
- **Tích hợp các loại thông tin nhạy cảm**

    Để biết thông tin về các loại nhạy cảm và chính sách DLP sẽ tìm kiếm khi phát hiện loại nhạy cảm, hãy xem: [những loại thông tin nhạy cảm tìm kiếm](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).

- **Các loại thông tin nhạy cảm tùy chỉnh**

    Nếu bạn đang cố gắng tạo các loại thông tin nhạy cảm tùy chỉnh, hãy sử dụng bài viết sau để biết thông tin về cách tạo loại nhạy cảm tùy chỉnh: [tạo loại thông tin nhạy cảm tùy chỉnh](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).

**Kiểm tra chính sách DLP**

Để kiểm tra dữ liệu của bạn bằng loại thông tin nhạy cảm được tích hợp hoặc tùy chỉnh, hãy sử dụng tùy chọn **loại thử nghiệm** **trong phân**  >  **loại thông tin nhạy cảm**. Để biết thêm thông tin, xem [kiểm tra các loại thông tin nhạy cảm tùy chỉnh](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).

 **Báo cáo**
  
- Nhận thông tin chi tiết dữ liệu nhạy cảm với [báo cáo DLP.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)

- Xem chi tiết cụ thể của sự kiện với [báo cáo](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports)việc làm.

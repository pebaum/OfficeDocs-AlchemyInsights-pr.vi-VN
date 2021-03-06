---
title: Thiết đặt chính sách cuộc họp
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000734"
- "2657"
ms.openlocfilehash: 509bd0c686830c04ed27f97372411677c0a7f4a4
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 02/15/2020
ms.locfileid: "42042866"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a>Quản lý chính sách cuộc họp trong Microsoft teams

**Lưu ý: có thể mất đến 24 giờ để thay đổi chính sách có hiệu lực đối với người dùng.** Bạn có thể không thể thực hiện thay đổi cho chính sách mới được tạo ngay lập tức; đợi 4 giờ và cố gắng sửa đổi một chính sách mới được tạo ra một lần nữa.

Chính sách cuộc họp được sử dụng để kiểm soát các tính năng sẵn có để gặp gỡ những người tham gia cuộc họp theo lịch trình của người dùng trong tổ chức của bạn. Một số tính năng của chính sách cuộc họp có thể không được thực hiện trong Trung tâm quản trị teams (chúng được gắn nhãn "đến sớm" trong tài liệu). Trong trường hợp này, hoặc nếu bạn nhận được lỗi như "chúng tôi không thể cập nhật chính sách ngay bây giờ nhưng hãy thử lại sau" trong Trung tâm quản trị Microsoft teams, chúng tôi khuyên bạn nên sử dụng PowerShell để tạo hoặc sửa đổi các chính sách cuộc họp của teams. 

Để biết thêm thông tin về chính sách cuộc họp, hãy xem các tài nguyên sau:

- Để tìm hiểu về cách tạo chính sách, thực hiện thay đổi và gán người dùng cho chính sách, hãy xem [quản lý chính sách cuộc họp trong teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).

- Để thực hiện thay đổi chính sách bằng cách sử dụng lệnh ghép ngắn PowerShell, hãy xem [tổng quan về nhóm PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview). 
    - Bạn cần sử dụng [Skype dành cho doanh nghiệp PowerShell mô-đun](https://www.microsoft.com/download/details.aspx?id=39366) cho các chính sách cuộc họp teams. 
    - Đánh giá [tài liệu lệnh ghép ngắn *-csteamsmeetingpolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) để biết thêm thông tin.


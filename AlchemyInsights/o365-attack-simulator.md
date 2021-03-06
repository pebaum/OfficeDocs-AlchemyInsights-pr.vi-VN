---
title: 2681 Attack Simulator trong Microsoft 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506760"
---
# <a name="attack-simulator-in-microsoft-365"></a>Attack Simulator trong Microsoft 365

- Bạn có thiếu Attack Simulator? Attack Simulator yêu cầu **office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** hoặc **Office 365 Enterprise E5**. Tấn công mô phỏng **không** được bao gồm trong Office 365 nâng cao mối đe dọa bảo vệ kế hoạch 1 (ATP kế hoạch 1), Office 365 Enterprise E3 hoặc bất kỳ Microsoft 365 ứng dụng cho đăng ký kinh doanh.

- Tài khoản bạn sử dụng để khởi chạy các cuộc tấn công mô phỏng yêu cầu quản trị viên toàn cầu hoặc quyền quản trị viên bảo mật và xác thực đa yếu tố (MFA). Để biết thêm thông tin về yêu cầu Attack Simulator, xem [chủ đề này](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

- Những điều quan trọng cần biết về mô phỏng tấn công **Brute Force mật khẩu** :

  - Nếu tài khoản đích đã bật MFA và mật khẩu đã được đoán đúng, tài khoản sẽ không hiển thị là bị xâm phạm (yếu tố xác thực thứ hai sẽ không đầy đủ).

  - Tệp mật khẩu không thể lớn hơn 10 MB. Sử dụng một mật khẩu cho mỗi dòng, và bao gồm một dòng trống (vận chuyển trở lại) sau khi mật khẩu cuối cùng trong danh sách.

- Những điều quan trọng cần biết về mô phỏng gắn giả **mạo của Spear** :

  - Theo thiết kế, bạn không thể cung cấp giá trị tùy chỉnh cho **URL máy chủ đăng nhập lừa đảo**.

  - Nếu người nhận sử dụng trình [bổ trợ thông báo báo cáo](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) để báo cáo thư là lừa đảo, bạn có thể không nhận được thông báo cho thư này (vì đây là một cuộc tấn công mô phỏng).

- Báo cáo: sau khi cuộc tấn công mô phỏng hoàn tất, bạn có thể nhấp **chi tiết tấn công** để xem báo cáo.

- Để biết hướng dẫn chi tiết và các tính năng mới trong Attack Simulator, xem [Attack Simulator trong Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

---
title: Outlook Desktop nhớ lại hoặc thay thế một thư email
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: bb84363ae7d3c91750d5de789c091c7cebbbedc2
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/02/2020
ms.locfileid: "44502341"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Gọi lại hoặc thay thế thư email Outlook

- Là quản trị viên, bạn có thể **nhớ lại thư thay mặt người dùng sử dụng PowerShell**. Bạn không thể gọi lại thư từ Trung tâm quản trị.
- Bạn chỉ có thể **gọi lại thư được gửi cho những người trong tổ chức của bạn**. Ví dụ: nếu thư được gửi đến địa chỉ Gmail, bạn không thể gọi lại thông báo đó.
- Bạn chỉ có thể **gọi lại thư được gửi từ Outlook 2016 trên PC**. Nếu người dùng gửi thư bằng cách sử dụng Outlook dành cho Mac hoặc Outlook trên web, bạn không thể gọi lại.

Để gọi lại hoặc thay thế thư email:

1. Trong ngăn thư mục bên trái cửa sổ Outlook, chọn thư mục mục đã gửi.
1. Bấm đúp vào thư bạn muốn gọi lại để mở.
1. Chọn tab **thư** , sau đó chọn **tác động**  >  **nhớ lại thư này**.
1. Chọn **xóa các bản sao chưa đọc của thư này** hoặc **xóa các bản sao chưa đọc và thay thế bằng một tin nhắn mới**, sau đó chọn **OK**.
1. Nếu bạn đang gửi một tin nhắn thay thế, soạn tin nhắn, và sau đó chọn **gửi**.
1. Sự thành công hay thất bại của một tin nhắn thu hồi phụ thuộc vào cài đặt của người nhận trong Outlook. Để biết các bước kiểm tra thu hồi, hãy xem [bài viết này](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Tìm kiếm và xóa thư email trong tổ chức của bạn

- Nếu bạn không phải là quản trị viên toàn cầu, tài khoản của bạn cần được thêm vào vai trò của trình quản lý eDiscovery hoặc vai trò quản lý tìm kiếm phù hợp để tìm kiếm thư. Để xóa thư, bạn sẽ cần tham gia nhóm vai trò quản lý tổ chức hoặc vai trò quản lý tìm kiếm và dọn sạch. Quyền cho các vai trò được chỉ định trong [Trung tâm bảo mật và tuân thủ](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Tạo tìm kiếm nội dung](https://docs.microsoft.com/microsoft-365/compliance/content-search) để tìm thư cần xóa.
- [Kết nối với PowerShell Trung tâm bảo mật và tuân thủ](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Nếu bạn đang sử dụng xác thực nhiều yếu tố, hãy xem [kết nối với Microsoft 365 bảo mật và tuân thủ trung tâm PowerShell bằng cách sử dụng xác thực nhiều yếu tố](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).
---
title: 618 chính sách chia sẻ lịch
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/26/2020
ms.locfileid: "44373021"
---
# <a name="policy-error-when-sharing-a-calendar"></a>Lỗi chính sách khi chia sẻ lịch

1. Thực hiện một trong những điều sau, nếu phù hợp với tình huống của bạn:
    - Kết nối với Exchange Online bằng cách sử dụng PowerShell từ xa. Để biết thêm thông tin, xem [kết nối với Exchange Online sử dụng PowerShell từ xa](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).
    - Trên máy chủ tại chỗ, mở Exchange Management Shell.
2. Xác định chính sách chia sẻ được gán cho người dùng. Để thực hiện việc này, hãy chạy lệnh sau và lưu ý chính sách trả lại:

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. Cập Nhật chính sách chia sẻ cho người dùng. Caranya sebagai berikut:
    - Mở Trung tâm quản trị Exchange.
    - Bấm **tổ chức**, và sau đó bấm đúp vào chính sách được gán cho người dùng trong **chia sẻ cá nhân**. Đây là chính sách được trả về trong bước 2.
    - Trên trang quy tắc chia sẻ, chọn mức độ chia sẻ lịch mà bạn muốn cho phép theo **chỉ định thông tin bạn muốn chia sẻ**; bấm vào **lưu**.

Để biết thêm thông tin xem: ["chính sách không cho phép cấp quyền ở mức này cho một hoặc nhiều người nhận" lỗi khi người dùng cố gắng chia sẻ lịch](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).

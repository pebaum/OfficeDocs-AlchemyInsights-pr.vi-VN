---
title: Nội dung tìm kiếm không có kết quả
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 09cdbc3cb0465e0e0bc08872c49e283081ad3e92
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/22/2019
ms.locfileid: "36516801"
---
# <a name="no-results-from-content-searchexports"></a>Không có kết quả từ nội dung tìm kiếm/xuất khẩu

Vấn đề với nội dung tìm kiếm/xuất khẩu không trả lại bất kỳ dữ liệu có thể là do một số bộ lọc bảo mật tuân thủ đã là thiết lập bởi một quản trị viên cụ thể và không giao tiếp với tất cả các quản trị viên.

Để giải quyết điều này, hãy kiểm tra xem nếu có bất kỳ bộ lọc bảo mật tuân thủ có thể gây ra điều này:
1. Kết nối bảo mật và tuân thủ trung tâm Powershell
2. Chạy commandlets sau đây:
<br>$org = "Tenmiencuaban.com"
<br>Get-ComplianceSecurityFilter-tổ chức $org
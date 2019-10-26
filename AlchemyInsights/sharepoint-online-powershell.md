---
title: SharePoint trực tuyến PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123020"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="0eea4-102">SharePoint trực tuyến PowerShell</span><span class="sxs-lookup"><span data-stu-id="0eea4-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="0eea4-103">Làm việc với PowerShell hoặc scripts trong SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="0eea4-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="0eea4-104">Hãy truy cập vào các liên kết bên dưới để biết thêm thông tin.</span><span class="sxs-lookup"><span data-stu-id="0eea4-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="0eea4-105">Bắt đầu với SharePoint Online Management Shell</span><span class="sxs-lookup"><span data-stu-id="0eea4-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="0eea4-106">Kết nối với SPO PowerShell với xác thực đa yếu tố (MFA)</span><span class="sxs-lookup"><span data-stu-id="0eea4-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="0eea4-107">[SharePoint Patterns và thực tiễn (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) chứa một thư viện lệnh PowerShell cho phép bạn thực hiện các hành động quản lý phức tạp đối với SPO.</span><span class="sxs-lookup"><span data-stu-id="0eea4-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="0eea4-108">Nếu bạn gặp sự cố kết nối với vỏ quản lý SPO, đảm bảo rằng bạn đã cập nhật lên phiên bản mới nhất và cố gắng [nhập lại mô-đun](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) bằng cách sử dụng *"nhập mô-đun Microsoft. Online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="0eea4-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="0eea4-109">Nếu bạn đang cố gắng chạy tập lệnh mô hình đối tượng phía máy khách, bạn sẽ cần phải có [SharePoint trực tuyến máy khách thành phần SDK](https://www.microsoft.com/download/details.aspx?id=42038) cài đặt trên máy tính cục bộ của bạn.</span><span class="sxs-lookup"><span data-stu-id="0eea4-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="0eea4-110">Nếu bạn gặp sự cố chạy tập lệnh từ PowerShell, bạn có thể xem xét Chạy PowerShell là quản trị viên và thay đổi [chính sách thực hiện](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="0eea4-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>
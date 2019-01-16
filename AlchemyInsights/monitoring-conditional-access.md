---
title: Giám sát truy cập có điều kiện
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 01/15/2019
ms.locfileid: "28321232"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="6d9fe-102">Giám sát truy cập có điều kiện</span><span class="sxs-lookup"><span data-stu-id="6d9fe-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="6d9fe-p101">Nhắm mục tiêu với điều kiện truy cập người dùng sẽ nhận được một email thông báo nếu họ không đáp ứng yêu cầu truy cập tổ chức của bạn. Để giải quyết, chúng tôi khuyên bạn nên một hoặc nhiều các giải pháp sau:</span><span class="sxs-lookup"><span data-stu-id="6d9fe-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="6d9fe-p102">Nếu thiết bị là presumed để được đăng ký, tư vấn cho người sử dụng để đi đến các ứng dụng cổng thông tin công ty và xác minh rằng nó xuất hiện trong cổng công ty. Nếu không, người dùng nên đăng ký các thiết bị.</span><span class="sxs-lookup"><span data-stu-id="6d9fe-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="6d9fe-p103">Trong các cổng Azure vào **dành \> thiết bị tuân thủ**. Trong **màn hình** nhấp vào **thiết bị tuân thủ**. Xem báo cáo của bạn tuân thủ thiết bị để kiểm chứng rằng thiết bị của người dùng được đánh dấu như tuân thủ.</span><span class="sxs-lookup"><span data-stu-id="6d9fe-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="6d9fe-p104">Trong các cổng Azure vào **dành \> thiết bị tuân thủ**. Trong **quản lý**, bấm vào **chính sách**. Trong danh sách các chính sách phù hợp, xác minh hồ sơ được gán cho thiết bị của người dùng. Nếu hồ sơ không được phân công, sau đó dành sẽ không thể để xác nhận tình trạng tuân thủ của thiết bị.</span><span class="sxs-lookup"><span data-stu-id="6d9fe-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="6d9fe-114">Chỉnh sửa của người dùng truy cập có điều kiện chuyển nhượng.</span><span class="sxs-lookup"><span data-stu-id="6d9fe-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="6d9fe-115">Trong các cổng Azure vào **dành \> có điều kiện truy cập \> chính sách**</span><span class="sxs-lookup"><span data-stu-id="6d9fe-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="6d9fe-116">Chọn một chính sách từ danh sách</span><span class="sxs-lookup"><span data-stu-id="6d9fe-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="6d9fe-117">Nhấp vào **người dùng và nhóm**</span><span class="sxs-lookup"><span data-stu-id="6d9fe-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="6d9fe-p105">Để nhắm mục tiêu một chính sách nhất định vào một ai đó, thêm chúng vào danh sách **bao gồm** . Để đảm bảo rằng một người bỏ qua từ chính sách, thêm chúng vào danh sách **loại trừ** .</span><span class="sxs-lookup"><span data-stu-id="6d9fe-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="6d9fe-120">Đọc thêm: [làm thế nào để giám sát truy cập có điều kiện thiết bị](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="6d9fe-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span></span>
  

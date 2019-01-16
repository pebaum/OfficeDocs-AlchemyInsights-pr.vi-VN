---
title: Có điều kiện tiếp cận với dành
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 01/15/2019
ms.locfileid: "28320145"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="e82dc-102">Có điều kiện tiếp cận với dành</span><span class="sxs-lookup"><span data-stu-id="e82dc-102">Conditional Access with Intune</span></span>

<span data-ttu-id="e82dc-103">Sử dụng **Có điều kiện tiếp cận** với dành yêu cầu 3 bước:</span><span class="sxs-lookup"><span data-stu-id="e82dc-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="e82dc-p101">Tạo một **Chính sách truy nhập có điều kiện** xác định những nguồn tài nguyên đang được bảo vệ, và điều kiện cần phải được đáp ứng để truy cập vào các nguồn lực. Ví dụ, một thiết bị phải được tuân thủ trước khi truy cập vào email của công ty.</span><span class="sxs-lookup"><span data-stu-id="e82dc-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="e82dc-p102">Tạo một **Chính sách tuân thủ** để xác định các cài đặt phải được đáp ứng trước khi thiết bị được coi là phù hợp. Ví dụ, một thiết bị phải có một pin ít nhất 6 chữ số trước khi nó được coi là phù hợp.</span><span class="sxs-lookup"><span data-stu-id="e82dc-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="e82dc-p103">Đảm bảo **Việc tuân thủ chính sách** và **Điều kiện chính sách truy cập** được nhắm mục tiêu cho các nhóm người dùng, bạn muốn. Điều này có thể cần tạo nhóm người dùng cụ thể vào Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e82dc-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="e82dc-110">Đọc thêm:</span><span class="sxs-lookup"><span data-stu-id="e82dc-110">Read more:</span></span>
  
- [<span data-ttu-id="e82dc-111">Có điều kiện tiếp cận thực tiễn tốt nhất</span><span class="sxs-lookup"><span data-stu-id="e82dc-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="e82dc-112">Bắt đầu với điều kiện truy cập</span><span class="sxs-lookup"><span data-stu-id="e82dc-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

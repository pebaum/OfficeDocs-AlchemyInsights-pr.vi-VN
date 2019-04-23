---
title: Xác định bên ngoài email chuyển tiếp vào hộp thư trong Nhật ký kiểm tra
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 7fb2c161c558a7eb961f86ca2b86e33750d902fd
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909685"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="4433c-102">Xác định khi chuyển tiếp email bên ngoài được cấu hình trên hộp thư</span><span class="sxs-lookup"><span data-stu-id="4433c-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="4433c-103">Khi người dùng cấu hình chuyển tiếp thư điện tử bên ngoài một hộp thư, các hoạt động kiểm toán là một phần của lệnh ghép ngắn **Set-Mailbox** .</span><span class="sxs-lookup"><span data-stu-id="4433c-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="4433c-104">Bạn có thể xem các hoạt động bằng cách sử dụng kiểm toán đăng nhập tìm kiếm trong an ninh & Trung tâm phù hợp.</span><span class="sxs-lookup"><span data-stu-id="4433c-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="4433c-105">Đăng nhập vào [Trung tâm Compliance Office 365 bảo mật &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="4433c-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="4433c-106">Nhấp vào **Tìm kiếm và điều tra** và chọn **Kiểm toán đăng nhập tìm kiếm**.</span><span class="sxs-lookup"><span data-stu-id="4433c-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="4433c-107">Chọn phạm vi ngày trong các **ngày bắt đầu** và **ngày kết thúc** .</span><span class="sxs-lookup"><span data-stu-id="4433c-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="4433c-108">Bạn không cần phải chỉ định một tên người dùng.</span><span class="sxs-lookup"><span data-stu-id="4433c-108">You don't need to specify a username.</span></span> <span data-ttu-id="4433c-109">Xác minh các lĩnh vực **hoạt động** được đặt để **Hiển thị kết quả cho tất cả các hoạt động**.</span><span class="sxs-lookup"><span data-stu-id="4433c-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="4433c-110">Nhấp vào **Tìm kiếm**.</span><span class="sxs-lookup"><span data-stu-id="4433c-110">Click **Search**.</span></span>

<span data-ttu-id="4433c-111">Trong kết quả, hãy nhấp vào **Bộ lọc kết quả** và loại **Set-Mailbox** trong hộp lọc hoạt động.</span><span class="sxs-lookup"><span data-stu-id="4433c-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="4433c-112">Hãy chọn một hồ sơ kiểm toán trong các kết quả.</span><span class="sxs-lookup"><span data-stu-id="4433c-112">Select an audit record in the results.</span></span> <span data-ttu-id="4433c-113">Trong flyout **chi tiết** , bấm vào **thêm thông tin**.</span><span class="sxs-lookup"><span data-stu-id="4433c-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="4433c-114">Bạn cần phải xem xét các chi tiết của mỗi hồ sơ kiểm toán để xác định nếu các hoạt động có liên quan đến email chuyển tiếp.</span><span class="sxs-lookup"><span data-stu-id="4433c-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="4433c-115">**ObjectId**: giá trị bí danh của hộp thư đã được thay đổi.</span><span class="sxs-lookup"><span data-stu-id="4433c-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="4433c-116">**Thông số**: _ForwardingSmtpAddress_ địa chỉ email mục tiêu cho biết.</span><span class="sxs-lookup"><span data-stu-id="4433c-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="4433c-117">**User**: người dùng đã đặt cấu hình chuyển tiếp email trong hộp thư trong lĩnh vực **ObjectId** .</span><span class="sxs-lookup"><span data-stu-id="4433c-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="4433c-118">Để biết thêm chi tiết, hãy xem [Determining người thiết lập email chuyển tiếp cho một hộp thư](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="4433c-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
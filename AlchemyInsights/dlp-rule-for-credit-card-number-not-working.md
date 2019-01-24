---
title: DLP quy tắc cho các số thẻ tín dụng không làm việc
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 01/15/2019
ms.locfileid: "28320332"
---
Bạn đang gặp vấn đề với **Công tác phòng chống mất mát dữ liệu (DLP)** không làm việc cho nội dung có chứa một **Số thẻ tín dụng** khi sử dụng một loại thông tin nhạy cảm DLP trong O365? Nếu vậy, hãy chắc chắn rằng nội dung của bạn có chứa các thông tin cần thiết để kích hoạt các chính sách DLP khi nó được đánh giá. Ví dụ, cho một **thẻ tín dụng chính sách** được cấu hình với mức độ tin cậy là 85%, sau đây được đánh giá và phải được phát hiện cho quy tắc để kích hoạt: 
  
- **[Định dạng:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 chữ số mà có thể được định dạng hoặc chưa định dạng (dddddddddddddddd) và phải vượt qua bài kiểm tra Luhn. 
    
- **[Mẫu:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Mô hình rất phức tạp và mạnh mẽ phát hiện thẻ từ tất cả các thương hiệu lớn trên toàn thế giới, bao gồm Visa, Mastercard, Discover Card, JCB, American Express, thẻ quà tặng và quán ăn thẻ. 
    
- **[Kiểm tra:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Vâng, kiểm tra Luhn 
    
- **[Định nghĩa:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Một chính sách DLP là 85% tự tin rằng nó đã phát hiện đây là loại thông tin nhạy cảm nếu, trong vòng một gần 300 ký tự: 
    
  - Chức năng Func_credit_card tìm thấy nội dung phù hợp với các mô hình.
    
  - Một trong những điều sau đây là đúng: 
    
  - Tìm thấy một từ khóa từ Keyword_cc_verification.
    
  - Tìm thấy một từ khóa từ Keyword_cc_name
    
  - Chức năng Func_expiration_date tìm thấy một ngày ở định dạng đúng ngày.
    
  - Đi kiểm tra
    
    Ví dụ, các mẫu sau sẽ kích hoạt cho một chính sách số DLP thẻ tín dụng:
    
  - Visa: 4485 3647 3952 7352 người 
    
  - Hết hạn: tháng 2 năm 2009
    
Để biết thêm chi tiết về những gì là cần thiết cho một **Số thẻ tín dụng** để được phát hiện cho nội dung của bạn, hãy xem phần sau đây trong bài viết này: [Những gì the nhạy cảm loại thông tin tìm kiếm thẻ tín dụng #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Bằng cách sử dụng một loại thông tin nhạy cảm khác nhau được xây dựng trong, xem bài viết sau đây để có thông tin về những gì là cần thiết cho các loại khác: [những gì the nhạy cảm loại thông tin tìm kiếm](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

---
title: Lỗi AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: fa1fdb35f1af250bc98aa61c0e5111f1f1b8aac4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703196"
---
# <a name="error-attributevaluemustbeunique"></a>Lỗi: AttributeValueMustBeUnique

Lý do phổ biến nhất cho AttributeValueMustBeUnique lỗi là hai đối tượng với SourceAnchor khác (immutableId) có cùng giá trị cho các thuộc tính ProxyAddresses và/hoặc UserPrincipalName. Để khắc phục lỗi AttributeValueMustBeUnique:
  
1. Xác định proxyAddresses trùng lặp, userPrincipalName hoặc giá trị thuộc tính khác gây ra lỗi. Cũng xác định hai (hoặc nhiều) đối tượng có liên quan trong cuộc xung đột. Báo cáo được tạo ra bởi Azure AD kết nối y tế để đồng bộ hóa có thể giúp bạn xác định hai đối tượng.
    
2. Xác định đối tượng nào sẽ tiếp tục có giá trị trùng lặp và đối tượng sẽ không.
    
3. Loại bỏ giá trị trùng lặp từ các đối tượng không phải có giá trị đó. Lưu ý rằng bạn nên thực hiện thay đổi trong thư mục nơi đối tượng có nguồn gốc từ. Trong một số trường hợp, bạn có thể cần phải xoá một trong các đối tượng xung đột.
    
4. Nếu bạn đã thực hiện thay đổi trên cơ sở quảng cáo, cho phép Azure AD kết nối đồng bộ hoá thay đổi lỗi để khắc phục.
    


---
title: Управление на синхронизиран потребител
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 5a383bdd17c5fa055c35a923ca36e0e0f6d429e4
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380494"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="d98d5-102">Не може да зададете основния имейл адрес или промяна на потребителски атрибути</span><span class="sxs-lookup"><span data-stu-id="d98d5-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="d98d5-103">Ако Синхронизирането на директории е разрешен за вашата среда някои потребител или обект атрибути не могат да бъдат променени с помощта на центъра за администрация на.</span><span class="sxs-lookup"><span data-stu-id="d98d5-103">If directory synchronization is enabled for your environment some user or object attributes cannot be changed using the Admin Center.</span></span>
<span data-ttu-id="d98d5-104">За да управлявате напълно синхронизирани потребители и всички техни атрибути, използвайте вашата локалната услуга active directory потребители и групи управление конзола (adsiedit.msc).</span><span class="sxs-lookup"><span data-stu-id="d98d5-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="d98d5-105">Алтернативно можете да промените отделни потребители или атрибути за синхронизирани потребители, използващи powershell, както е показано в тези общи примери:</span><span class="sxs-lookup"><span data-stu-id="d98d5-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="d98d5-106">Комплект-MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="d98d5-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="d98d5-107">Комплект-MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com" - DisplayName "Тестов потребител" - фамилия "Потребител"-заглавие "Мениджър"-отдел "Човешки ресурси"</span><span class="sxs-lookup"><span data-stu-id="d98d5-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="d98d5-108">Премествам-MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="d98d5-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>
---
title: Работа с iOS VPP приложения правило ИД 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 5bcfb6dd7222bd102ff2620c19bfb943e7bd9591
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 01/15/2019
ms.locfileid: "28276625"
---
# <a name="working-with-ios-vpp-applications"></a>Работа с iOS VPP приложения

Прочетете [как да управлявате iOS приложения, закупени чрез Том-покупка програма с Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) да научите повече за функциите, ограничения и стъпки, за да използвате на Apple Том пазаруване програма и подкрепа за него в Microsoft Intune. 
  
 **Общи въпроси:** "Възложих iOS VPP ап за моите потребители, но инсталирането е неуспешно." 
  
- Това може да се случи, ако една VPP маркер се използва в множество доставчици за управление на мобилно устройство. VPP символи от Apple може да се използва само с един доставчик. Ако сте използвали VPP точка маркер с няколко доставчици, трябва да качите отново знак Intune.
    
- Инсталацията също може да се провали, ако общият брой на инсталации надвишава броя на лицензи. За да видите на използване на доклад за вашите лицензи, отидете на **Intune мобилен apps** \> страницата **ап лицензи** . За да научите как да се възстановят лицензи в употреба, виж [тази статия.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

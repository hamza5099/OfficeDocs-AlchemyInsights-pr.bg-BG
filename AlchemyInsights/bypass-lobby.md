---
title: Байпас лоби
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: de665ca6defcd0d00d227435473e5a4ccf61bc82
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376525"
---
# <a name="control-lobby-settings-and-level-of-participation"></a>Управление на настройките на лобито и нивото на участие

Тези настройки контролират кои участници в събранието чакат в лобито, преди да бъдат допуснати до събранието, и нивото на участие, което са позволени в събранието. Можете да използвате PowerShell да актуализирате настройките на правилата за събрания, които все още не са изпълнени (с надпис "Очаквайте скоро") в центъра за администриране на екипите.  Вижте по-долу за пример PowerShell команда, която позволява на всички потребители да заобиколят лобито.  

- [Автоматично признават](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , че хората са правила за организатора, които контролират дали хората да се присъединят към събрание директно или да изчакат в лобито, докато не бъдат допуснати от удостоверен потребител.

- [Позволяване на анонимни хора да стартират среща](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) е политика за организатора, която контролира дали анонимните хора, включително B2B и външни потребители, могат да се присъединят към събранието на потребителя без удостоверен потребител от посещаемостта на организацията.

- [Позволяване на потребителите на комутируема връзка да заобиколят лобито](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**Очаквайте скоро**) е политика за организатора, която контролира дали хората, които се набират по телефона, се присъединяват към събранието директно или чакат в лобито, независимо от настройката за **автоматично допускане на хора** .

- [Позволяване на организаторите да отменят настройките на лобито](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**Очаквайте скоро**) е политика на организатора, която контролира дали организаторът на събранието може да замести настройките на лобито, които администраторът е зададен автоматично, за да **признае хората** и да **позволи комутируема връзка потребителите да заобиколят лобито** , когато планират ново събрание.

**Забележка:** Прочетете [управление на правилата за събрания в екипи](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) за пълен преглед на правилата за срещи на Microsoft екипи. 


**Пример за PowerShell**

Ако искате да позволите на всички, включително външни или анонимни потребители, да заобиколят лобито, можете да използвате и PowerShell, за да постигнете тази задача.  Ето пример за модифициране на правилата за глобално събрание за вашата организация.   

(Не забравяйте да прегледате документацията по-горе, преди да направите тези промени, за да разберете точно какво позволява това.)

Set-Ппарапарцияполитика-идентичност глобално-автоматично призна потребителите "всички"-Алловпстнусерстобипасслобби $True

За повече [информация вж.](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps)
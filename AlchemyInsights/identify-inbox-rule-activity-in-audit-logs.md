---
title: Идентифициране на входящи правило дейност в регистрационните файлове от одита
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539126"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>Идентифициране на входящи правило дейност в регистрационните файлове от одита

Можете да използвате одит регистрационния файл търсене в Office 365 сигурност & съответствие център да видите входящи правило събития (създаване, модифициране и изтриване на правила за входяща поща).

1. Влезте в [Office 365 сигурност & съответствие център](https://protection.office.com/).

2. Отидете на **Търсене на** > **одит регистрационния файл търсене** страница.

3. Изберете диапазона от дати в полетата **Начална дата** и **крайна дата** .

4. Под **Exchange пощенска кутия дейности**проверете полето **дейности** е зададена на **Ню-InboxRule създаване/промяна/разрешаване/забраняване на правило за "Входящи"**.

5. Щракнете върху **търсене**.

В резултатите изберете отчет. В детайли flyout щракнете върху **Повече информация**. Информация за настройките на правило за "Входящи" се показва в полето за **параметри** .

За повече информация вижте [определя, ако потребителят създаде правило за "Входящи"](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)

---
title: Идентифицира външни имейл изпращане на пощенски кутии в регистрационните файлове от одита
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 7defd0902e8c8bebae9c7bfee72c3199cbc1909f
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539090"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Идентифициране при външни имейл препращане е конфигуриран на пощенски кутии

Когато потребител на Office 365 конфигурира препращане на външни имейл на пощенската кутия, дейността е одит като част от кратката команда **Set -** Mailbox. Можете да видите дейността чрез одит регистрационния файл търсене в защита & съответствие център.

1. Влезте в [Office 365 сигурност & съответствие център](https://protection.office.com/).

2. Отидете на **Търсене на** > **одит регистрационния файл търсене** страница.

3. Изберете диапазона от дати в полетата **Начална дата** и **крайна дата** . Не е нужно да укажете потребителско име. Проверете полето **дейности** е зададена да **покаже резултати за всички дейности**.

4. Щракнете върху **търсене**.

В резултатите щракнете върху **Филтър резултатите** и въведете **Set-пощенска кутия** в полето на филтъра дейност. Изберете отчет в резултатите. В **детайли** flyout щракнете върху **повече информация**. Вие трябва да погледнете в детайлите на всеки одит запис да се определи дали дейността е свързана с имейл препращане.

- **ObjectId**: псевдоним стойността на пощенска кутия, която е модифициран.

- **Параметри**: _ForwardingSmtpAddress_ показва на целеви имейл адрес.

- **Потребителско име**: потребител, който е конфигуриран имейл препращане на пощенската кутия в полето **ObjectId** .

За повече информация вижте [определя кой създаде имейл спедиция за пощенска кутия](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).

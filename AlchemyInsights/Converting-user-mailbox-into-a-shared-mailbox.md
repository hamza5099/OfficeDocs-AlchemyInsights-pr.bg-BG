---
title: Конвертиране на пощенска кутия на потребител в споделената пощенска кутия?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 01/15/2019
ms.locfileid: "28276583"
---
Можете да преобразувате само потребителска пощенска кутия към споделена пощенска кутия, ако потребителят има лиценз за обмен. След като пощенската кутия се конвертира, тя ще продължи да се появи в списъка на активните потребители, защото този списък включва споделени пощенски кутии. Обаче преобразувания пощенската кутия ще се появи в списъка на споделена пощенска кутия. 
  
Ако се опитате да преобразувате пощенска кутия в Exchange административната конзола и конвертирането не успее, изчистете кеша на браузъра и бисквитки и опитайте отново. Ако тя все още не работи, опитайте конвертиране на пощенската кутия в размяната управление на Шел като пуснете следната команда:
  
```
Set-Mailbox -Type Shared
```

Повече информация за преобразуване на пощенската кутия е наличен в [Конвертиране на потребителска пощенска кутия към споделена пощенска кутия](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
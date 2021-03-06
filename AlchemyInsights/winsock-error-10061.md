---
title: 1554 Winsock грешка 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f54c7fc81c274871fbc22908ce0fb21500975d9e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530772"
---
# <a name="winsock-error-10061"></a>Winsock грешка 10061

Този код на грешка означава, че Office 365 не можа да установи TCP сокет (връзка) с хост. Най-вероятната причина за тази грешка е проблем с конфигурацията на защитната стена. За да коригирате проблема, проверете следните настройки:

- Проверете вашата защитна стена конфигурация с информацията в [Office 365 URL и IP адреси](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Ако грешката е специфичен за Exchange онлайн защита (EOP), вие трябва да са били оповестени до промяна на [Exchange онлайн защита IP адреси](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

- Уверете се, че вашият интернет доставчик (ISP) не блокира пристанището.

- Проверете смарт хоста и целевия сървър настройките във вашата конектори.

Обърнете внимание, че Office 365 не блокира *входящите* връзки по този начин.

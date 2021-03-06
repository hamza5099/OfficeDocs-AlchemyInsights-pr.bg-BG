---
title: Въпроси относно използването на инструмента за разполагане на Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: bg-BG
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553529"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Въпроси относно използването на инструмента за разполагане на Office (ODT)

Изтеглете инструмента за разполагане на Office от [центъра на Microsoft за изтегляния](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
След изтеглянето на файла стартирайте самоархивиращ се изпълнимия файл, който съдържа инструмента за разполагане на Office (setup. exe) и примерен конфигурационен файл (конфигурация. XML).
  
 **За да изключите или премахнете продукти на Office 365 ProPlus от клиентски компютри:**
  
При инсталиране на Office 365 ProPlus, можете да изключите конкретни продукти. За да направите това, следвайте стъпките за инсталиране на Office с ODT, но включва елемент Изключеapp в конфигурационния си файл. Например този конфигурационен файл инсталира всички Office 365 ProPlus продукти с изключение на Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Преглед на инструмента за разполагане на Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  


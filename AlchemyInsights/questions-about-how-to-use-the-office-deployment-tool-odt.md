---
title: Pitanja o tome kako koristiti alat za raspoređivanje Office (ODT)
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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36553554"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Pitanja o tome kako koristiti alat za raspoređivanje Office (ODT)

Preuzmite alatku za raspoređivanje Office iz [Microsoft centra za preuzimanje](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Nakon preuzimanja datoteke, pokrene na izvršnu datoteku, koja sadrži Office raspoređivanja alatku za izvršne (setup.exe) i datoteku za konfiguraciju uzorka (configuration.xml).
  
 **Da isključite ili uklonite Office 365 ProPlus proizvodi iz klijentske računare:**
  
Kada instalirate Office 365 ProPlus, možete da isključite specifične proizvode. Da biste to učinili, slijedite korake za instalaciju Office uz na ODT, ali uključuju ExcludeApp element u datoteci za konfiguraciju. Na primer, datoteka za konfiguraciju instalira Office 365 ProPlus proizvode osim izdavača:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Pregled sistema Office alatke za raspoređivanje](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  


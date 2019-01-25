---
title: Pitanja o tome kako koristiti alat za raspoređivanje Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: c16b7ac7d79794307fa33ed1039305ed5b842cf6
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487793"
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
  


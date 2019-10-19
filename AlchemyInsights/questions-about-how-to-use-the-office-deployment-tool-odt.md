---
title: Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)
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
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553554"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)

Preuzmite alatku za primenu sistema Office sa [lokacije Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Kada preuzmete datoteku, pokrenite izvršnu datoteku koja se samostalno izdvaja, a koja sadrži izvršnu alatku "Office alatka za primenu" (Setup. exe) i probnu datoteku za konfiguraciju (konfiguracija. XML).
  
 **Da biste izuzeli ili uklonili Office 365 ProPlus proizvode sa klijentskih računara:**
  
Kada instalirate Office 365 ProPlus, možete da isključite određene proizvode. Da biste to uradili, sledite korake za instaliranje sistema Office sa ODT, ali uključite i ExcludeApp element u datoteku za konfiguraciju. Na primer, ova datoteka za konfiguraciju instalira sve Office 365 ProPlus proizvode osim izdavača:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Pregled alatke za primenu sistema Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  


---
title: Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 96d3f70f554f71c43d6458ec8debc099cd9fb040
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43698072"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Pitanja o načinu korišćenja alatke za primenu sistema Office (ODT)

Preuzmite alatku za primenu sistema Office sa [lokacije Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Kada preuzmete datoteku, pokrenite izvršnu datoteku koja se samostalno izdvaja, a koja sadrži izvršnu alatku "Office alatka za primenu" (Setup. exe) i probnu datoteku za konfiguraciju (konfiguracija. XML).
  
 **Da biste izuzeli ili uklonili Microsoft 365 aplikacije za Enterprise proizvode sa klijentskih računara:**
  
Kada instalirate Microsoft 365 aplikacije za Enterprise, možete da izuzmete određene proizvode. Da biste to uradili, sledite korake za instaliranje sistema Office sa ODT, ali uključite i ExcludeApp element u datoteku za konfiguraciju. Na primer, ova datoteka za konfiguraciju instalira sve Microsoft 365 aplikacije za Enterprise proizvode osim izdavača:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Pregled alatke za primenu sistema Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  


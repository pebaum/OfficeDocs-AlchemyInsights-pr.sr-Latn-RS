---
title: Moderna lokaciju kao osnovne lokacije
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 6166493f79379f44b1a9bbbaca6becfe624fe912
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057767"
---
# <a name="modern-site-as-root-site"></a>Moderna lokaciju kao osnovna lokacija

[Cilj izdavanja](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) kupci sada može da omogući moderna komunikacija iskustvo lokacije na klasični matičnoj lokaciji od svoje SharePoint stanar.

Ovu funkciju možete aktivirati tako što ćete pokrenuti neki jednostavan PowerShell cmdlet. Na uspešno izvršenje na PowerShell command(s), osnovne lokacije će imati novu matičnu stranicu lokacije komunikacije. Detalji o zahtevima za PowerShell cmdlet i funkcija dostupnih u članku [Omogući-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps). 

Postepeno Valjaжemo se ovo, sa po podrazumevanoj vrednosti, na meti puštanje kupcima 2019 početkom maja, a slepi kolosek biće na raspolaganju širom sveta do kraja juna 2019. I dalje se odnose na [Centar za poruke](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) za druge nove funkcije sa modernom. 

**Važno**: nemojte brisati svoje klasične osnovne lokacije da biste kreirali lokaciju moderne komunikacije. Ovo je Microsoft ne podržava. Brisanje osnovne lokacije će da sve SharePoint lokacije u vašoj organizaciji može pristupiti svim korisnicima, dok ne vraćanje lokacije ili da kreirate novu lokaciju na istom URL adresi. 
 
 
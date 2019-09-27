---
title: Lokacija podataka
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: 0e683c8266d425be95e87c590d4cb5d56108721a
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207275"
---
# <a name="data-location"></a>Lokacija podataka

Možete da prikažete lokaciju Office 365 tenanta u okviru administratorskog centra ili tako što ćete se povezati sa Exchange online putem PowerShell.


**Admin Center:**
1. Prijavite se u [admin Center](https://admin.microsoft.com/Adminportal/Home).
2. Izaberite **Postavke** > za**Organizacioni profil**.
3. U okviru **lokacije sa podacima**izaberite stavku **Prikaži detalje**.


**PowerShell**
1. Povezivanje sa Exchange mrežom pomoću Windows PowerShell.
2. Izvođenje " [get-Organizacionalne jedinice](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) " cmdme da biste prikazali listu svojih staničnih svojstava. 
3. Pogledajte svojstvo "OrganizationId".

Kada imate lokaciju podataka za EXO i SPO, možete da utvrdite lokaciju podataka za druge usluge koje možete koristiti sa [mesta na kojima se podaci nalaze](https://products.office.com/where-is-your-data-located).
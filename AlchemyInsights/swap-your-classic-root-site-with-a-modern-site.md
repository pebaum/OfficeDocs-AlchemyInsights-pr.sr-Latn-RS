---
title: Razmenite tvoj Classic osnovna lokacija sa modernim lokacije
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: 0f6f962314d9099bd21c281a23ad2e95742da4a8
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270758"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Razmenite tvoj Classic osnovna lokacija sa modernim lokacije

Ako vaše okruženje je uspostavljen pre aprila 2019, možete da promenite svoje osnovne lokacije na moderne lokaciju koristeći Microsoft PowerShell:

- Ako imate neku drugu lokaciju na koju želite da koristite kao svoje osnovne lokacije, možete zameniti () osnovne sajtu to. 
    - Koristite [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) da razmenite adresu lokacije sa neke druge lokacije tokom arhiviranja originalne lokacije. Dostupno za lokaciju tima (nije povezan sa grupom), kao i komunikacija lokacije. 

- Dodatne mogućnosti će biti uveden uskoro to će vam omogućiti da nastavite da koristite sadržaj na lokaciji, ali konvertovanje postojeće lokacije na lokaciju za komunikaciju. 
>[!Important]
>Ove mogućnosti će biti poništena postepeno. Nastavite da proverite u Office 365 centar za poruke za ispravke. 

## <a name="known-issues-with-swapping-sites"></a>Poznati problemi sa zamenjivanje lokacije

- Na ciljnoj lokaciji može vratiti grešku „nije pronađeno” (HTTP 404) kratak period vremena.
- Sadržaj će morati da bude recrawled da biste ažurirali indeks za pretraživanje. Nema ručnu stepeništa potrebno - to će biti urađeno automatski.
- Sve zavisi od „statična” veze (kao što je datoteka za sinhronizaciju i OneNote datoteke) će treba ispraviti ručno.
- Ako izvorna lokacija bila lokaciju organizacione vesti, ažurirati URL adrese.Dobijete listu svih organizacionih nove sajtove.
- Project Server lokacije možda će biti potrebno da se vrši da biste bili sigurni da su oni povezani i dalje ispravno.






---
title: Uslovni pristup sa Intune
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: c9c47d71b2da3840504d5b28c7c9e067b4c05fa5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706035"
---
# <a name="conditional-access-with-intune"></a>Uslovni pristup sa Intune

Korišćenje **uslovnog pristupa** sa Intune zahteva 3 koraka: 
  
- Kreirajte **smernice za uslovno pristup** koje određuju koji resursi se štite i koji uslovi treba da budu ispunjeni da bi pristupili tim resursima. Na primer, uređaj mora biti usaglašen sa pristupom korporativnoj e-pošti. 
    
- Kreirajte **smernice usaglašenosti** da biste definisali postavke koje moraju da se ispune pre nego što se taj uređaj smatra usaglašen. Na primer, uređaj mora da ima PIN kôd od najmanje 6 cifara pre nego što se smatra usaglašen. 
    
- Obezbeđivanje **smernica usaglašenosti** i **smernica uslovnog pristupa** usmerena su na željene grupe korisnika. Ovo može zahtevati Kreiranje određenih grupa korisnika u Azure aktivnom direktorijumu. 
    
Opširnije:
  
- [Najbolje prakse uslovnog pristupa](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Prvi koraci sa uslovnim pristupom](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


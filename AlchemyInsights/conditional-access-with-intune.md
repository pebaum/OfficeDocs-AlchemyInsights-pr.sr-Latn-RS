---
title: Uslovni pristup sa Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/25/2019
ms.locfileid: "36505008"
---
# <a name="conditional-access-with-intune"></a>Uslovni pristup sa Intune

Korišćenje **uslovnog pristupa** sa Intune zahteva 3 koraka: 
  
- Kreirajte **smernice za uslovno pristup** koje određuju koji resursi se štite i koji uslovi treba da budu ispunjeni da bi pristupili tim resursima. Na primer, uređaj mora biti usaglašen sa pristupom korporativnoj e-pošti. 
    
- Kreirajte **smernice usaglašenosti** da biste definisali postavke koje moraju da se ispune pre nego što se taj uređaj smatra usaglašen. Na primer, uređaj mora da ima PIN kôd od najmanje 6 cifara pre nego što se smatra usaglašen. 
    
- Obezbeđivanje **smernica usaglašenosti** i **smernica uslovnog pristupa** usmerena su na željene grupe korisnika. Ovo može zahtevati Kreiranje određenih grupa korisnika u Azure aktivnom direktorijumu. 
    
Opširnije:
  
- [Najbolje prakse uslovnog pristupa](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Prvi koraci sa uslovnim pristupom](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


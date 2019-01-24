---
title: Conditional Access sa Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487966"
---
# <a name="conditional-access-with-intune"></a>Conditional Access sa Intune

Koristeći **Conditional Access** sa Intune zahteva 3 koraka: 
  
- Kreiranje **Smernica za uslovno pristup** koji definiše koji resursi su zaštićena, a koji uslovi treba da se ispune da pristupite tih resursa. Na primer, uređaj mora biti usaglašen pre pristupanja korporativni email. 
    
- Kreiranje **Politika usklađenosti** da definišete postavke koje moraju da se ispune da bi uređaj se smatra usaglašeni. Na primer, uređaj mora da ima pin najmanje 6 cifara smatra se usaglašen. 
    
- Osiguravanje **Usklađenosti politike** i **Uslovnog pristupa politike** su namenjene željene grupe korisnika. Ovo može da zahteva kreiranje određene grupe korisnika u sistemu Active Directory Azure. 
    
Opširnije:
  
- [Uslovnog pristupa najbolje prakse](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [Prvi koraci sa Conditional Access](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


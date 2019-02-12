---
title: Conditional Access sa Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 2e778bf4fbdb766700fb24b3405b4ddce89253f7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29935964"
---
# <a name="conditional-access-with-intune"></a>Conditional Access sa Intune

Koristeći **Conditional Access** sa Intune zahteva 3 koraka: 
  
- Kreiranje **Smernica za uslovno pristup** koji definiše koji resursi su zaštićena, a koji uslovi treba da se ispune da pristupite tih resursa. Na primer, uređaj mora biti usaglašen pre pristupanja korporativni email. 
    
- Kreiranje **Politika usklađenosti** da definišete postavke koje moraju da se ispune da bi uređaj se smatra usaglašeni. Na primer, uređaj mora da ima pin najmanje 6 cifara smatra se usaglašen. 
    
- Osiguravanje **Usklađenosti politike** i **Uslovnog pristupa politike** su namenjene željene grupe korisnika. Ovo može da zahteva kreiranje određene grupe korisnika u sistemu Active Directory Azure. 
    
Opširnije:
  
- [Uslovnog pristupa najbolje prakse](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Prvi koraci sa Conditional Access](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


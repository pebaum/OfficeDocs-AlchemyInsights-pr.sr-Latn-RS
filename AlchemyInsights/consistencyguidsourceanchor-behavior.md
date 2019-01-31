---
title: ConsistencyGuid / sourceAnchor ponašanje
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 010474bcc4cc6f97bcaafef9dfe6f4accfed4247
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29659605"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor ponašanje

Azurno AD povezivanje (verzija 1.1.524.0 i posle) sada olakšava upotrebu msDS-ConsistencyGuid kao atribut sourceAnchor. Kada koristite ovu funkciju, Azure AD Poveži se automatski podešava sinhronizaciju pravila da:
  
- Koristite msDS-ConsistencyGuid kao atribut sourceAnchor za objekte korisnika. ObjectGUID se koristi za druge tipove objekata.
    
- Za bilo koga s obzirom na lokalne AD korisnik objekat čija msDS-ConsistencyGuid atribut nije naseljena, Azure AD povezivanje upisuje njenu vrednost objectGUID nazad atribut msDS-ConsistencyGuid u Aktivnom direktoriju na više lokacija. Nakon što je atribut msDS-ConsistencyGuid je naseljena, Azure AD povezivanje onda izvozi objekat azurno AD.
    
 **Napomena:** Jednom je lokalne AD objekat uvezu u Azure AD povezivanje (to jest, uvesti u reklamni prostor spajanja i predviđena u u Metaverse), više ne možete promeniti njegovu sourceAnchor vrednost. Da biste naveli vrijednost sourceAnchor za neki s obzirom na lokalne AD prigovor, podesite svoj atribut msDS-ConsistencyGuid pre nego što se ona uvozi u Azure AD povezivanje. 
  
Za više informacija o SourceAnchor i ConsistencyGuid, obratite pažnju na sledeće: [Azure AD povezivanje: dizajn koncepte](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  


---
title: Greška AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7a97d1a5ff352b55833bd457e3220a56130d7e7e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499648"
---
# <a name="error-attributevaluemustbeunique"></a>Greška: AttributeValueMustBeUnique

Najčešći razlog za greške u AttributeValueMustBeUnique je da se dva objekta sa različitim SourceAnchor (immutableId) imaju istu vrednost za ProxyAddresses i/ili UserPrincipalName atribute. Da ispravim grešku AttributeValueMustBeUnique:
  
1. Identifikujte otisnutim proxyAddresses, userPrincipalName ili druge vrednosti atributa koji uzrokuje grešku. Takođe, odredi koje dva (ili više) objekti su učestvovale u ratu. Izveštaj generiše Azure AD povezivanje zdravlja za sinhronizaciju može vam pomoći da identifikujete dva objekta.
    
2. Identifikujte koji objekat treba da i dalje duplirana vrednost i koji objekat ne bi trebalo.
    
3. Uklonite duplicirati vrednost iz objekta koji ne bi trebalo da tu vrednost. Imajte na umu treba da promene u direktorijumu gde je označeni od strane objekta. U nekim slučajevima, možda će biti potrebno da izbrišete jedan od objekata u sukobu.
    
4. Ako ste napravili promene u prostorijama na AD, neka Azure AD povezivanje sinhronizaciju promena za grešku da se popravi.
    


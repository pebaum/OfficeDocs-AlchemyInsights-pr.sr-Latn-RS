---
title: Greška Pripisutevaluemustbejedinstvena
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: fa1fdb35f1af250bc98aa61c0e5111f1f1b8aac4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703188"
---
# <a name="error-attributevaluemustbeunique"></a>Greška: Pripisutevaluemustbejedinstvena

Najčešći razlog za grešku "Pripisutevaluemustbejedinstvena" je dva objekta sa različitim vrednostima izvora (immutableId) koji imaju istu vrednost atributa ProxyAddresses i/ili UserPrincipalName. Da biste ispravili grešku "Pripisutevaluemustbejedinstvena":
  
1. Identifikujte duplirane proxyAddresses, userPrincipalName ili drugu vrednost atributa koja uzrokuje grešku. Takođe Identifikujte koji dva (ili više) objekta su uključeni u neusaglašenost. Izveštaj koji je generisao "Azure" za povezivanje sa uslugom za sinhronizaciju može vam pomoći da identifikujete dva objekta.
    
2. Identifikujte objekat koji bi trebalo da nastavi da ima duplu vrednost i koji objekat ne bi trebalo da se nalazi.
    
3. Iz objekta uklonite duplu vrednost koja ne bi trebalo da ima tu vrednost. Imajte u vidu da bi trebalo da izvršite promenu u direktorijumu u kome je objekat povezan. U nekim slučajevima će možda biti potrebno da izbrišete jedan od objekata koji su neusaglašeni.
    
4. Ako ste napravili promenu u prostorijama oglasa, dopustite da se Azure reklama poveže sinhronizacija promena da se greška otkloni.
    


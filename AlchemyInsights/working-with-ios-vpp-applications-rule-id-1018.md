---
title: Rad sa iOS VPP aplikacija pravilo Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 5bcfb6dd7222bd102ff2620c19bfb943e7bd9591
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310350"
---
# <a name="working-with-ios-vpp-applications"></a>Rad sa iOS aplikacije VPP

Čitao [kako upravljati iOS aplikacije dobavljena pomoću volumena nabavke program sa Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) da biste saznali više o funkcijama, ograničenja i korake kako bi koristiti Apple volumena nabavke programa, kao i podršku za to u Microsoft Intune. 
  
 **Uobičajene probleme:** „Aplikaciju za iOS VPP je dodeljen moji korisnici, ali je instalacija nije uspjela”. 
  
- Ovo se može dogoditi ako jedan VPP token koristi preko više dobavljača za upravljanje mobilnim uređajem. VPP simboli iz jabuke se može koristiti samo kod jednog dobavljača. Ako ste koristili oznaku za VPP sa više dobavljača, morate ponovo da otpremite simbol da Intune.
    
- Instalaciju možete takođe propasti ako ukupan broj instalacija premašiti broj licenci. Da biste prikazali izveštaj o korišćenju za vaše licence, idi da **Intune mobilne aplikacije** \> **aplikacija za licence** stranice. Da biste saznali kako da povratite licence u upotrebi, pogledajte [Ovaj članak.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    


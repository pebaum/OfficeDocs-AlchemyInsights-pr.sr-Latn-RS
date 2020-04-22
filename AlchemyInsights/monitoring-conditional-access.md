---
title: Nadgledanje uslovnog pristupa
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 8b76d58791408037b5704b421d7afa166e3ea0be
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713732"
---
# <a name="monitoring-conditional-access-for-exchange"></a>Praćenje uslovnog pristupa za Exchange

Korisnici usmereni sa uslovnim pristupom dobiće obaveštenje e-poštom ako ne zadovoljavaju zahteve za pristup vašoj organizaciji. Da biste rešili, preporučujemo neka od sledećih rešenja:
  
- Ako se pretpostavlja da se uređaj upisuje, posavetuj korisnika da ode u aplikaciju "portal Company" i proverite da li se pojavljuje na portalu kompanije. Ako to ne uradite, korisnik bi trebalo da upiše uređaj.
    
- Na "Azure" portalu idite **do \> Intune usklađenosti uređaja**. U okviru **nadgledanje** izaberite stavku **usaglašenost uređaja**. Prikažite izveštaj o usaglašenosti uređaja da biste proverili da li je korisnički uređaj označen kao usaglašen. 
    
- Na "Azure" portalu idite **do \> Intune usklađenosti uređaja**. U odeljku **Upravljanje**kliknite na dugme **smernice**. Na listi smernica za usaglašenost proverite da li je profil dodeljen uređaju vašeg korisnika. Ako nijedan profil nije dodeljen, Intune neće moći da potvrdi status usaglašenosti uređaja. 
    
- Uredite dodeljivanje uslovnog pristupa korisnika.
    
1. Na Azure portalu idite na **Intune \> smernice za uslovnu \> pristup**
    
2. Izaberite smernice sa liste
    
3. Izaberite stavku **korisnici i grupe**
    
4. Da biste određenim smernicama ciljali određene smernice, dodajte ih u listu " **Uključi** ". Da biste se uverili da je osoba izostavljena iz smernice, dodajte ih na listu **isključenih** . 
    
Opširnije: [kako nadgledati uređaje za uslovnu pristup](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)
  


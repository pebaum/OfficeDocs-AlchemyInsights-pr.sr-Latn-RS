---
title: Rešavanje problema sa programom Access je porekao poruke
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 1930edcfd14acc48ea77b66e2793654a3e6332cc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759814"
---
# <a name="troubleshoot-access-denied-messages"></a>Rešavanje problema sa programom Access je porekao poruke

Ako je neko dobio poruku "pristup je odbijen" u deljenoj fascikli u sistemu SharePoint, administrator kolekcije lokacija je možda omogućio "režim zaključenja korisnika ograničenog pristupa". Da biste isključili ovu opciju: 
  
1. Potražite lokaciju, kliknite na ikonu postavke, a zatim izaberite stavku **Postavke lokacije**.
    
2. U okviru stavke **Administracija kolekcije lokacija**izaberite stavku **funkcije kolekcije lokacija**.
    
3. Kliknite na dugme " **Deaktiviraj**" pored **Access režima za zaključavanje ograničenog pristupa**.
    
Poruka koja je odbijena za pristup može da se pojavi i za deljene fascikle ako je lokacija lokacija za objavljivanje. Za informacije pogledajte odeljak " [pristup nije dozvoljen" prilikom pristupanja deljenoj fascikli](https://go.microsoft.com/fwlink/?linkid=2004317).
  
Ako je neko dobio poruku "pristup odbijen" prilikom pokušaja prikaza zahteva za pristup, korisnik mora da bude dodat kao administrator kolekcije lokacija ili član grupe vlasnika lokacije. Više informacija potražite u članku [zabranjen pristup listi zahteva za pristup](https://go.microsoft.com/fwlink/?linkid=2004220).
  
Ako je korisnik dobio poruku "pristup je odbijen" Nakon uklanjanja iz aktivnog direktorijuma u okviru objekta, a zatim ponovo dodat, pogledajte odeljak " [pristup odbijen kada se korisnički nalog sinhronizuje sa programom Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).
  


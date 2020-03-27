---
title: DLP ne radi na očekivani način
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 574a8a43d8264e98c6af2bfeb1bb472475e6e334
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977452"
---
# <a name="dlp-not-working-as-expected"></a>DLP ne radi na očekivani način

**Važno**: u ovakvim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive ostanu veoma dostupne – posetite [SharePoint online prilagođavanja](https://aka.ms/ODSPAdjustments) za više informacija.

 **Podešavanje DLP-a**

Da li imate problema sa **sprečavanjem gubitka podataka (DLP)** u sistemu Office 365 ne radi na očekivani način? Ako je tako, uverite se da je vaša **smernica za dlp** ispravno podešena i da podaci sadrže ono što ova **smernica za dlp** traži kada se proceni.
  
DLP smernice vam omogućavaju da identifikujete i zaštitite osetljive informacije u vašoj organizaciji. Da biste mogli da podesite DLP smernice, koristite [ovde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp)informacije.
  
 **Koje DLP smernice traže**
  
Prilikom korišćenja **ugrađenih tipova informacija** u sistemu Office 365 Security i centar za usaglašenost, dlp smernice traže određene šare i elemente kada otkrivaju ove osetljive tipove.
  
- **Ugrađeni tipovi osetljivih informacija**

    Za informacije o ugrađenim tipovima osetljivih tipova i o tome kako izgleda DLP smernica za otkrivanje osetljivih tipova, pogledajte: [koje tipove osetljivih informacija tražite](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).

- **Prilagođeni tipovi poverljivih informacija**

    Ako pokušavate da kreirate prilagođene tipove poverljivih podataka, koristite sledeći članak za informacije o tome kako da kreirate prilagođeni tip osetljive prirode: [Kreirajte prilagođeni tip poverljivih informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).

**Testiranje smernica za DLP**

Da biste testirali podatke pomoću ugrađenog ili prilagođenog tipa sa osetljivim informacijama, koristite opciju " **tip testa** " u okviru liste sa**osetljivim informacijama o** **klasifikaciji** > . Za više informacija pogledajte odeljak [testiranje prilagođenih osetljivih tipova informacija](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).

 **Izveštaje**
  
- Dobijte osetljive podatke u vezi sa [Dlp izveštajima.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)

- Pogledajte detaljne detalje o događaju sa [izveštajem o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).

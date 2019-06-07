---
title: Podešavanje DKIM u sistemu Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0f81fe02135f3d0901ffe5a26d7aa3dad70c3770
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765385"
---
# <a name="setup-dkim-in-office-365"></a>Podešavanje DKIM u sistemu Office 365

Kompletna uputstva za konfigurisanje DKIM za prilagođene domene u Office 365 su [ovde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

1. Za **svaku** prilagođenu domenu, morate da kreirate **dve** DKIM CNAME zapise kod vašeg domena DNS hosting servisa (obično u domenu prijavnicu). Na primer, contoso.com i fourthcoffee.com zahteva četiri DKIM CNAME zapisa: dva za contoso.com i dva za fourthcoffee.com.

   DKIM CNAME zapise za **svaku** prilagođenih domena koristite sledeće formate:

   - **Ime domaćina**:`selector1._domainkey.<CustomDomain>`

     **Tačke na adresu ili vrednost**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Ime domaćina**:`selector2._domainkey.<CustomDomain>`

     **Tačke na adresu ili vrednost**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\> je tekst sa leve strane `.mail.protection.outlook.com` u prilagođeni MX zapis za prilagođenih domena (na primer, `contoso-com` za u domenu contoso.com). \<InitialDomain\> je domen koji ste koristili kada ste se prijavili za Office 365 (na primer, contoso.onmicrosoft.com).

2. Nakon što ste kreirali CNAME zapise za tvoj prilagođenih domena, dovršite sledeće instrukcije:

   jedan. [Prijavite se na Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) uz svoj radni ili skola nalog.

   b. Izaberite aplikaciju pokretač ikonu u gornjem levom i odaberite **Admin**.

   c. U donjem levom navigaciji, proširite **Admin** i odaberite **Exchange**.

   d. Idite na **zaštitu** > **DKIM**.

   e. Izaberite domenu, a zatim odaberite **Omogući** za **znak poruke za ovaj domen sa DKIM potpisa**. Ponovite ovaj korak za svaku prilagođenih domena.

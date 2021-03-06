---
title: Podešavanje DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0acaed476dbd06bc933bf466f9bf6116413a44bb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509398"
---
# <a name="setup-dkim"></a>Podešavanje DKIM

Sva uputstva za konfigurisanje DKIM za prilagođene domene u sistemu Microsoft 365 su [ovde](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

1. Za **svaki** prilagođeni domen potrebno je da kreirate **dva** zapisa DKIM CNAME na DNS hosting u vašem domenu (obično je to registrator domena). Na primer, contoso.com i fourthcoffee.com zahtevaju četiri DKIM CNAME zapisa: dva za contoso.com i dva za fourthcoffee.com.

   Zapisi DKIM CNAME za **svaki** prilagođeni domen koriste sledeće formate:

   - **Ime domaćina**:`selector1._domainkey.<CustomDomain>`

     **Ukazuje na adresu ili vrednost**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Ime domaćina**:`selector2._domainkey.<CustomDomain>`

     **Ukazuje na adresu ili vrednost**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\>predstavlja tekst levo od `.mail.protection.outlook.com` PRILAGOĐENOG MX zapisa za prilagođeni domen (na primer, `contoso-com` za domen contoso.com). \<InitialDomain\>je domen koji ste koristili kada ste se prijavili za Microsoft 365 (na primer, contoso.onmicrosoft.com).

2. Nakon što ste kreirali zapise CNAME za svoje prilagođene domene, popunite sledeća uputstva:

   A. [Prijavite se u Microsoft 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomoću poslovnog ili školskog naloga.

   B. Izaberite ikonu pokretanja aplikacije u gornjem levom uglu i odaberite stavku " **admin**".

   C. U donjem levom navigaciji, razvijte **admin** i odaberite stavku **Exchange**.

   D. Idite na **zaštitu**  >  **dkim**.

   E. Izaberite domen, a zatim odaberite opciju **Omogući** za **potpisivanje poruka za ovaj domen sa dkim potpisima**. Ponovite ovaj korak za svaki prilagođeni domen.

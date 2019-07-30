---
title: Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "42"
- "43"
- "100002"
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: e437015d476c1417fa37e1b1c250e2205e9ce4d9
ms.sourcegitcommit: b825ced7b66d452b0f3874a57e033e690ec41c93
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/29/2019
ms.locfileid: "35925299"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a>Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga

1. Na stranici [domene](https://portal.office.com/adminportal/home#/Domains) , liste domena, izaberite domenu koristite za vašu Web lokaciju.

2. Izaberite **+ novi prilagođeni zapis** i unesite sledeće:

  - Unesite za **DNS tip** : **(adresa)**

  - U **ime domaćina ili pseudonim**, upišite sledeće:**@**

  - Za **IP adresu**, upišite statična IP adresa za vašu Web lokaciju gde se trenutno nalazi (na primer, 172.16.140.1).

    Ovo mora da je *statična* IP adresa za Web lokacije, ne *dinamičnu* IP adresu. Proverite sa lokacije gde vaša Web lokacija je bila je domaćin da proverite da li možete da dobijete statičnu IP adresu za vaše javne Web lokacije.

3. Izaberite **Sačuvaj**.

Osim toga, možete da kreirate CNAME zapis da bi pomogao korisnicima pronaći vašu Web lokaciju.
  
1. Izaberite **+ novi prilagođeni zapis** i unesite sledeće:

  - Unesite za **DNS tip** : **CNAME (Alias)**

  - Za **ime domaćina ili pseudonim**, otkucajte sledeće: **www**

  - Za **tačke na adresu**, upišite je potpuno određeno ime domena (FQDN) na svojoj Web lokaciji (na primer, contoso.com).

2. Izaberite **Sačuvaj**.

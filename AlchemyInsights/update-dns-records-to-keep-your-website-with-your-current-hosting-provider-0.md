---
title: Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga
ms.author: pebaum
author: pebaum
manager: mnirkhe
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
ms.openlocfilehash: 7bd36c3954d12d3ee4ac624a2f827d8e5cd88082
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665774"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a>Ažuriranje DNS zapisa da bi vaša Web lokacija sa svoje trenutne usluga hostinga

1. U centru za admin Microsoft 365, idite na **Podešavanje** > [domeni](https://portal.office.com/adminportal/home#/Domains) stranica i domena, izaberite liste domena koji koristite za vašu Web lokaciju.

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

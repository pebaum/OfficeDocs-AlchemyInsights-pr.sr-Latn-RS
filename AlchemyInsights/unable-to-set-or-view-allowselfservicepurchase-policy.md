---
title: Nije moguće podesiti ili prikazati smernicu Allowsebservicepurchase
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: a9b6e36e8034e71b3e72c49e3cc68a126ef97aca
ms.sourcegitcommit: cb9505f9eca032af3a4194c68d18c91789365690
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/16/2020
ms.locfileid: "42091758"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a>Nije moguće podesiti ili prikazati smernicu Allowsebservicepurchase

Kada pokušate da postavite ili prikažete smernicu Allowsebservicefurchase, dobićete sledeću poruku o grešci:

*Ručni greška: nije uspelo preuzimanje smernica proizvoda pomoću programa PolicyId ' Allowsamoservicepurchase ', greška-osnovna veza je zatvorena: došlo je do neočekivane greške prilikom slanja.*

Do ovoga je možda došlo zbog starije verzije bezbednosti sloja transporta (TLS). Da biste povezali MSCommerce uslugu, potrebno je da koristite TLS 1,2 ili noviji.  

Pokušajte sledeće korake da biste omogućili/podesili TLS protokol na 1,2, proverite i pokušajte ponovo.
 1. Na komandnoj liniji PowerShell (PS C:\) unesite sledeću komandu da biste podesili TLS protokol na verziju 1,2:

    \[Net. Servicepoinmanager]:: SecurityProtocol = \[net. Securityprotokoltype]:: Tls12

2. Provjerite TLS Protocol (e) u upotrebi, sa sledećom komandom:

    \[Net. Servicepoinmanager]:: SecurityProtocol 

3. Ponovo pokušajte da dobijete ili ažurirate komande po potrebi.


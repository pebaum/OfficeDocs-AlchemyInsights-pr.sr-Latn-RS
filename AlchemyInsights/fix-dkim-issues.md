---
title: Popravi DKIM instaliranja sustava
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765373"
---
# <a name="fix-dkim-setup-issues"></a>Popravi DKIM instaliranja sustava

Ako dođe do problema, što će omogućiti DKIM vašeg prilagođenih domena, slijedite ove korake:

- Većina DKIM instaliranja sustava se odnose na neispravan DNS zapisa. Proverite DKIM CNAME zapis (**ne** TXT zapis) ispravno formatiran. Za više informacija, pročitajte ovu [temu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Nakon te kreirate ili ažurirate DKIM DNS zapise u na DNS hosting servis vašeg domena (obično tvoj domena specijalista), stani za DNS zapise da propagira.

- Ako ne možete da kreirate na DKIM DNS zapise u admin centru, možete zameniti \<CustomDomain\> sa vašeg prilagođenih domena (na primer, contoso.com) i pokrenete ovu komandu u [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.

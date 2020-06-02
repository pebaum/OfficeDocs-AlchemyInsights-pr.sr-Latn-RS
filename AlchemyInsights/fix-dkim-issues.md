---
title: Rešavanje problema sa DKIM instalacijom
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 8195b0e3fada6da033b2d95b1fc6600e7fa3341e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506788"
---
# <a name="fix-dkim-setup-issues"></a>Rešavanje problema sa DKIM instalacijom

Ako imate problema sa omogućavanjem DKIM za prilagođeni domen, koristite sledeće korake:

- Većina problema sa instalacijom je povezana sa netačnim DNS zapisima. Proverite da li je zapis DKIM CNAME (**nije** zapis txt) ispravno formatiran. Za više informacija pogledajte ovu [temu](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

- Kada kreirate ili ažurirate svoje DKIM DNS zapise u usluzi DNS hosting za vaš domen (obično, registrator domena), sačekajte da se DNS zapisi prenose.

- Ako ne možete da kreirate DKIM DNS zapise u okviru administratorskog centra, možete da ga zamenite \<CustomDomain\> prilagođenim domenom (na primer, contoso.com) i pokrenete ovu komandu u [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .

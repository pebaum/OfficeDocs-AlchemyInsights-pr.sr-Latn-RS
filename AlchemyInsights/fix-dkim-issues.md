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
ms.openlocfilehash: d725eb0d46dcbf1b5b6d77ca9f59fcafa5298bf1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43717576"
---
# <a name="fix-dkim-setup-issues"></a>Rešavanje problema sa DKIM instalacijom

Ako imate problema sa omogućavanjem DKIM za prilagođeni domen, koristite sledeće korake:

- Većina problema sa instalacijom je povezana sa netačnim DNS zapisima. Proverite da li je zapis DKIM CNAME (**nije** zapis txt) ispravno formatiran. Za više informacija pogledajte ovu [temu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Kada kreirate ili ažurirate svoje DKIM DNS zapise u usluzi DNS hosting za vaš domen (obično, registrator domena), sačekajte da se DNS zapisi prenose.

- Ako ne možete da kreirate DKIM DNS zapise u okviru administratorskog centra, možete da zamenite \<\> prilagođeni domen prilagođenim domenom (na primer, contoso.com) i pokrenete ovu komandu u [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.

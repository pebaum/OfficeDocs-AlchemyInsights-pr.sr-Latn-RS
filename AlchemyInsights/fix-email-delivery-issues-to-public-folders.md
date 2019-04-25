---
title: Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 45665f900014c52e6a920325b0a3b0f6f79fb72d
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32401455"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama

Ako spoljni pošiljaoci mogu da šalju poruke za svoje javne fascikle sa omogućenom e-poštom i pošiljalaca dobiti grešku: **nije moguće pronaći (550 5.4.1)**, provjerite e-mail domena za javna fascikla je konfigurisan kao domena za interni relej umesto da je autoritativnih domena:

1. Otvorite [Centar za admin Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Idite na **tok pošte** \> **prihvaćeno domeni**, izaberite prihvaćena domena, a zatim izaberite stavku **Uredi**.

3. U svojstvima stranica taj otvara, ako tip domena podešen na **autoritativno**, promenite vrednost u **unutrašnje relej** i izaberite stavku **Sačuvaj**.

Ako spoljni pošiljaoci dobijate greške **nemate dozvolu (550 5.7.13)**, pokrenite sledeću komandu u [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) vidjeti dozvole za anonimne korisnike u javnoj fascikli:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Na primer, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Da biste dozvolili spoljnim korisnicima da šalju e-poruke ovoj javnoj fascikli, dodati CreateItems pristup redu anonimni korisnik. Na primer, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.

---
title: Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 900b6cc2765937ee005c7e7dce5d33bbdf582601
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752690"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Rešite probleme isporuku e-pošte da rade sa e-poštom javnim fasciklama

Ako spoljni pošiljaoci mogu da šalju poruke za svoje javne fascikle sa omogućenom e-poštom i pošiljalaca dobiti grešku: **nije moguće pronaći (550 5.4.1)**, provjerite e-mail domena za javna fascikla je konfigurisan kao domena za interni relej umesto da je autoritativnih domena:

1. Otvorite [Centar za admin Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Idite na **tok pošte** \> **prihvaćeno domeni**, izaberite prihvaćena domena, a zatim izaberite stavku **Uredi**.

3. U svojstvima stranica taj otvara, ako tip domena podešen na **autoritativno**, promenite vrednost u **unutrašnje relej** i izaberite stavku **Sačuvaj**.

Ako spoljni pošiljaoci dobijate greške **nemate dozvolu (550 5.7.13)**, pokrenite sledeću komandu u [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) vidjeti dozvole za anonimne korisnike u javnoj fascikli:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Na primer, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Da biste dozvolili spoljnim korisnicima da šalju e-poruke ovoj javnoj fascikli, dodati CreateItems pristup redu anonimni korisnik. Na primer, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.

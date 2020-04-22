---
title: Popravljanje problema sa isporukom e-pošte u javne fascikle koje su omogućene za poštu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716366"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Popravljanje problema sa isporukom e-pošte u javne fascikle koje su omogućene za poštu

Ako spoljni pošiljaoci ne mogu da šalju poruke u javne fascikle omogućene za poštu, a pošiljaoci dobijaju grešku: **nije bilo moguće pronaći (550 5.4.1)**, proverite da li je domen e-pošte za javnu fasciklu konfigurisan kao interni domen prenosa, a ne pouzdane domene:

1. Otvorite [Exchange admin Center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Idite na **tok** \> pošte **prihvaćeni domeni**, izaberite prihvaćeni domen, a zatim kliknite na dugme **Uredi**.

3. Na stranici sa svojstvima koja se otvara, ako je tip domena postavljen na **pouzdane**, promenite vrednost u **interni relej** i zatim kliknite na dugme **Sačuvaj**.

Ako spoljni pošiljaoci dobiju grešku nemate **dozvolu (550 5.7.13)**, pokrenite sledeću komandu u programu [Exchange online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) da biste videli dozvole za anonimne korisnike u javnoj fascikli:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Na primer, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Da biste dozvolili spoljnim korisnicima da šalju e-poruke u ovu javnu fasciklu, dodajte pravo pristupa za Createstavke korisniku anonimnom. Na primer, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.

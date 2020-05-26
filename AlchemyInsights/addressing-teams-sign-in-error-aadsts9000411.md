---
title: Adresiranje za prijavljivanje timova AADSTS9000411
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/20/2020
ms.locfileid: "44358370"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a>Adresiranje za prijavljivanje timova AADSTS9000411

Kada se prijavljujete u Microsoft timove, možete dobiti grešku: **Žao mi je, ali imamo problema sa prijavljivanjem u AADSTS9000411: zahtev nije ispravno oblikovan. "Login_hint" je duplirana.**

Da biste rešili ovaj problem, proverite da li su vaši Microsoft timovi klijenti ažurirani. Za više informacija o ažuriranju klijenta pogledajte odeljak [Ažuriranje Microsoft timova](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

Ako ne možete da ažurirate klijenta iz nekog razloga, odjavljivanje sa klijenta će obrisati većinu keširanih podataka. Međutim, ako i dalje imate problema nakon odjavljivanja/prijavljivanja, napustite timove i obrišite keš memoriju na sledeći način:
1. Zatvorite Microsoft timove.
2. Posetite lokaciju:%AppData%\microsoft\teams i izbrišite sve datoteke.
3. Ponovo otvorite Microsoft timove.

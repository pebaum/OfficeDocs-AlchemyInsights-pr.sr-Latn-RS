---
title: 618 smernice za deljenje kalendara
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/26/2020
ms.locfileid: "44373013"
---
# <a name="policy-error-when-sharing-a-calendar"></a>Greška u smernicama prilikom deljenja kalendara

1. Izvršite jednu od sledećih radnji, u skladu sa vašom situacijom:
    - Povezivanje na Exchange online pomoću daljinskog upravljača PowerShell. Više informacija potražite u članku [Povezivanje sa Exchange serverom putem daljinskog upravljača](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).
    - Na serveru na kome je otvorena Exchange Management Shell.
2. Utvrdite smernice za deljenje koje su dodeljene korisniku. Da biste to uradili, pokrenite sledeću komandu i zabeležite smernice koje ste vratili:

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. Ažurirajte smernice za deljenje za korisnika. Da biste to uradili, sledite ove korake:
    - Otvorite Exchange admin Center.
    - Izaberite stavku **organizacija**, a zatim dvaput kliknite na smernice koje su dodeljene korisniku pod **pojedinačnim deljenjem**. Ovo je politika koja je vraćena u koraku 2.
    - Na stranici "pravilo deljenja" izaberite nivo deljenja kalendara koji želite da dozvolite u okviru **navedite koje informacije želite da delite**. Kliknite na dugme **Sačuvaj**.

Za više informacija pogledajte: ["smernice ne dozvoljavaju dodeljivanje dozvola na ovom nivou jednom ili više primalaca" kada korisnik pokuša da deli kalendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).

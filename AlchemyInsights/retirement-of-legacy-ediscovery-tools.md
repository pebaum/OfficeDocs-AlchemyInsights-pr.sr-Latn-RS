---
title: Penzionisanje zastarelog eDiscovery alata
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: c4632b52dde579b7d5b2e6e15f1583300a0bd136
ms.sourcegitcommit: a7c17217c170ead24571421baaf5a14f1525b1a6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/20/2020
ms.locfileid: "42157700"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a>Penzionisanje zastarelog eDiscovery alata

Kao rezultat nove i poboljšane eDiscovery funkcionalnosti u centru za usaglašavanje u operativnom sistemu Microsoft 365, sledeće zastarele eDiscovery alatke i zaobe će biti penzionisane narednih meseci:

- [Na mestu eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) i [na mestu koje ima](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) Exchange admin Center.

- Exchange online PowerShell cmdlet komandi koje podržavaju mesto eDiscovery i na mestu. (Ove cmdlet se kolektivno identifikuju kao *-MailboxSearch cmdlet.) Ovo obuhvata sledeća cmdlet:

    - [Nova-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [Započni-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [Zaustavi-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [Set-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- [Pretraga-poštansko sanduče](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdmo u Exchange online PowerShell.
- Sledeće operacije u API Exchange Web usluga:
    - [Getsearchablemailbox](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [Setholdonpoštanske sandučići](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [Getholdonpoštanske sandučiće](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [Office 365 Advanced eDiscovery v 1.0](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

**Vremenska osa za penziju**:
- April 1, 2020: nećete moći da kreirate nove pretrage i zadrškama, ali i dalje možete da pokrećete, uređujete i brišete postojeće pretrage na vlastitu odgovornost. Microsoft podrška više neće podržavati eDiscovery & zauzima u EAC-u.

- 1. jul 2020: eDiscovery na mesto & sadrži funkcionalnost u okviru EAC-a biće smeštena u režim samo za čitanje. To znači da ćete moći da uklonite samo postojeće pretrage i zadrškama.

**Više informacija potražite u članku**:

 - [Migriranje nasleđenih eDiscovery pretraga i zadrška za Microsoft 365 centar za usaglašavanje](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [Penzionisanje zastarelog eDiscovery alata](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [Najčešća pitanja o eDiscovery i na mestu na kojem se nalazi mesto](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)




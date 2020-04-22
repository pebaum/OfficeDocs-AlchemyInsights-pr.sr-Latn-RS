---
title: 2491 obaveštenja e-poruke iz ' Phish dostavljene zbog načela tenanta ili zamene korisnika
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2e4efd504304da757687e697ff23374aeea31851
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758946"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Obavesti e-poruke sa ' Phish isporučenim zbog smernica za zatezivanje ili zamenu korisnika

Podrazumevane smernice za upozorenje pod nazivom "Phish isporučeno zbog tenanta ili korisničke zamene" su isporučene u stanari sa Office 365 ATP P1 i P2 licence. Ako ste primili ovo obaveštenje, evo koraka za istraživanje:

1. Iz poruke obaveštenja kliknite na dugme " **Prikaži obaveštenje** " da biste otišli na stranicu " **obaveštenja** " u centru za bezbednost &.

2. Izaberite obaveštenje da biste videli opciju za **Prikazivanje liste poruka** ili **Prikazivanje poruka u programu Explorer**. Obe opcije će vas odvesti do detalja poruke, koja uključuje ID poruke. Imajte na umu da će veza "Explorer za pretnje" automatski filtrirati poruke koje odgovaraju kriterijumu obaveštenja. Možda će biti potrebno da podesite filter datuma u istraživaču pretnji.

Prevarantska poruka je isporučena zbog ručnog konfigurisanog zamene:

- Dozvoljen pošiljalac ili domen koji je postavio korisnik.

- Dozvoljen pošiljalac ili domen koji je postavio administrator u smernicama za borbu protiv bezvredne pošte.

- Dozvoljena IP adresa u smernicama filtera veze.

- Pravilo toka pošte (poznato i kao pravilo prevoza) konfigurirano je tako da dozvoljava poruke.

Ako smatrate da je poruka nepravilno označena kao Phish, koristite [programski dodatak poruke u Outlook izveštaju](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) da biste prosledili uzorke poruka korporaciji Microsoft.

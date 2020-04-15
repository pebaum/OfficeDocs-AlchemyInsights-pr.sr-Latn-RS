---
title: Postavljanje automatskih odgovora za poštansko sanduče
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000761"
- "3514"
ms.openlocfilehash: aeeb2e1e76fe602d2767b422797452fd1155fdd5
ms.sourcegitcommit: fdfd41c2bfb2d45003b3906e6469377384a91cb5
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/15/2020
ms.locfileid: "43509515"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a>Postavljanje automatskih odgovora za poštansko sanduče korisnika

**Metod 1**

1. Prijavljivanje na Office 365 portal.

2. Idite na **korisnici > aktivni korisnici** (ili **grupe > deljeni poštanski sandučići ** ako je postavite na deljeno poštansko sanduče).

3. Izaberite korisnika koji ima Microsoft Exchange poštansko sanduče.

4. U dodatnom meniju nadesno idite na **postavke pošte > automatski odgovori **(ako je u pitanju deljeno poštansko sanduče, samo kliknite **automatski odgovori **u dodatnom meniju).

**Metod 2**

1. Prijavite se na portal Office 365 administrator pomoću akreditiva administratora.

2. Proširite ** centre za administraciju **, a zatim izaberite stavku ** Exchange **.

3. Kliknite na sliku u gornjem desnom uglu, izaberite stavku**još jedan korisnik **, a zatim kliknite na korisničko poštansko sanduče koje želite da promenite.

4. Na levoj strani izaberite stavku **opcije **, izaberite stavku **organizovanje e-pošte **, a zatim kliknite na dugme **automatski odgovori.**

**Metod 3**

Pokrenite sledeće cmdlet komandu stavke u usluzi Exchange Online Windows PowerShell:

PowerShellCopy

```
    Set-MailboxAutoReplyConfiguration
```

Više informacija o ovoj cmdlet komandi potražite u članku [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).

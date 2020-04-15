---
title: Postavljanje automatskih odgovora za poštansko sanduče korisnika
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
ms.openlocfilehash: e3cc01298c10fd3ba21327a7fb5cc5396d0ad74d
ms.sourcegitcommit: 23e5b94f1758bfe202008384e300b81816975375
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/14/2020
ms.locfileid: "43506646"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a>Postavljanje automatskih odgovora za poštansko sanduče korisnika

**Metod 1**

1. Prijavljivanje na Office 365 portal.

2. Idite na stavku**Korisnici > Aktivni korisnici** (ili **Grupe > Deljeni poštanski sandučići ** ako ste postavili ovo na deljeno poštansko sanduče).

3. Izaberite korisnika koji ima Microsoft Exchange poštansko sanduče.

4. U dodatnom meniju nadesno idite na **Postavke pošte > Automatski odgovori **(ako je u pitanju deljeno poštansko sanduče, samo kliknite **Automatski odgovori **u dodatnom meniju).

**Metod 2**

1. Prijavite se na portal Office 365 administrator pomoću akreditiva administratora.

2. Proširite **Centre za administraciju **, a zatim kliknite na stavku ** Exchange **.

3. Kliknite na sliku u gornjem desnom uglu, kliknite na stavku**Još jedan korisnik **, a zatim izaberite korisničko poštansko sanduče koje želite da promenite.

4. Na levoj strani izaberite stavku **Opcije **, kliknite na stavku **Organizovanje e-pošte **, a zatim kliknite na dugme **Automatski odgovori.**

**Metod 3**

Pokrenite sledeće cmdlet komandu u usluzi Exchange Online Windows PowerShell:

PowerShellCopy

    Set-MailboxAutoReplyConfiguration

Više informacija o ovoj cmdlet komandi potražite u članku [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).

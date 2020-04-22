---
title: S/MIME u Outlooku na Webu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 7184ffd68f56639a8bcb87e9c6cab88388868103
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764886"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrovanje e-poruka u programu Outlook

Microsoft 365 šifrovanje poruka je ugrađeno na Microsoft Azure Rights Management (Azure RMS), što je deo zaštitne zaštite informacija. Ako vaša pretplata uključuje uslugu Azure Rights Management ili Azure zaštitu informacija, **Ne morate da preduzmete radnje da biste ručno omogućili ili aktivirali** usluge upravljanja pravima.

Na osnovu povratnih informacija korisnika, više nećemo biti u toku omogućavanje pravila protoka pošte za Exchange da biste automatski šifrovali odlaznu e-poštu koja sadrži određeni tip osetljivih informacija u vašem stanantu. Umesto toga, obezbeđujemo detaljna uputstva o tome kako to možete učiniti sami. Dodatne informacije o kreiranju pravila transporta za šifrovanje osetljivih informacija potražite u [ovom članku](https://aka.ms/OmeEtr).

- Ako koristite Outlook na Webu **(ranije ove**): kada pišete e-poruku, jednostavno kliknite na dugme " **zaštiti** u owi". Ovo će primeniti dozvolu "ne prosleđi". Kliknite na dugme " **Promeni dozvolu** " i odaberite opciju " **Šifruj** " da biste šifrovali poruku.

- Ako koristite **Outlook Client**: da biste poslali šifrovanu poruku iz programa Outlook 2013 ili 2016 ili Outlook 2016 za Mac, izaberite **Opcije** > **dozvole**, a zatim izaberite opciju za zaštitu koja vam je potrebna.

- Da biste **automatski šifrovali svu e-poštu** poslatu određenim primaocima ili organizacijama spoljnih partnera, potrebno je da u Exchange admin Center kreirate pravilo transporta toka pošte. U [ovom članku za podršku](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities)obezbeđeni su detaljna uputstva.


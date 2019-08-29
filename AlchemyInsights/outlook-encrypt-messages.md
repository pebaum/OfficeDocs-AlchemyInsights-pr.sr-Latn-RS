---
title: S/MIME u programu Outlook na Webu
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: f2c047ca31c586c0aa36701e6e7ca9976cfd1734
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666854"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrovanje poruke e-pošte u programu Outlook

Šifriranje poruka Office 365 se gradi na Microsoft Azure upravljanje pravima (Azure RMS), koji je deo Azure zaštite informacija. Ako vaša pretplata uključuje Azure Rights Management ili Azure informacije zaštitu, da **Ne treba da preduzmu bilo kakve radnje ručno omogućavanje ili aktivirati** uslugom za upravljanje pravima.

Na osnovu povratne informacije, smo će više biti omogućavanje pravila protok pošte Exchange automatski šifrovati izlazni e-pošta koja sadrži određene vrste osetljivih informacija u tvojim podstanarom po podrazumevanoj vrednosti. Umesto toga, pružamo detaljna uputstva na kako to možete učiniti sami. Za dodatne detalje o tome kako da kreirate transporta pravilo da biste šifrovali poverljive informacije, pogledajte [Ovaj članak](https://aka.ms/OmeEtr).

- Ako koristite Outlook na Webu (nekadašnja **OWA**): prilikom sastavljanja e-poruku, jednostavno kliknite na **zaštiti** u OWA. To će se odnositi „Uradi ne napred” dozvolu. Kliknite na dugme **Promeni dozvolu** i odabrati **šifrovanje** da samo prilikom šifrovanja.

- Ako koristite **Outlook kao klijentski program**: izaberite **Opcije**da biste poslali šifrovanu poruku iz programa Outlook 2013 ili 2016, ili Outlook 2016 za Mac > **dozvole**, a zatim izaberite opciju "Zaštita" ti treba.

- **Automatski šifrovati sve e-poštu** poslati na određene primaoce ili eksterni partnerske organizacije, morate kreirati pravilo pošte protok saobraćaja u centru za Admin Exchange. Detaljna uputstva su navedena u [ovom članku za podršku](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).


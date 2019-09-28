---
title: 2681 sa Simulatom napada na Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305345"
---
# <a name="attack-simulator-in-office-365"></a>Simulatoru napada u Officeu 365

- Da li nedostaje simulatoru napada? Simulatoru napada zahteva **Office 365 napredni plan zaštite pretnji 2 (ATP plan 2)** ili **Office 365 Enterprise E5**. Simulatoru napada **nije** uključen u Office 365 napredni plan zaštite pretnje 1 (ATP plan 1), Office 365 Enterprise E3 ili bilo koje Office 365 poslovne pretplate.

- Nalog koji koristite za pokretanje simuliranog napada zahteva globalne administratorske ili administratorske dozvole za zaštitu od više faktora (MFA). Za više informacija o zahtevima za simulatoru napada pogledajte [ovu temu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).

- Važne stvari koje treba znati o **okrutne sile napada lozinke** :

  - Ako je ciljni nalog omogućen MFA, a lozinka je ispravno pogodila, nalog neće biti ugrožen (drugi faktor potvrde identiteta će biti nepotpun).

  - Datoteka sa lozinkama ne može da bude veća od 10 MB. Koristite jednu lozinku po redu, a zatim uključite prazan red (znak za kraj reda) nakon poslednje lozinke na listi.

- Važne stvari koje treba znati o **koplju phishing** Priloži simulacije:

  - Po dizajnu, ne možete da navedete prilagođenu vrednost za **URL adresu servera za prijavljivanje na phishing**.

  - Ako primalac koristi [programski dodatak "Omogući" poruke izveštaja](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) da prijavi poruku kao phishing, možda nećete primati obaveštenja za poruku (zato što je ovo simulirani napad).

- Izveštaji: Nakon dovršenog simuliranog napada, možete da izaberete stavku " **Detalji napada** " da biste videli izveštaj.

- Za detaljna uputstva i nove osobine na simulatoru napada pogledajte [simulatoru napada na Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

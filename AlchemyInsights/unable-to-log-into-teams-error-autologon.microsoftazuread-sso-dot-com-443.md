---
title: Nije moguće prijaviti se u Teams zbog greške autologon.microsoftazuread-sso.com:443
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9001686"
- "3750"
ms.openlocfilehash: 77049153939989d1c63789adfec0b494d047a6e4
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932032"
---
# <a name="unable-to-log-into-teams-due-to-error-autologonmicrosoftazuread-sso-dot-com443"></a>Nije moguće prijaviti se u Teams zbog greške autologon.microsoftazuread-sso dot com:443

Ako je omogućen automatski SSO kao potvrda identiteta za O365, možda ćete intranet sajtovima morati da dodate URL „autologon.microsoftazuread-sso.com“.  Ako je on već dodat na pouzdane sajtove i ako se automatski SSO koristi, treba ga ukloniti sa pouzdanih sajtova.

Pregledajte [Kontrolnu listu za rešavanje problema sa automatskim SSO prijavljivanjem](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).

Pratite ove korake da biste dodali URL na listu intranet sajtova:

1. Otvorite Internet Explorer klikom na dugme **Start**. U polje za pretragu unesite Internet Explorer, a zatim na listi rezultata kliknite na stavku **Internet Explorer**.
2. Kliknite na stavku **Alatke**, a zatim na stavku **Internet opcije**.
3. Izaberite karticu **Bezbednost**.
4. Sada kliknite na stavku **Lokalni intranet sajtovi**, zatim na dugme **Sajtovi**, pa na dugme **Napredno**.
5. Unesite URL veb sajta i kliknite na dugme **Dodaj**.
6. Kada završite, kliknite na dugme **Zatvori**.

Više informacija potražite u članku [Dokumentacija za primenu automatskog SSO prijavljivanja za O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (obuhvata proces zasnovan na smernicama za dodavanje URL adresa intranet sajtovima u 3. koraku).

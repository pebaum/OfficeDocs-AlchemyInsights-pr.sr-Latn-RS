---
title: Identifikuj IP adresu i klijenta u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 80b652eb65612093252dee226a19ec74bc035faa
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508930"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Identifikuj IP adresu i klijenta u evidencijama nadgledanja

IP adresa koja odgovara aktivnosti Microsoft 365 korisnika ili administratora prikazana je u evidencijama nadgledanja. Informacije o klijentu se takođe evidentiraju. Evo koraka za identifikovanje takvih informacija

1. Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/).

2. Idite na stranicu **Search**za  >  **pretraživanje evidencije nadgledanja** pretraživanja.

   Ako ste zainteresovani za određenu aktivnost, izaberite je sa liste **aktivnosti** . Ako ne, sve aktivnosti će biti vraćene za izabranog korisnika (podrazumevana postavka).

   **Napomena**: određene aktivnosti možda neće biti dostupne u meniju " **aktivnosti** "; Međutim, te stavke nadgledanja će biti vraćene ako je izabrano **Prikaz rezultata za sve aktivnosti** (podrazumevana postavka).

3. Navedite korisničko ime u polju " **Korisnici** " izaberite odgovarajući opseg datuma za aktivnost, a zatim kliknite na dugme " **Pretraži**".

U rezultatima možete videti IP adresu za tu aktivnost u oknu sa rezultatima. Izaberite zapis nadgledanja da biste videli detaljne informacije o **detaljima sa detalja** (npr. klijent, korisnik koji je izvršio radnju itd.)

Više informacija potražite u članku [PRONALAŽENJE IP adrese računara koji se koristi za pristup ugroženog naloga](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#find-the-ip-address-of-the-computer-used-to-access-a-compromised-account).

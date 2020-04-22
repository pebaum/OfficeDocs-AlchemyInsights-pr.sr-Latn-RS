---
title: Identifikuj događaje brisanja poruka u evidencijama nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 797a4b1146862faf91d2b9e8d74feade90f71650
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716510"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Evidencija nadgledanja izbrisanih e-poruka

Počevši od januara 2019, Microsoft podrazumevano postaje uključena evidencija nadgledanja poštanskog sandučeta. U suprotnom, da biste redigovali poruke o brisanju događaja za određenog korisnika, potrebno je da ručno omogućite brisanje radnji za nadgledanje. Ako je evidencija nadgledanja za poštansko sanduče već omogućena za vašu organizaciju ili za određenog korisnika, sledite dolenavedene korake.

1. Prijavite se na [Microsoft 365 Security & centar za usaglašavanje](https://protection.office.com/)

2. Kliknite na dugme **Pretraga i istraga** i izaberite **pretragu evidencije nadgledanja**.

3. Izaberite opseg datuma u poljima **Početni datum** i **Krajnji datum** . Odredite korisničko ime za korisnika koji želite da istražite (korisnika koji je izbrisao stavke). U polju **aktivnosti** izaberite **izbrisane poruke iz fascikle "Izbrisane stavke** " i **premestite poruke u fasciklu "Izbrisane stavke**".

4. Kliknite na dugme **Pretraži**.

U rezultatima izaberite zapis nadgledanja. Kliknite na dugme " **više informacija**" u prozoru "Detalji". Dodatne informacije o izbrisanom artiklu (na primer, red za temu i lokacija stavke kada je ona izbrisana) prikazane su u polju "zone za **stavke** ". Svojstvo **Clientinfostring** će prikazati da li je brisanje bilo u programu Outlook, Outlook na vebu (ranije poznato kao Outlook Web aplikacija) ili bilo koji drugi uređaj.

Više informacija potražite u članku [Utvrđivanje ko je podesio Prosleđivanje e-pošte za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Napomena**: ne možete da preuzimate izbrisane stavke pomoću funkcije "evidencija nadgledanja". Da biste preuzeli izbrisane poruke u programu Outlook na vebu, pogledajte odeljak [oporavak izbrisanih stavki u Outlook Web aplikaciji](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).

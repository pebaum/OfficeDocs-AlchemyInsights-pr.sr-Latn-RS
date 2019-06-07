---
title: Identifikujte brisanje poruka događaja u evidencije nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 0fb5d6aa0c99f7f68459c40302869bed69583b3f
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34755166"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Evidencije nadgledanja za izbrisane e-poruka

Počev od januara 2019, Microsoft je uključivanje Korektura poštanskog sandučeta evidentiranje po podrazumevanoj vrednosti. U suprotnom, da biste pregledali brisanje poruka događaja za određenog korisnika, potrebno je da ručno omogućite brisanje radnje za nadzor. Ako poštansko sanduče nadgledanja vođenja evidencije je već omogućena za vašu organizaciju ili za određenog korisnika, sledite korake ispod.

1. Prijavite se za [Office 365 bezbednosni & usklađenosti centar](https://protection.office.com/)

2. Izaberite **pretragu i istrage** i **Pretraživanje evidencije nadgledanja**.

3. Izaberite opseg datuma u poljima **datum početka** i **datum završetka** . Navedite korisničko ime za korisnika kojeg želite da istražite (korisnika koji su izbrisane stavke). U polju **aktivnosti** , izaberite **izbrisane poruke iz fascikle izbrisane stavke** i **Moved poruke u fasciklu izbrisane stavke**.

4. Kliknite na dugme **za pretragu**.

Na listi rezultata izaberite zapis o reviziji. U Potpaleta na detalje, kliknite **Više informacija**. Dodatne informacije o izbrisanih stavki (na primer, temu i lokaciju stavke kada je izbrisana) je prikazan u polju **AffectedItems** . Svojstvo **ClientInfoString** će prikazati ako brisanje je došlo u programu Outlook, Outlook na Webu (poznatog i kao Outlook Web App), ili bilo koji drugi uređaj.

Za više informacija, pogledajte [Determining ko podešavanje email Špedicija za poštansko sanduče](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Napomena**: te nije moguće preuzeti izbrisanih stavki pomoću funkcije evidencije nadgledanja. Da biste preuzeli izbrisane poruke u programu Outlook na Webu, vidim da [spasi izbrisane stavke u programu Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).

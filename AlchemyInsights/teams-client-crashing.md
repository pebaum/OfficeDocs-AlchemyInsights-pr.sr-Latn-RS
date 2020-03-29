---
title: Teams klijent otkazuje?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030674"
---
# <a name="teams-client-crashing"></a>Teams klijent otkazuje?

Ukoliko Teams klijent otkazuje, pokušajte sledeće:

- Ako koristite Teams aplikaciju za stone računare, [ uverite se da je aplikacija potpuno ažurirana](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

- Proverite da li su pristupačne sve [URL Office 365 adrese i svi rasponi adresa](https://docs.microsoft.com/microsoftteams/connectivity-issues).

- Prijavite se pomoću administratorskog naloga i proverite [Kontrolnu tablu za ispravnost usluge](https://docs.microsoft.com/office365/enterprise/view-service-health)da biste potvrdili da ne postoji prekid ili degradacija usluge. 

 - Kao poslednji korak, možete da pokušate da obrišete keš Teams klijenta:

    1.  Potpuno izađite iz Microsoft Teams klijent za radnu površinu. Možete da kliknete desnim tasterom miša na **Teams** iz ležišta za ikone i kliknete **Zatvorite**ili pokrenete Upravljač zadacima i potpuno ubijete proces.

    2.  Idite u Istraživač datoteka i otkucajte %appdata%\Microsoft\teams.

    3.  Kada stignete u direktorijum, videćete neke od sledećih fascikli:

         - U okviru **Keš aplikacije**, idite na Keš i izbrišite bilo koju datoteku na lokaciji keširanja: %appdata%\Microsoft\teams\application cache\cache.

        - U okviru stavke**Blob_storage**, izbrišite sve datoteke: %appdata%\Microsoft\teams\blob_storage.

        - U okviru stavke**Keš**, izbrišite sve datoteke: %appdata%\Microsoft\teams\Cache.

        - U okviru stavke**databases**, izbrišite sve datoteke: %appdata%\Microsoft\teams\databases.

        - U okviru stavke**GPUCache**, izbrišite sve datoteke: %appdata%\Microsoft\teams\GPUcache.

        - U okviru **IndexedDB**, izbrišite .db datoteku: %appdata%\Microsoft\teams\IndexedDB.

        - U okviru stavke**Lokalno skladište**, izbrišite sve datoteke: %appdata%\Microsoft\teams\Local Storage.

        - Na kraju, u okviru **tmp**izbrišite bilo koju datoteku: %appdata%\Microsoft\teams\tmp.

    4. Ponovo pokreni Teams klijent.

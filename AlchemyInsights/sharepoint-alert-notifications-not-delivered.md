---
title: SharePoint obaveštenja nije isporučena
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: f389785fcd1029ae5a47e07c723874f9f214109d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36504477"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a>SharePoint obaveštenja nije isporučena

Proverite fasciklu "Neželjena" u e-pošti, dok ponekad obaveštenja tamo idete.

Određivanje da li **sva obaveštenja se ne isporučuju** ili ako **pojedinačni obaveštenje** iz određene datoteke ili biblioteka nije dostavljeno.

- **Pojedinačne obaveštenja se ne isporučuju**: ako nije dostavljeno pojedinačne obaveštenje iz određene datoteke ili biblioteke, možete pokušati da obrišete i ponovo ga kreirate. Vidi [Upravljanje, prikaz, ili brisanje SharePoint obaveštenja](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) da ponovo stvori uzbunu.
- **Sva obaveštenja se ne isporučuju**: ako ne isporučuju sva obaveštenja sa više datoteka i biblioteke, posjetite [zdravstvenih usluga kontrolne table](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) za proveru javljanjima/incidenti, koji može biti koji se javljaju sa SharePoint ili Exchange. Problem mogao biti sa SharePoint upozorenja sposobnost ili odlaganja u e-mailove kroz Exchange. To će takođe biti napomenuti da li isporučuje ostale e-adrese, a ako ne, je problem verovatno sa Exchange odlaganja.

Najčešća pitanja o obaveštenjima:

- Nije moguće poslati upozorenja u grupi za distribuciju, samo sigurnost i O365 grupe nije podržana.
- Ne možete prilagoditi predloške upozorenja e-pošte; Morate koristiti Microsoft FLOW ili SharePoint Designer toka posla da se one ostvare.

Više informacija:

- **Podešavanje upozorenja**: za više informacija o podešavanju upozorenja, potražite u odeljku [Kreiranje obaveštenje na dobijanje obaveštenja kada je datoteka ili fascikla promene u SharePoint](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).
- **Rešavanje problema sa obaveštenjima**: za više informacija o otklanjanju poteškoća s upozorenja, vidim da [Korisnici ne dobijaju obaveštenja SharePoint Online](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications).
- **Napredni O365 usklađenosti Alert politika**: za više informacija o podešavanju ovih upozorenja, vidim [Usklađenosti Alert politike](https://docs.microsoft.com/office365/securitycompliance/alert-policies).
- **SharePoint i evidencija nadgledanja OneDrive**: za više informacija o tome kako preuzeti ove događaje, vidim [pretragu datoteka za evidenciju nadzora](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
- **Obaveštenja poslata od strane više opcija za zaštitu pretnja**: vidim [ATP za SharePoint i OneDrive](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).
- **Obaveštenja poslata od strane sprečavanje gubitka podataka smernice**: vidim [Email obaveštenja za politiku i Uroniti](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).

## <a name="related-topics"></a>Srodne teme

Da probamo Microsoft Flow u SharePoint Online?

- [Kreiranje toka](https://support.office.com/article/create-a-flow-for-a-list-or-library-in-sharepoint-online-or-onedrive-for-business-a9c3e03b-0654-46af-a254-20252e580d01)

- [SharePoint i protok](https://flow.microsoft.com/en-us/blog/sharepoint-and-flow/)

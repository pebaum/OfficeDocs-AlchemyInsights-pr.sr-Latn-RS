---
title: Premestite poruke e-pošte u poštansko sanduče arhive
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: a29fb799b68f5c187ca1d44aeaf94e6cd8760b0e
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35379511"
---
# <a name="move-email-to-the-archive-mailbox"></a>Premestite e-pošte u poštanskom sandučetu arhive

1. Potvrdi da je **arhiviranje poštansko sanduče** je omogućeno. U suprotnom, koristite korake u [ovom članku](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) da biste omogućili poštansko sanduče arhive.

2. Za arhiviranje poruka automatski u poštansko sanduče arhive, oznaku zadržavanja uz radnju **pokret za arhiviranje** mora biti postavljen **automatski stepenuje čitav poštansko sanduče (podrazumevano) oznaku**. Ovde koristite korake da biste kreirali oznaku: [arhiva podrazumevana oznaka](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).

3. Zatim dodajte oznaku **arhiva** zadržavanja politici. U centru za admin Exchange, odaberite **Smernice za zadržavanje** > dodati **premestite u arhivu oznaka** politike > **spasiti**.

4. Sada [dodelite smernice za zadržavanje](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) određene korisnikovom poštanskom sandučetu. Istu politiku će primeniti i na **primarnom** i poštansko sanduče na **arhive** .

To može biti neophodno da prisili uspeo fasciklu pomoćnika (MFA) da biste pokrenuli i primeni nove postavke na korisnikovom poštanskom sandučetu. Pokrenite sljedeću naredbu dok je [povezan sa EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) početi uspeo pomoćnika za fascikle za određeni poštansko sanduče:
  
Start-ManagedFolderAssistant-identitet<name of the mailbox>

Za više informacija o podešavanju smernice za arhiviranje, pogledajte [Podešavanje smernice za arhiviranje i brisanje za Poštanske sandučiće](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  
---
title: Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 0f1e427801107109e31486a4d300f53084880caf
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40054824"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu

Ako korisnici primaju poruku o grešci "nije moguće pronaći korisnika" u direktorijumu, pokušajte ponovo gde je tip problema "korisnik" nije u direktorijumu.

Sledeći koraci mogu biti dovršeni da biste rešili problem.

- Uverite se da je nalog koji je prihvatio pozivnicu e-poštom isti nalog koji se koristi za prijavljivanje kasnije. Uverite se da korisnik koristi isti nalog za prihvatanje poziva i prijavljivanje na lokaciju. 

Više informacija potražite u članku [Kako da upravljate pseudonimima za Microsoft nalog</a> da biste upravljali Office 365 prijavljivanju](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases). 

- Potražite svaku lokaciju u kojoj korisnik prima grešku. 

Dodajte "/_layouts/15/ljud.aspx/člana špeditergroupid = 0" (u okviru dvostrukih navodnika) do kraja URL adrese lokacije. 

Primer: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.

- Izaberite korisnika sa liste.

- Kliknite na dugme " **Ukloni korisničke dozvole** " sa glavne trake. 
-  Vratite korisnika i ponovo pošaljite poziv korisniku.


---
title: Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 59713231da25be441e7c05d788337e66bf17265a
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768815"
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


---
title: Čuvanje lokacije ili liste kao predloška
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 627f49991aaef984f731412045351d7a1862b376
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048738"
---
# <a name="save-site-or-list-as-a-template"></a>Čuvanje lokacije ili liste kao predloška

Predlošci SharePoint lokacija su unapred ugrađene definicije dizajnirane oko određenog poslovnog potreba. Više informacija potražite u članku [Korišćenje predložaka za kreiranje različitih vrsta SharePoint lokacija](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Evo nekih uobičajenih problema/rešenja u vezi sa čuvanjem lokacije ili liste kao predloška u sistemu SharePoint online.

**Dugme "Sačuvaj predložak lokacije/liste" nije dostupno ili nedostaje**. 

- Administratori će morati da omoguće da prilagođena skripta omogući funkcije predloška. Detaljne korake, primeri i razmatranja potražite u članku [Dozvoljavanje ili sprečavanje prilagođene skripte](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


- Lokacija "Sačuvaj lokaciju" kao predložak nije podržana i može da izazove probleme na lokacijama koje koriste infrastrukturu za objavljivanje SharePoint servera.


**Nije moguće kreirati predložak lokacije ili on ne funkcioniše ispravno**

- Predlošku nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i ne može da se aktivira. Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji lokacija, ne možete da koristite predložak lokacije da biste kreirali lokaciju.


- Proverite da li neke liste ili biblioteke premašuju [cenzus](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 stavki, jer to može blokirati Kreiranje predloška lokacije.


- Ova lokacija možda koristi previše resursa i zato predložak lokacije premašuje ograničenje od 50 megabajta (MB).


- Postoje problemi sa prikazivanjem podataka sa liste koja koristi kolonu za pronalaženje. Više informacija potražite u članku [Lista generisanih predložaka ne prikazuje podatke sa ispravne liste za pronalaženje u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).


Detaljnije informacije o uobičajenim problemima i rešenjima potražite u referenci, [Kreiranje i korišćenje predložaka lokacije](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).


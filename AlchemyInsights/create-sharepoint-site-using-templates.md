---
title: Kreiranje lokacije u sistemu SharePoint online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b9009fdbdc2a5e7443151446daade1685d2f5d45
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770437"
---
# <a name="create-sharepoint-sites-using-templates"></a>Kreiranje SharePoint lokacija pomoću predložaka

Mogućnost čuvanja lokacije kao predloška nije podržana sa modernim komunikacijama ili lokacijama timova. Više informacija o korišćenju predložaka potražite u članku [Čuvanje, preuzimanje i otpremanje SharePoint lokacije kao predloška](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).

Evo nekih uobičajenih problema/rešenja u vezi sa čuvanjem lokacije ili liste kao predloška u sistemu SharePoint online. 

**Dugme "Sačuvaj predložak lokacije/liste" nije dostupno ili nedostaje**

Administratori će morati da omoguće da prilagođena skripta omogući funkcije predloška. Za detaljne korake, primeri i razmatranja 

- [Dozvoljavanje ili sprečavanje prilagođene skripte](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- Lokacija "Sačuvaj lokaciju" kao predložak nije podržana i može da izazove probleme na lokacijama koje koriste infrastrukturu za objavljivanje SharePoint servera.

**Nije moguće kreirati predložak lokacije ili on ne funkcioniše ispravno**

Predlošku nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i ne može da se aktivira. Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji lokacija, ne možete da koristite predložak lokacije da biste kreirali lokaciju.

- Proverite da li neke liste ili biblioteke premašuju [cenzus](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 stavki, jer to može blokirati Kreiranje predloška lokacije.

- Lokacija možda koristi previše resursa i zato predložak lokacije premašuje ograničenje od 50 MB.


- Postoje problemi sa prikazivanjem podataka sa liste koja koristi kolonu za pronalaženje. Više informacija potražite u članku [Lista generisanih predložaka ne prikazuje podatke sa ispravne liste za pronalaženje u sistemu SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Detaljnije informacije o uobičajenim problemima i rešenjima potražite u okviru " [Kreiranje i korišćenje predložaka lokacije](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)".




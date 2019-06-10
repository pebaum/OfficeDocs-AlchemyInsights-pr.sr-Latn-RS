---
title: Sačuvaj lokaciju ili listu kao predložak
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 73a32536995a604c734393c2300b4c9bb507e2b2
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34770541"
---
# <a name="save-site-or-list-as-a-template"></a>Sačuvaj lokaciju ili listu kao predložak

Predlošci lokacija SharePoint su izgrađenom definicije dizajniran oko specifičnim poslovnim potrebama. Za više informacija, pogledajte [koristeći predloške da biste kreirali različite vrste SharePoint lokacije](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Evo nekih uobičajenih pitanja/rešenja u pogledu čuvanja na lokaciju ili listu kao predložak u SharePoint Online.

**Lista lokacija/predložak dugme je spasi nije dostupan ili nedostaje**. 

- Administratori morat ćete omogućiti skripte Prilagođeno da biste omogućili funkcije predloška. Detaljni koraci, primeri i razmatranja potražite u [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


- Sačuvaj lokaciju kao predložak komanda nije podržano i može da izazove probleme na lokacijama koje koriste SharePoint Server Publishing infrastrukturu.


**Predložak lokacije nije moguće kreirati ili ne radi ispravno**

- Obrazac može biti nedostaje [funkcija](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) i neće aktivirati. Ako funkcija nije dostupna za aktivaciju u trenutnoj kolekciji, predložak lokacije ne možete da kreirate lokaciju.


- Proverite da li ako liste ili biblioteke da premaši [Prag ograničenje prikaza liste](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) od 5000 artikala kao što to možete blokirati stvaranje predložak.


- Lokacija možda koristi previše resursa i stoga je predložak lokacije premašuje ograničenje od 50 megabajta (MB).


- Postoje problemi u prikazivanju podataka iz liste u kojoj se koristi kolone za pronalaženje. Više informacija potražite u odeljku [generiše predložak liste ne prikaže podatke iz liste ispravne za pronalaženje u SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).


Za detaljnije informacije o uobičajenim problemima i rešenjima molim referencu, [Kreiranje i upotreba predložaka lokacije](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).


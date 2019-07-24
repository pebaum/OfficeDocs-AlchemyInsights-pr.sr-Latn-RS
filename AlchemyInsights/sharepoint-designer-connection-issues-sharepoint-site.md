---
title: Pitanja za povezivanje SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 1d3f6ad3128292a9dbcc46cc7da23af59a63fbb4
ms.sourcegitcommit: a285c609319ade038461e090e14a701830031825
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/24/2019
ms.locfileid: "35840565"
---
# <a name="sharepoint-designer-connection-issues"></a>Pitanja za povezivanje SharePoint Designer 

Ako SharePoint Designer se suočava sa pitanjima za povezivanje sa SharePoint lokacijama, pokušajte sledeće zajedničkim rešenjima.

1. korak: Provjerite da SharePoint Designer 2013 se ažurira sa [SharePoint Designer sa servisnim paketom 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) i [2. avgust 2016 ažuriranje za SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



2. korak: Brisanje datoteke lokalnog keša:

1. Zatvorite SharePoint Designer 2013.

2. Na lokalnom računaru, uklonite sve datoteke pronađene u svakoj od sljedećih mapa.

    - %APPDATA%\Microsoft\Web server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Otvorite SharePoint Designer 2013 i unesite račun da vidimo da li radi.

3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).

4. korak: Administratori morat ćete **Omogućiti prilagođena skripta** u SharePoint Admin Center postavkama da biste dozvolili povezivanje na SharePoint Designer. Vidim [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) za više informacija.



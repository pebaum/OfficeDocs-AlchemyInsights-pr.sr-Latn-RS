---
title: Nivoi dozvola SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760706"
---
# <a name="sharepoint-designer-connection-issues"></a>Pitanja za povezivanje SharePoint Designer 

Ako SharePoint Designer se suočava sa pitanjima za povezivanje sa SharePoint lokacijama, molim vas pokušati sledeća uobičajene rešenja.

1. korak: Provjerite ažuriranja SharePoint Designer.

- [SharePoint Designer 2013](https://www.microsoft.com/download/details.aspx?id=35491)

- [SharePoint Designer servisni paket 1 (SP1)](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [Ažuriranje za SharePoint Designer 2013 (KB3114721)](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

2. korak: Brisanje datoteke lokalnog keša

- Zatvorite SharePoint Designer 2013.

- Na lokalnom računaru, pronađite sljedeće mape da biste uklonili keširane datoteke.

- Kliknite na dugme Start, Run i izbrisati sve datoteke pronađene ispod svakog je ispod lokacije.

Server za %APPDATA%\Microsoft\Web Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

Otvorite SharePoint Designer 2013 i unesite račun da vidimo da li radi.

3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na uređajima Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)

4. korak: Administratori morat ćete omogućiti prilagođena skripta da dozvolite vezu SharePoint Designer.

Detaljni koraci, primeri i razmatranja potražite u [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).



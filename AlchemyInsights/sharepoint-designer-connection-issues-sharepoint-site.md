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
ms.openlocfilehash: 7451cfe957545537298f57feb5b47bd6d43cddbf
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716905"
---
# <a name="sharepoint-designer-connection-issues"></a>Pitanja za povezivanje SharePoint Designer 

<p>Ako SharePoint Designer se suočava sa pitanjima za povezivanje sa SharePoint lokacijama, molim vas pokušati sledeća uobičajene rešenja.</p> <p><strong>1. korak:</strong> <strong>Se ažurira Provjerite SharePoint Designer&nbsp; </strong></p> <ul> <li><a href="https://www.microsoft.com/en-us/download/details.aspx?id=35491">SharePoint Designer 2013</a></li> <li><a href="https://support.microsoft.com/en-us/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1">SharePoint Designer servisni paket 1 (SP1)</a></li> <li><a href="https://support.microsoft.com/en-us/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721">Ažuriranje za SharePoint Designer 2013 (KB3114721)</a></li> </ul> <p><strong>2. korak:</strong> <strong>Brisanje datoteke lokalnog keša</strong>&nbsp;</p> <ol> <li style="font-weight: 400;">Zatvorite SharePoint Designer 2013.&nbsp;</li> <li style="font-weight: 400;">Na lokalnom računaru, pronađite sljedeće mape da biste uklonili keširane datoteke.&nbsp;</li> <li style="font-weight: 400;">Kliknite na <strong>Start -&gt; pokrenuti</strong> i izbrišite sve datoteke pronađene ispod svakog je ispod lokacije.&nbsp;<br /><br />%APPDATA%\Microsoft\Web server Extensions\Cache<br />%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache<br />%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</li> <li style="font-weight: 400;">Otvorite SharePoint Designer 2013 i unesite račun da vidimo da li radi.</li> </ol> <p><strong>Korak 3:</strong> <a href="https://docs.microsoft.com/en-us/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=%252fen-us%252farticle%252fEnable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&amp;view=o365-worldwide">Je da <strong>Omogući modernog identiteta za Office 2013 na Windows uređajima</strong></a>&nbsp;</p> <p><strong>4. korak:</strong> <strong>Administratori morat ćete omogućiti skripte Prilagođeno da biste dozvolili povezivanje na SharePoint Designer</strong>.</p> <p>Detaljni koraci, primeri i razmatranja potražite u <a href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Dozvoli ili sprečavaju adaptirani scenario</a>.&nbsp;</p>



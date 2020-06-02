---
title: Problemi sa SharePoint dizajnerom
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511558"
---
# <a name="sharepoint-designer-connection-issues"></a>Problemi sa SharePoint dizajnerom 

Ako SharePoint Designer ima problema sa povezivanjem sa SharePoint lokacijama, isprobajte sledeća uobičajena rešenja.

1. korak: proverite da li se SharePoint Designer 2013 ažurira pomoću [SharePoint Designer servisnog paketa 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) i [2. avgusta, 2016 Update za SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



2. korak: brisanje lokalnih datoteka keša:

1. Zatvorite SharePoint Designer 2013.

2. Na lokalnom računaru uklonite sve datoteke pronađene u svakoj od sledećih fascikli.

    - %APPDATA%\Microsoft\Web% Ekstenioni\keš
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Otvorite SharePoint Designer 2013 i ponovo unesite nalog da biste videli da li radi.

3. korak: [Omogućavanje moderne potvrde identiteta za Office 2013 na Windows uređajima](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).

4. korak: Administratori će morati da **dozvole prilagođenu skriptu** u postavkama sistema SharePoint admin Center da bi dozvolili povezivanje sa SharePoint dizajnerom. Više informacija potražite u članku [Dozvoljavanje ili sprečavanje prilagođene skripte](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .



---
title: Trajno brisanje sajta u sistemu SharePoint
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.custom: ''
ms.assetid:
- "5200006"
- "4391"
ms.openlocfilehash: 263317339d965d173a5a038fa006e0ce6f8476cc
ms.sourcegitcommit: da04e79b6072321caa16a6ceea6eb5f15de22394
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/25/2020
ms.locfileid: "42955239"
---
# <a name="permanently-delete-a-site-in-sharepoint"></a>Trajno brisanje sajta u sistemu SharePoint

Da biste ponovo koristili URL adresu sa izbrisanog sajta (radi ponovnog kreiranja sajta) ili da biste trajno izbrisali sajt zato što više nije u upotrebi, možete da koristite opciju **Trajno izbriši** u novom SharePoint centru administracije. 

1. Idite na [stranicu „Izbrisani sajtovi“ u novom SharePoint centru administracije](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) i prijavite se pomoću naloga koji ima administratorske dozvole za organizaciju. 

2. U levoj koloni izaberite sajt. 

3. Izaberite stavku **Trajno izbriši**. 

**Napomena**: Nije moguće trajno izbrisati sajtove povezane sa grupama u novom SharePoint centru administracije. Umesto toga ćete morati da koristite [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite).  

Više informacija potražite u članku [Trajno brisanje sajta](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site). 

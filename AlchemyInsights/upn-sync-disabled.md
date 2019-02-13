---
title: UPN sinhronizacija onemogućena
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 983796ce8fb7e8b52c0ce31aa13597b53cc9e038
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29921722"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="bc38b-102">UPN sinhronizacija onemogućena</span><span class="sxs-lookup"><span data-stu-id="bc38b-102">UPN sync disabled</span></span>

<span data-ttu-id="bc38b-103">Ako ste pokrenuli sinhronizovanje da azurno AD pre 30. marta 2016, pokrenite sledeću Azure AD PowerShell cmdlet da biste omogućili UPN meke odgovara vašoj organizaciji samo:</span><span class="sxs-lookup"><span data-stu-id="bc38b-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="bc38b-104">**Set-MsolDirSyncFeature-karakteristika EnableSoftMatchOnUpn-omogući $True**</span><span class="sxs-lookup"><span data-stu-id="bc38b-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="bc38b-105">UPN meke poklapa se automatski uključuje za organizacije koja je počela da se sinhronizuje sa azurno AD ili posle 30. marta 2016..</span><span class="sxs-lookup"><span data-stu-id="bc38b-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="bc38b-106">Da biste saznali više o omogućavanju meke meč na UPN i druge funkcije sinhronizacije, pogledajte [Azure AD povezivanje opcije usluge za sinhronizaciju](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="bc38b-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  


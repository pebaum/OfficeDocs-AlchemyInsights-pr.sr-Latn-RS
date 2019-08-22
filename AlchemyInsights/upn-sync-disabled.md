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
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: f390d659b191fa4c44bd7c8acb32409cd3021489
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36532345"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="81b75-102">UPN sinhronizacija onemogućena</span><span class="sxs-lookup"><span data-stu-id="81b75-102">UPN sync disabled</span></span>

<span data-ttu-id="81b75-103">Ako ste pokrenuli sinhronizovanje da azurno AD pre 30. marta 2016, pokrenite sledeću Azure AD PowerShell cmdlet da biste omogućili UPN meke odgovara vašoj organizaciji samo:</span><span class="sxs-lookup"><span data-stu-id="81b75-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="81b75-104">**Set-MsolDirSyncFeature-karakteristika EnableSoftMatchOnUpn-omogući $True**</span><span class="sxs-lookup"><span data-stu-id="81b75-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="81b75-105">UPN meke poklapa se automatski uključuje za organizacije koja je počela da se sinhronizuje sa azurno AD ili posle 30. marta 2016..</span><span class="sxs-lookup"><span data-stu-id="81b75-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="81b75-106">Da biste saznali više o omogućavanju meke meč na UPN i druge funkcije sinhronizacije, pogledajte [Azure AD povezivanje opcije usluge za sinhronizaciju](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="81b75-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  


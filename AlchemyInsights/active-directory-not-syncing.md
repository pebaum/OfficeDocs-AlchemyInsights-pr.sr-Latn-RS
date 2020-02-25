---
title: Aktivni direktorijum ne sinhronizuje
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001688"
- "3754"
ms.openlocfilehash: 3abad160ab28922685d235a1fa546105e31757fb
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265270"
---
# <a name="active-directory-not-syncing"></a><span data-ttu-id="5ddbe-102">Aktivni direktorijum ne sinhronizuje</span><span class="sxs-lookup"><span data-stu-id="5ddbe-102">Active Directory not syncing</span></span>

<span data-ttu-id="5ddbe-103">Ako dobijate greške pri sinhronizaciji, kao što je "bez nedavne sinhronizacije" ili ako primetite da status sinhronizacije direktorijuma u Office admin portalu kaže, "poslednji put sinhronizovano pre više od 3 dana," moguće je da AADConnect ima neispravne postavke ili nedovoljno dozvole za izvršavanje sinhronizacije.</span><span class="sxs-lookup"><span data-stu-id="5ddbe-103">If you are receiving synchronization errors, such as "no recent synchronization," or notice the directory synchronization status in the Office admin portal says, "Last synced more than 3 days ago," it may be that AADConnect has incorrect settings or insufficient permissions to perform a synchronization.</span></span>  

<span data-ttu-id="5ddbe-104">Ponovno instaliranje AADConnect pomoću ekspresne postavke može brzo da reši problem:</span><span class="sxs-lookup"><span data-stu-id="5ddbe-104">Reinstalling AADConnect by using express settings may resolve the issue quickly:</span></span>

1. <span data-ttu-id="5ddbe-105">[Preuzmite najnoviju verziju AADConnect-a](https://go.microsoft.com/fwlink/?LinkId=615771).</span><span class="sxs-lookup"><span data-stu-id="5ddbe-105">[Download the latest version of AADConnect](https://go.microsoft.com/fwlink/?LinkId=615771).</span></span>

2. <span data-ttu-id="5ddbe-106">[Sledite uputstva za ekspresnu instalaciju](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).</span><span class="sxs-lookup"><span data-stu-id="5ddbe-106">[Follow the instructions for express installation](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).</span></span>

<span data-ttu-id="5ddbe-107">Za više informacija o nalozima za uslugu AADConnect pogledajte odeljak [Azure Connect za povezivanje: nalozi i dozvole](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).</span><span class="sxs-lookup"><span data-stu-id="5ddbe-107">For more information about AADConnect service accounts, see [Azure AD Connect: Accounts and permissions](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).</span></span>

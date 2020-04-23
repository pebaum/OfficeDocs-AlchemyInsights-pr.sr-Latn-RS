---
title: 932 nadogradnja AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766507"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="5122d-102">Nadogradnja Azure AD Connect</span><span class="sxs-lookup"><span data-stu-id="5122d-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="5122d-103">Automatska Nadogradnja je podrazumevano omogućena za povezivanje Azure oglasa, što pomaže da se osigura da koristite najnoviju verziju.</span><span class="sxs-lookup"><span data-stu-id="5122d-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="5122d-104">Da biste proverili postavke automatskog nadograđivanje, koristite funkciju " **Preuzmi-Adupupozorenje** " u "Azure" PowerShell.</span><span class="sxs-lookup"><span data-stu-id="5122d-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="5122d-105">Cmdmo će vratiti jednu od sljedećih vrijednosti:</span><span class="sxs-lookup"><span data-stu-id="5122d-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="5122d-106">**Omogućeno**: automatska Nadogradnja je omogućena.</span><span class="sxs-lookup"><span data-stu-id="5122d-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="5122d-107">**Onemogućeno**: automatska Nadogradnja je onemogućena.</span><span class="sxs-lookup"><span data-stu-id="5122d-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="5122d-108">**Obustavljeno**: sistem više nema pravo da prima automatske nadogradnje.</span><span class="sxs-lookup"><span data-stu-id="5122d-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="5122d-109">Ne možete konfigurisati ovu vrednost; postavlja ga sistem.</span><span class="sxs-lookup"><span data-stu-id="5122d-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="5122d-110">Za više informacija pogledajte odeljak [Automatska nadogradnja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="5122d-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="5122d-111">Idite na lokaciju da biste preuzeli najnoviju verziju Azure Connect oglasa [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="5122d-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>

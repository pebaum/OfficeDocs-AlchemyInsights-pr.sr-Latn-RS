---
title: 932 nadogradnja AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 932
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 8ffa8f64019077034bc4fad61d1d843849c42898
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32389756"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="79d98-102">Nadogradnja azurno AD povezivanje</span><span class="sxs-lookup"><span data-stu-id="79d98-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="79d98-103">Po podrazumevanim postavkama, automatska Nadogradnja je omogućeno za Azure AD se poveže, koje pomažu da se osigura da koristite najnoviju verziju.</span><span class="sxs-lookup"><span data-stu-id="79d98-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="79d98-104">Da biste proverili postavke za automatsku nadogradnju, koristite cmdlet su **Se ADSyncAutoUpgrade** u Azure AD PowerShell.</span><span class="sxs-lookup"><span data-stu-id="79d98-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="79d98-105">Na cmdlet će se vratiti jedan od sledećih vrednosti:</span><span class="sxs-lookup"><span data-stu-id="79d98-105">The cmdlet will return one of following values:</span></span> 

- <span data-ttu-id="79d98-106">**Omogućeno**: omogućena je automatska nadogradnja.</span><span class="sxs-lookup"><span data-stu-id="79d98-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="79d98-107">**Onemogućeno**: automatska Nadogradnja je onemogućena.</span><span class="sxs-lookup"><span data-stu-id="79d98-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="79d98-108">**Prividne**: sistem je više da primate automatske nadogradnje.</span><span class="sxs-lookup"><span data-stu-id="79d98-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="79d98-109">Nije moguće podesiti ovu vrednost; To je podešen sistem.</span><span class="sxs-lookup"><span data-stu-id="79d98-109">You can't configure this value; it's set by the system.</span></span> 

<span data-ttu-id="79d98-110">Za više informacija, pogledajte [Automatska nadogradnja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="79d98-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="79d98-111">Da biste preuzeli najnoviju verziju programa Azure AD povezivanje, idite na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="79d98-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>

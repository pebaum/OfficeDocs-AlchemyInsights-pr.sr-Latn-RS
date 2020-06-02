---
title: Klasični SharePoint izveštaji za evidenciju nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509614"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="3c76b-102">SharePoint i OneDrive evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="3c76b-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="3c76b-103">SharePoint Classic evidencija nadgledanja</span><span class="sxs-lookup"><span data-stu-id="3c76b-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="3c76b-104">Nasleđena revizija SPO-a je premeštena u jedinstvenu evidenciju nadgledanja (UAL).</span><span class="sxs-lookup"><span data-stu-id="3c76b-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="3c76b-105">Sve zastarele revizorske izveštaje iz SPO-a sada će se provići kroz UAL, a signali nasleđene revizije su preseljeni u UAL.</span><span class="sxs-lookup"><span data-stu-id="3c76b-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="3c76b-106">Promene u ključu:</span><span class="sxs-lookup"><span data-stu-id="3c76b-106">Key changes:</span></span>

* <span data-ttu-id="3c76b-107">Skraćivanje nije dostupno kao mogućnost.</span><span class="sxs-lookup"><span data-stu-id="3c76b-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="3c76b-108">Izbor određenih događaja za reviziju nije dostupan.</span><span class="sxs-lookup"><span data-stu-id="3c76b-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="3c76b-109">Pogledajte [ovaj dokument](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) za kompletnu listu nadgledanog događaja koji su podrazumevano dostupni.</span><span class="sxs-lookup"><span data-stu-id="3c76b-109">Refer to [this document](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="3c76b-110">Opcija " **lokacija** " u okviru **prilagođenog izveštaja** nije dostupna.</span><span class="sxs-lookup"><span data-stu-id="3c76b-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="3c76b-111">Opcija " **Otvaranje" ili "preuzimanje dokumenata** " nije dostupna.</span><span class="sxs-lookup"><span data-stu-id="3c76b-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="3c76b-112">Konfigurisanje postavki nadgledanja za kolekciju lokacija</span><span class="sxs-lookup"><span data-stu-id="3c76b-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="3c76b-113">SharePoint i OneDrive savremeno ujednačene evidencije nadgledanja iz usaglašenosti</span><span class="sxs-lookup"><span data-stu-id="3c76b-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="3c76b-114">Uključivanje/isključivanje ujednačene evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="3c76b-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="3c76b-115">U sistemu SharePoint ili OneDrive nije potrebna dodatna konfiguracija.</span><span class="sxs-lookup"><span data-stu-id="3c76b-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="3c76b-116">Koristite pretragu vođenja evidencije nadgledanja da biste proverili aktivnost datoteka, fascikli, korisnika, dozvola:</span><span class="sxs-lookup"><span data-stu-id="3c76b-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="3c76b-117">Aktivnosti datoteka i stranica</span><span class="sxs-lookup"><span data-stu-id="3c76b-117">File and page activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="3c76b-118">Aktivnosti fascikle</span><span class="sxs-lookup"><span data-stu-id="3c76b-118">Folder activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="3c76b-119">Deljenje i pristup aktivnostima zahteva</span><span class="sxs-lookup"><span data-stu-id="3c76b-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="3c76b-120">Aktivnosti sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="3c76b-120">Synchronization activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="3c76b-121">Aktivnosti administracije lokacije</span><span class="sxs-lookup"><span data-stu-id="3c76b-121">Site administration activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="3c76b-122">Za više informacija o tome kako da preuzmete ove događaje pogledajte odeljak [pretraživanje evidencije nadgledanja](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="3c76b-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>

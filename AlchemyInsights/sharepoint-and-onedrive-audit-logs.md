---
title: Klasični SharePoint izveštaji za evidenciju nadgledanja
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068037"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="ac033-102">SharePoint i OneDrive evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="ac033-102">SharePoint and OneDrive audit logs</span></span>

<span data-ttu-id="ac033-103">**SharePoint i OneDrive savremeno ujednačene evidencije nadgledanja iz usaglašenosti**</span><span class="sxs-lookup"><span data-stu-id="ac033-103">**SharePoint and OneDrive Modern Unified Audit logs from compliance**</span></span>

- [<span data-ttu-id="ac033-104">Uključivanje/isključivanje ujednačene evidencije nadgledanja</span><span class="sxs-lookup"><span data-stu-id="ac033-104">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="ac033-105">U sistemu SharePoint ili OneDrive nije potrebna dodatna konfiguracija.</span><span class="sxs-lookup"><span data-stu-id="ac033-105">No additional configuration is required within SharePoint or OneDrive.</span></span>

- <span data-ttu-id="ac033-106">Koristite pretragu vođenja evidencije nadgledanja da biste proverili aktivnost datoteka, fascikli, korisnika, dozvola:</span><span class="sxs-lookup"><span data-stu-id="ac033-106">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

    - [<span data-ttu-id="ac033-107">Aktivnosti datoteka i stranica</span><span class="sxs-lookup"><span data-stu-id="ac033-107">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [<span data-ttu-id="ac033-108">Aktivnosti fascikle</span><span class="sxs-lookup"><span data-stu-id="ac033-108">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [<span data-ttu-id="ac033-109">Deljenje i pristup aktivnostima zahteva</span><span class="sxs-lookup"><span data-stu-id="ac033-109">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [<span data-ttu-id="ac033-110">Aktivnosti sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="ac033-110">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [<span data-ttu-id="ac033-111">Aktivnosti administracije lokacije</span><span class="sxs-lookup"><span data-stu-id="ac033-111">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- <span data-ttu-id="ac033-112">Za više informacija o tome kako da preuzmete ove događaje pogledajte odeljak [pretraživanje evidencije nadgledanja](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="ac033-112">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>

<span data-ttu-id="ac033-113">**SharePoint Classic evidencija nadgledanja**</span><span class="sxs-lookup"><span data-stu-id="ac033-113">**SharePoint classic Audit logs**</span></span>

<span data-ttu-id="ac033-114">Preselili smo iz SPO-a da bi se ujedinio evidencija nadgledanja (UAL).</span><span class="sxs-lookup"><span data-stu-id="ac033-114">We migrated SPO legacy auditing to Unified Audit Log (UAL).</span></span> <span data-ttu-id="ac033-115">To u suštini znači da će celokupan izveštaj o nadzoru iz SPO-a sada biti uključen u UAL, a da su signali nasleđene revizije preseljeni u UAL.</span><span class="sxs-lookup"><span data-stu-id="ac033-115">This essentially means that all SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="ac033-116">Promene u ključu:</span><span class="sxs-lookup"><span data-stu-id="ac033-116">Key changes:</span></span>

- <span data-ttu-id="ac033-117">Skraćivanje kao mogućnost nije dostupno.</span><span class="sxs-lookup"><span data-stu-id="ac033-117">Trimming as a capability is NOT available.</span></span>
- <span data-ttu-id="ac033-118">Odeljak u kome birate određene događaje za reviziju nije dostupan.</span><span class="sxs-lookup"><span data-stu-id="ac033-118">The section where you choose specific events to audit is NOT available.</span></span> <span data-ttu-id="ac033-119">Pogledajte [ovaj dokument](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) za kompletnu listu nadgledanog događaja koji su podrazumevano dostupni.</span><span class="sxs-lookup"><span data-stu-id="ac033-119">Please refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
- <span data-ttu-id="ac033-120">Opcija "lokacija" u okviru **prilagođenog izveštaja** nije dostupna.</span><span class="sxs-lookup"><span data-stu-id="ac033-120">The "Location" option under **Customized reports** is NOT available.</span></span> 
- <span data-ttu-id="ac033-121">Događaj "otvaranje ili preuzimanje dokumenata" nije dostupan.</span><span class="sxs-lookup"><span data-stu-id="ac033-121">“Opening or downloading documents” events is NOT available.</span></span> 


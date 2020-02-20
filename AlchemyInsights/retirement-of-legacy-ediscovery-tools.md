---
title: Penzionisanje zastarelog eDiscovery alata
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: c4632b52dde579b7d5b2e6e15f1583300a0bd136
ms.sourcegitcommit: a7c17217c170ead24571421baaf5a14f1525b1a6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/20/2020
ms.locfileid: "42157700"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="ec31d-102">Penzionisanje zastarelog eDiscovery alata</span><span class="sxs-lookup"><span data-stu-id="ec31d-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="ec31d-103">Kao rezultat nove i poboljšane eDiscovery funkcionalnosti u centru za usaglašavanje u operativnom sistemu Microsoft 365, sledeće zastarele eDiscovery alatke i zaobe će biti penzionisane narednih meseci:</span><span class="sxs-lookup"><span data-stu-id="ec31d-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="ec31d-104">[Na mestu eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) i [na mestu koje ima](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) Exchange admin Center.</span><span class="sxs-lookup"><span data-stu-id="ec31d-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="ec31d-105">Exchange online PowerShell cmdlet komandi koje podržavaju mesto eDiscovery i na mestu.</span><span class="sxs-lookup"><span data-stu-id="ec31d-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="ec31d-106">(Ove cmdlet se kolektivno identifikuju kao \*-MailboxSearch cmdlet.) Ovo obuhvata sledeća cmdlet:</span><span class="sxs-lookup"><span data-stu-id="ec31d-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="ec31d-107">Nova-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="ec31d-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="ec31d-108">Započni-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="ec31d-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="ec31d-109">Zaustavi-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="ec31d-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="ec31d-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="ec31d-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="ec31d-111">[Pretraga-poštansko sanduče](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdmo u Exchange online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ec31d-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="ec31d-112">Sledeće operacije u API Exchange Web usluga:</span><span class="sxs-lookup"><span data-stu-id="ec31d-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="ec31d-113">Getsearchablemailbox</span><span class="sxs-lookup"><span data-stu-id="ec31d-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="ec31d-114">Setholdonpoštanske sandučići</span><span class="sxs-lookup"><span data-stu-id="ec31d-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="ec31d-115">Getholdonpoštanske sandučiće</span><span class="sxs-lookup"><span data-stu-id="ec31d-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="ec31d-116">Office 365 Advanced eDiscovery v 1.0</span><span class="sxs-lookup"><span data-stu-id="ec31d-116">Office 365 Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="ec31d-117">**Vremenska osa za penziju**:</span><span class="sxs-lookup"><span data-stu-id="ec31d-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="ec31d-118">April 1, 2020: nećete moći da kreirate nove pretrage i zadrškama, ali i dalje možete da pokrećete, uređujete i brišete postojeće pretrage na vlastitu odgovornost.</span><span class="sxs-lookup"><span data-stu-id="ec31d-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="ec31d-119">Microsoft podrška više neće podržavati eDiscovery & zauzima u EAC-u.</span><span class="sxs-lookup"><span data-stu-id="ec31d-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="ec31d-120">1. jul 2020: eDiscovery na mesto & sadrži funkcionalnost u okviru EAC-a biće smeštena u režim samo za čitanje.</span><span class="sxs-lookup"><span data-stu-id="ec31d-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="ec31d-121">To znači da ćete moći da uklonite samo postojeće pretrage i zadrškama.</span><span class="sxs-lookup"><span data-stu-id="ec31d-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="ec31d-122">**Više informacija potražite u članku**:</span><span class="sxs-lookup"><span data-stu-id="ec31d-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="ec31d-123">Migriranje nasleđenih eDiscovery pretraga i zadrška za Microsoft 365 centar za usaglašavanje</span><span class="sxs-lookup"><span data-stu-id="ec31d-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="ec31d-124">Penzionisanje zastarelog eDiscovery alata</span><span class="sxs-lookup"><span data-stu-id="ec31d-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="ec31d-125">Najčešća pitanja o eDiscovery i na mestu na kojem se nalazi mesto</span><span class="sxs-lookup"><span data-stu-id="ec31d-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)




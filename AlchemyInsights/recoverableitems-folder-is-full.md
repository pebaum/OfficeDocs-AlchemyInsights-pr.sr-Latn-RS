---
title: 1336 fascikla za oporavak datoteke je puna
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: fb10b792981040bdcf4661b8aff30733c2438212
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720266"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="3e5c4-102">Fascikla "spasti stavke" je puna</span><span class="sxs-lookup"><span data-stu-id="3e5c4-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="3e5c4-103">Za Poštanske sandučiće za Exchange online, podrazumevano ograničenje prostora za skladištenje za fasciklu "Spasne stavke" je 30 GB.</span><span class="sxs-lookup"><span data-stu-id="3e5c4-103">For Exchange Online mailboxes, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="3e5c4-104">Ograničenje prostora za skladištenje za fasciklu "spasti stavke" se automatski povećava na 100 GB ako je poštansko sanduče postavljeno na čekanje, eDiscovery zadrške ili je dodeljeno smernicama za zadržavanje.</span><span class="sxs-lookup"><span data-stu-id="3e5c4-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to a retention policy.</span></span>

<span data-ttu-id="3e5c4-105">Kada fascikla "spasti stavke" dostigne ograničenje skladištenja, funkcionalnost poštanskog sandučeta utiče na sledeće načine:</span><span class="sxs-lookup"><span data-stu-id="3e5c4-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="3e5c4-106">Korisnik ne može da izbriše stavke iz poštanskog sandučeta.</span><span class="sxs-lookup"><span data-stu-id="3e5c4-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="3e5c4-107">Pomoćnik kontrolisane fascikle ne može da izbriše stavke zasnovane na oznaci zadržavanja ili postavkama kontrolisane fascikle.</span><span class="sxs-lookup"><span data-stu-id="3e5c4-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="3e5c4-108">Za Poštanske sandučiće koji imaju omogućenu podršku za jedan artikal ili su postavljeni na čekanju, proces zaštite stranice "Kopiraj na upisivanje" ne može da održava verzije stavki koje korisnik uređuje.</span><span class="sxs-lookup"><span data-stu-id="3e5c4-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="3e5c4-109">Za Poštanske sandučiće koji imaju omogućenu evidenciju nadgledanja u poštanskom sandučetu, nijedna stavka evidencije nadgledanja poštanskog sandučeta ne može biti sačuvana u potfascikli za reviziju u fascikli "Spasničke stavke".</span><span class="sxs-lookup"><span data-stu-id="3e5c4-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="3e5c4-110">Za Poštanske sandučiće koji nisu na čekanju, administratori mogu da `Search-Mailbox -SearchDumpsterOnly -DeleteContent` koriste komandu u Exchange online PowerShell za brisanje stavki u fascikli "Spasne stavke".</span><span class="sxs-lookup"><span data-stu-id="3e5c4-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="3e5c4-111">Za više informacija pogledajte sledeće teme:</span><span class="sxs-lookup"><span data-stu-id="3e5c4-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="3e5c4-112">Traženje i brisanje poruka</span><span class="sxs-lookup"><span data-stu-id="3e5c4-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="3e5c4-113">Pretraga-poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="3e5c4-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="3e5c4-114">Za Poštanske sandučiće koji su na čekanju, administratori moraju da uklone zadrške da bi mogli da izbrišu stavke iz fascikle "spasti stavke".</span><span class="sxs-lookup"><span data-stu-id="3e5c4-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="3e5c4-115">Više informacija potražite u članku [Brisanje stavki u fascikli "spasne stavke" Poštanske sandučiće na čekanju](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="3e5c4-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="3e5c4-116">Da bi sprečio da fascikla "spasti stavke" postane puna, administratori mogu da povećaju ograničenje prostora za skladištenje fascikli "spasdatoteke" za Poštanske sandučiće na čekanju i da postave smernice za zadržavanje poštanskog sandučeta koje premešta stavke iz fascikle "spasti stavke" u poštansko sanduče "arhiviranje".</span><span class="sxs-lookup"><span data-stu-id="3e5c4-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="3e5c4-117">Pogledajte odeljak [Povećavanje kvote za stavke koje se spasavaju za Poštanske sandučiće na čekanju](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="3e5c4-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>

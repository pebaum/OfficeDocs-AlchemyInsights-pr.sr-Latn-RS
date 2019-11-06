---
title: 2609-ili-ediscovery-održavanje
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994092"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a><span data-ttu-id="bd796-102">Nije moguće izbrisati stavke u sistemu SharePoint Online ili OneDrive za posao</span><span class="sxs-lookup"><span data-stu-id="bd796-102">Unable to delete items in SharePoint Online or OneDrive for Business</span></span>

<span data-ttu-id="bd796-103">Vi ili vaši korisnici možda nećete moći da izbrišete stavke na SharePoint mreži ili u usluzi OneDrive za posao zato što se smernice za zadržavanje, lokacija za zadržavanje ili eDiscovery zadršku primenjuju na SharePoint OneDrive lokaciju ili na određenu stavku.</span><span class="sxs-lookup"><span data-stu-id="bd796-103">You or your users may be unable to delete items in SharePoint Online or OneDrive for Business because a retention policy, retention label, or eDiscovery hold is applied to a SharePoint of OneDrive site or to a specific item.</span></span> <span data-ttu-id="bd796-104">Ovo podrazumeva da nije moguće izbrisati dokument, verziju dokumenta, fasciklu, biblioteku dokumenata, listu, aplikaciju, lokaciju ili kolekciju lokacija.</span><span class="sxs-lookup"><span data-stu-id="bd796-104">This includes being unable to delete a document, a document version, a folder, a document library, a list, an app, a site, or a site collection.</span></span> <span data-ttu-id="bd796-105">Evo nekih primera poruka o grešci koje možete da primite ako pokušate da izbrišete stavku koja se zadržava:</span><span class="sxs-lookup"><span data-stu-id="bd796-105">Here are some examples of the error messages you may received if you try to delete an item that is being retained:</span></span>

- <span data-ttu-id="bd796-106">"Nije moguće izbrisati ovu lokaciju zato što je uključena u eDiscovery zadršku ili zadržavanja"</span><span class="sxs-lookup"><span data-stu-id="bd796-106">"This site cannot be deleted because it is included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="bd796-107">"Ova lokacija ima smernice za usaglašenost podešene da blokiraju brisanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-107">"This site has a compliance policy set to block deletion"</span></span>
- <span data-ttu-id="bd796-108">"Smernice usaglašenosti trenutno blokiraju brisanje ove lokacije"</span><span class="sxs-lookup"><span data-stu-id="bd796-108">"A compliance policy is currently blocking this site deletion"</span></span>
- <span data-ttu-id="bd796-109">"Ova kolekcija lokacija ne može da se izbriše jer sadrži lokacije koje su uključene u smernice za eDiscovery zadržavanje ili zadržavanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-109">"This site collection can’t be deleted because it contains sites that are included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="bd796-110">"Morate da izbrišete sve stavke u ovoj fascikli pre nego što izbrišete fasciklu"</span><span class="sxs-lookup"><span data-stu-id="bd796-110">"You have to delete all the items in this folder before you delete the folder"</span></span>
- <span data-ttu-id="bd796-111">"Nije moguće izbrisati verzije ove stavke zato što je uključena u smernice za čekanje ili zadržavanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-111">"Versions of this item cannot be deleted because it is on hold or retention policy"</span></span>
- <span data-ttu-id="bd796-112">"Stavka se ne može izbrisati dok je na čekanju"</span><span class="sxs-lookup"><span data-stu-id="bd796-112">"Item cannot be deleted while on hold"</span></span>
- <span data-ttu-id="bd796-113">"Oznaka koja je primenjena na ovu stavku sprečava uređivanje ili brisanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-113">"The label that's applied to this item prevents it from being edited or deleted"</span></span>
- <span data-ttu-id="bd796-114">"Nije moguće izbrisati listu dok ste na smernicama za čekanje ili zadržavanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-114">"List cannot be deleted while on hold or retention policy"</span></span>
- <span data-ttu-id="bd796-115">"Nije moguće izbrisati listu ako je blokirana ili ako je primenjena smernica za zadržavanje"</span><span class="sxs-lookup"><span data-stu-id="bd796-115">"The list cannot be deleted if it is blocked or if a retention policy is applied to it"</span></span>

<span data-ttu-id="bd796-116">Da biste izbrisali stavke u jednom od ovih scenarija, moraju biti uklonjene smernice za zadržavanje, oznaka zadržavanja ili eDiscovery zadrška (ili lokacija mora biti isključena iz smernica za zadržavanje).</span><span class="sxs-lookup"><span data-stu-id="bd796-116">To delete items in one of these scenarios, the retention policy, retention label, or eDiscovery hold has to be removed (or a site has to be excluded from a retention policy).</span></span> <span data-ttu-id="bd796-117">Potrebno je da onemogućite ili isključite odgovarajući zadrška koji uzrokuje ovaj problem.</span><span class="sxs-lookup"><span data-stu-id="bd796-117">You need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="bd796-118">Nakon uklanjanja smernica za zadržavanje ili držanja, možda će biti potrebno najviše 24 sata da bi promena stupila na snagu.</span><span class="sxs-lookup"><span data-stu-id="bd796-118">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> 

<span data-ttu-id="bd796-119">Više informacija o različitim funkcijama zadržavanja i držanja koje se mogu primeniti na SharePoint lokacije i OneDrive naloge potražite u nekoj od sledećih tema.</span><span class="sxs-lookup"><span data-stu-id="bd796-119">For information about about the different retention and hold features that can be applied to SharePoint sites and OneDrive accounts, see one of the following topics.</span></span>

- [<span data-ttu-id="bd796-120">Pregled smernica za zadržavanje</span><span class="sxs-lookup"><span data-stu-id="bd796-120">Overview of retention policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [<span data-ttu-id="bd796-121">Pregled nalepnica za zadržavanje</span><span class="sxs-lookup"><span data-stu-id="bd796-121">Overview of retention labels</span></span>](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [<span data-ttu-id="bd796-122">Upravljaj zadrškama u naprednim eDiscovery</span><span class="sxs-lookup"><span data-stu-id="bd796-122">Manage holds in Advanced eDiscovery</span></span>](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [<span data-ttu-id="bd796-123">eDiscovery ima</span><span class="sxs-lookup"><span data-stu-id="bd796-123">eDiscovery holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [<span data-ttu-id="bd796-124">Naslijeđena pravila o zatvaranju i brisanju lokacije</span><span class="sxs-lookup"><span data-stu-id="bd796-124">Legacy site closure and deletion policies</span></span>](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)

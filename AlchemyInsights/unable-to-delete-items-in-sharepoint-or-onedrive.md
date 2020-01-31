---
title: Nije moguće izbrisati stavke u sistemu SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: abfcb91c6040aeed759d697ca63546ccea8ede97
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571285"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="b776e-102">Nije moguće izbrisati stavke</span><span class="sxs-lookup"><span data-stu-id="b776e-102">Unable to delete items</span></span>

<span data-ttu-id="b776e-103">Smernice za zadržavanje mogu da prouzrokuju ovo, potrebno je da onemogućite ili izuzmete odgovarajuće zadršku koji uzrokuje ovaj problem.</span><span class="sxs-lookup"><span data-stu-id="b776e-103">Retention policies can cause this, you need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="b776e-104">Nakon uklanjanja smernica za zadržavanje ili držanja, možda će biti potrebno najviše 24 sata da bi promena stupila na snagu.</span><span class="sxs-lookup"><span data-stu-id="b776e-104">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> <span data-ttu-id="b776e-105">Uverite se da na stavci nema podešavanja [smernica za zadržavanje](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .</span><span class="sxs-lookup"><span data-stu-id="b776e-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

<span data-ttu-id="b776e-106">Lokacija je možda prekoračila ograničenje prostora za skladištenje, povećala [kvotu lokacije](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) i izbrišite stavku.</span><span class="sxs-lookup"><span data-stu-id="b776e-106">The site might have exceeded storage limit, increase the [site quota](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) and delete the item.</span></span>

<span data-ttu-id="b776e-107">Uverite se da stavka nije [odjavljena](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) na drugi korisnik.</span><span class="sxs-lookup"><span data-stu-id="b776e-107">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

<span data-ttu-id="b776e-108">Na kraju, administratori mogu da koriste [SharePoint obrasce i prakse](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP) koji sadrže biblioteku komandi PowerShell koje vam omogućavaju da izvršavate složene radnje upravljanja, kao što je sila brisanje tvrdoglavih stavki.</span><span class="sxs-lookup"><span data-stu-id="b776e-108">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="b776e-109">Ukloni PNP datoteku</span><span class="sxs-lookup"><span data-stu-id="b776e-109">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="b776e-110">Ukloni PNP fasciklu</span><span class="sxs-lookup"><span data-stu-id="b776e-110">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="b776e-111">Uklanjanje stavke PNP liste</span><span class="sxs-lookup"><span data-stu-id="b776e-111">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="b776e-112">Ukloni PNP listu</span><span class="sxs-lookup"><span data-stu-id="b776e-112">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="b776e-113">Ukloni PNP polje (kolona)</span><span class="sxs-lookup"><span data-stu-id="b776e-113">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
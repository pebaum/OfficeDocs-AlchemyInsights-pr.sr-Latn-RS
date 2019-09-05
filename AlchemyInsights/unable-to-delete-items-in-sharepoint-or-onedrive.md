---
title: Nije moguće izbrisati stavke u sistemu SharePoint ili OneDrive
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 3cc168846999c6880b95edfaedb2df8cf6e843a6
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36748590"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="0189b-102">Nije moguće izbrisati stavke</span><span class="sxs-lookup"><span data-stu-id="0189b-102">Unable to delete items</span></span>

<span data-ttu-id="0189b-103">Imate li problema sa brisanjem SharePoint stavki?</span><span class="sxs-lookup"><span data-stu-id="0189b-103">Having issues deleting SharePoint items?</span></span>

- <span data-ttu-id="0189b-104">Uvek se uverite da imate [odgovarajuće dozvole](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) za brisanje stavke ili ako je [administrator kolekcije lokacija](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) pokušao da ukloni stavku.</span><span class="sxs-lookup"><span data-stu-id="0189b-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="0189b-105">Uverite se da na stavci nema podešavanja [smernica za zadržavanje](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .</span><span class="sxs-lookup"><span data-stu-id="0189b-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="0189b-106">Uverite se da stavka nije [odjavljena](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) na drugi korisnik.</span><span class="sxs-lookup"><span data-stu-id="0189b-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="0189b-107">Na kraju, administratori mogu da koriste [SharePoint obrasce i prakse](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP) koji sadrže biblioteku komandi PowerShell koje vam omogućavaju da izvršavate složene radnje upravljanja, kao što je sila brisanje tvrdoglavih stavki.</span><span class="sxs-lookup"><span data-stu-id="0189b-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="0189b-108">Ukloni PNP datoteku</span><span class="sxs-lookup"><span data-stu-id="0189b-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="0189b-109">Ukloni PNP fasciklu</span><span class="sxs-lookup"><span data-stu-id="0189b-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="0189b-110">Uklanjanje stavke PNP liste</span><span class="sxs-lookup"><span data-stu-id="0189b-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="0189b-111">Ukloni PNP listu</span><span class="sxs-lookup"><span data-stu-id="0189b-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="0189b-112">Ukloni PNP polje (kolona)</span><span class="sxs-lookup"><span data-stu-id="0189b-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
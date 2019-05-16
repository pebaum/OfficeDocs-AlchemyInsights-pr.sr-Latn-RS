---
title: Nije moguće izbrisati stavke u SharePoint ili OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057768"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="df242-102">Nije moguće izbrisati stavke</span><span class="sxs-lookup"><span data-stu-id="df242-102">Unable to delete items</span></span>

<span data-ttu-id="df242-103">Imamo problema brisanja stavki?</span><span class="sxs-lookup"><span data-stu-id="df242-103">Having issues deleting items?</span></span>

- <span data-ttu-id="df242-104">Uvek se uverite da imate [odgovarajuće dozvole](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) da izbrišete stavku ili je [administrator kolekcije lokacija](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) pokušaj da biste uklonili stavku.</span><span class="sxs-lookup"><span data-stu-id="df242-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="df242-105">Uverite se da tamo nije nameštaljka [smernica za čuvanje](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) na stavci.</span><span class="sxs-lookup"><span data-stu-id="df242-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="df242-106">Uverite se da stavka nije [odjavio](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) drugi korisnik.</span><span class="sxs-lookup"><span data-stu-id="df242-106">Ensure the item is not [checked out](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="df242-107">Konačno, administratori mogu da koriste [SharePoint šare i prakse](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) koje sadrži biblioteku PowerShell komande koje vam dozvoljavaju da izvršite složene upravljanja radnje kao što je prisiliti da brisanja stavki tvrdoglav.</span><span class="sxs-lookup"><span data-stu-id="df242-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span> 
- [<span data-ttu-id="df242-108">Uklonite PNP datoteku</span><span class="sxs-lookup"><span data-stu-id="df242-108">Remove PNP File</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="df242-109">Uklonite PNP fasciklu</span><span class="sxs-lookup"><span data-stu-id="df242-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="df242-110">Ukloni stavku PNP liste</span><span class="sxs-lookup"><span data-stu-id="df242-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="df242-111">Uklanjanje PNP liste</span><span class="sxs-lookup"><span data-stu-id="df242-111">Remove PNP List</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="df242-112">Uklonite PNP polje (kolona)</span><span class="sxs-lookup"><span data-stu-id="df242-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
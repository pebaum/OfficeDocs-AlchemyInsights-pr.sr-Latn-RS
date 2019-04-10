---
title: Rešavanje problema sa greška 404, datoteka nije pronađena
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 1b15444c-367b-4523-8e08-1c77bbea7524
ms.openlocfilehash: 2b0f6d84c53b812fe0552fc05473eebdfcc8d71a
ms.sourcegitcommit: 56c52c73e752414d66785f175c3a0e2925ad41c1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/02/2019
ms.locfileid: "31044053"
---
# <a name="troubleshoot-error-404-file-not-found"></a><span data-ttu-id="6e39e-102">Rešavanje problema sa greška 404, datoteka nije pronađena</span><span class="sxs-lookup"><span data-stu-id="6e39e-102">Troubleshoot Error 404, File not found</span></span>

<span data-ttu-id="6e39e-103">Neki greška 404 je primio kada korisnici pokušavate da pristupite lokaciji ili datoteka u SharePoint ili OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6e39e-103">An Error 404 is received when users are attempting to access a site or file in SharePoint or OneDrive.</span></span> <span data-ttu-id="6e39e-104">Ovo je često prouzrokovano sajt ili datoteke ili grupa postaje preimenovana, premeštena ili izbrisana.</span><span class="sxs-lookup"><span data-stu-id="6e39e-104">This is often caused by a site or file or group getting renamed, moved or deleted.</span></span> <span data-ttu-id="6e39e-105">Na primer: će korisnici iskusiti 404 greška pokušaja pristupa kolekciji lokacija na osnovnom i ona je izbrisana.</span><span class="sxs-lookup"><span data-stu-id="6e39e-105">For example: Users will experience a 404 Error attempting to access the Root Site Collection and it has been deleted.</span></span>

<span data-ttu-id="6e39e-106">Da biste otklonili grešku 404 za lokaciju koja je preimenovana, premeštena ili izbrisana:</span><span class="sxs-lookup"><span data-stu-id="6e39e-106">To resolve Error 404 for a Site that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="6e39e-107">Klasični lokacijama koje postoje u centru za Admin Classic, potražite [Vraćanje izbrisanih kolekciji](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="6e39e-107">For classic sites that exist in the Classic Admin Center, see [Restore a deleted site collection](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>


<span data-ttu-id="6e39e-108">Moderna lokacijama (komunikacije, grupa povezana, ili druge lokacije) koje postoje u novi admin centar za pregled, potražite u odeljku [prikaz i vraćanja izbrisane lokacije u centru za admin novu SharePoint](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="6e39e-108">For modern sites (communication, group-connected, or other sites) that exist in the new admin center preview, see [View and restore deleted sites in the new SharePoint admin center](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>

<span data-ttu-id="6e39e-109">Da biste otklonili grešku 404 za datoteke (ili druge stavke) to je preimenovana, premeštena ili izbrisana:</span><span class="sxs-lookup"><span data-stu-id="6e39e-109">To resolve Error 404 for a File (or other item) that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="6e39e-110">Idite na lokaciju SharePoint ili OneDrive i prikaz korpe za otpatke iz sadržaja na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="6e39e-110">Go to the SharePoint or OneDrive site and view the Recycle Bin from the Site contents.</span></span> <span data-ttu-id="6e39e-111">Vidi, [vraćanje stavki u korpu za otpatke na SharePoint lokaciji](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span><span class="sxs-lookup"><span data-stu-id="6e39e-111">See, [Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span></span>

<span data-ttu-id="6e39e-112">Ako ste i dalje nije moguće pronaći stavku možete da pretražujete evidenciju nadzora ako prijavljivanje je omogućeno pogledajte, [pretraživanje revizija prijavi u Office 365 bezbednosti & usklađenosti centar](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span><span class="sxs-lookup"><span data-stu-id="6e39e-112">If you are still unable to find the item you can search the audit log if logging is enabled see, [Search the audit log in the Office 365 Security & Compliance Center](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span></span>
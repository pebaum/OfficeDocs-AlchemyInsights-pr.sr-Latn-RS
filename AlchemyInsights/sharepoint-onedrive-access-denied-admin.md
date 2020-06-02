---
title: Rešavanje problema sa programom Access je porekao poruke
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 9430b9786b35dda9fb2604fb6ae3c39c8c258d6e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505393"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="5f394-102">Rešavanje problema sa pristupom odbijen je pristup porukama u sistemu SharePoint/OneDrive admin Center</span><span class="sxs-lookup"><span data-stu-id="5f394-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="5f394-103">Ako dobijate poruku o zabranama pristupa kada pokušate da potražite SharePoint/OneDrive admin Center, uverite se da ste [korisniku dodelili licencu](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span><span class="sxs-lookup"><span data-stu-id="5f394-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span></span> <span data-ttu-id="5f394-104">Ako korisnik ima licencu, trebalo bi takođe da se uverite da su [dodeljene administratorskom ulogom](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) koja može da pristupi administratorskim centrima.</span><span class="sxs-lookup"><span data-stu-id="5f394-104">If the user has a license, you should also make sure they are [assigned an administrator role](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) that can access the admin centers.</span></span>

<span data-ttu-id="5f394-105">Do ovog problema može doći i kada se korisnik izbriše i ponovo kreira sa istim glavnim korisničkim imenom (UPN).</span><span class="sxs-lookup"><span data-stu-id="5f394-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="5f394-106">Novi nalog se kreira koristeći drugačiju PUID (Passport jedinstveni ID) vrednost.</span><span class="sxs-lookup"><span data-stu-id="5f394-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="5f394-107">Kada korisnik pokuša da pristupi kolekciji lokacija ili usluzi OneDrive, korisnik ima neispravan PUID.</span><span class="sxs-lookup"><span data-stu-id="5f394-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="5f394-108">Drugi scenario uključuje sinhronizaciju direktorijuma sa organizacionom jedinicom aktivnog direktorijuma (OU).</span><span class="sxs-lookup"><span data-stu-id="5f394-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="5f394-109">Ako su korisnici već prijavljeni na SharePoint, a zatim se premeštaju u drugu i ponovo povezani sa SharePoint, može doći do ovog problema.</span><span class="sxs-lookup"><span data-stu-id="5f394-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="5f394-110">Da biste rešili ovaj problem, trebalo bi da vratite prvobitni UPNP korak sa koracima u članku, [vratite korisnika u aplikaciji Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="5f394-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>

<span data-ttu-id="5f394-111">Napomena: ako OneDrive ili SharePoint admin Center nije dostupan većem broju korisnika koji su ranije imali pristup, možda postoji problem sa privremenim servisom.</span><span class="sxs-lookup"><span data-stu-id="5f394-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="5f394-112">[Proverite kontrolnu tablu usluge za zdravstvo](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="5f394-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>



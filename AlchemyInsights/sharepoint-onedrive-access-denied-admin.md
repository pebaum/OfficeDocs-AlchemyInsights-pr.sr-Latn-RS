---
title: Rešavanje problema sa zabranom pristupa porukama
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: c204f1889e03886fdfd3d1c760a4a2beb82b0836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760354"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="03d4f-102">Rešavanje problema sa zabranom pristupa porukama u Sharepoint/OneDrive Admin Center</span><span class="sxs-lookup"><span data-stu-id="03d4f-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="03d4f-103">Ako dobijate pristup nije dozvoljen poruka pri pokušaju da pregledaju Sharepoint/OneDrive Admin centru, uverite se da [dodelite dozvole za korisnika](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="03d4f-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="03d4f-104">Ako korisnik ima dozvolu, obavezno takođe se uverite da su [dodeljene su ulogu administratora](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) koji možete da pristupite sa admin centrima.</span><span class="sxs-lookup"><span data-stu-id="03d4f-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="03d4f-105">Ovog problema takođe može doći kada korisnik je izbrisan i ponovo kreiran sa istom glavno ime korisnika (UPN).</span><span class="sxs-lookup"><span data-stu-id="03d4f-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="03d4f-106">Novi nalog kreiran pomoću različitih PUID (jedinstveni Passport ID) vrednost.</span><span class="sxs-lookup"><span data-stu-id="03d4f-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="03d4f-107">Kada korisnik pokuša da pristupi kolekciju lokacija ili njihove OneDrive, je jedan pogrešan PUID korisnika.</span><span class="sxs-lookup"><span data-stu-id="03d4f-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="03d4f-108">Drugi scenario uključuje sinhronizacija direktorijuma sa organizacionih jedinica za Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="03d4f-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="03d4f-109">Ako su korisnici već prijavljeni na SharePoint, i onda su se preselili u različitim OU i najhrabriji sa SharePoint, oni su iskusiti ovaj problem.</span><span class="sxs-lookup"><span data-stu-id="03d4f-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="03d4f-110">Da biste rešili ovaj problem, trebalo da vratite u prethodno stanje originalnu UPN sa koracima u članku, [Vraćanje korisnik u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="03d4f-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="03d4f-111">Napomena: Ako centar za OneDrive ili SharePoint Admin nije dostupna za više korisnika koji su prethodno imali pristup, postoji problem sa privremene usluge.</span><span class="sxs-lookup"><span data-stu-id="03d4f-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="03d4f-112">[Proverite kontrolnu tablu zdravstvenih usluga](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="03d4f-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>



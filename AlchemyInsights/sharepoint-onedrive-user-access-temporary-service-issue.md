---
title: Problemi sa performansama-SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 2dc0cd5f1641298853443d364eb9434ec1d9cd5a
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511162"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="305ec-102">SharePoint ili OneDrive sporo, nepristupačno ili nedostupan za više korisnika</span><span class="sxs-lookup"><span data-stu-id="305ec-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="305ec-103">Ako OneDrive ili SharePoint lokacija nije dostupna većem broju korisnika koji su ranije imali pristup, možda postoji problem sa privremenim servisom.</span><span class="sxs-lookup"><span data-stu-id="305ec-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="305ec-104">[Proverite kontrolnu tablu usluge za zdravstvo](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="305ec-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="305ec-105">**Dodaj i licenciraj korisnika**</span><span class="sxs-lookup"><span data-stu-id="305ec-105">**Add and license the user**</span></span>

<span data-ttu-id="305ec-106">Uverite se da ste [dodelili licence korisnicima u sistemu Microsoft 365 za posao](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span><span class="sxs-lookup"><span data-stu-id="305ec-106">Ensure that you [Assign licenses to users in Microsoft 365 for business](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span></span>


<span data-ttu-id="305ec-107">**Dodeli dozvole**</span><span class="sxs-lookup"><span data-stu-id="305ec-107">**Assign Permissions**</span></span>

<span data-ttu-id="305ec-108">Ako je korisniku dodeljena SharePoint licenca i još uvek prima poruku koja je zabranila pristup, proverite da li su dodeljeni [odgovarajući nivo dozvola](https://docs.microsoft.com/sharepoint/understanding-permission-levels) .</span><span class="sxs-lookup"><span data-stu-id="305ec-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/sharepoint/understanding-permission-levels) assigned.</span></span>

<span data-ttu-id="305ec-109">**Razmislite o korišćenju funkcije "zahtev za pristup"**</span><span class="sxs-lookup"><span data-stu-id="305ec-109">**Consider using the access request feature**</span></span>

<span data-ttu-id="305ec-110">[Funkcija zahteva za pristup](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) omogućava osobama da zahtevaju pristup sadržaju za koji trenutno nemaju dozvolu za pregled.</span><span class="sxs-lookup"><span data-stu-id="305ec-110">The [access request feature](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

<span data-ttu-id="305ec-111">**Dozvoli da prilagođena skripta uzrokuje probleme sa zabranim pristupom**</span><span class="sxs-lookup"><span data-stu-id="305ec-111">**Allow custom script may cause access denied issues**</span></span>

<span data-ttu-id="305ec-112">Postoje određeni slučajevi u kojima funkcija *Dozvoli prilagođeno skripte* može da predstavlja Nedozvoljen pristup.</span><span class="sxs-lookup"><span data-stu-id="305ec-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="305ec-113">Za spisak funkcija koje su pogođene, bezbednosna razmatranja i mogućnost onemogućavanja funkcija.</span><span class="sxs-lookup"><span data-stu-id="305ec-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="305ec-114">Molimo posetite [ili sprečite prilagođenu skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="305ec-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


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
ms.openlocfilehash: 5958ad06ca905f713b5f56aa5c536e95a485f01c
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735751"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="b0a5e-102">Rešavanje problema sa zabranom pristupa porukama</span><span class="sxs-lookup"><span data-stu-id="b0a5e-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="b0a5e-103">Ako dobijate pristup nije dozvoljen poruka pri pokušaju da potraži lokaciju Sharepoint Online, molim vas pogledajte na ispod članaka.</span><span class="sxs-lookup"><span data-stu-id="b0a5e-103">If you are receiving an access denied message when attempting to browse a Sharepoint Online site, please see the below articles.</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="b0a5e-104">Dodavanje i licenciranje korisnika</span><span class="sxs-lookup"><span data-stu-id="b0a5e-104">Add and License the user</span></span>

<span data-ttu-id="b0a5e-105">Uverite se da ste [dodelili licence korisnicima u Office 365 za poslovne](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="b0a5e-105">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>

<span data-ttu-id="b0a5e-106">Dodelite dozvole</span><span class="sxs-lookup"><span data-stu-id="b0a5e-106">Assign Permissions</span></span>

<span data-ttu-id="b0a5e-107">Ako korisnik je dodeljena dozvola Sharepoint, a i dalje prima pristup nije dozvoljen poruku, uverite se da oni imaju [odgovarajući nivo dozvola dodeljuje](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="b0a5e-107">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level assigned](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>

<span data-ttu-id="b0a5e-108">Razmotrite upotrebu funkcije zahtev za pristup</span><span class="sxs-lookup"><span data-stu-id="b0a5e-108">Consider using the access request feature</span></span>

<span data-ttu-id="b0a5e-109">Funkcija [zahteva pristup](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) omogućava osobama da biste zatražili pristup sadržaju koji trenutno nemaju dozvolu za gledanje.</span><span class="sxs-lookup"><span data-stu-id="b0a5e-109">The [access request](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) feature allows people to request access to content that they do not currently have permission to see.</span></span> 

<span data-ttu-id="b0a5e-110">Dozvoli adaptirani scenario može dovesti do toga da pristup nije dozvoljen pitanjima</span><span class="sxs-lookup"><span data-stu-id="b0a5e-110">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="b0a5e-111">Postoje određene scenarije gde je funkcija „Dozvoli adaptirani scenario” može biti predstavljajući pristup nije dozvoljen.</span><span class="sxs-lookup"><span data-stu-id="b0a5e-111">There are certain scenarios where the "Allow custom script" feature may be presenting an access denied.</span></span> <span data-ttu-id="b0a5e-112">Za listu funkcije na koje utiče, pitanja bezbednosti i mogućnost da onemogućite funkciju.</span><span class="sxs-lookup"><span data-stu-id="b0a5e-112">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="b0a5e-113">Posjetite, [Dozvoli ili sprečavaju adaptirani scenario](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span><span class="sxs-lookup"><span data-stu-id="b0a5e-113">Please visit , [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span></span>

<span data-ttu-id="b0a5e-114">Napomena: Ako OneDrive ili SharePoint lokacije nisu dostupni za više korisnika koji su prethodno imali pristup, postoji problem sa privremene usluge.</span><span class="sxs-lookup"><span data-stu-id="b0a5e-114">Note: If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="b0a5e-115">[Proverite kontrolnu tablu zdravstvenih usluga](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="b0a5e-115">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


  


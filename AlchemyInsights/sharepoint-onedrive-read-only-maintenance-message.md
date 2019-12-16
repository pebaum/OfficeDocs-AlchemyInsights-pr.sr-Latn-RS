---
title: Poruka "samo za čitanje" prilikom pokušaja korišćenja sistema SharePoint ili OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051295"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="c88f3-102">Poruka "samo za čitanje" prilikom pokušaja korišćenja sistema SharePoint ili OneDrive</span><span class="sxs-lookup"><span data-stu-id="c88f3-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="c88f3-103">Kada pokušate da koristite SharePoint ili OneDrive za jedan od sledećih scenarija, korisnici mogu da prime poruku **samo za čitanje** .</span><span class="sxs-lookup"><span data-stu-id="c88f3-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive for one of the following scenarios.</span></span> 

-   <span data-ttu-id="c88f3-104">Planirana ili aktivna aktivnost održavanja.</span><span class="sxs-lookup"><span data-stu-id="c88f3-104">A planned or active maintenance activity.</span></span>  <span data-ttu-id="c88f3-105">Proverite ih tako što ćete se krećete do [centra za poruke](https://portal.office.com/adminportal/home#/messagecenter).</span><span class="sxs-lookup"><span data-stu-id="c88f3-105">Check for them by navigating to the [Message Center](https://portal.office.com/adminportal/home#/messagecenter).</span></span>
-   <span data-ttu-id="c88f3-106">Događaj visokog prioriteta, koji može da se odvija.</span><span class="sxs-lookup"><span data-stu-id="c88f3-106">A high-priority, active service incident that may be occurring.</span></span> <span data-ttu-id="c88f3-107">Proverite da li postoje neki savetnici/incidenti u vezi sa [zdravstvom usluge](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="c88f3-107">Check for any advisories/incidents by navigating to [Service Health](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
-   <span data-ttu-id="c88f3-108">Neki niži scenario za automatsko lečenje koji se može dogoditi zbog neočekivanih događaja na serverima koji mogu da traju manje od 30 min.</span><span class="sxs-lookup"><span data-stu-id="c88f3-108">A minor auto-healing recovery scenario that could be happening due to any unexpected events on the servers which might last for less than 30 min or so.</span></span> 
    
    <span data-ttu-id="c88f3-109">Ne postoji centar za poruke ili zdravstveno stanje usluga za ove male funkcije za oporavak, ali bi trebalo da se vratite na normalan veoma brzo.</span><span class="sxs-lookup"><span data-stu-id="c88f3-109">There are no Message Center or Service Health posts for these minor recoveries but you should be back to normal very soon.</span></span>

<span data-ttu-id="c88f3-110">U veoma malo navrata primetili smo da je jedan od tri scenarija koji su navedeni gore bio uzrok, a usluga je vraćena u prethodno stanje, ali korisnici neće biti očišćeni.</span><span class="sxs-lookup"><span data-stu-id="c88f3-110">On very few occasions we observed that one of the three scenarios listed above have been the cause, and service has been restored, but the users browser cache hasn’t been cleared up.</span></span>

<span data-ttu-id="c88f3-111">Pokušajte da obrišete keš za pregledač pre nego što se krećete na lokaciju.</span><span class="sxs-lookup"><span data-stu-id="c88f3-111">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="c88f3-112">U pregledaču Microsoft Edge izaberite stavku **Postavke**, a zatim izaberite **privatnost i bezbednost**.</span><span class="sxs-lookup"><span data-stu-id="c88f3-112">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="c88f3-113">U okviru **Obriši pregledanje**izaberite stavku **Odaberite šta želite da obrišete**.</span><span class="sxs-lookup"><span data-stu-id="c88f3-113">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="c88f3-114">Izaberite **kolačiće i sačuvane podatke o Veb lokacijama**i izaberite opciju **Obriši**.</span><span class="sxs-lookup"><span data-stu-id="c88f3-114">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="c88f3-115">Ovi koraci se mogu razlikovati prilikom korišćenja drugih pregledača kao što su Mozilla Firefox ili Google Chrome.</span><span class="sxs-lookup"><span data-stu-id="c88f3-115">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="c88f3-116">Druga opcija bi bila da otvorite SharePoint lokaciju ili OneDrive u novom InPrivate prozoru.</span><span class="sxs-lookup"><span data-stu-id="c88f3-116">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>
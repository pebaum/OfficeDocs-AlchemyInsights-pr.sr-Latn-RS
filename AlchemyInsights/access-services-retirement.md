---
title: Pristup uslugama penzije
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 8886d7a6fad49e942e17f6a2f3c98542f87aae0b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36495765"
---
# <a name="access-services-retirement"></a><span data-ttu-id="9171b-102">Pristup uslugama penzije</span><span class="sxs-lookup"><span data-stu-id="9171b-102">Access services retirement</span></span>

<span data-ttu-id="9171b-103">Kao što smo prvobitno najavio u MC97576, u martu 2017, i nastavio da komuniciraju u proteklih godinu dana usluge pristupa su mirovinu iz Office 365.</span><span class="sxs-lookup"><span data-stu-id="9171b-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="9171b-104">Naredni u ovaj proces će biti uklanjanje Access Web baze podataka koje koriste SharePoint liste kao svoje osnovno skladište podataka.</span><span class="sxs-lookup"><span data-stu-id="9171b-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="9171b-105">**Kako to utiče na mene?**</span><span class="sxs-lookup"><span data-stu-id="9171b-105">**How does this affect me?**</span></span>

<span data-ttu-id="9171b-106">Počev od juna 2019, zaustavit ćemo stvaranje nove Access baze podataka u SharePoint Online se i isključite servis i preostale aplikacije do aprila 2020.</span><span class="sxs-lookup"><span data-stu-id="9171b-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="9171b-107">**Što trebam napraviti da se pripremite za ova promena?**</span><span class="sxs-lookup"><span data-stu-id="9171b-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="9171b-108">Savetujemo vam da napravite plan tranzicije za vaše organizacije Access web baze podataka.</span><span class="sxs-lookup"><span data-stu-id="9171b-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="9171b-109">Admini možete da koristite [SharePoint Access aplikacija za skener](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) da biste nabavili inventar Access aplikacija koje koriste lokacije.</span><span class="sxs-lookup"><span data-stu-id="9171b-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="9171b-110">Postoji nekoliko načina da biste migrirali podatke iz baze podataka programa Access web:</span><span class="sxs-lookup"><span data-stu-id="9171b-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="9171b-111">Uvoz u lokalnoj bazi podataka programa Access (. ACCDB) ili u Excel datoteku.</span><span class="sxs-lookup"><span data-stu-id="9171b-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="9171b-112">Takođe preporučujemo da istraživanje Microsoft PowerApps kao je alternativna platforma za kreiranje bez koda poslovnih rešenja za web i mobilne uređaje.</span><span class="sxs-lookup"><span data-stu-id="9171b-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>
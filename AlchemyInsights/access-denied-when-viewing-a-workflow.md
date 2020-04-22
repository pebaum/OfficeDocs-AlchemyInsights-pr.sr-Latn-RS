---
title: Pristup odbijen prilikom prikazivanja toka posla
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687344"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="c534a-102">Pristup odbijen prilikom prikazivanja toka posla</span><span class="sxs-lookup"><span data-stu-id="c534a-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="c534a-103">SharePoint 2013 tokovi posla koji pokušaju da pošalju e-poruku SharePoint grupi mogu da uspeju sa porukom o grešci "pristup nije dozvoljen" Ako članstvo SharePoint grupe nije postavljeno na svakoga.</span><span class="sxs-lookup"><span data-stu-id="c534a-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="c534a-104">**Da biste rešili ovaj problem, izvršite ove korake:**</span><span class="sxs-lookup"><span data-stu-id="c534a-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="c534a-105">Dozvolite svima da vide članove SharePoint grupe.</span><span class="sxs-lookup"><span data-stu-id="c534a-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="c534a-106">Uklonite SharePoint grupu iz reda "za" ili "CC" e-poruke.</span><span class="sxs-lookup"><span data-stu-id="c534a-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="c534a-107">Izričito dodajte korisnike u red "za" ili "CC" Ako se ne može promeniti vidljivost članstva za SharePoint grupu.</span><span class="sxs-lookup"><span data-stu-id="c534a-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="c534a-108">Da biste prikazali više detalja, pogledajte [http neovlašćen do/_vti_bin/Client.svc/SP.Utilities.Utility.sendemail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="c534a-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  
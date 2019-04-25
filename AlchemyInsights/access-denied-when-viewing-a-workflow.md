---
title: Zabranjen pristup prilikom prikazivanja toka posla
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 43369c600687d6ac253f70a8535dc2bd0d41687e
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32389901"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="4dfa1-102">Zabranjen pristup prilikom prikazivanja toka posla</span><span class="sxs-lookup"><span data-stu-id="4dfa1-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="4dfa1-103">SharePoint 2013 tokove posla koji se pokušaj pošaljite email SharePoint grupi možete propasti sa poruku o grešci „Pristup je odbijen” ako članstva SharePoint grupe podešen prema svima.</span><span class="sxs-lookup"><span data-stu-id="4dfa1-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="4dfa1-104">**Da biste rešili ovaj problem, izvršite ove korake:**</span><span class="sxs-lookup"><span data-stu-id="4dfa1-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="4dfa1-105">Dozvoli svima da vide članovi SharePoint grupe.</span><span class="sxs-lookup"><span data-stu-id="4dfa1-105">Allow everybody to see the members of the SharePoint group.</span></span> 
  
 2. <span data-ttu-id="4dfa1-106">Uklonite SharePoint grupu iz "za" i "CC red za e-poštu.</span><span class="sxs-lookup"><span data-stu-id="4dfa1-106">Remove the SharePoint group from the To or CC line of the email.</span></span> 
  
 3. <span data-ttu-id="4dfa1-107">Eksplicitno dodati korisnike za ili kopija u red ako članstvo vidljivost nije moguće promeniti SharePoint grupe.</span><span class="sxs-lookup"><span data-stu-id="4dfa1-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span> 
  
<span data-ttu-id="4dfa1-108">Da biste prikazali više detalja pogledajte [HTTP Unauthorized da /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="4dfa1-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  


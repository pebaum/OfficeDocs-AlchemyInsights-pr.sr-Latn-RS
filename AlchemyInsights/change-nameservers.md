---
title: Promena servera imena
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 572f8befd84f55cb07a3535852a46e735d3ed620
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706769"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="ea573-102">Ažurirajte servere imena domena tako da ukazuju na Microsoft</span><span class="sxs-lookup"><span data-stu-id="ea573-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="ea573-103">Napomena: Promena servera imena ponekad može da potraje do 48 časova.</span><span class="sxs-lookup"><span data-stu-id="ea573-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="ea573-104">Da biste podesili domen u sistemu Microsoft 365, serveri imena u registru treba da se ažuriraju.</span><span class="sxs-lookup"><span data-stu-id="ea573-104">To set up your domain in Microsoft 365, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="ea573-105">Kreirajte ili uredite zapise servera imena u registru domena.</span><span class="sxs-lookup"><span data-stu-id="ea573-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="ea573-106">Idite na veb sajt registra domena i pronađite oblast gde možete da uredite servere imena.</span><span class="sxs-lookup"><span data-stu-id="ea573-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="ea573-107">Kreirajte ili uredite dva zapisa servera imena tako da se podudaraju sa ovim vrednostima:</span><span class="sxs-lookup"><span data-stu-id="ea573-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="ea573-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="ea573-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="ea573-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="ea573-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="ea573-110">Sačuvajte promene.</span><span class="sxs-lookup"><span data-stu-id="ea573-110">Save changes.</span></span>

<span data-ttu-id="ea573-111">Takođe možete da pronađete detaljna uputstva u ovom članku: [Promena servera imena pomoću bilo kog registra domena](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="ea573-111">You can also find detailed instructions in this article: [Change nameservers with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  
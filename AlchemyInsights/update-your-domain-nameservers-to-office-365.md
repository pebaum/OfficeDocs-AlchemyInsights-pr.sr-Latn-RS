---
title: Ažurirajte servere imena domena tako da ukazuju na Microsoft
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 9dd52c60b2d15d66c1c3f2a96c9db08ea2a010c6
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510298"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="c2b91-102">Ažurirajte servere imena domena tako da ukazuju na Microsoft</span><span class="sxs-lookup"><span data-stu-id="c2b91-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="c2b91-103">Napomena: Promena servera imena ponekad može da potraje do 48 časova.</span><span class="sxs-lookup"><span data-stu-id="c2b91-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="c2b91-104">Da biste podesili svoj domen sa korporacijom Microsoft, potrebno je ažurirati imena imenervera u vašem matičar.</span><span class="sxs-lookup"><span data-stu-id="c2b91-104">To set up your domain with Microsoft, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="c2b91-105">Kreirajte ili uredite zapise servera imena u registru domena.</span><span class="sxs-lookup"><span data-stu-id="c2b91-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="c2b91-106">Idite na veb sajt registra domena i pronađite oblast gde možete da uredite servere imena.</span><span class="sxs-lookup"><span data-stu-id="c2b91-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="c2b91-107">Kreirajte ili uredite dva zapisa servera imena tako da se podudaraju sa ovim vrednostima:</span><span class="sxs-lookup"><span data-stu-id="c2b91-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="c2b91-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="c2b91-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="c2b91-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="c2b91-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="c2b91-110">Sačuvajte promene.</span><span class="sxs-lookup"><span data-stu-id="c2b91-110">Save changes.</span></span>

<span data-ttu-id="c2b91-111">U ovom članku takođe možete pronaći detaljna uputstva: [Promena imena imenicervera da biste podesili Microsoft 365 sa bilo kojim matičdomene domena](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="c2b91-111">You can also find detailed instructions in this article: [Change nameservers to set up Microsoft 365 with any domain registrar](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  
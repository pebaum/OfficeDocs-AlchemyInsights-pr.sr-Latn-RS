---
title: Ažuriranje servera imena domena u usluzi Office 365
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 5/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 8e25c510233f2a00d133ea69a338141c5a475465
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35352903"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="82fcc-102">Ažuriranje servera imena domena u usluzi Office 365</span><span class="sxs-lookup"><span data-stu-id="82fcc-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="82fcc-103">Napomena: Promena servera imena ponekad može da potraje do 48 časova.</span><span class="sxs-lookup"><span data-stu-id="82fcc-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="82fcc-104">Da biste podesili domen u usluzi Office 365, serveri imena u registru treba da se ažuriraju.</span><span class="sxs-lookup"><span data-stu-id="82fcc-104">To set up your domain in Office 365, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="82fcc-105">Kreirajte ili uredite zapise servera imena u registru domena.</span><span class="sxs-lookup"><span data-stu-id="82fcc-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="82fcc-106">Idite na veb sajt registra domena i pronađite oblast gde možete da uredite servere imena.</span><span class="sxs-lookup"><span data-stu-id="82fcc-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="82fcc-107">Kreirajte ili uredite dva zapisa servera imena tako da se podudaraju sa ovim vrednostima:</span><span class="sxs-lookup"><span data-stu-id="82fcc-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="82fcc-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="82fcc-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="82fcc-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="82fcc-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="82fcc-110">Sačuvajte promene.</span><span class="sxs-lookup"><span data-stu-id="82fcc-110">Save changes.</span></span>

<span data-ttu-id="82fcc-111">Takođe možete da pronađete detaljna uputstva u ovom članku: [Promena servera imena radi podešavanja usluge Office 365 pomoću bilo kog registra domena](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="82fcc-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  
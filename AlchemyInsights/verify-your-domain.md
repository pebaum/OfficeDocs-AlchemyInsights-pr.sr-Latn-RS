---
title: Provjerite vaš domen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "47"
- "48"
- "8"
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: 5bd6c32a246db9dfcdb475368ade0441df4dc9c3
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35365431"
---
# <a name="verify-your-domain"></a><span data-ttu-id="44e42-102">Provjerite vaš domen</span><span class="sxs-lookup"><span data-stu-id="44e42-102">Verify your domain</span></span>

 <span data-ttu-id="44e42-103">**Zapis se verovatno nije menjao preko interneta.**</span><span class="sxs-lookup"><span data-stu-id="44e42-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="44e42-104">Obično samo traje nekoliko minuta za nas da bi mogli da vidite novi zapis, ali ponekad to može potrajati i nekoliko sati.</span><span class="sxs-lookup"><span data-stu-id="44e42-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="44e42-105">Ako ste čekali ste to već dugo, ponovo proverite da ste kopirati i nalepiti točna vrijednost u TXT zapis verifikacije na vaš domaćin DNS.</span><span class="sxs-lookup"><span data-stu-id="44e42-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="44e42-106">Jedan zajednički problem je ne uključujući u „MS =” deo zapisa.</span><span class="sxs-lookup"><span data-stu-id="44e42-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="44e42-107">Treba nam to!</span><span class="sxs-lookup"><span data-stu-id="44e42-107">We need that too!</span></span>

- <span data-ttu-id="44e42-108">Kod nekih DNS domaćini, morate uzeti dodatni korak da biste sačuvali datoteku u zoni (gde je DNS zapis uskladišten) tako da to će ažurirati preko interneta.</span><span class="sxs-lookup"><span data-stu-id="44e42-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="44e42-109">Uverite se da ste sačuvali promene tako Office 365 možete da vidite i provjerite zapisnik.</span><span class="sxs-lookup"><span data-stu-id="44e42-109">Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>

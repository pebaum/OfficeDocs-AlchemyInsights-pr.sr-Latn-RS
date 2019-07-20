---
title: isto kao i ime datoteke je najbolje
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 31a578800468e9f3a69fff4f6e2e1945943c779c
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800059"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="49196-102">Potrebne alhemija zaglavlje H1, H2, ne radim.</span><span class="sxs-lookup"><span data-stu-id="49196-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="49196-103">Najbolje prakse i uputstva za kreiranje alhemija:</span><span class="sxs-lookup"><span data-stu-id="49196-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="49196-104">**Ne Gnezde se alhemija uvida u fasciklama**- ovo će slomiti url strukturu.</span><span class="sxs-lookup"><span data-stu-id="49196-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="49196-105">Proveravamo drugog izlaza.</span><span class="sxs-lookup"><span data-stu-id="49196-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="49196-106">Datoteke u mapi **AlchemyInsights** treba da ima mala slova imena datoteka sa crticama na prostorima ex.</span><span class="sxs-lookup"><span data-stu-id="49196-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="49196-107">***Kako-da omogući-parnice-drži***.</span><span class="sxs-lookup"><span data-stu-id="49196-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="49196-108">Uključite ID ID pravila "ili" kanta sa [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) u ms.custom polju.</span><span class="sxs-lookup"><span data-stu-id="49196-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="49196-109">bivsi.</span><span class="sxs-lookup"><span data-stu-id="49196-109">ex.</span></span> <span data-ttu-id="49196-110">***Ms.Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="49196-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="49196-111">Koristite ostatak metapodatke na vrhu ovu datoteku kao predložak.</span><span class="sxs-lookup"><span data-stu-id="49196-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="49196-112">U [alhemija partnerski portal](https://alchemyportal.azurewebsites.net), dođite do odeljka **kupca uvid naslov:** i koristi to kao početak postavite H1 naslova za uvid.</span><span class="sxs-lookup"><span data-stu-id="49196-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="49196-113">Alhemija uvid mora da ima samo za jednu H1 na vrhu ili Razbit će se u proizvodnji.</span><span class="sxs-lookup"><span data-stu-id="49196-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="49196-114">H2s ne donosi toliko koristi **podebljano** ili drugim konvencijama koje će označavati odvojene sekcije.</span><span class="sxs-lookup"><span data-stu-id="49196-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="49196-115">Zatim popunite telo teksta koristeći nacrt materijal u odeljku kupca opažanja alhemija pravilo stranice</span><span class="sxs-lookup"><span data-stu-id="49196-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="49196-116">Znakovima za nabrajanje su u redu</span><span class="sxs-lookup"><span data-stu-id="49196-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="49196-117">I numerisane liste</span><span class="sxs-lookup"><span data-stu-id="49196-117">Numbered lists too</span></span>
    1. <span data-ttu-id="49196-118">**Podebljano** i *kurzivno* su tudu</span><span class="sxs-lookup"><span data-stu-id="49196-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="49196-119">Veze treba da bude ni **„veze ka web” / eksterni** OR **duboko-veze ka elemente korisničkog Interfejsa**, ne interne veze.</span><span class="sxs-lookup"><span data-stu-id="49196-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="49196-120">Slike su službeno nije podržana u ovom trenutku, ali je o planu.</span><span class="sxs-lookup"><span data-stu-id="49196-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="49196-121">I ovo je stvarno već malo predugo.</span><span class="sxs-lookup"><span data-stu-id="49196-121">And this is really already a bit too long.</span></span> <span data-ttu-id="49196-122">Najbolji metod je oko 400 znakova---</span><span class="sxs-lookup"><span data-stu-id="49196-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="49196-123">Kada sadržaj bude spreman, povuci za uživo granu.</span><span class="sxs-lookup"><span data-stu-id="49196-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="49196-124">Onda, idi do [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) i unesite ime datoteke u polje URL adresa.</span><span class="sxs-lookup"><span data-stu-id="49196-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> 
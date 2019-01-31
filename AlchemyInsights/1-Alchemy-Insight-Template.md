---
title: 'isto kao i ime datoteke je najbolje [pravilo #-opis]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 1bb1cb35f06e16a2dc85b7e2642b9fa0d203945e
ms.sourcegitcommit: b032c2ac45540b1eb5dd68a4ec7ce1a5d6922f0e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662944"
---
# <a name="required-customer-facing-h1-h2-doesnt-work"></a><span data-ttu-id="aeed9-102">Zahteva kupaca sa kojima se suočava H1, H2 ne radi.</span><span class="sxs-lookup"><span data-stu-id="aeed9-102">Required Customer Facing H1, H2 doesn't work</span></span>
<span data-ttu-id="aeed9-103">Primer teksta blokirano - slijedite ove upute:</span><span class="sxs-lookup"><span data-stu-id="aeed9-103">Example text block - follow these instructions:</span></span>

1. <span data-ttu-id="aeed9-104">Datoteke u fascikli " **AlchemyInsights** " bi trebalo pravilo ID i ime pravila iz [alhemije partnerski portal](https://alchemyportal.azurewebsites.net) u ime datoteke.</span><span class="sxs-lookup"><span data-stu-id="aeed9-104">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="aeed9-p101">npr. ***976-How-to-enable-litigation-hold***</span><span class="sxs-lookup"><span data-stu-id="aeed9-p101">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="aeed9-p102">Koristite metapodatke na vrhu ovu datoteku kao predložak. Nije bio potreban.</span><span class="sxs-lookup"><span data-stu-id="aeed9-p102">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="aeed9-109">U [alhemija partnerski portal](https://alchemyportal.azurewebsites.net), dođite do odeljka **kupca uvid naslov:** i koristi to kao početak postavite H1 naslova za uvid.</span><span class="sxs-lookup"><span data-stu-id="aeed9-109">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="aeed9-p103">Alhemija uvid mora da ima samo za jednu H1 na vrhu ili Razbit će se u proizvodnji. H2s ne donosi toliko koristi **podebljano** ili drugim konvencijama koje će označavati odvojene sekcije.</span><span class="sxs-lookup"><span data-stu-id="aeed9-p103">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="aeed9-112">Zatim popunite telo teksta koristeći nacrt materijal u odeljku kupca opažanja alhemija pravilo stranice</span><span class="sxs-lookup"><span data-stu-id="aeed9-112">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="aeed9-113">Znakovima za nabrajanje su u redu</span><span class="sxs-lookup"><span data-stu-id="aeed9-113">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="aeed9-114">I numerisane liste</span><span class="sxs-lookup"><span data-stu-id="aeed9-114">Numbered lists too</span></span>
    1. <span data-ttu-id="aeed9-115">**Podebljano** i *kurzivno* su tudu</span><span class="sxs-lookup"><span data-stu-id="aeed9-115">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="aeed9-116">Veze treba da bude ni **„veze ka web” / eksterni** OR **duboko-veze ka elemente korisničkog Interfejsa**, ne interne veze.</span><span class="sxs-lookup"><span data-stu-id="aeed9-116">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="aeed9-p104">I ovo je stvarno već malo predugo. Najbolji metod je oko 400 znakova---</span><span class="sxs-lookup"><span data-stu-id="aeed9-p104">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="aeed9-p105">Kada sadržaj bude spreman, povuci za uživo granu. Onda, idi do [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) i unesite ime datoteke u polje URL adresa. Uverite se da uvid pregledali i objavili kaže „da”, a zatim izaberite stavku ažuriranje pravilo. (Ovo će izgledaju lepse u novu verziju portal - otpuštajući uskoro).</span><span class="sxs-lookup"><span data-stu-id="aeed9-p105">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. (This will look prettier in the new version of the portal - releasing soon.)</span></span>

![URL polje](media/for-content-team.PNG)


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
ms.openlocfilehash: 278a26f4b986a85e33442baef690d3bb44462ace
ms.sourcegitcommit: 32355b76d45b730a069575efeec708149d4aeaa3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/01/2019
ms.locfileid: "29697144"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="d2c4e-102">Potrebne alhemija zaglavlje H1, H2, ne radim.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="d2c4e-103">Najbolje prakse i uputstva za kreiranje alhemija:</span><span class="sxs-lookup"><span data-stu-id="d2c4e-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="d2c4e-p101">**Ne Gnezde se alhemija uvida u fasciklama**- ovo će slomiti url strukturu. Proveravamo drugog izlaza.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p101">**Do not nest Alchemy Insights in folders**- this will break the url structure. We're looking into fixing this.</span></span>
1. <span data-ttu-id="d2c4e-106">Datoteke u fascikli " **AlchemyInsights** " bi trebalo pravilo ID i ime pravila iz [alhemije partnerski portal](https://alchemyportal.azurewebsites.net) u ime datoteke.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="d2c4e-p102">npr. ***976-How-to-enable-litigation-hold***</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p102">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="d2c4e-p103">Koristite metapodatke na vrhu ovu datoteku kao predložak. Nije bio potreban.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p103">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="d2c4e-111">U [alhemija partnerski portal](https://alchemyportal.azurewebsites.net), dođite do odeljka **kupca uvid naslov:** i koristi to kao početak postavite H1 naslova za uvid.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="d2c4e-p104">Alhemija uvid mora da ima samo za jednu H1 na vrhu ili Razbit će se u proizvodnji. H2s ne donosi toliko koristi **podebljano** ili drugim konvencijama koje će označavati odvojene sekcije.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p104">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="d2c4e-114">Zatim popunite telo teksta koristeći nacrt materijal u odeljku kupca opažanja alhemija pravilo stranice</span><span class="sxs-lookup"><span data-stu-id="d2c4e-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="d2c4e-115">Znakovima za nabrajanje su u redu</span><span class="sxs-lookup"><span data-stu-id="d2c4e-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="d2c4e-116">I numerisane liste</span><span class="sxs-lookup"><span data-stu-id="d2c4e-116">Numbered lists too</span></span>
    1. <span data-ttu-id="d2c4e-117">**Podebljano** i *kurzivno* su tudu</span><span class="sxs-lookup"><span data-stu-id="d2c4e-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="d2c4e-118">Veze treba da bude ni **„veze ka web” / eksterni** OR **duboko-veze ka elemente korisničkog Interfejsa**, ne interne veze.</span><span class="sxs-lookup"><span data-stu-id="d2c4e-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="d2c4e-p105">I ovo je stvarno već malo predugo. Najbolji metod je oko 400 znakova---</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p105">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="d2c4e-p106">Kada sadržaj bude spreman, povuci za uživo granu. Onda, idi do [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) i unesite ime datoteke u polje URL adresa. Uverite se da uvid pregledali i objavili kaže „da”, a zatim izaberite stavku ažuriranje pravilo. **(Ovo će izgledaju lepse u novu verziju portal - otpuštajući uskoro).** 
 ![url polje](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="d2c4e-p106">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. **(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>


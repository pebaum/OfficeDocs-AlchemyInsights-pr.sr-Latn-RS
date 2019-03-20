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
ms.openlocfilehash: ec979c2f2246fa06945b79bbb9348a7a57ad5180
ms.sourcegitcommit: b3cf5130ac8118f0fed66abe5286aa80ee91af52
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/19/2019
ms.locfileid: "30683863"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Potrebne alhemija zaglavlje H1, H2, ne radim.
Najbolje prakse i uputstva za kreiranje alhemija:

1. **Ne Gnezde se alhemija uvida u fasciklama**- ovo će slomiti url strukturu. Proveravamo drugog izlaza.
1. Datoteke u mapi **AlchemyInsights** treba da ima mala slova imena datoteka sa crticama na prostorima ex. ***Kako-da omogući-parnice-drži***.
    1. Uključite ID ID pravila "ili" kanta sa [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) u ms.custom polju. bivsi. ***Ms.Custom: 100021***
1. Koristite ostatak metapodatke na vrhu ovu datoteku kao predložak.
1. U [alhemija partnerski portal](https://alchemyportal.azurewebsites.net), dođite do odeljka **kupca uvid naslov:** i koristi to kao početak postavite H1 naslova za uvid. 
    > [!NOTE]
    > Alhemija uvid mora da ima samo za jednu H1 na vrhu ili Razbit će se u proizvodnji. H2s ne donosi toliko koristi **podebljano** ili drugim konvencijama koje će označavati odvojene sekcije.
1. Zatim popunite telo teksta koristeći nacrt materijal u odeljku kupca opažanja alhemija pravilo stranice
    1. Znakovima za nabrajanje su u redu
    1. I numerisane liste
    1. **Podebljano** i *kurzivno* su tudu
    1. Veze treba da bude ni **„veze ka web” / eksterni** OR **duboko-veze ka elemente korisničkog Interfejsa**, ne interne veze.
    1. Slike su službeno nije podržana u ovom trenutku, ali je o planu.

I ovo je stvarno već malo predugo. Najbolji metod je oko 400 znakova---

Kada sadržaj bude spreman, povuci za uživo granu. Onda, idi do [alhemija partnerski portal](https://alchemyportal.azurewebsites.net) i unesite ime datoteke u polje URL adresa. M
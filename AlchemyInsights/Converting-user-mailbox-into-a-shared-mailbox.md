---
title: Pretvaranje korisničko poštansko sanduče u Deljeno poštansko sanduče?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29487392"
---
<span data-ttu-id="0ee1c-p101">Samo pretvaranja korisničko poštansko sanduče za Deljeno poštansko sanduče ako korisnik nema licencu za Exchange. Nakon što se konvertuje u poštansko sanduče, to će nastaviti da se pojavi u listi aktivnih korisnika, zato što ta lista uključuje deljene poštanskih sandučića. Međutim, poštansko sanduče na konvertovani će takođe se pojaviti na listi Deljeno poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="0ee1c-p101">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license. After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes. However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="0ee1c-p102">Ako pokušate da konvertujete u konzoli Admin Exchange poštansko sanduče, a konverzije ne uspe, opozovite svoje keša pregledača i kolačiće i pokušajte ponovo. Ako to i dalje ne radi, pokušajte da konvertujete poštansko sanduče u Exchange Management Shell tako što ćete pokrenuti sljedeću naredbu:</span><span class="sxs-lookup"><span data-stu-id="0ee1c-p102">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again. If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="0ee1c-107">Više informacija za konverziju poštansko sanduče dostupno je u [pretvorite poštansko sanduče korisnika sa deljenom poštanskim sandučetom](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="0ee1c-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  

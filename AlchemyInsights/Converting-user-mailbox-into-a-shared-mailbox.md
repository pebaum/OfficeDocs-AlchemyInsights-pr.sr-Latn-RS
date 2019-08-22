---
title: Pretvaranje korisničko poštansko sanduče u Deljeno poštansko sanduče?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496449"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a><span data-ttu-id="f3e2c-102">Okvir za poštu korisnika pretvori Deljeno poštansko sanduče</span><span class="sxs-lookup"><span data-stu-id="f3e2c-102">Convert a user mail box into a shared mailbox</span></span>

<span data-ttu-id="f3e2c-103">Samo pretvaranja korisničko poštansko sanduče za Deljeno poštansko sanduče ako korisnik nema licencu za Exchange.</span><span class="sxs-lookup"><span data-stu-id="f3e2c-103">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="f3e2c-104">Nakon što se konvertuje u poštansko sanduče, to će nastaviti da se pojavi u listi aktivnih korisnika, zato što ta lista uključuje deljene poštanskih sandučića.</span><span class="sxs-lookup"><span data-stu-id="f3e2c-104">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="f3e2c-105">Međutim, poštansko sanduče na konvertovani će takođe se pojaviti na listi Deljeno poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="f3e2c-105">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="f3e2c-106">Ako pokušate da konvertujete u konzoli Admin Exchange poštansko sanduče, a konverzije ne uspe, opozovite svoje keša pregledača i kolačiće i pokušajte ponovo.</span><span class="sxs-lookup"><span data-stu-id="f3e2c-106">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="f3e2c-107">Ako to i dalje ne radi, pokušajte da konvertujete poštansko sanduče u Exchange Management Shell tako što ćete pokrenuti sljedeću naredbu:</span><span class="sxs-lookup"><span data-stu-id="f3e2c-107">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="f3e2c-108">Više informacija za konverziju poštansko sanduče dostupno je u [pretvorite poštansko sanduče korisnika sa deljenom poštanskim sandučetom](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span><span class="sxs-lookup"><span data-stu-id="f3e2c-108">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span></span>
  

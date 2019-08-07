---
title: 1332 OWA - poštanskom sandučetu pravila se ne izvršava za poštansko sanduče
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 218a05a8d321b76dd07345ea48d6b3e158cc120e
ms.sourcegitcommit: 77f704672b7c7de541899e25c022ff10c111e304
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/05/2019
ms.locfileid: "36204074"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="06572-102">Pravilo za Prispjelu poštu ne radi kao što se očekivalo</span><span class="sxs-lookup"><span data-stu-id="06572-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="06572-103">Provjerite sljedeće postavke:</span><span class="sxs-lookup"><span data-stu-id="06572-103">Verify the following settings:</span></span>

- <span data-ttu-id="06572-104">Poruku možete preusmerena, prosleđivanja ili odgovoreno da automatski na osnovu pravila prijemnog samo jedan put.</span><span class="sxs-lookup"><span data-stu-id="06572-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="06572-105">Preusmeravanje pravilo (pravilo za Prispjelu poštu ili protok pravilo za poštu, poznat i kao transportni pravilo) možete dodati najviše 10 špedicije primaoci poruke.</span><span class="sxs-lookup"><span data-stu-id="06572-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="06572-106">Za više informacija, pogledajte [dnevnik, Transport, i poštanskom sandučetu pravilo ograničenja](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="06572-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="06572-107">Poštanskom sandučetu pravila ne funkcionišu u poštansko sanduče na alternativni ugojena.</span><span class="sxs-lookup"><span data-stu-id="06572-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="06572-108">Za više informacija o poštanskom sandučetu alternativni ugojena, vidim [poštansko sanduče alternativni ugojena](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="06572-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="06572-109">Da biste rešili ove probleme, vidim [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="06572-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="06572-110">Ako prethodna pitanja ne odnose, pokrenite dijagnostiku izveštaj prijemnog pravilo pre nego što si eskalirati problem na lokaciji Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="06572-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="06572-111">Otvoriti poštansko sanduče u programu Outlook na Webu, i kliknite na dugme</span><span class="sxs-lookup"><span data-stu-id="06572-111">Open the mailbox in Outlook on the web, and click</span></span> <img src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAMAAABhEH5lAAAA51BMVEX6+fj6+fDr+fjK+fj69LRxsuj6+cjY+fi/+fin3ev6+ddMk81HdK5AaatHLn/ntXTrsW5cRmLOk0pAND5KNCl1NCOi3fiGwvjJ3fDBz+F6teFgpdt6stX68c314syTucirtchum8bjz8BQh7/6+b47fbrKtapiian63aFDaaHJuZJiQo36woVabH7ZtHiOQnTHm2wlKmqriWF/cFzVnVTFjlSyeUkrNEmBLkWfaUGsaT67fTrj9Pi19PjO8fiv5vj69OFWm9Pt3aZ1Qo0lNHQ1P2iYTWGOQmHcpV5kRlqvc0mrbERpPzMoEeekAAAAxElEQVQY03WQ5w6CUAyFy3Jv3HsrICoKqLj3fP/nsTcNakjsn9t+bW/OKfyL6iTCc49e/ktuRs2WEhE1U/qgQQfEzGkNyxzVXLdw0ASW+a7BZp3HpJ+cpovUjcv6PYtvSmKj4/SswTMaBgg9FQF5axWysKoson4cGMYCvlEAQDwK7XkZwEVbRBpDPC46ygbAbPl31p4Wvd8nwiRCLnIArJb1ZBD7KFWMkdQLSUVIhowsGaIwzzVHikfVV8lzHPv3OGTfTd4gnRNqGdZ49AAAAABJRU5ErkJggg==' />
 <span data-ttu-id="06572-112">**Postavke** > **Prikaz svih postavki programa Outlook** > **e** > **pravila**.</span><span class="sxs-lookup"><span data-stu-id="06572-112">**Settings** > **View all Outlook Settings** > **Mail** > **Rules**.</span></span>

2. <span data-ttu-id="06572-113">U donjem delu stranice, izaberite opciju **Ako vaša pravila ne rade kliknite ovde da biste generisali dijagnostički izveštaj**.</span><span class="sxs-lookup"><span data-stu-id="06572-113">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>

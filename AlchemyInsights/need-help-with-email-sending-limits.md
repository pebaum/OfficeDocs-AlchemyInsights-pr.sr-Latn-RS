---
title: Potrebna vam je pomoć sa ograničenjima za slanje e-pošte?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002938"
- "5630"
ms.openlocfilehash: 7f563df313c869d18c3e4240d271c649a74914af
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/20/2020
ms.locfileid: "44358357"
---
# <a name="need-help-with-email-sending-limits"></a><span data-ttu-id="b6af6-102">Potrebna vam je pomoć sa ograničenjima za slanje e-pošte?</span><span class="sxs-lookup"><span data-stu-id="b6af6-102">Need help with email sending limits?</span></span>

<span data-ttu-id="b6af6-103">U nastavku se nalaze **ograničenja koja šalju po dizajnu** primenjena u usluzi.</span><span class="sxs-lookup"><span data-stu-id="b6af6-103">Below is the **by-design sending limits** enforced in the service.</span></span> <span data-ttu-id="b6af6-104">Više informacija o ovim ograničenjima je [ovde](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits)dokumentovano.</span><span class="sxs-lookup"><span data-stu-id="b6af6-104">More information on these limits is documented [here](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).</span></span>

- <span data-ttu-id="b6af6-105">Da bismo obeshrabrili isporuku neželjenih masovnih poruka, primenjujemo **ograničenje za kamatne stope po korisniku za sve izlazne i interne poruke**.</span><span class="sxs-lookup"><span data-stu-id="b6af6-105">To discourage the delivery of unsolicited bulk messages, we apply per-user **recipient rate limits to all outbound and internal messages**.</span></span> <span data-ttu-id="b6af6-106">U svim skusu, ovo ograničenje je **10.000 primalaca dnevno**.</span><span class="sxs-lookup"><span data-stu-id="b6af6-106">Across all SKUs, this limit is **10,000 recipients per day**.</span></span>  <span data-ttu-id="b6af6-107">Korisnici kojima je potrebno da pošalju legitimnu komercijalnu e-poštu (na primer, bilteni za korisnike) trebalo bi da koriste nezavisne dobavljače koji su specijalizovani za te usluge.</span><span class="sxs-lookup"><span data-stu-id="b6af6-107">Customers who need to send legitimate bulk commercial email (for example, customer newsletters) should use third-party providers that specialize in these services.</span></span>
    - <span data-ttu-id="b6af6-108">**Napomena**: kada se dostigne ograničenje brzine primaoca, poruke se ne mogu poslati iz poštanskog sandučeta sve dok broj primalaca koji su poslate poruke u protekla 24 časa ne padne ispod granice.</span><span class="sxs-lookup"><span data-stu-id="b6af6-108">**Note**: Once the recipient rate limit is reached, messages can't be sent from the mailbox until the number of recipients that were sent messages in the past 24 hours drops below the limit.</span></span> <span data-ttu-id="b6af6-109">Korisnik neće moći da šalje poruke do te tačke.</span><span class="sxs-lookup"><span data-stu-id="b6af6-109">The user will not be able to send messages until that point.</span></span>
- <span data-ttu-id="b6af6-110">Ograničenje brzine poruke od **30 poruka u minutu** se primenjuje na svim MJ.</span><span class="sxs-lookup"><span data-stu-id="b6af6-110">Message rate limit of **30 messages per minute** is applied across all SKUs.</span></span> <span data-ttu-id="b6af6-111">Ovo određuje broj poruka koje korisnik može da pošalje sa svog naloga za Exchange Online u okviru navedenog perioda.</span><span class="sxs-lookup"><span data-stu-id="b6af6-111">This determines how many messages a user can send from their Exchange Online account within a specified period.</span></span>
- <span data-ttu-id="b6af6-112">**Maksimalni broj primalaca dozvoljen u poljima "za", "Cc" i "Bcc** " za jednu e-poruku, preko svih MJ, je **1000 primalaca**.</span><span class="sxs-lookup"><span data-stu-id="b6af6-112">The **maximum number of recipients allowed in the To, Cc, and Bcc** fields for a single email message, across all SKUs, is **1000 recipients**.</span></span> <span data-ttu-id="b6af6-113">Da biste prilagodili ovo ograničenje, idite [ovde](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span><span class="sxs-lookup"><span data-stu-id="b6af6-113">To customize this limit, go [here](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span></span>

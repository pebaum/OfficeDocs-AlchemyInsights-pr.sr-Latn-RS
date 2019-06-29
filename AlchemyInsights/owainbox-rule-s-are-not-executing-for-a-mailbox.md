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
ms.openlocfilehash: 7d1848830847fc6722da20e09a4875f49bf02bd3
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35360931"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="422c7-102">Pravilo za Prispjelu poštu ne radi kao što se očekivalo</span><span class="sxs-lookup"><span data-stu-id="422c7-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="422c7-103">Provjerite sljedeće postavke:</span><span class="sxs-lookup"><span data-stu-id="422c7-103">Verify the following settings:</span></span>

- <span data-ttu-id="422c7-104">Poruku možete preusmerena, prosleđivanja ili odgovoreno da automatski na osnovu pravila prijemnog samo jedan put.</span><span class="sxs-lookup"><span data-stu-id="422c7-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="422c7-105">Preusmeravanje pravilo (pravilo za Prispjelu poštu ili protok pravilo za poštu, poznat i kao transportni pravilo) možete dodati najviše 10 špedicije primaoci poruke.</span><span class="sxs-lookup"><span data-stu-id="422c7-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="422c7-106">Za više informacija, pogledajte [dnevnik, Transport, i poštanskom sandučetu pravilo ograničenja](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="422c7-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="422c7-107">Poštanskom sandučetu pravila ne funkcionišu u poštansko sanduče na alternativni ugojena.</span><span class="sxs-lookup"><span data-stu-id="422c7-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="422c7-108">Za više informacija o poštanskom sandučetu alternativni ugojena, vidim [poštansko sanduče alternativni ugojena](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="422c7-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="422c7-109">Da biste rešili ove probleme, vidim [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="422c7-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="422c7-110">Ako prethodna pitanja ne odnose, pokrenite dijagnostiku izveštaj prijemnog pravilo pre nego što si eskalirati problem na lokaciji Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="422c7-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="422c7-111">Otvoriti poštansko sanduče u programu Outlook na Webu, i kliknite na dugme **Postavke** \> **Opcije** \> **Organizuj email** \> **pravila prijemnog**.</span><span class="sxs-lookup"><span data-stu-id="422c7-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>

2. <span data-ttu-id="422c7-112">U donjem delu stranice, izaberite opciju **Ako vaša pravila ne rade kliknite ovde da biste generisali dijagnostički izveštaj**.</span><span class="sxs-lookup"><span data-stu-id="422c7-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>

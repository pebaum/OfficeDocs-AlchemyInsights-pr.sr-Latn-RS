---
title: Rešavanje problema sa Office 365 napredni pretnja zaštitu (ATP)
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dbdfe2ddcc4afd4477f66ffd060ddb7093af8fd6
ms.sourcegitcommit: 601aec31e6556286fe5e0fd62827a037cbb6fe17
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/02/2019
ms.locfileid: "31031080"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="1c5b5-102">Rešavanje problema sa Office 365 ATP</span><span class="sxs-lookup"><span data-stu-id="1c5b5-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="1c5b5-103">**Najave kašnjenja sa isporukom poruka e-pošte**?</span><span class="sxs-lookup"><span data-stu-id="1c5b5-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="1c5b5-104">Pokušajte da koristite opciju dinamiku isporuka za polisa ATP sigurnom priloge.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="1c5b5-105">Ovo će izbeći kašnjenja Isporuka poruke e-pošte istovremeno štiteći primaoce iz zlonamerne datoteke.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="1c5b5-106">**Da li želite izveštaj greške ili false negative**?</span><span class="sxs-lookup"><span data-stu-id="1c5b5-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="1c5b5-107">Koristite ovaj link da podnesu svoje datoteke za analizu:[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="1c5b5-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="1c5b5-108">**Znali ste da možete da omogućite zaštitu ATP bezbedna veza za e-poštu šalju između ljudi u vašoj organizaciji**?</span><span class="sxs-lookup"><span data-stu-id="1c5b5-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="1c5b5-109">Slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="1c5b5-109">Follow these steps:</span></span>
    1. <span data-ttu-id="1c5b5-110">Idite na https://protection.office.com, i prijavite se.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="1c5b5-111">Idite na **prijetnje** > **politiku** > **Sigurna veza**.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="1c5b5-112">U okviru **politike koji se odnose na određene primaoce**, uređivanje (ili dodajte) politiku.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="1c5b5-113">Izaberite **Primeni bezbedna veza ka poruke poslane unutar organizacije**.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="1c5b5-114">Sačuvajte svoje politike, a omogućavaju oko 30 minuta da bi promene probijaju kroz tvoj datacenter.</span><span class="sxs-lookup"><span data-stu-id="1c5b5-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="1c5b5-115">Da biste dobili pomoć u vezi sa ATP, vidim [Zaštitu napredni pretnja programa Office 365](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span><span class="sxs-lookup"><span data-stu-id="1c5b5-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>
---
title: Rešavanje problema sa programom Office 365 napredna zaštita pretnje (ATP)
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: 99bc985f2d66693aca45f0833ab47c043acc1324
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766759"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="09bc2-102">Rešavanje problema sa Office 365 ATP</span><span class="sxs-lookup"><span data-stu-id="09bc2-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="09bc2-103">**Obratite pažnju na odlaganje isporučivanja e-poruka**?</span><span class="sxs-lookup"><span data-stu-id="09bc2-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="09bc2-104">Pokušajte da koristite opciju "Dinamičko isporučivanje" za ATP smernice za bezbedno priloge.</span><span class="sxs-lookup"><span data-stu-id="09bc2-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="09bc2-105">Ovo će izbeći odlaganje isporučivanja e-poruka prilikom zaštite primalaca od zlonamernih datoteka.</span><span class="sxs-lookup"><span data-stu-id="09bc2-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="09bc2-106">**Želite li da izvestite o lažnim imali greške ili lažnim negativima**?</span><span class="sxs-lookup"><span data-stu-id="09bc2-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="09bc2-107">Koristite ovu vezu da biste prosledili datoteku na analizu:[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="09bc2-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="09bc2-108">Da **li ste znali da možete da omogućite ATP zaštitu bezbednih veza za e-poštu poslatu između osoba u vašoj organizaciji**?</span><span class="sxs-lookup"><span data-stu-id="09bc2-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="09bc2-109">Sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="09bc2-109">Follow these steps:</span></span>
    1. <span data-ttu-id="09bc2-110">Idite na https://protection.office.comlokaciju i prijavite se.</span><span class="sxs-lookup"><span data-stu-id="09bc2-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="09bc2-111">Idite na**bezbedne veze** > **smernica** > za **Upravljanje pretnjama**.</span><span class="sxs-lookup"><span data-stu-id="09bc2-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="09bc2-112">U okviru **smernica koje se odnose na određene primaoce**, uredite (ili dodajte) smernice.</span><span class="sxs-lookup"><span data-stu-id="09bc2-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="09bc2-113">Izaberite stavku **Primeni bezbedne veze sa porukama poslatim u organizaciji**.</span><span class="sxs-lookup"><span data-stu-id="09bc2-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="09bc2-114">Sačuvajte smernice, a zatim dopustite oko 30 minuta da vaše promene rade putem svog Datacenter.</span><span class="sxs-lookup"><span data-stu-id="09bc2-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="09bc2-115">Da biste dobili dodatnu pomoć sa ATP-om, pogledajte [Office 365 dodatnu zaštitu pretnji](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span><span class="sxs-lookup"><span data-stu-id="09bc2-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>
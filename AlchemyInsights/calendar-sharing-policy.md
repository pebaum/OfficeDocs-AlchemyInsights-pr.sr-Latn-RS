---
title: 618 smernice za deljenje kalendara
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/26/2020
ms.locfileid: "44373013"
---
# <a name="policy-error-when-sharing-a-calendar"></a><span data-ttu-id="99a10-102">Greška u smernicama prilikom deljenja kalendara</span><span class="sxs-lookup"><span data-stu-id="99a10-102">Policy error when sharing a calendar</span></span>

1. <span data-ttu-id="99a10-103">Izvršite jednu od sledećih radnji, u skladu sa vašom situacijom:</span><span class="sxs-lookup"><span data-stu-id="99a10-103">Do one of the following, as appropriate for your situation:</span></span>
    - <span data-ttu-id="99a10-104">Povezivanje na Exchange online pomoću daljinskog upravljača PowerShell.</span><span class="sxs-lookup"><span data-stu-id="99a10-104">Connect to Exchange Online by using Remote PowerShell.</span></span> <span data-ttu-id="99a10-105">Više informacija potražite u članku [Povezivanje sa Exchange serverom putem daljinskog upravljača](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="99a10-105">For more information, see [Connect to Exchange Online using Remote PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span></span>
    - <span data-ttu-id="99a10-106">Na serveru na kome je otvorena Exchange Management Shell.</span><span class="sxs-lookup"><span data-stu-id="99a10-106">On the on-premises server, open the Exchange Management Shell.</span></span>
2. <span data-ttu-id="99a10-107">Utvrdite smernice za deljenje koje su dodeljene korisniku.</span><span class="sxs-lookup"><span data-stu-id="99a10-107">Determine the sharing policy that's assigned to the user.</span></span> <span data-ttu-id="99a10-108">Da biste to uradili, pokrenite sledeću komandu i zabeležite smernice koje ste vratili:</span><span class="sxs-lookup"><span data-stu-id="99a10-108">To do this, run the following command and note the policy returned:</span></span>

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. <span data-ttu-id="99a10-109">Ažurirajte smernice za deljenje za korisnika.</span><span class="sxs-lookup"><span data-stu-id="99a10-109">Update the sharing policy for the user.</span></span> <span data-ttu-id="99a10-110">Da biste to uradili, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="99a10-110">To do this, follow these steps:</span></span>
    - <span data-ttu-id="99a10-111">Otvorite Exchange admin Center.</span><span class="sxs-lookup"><span data-stu-id="99a10-111">Open the Exchange admin center.</span></span>
    - <span data-ttu-id="99a10-112">Izaberite stavku **organizacija**, a zatim dvaput kliknite na smernice koje su dodeljene korisniku pod **pojedinačnim deljenjem**.</span><span class="sxs-lookup"><span data-stu-id="99a10-112">Click **Organization**, and then double-click the policy that's assigned to the user under **Individual Sharing**.</span></span> <span data-ttu-id="99a10-113">Ovo je politika koja je vraćena u koraku 2.</span><span class="sxs-lookup"><span data-stu-id="99a10-113">This is the policy that was returned in step 2.</span></span>
    - <span data-ttu-id="99a10-114">Na stranici "pravilo deljenja" izaberite nivo deljenja kalendara koji želite da dozvolite u okviru **navedite koje informacije želite da delite**. Kliknite na dugme **Sačuvaj**.</span><span class="sxs-lookup"><span data-stu-id="99a10-114">On the Sharing Rule page, select the calendar sharing level that you want to allow under **Specify what information you want to share**; click **Save**.</span></span>

<span data-ttu-id="99a10-115">Za više informacija pogledajte: ["smernice ne dozvoljavaju dodeljivanje dozvola na ovom nivou jednom ili više primalaca" kada korisnik pokuša da deli kalendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span><span class="sxs-lookup"><span data-stu-id="99a10-115">For more information see: ["Policy does not allow granting permissions at this level to one or more of the recipient(s)" error when user tries to share calendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span></span>

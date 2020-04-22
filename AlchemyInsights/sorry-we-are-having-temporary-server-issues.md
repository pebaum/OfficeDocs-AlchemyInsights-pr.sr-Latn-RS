---
title: Popravljanje Office aplikacija Žao nam je, imamo poruke o privremenom serveru
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: a1ac62f3587e318d563cfea1df8db23b720358a6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764131"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="5db59-102">Popravljanje Office aplikacija "Oprostite, imamo poruku o privremenim problemima na serveru"</span><span class="sxs-lookup"><span data-stu-id="5db59-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="5db59-103">Ako dobijete ovu poruku, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="5db59-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="5db59-104">Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama.</span><span class="sxs-lookup"><span data-stu-id="5db59-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="5db59-105">Pogledajte [URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="5db59-105">See [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="5db59-106">Idite na **početni ekran** > **Run**i otkucajte **usluge. msc**.</span><span class="sxs-lookup"><span data-stu-id="5db59-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="5db59-107">Uverite se da su sve pokrenute sledeće usluge:</span><span class="sxs-lookup"><span data-stu-id="5db59-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="5db59-108">Automatsko podešavanje uređaja povezanih sa mrežom</span><span class="sxs-lookup"><span data-stu-id="5db59-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="5db59-109">Usluga liste mreža</span><span class="sxs-lookup"><span data-stu-id="5db59-109">Network List Service</span></span>
    - <span data-ttu-id="5db59-110">Svest o mrežnoj lokaciji</span><span class="sxs-lookup"><span data-stu-id="5db59-110">Network Location Awareness</span></span>
    - <span data-ttu-id="5db59-111">Windows evidencija događaja</span><span class="sxs-lookup"><span data-stu-id="5db59-111">Windows Event Log</span></span>

<span data-ttu-id="5db59-112">Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete.</span><span class="sxs-lookup"><span data-stu-id="5db59-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="5db59-113">Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:</span><span class="sxs-lookup"><span data-stu-id="5db59-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="5db59-114">**Sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="5db59-114">**sfc /scannow**</span></span>

<span data-ttu-id="5db59-115">Nakon završetka ove komande, ponovo pokrenite računar.</span><span class="sxs-lookup"><span data-stu-id="5db59-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="5db59-116">Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "Greška prilikom aktiviranja](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="5db59-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>
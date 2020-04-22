---
title: Pitanje aktivacije-ne možemo odmah da se povežemo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 56accf68f2cf41dbe6119281b74e2cb56b702789
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716186"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a><span data-ttu-id="d3415-102">Popravljanje Office aplikacija "ne možemo odmah da se povežemo" poruka</span><span class="sxs-lookup"><span data-stu-id="d3415-102">Fixing the Office apps "We are unable to connect right now" message</span></span>

<span data-ttu-id="d3415-103">Ako dobijete ovu poruku, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="d3415-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="d3415-104">Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama.</span><span class="sxs-lookup"><span data-stu-id="d3415-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="d3415-105">Pogledajte [Microsoft URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="d3415-105">See [Microsoft URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="d3415-106">Idite na **početni ekran** > **Run**i otkucajte **usluge. msc**.</span><span class="sxs-lookup"><span data-stu-id="d3415-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="d3415-107">Uverite se da su sve pokrenute sledeće usluge:</span><span class="sxs-lookup"><span data-stu-id="d3415-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="d3415-108">Automatsko podešavanje uređaja povezanih sa mrežom</span><span class="sxs-lookup"><span data-stu-id="d3415-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="d3415-109">Usluga liste mreža</span><span class="sxs-lookup"><span data-stu-id="d3415-109">Network List Service</span></span>
    - <span data-ttu-id="d3415-110">Svest o mrežnoj lokaciji</span><span class="sxs-lookup"><span data-stu-id="d3415-110">Network Location Awareness</span></span>
    - <span data-ttu-id="d3415-111">Windows evidencija događaja</span><span class="sxs-lookup"><span data-stu-id="d3415-111">Windows Event Log</span></span>

<span data-ttu-id="d3415-112">Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete.</span><span class="sxs-lookup"><span data-stu-id="d3415-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="d3415-113">Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:</span><span class="sxs-lookup"><span data-stu-id="d3415-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="d3415-114">**Sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="d3415-114">**sfc /scannow**</span></span>

<span data-ttu-id="d3415-115">Nakon završetka ove komande, ponovo pokrenite računar.</span><span class="sxs-lookup"><span data-stu-id="d3415-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="d3415-116">Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "greška kada aktivirate Office sa Microsoft 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="d3415-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Microsoft 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>
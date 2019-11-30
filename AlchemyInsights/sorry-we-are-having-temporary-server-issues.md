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
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628004"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="dd6b2-102">Popravljanje Office aplikacija "Oprostite, imamo poruku o privremenim problemima na serveru"</span><span class="sxs-lookup"><span data-stu-id="dd6b2-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="dd6b2-103">Ako dobijete ovu poruku, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="dd6b2-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="dd6b2-104">Proverite zaštitni zid, antivirusni softver i proxy postavke da biste potvrdili da ne blokiraju pristup internetu u Office aplikacijama.</span><span class="sxs-lookup"><span data-stu-id="dd6b2-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="dd6b2-105">Pogledajte [Office 365 URL adrese i OPSEGE IP adresa](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="dd6b2-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="dd6b2-106">Idite na **početni ekran** > \*\*\*\* i otkucajte **usluge. msc**.</span><span class="sxs-lookup"><span data-stu-id="dd6b2-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="dd6b2-107">Uverite se da su sve pokrenute sledeće usluge:</span><span class="sxs-lookup"><span data-stu-id="dd6b2-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="dd6b2-108">Automatsko podešavanje uređaja povezanih sa mrežom</span><span class="sxs-lookup"><span data-stu-id="dd6b2-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="dd6b2-109">Usluga liste mreža</span><span class="sxs-lookup"><span data-stu-id="dd6b2-109">Network List Service</span></span>
    - <span data-ttu-id="dd6b2-110">Svest o mrežnoj lokaciji</span><span class="sxs-lookup"><span data-stu-id="dd6b2-110">Network Location Awareness</span></span>
    - <span data-ttu-id="dd6b2-111">Windows evidencija događaja</span><span class="sxs-lookup"><span data-stu-id="dd6b2-111">Windows Event Log</span></span>

<span data-ttu-id="dd6b2-112">Ako neka od ovih usluga nije pokrenuta, pokušajte da ga pokrenete.</span><span class="sxs-lookup"><span data-stu-id="dd6b2-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="dd6b2-113">Ako imate problem sa pokretanjem usluge, pokrenite sledeću komandu tako što ćete otvoriti komandnu liniju sa punim dozvolama:</span><span class="sxs-lookup"><span data-stu-id="dd6b2-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="dd6b2-114">**Sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="dd6b2-114">**sfc /scannow**</span></span>

<span data-ttu-id="dd6b2-115">Nakon završetka ove komande, ponovo pokrenite računar.</span><span class="sxs-lookup"><span data-stu-id="dd6b2-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="dd6b2-116">Detaljnije informacije potražite u članku ["Nažalost, ne možemo da se povežemo sa vašim nalogom. Pokušajte ponovo kasnije "Greška prilikom aktiviranja sistema Office sa verzije Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="dd6b2-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>
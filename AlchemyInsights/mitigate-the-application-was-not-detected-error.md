---
title: Ublažavanje greške „Ova aplikacija nije otkrivena”
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810497"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="3bc87-102">Ublažavanje greške „Ova aplikacija nije otkrivena”</span><span class="sxs-lookup"><span data-stu-id="3bc87-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="3bc87-103">Greška pri instalaciji aplikacije, „Aplikacija nije otkrivena nakon uspešnog završetka instalacije”, koju prijavljuje Intune, može da se pojavi na svim većim OS platformama (Windows, iOS i Android).</span><span class="sxs-lookup"><span data-stu-id="3bc87-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="3bc87-104">Najčešći scenariji koji generišu ovu grešku uključuju:</span><span class="sxs-lookup"><span data-stu-id="3bc87-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="3bc87-105">Aplikacija je ažurirana izvan same Intune aplikacije (iz prodavnice nezavisnih proizvođača) posle početne primene.</span><span class="sxs-lookup"><span data-stu-id="3bc87-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="3bc87-106">Na primer, neke aplikacije kao što je Google Chrome mogu da izvrše automatsko ažuriranje.</span><span class="sxs-lookup"><span data-stu-id="3bc87-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="3bc87-107">Korisnik je deinstalirao aplikaciju nakon početne instalacije.</span><span class="sxs-lookup"><span data-stu-id="3bc87-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="3bc87-108">Da biste ublažili ovaj problem, prvo izvršite pregled pogođenih uređaja da biste odredili scenario u kom se greška događa.</span><span class="sxs-lookup"><span data-stu-id="3bc87-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="3bc87-109">Ako je aplikacija ažurirana izvan same Intune aplikacije, primena aplikacije može se podesiti tako da zanemari verziju aplikacije.</span><span class="sxs-lookup"><span data-stu-id="3bc87-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="3bc87-110">Da biste to uradili, u okviru **Konfiguracije aplikacije > Informacije o aplikaciji**, postavite **Zanemari verziju aplikacije** na **Da**.</span><span class="sxs-lookup"><span data-stu-id="3bc87-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="3bc87-111">Kada ciljate klijenta, možda bi trebalo da primenite aplikaciju kao „obaveznu” i da osigurate da je primenjena najnovija verzija.</span><span class="sxs-lookup"><span data-stu-id="3bc87-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="3bc87-112">Druga mogućnost je da na iOS platformi možete da koristite funkcionalnost **automatskog ažuriranja** koja je povezana sa programom za količinsku kupovinu kompanije Apple, koji se može konfigurisati tako da automatski ažurira aplikacije kada nove verzije postanu dostupne.</span><span class="sxs-lookup"><span data-stu-id="3bc87-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="3bc87-113">Dodatne informacije o rešavanju problema sa instalacijom aplikacija potražite u članku [Rešavanje problema prilikom instalacije aplikacije](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="3bc87-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>

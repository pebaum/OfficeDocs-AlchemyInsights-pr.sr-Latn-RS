---
title: Nije moguće prijaviti se u Teams zbog greške autologon.microsoftazuread-sso.com:443
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9001686"
- "3750"
ms.openlocfilehash: 77049153939989d1c63789adfec0b494d047a6e4
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932032"
---
# <a name="unable-to-log-into-teams-due-to-error-autologonmicrosoftazuread-sso-dot-com443"></a><span data-ttu-id="d51b3-102">Nije moguće prijaviti se u Teams zbog greške autologon.microsoftazuread-sso dot com:443</span><span class="sxs-lookup"><span data-stu-id="d51b3-102">Unable to log into Teams due to error autologon.microsoftazuread-sso dot com:443</span></span>

<span data-ttu-id="d51b3-103">Ako je omogućen automatski SSO kao potvrda identiteta za O365, možda ćete intranet sajtovima morati da dodate URL „autologon.microsoftazuread-sso.com“.</span><span class="sxs-lookup"><span data-stu-id="d51b3-103">If Seamless SSO is enabled as the O365 authentication, the URL "autologon.microsoftazuread-sso.com" may need to be added to Intranet Sites.</span></span>  <span data-ttu-id="d51b3-104">Ako je on već dodat na pouzdane sajtove i ako se automatski SSO koristi, treba ga ukloniti sa pouzdanih sajtova.</span><span class="sxs-lookup"><span data-stu-id="d51b3-104">If it has previously been added to Trusted Sites  and Seamless SSO is in use, it should be removed from Trusted Sites.</span></span>

<span data-ttu-id="d51b3-105">Pregledajte [Kontrolnu listu za rešavanje problema sa automatskim SSO prijavljivanjem](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span><span class="sxs-lookup"><span data-stu-id="d51b3-105">Please review the [Seamless SSO Troubleshooting Checklist](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span></span>

<span data-ttu-id="d51b3-106">Pratite ove korake da biste dodali URL na listu intranet sajtova:</span><span class="sxs-lookup"><span data-stu-id="d51b3-106">Follow these steps to add a URL to Intranet Sites list:</span></span>

1. <span data-ttu-id="d51b3-107">Otvorite Internet Explorer klikom na dugme **Start**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-107">Open Internet Explorer by clicking the **Start** button.</span></span> <span data-ttu-id="d51b3-108">U polje za pretragu unesite Internet Explorer, a zatim na listi rezultata kliknite na stavku **Internet Explorer**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-108">In the search box, type Internet Explorer, and then, in the list of results, click **Internet Explorer**.</span></span>
2. <span data-ttu-id="d51b3-109">Kliknite na stavku **Alatke**, a zatim na stavku **Internet opcije**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-109">Click **Tools**, and then click **Internet options**.</span></span>
3. <span data-ttu-id="d51b3-110">Izaberite karticu **Bezbednost**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-110">Click the **Security** tab.</span></span>
4. <span data-ttu-id="d51b3-111">Sada kliknite na stavku **Lokalni intranet sajtovi**, zatim na dugme **Sajtovi**, pa na dugme **Napredno**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-111">Now click on **Local Intranet sites** and then click on the **sites** button and then **Advanced** button.</span></span>
5. <span data-ttu-id="d51b3-112">Unesite URL veb sajta i kliknite na dugme **Dodaj**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-112">Enter the Website URL and click **Add**.</span></span>
6. <span data-ttu-id="d51b3-113">Kada završite, kliknite na dugme **Zatvori**.</span><span class="sxs-lookup"><span data-stu-id="d51b3-113">When you are finished, click **Close**.</span></span>

<span data-ttu-id="d51b3-114">Više informacija potražite u članku [Dokumentacija za primenu automatskog SSO prijavljivanja za O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (obuhvata proces zasnovan na smernicama za dodavanje URL adresa intranet sajtovima u 3. koraku).</span><span class="sxs-lookup"><span data-stu-id="d51b3-114">For more information, see [Documentation for deploying Seamless SSO for O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (includes Policy-based process to add a URL to Intranet Sites in Step 3).</span></span>

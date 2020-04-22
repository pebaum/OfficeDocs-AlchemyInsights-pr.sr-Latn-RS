---
title: Problemi sa prijavljivanjem u Office aplikacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2574"
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763015"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="20622-102">Problemi sa prijavljivanjem u Office aplikacije</span><span class="sxs-lookup"><span data-stu-id="20622-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="20622-103">Da biste ispravili probleme sa prijavljivanjem pomoću Office aplikacija, Isprobajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="20622-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="20622-104">Uklonite sve poslovne naloge, izuzev sa pogođenim nalogom, koristeći Windows postavke > **pristup poslu ili školi**.</span><span class="sxs-lookup"><span data-stu-id="20622-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="20622-105">[Obrišite Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) koristeći Windows upravljač akreditivima.</span><span class="sxs-lookup"><span data-stu-id="20622-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="20622-106">**Napomena:** Putanje registratora za Office 2016 su promenjene u 16,0.</span><span class="sxs-lookup"><span data-stu-id="20622-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="20622-107">(Ex: \Software\microsoft\office\16.0\zajed\identitet\)</span><span class="sxs-lookup"><span data-stu-id="20622-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="20622-108">Otvorite Office aplikaciju, odaberite stavku "**nalog** > za **datoteku** > **".** Zatim se prijavite koristeći korisnički nalog sa važećom licencom.</span><span class="sxs-lookup"><span data-stu-id="20622-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="20622-109">Detaljne informacije potražite u članku [Nalozi u sistemu Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="20622-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="20622-110">Za Mac računar pročitajte članak [Nije moguće prijaviti se u Office 2016 za Mac aplikaciju](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="20622-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="20622-111">Ako dođe do grešaka prilikom povezivanja sa Microsoft 365 pomoću programa Office 2013, omogućite modernu potvrdu identiteta za Office Client.</span><span class="sxs-lookup"><span data-stu-id="20622-111">If the errors occurs while connecting to Microsoft 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="20622-112">Za više informacija pogledajte:</span><span class="sxs-lookup"><span data-stu-id="20622-112">For more information, see:</span></span>
- [<span data-ttu-id="20622-113">Ne možete da se prijavite u Microsoft 365, Azure ili Intune</span><span class="sxs-lookup"><span data-stu-id="20622-113">You can't sign in to Microsoft 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="20622-114">Problemi sa vezom u prijavljivanju nakon ažuriranja na Office 2016 Build 16.0.7967 na Windows 10</span><span class="sxs-lookup"><span data-stu-id="20622-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="20622-115">"Nažalost, drugi nalog iz vaše organizacije je već prijavljen na ovaj računar" u sistemu Office</span><span class="sxs-lookup"><span data-stu-id="20622-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="20622-116">Rešavanje problema pri prijavljivanju sa Office modernom potvrdom identiteta kada koristite ADFS</span><span class="sxs-lookup"><span data-stu-id="20622-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)
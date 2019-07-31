---
title: Problemi prijavljivanja na Office aplikacije
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
ms.openlocfilehash: 3622a3408b25b43090e9414ae5ffcfc2760264ee
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938326"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="fa1d7-102">Problemi prijavljivanja na Office aplikacije</span><span class="sxs-lookup"><span data-stu-id="fa1d7-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="fa1d7-103">Da biste otklonili probleme za prijavljivanje sa Office aplikacija, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="fa1d7-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="fa1d7-104">Uklonite sve naloge za rad, osim pogođene naloga, koristite Windows postavke > **pristup posao ili u školu**.</span><span class="sxs-lookup"><span data-stu-id="fa1d7-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="fa1d7-105">[Jasna Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomoću Windows upravljač akreditivima.</span><span class="sxs-lookup"><span data-stu-id="fa1d7-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="fa1d7-106">**Napomena:** Putanje registratora za Office 2016 promenili 16.0.</span><span class="sxs-lookup"><span data-stu-id="fa1d7-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="fa1d7-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="fa1d7-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="fa1d7-108">Otvorite aplikaciju Office, odaberite **datoteku** > **računa** > **Odjavljivanje**. Zatim se prijavite koristeći korisnički nalog sa važećom licencom.</span><span class="sxs-lookup"><span data-stu-id="fa1d7-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="fa1d7-109">Detaljne informacije potražite u [naloge u kancelariji](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="fa1d7-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="fa1d7-110">Mac, potražite u odeljku [mogu da se prijavim za 2016 za Office za Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="fa1d7-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="fa1d7-111">Ako dođe do greške prilikom povezivanja Office 365 pomoću Office 2013 omogući modernog identiteta za Office klijenta.</span><span class="sxs-lookup"><span data-stu-id="fa1d7-111">If the errors occurs while connecting to Office 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="fa1d7-112">Za više informacija, pogledajte:</span><span class="sxs-lookup"><span data-stu-id="fa1d7-112">For more information, see:</span></span>
- [<span data-ttu-id="fa1d7-113">Ne mogu da se prijavite u Office 365, Azure ili Intune</span><span class="sxs-lookup"><span data-stu-id="fa1d7-113">You can't sign in to Office 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="fa1d7-114">Povezivanje pitanja na za prijavljivanje nakon ažuriranja za Office 2016 izgradi 16.0.7967 na Windows 10</span><span class="sxs-lookup"><span data-stu-id="fa1d7-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="fa1d7-115">„Izvini, drugi nalog iz vaše organizacije je već prijavljeni na ovaj računar” u kancelariji</span><span class="sxs-lookup"><span data-stu-id="fa1d7-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="fa1d7-116">Rešavanje problema sa prijavljivanjem moderne verifikaciju Office kada koristite ADFS</span><span class="sxs-lookup"><span data-stu-id="fa1d7-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)
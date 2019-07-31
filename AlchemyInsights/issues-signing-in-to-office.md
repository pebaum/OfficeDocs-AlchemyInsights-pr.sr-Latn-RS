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
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938327"
---
# <a name="blank-sign-in-screen-in-office-apps"></a><span data-ttu-id="40b54-102">Prazan za prijavljivanje ekran u Office aplikacije</span><span class="sxs-lookup"><span data-stu-id="40b54-102">Blank sign-in screen in Office apps</span></span>

<span data-ttu-id="40b54-103">Da biste rešili ovaj problem, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="40b54-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="40b54-104">Instalirajte najnovije ispravke za [Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="40b54-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="40b54-105">Poništavanje opcije programa Internet Explorer: U **Alatke** > **Internet opcije** > **Više opcija** > **Vraćanje početnih postavki programa Internet Explorer** (Napomena da će izgubiti prilagođene postavke) i zatim pokušajte ponovo potpisivanje kancelariju.</span><span class="sxs-lookup"><span data-stu-id="40b54-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="40b54-106">Onemogućite garde aplikacije Windows Defender (WDAG) ili bilo koji sličan zaštitni zid ili antivirusni program:</span><span class="sxs-lookup"><span data-stu-id="40b54-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="40b54-107">Na kontrolnoj tabli, idite na **programe**, a zatim odaberite **Windows Uključivanje ili isključivanje funkcija**.</span><span class="sxs-lookup"><span data-stu-id="40b54-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="40b54-108">Ako je omogućen Windows Defender aplikacije garde, pokušajte da ga onemogućite.</span><span class="sxs-lookup"><span data-stu-id="40b54-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="40b54-109">**Napomena:** Morate ponovo pokrenuti računalo.</span><span class="sxs-lookup"><span data-stu-id="40b54-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="40b54-110">Uverite se da se Microsoft.AAD.BrokerPlugin [AAD WAM dodatne komponente](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) ne blokira neke aplikacije ili program zaštitnog zida/anti-virus.</span><span class="sxs-lookup"><span data-stu-id="40b54-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="40b54-111">[Jasna Office akreditive](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomoću Windows upravljač akreditivima.</span><span class="sxs-lookup"><span data-stu-id="40b54-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="40b54-112">**Napomena:** Putanje registratora za Office 2016 promenili 16.0.</span><span class="sxs-lookup"><span data-stu-id="40b54-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="40b54-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="40b54-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="40b54-114">Više informacija potražite u odeljku [za povezivanje pitanja u za prijavljivanje nakon ažuriranja za Office 2016 build 16.0.7967 na Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="40b54-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>
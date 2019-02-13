---
title: Instaliranje sistema office na Terminal serveru - bez dozvole
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 971edd9c064b448446ba16361e99df4a2291c14f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29918994"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="c103b-102">Instaliranje sistema Office na Terminal servera</span><span class="sxs-lookup"><span data-stu-id="c103b-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="c103b-103">Za primenu Office 365 ProPlus na Windows serveru koristeći usluge udaljene radne površine (RDS), nekadašnja po imenu Terminal Services:</span><span class="sxs-lookup"><span data-stu-id="c103b-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="c103b-p101">Morate imati plan za Office 365 koji uključuje Office 365 ProPlus, kao što je Office 365 Enterprise E3 ili Enterprise E5. Ne uključuj Office 365 ProPlus Office 365 Business i Office 365 poslovne Premium planove.</span><span class="sxs-lookup"><span data-stu-id="c103b-p101">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5. The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
    
- <span data-ttu-id="c103b-106">Potrebno je da omogućite [aktivacija deljenih računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="c103b-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>
    
<span data-ttu-id="c103b-107">Ako želite da instalirate Office 365 ProPlus na RDS iz Office 365 portal, \*\* *koji koristi podrazumevane postavke instalacije* \*\*, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="c103b-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span> 
  
1. <span data-ttu-id="c103b-p102">Pogledajte kakav plan Office 365, imate. [Saznajte kako](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span><span class="sxs-lookup"><span data-stu-id="c103b-p102">Check what Office 365 plan you have. [Learn how](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span></span>
    
2. <span data-ttu-id="c103b-p103">Ako je potrebno, prebaci se na drugu Office 365 planiraju. [Saznajte kako](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span><span class="sxs-lookup"><span data-stu-id="c103b-p103">If necessary, switch to a different Office 365 plan. [Learn how](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span></span>
    
3. <span data-ttu-id="c103b-p104">Ako Office je već instaliran na serveru RDS pomoću neke druge planove za Office 365, deinstalirajte ga. Na primer, tako što ćete posetiti Kontrolna tabla \> Deinstaliranje programa. Deinstalirajte koristeći [Microsoft podršci i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) Ako pokrećete u pitanjima.</span><span class="sxs-lookup"><span data-stu-id="c103b-p104">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it. For example, by going to Control Panel \> Uninstall a program. Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span> 
    
4. <span data-ttu-id="c103b-115">Na serveru RDS, prijavite se Office 365 portal sa administratorskim nalogom i [Instalirajte Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="c103b-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
    
5. <span data-ttu-id="c103b-116">Nakon instaliranja Office, \*\* *ne otvori ili se prijavite u* \*\* da sve Office aplikacije.</span><span class="sxs-lookup"><span data-stu-id="c103b-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span> 
    
6. <span data-ttu-id="c103b-117">Na serveru RDS, Omogućavanje aktivacije deljeni računar uređivanjem registra tako što ćete pratiti ove korake:</span><span class="sxs-lookup"><span data-stu-id="c103b-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
    
1. <span data-ttu-id="c103b-p105">Kliknite desnim tasterom miša na Windows dugme u donjem levom uglu ekrana i izaberite stavku Pokreni. U polju otvori otkucajte **regedit**, a zatim izaberite OK.</span><span class="sxs-lookup"><span data-stu-id="c103b-p105">Right-click the Windows button in the lower left-hand corner of your screen and select Run. In the Open box, type **regedit**, and then select OK.</span></span> 
    
2. <span data-ttu-id="c103b-120">Izaberite opciju da kada se od vas zatraži da dozvolite Registry Editor da biste promenili vaš uređaj.</span><span class="sxs-lookup"><span data-stu-id="c103b-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>
    
3. <span data-ttu-id="c103b-121">U programu Registry Editor, dodajte vrednost niske od **SharedComputerLicensing** sa postavkom 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="c103b-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span> 
    
7. <span data-ttu-id="c103b-122">Na serveru RDS, \*\* *prijaviti se kao krajnji korisnik* \*\* i [Proverite da li deljeni računar aktivacija omogućena za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="c103b-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
    
<span data-ttu-id="c103b-123">Za više detalja o preduslovi, uputstva za instalaciju i Vodič kroz prilagođene instalacije pomoću alatke za primenu za Office, pogledajte [Korištenje Office 365 ProPlus pomoću usluge udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="c103b-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="c103b-124">Da biste popravili greške vezane za aktivaciju deljeni računar, pogledajte [Rešavanje problema sa aktivacija deljenih računara za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="c103b-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  


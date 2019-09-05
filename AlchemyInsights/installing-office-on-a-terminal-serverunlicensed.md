---
title: Instaliranje sistema Office na Terminal serveru-nelicenciran
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 53071224a7c33532d864cd70b84bf0e3cc6a992f
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36735403"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="adc16-102">Instaliranje sistema Office na Terminal serveru</span><span class="sxs-lookup"><span data-stu-id="adc16-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="adc16-103">Za primenu sistema Office 365 ProPlus na Windows serveru pomoću usluga udaljene radne površine (RDS), prethodno imenovanih usluga terminala:</span><span class="sxs-lookup"><span data-stu-id="adc16-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="adc16-104">Morate imati Office 365 plan koji uključuje Office 365 ProPlus, kao što je Office 365 Enterprise E3 ili Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="adc16-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="adc16-105">Office 365 Business i Office 365 Business Premium planovi ne uključuju Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="adc16-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="adc16-106">Potrebno je da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="adc16-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="adc16-107">Ako želite da instalirate Office 365 ProPlus na RDS iz Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="adc16-107">If you want to install Office 365 ProPlus on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, follow these steps:</span></span>
  
1. <span data-ttu-id="adc16-108">Proverite koji Office 365 plan imate.</span><span class="sxs-lookup"><span data-stu-id="adc16-108">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="adc16-109">Saznajte kako</span><span class="sxs-lookup"><span data-stu-id="adc16-109">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="adc16-110">Prebacite se na drugi Office 365 plan ako je potrebno.</span><span class="sxs-lookup"><span data-stu-id="adc16-110">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="adc16-111">Saznajte kako</span><span class="sxs-lookup"><span data-stu-id="adc16-111">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="adc16-112">Ako je Office već instaliran na RDS serveru koristeći bilo koji drugi Office 365 plan, deinstalirajte ga.</span><span class="sxs-lookup"><span data-stu-id="adc16-112">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="adc16-113">Na primer, tako što ćete otići na \> kontrolnu tablu deinstalirajte program.</span><span class="sxs-lookup"><span data-stu-id="adc16-113">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="adc16-114">Deinstalirajte koristeći [Microsoft pomoć i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) ako se radi o problemima.</span><span class="sxs-lookup"><span data-stu-id="adc16-114">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="adc16-115">Na RDS serveru, prijavite se u Microsoft 365 admin Center sa administratorskim nalogom i [Instalirajte Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="adc16-115">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="adc16-116">Nakon instalacije sistema Office, ***Nemojte da otvarate niti*** da se prijavljujete u bilo koju Office aplikaciju.</span><span class="sxs-lookup"><span data-stu-id="adc16-116">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="adc16-117">Na RDS serveru omogućite deljenu aktivaciju računara uređivanjem registratora tako što ćete slediti ove korake:</span><span class="sxs-lookup"><span data-stu-id="adc16-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="adc16-118">Kliknite desnim tasterom miša na dugme Windows u donjem levom uglu ekrana i izaberite stavku Pokreni.</span><span class="sxs-lookup"><span data-stu-id="adc16-118">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="adc16-119">U polju otvori otkucajte **Regedit**, a zatim izaberite "u redu".</span><span class="sxs-lookup"><span data-stu-id="adc16-119">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="adc16-120">Kliknite na dugme "da" kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.</span><span class="sxs-lookup"><span data-stu-id="adc16-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="adc16-121">U programu Registry Editor Dodajte vrednost niske za **Sharedkompjuterlicenciranje** sa postavkom 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\kliktorun\konfiguration.</span><span class="sxs-lookup"><span data-stu-id="adc16-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="adc16-122">Na RDS serveru prijavite se ***kao krajnji korisnik*** i [Proverite da li je aktivacija deljenog računara omogućena za Office 365 proplus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="adc16-122">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="adc16-123">Za više detalja o preduslovi, uputstva za podešavanje i uputstva o prilagođenim instalacijama pomoću alatke za primenu sistema Office, pogledajte odeljak [Primena sistema office 365 ProPlus pomoću usluga udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="adc16-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="adc16-124">Da biste ispravili greške u vezi sa aktivacijom deljenog računara, pogledajte odeljak [Rešavanje problema sa aktivacijom deljenog računara za Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="adc16-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  
---
title: Instaliranje sistema Office na Terminal serveru-nelicenciran
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 6e952513679c9ac66f8de2b43d6d243cf17ff789
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010628"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="458df-102">Instaliranje sistema Office na Terminal serveru</span><span class="sxs-lookup"><span data-stu-id="458df-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="458df-103">Za primenu aplikacija Microsoft 365 za Enterprise na Windows serveru pomoću usluga udaljene radne površine (RDS), prethodno imenovanih usluga terminala:</span><span class="sxs-lookup"><span data-stu-id="458df-103">For deploying Microsoft 365 Apps for enterprise on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="458df-104">Morate da imate Microsoft 365 pretplatu koja uključuje Microsoft 365 aplikacije za Enterprise, kao što je Office 365 Enterprise E3 ili Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="458df-104">You must have a Microsoft 365 subscription that includes Microsoft 365 Apps for enterprise, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="458df-105">Microsoft 365 aplikacije za poslovne i Microsoft 365 aplikacije za poslovne Premium planove ne uključuju Microsoft 365 aplikacije za Enterprise.</span><span class="sxs-lookup"><span data-stu-id="458df-105">The Microsoft 365 Apps for business and Microsoft 365 Apps for business Premium plans do not include Microsoft 365 Apps for enterprise.</span></span>

- <span data-ttu-id="458df-106">Potrebno je da omogućite [deljenu aktivaciju računara](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="458df-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span></span>

<span data-ttu-id="458df-107">Ako želite da instalirate Microsoft 365 aplikacije za Enterprise na RDS od Microsoft 365 admin Center, ***koji koristi podrazumevane postavke instalacije***, slijedite ove korake.</span><span class="sxs-lookup"><span data-stu-id="458df-107">If you want to install Microsoft 365 Apps for enterprise on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="458df-108">Takođe možete preuzeti i pokrenuti [Microsoft pomoćnik za podršku i oporavak](https://aka.ms/SaRA_OfficeSCA_M365Portal) da biste instalirali Microsoft 365 aplikacije za Enterprise u režimu aktiviranja deljenog računara.</span><span class="sxs-lookup"><span data-stu-id="458df-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Microsoft 365 Apps for enterprise in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="458df-109">Proverite koju Microsoft 365 pretplatu imate.</span><span class="sxs-lookup"><span data-stu-id="458df-109">Check what Microsoft 365 subscription you have.</span></span> [<span data-ttu-id="458df-110">Saznajte kako</span><span class="sxs-lookup"><span data-stu-id="458df-110">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="458df-111">Ako je potrebno, prebacite se na drugu Microsoft 365 pretplatu.</span><span class="sxs-lookup"><span data-stu-id="458df-111">If necessary, switch to a different Microsoft 365 subscription.</span></span> [<span data-ttu-id="458df-112">Saznajte kako</span><span class="sxs-lookup"><span data-stu-id="458df-112">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="458df-113">Ako je Office već instaliran na RDS serveru koristeći druge Microsoft 365 pretplate, deinstalirajte je.</span><span class="sxs-lookup"><span data-stu-id="458df-113">If Office is already installed on the RDS server using any other Microsoft 365 subscriptions, uninstall it.</span></span> <span data-ttu-id="458df-114">Na primer, tako što ćete otići na \> kontrolnu tablu deinstalirajte program.</span><span class="sxs-lookup"><span data-stu-id="458df-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="458df-115">Deinstalirajte koristeći [Microsoft pomoć i pomoćnik za oporavak](https://aka.ms/SARA-OfficeUninstall-Alchemy) ako se radi o problemima.</span><span class="sxs-lookup"><span data-stu-id="458df-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="458df-116">Na RDS serveru, prijavite se u Microsoft 365 admin Center sa administratorskim nalogom i [instalirajte Microsoft 365 aplikacije za Enterprise](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="458df-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Microsoft 365 Apps for enterprise](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="458df-117">Nakon instalacije sistema Office, ***Nemojte da otvarate niti*** da se prijavljujete u bilo koju Office aplikaciju.</span><span class="sxs-lookup"><span data-stu-id="458df-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="458df-118">Na RDS serveru omogućite deljenu aktivaciju računara uređivanjem registratora tako što ćete slediti ove korake:</span><span class="sxs-lookup"><span data-stu-id="458df-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="458df-119">Kliknite desnim tasterom miša na dugme Windows u donjem levom uglu ekrana i izaberite stavku Pokreni.</span><span class="sxs-lookup"><span data-stu-id="458df-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="458df-120">U polju otvori otkucajte **Regedit**, a zatim izaberite "u redu".</span><span class="sxs-lookup"><span data-stu-id="458df-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="458df-121">Kliknite na dugme "da" kada se od vas zatraži da dozvolite Registry Editoru da promeni vaš uređaj.</span><span class="sxs-lookup"><span data-stu-id="458df-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="458df-122">U programu Registry Editor Dodajte vrednost niske za **Sharedkompjuterlicenciranje** sa postavkom 1 u HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\kliktorun\konfiguration.</span><span class="sxs-lookup"><span data-stu-id="458df-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="458df-123">Na RDS serveru prijavite se ***kao krajnji korisnik*** i [Proverite da li je aktivacija deljenog računara omogućena za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span><span class="sxs-lookup"><span data-stu-id="458df-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span></span>

<span data-ttu-id="458df-124">Za više detalja o preduslovi, uputstva za podešavanje i uputstva o prilagođenim instalacijama pomoću alatke za primenu sistema Office, pogledajte odeljak [Primena Microsoft 365 aplikacija za Enterprise pomoću usluga udaljene radne površine](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="458df-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Microsoft 365 Apps for enterprise by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span></span>
  
<span data-ttu-id="458df-125">Da biste ispravili greške u vezi sa aktivacijom deljenog računara, pogledajte odeljak [Rešavanje problema sa aktivacijom deljenog računara za Microsoft 365 aplikacije za Enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="458df-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span></span>
  
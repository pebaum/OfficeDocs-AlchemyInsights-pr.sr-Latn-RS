---
title: Rešavanje problema sa sinhronizacijom lozinke
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: edd4f68466296f72c2dc0bafda45e6749d62d942
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732524"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="48921-102">Rešavanje problema sa sinhronizacijom lozinke</span><span class="sxs-lookup"><span data-stu-id="48921-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="48921-103">Da biste rešili probleme na koje nema sinhronizovanih lozinki sa 1.1.614.0 ili novijim verzijama za Connect Azure:</span><span class="sxs-lookup"><span data-stu-id="48921-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="48921-104">Otvorite novu sesiju Windows PowerShell na serveru za povezivanje Azure oglasa sa opcijom " **Pokreni kao administrator** ".</span><span class="sxs-lookup"><span data-stu-id="48921-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span>

2. <span data-ttu-id="48921-105">Pokretanje **Set-izvršne smernice RemoteSigned** ili **Set-izvršne smernice neograničeno**.</span><span class="sxs-lookup"><span data-stu-id="48921-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span>

3. <span data-ttu-id="48921-106">Pokrenite čarobnjak za povezivanje "Azure AD".</span><span class="sxs-lookup"><span data-stu-id="48921-106">Start the Azure AD Connect wizard.</span></span>

4. <span data-ttu-id="48921-107">Krećite se do stranice sa **dodatnim zadacima** , izaberite **Rešavanje problema**, a zatim kliknite na dugme **dalje**.</span><span class="sxs-lookup"><span data-stu-id="48921-107">Navigate to the **Additional Tasks** page, select **Troubleshoot**, and click **Next**.</span></span>

5. <span data-ttu-id="48921-108">Na stranici rešavanje problema kliknite na dugme **Pokreni da biste pokrenuli meni rešavanje problema** u programu PowerShell.</span><span class="sxs-lookup"><span data-stu-id="48921-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span>

6. <span data-ttu-id="48921-109">U glavnom meniju izaberite stavku **Rešavanje problema pri sinhronizaciji lozinke**.</span><span class="sxs-lookup"><span data-stu-id="48921-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span>

7. <span data-ttu-id="48921-110">U podmeniju izaberite stavku " **Sinhronizacija lozinke" ne radi uopšte**.</span><span class="sxs-lookup"><span data-stu-id="48921-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span>

<span data-ttu-id="48921-111">**Razumevanje rezultata zadatka "Rešavanje problema"**</span><span class="sxs-lookup"><span data-stu-id="48921-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="48921-112">Zadatak rešavanja problema izvršava sledeće čekove:</span><span class="sxs-lookup"><span data-stu-id="48921-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="48921-113">Proverava valjanost funkcije za sinhronizaciju lozinke za vaš Azure oglas.</span><span class="sxs-lookup"><span data-stu-id="48921-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>

- <span data-ttu-id="48921-114">Proverava valjanost servera za povezivanje Azure oglasa nije u režimu za postavljanje.</span><span class="sxs-lookup"><span data-stu-id="48921-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>

- <span data-ttu-id="48921-115">Za svaku postojeću liniju spajanja aktivnog direktorijuma (koja odgovara postojećoj šumi aktivnog direktorijuma):</span><span class="sxs-lookup"><span data-stu-id="48921-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>

- 
  - <span data-ttu-id="48921-116">Proverava valjanost funkcije za sinhronizaciju lozinke.</span><span class="sxs-lookup"><span data-stu-id="48921-116">Validates that the password synchronization feature is enabled.</span></span>

  - <span data-ttu-id="48921-117">Pretražuje događaje u sinhronizaciji lozinke u evidencijama događaja Windows aplikacije.</span><span class="sxs-lookup"><span data-stu-id="48921-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>

  - <span data-ttu-id="48921-118">Za svaki domen aktivnog direktorijuma u okviru konektora aktivnog direktorijuma na prostoru:</span><span class="sxs-lookup"><span data-stu-id="48921-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>

  - <span data-ttu-id="48921-119">Proverava valjanost domena koji se može pristupiti sa servera za povezivanje Azure oglasa.</span><span class="sxs-lookup"><span data-stu-id="48921-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>

  - <span data-ttu-id="48921-120">Proverava valjanost naloga za usluge domena aktivnog direktorijuma (AD DS) koje koristi linija spajanja aktivnog direktorijuma na prostoru ima ispravno korisničko ime, lozinku i dozvole potrebne za sinhronizaciju lozinke.</span><span class="sxs-lookup"><span data-stu-id="48921-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>

<span data-ttu-id="48921-121">Više pomoći za rešavanje problema sa lozinkom sinhronizacija potražite [u članku rešavanje problema sa sinhronizacijom lozinke pomoću programa AZURE AD Connect Sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="48921-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  
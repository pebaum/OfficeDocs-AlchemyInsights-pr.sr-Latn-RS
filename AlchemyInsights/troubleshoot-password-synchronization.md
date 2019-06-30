---
title: Rešavanje problema sa lozinkom sinhronizacije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 165e0ff4b2136b727450946d2c47756ebee7d393
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353119"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="43a7f-102">Rešavanje problema sa lozinkom sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="43a7f-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="43a7f-103">Da biste rešili probleme gde nema lozinke koje su sinhronizovane sa Azure AD povezivanje verzija 1.1.614.0 ili novija:</span><span class="sxs-lookup"><span data-stu-id="43a7f-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="43a7f-104">Otvorite novu sesiju Windows PowerShell na vašem serveru Azure AD povezivanje koristeći opciju " **Pokreni kao Administrator** ".</span><span class="sxs-lookup"><span data-stu-id="43a7f-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span>

2. <span data-ttu-id="43a7f-105">Pokretanje **Set-ExecutionPolicy RemoteSigned** ili **Set-ExecutionPolicy bez nadzora**.</span><span class="sxs-lookup"><span data-stu-id="43a7f-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span>

3. <span data-ttu-id="43a7f-106">Pokrenite čarobnjak za povezivanje Azure AD.</span><span class="sxs-lookup"><span data-stu-id="43a7f-106">Start the Azure AD Connect wizard.</span></span>

4. <span data-ttu-id="43a7f-107">Pronađite **Dodatne zadatke** stranicu, izaberite **rešavanje**i kliknite na dugme **dalje**.</span><span class="sxs-lookup"><span data-stu-id="43a7f-107">Navigate to the **Additional Tasks** page, select **Troubleshoot**, and click **Next**.</span></span>

5. <span data-ttu-id="43a7f-108">Na stranici za rešavanje problema, u meniju **start rešavanja problema, lansiranje** u PowerShell.</span><span class="sxs-lookup"><span data-stu-id="43a7f-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span>

6. <span data-ttu-id="43a7f-109">U glavnog menija, izaberite opciju **Sinhronizacije rešavanje problema sa lozinkom**.</span><span class="sxs-lookup"><span data-stu-id="43a7f-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span>

7. <span data-ttu-id="43a7f-110">U podmeniju, izaberite **lozinku sinhronizacije ne radi na svim**.</span><span class="sxs-lookup"><span data-stu-id="43a7f-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span>

<span data-ttu-id="43a7f-111">**Razumeju rezultate za rešavanje problema zadatka**</span><span class="sxs-lookup"><span data-stu-id="43a7f-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="43a7f-112">Rešavanje problema zadatka obavlja sledeće čekove:</span><span class="sxs-lookup"><span data-stu-id="43a7f-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="43a7f-113">Proverava da li funkcije sinhronizacije lozinku omogućen za Azure AD podstanara.</span><span class="sxs-lookup"><span data-stu-id="43a7f-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>

- <span data-ttu-id="43a7f-114">Valjanost Azure AD povezivanje server nije u organizovanje režimu.</span><span class="sxs-lookup"><span data-stu-id="43a7f-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>

- <span data-ttu-id="43a7f-115">Za svaku postojeću lokalne Active Directory connector (koji odgovara na postojeće Active Directory šume):</span><span class="sxs-lookup"><span data-stu-id="43a7f-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>

- 
  - <span data-ttu-id="43a7f-116">Proverava da li je omogućena funkcija sinhronizacije lozinku.</span><span class="sxs-lookup"><span data-stu-id="43a7f-116">Validates that the password synchronization feature is enabled.</span></span>

  - <span data-ttu-id="43a7f-117">Traži lozinku sinhronizacije otkucaje srca događaja u evidencijama događaja Windows aplikacije.</span><span class="sxs-lookup"><span data-stu-id="43a7f-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>

  - <span data-ttu-id="43a7f-118">Za svaku Active Directory domena ispod linije spajanja aktivnog direktorijuma na više lokacija:</span><span class="sxs-lookup"><span data-stu-id="43a7f-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>

  - <span data-ttu-id="43a7f-119">Valjanost da domen je dostupan sa Azure AD povezivanje servera.</span><span class="sxs-lookup"><span data-stu-id="43a7f-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>

  - <span data-ttu-id="43a7f-120">Valjanost da usluga domena aktivnog direktorijuma (AD DS) nalozi koje koriste lokalne Active Directory konektor ima ispravno korisničko ime, lozinku i dozvole potrebne za sinhronizaciju lozinku.</span><span class="sxs-lookup"><span data-stu-id="43a7f-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>

<span data-ttu-id="43a7f-121">Za dodatnu pomoć u rešavanju problema sa lozinkom pri sinhronizaciji, vidim [rešavanje lozinku sinhronizacije sa Azure AD povezivanje sinhronizacije](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="43a7f-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  
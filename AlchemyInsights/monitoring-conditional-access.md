---
title: Nadgledanje Conditional Access
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 374814f4eabd61433a15876ebf7f351819933c21
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36538782"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="bbb77-102">Nadgledanje uslovnog pristupa za Exchange</span><span class="sxs-lookup"><span data-stu-id="bbb77-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="bbb77-103">Korisnici na meti sa uslovnog pristupa će dobiti email sa obavijesti ako ne ispunjavaju zahteve za pristup vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="bbb77-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="bbb77-104">Da biste riješili, preporučujemo jedan ili više od sledećih rešenja:</span><span class="sxs-lookup"><span data-stu-id="bbb77-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="bbb77-105">Ako uređaj pretpostavlja se da budete upisani, savetujem da korisnik u kompaniji Portal aplikaciju i proverite da li je prikazan u kompaniji Portal.</span><span class="sxs-lookup"><span data-stu-id="bbb77-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="bbb77-106">Ako ne, korisnik treba da upiše uređaj.</span><span class="sxs-lookup"><span data-stu-id="bbb77-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="bbb77-107">U azurno portal idite do **Intune \> uređaj usklađenosti**.</span><span class="sxs-lookup"><span data-stu-id="bbb77-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="bbb77-108">Izaberite **uređaj usklađenosti**ispod **monitora** .</span><span class="sxs-lookup"><span data-stu-id="bbb77-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="bbb77-109">Prikazivanje izveštaja usklađenosti uređaj da biste potvrdili da je korisnikov uređaj označen kao usaglašeni.</span><span class="sxs-lookup"><span data-stu-id="bbb77-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="bbb77-110">U azurno portal idite do **Intune \> uređaj usklađenosti**.</span><span class="sxs-lookup"><span data-stu-id="bbb77-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="bbb77-111">U okviru **Upravljanje**, kliknite na **politiku**.</span><span class="sxs-lookup"><span data-stu-id="bbb77-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="bbb77-112">Na listi usklađenosti politike, provjerite profil je dodeljena vašem korisničkom uređaju.</span><span class="sxs-lookup"><span data-stu-id="bbb77-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="bbb77-113">Ako nema profila je dodeljeno, onda Intune ne moći da potvrdi status usklađenosti uređaja.</span><span class="sxs-lookup"><span data-stu-id="bbb77-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="bbb77-114">Uredi zadatak uslovnog pristupa korisnika.</span><span class="sxs-lookup"><span data-stu-id="bbb77-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="bbb77-115">U azurno portal idite do **Intune \> Conditional access \> politiku**</span><span class="sxs-lookup"><span data-stu-id="bbb77-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="bbb77-116">Sa liste izaberite smernice</span><span class="sxs-lookup"><span data-stu-id="bbb77-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="bbb77-117">Kliknite na dugme **korisnici i grupe**</span><span class="sxs-lookup"><span data-stu-id="bbb77-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="bbb77-118">Da biste ciljali određene politiku na nekoga, ih dodati listi **uključenih** .</span><span class="sxs-lookup"><span data-stu-id="bbb77-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="bbb77-119">Da biste bili sigurni da osoba je izostavljena iz polise, dodati ih na listu **izuzmete** .</span><span class="sxs-lookup"><span data-stu-id="bbb77-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="bbb77-120">Opširnije: [Kako da Monitor Conditional Access uređaji](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="bbb77-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  


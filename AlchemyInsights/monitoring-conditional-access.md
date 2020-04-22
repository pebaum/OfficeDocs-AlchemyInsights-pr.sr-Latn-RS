---
title: Nadgledanje uslovnog pristupa
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 8b76d58791408037b5704b421d7afa166e3ea0be
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713732"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="2318f-102">Praćenje uslovnog pristupa za Exchange</span><span class="sxs-lookup"><span data-stu-id="2318f-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="2318f-103">Korisnici usmereni sa uslovnim pristupom dobiće obaveštenje e-poštom ako ne zadovoljavaju zahteve za pristup vašoj organizaciji.</span><span class="sxs-lookup"><span data-stu-id="2318f-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="2318f-104">Da biste rešili, preporučujemo neka od sledećih rešenja:</span><span class="sxs-lookup"><span data-stu-id="2318f-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="2318f-105">Ako se pretpostavlja da se uređaj upisuje, posavetuj korisnika da ode u aplikaciju "portal Company" i proverite da li se pojavljuje na portalu kompanije.</span><span class="sxs-lookup"><span data-stu-id="2318f-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="2318f-106">Ako to ne uradite, korisnik bi trebalo da upiše uređaj.</span><span class="sxs-lookup"><span data-stu-id="2318f-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="2318f-107">Na "Azure" portalu idite **do \> Intune usklađenosti uređaja**.</span><span class="sxs-lookup"><span data-stu-id="2318f-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="2318f-108">U okviru **nadgledanje** izaberite stavku **usaglašenost uređaja**.</span><span class="sxs-lookup"><span data-stu-id="2318f-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="2318f-109">Prikažite izveštaj o usaglašenosti uređaja da biste proverili da li je korisnički uređaj označen kao usaglašen.</span><span class="sxs-lookup"><span data-stu-id="2318f-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="2318f-110">Na "Azure" portalu idite **do \> Intune usklađenosti uređaja**.</span><span class="sxs-lookup"><span data-stu-id="2318f-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="2318f-111">U odeljku **Upravljanje**kliknite na dugme **smernice**.</span><span class="sxs-lookup"><span data-stu-id="2318f-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="2318f-112">Na listi smernica za usaglašenost proverite da li je profil dodeljen uređaju vašeg korisnika.</span><span class="sxs-lookup"><span data-stu-id="2318f-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="2318f-113">Ako nijedan profil nije dodeljen, Intune neće moći da potvrdi status usaglašenosti uređaja.</span><span class="sxs-lookup"><span data-stu-id="2318f-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="2318f-114">Uredite dodeljivanje uslovnog pristupa korisnika.</span><span class="sxs-lookup"><span data-stu-id="2318f-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="2318f-115">Na Azure portalu idite na **Intune \> smernice za uslovnu \> pristup**</span><span class="sxs-lookup"><span data-stu-id="2318f-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="2318f-116">Izaberite smernice sa liste</span><span class="sxs-lookup"><span data-stu-id="2318f-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="2318f-117">Izaberite stavku **korisnici i grupe**</span><span class="sxs-lookup"><span data-stu-id="2318f-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="2318f-118">Da biste određenim smernicama ciljali određene smernice, dodajte ih u listu " **Uključi** ".</span><span class="sxs-lookup"><span data-stu-id="2318f-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="2318f-119">Da biste se uverili da je osoba izostavljena iz smernice, dodajte ih na listu **isključenih** .</span><span class="sxs-lookup"><span data-stu-id="2318f-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="2318f-120">Opširnije: [kako nadgledati uređaje za uslovnu pristup](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="2318f-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  


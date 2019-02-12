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
ms.openlocfilehash: 756c5e98ed3e9cedd0152b5747ea6bf1ed31778e
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29902374"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="55fbc-102">Nadgledanje Conditional Access</span><span class="sxs-lookup"><span data-stu-id="55fbc-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="55fbc-p101">Korisnici na meti sa uslovnog pristupa će dobiti email sa obavijesti ako ne ispunjavaju zahteve za pristup vašoj organizaciji. Da biste riješili, preporučujemo jedan ili više od sledećih rešenja:</span><span class="sxs-lookup"><span data-stu-id="55fbc-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="55fbc-p102">Ako uređaj pretpostavlja se da budete upisani, savetujem da korisnik u kompaniji Portal aplikaciju i proverite da li je prikazan u kompaniji Portal. Ako ne, korisnik treba da upiše uređaj.</span><span class="sxs-lookup"><span data-stu-id="55fbc-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="55fbc-p103">U azurno portal idite do **Intune \> uređaj usklađenosti**. Izaberite **uređaj usklađenosti**ispod **monitora** . Prikazivanje izveštaja usklađenosti uređaj da biste potvrdili da je korisnikov uređaj označen kao usaglašeni.</span><span class="sxs-lookup"><span data-stu-id="55fbc-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="55fbc-p104">U azurno portal idite do **Intune \> uređaj usklađenosti**. U okviru **Upravljanje**, kliknite na **politiku**. Na listi usklađenosti politike, provjerite profil je dodeljena vašem korisničkom uređaju. Ako nema profila je dodeljeno, onda Intune ne moći da potvrdi status usklađenosti uređaja.</span><span class="sxs-lookup"><span data-stu-id="55fbc-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="55fbc-114">Uredi zadatak uslovnog pristupa korisnika.</span><span class="sxs-lookup"><span data-stu-id="55fbc-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="55fbc-115">U azurno portal idite do **Intune \> Conditional access \> politiku**</span><span class="sxs-lookup"><span data-stu-id="55fbc-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="55fbc-116">Sa liste izaberite smernice</span><span class="sxs-lookup"><span data-stu-id="55fbc-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="55fbc-117">Kliknite na dugme **korisnici i grupe**</span><span class="sxs-lookup"><span data-stu-id="55fbc-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="55fbc-p105">Da biste ciljali određene politiku na nekoga, ih dodati listi **uključenih** . Da biste bili sigurni da osoba je izostavljena iz polise, dodati ih na listu **izuzmete** .</span><span class="sxs-lookup"><span data-stu-id="55fbc-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="55fbc-120">Opširnije: [Kako da Monitor Conditional Access uređaji](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="55fbc-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  


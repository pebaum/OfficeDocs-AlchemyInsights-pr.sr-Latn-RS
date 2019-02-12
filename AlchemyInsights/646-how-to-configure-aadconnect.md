---
title: 646 kako konfigurirati AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: dd6d6986b23c8adcc98fe713bacf32fb5bf8b4b6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915601"
---
# <a name="configure-sync-features"></a><span data-ttu-id="b1aef-102">Podesite opcije sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="b1aef-102">Configure sync features</span></span>

<span data-ttu-id="b1aef-p101">Azurno AD povezivanje sadrži nekoliko funkcija koje su podrazumevano, ili to možete omogućiti kasnije. Neke funkcije zahtevaju dodatne konfiguracije u određenim sredinama.</span><span class="sxs-lookup"><span data-stu-id="b1aef-p101">Azure AD Connect includes several features that are enabled by default, or that you can enable later. Some features require additional configuration in specific environments.</span></span>
  
- <span data-ttu-id="b1aef-p102">[Filtriranje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) ograničenja objektima se sinhronizuju sa azurno AD. Podrazumevane, svi korisnici, kontakti, grupe i Windows 10 računara nalozi se sinhronizuju. Možete uključiti ili isključiti objekte na osnovu domeni, organizacione jedinice ili druge atribute.</span><span class="sxs-lookup"><span data-stu-id="b1aef-p102">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD. By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized. You can include or exclude objects based on domains, OUs, or other attributes.</span></span> 
    
- <span data-ttu-id="b1aef-p103">[Lozinka hash sačekate](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sinhronizuje lozinku hash iz lokalne aktivni direktorijum se azurno oglasa. Ovo omogućava upravljanje lozinkama na jednoj lokaciji, ali koristi istu lozinku u oba na više lokacija i zamagle okruženjima. Pošto je Active Directory autoritativnih izvora, možete da koristite polisa lozinku.</span><span class="sxs-lookup"><span data-stu-id="b1aef-p103">[Password hash syncronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD. This allows password management in one location, but use of the same password in both on-premises and cloud environments. Because Active Directory is the authoritative source, you can use your own password policies.</span></span> 
    
- <span data-ttu-id="b1aef-111">[Samouslužno gesla (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) omogućava korisnicima da poništi svoje lozinke u oblaku prilikom i dalje primene svoje lokalne smernice za lozinke.</span><span class="sxs-lookup"><span data-stu-id="b1aef-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span> 
    
- <span data-ttu-id="b1aef-112">[Writeback uređaj](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) dozvoljava registrirani uređaji u azurno AD za zapisivanje nazad aktivni direktorijum lokalne tako da može da se koristi za uslovnog pristupa.</span><span class="sxs-lookup"><span data-stu-id="b1aef-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span> 
    
- <span data-ttu-id="b1aef-p104">[Sprečavanje slučajnog briše](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) se zadano sprečavanje brisanja previše istovremenih objekta (više od 500 objekata po sinhronizacije). Možete da promenite ovu postavku u susret potrebama vaše organizacije.</span><span class="sxs-lookup"><span data-stu-id="b1aef-p104">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization). You can change this setting to meet the needs of your organization.</span></span> 
    
- <span data-ttu-id="b1aef-115">[Automatska nadogradnja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je zadano omogućen za Ekspresna instalacija i da se obezbedi tvoja verzija povezivanja Azure AD je uvek trenutni.</span><span class="sxs-lookup"><span data-stu-id="b1aef-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span> 
    


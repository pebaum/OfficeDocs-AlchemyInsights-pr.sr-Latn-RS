---
title: 646 kako konfigurirati AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 646
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 2dc4ae7d6809c24ce599ac128570e9354c9f2b30
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752575"
---
# <a name="configure-sync-features"></a><span data-ttu-id="4b8d2-102">Podesite opcije sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="4b8d2-102">Configure sync features</span></span>

<span data-ttu-id="4b8d2-103">Azurno AD povezivanje sadrži nekoliko funkcija koje su podrazumevano, ili to možete omogućiti kasnije.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="4b8d2-104">Neke funkcije zahtevaju dodatne konfiguracije u određenim sredinama.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="4b8d2-105">[Filtriranje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) ograničenja objektima se sinhronizuju sa azurno AD.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="4b8d2-106">Podrazumevane, svi korisnici, kontakti, grupe i Windows 10 računara nalozi se sinhronizuju.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="4b8d2-107">Možete uključiti ili isključiti objekte na osnovu domeni, organizacione jedinice ili druge atribute.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="4b8d2-108">[Lozinka hash sačekate](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sinhronizuje lozinku hash iz lokalne aktivni direktorijum se azurno oglasa.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-108">[Password hash syncronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="4b8d2-109">Ovo omogućava upravljanje lozinkama na jednoj lokaciji, ali koristi istu lozinku u oba na više lokacija i zamagle okruženjima.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="4b8d2-110">Pošto je Active Directory autoritativnih izvora, možete da koristite polisa lozinku.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="4b8d2-111">[Samouslužno gesla (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) omogućava korisnicima da poništi svoje lozinke u oblaku prilikom i dalje primene svoje lokalne smernice za lozinke.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="4b8d2-112">[Writeback uređaj](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) dozvoljava registrirani uređaji u azurno AD za zapisivanje nazad aktivni direktorijum lokalne tako da može da se koristi za uslovnog pristupa.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="4b8d2-113">[Sprečavanje slučajnog briše](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) se zadano sprečavanje brisanja previše istovremenih objekta (više od 500 objekata po sinhronizacije).</span><span class="sxs-lookup"><span data-stu-id="4b8d2-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="4b8d2-114">Možete da promenite ovu postavku u susret potrebama vaše organizacije.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="4b8d2-115">[Automatska nadogradnja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je zadano omogućen za Ekspresna instalacija i da se obezbedi tvoja verzija povezivanja Azure AD je uvek trenutni.</span><span class="sxs-lookup"><span data-stu-id="4b8d2-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>

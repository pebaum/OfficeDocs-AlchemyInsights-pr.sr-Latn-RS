---
title: 646 kako konfigurisati AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 713cda26e55f07f0438cb9ebe5aa9da86c4ebb3a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43722577"
---
# <a name="configure-sync-features"></a><span data-ttu-id="6599f-102">Konfigurisanje funkcija sinhronizacije</span><span class="sxs-lookup"><span data-stu-id="6599f-102">Configure sync features</span></span>

<span data-ttu-id="6599f-103">Azure Connect AD sadrži nekoliko funkcija koje su podrazumevano omogućene ili koje možete da omogućite kasnije.</span><span class="sxs-lookup"><span data-stu-id="6599f-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="6599f-104">Neke funkcije zahtevaju dodatnu konfiguraciju u određenim okruženjima.</span><span class="sxs-lookup"><span data-stu-id="6599f-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="6599f-105">[Filtriranje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) ograničenja objekti se sinhronizuju sa Azure oglasima.</span><span class="sxs-lookup"><span data-stu-id="6599f-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="6599f-106">Podrazumevano je da se svi korisnici, kontakti, grupe i Windows 10 računarski nalozi sinhronizuju.</span><span class="sxs-lookup"><span data-stu-id="6599f-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="6599f-107">Objekte možete da uključite ili izuzmete na osnovu domena, ili drugih atributa.</span><span class="sxs-lookup"><span data-stu-id="6599f-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="6599f-108">[Sinhronizacija hash sinhronizacije](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sinhronizuje hash lozinku iz aktivnog direktorijuma na "AZURE" a.d..</span><span class="sxs-lookup"><span data-stu-id="6599f-108">[Password hash synchronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="6599f-109">Ovo omogućava upravljanje lozinkom na jednoj lokaciji, ali koristi istu lozinku i u okruženjima i u informatičkom oblaku.</span><span class="sxs-lookup"><span data-stu-id="6599f-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="6599f-110">Pošto je aktivni direktorijum ovlašćeni izvor, možete da koristite sopstvene smernice za lozinke.</span><span class="sxs-lookup"><span data-stu-id="6599f-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="6599f-111">[Uspostavljanje početne vrednosti lozinke za samouslugu (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) omogućava korisnicima da resetuje sopstvene lozinke u informatičkom oblaku dok i dalje primenjuje vaše smernice za lozinku.</span><span class="sxs-lookup"><span data-stu-id="6599f-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="6599f-112">Zapisivanje [uređaja](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) dozvoljava da registrovani uređaji u Azure oglasnom programu budu napisani nazad u aktivni direktorijum na tom prostoru kako bi mogli da se koriste za uslovno pristupanje.</span><span class="sxs-lookup"><span data-stu-id="6599f-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="6599f-113">[Sprečavanje nehotičnog](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) brisanja je podrazumevano omogućeno da bi se sprečilo da se spreči previše istovremenih brisanja objekata (više od 500 objekata po sinhronizaciji).</span><span class="sxs-lookup"><span data-stu-id="6599f-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="6599f-114">Ovu postavku možete da promenite da bi zadovoljili potrebe vaše organizacije.</span><span class="sxs-lookup"><span data-stu-id="6599f-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="6599f-115">[Automatsko nadograđivanje](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je podrazumevano omogućeno za ekspresne instalacije i pomaže vam da se uverite da je vaša verzija programa Azure AD Connect uvek aktuelna.</span><span class="sxs-lookup"><span data-stu-id="6599f-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>

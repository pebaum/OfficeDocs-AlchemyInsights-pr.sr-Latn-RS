---
title: Teams centar administracije
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002890"
- "5542"
ms.openlocfilehash: d504a26ee6532ec291eae797b1c81d86a05414b0
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/23/2020
ms.locfileid: "44354102"
---
# <a name="teams-admin-center"></a><span data-ttu-id="cb9ba-102">Teams centar administracije</span><span class="sxs-lookup"><span data-stu-id="cb9ba-102">Teams Admin Center</span></span>

<span data-ttu-id="cb9ba-103">Saznajte više o upravljanju uslugom Teams uz[Teams centar administracije](https://docs.microsoft.com/microsoftteams/manage-teams-skypeforbusiness-admin-center).</span><span class="sxs-lookup"><span data-stu-id="cb9ba-103">Learn about managing Teams with the [Teams Admin Center](https://docs.microsoft.com/microsoftteams/manage-teams-skypeforbusiness-admin-center).</span></span>

<span data-ttu-id="cb9ba-104">Ako ne možete da pristupite Teams centru administracije, proverite sledeće stavke:</span><span class="sxs-lookup"><span data-stu-id="cb9ba-104">If you are unable to access the Teams Admin Center, please check the following items:</span></span>

- <span data-ttu-id="cb9ba-105">Uverite se da ste omogućili odgovarajuće [Office 365 IP adrese i URL adrese ](https://docs.microsoft.com/Office365/Enterprise/office-365-ip-web-service)na bilo kom uređaju (zaštitnom zidu itd.) ili u okviru pravila zaštitnog zida na lokalnom računaru.</span><span class="sxs-lookup"><span data-stu-id="cb9ba-105">Verify that you have allowed the appropriate [Office 365 IP addresses and URL's](https://docs.microsoft.com/Office365/Enterprise/office-365-ip-web-service) on any perimeter devices (firewall, etc.) or in the firewall rules on your local machine.</span></span>
- <span data-ttu-id="cb9ba-106">Proverite da li se prijavljivanje koje koristite za pristup Teams portalu za administraciju podudara sa vašim korisničkim imenom navedeno na [Microsoft 365 portalu za administraciju](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).</span><span class="sxs-lookup"><span data-stu-id="cb9ba-106">Verify that the login you are using to access the Teams Admin Portal matches your username listed in the [Microsoft 365 Admin portal](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).</span></span>

<span data-ttu-id="cb9ba-107">Ako se korisnici ne pojavljuju u Teams centru administracije, proverite sledeće:</span><span class="sxs-lookup"><span data-stu-id="cb9ba-107">If users are not appearing in the Teams Admin Center, please check the following:</span></span>

- <span data-ttu-id="cb9ba-108">Da li ste kreirali korisnike ili dodeljivali licence u protekla 24 časa?</span><span class="sxs-lookup"><span data-stu-id="cb9ba-108">Have you created users or assigned licenses in the last 24 hours?</span></span> <span data-ttu-id="cb9ba-109">Uverite se da ste sačekali najmanje 24 časa pre otvaranja tiketa za podršku.</span><span class="sxs-lookup"><span data-stu-id="cb9ba-109">Please make sure you wait at least 24 hours before opening a support ticket.</span></span>
- <span data-ttu-id="cb9ba-110">Proverite da li ste dodelili odgovarajuće licence?</span><span class="sxs-lookup"><span data-stu-id="cb9ba-110">Verify you have assigned appropriate licenses?</span></span>
- <span data-ttu-id="cb9ba-111">Ako imate aktivni direktorijum na osnovu lokalnog direktorijuma, proverite da li je [vrednost msRTCSIP-PrimaryUserAddress ili adrese SIP-a u polju ProxyAddresses u lokalnom aktivnom direktorijumu jedinstvena i da format odgovara](https://docs.microsoft.com/skypeforbusiness/troubleshoot/online-configuration/msrtcsip-primaryuseraddress-proxyaddaddress) SIP-u:**korisničko ime** korisnika iz [Microsoft 365 admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).</span><span class="sxs-lookup"><span data-stu-id="cb9ba-111">If you have an on-premise Active Directory, verify that [the value of msRTCSIP-PrimaryUserAddress or the SIP address in the ProxyAddresses field in your local Active Directory is unique and the format matches](https://docs.microsoft.com/skypeforbusiness/troubleshoot/online-configuration/msrtcsip-primaryuseraddress-proxyaddaddress) sip:**Username** of the user from the [Microsoft 365 admin center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).</span></span>
- <span data-ttu-id="cb9ba-112">Ako nameravate da koristite Skype za raspoređivanje poslovnih servera i ako su korisnici bili u fazi i na mreži: pratite **"Podešavanje hibrida sa timovima i Skype za Business online"** na kontrolnoj tabli Skype za poslovni server i premeštanje korisnika na mreži.</span><span class="sxs-lookup"><span data-stu-id="cb9ba-112">If you intend to keep a Skype for Business Server deployment and have users homed on-premises and Online: follow the **"Set up hybrid with Teams and Skype for Business Online"** in your Skype for Business Server Control Panel and move users Online.</span></span>

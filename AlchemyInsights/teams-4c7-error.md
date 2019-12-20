---
title: Greška u timovima 4c7
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 0945a341c6456ee4178c0485f3bfb9232fa78a11
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796344"
---
# <a name="4c7-error-in-microsoft-teams"></a><span data-ttu-id="9045a-102">4c7 greška u Microsoft timovima</span><span class="sxs-lookup"><span data-stu-id="9045a-102">4c7 error in Microsoft Teams</span></span>

<span data-ttu-id="9045a-103">Ova greška se javlja zato što Microsoft timovi zahtevaju potvrdu identiteta obrazaca.</span><span class="sxs-lookup"><span data-stu-id="9045a-103">This error occurs because Microsoft Teams requires Forms Authentication.</span></span> <span data-ttu-id="9045a-104">Kada primenite usluge Federacije aktivnog direktorijuma (AD FS), provera identiteta obrazaca podrazumevano nije omogućena za internu mrežu.</span><span class="sxs-lookup"><span data-stu-id="9045a-104">When you deploy Active Directory Federation Services (AD FS), Forms Authentication is not enabled for the intranet by default.</span></span> <span data-ttu-id="9045a-105">Ako Windows integrisana potvrda identiteta ne uspe, od vas će se zatražiti da se prijavite pomoću provere identiteta obrazaca.</span><span class="sxs-lookup"><span data-stu-id="9045a-105">If Windows Integrated Authentication fails, you are prompted to sign in by using Forms Authentication.</span></span>

<span data-ttu-id="9045a-106">Da biste rešili ovaj problem, omogućite potvrdu identiteta obrazaca pomoću proširenja konzole "AD FS Microsoft Management Console (MMC)" na računaru koji ima lokalnu kopiju aktivnog direktorijuma.</span><span class="sxs-lookup"><span data-stu-id="9045a-106">To resolve this issue, enable Forms Authentication by using the AD FS Microsoft Management Console (MMC) snap-in on the computer that has the local copy of Active Directory.</span></span> <span data-ttu-id="9045a-107">Da biste to uradili, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="9045a-107">To do this, follow these steps:</span></span> 

1. <span data-ttu-id="9045a-108">U oknu za navigaciju potražite smernice za **potvrdu identiteta**.</span><span class="sxs-lookup"><span data-stu-id="9045a-108">In the navigation pane, browse to **Authentication Policies**.</span></span>
2. <span data-ttu-id="9045a-109">U okviru **stavke Radnje** u oknu sa detaljima izaberite stavku **Uredi globalnu primarnu potvrdu identiteta**.</span><span class="sxs-lookup"><span data-stu-id="9045a-109">Under **Actions** in the details pane, select **Edit Global Primary Authentication**.</span></span>
3. <span data-ttu-id="9045a-110">Na kartici " **interna mreža** " izaberite stavku " **Provera identiteta obrazaca**".</span><span class="sxs-lookup"><span data-stu-id="9045a-110">On the **Intranet** tab, select **Forms Authentication**.</span></span>
4. <span data-ttu-id="9045a-111">Izaberite **"u redu"** (ili **Primijeni**).</span><span class="sxs-lookup"><span data-stu-id="9045a-111">Select **OK** (or **Apply**).</span></span>
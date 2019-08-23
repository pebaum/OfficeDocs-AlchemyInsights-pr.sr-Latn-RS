---
title: Rad sa iOS VPP aplikacija pravilo Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: a0bbc1f49f251ef4f16300c8cca98e219008d17e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558019"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="af222-102">Rad sa iOS aplikacije VPP</span><span class="sxs-lookup"><span data-stu-id="af222-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="af222-103">Čitao [kako upravljati iOS aplikacije dobavljena pomoću volumena nabavke program sa Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) da biste saznali više o funkcijama, ograničenja i korake kako bi koristiti Apple volumena nabavke programa, kao i podršku za to u Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="af222-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="af222-104">**Uobičajene probleme:** „Aplikaciju za iOS VPP je dodeljen moji korisnici, ali je instalacija nije uspjela”.</span><span class="sxs-lookup"><span data-stu-id="af222-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="af222-105">Ovo se može dogoditi ako jedan VPP token koristi preko više dobavljača za upravljanje mobilnim uređajem.</span><span class="sxs-lookup"><span data-stu-id="af222-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="af222-106">VPP simboli iz jabuke se može koristiti samo kod jednog dobavljača.</span><span class="sxs-lookup"><span data-stu-id="af222-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="af222-107">Ako ste koristili oznaku za VPP sa više dobavljača, morate ponovo da otpremite simbol da Intune.</span><span class="sxs-lookup"><span data-stu-id="af222-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="af222-108">Instalaciju možete takođe propasti ako ukupan broj instalacija premašiti broj licenci.</span><span class="sxs-lookup"><span data-stu-id="af222-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="af222-109">Da biste prikazali izveštaj o korišćenju za vaše licence, idi da **Intune mobilne aplikacije** \> **aplikacija za licence** stranice.</span><span class="sxs-lookup"><span data-stu-id="af222-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="af222-110">Da biste saznali kako da povratite licence u upotrebi, pogledajte [Ovaj članak.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="af222-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>

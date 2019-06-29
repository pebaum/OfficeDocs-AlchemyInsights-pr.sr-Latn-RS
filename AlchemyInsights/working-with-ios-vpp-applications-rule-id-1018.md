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
ms.openlocfilehash: 58471f22ce78be1b40d3330a76a92d811819849d
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/28/2019
ms.locfileid: "35364879"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="e40cd-102">Rad sa iOS aplikacije VPP</span><span class="sxs-lookup"><span data-stu-id="e40cd-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="e40cd-103">Čitao [kako upravljati iOS aplikacije dobavljena pomoću volumena nabavke program sa Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) da biste saznali više o funkcijama, ograničenja i korake kako bi koristiti Apple volumena nabavke programa, kao i podršku za to u Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="e40cd-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="e40cd-104">**Uobičajene probleme:** „Aplikaciju za iOS VPP je dodeljen moji korisnici, ali je instalacija nije uspjela”.</span><span class="sxs-lookup"><span data-stu-id="e40cd-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="e40cd-105">Ovo se može dogoditi ako jedan VPP token koristi preko više dobavljača za upravljanje mobilnim uređajem.</span><span class="sxs-lookup"><span data-stu-id="e40cd-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="e40cd-106">VPP simboli iz jabuke se može koristiti samo kod jednog dobavljača.</span><span class="sxs-lookup"><span data-stu-id="e40cd-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="e40cd-107">Ako ste koristili oznaku za VPP sa više dobavljača, morate ponovo da otpremite simbol da Intune.</span><span class="sxs-lookup"><span data-stu-id="e40cd-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="e40cd-108">Instalaciju možete takođe propasti ako ukupan broj instalacija premašiti broj licenci.</span><span class="sxs-lookup"><span data-stu-id="e40cd-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="e40cd-109">Da biste prikazali izveštaj o korišćenju za vaše licence, idi da **Intune mobilne aplikacije** \> **aplikacija za licence** stranice.</span><span class="sxs-lookup"><span data-stu-id="e40cd-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="e40cd-110">Da biste saznali kako da povratite licence u upotrebi, pogledajte [Ovaj članak.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="e40cd-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>

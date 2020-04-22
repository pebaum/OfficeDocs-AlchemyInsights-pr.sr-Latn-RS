---
title: Rad s iOS VPP Applications ID 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 88a1ef66bf337b3a0094976c122330591aee77ff
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719971"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="08fdb-102">Rad u radu sa iOS VPP aplikacijama</span><span class="sxs-lookup"><span data-stu-id="08fdb-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="08fdb-103">Pročitajte [Kako da upravljate aplikacijama za iOS koje su kupljene pomoću programa za kupovinu volumena pomoću programa Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) da biste saznali više o funkcijama, ograničenjima i koracima za korišćenje programa za kupovinu volumena u Apple sistemu i podršku za nju u programu Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="08fdb-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="08fdb-104">**Česta pitanja:** "Za svoje korisnike sam dodelio" iOS VPP aplikaciju ", ali Instalacija nije uspela."</span><span class="sxs-lookup"><span data-stu-id="08fdb-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="08fdb-105">Do ovoga može doći ako se u više dobavljača za upravljanje mobilnim uređajima koristi jedan VPP simbol.</span><span class="sxs-lookup"><span data-stu-id="08fdb-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="08fdb-106">VPP tokena iz jabuke može da se koristi samo sa jednim dobavljačem.</span><span class="sxs-lookup"><span data-stu-id="08fdb-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="08fdb-107">Ako ste koristili VPP Token sa više dobavljača, morate ponovo da otpremite oznaku u Intune.</span><span class="sxs-lookup"><span data-stu-id="08fdb-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="08fdb-108">Instalacija takođe može da otkaže ako ukupan broj instalacija premaši broj licenci.</span><span class="sxs-lookup"><span data-stu-id="08fdb-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="08fdb-109">Da biste pogledali izveštaj o korišćenju vaših licenci, idite na stranicu "Intune licence za aplikacije za **mobilnu** \> **aplikaciju"** .</span><span class="sxs-lookup"><span data-stu-id="08fdb-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="08fdb-110">Da biste saznali kako da povratite licence u upotrebi, pogledajte [Ovaj članak.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="08fdb-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>

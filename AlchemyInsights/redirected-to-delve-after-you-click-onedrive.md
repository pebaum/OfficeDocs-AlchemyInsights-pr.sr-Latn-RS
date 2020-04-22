---
title: OneDrive za poslovnu Web OneDrive preusmerava na Delve
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1870"
- "900072"
ms.openlocfilehash: cbf3db148e16ba6631e9077f893a18d3e1b977af
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43722824"
---
# <a name="redirected-to-delve-after-you-click-onedrive"></a><span data-ttu-id="2fe61-102">Preusmeravaju se na Delve nakon što kliknete na OneDrive</span><span class="sxs-lookup"><span data-stu-id="2fe61-102">Redirected to Delve after you click OneDrive</span></span>

<span data-ttu-id="2fe61-103">Pogledajte naš detaljni [Vodič za rešavanje problema](https://docs.microsoft.com/sharepoint/support/sites/troubleshooting-guide-for-sites-stopped-at-provisioning).</span><span class="sxs-lookup"><span data-stu-id="2fe61-103">See our detailed [Troubleshooting Guide](https://docs.microsoft.com/sharepoint/support/sites/troubleshooting-guide-for-sites-stopped-at-provisioning).</span></span>

<span data-ttu-id="2fe61-104">Da bi rešio ovaj problem, administrator mora korisnicima da dodeli pravo da kreira svoje lokacije mog portala.</span><span class="sxs-lookup"><span data-stu-id="2fe61-104">To resolve this problem, the administrator must grant users the right to create their My Sites site.</span></span> <span data-ttu-id="2fe61-105">Do ovoga dolazi zato što se na lokacijama kreira OneDrive za poslovnu stranicu.</span><span class="sxs-lookup"><span data-stu-id="2fe61-105">This is because the OneDrive for Business page is created on My Sites.</span></span>

<span data-ttu-id="2fe61-106">Da biste dodelili ovo pravo, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="2fe61-106">To grant this right, follow these steps:</span></span>

1. <span data-ttu-id="2fe61-107">U sistemu SharePoint admin Center izaberite stavku **korisnički profili**.</span><span class="sxs-lookup"><span data-stu-id="2fe61-107">In the SharePoint admin center,click **user profiles**.</span></span>

2. <span data-ttu-id="2fe61-108">U odeljku " **osobe** " izaberite stavku " **Upravljanje korisničkim dozvolama**".</span><span class="sxs-lookup"><span data-stu-id="2fe61-108">In the **People** section, click **Manage User Permissions**.</span></span>

3. <span data-ttu-id="2fe61-109">Dodajte korisnike koji zahtevaju dozvolu za kreiranje lokacije "Moji portali".</span><span class="sxs-lookup"><span data-stu-id="2fe61-109">Add users who require permissions to create their My Sites site.</span></span> <span data-ttu-id="2fe61-110">Ova postavka je podrazumevano postavljena na **sve osim za spoljne korisnike**.</span><span class="sxs-lookup"><span data-stu-id="2fe61-110">By default, this setting is set to **Everyone except external users**.</span></span>

4. <span data-ttu-id="2fe61-111">Nakon što dodate korisnika, korisnike ili grupu, uverite se da je izabran korisnik, korisnici ili grupa, pomerite se do odeljka " **dozvole** ", a zatim potvrdite izbor u polju za potvrdu pored stavke " **Kreiranje lične lokacije" (potrebno za lično skladištenje, ubacivanje papira i praćeni sadržaj)**.</span><span class="sxs-lookup"><span data-stu-id="2fe61-111">After you have added the user, users, or group, make sure that the added user, users, or group is selected, scroll to the **permissions** section, and then select the check box next to **Create Personal Site (required for personal storage, newsfeed, and followed content)**.</span></span>

5. <span data-ttu-id="2fe61-112">Kliknite na dugme **u redu**, a zatim neka korisnik Potraži do OneDrive stranice da bi kreirao lokaciju.</span><span class="sxs-lookup"><span data-stu-id="2fe61-112">Click **OK**, and then have the user browse to the OneDrive page to create the site.</span></span>

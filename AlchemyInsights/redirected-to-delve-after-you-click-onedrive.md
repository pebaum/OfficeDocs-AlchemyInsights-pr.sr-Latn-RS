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
ms.openlocfilehash: 74151ed149c57ceebc841902796189f6638795a9
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571239"
---
# <a name="redirected-to-delve-after-you-click-onedrive"></a><span data-ttu-id="3d0d7-102">Preusmeravaju se na Delve nakon što kliknete na OneDrive</span><span class="sxs-lookup"><span data-stu-id="3d0d7-102">Redirected to Delve after you click OneDrive</span></span>

<span data-ttu-id="3d0d7-103">Pogledajte naš detaljni [Vodič za rešavanje problema](https://docs.microsoft.com/sharepoint/support/sites/troubleshooting-guide-for-sites-stopped-at-provisioning).</span><span class="sxs-lookup"><span data-stu-id="3d0d7-103">See our detailed [Troubleshooting Guide](https://docs.microsoft.com/sharepoint/support/sites/troubleshooting-guide-for-sites-stopped-at-provisioning).</span></span>

<span data-ttu-id="3d0d7-104">Da biste rešili ovaj problem, administrator sistema Office 365 mora korisnicima dodeliti pravo da kreiraju svoje lokacije "moje lokacije".</span><span class="sxs-lookup"><span data-stu-id="3d0d7-104">To resolve this problem, the Office 365 administrator must grant users the right to create their My Sites site.</span></span> <span data-ttu-id="3d0d7-105">Do ovoga dolazi zato što se na lokacijama kreira OneDrive za poslovnu stranicu.</span><span class="sxs-lookup"><span data-stu-id="3d0d7-105">This is because the OneDrive for Business page is created on My Sites.</span></span>

<span data-ttu-id="3d0d7-106">Da biste dodelili ovo pravo, sledite ove korake:</span><span class="sxs-lookup"><span data-stu-id="3d0d7-106">To grant this right, follow these steps:</span></span>

1. <span data-ttu-id="3d0d7-107">U sistemu SharePoint admin Center izaberite stavku **korisnički profili**.</span><span class="sxs-lookup"><span data-stu-id="3d0d7-107">In the SharePoint admin center,click **user profiles**.</span></span>

2. <span data-ttu-id="3d0d7-108">U odeljku " **osobe** " izaberite stavku " **Upravljanje korisničkim dozvolama**".</span><span class="sxs-lookup"><span data-stu-id="3d0d7-108">In the **People** section, click **Manage User Permissions**.</span></span>

3. <span data-ttu-id="3d0d7-109">Dodajte korisnike koji zahtevaju dozvolu za kreiranje lokacije "Moji portali".</span><span class="sxs-lookup"><span data-stu-id="3d0d7-109">Add users who require permissions to create their My Sites site.</span></span> <span data-ttu-id="3d0d7-110">Ova postavka je podrazumevano postavljena na **sve osim za spoljne korisnike**.</span><span class="sxs-lookup"><span data-stu-id="3d0d7-110">By default, this setting is set to **Everyone except external users**.</span></span>

4. <span data-ttu-id="3d0d7-111">Nakon što dodate korisnika, korisnike ili grupu, uverite se da je izabran korisnik, korisnici ili grupa, pomerite se do odeljka " **dozvole** ", a zatim potvrdite izbor u polju za potvrdu pored stavke " **Kreiranje lične lokacije" (potrebno za lično skladištenje, ubacivanje papira i praćeni sadržaj)**.</span><span class="sxs-lookup"><span data-stu-id="3d0d7-111">After you have added the user, users, or group, make sure that the added user, users, or group is selected, scroll to the **permissions** section, and then select the check box next to **Create Personal Site (required for personal storage, newsfeed, and followed content)**.</span></span>

5. <span data-ttu-id="3d0d7-112">Kliknite na dugme **u redu**, a zatim neka korisnik Potraži do OneDrive stranice da bi kreirao lokaciju.</span><span class="sxs-lookup"><span data-stu-id="3d0d7-112">Click **OK**, and then have the user browse to the OneDrive page to create the site.</span></span>

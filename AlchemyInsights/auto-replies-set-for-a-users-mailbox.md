---
title: Postavljanje automatskih odgovora za poštansko sanduče
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000761"
- "3514"
ms.openlocfilehash: aeeb2e1e76fe602d2767b422797452fd1155fdd5
ms.sourcegitcommit: fdfd41c2bfb2d45003b3906e6469377384a91cb5
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/15/2020
ms.locfileid: "43509515"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a><span data-ttu-id="2147f-102">Postavljanje automatskih odgovora za poštansko sanduče korisnika</span><span class="sxs-lookup"><span data-stu-id="2147f-102">Set auto replies for a user's mailbox</span></span>

<span data-ttu-id="2147f-103">**Metod 1**</span><span class="sxs-lookup"><span data-stu-id="2147f-103">**Method 1**</span></span>

1. <span data-ttu-id="2147f-104">Prijavljivanje na Office 365 portal.</span><span class="sxs-lookup"><span data-stu-id="2147f-104">Sign in to the Office 365 portal.</span></span>

2. <span data-ttu-id="2147f-105">Idite na **korisnici > aktivni korisnici** (ili \*\*grupe > deljeni poštanski sandučići \*\* ako je postavite na deljeno poštansko sanduče).</span><span class="sxs-lookup"><span data-stu-id="2147f-105">Go to **Users > Active users** (or **Groups > Shared mailboxes** if you set this on a shared mailbox).</span></span>

3. <span data-ttu-id="2147f-106">Izaberite korisnika koji ima Microsoft Exchange poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="2147f-106">Select a user who has a Microsoft Exchange mailbox.</span></span>

4. <span data-ttu-id="2147f-107">U dodatnom meniju nadesno idite na \*\*postavke pošte > automatski odgovori \*\*(ako je u pitanju deljeno poštansko sanduče, samo kliknite \*\*automatski odgovori \*\*u dodatnom meniju).</span><span class="sxs-lookup"><span data-stu-id="2147f-107">On the fly-out menu on the right, go to **Mail settings > Automatic replies** (if it's a shared mailbox, just click **Automatic replies** on the fly-out).</span></span>

<span data-ttu-id="2147f-108">**Metod 2**</span><span class="sxs-lookup"><span data-stu-id="2147f-108">**Method 2**</span></span>

1. <span data-ttu-id="2147f-109">Prijavite se na portal Office 365 administrator pomoću akreditiva administratora.</span><span class="sxs-lookup"><span data-stu-id="2147f-109">Sign in to the Office 365 admin portal by using administrator credentials.</span></span>

2. <span data-ttu-id="2147f-110">Proširite \*\* centre za administraciju \*\*, a zatim izaberite stavku \*\* Exchange \*\*.</span><span class="sxs-lookup"><span data-stu-id="2147f-110">Expand **Admin Centers**, and then click **Exchange**.</span></span>

3. <span data-ttu-id="2147f-111">Kliknite na sliku u gornjem desnom uglu, izaberite stavku\*\*još jedan korisnik \*\*, a zatim kliknite na korisničko poštansko sanduče koje želite da promenite.</span><span class="sxs-lookup"><span data-stu-id="2147f-111">Click the picture in the upper-right corner, click **Another User**, and then select the user mailbox that you want to change.</span></span>

4. <span data-ttu-id="2147f-112">Na levoj strani izaberite stavku \*\*opcije \*\*, izaberite stavku \*\*organizovanje e-pošte \*\*, a zatim kliknite na dugme **automatski odgovori.**</span><span class="sxs-lookup"><span data-stu-id="2147f-112">On the left side, select **Options**, click **Organize E-mail**, and then click **Automatic replies.**</span></span>

<span data-ttu-id="2147f-113">**Metod 3**</span><span class="sxs-lookup"><span data-stu-id="2147f-113">**Method 3**</span></span>

<span data-ttu-id="2147f-114">Pokrenite sledeće cmdlet komandu stavke u usluzi Exchange Online Windows PowerShell:</span><span class="sxs-lookup"><span data-stu-id="2147f-114">Run the following cmdlet in Exchange Online PowerShell:</span></span>

<span data-ttu-id="2147f-115">PowerShellCopy</span><span class="sxs-lookup"><span data-stu-id="2147f-115">PowerShellCopy</span></span>

```
    Set-MailboxAutoReplyConfiguration
```

<span data-ttu-id="2147f-116">Više informacija o ovoj cmdlet komandi potražite u članku [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span><span class="sxs-lookup"><span data-stu-id="2147f-116">For more information about this cmdlet, see [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span></span>

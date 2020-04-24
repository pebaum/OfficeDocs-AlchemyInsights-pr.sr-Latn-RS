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
ms.openlocfilehash: 4ffe8d77dad7db5fd5806fe879cf4934e5ca7c4a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2020
ms.locfileid: "43788896"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a><span data-ttu-id="c006e-102">Postavljanje automatskih odgovora za poštansko sanduče korisnika</span><span class="sxs-lookup"><span data-stu-id="c006e-102">Set auto replies for a user's mailbox</span></span>

<span data-ttu-id="c006e-103">**Metod 1**</span><span class="sxs-lookup"><span data-stu-id="c006e-103">**Method 1**</span></span>

1. <span data-ttu-id="c006e-104">Prijavljivanje u Microsoft 365 portal.</span><span class="sxs-lookup"><span data-stu-id="c006e-104">Sign in to the Microsoft 365 portal.</span></span>

2. <span data-ttu-id="c006e-105">Idite na stavku**Korisnici > Aktivni korisnici** (ili \*\*Grupe > Deljeni poštanski sandučići \*\* ako ste postavili ovo na deljeno poštansko sanduče).</span><span class="sxs-lookup"><span data-stu-id="c006e-105">Go to **Users > Active users** (or **Groups > Shared mailboxes** if you set this on a shared mailbox).</span></span>

3. <span data-ttu-id="c006e-106">Izaberite korisnika koji ima Microsoft Exchange poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="c006e-106">Select a user who has a Microsoft Exchange mailbox.</span></span>

4. <span data-ttu-id="c006e-107">U dodatnom meniju nadesno idite na \*\*Postavke pošte > Automatski odgovori \*\*(ako je u pitanju deljeno poštansko sanduče, samo kliknite \*\*Automatski odgovori \*\*u dodatnom meniju).</span><span class="sxs-lookup"><span data-stu-id="c006e-107">On the fly-out menu on the right, go to **Mail settings > Automatic replies** (if it's a shared mailbox, just click **Automatic replies** on the fly-out).</span></span>

<span data-ttu-id="c006e-108">**Metod 2**</span><span class="sxs-lookup"><span data-stu-id="c006e-108">**Method 2**</span></span>

1. <span data-ttu-id="c006e-109">Prijavite se na Microsoft 365 portal za administraciju pomoću akreditiva administratora.</span><span class="sxs-lookup"><span data-stu-id="c006e-109">Sign in to the Microsoft 365 admin portal by using administrator credentials.</span></span>

2. <span data-ttu-id="c006e-110">Proširite \*\*Centre za administraciju \*\*, a zatim kliknite na stavku \*\* Exchange \*\*.</span><span class="sxs-lookup"><span data-stu-id="c006e-110">Expand **Admin Centers**, and then click **Exchange**.</span></span>

3. <span data-ttu-id="c006e-111">Kliknite na sliku u gornjem desnom uglu, kliknite na stavku\*\*Još jedan korisnik \*\*, a zatim izaberite korisničko poštansko sanduče koje želite da promenite.</span><span class="sxs-lookup"><span data-stu-id="c006e-111">Click the picture in the upper-right corner, click **Another User**, and then select the user mailbox that you want to change.</span></span>

4. <span data-ttu-id="c006e-112">Na levoj strani izaberite stavku \*\*Opcije \*\*, kliknite na stavku \*\*Organizovanje e-pošte \*\*, a zatim kliknite na dugme **Automatski odgovori.**</span><span class="sxs-lookup"><span data-stu-id="c006e-112">On the left side, select **Options**, click **Organize E-mail**, and then click **Automatic replies.**</span></span>

<span data-ttu-id="c006e-113">**Metod 3**</span><span class="sxs-lookup"><span data-stu-id="c006e-113">**Method 3**</span></span>

<span data-ttu-id="c006e-114">Pokrenite sledeće cmdlet komandu u usluzi Exchange Online Windows PowerShell:</span><span class="sxs-lookup"><span data-stu-id="c006e-114">Run the following cmdlet in Exchange Online PowerShell:</span></span>

<span data-ttu-id="c006e-115">PowerShellCopy</span><span class="sxs-lookup"><span data-stu-id="c006e-115">PowerShellCopy</span></span>

```
    Set-MailboxAutoReplyConfiguration
```

<span data-ttu-id="c006e-116">Više informacija o ovoj cmdlet komandi potražite u članku [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span><span class="sxs-lookup"><span data-stu-id="c006e-116">For more information about this cmdlet, see [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span></span>

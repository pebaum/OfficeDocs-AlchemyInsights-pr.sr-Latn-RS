---
title: Postavljanje automatskih odgovora za poštansko sanduče korisnika
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
ms.openlocfilehash: e3cc01298c10fd3ba21327a7fb5cc5396d0ad74d
ms.sourcegitcommit: 23e5b94f1758bfe202008384e300b81816975375
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/14/2020
ms.locfileid: "43506646"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a><span data-ttu-id="97c85-102">Postavljanje automatskih odgovora za poštansko sanduče korisnika</span><span class="sxs-lookup"><span data-stu-id="97c85-102">Set auto replies for a user's mailbox</span></span>

<span data-ttu-id="97c85-103">**Metod 1**</span><span class="sxs-lookup"><span data-stu-id="97c85-103">**Method 1**</span></span>

1. <span data-ttu-id="97c85-104">Prijavljivanje na Office 365 portal.</span><span class="sxs-lookup"><span data-stu-id="97c85-104">Sign in to the Office 365 portal.</span></span>

2. <span data-ttu-id="97c85-105">Idite na stavku**Korisnici > Aktivni korisnici** (ili \*\*Grupe > Deljeni poštanski sandučići \*\* ako ste postavili ovo na deljeno poštansko sanduče).</span><span class="sxs-lookup"><span data-stu-id="97c85-105">Go to **Users > Active users** (or **Groups > Shared mailboxes** if you set this on a shared mailbox).</span></span>

3. <span data-ttu-id="97c85-106">Izaberite korisnika koji ima Microsoft Exchange poštansko sanduče.</span><span class="sxs-lookup"><span data-stu-id="97c85-106">Select a user who has a Microsoft Exchange mailbox.</span></span>

4. <span data-ttu-id="97c85-107">U dodatnom meniju nadesno idite na \*\*Postavke pošte > Automatski odgovori \*\*(ako je u pitanju deljeno poštansko sanduče, samo kliknite \*\*Automatski odgovori \*\*u dodatnom meniju).</span><span class="sxs-lookup"><span data-stu-id="97c85-107">On the fly-out menu on the right, go to **Mail settings > Automatic replies** (if it's a shared mailbox, just click **Automatic replies** on the fly-out).</span></span>

<span data-ttu-id="97c85-108">**Metod 2**</span><span class="sxs-lookup"><span data-stu-id="97c85-108">**Method 2**</span></span>

1. <span data-ttu-id="97c85-109">Prijavite se na portal Office 365 administrator pomoću akreditiva administratora.</span><span class="sxs-lookup"><span data-stu-id="97c85-109">Sign in to the Office 365 admin portal by using administrator credentials.</span></span>

2. <span data-ttu-id="97c85-110">Proširite \*\*Centre za administraciju \*\*, a zatim kliknite na stavku \*\* Exchange \*\*.</span><span class="sxs-lookup"><span data-stu-id="97c85-110">Expand **Admin Centers**, and then click **Exchange**.</span></span>

3. <span data-ttu-id="97c85-111">Kliknite na sliku u gornjem desnom uglu, kliknite na stavku\*\*Još jedan korisnik \*\*, a zatim izaberite korisničko poštansko sanduče koje želite da promenite.</span><span class="sxs-lookup"><span data-stu-id="97c85-111">Click the picture in the upper-right corner, click **Another User**, and then select the user mailbox that you want to change.</span></span>

4. <span data-ttu-id="97c85-112">Na levoj strani izaberite stavku \*\*Opcije \*\*, kliknite na stavku \*\*Organizovanje e-pošte \*\*, a zatim kliknite na dugme **Automatski odgovori.**</span><span class="sxs-lookup"><span data-stu-id="97c85-112">On the left side, select **Options**, click **Organize E-mail**, and then click **Automatic replies.**</span></span>

<span data-ttu-id="97c85-113">**Metod 3**</span><span class="sxs-lookup"><span data-stu-id="97c85-113">**Method 3**</span></span>

<span data-ttu-id="97c85-114">Pokrenite sledeće cmdlet komandu u usluzi Exchange Online Windows PowerShell:</span><span class="sxs-lookup"><span data-stu-id="97c85-114">Run the following cmdlet in Exchange Online PowerShell:</span></span>

<span data-ttu-id="97c85-115">PowerShellCopy</span><span class="sxs-lookup"><span data-stu-id="97c85-115">PowerShellCopy</span></span>

    Set-MailboxAutoReplyConfiguration

<span data-ttu-id="97c85-116">Više informacija o ovoj cmdlet komandi potražite u članku [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span><span class="sxs-lookup"><span data-stu-id="97c85-116">For more information about this cmdlet, see [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span></span>

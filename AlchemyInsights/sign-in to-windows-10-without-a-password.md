---
title: Prijavljivanje u operativni sistem Windows 10 bez korišćenja lozinke
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001690"
- "3766"
ms.openlocfilehash: 1f325eb7afb1e88457296e8187f8ba6dff2ebfe0
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588294"
---
# <a name="sign-in-to-windows-10-without-using-a-password"></a><span data-ttu-id="6ac41-102">Prijavljivanje u operativni sistem Windows 10 bez korišćenja lozinke</span><span class="sxs-lookup"><span data-stu-id="6ac41-102">Sign-in to Windows 10 without using a password</span></span>

<span data-ttu-id="6ac41-103">Da biste izbegli da otkucate lozinku pri pokretanju operativnog sistema Windows, preporučujemo vam da koristite neku od opcija za Windows Hello bezbedna prijavljivanja, kao što je PIN, prepoznavanje lica ili otisak prsta, ako je dostupan.</span><span class="sxs-lookup"><span data-stu-id="6ac41-103">To avoid having to type a password at Windows startup, we recommend you use one of the Windows Hello secure sign-in options, like a PIN, face recognition, or fingerprint, if available.</span></span> <span data-ttu-id="6ac41-104">Ako zaista želite da onemogućite bezbednu prijavljivanje, pogledajte dolenavedena uputstva "automatski se prijavi u Windows 10".</span><span class="sxs-lookup"><span data-stu-id="6ac41-104">If you really want to disable secure sign-in, see the "Automatically sign in to Windows 10" instructions below.</span></span>

<span data-ttu-id="6ac41-105">**Bezbedni Windows Hello alternative za lozinku naloga**</span><span class="sxs-lookup"><span data-stu-id="6ac41-105">**Secure Windows Hello alternatives to the account password**</span></span>

<span data-ttu-id="6ac41-106">Izaberite **podešavanja > nalozi > opcije za prijavljivanje** (ili kliknite [ovde](ms-settings:signinoptions?activationSource=GetHelp)).</span><span class="sxs-lookup"><span data-stu-id="6ac41-106">Go to **Settings  > Accounts > Sign-in options** (or click [here](ms-settings:signinoptions?activationSource=GetHelp)).</span></span> <span data-ttu-id="6ac41-107">Biće navedene raspoložive opcije za prijavljivanje.</span><span class="sxs-lookup"><span data-stu-id="6ac41-107">Available sign-in options will be listed.</span></span> <span data-ttu-id="6ac41-108">Na primer:</span><span class="sxs-lookup"><span data-stu-id="6ac41-108">For example:</span></span>

![Opcije za prijavljivanje.](media/sign-in-options.png)

<span data-ttu-id="6ac41-110">Kliknite ili dodirnite jednu od opcija da biste je konfigurisali.</span><span class="sxs-lookup"><span data-stu-id="6ac41-110">Click or tap one of the options to configure it.</span></span> <span data-ttu-id="6ac41-111">Sledeći put kada pokrenete ili otključate Windows, moći ćete da koristite novu opciju umesto lozinke.</span><span class="sxs-lookup"><span data-stu-id="6ac41-111">Next time you start or unlock Windows, you will be able to use the new option instead of a password.</span></span> 

<span data-ttu-id="6ac41-112">**Automatsko prijavljivanje na Windows 10**</span><span class="sxs-lookup"><span data-stu-id="6ac41-112">**Automatically sign-in to Windows 10**</span></span>

<span data-ttu-id="6ac41-113">**Napomena**: automatsko prijavljivanje je zgodno, ali predstavlja bezbednosni rizik, naročito ako je računaru dostupno više osoba.</span><span class="sxs-lookup"><span data-stu-id="6ac41-113">**Note**: Automatic sign-in is convenient, but introduces a security risk, especially if your PC is accessible by multiple people.</span></span> 

1. <span data-ttu-id="6ac41-114">Kliknite ili dodirnite dugme " **Start** " na traci zadataka.</span><span class="sxs-lookup"><span data-stu-id="6ac41-114">Click or tap the **Start** button in the Taskbar.</span></span>

2. <span data-ttu-id="6ac41-115">Ukucajte **netplwiz** i udarajte tipku ENTER da biste otvorili prozor korisnički računi.</span><span class="sxs-lookup"><span data-stu-id="6ac41-115">Type **netplwiz** and hit the Enter key to open the User Accounts window.</span></span>

3. <span data-ttu-id="6ac41-116">U **korisničkim nalozima**izaberite nalog na koji želite da se automatski prijavite kada se Windows pokrene.</span><span class="sxs-lookup"><span data-stu-id="6ac41-116">In **User Accounts**, click the account you want to automatically sign in to when Windows starts.</span></span>

4. <span data-ttu-id="6ac41-117">Opozovite izbor u polju za potvrdu "korisnici moraju da unesu korisničko ime i lozinku da bi koristili ovaj računar".</span><span class="sxs-lookup"><span data-stu-id="6ac41-117">Uncheck the "Users must enter a user name and password to use this computer" checkbox.</span></span>

    ![Korisnici moraju da unesu opciju "korisničko ime" i "lozinka".](media/users-must-enter-username.png)

5. <span data-ttu-id="6ac41-119">Kliknite na dugme **U redu**.</span><span class="sxs-lookup"><span data-stu-id="6ac41-119">Click **OK**.</span></span> <span data-ttu-id="6ac41-120">Od vas će se zatražiti da unesete i potvrdite lozinku za nalog koji ste izabrali.</span><span class="sxs-lookup"><span data-stu-id="6ac41-120">You will be asked to enter and confirm the password for the account you selected.</span></span> <span data-ttu-id="6ac41-121">Kliknite na dugme **u redu** da biste završili.</span><span class="sxs-lookup"><span data-stu-id="6ac41-121">Click **OK** to finish.</span></span> <span data-ttu-id="6ac41-122">Sledeći put kada se pokrene Windows 10, on će se automatski prijaviti u nalog koji ste izabrali.</span><span class="sxs-lookup"><span data-stu-id="6ac41-122">Next time Windows 10 starts, it will automatically sign in to the account you selected.</span></span>

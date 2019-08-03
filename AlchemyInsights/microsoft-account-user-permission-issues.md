---
title: Poteškoća - korisnik nije pronađen u katalogu
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 0909edc581c811fdc4683b004e0df0adbac88d1c
ms.sourcegitcommit: 514ced512d0d7fff485b6fbf236cd27d6b4166e0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/26/2019
ms.locfileid: "35249927"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="14761-102">Poteškoća - korisnik nije pronađen u katalogu</span><span class="sxs-lookup"><span data-stu-id="14761-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="14761-103">Ako korisnici primaju greška „korisnika nije moguće pronaći poruku” u direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="14761-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="14761-104">Pokušajte ponovo kada tip problema nije korisnika u imeniku.</span><span class="sxs-lookup"><span data-stu-id="14761-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="14761-105">Ove korake možete dovršiti rešavanje problema.</span><span class="sxs-lookup"><span data-stu-id="14761-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="14761-106">Uverite se da nalog koji je prihvatio poziv email je isti konto koji se koristi za prijavljivanje u kasnije.</span><span class="sxs-lookup"><span data-stu-id="14761-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="14761-107">Uverite se da korisnik koristi isti nalog da prihvati pozivnicu i prijaviti na lokaciji.</span><span class="sxs-lookup"><span data-stu-id="14761-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="14761-108">Za više informacija, pogledajte [Kako da upravljate pseudonime za Microsoft nalog</a> da upravlja Office 365 prijavljivanje](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="14761-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="14761-109">Pronađite svaki site(s) u kojem korisnik prima grešku.</span><span class="sxs-lookup"><span data-stu-id="14761-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="14761-110">Dodavanje „/ _layouts/15/people.aspx/membershipgroupid=0” (unutar dvostruke navodnike) na kraj URL lokacije.</span><span class="sxs-lookup"><span data-stu-id="14761-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="14761-111">Primer: https://_lT _"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="14761-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="14761-112">Izaberite korisnika iz liste.</span><span class="sxs-lookup"><span data-stu-id="14761-112">Select the user from the list.</span></span>

- <span data-ttu-id="14761-113">Kliknite na dugme **Ukloni korisničke dozvole** sa glavne trake.</span><span class="sxs-lookup"><span data-stu-id="14761-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="14761-114">Ponovo dodajte korisnika i ponovo pošaljite pozivnicu za korisnika.</span><span class="sxs-lookup"><span data-stu-id="14761-114">Add back the User and Resend the invite to the user.</span></span>


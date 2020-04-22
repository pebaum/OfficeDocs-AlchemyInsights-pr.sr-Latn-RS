---
title: Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 3b863c5e9962dd29ca2ed41d113041d74830f615
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702752"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="6b965-102">Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu</span><span class="sxs-lookup"><span data-stu-id="6b965-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="6b965-103">Ako korisnici primaju poruku o grešci "nije moguće pronaći korisnika" u direktorijumu, pokušajte ponovo gde je tip problema "korisnik" nije u direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="6b965-103">If users are receiving error message "user can't be found" in the directory, please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="6b965-104">Sledeći koraci mogu biti dovršeni da biste rešili problem.</span><span class="sxs-lookup"><span data-stu-id="6b965-104">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="6b965-105">Uverite se da je nalog koji je prihvatio pozivnicu e-poštom isti nalog koji se koristi za prijavljivanje kasnije.</span><span class="sxs-lookup"><span data-stu-id="6b965-105">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="6b965-106">Uverite se da korisnik koristi isti nalog za prihvatanje poziva i prijavljivanje na lokaciju.</span><span class="sxs-lookup"><span data-stu-id="6b965-106">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="6b965-107">Više informacija potražite u članku [Kako da upravljate pseudonimima za Microsoft nalog</a> da biste upravljali Microsoft 365 prijavljivanju](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="6b965-107">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Microsoft 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="6b965-108">Potražite svaku lokaciju u kojoj korisnik prima grešku.</span><span class="sxs-lookup"><span data-stu-id="6b965-108">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="6b965-109">Dodajte "/_layouts/15/ljud.aspx/člana špeditergroupid = 0" (u okviru dvostrukih navodnika) do kraja URL adrese lokacije.</span><span class="sxs-lookup"><span data-stu-id="6b965-109">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="6b965-110">Primer: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="6b965-110">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="6b965-111">Izaberite korisnika sa liste.</span><span class="sxs-lookup"><span data-stu-id="6b965-111">Select the user from the list.</span></span>

- <span data-ttu-id="6b965-112">Kliknite na dugme " **Ukloni korisničke dozvole** " sa glavne trake.</span><span class="sxs-lookup"><span data-stu-id="6b965-112">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="6b965-113">Vratite korisnika i ponovo pošaljite poziv korisniku.</span><span class="sxs-lookup"><span data-stu-id="6b965-113">Add back the User and Resend the invite to the user.</span></span>


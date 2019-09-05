---
title: Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 81b9dafe8e27e5f73fe232c51ff56fed3fec29b4
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/04/2019
ms.locfileid: "36754206"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="15ee2-102">Rešavanje problema sa pitanjem-korisnik nije pronađen u direktorijumu</span><span class="sxs-lookup"><span data-stu-id="15ee2-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="15ee2-103">Ako korisnici primaju poruku o grešci "nije moguće pronaći korisnika" u direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="15ee2-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="15ee2-104">Pokušajte ponovo gde je tip problema korisnik nije u direktorijumu.</span><span class="sxs-lookup"><span data-stu-id="15ee2-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="15ee2-105">Sledeći koraci mogu biti dovršeni da biste rešili problem.</span><span class="sxs-lookup"><span data-stu-id="15ee2-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="15ee2-106">Uverite se da je nalog koji je prihvatio pozivnicu e-poštom isti nalog koji se koristi za prijavljivanje kasnije.</span><span class="sxs-lookup"><span data-stu-id="15ee2-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="15ee2-107">Uverite se da korisnik koristi isti nalog za prihvatanje poziva i prijavljivanje na lokaciju.</span><span class="sxs-lookup"><span data-stu-id="15ee2-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="15ee2-108">Više informacija potražite u članku [Kako da upravljate pseudonimima za Microsoft nalog</a> da biste upravljali Office 365 prijavljivanju](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="15ee2-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="15ee2-109">Potražite svaku lokaciju u kojoj korisnik prima grešku.</span><span class="sxs-lookup"><span data-stu-id="15ee2-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="15ee2-110">Dodajte "/_layouts/15/ljud.aspx/članidaci\id = 0" (u okviru dvostrukih navodnika) do kraja URL adrese lokacije.</span><span class="sxs-lookup"><span data-stu-id="15ee2-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="15ee2-111">Primer: https: da se _ "contoso">. SharePoint. com/_rasporeda/15/People. aspx/člana Špediterski ID = 0.</span><span class="sxs-lookup"><span data-stu-id="15ee2-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="15ee2-112">Izaberite korisnika sa liste.</span><span class="sxs-lookup"><span data-stu-id="15ee2-112">Select the user from the list.</span></span>

- <span data-ttu-id="15ee2-113">Kliknite na dugme " **Ukloni korisničke dozvole** " sa glavne trake.</span><span class="sxs-lookup"><span data-stu-id="15ee2-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="15ee2-114">Vratite korisnika i ponovo pošaljite poziv korisniku.</span><span class="sxs-lookup"><span data-stu-id="15ee2-114">Add back the User and Resend the invite to the user.</span></span>


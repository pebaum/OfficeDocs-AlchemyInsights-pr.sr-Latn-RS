---
title: Nije moguće pristupiti javnim fasciklama
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891763"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="2b28a-102">Outlook ne može da se poveže sa javnim fasciklama</span><span class="sxs-lookup"><span data-stu-id="2b28a-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="2b28a-103">Ako pristup javnoj fascikli ne funkcioniše za neke korisnike, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="2b28a-103">If public folder access isn't working for some users, try the following:</span></span>

<span data-ttu-id="2b28a-104">Povežite se sa EXO PowerShell i konfigurišite parametar DefaultPublicFolderMailbox na korisničkom računu za ovaj problem da bi se podudarali sa parametrom na radnom korisničkom računu.</span><span class="sxs-lookup"><span data-stu-id="2b28a-104">Connect to EXO PowerShell and configure the DefaultPublicFolderMailbox parameter on the problem user account to match the parameter on a working user account.</span></span>

<span data-ttu-id="2b28a-105">Primer:</span><span class="sxs-lookup"><span data-stu-id="2b28a-105">Example:</span></span>

<span data-ttu-id="2b28a-106">Get-poštansko sanduče | FT DefaultPublicFolderMailbox, EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="2b28a-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="2b28a-107">Set-poštansko sanduče-problem korisnik \<-DefaultPublicFolderMailbox vrednost iz prethodne komande></span><span class="sxs-lookup"><span data-stu-id="2b28a-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="2b28a-108">Sačekajte najmanje jedan sat da bi promena stupila na snagu.</span><span class="sxs-lookup"><span data-stu-id="2b28a-108">Wait at least one hour for the change to take effect.</span></span>

<span data-ttu-id="2b28a-109">Ako problem i dalje postoji, sledite [ovaj postupak](https://aka.ms/pfcte) da biste rešili probleme sa pristupom javne fascikle pomoću programa Outlook.</span><span class="sxs-lookup"><span data-stu-id="2b28a-109">If the issue remains, please follow [this procedure](https://aka.ms/pfcte) to troubleshoot public folder access issues using Outlook.</span></span>
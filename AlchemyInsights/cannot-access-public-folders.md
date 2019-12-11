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
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959508"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="53ba1-102">Outlook ne može da se poveže sa javnim fasciklama</span><span class="sxs-lookup"><span data-stu-id="53ba1-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="53ba1-103">Ako pristup javnoj fascikli ne funkcioniše za nekoliko korisnika, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="53ba1-103">If public folder access isn't working for few users, try the following:</span></span>

<span data-ttu-id="53ba1-104">Povežite se sa EXO PowerShell i konfigurišite DefaultPublicFolderMailbox na korisničkom nalogu problema da bi se podudarali sa jednim na radnom korisničkom računu.</span><span class="sxs-lookup"><span data-stu-id="53ba1-104">Connect to EXO PowerShell, and configure the DefaultPublicFolderMailbox on the problem user account to match one on a working user account.</span></span>

<span data-ttu-id="53ba1-105">Primer:</span><span class="sxs-lookup"><span data-stu-id="53ba1-105">Example:</span></span>

<span data-ttu-id="53ba1-106">Get-poštansko sanduče | FT DefaultPublicFolderMailbox, EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="53ba1-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="53ba1-107">Set-poštansko sanduče-problem korisnik \<-DefaultPublicFolderMailbox vrednost iz prethodne komande></span><span class="sxs-lookup"><span data-stu-id="53ba1-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="53ba1-108">Sačekajte najmanje jedan sat da bi promena stupila na snagu.</span><span class="sxs-lookup"><span data-stu-id="53ba1-108">Wait at least one hour for the change to take effect.</span></span>
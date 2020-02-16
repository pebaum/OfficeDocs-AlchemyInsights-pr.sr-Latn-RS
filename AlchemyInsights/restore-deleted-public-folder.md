---
title: Vraćanje izbrisane javne fascikle u prethodno stanje
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
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063736"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="7c16c-102">Vraćanje izbrisane javne fascikle u prethodno stanje</span><span class="sxs-lookup"><span data-stu-id="7c16c-102">Restore a deleted public folder</span></span>

<span data-ttu-id="7c16c-103">**Da biste izbrisane stavke vratili u prethodno stanje iz javne fascikle**:</span><span class="sxs-lookup"><span data-stu-id="7c16c-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="7c16c-104">Vidi [ne možete spasiti izbrisane stavke iz javne fascikle koja ne pripada pošti u programu Outlook 2016](https://aka.ms/pfrec).</span><span class="sxs-lookup"><span data-stu-id="7c16c-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="7c16c-105">**Da biste vratili izbrisanu javnu fasciklu (bilo koji tip)**:</span><span class="sxs-lookup"><span data-stu-id="7c16c-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="7c16c-106">Koristite sledeću komandu "EXO PowerShell":</span><span class="sxs-lookup"><span data-stu-id="7c16c-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="7c16c-107">Sintaksa:</span><span class="sxs-lookup"><span data-stu-id="7c16c-107">Syntax:</span></span>

    ><span data-ttu-id="7c16c-108">$pf = get-Publicfascikla \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recse |? {$_. Ime-oko "\<name_of_deleted_public_Folder"}; Set-Publicfascikla $pf. putanja do lične \<putanje gde će fascikla biti vraćena u prethodno stanje></span><span class="sxs-lookup"><span data-stu-id="7c16c-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored></span></span>

    <span data-ttu-id="7c16c-109">Primer: sledeća komanda će vratiti Subfolder1 u prethodno stanje i postaviti je pod \Nadređeni T1:</span><span class="sxs-lookup"><span data-stu-id="7c16c-109">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    ><span data-ttu-id="7c16c-110">$pf = get-Publicfascikla \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recse |? {$_. Ime-Subfolder1 "}; Set-Publicfascikla $pf. identitet-putanja \Nadređeni T1</span><span class="sxs-lookup"><span data-stu-id="7c16c-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1</span></span>

<span data-ttu-id="7c16c-111">Više detalja potražite u [obnovi izbrisane javne fascikle](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) .</span><span class="sxs-lookup"><span data-stu-id="7c16c-111">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>

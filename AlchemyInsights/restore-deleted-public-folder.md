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
ms.openlocfilehash: cd85dd3c0eb14f6e02ac4f912e733468403387aa
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158538"
---
# <a name="restore-a-deleted-public-folder"></a>Vraćanje izbrisane javne fascikle u prethodno stanje

**Da biste izbrisane stavke vratili u prethodno stanje iz javne fascikle**:

- Vidi [ne možete spasiti izbrisane stavke iz javne fascikle koja ne pripada pošti u programu Outlook 2016](https://aka.ms/pfrec).
 
**Da biste vratili izbrisanu javnu fasciklu (bilo koji tip)**: 

- Koristite sledeću komandu "EXO PowerShell":

    Sintaksa:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Primer: sledeća komanda će vratiti Subfolder1 u prethodno stanje i postaviti je pod \Nadređeni T1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Više detalja potražite u [obnovi izbrisane javne fascikle](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) .

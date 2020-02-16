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
# <a name="restore-a-deleted-public-folder"></a>Vraćanje izbrisane javne fascikle u prethodno stanje

**Da biste izbrisane stavke vratili u prethodno stanje iz javne fascikle**:

- Vidi [ne možete spasiti izbrisane stavke iz javne fascikle koja ne pripada pošti u programu Outlook 2016](https://aka.ms/pfrec).
 
**Da biste vratili izbrisanu javnu fasciklu (bilo koji tip)**: 

- Koristite sledeću komandu "EXO PowerShell":

    Sintaksa:

    >$pf = get-Publicfascikla \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recse |? {$_. Ime-oko "\<name_of_deleted_public_Folder"}; Set-Publicfascikla $pf. putanja do lične \<putanje gde će fascikla biti vraćena u prethodno stanje>

    Primer: sledeća komanda će vratiti Subfolder1 u prethodno stanje i postaviti je pod \Nadređeni T1:

    >$pf = get-Publicfascikla \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-Recse |? {$_. Ime-Subfolder1 "}; Set-Publicfascikla $pf. identitet-putanja \Nadređeni T1

Više detalja potražite u [obnovi izbrisane javne fascikle](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) .

---
title: Za grupu za migraciju javnih fascikli sa statusom Dovršavagrešaka status
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
- "3532"
ms.openlocfilehash: 4243cdf0170fed1eadac6560d2a04e1a861c63e5
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/15/2020
ms.locfileid: "42043615"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Za grupu za migraciju javnih fascikli sa statusom Dovršavagrešaka status

Koristite sledeće korake da biste dovršili ovu grupu, preskakanje velikih/loših stavki: 
1. Odobri preskočene stavke u grupi za migraciju:

    Set-Seljko \<prezime>-ApproveSkippedItems 
2. Koristite sledeću komandu da biste odobrili preskočene stavke na zahtevima za migraciju koji su "sinhronizovani", ali nisu dovršeni:

    $pf = get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics-IncludeReport; Uvodna reč ($i u $pf) {IF ($i. Largeartiks-gt-narednik 0-ili $i. Badartikon-gt 0) {set-PublicFolderMailboxMigrationRequest $i. identitet. identifikacione-SkippedItemApprovalTime $ ([DateTime]:: UtcNow)}}
3. Grupa za migraciju i zahtevi treba da se nastave i završe za nekoliko minuta.


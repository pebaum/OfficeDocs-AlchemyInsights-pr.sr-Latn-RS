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
ms.openlocfilehash: 739e9d91f90e4c0374814d199e4372eb5625553a
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158633"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Za grupu za migraciju javnih fascikli sa statusom Dovršavagrešaka status

Koristite sledeće korake da biste dovršili ovu grupu, preskakanje velikih/loših stavki: 
1. Odobri preskočene stavke u grupi za migraciju:

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. Koristite sledeću komandu da biste odobrili preskočene stavke na zahtevima za migraciju koji su "sinhronizovani", ali nisu dovršeni:

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. Grupa za migraciju i zahtevi treba da se nastave i završe za nekoliko minuta.


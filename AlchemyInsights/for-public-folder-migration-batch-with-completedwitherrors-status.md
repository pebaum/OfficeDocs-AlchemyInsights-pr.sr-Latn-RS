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
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="febb0-102">Za grupu za migraciju javnih fascikli sa statusom Dovršavagrešaka status</span><span class="sxs-lookup"><span data-stu-id="febb0-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="febb0-103">Koristite sledeće korake da biste dovršili ovu grupu, preskakanje velikih/loših stavki:</span><span class="sxs-lookup"><span data-stu-id="febb0-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="febb0-104">Odobri preskočene stavke u grupi za migraciju:</span><span class="sxs-lookup"><span data-stu-id="febb0-104">Approve the skipped items on migration batch:</span></span>

    <span data-ttu-id="febb0-105">Set-Seljko \<prezime>-ApproveSkippedItems</span><span class="sxs-lookup"><span data-stu-id="febb0-105">Set-MigrationBatch \<batchname> -ApproveSkippedItems</span></span> 
2. <span data-ttu-id="febb0-106">Koristite sledeću komandu da biste odobrili preskočene stavke na zahtevima za migraciju koji su "sinhronizovani", ali nisu dovršeni:</span><span class="sxs-lookup"><span data-stu-id="febb0-106">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    <span data-ttu-id="febb0-107">$pf = get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics-IncludeReport; Uvodna reč ($i u $pf) {IF ($i. Largeartiks-gt-narednik 0-ili $i. Badartikon-gt 0) {set-PublicFolderMailboxMigrationRequest $i. identitet. identifikacione-SkippedItemApprovalTime $ ([DateTime]:: UtcNow)}}</span><span class="sxs-lookup"><span data-stu-id="febb0-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}</span></span>
3. <span data-ttu-id="febb0-108">Grupa za migraciju i zahtevi treba da se nastave i završe za nekoliko minuta.</span><span class="sxs-lookup"><span data-stu-id="febb0-108">The migration batch and requests should resume and complete in a few minutes.</span></span>


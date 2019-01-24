---
title: 902 (greške pri sinhronizaciji zbog duplirane objekte)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f8db233167a5e2b2ef7290438b8e6d92d0dccb1e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/24/2019
ms.locfileid: "29488069"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="75cd3-102">Greške pri sinhronizaciji zbog duplirane objekte</span><span class="sxs-lookup"><span data-stu-id="75cd3-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="75cd3-103">Možete dobiti neku od sledećih poruka o grešci kada se završi sinhronizacija direktorijuma:</span><span class="sxs-lookup"><span data-stu-id="75cd3-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="75cd3-104">Nije moguće ažurirati ovaj objekat u Microsoft Online Services jer sledeće atribute povezane sa ovom objektu imati vrednosti koje možda već povezan sa drugim objektom u vaš lokalni imenik.</span><span class="sxs-lookup"><span data-stu-id="75cd3-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="75cd3-105">Sinhronizovani objekat sa iste adrese proxy već postoji u Microsoft Online Services kataloga.</span><span class="sxs-lookup"><span data-stu-id="75cd3-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="75cd3-106">Nije moguće ažurirati ovaj objekat jer sledeće atribute povezane sa ovom objektu imati vrednosti koje možda već povezan sa drugim objektom u svoje usluge lokalnim direktorijuma: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="75cd3-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="75cd3-107">Za identifikovanje i rešavanje problema, preuzimanje i pokretanje [IdFix DirSync greška oporavka alat](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="75cd3-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="75cd3-108">Za više informacija, pogledajte [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="75cd3-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  


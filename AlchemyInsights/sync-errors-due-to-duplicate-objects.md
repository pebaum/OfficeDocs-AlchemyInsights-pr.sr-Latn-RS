---
title: 902 (greške pri sinhronizaciji zbog duplirane objekte)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: ce7eeb07cfde16e6d6856a9369c042dcf4f05b63
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/13/2019
ms.locfileid: "31859118"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="abc39-102">Greške pri sinhronizaciji zbog duplirane objekte</span><span class="sxs-lookup"><span data-stu-id="abc39-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="abc39-103">Možete dobiti neku od sledećih poruka o grešci kada se završi sinhronizacija direktorijuma:</span><span class="sxs-lookup"><span data-stu-id="abc39-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>

- <span data-ttu-id="abc39-104">Nije moguće ažurirati ovaj objekat u Microsoft Online Services jer sledeće atribute povezane sa ovom objektu imati vrednosti koje možda već povezan sa drugim objektom u vaš lokalni imenik.</span><span class="sxs-lookup"><span data-stu-id="abc39-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="abc39-105">Sinhronizovani objekat sa iste adrese proxy već postoji u Microsoft Online Services kataloga.</span><span class="sxs-lookup"><span data-stu-id="abc39-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="abc39-106">Nije moguće ažurirati ovaj objekat jer sledeće atribute povezane sa ovom objektu imati vrednosti koje možda već povezan sa drugim objektom u svoje usluge lokalnim direktorijuma: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="abc39-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="abc39-107">Za identifikovanje i rešavanje problema, preuzimanje i pokretanje [IdFix DirSync greška oporavka alat](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="abc39-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="abc39-108">Za više informacija, pogledajte [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="abc39-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>

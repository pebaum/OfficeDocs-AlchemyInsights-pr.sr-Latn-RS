---
title: Uputstva za skrivanje/otkrivanje grupe iz liste adresa
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 61ba34e6d554831da712a92401f26fabb02c26b7
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908358"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>Sakrij Microsoft 365 grupu sa spiska adresa (GAL)

Da biste sakrili Microsoft 365 grupu sa lista adresa (GAL) Exchange klijenata (kao što su Outlook ili OWOVA), koristite sledeću komandu u EXO Shell:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Da biste sakrili Microsoft 365 grupu koja je vidljiva za Exchange klijente, koristite sledeću komandu u EXO Shell:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`


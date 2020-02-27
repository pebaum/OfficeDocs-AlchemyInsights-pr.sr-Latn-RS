---
title: Kreiranje e-poruke uhvati sve
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286305"
---
# <a name="create-an-email-catch-all"></a>Kreiranje e-poruke uhvati sve

Korišćenje hvataka sve je snažno obeshrabrilo. Bolje je vratiti se pošiljaocu i pustiti pošiljaoce da znaju da njihova poruka nije mogla da se isporuči kao adresirana kako bi mogla da preduzmu korake. Takođe možete ograničiti nadgledani poštansko sanduče da biste hvatali i ranije važeće e-adrese. 

Svaki od njih može dobiti dobar posao bezvredne pošte i na kraju će popuniti ako ne bude pažljivo nadgledan. (Dobijaju se ograničenja.) 

Ako odlučite da nastavite, sledite ove korake:

1. Kreiranje dinamičke grupe za distribuciju & sadrži "sve tipove primalaca".

2. Kreirajte namensko poštansko sanduče za hvatanje e-poruka, na primer catchall@domain.com.

3. Za određeni domen podesite DomainType na "Internalreleu". Ako kasnije uklonite "uhvati sve", uverite se da ste ponovo podesili domen na pouzdane.

4. Kreirajte pravilo transporta za tok pošte na sledeći način:

    - Ako je pošiljalac "izvan organizacije"
    - Preusmeri poruku na Catchall@domain.com
    - Osim ako je primalac član allusers@domain.com (grupa za distribuciju sadrži sve članove)
    - Uverite se da ste proverili da li su novi poštanski sandučići dodati u dinamičku grupu distribucije

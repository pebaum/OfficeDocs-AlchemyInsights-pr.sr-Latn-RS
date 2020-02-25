---
title: Aktivni direktorijum ne sinhronizuje
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001688"
- "3754"
ms.openlocfilehash: 3abad160ab28922685d235a1fa546105e31757fb
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265270"
---
# <a name="active-directory-not-syncing"></a>Aktivni direktorijum ne sinhronizuje

Ako dobijate greške pri sinhronizaciji, kao što je "bez nedavne sinhronizacije" ili ako primetite da status sinhronizacije direktorijuma u Office admin portalu kaže, "poslednji put sinhronizovano pre više od 3 dana," moguće je da AADConnect ima neispravne postavke ili nedovoljno dozvole za izvršavanje sinhronizacije.  

Ponovno instaliranje AADConnect pomoću ekspresne postavke može brzo da reši problem:

1. [Preuzmite najnoviju verziju AADConnect-a](https://go.microsoft.com/fwlink/?LinkId=615771).

2. [Sledite uputstva za ekspresnu instalaciju](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).

Za više informacija o nalozima za uslugu AADConnect pogledajte odeljak [Azure Connect za povezivanje: nalozi i dozvole](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).

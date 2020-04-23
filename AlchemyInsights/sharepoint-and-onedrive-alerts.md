---
title: Kašnjenja u dobijanju upozorenja na SharePoint i OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: fb7ab6e8139c46d89b1cae1ee0ab9b9a601c8b64
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742015"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a>Kašnjenja u dobijanju upozorenja na SharePoint i OneDrive

- Prvo proverite fasciklu "Neželjena pošta" ili "bezvredna pošta" u e-poruci.
- Ako **su sva obaveštenja iz više datoteka ili biblioteka odložena**, posetite [kontrolnu tablu za uslugu](https://portal.office.com/adminportal/home?ref=/servicehealth) da biste proverili da li postoje neki savetnici/incidenti koji se mogu imati sa SharePoint ili Exchange serverom. Moguće je da je to problem sa mogućnošću SharePoint upozorenja ili kašnjenja u e-porukama putem Exchange servera. Takođe obratite pažnju na to da li se isporučuje druga e-pošta – ako to nije moguće, problem će verovatno imati kašnjenja u razmeni.
- Ako **pojedinačna uzbuna iz određene datoteke ili biblioteke nije isporučena**, pokušajte da je izbrišete i ponovo kreirate. Pogledajte odeljak [Upravljanje, prikazivanje ili brisanje SharePoint obaveštenja](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) da biste ponovo kreirali obaveštenje.

> [!NOTE]
> - Nije moguće poslati obaveštenja grupi distribucije. Podržane su samo bezbednosne i O365 grupe.
> - Ne možete da prilagodite predloške e-pošte obaveštenja. Morate da koristite Microsoft flow ili tok posla SharePoint Designer da biste ih ostvarili.

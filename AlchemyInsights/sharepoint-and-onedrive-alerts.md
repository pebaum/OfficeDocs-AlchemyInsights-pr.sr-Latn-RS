---
title: Nije moguće primati upozorenja na SharePoint i OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/25/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 80423791ad558fc414d50608c73f823036432e14
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205551"
---
# <a name="not-receiving-sharepoint-and-onedrive-alerts"></a>Nije moguće primati upozorenja na SharePoint i OneDrive

Prvo proverite fasciklu "Neželjena pošta" ili "bezvredna pošta" u e-poruci.

Zatim utvrdite da li **se sva obaveštenja ne isporučuju** ili ako **pojedinačna uzbuna** iz određene datoteke ili biblioteke nije isporučena.

- Ako **se sva obaveštenja iz više datoteka ili biblioteka ne isporučuju**, posetite [kontrolnu tablu za uslugu](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) da biste proverili da li postoje neki savetnici/incidenti koji se mogu imati sa SharePoint ili Exchange serverom. Moguće je da je to problem sa mogućnošću SharePoint upozorenja ili kašnjenja u e-porukama putem Exchange servera. Takođe obratite pažnju na to da li se isporučuje druga e-pošta – ako to nije moguće, problem će verovatno imati kašnjenja u razmeni.
- Ako **pojedinačna uzbuna iz određene datoteke ili biblioteke nije isporučena**, pokušajte da je izbrišete i ponovo kreirate. Pogledajte odeljak [Upravljanje, prikazivanje ili brisanje SharePoint obaveštenja](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) da biste ponovo kreirali obaveštenje.

> [!NOTE]
> - Nije moguće poslati obaveštenja grupi distribucije. Podržane su samo bezbednosne i O365 grupe.
> - Ne možete da prilagodite predloške e-pošte obaveštenja. Morate da koristite Microsoft flow ili tok posla SharePoint Designer da biste ih ostvarili.

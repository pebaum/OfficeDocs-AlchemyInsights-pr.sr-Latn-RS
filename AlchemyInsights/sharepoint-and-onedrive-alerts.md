---
title: Kašnjenja u dobijanju upozorenja na SharePoint i OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 02/04/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 0bc9f614047e06e8654a9b3ff64e87427f33139f
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 02/04/2020
ms.locfileid: "41771229"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="0bc69-102">Kašnjenja u dobijanju upozorenja na SharePoint i OneDrive</span><span class="sxs-lookup"><span data-stu-id="0bc69-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="0bc69-103">Prvo proverite fasciklu "Neželjena pošta" ili "bezvredna pošta" u e-poruci.</span><span class="sxs-lookup"><span data-stu-id="0bc69-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="0bc69-104">Ako **su sva obaveštenja iz više datoteka ili biblioteka odložena**, posetite [kontrolnu tablu za uslugu](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) da biste proverili da li postoje neki savetnici/incidenti koji se mogu imati sa SharePoint ili Exchange serverom.</span><span class="sxs-lookup"><span data-stu-id="0bc69-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="0bc69-105">Moguće je da je to problem sa mogućnošću SharePoint upozorenja ili kašnjenja u e-porukama putem Exchange servera.</span><span class="sxs-lookup"><span data-stu-id="0bc69-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="0bc69-106">Takođe obratite pažnju na to da li se isporučuje druga e-pošta – ako to nije moguće, problem će verovatno imati kašnjenja u razmeni.</span><span class="sxs-lookup"><span data-stu-id="0bc69-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="0bc69-107">Ako **pojedinačna uzbuna iz određene datoteke ili biblioteke nije isporučena**, pokušajte da je izbrišete i ponovo kreirate.</span><span class="sxs-lookup"><span data-stu-id="0bc69-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="0bc69-108">Pogledajte odeljak [Upravljanje, prikazivanje ili brisanje SharePoint obaveštenja](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) da biste ponovo kreirali obaveštenje.</span><span class="sxs-lookup"><span data-stu-id="0bc69-108">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="0bc69-109">Nije moguće poslati obaveštenja grupi distribucije.</span><span class="sxs-lookup"><span data-stu-id="0bc69-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="0bc69-110">Podržane su samo bezbednosne i O365 grupe.</span><span class="sxs-lookup"><span data-stu-id="0bc69-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="0bc69-111">Ne možete da prilagodite predloške e-pošte obaveštenja.</span><span class="sxs-lookup"><span data-stu-id="0bc69-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="0bc69-112">Morate da koristite Microsoft flow ili tok posla SharePoint Designer da biste ih ostvarili.</span><span class="sxs-lookup"><span data-stu-id="0bc69-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>

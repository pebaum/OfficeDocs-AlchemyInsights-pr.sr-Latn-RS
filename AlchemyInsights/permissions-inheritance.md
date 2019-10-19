---
title: Nasleđivanje dozvola
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 8/7/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bb5c440a-ca70-4dc6-b517-688e80551101
ms.openlocfilehash: 6322ca12902be2612f65b6388a650300b257a95e
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36554972"
---
# <a name="how-permissions-inheritance-works-in-sharepoint"></a><span data-ttu-id="12ae9-102">Kako funkcioniše nasleđivanje dozvola u sistemu SharePoint?</span><span class="sxs-lookup"><span data-stu-id="12ae9-102">How permissions inheritance works in SharePoint</span></span>

<span data-ttu-id="12ae9-103">Podrazumevano, dozvole u sistemu SharePoint su nasleđene od višeg u hijerarhiji.</span><span class="sxs-lookup"><span data-stu-id="12ae9-103">By default, permissions in SharePoint are inherited from higher up in the hierarchy.</span></span> <span data-ttu-id="12ae9-104">Zato datoteka nasleđuje dozvole iz fascikle koja nasleđuje dozvole iz biblioteke, što nasleđuje dozvole od lokacije, što nasleđuje dozvole iz kolekcije lokacija.</span><span class="sxs-lookup"><span data-stu-id="12ae9-104">So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site, which inherits its permissions from the site collection.</span></span>
  
<span data-ttu-id="12ae9-105">Informacije o uklanjanju jedinstvenih dozvola i vraćanju nasleđivanja potražite [u članku uređivanje dozvola za listu ili biblioteku](https://go.microsoft.com/fwlink/?linkid=869946).</span><span class="sxs-lookup"><span data-stu-id="12ae9-105">For info about removing unique permissions and restoring inheritance, see [Edit and manage permissions for a list or library](https://go.microsoft.com/fwlink/?linkid=869946).</span></span>
  


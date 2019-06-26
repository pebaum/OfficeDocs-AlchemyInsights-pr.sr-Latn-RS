---
title: Rešavanje problema „Otvori pomoću Explorera“ u sistemu SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 5/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 5ad2f1f2-9650-4eb0-b4fa-2f52a09f535a
ms.openlocfilehash: fcaca189741bd68878b1dcfab879e6e0f64e6794
ms.sourcegitcommit: 204c8fadd59a597a18ebde24b3c63fbb656ec1b6
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/25/2019
ms.locfileid: "35223654"
---
# <a name="troubleshoot-open-with-explorer-issues-in-sharepoint-online"></a><span data-ttu-id="4822c-102">Rešavanje problema „Otvori pomoću Explorera“ u sistemu Sharepoint Online</span><span class="sxs-lookup"><span data-stu-id="4822c-102">Troubleshoot “Open with Explorer” issues in Sharepoint Online</span></span>

<span data-ttu-id="4822c-103">Komanda „Otvori pomoću Explorera“ otvara lokalnu instancu Windows Explorera koja prikazuje strukturu fascikli na serveru na kom se nalazi SharePoint sajt.</span><span class="sxs-lookup"><span data-stu-id="4822c-103">The Open with Explorer command opens a local instance of Windows Explorer that displays the folder structure on the server that hosts the SharePoint site.</span></span> <span data-ttu-id="4822c-104">Imajući to u vidu, preporučujemo [sinhronizovanje SharePoint datoteka sa novim One Drive klijentom za sinhronizaciju](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> koji pruža [Datoteke na zahtev](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) zato što vam daje lokalni pristup datotekama i nudi najbolje performanse.</span><span class="sxs-lookup"><span data-stu-id="4822c-104">This being said , we recommend [syncing SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) because it provides local access to your files and offers the best performance.</span></span>


<span data-ttu-id="4822c-105">Ako ste odabrali da koristite prikaz istraživača umesto da koristite novi klijent za sinhronizaciju, obavezno pratite korake i najbolje prakse iz dolenavedenog članka.</span><span class="sxs-lookup"><span data-stu-id="4822c-105">If you chose to use explorer view instead of using the new sync client, ensure you follow the steps and best practices in the articles below.</span></span>

- [<span data-ttu-id="4822c-106">Kako se komanda „Otvori u istraživaču“ koristi za rešavanje problema u usluzi SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="4822c-106">How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online</span></span>](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4)

- [<span data-ttu-id="4822c-107">Kopiranje ili premeštanje datoteka biblioteke korišćenjem opcije „Otvori pomoću programa Explorer“</span><span class="sxs-lookup"><span data-stu-id="4822c-107">Copy or move library files by using Open with Explorer</span></span>](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2)

<span data-ttu-id="4822c-108">Napomena: Dugme „Otvori u istraživaču“ se ne prikazuje u novom dizajnu biblioteke.</span><span class="sxs-lookup"><span data-stu-id="4822c-108">Note:  The Open with Explorer button doesn't appear in the new library experience.</span></span> <span data-ttu-id="4822c-109">Kliknite na padajući meni Prikaz u gornjem desnom uglu (ime padajućeg menija sa menja u zavisnosti od trenutnog prikaza), a zatim izaberite Prikaz u istraživaču datoteka.</span><span class="sxs-lookup"><span data-stu-id="4822c-109">Click the View drop-down in the upper right (the name of the drop-down changes depending on your current view), and then click View in File Explorer.</span></span>

 <span data-ttu-id="4822c-110">Komanda „Otvori u istraživaču“ u sistemu SharePoint koristi ActiveX kontrole, tako da je podržana samo u pregledaču Internet Explorer 10 ili 11.</span><span class="sxs-lookup"><span data-stu-id="4822c-110">SharePoint Open with Explorer uses ActiveX controls, so it's only supported in Internet Explorer 10 or 11.</span></span> <span data-ttu-id="4822c-111">Otvaranje u istraživaču ne funkcioniše u operativnom sistemu Windows koji koristi pregledače Microsoft Edge, Google Chrome, Mozilla Firefox, kao i na Mac platformi.</span><span class="sxs-lookup"><span data-stu-id="4822c-111">Open with Explorer doesn't work in Windows with Microsoft Edge, Google Chrome, Mozilla Firefox, or on the Mac platform.</span></span> <span data-ttu-id="4822c-112">Zato je opcija Prikaz u istraživaču možda zasivljena.</span><span class="sxs-lookup"><span data-stu-id="4822c-112">Due to this reason, the Explorer View option may be grayed out.</span></span>

- <span data-ttu-id="4822c-113">[Zašto su dugmad na SharePoint traci nedostupna ili zasivljena](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span><span class="sxs-lookup"><span data-stu-id="4822c-113">[Why SharePoint ribbon buttons are unavailable or grayed out](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span></span>
  


---
title: Teams klijent otkazuje?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030674"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="563a1-102">Teams klijent otkazuje?</span><span class="sxs-lookup"><span data-stu-id="563a1-102">Teams client crashing?</span></span>

<span data-ttu-id="563a1-103">Ukoliko Teams klijent otkazuje, pokušajte sledeće:</span><span class="sxs-lookup"><span data-stu-id="563a1-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="563a1-104">Ako koristite Teams aplikaciju za stone računare, [ uverite se da je aplikacija potpuno ažurirana](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="563a1-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="563a1-105">Proverite da li su pristupačne sve [URL Office 365 adrese i svi rasponi adresa](https://docs.microsoft.com/microsoftteams/connectivity-issues).</span><span class="sxs-lookup"><span data-stu-id="563a1-105">Make sure all the [Office 365 URL's and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="563a1-106">Prijavite se pomoću administratorskog naloga i proverite [Kontrolnu tablu za ispravnost usluge](https://docs.microsoft.com/office365/enterprise/view-service-health)da biste potvrdili da ne postoji prekid ili degradacija usluge. </span><span class="sxs-lookup"><span data-stu-id="563a1-106">Log in with your admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

 - <span data-ttu-id="563a1-107">Kao poslednji korak, možete da pokušate da obrišete keš Teams klijenta:</span><span class="sxs-lookup"><span data-stu-id="563a1-107">As a last step, you can attempt to clear your Teams client cache:</span></span>

    1.  <span data-ttu-id="563a1-108">Potpuno izađite iz Microsoft Teams klijent za radnu površinu.</span><span class="sxs-lookup"><span data-stu-id="563a1-108">Fully exit the Microsoft Teams desktop client.</span></span> <span data-ttu-id="563a1-109">Možete da kliknete desnim tasterom miša na **Teams** iz ležišta za ikone i kliknete **Zatvorite**ili pokrenete Upravljač zadacima i potpuno ubijete proces.</span><span class="sxs-lookup"><span data-stu-id="563a1-109">You can right-click **Teams** from the Icon Tray and click **Quit**, or run Task Manager and fully kill the process.</span></span>

    2.  <span data-ttu-id="563a1-110">Idite u Istraživač datoteka i otkucajte %appdata%\Microsoft\teams.</span><span class="sxs-lookup"><span data-stu-id="563a1-110">Go to File Explorer, and type in %appdata%\Microsoft\teams.</span></span>

    3.  <span data-ttu-id="563a1-111">Kada stignete u direktorijum, videćete neke od sledećih fascikli:</span><span class="sxs-lookup"><span data-stu-id="563a1-111">Once in the directory, you'll see a few of the following folders:</span></span>

         - <span data-ttu-id="563a1-112">U okviru **Keš aplikacije**, idite na Keš i izbrišite bilo koju datoteku na lokaciji keširanja: %appdata%\Microsoft\teams\application cache\cache.</span><span class="sxs-lookup"><span data-stu-id="563a1-112">From within **Application Cache**, go to Cache and delete any of the files in the Cache location:  %appdata%\Microsoft\teams\application cache\cache.</span></span>

        - <span data-ttu-id="563a1-113">U okviru stavke**Blob_storage**, izbrišite sve datoteke: %appdata%\Microsoft\teams\blob_storage.</span><span class="sxs-lookup"><span data-stu-id="563a1-113">From within **Blob_storage**, delete all files: %appdata%\Microsoft\teams\blob_storage.</span></span>

        - <span data-ttu-id="563a1-114">U okviru stavke**Keš**, izbrišite sve datoteke: %appdata%\Microsoft\teams\Cache.</span><span class="sxs-lookup"><span data-stu-id="563a1-114">From within **Cache**, delete all files: %appdata%\Microsoft\teams\Cache.</span></span>

        - <span data-ttu-id="563a1-115">U okviru stavke**databases**, izbrišite sve datoteke: %appdata%\Microsoft\teams\databases.</span><span class="sxs-lookup"><span data-stu-id="563a1-115">From within **databases**, delete all files: %appdata%\Microsoft\teams\databases.</span></span>

        - <span data-ttu-id="563a1-116">U okviru stavke**GPUCache**, izbrišite sve datoteke: %appdata%\Microsoft\teams\GPUcache.</span><span class="sxs-lookup"><span data-stu-id="563a1-116">From within **GPUCache**, delete all files: %appdata%\Microsoft\teams\GPUcache.</span></span>

        - <span data-ttu-id="563a1-117">U okviru **IndexedDB**, izbrišite .db datoteku: %appdata%\Microsoft\teams\IndexedDB.</span><span class="sxs-lookup"><span data-stu-id="563a1-117">From within **IndexedDB**, delete the .db file: %appdata%\Microsoft\teams\IndexedDB.</span></span>

        - <span data-ttu-id="563a1-118">U okviru stavke**Lokalno skladište**, izbrišite sve datoteke: %appdata%\Microsoft\teams\Local Storage.</span><span class="sxs-lookup"><span data-stu-id="563a1-118">From within **Local Storage**, delete all files: %appdata%\Microsoft\teams\Local Storage.</span></span>

        - <span data-ttu-id="563a1-119">Na kraju, u okviru **tmp**izbrišite bilo koju datoteku: %appdata%\Microsoft\teams\tmp.</span><span class="sxs-lookup"><span data-stu-id="563a1-119">Lastly, from within **tmp**, delete any file: %appdata%\Microsoft\teams\tmp.</span></span>

    4. <span data-ttu-id="563a1-120">Ponovo pokreni Teams klijent.</span><span class="sxs-lookup"><span data-stu-id="563a1-120">Restart your Teams client.</span></span>

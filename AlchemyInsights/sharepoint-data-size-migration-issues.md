---
title: Problemi prilikom migriranja podataka u SharePoint online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "1885"
ms.openlocfilehash: b53a98480bab48497274c7358f7e606caa477f5a
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931708"
---
# <a name="issues-while-migrating-data-to-sharepoint-online"></a><span data-ttu-id="f1ad4-102">Problemi prilikom migriranja podataka u SharePoint online</span><span class="sxs-lookup"><span data-stu-id="f1ad4-102">Issues while migrating data to SharePoint Online</span></span>

<span data-ttu-id="f1ad4-103">**Važno**: mnogi korisnici usluge SharePoint Online i OneDrive pokreću poslovne aplikacije u odnosu na uslugu koja se pokreće u pozadini.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="f1ad4-104">Ovo uključuje migraciju sadržaja, sprečavanje gubitka podataka (DLP) i rešenja za rezervno kopiranje.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="f1ad4-105">U ovim vremenima bez presedana preduzimamo korake da bismo obezbedili da SharePoint Online i usluge OneDrive budu veoma dostupne i pouzdane za korisnike koji zavise od usluge u udaljenim radnim scenarijima.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="f1ad4-106">U cilju podrške ovom cilju, Implementirao sam strožije limite na aplikacije u pozadini (migracioni, DLP i Backup rešenja) tokom dana u danima u sedmici.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="f1ad4-107">Trebalo bi da očekujete da će ove aplikacije ostvariti veoma ograničenu propusnost tokom ovih vremena.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="f1ad4-108">Međutim, tokom večeri i vikenda u regionu, usluga će biti spremna da obradi znatno veći obim zahteva iz aplikacija u pozadini.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="f1ad4-109">**Migriranje preko 100TB podataka**</span><span class="sxs-lookup"><span data-stu-id="f1ad4-109">**Migrating over 100TB of data**</span></span>

<span data-ttu-id="f1ad4-110">Čini se da migrirate preko 100TB podataka na SharePoint online.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-110">It appears you are migrating over 100TB of data to SharePoint Online.</span></span> <span data-ttu-id="f1ad4-111">Pratite dolenavedene korake da bismo vam mogli pomoći u najkraćem mogućem roku.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="f1ad4-112">Izaberite **novi zahtev za servis**, a zatim **novi zahtev za servis**.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-112">Select **New Service Request**, and then **New Service Request**.</span></span> 
2. <span data-ttu-id="f1ad4-113">Ostavite naslov i opis kao **SharePoint migraciju preko 100TB**.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-113">Leave the title and description as **SharePoint migration over 100TB**.</span></span>
3. <span data-ttu-id="f1ad4-114">Kada se karta prosledi, ažurirajte je sledećim informacijama:</span><span class="sxs-lookup"><span data-stu-id="f1ad4-114">Once the ticket has been submitted, please update it with the following information:</span></span> 

    - <span data-ttu-id="f1ad4-115">Procenjena veličina migracije.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-115">Estimated size of your migration.</span></span>
    - <span data-ttu-id="f1ad4-116">Procena kada biste želeli da započnete i dovršite migraciju.</span><span class="sxs-lookup"><span data-stu-id="f1ad4-116">An estimate of when you would like to start and complete your migration.</span></span>
    - <span data-ttu-id="f1ad4-117">Opišite mesto na koje želite da migrirate sadržaj, kao što je SharePoint Server, box, Gdisk, deljeni resursi datoteka itd...</span><span class="sxs-lookup"><span data-stu-id="f1ad4-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>


  


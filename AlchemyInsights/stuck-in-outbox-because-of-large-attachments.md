---
title: Zaglavljena u otpremnom poštanskom sandučetu zbog velikih priloga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441319"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="1c1b9-102">Popravljanje poruka koje su zaglavljena u otpremnom poštanskom sandučetu</span><span class="sxs-lookup"><span data-stu-id="1c1b9-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="1c1b9-103">Preporučujemo da počnete pokretanjem scenarija "Imam problema sa [slanjem, prijemom ili pronalaženjem e-poruka"](https://aka.ms/SaRA-OutlookSendReceive) iz alatke [Microsoft pomoćnik za podršku i oporavak](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="1c1b9-103">We recommend that you start by running the scenario ["I’m having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="1c1b9-104">Kada se poruka zaglavila u otpremnom poštanskom sandučetu, najverovatniji uzroci su:</span><span class="sxs-lookup"><span data-stu-id="1c1b9-104">When a message gets stuck in your Outbox, the most likely causes are:</span></span>
- <span data-ttu-id="1c1b9-105">Velikih priloga.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-105">Large attachments.</span></span>
- <span data-ttu-id="1c1b9-106">Opcija " **Pošalji odmah" kada veza** nije omogućena.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-106">The **Send immediately when connected** option is not enabled.</span></span>

<span data-ttu-id="1c1b9-107">Da biste uklonili velike priloge:</span><span class="sxs-lookup"><span data-stu-id="1c1b9-107">To remove large attachments:</span></span> 

1. <span data-ttu-id="1c1b9-108">U programu Outlook izaberite opciju **Pošalji/primi** > **van mreže**.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-108">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="1c1b9-109">U oknu za navigaciju izaberite stavku **Otpremno poštansko sanduče**.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-109">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="1c1b9-110">Odavde možete da:</span><span class="sxs-lookup"><span data-stu-id="1c1b9-110">From here, you can:</span></span> 
    - <span data-ttu-id="1c1b9-111">Izbrišite poruku (izaberite je, a zatim izaberite **Izbriši**).</span><span class="sxs-lookup"><span data-stu-id="1c1b9-111">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="1c1b9-112">Prevucite poruku u fasciklu "radne verzije", dvaput kliknite da biste je otvorili, a zatim uklonite prilog izaberite ga, a zatim kliknite na dugme " **Izbriši**".</span><span class="sxs-lookup"><span data-stu-id="1c1b9-112">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="1c1b9-113">Ako dobijete grešku u kojoj piše da Outlook pokušava da prenese poruku, zatvorite Outlook.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-113">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="1c1b9-114">Za izlazak može potrajati nekoliko trenutaka.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-114">It may take a few moments to exit.</span></span> <span data-ttu-id="1c1b9-115">Ako se Outlook ne zatvori, pritisnite tastere CTRL + ALT + DELETE i izaberite stavku **Pokretanje upravljača zadacima**.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-115">If Outlook doesn’t close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="1c1b9-116">U upravljaču zadacima izaberite karticu **procesi** , pomerite se nadole do stavke Outlook. exe i izaberite stavku **kraj procesa**.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-116">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="1c1b9-117">Nakon što se Outlook zatvori, ponovo ga pokrenite i ponovite korake 2 i 3.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-117">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="1c1b9-118">Kada uklonite prilog, kliknite na dugme " **Pošalji/primi** > **rad van mreže** " da biste nastavili sa radom na mreži.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-118">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="1c1b9-119">Poruke se takođe zaglave u otpremnom poštanskom sandučetu kada kliknete na dugme " **Pošalji**", ali niste povezani.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-119">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="1c1b9-120">Kliknite na dugme " **Pošalji/primi** " i pogledajte dugme " **radi van mreže** ".</span><span class="sxs-lookup"><span data-stu-id="1c1b9-120">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="1c1b9-121">Ako je plava, veza je prekinuta.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-121">If it's blue, you're disconnected.</span></span> <span data-ttu-id="1c1b9-122">Izaberite ga da biste se povezali (dugme postaje belo) i kliknite na dugme " **Pošalji sve**".</span><span class="sxs-lookup"><span data-stu-id="1c1b9-122">Select it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="1c1b9-123">Da biste omogućili **Slanje odmah nakon povezivanja**:</span><span class="sxs-lookup"><span data-stu-id="1c1b9-123">To enable **Send immediately when connected**:</span></span>
 
- <span data-ttu-id="1c1b9-124">Izaberite \*\*\*\* > \*\*\*\* opcije >  za**Napredne**datoteke.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-124">Select **File** > **Options** >  **Advanced**.</span></span>
<span data-ttu-id="1c1b9-125">U odeljku **Slanje i prijem** izaberite opciju **Pošalji odmah kada se povežete**, a zatim odaberite **"u redu"**.</span><span class="sxs-lookup"><span data-stu-id="1c1b9-125">In the **Send and receive** section, select **Send immediately when connected**, and then choose **OK**.</span></span>
 
<span data-ttu-id="1c1b9-126">Za sve detalje pogledajte:</span><span class="sxs-lookup"><span data-stu-id="1c1b9-126">For full details see:</span></span>
- [<span data-ttu-id="1c1b9-127">Video zapis: slanje ili brisanje zaglavljena e-poruke</span><span class="sxs-lookup"><span data-stu-id="1c1b9-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="1c1b9-128">E-poruka ostaje u fascikli "Otpremno poštansko sanduče" dok ručno ne pokrenete operaciju slanja/prijema u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="1c1b9-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)

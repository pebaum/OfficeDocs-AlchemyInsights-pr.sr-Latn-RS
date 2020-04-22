---
title: 2491 obaveštenja e-poruke iz ' Phish dostavljene zbog načela tenanta ili zamene korisnika
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2e4efd504304da757687e697ff23374aeea31851
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758946"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="f0071-102">Obavesti e-poruke sa ' Phish isporučenim zbog smernica za zatezivanje ili zamenu korisnika</span><span class="sxs-lookup"><span data-stu-id="f0071-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="f0071-103">Podrazumevane smernice za upozorenje pod nazivom "Phish isporučeno zbog tenanta ili korisničke zamene" su isporučene u stanari sa Office 365 ATP P1 i P2 licence.</span><span class="sxs-lookup"><span data-stu-id="f0071-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="f0071-104">Ako ste primili ovo obaveštenje, evo koraka za istraživanje:</span><span class="sxs-lookup"><span data-stu-id="f0071-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="f0071-105">Iz poruke obaveštenja kliknite na dugme " **Prikaži obaveštenje** " da biste otišli na stranicu " **obaveštenja** " u centru za bezbednost &.</span><span class="sxs-lookup"><span data-stu-id="f0071-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="f0071-106">Izaberite obaveštenje da biste videli opciju za **Prikazivanje liste poruka** ili **Prikazivanje poruka u programu Explorer**.</span><span class="sxs-lookup"><span data-stu-id="f0071-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="f0071-107">Obe opcije će vas odvesti do detalja poruke, koja uključuje ID poruke.</span><span class="sxs-lookup"><span data-stu-id="f0071-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="f0071-108">Imajte na umu da će veza "Explorer za pretnje" automatski filtrirati poruke koje odgovaraju kriterijumu obaveštenja.</span><span class="sxs-lookup"><span data-stu-id="f0071-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="f0071-109">Možda će biti potrebno da podesite filter datuma u istraživaču pretnji.</span><span class="sxs-lookup"><span data-stu-id="f0071-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="f0071-110">Prevarantska poruka je isporučena zbog ručnog konfigurisanog zamene:</span><span class="sxs-lookup"><span data-stu-id="f0071-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="f0071-111">Dozvoljen pošiljalac ili domen koji je postavio korisnik.</span><span class="sxs-lookup"><span data-stu-id="f0071-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="f0071-112">Dozvoljen pošiljalac ili domen koji je postavio administrator u smernicama za borbu protiv bezvredne pošte.</span><span class="sxs-lookup"><span data-stu-id="f0071-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="f0071-113">Dozvoljena IP adresa u smernicama filtera veze.</span><span class="sxs-lookup"><span data-stu-id="f0071-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="f0071-114">Pravilo toka pošte (poznato i kao pravilo prevoza) konfigurirano je tako da dozvoljava poruke.</span><span class="sxs-lookup"><span data-stu-id="f0071-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="f0071-115">Ako smatrate da je poruka nepravilno označena kao Phish, koristite [programski dodatak poruke u Outlook izveštaju](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) da biste prosledili uzorke poruka korporaciji Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f0071-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>

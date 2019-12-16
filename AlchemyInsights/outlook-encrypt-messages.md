---
title: S/MIME u Outlooku na Webu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 33e94eac6a2982b8036e13d17bf60015f244f2cb
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053239"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="38d4e-102">Šifrovanje e-poruka u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="38d4e-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="38d4e-103">Office 365 šifrovanje poruka je ugrađeno na Microsoft Azure Rights Management (azazni RMS), koja je deo zaštitne zaštite informacija.</span><span class="sxs-lookup"><span data-stu-id="38d4e-103">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="38d4e-104">Ako vaša pretplata uključuje uslugu Azure Rights Management ili Azure zaštitu informacija, **Ne morate da preduzmete radnje da biste ručno omogućili ili aktivirali** usluge upravljanja pravima.</span><span class="sxs-lookup"><span data-stu-id="38d4e-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="38d4e-105">Na osnovu povratnih informacija korisnika, više nećemo biti u toku omogućavanje pravila protoka pošte za Exchange da biste automatski šifrovali odlaznu e-poštu koja sadrži određeni tip osetljivih informacija u vašem stanantu.</span><span class="sxs-lookup"><span data-stu-id="38d4e-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="38d4e-106">Umesto toga, obezbeđujemo detaljna uputstva o tome kako to možete učiniti sami.</span><span class="sxs-lookup"><span data-stu-id="38d4e-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="38d4e-107">Dodatne informacije o kreiranju pravila transporta za šifrovanje osetljivih informacija potražite u [ovom članku](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="38d4e-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="38d4e-108">Ako koristite Outlook na Webu **(ranije ove**): kada pišete e-poruku, jednostavno kliknite na dugme " **zaštiti** u owi".</span><span class="sxs-lookup"><span data-stu-id="38d4e-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="38d4e-109">Ovo će primeniti dozvolu "ne prosleđi".</span><span class="sxs-lookup"><span data-stu-id="38d4e-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="38d4e-110">Kliknite na dugme " **Promeni dozvolu** " i odaberite opciju " **Šifruj** " da biste šifrovali poruku.</span><span class="sxs-lookup"><span data-stu-id="38d4e-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="38d4e-111">Ako koristite **Outlook Client**: da biste poslali šifrovanu poruku iz programa Outlook 2013 ili 2016 ili Outlook 2016 za Mac, izaberite **Opcije** > **dozvole**, a zatim izaberite opciju za zaštitu koja vam je potrebna.</span><span class="sxs-lookup"><span data-stu-id="38d4e-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="38d4e-112">Da biste **automatski šifrovali svu e-poštu** poslatu određenim primaocima ili organizacijama spoljnih partnera, potrebno je da u Exchange admin Center kreirate pravilo transporta toka pošte.</span><span class="sxs-lookup"><span data-stu-id="38d4e-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="38d4e-113">U [ovom članku za podršku](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities)obezbeđeni su detaljna uputstva.</span><span class="sxs-lookup"><span data-stu-id="38d4e-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>


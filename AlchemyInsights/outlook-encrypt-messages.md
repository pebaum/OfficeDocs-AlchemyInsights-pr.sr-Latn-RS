---
title: S/MIME u programu Outlook na Webu
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: f2c047ca31c586c0aa36701e6e7ca9976cfd1734
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666854"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="04163-102">Šifrovanje poruke e-pošte u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="04163-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="04163-103">Šifriranje poruka Office 365 se gradi na Microsoft Azure upravljanje pravima (Azure RMS), koji je deo Azure zaštite informacija.</span><span class="sxs-lookup"><span data-stu-id="04163-103">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="04163-104">Ako vaša pretplata uključuje Azure Rights Management ili Azure informacije zaštitu, da **Ne treba da preduzmu bilo kakve radnje ručno omogućavanje ili aktivirati** uslugom za upravljanje pravima.</span><span class="sxs-lookup"><span data-stu-id="04163-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="04163-105">Na osnovu povratne informacije, smo će više biti omogućavanje pravila protok pošte Exchange automatski šifrovati izlazni e-pošta koja sadrži određene vrste osetljivih informacija u tvojim podstanarom po podrazumevanoj vrednosti.</span><span class="sxs-lookup"><span data-stu-id="04163-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="04163-106">Umesto toga, pružamo detaljna uputstva na kako to možete učiniti sami.</span><span class="sxs-lookup"><span data-stu-id="04163-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="04163-107">Za dodatne detalje o tome kako da kreirate transporta pravilo da biste šifrovali poverljive informacije, pogledajte [Ovaj članak](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="04163-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="04163-108">Ako koristite Outlook na Webu (nekadašnja **OWA**): prilikom sastavljanja e-poruku, jednostavno kliknite na **zaštiti** u OWA.</span><span class="sxs-lookup"><span data-stu-id="04163-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="04163-109">To će se odnositi „Uradi ne napred” dozvolu.</span><span class="sxs-lookup"><span data-stu-id="04163-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="04163-110">Kliknite na dugme **Promeni dozvolu** i odabrati **šifrovanje** da samo prilikom šifrovanja.</span><span class="sxs-lookup"><span data-stu-id="04163-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="04163-111">Ako koristite **Outlook kao klijentski program**: izaberite **Opcije**da biste poslali šifrovanu poruku iz programa Outlook 2013 ili 2016, ili Outlook 2016 za Mac > **dozvole**, a zatim izaberite opciju "Zaštita" ti treba.</span><span class="sxs-lookup"><span data-stu-id="04163-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="04163-112">**Automatski šifrovati sve e-poštu** poslati na određene primaoce ili eksterni partnerske organizacije, morate kreirati pravilo pošte protok saobraćaja u centru za Admin Exchange.</span><span class="sxs-lookup"><span data-stu-id="04163-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="04163-113">Detaljna uputstva su navedena u [ovom članku za podršku](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="04163-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>


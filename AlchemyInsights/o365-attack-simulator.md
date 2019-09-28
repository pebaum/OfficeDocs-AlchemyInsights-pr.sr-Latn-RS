---
title: 2681 sa Simulatom napada na Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305345"
---
# <a name="attack-simulator-in-office-365"></a><span data-ttu-id="1222e-102">Simulatoru napada u Officeu 365</span><span class="sxs-lookup"><span data-stu-id="1222e-102">Attack Simulator in Office 365</span></span>

- <span data-ttu-id="1222e-103">Da li nedostaje simulatoru napada?</span><span class="sxs-lookup"><span data-stu-id="1222e-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="1222e-104">Simulatoru napada zahteva **Office 365 napredni plan zaštite pretnji 2 (ATP plan 2)** ili **Office 365 Enterprise E5**.</span><span class="sxs-lookup"><span data-stu-id="1222e-104">Attack Simulator requires **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5**.</span></span> <span data-ttu-id="1222e-105">Simulatoru napada **nije** uključen u Office 365 napredni plan zaštite pretnje 1 (ATP plan 1), Office 365 Enterprise E3 ili bilo koje Office 365 poslovne pretplate.</span><span class="sxs-lookup"><span data-stu-id="1222e-105">Attack Simulator is **not** included in Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Office 365 Business subscriptions.</span></span>

- <span data-ttu-id="1222e-106">Nalog koji koristite za pokretanje simuliranog napada zahteva globalne administratorske ili administratorske dozvole za zaštitu od više faktora (MFA).</span><span class="sxs-lookup"><span data-stu-id="1222e-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="1222e-107">Za više informacija o zahtevima za simulatoru napada pogledajte [ovu temu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span><span class="sxs-lookup"><span data-stu-id="1222e-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span></span>

- <span data-ttu-id="1222e-108">Važne stvari koje treba znati o **okrutne sile napada lozinke** :</span><span class="sxs-lookup"><span data-stu-id="1222e-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="1222e-109">Ako je ciljni nalog omogućen MFA, a lozinka je ispravno pogodila, nalog neće biti ugrožen (drugi faktor potvrde identiteta će biti nepotpun).</span><span class="sxs-lookup"><span data-stu-id="1222e-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="1222e-110">Datoteka sa lozinkama ne može da bude veća od 10 MB.</span><span class="sxs-lookup"><span data-stu-id="1222e-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="1222e-111">Koristite jednu lozinku po redu, a zatim uključite prazan red (znak za kraj reda) nakon poslednje lozinke na listi.</span><span class="sxs-lookup"><span data-stu-id="1222e-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="1222e-112">Važne stvari koje treba znati o **koplju phishing** Priloži simulacije:</span><span class="sxs-lookup"><span data-stu-id="1222e-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="1222e-113">Po dizajnu, ne možete da navedete prilagođenu vrednost za **URL adresu servera za prijavljivanje na phishing**.</span><span class="sxs-lookup"><span data-stu-id="1222e-113">By design, you can't provide a custom value for **Phishing login server URL**.</span></span>

  - <span data-ttu-id="1222e-114">Ako primalac koristi [programski dodatak "Omogući" poruke izveštaja](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) da prijavi poruku kao phishing, možda nećete primati obaveštenja za poruku (zato što je ovo simulirani napad).</span><span class="sxs-lookup"><span data-stu-id="1222e-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="1222e-115">Izveštaji: Nakon dovršenog simuliranog napada, možete da izaberete stavku " **Detalji napada** " da biste videli izveštaj.</span><span class="sxs-lookup"><span data-stu-id="1222e-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="1222e-116">Za detaljna uputstva i nove osobine na simulatoru napada pogledajte [simulatoru napada na Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="1222e-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>

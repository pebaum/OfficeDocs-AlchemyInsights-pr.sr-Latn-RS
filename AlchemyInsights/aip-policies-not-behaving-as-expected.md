---
title: 'AIP: smernice se ne ponašaju na očekivani način'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4780"
ms.openlocfilehash: 527556fcb02525eb88ea992c38a2ddfcba6f9453
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506572"
---
# <a name="aip-policies-not-behaving-as-expected"></a><span data-ttu-id="505ef-102">AIP: smernice se ne ponašaju na očekivani način</span><span class="sxs-lookup"><span data-stu-id="505ef-102">AIP: Policies not behaving as expected</span></span>

<span data-ttu-id="505ef-103">Azure zaštita informacija: smernice se ne ponašaju kao što je očekivano, pogledajte sledeće za preporučene smernice za različite probleme sa smernicama:</span><span class="sxs-lookup"><span data-stu-id="505ef-103">Azure Information Protection: Policies not behaving as expected, see the following for recommended guidelines for various policy issues:</span></span>

1. <span data-ttu-id="505ef-104">Ako imate problema sa vizuelnim oznakama, pregledajte [kada se primenjuju vizuelne oznake](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span><span class="sxs-lookup"><span data-stu-id="505ef-104">If you are having issues with visual markings, please review [When visual markings are applied](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).</span></span>
2. <span data-ttu-id="505ef-105">Ako imate problema sa automatskim označenim korišćenjem, pregledajte [Kako da konfigurišete uslove za automatsku i preporučenu klasifikaciju za zaštitu od informacija](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) i [koje tipove osetljivih informacija izgledaju](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span><span class="sxs-lookup"><span data-stu-id="505ef-105">If you are having issues with automatic labeling, please review [How to configure conditions for automatic and recommended classification for Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) and [What the sensitive information types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span></span>
3. <span data-ttu-id="505ef-106">Ako imate problema sa zaštitom matičnog/Pdatoteka, pregledajte [KONFIGURACIJU API datoteke](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span><span class="sxs-lookup"><span data-stu-id="505ef-106">If you are having issues with Native/Pfile protection, please review [File API configuration](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).</span></span>
4. <span data-ttu-id="505ef-107">Proverite da li koristite nepodešene smernice koje nisu ispravno konfigurisane: [Kako da konfigurišete smernice za zaštitu informacija koje se koriste za određene korisnike pomoću smernica na osnovu programa](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span><span class="sxs-lookup"><span data-stu-id="505ef-107">Check if you are using scoped policies that aren't configured properly: [How to configure the Azure Information Protection policy for specific users by using scoped policies](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span></span>
5. <span data-ttu-id="505ef-108">Ako Automatsko označavanje ne radi za Outlook prilikom prilaganja označanog dokumenta, proverite da li je funkcija DRMEncryptProperty nije definisana kao što je ovde opisano: [postavke registratora usluge IRM za bezbednost](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span><span class="sxs-lookup"><span data-stu-id="505ef-108">If automatic labeling isn't working for Outlook when attaching a labeled document, verify that DRMEncryptProperty isn't defined as described here: [IRM registry settings for security](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span></span>

<span data-ttu-id="505ef-109">Ako i dalje imate problema, prikupite informacije o klijentskim zapisnicima za zaštitu informacija i priložite izvezenu evidenciju na ovu kartu.</span><span class="sxs-lookup"><span data-stu-id="505ef-109">If you still are experiencing issues, please collect Azure Information Protection client logs and attach the exported logs to this ticket.</span></span>

1. <span data-ttu-id="505ef-110">Otvorite Office dokument ili kreirajte novu e-poruku u programu Outlook.</span><span class="sxs-lookup"><span data-stu-id="505ef-110">Open an Office document or create a new email in Outlook.</span></span>
2. <span data-ttu-id="505ef-111">Izaberite stavku **Zaštita/osetljivost**u  >  **okviru pomoći i povratnih informacija**.</span><span class="sxs-lookup"><span data-stu-id="505ef-111">Click **Protect/Sensitivity** > **Help and feedback**.</span></span>
3. <span data-ttu-id="505ef-112">Kliknite na dugme **evidencije izvoza**.</span><span class="sxs-lookup"><span data-stu-id="505ef-112">Click **Export Logs**.</span></span>
4. <span data-ttu-id="505ef-113">Sačuvajte evidencije na izboru lokacije i priključite ih na zahtev za uslugu.</span><span class="sxs-lookup"><span data-stu-id="505ef-113">Save the logs to your choice of location, and attach them to this service request.</span></span>

<span data-ttu-id="505ef-114">Dodatni resursi:</span><span class="sxs-lookup"><span data-stu-id="505ef-114">Additional resources:</span></span>

- [<span data-ttu-id="505ef-115">Konfigurisanje oznake za vizuelne oznake za zaštitu od Azure informacija</span><span class="sxs-lookup"><span data-stu-id="505ef-115">How to configure a label for visual markings for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy-markings)
- [<span data-ttu-id="505ef-116">Pregled dokumentacije za zaštitu od Azure informacija</span><span class="sxs-lookup"><span data-stu-id="505ef-116">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [<span data-ttu-id="505ef-117">Korišćenje oznaka za osetljivost u Office aplikacijama</span><span class="sxs-lookup"><span data-stu-id="505ef-117">Use sensitivity labels in Office apps</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels-office-apps)


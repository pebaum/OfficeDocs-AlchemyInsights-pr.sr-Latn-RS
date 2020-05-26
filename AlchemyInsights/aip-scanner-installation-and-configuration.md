---
title: 'AIP skener: instalacija i konfiguracija'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002278"
- "5119"
ms.openlocfilehash: d059d411aef03ca57662b71fbd7d27aecd3e0e57
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/23/2020
ms.locfileid: "44358565"
---
# <a name="aip-scanner-installation-and-configuration"></a><span data-ttu-id="a2b95-102">AIP skener: instalacija i konfiguracija</span><span class="sxs-lookup"><span data-stu-id="a2b95-102">AIP scanner: installation and configuration</span></span>

<span data-ttu-id="a2b95-103">**Pratite preporučene smernice da biste instalirali AIP skener**:</span><span class="sxs-lookup"><span data-stu-id="a2b95-103">**To install the AIP scanner, follow the recommended guidelines**:</span></span>

1. <span data-ttu-id="a2b95-104">Ako nadograđujete i ne izvršavate čistu instalaciju, proverite da li ste pratili uputstva za [nadogradnju zaštitnog skenera za zaštitu informacija](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide#upgrading-the-azure-information-protection-scanner) i za objedinjenu korisnika, pogledajte odeljak [Nadogradnja skenera za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide#upgrading-the-azure-information-protection-scanner).</span><span class="sxs-lookup"><span data-stu-id="a2b95-104">If you are upgrading and not performing a clean installation, please make sure you have followed the guidelines for [upgrading the Azure Information Protection scanner](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide#upgrading-the-azure-information-protection-scanner) and for unified labeling client, see [upgrading the Azure Information Protection scanner](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide#upgrading-the-azure-information-protection-scanner).</span></span>
2. <span data-ttu-id="a2b95-105">Proverite da li ste u skladu sa svim [zaštitnim zidovima i zahtevima za postavke mrežne infrastrukture](https://docs.microsoft.com/azure/information-protection/requirements#firewalls-and-network-infrastructure).</span><span class="sxs-lookup"><span data-stu-id="a2b95-105">Verify that you comply with all [Firewalls and network infrastructure settings requirements](https://docs.microsoft.com/azure/information-protection/requirements#firewalls-and-network-infrastructure).</span></span>
3. <span data-ttu-id="a2b95-106">Uverite se da [su smernice podešene](https://docs.microsoft.com/azure/information-protection/configure-policy) za automatsko označavanje ili da imaju podrazumevanu oznaku u smernici.</span><span class="sxs-lookup"><span data-stu-id="a2b95-106">Make sure your [policies are set](https://docs.microsoft.com/azure/information-protection/configure-policy) to automatic labeling or have a default label in the policy.</span></span>
4. <span data-ttu-id="a2b95-107">Uverite se da je odgovarajući tip datoteke konfigurisan za oznaku/zaštitu kao što je opisano u [tipovima datoteka koje podržava "Azure" softver za zaštitu informacija](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#supported-file-types-for-classification-and-protection).</span><span class="sxs-lookup"><span data-stu-id="a2b95-107">Make sure that the relevant file type is configured for label/protection as described in [File types supported by the Azure Information Protection client](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#supported-file-types-for-classification-and-protection).</span></span> <span data-ttu-id="a2b95-108">Pored toga, ako želite da promenite podrazumevano ponašanje, sledite ove smernice: [Promena podrazumevanog nivoa zaštite datoteka](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#changing-the-default-protection-level-of-files).</span><span class="sxs-lookup"><span data-stu-id="a2b95-108">In addition, if you want to change the default behavior, follow these guidelines: [Changing the default protection level of files](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#changing-the-default-protection-level-of-files).</span></span>
5. <span data-ttu-id="a2b95-109">Proverite da li korisnički nalog konfigurisan za pokretanje usluge skenera ima dozvole za pristup svim konfigurisanim depoa.</span><span class="sxs-lookup"><span data-stu-id="a2b95-109">Verify that the user account configured to run the scanner service has permissions to access all the configured repositories.</span></span>
6. <span data-ttu-id="a2b95-110">Ako i dalje budete imali problema, izvezite evidencije skenera i dodajte ih na kartu za podršku.</span><span class="sxs-lookup"><span data-stu-id="a2b95-110">If you still experience issues, please export the scanner logs and add them to your support ticket.</span></span>

<span data-ttu-id="a2b95-111">**Evidencija za izvoz Azure datoteka zaštite skenera**</span><span class="sxs-lookup"><span data-stu-id="a2b95-111">**Export Azure Information Protection Scanner logs**</span></span>

1. <span data-ttu-id="a2b95-112">Krećite se do%localappdata%\Microsoft\MSIP u okviru korisničkog konteksta koji koristi uslugu skenera.</span><span class="sxs-lookup"><span data-stu-id="a2b95-112">Navigate to %localappdata%\Microsoft\MSIP under the user context running the scanner service.</span></span>
2. <span data-ttu-id="a2b95-113">Zip svi sadržaji u okviru MSIP fascikle.</span><span class="sxs-lookup"><span data-stu-id="a2b95-113">Zip all the contents under the MSIP folder.</span></span>
3. <span data-ttu-id="a2b95-114">Sačuvajte evidencije na izboru lokacije i priložite ih svom zahtevu za uslugu.</span><span class="sxs-lookup"><span data-stu-id="a2b95-114">Save the logs to your choice of location, and attach them to your service request.</span></span>
4. <span data-ttu-id="a2b95-115">Takođe možete koristiti funkciju " [Izvezi-Aipevidencijama"-Onbpolof](https://docs.microsoft.com/powershell/module/azureinformationprotection/export-aiplogs?view=azureipps).</span><span class="sxs-lookup"><span data-stu-id="a2b95-115">You can also use [Export-AIPLogs -OnBehalfOf](https://docs.microsoft.com/powershell/module/azureinformationprotection/export-aiplogs?view=azureipps).</span></span>

<span data-ttu-id="a2b95-116">**Za dodatne informacije pogledajte**:</span><span class="sxs-lookup"><span data-stu-id="a2b95-116">**For additional information, see**:</span></span>
- [<span data-ttu-id="a2b95-117">Primena skenera za zaštitu od Azure informacija radi automatskog klasifikivanja i zaštite datoteka</span><span class="sxs-lookup"><span data-stu-id="a2b95-117">Deploying the Azure Information Protection scanner to automatically classify and protect files</span></span>](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner)
- [<span data-ttu-id="a2b95-118">Određivanje i korišćenje parametra tokena za podešavanje-Aipprovjeru autentičnosti</span><span class="sxs-lookup"><span data-stu-id="a2b95-118">Specify and use the Token parameter for Set-AIPAuthentication</span></span>](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-powershell#specify-and-use-the-token-parameter-for-set-aipauthentication)
- [<span data-ttu-id="a2b95-119">Pokretanje ciklusa otkrivanja i prikazivanje izveštaja za skener</span><span class="sxs-lookup"><span data-stu-id="a2b95-119">Run a discovery cycle and view reports for the scanner</span></span>](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner#run-a-discovery-cycle-and-view-reports-for-the-scanner)
- [<span data-ttu-id="a2b95-120">Pregled dokumentacije za zaštitu od Azure informacija</span><span class="sxs-lookup"><span data-stu-id="a2b95-120">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [<span data-ttu-id="a2b95-121">Zahtevi za zaštitu od Azure informacija</span><span class="sxs-lookup"><span data-stu-id="a2b95-121">Requirements for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/requirements)
- [<span data-ttu-id="a2b95-122">Preuzimanje programa za zaštitu od Azure informacija</span><span class="sxs-lookup"><span data-stu-id="a2b95-122">Download Azure Information Protection client</span></span>](https://www.microsoft.com/download/details.aspx?id=53018)

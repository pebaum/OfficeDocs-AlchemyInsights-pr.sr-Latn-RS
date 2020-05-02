---
title: Privatni kanal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001223"
- "3205"
ms.openlocfilehash: be518df0d40123c1f0da6596bd6e2e91a0c2c8fa
ms.sourcegitcommit: 057d87c9d866fa1371d02350420d13774545c028
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/02/2020
ms.locfileid: "44005452"
---
# <a name="private-channels-in-microsoft-teams"></a><span data-ttu-id="f2240-102">Privatni kanali u Microsoft timovima</span><span class="sxs-lookup"><span data-stu-id="f2240-102">Private channels in Microsoft Teams</span></span>

<span data-ttu-id="f2240-103">Privatni kanali su nova funkcija u Microsoft timovima.</span><span class="sxs-lookup"><span data-stu-id="f2240-103">Private channels is a new feature in Microsoft Teams.</span></span> <span data-ttu-id="f2240-104">Imajte na umu da se privatni kanali ne mogu konvertovati sa standardnih kanala ili obrnuto.</span><span class="sxs-lookup"><span data-stu-id="f2240-104">Note that private channels cannot be converted from standard channels or vice versa.</span></span>

<span data-ttu-id="f2240-105">Za detalje o privatnim kanalima, kao što su informacije o [kreiranju privatnih kanala i](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) lokacijama za članstvo i [privatnim](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites)kanalima, pogledajte [privatne kanale u Microsoft timovima](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span><span class="sxs-lookup"><span data-stu-id="f2240-105">For details about private channels, such as information on [private channel creation and membership](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) and [private channel SharePoint sites](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), see [Private channels in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span></span> 

<span data-ttu-id="f2240-106">**Napomena:** Pošto konfiguracija poruka privatnih kanala još uvek nije podržana, stanari sa omogućenim smernicama za zadržavanje neće podrazumevano imati omogućene privatne kanale.</span><span class="sxs-lookup"><span data-stu-id="f2240-106">**Note:** Because configuration for retention of private channel messages is not yet supported, tenants with retention policies enabled will not have private channels enabled by default.</span></span> <span data-ttu-id="f2240-107">Privatni kanali mogu biti omogućeni u okviru administratorskog centra timova.</span><span class="sxs-lookup"><span data-stu-id="f2240-107">Private channels can be enabled in the Teams admin center.</span></span> <span data-ttu-id="f2240-108">Takođe, imajte na umu da, iako zadržavanje poruka privatnih kanala nije podržano, podržano je zadržavanje datoteka koje su deljene u privatnim kanalima.</span><span class="sxs-lookup"><span data-stu-id="f2240-108">Also, note that while retention of private channel messages is not supported, retention of files shared in private channels is supported.</span></span>

<span data-ttu-id="f2240-109">**Potreban vam je novi vlasnik tima?**</span><span class="sxs-lookup"><span data-stu-id="f2240-109">**Need a new team owner?**</span></span>

<span data-ttu-id="f2240-110">Ako vlasnik vašeg privatnog kanala ode, možete da dodate novog vlasnika tima pomoću PowerShell timova.</span><span class="sxs-lookup"><span data-stu-id="f2240-110">If your private channel owner leaves, you can add a new team owner via Teams Powershell.</span></span>


- <span data-ttu-id="f2240-111">Idite [ovde](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) da biste instalirali "PowerShell" timova.</span><span class="sxs-lookup"><span data-stu-id="f2240-111">Go [here](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) to install Teams Powershell.</span></span>

<span data-ttu-id="f2240-112">Evo vam cmdda vam zatreba:</span><span class="sxs-lookup"><span data-stu-id="f2240-112">Here is the cmdlet you will need:</span></span>

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

<span data-ttu-id="f2240-113">Za više informacija o PowerShell timova pogledajte odeljak [Pregled PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="f2240-113">For more information on Teams Powershell, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span>

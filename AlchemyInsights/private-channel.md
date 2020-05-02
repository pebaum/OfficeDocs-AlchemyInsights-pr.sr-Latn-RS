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
# <a name="private-channels-in-microsoft-teams"></a>Privatni kanali u Microsoft timovima

Privatni kanali su nova funkcija u Microsoft timovima. Imajte na umu da se privatni kanali ne mogu konvertovati sa standardnih kanala ili obrnuto.

Za detalje o privatnim kanalima, kao što su informacije o [kreiranju privatnih kanala i](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) lokacijama za članstvo i [privatnim](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites)kanalima, pogledajte [privatne kanale u Microsoft timovima](https://docs.microsoft.com/MicrosoftTeams/private-channels). 

**Napomena:** Pošto konfiguracija poruka privatnih kanala još uvek nije podržana, stanari sa omogućenim smernicama za zadržavanje neće podrazumevano imati omogućene privatne kanale. Privatni kanali mogu biti omogućeni u okviru administratorskog centra timova. Takođe, imajte na umu da, iako zadržavanje poruka privatnih kanala nije podržano, podržano je zadržavanje datoteka koje su deljene u privatnim kanalima.

**Potreban vam je novi vlasnik tima?**

Ako vlasnik vašeg privatnog kanala ode, možete da dodate novog vlasnika tima pomoću PowerShell timova.


- Idite [ovde](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) da biste instalirali "PowerShell" timova.

Evo vam cmdda vam zatreba:

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

Za više informacija o PowerShell timova pogledajte odeljak [Pregled PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).

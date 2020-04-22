---
title: Ograničavanje pristupa u sistemu SharePoint ili OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: ed8e97b20c96a7b46995c969074cc4cef3a787d9
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715898"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Ograničavanje pristupa u sistemu SharePoint ili OneDrive

U sistemu SharePoint i OneDrive ograničajte pristup stavkama kao što su datoteke, fascikle i liste dodeljivanjem pristupa samo grupama ili pojedincima kojima želite da pristupite. Podrazumevano, dozvole u sistemu SharePoint su nasleđene od višeg u hijerarhiji. Zato datoteka nasleđuje dozvole iz fascikle koja nasleđuje dozvole iz biblioteke, što nasleđuje dozvole od lokacije.
  
Možete da delite na višem nivou (kao što je deljenje čitave lokacije), a zatim da prekinete nasleđivanje ako ne želite da delite sve stavke na lokaciji. Međutim, to ne preporučujemo zato što je održanje dozvola u budućnosti složenija i zbunjujuća. Evo šta možete uraditi:
  
- Ako, na primer, želite da delite celokupan sadržaj fascikle osim jedne datoteke u njoj, premestite tu datoteku na novu lokaciju koja se ne deli.
    
- Ako imate dve potfascikle u fascikli i želite da delite jednu potfasciklu sa grupama a i B i da dozvolite samo grupisanje pristupa drugoj potfascikli, podelite nadređenu fasciklu sa grupom a i dodajte grupu B u prvu potfasciklu.
    
[Prestanak deljenja datoteke ili fascikle](https://go.microsoft.com/fwlink/?linkid=2008861)
  


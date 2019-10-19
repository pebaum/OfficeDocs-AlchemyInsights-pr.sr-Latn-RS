---
title: Ograničavanje pristupa u sistemu SharePoint ili OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e5458226fe33bd5cb3da1f608fb113b888fbfd16
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36551465"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Ograničavanje pristupa u sistemu SharePoint ili OneDrive

U sistemu SharePoint i OneDrive ograničajte pristup stavkama kao što su datoteke, fascikle i liste dodeljivanjem pristupa samo grupama ili pojedincima kojima želite da pristupite. Podrazumevano, dozvole u sistemu SharePoint su nasleđene od višeg u hijerarhiji. Zato datoteka nasleđuje dozvole iz fascikle koja nasleđuje dozvole iz biblioteke, što nasleđuje dozvole od lokacije.
  
Možete da delite na višem nivou (kao što je deljenje čitave lokacije), a zatim da prekinete nasleđivanje ako ne želite da delite sve stavke na lokaciji. Međutim, to ne preporučujemo zato što je održanje dozvola u budućnosti složenija i zbunjujuća. Evo šta možete uraditi:
  
- Ako, na primer, želite da delite celokupan sadržaj fascikle osim jedne datoteke u njoj, premestite tu datoteku na novu lokaciju koja se ne deli.
    
- Ako imate dve potfascikle u fascikli i želite da delite jednu potfasciklu sa grupama a i B i da dozvolite samo grupisanje pristupa drugoj potfascikli, podelite nadređenu fasciklu sa grupom a i dodajte grupu B u prvu potfasciklu.
    
[Prestanak deljenja datoteke ili fascikle](https://go.microsoft.com/fwlink/?linkid=2008861)
  


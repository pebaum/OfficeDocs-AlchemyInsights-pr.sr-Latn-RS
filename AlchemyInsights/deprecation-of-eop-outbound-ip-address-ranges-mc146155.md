---
title: 1065. amortizacija EOP odlazne IP adrese rangesMC146155
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: f4854c32d970d84f3a0664a9e384dc6e3cd0bfa7
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704611"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Amortiziranje opsega izlaznih IP adresa

Otkrili smo potencijalni problem sa vašom organizacijom da (ako se ne ispravi do 26. oktobra 2018) može da prekine protok pošte na vašim objektima ili spoljnim destinacijama. Kao što je prethodno komuniciranje, pojednostavljivanje upravljanja opsegom IP adresa, konsolidujemo opsege IP adresa za Exchange Online (EOP) koji se koriste za slanje i primanje e-pošte van Microsoft 365. Naša analiza ukazuje na to da neki spoljni izvori e-pošte ili destinacije koje ste konfigurisali u okviru linija za protok pošte ne prihvataju veze iz opsega IP adresa koji su [ovde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)prikazani.

Pre 26 oktobra, kako bi se osiguralo da ovi izvori i destinacije prihvate veze sa svim [objavljenim EOP IP adresama](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Za više informacija o ovoj promeni pogledajte poruke u centru poruka [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)ili [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Napomena**: Ako ste ranije koristili IP ili URL Publishing izdanja putem HTML-a, XML-a i RSS-a za ispravke krajnjeg čvorišta, trebalo bi da migrirate i na nove Web usluge za automatizaciju ovih tipova ispravki. Za više informacija pogledajte [microsoft 365 kategorije krajnje tačke i Web usluge microsoft 365 IP adresa i URL adresa](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).

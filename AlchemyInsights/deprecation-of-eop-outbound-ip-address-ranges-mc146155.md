---
title: 1065 svoja mišljenja i negodovanja od EOP izlaznog IP adresa rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 17beb1722142d94ea05b67ce5ed1f20f8b11375c
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404835"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Svoja mišljenja i negodovanja izlaznog opsega IP adresa EOP

Detektovali smo potencijalni problem sa vaše organizacije (ako se ne ispravlja do 26 oktobra, 2018) mogao bih da razbije tok pošte na lokalne ili spoljnim odredištima. Kao prethodno prenesenu, da pojednostavim IP adresu opseg upravljanja, smo konsolidujete opsege Exchange Online zaštitu (EOP) IP adresa koje se koriste za slanje i primanje e-pošte izvan Office 365. Analizu ukazuje na to da neki od spoljnih email izvore ili destinacije koje ste konfigurisali u poštu protok konektori nisu prihvatanjem veza sa na IP adresa opsege prikazan [ovde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Glumiš 26 oktobra da osigura ovih izvora i odredišta će da prihvati veze ka i od svih [objavio EOP IP adrese](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Za više informacija o ovoj promeni, pogledajte centar za poruke knjiži [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)ili [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Napomena**: Ako ste ranije koristili IP ili URL adresu za objavljivanje putem HTML, XML i RSS za krajnju ispravke, ti treba da migrirate novi web uslugama za automatizaciju ove vrste ispravki. Za više informacija, pogledajte [Office 365 krajnja tačka kategorije i Office 365 IP adresa i URL adresu web usluge](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).

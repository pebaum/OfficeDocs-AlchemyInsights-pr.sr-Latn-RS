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
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="135fb-102">Svoja mišljenja i negodovanja izlaznog opsega IP adresa EOP</span><span class="sxs-lookup"><span data-stu-id="135fb-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="135fb-103">Detektovali smo potencijalni problem sa vaše organizacije (ako se ne ispravlja do 26 oktobra, 2018) mogao bih da razbije tok pošte na lokalne ili spoljnim odredištima.</span><span class="sxs-lookup"><span data-stu-id="135fb-103">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations.</span></span> <span data-ttu-id="135fb-104">Kao prethodno prenesenu, da pojednostavim IP adresu opseg upravljanja, smo konsolidujete opsege Exchange Online zaštitu (EOP) IP adresa koje se koriste za slanje i primanje e-pošte izvan Office 365.</span><span class="sxs-lookup"><span data-stu-id="135fb-104">As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365.</span></span> <span data-ttu-id="135fb-105">Analizu ukazuje na to da neki od spoljnih email izvore ili destinacije koje ste konfigurisali u poštu protok konektori nisu prihvatanjem veza sa na IP adresa opsege prikazan [ovde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="135fb-105">Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="135fb-106">Glumiš 26 oktobra da osigura ovih izvora i odredišta će da prihvati veze ka i od svih [objavio EOP IP adrese](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="135fb-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="135fb-107">Za više informacija o ovoj promeni, pogledajte centar za poruke knjiži [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)ili [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="135fb-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>

<span data-ttu-id="135fb-108">**Napomena**: Ako ste ranije koristili IP ili URL adresu za objavljivanje putem HTML, XML i RSS za krajnju ispravke, ti treba da migrirate novi web uslugama za automatizaciju ove vrste ispravki.</span><span class="sxs-lookup"><span data-stu-id="135fb-108">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates.</span></span> <span data-ttu-id="135fb-109">Za više informacija, pogledajte [Office 365 krajnja tačka kategorije i Office 365 IP adresa i URL adresu web usluge](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="135fb-109">For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>

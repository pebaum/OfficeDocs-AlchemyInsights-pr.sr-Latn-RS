---
title: Exchange PowerShell i osnovna zastarela potvrda identiteta
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "4577"
ms.openlocfilehash: 24d59860732b42e8d62da8c1a8c37f2018a0d126
ms.sourcegitcommit: 264b782ac2fba8ffd84524180dc4f7d60b45e9a4
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/04/2020
ms.locfileid: "44015703"
---
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a>Exchange PowerShell i osnovna zastarela potvrda identiteta

Najnovije informacije o tome kako da se povežete sa uslugom Exchange Online PowerShell bez upotrebe osnovne potvrde identiteta [potražite ovde](https://aka.ms/psbasicauth).

Imajte u vidu da Osnovna potvrda identiteta i dalje mora da bude omogućena na klijentskom računaru.
Novi modul programa PowerShell v2 koristi modernu potvrdu identiteta za uspostavljanje veze za omogućavanje svih V2 cmdlet zasnovanih na REST. Pored V2 cmdlets, omogućava vam i da pristupate starijim daljinskim PowerShell (RPS) Cmdlets koje zahtevaju daljinsku PowerShell sesiju da bude uspostavljena. Uspostavljanje RPS sesije na Windows računaru zahteva da WinRM osnovna potvrda identiteta bude omogućena na računaru klijenta iako modul koristi mehanizam moderne potvrde identiteta za potvrdu identiteta usluge. WinRM kanal osnovne potvrde identiteta se koristi za prenošenje tokena moderne potvrde identiteta. Ako se WinRM kanal osnovne potvrde identiteta onemogući na računaru klijenta, novi V2 cmdlet nastaviće da radi (ali stariji RPS cmdlets neće).

---
title: Mikro kašnjenja ili ograničavanje u usluzi Exchange Online PowerShell
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
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/30/2020
ms.locfileid: "43948033"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Mikro kašnjenja ili ograničavanje u usluzi Exchange Online PowerShell

Možda ćete videti upozorenja „Primenjeno je mikro kašnjenje“ ili kašnjenja kada pokrenete skripte ili cmdlet komande u usluzi Exchange Online. Evo dva predloga koja se odnose na ovo:

- Možete da pokušate da koristite [modul Exchange Online v2 PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) koji uključuje CMDlet komande zasnovane na REST API-ju i koje imaju znatno bolje performanse. Ovo može biti odlično rešenje za Get- CMDlet komande koje se često koriste.
- Ako morate da koristite CMDlet komande koje još uvek nisu obuhvaćene v2 modulom, pogledajte članak [„Pokretanje PowerShell cmdlet komande za veliki broj korisnika u sistemu Office 365“](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#) koji govori o tome kako da zaobiđete očekivana PowerShell ograničenja u usluzi Exchange Online.

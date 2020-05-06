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
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a><span data-ttu-id="ae967-102">Exchange PowerShell i osnovna zastarela potvrda identiteta</span><span class="sxs-lookup"><span data-stu-id="ae967-102">Exchange PowerShell and basic authentication deprecation</span></span>

<span data-ttu-id="ae967-103">Najnovije informacije o tome kako da se povežete sa uslugom Exchange Online PowerShell bez upotrebe osnovne potvrde identiteta [potražite ovde](https://aka.ms/psbasicauth).</span><span class="sxs-lookup"><span data-stu-id="ae967-103">For the latest information about how to connect to Exchange Online PowerShell without the use of Basic Authentication, [please go here](https://aka.ms/psbasicauth).</span></span>

<span data-ttu-id="ae967-104">Imajte u vidu da Osnovna potvrda identiteta i dalje mora da bude omogućena na klijentskom računaru.</span><span class="sxs-lookup"><span data-stu-id="ae967-104">Please note that Basic Authentication still needs to be enabled on your client machine.</span></span>
<span data-ttu-id="ae967-105">Novi modul programa PowerShell v2 koristi modernu potvrdu identiteta za uspostavljanje veze za omogućavanje svih V2 cmdlet zasnovanih na REST.</span><span class="sxs-lookup"><span data-stu-id="ae967-105">The new PowerShell V2 module uses Modern Auth to establish connection for enabling all of REST-based V2 Cmdlets.</span></span> <span data-ttu-id="ae967-106">Pored V2 cmdlets, omogućava vam i da pristupate starijim daljinskim PowerShell (RPS) Cmdlets koje zahtevaju daljinsku PowerShell sesiju da bude uspostavljena.</span><span class="sxs-lookup"><span data-stu-id="ae967-106">In addition to V2 cmdlets, it also allows you to access older Remote PowerShell (RPS) Cmdlets which requires a Remote PowerShell session to be established.</span></span> <span data-ttu-id="ae967-107">Uspostavljanje RPS sesije na Windows računaru zahteva da WinRM osnovna potvrda identiteta bude omogućena na računaru klijenta iako modul koristi mehanizam moderne potvrde identiteta za potvrdu identiteta usluge.</span><span class="sxs-lookup"><span data-stu-id="ae967-107">Establishing an RPS session on Windows machine requires WinRM BasicAuth to be enabled on the client machine even though the module uses Modern Auth mechanism to authenticate to the service.</span></span> <span data-ttu-id="ae967-108">WinRM kanal osnovne potvrde identiteta se koristi za prenošenje tokena moderne potvrde identiteta.</span><span class="sxs-lookup"><span data-stu-id="ae967-108">The WinRM Basic Auth pipeline is used for transporting Modern Auth tokens.</span></span> <span data-ttu-id="ae967-109">Ako se WinRM kanal osnovne potvrde identiteta onemogući na računaru klijenta, novi V2 cmdlet nastaviće da radi (ali stariji RPS cmdlets neće).</span><span class="sxs-lookup"><span data-stu-id="ae967-109">If WinRM Basic Auth is disabled on the client machine, the new V2 cmdlets will continue to work (but the older RPS cmdlets will not).</span></span>

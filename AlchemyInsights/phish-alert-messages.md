---
title: 2491 upozorenja e-poruka od „Kasetama isporučena usled stanara ili korisnika da zameni” politike
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 456b186ecea59422c791c79d4df056ad8446bc70
ms.sourcegitcommit: 7c90dcc570d32ebd968e3e4e816a7b482890b3a4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/13/2019
ms.locfileid: "36391500"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Upozorenje o e-poruka od „Kasetama isporučena usled stanara ili korisnika da zameni” politike

Podrazumevani upozorenja politike koja se zove „Kasetama Delivered zbog stanara ili korisnika override” je bilo umotano stanarima sa Office 365 ATP P1 i P2 licence. Ako ste primili ovo obaveštenje, evo korake kako bi istražili:

1. Iz poruka sa obaveštenjem, kliknite **Prikaz upozorenje** da idite na stranicu **upozorenja** u bezbednosti & usklađenosti centar.

2. Izaberite obaveštenje da vidite opciju za **prikaz liste poruka** ili **Prikaz poruka u Explorer**. Obe ove opcije te odvesti na detalje poruke, koja uključuje ID poruke. Imajte na umu da će na pretnju Explorer vezu automatski filtrirati poruke koje odgovara kriterijumima upozorenja. Možda ti treba da podesite filter datuma u opasnost Explorer.

Phishing poruka je isporučena zbog premostite ručno konfiguriran:

- Za dozvoljenih pošiljaoca ili domena postavljen od strane korisnika.

- Za dozvoljenih pošiljaoca ili domena postavio admin u smernice za borbu protiv neželjene pošte.

- Dozvoljenih IP adresu u smernicama za povezivanje filtera.

- Pošta protok pravilo (poznat i kao transportni pravilo) koji je konfigurisan da dozvoli poruke u.

Ako smatrate da je poruka bila pogrešno označene kao Cecu, koristite Outlook [poruku o izveštaju programski dodatak](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) da prosledite poruku uzorke korporaciji Microsoft.

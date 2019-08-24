---
title: Samo za čitanje za održavanje poruku kada pokušate da koristite SharePoint ili OneDrive
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 5b1e56253d6deeb0f9ba2f753eff5c00ff9c51a2
ms.sourcegitcommit: cd79ecca88b2cb166f78f44ab8bc4e8136729418
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 08/23/2019
ms.locfileid: "36620737"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a>Samo za čitanje za održavanje poruku kada pokušate da koristite SharePoint ili OneDrive

Korisnici mogu dobiti poruku **Samo za čitanje za održavanje** kada pokušaju da koriste SharePoint ili OneDrive za jedan od sledećih scenarija. 

-   Aktivnost na planirane ili aktivnog održavanja.  Potraži ih navigacijom u [Centar za poruke](https://portal.office.com/adminportal/home#/messagecenter).
-   Incident aktivne usluge visokog prioriteta, to može biti zatvorena. Potraži savjete/incidenti, navigacijom do [Zdravstvenih usluga](https://portal.office.com/adminportal/home#/servicehealth).
-   Manji isceljenja automatskog oporavka scenario koji moglo dogoditi zbog neočekivane događaje na serverima koji može trajati za manje od 30 min ili tako nešto. 
    
    Postoje nema centar za poruke ili zdravstveni servis knjiži ovih manjih oporavljaju, ali ti treba da se vrati u normalu uskoro.

U nekoliko navrata posmatrali smo da jedan od tri scenarija gore navedene bio uzrok, i usluga obnovljena, ali korisnici pregledača keš nije postala jasnija.

Molim te, pokušati da biste obrisali keš memoriju pregledača ranije kretanje do lokacije.

1. U pregledaču Microsoft Edge, izaberite stavku **Postavke**, a zatim izaberite **privatnosti i bezbednosti**.
2. Pod **jasno pregledanja**, izaberite **izaberem kako biste obrisali**.
3. Izaberite **kolačiće i podatke sačuvane Veb lokacija**i izaberite **Obriši**.

>[!Note] 
> Ovi koraci mogu da se razlikuju kada koristite drugi pregledači, kao što su Mozilla Firefox ili Google Chrome.

>[!Note] 
> Druga opcija je da otvorite SharePoint lokacija ili OneDrive u novom prozoru InPrivate.
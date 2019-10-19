---
title: Nije uspjelo aktiviranje toka posla koji nedostaje
ms.author: pebaum
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: f03d7e1441465050c4b0608f4100f217b183d2e2
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 10/18/2019
ms.locfileid: "36753810"
---
# <a name="missing-workflow-failed-to-activate"></a>Nije uspjelo aktiviranje toka posla koji nedostaje

U Microsoft SharePoint kolekciji lokacija ne možete dodati globalno tok posla koji je moguće ponovo koristiti (kao što je "odobrenje-SharePoint 2010") u listu ili biblioteku.
  
Da biste riješili taj problem, slijedite ove korake: 
  
1. Otvorite osnovnu Web lokaciju kolekcije lokacija u programu SharePoint Designer 2013.
  
2. U okviru **objekti lokacije**izaberite stavku **Tokovi posla**. 
  
3. U **novom** odeljku trake **tokova posla** izaberite opciju **tok posla**koji je moguće ponovo koristiti. 
  
4. U obrascu **Kreiranje toka posla** koji je moguće ponovo koristiti unesite ime * * *Repair2010* * *. Za **tip platforme**izaberite stavku **SharePoint 2010 tok posla**, a zatim kliknite na dugme **u redu**. 
  
1. U odeljku **Sačuvaj** na traci **toka posla** izaberite stavku **Objavi**. 
  
2. U odeljku " **Upravljanje** " na traci **toka posla** izaberite opciju " **Objavi globalno**". U dijalogu za potvrđivanje koji se pojavljuje izaberite **"u redu"**. 
  
3. U Web pregledaču pronađite osnovnu Veb lokaciju kolekcije lokacija, a zatim pristupite **postavkama** \> **kolekcije**lokacija. Zatim Preklapaj funkciju **tokova posla** : 
  
· Ako je funkcija *aktivirana* , kliknite na dugme **"Deaktiviraj",** a zatim kliknite na dugme " **Aktiviraj**". 
  
· Ako je funkcija *deaktivirana* , kliknite na dugme " **Aktiviraj**". 
  
Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  


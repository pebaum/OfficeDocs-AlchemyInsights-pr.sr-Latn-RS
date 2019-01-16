---
title: Nedostaje tok posla nije uspeo da aktivira
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 33b92c2cae1f641b0cd88c82fd4ae5e8632d76c2
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 01/15/2019
ms.locfileid: "28310360"
---
# <a name="missing-workflow-failed-to-activate"></a>Nedostaje tok posla nije uspeo da aktivira

U kolekciji lokacija Microsoft SharePoint, ne možete dodati globalno koji možete ponovo koristiti toka posla (kao što su „odobrenje - SharePoint 2010”) u listu ili biblioteku.
  
Da biste riješili taj problem, slijedite ove korake: 
  
1. Otvorite osnovnu Web lokacija u kolekciji lokacija u SharePoint Designer 2013.
  
2. U okviru **Lokacije objekata**, izaberite **tokova posla**. 
  
3. U **novom** delu glavnoj **tokova posla** , izaberite **Tok posla moguće ponovo koristiti**. 
  
4. **Kreiranje toka posla moguće ponovo koristiti** obrazac, unesite ime ** *Repair2010* **. Za **Tip platforme**, kliknite **SharePoint 2010 toka posla**, a zatim kliknite na dugme **u redu**. 
  
1. U odeljku **spasiti** glavne trake **toka posla** , izaberite **objavljivanje**. 
  
2. U odeljku za **Upravljanje** glavne trake **toka posla** , izaberite **Objavljivanje globalno**. U okviru za dijalog koji se pojavljuje, izaberite **OK**. 
  
3. U web pregledaču, pronađite osnovne Web lokacija u kolekciji lokacija, a zatim pristupite **Postavke lokacije** \> **Funkcije kolekcije lokacija**. Onda, Uključi/isključi funkcije za **tokove posla** : 
  
· Ako je funkcija *aktivirano* , kliknite **Deaktiviraj,** a zatim **Aktiviraj**. 
  
· Ako je funkcija " *Deactivated* ", kliknite na dugme **Aktiviraj**. 
  
Za više informacija pogledajte sledeći [članak](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  


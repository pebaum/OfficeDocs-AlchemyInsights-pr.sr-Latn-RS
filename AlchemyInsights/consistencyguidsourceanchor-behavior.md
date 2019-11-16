---
title: Postojenciguid/ponašanje u okviru izvora
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: f0ff94a8e46f1fb4e0ac8653c51f8f651e29498b
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/15/2019
ms.locfileid: "36517008"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>Postojenciguid/ponašanje u okviru izvora

Azure reklama Connect (verzija 1.1.524.0 i nakon) sada olakšava korišćenje msDS-a-Postojenciguid-a kao atributa izvora. Kada koristite ovu funkciju, Azure funkcija Connect automatski konfiguriše pravila sinhronizacije na:
  
- Za korisničke objekte koristite msDS-postojan Enciguid kao atribut Loncerenja. ObjectGUID se koristi za druge tipove objekata.
    
- Za sve date objekte za korisnike oglasa čiji msDS-postojani Encyguid atribut nije naseljen, Azure Connect za povezivanje upisuje svoju objectGUID vrednost nazad na msDS-Postojencyguid atribut u aktivnom direktorijumu na prostoru. Nakon što datoteka msDS-a ima Encyguid atribut bude popunjena, Azure oglas Connect zatim izvozi objekat u Azure oglas.
    
 **Napomena:** Kada se objekat na objektu u programu "Uvoz" bude uvezen u "Azure" Connect (odnosno uvezen u prostor za konektore), ne možete više da promenite njegovu vrednost. Da biste naveli vrednost polja izvora na osnovu datog objekta na objektu, konfigurišite njen msDS-Postojenciguid atribut pre nego što se uveze u "Azure" povezivanje sa više lokacija. 
  
Za više informacija o polju "isusidriti" i "Postojenciguid" Pogledajte sledeće: [AZURE oglas Connect: koncepti dizajna](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  


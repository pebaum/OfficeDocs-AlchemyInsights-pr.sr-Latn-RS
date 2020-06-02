---
title: 'AIP: smernice se ne ponašaju na očekivani način'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4780"
ms.openlocfilehash: 7926ff9ebbd54969fb5b3ae5d909baffe96a4292
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/26/2020
ms.locfileid: "44493416"
---
# <a name="aip-policies-not-behaving-as-expected"></a>AIP: smernice se ne ponašaju na očekivani način

Azure zaštita informacija: smernice se ne ponašaju kao što je očekivano, pogledajte sledeće za preporučene smernice za različite probleme sa smernicama:

1. Ako imate problema sa vizuelnim oznakama, pregledajte [kada se primenjuju vizuelne oznake](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).
2. Ako imate problema sa automatskim označenim korišćenjem, pregledajte [Kako da konfigurišete uslove za automatsku i preporučenu klasifikaciju za zaštitu od informacija](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) i [koje tipove osetljivih informacija izgledaju](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).
3. Ako imate problema sa zaštitom matičnog/Pdatoteka, pregledajte [KONFIGURACIJU API datoteke](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).
4. Proverite da li koristite nepodešene smernice koje nisu ispravno konfigurisane: [Kako da konfigurišete smernice za zaštitu informacija koje se koriste za određene korisnike pomoću smernica na osnovu programa](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).
5. Ako Automatsko označavanje ne radi za Outlook prilikom prilaganja označanog dokumenta, proverite da li je funkcija DRMEncryptProperty nije definisana kao što je ovde opisano: [postavke registratora usluge IRM za bezbednost](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).

Ako i dalje imate problema, prikupite informacije o klijentskim zapisnicima za zaštitu informacija i priložite izvezenu evidenciju na ovu kartu.

1. Otvorite Office dokument ili kreirajte novu e-poruku u programu Outlook.
2. Izaberite stavku **Zaštita/osetljivost**u  >  **okviru pomoći i povratnih informacija**.
3. Kliknite na dugme **evidencije izvoza**.
4. Sačuvajte evidencije na izboru lokacije i priključite ih na zahtev za uslugu.

Dodatni resursi:

- [Konfigurisanje oznake za vizuelne oznake za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/configure-policy-markings)
- [Pregled dokumentacije za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [Korišćenje oznaka za osetljivost u Office aplikacijama](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels-office-apps)


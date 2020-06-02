---
title: Automatska klasifikacija se ne ponaša na očekivani način sa AIP klijentom
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
- "4373"
ms.openlocfilehash: 95a994d6a49ee8737a6ebcb196314f92776d8482
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 05/26/2020
ms.locfileid: "44493434"
---
# <a name="automatic-classification-not-behaving-as-expected-with-the-aip-client"></a>Automatska klasifikacija se ne ponaša na očekivani način sa AIP klijentom

Automatska klasifikacija se ne ponaša na očekivani način, koristite sledeća preporučena uputstva:

1. Ako imate problema sa automatskim označenim načinom rada, pogledajte [Kako da konfigurišete uslove za automatsku i preporučenu klasifikaciju za zaštitu od informacija](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) i [kako izgledaju tipovi osetljivih informacija](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).
2. Proverite da li koristite nepodešene smernice koje nisu ispravno konfigurisane: [Kako da konfigurišete smernice za zaštitu informacija koje se koriste za određene korisnike pomoću smernica na osnovu programa](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).
3. Ako Automatsko označavanje ne radi za Outlook prilikom prilaganja označanog dokumenta, proverite da `DRMEncryptProperty` nije definisano kao što je ovde opisano: [postavke registratora usluge IRM za bezbednost](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).
4. Ako ste koristili [ugrađene tipove informacija](https://support.office.com/article/What-the-sensitive-information-types-look-for-fd505979-76be-4d9f-b459-abef3fc9e86b) za smernice za zaštitu informacija, proverite da li se sadržaj podudara sa očekivanim formatom.
5. Proverite da li je oznaka ispravno konfigurisana za **Automatsko** ili **preporučenu**. (**Automatsko** označavanje je dostupno za sve Office aplikacije **, dok je** za sve Office aplikacije dostupno samo za Outlook.)
6. Ne možete da koristite automatsku klasifikaciju za dokumente i e-poruke koje su prethodno bile ručno označene ili koje su prethodno automatski označene sa većom klasifikacijom.  Više informacija potražite u članku: [Kako se primenjuju automatske ili preporučene oznake](https://docs.microsoft.com/azure/information-protection/configure-policy-classification#how-automatic-or-recommended-labels-are-applied).
7. Ako i dalje nailazite na probleme, prikupite informacije o klijentskim evidencijama za zaštitu informacija o zaštiti podataka i priložite izvezene evidencije na vašu kartu za podršku. Da biste izvezli evidencije o zaštiti od Azure informacija:
    - Otvorite Office dokument ili kreirajte novu e-poruku u programu Outlook.
    - Izaberite stavku **Zaštita/osetljivost**u  >  **okviru pomoći i povratnih informacija**.
    - Kliknite na dugme **evidencije izvoza**.
    - Sačuvajte evidencije na izboru lokacije i priložite ih svom zahtevu za uslugu.

Za dodatne informacije pogledajte:

- [Kako konfigurirati uslove za automatsku i preporučenu klasifikaciju za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/configure-policy-classification)
- [Vodiči za uobičajene scenarije koji koriste Azure zaštitu informacija](https://docs.microsoft.com/azure/information-protection/how-to-guides)
- [Pregled dokumentacije za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [Pregled pretplata i funkcija zaštite od Azure podataka](https://azure.microsoft.com/pricing/details/information-protection)
- [Zahtevi za zaštitu od Azure informacija](https://docs.microsoft.com/azure/information-protection/get-started/requirements)
- [Brzo pokretanje obuka za Azure zaštitu informacija](https://docs.microsoft.com/azure/information-protection/get-started/infoprotect-quick-start-tutorial)
- [Preuzimanje programa za zaštitu od Azure informacija](https://www.microsoft.com/download/details.aspx?id=53018)

---
title: Zaglavljena u otpremnom poštanskom sandučetu zbog velikih priloga
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232644"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Popravljanje poruka koje su zaglavljena u otpremnom poštanskom sandučetu

Preporučujemo da počnete pokretanjem scenarija "Imam problema sa [slanjem, prijemom ili pronalaženjem e-poruka"](https://aka.ms/SaRA-OutlookSendReceive) sa Microsoft alatke " [Pomoćnik za podršku i oporavak](https://diagnostics.office.com/#/) " na računaru sa pogođenim računarom.

Kada se poruka zaglavi u vašem otpremnom poštanskom sandučetu, Najverovatniji uzrok je veliki prilog ili opcija "Pošalji odmah kada veza" nije omogućena.

**Uklanjanje velikog priloga**

1. Kliknite na dugme **Pošalji/primi** > **van mreže**. 
2. U oknu za navigaciju izaberite stavku **Otpremno poštansko sanduče**. Odavde možete da: 
    - Izbrišite poruku. Samo ga izaberite i kliknite na dugme **Izbriši**.
    - Prevucite poruku u **fasciklu "radne verzije**", dvaput kliknite da biste otvorili poruku i izbrišite prilog (kliknite na nju i kliknite na dugme " **Izbriši**").
3. Ako vam greška saopštava da Outlook pokušava da prenese poruku, zatvorite Outlook. Za izlazak može potrajati nekoliko trenutaka. Ako se Outlook ne zatvori, pritisnite **tastere CTRL + ALT + DELETE** i kliknite na dugme " **Pokreni Menadžer zadataka**". U upravljaču zadacima izaberite karticu **procesi** , pomerite se nadole do stavke Outlook. exe, a zatim izaberite stavku **završi proces**.
4. Nakon što se Outlook zatvori, ponovo pokrenite Outlook i ponovite korake 2-3. 
5. Kada uklonite prilog, kliknite na dugme " **Pošalji/primi** > **rad van mreže** " da biste poništili izbor dugmeta i nastavili sa radom na mreži. 

Poruke se takođe zaglave u otpremnom poštanskom sandučetu kada kliknete na dugme " **Pošalji**", ali niste povezani. Kliknite na dugme " **Pošalji/primi** " i pogledajte dugme " **radi van mreže** ". Ako je plava, veza je prekinuta. Kliknite na nju da biste se povezali (dugme postaje belo) i kliknite na dugme " **Pošalji sve**".
 
**Omogući slanje odmah nakon povezivanja**
 
1. Na kartici datoteka izaberite stavku **Opcije**.

2. U dijalogu "Opcije programa Outlook" kliknite na dugme " **Više opcija**".

3. U odeljku slanje i prijem kliknite da biste omogućili **Slanje odmah nakon povezivanja**. Kliknite na dugme **U redu**.
 
Za sve detalje pogledajte:
- [Video zapis: slanje ili brisanje zaglavljena e-poruke](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [E-poruka ostaje u fascikli "Otpremno poštansko sanduče" dok ručno ne pokrenete operaciju slanja/prijema u programu Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)

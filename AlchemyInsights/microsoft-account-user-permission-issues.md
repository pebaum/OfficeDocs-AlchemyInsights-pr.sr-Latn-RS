---
title: Da kreirate i koristite deljene poštansko sanduče
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 1825cfd0a78a29734d0a5128e19acbfba9115d32
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/04/2019
ms.locfileid: "34717360"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Poteškoća - korisnik nije pronađen u katalogu

<p>Ako korisnici dobijaju poruku o grešci <strong> &ldquo; &hellip;korisnik može&rsquo;t nije moguće pronaći u direktorijumu. Pokušajte ponovo&hellip; </strong> gde je tip problema <strong> &ldquo;korisnik nije u direktorijumu.&rdquo;</strong>, sledeći koraci mogu završiti rešavanje problema.</p> <ol> <li>Uverite se da nalog koji je prihvatio poziv email je isti konto koji se koristi za prijavljivanje u kasnije. Uverite se da korisnik koristi isti nalog da prihvati pozivnicu i prijaviti na lokaciji. <br /><br />Za više informacija, vidi <a href="https://support.microsoft.com/en-us/help/12407/microsoft-account-how-to-manage-aliases">kako upravljati pseudonime za Microsoft nalog</a> se upravlja Office 365 prijavljivanje. <br /><br /></li> <li>Pronađite svaki site(s) u kojem korisnik prima grešku. <br /><br />jedan. Dodajte <strong> &ldquo;/_layouts/15/people.aspx/membershipgroupid=0&rdquo; </strong> (unutar dvostruke navodnike) na kraj URL lokacije. <br /><br />Primer: https://&lt;contoso&gt;.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0 <br /><br />b. Izaberite korisnika iz liste. <br /><br />c. Kliknite na dugme <strong>Ukloni korisničke dozvole sa glavne trake</strong>. <br /><br />d. Ponovo dodajte korisnika i ponovo pošaljite pozivnicu za korisnika.</li> </ol>


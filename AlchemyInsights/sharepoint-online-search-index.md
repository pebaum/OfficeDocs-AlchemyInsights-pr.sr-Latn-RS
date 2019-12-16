---
title: Pretraga u sistemu SharePoint online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044057"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a>Popisivanje i indeksiranje sadržaja u sistemu SharePoint online

Sadržaj mora biti popisan i dodat indeksu pretrage da bi korisnici pronašli ono što traže u sistemu SharePoint online. Sadržaj se automatski popisuje na osnovu unapred definisanog rasporeda popisivanja (raspored popisivanja ne može biti promenjen). Pauk bira sadržaj koji se promenio od poslednjeg popisivanja i ažurira indeks. Da biste se uverili da je sadržaj popisan, a indeks ažuriran, imajte na umu sledeće:

- Uverite se da sadržaj možete pronaći tako što ćete [izvršiti pretraživo sadržaj lokacije](https://docs.microsoft.com/sharepoint/make-site-content-searchable).

- Kada promenite upravljano svojstvo ili kada ste promenili mapiranje popisanih i upravljanih svojstava, lokacija mora biti ponovo popisana pre nego što se promene odraze u indeks pretrage. 

    Pošto su promene napravljene u šemi pretrage, a ne na trenutnoj lokaciji, pauk neće automatski ponovo indeksirati lokaciju. 

    Više informacija potražite u članku [ručno traženje popisivanja i ponovno indeksiranje lokacije, biblioteke ili liste](https://docs.microsoft.com/sharepoint/crawl-site-conten).

- Sačekajte najmanje 24 časa nakon što ručno zahtevate popisivanje i kompletan reindeks da biste videli da li i dalje dolazi do problema. 

    Ako je prošlo više od 24 časa od kada ste pokrenuli popisivanje i puni ponovo indeks, evidentirali ste predmet podrške. U mnogim slučajevima već radimo na rešenju. Molimo vas da nam date najmanje 24 sata da završimo rešenje.

> [!IMPORTANT]
> Ako je lokacija, dokument (biblioteka) ili lista izbrisana, a i dalje prikazana u rezultatima pretrage, korisnici bi trebalo da dobiju **grešku 404 datoteku koja nije pronađena** kada pokušate da joj pristupite. Ovaj problem bi trebalo da bude evidentiran kao predmet podrške za dalju istragu. 




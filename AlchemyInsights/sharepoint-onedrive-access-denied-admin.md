---
title: Rešavanje problema sa programom Access je porekao poruke
ms.author: pebaum
author: pebaum
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 57919e6dbd81a5bf3b17fb067485e8eec23b7d4c
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051439"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Rešavanje problema sa pristupom odbijen je pristup porukama u sistemu SharePoint/OneDrive admin Center

Ako dobijate poruku o zabranama pristupa kada pokušate da potražite SharePoint/OneDrive admin Center, uverite se da ste [korisniku dodelili licencu](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Ako korisnik ima licencu, trebalo bi takođe da se uverite da su [dodeljene administratorskom ulogom](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) koja može da pristupi administratorskim centrima.

Do ovog problema može doći i kada se korisnik izbriše i ponovo kreira sa istim glavnim korisničkim imenom (UPN). Novi nalog se kreira koristeći drugačiju PUID (Passport jedinstveni ID) vrednost. Kada korisnik pokuša da pristupi kolekciji lokacija ili usluzi OneDrive, korisnik ima neispravan PUID. Drugi scenario uključuje sinhronizaciju direktorijuma sa organizacionom jedinicom aktivnog direktorijuma (OU). Ako su korisnici već prijavljeni na SharePoint, a zatim se premeštaju u drugu i ponovo povezani sa SharePoint, može doći do ovog problema.

Da biste rešili ovaj problem, trebalo bi da vratite prvobitni UPNP korak sa koracima u članku, da [vratite korisnika u Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Napomena: ako OneDrive ili SharePoint admin Center nije dostupan većem broju korisnika koji su ranije imali pristup, možda postoji problem sa privremenim servisom.  [Proverite kontrolnu tablu usluge za zdravstvo](https://portal.office.com/adminportal/home#/servicehealth).



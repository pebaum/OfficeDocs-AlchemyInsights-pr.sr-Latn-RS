---
title: Rešavanje problema sa programom Access je porekao poruke
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 9430b9786b35dda9fb2604fb6ae3c39c8c258d6e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505393"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Rešavanje problema sa pristupom odbijen je pristup porukama u sistemu SharePoint/OneDrive admin Center

Ako dobijate poruku o zabranama pristupa kada pokušate da potražite SharePoint/OneDrive admin Center, uverite se da ste [korisniku dodelili licencu](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users). Ako korisnik ima licencu, trebalo bi takođe da se uverite da su [dodeljene administratorskom ulogom](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) koja može da pristupi administratorskim centrima.

Do ovog problema može doći i kada se korisnik izbriše i ponovo kreira sa istim glavnim korisničkim imenom (UPN). Novi nalog se kreira koristeći drugačiju PUID (Passport jedinstveni ID) vrednost. Kada korisnik pokuša da pristupi kolekciji lokacija ili usluzi OneDrive, korisnik ima neispravan PUID. Drugi scenario uključuje sinhronizaciju direktorijuma sa organizacionom jedinicom aktivnog direktorijuma (OU). Ako su korisnici već prijavljeni na SharePoint, a zatim se premeštaju u drugu i ponovo povezani sa SharePoint, može doći do ovog problema.

Da biste rešili ovaj problem, trebalo bi da vratite prvobitni UPNP korak sa koracima u članku, [vratite korisnika u aplikaciji Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).

Napomena: ako OneDrive ili SharePoint admin Center nije dostupan većem broju korisnika koji su ranije imali pristup, možda postoji problem sa privremenim servisom.  [Proverite kontrolnu tablu usluge za zdravstvo](https://portal.office.com/adminportal/home#/servicehealth).



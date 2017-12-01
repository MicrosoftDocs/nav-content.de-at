---
title: "Verwalten, löschen oder komprimieren von Belegen"
description: "Speichern Sie die historischen Daten oder löschen Sie sie."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 89e541c7d38d26204c403636e4df11b7468bffa9
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="manage-documents"></a>Verwalten von Belegen
Ein Benutzer mit einer zentralen Rolle, z. B. der Anwendungsadministrator, muss sich regelmäßig um die angesammelten historischen Belege kümmern, indem er diese löscht oder komprimiert.  

## <a name="delete-documents"></a>Belege löschen
Es kann gelegentlich erforderlich sein, erledigte Einkaufsbestellungen zu löschen, die noch nicht gelöscht wurden. [!INCLUDE[d365fin](includes/d365fin_md.md)] überprüft, ob Sie die gelöschten Bestellungen vollständig fakturiert haben. Sie können keine Bestellungen löschen, die noch nicht vollständig geliefert und fakturiert wurden.  

Reklamationen werden üblicherweise gelöscht, nachdem sie fakturiert wurden. Wenn Sie eine Rechnung buchen, wird sie in das Fenster **Geb. Einkaufsgutschrift** übertragen. Ist das Kontrollkästchen **Rücklieferung bei Gutschrift** im Fenster **Kreditoren & Einkauf Einr.** aktiviert, wird sie auch in das Fenster **Gebuchte Rücklieferung** übertragen. Belege können mithilfe der Stapelverarbeitung **Erledigte Eink.-Rekl. löschen** gelöscht werden. Vor dem Löschen prüft die Stapelverarbeitung, ob die Einkaufsreklamationen vollständig geliefert und fakturiert wurden.  

Rahmenbestellungen werden nicht gelöscht, nachdem Sie alle zugehörigen Bestellungen verarbeitet und fakturiert haben. Sie können erledigte Rahmenbestellungen mit Hilfe der Stapelverarbeitung **Erledigte Rahmenbestellungen löschen** löschen.  

Verrechnete Serviceaufträge werden automatisch gelöscht, nachdem diese vollständig fakturiert wurden. Beim Buchen einer Rechnung wird ein entsprechender Posten im Fenster **Gebuchte Servicerechnungen** erstellt. Der gebuchte Beleg kann im Fenster **Gebuchte Servicerechnung** angezeigt werden.  

Serviceaufträge werden aber nicht automatisch gelöscht, wenn die Gesamtmenge des Auftrags nicht aus dem eigentlichen Serviceauftrag, sondern im Fenster **Servicerechnung** gebucht wurde. In diesem Fall müssen Sie fakturierte Aufträge, die nicht gelöscht wurden, manuell löschen. Dazu führen Sie die Stapelverarbeitung **Fakturierte Serviceaufträge löschen** aus.  

## <a name="see-also"></a>Siehe auch  
[Einrichtung und Verwaltung in Dynamics NAV](admin-setup-and-administration.md)  


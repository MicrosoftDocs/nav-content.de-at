---
title: "Designdetails – Priorisieren von Aufträgen"
description: "Lesen, wie priorisiert wird, um Bedarf und Versorgungsbedarf zu erfüllen."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, priority, prioritize, order, sku, demand, supply
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c01ad1bb74e01ff81f35159865eddf14e9a34910
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-prioritizing-orders"></a>Designdetails: Priorisieren von Aufträgen
In bestimmten Lagerhaltungsdaten zeigt das angeforderte oder verfügbare Datum die höchste Priorität an; mit dem Bedarf des heutigen Tages soll vor dem Bedarf der nächsten Woche verfahren werden. Zusätzlich zu dieser allgemeinen Priorität schlägt das Planungssystem jedoch auch vor, welche Art von Bedarf vor anderen Bedarfen erfüllt werden soll. Ebenso empfiehlt es eine auszugleichende Versorgungsquelle vor anderen Versorgungsquellen. Dieses wird gemäß Auftragsprioritäten durchgeführt.  
  
Geladener Bedarf und Vorrat tragen zu einem Profil für den voraussichtlichen Lagerbestand entsprechend den folgenden Prioritäten bei:  
  
## <a name="priorities-on-the-demand-side"></a>Prioritäten der Bedarfs-Seite  
1. Bereits geliefert: Artikelposten  
2. Einkaufsreklamation  
3. Verkaufsauftrag  
4. Serviceauftrag  
5. Bedarf an Produktionskomponenten  
6. Montageauftragszeile  
7. Ausgehender Umlagerungsauftrag.  
8. Rahmenauftrag (der nicht bereits durch zugehörige Verkaufsaufträge verbraucht wurde)  
9. Planung (die nicht bereits durch andere Verkaufsaufträge verbraucht wurde)  
  
> [!NOTE]  
>  Einkaufsreklamationen sind normalerweise nicht Teil der Absatzplanung; sie sollten stets in der Charge reserviert sein, die zurückgegeben wird. Falls nicht reserviert, spielen Einkaufsreklamationen eine Rolle bei der Verfügbarkeit und werden hoch priorisiert, um zu vermeiden, dass das Planungssystem einen Beschaffungsauftrag vorschlägt, nur um eine Einkaufsreklamation zu erfüllen.  
  
## <a name="priorities-on-the-supply-side"></a>Prioritäten der Bedarfs-Seite  
1. Bereits im Bestand: Artikelposten (Planungs-Flexibilität = keine)  
2. Verkaufsreklamation (Planungs-Flexibilität = keine)  
3. Ausgehende Umlagerungsaufträge  
4. Fertigungsauftrag  
5. Montageauftrag  
6. Bestellung  
  
## <a name="priority-related-to-the-state-of-demand-and-supply"></a>Priorität in Bezug auf Status des Bedarfs und des Angebotes  
Abgesehen von den Prioritäten, die von dem Typ des Bedarfs oder des Vorrats vorgegeben werden, definiert der aktuelle Zustand der Aufträge im Ausführungsprozess ebenfalls eine Priorität. Beispielsweise haben Lageraktivitäten Auswirkungen, und der Status von Verkaufs-, Einkaufs-, Umlagerungs-, Montage- und Fertigunksaufträgen wird berücksichtigt:  
  
1. Teilweise bearbeitet (Planungs-Flexibilität = Nein)  
2. Bereits in Bearbeitung im Lager (Planungs-Flexibilität = keine)  
3. Freigegeben - alle Auftragsarten (Planungs-Flexibilität = unbegrenzt)  
4. Fest geplanter Fertigungsauftrag (Planungs-Flexibilität = unbegrenzt)  
5. Geplant/Offen – alle Ordnertypen (Planungs-Flexibilität = unbegrenzt)  
  
## <a name="see-also"></a>Siehe auch  
[Designdetails: Ausgleich von Bedarf und Vorrat](design-details-balancing-demand-and-supply.md)   
[Designdetails: Zentrale Konzepte des Planungssystems](design-details-central-concepts-of-the-planning-system.md)   
[Designdetails: Vorratsplanung](design-details-supply-planning.md)

---
title: "Setzen von Filtern für dynamische Zuteilungsgrundlagen"
description: "Die Methode der dynamischen Zuteilung basiert auf veränderbaren Werten. Zum Beispiel die Anzahl der Mitarbeiter in einer Kostenstelle oder die Artikel eines Kostenträgers, die in einem bestimmten Zeitraum verkauft wurden. Es gibt neun vordefinierte Zuteilungsgrundlagen und zwölf dynamische Datumsbereiche. Die verschiedenen Filter werden basierend auf der Zuteilungsgrundlage eingestellt."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8372f855cfaa19456ab597e163006ae20411defd
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="setting-filters-for-dynamic-allocation-bases"></a>Setzen von Filtern für dynamische Zuteilungsgrundlagen
Die Methode der dynamischen Zuteilung basiert auf veränderbaren Werten. Zum Beispiel die Anzahl der Mitarbeiter in einer Kostenstelle oder die Artikel eines Kostenträgers, die in einem bestimmten Zeitraum verkauft wurden. Es gibt neun vordefinierte Zuteilungsgrundlagen und zwölf dynamische Datumsbereiche. Die verschiedenen Filter werden basierend auf der Zuteilungsgrundlage eingestellt.  

## <a name="setting-filters-for-dynamic-allocation-bases"></a>Setzen von Filtern für dynamische Zuteilungsgrundlagen  
 Die nachstehende Tabelle zeigt, welche Filter für verschiedene Zuteilungsgrundlagen möglich sind und welche Werte in den Feldern **Filter-Nr.** und **Gruppenfilter** gültig sind. Drücken Sie F1 im Feld **Datenfiltercode**, um detaillierte Beschreibungen zu lesen.  

|**Bemessungsgrundlage**|**Nr. Filter**|**Datumsfiltercode**|**Kostenstellenfilter**|**Kostenträgerfilter**|**Gruppenfilter**|  
|--------------|----------------------------------------|----------------------------------------------|------------------------------------------------|------------------------------------------------|------------------------------------------|  
|Sachposten|Sachkonto|Ja|Ja|Ja|N/Z|  
|Finanzbudgetposten|Sachkonto|Ja|Ja|Ja|Finanzbudgetname|  
|Kostenartposten|Einstandspreisberechnung|Ja|Ja|Ja|N/Z|  
|Kostenbudgetposten|Einstandspreisberechnung|Ja|Ja|Ja|Budgetname|  
|Anzahl Mitarbeiter|N/Z|Ja|Ja|Ja|N/Z|  
|Verkaufte Artikel (Menge)|Artikelnr.|Ja|Ja|Ja|Lagerbuchungsgruppe|  
|Erworbene Artikel (Menge)|Artikelnr.|Ja|Ja|Ja|Lagerbuchungsgruppe|  
|Verkaufte Artikel (Betrag)|Artikelnr.|Ja|Ja|Ja|Lagerbuchungsgruppe|  
|Erworbene Artikel (Betrag)|Artikelnummer|Ja|Ja|Ja|Lagerbuchungsgruppe|  

## <a name="see-also"></a>Siehe auch  
 [Szenario-Beispiel: Definieren von dynamischen Zuteilungen auf der Basis der verkauften Artikel](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md)   
 [Vorgehensweise: Einrichten von Zuteilungsquellen und -zielen](finance-how-to-set-up-allocation-source-and-targets.md)   
 [Definieren und Zuweisen von Kosten](finance-define-and-allocate-costs.md)


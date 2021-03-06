---
title: "Vorgehensweise beim Übertragen von Sachposten in Kostenposten"
description: "Sie können Sachposten in Kostenposten übertragen."
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
ms.openlocfilehash: b7a78fb1023e8b664fd866eb1a8b5e42ff0de265
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-general-ledger-entries-to-cost-entries"></a>Vorgehensweise: Übertragen von Sachposten in Kostenposten
Sie können Sachposten in Kostenposten übertragen.  

Bevor Sie den Vorgang für das Übertragen von Sachposten in Kostenposten durchführen, müssen Sie die Übertragung vorbereiten, um manuelle Korrekturbuchungen zu vermeiden.  

## <a name="to-prepare-the-transfer"></a>So bereiten Sie die Übertragung vor  

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Kostenrechnungseinrichtung** ein und wählen dann den zugehörigen Link aus.  
2.  Stellen Sie im Fenster **Kostenrechnungseinrichtung** sicher, dass im Feld **Startdatum für Sachkontenübertragung** der richtige Wert eingetragen ist.  
3.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Kostenartenplan** ein und wählen dann den zugehörigen Link aus.  
4.  Im Fenster **Kostenartkarte** prüfen Sie, dass das **Sachkontobereich** Feld für jede Kostenart korrekt verknüpft ist, um Posten aus dem Sachkonto zu übernehmen.  
5.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") aus und geben **Kontenplan** ein. Wählen Sie dann den zugehörigen Link aus.  
6.  Überprüfen Sie für jedes Sachkonto im Fenster **Sachkontokarte**, ob das **Kostenartnr.** Feld wird korrekt zu einer Kostenart verknüpft. Weitere Informationen finden Sie unter [Definieren der Beziehung zwischen Kostenarten und Sachkonten](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md)  
7.  Vergewissern Sie sich, dass alle entsprechenden Sachposten Dimensionswerte haben, die einer Kostenstelle und zu einem Kostenträger entsprechen.  

## <a name="to-transfer-general-ledger-entries-to-cost-entries"></a>So übertragen Sie Sachposten in Kostenposten  
1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Sachposten in Kostenrechnung übertragen** ein und wählen dann den zugehörigen Link aus.  
2.  Wählen Sie auf Schaltfläche **OK**, um die Umlagerung zu starten. Der Prozess überträgt alle Sachposten, die nicht bereits übertragen wurden.  

    Während der Übertragung erstellt der Vorgang Verknüpfungen in den Posten **Posteneintrag** und **Kostentabelle**. Dies ermöglicht es Ihnen, die Herkunft von Kostenposten nachzuverfolgen.  

## <a name="see-also"></a>Siehe auch  
 [Kriterien für die Übertragung von Sachposten in Kostenposten](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md)   
 [Automatische Übertragung und kombinierte Posten](finance-automatic-transfer-combined-entries.md)   
 [Ergebnisse der Übertragung](finance-results-of-the-transfer.md)   
 [Übertragung und Buchung von Kostenzuteilungen](finance-transfer-and-post-cost-entries.md)   
 [Definieren der Beziehung zwischen Kostenarten und Sachkonten](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md)   


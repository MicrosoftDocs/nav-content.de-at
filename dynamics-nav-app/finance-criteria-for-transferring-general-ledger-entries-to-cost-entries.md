---
title: "Kriterien für die Übertragung von Sachposten in Kostenposten"
description: "Es ist wichtig, die Kriterien für den Transfer von Sachposten in Kostenposten zu kennen. Während des Transfers verwendet der Batchauftrag **Sachposten in Kostenrechnung übertragen** die folgenden Kriterien, um zu ermitteln, ob und wie die Sachposten transferiert werden sollen."
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
ms.openlocfilehash: 99b18cee56b6300cb1852265eed6d56206a2eaab
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="criteria-for-transferring-general-ledger-entries-to-cost-entries"></a>Kriterien für die Übertragung von Sachposten in Kostenposten
Es ist wichtig, die Kriterien für den Transfer von Sachposten in Kostenposten zu kennen. Während des Transfers verwendet der Batchauftrag **Sachposten in Kostenrechnung übertragen** die folgenden Kriterien, um zu ermitteln, ob und wie die Sachposten transferiert werden sollen.  

Sachposten werden transferiert, wenn Folgendes zutrifft:  

-   Die Posten haben Dimensionswerte, die entweder einer Kostenstelle oder einem Kostenträger entsprechen.  
-   Die Posten haben Dimensionswerte, die einer Kostenstelle und einem Kostenträger entsprechen. Bei diesen Posten hat die Kostenstelle Vorrang. Dies ist hilfreich, um eine Situation zu vermeiden, in der eine Kostenart sowohl in einem Kostenträger als auch in einer Kostenstelle auftritt und daher in der Statistik zweimal gezählt wird.  
-   Die Belegnummer in den Posten ist leer, sodass sie mit einer Belegnummer von 0000 in den Kostenposten angezeigt wird.  
-   Die Posten werden in eine Kostenart transferiert, die kombinierte Posten zulässt, und diese Posten werden als kombinierter monatlicher oder täglicher Posten transferiert.  

Sachposten werden nicht transferiert, wenn Folgendes zutrifft:  

-   Die Posten haben Dimensionswerte, die weder einer Kostenstelle noch einem Kostenträger entsprechen.  
-   Die Posten weisen einen Betrag von Null auf.  
-   Die Posten haben ein Sachkonto, das gelöscht wurde.  
-   Die Posten haben ein Sachkonto, das nicht vom Typ **GuV** ist.  
-   Die Posten haben ein Sachkonto, dem keine Kostenart zugeordnet ist.  
-   Die Posten haben ein Buchungsdatum vor **Startdatum für Sachkontenübertragung**.  
-   Die Posten wurden mit einem Abschlussdatum gebucht. Dies sind typische Posten, die den Saldo der GuV am Ende des Geschäftsjahres zurücksetzen.  

## <a name="see-also"></a>Siehe auch  
[Kostenrechnung](finance-manage-cost-accounting.md)  
 [Vorgehensweise: Übertragen von Sachposten in Kostenposten](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
 [Übertragung und Buchung von Kostenzuteilungen](finance-transfer-and-post-cost-entries.md)   
 [Informationen zur Kostenrechnung](finance-about-cost-accounting.md)  
 [Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


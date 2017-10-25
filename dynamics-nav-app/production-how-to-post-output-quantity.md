---
title: Vorgehensweise beim Stapelbuchen von Produktions-Warenabgang und Laufzeiten
description: Die fertig gestellte Menge stellt den Arbeitsfortschritt in Form der gefertigten Menge dar.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 266c3f52dda22133acebf6052326ab57551b2ec0
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-batch-post-output-and-run-times"></a>Vorgehensweise: Ausgabe über Stapelverarbeitung buchen und Bearbeitungszeiten prüfen
Die fertig gestellte Menge stellt den Arbeitsfortschritt in Form der gefertigten Menge dar.  

> [!NOTE]
> Nur wenn Sie die fertig gestellte Menge für den letzten Arbeitsgang buchen, dann aktualisiert die Anwendung automatisch den Lagerbestand.  

## <a name="to-post-output-quantities-for-one-or-more-production-order-lines"></a>Die fertig gestellte Mengen für eine oder mehrere Fertigungsauftragszeilen buchen
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Ausgabe-Buchblatt** ein und wählen den zugehörenden Link aus.  
2. Füllen Sie die Felder mit den Daten des Fertigungsauftrags und den Ausgabedaten aus. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Wenn der Arbeitsgang beendet ist, wählen Sie das Feld **Beendet** aus.  

    Wenn der Lagerort, in den die Artikel eingelagert werden sollen, Lagerplätze verwendet, die Bearbeitung der Einlagerung jedoch nicht erforderlich ist,  weisen Sie der Buch.-Blattzeile einen Lagerplatzcode zu, um festzulegen, wo die Artikel im Lagerort eingelagert werden sollen. Weitere Informationen finden Sie unter [Vorgehensweise: Produktionseinlagerung oder Montageausgabe](warehouse-how-to-put-away-production-output.md).  

4. Wählen Sie **Buchen** aus, um die Vorgänge zu buchen. Die fertig gestellte Menge wird gebucht. Der Artikel ist jetzt versandbereit.  

## <a name="to-post-run-times-for-one-or-more-production-order-lines"></a>Die Laufzeit für eine oder mehrere Fertigungsauftragszeilen buchen
Die Bearbeitungszeit stellt den Arbeitsfortschritt in Form der benötigten Arbeitszeit dar.    

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Ausgabe-Buchblatt** ein und wählen den zugehörenden Link aus.  
2. Füllen Sie die Felder mit den Daten des Fertigungsauftrags und den Ausgabedaten aus.  
3.  Wenn der Arbeitsgang beendet ist, wählen Sie das Feld **Beendet** aus.  
4. Wählen Sie die **Buchen** Aktion aus, um die Zeit zu buchen, die je Arbeitsgang aufgewendet wurde. Kapazitätsposten werden für die benötigte Arbeitsplätzen oder Arbeitsplatzgruppen aktualisiert.

## <a name="see-also"></a>Siehe auch  
[Produktion](production-manage-manufacturing.md)    
[Produktion einrichten](production-configure-production-processes.md)  
[Planung](production-planning.md)      
[Lagerbesttand](inventory-manage-inventory.md)  
[Einkauf](purchasing-manage-purchasing.md)  
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


---
title: 'Exemplarische Vorgehensweise: Eingang und Einlagerung in Basis-Lagerkonfigurationen'
description: "In [!INCLUDE[d365fin](includes/d365fin_md.md)] können die eingehenden Prozesse für das Empfangen und Einlagern auf vier Arten, mit den verschiedenen Funktionen, abhängig von der Lagerkomplexitätsebene, ausgeführt werden."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 0a540f5813ed67ee62e43390d6d11b7c3a137f13
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---
# <a name="walkthrough-receiving-and-putting-away-in-basic-warehouse-configurations"></a>Exemplarische Vorgehensweise: Eingang und Einlagerung in Basis-Lagerkonfigurationen
In [!INCLUDE[d365fin](includes/d365fin_md.md)] können die eingehenden Prozesse für das Empfangen und Einlagern auf vier Arten, mit den verschiedenen Funktionen, abhängig von der Lagerkomplexitätsebene, ausgeführt werden.  

|Art|Eingangsprozess|Lagerplätze|Geb. Umlag.-Eingänge|Einlagerungen|Komplexitätsebene anzeigen (siehe [Designdetails: Lagerhaus-Einrichtung](design-details-warehouse-setup.md))|  
|------------|---------------------|----------|--------------|----------------|--------------------------------------------------------------------------------------------------------------------|  
|A|Posteinlieferungsschein und die Einlagerung der Auftragszeile|X|||2|  
|B|Posteinlieferungsschein und Einlagerung aus dem Beleg "Lagereinlagerung"|||X|3|  
|C|Posteinlieferungsschein und Einlagerung aus einem Wareneingangsbeleg||X||4/5/6|  
|T|Posteinlieferungsschein aus einem Wareneingangsbeleg und Posteinlagerung aus einem Einlagerungsbeleg||X|X|4/5/6|  

Weitere Informationen finden Sie unter [Designdetails: Eingehender Lagerfluss](design-details-inbound-warehouse-flow.md).  

In der folgenden Vorgehensweise wird Methode B in der vorhergegangenen Tabelle beschrieben.  

## <a name="about-this-walkthrough"></a>Informationen zu dieser exemplarischen Vorgehensweise  
Bei Basis-Lagerkonfigurationen gilt Folgendes: Wenn ein Lagerort so eingerichtet wurde, dass die Bearbeitung der Einlagerung erforderlich ist, die des Wareneingangs jedoch nicht erforderlich ist, verwenden Sie das Fenster **Lagereinlagerung**, um Einlagerungs- und Wareneingangsinformationen für Ihre Herkunftsbelege zu erfassen und zu buchen. Der eingehende Herkunftsbeleg kann eine Einkaufsbestellung, eine Verkaufsreklamation, ein eingehender Umlagerungsauftrag oder ein Fertigungsauftrag sein, dessen Endprodukt zur Einlagerung bereitsteht.

> [!NOTE]
> Obwohl die Einstellungen **Kommissionierung erforderlich** und **Einlagerung erforderlich** genannt werden, können Sie weiterhin Wareneingänge und Lieferungen direkt aus den Quellgeschäftsunterlagen an Lagerorten, in denen Sie diese Kontrollkästchen aktivieren.  

In dieser exemplarischen Vorgehensweise werden folgende Aufgaben erläutert.  

-   Einrichtung des SILBERNEN Lagerorts für Einlagerungen.  
-   Einrichtung des SILBERNEN Lagerorts für Lagerplatzbehandlung.  
-   Definieren eines Standardlagerplatzes für Artikel LS-81. (LS-75 ist bereits in CRONUS eingerichtet.)  
-   Erstellen einer Bestellung für den Kreditor 10000 für 40 Lautsprecher.  
-   Überprüfen, dass Lagerplätze der Einlagerung durch Einrichtung voreingestellt werden.  
-   Freigeben der Bestellung für Lagerdurchlaufzeit.  
-   Erstellen einer Lagereinlagerung basierend auf einem freigegebenen Herkunftsbeleg.  
-   Überprüfen, dass Lagerplätze der Einlagerung von der Einkaufsbestellung übernommen werden.  
-   Erfassen der Lagerplatzumlagerung in das Lager und gleichzeitig Buchen der Einkaufslieferung für die ursprüngliche Einkaufsbestellung.  

## <a name="roles"></a>Rollen  
Die Aufgaben in dieser Demonstration werden von den folgenden Benutzerrollen ausgeführt:  

-   Lagerortleiter  
-   Einkäufer  
-   Lagermitarbeiter  

## <a name="prerequisites"></a>Voraussetzungen  
Für diese exemplarische Vorgehensweise gelten folgende Voraussetzungen:  

-   CRONUS International Ltd. installiert.  
-   Machen Sie sich anhand der nachfolgenden Schritte zu einem Lagermitarbeiter am Standort SILVER:  

    1.  Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Lagerhaus-Mitarbeiter** ein. Wählen Sie dann den zugehörigen Link aus.  
    2.  Wählen Sie das Feld **Benutzer-ID** aus, und wählen Sie Ihr eigenes Benutzerkonto im Fenster **Benutzer** aus.  
    3.  Geben Sie im Feld **Lagerortcode** SILVER ein.  
    4.  Wählen Sie das Feld **Standard** aus.  

## <a name="story"></a>Hintergrund  
Ellen, die Einkäuferin bei CRONUS International Ltd. erstellt eine Bestellung für 10 Einheiten des Artikels LS-75 und 30 Einheiten des Artikels LS-81 von dem Kreditor 10000, um zum SILBER Lagerhaus geliefert zu werden. Wenn die Lieferung im Lager eingeht, lagert John, der Lagermitarbeiter, die Artikel in die Standardlagerplätze ein, die für die Artikel eingerichtet sind. Wenn John Einlagerungen bucht, werden die Artikel gebucht als im Lager erhalten und verfügbar zum Verkauf oder anderen Bedarf.  

## <a name="setting-up-the-location"></a>Einrichten des Lagerorts  
 Das Einrichten des Fensters **Standortkarte** definiert die Warenflüsse des Unternehmens.  

### <a name="to-set-up-the-location"></a>So richten Sie den Lagerort ein  

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") aus und geben Sie **Lagerplätze** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Öffnen Sie die SILBERNE Lagerortkarte.  
3.  Aktivieren Sie das Kontrollkästchen **Einlagerung erforderlich**  

    Fahren Sie fort, um einen Vorgabelagerplatz für die beiden Artikelnummern einzurichten, um zu steuern, wo sie eingelagert werden.  

4.  Wählen Sie die Aktion **Lagerplätze** aus.  
5.  Wählen Sie die erste Zeile, für den Lagerplatz S-01-0001, und wählen die **Inhalt** Aktion aus.  

    Beachten Sie im Fenster **Lagerplatzinhalt**, dass der Artikel LS-75 bereits als Inhalt im Lagerplatz S-01-0001 eingerichtet wurde.  

6.  Wählen Sie die Aktion **Neu** aus.  
7.  Wählen Sie die Felder **Fest** und **Standard** .  
8.  Geben Sie im Feld **Belegnr.** den Wert LS-81 ein.  

## <a name="creating-the-purchase-order"></a>Erstellen der Bestellung  
Bestellungen sind die häufigste Art des eingehenden Herkunftsbelegs.  

### <a name="to-create-the-purchase-order"></a>Bestellung erstellen  

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Gebuchte Aufträge** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Erstellen Sie eine Bestellung für den Kreditor 10000 auf das Arbeitsdatum (23. Jänner) mit den folgenden Einkaufszeilen.  

    |Artikel|Lagerortcode|Lagerplatzcode|Menge|  
    |----------|-------------------|--------------|--------------|  
    |LS_75|SILBER|S-01-0001|10|  
    |LS-81|SILBER|S-01-0001|30|  

    > [!NOTE]  
    >  Der Lagerplatzcode wird automatisch gemäß der Einrichtung eingegeben, dem Sie im "Aufstellung Lagerort" Abschnitt zulassen.  

    Fahren Sie fort, das Lager zu informieren, dass die Einkaufsbestellung in Lagerdurchlaufzeit bereit ist, wenn die Lieferung eingeht.  

4.  Wählen Sie die Aktion **Freigabe** aus.  

    Der Warenausgang von Lautsprechern vom Lieferanten 10000 ist im SILBERNEN Lager eingetroffen, und John fährt fort, um sie einzulagern.  

## <a name="receiving-and-putting-the-items-away"></a>Erhalten und Einlagern der Artikel  
Im Fenster **Lagerkommissionierung** können Sie alle eingehenden Lageraktivitäten für einen bestimmten Herkunftsbeleg, wie einen Einkauf, verwalten.  

### <a name="to-receive-and-put-the-items-away"></a>Artikel erhalten und einlagern  

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") aus und geben Sie **Einlagerung** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Wählen Sie die Aktion **Neu** aus.  
3.  Wählen Sie das Feld **Herkunftsdokument** , und wählen Sie **Einkaufsauftrag** aus.  
4.  Wählen Sie das Feld **Herkunftsnr.** aus, wählen Sie die Zeile für den Einkauf von Kreditor 10000 aus, und wählen Sie dann die Schaltfläche **OK**.  

    Alternativ auf der Registerkarte **Aktionen**, in der Gruppe **Funktion**, wählen Sie **Herkunftsbeleg holen** und wählen Sie die Bestellung aus.  

5.  Wählen Sie die **Die zu verarbeitende Menge automatisch ausfüllen** Aktion aus.  

    Alternativ im Feld **Menge zu verarbeiten**geben Sie 10 und 30 jeweils auf den zwei Lagerkommissionierzeilen ein.  

6.  Wählen Sie die Aktion **Buchen** aus, wählen Sie die Option **Lieferung und Rechnung**, und wählen Sie dann die Schaltfläche **OK** aus.  

    Die 40 Lautsprecher werden nun erfasst, wie von den Lagereinlagerungsplätzen S-01-0001 kommissioniert, und ein positiver Artikelposten wird, die gebuchte Einkaufslieferung reflektierend, erstellt.  

## <a name="see-also"></a>Siehe auch  
 [So wird's gemacht: Artikel mit Lagereinlagerungen einlagern](warehouse-how-to-put-items-away-with-inventory-put-aways.md)   
 [Vorgehensweise: Einrichten von Basislagern mit Vorgangsbereichen](warehouse-how-to-set-up-basic-warehouses-with-operations-areas.md)   
 [Vorgehensweise: Umlagern von Komponenten in einen Arbeitsgangbereich in Basis-Lagerkonfigurationen](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)   
 [Vorgehensweise: Kommissionierung für die Produktion oder Montage](warehouse-how-to-pick-for-production.md)   
 [Vorgehensweise: Ad-hoc-Umlagerung von Artikeln in Basis-Lagerkonfigurationen](warehouse-how-to-move-items-ad-hoc-in-basic-warehousing.md)   
 [Designdetails: Eingehender Lagerfluss](design-details-inbound-warehouse-flow.md)   
 [Exemplarische Vorgehensweisen für Geschäftsprozesse](walkthrough-business-process-walkthroughs.md)  
 [Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

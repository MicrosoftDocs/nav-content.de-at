---
title: So erstellen Sie eine MwSt.-Abrechnung
description: "Sie können einen regelmäßigen Bericht der MsSt.-Transaktionen übermitteln. Die MwSt.-Abrechnung wird als FDF-Datei übermittelt. Dieses Dateiformat entspricht einer bearbeitbaren PDF-Datei der Steuerbehörde."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 93ff2c7374b65d55ea78dbb94aae9467de8ab685
ms.contentlocale: de-at
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-create-a-vat-statement"></a>Gewusst wie: Erstellen einer MwSt.-Abrechnung
[!INCLUDE[navnow](../../includes/navnow_md.md)] ermöglicht Ihnen, einen regelmäßigen Bericht der MsSt.-Transaktionen zu übermitteln. Die MwSt.-Abrechnung wird als FDF-Datei übermittelt. Dieses Dateiformat entspricht einer bearbeitbaren PDF-Datei der Steuerbehörde.  

> [!IMPORTANT]  
>  Vor der Erstellung der MwSt.-Erklärung müssen Sie detaillierte Informationen zu Ihrer Firmenadresse im Fenster „Firmendaten” angeben. Zu diesen Angaben zählen Straße, Hausnummer, Etage und Zimmernummer. Diese Informationen werden in die FDF-Datei aufgenommen.  

## <a name="to-create-a-vat-statement"></a>So erstellen Sie eine MwSt.-Abrechnung  

1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Nach Seite oder Bericht suchen"), geben Sie **MwSt.-Abrechnung AT** ein, und wählen Sie dann den zugehörigen Link.  
2.  Füllen Sie im Inforegister **Optionen** die Felder gemäß der Beschreibung in der folgenden Tabelle aus.  

    |Feld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Startdatum**|Gibt das Startdatum der MwSt.-Periode an.|  
    |**Enddatum**|Gibt das Enddatum der MwSt.-Periode an.|  
    |**MwSt.-Posten einschließen**|Gibt an, ob offene oder geschlossene oder sowohl offene als auch geschlossene MwSt.-Posten einbezogen werden.|  
    |**MwSt.-Posten einschließen**|Gibt an, ob nur MwSt.-Posten aus der angegebenen Periode oder auch MwSt.-Posten aus der vorhergehenden Periode eingebogen werden.|  
    |**Berichtstyp**|Markieren Sie, ob diese MwSt.-Abrechnung den vierteljährlichen Bericht, den monatlichen Bericht oder einen Bericht zu einer anderen Periode darstellt.|  
    |**Positionen prüfen**|Wählen Sie diese Option, um die Positionen der MwSt.-Abrechnung während des Exports zu überprüfen.|  
    |**Auf ganze Zahlen runden**|Hier wird ausgewählt, dass Beträge auf ganze Zahlen gerundet werden sollen.|  
    |**Für Zahlung von Verbindlichkeiten genutzter Überschuss**|Wählen Sie diese Option, wenn ein möglicher Überschuss zur Deckung anderer Verbindlichkeiten verwendet werden soll.|  
    |**Weitere per Post geschickte Rechnungen**|Wählen Sie diese Option, wenn Sie zusätzliche Informationen senden werden.|  
    |**Nummer §6 Abs. 1**|Geben Sie die Nummer gemäß §6 Absatz 1 an, wenn steuerfreie Einnahmen ohne Vorsteuerabzug geltend machen möchten.|  

3.  Wählen Sie die Schaltfläche **OK** aus.  
4.  Speichern oder öffnen Sie nach der entsprechenden Aufforderung die generierte XML-Datei und FDF-Datei.  

Wenn Ihre MwSt-Abrechnung fehlerfrei ist, können Sie die FDF-Datei an die Steuerbehörde übermitteln. Weitere Informationen finden Sie online unter [Finanz-Online portal](http://go.microsoft.com/fwlink/?LinkId=239929).  

## <a name="see-also"></a>Siehe auch  
[MwSt.-Abrechnung](vat-reporting.md)


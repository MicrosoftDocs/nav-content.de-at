---
title: Servicestatistik
description: "Mit der Funktion \"Servicestatistik\" können Sie sich schnell einen Überblick über den Inhalt eines gesamten Servicebelegs (Angebot, Rechnung oder Gutschrift) verschaffen, d. h. Sie können die Details zu den spezifischen Servicezeilen und Artikeln im Beleg anzeigen."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 0fab2eab4cc664696c6f3c3c50286c581e76627b
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---

# <a name="viewing-service-statistics"></a>So zeigen Sie die Servicestatistik an
Dynamics NAV kann einige Statistik zur Verfügung stellen, die Sie verwenden können, um Belege zu analysieren und zu bestimmen, wie Sie Ihre Dienstvorgänge verwalten sollen. Sie können Serviceverträge, Artikel, Bestellungen, Rechnungen, Gutschriften und Anfragen analysieren, indem Sie die **Statistik** Aktion auswählen. Für Serviceartikel und Verträge können Sie **Serviceartikel-Trendscape** oder **Servicevertrag-Trendscape** verwenden, um eine Zusammenfassung der Serviceposten für einen bestimmten Serviceartikel angezeigt.   

## <a name="viewing-statistics-for-service-orders"></a>So zeigen Sie die Serviceauftragsstatistik an
Die Funktion "Serviceauftragsstatistik" bietet Ihnen einen schnellen Überblick über den Inhalt des gesamten Serviceauftrags, über die Details zu bestimmten Servicezeilen und über Informationen zur Fakturierung, Lieferung und dem Verbrauch sowie über den Saldo des Debitors.  

Die statistischen Daten eines Serviceauftrags werden im Fenster **Serviceauftragsstatistik** des jeweiligen Auftrags angezeigt. Sie können das entsprechende Statistikfenster aus einem Serviceauftrag öffnen. Das Fenster **Serviceauftrag** wählen Sie **Statisitk**. Auf den Inforegistern in diesem Fenster werden u. a. die Menge, der Betrag, der MwSt.-Betrag, der Einstandspreis, der Deckungsbeitrag und das Kreditlimit des Debitors angezeigt. Die Beträge im Fenster werden – sofern nichts anderes angegeben wird – in der Währung des Serviceauftrags angezeigt.  

### <a name="view-totals-for-a-service-order"></a>Anzeigen von Summen für einen Auftrag  
Die Daten umfassen den Gesamtbetrag der Servicezeilen (mit und ohne MwSt.), MwSt.-Anteil, Einstandspreis sowie DB der Servicezeilen. Das Fenster zeigt auch die artikelspezifischen Informationen, wie Gewicht, Volumen und Menge an Paketen.  

### <a name="view-shipping-information"></a>Ansichtsversandinformationen  
Auf diesem Inforegister werden die Informationen über die zu liefernden Artikel, Ressourcen und/oder Kosten angezeigt. Die Anwendung verwendet die im Feld **Zu liefern** für die einzelnen Servicezeilen angegebenen Werte, um die Informationen bereitzustellen.  

### <a name="view-order-details"></a>Auftragsdetails anzeigen  
Auf diesem Inforegister werden Informationen zu den Artikeln, Ressourcenstunden und Kosten angezeigt, die fakturiert und verbraucht werden sollen. Die Berechnungen sind in der folgenden Tabelle beschrieben.  

|Spalte | Description|  
|------------|---------------------------------------|  
|**Fakturierung**|Enthält Beträge, die vom Serviceauftrag aus als fakturiert gebucht werden müssen.|  
|**Verbrauch**|Zeigt die Menge und die Kosten von Artikeln oder Ressourcen an, die als verbraucht gebucht wurden.|  
|**Summe**|Zeigt die Gesamtbeträge des Serviceauftrags an, die sich durch Addieren der Beträge für die Fakturierung mit den Beträgen für den Verbrauch ergeben.|  

### <a name="analyze-service-order-lines"></a>Serviceauftragspositionen analysieren  
Sie können die Informationen nach den Arten von Servicezeilen analysieren, die sich im Serviceauftrag befinden. Die Beträge werden einzeln für Folgendes angezeigt:  

* Artikel  
* Ressourcen  
* Kosten und Sachkonten  

### <a name="view-customer-information"></a>So zeigen Sie Debitoreninformationen an  
Dieses Inforegister enthält den Saldo des Debitorenkontos sowie das maximale Kreditlimit, das dem Debitor gewährt werden kann, für den Sie den Servicebeleg erstellt haben.

## <a name="viewing-service-item-statistics"></a>So zeigen Sie die Servicestatistik an
In dem Fenster **Serviceartikelstatistik** sind aktuelle Informationen über den Verbrauch, fakturierte Beträge und Deckungsbetrag eines bestimmten Artikels ersichtlich.  

* Ressourcen  
* Artikel  
* Servicekosten  
* Serviceverträge  
* Summe  

Für jede Postenart sind der fakturierte Betrag, der Verbrauchsbetrag, der Einstandsbetrag, die Menge, die fakturierte und die verbrauchte Menge, der Deckungsbeitrag und der Deckungsbeitrag in Prozent angegeben. Der Deckungsbeitrag in Prozent wird gemäß der folgenden Formel berechnet:  

* (Fakturierter Betrag - Verbrauch (Kosten)) x 100 / Fakturierter Betrag  

## <a name="using-trendscapes"></a>Trendscapes nutzen
Um Serviceartikel und Serviceverträgen stellt die Fenster **Serviceartikel-Trendscape** oder **Servicevertrags-Trendscape** eine Zusammenfassung der Serviceposten in einem Zeitraum für einen bestimmten Serviceartikel oder einen Vertrag. Um das Trendscape anzuzeigen, öffnen Sie den Serviceartikel oder den Servicevertrag, wählen Sie die **Statistik** Aktion aus, und wählen Sie dann **Trendscape** aus.

Wenn Sie mit den Bildlaufleisten den sichtbaren Fensterausschnitt verschieben, werden automatisch die Beträge für das gewählte Intervall berechnet. Alle Beträge aus den Serviceposten werden berechnet. Dabei handelt es sich um Posten, die beim Buchen von Serviceaufträgen oder Servicerechnungen erzeugt wurden.

Sie können die Liste filtern, indem Sie die Serviceartikel festlegen, die berücksichtigt werden sollen.  

> [!Tip]  
>  Wenn Sie die Periodenlänge auf **Tag** gesetzt haben und die Suche mit den Bildlaufleisten sehr lange dauert, können Sie auch ein größeres Intervall (z. B. **Quartal**) verwenden. Wenn Sie die gewünschte Periode gefunden haben, können Sie wieder auf das ursprüngliche Intervall umschalten, so dass detailliertere Daten angezeigt werden.   

## <a name="viewing-gains-and-losses-on-contracts"></a>Gewinne und Verluste auf Verträgen anzeigen  
Die Anwendung erstellt automatisch einen Gewinn- oder Verlustposten, wenn Vertragsangebote in Serviceverträge umgewandelt werden, wenn Vertragszeilen zum Servicevertrag hinzugefügt oder aus ihm entfernt werden und wenn Verträge gekündigt werden. Sie können Vertragsgewinne oder -verluste auf den folgenden Seiten anzeigen.  

|Seite | Description|  
|----------------|---------------------------------------|  
|**Vertrag Gew./Verl. (Verträge)**|Um den Vertragsgewinn/-verlust nach Servicevertrag anzuzeigen.|  
|**Vertrag Gew./Verl. (Gruppen)**|Um den Vertragsgewinn/-verlust nach Servicevertragsgruppe anzuzeigen.|  
|**Vertrag Gew./Verl. (Debitoren)**|Um den Vertragsgewinn/-verlust nach Debitor anzuzeigen.|  
|**Vertrag Gew./Verl. (Ursachen)**|Um den Vertragsgewinn/-verlust nach Ursachencode anzuzeigen.|  
|**Vertrag Gew./Verl. (Zust.Ein.)**|Um den Vertragsgewinn/-verlust nach Zuständigkeitseinheit anzuzeigen.|  

1. Um einen Bericht anzuzeigen, wählen Sie das Symbol ![Suche für Seite oder Bericht] (media/ui-search/search_small.png "Suche nach Seite oder Bericht")und geben Sie den Namen wie er in der Tabelle erscheint ein, und wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Filterkriterien aus, die Sie anwenden möchten. Wählen Sie beispielsweise im Fenster **Vertrag Gew./Verl. (Ursachen)** einen Wert für **Ursachencodefilter** aus.  
3. Wählen Sie die Aktion **Matrix anzeigen** aus.

## <a name="viewing-statistics-for-posted-service-documents"></a>Servicestatistik für gebuchte Service-Belege anzeigen
Mit der Funktion "Servicestatistik" erhalten Sie eine statistische Übersicht über den Inhalt von gebuchten Servicebelegen, wie gebuchte Lieferungen, Rechnungen und Gutschriften.  

Die statistischen Daten werden im Fenster "Servicestatistik" für den gebuchten Service angezeigt. Sie können das entsprechende Statistikfenster aus der gebuchten Servicelieferung, aus der gebuchten Servicerechnung oder den gebuchten Servicegutschriftbelegen öffnen. Für jede der Belegarten wählen Sie auf der Registerkarte **Start** in der Gruppe **Vorgang** **Statistik** aus. Um es zum Beispiel aus dem Fenster **Gebuchte Servicerechnungen** heraus zu öffnen, wählen Sie auf der Registerkarte **Start** in der Gruppe **Vorgang** die Option **Statistik** aus.  

### <a name="posted-service-shipment-statistics"></a>Geb. Servicelieferungsstatistik  
Das Fenster **Servicelieferungsstatistik** bietet Ihnen eine Übersicht über die gebuchte Servicelieferung. Das Fenster umfasst das Inforegister "Allgemein", auf dem Informationen zum physischen Inhalt der Lieferung angezeigt werden, z. B. die Menge der gelieferten Artikel, die Ressourcenstunden oder die Einstandspreise und das Gewicht sowie das Volumen der gelieferten Artikel.  

### <a name="posted-service-invoice-statistics"></a>Geb. Servicerechnungsstatistik  
Im Fenster **Servicerechnungsstatistik** wird eine statistische Zusammenfassung der gebuchten Servicerechnung angezeigt. Sie können die Summen der gebuchten Servicerechnung angezeigt. Die Daten umfassen den Gesamtbetrag der Servicezeilen (mit und ohne MwSt.), die als fakturiert gebucht wurden, MwSt.-Anteil, Einstandspreis sowie DB der gebuchten Rechnung. Die Spalten im Fenster zeigen darüber hinaus die folgenden Informationen an:  

* Die Artikel in den Servicerechnungszeilen, wie Gewicht, Volumen und Menge an Paketen.  
* Der Saldo des Debitorenkontos und der  maximale Kredit, den Sie für den Debitor erweitern können.  

### <a name="posted-service-credit-memo-statistics"></a>Statistik zu gebuchten Servicegutschriften  
Im Fenster **Servicegutschriftstatistik** erhalten Sie eine Übersicht über die Zeilen in einer gebuchten Servicegutschrift. Die Übersicht kann gehören:

* Auf dem Inforegister "Allgemein" werden die Gesamtbeträge der gebuchten Gutschrift sowie Informationen wie Menge, Betrag, MwSt., Einstandspreis und DB angezeigt. Das Inforegister enthält zudem spezifische Informationen über die Artikel in den Servicezeilen der gebuchten Gutschrift wie Menge, Gewicht und Volumen.  
* Das Inforegister "Debitor" enthält allgemeine Informationen zum Debitor, z. B. Kreditlimit und Kontosaldo.  

## <a name="see-also"></a>Siehe auch  
[Vorgehensweise: Erstellen von Serviceaufträgen](service-how-to-create-service-orders.md)   
[Vorgehensweise: Erstellen von Serviceartikeln](service-how-to-create-service-items.md)   
[Planungsservice](service-plan-service.md)  


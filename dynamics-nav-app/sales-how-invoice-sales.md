---
title: 'Vorgehensweise: Fakturieren'
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: cba338ec6469ea0ac22f024571664a718988e827
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-invoice-sales"></a>Vorgehensweise: Fakturieren

Sie erstellen eine Verkaufsrechnung oder eine Bestellung, um Ihre Vereinbarung mit dem Kunden zu erfassen, um bestimmte Produkte unter speziellen Liefer- und Zahlungsbedingungen zu verkaufen.

**Hinweis**: Sie müssen Verkaufsaufträge verwenden, wenn der Verkaufsprozess dies erfordert, dass Sie Teile einer Bestellmenge liefern können, weil beispielsweise die vollständige Menge nicht sofort verfügbar ist. Wenn Sie Artikel als Direktlieferung verkaufen, indem Sie direkt von Ihrem Kreditor an Ihren Debitor versenden, müssen Sie ebenfalls Verkaufsaufträge verwenden. Weitere Informationen finden Sie unter [So geht's: Direktlieferungen erstellen](sales-how-drop-shipment.md) In allen anderen Aspekten ist das Vorgehen bei Verkaufsaufträgen gleich wie bei Verkaufsrechnungen. Weitere Informationen finden Sie unter [So geht's: Produkte verkaufen](sales-how-sell-products.md)

Sie können mit dem Debitor verhandeln, indem Sie zuerst ein Verkaufsangebot erstellen, das Sie in eine Verkaufsrechnung umwandeln können, wenn Sie dem Verkauf zustimmen. Weitere Informationen finden Sie unter [Vorgehensweise: Angebote erstellen](sales-how-make-offers.md)

Nachdem der Debitor die Vereinbarung bestätigt hat, beispielsweise nach dem Angebotsprozess, buchen Sie die Verkaufsrechnung, um Ihre Verpflichtung zu erfassen, die Produkte wie vereinbart zu liefern. Wenn Sie die Verkaufsrechnung buchen, können Sie das Dokument als PDF-Dateianhang auch senden. Sie können den E-Mail-Text haben, der mit einer Zusammenfassung der Rechnung und der Zahlungsinformationen, wie ein Link zu Paypal, vorab ausgefüllt wurde. Weitere Informationen finden Sie unter [Vorgehensweise: Senden von Belegen per E-Mail](ui-how-send-documents-email.md).

Im betrieblichen Umfeld, in dem der Debitor bezahlen muss, bevor Produkte, wie in der Einzelhandelsbranche, geliefert werden, müssen Sie den Zahlungseingang für die Produkte abwarten, bevor Sie die Produkte liefern. In den meisten Fällen verarbeiten Sie eingehende Zahlungen einige Wochen nach Lieferung, indem Sie die Zahlungen in ihre entsprechenden gebuchten, unbezahlten Verkaufsrechnungen übernehmen. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).

Wenn die gebuchte Verkaufsrechnung bezahlt ist, müssen Sie eine Verkaufsgutschrift erstellen, um den Verkauf zu stornieren. Weitere Informationen finden Sie unter [Vorgehensweise: Retouren verarbeiten oder Stornieren](sales-how-process-sales-returns-cancellations.md).

Produkte können Lagerartikel und Dienstleistungen sein. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md). Der Verkaufsrechnungsprozess ist derselbe für beide Produkttypen.

**Hinweis**: In Dynamics NAV wird ein Produkt als “Artikel” bezeichnet.

Sie können die oberen Infoboxen des Verkaufsangebotes auf zwei Arten ausfüllen, abhängig davon, ob der Debitor bereits registriert ist.

## <a name="to-create-a-sales-invoice"></a>So erstellen Sie eine Verkaufsrechnung
1. Auf der Seite Homepage wählen Sie die Aktion **Verkaufsrechung** aus.  
3. Geben Sie im Feld **Debitor** den Namen eines vorhandenen Debitors ein.

    Andere Felder im Fenster **Verkaufsrechnung** werden nun mit den Standardinformationen vom ausgewählten Debitor ausgefüllt. Wenn der Debitor noch nicht erfasst wurde, dann führen Sie die folgenden Schritte durch:
4. Geben Sie im Feld **Debitor** den Namen eines neuen Debitors ein.
5. Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**, um die Übertragung zu bestätigen.
6. Im Fenster **Vorlage für neuen Debitor wählen** wählen Sie eine Vorlage, auf der die neue Debitorenkarte basieren soll, und dann wählen Sie die Schaltfläche **OK**.
7. Eine neue Debitorenkarte wird geöffnet, vorausgefüllt mit Informationen auf der ausgewählten Debitorenvorlage. Das Feld **Name** wird mit dem neuen Namen des Debitors vorab ausgefüllt, den Sie in der Verkaufsrechnung eingegeben haben.
8. Fahren Sie fort, die restlichen Felder auf der Debitorenkarte auszufüllen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Debitoren](sales-how-register-new-customers.md).  
9. Wenn Sie die Debitorenkarte abgeschlossen haben, wählen Sie die Schaltfläche **OK**, um zum Fenster **Verkaufsrechnung** zurückzugehen.

    Felder im Verkaufsrechnungskopf werden mit den Informationen, die Sie festgelegt haben, in der neuen Debitorenkarte ausgefüllt.
10. Füllen Sie im Fenster **Verkaufsrechnung** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

    Sie sind nun bereit, die Verkaufsrechnungszeilen mit Lagerartikeln oder Services auszufüllen, die Sie an den Kunden verkaufen möchten.

    Wenn Sie wiederkehrende Verkaufszeilen für den Debitor, wie einen Monatsersatzauftrag, eingerichtet haben, können Sie diese Zeilen auf der Rechnung durch Auswählen der Schaltfläche **Wiederkehrende Verkaufszeilen holen** einfügen.
11. Geben Sie im Inforegister **Zeilen** im Feld **Artikel** die Nummer eines Lagerartikels oder Service ein.  
12. Geben Sie in dem Feld **Menge** die Anzahl des Artikels an, der verkauft werden soll.

    **Hinweis**: Für Artikel des Typs Service ist die Menge eine Zeiteinheit wie Stunden, wie im Feld **Einheit des Messcodes** der Zeile angegeben.

    Das Feld **Zeilenmenge** wird aktualisiert, um den Wert im Feld **Einheitspreis** multipliziert ist mit dem Wert im Feld **Menge** anzuzeigen.

    Der Preis und der Zeilenbetrag auf den Verkaufsrechnungszeilen werden mit oder ohne MwSt. angezeigt je nachdem, was Sie im Feld **Preis inklusive Mehrwertsteuer** auf der Debitorenkarte ausgewählt haben.
13. Geben Sie im Feld **Zeilenrabatt in Prozent** einen Prozentsatz ein, wenn Sie dem Debitor einen Rabatt auf das Produkt gewähren möchten. Der Wert im Feld **Zeilenbetrag** wird entsprechend aktualisiert.

    Wenn Sie bestimmte Artikelpreise für den Debitor auf dem Inforegister **Verkaufspreise und Verkaufspreis-Zeilenrabatte** eingerichtet haben, werden der Preis und der Betrag auf der Rechnungszeile automatisch aktualisiert, wenn die vereinbarten Preiskriterien erfüllt sind. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
14. Um eine Bemerkung über die Angebotszeile hinzuzufügen, die der Debitor auf dem gedruckten Angebot anzeigen kann, schreiben Sie einen Text im Feld **Beschreibung**-in einer leeren Zeile.  
15. Wiederholen Sie die Schritte 10 bis 13 für jeden Artikel, den Sie an den Kunden verkaufen möchten.

    Die Summen unter den Zeilen werden berechnet, während Sie Zeilen erstellen oder ändern.
16. Geben Sie im Feld **Rabattbetrag in Rechnung stellen** einen Betrag ein, der vom Wert abgezogen werden soll, der im Feld **Total inklusive Mehrwertsteuer** im unteren Bereich der Rechnung angezeigt wird.

    Wenn Sie Rechnungsrabatte für den Debitor eingerichtet haben, wird der angegebene Prozentwert automatisch in das Feld **Rechnungsrabatt in Prozent** eingetragen, sobald die Kriterien erfüllt sein, und der entsprechende Betrag wird im Feld **Rechnungsbetrag mit Rabatt ohne Mehrwertsteuer** eingefügt. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
17. Wenn die Verkaufsrechnungszeilen ausgeführt werden, wählen Sie die Aktion **Buchen und Senden** aus.

Das Dialogfeld **Buchungs- und Sendebestätigung** wird geöffnet und zeigt die bevorzugte Sendemethode für den Debitor an. Sie können die Sendemethode ändern, indem Sie die Schaltfläche vom Feld **Beleg senden an** auswählen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Sendeprofilen](sales-how-setup-document-send-profiles.md).

Der zugehörige Artikel und die Debitorenposten werden nun im System erfasst erstellt, und die Verkaufsrechnung wird als PDF-Dokument ausgegeben. Die Verkaufsrechnung wird in der Liste der gebuchten Verkaufsrechnungen entfernt und durch einen neuen Beleg in der Liste der gebuchten Verkaufsrechnungen ersetzt.

## <a name="see-also"></a>Siehe auch  
[Verkauf verwalten](sales-manage-sales.md)  
[Auftrag einrichten](sales-setup-sales.md)  
[Lagerbest](inventory-manage-inventory.md)    
[Gewusst wie: Senden von Belegen über E-Mail](ui-how-send-documents-email.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


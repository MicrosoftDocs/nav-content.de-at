---
title: 'Gewusst wie: Produkte verkaufen'
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
ms.openlocfilehash: e45d67005364f7d45817d917ccaeab219b6f8446
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-sell-products"></a>Gewusst wie: Produkte verkaufen
Sie erstellen eine Verkaufsrechnung oder eine Bestellung, um Ihre Vereinbarung mit dem Kunden zu erfassen, um bestimmte Produkte unter speziellen Liefer- und Zahlungsbedingungen zu verkaufen.

**Hinweis**: Sie verwenden Verkaufsaufträge, wenn der Verkaufsprozess erfordert, dass Sie Teile einer Bestellmenge liefern können, weil beispielsweise die vollständige Menge nicht sofort verfügbar ist. Wenn Sie Artikel als Direktlieferung verkaufen, indem Sie direkt von Ihrem Kreditor an Ihren Debitor versenden, müssen Sie ebenfalls Verkaufsaufträge verwenden. Weitere Informationen finden Sie unter [So geht's: Direktlieferungen erstellen](sales-how-drop-shipment.md) In allen anderen Aspekten ist das Vorgehen bei Verkaufsaufträgen gleich wie bei Verkaufsrechnungen. Weitere Informationen finden Sie unter [Gewusst wie: Rechnungsverkäufe](sales-how-invoice-sales.md).

Sie können mit dem Debitor verhandeln, indem Sie zuerst ein Verkaufsangebot erstellen, das Sie in eine Verkaufsrechnung umwandeln können, wenn Sie dem Verkauf zustimmen. Weitere Informationen finden Sie unter [Vorgehensweise: Angebote erstellen](sales-how-make-offers.md)

Nachdem der Debitor die Vereinbarung bestätigt hat, beispielsweise nach dem Angebotsprozess, können Sie eine Auftragsbestätigung senden, um Ihre Verpflichtung zu erfassen, die Produkte wie vereinbart zu liefern.

Wenn Sie die Produkte teilweise oder gesamthaft liefern, buchen Sie die Verkaufsrechnung oder den Verkaufsauftrag als geliefert oder als geliefert und fakturiert, um den zugehörigen Artikel und die Debitorenposten im System zu erfassen. Wenn Sie den Verkaufsauftrag buchen, können Sie das Dokument auch als PDF-Dateianhang senden. Sie können den E-Mail-Text mit einer Zusammenfassung des Auftrags und der Zahlungsinformationen, wie ein Link zu Paypal automatisch ausfüllen lassen. Weitere Informationen finden Sie unter [Vorgehensweise: Senden von Belegen per E-Mail](ui-how-send-documents-email.md).

Im betrieblichen Umfeld, in dem der Debitor bezahlen muss, bevor Produkte, wie in der Einzelhandelsbranche, geliefert werden, müssen Sie den Zahlungseingang für die Produkte abwarten, bevor Sie die Produkte liefern. In den meisten Fällen verarbeiten Sie eingehende Zahlungen einige Wochen nach Lieferung, indem Sie die Zahlungen in ihre entsprechenden gebuchten, unbezahlten Verkaufsrechnungen übernehmen. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).

Wenn die gebuchte Verkaufsrechnung bezahlt ist, müssen Sie eine Verkaufsgutschrift erstellen, um den Verkauf zu stornieren. Weitere Informationen finden Sie unter [Vorgehensweise: Retouren verarbeiten oder Stornieren](sales-how-process-sales-returns-cancellations.md).

Produkte können Lagerartikel und Dienstleistungen sein. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md). Der Verkaufsangebotsprozess ist derselbe für beide Produkttypen.

**Hinweis**: In Dynamics NAV wird ein Produkt als “Artikel” bezeichnet.

Sie können die Debitorenfelder des Verkaufsangebotes auf zwei Arten ausfüllen, abhängig davon, ob der Debitor bereits registriert ist oder nicht.

## <a name="to-create-a-sales-order"></a>So erstellen Sie einen Verkaufsauftrag
1. Auf der Startseite wählen Sie die Aktion **Verkaufsauftrag** aus.  
2. Geben Sie im Feld **Debitor** den Namen eines vorhandenen Debitors ein.

    Andere Felder im Fenster **Verkaufsangebot** werden nun mit den Standardinformationen vom ausgewählten Debitor ausgefüllt. Wenn der Debitor noch nicht erfasst wurde, dann führen Sie die folgenden Schritte durch:

3. Geben Sie im Feld **Debitor** den Namen eines neuen Debitors ein.
4. Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**, um die Übertragung zu bestätigen.  
5. Im Fenster **Vorlage für neuen Debitor wählen** wählen Sie eine Vorlage, auf der die neue Debitorenkarte basieren soll, und dann wählen Sie die Schaltfläche **OK**.

    Eine neue Debitorenkarte wird geöffnet, vorausgefüllt mit Informationen auf der ausgewählten Debitorenvorlage. Das Feld **Name** wird mit dem neuen Namen des Debitors vorab ausgefüllt, den Sie im Verkaufsauftrag eingegeben haben.
6. Fahren Sie fort, die restlichen Felder auf der Debitorenkarte auszufüllen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Debitoren](sales-how-register-new-customers.md).  
7. Wenn Sie die Debitorenkarte abgeschlossen haben, wählen Sie die Schaltfläche **OK**, um zum Fenster **Verkaufsangebot** zurückzugehen.

    Felder im Verkaufsangebot werden mit den Informationen, die Sie festgelegt haben, in der neuen Debitorenkarte ausgefüllt.
8. Füllen Sie im Fenster **Verkaufsangebot** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

    Sie sind nun bereit, die Verkaufsangebotszeilen mit Lagerartikeln oder Services auszufüllen, die Sie an den Kunden verkaufen möchten.

    Wenn Sie wiederkehrende Verkaufszeilen für den Debitor wie einen Monatsersatzauftrag, eingerichtet haben, können Sie diese Zeilen auf der Rechnung durch Auswählen der Schaltfläche **Wiederkehrende Verkaufszeilen holen** einfügen.
9. Geben Sie im Inforegister **Zeilen** im Feld **Artikel** die Nummer eines Lagerartikels oder Service ein.  
10. Geben Sie in dem Feld **Menge** die Anzahl des Artikels an, der verkauft werden soll.

    **Hinweis**: Für Artikel des Typs Service ist die Menge eine Zeiteinheit wie Stunden, wie im Feld **Einheit des Messcodes** der Zeile angegeben.

    Das Feld **Zeilenmenge** wird aktualisiert, um den Wert im Feld **Einheitspreis** multipliziert ist mit dem Wert im Feld **Menge** anzuzeigen.

    Der Preis und der Zeilenbetrag auf den Verkaufsrechnungszeilen werden mit oder ohne MwSt. angezeigt je nachdem, was Sie im Feld **Preis inklusive Mehrwertsteuer** auf der Debitorenkarte ausgewählt haben.
11. Geben Sie im Feld **Zeilenrabatt in Prozent** einen Prozentsatz ein, wenn Sie dem Debitor einen Rabatt auf das Produkt gewähren möchten. Der Wert im Feld **Zeilenbetrag** wird entsprechend aktualisiert.

    Wenn Sie bestimmte Artikelpreise für den Debitor auf dem Inforegister **Verkaufspreise und Verkaufspreis-Zeilenrabatte** eingerichtet haben, werden der Preis und der Betrag auf der Rechnungszeile automatisch aktualisiert, wenn die vereinbarten Preiskriterien erfüllt sind. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
12. Um eine Bemerkung über die Angebotszeile hinzuzufügen, die der Debitor auf dem gedruckten Angebot anzeigen kann, schreiben Sie einen Text im Feld **Beschreibung**-in einer leeren Zeile.  
13. Wiederholen Sie die Schritte 10 bis 13 für jeden Artikel, den Sie an den Kunden verkaufen möchten.

    Die Summen unter den Zeilen werden berechnet, während Sie Zeilen erstellen oder ändern.
14. Geben Sie im Feld **Rabattbetrag in Rechnung stellen** einen Betrag ein, der vom Wert abgezogen werden soll, der im Feld **Total inklusive Mehrwertsteuer** im unteren Bereich der Rechnung angezeigt wird.

    Wenn Sie Rechnungsrabatte für den Debitor eingerichtet haben, wird der angegebene Prozentwert automatisch in das Feld **Rechnungsrabatt in Prozent** eingetragen, sobald die Kriterien erfüllt sein, und der entsprechende Betrag wird im Feld **Rechnungsbetrag mit Rabatt ohne Mehrwertsteuer** eingefügt. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
15. Um nur einen Teil der Auftragsmenge zu liefern, geben Sie die Menge im Feld **Menge für Versand** ein. Der Wert wird in das Feld **Zu fakturierende Menge** kopiert.
16. Um nur einen Teil der Auftragsmenge zu fakturieren, geben Sie die Menge im Feld **Menge für Fakturierung** ein. Die zu fakturierende Menge kann nicht größer sein, als der Wert im Feld **Menge geliefert**.   
17. Wenn die Verkaufsangebotszeilen ausgeführt werden, wählen Sie die Aktion **Buchen und Senden** aus.
Das Dialogfeld **Buchungs- und Sendebestätigung** wird geöffnet und zeigt die bevorzugte Sendemethode für den Debitor an.

Sie können die Sendemethode ändern, indem Sie die Schaltfläche vom Feld **Beleg senden an** auswählen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Sendeprofilen](sales-how-setup-document-send-profiles.md).

Der zugehörige Artikel und die Debitorenposten werden nun im System erfasst erstellt, und das Verkaufsangebot wird als PDF-Dokument ausgegeben. Wenn der Auftrag vollständig gebucht wird, wird er aus der Liste von Verkaufsaufträgen entfernt und durch neue Belege in der Übersicht der gebuchten Verkaufsrechnungen und in der Liste gebuchter Lieferungen ersetzt.

## <a name="see-also"></a>Siehe auch  
[Verkauf verwalten](sales-manage-sales.md)  
[Auftrag einrichten](sales-setup-sales.md)  
[Lagerbest](inventory-manage-inventory.md)  
[Gewusst wie: Senden von Belegen über E-Mail](ui-how-send-documents-email.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


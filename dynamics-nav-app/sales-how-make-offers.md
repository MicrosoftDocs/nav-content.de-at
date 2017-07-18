---
title: 'Vorgehensweise: Machen Sie ein Angebot'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e126c755a9121c3a91f3af72f3f1ae14702a4701
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-offers"></a>Vorgehensweise: Machen Sie ein Angebot
Sie erstellen eine Angebotsrechnung, um Ihr Angebot für den Debitor zu erfassen, um bestimmte Produkte unter speziellen Lieferungs- und Zahlungsbedingungen zu verkaufen. Sie können das Verkaufsangebot an den Debitor senden, um das Angebot mitzuteilen. Sie können den Beleg als PDF-Dateianhang senden. Sie können den E-Mail-Text auch, der mit einer Zusammenfassung des Angebots vorab ausgefüllt wurde. Weitere Informationen finden Sie unter [Vorgehensweise: Senden von Belegen per E-Mail](ui-how-send-documents-email.md).

Während Sie mit dem Debitor verhandeln, können Sie das Verkaufsangebot ändern wie benötigt und erneut versenden. Wenn der Kunde das Angebot annimmt, wandeln Sie das Verkaufsangebot in eine Verkaufsrechnung, in der Sie den Verkauf verarbeiten. Weitere Informationen finden Sie unter [Vorgehensweise: Fakturieren von Verkäufen](sales-how-invoice-sales.md) und [Vorgehensweise: Neue Produkte verkaufen](sales-how-sell-products.md).

Produkte können Lagerartikel und Dienstleistungen sein. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md). Der Verkaufsangebotsprozess ist derselbe für beide Produkttypen.

**Hinweis**: In Dynamics NAV wird ein Produkt als “Artikel” bezeichnet.

Sie können die oberen Infoboxen des Verkaufsangebotes auf zwei Arten ausfüllen, abhängig davon, ob der Debitor bereits registriert ist oder nicht.

## <a name="to-create-a-sales-quote"></a>So erstellen Sie Verkaufsangebote:
1. Auf der Seite Homepage wählen Sie die Aktion **Verkaufsrechung** aus.  
2. Geben Sie im Feld **Debitor** den Namen eines vorhandenen Debitors ein.

    Andere Felder im Fenster **Verkaufsangebot** werden nun mit den Standardinformationen vom ausgewählten Debitor ausgefüllt. Wenn der Debitor noch nicht erfasst wurde, dann führen Sie die folgenden Schritte durch:

3. Geben Sie im Feld **Debitor** den Namen eines neuen Debitors ein.
4. Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**, um die Übertragung zu bestätigen.
5. Im Fenster **Vorlage für neuen Debitor wählen** wählen Sie eine Vorlage, auf der die neue Debitorenkarte basieren soll, und dann wählen Sie die Schaltfläche **OK**.
6. Eine neue Debitorenkarte wird geöffnet, vorausgefüllt mit Informationen auf der ausgewählten Debitorenvorlage. Das Feld **Name** wird mit dem neuen Namen des Debitors vorab ausgefüllt, den Sie in der Verkaufsrechnung eingegeben haben.
7. Fahren Sie fort, die restlichen Felder auf der Debitorenkarte auszufüllen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Debitoren](sales-how-register-new-customers.md).  
8. Wenn Sie die Debitorenkarte abgeschlossen haben, wählen Sie die Schaltfläche **OK**, um zum Fenster **Verkaufsangebot** zurückzugehen.

    Felder im Verkaufsangebot werden mit den Informationen, die Sie festgelegt haben, in der neuen Debitorenkarte ausgefüllt.
9. Füllen Sie im Fenster **Verkaufsangebot** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

    Sie sind nun bereit, die Verkaufsrechnungszeilen mit Lagerartikeln oder Diensten auszufüllen, die Sie an den Kunden verkaufen möchten.

    **Hinweis:**Wenn Sie wiederkehrende Verkaufszeilen für den Debitor, wie einen Monatsersatzauftrag, eingerichtet haben, können Sie diese Zeilen auf dem Angebot durch Auswählen der Schaltfläche **Wiederkehrende Verkaufszeilen holen** einfügen.
10. Geben Sie auf dem Inforegister **Zeilen** im Feld **Artikelnummer** die Nummer eines Lagerartikels oder Dienstes ein.
11. Geben Sie in dem Feld **Menge** die Anzahl der Artikel an, der verkauft werden soll.

    **Hinweis**: Für Artikel des Typs Service ist die Menge eine Zeiteinheit wie Stunden, wie im Feld **Einheit des Messcodes** der Zeile angegeben.

    Das Feld **Zeilenmenge** wird aktualisiert, um den Wert im Feld **Einheitspreis** multipliziert ist mit dem Wert im Feld **Menge** anzuzeigen.

    Der Preis und der Zeilenbetrag auf den Verkaufsrechnungszeilen werden mit oder ohne MwSt. angezeigt je nachdem, was Sie im Feld **Preis inklusive Mehrwertsteuer** auf der Debitorenkarte ausgewählt haben.
12. Geben Sie im Feld **Zeilenrabatt in Prozent** einen Prozentsatz ein, wenn Sie dem Debitor einen Rabatt auf das Produkt gewähren möchten. Der Wert im Feld **Zeilenbetrag** wird entsprechend aktualisiert.

    **Hinweis**: Wenn Sie bestimmte Artikelpreise für den Debitor auf dem Inforegister **Verkaufspreise und Verkaufspreis-Zeilenrabatte** eingerichtet haben, werden der Preis und der Betrag auf der Rechnungszeile automatisch aktualisiert, wenn die vereinbarten Preiskriterien erfüllt sind. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
13. Um eine Bemerkung über die Angebotszeile hinzuzufügen, die der Debitor auf dem gedruckten Angebot anzeigen kann, schreiben Sie einen Text im Feld **Beschreibung**-in einer leeren Zeile.  
14. Wiederholen Sie die Schritte 10 bis 13 für jeden Artikel, den Sie an den Kunden verkaufen möchten.

    Die Summen unter den Zeilen werden berechnet, während Sie Zeilen erstellen oder ändern.
15. Geben Sie im Feld **Rabattbetrag in Rechnung stellen** einen Betrag ein, der vom Wert abgezogen werden soll, der im Feld **Total inklusive Mehrwertsteuer** im unteren Bereich der Rechnung angezeigt wird.

    **Hinweis**: Wenn Sie Rechnungsrabatte für den Debitor eingerichtet haben, wird der angegebene Prozentwert automatisch in das Feld **Rechnungsrabatt in Prozent** eingetragen, sobald die Kriterien erfüllt sein, und der entsprechende Betrag wird im Feld **Rechnungsbetrag mit Rabatt ohne Mehrwertsteuer** eingefügt. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)
16. Wenn die Verkaufsangebotszeilen ausgeführt werden, wählen Sie die Aktion **E-Mail** oder **Drucken** aus.

    Wenn Sie **E-Mail** ausgewählt haben, wird automatisch eine PDF-Datei an die E-Mail-Nachricht für den Kunden angehängt. Sie können die E-Mail so festlegen, dass Sie eine Zusammenfassung des Angebots enthält. Weitere Informationen finden Sie unter [Vorgehensweise: Senden von Belegen per E-Mail](ui-how-send-documents-email.md).
17. Wenn der Kunde das Angebot annimmt, wählen Sie **Rechnung erstellen** oder **Auftrag vornehmen** aus.

Das Verkaufsangebot wird aus der Datenbank entfernt. Eine Verkaufsrechnung oder ein Verkaufsauftrag wird auf der Basis der Informationen im Verkaufsangebot erstellt, in dem Sie den Verkauf verarbeiten können. Im Feld **Angebotnummer** auf der erstellten Verkaufsrechnung oder im Verkaufsauftrag sehen Sie die Anzahl der Verkaufsangebote, aus dem sie erstellt wurde. Weitere Informationen finden Sie unter [Vorgehensweise: Fakturieren von Verkäufen](sales-how-invoice-sales.md) und [Vorgehensweise: Neue Produkte verkaufen](sales-how-sell-products.md).

## <a name="see-also"></a>Siehe auch  
[Verkauf verwalten](sales-manage-sales.md)  
[Auftrag einrichten](sales-setup-sales.md)  
[Gewusst wie: Senden von Belegen über E-Mail](ui-how-send-documents-email.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


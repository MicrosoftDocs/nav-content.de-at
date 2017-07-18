---
title: 'Vorgehensweise: Erfassen eines Einkaufs'
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
ms.openlocfilehash: 6d1933bf1e1c9236d34d429a4da84c907df13708
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-purchases"></a>Vorgehensweise: Erfassen eines Einkaufs
Sie erstellen eine Einkaufsrechnung oder Einkaufsbestellung, um die Kosten der Einkäufe zu erfassen und Kreditoren zu verfolgen. Wenn Sie einen Bestand steuern müssen, werden Einkaufsrechnungen und Einkaufsbestellungen auch verwendet, um Lagerbestände dynamisch zu aktualisieren, sodass Sie Ihre Lagerbestandskosten minimieren und besseren Kundenservice bereitstellen können. Die Einkaufskosten, einschließlich Servicekosten und Bestandswerte, die aus der Buchung von Einkaufsrechnungen oder -bestellungen resultieren, tragen zu den Gewinnzahlen und anderen finanziellen Kennziffern auf Ihrer Startseite bei.

**Hinweis**: Sie müssen Einkaufsbestellungen verwenden, wenn es für den Einkaufsprozess erforderlich ist, Teillieferungen einer Bestellmenge zu erfassen, weil beispielsweise die vollständige Menge beim Kreditor nicht sofort verfügbar ist. Wenn Sie Artikel als Direktlieferung verkaufen, indem Sie direkt von Ihrem Kreditor an Ihren Debitor versenden, müssen Sie ebenfalls Einkaufsbestellungen verwenden. Weitere Informationen finden Sie unter [So geht's: Direktlieferungen erstellen](sales-how-drop-shipment.md) In allen anderen Aspekten ist das Vorgehen bei Einkaufsbestellungen genau wie bei Einkaufsrechnungen. Das folgende Verfahren basiert auf einer Einkaufsrechnung. Die Schritte sind für eine Einkaufsbestellung ähnlich.

Wenn Sie den Lagerartikel erhalten haben oder die erworbene Dienstleistung abgeschlossen ist, buchen Sie die Einkaufsrechnung oder-bestellung, um Lagerbestands- und Finanzdatensätze zu aktualisieren und Zahlungen für den Kreditor entsprechend der Zahlungsbedingungen zu aktivieren. Weitere Informationen finden Sie unter [Zahlungen durchführen](payables-make-payments.md).

**Achtung**: Buchen Sie keine Einkaufsrechnung, bevor Sie die Produkte erhalten und die abschließenden Einkaufskosten kennen, einschließlich aller zusätzlichen Gebühren. Andernfalls werden Ihr Lagerwert und DB-Zahlen möglicherweise falsch sein.

Wenn Sie bereits für Produkte auf der gebuchten Einkaufsrechnung bezahlt haben, müssen Sie eine Einkaufsgutschrift erstellen, um den Einkauf zu stornieren. Weitere Informationen finden Sie unter [Vorgehensweise: Einkaufsretouren verarbeiten oder Stornieren](purchasing-how-process-purchase-returns-cancellations.md).

Produkte können Lagerartikel und Dienstleistungen sein. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md). Der Einkaufsrechnungsprozess ist derselbe für beide Produkttypen.



Sie können die oberen Infoboxen des Einkaufsangebotes auf zwei Arten ausfüllen, abhängig davon, ob der Kreditor bereits registriert ist.

## <a name="to-create-a-purchase-invoice"></a>Erstellen Sie eine neue Einkaufsrechnung.
1. Auf der Seite Homepage wählen Sie die Aktion **Einkaufsrechung** aus.  
2. Geben Sie im Feld **Kreditor** den Namen eines vorhandenen Debitors ein.

    Andere Felder im Fenster **Einkaufsrechnung** werden nun mit den Standardinformationen vom ausgewählten Kreditor ausgefüllt. Wenn der Kreditor noch nicht erfasst wurde, dann führen Sie die folgenden Schritte durch:
3. Geben Sie im Feld **Kreditor** den Namen eines neuen Kreditors ein.
4. Klicken Sie im Dialogfeld auf die Schaltfläche **Ja**, um den neuen Kreditor zu bestätigen.
5. Im Fenster **Vorlage für neuen Kreditor wählen** wählen Sie eine Vorlage, auf der die neue Kreditorenkarte basieren soll, und dann wählen Sie die Schaltfläche **OK**.
6. Eine neue Debitorenkarte wird geöffnet, vorausgefüllt mit Informationen auf der ausgewählten Debitorenvorlage. Das Feld **Name** wird mit dem neuen Namen des Kreditors vorab ausgefüllt, den Sie in der Einkaufsrechnung eingegeben haben.
7. Fahren Sie fort, die restlichen Felder auf der Kreditorenkarte auszufüllen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Kreditoren](purchasing-how-register-new-vendors.md).  
8. Wenn Sie die Kreditorenkarte abgeschlossen haben, wählen Sie die Schaltfläche **OK**, um zum Fenster **Einkaufsrechnung** zurückzugehen.

    Einige Felder im Fenster **Einkaufsrechnung** werden mit den Informationen, die Sie in der neuen Kreditorenkarte festgelegt haben, ausgefüllt.
9. Füllen Sie im Fenster **Einkaufsrechnung** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

    Sie können jetzt die Einkaufssrechnungszeilen mit Lagerartikeln oder Services auszufüllen, die Sie von Ihrem Kreditor gekauft haben.

    **Hinweis**: Wenn Sie wiederkehrende Einkaufszeilen für den Debitor, wie einen monatlichen Ersatzauftrag, eingerichtet haben, können Sie diese Zeilen auf der Rechnung durch Auswählen der Aktion **Wiederkehrende Einkaufszeilen abrufen** einfügen.
10. Geben Sie auf dem Inforegister **Zeilen** im Feld **Artikelnummer** die Nummer eines Lagerartikels oder Dienstes ein.
11. Geben Sie in dem Feld **Menge** die Anzahl des Artikels an, der eingekauft wird.

    **Hinweis**: Für Artikel des Typs **Service** ist die Menge eine Zeiteinheit wie Stunden, wie im Feld **Einheit des Messcodes** der Zeile angegeben.

    Das Feld **Zeilenmenge** wird aktualisiert, um den Wert im Feld **EK-Preis** multipliziert ist mit dem Wert im Feld **Menge** anzuzeigen.

    Der Preis und der Zeilenbetrag auf den Verkaufsrechnungszeilen werden mit oder ohne MwSt. angezeigt je nachdem, was Sie im Feld **Preis inklusive Mehrwertsteuer** auf der Kreditorenkarte ausgewählt haben.
12. Geben Sie im Feld **Rabattbetrag in Rechnung stellen** einen Betrag ein, der vom Wert abgezogen werden soll, der im Feld **Total inklusive Mehrwertsteuer** im unteren Bereich der Rechnung angezeigt wird.

    **Hinweis**: Wenn Sie Rechnungsrabatte für den Kreditor eingerichtet haben, wird der angegebene Prozentwert automatisch in das Feld **Kreditor Rechnungsrabatt in Prozent** eingetragen, sobald die Kriterien erfüllt sein, und der entsprechende Betrag wird im Feld **Rechnungsbetrag mit Rabatt** eingefügt.
13. Falls Sie die eingekauften Artikel oder Dienstleistungen erhalten, wählen Sie aus **Buchen**.

Der Einkauf ist nun im Bestand und in den Finanzdatensätzen reflektiert, und die Lieferantenzahlung ist aktiviert. Die Einkaufsrechnung wird in der Liste der gebuchten Einkaufsrechnungen entfernt und durch einen neuen Beleg in der Liste der gebuchten Einkaufsrechnungen ersetzt.

## <a name="see-also"></a>Siehe auch  
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Einkauf einrichten:](purchasing-setup-purchasing.md)  
[Vorgehensweise: Einkauf von Produkten für einen Verkauf](purchasing-how-purchase-products-sale.md)  
[Vorgehensweise: Einen neuen Kreditor registrieren](purchasing-how-register-new-vendors.md)  
[So geht's: Direktlieferungen vorbereiten](sales-how-drop-shipment.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


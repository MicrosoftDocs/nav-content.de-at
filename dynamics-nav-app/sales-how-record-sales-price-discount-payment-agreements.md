---
title: 'Gewusst wie: Verkaufspreise und Rabatte aufzeichnen'
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
ms.openlocfilehash: 2d6438108fb2c36bb6f0d44efddc053bd628d068
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a>Gewusst wie: Verkaufspreise und Rabatte aufzeichnen
Die unterschiedlichen Preis- und Zahlungsrichtlinien, die beim Verkauf an verschiedene Debitoren gelten, müssen so definiert werden, dass die vereinbarten Regeln und Werte für Verkaufsbelege übernommen werden, die für den Debitor erstellt werden.

Für die Preise können Sie besondere auf den Verkaufszeilen verschiedene Verkaufspreise einfügen, wenn eine bestimmte Kombination aus Debitor, Artikel, Mindestmenge, Einheit oder des Start-/Enddatum vorhanden ist.

Für die Rabatte können Sie zwei Arten von Verkaufsrabatten einrichten und verwenden:

|Rabattart |Beschreibung |
|--------------|------------|
|**Verkaufszeilenrabatt**|Ein Betrag mit Rabatt wird auf den Verkaufszeilen eingefügt, wenn eine bestimmte Kombination aus Debitor, Artikel, Mindestmenge, Einheit oder des Start-/Enddatum vorhanden ist. Diese Funktionalität gilt auf gleiche Weise für Verkaufsbelege.|
|**Rechnungsrabatt**|Ein prozentualer Rabatt, der gewährt wird, wenn der Wertbetrag aller Zeilen eines Einkaufsbelegs einen bestimmten Mindestwert übersteigt.|

Da Verkaufszeilenrabatte und Verkaufspreise auf einer Kombination aus Artikel und Debitor bestehen, können Sie diese Konfiguration auch auf der Artikelkarte des Artikels eingerichtet werden, für den die Regeln und Werte gelten.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>Um Verkaufspreise für einen Debitor zu erstellen:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kunde** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die entsprechende Debitorenkarte und klicken dann auf **Preise**.

    Das Feld **Verkaufsart** ist mit dem Code **Debitor** ausgefüllt und das Feld **Verkaufscode** enthält die Nummer des Debitoren.
3. Füllen Sie die Felder in der Zeile wie erforderlich aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
4. Füllen Sie eine Zeile für jede Kombination aus, die dem Debitor einen besonderen Preis gewährt.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>So erstellen Sie Verkaufszeilenrabatte für einen Debitor:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kunde** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die entsprechende Debitorenkarte und klicken dann auf **Zeilenpreise**.

    Das Feld **Verkaufsart** ist mit dem Code **Debitor** ausgefüllt und das Feld **Verkaufscode** enthält die Nummer des Debitoren.
3.  Füllen Sie die Felder in der Zeile wie erforderlich aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
4. Füllen Sie eine Zeile für jede Kombination aus, die dem Debitor einen besonderen Preis gewährt.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>Um Rechnungsrabattkonditionen für Einkäufe einzurichten:
Nachdem Sie sich entschieden haben, welche Debitoren für Rechnungsrabatte in Frage kommen, geben Sie die Rechnungsrabattcodes auf den Debitorenkarten ein, und richten Sie die Bedingungen für die einzelnen Codes ein.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kunde** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die Debitorenkarte für einen Debitor, der für Rechnungsrabatte in Frage kommt.
3. Geben Sie im Feld **Rechnungsrabattcode** einen Code für das jeweilige Rechnungsrabattfenster ein, das die Anwendung verwenden soll, um Rechnungsrabatte für den Debitor zu berechnen.

    **Hinweis**: Rechnungsrabattcodes werden durch Bestandskundenkarten dargestellt. Dies ermöglicht es Ihnen, Rechnungsrabattbedingungen schnell einem Debitor zuzuweisen, indem es den Namen eines anderen Debitors mit den selben Konditionen auswählt..

    Fahren Sie fort, um neue Verkaufsrechnungsrabatt-Bedingungen einzurichten.
4. Im Fenster **Debitorenkarte** wählen Sie die Aktion **Rechnungsrabatt** aus. Das Fenster **Debitorenrechnungsrabatte** wird geöffnet.
5. Geben Sie in dem Feld **Währungscode** den Code für die Währung ein, für die die Rechnungsrabattkonditionen gelten sollen. Wenn Sie Rechnungsrabattbedingungen in EUR einrichten möchten, dann lassen Sie das Feld leer.
6. Geben Sie im Feld **Minimalbetrag** den Mindestbetrag ein, den eine Rechnung aufweisen muss, um für einen Rabatt in Frage zu kommen.
7. Geben Sie im Feld **Rabatt** den Rechnungsrabatt als Prozentsatz des Rechnungsbetrages ein.
8. Wiederholen Sie die Schritte 5 bis 7 für jede Währung, für die der Debitor einen Rechnungsrabatt erhält.

Der Rechnungsrabatt wird jetzt eingerichtet und dem fraglichen Debitor zugewiesen. Wenn Sie den Debitorencode im Feld **Rechnungs-Rabattcode** für andere Debitorenkarten auswählen, wird derselbe Rechnungsrabatt diesen Kunden zugewiesen.

## <a name="see-also"></a>Siehe auch  
[Auftrag einrichten](sales-setup-sales.md)  
[Verkauf verwalten](sales-manage-sales.md)


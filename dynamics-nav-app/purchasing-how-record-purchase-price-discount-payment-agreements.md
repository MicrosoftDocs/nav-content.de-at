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
ms.openlocfilehash: f99bb0aeef2c25048b0da3e0476ae2d612bff562
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-record-purchase-prices-and-discounts"></a>Gewusst wie: Verkaufspreise und Rabatte aufzeichnen
Definieren Sie die verschiedenen Preis- und Rabattvereinbarungen, die beim Artikeleinkauf von unterschiedlichen Kreditoren gelten, damit die vereinbarten Regeln und Werte auf die für den Kreditor erstellten Einkaufsbelege angewendet werden.

Für die Preise können Sie besondere auf den Einkaufszeilen verschiedene Einkaufspreise einfügen, wenn eine bestimmte Kombination aus Kreditor, Artikel, Mindestmenge, Einheit oder des Start-/Enddatum vorhanden ist.

Für die Rabatte können Sie zwei Arten von Einkaufsrabatten einrichten und verwenden:

|Rabattart |Beschreibung |
|--------------|------------|
|**Einkaufszeilenrabatt**|Ein Betrag mit Rabatt wird auf den Einkaufszeilen eingefügt, wenn eine bestimmte Kombination aus Kreditor, Artikel, Mindestmenge, Einheit oder des Start-/Enddatum vorhanden ist. Diese Funktionalität gilt auf gleiche Weise für Einkaufsbelege.|
|**Rechnungsrabatt**|Ein prozentualer Rabatt, der gewährt wird, wenn der Wertbetrag aller Zeilen eines Einkaufsbelegs einen bestimmten Mindestwert übersteigt.|

Da Einkaufszeilenrabatte und Einkaufspreise auf einer Kombination aus Artikel und Kreditor basieren, kann diese Konfiguration auch auf der Artikelkarte erfolgen, auf der die Regeln und Werte definiert sind. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md).

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a>Einen Speziellen Einkaufspreis für einen Kreditor einrichten
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kreditoren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die relevante Kreditorenkarte, und klicken Sie dann auf die Aktion **Preise**.

    Das **Einkaufstyp**-Feld ist mit **Kreditor** vorausgefüllt und das Feld **Einkaufscode** ist mit der Kreditorennummer vorausgefüllt.
3. Füllen Sie die Felder in der Zeile wie erforderlich aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
4. Füllen Sie eine Zeile für jede Kombination aus, für die Sie dem Kreditor einen Einkaufszeilenrabatt gewähren.

## <a name="to-set-up-a-line-discount-for-a-vendor"></a>Um einen Zeilenrabatt für einen Kreditor einzurichten
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kreditoren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die relevante Kreditorenkarte, und klicken Sie dann auf die Aktion **Zeilenrabatte**.

    Das **Einkaufstyp**-Feld ist mit **Kreditor** vorausgefüllt und das Feld **Einkaufscode** ist mit der Kreditorennummer vorausgefüllt.
3. Füllen Sie die Felder in der Zeile wie erforderlich aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
4. Füllen Sie eine Zeile für jede Kombination aus, für die Sie dem Kreditor einen Einkaufszeilenrabatt gewähren.

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a>Um einen Rechnungsrabatt für einen Kreditor einzurichten
Wenn Ihre Kreditoren Sie informiert haben, welche Rechnungsrabatte sie gewähren, können Sie den Rechnungsrabattcode auf den Kreditorenkarten eingeben und Bedingungen für jeden Code einrichten.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kreditoren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die Kreditorenkarte für einen Kreditor, der für Rechnungsrabatte in Frage kommt.
3. Geben Sie im Feld **Rechnungsrabattcode** einen Code für die jeweilige Rechnungsrabattbedingungen ein, die zur Berechnung der Rabatte für den Kreditor verwendet werden sollen.

    **Hinweis**: Rechnungsrabattcodes werden durch vorhandene Kreditorenkarten dargestellt. Dies ermöglicht es Ihnen, Rechnungsrabattbedingungen schnell einem Kreditor zuzuweisen, indem es den Namen eines anderen Kreditors mit den selben Konditionen auswählt..

    Fahren Sie fort, um neue Einkaufssrechnungsrabatt-Bedingungen einzurichten.
4. Im Fenster **Kreditorenkarte** wählen Sie die Aktion **Rechnungsrabatt** aus. Das Fenster **Kreditorenrechnungsrabatte** wird geöffnet.
5. Geben Sie in dem Feld **Währungscode** den Code für die Währung ein, für die die Rechnungsrabattkonditionen gelten sollen. Wenn Sie Rechnungsrabattbedingungen in EUR einrichten möchten, dann lassen Sie das Feld leer.
6. Geben Sie im Feld **Minimalbetrag** den Mindestbetrag ein, den eine Rechnung aufweisen muss, um für einen Rabatt in Frage zu kommen.
7. Geben Sie im Feld **Rabatt** den Rechnungsrabatt als Prozentsatz des Rechnungsbetrages ein.
8. Wiederholen Sie die Schritte 5 bis 7 für jede Währung, für die der Kreditor einen Rechnungsrabatt erhält.

Der Rechnungsrabatt wird jetzt eingerichtet und dem fraglichen Kreditor zugewiesen. Wenn Sie den Kreditorencode im Feld **Rechnungs-Rabattcode** für andere Kreditorenkarten auswählen, wird derselbe Rechnungsrabatt diesen Kreditor zugewiesen.

## <a name="see-also"></a>Siehe auch  
[Einkauf einrichten:](purchasing-setup-purchasing.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)


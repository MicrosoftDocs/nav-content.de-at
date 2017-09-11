---
title: 'So geht''s: Arbeiten mit Katalogartikeln'
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6d99e06c167d3b86db97883c02c8bf5cd746ae10
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# So geht's: Arbeiten mit Katalogartikeln
Sie können Ihren Debitoren bestimmte Artikel als Dienstleistung anbieten, die Sie nicht im Lager verwalten möchten, bis Sie den Verkauf sie starten. Wenn Sie damit beginnen wollen, solche Artikel im Lager zu verwalten, können Sie sie auf zwei Arten in normale Artikelkarten umwandeln.

- Erstellen Sie eine neue Artikelkarte aus der Katalogartikelkarte auf Basis einer Vorlage.
- Wählen Sie einen Katalogartikel aus einer Verkaufszeile mit einem leeren **Artikel**-Feld. Wenn Sie den Verkauf buchen, wird für diesen Katalogartikel automatisch eine Artikelkarte erzeugt.

**Hinweis**: Sie können im Fenster **Verkaufsrechnung** keine Katalogartikel auswählen. Sie können Katalogartikel im Fenster **Verkaufschance** auswählen, aber der Katalogartikel wird nicht in einen normalen Artikel konvertiert, wenn Sie die Funktion **Auftrag erstellen** verwenden.

Ein Katalogartikel besitzt üblicherweise die Artikelnummer des Kreditoren, der diesen bereitstellt. Um die Konvertierung einer Katalogartikelkarte in eine normale Artikelkarte zu aktivieren, muß zunächst eingerichtet werden, wie die Kreditorenartikelnummerierung in Ihre eigene Artikelnummerierung umgewandelt wird.   

## So erstellen Sie einen Katalogartikel:
Katalogartikelkarten enthalten viel weniger Informationen als normale Artikelkarten, da Sie diese nur verwenden, um Angebote auf Anfragen oder auf andere Arten zu erstellen. Aus diesem Grund müssen sie in normale Artikelkarten konvertiert werden, bevor Sie Verkaufstransaktionen mit ihnen buchen können.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Katalogartikel** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus.
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

## So richten Sie ein, wie Katalogartikelnummern in Ihrer eigenen Nummerierung erstellt werden  
Um die Konvertierung einer Katalogartikelkarte in eine normale Artikelkarte zu aktivieren, muß zunächst festgelegt werden, wie die Kreditorenartikelnummerierung in Ihr eigenes Artikelnummernformat umgewandelt wird.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Katalogartikel Einrichtung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie die Felder je nach Bedarf aus.

## So konvertieren Sie einen Katalogartikel in einen normalen Artikel
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Katalogartikel** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die Karte für einen Katalogartikel, den Sie in einen normalen Artikel umwandeln wollen.
3. Wählen Sie im Fenster **Katalogartikelkarte** die Aktion **Artikel erstellen** aus.

Eine neue Artikelkarte, die mit Informationen des Katalogartikels und einer Vorlage des entsprechenden Artikels ausgefüllt ist, wird erstellt. Sie können dann die Felder in der neuen Artikelkarte nach Bedarf ausfüllen oder ändern. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md).

## So verkaufen Sie einen Katalogartikel und konvertieren ihn in einen normalen Artikel
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufsaufträge** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus. füllen Sie die Felder auf dem Inforegister **Allgemein** für alle Verkaufsaufträge aus.
3. Lassen Sie das Feld **Artikel** in einer neuen Verkaufszeile leer, wählen **Zeile**, **Funktionen** und dann **Katalogartikel**.

    Der Katalogartikel ist nun in einen normalen Artikel umgewandelt. Eine neue Artikelkarte, die mit Informationen des Katalogartikels und einer Vorlage des entsprechenden Artikels ausgefüllt ist, wird erstellt.
4. Wählen Sie im Fenster **Katalogartikel** den Katalogartikel aus, den Sie verkaufen möchten, und klicken Sie anschließend auf **OK**.
5. Wenn der Verkaufsauftrag ausgeführt wurde, wählen Sie die Aktion **Buchen** aus.

Sie können dann die Felder in der neuen Artikelkarte nach Bedarf ausfüllen oder ändern. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Produkte](inventory-how-register-new-products.md).

**Hinweis**: Für den Kreditor des Artikels wird automatisch ein Artikelreferenzdatensatz zwischen der Artikelnummer des Kreditors und Ihrer neuen Artikelnummer erstellt.

## Siehe auch
[Vorgehensweise: Ein neues Produkt registrieren](inventory-how-register-new-products.md)  
[Verwalten des Lagerbestands](inventory-manage-inventory.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


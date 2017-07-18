---
title: 'So geht''s: Anlagen abschreiben oder amortisieren'
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
ms.openlocfilehash: af71f30681d436ed5da1cd6cb3c2e13f86558631
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>So geht's: Anlagen abschreiben oder amortisieren
Abschreibung wird verwendet, um die Anschaffungskosten von Anlagen wie Maschinen und Ausrüstung über die Nutzungsdauer zu verteilen. Sie müssen für jede Anlage definieren, wie diese abgeschrieben wird.  

 Es gibt zwei Wege, Abschreibungen zu buchen:
- Automatisch durch Ausführen der Stapelverarbeitung **AfA berechnen**
- Manuell, unter Verwendung des Anlagen Fibu Buch.-Blattes.  

Dynamics NAV kann tägliche Abschreibungen berechnen, sodass Sie Abschreibungen für beliebige Perioden berechnen können. Sie können damit das aktuelle operative Ergebnis beispielsweise auf monatlicher, quartalsweiser oder jährlicher Basis analysieren. Die Berechnungen verwendet ein standardisiertes Jahr mit 360 Tagen und einen standardisierten Monat mit 30 Tagen. Weitere Informationen finden Sie unter [AfA-Methoden](fa-depreciation-methods.md).

Falls eine Anlage von verschiedenen Kostenstellen verwendet wird, kann die AfA automatisch entsprechend einer benutzerdefinierten Tabelle auf diese Kostenstellen verteilt werden.  

Sie können falsche AfA-Posten mit Hilfe der Stapelverarbeitung **Anlagenposten stornieren** stornieren. Danach können Sie die korrekten Beträge buchen, indem Sie die Stapelverarbeitung **AfA berechnen** erneut ausführen. Wenn Sie Fehler korrigieren, werden diese als Anlagenstornoposten gebucht.  

Die Indexierung wird verwendet, um die Werte allgemeinen Preisänderungen anzupassen. Die Stapelverarbeitung **Anlagen indexieren** kann verwendet werden, um die AfA-Beträge neu zu berechnen.  

## <a name="to-calculate-a-depreciation-automatically"></a>So berechnen Sie die AfA automatisch
Einmal monatlich oder in beliebigen anderen Intervallen können Sie die Stapelverarbeitung **AfA berechnen** ausführen. Anlagen, die verkauft wurden, auf der Anlagenkarte gesperrt oder inaktiv sind, und Anlagen, die die AfA-Methode "Manuell" verwenden, werden ausgelassen.    

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **AfA berechnen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Wählen Sie die Schaltfläche **OK** aus.  

    Die Stapelverarbeitung berechnet die AfA und erstellt Zeilen im Anlagen Fibu Buch.-Blatt.  
4. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen Fibu Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.

    Im Fenster **Anlagen-Fibu Buch.-Blatt** können Sie im Feld **Anzahl AfA-Tage** sehen, wie viele AfA-Tage berechnet wurden.  
5. Wählen Sie die Aktion **Buchen** aus.

## <a name="to-post-a-depreciation-manually-from-the-fixed-asset-gl-journal"></a>So buchen Sie eine AfA aus dem Anlagen Fibu Buch.-Blatt
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen-Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Erstellen Sie eine ursprüngliche Buch.-Blattzeile und füllen Sie die notwendigen Felder aus.
3. Wählen Sie im Feld **Anlagenbuchungsart** die **AfA**.
4. Wählen Sie die Aktion **Anlagengegenkonto einfügen**. Eine zweite Buch.-Blattzeile wird für das Gegenkonto erstellt, das für die AfA-Buchung eingerichtet ist. Weitere Informationen finden Sie im Abschnitt "So richten Sie Anlagenbuchungsgruppen ein" in [So geht's: Allgemeine Anlageninformationen einrichten](fa-how-setup-general.md).
5. Wählen Sie auf der Registerkarte **Start** die Option **Buchen** aus, um das Buch.-Blatt zu buchen.

Falls Sie Anlagenverteilungsschlüssel eingerichtet haben, um Beträge auf verschiedene Kostenstellen und/oder Kostenträger zu verteilen, werden die Beträge während der Buchung zugeordnet. Weitere Informationen finden Sie unter [So geht's: Allgemeine Anlageninformationen einrichten](fa-how-setup-general.md).

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>So berechnen Sie Verteilungen in Anlagen Fibu Buch.-Blättern
Falls eine Anlage von verschiedenen Kostenstellen verwendet wird, kann die AfA automatisch entsprechend einer benutzerdefinierten Tabelle auf diese Kostenstellen verteilt werden.  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen-Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.   
Erstellen Sie eine ursprüngliche Zeile und füllen Sie die notwendigen Felder aus.
3. Wählen Sie im Feld **Anlagenbuchungsart** die **Verteilung**.
4. Wählen Sie die Aktion **Anlagengegenkonto einfügen**. Eine zweite Buch.-Blattzeile wird für das Gegenkonto erstellt, das für die Buchung einer Verteilung eingerichtet wird.
5. Wählen Sie auf der Registerkarte **Start** die Option **Buchen** aus, um das Buch.-Blatt zu buchen.

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Kopiervorgänge zum Vorbereiten von Buchungen in mehrere AfA-Bücher verwenden  
Wenn Sie Zeilen in einem Buch.-Blatt für die Buchung auf ein AfA-Buch ausfüllen, können Sie die Zeilen in ein anderes Buch.-Blatt kopieren. Dann können diese Zeilen auf ein anderes AfA-Buch gebucht werden. Weitere Informationen finden Sie im Abschnitt "So buchen Sie Posten auf verschiedene AfA-Bücher".

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **AfA-Bücher** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Öffnen Sie das entsprechende AfA-Buch aus und aktivieren Sie dann das Kontrollkästchen **Kopien ermöglichen**.  

**Wichtig**: Wenn Sie das Feld **Kopiervorgang aktivieren** ausgewählt haben, dürfen Sie im Buch.-Blatt keine Nummernserien verwenden. Der Grund dafür ist, dass die Nummernserie für das Anlagen Fibu Buch.-Blatt nicht der Nummernserie im Anlagen Buch.-Blatt entspricht.

## <a name="to-post-entries-to-different-depreciation-books"></a>So buchen Sie Posten auf verschiedene AfA-Bücher  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen-Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Aktivieren Sie im Buch.-Blatt, das Sie zum Buchen der AfA verwenden möchten, das Kontrollkästchen **Kopiervorgang aktivieren**.
3. Füllen Sie die verbleibenden Felder je nach Bedarf aus.
4. Wählen Sie die Aktion **Buchen** aus.
5. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.

    Das Fenster **Anlagen Buch.-Blatt** enthält neue Zeilen für verschiedene AfA-Bücher entsprechend der Verdopplungsliste.   

6. Prüfen oder bearbeiten Sie die Zeilen, und wählen Sie dann die Aktion **Buchen** aus.

**Hinweis**: Eine andere Art, einen Posten in ein separates Buch zu kopieren, ist es, einen AfA-Buchcode im Feld **In AfA-Buch kopieren** anzugeben, wenn Sie eine Buch.-Blattzeile ausfüllen.

Sie können mit Hilfe der Stapelverarbeitung **AfA-Buch kopieren** Posten von einem AfA-Buch in ein anderes AfA-Buch kopieren. Die Stapelverarbeitung erstellt Buch.-Blattzeilen in dem Buch.-Blatt, das Sie in dem Fenster **Anlagen Buch.-Blatt Einr.** für das AfA-Buch angegeben haben, aus dem Sie kopieren möchten. Weitere Informationen finden Sie in der folgenden Prozedur.

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>So kopieren Sie Anlagenposten zwischen AfA-Büchern  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **AfA-Bücher** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die entsprechende AfA-Buch - Karte und wählen Sie dann die Aktion **AfA-Buch kopieren**.  
3. Füllen Sie im Fenster **AfA-Buch kopieren** die Felder nach Bedarf aus.  
4. Wählen Sie die Schaltfläche **OK** aus.  

Die kopierten Zeilen werden entweder in einem Anlagen Fibu Buch.-Blatt oder im Anlagen Buch.-Blatt erstellt. Dies hängt davon ab, ob das AfA-Buch, das Sie kopieren, in der Finanzbuchhaltung aktiviert wurde.

## <a name="see-also"></a>Siehe auch
[Verwalten von Anlagen](fa-manage.md)  
[Anlageneinrichtung](fa-setup.md)  
[Finanzen](finance-setup.md)  
[Willkommen bei Dynamics NAV](across-get-started.md)


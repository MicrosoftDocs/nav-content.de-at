---
title: "Übersicht über die Zuweisung von Kosten und Einnahmen"
description: Die Posten einer Fibu Buch.-Blattzeile lassen sich beim Buchen des Buch.-Blatts auf verschiedene Konten verteilen.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fdb03090dc9ba024d84a175e313f7d530bd0feae
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-allocate-costs-and-income"></a>Erklärt, wie Kosten und Einnahmen zugewiesen werden.
Die Posten einer Fibu Buch.-Blattzeile lassen sich beim Buchen des Buch.-Blatts auf verschiedene Konten verteilen. Für die Verteilung stehen drei unterschiedliche Methoden zur Verfügung:

* Menge
* Prozentsatz (%)
* Betrag

Die Verteilungsfeatures können sowohl in wiederkehrenden Buch.-Blättern als auch in Buch.-Blättern für Anlagen verwendet werden.
<!--You can also distribute the cost or revenue of a line to an intercompany partner when you post a sales or purchase document. When you post the document, a line will be posted in your general journal, and a corresponding line will be created in the intercompany outbox.-->

Die folgenden Verfahren beschreiben, was bereitgestellt werden muss, um Kosten in einem wiederkehrenden Buch.-Blatt zuzuordnen, indem Verteilungsschlüssel eingerichtet werden. Wenn Verteilungsschlüssel definiert werden, beenden und buchen Sie das Buch.-Blatt wie alle anderen wiederkehrenden Fibu Buch.-Blätter. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)

## <a name="to-set-up-allocation-keys"></a>Einrichten von Verteilungsschlüsseln
Die Posten einer Fibu Buch.-Blattzeile lassen sich beim Buchen des Buch.-Blatts auf verschiedene Konten verteilen. Die Verteilung kann nach Anzahl, Prozent oder Betrag vorgenommen werden.
1. Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Wiederkehrendes Buch-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Fibu Buch.-Blattnamen** den **Buch.-Blattnamen**.
3. Sie können entweder Zuordnungen in einer vorhandene Charge in der Liste ändern oder eine neue Charge mit Zuordnungen erstellen.
   * Um eine neue Chargennummer zu erstellen, wählen Sie die Aktion **Neu** und gehen Sie zum nächsten Schritt.
   * Um die Zuordnungen eines vorhandenen Buch.-Blattes zu ändern, wählen Sie das Buch.-Blatt und gehen Sie zum Schritt 7.    
4. Geben Sie im Feld **Name** einen Namen für das Buch.-Blatt ein, wie beispielsweise REINIGUNG. Geben Sie im Feld **Beschreibung** eine Beschreibung ein, wie z. B. Reinigungsausgaben Buch.-Blatt.
5. Wenn Sie fertig sind, schließen Sie das Fenster. Ein neues, leeres wiederkehrendes Buchungsblatt wird geöffnet.
6. Füllen Sie die Felder in der Zeile aus.
7. Wählen Sie die Aktion **Verteilung** aus.
8. Erstellen Sie für jede Verteilung eine Zeile. Sie müssen entweder das Feld **Verteilung %**, **Anzahl Verteilungen** oder **Betrag** ausfüllen. Sie müssen ebenfalls das Feld **Kontonr.** ausfüllen und, wenn Sie auf globale Dimensionen verteilen, auch die Felder "globale Dimensionen".
9. Wenn Sie in der Zeile einen Prozentsatz eingeben, wird der Betrag im Feld **Betrag** automatisch berechnet. Diese Beträge haben das gegenteilige Vorzeichen von dem Gesamtbetrag im Feld **Betrag** des Wiederk. Buch.-Blattes.
10. Nachdem Sie die Zuteilungszeilen eingegeben haben, wählen Sie **OK** aus, um zum Fenster **Wiederk. Fibu Buch.-Blätter** zurückzukehren. Das Feld **Zugewiesener Betrag (USD)** ist ausgefüllt und entspricht dem Feld **Betrag**.
11. Buchen Sie die Buch.-Blattzeile.

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a>Ändern eines bereits eingerichteten Verteilungsschlüssels
1. Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben die **Wiederkehrendes Buch-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Wiederk. Fibu Buch.-Blatt** das Buch.-Blatt mit der Verteilung aus.
3. Wählen Sie die Zeile mit der Verteilung, und wählen Sie dann die Aktion **Zuweisungen** aus.
4. Ändern Sie die relevanten Felder und wählen Sie dann die Schaltfläche **OK** aus.

## <a name="see-also"></a>Siehe auch
[Beenden von Jahresabschluss und Perioden](year-close-years-periods.md)  
[Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)    
[Journale und Dokumente buchen](ui-post-documents-journals.md)    
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


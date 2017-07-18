---
title: Erstellen von Nummernkreisen
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 22b3bcf71c99e106527d6bfa35478045d29b9629
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="create-number-series"></a>Erstellen von Nummernkreisen

Für jeden eingerichteten Mandanten müssen eindeutige Identifizierungscodes für Elemente wie Sachkonten, Debitor-/Kreditorkonten, Rechnungen und Belege zugeordnet werden. Die Nummerierung dient jedoch nicht nur zur Identifizierung. Ein durchdachtes Nummerierungssystem trägt zur einfacheren Verwaltung und besseren Analysierbarkeit des Mandanten bei, was eine Verringerung von Eingabefehlern zur Folge hat.

Sie haben die Möglichkeit zum Einrichten eines vollständigen Nummerierungssystems mit einer unbegrenzten Anzahl von Nummernserien. Nummernserien können für alle Arten von Belegen sowie für Masterdaten wie Debitoren, Artikel und Projekte verwendet werden.

Die Verwendung von Nummernserien lässt sich mit einer manuellen Nummerierung kombinieren.

Ein Nummerierungssystem wird durch Einrichten mindestens eines Codes für die einzelnen Arten von Masterdaten oder Belegen eingerichtet. So können Sie beispielsweise einen Code für die Nummerierung von Debitoren, einen weiteren Code für die Nummerierung von Verkaufsrechnungen und einen weiteren Code für die Nummerierung von Belegen in Fibu Buch.-Blättern einrichten.

Nachdem ein Code eingerichtet wurde, muss mindestens eine Nummernserienzeile eingerichtet werden. Die Nummernserienzeile enthält Informationen wie die erste und die letzte Nummer der Serie sowie das Startdatum. Pro Nummernseriencode lassen sich mehrere Nummernserienzeilen mit unterschiedlichem Startdatum einrichten. Die Serie wird fortlaufend verwendet, wobei jede Serie zum entsprechenden Startdatum beginnt.

Verwenden Sie Nummernserienbeziehungen, wenn Sie für eine Masterdatenart mehrere Nummernseriencodes verwenden möchten – beispielsweise, um für unterschiedliche Artikelkategorien unterschiedliche Nummernserien zu verwenden.

Zusätzlich zu den Nummern, die manuell oder durch das Nummerierungssystem zugeordnet werden, werden alle Transaktionen (Posten) automatisch mit laufenden Nummern versehen. Diese Nummern können Sie in der **Eintrags-Nr.** sehen. Feld in allen Postenfenstern. Diese Nummern können weder geändert noch gelöscht werden.

## <a name="to-create-relationships-between-number-series"></a>Verbindungen zwischen Nummernserien herstellen:
Wenn Sie mehr als einen Nummernseriencode für dieselbe Art von grundlegenden Daten oder Geschäftsvorfällen eingerichtet haben, können Sie Verbindungen zwischen diesen Codes herstellen. Dann können Sie zwischen den verschiedenen Codes auswählen, wenn Sie eine Nummer verwenden wollen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Artikelnummer** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Zeile mit der Nummernserie, für die Sie Verbindungen herstellen wollen und wählen Sie **Beziehungen**.
3. Geben Sie im Feld **Seriencode** den Code für die Nummernserie ein, für die Sie eine Verbindung mit der in Schritt 2 ausgewählten Nummernserie herstellen möchten.
4. Fügen Sie für jeden Code, für den eine Verbindung mit der ausgewählten Nummernserie hergestellt werden soll, eine neue Zeile hinzu.
5. Schließen Sie das Fenster.

Wenn Sie jetzt etwas einrichten, was eine Nummer benötigt, können Sie die von Ihnen erzeugten Verbindungen verwenden, um zwischen den verbundenen Nummernserien auszuwählen.

## <a name="see-also"></a>Siehe auch
[Arbeiten mit Dynamics NAV](ui-work-product.md)


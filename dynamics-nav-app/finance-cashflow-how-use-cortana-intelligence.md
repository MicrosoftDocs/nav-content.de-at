---
title: 'Vorgehensweise: Einrichten von voraussagenden Cashflowplanungen'
author: bholtorf
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 1fdb53b0f58ada22475fe1c1510146c156a60410
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---

# <a name="how-to-make-predictive-cash-flow-forecasts"></a>Vorgehensweise: Einrichten von voraussagenden Cashflowplanungen
Cashflowplanungen helfen Ihnen, sicherzustellen, dass Ihr Mandant genügend liquide Mittel hat, um den finanziellen Verpflichtungen nachzukommen und sind praktisch, um Anpassungen zu identifizieren. Wenn Sie beispielsweise einen Kassenüberschuss haben, können Sie möglicherweise Schulden begleichen und Sie schätzen eine Frühwarnung, wenn es knapp wird.

Cortana-Intelligenz verwendet den Azure Machine Learning-Service, um verlässliche, vorhersagende Planungen zu erstellen. Beispielsweise können Planungen aus Cortana-Intelligenz Ihnen dabei helfen, Voraussagen zu machen und Kassendefizite zu vermeiden. Der Service kombiniert historische Informationen mit aktuellen Buchungen für Forderungen und Verbindlichkeiten, einschließlich Buchungen mit Fälligkeitsdaten, die in der Zukunft liegen. Dazu gehören:
* Bestellungen
* Verkaufsaufträge
* Gebuchte Einkaufs- und Verkaufsrechnungen
* Gutschriften

## <a name="before-you-start"></a>Bevor Sie beginnen  
Es gibt mehrere Dinge zu tun, bevor Sie Cortana-Intelligenz für Cashflowplanungen verwenden können:
* Wenn Sie nicht bereits Cashflowplanungen verwenden, müssen Sie diese einrichten:
    * Eine oder mehrere Einstellungen in **Cashfloweinrichtungen**
    * Konten für Verbindlichkeiten, Forderungen, Verkaufsaufträge und Bestellungen. Cortana-Intelligenz verwendet die Buchungen in diesen Konten.
    * Eine oder mehrere Cashflowplanungen in **Cashflowplanung**. Stellen Sie sicher, Bestellungen, Verkaufsaufträge, Forderungen und Verbindlichkeiten als Quellen zu berücksichtigen.  
    Weitere Informationen finden Sie in unter _Cashflowplanungen_ im Hilfesystem.
* Sie kennen den API URL und den API Schlüssel, der für den vorhersagenden Webservice verwendet werden soll.  
    Sie können Azure Machine Learning oder einen anderen Service verwenden, wenn Sie einen haben. Alternativ ist ein öffentliches Modell mit dem Namen _Vorhersagemodell für Microsoft Dynamics NAV_ online im Cortana Intelligence-Katalog verfügbar. Um das Modell zu verwenden, gehen folgendermaßen vor:

    1. Wechseln Sie in einem Browser zum [Cortana-Intelligenz-Katalog](https://go.microsoft.com/fwlink/?linkid=828352)
    2. Suchen Sie nach dem _Vorhersagemodell für Microsoft Dynamics NAV_ und öffnen Sie dann das Modell im Azure Machine Learning Studio.
    3. Verwenden Sie das Microsoft-Konto, um sich für einen Arbeitsbereich anzumelden und kopieren Sie dann das Muster.
    4. Führen Sie die Vorlage aus und veröffentlichen Sie dieses als Webdienst.
    5. Notieren Sie den API URL und den API Schlüssel. Sie verwenden diese Anmeldeinformationen, wenn Sie Cortana Intelligence in [!INCLUDE[navnow](includes/navnow_md.md)] einrichten.  

* Berücksichtigen Sie, wieoft die Planung berechnet werden soll. Der Azure Machine Learning-Service hat Einschränkungen bezüglich der Verwendung. Falls Sie beispielsweise zahlreiche Artikel haben, kann es besser sein, diese weniger häufig zu berechnen.
* Sie werden dem Buchhalterrollencenter zugeordnet.

## <a name="set-up-cortana-intelligence"></a>Cortana Intelligence einrichten
Sie können die unterstützte Einrichtung verwenden, um die Cashflowplanungen einzurichten. Die Handbuchhilfen helfen Ihnen, Elemente festzulegen, beispielsweise wie oft die Planung aktualisiert werden soll, die Konten, die darauf basieren sollen, Informationen darüber, wann Sie Steuern bezahlen und ob Cortana-Intelligenz verwendet werden soll.  

Wenn Sie bereits Cashflowplanungen verwenden und nur Cortana-Intelligenz einschalten möchten, können Sie auch einen manuellen Prozess anwenden. Wenn Sie in unterzeichnen, wird eine Benachrichtigung in einer blauen Leiste im oberen Bereich des Arbeitsbereichs angezeigt. Um Cortana-Intelligenz sofort einzurichten, wählen Sie **Ja, bitte**. Die Mitteilung wird jeweils nur einmal angezeigt. Wenn Sie sie schließen, verwenden Sie den manuellen Vorgang, um Cortana-Intelligenz einzurichten.  

**Tip:** Beachten Sie die Länge der Perioden, die der Service in den Berechnungen verwendet. Je mehr Daten Sie liefern, umso genauer wird die Vorhersage sein. Halten Sie auch nach umfangreichen Abweichungen in Perioden Ausschau. Sie werden ebenfalls Auswirkungen auf die Vorhersagen haben. Wenn Cortana-Intelligenz nicht genügend Daten findet oder die Daten stark abweichen, wird der Service keine Vorhersage machen.

Um die unterstützte Einrichtung zu verwenden:
1. Im Buchhalterrollencenter unter **Cashflow-Planung** wählen Sie die Aktion **Unterstütze Einrichtung** aus.
2. Füllen Sie die Felder soweit erforderlich in jedem Schritt im Handsbuch aus.

Um einen manuellen Vorgang zu verwenden:
1. Suchen Sie nach **Cashflow einrichten** und wählen Sie dann den zugehörigen Link aus.
2. Erweitern Sie das Inforegister **Cortana Intelligence** und füllen Sie die Felder wie notwendig aus.

## <a name="turn-on-cortana-intelligence-for-cash-flow-forecasts"></a>Aktivieren Sie Cortana-Intelligenz für Cashflowplanungen
1. Suchen Sie nach **Cashflow-Planungen** und wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Cashflow Arbeitsblatt** aus.
3. Auf der Seite **Cashflow Arbeitsblatt** wählen Sie die Aktion **Vorgeschlagene Arbeitsblattpositionen** aus.  
4. Unter **Einzuschließen Herkunftsartene**, wählen Sie das Kontrollkästchen **Cortana Intelligence Forecast** aus.

## <a name="investigate-a-cash-flow-forecast"></a>Untersuchen Sie eine Cashflowplanung
Um einen guten Blick auf die Daten hinter die Planung, einschließlich der Abweichung zu werfen, wählen Sie die die Spalte **Cortana Intelligence**. Die erste Tabellenzeile zeigt die Abweichung. Die anderen Zeilen werden nach Herkunftsbeleg angeordnet.  

Beispielsweise wird angezeigt, wie die Planungs:    
* Verarbeitet bestätigte Verkäufe und Einkäufe
* Subtrahiert Verbindlichkeiten und fügt Forderungen hinzu
* Überspringt duplizierte Verkaufsaufträge und Bestellungen

## <a name="see-also"></a>Siehe auch  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


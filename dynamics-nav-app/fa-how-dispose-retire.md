---
title: "So geht's: Anlagen entsorgen oder außer Dienst stellen"
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
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a>So geht's: Anlagen entsorgen oder außer Dienst stellen
Wenn Sie eine Anlage verkaufen oder anderweitig entfernen, muss der Verkaufswert gebucht werden, um den Gewinn oder Verlust zu berechnen und zu erfassen. Ein Verkaufsposten muss der letzte gebuchte Posten einer Anlage sein. Für teilweise verkaufte Anlagen können Sie mehrere Verkaufsposten buchen. Die Summe aller gebuchten Verkaufsbeträge muss ein Habenposten sein.

 **Hinweis**: Falls Sie für den Verkauf einer Anlage eine andere Anlage in Zahlung nehmen, müssen Sie sowohl den Verkauf der alten Anlage als auch die Anschaffung der neuen Anlage buchen. Weitere Informationen finden Sie unter [So geht's: Beschaffen von Anlagen](fa-how-acquire.md).

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a>So buchen Sie einen Verkauf aus dem Anlagen Fibu Buch.-Blatt  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen Fibu Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Erstellen Sie eine ursprüngliche Buch.-Blattzeile und füllen Sie die notwendigen Felder aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Wählen Sie im Feld **Anlagenbuchungsart** den **Verkauf**.
4. Wählen Sie die Aktion **Anlagengegenkonto einfügen**. Eine zweite Buch.-Blattzeile wird für das Gegenkonto erstellt, das für die Buchung eines Verkaufs eingerichtet wird.

    **Hinweis**: Schritt 4 funktioniert nur, wenn Sie Folgendes eingerichtet haben: Im Fenster **Anlagenbuchungsgruppenkarte** der Buchungsgruppe der Anlage enthält das Feld **Kto. Verkauf** das Sollkonto im Sachkonto und das Feld **Gegenkto. Verkauf** enthält das Sachkonto, auf das die Gegenposten für Zuschreibungen gebucht werden sollen. Weitere Informationen finden Sie im Abschnitt "So richten Sie Anlagenbuchungsgruppen ein" in [So geht's: Allgemeine Anlageninformationen einrichten](fa-how-setup-general.md).
5. Wählen Sie die Aktion **Buchen** aus.

Wenn Sie eine Anlage zum Teil verkaufen, müssen Sie die Anlage aufteilen, bevor Sie die Verkaufstransaktion buchen können. Weitere Informationen finden Sie unter [So geht's: Übertragen, Teilen oder Kombinieren von Anlagen.](fa-how-trans-split-combine.md).

## <a name="to-view-disposal-ledger-entries"></a>So zeigen Sie Verkaufsposten an  
Wenn Sie eine Anlage verkaufen, wird der Verkaufswert in den Sachposten gebucht, wo Sie die Ergebnisse anzeigen können.   

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlagen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Anlage aus, für die Sie die Posten anzeigen möchten und wählen Sie dann die Aktion **AfA-Bücher** aus.
3. Wählen Sie das AfA-Buch aus, für das Sie die Posten anzeigen möchten und wählen Sie dann die Aktion **Posten** aus.
4. Wählen Sie im Feld **Anlagebuchungskategorie** die Zeile mit **Verkauf** aus, und klicken Sie auf die Aktion **Navigieren**.  
5. Wählen Sie im Fenster **Navigieren** die Sachpostenzeile aus, und klicken Sie auf die Aktion **Anzeigen**.
Das Fenster **Sachposten** wird geöffnet, in dem Sie die Posten sehen können, die aus der Verkaufsbuchung resultieren.

## <a name="see-also"></a>Siehe auch
[Verwalten von Anlagen](fa-manage.md)  
[Anlageneinrichtung](fa-setup.md)  
[Finanzen](finance-setup.md)  
[Willkommen bei Dynamics NAV](across-get-started.md)


---
title: 'So geht''s: Versichern von Anlagen'
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
ms.openlocfilehash: a3a59bc091042f72775b56fdd5bbe37ffa1a6d80
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-insure-fixed-assets"></a>So geht's: Versichern von Anlagen
Eine Versicherungspolice für eine Anlage wird durch eine Versicherungskarte angezeigt. Sie können eine Anlage einer Versicherungspolice oder mehreren Anlagen einer Versicherungspolice zuzuordnen.

Sie ordnen einer Anlage einer Versicherungspolice zu, indem Sie sie im Versicherungsposten im Fenster **Versicherungs Buch.-Blatt** buchen.

Zudem können Sie eine Anlage einer Versicherungspolice zuzuordnen und Versicherungsposten erstellen, wenn Sie deren Anschaffungskosten buchen. Sie tun dies, indem Sie Anschaffungskosten aus dem Anlagen Buch.-Blatt buchen und das Feld **Versicherungsnr.** ausgefüllt ist. Das Kontrollkästchen **Autom. Versicherungsbuchung** im Fenster **Anlageneinrichtung** muss aktiviert sein. Weitere Informationen finden Sie unter "Wie Anlagenanschaffungen mit dem Anlagen-Fibu Buch.-Blatt manuell gebucht werden" unter [So geht's: Anlagen erwerben](fa-how-acquire.md).

Wenn das Kontrollkästchen **Autom. Versicherungsbuchung** im Fenster **Anlageneinrichtung** nicht ausgewählt ist, werden beim Buchen von Anschaffungen Zeilen im Fenster **Versicherung Buch.-Blatt** erstellt, die Sie dann manuell buchen müssen.

**Warnung**: Wenn Sie das Kontrollkästchen **Autom. Versicherungsbuchung** im Fenster **Anlageneinrichtung** auswählen, dann sollte das Versicherungs Buch.-Blatt auf einer Buch.-Blattvorlage ohne Nummernserie basieren. Der Grund dafür ist, dass die eingefügten Belegnummern aus der Buch.-Blattzeile andernfalls einen Konflikt mit der Nummernserie des Versicherungs Buch.-Blattes verursachen. Weitere Informationen über Buch.-Blattvorlagen und Buch.-Blattstapel finden Sie unter [So geht's: Einrichten allgemeiner Anlagen-Informationen](fa-how-setup-general.md).

Nachdem Sie eine Anlage einer Versicherungspolice zugewiesen haben, wird das Kontrollkästchen **Versichert** auf der Anlagenkarte aktiviert. Wenn Sie die Anlage verkaufen, wird das Kontrollkästchen automatisch deaktiviert.

## <a name="to-create-or-modify-an-insurance-card"></a>So erstellen oder ändern Sie eine Versicherungskarte
Eine Versicherungspolice für eine Anlage muß durch eine Versicherungskarte angezeigt werden.

Wenn Sie Informationen über Änderungen der Deckungssumme erhalten, müssen Sie diese im Fenster **Versicherungskarte** aktualisieren, um sicherzustellen, dass Sie die Versicherungsdeckung korrekt analysieren.  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Versicherung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus, um eine neue Karte für eine Versicherungspolice zu erstellen. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Alternativ wählen Sie die Versicherungspolice, die Sie ändern möchten, und wählen die Aktion **Bearbeiten** aus.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a>So verknüpfen Sie eine Anlage mit einer Versicherungspolice durch Buchen aus einem Versicherungs Buch.-Blatt
Sie verknüpfen eine Anlage mit einer Versicherungspolice, indem Sie sie in den Versicherungsposten buchen.

Nachfolgend wird beschrieben, wie Sie eine Versicherungs Buch.-Blattzeile manuell erstellen. Wenn das Kontrollkästchen **Autom. Versicherungsbuchung** im Fenster **Anlageneinrichtung** ausgewählt wird, werden Versicherungs Buch.-Blattzeilen automatisch erstellt, wenn Sie Anschaffungskosten buchen. In diesem Fall müssen Sie nur das Buch.-Blatt buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Vers. Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie das relevante Buch.-Blatt und füllen Sie die Buch.-Blattzeilen nach Bedarf aus.
3. Um mehrere Anlagen einer Versicherungspolice zuzuweisen, können Sie Buch.-Blattzeilen mit dem gleichen Wert im Feld **Versicherungsnr.** und unterschiedlichen Werten im Feld **Anlagennr.** erstellen Feld
4. Wählen Sie die Aktion **Buchen** aus.

**Hinweis**: Die Posten aus dem Vers. Buch.-Blatt werden nur auf die Versicherungsposten gebucht.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a>So aktualisieren Sie den Versicherungswert einer Anlage
Sie können die Stapelverarbeitung **Indexiere Versicherung** verwenden, um den Wert der versicherten Anlagen zu aktualisieren.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Versicherung indexieren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie die Felder je nach Bedarf aus.

    **Hinweis**: Im Feld **Indexzahl** wird eine Senkung um 5% bespielsweise als "95" eingegeben, während eine Steigerung von 2% als "102" eingegeben wird.  
3.  Wählen Sie die Schaltfläche **OK** aus.  

    Die Stapelverarbeitung berechnet den neuen Betrag als Prozentsatz des gesamten versicherten Wertes aus dem Fenster **Versicherungsstatistik** und erstellt dann eine Zeile im Vers. Buch.-Blatt.  
4. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Vers. Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
5. Öffnen Sie das relevante Versicherungs Buch.-Blatt, prüfen Sie die erstellten Posten und buchen Sie diese dann auf die Versicherungsposten.

## <a name="to-monitor-insurance-coverage"></a>So überwachen Sie die Versicherungsdeckung
Dynamics NAV bietet dedizierte Berichte und Statistikfenster, die dazu verwendet werden können, Versicherungspolicen zu analysieren und zu überprüfen, ob Ihre Anlagen über- oder unterversichert sind.

### <a name="overview-of-insurance-policies"></a>Übersicht der Versicherungspolicen  
Um sich einen Überblick über Ihre Versicherungspolicen zu verschaffen, können Sie den Bericht **Versicherungsübersicht** ausdrucken oder anzeigen. In diesem Bericht werden die einzelnen Policen und die wichtigsten Felder der Versicherungskarten angezeigt.  

### <a name="insurance-coverage"></a>Versicherungsdeckung
Um zu sehen, welche Versicherungspolicen welche Anlagen in welcher Höhe abdecken, können Sie den Bericht **Versicherung – Vers. Summe** ausdrucken oder anzeigen.

### <a name="overunder-coverage"></a>Unter-/Überversicherung
Folgendermaßen können Sie prüfen, ob Anlagen über- oder unterversichert sind:
- Das Fenster **Versicherungsstatistik**. Ein positiver Betrag in dem Feld **Über-/Unterversichert** bedeutet, dass die Anlage überversichert ist. Ein negativer Betrag zeigt eine Unterversicherung an.
- Das Fenster **Anlagenstatistik**. Wählen Sie das Feld **Versicherte Summe**, um das Fenster **Versicherungsposten** anzuzeigen.  
- Der Bericht **Unter-/Überversicherung**.  
- Der Bericht **Versicherungsanalyse**.

### <a name="uninsured-fixed-assets"></a>Unversicherte Anlagen
Um zu prüfen, ob Sie vergessen haben, eine Anlage einer Versicherungspolice zuzuweisen, können Sie den Bericht **Versicherung - Unvers. Anlagen** drucken oder anzeigen. Dieser Bericht zeigt Anlagen an, für die noch keine Beträge in den Versicherungsposten gebucht wurden.

## <a name="to-view-insurance-coverage-ledger-entries"></a>So zeigen Sie Versicherungsposten an
Sie können sich die einzelnen Posten anzeigen lassen, die Sie in den Versicherungsposten erstellt haben.  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Versicherung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die entsprechende Versicherungspolice aus, und wählen Sie dann die Aktion **Versicherungsposten**.

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a>So zeigen Sie den gesamten Versicherungswert von Anlagen an:
Ein dediziertes Matrixfenster zeigt die Versicherungswerte jeder Anlage und jeder Versicherungspolice als Ergebnis der versicherungsbezogenen Beträge an, die von Ihnen gebucht wurden.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Versicherung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die entsprechende Versicherungspolice aus, und wählen Sie dann die Aktion **Versicherte Summe pro Anlage**.
3. Füllen Sie die Felder je nach Bedarf aus  
4. wählen Sie die Aktion **Matrix anzeigen** aus.  
5. Um die zu Grunde liegenden Versicherungsposten anzuzeigen, aktivieren Sie einen Wert in der Matrix.

## <a name="to-correct-insurance-coverage-entries"></a>So korrigieren Sie Versicherungsposten  
Wenn eine Anlage der falschen Versicherung zugeordnet wurde, können Sie diese korrigieren, indem Sie zwei Umbuchungsposten aus dem Versicherungs Buch.-Blatt erstellen.  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Vers. Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
2. Erstellen Sie eine Buch.-Blattzeile für die Anlage und die korrekte Versicherungspolice, in der der Wert im Feld **Betrag** positiv ist.
3. Erstellen Sie eine weitere Buch.-Blattzeile für die Anlage und die inkorrekte Versicherungspolice, in der der Wert im Feld **Betrag** negativ ist.  
4. Wählen Sie die Aktion **Buchen** aus.

Die Verknüpfung der Anlage mit der falschen Versicherung der zweiten Zeile wird aufgehoben und stattdessen eine Verknüpfung mit der richtigen Versicherung aus der ersten Zeile erstellt.

## <a name="see-also"></a>Siehe auch
[Verwalten von Anlagen](fa-manage.md)  
[Anlageneinrichtung](fa-setup.md)  
[Finanzen](finance-setup.md)  
[Willkommen bei Dynamics NAV](across-get-started.md)

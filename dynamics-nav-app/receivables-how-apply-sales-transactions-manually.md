---
title: 'Vorgehensweise: Manuelle Abstimmung vom Zahlungen'
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
ms.openlocfilehash: de0c94386ad5a0bbfba5cc0516fa7faa5cdcc0b4
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually"></a>Vorgehensweise: Manuelle Abstimmung vom Zahlungen
Wenn Sie einen Zahlungseingang von einem Debitor erhalten oder eine Barerstattung durchführen, müssen Sie entscheiden, ob die Zahlung oder die Rückerstattung mit einem oder mehreren offenen Soll- oder Habenposten ausgeglichen werden soll. Sie können den genauen Betrag angeben, den Sie anwenden möchten. Beispielsweise kann es sein, dass Sie nur einen Teil der Zahlung ausgleichen und dadurch Debitorenposten nur teilweise ausgleichen möchten. Es ist wichtig, an einem bestimmten Punkt alle Debitorenposten zu schließen (anzuwenden), um korrekte Debitorenstatistiken und Ausdrucke der Kontoauszüge und Finanzeinrichtungsgebühren zu erhalten.

Sie können Debitorenposten auf drei verschiedene Arten übernehmen:

- Durch die Eingabe von Informationen in speziellen Fenstern, wie das **Barzahlungseingangsbuch.-Blatt** und das Fenster **Zahlungsabstimmungsbuch.-Blatt**.
- Aus den Verkaufsgutschriftsbelegen.
- Debitorenposten nach Verkaufsbelegen werden gebucht aber nicht angewendet.

**Hinweis**: Wenn das Feld **Ausgleichsmethode** auf der Debitorenkarte **Auf älteste anwenden** enthält, dann wird die Zahlung automatisch mit der ältesten offenen Rechnung abgeglichen, wenn Sie nicht explizit angeben, auf welchen Habenposten sie sich bezieht. Ist die Ausgleichsmethode eines Debitors auf **Manuell** festgelegt, müssen die Posten manuell ausgeglichen werden.

Sie können Zahlungen automatisch im Fenster **Zahlungseingangsbuch.-Blatt** manuell verbuchen. Ein Zahlungseingangs Buch.-Blatt ist eine Art von Fibu Buch.-Blatt. Daher können Sie es verwenden, um Transaktionen auf Sach-, Bank-, Debitoren-, Kreditor- und Anlagenkonten zu buchen. Daher können Sie die Zahlungen beim Buchen auf einen oder mehrere Sollposten anwenden oder die gebuchten Posten später anwenden.

Sie können Debitorenzahlungen und Kreditorenzahlungen, im Fenster **Zahlungsabstimmungsbuch.-Blatt** mithilfe von Funktionalitäten für den Bankkontoauszugsimport, die automatische Anwendung und die Bankkontoabstimmung verwenden. Weitere Informationen finden Sie unter [Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md). Alternativ können Sie Debitorenzahlungen auf einer Liste der unbezahlten Verkaufsbelegen im Fenster **Zahlungs-Registrierung** abstimmen. Weitere Informationen finden Sie unter [So geht's: Abstimmen von Debitoren-Zahlungen aus einer Liste mit unbezahlten Verkaufsbelegen](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

## <a name="to-fill-and-post-a-cash-receipt-journal"></a>So füllen Sie ein Zahlungseingangs Buch.-Blatt aus und buchen dieses
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlungseingang&s Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Feld **Buch.-Blattname** das relevante Buch.-Blatt aus.
3. Füllen Sie das Feld **Buchungsdatum** auf.  
4. Wählen Sie im Feld **Belegart** die Option **Zahlung** aus.

    Die **Dokumentennummer** Feld wird anhand der Nummernserie ausgefüllt, die dem Charge zugeordnet ist.
5. **Externe Dokumentennummer** verwenden Verwenden Sie das Feld Externe Belegnummer, um eine Kennung wie die Schecknummer des Debitors zu speichern.
6. Wählen Sie im Feld **Kontoart** die Option **Kreditor** aus.
7. Wählen Sie im Feld **Kontonummer** Wählen Sie das entsprechende Sachkonto.
8. Falls Sie den Ausgleich gleichzeitig mit dem Buch.-Blatt buchen möchten, führen Sie einen der folgenden Schritte durch.
9. Wählen Sie im Feld **Gegenkontoart** das **Sachkonto** für Barzahlungen und das **Bankkonto** für sonstige Zahlungen aus.
10. Wählen Sie im Feld **Ausgleichskontonummer** das Barkonto für Barzahlungen oder das zutreffende Bankkonto für sonstige Zahlungen aus.
11. Buchen Sie die Buch.-Blattzeile.

## <a name="to-apply-a-payment-to-a-single-customer-ledger-entry"></a>So gleichen Sie einen einzelnen Debitorenposten mit einer Zahlung aus:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Barzahlungseingangsbuch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie in der ersten Buch.-Blattzeile die entsprechenden Informationen zu dem auszugleichenden Posten ein.
3. Wählen Sie im Feld **Belegart** die Option **Zahlung** aus.
4. Wählen Sie im Feld **Kontoart** die Option **Kreditor** aus.
5. Wählen Sie im Feld **Gegenkontoart** die Option **Bankkonto** aus.
6. Wählen Sie im Feld **Ausgleich mit Belegnr.** Feld, wählen das Feld, um das Fenster **Debitorenposten anwenden**.
7. Wählen Sie im Fenster **Kreditorenpostenausgleich** die Zeilen mit den Posten aus, die Sie mit der Zahlung ausgleichen möchten.
8. Geben Sie in jeder Zeile im Feld **Anzuwendender Betrag** den Betrag ein, mit dem Sie den entsprechenden Posten ausgleichen möchten. Wenn Sie keinen Betrag eingeben, wird automatisch mit dem Höchstbetrag ausgeglichen.

    Am unteren Rand des Fensters **Benutzerdefinierter Eintrag anwenden** sehen Sie einen spezifischen Betrag im Fenster **Angewendeter Betrag** und auch, ob die Buchung ausgeglichen ist.
9. Wählen Sie die Schaltfläche **OK**. Das Fenster **Bahrzahlungseingangsbuch.-Blatt** zeigt nun die von Ihnen ausgewählten Einträge unter **Auf Dokumenttyp anwenden** und auf **Dokumenttyp anwenden**. Felder.
10. Buchen Sie das Zahlungseingangs-Buch.-Blatt.

## <a name="to-apply-a-payment-to-multiple-customer-ledger-entries"></a>So gleichen Sie mehrere Debitorenposten mit einer Zahlung aus:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Barzahlungseingangsbuch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie in der ersten Buch.-Blattzeile die entsprechenden Informationen zu dem auszugleichenden Posten ein.
3. Wählen Sie im Feld **Belegart** die Option **Zahlung** aus.
4. Wählen Sie im Feld **Kontoart** die Option **Kreditor** aus.
5. Wählen Sie im Feld **Gegenkontoart** die Option **Bankkonto** aus.
6. Geben Sie im Feld **Betrag** die vollständige Zahlung als negativen Betrag ein.
7. Wenn Sie die Zahlung bei der Buchung mit mehreren Kreditorenposten ausgleichen möchten, klicken Sie auf die Aktionen **Einträge anwenden**.
8. Wählen Sie die Zeilen mit den Posten aus, die mit dem Ausgleichsposten ausgeglichen werden sollen, und klicken Sie anschließend auf **Ausgleichs-ID setzen anwenden**.
9. Geben Sie in jeder Zeile im Feld **Ausgleichsbetrag** den Betrag ein, mit dem Sie den entsprechenden Posten ausgleichen möchten. Wenn Sie keinen Betrag eingeben, wird automatisch mit dem Höchstbetrag ausgeglichen.

    Am unteren Rand des Fensters **Benutzerdefinierter Eintrag anwenden** sehen Sie einen spezifischen Betrag im Fenster **Angewendeter Betrag** und auch, ob die Buchung ausgeglichen ist.
10. Wählen Sie die Schaltfläche **OK**.
11. Buchen Sie das Zahlungseingangs-Buch.-Blatt.

## <a name="to-apply-a-credit-memo-to-a-single-customer-ledger-entry"></a>So gleichen Sie einen einzelnen Debitorenposten mit einer Gutschrift aus:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufs-Gutschrift** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die relevante Verkaufsgutschrift.
3. Wenn Sie bei der Buchung einen einzelnen Kreditorenposten durch die Gutschrift ausgleichen möchten, klicken Sie auf das Feld **Auf Dok.Nummer anwenden** und wählen den Posten aus, den Sie mit der Zahlung ausgleichen möchten.
4. Geben Sie in jeder Zeile im Feld **Ausgleichsbetrag** den Betrag ein, mit dem Sie den entsprechenden Posten ausgleichen möchten.

    Wenn Sie keinen Betrag eingeben, gleicht das Programm automatisch mit dem Höchstbetrag aus. Am unteren Rand des Fensters **Benutzerdefinierter Eintrag anwenden** sehen Sie einen spezifischen Betrag im Fenster **Angewendeter Betrag** und auch, ob die Buchung ausgeglichen ist.
5. Wählen Sie die Schaltfläche **OK**. Das Fenster **Verkaufsgutschrift** zeigt nun die von Ihnen ausgewählten Einträge unter **Auf Dokumenttyp anwenden** und auf **Dokumenttyp anwenden**. Felder. Und den Betrag der zu buchenden Gutschrift an, wobei mögliche Skonti berücksichtigt werden.
6. Buchen Sie die Gutschrift.

## <a name="to-apply-a-credit-memo-to-multiple-customer-ledger-entries"></a>So gleichen Sie mehrere Debitorenposten mit einer Gutschrift aus:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufs-Gutschrift** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die relevante Verkaufsgutschrift.
3. Wenn Sie die Zahlung bei der Buchung mit mehreren Kreditorenposten ausgleichen möchten, klicken Sie auf die Aktionen **Einträge anwenden**.
4. Wählen Sie die Zeilen mit den Posten aus, die mit dem Ausgleichsposten ausgeglichen werden sollen, und klicken Sie anschließend auf **Ausgleichs-ID setzen anwenden**.
5. Geben Sie in jeder Zeile im Feld **Ausgleichsbetrag** den Betrag ein, mit dem Sie den entsprechenden Posten ausgleichen möchten. Wenn Sie keinen Betrag eingeben, wird automatisch mit dem Höchstbetrag ausgeglichen.

  Am unteren Rand des Fensters **Benutzerdefinierter Eintrag anwenden** sehen Sie einen spezifischen Betrag im Fenster **Angewendeter Betrag** und auch, ob die Buchung ausgeglichen ist.
6. Wählen Sie die Schaltfläche **OK**. Das Fenster **Verkaufsgutschrift** zeigt nun den Betrag der zu buchenden Gutschrift an, wobei gegebenenfalls Skonto berücksichtigt wird.
7. Buchen Sie die Gutschrift.

## <a name="to-apply-posted-customer-ledger-entries"></a>So gleichen Sie gebuchte Debitorenposten aus:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kunde** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die Debitorenkarte für den Debitor mit den Posten, die Sie ausgleichen möchten.
3. Klicken Sie auf **Einträge** und wählen dann die Zeile mit dem Posten aus, den Sie ausgleichen möchten.
4. Wählen Sie die Aktion **Posten ausgleichen...** aus. Im Fenster **Debitorenpostenausgleich** werden die offenen Posten für den Debitor angezeigt.
5. Wählen Sie die Zeilen mit den Posten aus, die mit dem Ausgleichsposten ausgeglichen werden sollen, und klicken Sie anschließend auf **Ausgleichs-ID setzen anwenden**. Aktion
6. Geben Sie in jeder Zeile im Feld **Ausgleichsbetrag** den Betrag ein, mit dem Sie den entsprechenden Posten ausgleichen möchten. Wenn Sie keinen Betrag eingeben, wird automatisch mit dem Höchstbetrag ausgeglichen.

    Am unteren Rand des Fensters **Debitorenpostenausgleich** wird im Feld **Ausgleichsbetrag** der spezifische Betrag angezeigt.
7. Wählen Sie die Aktion **Ausgleich buchen** aus. Das Fenster **Ausgleich buchen** wird mit der Belegnummer des Ausgleichspostens und dem Buchungsdatum des Postens angezeigt, der das aktuellste Buchungsdatum aufweist.  
8. Klicken Sie auf die Schaltfläche **OK**, um den Ausgleich zu buchen.

    Wenn der gebuchte Ausgleich abgeschlossene Debitorenposten zur Folge hat, wird für diese Posten im Feld **Offen** kein Häkchen mehr angezeigt.
9. Um die Buchungseinträge zu sehen, wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Kunde** ein. Wählen Sie dann den zugehörigen Link aus. Wechseln Sie zur Karte für den jeweiligen Debitor, um die Buchungsposten zu sehen.

Sie können in der Liste der Posten sehen, dass„” „”i„”n der Zeile mit dem vollständig ausgeglichenen Posten das Feld **Offen** nicht aktiviert ist.  

**Hinweis**: Nachdem Sie im Fenster **Debitorenpostenausgleich** einen Posten oder mehrere Posten durch Festlegen der **Ausgleichs-ID** ausgewählt haben, enthält das Feld **Ausgleichsbetrag** die Summe der Restbeträge für die ausgewählten gebuchten Posten, es sei denn, das Feld enthält bereits Informationen. Wenn Sie **Auf Älteste Anwenden** im Feld **Anwendungsmethode** auf der Debitorenkarte auswählen, tritt die Anwendung automatisch auf.

## <a name="to-apply-customer-ledger-entries-in-different-currencies-to-one-another"></a>So gleichen Sie Debitorenposten in verschiedenen Währungen untereinander aus:
Wenn Sie an einen Debitor in einer Währung verkaufen und die Zahlung in einer anderen Währung erhalten, können Sie dennoch die Rechnung mit der Zahlung ausgleichen.

Wenn Sie einen Posten (Posten 2) in einer Währung mit einem Posten (Posten 1) in einer anderen Währung ausgleichen, wird das Buchungsdatum von Posten 1 verwendet, um den entsprechenden Wechselkurs zur Umrechnung der Beträge von Posten 2 zu ermitteln. Den Wechselkurs finden Sie im Fenster **Währungswechselkurse**.

Das Ausgleichen von Debitorenposten in verschiedenen Währungen muss aktiviert sein. Weitere Informationen finden Sie unter [So geht's: Anwendung von Kreditorenposten in unterschiedlichen Währungen aktivieren](finance-setup-how-enable-application-ledger-entries-different-currencies.md)

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Barzahlungseingangsbuch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie das gewünschte Buch.-Blatt, und füllen Sie unter Verwendung eines Währungscodes die erste Zeile aus.
3. Wählen Sie die Aktion **Posten ausgleichen...** aus.
4. Klicken Sie auf die Zeile mit dem Posten, mit dem Sie den Posten im Zahlungsausgangs-Buch.-Blatt ausgleichen möchten. Klicken Sie dann auf **Ausgleichs-ID festlegen** und wählen Sie den auszugleichenden Posten aus.
5. Wählen Sie die Schaltfläche **OK**, um zum Barzahlungseingangsbuch zurückzukehren.
6. Buchen Sie das Verkaufs Buch.-Blatt.

**Wichtig**: Wenn Sie Posten in verschiedenen Währungen miteinander ausgleichen, rechnet die Anwendung die Beträge in EUR um. Selbst wenn der Wechselkurs fest ist, z. B. zwischen USD und EUR, kann es zu Rundungsdifferenzen kommen, wenn diese Fremdwährungsbeträge in EUR umgerechnet werden. Diese Rundungsdifferenzen werden als Gewinne und Verluste auf die Konten gebucht, die in den Feldern **Kursgewinn realisiert** oder **Kursverlust realisiert** des Fensters **Währungen** angegeben sind. Außerdem werden die Beträge im Feld **Betrag (EUR)** der entsprechenden Kreditorenposten angepasst.

## <a name="to-unapply-an-application-of-customer-entries"></a>So heben Sie den Ausgleich von Debitoren- oder Kreditorenposten auf
Wenn Sie einen fehlerhaften Ausgleich aufheben, wird ein Korrekturposten (ein Posten, der mit dem ursprünglichen Posten identisch ist, im Betragsfeld allerdings ein umgekehrtes Vorzeichen aufweist) für alle Posten erstellt und gebucht, einschließlich aller aus dem Ausgleich abgeleiteten Fibu-Buchungen, z. B. Skonto und Währungsgewinne/-verluste. Die von der Anwendung geschlossenen Posten werden erneut geöffnet.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kunde** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die relevante Debitorenkarte.
3. Wählen Sie die Aktion **Posten** aus.
4. Wählen Sie den entsprechenden Posten aus, und wählen Sie die Aktionen **Ausgleich aufheben**.
5. Alternativ wählen Sie die Aktion **Detaillierte Posten** aus.
6. Wählen Sie den entsprechenden Ausgleichsposten aus, und wählen Sie die Aktionen **Ausgleich aufheben**.
7. Füllen Sie die Felder im Kopf aus, und wählen Sie dann die Aktion **Aufheben** aus.

**Wichtig**: Wenn ein Posten durch mehrere Ausgleichsposten ausgeglichen wurde, müssen Sie zuerst den Ausgleich des letzten Ausgleichspostens aufheben.

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Verkauf verwalten](sales-manage-sales.md)


---
title: 'Gewusst wie: Bankkonten separat abstimmen'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8b05bc9d09fa1e1a7a01eb4816ffba727611b776
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-bank-accounts-separately"></a>Gewusst wie: Bankkonten separat abstimmen
Um Bankkonten in Dynamics NAV mit den Kontoauszügen abzustimmen, die Sie von der Bank erhalten haben, müssen Sie die Zeilen im Fenster **Bankkontoabstimmung** ausfüllen.

**Hinweis**: Sie können Bankkonten auch im Fenster **Zahlungsabstimmungsbuch.-Blatt** abstimmen. Alle offnen Bankposten, die sich auf ausgeglichene Debitoren- oder Kreditorenposten beziehen, werden geschlossen, wenn Sie die Aktion **Zahlungen buchen und Bankkonto abstimmen** auswählen. Dies bedeutet, dass das Bankkonto mit Zahlungen abgestimmt wird, die Sie mit dem Buch.-Blatt buchen. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).

Um den Import von Bankkontoauszügen als Bankfeed zu aktivieren, müssen Sie den Bankfeeddienst Envestnet Yodlee einrichten und aktivieren und dann Ihr Bankkonto mit den entsprechenden Onlinebankkonten verbinden. Für weitere Informationen, siehe [So gehts: Einrichten des Envestnet Yodlee Bank-Feed-Service](bank-how-setup-bank-statement-service.md).

**Notiz**: Der Bank-Feed-Service Envestnet Yodlee oder ein anderer Bankfeeddienstservice Anbieters stehen möglicherweise nicht in der Anwendung zur Verfügung. Erkundigen Sie sich beim zuständigen Microsoft-Partner, wenn Sie einen Bankfeeddienst verwenden möchten, um Bankkontoauszüge zu importieren.

Die Zeilen im Fenster **Bankkontoabstimmung** sind in zwei Bereiche unterteilt. Der Bereich **Bankauszugspositionen** zeigt entweder importierte Banktransaktionen oder Posten mit ausstehenden Zahlungen an. Der Bereich **Bankposten** zeigt die Posten im Bankkonto an.

Die Aktivität der Suche und des Übernehmens der abzustimmenden Bankposten wird als *übereinstimmend* bezeichnet. Sie können auswählen, ob Sie einen automatischen Abgleich vornehmen wollen, indem Sie die Funktion **Automatisch abgleichen** verwenden. Alternativ können Sie in beiden Bereichen Zeilen manuell auswählen, um die Bankkontoauszugszeile mit einem oder mehreren entsprechenden Bankposten zu verknüpfen und anschließend die Funktion **Manuell abgleichen** verwenden. Das Kontrollkästchen **Ausgeglichen** ist in Zeilen ausgewählt, in denen Posten übereinstimmen.

Sie können den Bereich **Bankauszugspositionen** im Fenster **Bankkontoabstimmung** auf folgende Arten ausfüllen:

* Automatisch durch die Anwendung der Funktion **Bankauszug importieren**, um die Zeilen entsprechend der tatsächlichen Bankkontoauszügen auszufüllen, basierend auf einer Datei, die von der Bank bereitgestellt wird.
* Sie können die Funktion **Vorschlagszeilen** manuell verwenden, um die Zeilen mit Posten für Rechnungen auszufüllen, die noch zur Zahlung ausstehen.

Wenn der Wert im Feld **Gesamtsaldo** im Bereich **Bankauszugspositionen** dem Wert im Feld **Abzustimmender Saldo** im Bereich **Bankposten** entspricht, können Sie die Aktion **Buchen** auswählen, um die saldierten Bankposten abzugleichen.. Jeder nicht zugeordnete Bankposten wird weiterhin im Fenster angezeigt. Dies bedeutet, dass die Zahlungen, die für das Bankkonto verarbeitet werden, nicht im letzten Bankkontoauszug dargestellt sind, oder dass einige Zahlungen als Schecks eingegangen sind.

**Hinweis**: Wenn sich Bankauszugspositionen auf Scheckposten beziehen, können Sie die entsprechenden Funktionen nicht verwenden. Stattdessen müssen Sie die Aktion **Posten ausgleichen** auswählen und im Inforegister Bankauszugspositionen auswählen und dann die entsprechenden Scheckposten auswählen, mit denen Sie die Bankkontoauszugszeile ausgleichen möchten.

## <a name="to-fill-bank-reconciliation-lines-by-importing-a-bank-statement"></a>So füllen Sie Bankabstimmungszeilen mithilfe des Importierens eines Bankkontoauszugs aus  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkontoabstimmung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus.
3. Wählen Sie im Feld **Bankkontonummer** das entsprechende Bankkonto aus. Die Bankposten, die im Bankkonto vorhanden sind, werden im Bereich **Bankposten** angezeigt.
4. Geben Sie im Feld **Auszugsdatum** das Datum des Kontoauszuges der Bank ein.
5. Geben Sie im Feld **Auszug Schluss-Saldo** den Saldo des Bankauszuges ein.
6. Wenn Sie eine Bankauszugsdatei haben, wählen Sie die Aktion **Bankauszug importieren**.
7. Suchen Sie die Datei und wählen Sie dann **Öffnen**, um die Banktransaktionen in die Zeilen des Fensters **Bankkontoabstimmung** zu importieren.

## <a name="to-fill-bank-reconciliation-lines-with-the-suggest-lines-function"></a>So füllen Sie Bankabstimmungszeilen mit der Funktion "Vorschlagszeilen" aus.
1. Wählen Sie im Fenster **Bankkontoabstimmung** die Aktion **Vorschlagszeilen** aus.
2. Geben Sie im Feld **Startdatum** das früheste Buchungsdatum für die Posten ein, die bei der Abstimmung berücksichtigt werden sollen.
3. Geben Sie im Feld **Enddatum** das späteste Buchungsdatum für die Posten ein, die bei der Abstimmung berücksichtigt werden sollen.
4. Aktivieren Sie das Kontrollkästchen **Mit Schecks** für alle berücksichtigten Scheckposten anstelle der entsprechenden Bankposten.
5. Wählen Sie die Schaltfläche **OK**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-automatically"></a>So gleichen Sie Bankkontoauszugszeilen mit Bankposten automatisch ab
1. Wählen Sie im Fenster **Bankkontoabstimmung** die Aktion **Automatisch abgleichen** aus. Das Fenster **Bankposten abstimmen** wird geöffnet.
2. Geben Sie im Feld **Toleranz Buchungsdaten in Tagen** die Anzahl der Tage vor und nach dem Bankpostenbuchungsdatum an, innerhalb dessen die Funktion nach entsprechenden Transaktionsdaten im Bankkontoauszug sucht.

    Wenn Sie "0" eingeben oder das Feld leer lassen, sucht die Funktion **Automatisch abgleichen** nur nach übereinstimmenden Buchungsdaten am Buchungsdatum des Bankpostens.  
3. Wählen Sie die Schaltfläche **OK**.  
Alle Bankkontoauszugszeilen und Bankposten, die zugeordnet werden können, ändern ihre Schriftart zu grün, und das Kontrollkästchen **Ausgeglichen** ist aktiviert.
4. Um eine Übereinstimmung zu entfernen, wählen Sie die Bankkontoauszugszeile, und dann die Aktion **Übereinstimmung entfernen**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-manually"></a>So gleichen Sie manuell Bankauszugspositionen mit Bankposten ab
1. Wählen Sie im Fenster **Bankkontoabstimmung** eine nicht zugeordnete Zeile im Bereich **Bankauszugspositionen** aus.
2. Wählen Sie im Bereich **Bankposten** eine oder mehrere Bankkontoposten aus, die mit der ausgewählten Bankauszugszeile abgeglichen werden können. Um mehrere Zeilen auszuwählen, halten Sie die Strg-Taste gedrückt.  
3. Wählen Sie die Aktion **Manuell abgleichen** aus.

    Die ausgewählte Bankkontoauszugszeilen und die Bankposten ändern ihre Schriftart zu grün, und das Kontrollkästchen **Ausgeglichen** im rechten Fensterbereich ist aktiviert.
4. Wiederholen Sie die Schritte 1 bis 3 für alle Bankkontoauszugszeilen, die nicht abgeglichen wurden.
5. Um eine Übereinstimmung zu entfernen, wählen Sie die Bankkontoauszugszeile, und dann die Aktion **Übereinstimmung entfernen**.

## <a name="to-create-missing-ledger-entries-to-match-bank-transactions-with"></a>So erzeugen Sie fehlende Posten, mit denen Sie die Banktransaktionen abgleichen können
Manchmal enthält ein Bankkontoauszug einen Betrag für berechnete Zinsen oder Gebühren. Solche Banktransaktionen können nicht abgeglichen werden, da keine entsprechenden Posten in Dynamics NAV vorhanden sind. In diesem Fall müssen Sie eine Buch.-Blattzeile für jede Transaktion buchen, um einen entsprechenden Posten zu erstellen, mit dem abgeglichen werden kann.

1. Wählen Sie im Fenster **Bankkontoabstimmung** die Aktion **Übertragung an Fibu Buch.-Blatt** aus.  
2. Geben Sie im Fenster **Bankkto. Ausgl. Fibu Buch.-Bl.** an, welches Fibu Buch.-Blatt verwendet werden soll, und klicken Sie dann auf die Schaltfläche **OK** .

    Das Fenster **Fibu Buch.-Blatt** wird geöffnet und enthält neue Buch.-Blattzeilen für sämtliche Bankauszugspositionen mit fehlende Posten.
3. Vervollständigen Sie die Buch.-Blattzeile mit entsprechenden Informationen, wie z. B. dem Gegenkonto ab. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).  
4. Wählen Sie die Aktion **Buchen** aus.  
Nachdem der Posten gebucht ist, können Sie ihn mit der Banktransaktion abgleichen.
5. Aktualisieren oder öffnen Sie erneut das Fenster **Bankkontoabstimmung**. Der neue Posten erscheint im Bereich **Bankposten**.
6. Vergleichen Sie die Bankkontoauszugszeile mit dem Bankposten, entweder manuell oder automatisch.

## <a name="see-also"></a>Siehe auch  
[Verwalten von Bankkonten](bank-manage-bank-accounts.md)  
[Bank einrichten](bank-setup-banking.md)


---
title: 'So gehts: Arbeiten mit Schecks'
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a>So gehts: Arbeiten mit Schecks
Dynamics NAV unterstützt die elektronische und die manuelle Scheckausstellung. Bei beiden Verfahren erfolgt die Ausstellung von Schecks an Kreditoren über das Zahlungsausgangs-Buch.-Blatt. Sie können auch Schecks annullieren und Scheckposten anzeigen.

Bei dem Verfahren zum Ausstellen von Schecks werden Zahlungsvorschläge gemacht, Scheckposten erstellt und die Computerschecks gedruckt.

Der Drucker muss für den Ausdruck von Scheckformularen eingerichtet werden, und Sie müssen festlegen welches Layout verwendet werden soll. Weitere Informationen zum Definieren von Attributen finden Sie unter [So gehts: Definieren von Scheck-Layouts](finance-setup-how-define-check-layouts.md).

## <a name="to-issue-checks"></a>Um Schecks auszustellen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlung Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie das Buch.-Blatt mit den entsprechenden Zahlungen aus, z. B. indem Sie die Zahlungsvorschläge verwenden. Weitere Informationen finden Sie unter [Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren](payables-how-suggest-vendor-payments.md).
3. Im Feld **Bankkontozahlungsart** der Buch.-Blattzeilen zur Zahlung, die Sie mit Schecks vornehmen möchten, wählen Sie eine der folgenden Optionen:

 - **Computer Scheck**: Wählen Sie diese Option, wenn Sie einen Scheck über den in der Buch.-Blattzeile angezeigten Betrag drucken wollen. Sie müssen die Schecks drucken, bevor Sie die Buch.-Blattzeilen buchen können. Sie können **Computer Scheck** nur auswählen, wenn **Gegenkontoart** oder **Kontoart** den Wert **Bankkonto** hat.

 - **Manueller Scheck**: Wählen Sie diese Option, wenn Sie einen Scheck manuell ausstellen und einen entsprechenden Scheckposten über diesen Betrag anlegen möchten. Mit dieser Option ist das automatische Drucken von Schecks in Dynamics NAV nicht möglich. Sie können **Manueller Scheck** nur auswählen, wenn **Gegenkontoart** oder **Kontoart** den Wert **Bankkonto** hat.

    **Hinweis**: Sie müssen die Computer Schecks drucken, bevor Sie die entsprechenden Buch.-Blattzeilen buchen können.
4. Im Falle von Computer Schecks wählen Sie **Scheck drucken** aus.
5. Füllen Sie im Fenster **Check** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
6. Wählen Sie die Schaltfläche **Drucken** aus.

**Hinweis**: Wenn Sie Schecks in mehreren Währungen von mehreren Bankkonten aus ausdrucken möchten, muss die Stapelverarbeitung **Scheck drucken** für jede einzelne Währung ausgeführt und das entsprechende Bankkonto muss angegeben werden.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>So stornieren Sie gedruckte Schecks, die nicht gebucht wurden
Sie können nicht gebuchte Schecks stornieren, nachdem sie gedruckt wurden, indem Sie die Aktion **Scheck annullieren** im Fenster **Zahlungsausgangs Buch.-Blatt** verwenden.
1. Wählen Sie im Fenster **Zahlungsausgangs Buch.-Blatt** **Scheck annullieren** aus, und wählen Sie aus, welche Prüfungen durchgeführt zum stornieren mit den Schecks durchgeführt werden.

## <a name="to-void-checks"></a>Annullieren von Schecks
Wenn Scheckzahlung gebucht wurden, können Sie Schecks aus den resultierenden Bankposten nur stornieren (annulieren).

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie das entsprechende Bankkonto aus, wählen Sie die **Bearbeiten**-Aktion aus, und wählen Sie dann die **Scheckposten**-Aktion aus.
3. Im **Scheckposten**-Fenster wählen Sie die **Scheck annullieren**-Aktion aus.
4. Wählen das Kontrollkästchen **Scheck nur annullieren**.
5. Wählen Sie die Schaltfläche **OK** aus.

## <a name="see-also"></a>Siehe auch
[Verwalten von Verbindlichkeiten](payables-manage-payables.md)  
[Bank einrichten](bank-setup-banking.md)  


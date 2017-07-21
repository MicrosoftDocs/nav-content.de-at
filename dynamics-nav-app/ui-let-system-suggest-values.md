---
title: Dynamics NAV Werte vorschlagen lassen
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
ms.openlocfilehash: 889d0aa5da36d7a4b7e2be1d796ac95e74aaaaf6
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="letting-dynamics-nav-suggest-values"></a>Dynamics NAV Werte vorschlagen lassen
Dynamics NAV kann Ihnen dabei helfen, Aufgaben schneller und korrekter zu erledigen, indem es Felder oder Zeilen mit Daten ergänzt, die Sie sonst berechnen und manuell eingeben müssten. Obwohl solche automatische Dateneingaben immer korrekt sind, können Sie diese später ändern, wenn Sie dies wünschen.

Funktionen, die Feldwerte für Sie eingeben, werden in der Regel für Aufgaben angeboten, in denen Sie große Volumen von Transaktionsdaten eingeben müssen und Fehler vermeiden und Zeit sparen möchten. Dieses Thema enthält eine Auswahl solcher Funktionen. Weitere Abschnitte werden in zukünftigen Aktualisierungen von Dynamics NAV hinzugefügt.

## <a name="the-suggest-balancing-amount-check-box-in-the-general-journal-batches-window"></a>Das Kontrollkästchen **Ausgleichsbetrag vorschlagen** im **Fibu Buch.-Blattnamen** Fenster
Wenn Sie beispielsweise von Fibu Buch.-Blattzeilen mehrere Ausgaben eingeben, die alle in demselben Bankkonto gebucht werden müssen, dann wird jedes Mal, wenn Sie eine neue Buch.-Blattzeile für Ausgaben eingeben, das Feld **Betrag** auf der Bankkontoenzeile automatisch mit dem Betrag aktualisiert, mit dem die Ausgabe ausgeglichen ist. Weitere Informationen zum Arbeiten mit Fibu Buch.-Blättern, finden Sie unter [Arbeiten mit Fibu Buch.-Blätter](ui-work-general-journals.md)

### <a name="to-have-the-amount-field-on-balancing-general-journal-lines-filled-automatically"></a>Um das Feld **Betrag** auf Fibu Buch.-Blattzeilen automatisch zu aktualisieren.
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie in der Zeile für Ihren bevorzugten Fibu Buch.-Blattnamen das Kontrollkästchen **Ausgleichbetrag vorschlagen**.
3. Öffnen Sie das Fibu Buch.-Blatt, um Transaktionen unter Verwendung der beschriebenen Funktionen zum automatischen Buchen eines Feldwerts zu erfassen und zu buchen.       

Weitere Informationen darüber, wie ein persönliches Buch.-Blatt zum Beispiel für die Ausgabenbehandlung eingerichtet wird, finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).

## <a name="the-automatically-fill-date-received-field-in-the-payment-registration-window"></a>Das Feld **Automatisch empfangene Daten einsetzen** im Fenster **Zahlungs-Registrierung**
Das Fenster **Zahlungs-Registrierung** zeigt ausstehende eingehende Zahlungen als Zeilen an, welche gebuchte Verkaufsbelege darstellen, in denen ein Betrag zur Zahlung fällig ist. Weitere Informationen finden Sie unter [Vorgehensweise: Manuelles Abstimmen von Debitoren-Zahlungen aus einer Liste mit unbezahlten Verkaufsbelegen](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)

Ihre Hauptaktionen im Fenster ist es das Kontrollkästchen **Getätigte Zahlungen** und das Feld **Eingangsdatum** auszufüllen. Sie können Dynamics NAV so einrichten, dass das Arbeitsdatum automatisch im Feld **Empfangsdatum** ausgefüllt wird, wenn Sie das Kontrollkästchen **Zahlung getätigt** aktivieren.

### <a name="to-have-the-date-received-field-in-the-payment-registration-window-filled-automatically"></a>Um das Feld **Eingangsdatum** im Fenster **Zahlungs-Registrierung** automatisch auszufüllen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung der Zahlungserfassung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie das Kontrollkästchen **Eingangsdatum automatisch ausfüllen** ** aus.
3. Öffnen Sie das Fenster **Zahlungs-Registrierung** und fahren Sie fort, um eingehende Debitorenzahlungen anhand der beschriebenen Funktionen zum automatischen Posten eines Feldwerts zu verarbeiten.

## <a name="see-also"></a>Siehe auch
[Arbeiten mit Dynamics NAV](ui-work-product.md)  
[Finanzen](Finance.md)


---
title: 'Vorgehensweise: Zahlungen in eine Bankdatei exportieren'
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
ms.openlocfilehash: 09bdf56b3d5e76b12d868091e89232ce9c08e215
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-export-payments-to-a-bank-file"></a>Vorgehensweise: Zahlungen in eine Bankdatei exportieren
Wenn Sie bereit sind, Zahlungen an Ihre Kreditoren mit dem Fenster **Zahlung Buch.-Blatt** vorzunehmen, können Sie eine Datei mit den Zahlungsinformationen auf den Buch.-Blattzeilen exportieren. Sie können die Datei dann zu Ihrer elektronischen Bank hochladen, um die entsprechenden Geldüberweisungen zu verarbeiten.

In der generischen Version von Dynamics NAV wird ein globaler Diensteanbieter eingerichtet und verbunden, der Bankdaten in das Dateiformat konvertiert, das Ihre Bank benötigt.

**Hinweis**: Bevor Sie aus einem Zahlungsausgangs-Buch exportieren können, müssen Sie den Export auf dem zugehörigen Buch.-Blattnamen aktivieren. Darüber hinaus müssen Ihr Bankkonto und das des Kreditors für elektronische Zahlungen eingerichtet werden. Für weitere Informationen, siehe [Gewusst wie: Einrichten des Bankdatenkonvertierungsservice](bank-how-setup-bank-data-conversion-service.md).

Sie verwenden das Fenster **Kreditübertragungsjournale**, um die Zahlungsdateien anzuzeigen, die aus dem Zahlungsausgangs Buch.-Blatt exportiert wurden. Von diesem Fenster aus können Sie Zahlungsdateien auch erneut exportieren (im Fall von technischen Fehlern oder Dateiänderungen).

## <a name="to-export-payments-to-a-bank-file"></a>Zahlungen in eine Bankdatei exportieren
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlung Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie die Buch.-Blattzeilen z. B. mit der Funktion **Zahlungsvorschlag** aus. Weitere Informationen finden Sie unter [Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren](payables-how-suggest-vendor-payments.md).  
3. Wenn Sie alle Zahlungsausgangs Buch.-Blattzeilen abgeschlossen haben, wählen Sie **Zahlung in Datei exportieren** aus.

    Vorhandene Fehlermeldungen werden in der **Fehler Zahlungsdatei**-Infobox angezeigt, in der Sie eine Fehlermeldung festlegen können, um ausführliche Informationen anzuzeigen. Sie müssen alle Fehler lösen, bevor die Zahlungsdatei exportiert werden kann.

    **Tipp**: Wenn Sie den Bankdaten-Konvertierungsdienst verwenden, meldet eine häufige Fehlermeldung, dass die Bankkontonummer nicht die Länge hat, die Ihre Bank benötigt. Um den Fehler zu vermeiden oder zu beheben, müssen Sie den Wert im **IBAN**-Feld im **Bankkontokarte**-Fenster entfernen, und dann im Feld **Bankkontonummer** eine Bankkontonummer im Format eingeben, das die Bank benötigt.
4. Geben Sie im Fenster **Speichern unter** den Speicherort an, zu dem die Datei exportiert werden soll, und wählen Sie dann **Speichern**.

Die Bankzahlungsdatei wird in den Speicherort exportiert, den Sie festlegen, und Sie können fortfahren, sie in das elektronische Bankkonto hochzuladen und die tatsächlichen Zahlungen zu leisten.

Wenn Sie die Bestätigung erhalten, dass die Zahlungen erfolgreich von der Bank verarbeitet wurden, können Sie die exportierten Zahlungsausgangs Buch.-Blattzeilen buchen.

## <a name="to-plan-when-to-post-exported-payments"></a>Um die Buchung von exportierten Zahlungen zu planen
Wenn Sie keine Buch.-Blattzeile für eine exportierte Zahlung buchen möchten, weil Sie beispielsweise eine Bestätigung erwarten, dass die Transaktion von der Bank verarbeitet wurde, können Sie die Buch.-Blattzeile einfach löschen. Falls Sie später eine Buch.-Blattzeile, um den Restbetrag der gebuchten Rechnung zu bezahlen, zeigt das **Exportierter Betrag gesamt**-Feld, wie viel des Zahlungsbetrags bereits exportiert wurde. Detaillierte Informationen über die exportierte Summe können Sie auch finden, indem Sie die Schaltfläche **Posten im Kreditübertragungsjournal** auswählen, um Einzelheiten zu Dateien der exportierten Zahlung anzuzeigen.

Wenn Sie ein Vorgang folgen, bei dem Sie keine Zahlungen buchen bis Sie die Bestätigung haben, dass sie in der Bank verarbeitet wurden, können Sie dieses auf zwei Arten steuern.

* In einem Zahlungsausgangs-Buch.-Blatt mit vorgeschlagenen Zahlungszeilen, können Sie entweder nach der **In Zahlungsdatei exportiert**-Spalte oder nach **Exportierter Betrag gesamt** sortieren, und dann Zahlungsvorschläge für offene Rechnungen, für die bereits Zahlungen geleistet wurden und für die Sie keine Zahlungen leisten möchten, löschen.
* Im Fenster **Zahlungsvorschläge für Kreditoren**, in dem Sie festlegen, welche Zahlungen in das Zahlungsausgangs Buch.-Blatt einzufügen sind, können Sie das Kontrollkästchen **Exportierte Zahlungen überspringen** aktivieren, wenn Sie keine Buch.-Blattzeilen für Zahlungen einfügen möchten, die bereits exportiert wurden.

Um Informationen über exportierte Zahlungen anzuzeigen, wählen Sie die Aktion **Zahlungs-Export-Verlauf**.

## <a name="to-re-export-payments-to-a-bank-file"></a>Um Zahlungen erneut in eine Bankdatei zu exportieren
Sie können Zahlungsdateien aus dem **Kreditübertragungsjournale**-Fenster exportieren. Bevor Sie Zahlungsausgangs Buch.-Blattzeilen löschen oder buchen, können Sie die Zahlungsdatei aus dem **Zahlung Buch.-Blatt**-Fenster auch erneut exportieren, indem Sie es einfach wieder exportieren.

Wenn Sie ein Zahlungsausgangs-Buch.-Blatt gelöscht oder gebucht haben, nachdem Sie es exportiert haben, können Sie dieselbe Zahlungsdatei nur aus dem **Kreditübertragungsjournale**-Fenster erneut exportieren. Wählen Sie die Zeile für den Stapelauftrag für Gutschriftübertragungen aus, die Sie erneut exportieren möchten, und verwenden Sie dann die Aktion **Zahlungen erneut in Datei exportieren**.

## <a name="see-also"></a>Siehe auch
[Kreditoren](payables-manage-payables.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Einkauf einrichten:](purchasing-setup-purchasing.md)


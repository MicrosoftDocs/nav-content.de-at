---
title: "Gewusst wie: Senden von Belegen über E-Mail"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e4476c2ab903001017dcd6c8bdaa84892ba79c9e
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-send-documents-by-email"></a>Gewusst wie: Senden von Belegen über E-Mail
Um die Inhalte von Geschäftsbelegen Ihren Geschäftspartnern rasch zu kommunizieren, wie beispielsweise Zahlungsinformationen auf Verkaufsbelegen an Debitoren, können Sie die Berichtslayoutfunktion verwenden, um dokumentspezifischen Inhalt zu definieren, der automatisch in E-Mail-Texte eingefügt wird.

Um E-Mails aus Dynamics NAV zu aktivieren, starten Sie die unterstützte Einrichtung **E-Mail einrichten** auf der Homepage.

Sie können praktisch alle Belegarten als Dateianhänge in E-Mails direkt im Fenster senden, das den Beleg anzeigt. Zusätzlich zum Dateianhang können Sie dokumentspezifische E-Mail-Texte mit Kerninformationen aus dem Beleg einrichten, der vom Standardtext gefolgt wird, der den E-Mail-Empfänger grüßt und den fraglichen Beleg vorstellt. Um Ihren Debitoren anzubieten, für Verkäufe unter Verwendung eines Zahlungsservice wie Paypal elektronisch zu bezahlen, können Sie die Paypal-Informationen und -Links auch in den E-Mail-Text einfügen.

Von allen unterstützten Belegen initiieren Sie das Übermitteln per E-Mail, indem Sie **Senden** auf gebuchten Belegen oder **Buchen und Senden** auf nicht-gebuchten Belegen auswählen.

Wenn das Feld **E-Mail** Im Fenster **Dokument senden an** auf **JA festgelegt wurde (Aufforderung für Einstellungen)**, dann wird das Fenster **Senden per E-Mail** geöffnet und mit der Kontaktperson im Feld **Zu** ergänzt und das Dokument als PDF-Datei angehängt. Geben Sie im Feld **Text** entweder den Text manuell ein oder Sie können definieren, dass das Feld mit einem dokumentspezifischen E-Mail-Text ausgefüllt wird, den Sie eingerichtet haben.

Nachfolgend wird beschrieben, wie der Bericht **Verkaufsrechnung** für dokumentspezifische E-Mail-Texte verwendet wird, wenn Sie gebuchte Verkaufsrechnungen senden.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>Einen dokumentspezifischen E-Mail-Text für Verkaufsrechnungen einrichten
1. Alternativ wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Berichtauswahl Verkäufe** ein. Wählen Sie dann den zugehörigen Link aus.
2. Im Fenster **Berichts-Auswahl - Verkauf** unter **Verwendung** wählen Sie **Rechnung**.
3. In einer neuen Zeile im Feld **Berichts-ID** wählen Sie beispielsweise Standardbericht 1306.
4. Wählen Sie das Kontrollkästchen **Für E-Mail-Text verwenden**.
5. Wählen Sie das Feld **E-Mail-Text Layout-ID** und wählen Sie anschließend eines der verfügbaren Layouts aus dem **Benutzerdefinierten Berichtlayouts** aus.
6. Berichtslayouts definieren das Format und den Inhalt des E-Mail-Texts, einschließlich den Standardtext, der den Kernbeleginformationen im E-Mail-Text vorangeht.
7. Um das Layout anzusehen oder zu bearbeiten, auf dem der E-Mail-Text basiert, gehen Sie zum Fenster **Benutzerdefinierte Berichtslayouts** und wählen die Aktion **Layout bearbeiten** aus.
8. Um Ihren Debitoren anzubieten, für Verkäufe unter Verwendung eines Zahlungsservice wie Paypal elektronisch zu bezahlen, können Sie die Paypal-Informationen und -Links auch in den E-Mail-Text einfügen. Weitere Informationen finden Sie unter [Vorgehensweise: Aktivieren Sie Debitoren-Zahlungen durch Paypal](sales-how-enable-customer-payments-paypal.md)
9. Wählen Sie die Schaltfläche **OK**.

Wenn Sie jetzt beispielsweise die Sendaktion im Fenster **Gebuchte Verkaufsrechnung** auswählen, enthält der E-Mail-Text die Beleginformationen 1306 des Berichts, der von formatiertem Standardtext entsprechend dem Berichtslayout stammt, das Sie in Schritt 5 ausgewählt haben.

Nachfolgend wird beschrieben, wie eine gebuchte Verkaufsrechnung als E-Mail mit dem Beleg gesendet wird, der als PDF-Datei angehängt ist und einen dokumentspezifischen E-Mail-Text enthält.
## <a name="to-send-documents-by-email"></a>Senden von Belegen über E-Mail
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Gebuchte Verkaufsrechnungen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die relevante Verkaufsrechnung aus und wählen Sie die Aktion **Senden**. Das Fenster **Dokument senden an** wird geöffnet.
3. Wählen Sie im Feld **E-Mail** **Ja (Aufforderung für Einstellung)** aus. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Sendeprofilen](sales-how-setup-document-send-profiles.md).
4. Wählen Sie die Schaltfläche **OK**. Das Fenster **E-Mails senden** wird geöffnet.
5. Im Feld **Zu** geben Sie eine gültige E-Mail-Adresse ein. Der Standardwert ist die E-Mail-Adresse des Debitors.
6. Geben Sie im Feld **CC:** eine E-Mail-Adresse an, um eine Kopie der E-Mail an einen anderen Empfänger zu senden.
7. Geben Sie im Feld **BCC** eine E-Mail-Adresse an, um eine Kopie der E-Mail an einen anderen Empfänger zu senden, ohne dass dessen Name dem anderen Empfängern angezeigt wird.
8. Geben Sie im Feld **Betreff** einen beschreibenden Betreff ein. Der Standardwert ist der Debitorennamen und die Rechnungsnummer.
9. Im Feld **Anhang** wird die generierte Rechnung standardmäßig als PDF_Datei angehängt. Wählen Sie die Suchschaltfläche, um die Datei zu öffnen oder eine andere Datei anzufügen.
10. Geben Sie im **Nachrichtentext**-Feld eine kurze Mitteilung an den Empfänger ein.

    Wenn ein dokumentspezifischer E-Mail-Text im Fenster **Berichts-Auswahl - Verkauf** eingerichtet wird, wird das Feld **Text** automatisch ausgefüllt. Weitere Informationen finden Sie unter “Einrichten eines dokumentspezifischen E-Mail-Texts für Verkaufsrechnungen” im betreffenden Abschnitt zu diesem Thema.
11. Wählen Sie das Kontrollkästchen **Outlook-Webanwendung bearbeiten** , um die E-Mail in der E-Mail-Anwendung für Office 365 zu öffnen.
12. Wählen Sie die Schaltfläche **OK**, um die E-Mail zu senden.

**Hinweis**: Wenn Sie die E-Mail-Einstellungen nicht jedes Mal ändern müssen, wenn Sie ein Dokument per E-Mail senden, können die Option **Ja (Standardeinstellungen verwenden)** im Feld "E-Mail" im Fenster **Dokument senden an** auswählen. In diesem Fall wird das Fenster **E-Mail senden** nicht geöffnet. Siehe dazu auch Schritt 4. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Sendeprofilen](sales-how-setup-document-send-profiles.md).

## <a name="see-also"></a>Siehe auch  
[Arbeiten mit Dynamics NAV](ui-work-product.md)  
[Vorgehensweise: Fakturieren](sales-how-invoice-sales.md)


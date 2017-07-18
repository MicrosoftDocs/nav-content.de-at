---
title: Eingehende Dokumente verwalten
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
ms.openlocfilehash: 49acc3549180b73dada6415f3ea40f17c1dd9e4c
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="manage-incoming-documents"></a>Eingehende Dokumente verwalten
Einige Geschäftstransaktionen werden nicht von Anfang an in Dynamics NAV erfasst. Stattdessen geht ein externes Geschäftsdokument in Ihrem Unternehmen als E-Mail-Anhang oder Papierkopie ein, die Sie in eine Datei scannen. Dieses ist typisch für Einkäufe, wo solche Eingangsbelege Zahlungseingänge für Aufwendungen oder kleine Einkäufe darstellen.

Mithilfe eines externen OCR-Dienstes (optische Zeichenerkennung) können Sie aus PDF- oder Bilddateien, die die Eingangsbelege darstellen, elektronische Belege generieren, die dann in Dynamics NAV in Belegdatensätze konvertiert werden können.

Im Fenster **Eingehende Dokumente** können Sie verschiedene Funktionen zum Überprüfen von Ausgabenbelegen, Verwalten von OCR-Aufgaben und Konvertieren eingehender Belege, manuell oder automatisch, in den entsprechenden Belegen oder Buch.-Blattzeilen verwenden. Die externen Dateien können jeder Prozessphase zugeordnet werden, auch gebuchten Belegen und den resultierenden Kreditoren-, Debitoren- und Sachposten.

Die Verarbeitung von Eingangsbelegen kann aus den folgenden Hauptaktivitäten bestehen:

* Erfassen Sie die externen Belege in Dynamics NAV, indem Sie mithilfe einer der folgenden Methoden Zeilen im Fenster **Eingehende Dokumente** anlegen:
    * Manuell, mithilfe von einfachen Funktionen, entweder von einem PC oder von einem mobilen Gerät aus, auf eine der folgenden Arten:
        * Verwenden Sie die Schaltfläche **Aus Datei erstellen** und füllen Sie dann die entsprechenden Felder im Fenster **Eingehender Beleg** aus. Die Datei wird automatisch angehängt.  
        * Verwenden Sie die Schaltfläche **Neu**, füllen Sie dann die entsprechende Felder im Fenster **Eingehender Beleg** aus und hängen Sie die betreffende Datei an.
        * Auf einem Tablet oder einem Telefon verwenden Sie die Schaltfläche **Von Kamera erstellen**, um einen neuen Eingangsbelegsdatensatz zu erstellen, und senden das Bild dann beispielsweise an den OCR-Dienst.
    * Automatisch, indem Sie den Beleg vom OCR-Dienst als ein elektronisches Dokument empfangen, nachdem Sie die zugehörige PDF- oder Bilddatei per E-Mail an den OCR-Dienst gesendet haben. Das Inforegister **Finanzinformationen** wird automatisch im Fenster **Eingehender Beleg** ausgefüllt.
* Nutzen Sie den OCR-Dienst zur Umwandlung von PDF- oder Bilddateien in elektronische Belege, die in Dynamics NAV in Belegdatensätze konvertiert werden können.
* Erstellen Sie neue Belege oder eine Fibu Buch.-Blattzeilen aus einem eingehenden Belegdatensatz, indem sie die Informationen so eingeben, wie sie in den eingehenden Belegen stehen.
* Fügen Sie eingehender Belege zu Einkaufs- und Verkaufsbelegen jeden möglichen Status hinzu, einschließlich der resultierenden Kreditor, Debitor- und Sachposten, die aus dem Buchen resultieren.
* Zeigen Sie Eingangsbelege und deren Anhänge aus Einkaufs- und Verkaufsbelegen oder Posten an, oder finden Sie alle Sachposten ohne Eingangsbelege im Fenster **Kontenplan**.


|Aktion |Siehe |
|---|----|
|Richten Sie die Funktion für Eingangsbelege und den OCR-Dienst ein.|[Gewusst wie: Eingehende Dokumente einrichten](across-how-setup-income-documents.md)|
|Erstellen Sie eingehende Belegdatensätze, fügen Sie Dateien hinzu, nutzen Sie OCR, um PDF-Dateien in elektronische Belege umzuwandeln, konvertieren Sie elektronische Belege in Belegdatensätze, überwachen Sie eingehende Belegdatensätze aus gebuchten Verkaufs- und Einkaufsbelegen.|[Eingehende Dokumente verarbeiten](across-process-income-documents.md)|

## <a name="see-also"></a>Siehe auch  
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


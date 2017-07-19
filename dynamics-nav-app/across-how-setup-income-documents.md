---
title: 'Gewusst wie: Eingehende Dokumente einrichten'
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
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>Gewusst wie: Eingehende Dokumente einrichten
Wenn Sie Fibu Buch.-Blattzeilen für eingehende Belegdatensätze erstellen, müssen Sie im Fenster **Einrichtung für eingehende Dokumente** angeben, welche Buch.-Blattvorlage und welches Buch.-Blatt verwendet werden sollen.

Wenn Sie nicht möchten, dass Benutzer Rechnungen oder Fibu Buch.-Blattzeilen anhand von eingehende Belegdatensätzen erstellen können, ausser, wenn diese genehmigt sind, müssen Sie Genehmiger im Fenster **Genehmiger für eingehendes Dokument** einrichten.

Um PDF und Bilddateien in elektronische Dokumente umzuwandeln, zum Beispiel Einkaufsrechnungen innerhalb von Dynamics NAV, müssen Sie zuerst die OCR-Funktion einrichten und den Dienst aktivieren.

Wenn die Funktion für Eingangsbelege eingerichtet ist, können Sie verschiedene Funktionen zum Überprüfen von Ausgabenbelegen, Verwalten von OCR-Aufgaben und Konvertieren von Eingangsbelegen, manuell oder automatisch, in den entsprechenden Belegen oder Buch.-Blattzeilen verwenden. Die externen Dateien können jeder Prozessphase zugeordnet werden, auch gebuchten Belegen und den resultierenden Kreditoren-, Debitoren- und Sachposten. Weitere Informationen finden Sie unter [So gehts: Eingehende Dokumente verarbeiten](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>So richten Sie die Funktion für Eingangsbelege ein
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung für eingehende Dokumente** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>So richten Sie Genehmiger für Eingangsbelege ein
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung für eingehende Dokumente** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie im Fenster **Einrichtung für eingehende Dokumente** die Aktion **Genehmiger** aus.

    Im Fenster **Genehmiger für eingehendes Dokument** werden alle Benutzer angezeigt, die in Ihrem Dynamics NAV eingerichtet sind.  
3. Wählen Sie mindestens einen Benutzer aus, der einen eingehenden Beleg genehmigen kann, bevor eine zugehörige Beleg- oder Buch.-Blattzeile erstellt werden kann.

Nachdem Sie Genehmiger im Fenster **Genehmiger für eingehendes Dokument** eingerichtet haben, können nur diese Benutzer ein eingehendes Dokument genehmigen, wenn im Fenster **Einrichtung für eingehende Dokumente** das Kontrollkästchen **Genehmigung zum Erstellen anfordern** aktiviert ist.

**Hinweis**: Diese Genehmigungseinrichtung ist nicht mit den Genehmigungsworkflows verknüpft. Weitere Informationen erhalten Sie unter [So gehts: Genehmigungsworkflow verwenden](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>So richten Sie einen OCR-Service ein
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **OCR-Dienst einrichten** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.


## <a name="to-encrypt-your-login-information"></a>So verschlüsseln Sie Ihre Anmeldeinformationen
Es wird empfohlen, dass Sie die Anmeldeinformationen, die Sie im Fenster **OCR-Dienst einrichten** eingeben, schützen. Sie können Daten auf dem Server verschlüsseln, indem Sie neue Verschlüsselungsschlüssel erstellen oder vorhandene importieren, die Sie auf der Serverinstanz aktivieren, die mit der Datenbank verknüpft ist.

1. Wählen Sie im Fenster **OCR-Dienst einrichten** die Aktion **Verschlüsselungsverwaltung**.
2. Aktivieren Sie im Fenster **Datenverschlüsselungsverwaltung** die Verschlüsselung der Daten.

## <a name="see-also"></a>Siehe auch  
[Eingehende Dokumente verarbeiten](across-process-income-documents.md)  
[Eingehende Belege](across-income-documents.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


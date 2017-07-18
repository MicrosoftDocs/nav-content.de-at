---
title: 'Vorgehensweise: Erstellen von Eingangsbelegen'
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
ms.openlocfilehash: 10ba191b197be8b98b2d5d5ab9ac4bc3baf0d82b
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-incoming-document-records"></a>Vorgehensweise: Erstellen von Eingangsbelegen
Im Fenster **Eingehende Dokumente** können Sie verschiedene Funktionen zum Überprüfen von Ausgabenbelegen, Verwalten von OCR-Aufgaben und Konvertieren eingehender Belege, manuell oder automatisch, in den entsprechenden Belegen oder Buch.-Blattzeilen verwenden. Die externen Dateien können jeder Prozessphase zugeordnet werden, auch gebuchten Belegen und den resultierenden Kreditoren-, Debitoren- und Sachposten.

Um einen externen Beleg in Dynamics NAV aufzuzeichnen, müssen Sie zuerst einen Datensatz des eingehenden Belegdatensatzes anlegen oder ausfüllen. Dies kann manuell erfolgen, oder Sie können ein Foto des externen Belegs machen und einen Eingangsbelegsdatensatz mit der angehängten Bilddatei erstellen.

Bevor Sie die Funktion für Eingangsbelege verwenden können, müssen Sie sie entsprechend einrichten. Weitere Informationen finden Sie unter [So gehts: Einrichten von eingehenden Belegen](across-how-setup-income-documents.md).

## <a name="to-approve-or-reject-an-incoming-document"></a>So können Sie einen eingehenden Beleg genehmigen oder ablehnen
Wenn Sie wünschen, dass Benutzer Rechnungen oder Hauptjournalzeilen aus Eingangsbelegen nur dann erstellen dürfen, wenn diese genehmigt sind, können Sie Genehmiger einrichten, die alle Belege genehmigen müssen, bevor sie verarbeitet werden können.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Eingehende Belege** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Zeile mit dem Beleg, den Sie genehmigen oder ablehnen möchten, und wählen Sie dann die Aktion **Genehmigen** oder **Ablehnen** aus.

Das Kontrollkästchen **Freigegeben** in der Zeile für den Eingangsbeleg ist aktiviert, wenn dieser genehmigt wurde. Der jeweilige Benutzer, beispielsweise der für das Erstellen von Einkaufsrechnungen zuständige, kann dann fortfahren, den Datensatz zu verarbeiten.

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a>So erstellen Sie Eingangsbelegdatensätze indem Sie ein Foto machen
**Hinweis**: Der folgende Vorgang gilt nur für Dynamics NAV-Tablet- und Smarpthone-Clients.

1. Wählen Sie auf der App-Leiste die Kachel **Erstellen von eingehendem Beleg von Kamera**, und wechseln Sie dann zu Schritt 4.
2. Wählen Sie alternativ in er Anwendungsleiste die Optionsschaltfläche aus, wählen Sie **Eingehende Belege** und wählen Sie dann **Alle** aus.
3. Verwenden Sie im Fenster **Eingehende Belege** die Auslassungspunkt-Schaltfläche, und wählen Sie dann **Von Kamera erstellen** aus. Die Kamera im Tablet oder dem Smartphone wird aktiviert.
4. Nehmen Sie ein Foto eines Belegs, wie einer Einkaufsquittung, die Sie als eingehender Beleg bearbeiten wollen, und wählen Sie dann die Schaltfläche **OK**.

Ein neuer Datensatz für den eingehenden Beleg wird erstellt und das Bild wird angehängt.

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a>So hängen Sie ein Bild an ein Eingangsbelegdatensatz an, indem Sie ein Foto machen
**Hinweis**: Der folgende Vorgang gilt nur für Dynamics NAV-Tablet- und Smarpthone-Clients.

1. Wählen Sie auf der App-Leiste die Optionsschaltfläche aus, wählen Sie **Eingehende Belege** und wählen Sie dann **Alle** aus.
2. Öffnen Sie die Karte eines vorhandenen eingehenden Belegsdatensatzes.
3. Verwenden Sie im Fenster **Eingehende Belege** die Auslassungspunkt-Schaltfläche, und wählen Sie dann **Bild von Kamera anhängen** aus. Die Kamera im Tablet oder dem Smartphone wird aktiviert.
4. Nehmen Sie ein Foto eines Belegs, wie einer Einkaufsquittung, die Sie als eingehender Beleg bearbeiten wollen, und wählen Sie dann die Schaltfläche **OK**.

Das Bild wurde dem Datensatz des eingehenden Beleges angehängt.

## <a name="to-create-an-incoming-document-record-manually"></a>Eingangsbelege manuell erstellen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Eingehende Belege** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Aus Datei erstellen** aus.  
3. Wählen Sie im Fenster **Datei einfügen** eine Datei aus und wählen Sie dann **Offen** aus.

    Die Datei wird automatisch angehängt.
4. Wählen Sie alternativ die Aktion **Neu** aus.
5. Um eine Datei hinzuzufügen, wählen Sie die Aktion **Datei anhängen**.
6. Im **Datei einfügen**-Fenster wählen Sie die Datei, die den jeweiligen Eingangsbeleg darstellt, und wählen Sie die Schaltfläche **Öffnen**.
7. Füllen Sie im Fenster **Eingehende Belege** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

##<a name="see-also"></a>Siehe auch  
[Eingehende Dokumente verarbeiten](across-process-income-documents.md)  
[Eingehende Belege](across-income-documents.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


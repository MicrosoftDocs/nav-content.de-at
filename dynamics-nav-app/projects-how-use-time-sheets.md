---
title: "Gewusst wie: Verwenden von Arbeitszeittabellen für Projekte"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: b4f766dd5d614d339b16c00f2988a4130edc39ff
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-use-time-sheets-for-jobs"></a>Gewusst wie: Verwenden von Arbeitszeittabellen für Projekte
Verwenden Sie die Stapelverarbeitung **Arbeitszeittabellen erstellen**, um Arbeitszeittabellen für eine bestimmte Anzahl von Perioden oder Wochen einzurichten. Sie müssen Berechtigungen haben, Arbeitszeittabellen zu erstellen.

Sie können Ihre Projektplanzeilen in die Arbeitszeittabelle kopieren und verwenden. Auf diese Art müssen Sie die Informationen immer nur an einer Stelle eingeben und die Zeileninformationen sind immer korrekt.

Nachdem Sie Arbeitszeittabellenposten für ein Projekt genehmigt haben, können Sie sie in das entsprechende Projektjournal oder Ressourcen-Journal buchen.

Bevor Sie Arbeitszeittabellen verwenden können, müssen Sie Informationen einrichten und einen Administrator und mindestens einen Genehmiger für Arbeitszeittabellen festlegen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Arbeitszeittabellen](projects-how-setup-time-sheets.md).

## <a name="to-create-a-time-sheet"></a>Arbeitszeittabellen erstellen  
Sie können die Stapelverarbeitung **Arbeitszeittabellen erstellen** verwenden, um Arbeitszeittabellen für eine bestimmte Anzahl von Perioden oder Wochen einzurichten. Nachdem eine Arbeitszeittabelle erstellt wurde, kann der Arbeitszeittabellenbesitzer sie öffnen und die Zeit aufzeichnen, die für eine Aufgabe benötigte wurde.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Im Fenster **Arbeitszeittabellen-Liste** wählen Sie die Aktion **Arbeitszeittabellen erstellen** aus.
3. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

**Notiz**: Die Felder **Arbeitszeittabellen verwenden** und **Arbeitszeittabellenbesitzer-Benutzer-ID** müssen auf der Karte der Arbeitszeittabelle für die Ressource ausgefüllt werden.  

4. Wählen Sie die Schaltfläche **OK** aus.
Im Fenster **Liste Arbeitszeittabelle** können Sie die erstellten Arbeitszeittabellen anzeigen.

## <a name="to-copy-job-planning-lines-to-a-time-sheet"></a>So kopieren Sie Projektplanzeilen in eine Arbeitszeittabelle:  
Die folgende Vorgehensweise beschreibt, wie Projektplanzeilen einer Arbeitszeittabelle enfach hinzugefügt werden können.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Im Fenster **Arbeitszeittabellen-Liste** wählen Sie eine Arbeitszeittabelle für den entsprechenden Zeitraum aus und wählen Sie dann die Aktion **Arbeitszeittabelle bearbeiten** aus.  
3. Wählen Sie die Aktion **Zeilen von Projektplanung erstellen** aus. Jegliche Projektplanzeilen im Arbeitszeittabellenzeitraum werden in die Arbeitszeittabelle für die Person oder die Maschine unter **Ressourcennummer** kopiert. Feld auf der Arbeitszeittabelle.

## <a name="to-define-work-types-and-add-one-to-a-time-sheet"></a>Um Arbeitstypen festzulegen und einer Arbeitszeittabelle hinzufügen  
Sie können den Arbeitstyp für alle Arbeitszeittabellenzeilen für Projekte festlegen. Auf diese Art können Sie Informationen hinzufügen, die Sie benötigen, um dem Debitor unterschiedliche Arten von Arbeit zu berechnen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen** ein. Wählen Sie dann den zugehörigen Link aus.   
2. Öffnet die entsprechende Arbeitszeittabelle.
3. Wählen Sie das Feld **Beschreibung**.  
4. Im Fenster **Arbeitszeittabellenzeilen-Projekt-Detail** wählen Sie das Feld **Arbeitstypencode** und wählen Sie einen Arbeitstyp aus der Liste aus, wie beispielsweise **Meilen**.  
5. Wenn keine Arbeitstypen vorhanden sind, wählen Sie die Aktion **Neu** aus.
6. Im Fenster **Arbeitstypen** füllen Sie die notwendigen Felder aus.
7. Wiederholen Sie Schritt 4, um den neuen Arbeitstyp in der Arbeitszeittabelle einzugeben.

## <a name="to-reuse-time-sheet-lines-in-other-time-sheets"></a>So können Sie Arbeitszeittabellenzeilen in anderen Arbeitszeittabellen wiederverwenden  
Falls die Arbeitszeittabelle Informationen von einem Zeitraum zum anderen gleich bleiben, können Sie Zeit sparen, indem Sie die Zeilen aus dem vorherigen Zeitraum kopieren. Tragen Sie dann einfach Ihren Zeitverbrauch für die neuen Periode ein.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Öffnen Sie die Arbeitszeittabelle für eine Periode nach der Periode für eine vorhandene Arbeitszeittabelle mit Zeilen.  
3. Wählen Sie die Aktion **Zeilen aus vorherigen Arbeitszeittabellen kopieren** aus.

Die Zeilen werden kopiert, einschließlich Informationen wie Art und Beschreibung. Wenn beispielsweise die Zeile mit einem Projekt verknüpft ist, wird die **Projektnr.** kopiert. Alle kopierten Zeilen haben den Status **Offen**. Sie können die benutzerdefinierten Zeilen jetzt bei Bedarf ändern.

## <a name="to-fill-in-a-time-sheet-lines-and-submit-for-approval"></a>So können Sie Arbeitszeittabellenzeilen ausfüllen und zur Genehmigung senden  
Die Arbeitszeittabellenregistrierung wird in Stunden verfolgt, der Standard-Basiseinheit für Ressourcen. Standardmäßig zeigt eine Arbeitszeittabelle die allgemeinen Arbeitstage von Montag bis Freitag an.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie eine Arbeitszeittabelle für den entsprechenden Zeitraum aus und wählen Sie dann die Aktion **Arbeitszeittabelle bearbeiten** aus.  
3. Füllen Sie die Felder in einer neuen Zeile wie erforderlich aus. Geben Sie die Anzahl der Stunden ein, die von der Ressource an jedem Wochentag verwendet werden.

    **Hinweis**: Sie können die Summe der Arbeitszeittabellenstunden überprüfen, die Sie in die Infobox **Tatsächlich/Budgetiert** eingegeben haben.  

4. Wiederholen Sie Schritt 3 für weitere Arbeitstypen, die die Ressource ausführt.
5. Wählen Sie die Aktion **Übermitteln** aus und wählen Sie dann die Aktion **Alle offenen Zeilen**, um alle Zeilen zu senden oder **Nur ausgewählte Zeilen**, um nur die Zeilen zu übermitteln, die im Fenster **Arbeitszeittabelle** ausgewählt wurden.  

    **Hinweis**: Sie können nur Arbeitszeitta‎bellenzeilen senden, für die Sie Zeit eingegeben haben.  

6. Um Informationen in einer Zeile zu ändern, die auf **Übermittelt** festgelegt wurde, wählen Sie die Zeile und wählen Sie dann die Aktion **Erneut öffnen** aus.

    **Hinweis**: Ein Manager weist möglicherweise eine Arbeitszeittabellenzeile zurück, die zur Genehmigung eingesendet wird. Wenn eine Zeile den Status **Abgelehnt** hat, können Sie an der Zeile Änderungen vornehmen und dann erneut **Übermitteln** wählen.  

7. Wählen Sie die Schaltfläche **OK** aus.

## <a name="to-approve-or-reject-a-time-sheet"></a>So können Sie Arbeitszeittabellen genehmigen und ablehnen:  
Eine Arbeitszeittabelle muss zur Genehmigung eingereicht werden, bevor Sie verwendet wird. Sie können einzelne Zeilen in der Arbeitszeittabelle genehmigen oder ablehnen und sie wieder an den Antragsteller für zusätzliche Aktion senden. Eine Arbeitszeittabelle kann auf zwei Arten genehmigt werden:
- Ein Arbeitszeittabellenadministrator kann jede Arbeitszeittabelle genehmigen.
- Die Person, die im Feld **Arbeitszeittabellen-Genehmiger Benutzer-ID** in einer Ressourcenkarte angegeben wird, kann die Arbeitszeittabellen dieser Ressource genehmigen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Arbeitszeittabellen](projects-how-setup-time-sheets.md).

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen-Manager** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie eine Arbeitszeittabelle aus der Liste aus.  
3. Wählen Sie im Fenster **Arbeitszeittabelle** die Aktion **Genehmigen** aus, und wählen Sie die Aktion **Alle übermittelten Zeilen**, um alle Zeilen zu übermitteln oder **Nur ausgewählte Zeilen**, um nur jene Zeilen zu genehmigen, die im Fenster **Arbeitszeittabelle** ausgewählt wurden.
4. Wählen Sie die Schaltfläche **OK** aus.  
5. Alternativ wählen Sie die Aktion **Ablehnen** und führen Sie die Schritte 4 bis 5 aus.  

**Hinweis**: Verwenden Sie die Infoboxen **Arbeitszeittabellenstatus** uns **Tatsächliche/Geplante Zusammenfassung** aus, um einen schnellen Überblick zu Arbeitszeittabelleninformationen zu erhalten.

Nachdem Sie eine Arbeitszeittabelle genehmigt oder abgelehnt haben, kann sie nicht mehr bearbeitet werden, außer wenn sie zuerst wieder geöffnet wird. Verwenden Sie das folgende Vorgehen, um eine genehmigte oder zurückgewiesene Arbeitszeittabelle erneut zu öffnen.

## <a name="to-reopen-a-time-sheet"></a>So öffnen Sie eine Arbeitszeittabelle erneut:  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Manager Arbeitszeittabelle** oder **Arbeitszeittabelle**ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnet eine Arbeitszeittabelle aus der Liste.  

    **Hinweis**; Sie können Zeilen nur erneut öffnen, die den Status **Genehmigt** haben. Sie können keine Zeilen erneut öffnen, die den Status **Abgelehnt** haben. Sie können eine Arbeitszeittabelle nicht erneut öffnen, wenn diese gebucht wurde.  

3. Wählen Sie im Fenster **Arbeitszeittabelle** die Aktion **Erneut öffnen** aus, und wählen Sie die Aktion **Alle übermittelten Zeilen**, um alle Zeilen erneut zu öffnen oder **Nur ausgewählte Zeilen**, um nur jene Zeilen zu öffnen, die im Fenster **Arbeitszeittabelle** ausgewählt wurden.
4. Wählen Sie die Schaltfläche **OK** aus. Der Status der Arbeitszeittabellen, Zeile oder Zeilen wechselt auf **Übermittelt**.  

## <a name="to-post-time-sheet-lines-in-a-resource-journal"></a>Buchen von Arbeitszeittabellenzeilen zu einem Ressourcen-Buch.-Blatt  
Nachdem Sie Arbeitszeittabellenposten für eine Ressource genehmigt haben, können Sie sie in das entsprechende Ressourcen-Buch.-Blatt buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen-Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Aktion **Zeilen von Arbeitszeittabellen vorschlagen** aus.  
3. Füllen Sie die Felder je nach Bedarf aus.  
4. Wählen Sie die Schaltfläche **OK** aus. Einträge für Verbrauch werden im Ressourcen Buch.-Blatt erstellt, in dem Sie die Informationen ändern können.  
5. Wählen Sie die Aktion **Buchen** aus.  
6. Um die Buchung zu überprüfen, wählen Sie die Aktion **Sachposten** aus. Das Fenster **Ressourcen-Buch.-Blatt** öffnet die Anzeige des Ergebnisses der Buchung des Ressourcen Buch.-Blattes.

## <a name="to-post-time-sheet-lines-in-a-job-journal"></a>Buchen von Arbeitszeittabellenzeilen in einem Ressourcen-Buch.-Blatt  
Nachdem Sie Arbeitszeittabellenposten für ein Projekt genehmigt haben, können Sie sie in das Projektbuchungsblatt des entsprechenden Projekts buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Projekt Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Aktion **Zeilen von Arbeitszeittabellen vorschlagen** aus.  
3. Füllen Sie die Felder je nach Bedarf aus.  
4. Wählen Sie die Schaltfläche **OK** aus. Einträge für Verbrauch werden im Ressourcen Buch.-Blatt erstellt, in dem Sie die Informationen ändern können.  

    **Hinweis**: Informationen über den Arbeitstyp und ob die Arbeit fakturierbar ist, werden aus der Arbeitszeittabellenzeile kopiert. Bei Bedarf können Sie die Anzahl der Stunden reduzieren und eine Teilbuchung durchführen. Wenn Sie die Anzahl reduzieren, dann wird bei der nächsten Auswahl von **Zeilen anhand von Arbeitszeittabellen vorschlagen** eine Zeile mit der Restmenge der Stunden erstellt.  

5. Wählen Sie die Aktion **Buchen** aus.  
6. Um die Buchung zu überprüfen, wählen Sie die Aktion **Sachposten** aus. Das Fenster **Projekt-Buch.-Blatt** öffnet die Anzeige des Ergebnisses der Buchung des Ressourcen Buch.-Blattes.

## <a name="to-archive-time-sheets"></a>So archivieren Sie Arbeitszeittabellen  
Nachdem Sie Arbeitszeittabellen gebucht haben, können Sie diese für spätere Bezugnahme archivieren. Alle Arbeitszeittabellenzeilen müssen gebucht werden, bevor eine Arbeitszeittabelle archiviert werden kann.

**Hinweis**: Wenn Sie eine Arbeitszeittabelle archivieren, wird sie aus der Liste **Arbeitszeittabelle** und aus der Liste **Arbeitszeittabelle für Manager** entfernt.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Arbeitszeittabellen in Archiv verschieben** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Im Fenster Arbeitstypen füllen Sie die notwendigen Felder aus und schließen das Fenster.  
3. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Archiv Arbeitszeittabelle** oder **Manager Archiv Arbeitszeittabelle**ein. Wählen Sie dann den zugehörigen Link aus.

## <a name="see-also"></a>Siehe auch
[Projekte verwalten](projects-manage-projects.md)  
[Projektmanagement einrichten](projects-setup-projects.md)    
[Finanzen](finance-setup.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)         
[Verkauf verwalten](sales-manage-sales.md)     
[Arbeiten mit Dynamics NAV](ui-work-product.md)  


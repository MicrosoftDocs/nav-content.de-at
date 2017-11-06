---
title: Personalisieren von Seiten im Dynamics Windows Client
description: "Erfahren Sie, wie Sie die Benutzeroberfläche anpassen, damit diese Ihren Bedürfnissen entspricht."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: e22f3464c6a4dd917880ad0b903880fe5f57a37d
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---
# <a name="personalizing-your-workspace-in-the-dynamics-windows-client"></a>Personalisieren Ihres Arbeitsbereichs im Dynamics Windows Client
Sie können Ihren Arbeitsbereich für Ihre Arbeit personalisieren oder anpassen und Präferenzen definieren, indem Sie die Seiten ändern, so dass Sie nur die Informationen angezeigt erhalten, die Sie benötigen. Die Personalisierungsänderungen, die Sie durchführen, beeinflussen nur, was Sie sehen, und nicht, was die Benutzer sehen. –Sie können viele Teile der Benutzeroberfläche personalisieren, einschließlich der auf dem Menüband zu berücksichtigenden Aktionen, der Art und Weise, wie Felder auf den Inforegistern oder in Infoboxen positioniert werden und der im Navigationsbereich zu berücksichtigenden Menüpunkte.

> [!NOTE]  
> Sie können mithilfe von [!INCLUDE[nav_web_md](includes/nav_web_md.md)] auch Seuiten personalisieren. Um zu erfahren, wie die Personalisierung zwischen den beiden Clients funktioniert, gehen Sie zu [Übersicht Personalisieren](ui-personalization-overview.md)..

## <a name="how-to-personalize-your-workspace"></a>Wie Sie den Arbeitsbereich personalisieren
Sie führen die meisten der Anpassungsarbeit aus, indem Sie die Funktion**Anpassen** verwenden, auf die sie von praktischen allen Seiten her zugreifen können, indem Sie Folgendes tun:

1.  Öffnen Sie die Seite, die Sie personalisieren möchten.
2.  Wählen Sie oben links das Menü **Anwendung** ![Anwendungs-Menütaste im Menüband](media/applicationmenuicon.png "ApplicationMenuIcon"), wählen Sie **Anpassen** und dann eine der Anpassungsoptionen.

Es gibt auch einige grundlegende Benutzeroberflächen-Änderungen wie Anpassung der Größe für alle Fensters oder Erweitern der Breite der Spalten, die Sie direkt auf der Seite aus, außerhalb der Option **Anpassen** vornehmen können.

## <a name="general-information"></a>Allgemeine Informationen
Beim Anpassen der Benutzeroberfläche ist es empfehlenswert, an diese Punkte zu denken.

-   Sie können mehrere Anpassungen derselben Seite aufzeichnen, basierend auf verschiedenen Zugriffspunkten für die Seite. Beispielsweise kann das Fenster Verkaufsaufträge angepasst werden, um es anders anzuzeigen, wenn es im Fenster Debitorenkarte geöffnet wird, als wenn es im Verkaufsauftragverarbeitung-Rollencenter geöffnet wird. Der Punkt, von dem Sie auf die anzupassende Seite zugreifen, ist in der Anpassung dieser Seite aufgezeichnet. Entsprechend bestehen möglicherweise mehrere Seitenanpassungsdatensätze in der Datenbank, wie Sie im **Profilkonfiguration löschen**-Fenster sehen.

-   Die Benutzeroberfläche kann so konfiguriert werden, dass Benutzeroberflächenelemente (wie Felder, Inforegister und Infoboxen) auf Grundlage von Lizenz oder Benutzerberechtigungen angezeigt oder ausgeblendet werden. Sie können nur Felder anzuzeigen und konfigurieren, für die Sie die Berechtigung haben.

## <a name="customize-ribbons"></a>Menüband anpassen
Das Menüband bietet Zugriff auf verschiedene Aktionen. Sie können das Menüband anpassen, um Arbeitsprozesse und Einstellungen zu optimieren. Wenn Sie beispielsweise häufig das Fenster **Dimensionen** verwenden, können Sie die **Dimensionen**-Aktion der Aktionsgruppe **Vorgang** hinzufügen. Sie können auch nie benötigte Aktionen für eine bessere Übersicht entfernen.  

Sie haben folgende Möglichkeiten, um Menübänder auf Seiten anzupassen:  

-   Fügen Sie Registerkarten, Gruppen, Aktionen und Menüs hinzu, benennen Sie sie um oder löschen Sie sie.  
-   Ändern Sie die Anordnung der Aktionen.  
-   Stellen Sie die Standardeinstellung des Menübands wieder her.  

### <a name="to-customize-a-ribbon"></a>Um ein Meneüband anzupassen
1. Öffnen Sie die Seite, die Sie personalisieren möchten.
2. Link oben im Menüband im Menü **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Menüband anpassen**.

Das Dialogfeld **Organisieren der Aktionen auf dem Menüband.** wird in zwei Bereiche geteilt. Der Bereich **Verfügbare Aktionen** zeigt alle Aktionen auf, die Sie wählen können, um die Seite hinzuzufügen. Der Bereich **Aktionen in dieser Reihenfolge anzeigen** zeigt die Struktur aller Aktionen an, die derzeit auf der Seite angezeigt werden.

-   Artikel auf der Stammebene Registerkarten festlegen.

    -   Artikel der zweiten Ebene definieren eine Gruppe in einer Registerkarte.

        -   Artikel in der dritten Ebene definieren ein Aktionsmenü in einer Gruppe

### <a name="add-a-group"></a>Gruppe hinzufügen
Wählen Sie die Registerkarte, unter der Sie die Gruppe möchten"" und wählen Sie dann **Gruppe erstellen**. Sie können eine Gruppe nicht unter einem Menü hinzufügen.

### <a name="add-a-menu"></a>Menü hinzufügen
Wählen Sie die Registerkarte, unter der Sie das Menü möchten und wählen Sie dann **Menü erstellen**. Sie können ein Menü einer Gruppe oder einem anderen Menü hinzufügen.

#### <a name="add-an-action"></a>Aktion hinzufügen
Im Bereich **Verfügbare Aktionen** wählen Sie **Hinzufügen**, um ihn dem Bereich **Aktionen in dieser Reihenfolge anzeigen** hinzuzufügen, verwenden Sie die Schaltflächen **Nach oben** und **Nach unten**, um diesen zu setzen, wo Se ihn möchten.

Sie können keine Aktion einer Registerkarte hinzufügen; nur zu einer Gruppe oder einem Menü.

###  <a name="limitations-and-recommendations"></a>Einschränkungen und Empfehlungen
Berücksichtigen Sie die folgenden Einschränkungen, wenn Sie das Menüband anpassen:  

-   Systemregisterkarten oder -gruppen wie **Start** oder - **Neu** können nicht verschoben oder umbenannt werden. Die Position mehrerer Gruppen, wie **Neuer Beleg** ist fixiert.  
-   Aktionen oder Gruppen, die dynamische Sichtbarkeit haben, können nicht hinzugefügt oder entfernt werden.
-   Sie können Menüis nur innerhalb von Gruppen, nicht aber innerhalb von Registerkarten erstellen.  
-   Sie können ein Menü innerhalb eines anderen Menüs schachteln, aber dies wird nicht empfohlen.  
-   Wenn Sie unerwartetes Verhalten bei Gruppen und Aktionen feststellen, nachdem Sie das Menüband angepasst haben, gehen Sie wie folgt vor:  

    1.  Die Gruppe, in der das Problem auftritt, leeren, jedoch nicht löschen.  
    2.  Schließen Sie das Dialogfeld mithilfe der Schaltfläche **OK**.  
    3.  Öffnen Sie das Dialogfeld erneut und fügen Sie die Aktionen der Gruppe erneut hinzu.  

> [!IMPORTANT]  
>  Jede Anpassung, die das Menüband verändert, könnte die Anleitung beeinflussen, die in der [!INCLUDE[navnow_md](includes/navnow_md.md)]-Hilfe bereitgestellt wird, da sich Navigationsschritte in der Hilfe möglicherweise auf ein anderes Menübandlayout beziehen.

## <a name="customize-fasttabs"></a>Inforegister anpassen
Inforegister helfen, Informationen über Seiten in einfachen, überschaubaren Gruppen zu strukturieren. Sie können Inforegister auf Seiten einrichten, sodass diese Ihren Workflow unterstützen. Beispielsweise können Sie weniger Inforegister anzeigen oder bestimmte Felder in Inforegistern ausblenden. Überdies besteht die Möglichkeit, die wichtigsten Felder in die Inforegisterköpfe einzuschließen, wenn die Inforegister reduziert sind.  

### <a name="to-customize-a-fasttab"></a>So passen Sie ein Inforegister individuell an:  

1.  Öffnen Sie die Seite, die Sie personalisieren möchten.
2.  Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Menüband anpassen**.  
3.  Wählen Sie im Dialogfeld **<Page Name>anpassen** die Option **Inforegister** aus.  

### <a name="add-move-or-remove-fasttabs"></a>Inforegister hinzufügen, verschieben oder entfernen
Das Feld **Inforegister in dieser Reihenfolge anzeigen** enthält die Inforegister, die derzeit auf der Seite sind, und die Reihenfolge, in der sie angezeigt werden. Verwenden Sie **Hinzufügen**, **Löschen** und **Nach oben** und **Nach unten** Schaltflächen, um Änderungen vorzunehmen.

### <a name="show-and-hide-fields-on-fasttabs"></a>Felder auf den Inforegistern ausblenden oder anzeigen
Wählen Sie im Feld **Inforegister in dieser Reihenfolge anzeigen** das anzupassende Inforegister aus, und wählen Sie anschließend **Inforegister anpassen**. Verwenden Sie die Schaltflächen, um die Felder anzupassen, die Sie anzeigen möchten und den Auftrag auf der Seite.

Legen Sie **Wichtigkeit** fest, wie folgt:
-   Wenn Sie das Feld im Inforegisterkopf anzeigen möchten, wenn das Inforegister reduziert wird, können Sie dieses auf **Heraufgestuft** festlegen.
- Wenn Sie das Feld ausblenden möchten, es sei denn, der Benutzer wählt die Aktion **Mehr Felder anzeigen** im Inforegister, können Sie dieses auf **Zusätzlich** festlegen.
-   **Standard** ist standardmäßig oder die normale Einstellung.

### <a name="set-up-field-for-quick-entry"></a>Feldeinstellungen für schnelle Eingaben
Wählen Sie das Kontrollkästchen **Schnelleingabe**, um das Feld der Eingabefeldliste schnell hinzuzufügen. Wenn Sie  auf der Seite arbeiten und die Eingabetaste in einem Feld drücken, springt der Bezug zum nächsten Feld, das als Schnelleingabefeld festgelegt ist.

## <a name="customize-factboxes"></a>Anpassen von Infoboxen
Die Infoboxen beinhalten Informationen bezüglich des Datensatzes, der in der Liste oder auf einer Aufgabenseite ausgewählt wurde. In einer Infobox-Liste können die anzuzeigenden Datensätze ausgewählt werden. Infoboxen können so angepasst werden, dass nur die jeweils benötigten Felder angezeigt werden.  

### <a name="to-show-or-hide-the-factbox-pane"></a>Um den Infoboxbereich auszublenden oder anzuzeigen
Infoboxen sind in einem Infoboxbereich enthalten, den Sie auf der Seitenbasis darstellen oder ausblenden können. Dadurch können Sie zu einfach mehrere Infoboxen verbergen, ohne diese individuell entfernen zu müssen.

1.  Öffnen Sie die Seite, die Sie personalisieren möchten.
2.  Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Menüband anpassen**. Ein Häkchen bedeutet, dass die Infobox-Leiste aktiviert wurde.  

### <a name="to-customize-the-factbox-pane"></a>So passen Sie den Infoboxbereich an  
1.  Öffnen Sie die Seite, die Sie personalisieren möchten.
2.  Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Infobereich anpassen**.  

### <a name="add-a-factbox"></a>Fügen Sie eine Infobox hinzu.  

Soll dem Infobox-Bereich eine neue Infobox hinzugefügt werden, wählen Sie die Infobox, die Sie dem Infobox-Bereich **hinzufügen** möchten, im Feld  **Verfügbare Infoboxen** aus.  

### <a name="remove-a-factbox"></a>Entfernen einer Infobox  

Wenn Sie eine Infobox **entfernen** möchten, wählen Sie die Infoboxen im Feld **Infoboxen in dieser Reihenfolge anzeigen** aus.   

### <a name="change-the-order-of-the-factboxes"></a>So ändern Sie die Reihenfolge der Infoboxen:  

Wählen Sie die Infobox, die Sie in das Feld **Infoboxen in dieser Reihenfolge anzeigen** verschieben möchten, und dann die Schaltflächen **Nach oben** oder **Nach unten**, bis die gewünschte Position erreicht ist.  

### <a name="change-the-fields-in-a-factbox"></a>Ändern Sie die Felder in einer Infobox  

1.  Wenn Sie eine Infobox **anpassen** möchten, wählen Sie die Infoboxen im Feld **Infoboxen in dieser Reihenfolge anzeigen** aus.  

2.   Die Box **Verfügbare Felder** zeigt alle Felder, aus denen Sie auswählen können. Das Feld **Angezeigte Felder** zeigt alle Felder an, die derzeit in der Infobox angezeigt werden. Verwenden Sie die Schaltflächen, um die Felder hinzuzufügen, zu löschen und zu verschieben.   


## <a name="customize-columns-in-a-list-or-on-document-lines"></a>In einer Liste oder in Belegzeilen können Sie Spalten folgendermaßen hinzufügen oder entfernen:
Um einen besseren Überblick über die Informationen zu erhalten, die Sie benötigen, können Sie Listenseite und Kartenseiten anpassen, indem Sie Spalten neu anordnen und eine Fixzierung hinzufügen.  

### <a name="to-add-remove-and-arrange-columns"></a>Um Spalten hinzuzufügen, zu entfernen und neu anzuordnen  

1.  Sie können Spalten auf zwei Arten hinzufügen, entfernen oder neu anordnen:

    -   Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Spalten auswählen**.
    -   Klicken Sie mit der rechten Maustaste auf eine Spaltenüberschrift, und klicken Sie anschließend auf **Spalten auswählen**.

2.  Im Dialogfeld **Wählen Sie aus, welche Spalten in der Liste angezeigt werden** unter **Verfügbare Spalten** enthält der Bereich Spalten, die ausgeblendet werden. Das Feld **Spalten in dieser Reihenfolge anzeigen** enthält Spalten, die angezeigt werden. Verwenden Sie die Schaltflächen **Hinzufügen** und **Entfernen**, um Spalten zwischen den beiden Feldern zu verschieben. Die Schaltflächen **Nach oben** und **Nach unten** dienen zum Positionieren der Spalten.

>[!TIP]
>Wählen Sie das Kontrollkästchen **Schnelleingabe**, um das Feld der Eingabefeldliste schnell hinzuzufügen. Wenn Sie  auf der Seite arbeiten und die Eingabetaste in einem Feld drücken, springt der Bezug zum nächsten Feld, das als Schnelleingabefeld festgelegt ist.

### <a name="to-set-the-freeze-pane"></a>Fixierung festlegen
Eine Liste kann mehrere Spalten haben, die Sie dazu zwingen können, horizontal zu scrollen, um alle Spalten anzuzeigen. Es kann eine größere Anzahl von Spalten haben, die Sie immer sehen möchten, selbst wenn Sie blättern. Um dies zu erzielen, können Sie mit einer vertikalen Fixierung mehrere Spalten fixieren. Dies ermöglicht Ihnen, sicherstellen, dass nur weniger wichtige Spalten beim Scrollen verschoben werden.

Um die Fixierung festzulegen, wählen Sie die Spalte aus nach der die Fixierung beginnen soll und dann **Fixierung hinzufügen**.

## <a name="customizing-the-navigation-pane"></a>Anpassen des Navigationsbereichs
Im Navigationsbereich wird ein Menü von Verknüpfungen mit den verschiedenen Listenseiten angezeigt. Verknüpfungen werden unter der Schaltflächen auf der Stammebene gruppiert.

### <a name="to-customize-the-navigation-pane"></a>Anpassen des Navigationsbereichs  

Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Navigationsbereich anpassen**.  

### <a name="rename-or-rearrange-buttons-in-the-navigation-pane"></a>Umbenennen oder Neuanordnen von Schaltflächen im Navigationsbereich  
Klicken Sie im Bereich links im Dialogfeld **Navigationsbereich anpassen** auf die Schaltfläche, die Sie verschieben, umbenennen oder entfernen möchten, und klicken Sie in der Mitte des Fensters auf die entsprechende Schaltfläche.

Sie können die Schaltfläche **Start** nicht verschieben, umbenennen oder entfernen. Die Schaltfläche **Abteilungen** kann über den Navigationsbereich entfernt, jedoch nicht umbenannt oder verschoben werden.

### <a name="add-a-new-menu-button"></a>Eine neue Menüschaltfläche finzufügen
Sie können eine neue Schaltfläche erstellen auf der Stammebene und fügen dann ein Menü von Links  unter der Schaltfläche hinzu, um verschiedenen Seiten zu öffen.

1. Wählen Sie im Dialogfeld **Navigationsbereich anpassen** die Option **Neu**, und geben Sie anschließend im Feld **Name** einen Namen ein.
2.  Wählen Sie die Schaltfläche **OK**.

Nun können dem Menü Links hinzugefügt werden.  

### <a name="add-a-link-to-a-button"></a>So fügen Sie einem Menü einen Link hinzu:   
Sofern Sie die Berechtigung zum Anzeigen einer Liste besitzen (beispielsweise die Verkaufauftragsübersicht), können Sie der Liste einen Link zu einem der Menüs im Navigationsbereich hinzufügen.  

1.  Wählen Sie im Dialogfeld **Navigationsbereich anpassen** im Feld **Schaltflächen des Navigationsbereichs** das Menü aus, dem Sie den Link hinzufügen möchten.  

2.  Wählen Sie die Schaltfläche **Hinzufügen**.  

3.  Navigieren Sie zu dem Sie den Link, den Sie hinzufügen möchten, und klicken Sie anschließend auf **OK**.  
> [!TIP]
> Falls Sie auf den Seiten von **Abteilungen** einen Link finden, kann dieser ebenfalls dem Navigationsbereich hinzugefügt werden. Weitere Informationen finden Sie unter  Hinzufügen eines Links von Abteilungen zum Rollencenter  

### <a name="move-or-copy-a-link-from-one-button-to-another"></a>Um einen Link von einem Menü in ein anderes zu verschieben oder zu kopieren  

1.  Wählen Sie im Dialogfeld **Navigationsbereich anpassen** im Feld **Schaltflächen des Navigationsbereichs** das Menü aus, in dem der Link derzeit angezeigt wird.  

2.  Wählen Sie im Bereich **Listen** den zu verschiebenden Link aus, und wählen Sie anschließend **Verschieben nach** oder **Kopieren nach**.  

3.  Wählen Sie das Menü, dem Sie den Link hinzufügen möchten, und klicken Sie anschließend auf **OK**.  

### <a name="rearrange-the-order-of-a-links-under-a-button"></a>Ordnen Sie den Auftrag von einem Link unter der Schaltfläche neu an  

1.  Wählen Sie im Bereich **Listen** den zu verschiebenden Link aus.  

2.  Ordnen Sie den Link mithilfe der Schaltflächen **Nach oben** und **Nach unten** an.

## <a name="adding-department-links-to-the-role-center"></a>Vorgehensweise: Hinzufügen von Abteilungslinks zum Rollencenter
Gelegentlich befindet sich auf der Seite  **Abteilungen** möglicherweise ein Link, den Sie dem Rollencenter hinzufügen möchten. Wo Sie den Link im Rollencenter platzieren können, hängt von der Kategorie des Links im Rollencenter auf der Seite **Abteilungen** ab.

Die folgende Tabelle enthält eine Beschreibung der Linktypen in jeder Kategorie auf den Seiten des Menüs **Abteilungen** und Angaben zu den Hinzufügemöglichkeiten für Links in Rollencentern.  

|**Kategorie**|**Inhalt**|**Link hinzufügen zu**|  
|------------------|------------------|---------------------|  
|Listen|Listenseiten|**Startseiten**-Schaltflächen des Navigationsbereichs:|  
|Aufgaben|Aufgabenseiten, Stapelverarbeitungen, Vorschläge, Buch.-Blätter|Registerkarte **Aktion** im Menüband.|  
|Berichte und Analysen|Berichte, Stapelverarbeitungen, Matrixfenster|Registerkarte **Berichte** im Menüband.|  
|Belege|Dokumente wie Rechnungen und Mahnungen|Registerkarte in Menüband **Berichte**|  
|Archiv/Historie|Gebuchte/fertig gestellte Dokumente, Journale|**Startseiten**-Schaltflächen des Navigationsbereichs:|  
|Verwaltung|Einrichtungsfenster|Registerkarte **Aktion** im Menüband.|  

### <a name="to-copy-department-links-to-your-role-center"></a>So kopieren Sie Abteilungslinks in das Rollencenter:  

1.  Öffnen der Seite **Abteilungen**.  

2.  Klicken Sie mit der rechten Maustaste auf den Link, und klicken Sie auf eine der folgenden Optionen (nur eine dieser Optionen ist verfügbar):  

    |**Markieren**|**Um den Link hinzuzufügen**|  
    |----------------|----------------------------|  
    |**Zu Navigationsbereich hinzufügen**|Die Schaltfläche **Startseite** im Navigationsbereich auf Ihrem Rollencenter.|  
    |**Zu Aktionen auf dem Rollencenter-Menüband hinzufügen**|Das Menü **Aktion** auf dem Menüband im Rollencenter.|  
    |**Zu Berichten auf dem Rollencenter-Menüband hinzufügen**|Das Menü **Berichte** auf dem Menüband im Rollencenter.|  

3.  Bestätigen Sie die angezeigte Meldung.  

 Der neue Link wird nun in dem Menü angezeigt, dem er Link hinzugefügt wurde. Allerdings möchten Sie den Link möglicherweise an eine andere Position im Menü verschieben. Falls Sie dem Navigationsbereich beispielsweise einen Link hinzugefügt haben, wird dieser im Menü **Start** hinzugefügt. Sie können den Link jedoch in ein anderes Menü im Navigationsbereich verschieben. Weitere Informationen finden Sie unter Gewusst wie: Navigationsbereich anpassen.

## <a name="adding-charts-to-role-centers-and-list-pages"></a>Hinzufügen von Diagrammen zu Rollencentern und Listenseiten
Wenn Sie komplexe Informationen haben, möchten Sie vielleicht eine visuelle Darstellung der Daten anzeigen, die Ihnen hilft, Trends zu sehen und Entscheidungen zu treffen. Möglicherweise möchten Sie die Salden pro Bankkonto für Ihren Mandanten in einer Tabelle überwachen. Sie verwenden den Diagrammbereich, um Daten aus einer Liste auf den folgenden Arten von Seiten anzuzeigen:  

-   In Ihrem Rollencenter, wo Sie aus vordefinierten generischen Diagrammen auswählen können.  

-   Auf einer Listenseite, auf der Sie auswählen können, eine Liste als Diagramm anzuzeigen.  

### <a name="to-add-a-generic-chart-to-your-role-center"></a>So fügen Sie Ihrem Rollencenter ein allgemeines Diagramm hinzu:  

1.  Wählen Sie **Anwendung** ![Anwendungs-Menütaste im Menüband] (media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Menüband anpassen**.  

2.  Wählen Sie im Fenster **Rollencenter anpassen** im Feld **Verfügbare Elemente** die Option **Diagrammelement** aus, und wählen Sie anschließend **Hinzufügen**.  

3.  Positionieren Sie das Diagrammelement mithilfe der Schaltflächen **Nach oben**, **Nach unten**, **Nach links** und **Nach rechts** auf Ihrem Rollencenter.  

4.  Wählen Sie das Diagrammelement aus, wählen Sie **Teil anpassen**.  

5.  Wählen Sie im Fenster **Diagramm anpassen** das vordefinierte Diagramm aus, das Sie anzeigen möchten, und klicken Sie anschließend auf **OK**.  

### <a name="to-view-a-list-as-a-chart"></a>So zeigen Sie eine Liste als Diagramm an:  

1.  Wählen Sie auf der Listenseite **Als Diagramm anzeigen**.  

2.  Wählen Sie ein Maß und eine Dimension, um ein individuell angepasstes Diagram zu erstellen. Um weitere Informationen anzuzeigen, wählen Sie eine sekundäre Dimension aus. Einfache Balkendiagramme werden z. B. durch Auswählen einer Dimension für die x-Achse und der Dimension **Dimensionsanzahl** für die y-Achse erstellt.  

> [!NOTE]  
>  Der Diagrammbereich wird standardmäßig ausgeblendet, da sich ansonsten möglicherweise die Anwendungsleistung verringert. Sie sollten das Diagramm nur anzeigen, wenn Sie die Informationen benötigen.  

## <a name="handling-external-files-and-automation-objects"></a>Auflösen von externen Dateien und von Automatisierungsobjekten
Wenn [!INCLUDE[navnow_md](includes/navnow_md.md)] eine externe Datei erhält, wird Ihnen ein Dialogfeld angezeigt. Zusätzlich zur Auswahl der Verfahrensweise mit der Datei können Sie entscheiden, wie Sie mit dem Dateityp verfahren möchten, wenn Sie sie das nächste Mal erhalten.  

Wenn [!INCLUDE[navnow_md](includes/navnow_md.md)] ein Automatisierungsobjekt ausführen soll, wird Ihnen ein Dialogfeld angezeigt. Sie können entscheiden, ob diese Art des Objekts immer oder nie in der Lage sein soll, ausgeführt zu werden.  

### <a name="to-specify-how-to-handle-external-files"></a>Angeben, wie externe Dateien bearbeitet werden  

1.  Wenn mit dem Dialogfeld dargestellt werden, löschen Sie das Kontrollkästchen **Immer fragen, wenn Sie eine solche Datei öffnen**, wenn Sie möchten, dass [!INCLUDE[navnow_md](includes/navnow_md.md)] sich diese Option merkt. Das nächste Mal, wenn diese Art Datei kommt, wird das Dialogfeld nicht angezeigt, und die Datei wird wie in Schritt 2 beschrieben behandelt.  

     Oder wählen Sie das Kontrollkästchen **Vor dem Öffnen dieses Dateityps immer bestätigen**, das immer angezeigt wird, wenn Dateien dieses Typs eingehen.  

2.  Wählen Sie **Öffnen**, **Speichern** oder **Abbrechen**. Die Datei wird entsprechend Ihrer Wahl verarbeitet.  

### <a name="to-specify-how-to-handle-automation-objects"></a>Angeben, wie Automatisierungsobjekte bearbeitet werden  

Wenn ein Dialogfeld erscheint, wählen Sie das Kontrollkästchen ,**Immer zulassen**, wenn Sie möchten, dass [!INCLUDE[navnow_md](includes/navnow_md.md)] diese Art von Automatisierungsobjekt immer ausführen soll. Wenn diese Art von Automatisierungsobjekt das nächste Mal ausgeführt werden muss, erscheint das Dialogfeld nicht, und das Automatisierungsobjekt wird direkt ausgeführt.  

Oder wählen Sie das Kontrollkästchen **Niemals erlauben**. Wenn diese Art von Automatisierungsobjekt das nächste Mal ausgeführt werden muss, erscheint das Dialogfeld nicht, und das Automatisierungsobjekt wird nicht ausgeführt.  

## <a name="CancelPersonalization"></a> Abbrechen der Personalisierung
Die Stornierung der Personalisierung kann in zwei Kategorien unterteilt werden:

-   Änderungen stornieren, die Sie durchgeführt haben, indem Sie die Funktion **Anpassen** verwendet haben.
-   Abbrechen von grundlegenden Benutzeroberflächen-Änderungen.

### <a name="cancel-customization"></a>Anpassung stornieren
Wenn Sie alle UI-Anpassungen rückgängig machen möchten, die Sie jemals für eine Seite unter Ihrer aktuellen Benutzeranmeldung durchgeführt haben, oder die Sie seit Ihrer letzten stornierten UI-Anpassung vorgenommen haben, können Sie das Fenster **Benutzerpersonalisierung löschen** verwenden. Das Layout der Seite, für die Sie Ihre Personalisierung löschen, wird dann auf die Standardkonfiguration für Ihr Profil zurückgesetzt.  

Wenn Sie nur die UI-Anpassungen stornieren möchten, die Sie einem bestimmten UI-Bereich auf einer Seite, wie etwa dem Menüband, durchgeführt haben, können Sie die Schaltfläche **Standardeinstellungen wiederherstellen** im Fenster **Anpassen** verwenden. Das Layout des spezifischen UI-Bereichs auf dieser Seite wird dann auf die Standardkonfiguration für Ihr Profil zurückgesetzt.  

#### <a name="to-cancel-all-ui-customization-that-you-have-made-to-a-page"></a>Alle Benutzeroberflächenanpassung, die Sie für eine Seite vorgenommen haben, stornieren  

1.  Geben Sie im Feld **Suchen** die Option **Benutzeranpassung löschen** ein, und wählen Sie dann den zugehörigen Link aus.  

2.  Wählen Sie die Seite aus, für die Sie Ihre UI-Anpassung stornieren möchten, und dann, auf der Registerkarte **Start**, in der Gruppe **Ansicht**, **Löschen**.  

> [!NOTE]  
>  Alle UI-Anpassungen der Seite, die Sie jemals unter Ihrer aktuellen Benutzeranmeldung durchgeführt haben, oder seit Sie zuletzt die Schaltfläche **Benutzeranpassung löschen** betätigt haben, werden storniert. Das Layout der Seite wird auf die Standardkonfiguration für Ihr Profil zurückgesetzt, wie vom Administrator konfiguriert oder wie mit [!INCLUDE[navnow](includes/navnow_md.md)] eingerichtet.  

#### <a name="to-cancel-ui-customization-that-you-have-made-to-a-ui-area-on-a-page"></a>Benutzeroberflächenanpassungen, die Sie für einen Benutzeroberflächenbereich auf einer Seite vorgenommen haben, stornieren  

1.  Von der Seite, in der Sie einen Benutzeroberfläche-Bereich, wie beispielsweise das Menüband angepasst haben, wählen Sie im Menü **Anwendung** S![chaltfläche Anwendung in der Menüleiste](media/applicationmenuicon.png "ApplicationMenuIcon")und **Anpassen** und dann **<UI area>anpassen**.  

2.  Wählen Sie am unteren Rand des Fensters **Anpassen** die Schaltfläche **Standardeinstellungen wiederherstellen**.  

> [!NOTE]  
>  Alle Anpassungen des UI-Bereichs, die Sie jemals für die Seite unter Ihrer aktuellen Benutzeranmeldung durchgeführt haben, oder seit Sie zuletzt die Schaltfläche **Standardeinstellungen wiederherstellen** betätigt haben, werden storniert. Das Layout des Benutzeroberflächenbereichs der Seite wird auf die Standardkonfiguration für Ihr Profil zurückgesetzt, wie vom Administrator konfiguriert oder wie mit [!INCLUDE[navnow](includes/navnow_md.md)] eingerichtet.

### <a name="cancel-basic-ui-changes"></a>Abbrechen von grundlegenden Benutzeroberflächen-Änderungen.
Sie können Ihre grundlegenden UI-Änderungen stornieren, indem Sie das Fenster **Von Benutzern angegebene Einstellungen zurücksetzen** von Ihrem Rollencenter aus öffnen.  

Grundlegende Benutzeroberflächen-Änderungen enthalten Elemente wie:
 -  Ändern der Größe und Position irgendeines Fensters.
 -  Ändern der Breite einer Spalte
 -  Die Höhe von Spaltenüberschriften ändern.
 -  Sortierung in Spalten aus einer Liste.
 -  Listen als Diagramm anzeigen.
 -  Angeben, wie externe Dateien und Automatisierungsobjekte behandelt werden.  

#### <a name="to-cancel-basic-ui-changes"></a>Abbrechen von grundlegenden Benutzeroberflächen-Änderungen.

1.  Ansteuern des Rollencenters.  

     Wählen Sie im Fenster **Anwednung** im Menü ![Anwendungs-Menütaste](media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Benutzerdefinierte Einstellungen wieder herstellen**.  

2.  Wählen Sie die Schaltfläche **Benutzeroberflächeneinstellungen zurücksetzen**. Wählen Sie alternativ die Schaltfläche **Alle zurücksetzen**, um auch Ihre Entscheidungen zur Verarbeitung von Dateien und Automatisierungsobjekten zu stornieren.  

 Alle grundlegenden Benutzeroberfläche-Änderungen, die Sie unter Ihrer aktuellen Benutzeranmeldung an [!INCLUDE[navnow_md](includes/navnow_md.md)] vorgenommen haben, seitdem Sie zuletzt die Schaltfläche **Benutzeroberflächeneinstellungen zurücksetzen** betätigt haben, werden storniert. Die Benutzeroberfläche wird auf die Standardkonfiguration für Ihr Profil zurückgesetzt.  

#### <a name="to-cancel-your-decision-for-running-or-saving-external-files"></a>Ihre Entscheidung für die Ausführung oder Speicherung von externen Dateien stornieren  

1.  Ansteuern des Rollencenters.  

     Wählen Sie im Fenster **Anwednung** im Menü ![Anwendungs-Menütaste](media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Benutzerdefinierte Einstellungen wieder herstellen**.  

2.  Wählen Sie die Schaltfläche **Einstellung für Dateibehandlung zurücksetzen**. Wählen Sie alternativ die Schaltfläche **Alle zurücksetzen**, um auch Ihre Änderungen von Ansichten und Ihre Entscheidungen zur Verarbeitung von Dateien und Automatisierungsobjekten zu stornieren.  

 Alle Entscheidungen für die Standardverarbeitung von Dateitypen, die Sie unter Ihrer aktuellen Benutzeranmeldung vorgenommen haben oder seitdem Sie zuletzt die Schaltfläche **Zugriff auf Clientdatei** betätigt haben, werden storniert und auf die Standardkonfiguration für Ihr das Profil zurückgesetzt. Wenn das nächste Mal [!INCLUDE[navnow_md](includes/navnow_md.md)] eine externe Datei beliebiger Art erhält, wird Ihnen ein Dialogfeld mit den Optionen **Speichern**, **Ausführen** und **Abbrechen** angezeigt.  

### <a name="to-cancel-your-decision-for-handling-automation-objects"></a>Ihre Entscheidung zur Verarbeitung von Automatisierungsobjekten stornieren  

1.  Ansteuern des Rollencenters.  

     Wählen Sie im Fenster **Anwednung** im Menü ![Anwendungs-Menütaste](media/applicationmenuicon.png "ApplicationMenuIcon") wählen Sie **Anpassen** und dann **Benutzerdefinierte Einstellungen wieder herstellen**.  

2.  Wählen Sie die Schaltfläche **Automatisierungseinstellungen zurücksetzen**. Wählen Sie alternativ die Schaltfläche **Alle zurücksetzen**, um auch Ihre Änderungen von Ansichten und Ihre Entscheidungen zur Ausführung und zum Speichern externer Dateien zu stornieren.  

 Alle Entscheidungen zur Ausführung automatischer Objekte, die Sie unter Ihrer aktuellen Benutzeranmeldung getroffen haben, seitdem Sie zuletzt die Schaltfläche **Automatische Entscheidungen zurücksetzen** betätigt haben, werden storniert. Das Dateibehandlungsverhalten wird auf die Standardkonfiguration für Ihr Profil zurückgesetzt. Wenn [!INCLUDE[navnow_md](includes/navnow_md.md)] beim nächsten Mal ein Automatisierungsobjekt beliebiger Art ausführen muss, wird Ihnen ein Dialogfeld mit den Optionen, **Immer zulassen** und **Niemals zulassen** angezeigt.    

<!--Use the following table to get more information about customizing the different elements of the UI.

| To | See |
| --- | --- |
| Change which actions to show on the ribbon and how the actions are grouped. |[How to: Customize FastTabs](purchasing-how-record-purchases.md) |
|Change which FastTabs to show and which fields to include on the FastTabs.|[How to: Request Quotes](purchasing-how-request-quotes.md)|
|Add, remove, or arrange columns in a list or document-lines that represent fields in the underlying tables. |[ How to: Add or Remove Columns in a List or on Document Lines](purchasing-how-purchase-products-sale.md) |
| Rename or rearrange buttons, create a new menu button, add a link to a menu, or rearrange the order of a menu. |[ How to: Customize the Navigation Pane](purchasing-how-correct-cancel-unpaid-purchase-invoices.md) |
| Add a link from a department page to your Role Center. |[How to: Process Purchase Returns or Cancellations](purchasing-how-register-new-vendors.md) |
|Add a chart to your Role Center or to a list page.|[How to: Combine Receipts on a Single Invoice](purchasing-how-to-combine-receipts.md)|
| Unod personalization that you have made to your user interface, either for a specific area on a page, such as a ribbon, or for the whole page.|[How to: Cancel Personalization](ui-customization-cancel.md)|
-->


## <a name="see-also"></a>Siehe auch
[Personalisieren Ihres Arbeitsbereichs im Dynamics Web-Client](ui-personalization-user.md)  
[Anpassungs-Übersicht](ui-personalization-overview.md)  


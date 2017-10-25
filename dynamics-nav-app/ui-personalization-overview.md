---
title: "Den Arbeitsbereich personalisieren - Überblick"
description: "Erfahren Sie, wie Sie die Benutzeroberfläche anpassen, damit diese Ihren Bedürfnissen entspricht."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 04334d3bb50b37b9643b848ca4f59b015f03ad04
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="personalizing-your-workspace---overview"></a>Den Arbeitsbereich personalisieren - Überblick
Sie können Ihren Arbeitsbereich für Ihre Arbeit *personalisieren* oder anpassen und Präferenzen definieren, indem Sie die Seiten ändern, so dass Sie nur die Informationen angezeigt erhalten, die Sie benötigen. Die Personalisierungsänderungen, die Sie durchführen, beeinflussen nur, was Sie sehen, und nicht, was die Benutzer sehen.

Personalisieren des Arbeitsbereichs mithilfe von [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] und [!INCLUDE[nav_web_md](includes/nav_web_md.md)]. Die personlization Änderungen, die Sie durchführen, werden ebenfalls in [!INCLUDE[nav_phone_md](includes/nav_phone_md.md)] und [!INCLUDE[nav_web_md](includes/nav_phone_md.md)]angezeigt .
  
> [!NOTE]  
> Der Administrator in Ihrem Unternehmen hat möglicherweise bereits Ihre Benutzeroberfläche zu einem rollenspezifischen Layout für alle Benutzer angepasst, die das gleiche Profil wie Sie haben und dasselbe Rollencenter verwenden. Anpassungen, die Sie Ihrem Arbeitsbereich machen, werden unter dem Benutzerkonto gespeichert, und  werden beibehalten, auch wenn ein Administrator eine neue Zusammenstellung rollenspezifischer Layouts in Ihrem Unternehmens bereitstellt. Weitere Informationen finden Sie unter [Konfigurieren der Benutzeroberfläche](admin-configure-user-interface.md).

## <a name="comparing-personalization-in-the-dynamics-nav-windows-and-web-clients"></a>Vergleichen der Personalisierung in Dynamics NAV Windows und in den Webclienten
Abhängig von der Seite, können Sie viele Teile der Benutzeroberfläche, wie Felder oder Spalten anpassen und definieren, wo sie platziert werden, Aktionen die eingeschlossen sind auf dem Menüband und mehr. Viele dieser Elemente können Sie im Windows-Client und Webclienten tun. Die folgende Tabelle enthält einen Überblick über die Anpassungsfunktionen in jedem Client.

|  Personalisieren  ||  Windows-Client  |  Webclient  |
|---------------|-|------------------|--------------|
|Felder in den Inforegistern||||
||Hinzufügen, veschieben, entfernen |X|X|
||Im reduzierten Kopf anzeigen|X||
||Unter**Mehr Felder anzeigen** Aktion verbergen|X||
|Listen oder Belegzeilen ||||
||Hinzufügen, veschieben, entfernen von Spalten  |X|X|
||Fixierung entfernen, verschieben, hinzufügen  |X|X|
|Infoboxen|||
||Hinzufügen, entfernen|X|X|
||Hinzufügen|X||
||Felder hinzufügen, bewegen und entfernen.|X|X|
|Stapel||||
||Hinzufügen, entfernen|X|X|
||Hinzufügen |X||
|Diagramme||||
||Hinzufügen, entfernen|X|X|
||Hinzufügen|X| |
|Menüband und Aktionen||X||
|Navigationsbereich||X||

Eine andere Differenz ist, dass beim Personalisieren, indem Sie den Windows-Client, Sie können verschiedene Versionen personalisierte derselben Seite haben, verwenden auf verschiedenen Zugangspunkte die Seite. Beispielsweise kann das Fenster **Verkaufsaufträge** angepasst werden, um es anders anzuzeigen, wenn es im Fenster **Debitorenkarte** geöffnet wird, als wenn es im **Verkaufsauftragverarbeitung**-Rollencenter geöffnet wird. Wenn Sie eine Seite anpassen, indem Sie den Webclienten wählen, gibt es nur eine personalisierte Version pro Seite, sodass die Änderungen der Seite angezeigt werden, egal von wo Sie sie öffnen.

##  <a name="PersonalizationWinWeb"></a>Arbeiten mit Anpassungen zwischen Dynamics NAV Windows und Webclient
Bevor Sie das Personalisieren vonseiten beginnen, ist es wichtig zu verstehen, wie die Anpassung zwischen dem Fensterclient und den Webclient arbeiten. Wenn Sie nur eine Zeile entweder den Windows-Client oder den Webclienten verwenden, wurden diese Informationen relevant sein. Jedoch ist es wichtig, wenn Sie beginnen, die Seiten mithilfe beider Clients zu personalisieren oder wenn Sie den Webclient anstelle dem Windows Cleint verwenden möchten.  

-   Wenn Sie den Windows-Client verwenden, um eine bestimmte Seite von Anfang an zu personalisieren, siehe auch die Anpassungsänderungen der Seite unter in [!INCLUDE[nav_web_md](includes/nav_web_md.md)].

-   Solange Sie fortfahren, den Windows-Client zu verwenden, um die Seite zu personalisieren, werden jegliche Personalisierungsänderungen beschrieben, die Sie durchführen, auch für die Seite im Webclient.

-   Jedoch sobald Sie starten, um die Seite zu personalisieren, indem Sie den Webclienten verwenden, wird die Personalisierung für diese Seite zwischen den beiden Clients einzelne, und Sie haben eine Version personalisierte für jeden Client. Im Webclienten werden die vorherigen Anpassungen auf der Seite gelöscht, d. h., dass die Seite in das ursprüngliche Layout zurückkehrt. Sie beginnen erneut, um die Seiten zu personalisieren. Die vorherigen Anpassungen im Windows-Client sind unverändert.

- Ab hier personalisieren Sie die Seiten im Windows und Webclient unabhängig voneinander,  dies bedeutet, jeder Client kann unterschiedlich aussehen. Die Telefon und Tabletclients zeigen die gleiche Seitenpersonalisierungen wie der Webclient an.  

> [!Tip]  
>Wenn Sie die Seite **Benutzeranpassung löschen** öffnen, können Sie alle Seiten sehen, die von jedem Benutzer angepasst wurden. Die Spalte **Vorgänger-Anpassung** zeigt Ihnen, ob die Personalisierung im Windows-Client oder -Webclienten vorgenommen wurde. Wenn sich ein Häkchen bei derr Spalte befindet, wurde die Personalisierung im Windows-Client vorgenommen (oder im Webclient [!INCLUDE[navnow_md](includes/navnow_md.md)]).

## <a name="see-also"></a>Siehe auch
[Personalisieren Ihres Arbeitsbereichs im Dynamics NAV](ui-personalization-windows-client.md)  
[Personalisieren Ihres Arbeitsbereichs im Dynamics NAV Webclient](ui-personalization-user.md)  
[Verwalten der Personalisierung](ui-personalization-manage.md)  
[Anpassen von Dynamics NAV](ui-customizing-overview.md)  


---
title: Profile und Rollencenter verwalten
description: Erfahren Sie, wie Sie Benutzer und Rollencenter in Dynamics NAV verwalten.
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: profiles, roles, role centers, user roles
ms.date: 09/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: a657c409c9cd361a505f1fd61dbb5254b25c5144
ms.contentlocale: de-at
ms.lasthandoff: 10/26/2017

---
# <a name="managing-profiles-and-role-centers"></a>Profile und Rollencenter verwalten
Profile sind Sammlungen von [!INCLUDE[navnow_md](includes/navnow_md.md)]-Benutzern, die dasselbe Rollencenter nutzen. Ein Rollencenter ist eine Art Seite, auf die Sie verschiedene Teile setzen können. Jeder Teil ist ein Container, in dem Sie andere Seiten oder vordefinierte Systemteilen hosten können, wie etwa ein Outlook-Teil oder Teile für das Hinzufügen von Aufgaben, von Benachrichtigungen oder von Notizen.  

## <a name="about-profiles-and-role-centers"></a>Über Profile und Rollencenter
Profile werden verwendet, um Benutzer mit vordefinierten Rollencentern zu verknüpfen. Ein Rollencenter ist eine Homepage für alle Benutzer eines Profils, das konfiguriert wurde, damit es Aufgaben und Prioritäten von Benutzern des Profils widerspiegelt. Beispielsweise wird das Auftragsverarbeitungs-Rollencenter so konfiguriert, dass Aufgaben und Prioritäten einer Auftragsabwicklung wiedergegeben werden. Ein Rollencenter bietet einen einfachen Zugriff auf Informationen, die Benutzer zur Ausführung ihrer täglichen Arbeit benötigen. Beispielsweise bestimmt das Rollencenter die Stapel oder Kachel, die anzeigen, wenn Benutzer sich zuerst anmelden sowie die Links von der Navigationsseite.

Das verwendete Profil wird im Kopf des Hauptinhaltsbereichs des Rollencenters angezeigt. Ein Administrator kann dieses Rollencenter anpassen, um die Anforderungen einer bestimmten Rolle in einem bestimmten Unternehmen zu erfüllen. Das Auftragsverarbeitungs-Rollencenter kann weiter an einen einzelnen Computer angepasst werden, um die Anforderungen einer Person zu erfüllen, die die Auftragsabwicklung durchführt. Diese Person kann das Rollencenter anpassen, indem sie Abfragen speichert, Filter hinzufügt und Felder hinzufügt oder entfernt.

Profile und Rollencenter richten sich an den Rollen und Zuständigkeiten innerhalb Ihrer Organisation aus. [!INCLUDE[navnow_md](includes/navnow_md.md)] enthält einen Satz von Standardprofilen, die jeweils einem Rollencenter entsprechen und mit diesem verknüpft sind. Administratoren können vorhandene Profile ändern oder neue Profile erstellen.  

> [!NOTE]  
>  Profile sind nicht explizit mit den Rollen und Berechtigungen des Sicherheitssystems verknüpft, einem Profil zugewiesene Benutzer benötigen jedoch Berechtigungen, die ihren Rollen im Sicherheitssystem entsprechen. Weitere Informationen finden Sie unter [Sicherheit in den rollenbasierten Umgebungen in der Dokumentation der MSDN-Bibliothek](http://go.microsoft.com/fwlink?LinkId=147633).

## <a name="to-create-a-profile"></a>So erstellen Sie ein Profil:
1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”") aus, geben Sie **Profile** ein, und wählen Sie dann den zugehörigen Link aus.  

2.  Wählen Sie die Aktion **Neu** aus, um das Fenster **Neue Profilkarte** zu öffnen.  

3.  Geben Sie im Feld **Profil-ID** einen Namen ein, der die gewünschte Rolle des Benutzers beschreibt.  

4.  Geben Sie im Feld **Beschreibung** eine Beschreibung der Profil-ID, beispielsweise **Auftragsverarbeitung** ein.  

5.  Legen Sie das Feld **Rollencenter-ID** auf das Rollencenter fest, das Sie dem Profil zuweisen wollen.  

6.  Um dieses Rollencenter als Standard für das Profil festzulegen, aktivieren Sie das Kontrollkästchen **Standardrollencenter**.  

7.  Wählen Sie die Schaltfläche **OK**. .  

Das Verfahren zum Ändern eines vorhandenen Profils ist dasselbe, außer dass Sie ein vorhandenes Profil in der Profilseite auswählen, anstatt auf **Neu** zu klicken.  


##<a name="copying-a-profile"></a>Ein Profil kopieren
Durch Kopieren eines Profils sparen Sie Zeit, wenn Sie ähnlichen Einstellungen in einem Profil verwenden möchten und nur einige wenige Einstellungen ändern möchten.

1.  Öffnen Sie das Profil, das Sie kopieren möchten, und wählen Sie dann die Aktion **Profil kopieren** aus.

2.  Geben Sie im Feld **Neue Profil-ID** einen Namen für das zu kopierende Profil ein.

3.  Legen Sie das Feld **Neuer Profilbereich** auf eines der Folgenden fest:

    - **System**, damit das neue Profil für alle Tenantdatenbanken verfügbar ist, die die Anwendung verwenden.
    - **Tenant**, damit das neue Profil nur der aktuellen Tenantdatenbank zur Verfügung steht.
4. Wenn Sie fertig sind, wählen Sie die Schaltfläche **OK** aus.

## <a name="ExportImportProfile"></a>Exportieren und Importieren von Profilen

Sie können Profile als XML-Dateien aus und nach einer [!INCLUDE[d365fin](includes/d365fin_md.md)]-Datenbank exportieren, bzw. importieren. Durch das Exportieren und das Importieren eines Profils können Sie Zeit speichern, wenn Sie die Benutzeroberfläche konfigurieren, da Sie eine vorhandene Profilkonfiguration wieder verwenden, statt ein Profil von Grund auf neu konfigurieren zu müssen. Wenn Sie ein Profil haben, das in einer [!INCLUDE[d365fin](includes/d365fin_md.md)]-Datenbank konfiguriert ist und Sie alle oder einige derselben Profilkonfigurationen in einer anderen Datenbank erneut verwenden möchten, können Sie das Profil in eine XML-Datei exportieren. Anschließend können Sie die XML-Profildatei in die andere Datenbank importieren.

-   Um ein Profil zu exportieren, öffnen Sie die Suche für und öffnen Sie die Seite **Profile exportieren**, wählen Sie das Profil aus der Liste aus, und wählen Sie dann die Aktion **Exportieren** aus. Speichern Sie die XML-Datei an einem Speicherort auf Ihrem Computer oder Netzwerk.

-   Um ein Profil zu importieren, öffnen Sie die Suche für und öffnen Sie die Seite **Profile importieren**, wählen Sie die XML-Profildatei aus, und wählen Sie dann die Schaltfläche **OK** aus.

    > [!NOTE]  
    >  Sie können kein Profil importieren, das bereits in der Datenbank vorhanden ist, auch wenn die XML-Datei einen anderen Namen oder unterschiedlichen Inhalt hat. Sie müssen das vorhandene Profil löschen, bevor Sie das neue Profil importieren können.



## <a name="see-also"></a>Siehe auch  
[Vorgehensweise: Verwalten Sie Benutzer und Berechtigungen](ui-how-users-permissions.md)  
[Anpassen der Benutzeroberfläche](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->


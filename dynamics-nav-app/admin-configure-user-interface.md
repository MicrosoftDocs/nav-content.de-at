---
title: "Konfigurieren der Benutzeroberfläche (UI) für Benutzer"
description: "Als Administrator konfigurieren Sie die Standardbenutzeroberflächen Ihres Unternehmens, indem Sie Seitenlayouts für verschiedene Benutzerprofile im Unternehmen anpassen."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize pages, configure user interface, customize UI
ms.date: 07/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7ba3d45a856eb38fe99fc5012b4e2f2d8609f9ce
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="configuring-the-user-interface-ui-for-users"></a>Konfigurieren der Benutzeroberfläche (UI) für Benutzer
Als Administrator konfigurieren Sie die Standardbenutzeroberflächen Ihres Unternehmens, indem Sie Seitenlayouts für verschiedene Benutzerprofile im Unternehmen anpassen. Um diese Arbeit auszuführen, müssen Sie ein Administrator mit dem SUPER-Zugriffsrechtsatz sein. Darüber hinaus müssen Profile eingerichtet und die entsprechenden Benutzer ihnen zugeordnet werden. Weitere Informationen finden Sie unter [Verwaltung von Benutzern, von Profilen und von Rollencentern](admin-users-profiles-roles.md).  
  
Sie konfigurieren die Benutzeroberfläche für mehrere Benutzer, indem Sie Seiten für ein bestimmtes Profil anpassen, dem die Benutzer zugewiesen sind. Sie tun dies, indem Sie die [!INCLUDE[nav_windows](includes/nav_windows_md.md)] verwenden, und indem Sie Anpassungen in gleicher Weise vornehmen, wie individuelle Benutzer ihre eigenen Arbeitsbereiche personalisieren, das heißt, indem Sie die Funktion **Anpassen** verwenden. Die Unterschied besteht darin, dass Sie die [!INCLUDE[nav_windows](includes/nav_windows_md.md)] im Konfigurationsmodus öffnen. Häufige Anpassungen sind, welche Aktionen auf dem Menüband zu berücksichtigen sind, die Art und Weise, wie Felder auf den Inforegistern oder in Infoboxen positioniert werden und die im Navigationsbereich zu berücksichtigenden Menüpunkte. 

> [!TIP]  
>  Eine schnellen Art, Benutzeroberflächenkonfigurationen für ein Profil zu implementieren ist, wenn Sie bereits ein konfiguriertes Profil in einer anderen [!INCLUDE[d365fin](includes/d365fin_md.md)]-Datenbank haben. Sie können dieses Profil dann exportieren und anschließend in die aktuelle Datenbank importieren. Weitere Informationen finden Sie unter [Profile exportieren und importieren](admin-profiles.md#ExportImportProfile).  
  
## <a name="general-information"></a>Allgemeine Informationen
Beachten Sie die folgenden Informationen, bevor Sie beginnen, die Benutzeroberfläche zu konfigurieren:
-   Bevor Sie beginnen, die Benutzeroberfläche zu Konfigurieren, kann die Anwendung so konfiguriert werden, dass Benutzeroberflächenelemente (wie Felder, Inforegister und Infoboxen) auf Grundlage von Lizenz oder Benutzerberechtigungen angezeigt oder ausgeblendet werden. Weitere Informationen, wie dies getan wird, finden Sie unter [Entfernen von Elementen in der Benutzeroberfläche entsprechend den Berechtigungen](https://msdn.microsoft.com/en-us/dynamics-nav/removing-elements-from-the-user-interface-according-to-permissions)

    Um den Effekt der Option zum Entfernen von Benutzeroberflächenelementen zu sehen, können Sie sich als Testbenutzer mit dem Berechtigungssatz des Profils, dass Sie gerade konfigurieren, anmelden. Der Grund ist, dass Sie als Administrator den SUPER-Berechtigungssatz haben und daher während Ihrer eigenen Anmeldung die resultierende Benutzeroberfläche nicht sehen und testen können.    
-   Ebenso wird die Personalisierung der Benutzeroberfläche gespeichert und nicht durch die neue Seitenkonfiguration überschrieben, wenn Sie Änderungen an der Konfiguration der durch einen Benutzer personalisierten Benutzeroberfläche vornehmen. Ebenso wird eine Personalisierung des Benutzeroberfläche nicht storniert, wenn Sie Ihre Benutzeroberflächen-Konfiguration einer Seite stornieren, die ein Benutzer seitdem personalisiert hat.
-   Die einzige Situation, in der die UI-Konfiguration UI-Personalisierungen überschreibt, ist die, in der ein UI-Element durch die Konfiguration entfernt wird. Wenn beispielsweise der Administrator ein Feld entfernt, das der Benutzer umbenannt oder verschoben hat, wird das Feld dennoch aus der Benutzeroberfläche des Benutzers entfernt.
-   Sie können Benutzeroberflächenkonfigurationen derselben Seite aufzeichnen, basierend auf verschiedenen Zugriffspunkten für die Seite. Beispielsweise kann das Fenster **Verkaufsaufträge** angepasst werden, um es anders anzuzeigen, wenn es im Fenster **Debitorenkarte** geöffnet wird, als wenn es im **Verkaufsauftragverarbeitung**-Rollencenter geöffnet wird. Der Punkt, von dem Sie auf die anzupassende Seite zugreifen, ist in der Anpassung dieser Seite aufgezeichnet. Entsprechend bestehen möglicherweise mehrere Seitenanpassungsdatensätze in der Datenbank, wie Sie im **Profilkonfiguration löschen**-Fenster sehen.  
-   Anders als wenn Benutzer die Größe von Fenstern oder die Breite der Spalten auf ihrem eigenen Computer ändern, werden solche grundlegenden Ansichtsänderungen, die Sie während der Konfiguration der Benutzeroberfläche für ein Profil vornehmen, nicht im Profil gespeichert und sind nicht für die Benutzer verfügbar, die dem Profil zugeordnet sind. Grundlegende Ansichtsänderungen sind computerspezifisch.   

## <a name="configure-a-profile-with-the-includenavwindowsincludesnavwindowsmdmd-in-configuration-mode"></a>Konfigurieren eines Profils mit [!INCLUDE[nav_windows](includes/nav_windows_md.md)] im Konfigurationsmodus
1.  Öffnen Sie eine Eingabeaufforderung und geben Sie den folgenden Befehl ein, um Änderungen am Installationsordner von [!INCLUDE[nav_windows](includes/nav_windows_md.md)] vorzunehmen. Beispiel:  
  
    ```  
    cd C:\Program Files\(x86)\Microsoft Dynamics NAV\110\RoleTailored Client  
    ```  
  
2.  Geben Sie den folgenden Befehl ein, um [!INCLUDE[nav_windows](includes/nav_windows_md.md)] im Konfigurationsmodus für ein bestimmtes Profil zu starten:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"profileid"  
    ```  
  
     Ersetzen Sie **profileid** durch den Namen des Profils, das Sie konfigurieren möchten.  
  
     Um zum Beispiel das Buchhaltungsmanagerprofil zu konfigurieren, verwenden sie diesen Befehl:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"Accounting Manager"  
    ``` 

3. Jetzt sind Sie soweit, mit der Konfiguration der Benutzeroberfläche zu beginnen, was genauso geschieht, wie einzelne Benutzer ihre eigenen Arbeitsbereiche personalisieren. Weitere Informationen finden Sie unter [Personalisieren des Arbeitsbereichs in [!INCLUDE[nav_windows](includes/nav_windows_md.md)]](ui-personalization-windows-client.md). 

## <a name="cancel-ui-configuration"></a>Stornieren der UI-Konfiguration
Stornieren Sie UI-Anpassungen, die Sie als Konfiguration für ein Profil in einer von drei Arten vorgenommen haben:  
  
-   Stornieren Sie alle UI-Anpassungen, die Sie für ein Profil durchgeführt haben, indem Sie die Schaltfläche **Konfigurierte Seiten löschen** im Fenster **Profilkarte** betätigen.  
  
-   Stornieren Sie UI-Anpassungen, die Sie für bestimmte Seiten für ein Profil vorgenommen haben, indem Sie die Zeilen im **Profil-Konfiguration**-Fenster löschen.  
  
-   Stornieren Sie UI-Anpassungen, die Sie für einen bestimmten UI-bereich einer bestimmten Seite für ein Profil vorgenommen haben, indem Sie die Schaltfläche **Standardeinstellungen wiederherstellen** im Fenster **Anpassen** betätigen.  
  
### <a name="general-information"></a>Allgemeine Informationen  
-   Benutzer können Benutzeroberflächenanpassungen unter ihrer eigenen Benutzeranmeldung vornehmen, um ihre Benutzeroberfläche zu personalisieren. Ebenso wird eine Personalisierung des Benutzeroberfläche nicht storniert, wenn Sie Ihre Benutzeroberflächen-Konfiguration einer Seite stornieren, die ein Benutzer seitdem personalisiert hat. Ebenso wird die Personalisierung der Benutzeroberfläche gespeichert und nicht durch die neue Seitenkonfiguration überschrieben, wenn Sie eine neue Konfiguration der durch den Benutzer personalisierten Benutzeroberfläche vornehmen.  

    Die einzige Situation, in der die UI-Konfiguration UI-Personalisierungen überschreibt, ist die, in der ein UI-Element durch die Konfiguration entfernt wird. Wenn beispielsweise der Administrator ein Feld entfernt, das der Benutzer umbenannt oder verschoben hat, wird das Feld dennoch aus der Benutzeroberfläche des Benutzers entfernt.  
  
-   Im Fenster **Benutzrpersonalisierung löschen** und mit der Schaltfläche **Standardeinstellungen** wiederherstellen im Fenster **Anpassen** können Benutzer UI-Anpassungen stornieren, die sie an Seiten unter ihrer eigenen Benutzeranmeldung vorgenommen haben. Wenn sie dies tun, wird das Layout der Seiten auf jeder UI-Anpassung zurückgesetzt, die der Administrator für das Profil konfiguriert hat. Wenn das Profil nicht konfiguriert wurde, wird das Layout der Seiten des Benutzers auf die Standardprofilkonfiguration zurückgesetzt. Weitere Informationen darüber, wie Benutzer Personalisierung stornieren, siehe [Stornieren der Personalisierung](ui-personalization-windows-client.md#CancelPersonalization).
  
### <a name="to-cancel-all-ui-customization-that-you-have-made-for-a-profile"></a>Alle Benutzeroberflächenanpassung, die Sie für ein Profil vorgenommen haben, stornieren  
  
1.  Geben Sie im Feld **Suchen** den Begriff **Profile** ein, und wählen Sie dann den zugehörigen Link aus.  
  
2.  Wählen Sie das Profil aus, für das Sie alle UI-Anpassungen stornieren möchten, und dann, auf der Registerkarte **Start**, in der Gruppe **Verwalten**, **Löschen**.  
  
3.  Wählen Sie im Fenster **Profilkarte** auf der Registerkarte **Aktionen** in der Gruppe **Funktionen** die Option **Konfigurierte Seiten löschen** aus.  
  
> [!NOTE]  
>  Alle UI-Anpassungen für das Profil, sowohl die, die mit der Anwendung installiert wurden, als auch die durch den Administrator vorgenommenen, werden storniert. Auf das Profil abgestimmte Seitenlayouts verbleiben nicht in der Datenbank.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-specific-page-for-a-profile"></a>Benutzeroberflächenanpassungen, die Sie für eine bestimmte Seite für ein Profil vorgenommen haben, stornieren  
  
1.  Geben Sie im Feld **Suchen** die Begriffe **Profilkonfiguration löschen** ein, und wählen Sie dann den zugehörigen Link aus.  
  
2.  Wählen Sie den Profil-/Seitensatz aus, für den Sie Ihre UI-Anpassung stornieren möchten, und dann, auf der Registerkarte **Start**, in der Gruppe **Verwalten**, **Löschen**.  
  
    > [!IMPORTANT]  
    >  Wenn Sie verschiedene UI-Anpassungen derselben Seite auf der Grundlage verschiedener Navigationspfade zu der Seite konfiguriert haben, wird jede Seitenanpassung im Fenster **Profilkonfiguration löschen** mit den gleichen Informationen aufgelistet. Es gibt keine Informationen, um festzustellen, welche Position mit welchem Navigationspfad verknüpft ist. Daher müssen Sie die Zeilen entweder einzeln löschen, und dann Sichtprüfen auf der Seite durchführen, oder Sie können alle Zeilen mit Benutzeroberflächenanpassungen für das Profil/die Seite löschen.
    >    
    >  Alle Benutzeroberfläche-Anpassungen für die Seite für das Profil, die Sie jemals in der Installation durchgeführt haben, oder seitdem Sie zuletzt das Fenster **Profilkonfiguration löschen** verwendet haben, werden storniert. Das Layout der Seite wird auf das Standardlayout des Seitenobjekts zurückgesetzt.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-a-specific-ui-area-for-a-specific-page-for-a-profile"></a>Eine Benutzeroberflächenanpassung stornieren, die Sie an einem bestimmten Benutzeroberflächenbereich für eine bestimmte Seite für ein Profil vorgenommen haben  
  
Sie können Änderungen für die einzelnen Benutzeroberflächenbereiche, wie z. B. ein Menüband, rückgängig machen, indem Sie die Schaltfläche **Standardeinstellungen wiederherstellen** im Fenster **Anpassen** verwenden. Oder Sie können alle UI-Änderungen annullieren, die Sie für ein Profil vorgenommen haben, indem Sie das  Fenster **Profilkonfiguration löschen**verwenden.  
  
Die Benutzeroberflächenanpassung für das Profil des speziellen Benutzeroberflächenbereichs auf der jeweiligen Seite wird abgebrochen. Das Layout des UI-Bereichs wird auf die Standardkonfiguration zurückgesetzt, wie entweder vom Administrator konfiguriert oder wie mit der Anwendung installiert.  
  
## <a name="see-also"></a>Siehe auch  
[Anpassen von [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-customizing-overview.md)   

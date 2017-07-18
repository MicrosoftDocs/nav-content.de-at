---
title: 'Gewusst wie: Einrichten des Bankdatenkonvertierungsservice'
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
ms.openlocfilehash: 801e2abee52ec9804028a797e4f330b5e080549a
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Gewusst wie: Einrichten des Bankdatenkonvertierungsservice
Sie können Zahlungspositionen aus dem Fenster **Zahlungsausgangs Buch.-Blatt** in einen Datenstream exportieren, den Sie dann bei Ihrer Bank zum automatische Verarbeiten hochladen, sodass Sie elektronische Zahlungen nicht einzeln ausführen müssen. Weitere Informationen finden Sie unter [So gehts: Zahlungen in eine Bankdatei exportieren](payables-how-export-payments-bank-file.md).

Ein globaler Diensteanbieter, der Bankdaten in das Dateiformat konvertiert, das Ihre Bank verlangt, ist in Dynamics NAV verbunden und kann aktiviert werden.

Als Alternative zum Bankfeeddienstes Envestnet können Sie auch den Bankdaten-Konvertierungsdienst verwenden, um eine Bankkontoauszugsdatei, die Sie von Ihrer Bank erhalten, in einen Datenstream zu konvertieren, den Sie in Dynamics NAV importieren können. Weitere Informationen finden Sie unter [So gehts: Zahlungen automatisch vornehmen und Bankkonten abstimmen](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Hinweis**: Der Bankdaten-Konvertierungsdienst legt möglicherweise einen Höchstwert für die Anzahl der Zeilen fest, die in einer Datei exportiert werden können. Sie erhalten eine Fehlermeldung, wenn der Grenzwert überschritten wird. Es wird empfohlen, das Bankkontoauszugsdateien nicht 1000 Zeilen überschreiten, da die Verarbeitungszeit im Bankdaten-Konvertierungsdienst andernfalls sich erheblich erhöht.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Ihr Unternehmen für den Bankdatenkonvertierungs-Service anmelden
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung Bankdaten-Konvertierungsservice** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Das Fenster **Einrichtung Bankdaten-Konvertierungsservice** wird geöffnet und zeigt drei Felder an, die mit relevanten URLs des Anbieters des Bankdaten-Konvertierungsdienst vorab ausgefüllt sind.

    **Hinweis**: In der Demodatenbank "CRONUS AG" werden die Felder "Benutzername" und "Kennwort" mit Demonstrationsanmeldungsinformationen vorausgefüllt, die Sie mit den tatsächlichen Informationen Ihres Unternehmens ersetzen müssen, wenn Sie sich für den Bankdaten-Konvertierungsdienst anmelden.
3. Wählen Sie im Feld **Registrierungs-URL** die Browserschaltfläche, um die Registrierungsseite des Dienstanbieters zu öffnen.  
4. Geben Sie auf der Registrierungsseite des Bankdatendienstanbieters den Benutzernamen und das Kennwort für das Abonnement Ihres Unternehmens ein, und schließen Sie dann die Anmeldung ab, wie von dem Dienstanbieter angewiesen.

    Ihr Unternehmen ist jetzt für den Bankdatenkonvertierungs-Dienst registriert. Fahren Sie fort, indem Sie den Benutzernamen und das Kennwort eingeben, die Sie in den entsprechenden Einrichtungsfeldern in Dynamics NAV für den Dienst festgelegt haben.
5. Im Fenster **Einrichtung Bankdaten-Konvertierungsservice** geben Sie im Feld **Benutzername** den gleichen Wert ein, den Sie als Benutzername auf der Seite des Dienstanbieters in Schritt 4 eingegeben haben.
6. Geben Sie im Feld **Kennwort** denselben Wert ein, den Sie im Feld **Kennwort** auf der Seite des Dienstanbieters in Schritt 4 angegeben haben.

## <a name="to-encrypt-your-login-information"></a>So verschlüsseln Sie Ihre Anmeldeinformationen
Es wird empfohlen, dass Sie die Anmeldeinformationen, die Sie im Fenster **Einrichtung Bankdaten-Konvertierungsservice** eingeben, schützen. Sie können Daten auf dem Dynamics NAV-Server verschlüsseln, indem Sie neue Verschlüsselungsschlüssel erstellen oder vorhandene importieren, die Sie auf der Dynamics NAV-Serverinstanz aktivieren, die mit der Datenbank verknüpft ist.

1. Wählen Sie im Fenster **Einrichtung Bankdaten-Konvertierungsservice** die Aktion **Verschlüsselungsverwaltung**.
2. Aktivieren Sie im Fenster **Datenverschlüsselungsverwaltung** die Verschlüsselung der Daten.

##<a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Um die Liste der gerade unterstützten Bankdatenformate anzeigen oder zu aktualisieren
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung Bankdaten-Konvertierungsservice** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Einrichtung Bankdaten-Konvertierungsservice** die Aktion **Bankname – Datenkonvertierungsübersicht**, um die Liste der Banknamen zu öffnen, die die Bankdatenformate darstellen, die von dem Konvertierungs-Service unterstützt werden.
3. Wählen Sie auf der Seite **Bankname – Datenkonvertierungsübersicht** die Aktion **Banknamenübersicht aktualisieren** aus.

Die Liste der Bankdatenformaten, die aus dem Bankdatenkonvertierungs-Service unterstützt werden, wird jetzt aktualisiert. Dies ist die Liste der Banknamen, gefiltert nach den Ländern/Regionen, die Sie im Feld **Bankname – Datenkonvertierung** im Fenster **Bankkontokarte** auswählen können.

**Hinweis**: Die Aktualisierung der unterstützten Bankdatenformate erfolgt auch, wenn Sie einen Wert im Feld **Bankname – Datenkonvertierung** des Bankkontos auswählen oder dort einen Wert eingeben.

Sie sind nun für den Bankdatenkonvertierungs-Dienst registriert. Fahren Sie fort, die Registrierungsinformationen über jedes Bankkonto wiederzugeben, das der Service verwendet.

## <a name="to-set-up-bank-accounts-to-use-the-bank-data-conversion-service"></a>Bankkonten einrichten, die für den Bankdatenkonvertierungs-Service verwendet werden
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die Karte für ein Bankkonto, mit dem Sie Bankdateien exportieren oder importiere, indem Sie den Bankdatenkonvertierungs-Service verwenden.
3. Im Inforegister **Transfer** im Feld **Format Zahlungsexport** wählen Sie **Bankdaten-Konvertierungsdienst – Kreditüberweisung** aus, um den Export der Zahlungen einzurichten.
4. Geben Sie im Feld **Bankname – Datenkonvertierung** den Namen des Datenformats der Bank ein, für das Sie sich in Schritt 4 im Abschnitt “So melden Sie sich für den Bankdatenkonvertierungsservice an” angemeldet haben, oder wählen Sie dieses aus.
5. Wiederholen Sie die Schritte 1 bis 4 für andere Bankkonten, die den Bankdaten-Konvertierungsdienst verwenden.

## <a name="see-also"></a>Siehe auch  
[Bank einrichten](bank-setup-banking.md)  
[Verwalten von Bankkonten](bank-manage-bank-accounts.md)


---
title: "Verwenden des Dynamics NAV-Inhaltspakets für Power BI"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 6351e4819a2f3665cc561b5b1f868eea5d435f75
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a>Verwenden des Dynamics NAV-Inhaltspakets für Power BI
Nutzen Sie Einblicke in Ihre Dynamics NAV-Daten mit Power BI und dem Dynamics NAV-Inhaltspaket. Power BI ruft die Daten ab und dann erstellt ein Standarddashboard und Berichte auf Grundlage der Daten.  

Das Inhaltspaket ist vorkonfiguriert, um mit Umsatzdaten und Finanzdaten aus dem Demounternehmen zu arbeiten, das Sie erhalten, wenn Sie sich zur Dynamics NAV-Vorschau anmelden.  

- Wählen Sie eine Darstellung im Dashboard, um einen von sieben Berichten anzuzeigen.  
- Filtern Sie den Bericht oder fügen Sie Felder hinzu, die Sie überwachen möchten.  
- Heften Sie diese benutzerdefinierte Ansicht an das Dashboard an, um sie weiter zu Verfolgen.  
Das Dashboard und die zu Grunde liegenden Berichte aktualisieren sich täglich. Sie können den Aktualisierungszeitplan steuern und die Häufigkeit im Dataset ändern.  

## <a name="accessing-dynamics-nav-in-power-bi"></a>Aufrufen von Dynamics NAV in Power BI
Um Ihre Dynamics NAV-Daten in Power BI anzuzeigen, müssen Sie Folgendes haben:  

- Zugriff auf Dynamics NAV. Weitere Informationen finden Sie unter [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Zugriff auf Power BI Weitere Informationen finden Sie unter [Power BI](https://powerbi.microsoft.com).

Auf der Power BI-Website finden Sie zusätzliche Informationen zum [Hinzufügen des Dynamics NAV-Inhaltspakets zu Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).  

Um auf das Dynamics NAV-Inhaltspaket in Power BI zuzugreifen, müssen Sie im Verbindungsfenster die folgenden Informationen angeben:

| Feld       | Beschreibung              |
|-------------|--------------------------|
|**OData-Feed-URL**|Die OData-URL, damit Power BI auf die Daten von Ihrem Unternehmen zugreifen kann, wie beispielsweise https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').|
|**Authentifizierungsmethode**|Wählen Sie **Standard** aus.|
|**Benutzername**|Das E-Mail-Konto, das Sie verwendet haben, um sich für Dynamics NAV anzumelden, z. B. *me@mybusiness.com*.|
|**Kennwort**|Dies ist der Webdienst-Zugriffsschlüssel für Ihr Benutzerkonto in Dynamics NAV.|

Das bedeutet, dass Sie zwei Informationen aus Dynamics NAV benötigen: die OData-URL und den Webdienst-Zugriffsschlüssel für Ihr Benutzerkonto.  
**Abrufen der URL**  
Wenn Sie Dynamics NAV zu Power BI hinzufügen, müssen Sie eine URL angeben, über die Power BI Daten von Ihrem Unternehmen abrufen kann. Im Verbindungsfenster wird die URL als **OData-Feed URL** bezeichnet und muss folgendes Format aufweisen:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
In diesem Beispiel ist *mybusiness* der Name des Dynamics NAV-Dienstes und *CRONUS US* ist der Name des Demounternehmens, wobei *%20* das Leerzeichen im Namen darstellt.   
Um die URL abzurufen, suchen Sie in Dynamics NAV das Fenster **Webdienste** und öffnen es. Dieses Fenster führt die Webdienste auf, die aktuell verfügbar sind, und Sie können den Link aus dem **OData URL**-Feld für einen der OData-Webdienste kopieren.  
**Abrufen des Webdienst-Zugriffsschlüssels**  
Um Daten aus Dynamics NAV in Power BI zu nutzen, müssen Sie im Fenster **Mit Dynamics NAV verbinden** Ihren Benutzernamen (Ihr E-Mail-Konto) und ein Kennwort angeben. Das Kennwort ist der Webdienst-Zugriffsschlüssel, den Sie in Dynamics NAV für Ihr Benutzerkonto angelegt haben.  
Um den Webdienst-Zugriffsschlüssel in Dynamics NAV abzurufen, suchen Sie das Fenster **Benutzer**, und öffnen dann die Karte für Ihr Benutzerkonto. Kopieren Sie im Inforegister **Webdienstzugriff** den Inhalt des Felds **Webdienst-Zugriffsschlüssel**. Wenn das Feld leer ist, wählen Sie im Menüband **Webdienst-Zugriffsschlüssel ändern**", **Schlüssel läuft nie ab**, und klicken Sie anschließend auf OK. Anschließend können Sie den Schlüssel kopieren.  

## <a name="getting-data-from-dynamics-nav"></a>Abrufen von Daten aus Dynamics NAV
Das Dynamics NAV-Dashboard zeigt die Berichte an, die sie normalerweise verwenden, um Ihr Geschäft zu verfolgen. Die Daten werden von Ihrem Dynamics NAV-Unternehmen über Webdienste zum Lesen von Livedaten abgerufen. In Dynamics NAV listet das Fenster **Webdienste** die Webdienste auf, die für Sie eingerichtet wurden, einschließlich der folgenden, die vom Inhaltspaket in Power BI genutzt werden:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance-Einrichtung  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Hinweis**: Wenn Sie den Namen dieser Webdienste ändern, werden die Daten nicht in Power BI angezeigt.  
Wenn Sie weitere Daten in Power BI hinzufügen und verwenden wollen, müssen Sie die Tabellen in Dynamics NAV suchen, sie als Webdienste verfügbar machen und diese dann dem Inhaltspaket hinzufügen. Dies ist ein erweitertes Szenario. Wir empfehlen, dass Sie mit den Daten beginnen, die bereits in Power BI verfügbar sind.  

## <a name="troubleshooting"></a>Problembehebung
Das Power BI-Dashboard beruht auf den veröffentlichten Webdiensten, die oben erwähnten werden. Es enthält Daten vom Demomandanten oder von Ihrem eigenen Unternehmen wenn Sie Daten aus der aktuellen Finanzeinrichtungslösung importieren. Wenn etwas schief geht, stellt dieser Abschnitt eine Problemumgehung für die häufigsten Probleme bereit.  

**Parameterprüfung fehlgeschlagen. Prüfen Sie, ob alle Parameter gültig sind**  
Wenn Sie diesen Fehler erhalten nachdem Sie die Dynamics NAV-URL eingegeben haben, vergewissern Sie sich, dass die folgenden Anforderungen erfüllt sind:  

- Die URL folgt diesem Muster:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Löschen Sie den Text nach Mandantennamen in den Klammern  
- Stellen Sie sicher, dass am Ende der URL kein Schrägstrich steht.  
- Stellen Sie sicher, dass es sich um eine sichere Verbindung handelt (URL beginnt mit *https*).  


**"Anmeldung fehlgeschlagen"**  
Wenn Sie einen "Anmeldung fehlgeschlagen"-Fehler erhalten, wenn Sie mit Ihren Dynamics NAV-Anmeldedaten am Dashboard angemeldet sind, kann dies durch eines der folgenden Probleme verursacht werden:

* Das Konto, das Sie verwenden, hat keine Berechtigungen, um die Dynamics NAV-Daten aus Ihrem Konto zu lesen.

    Prüfen Sie Ihr Benutzerkonto in Dynamics NAV und vergewissern Sie sich, ob Sie den richtigen Webdienst-Zugriffsschlüssel und das passende Kennwort verwendet haben, und versuchen Sie es dann erneut.  
* Die Dynamics NAV-Instanz mit der Sie eine Verbindung herstellen wollen, hat kein gültiges SSL-Zertifikat. In diesem Fall wir eine detailliertere Fehlermeldung angezeigt ("Vertrauenswürdiges SSL-Beziehung kann nicht erstellt werden").

    **Hinweis**: Selbstsignierte Zertifikate werden nicht unterstützt.  


**"Oops"**  
Wenn Sie ein Oops "-Fehlerdialogfeld" erhalten, nachdem Sie das Authentifizierungsdialogfeld abgeschlossen haben, wird dieses am häufigsten durch ein Problem mit der Verbindung zu den Daten für das Inhaltspaket verursacht.

* Vergewissern Sie sich, dass die URL dem Muster folgt, das oben angegeben wurde:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
* Ein häufiger Fehler ist, das gesamte URL für einen bestimmten Webdienst angegeben wird:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup  
* Oder Sie vergessen den Unternehmensnamen anzugeben:

    https://mybusiness.projectmadeira.com:7048/MS/OData/  


## <a name="see-also"></a>Siehe auch
[Willkommen bei Dynamics NAV](across-get-started.md)  


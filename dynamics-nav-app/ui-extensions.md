---
title: Installieren von Erweiterungen, um Dynamics NAV anzupassen
description: "Informationen zum Hinzuf�gen von Funktionalit�t und Anpassungen f�r Dynamics NAV durch die Installation von Erweiterungen."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: app, add-in, manifest, customize
ms.date: 07/07/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 109eb8d0e2a38566739878ef513ffa3bec8dcd30
ms.contentlocale: de-at
ms.lasthandoff: 10/26/2017

---
# <a name="customizing-dynamics-nav-using-extensions"></a>Dynamics NAV Benutzererweiterungen anpassen
Sie k�nnen [!INCLUDE[d365fin](includes/d365fin_md.md)] �ndern, indem Sie beispielsweise Erweiterungen installieren, die Funktionalit�t hinzuf�gen, das Verhalten �ndern oder Zugriff auf die neuen Onlinediensten geben.
Wenn Sie das [!INCLUDE[d365fin](includes/d365fin_md.md)] zuerst starten, werden bestimmte Erweiterungen bereits eingerichtet. Im Zeitverlauf werden mehr Erweiterungen f�r Sie zug�nglich und Sie k�nnen ausw�hlen, ob Sie die Erweiterung verwenden m�chten oder nicht.

Beispielsweise bietet Microsoft eine Erweiterung an, die die Integration mit Standard Paypal-Zahlungen erm�glicht. Diese Erweiterung wird standardm��ig eingerichtet.
Wenn aber keine andere Erweiterung bereitgestellt wird, die die Integration mit einem anderen Zahlungsservice anbietet, k�nnen Sie die neue Erweiterung einrichten und dann ausw�hlen, welcher der beiden Services verwendet werden soll.  

Sie verwalten die Erweiterung des **Erweiterungs-Verwaltungs**-Fenster. Sie k�nnen vom Startbildschirm auf dieses Fenster zugreifen. In der oberen rechter Ecke w�hlen Sie das Symbol **Nach Seite oder Bericht suchen aus**![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "")Symbol nach Seite oder Bericht suchen. Geben Sie **Erweiterung** ein und w�hlen Sie dann den entsprechenden Link aus.  

> [!NOTE]  
>   Wenn Sie der Meinung sind, Sie sollten Zugriff zu einer Erweiterung haben, k�nnen die Funktionalit�t aber nicht finden, �berpr�fen Sie das Fenster **Erweiterungsverwaltung**, wenn die Erweiterung dort nicht aufgef�hrt wird, k�nnen Sie sie einrichten, wie im folgenden Abschnitt erl�utert.  

## <a name="installing-an-extension"></a>Eine Erweiterung wird installiert
Sie k�nnen neue Erweiterungen vom Marketplace abrufen unter [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1). Hier k�nnen Sie alle verf�gbaren Erweiterungen anzeigen f�r [!INCLUDE[d365fin](includes/d365fin_md.md)] und Sie k�nnen Apps, Erweiterungen und Inhaltpakete f�r andere Microsoft-Produkte abrufen. Legen Sie die gew�nschten Filter fest, werfen Sie einen Blick auf die Informationen f�r jede Erweiterung, und rufen Sie eine Erweiterung f�r Ihr [!INCLUDE[d365fin](includes/d365fin_md.md)] ab.  
> [!NOTE]  
>   Melden Sie sich auf [AppSource.microsoft.com](https://appsource.microsoft.com/)�ber Ihr E-Mail- Konto an, das Sie f�r [!INCLUDE[d365fin](includes/d365fin_md.md)] verwenden. Verwenden Sie dasselbe E-Mail-Konto f�r andere Produkte und Dienste f�r eine reibungslose Nutzung.  

Sie k�nnen auch auf den Marketplace aus [!INCLUDE[d365fin](includes/d365fin_md.md)]zugreifen. Im Fenster **Erweiterungsverwaltung** k�nnen Sie die Erweiterungen sehen, die zur Zeit installiert sind, und Sie k�nnen die Seite **Marketplace f�r Erweiterungen** �ffnen, die die [!INCLUDE[d365fin](includes/d365fin_md.md)]Erweiterungen anzeigen, die aktuell �ber die AppSource verf�gbar sind. Wenn Sie den Link *Weitere Apps* ausw�hlen, werden Sie auf [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1) weitergeleitet.  

Wenn Sie eine Erweiterung ausw�hlen, k�nnen Sie erfahren, was die Erweiterung ausf�hrt, und auf die Hilfe f�r die Erweiterung zugreifen, um mehr dar�ber zu erfahren. Wenn Sie eine Erweiterung erhalten m�chten, m�ssen Sie die Nutzungsbedingungen zustimmen. Wenn Sie Erweiterungen von der AppSource-Website abrufen, werden Sie in [!INCLUDE[d365fin](includes/d365fin_md.md)] angemeldet, um die Installation abzuschlie�en.  

Wenn Sie eine Erweiterung installieren, m�ssen Sie diese m�glicherweise einrichten, wie ein Konto zur Verwendung mit Erweiterung f�r **Paypal-Zahlungen Standard** f�r [!INCLUDE[d365fin](includes/d365fin_md.md)] definieren.
Andere Erweiterungen f�gen einfach Felder einer vorhandenen Seite hinzu, oder sie f�gen beispielsweise eine neue Seite hinzu.   

Wenn Sie eine Erweiterung deinstallieren und Sie dann Ihre Absicht �ndern, k�nnen Sie sie wieder einrichten. Wenn Sie eine Erweiterung deinstallieren, die Sie verwendet haben, werden die Daten beibehalten, sodass, wenn Sie die Erweiterung erneut einrichten, die Daten noch verf�gbar sind.  

Einige Erweiterungen werden von Microsoft bereitgestellt, und andere Erweiterungen werden von anderen [anderen Unternehmen](ui-extensions-other.md) bereitgestellt. Alle Erweiterungen werden getestet, bevor sie zug�nglich gemacht werden, aber wir empfehlen, dass Sie auf die Links zugreifen, die mit jeder Erweiterung zur Verf�gung gestellt wurden, um mehr �ber die Erweiterung zu erfahren, bevor Sie entscheiden, sie einzurichten.  

Microsoft stellt die folgenden Erweiterungen bereit:  

* [Dynamics GP Datenmigration](ui-extensions-dynamicsgp-data-migration.md)  
* [PayPal Payments Standard](ui-extensions-paypal-payments-standard.md)  
* [QuickBooks Datenmigration](ui-extensions-quickbooks-data-migration.md)  
* [Umsatz- und Lagerbestandsplanung](ui-extensions-sales-forecast.md)  
* [Ceridian-Gehaltsliste](ui-extensions-ceridian-payroll.md)  
* [Import von QuickBooks-Lohndatei](ui-extensions-quickbooks-payroll.md)  
* [WorldPay Zahlungsstandard](ui-extensions-worldpay-payments-standard.md)
* [GetAddress.io Postleitzahlen Gro�britannien](ui-extensions-getaddressio.md)
* [QuickBooks Onlin Datenmigration](ui-extensions-quickbooks-online-data-migration.md)
* [Buchhaltungsportal](ui-extensions-accountant-portal.md)  
* [Schliffbildanalysator](ui-extensions-image-analyzer.md)

> [!NOTE]  
>  Neue Erweiterungen sind nicht in AppSource verf�gbar, sofort nachdem wird ein ank�ndigen aktualisieren. Sie k�nnen die Erweiterung [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1) im Auge behalten.

## <a name="see-also"></a>Siehe auch
[Gewusst wie: Aktivieren von Debitoren-Zahlungen durch Paypal](sales-how-enable-payment-service-extensions.md)  
[Gesch�ftsdaten aus anderen Finanzsystemen migrieren](upload-data.md)    
[[!INCLUDE[d365fin](includes/d365fin_md.md)]Erweiterungen f�r andere Anbieter](ui-extensions-other.md)E  
[Willkommen bei [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  

##



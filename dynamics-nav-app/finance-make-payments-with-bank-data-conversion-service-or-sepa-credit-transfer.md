---
title: "Wählen Sie die Methode „elektronische Zahlungen” aus"
description: Verwalten Sie Zahlungen an Ihre Kreditoren, indem Sie eine Datei zusammen mit den Zahlungsinformationen von den Buch.-Blattzeilen exportieren.
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: baafa833fb170fb05f866aac91a05085545aaf97
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="make-payments-with-bank-data-conversion-service-or-sepa-credit-transfer"></a>Nemen Sie Zahlungen mit dem Bank-Datenkonvertierungs-Service- oder einer SEPA-Banküberweisung vor
Im Fenster **Zahlungsjournal** können Sie Zahlungen an Ihre Kreditoren verarbeiten, indem Sie eine Datei zusammen mit den Zahlungsinformationen von den Buch.-Blattzeilen exportieren. Sie können die Datei dann zu Ihrer elektronischen Bank hochladen, um die entsprechenden Geldüberweisungen zu verarbeiten. [!INCLUDE[d365fin](includes/d365fin_md.md)] unterstützt das Abbuchungsformat SEPA, aber in Ihrem Land/die Region, sind möglicherweise andere Formate für den elektronischen Zahlungsverkehr verfügbar.   

 Um SEPA-Banküberweisungen zu aktivieren, müssen Sie zunächst ein Bankkonto, einen Kreditor und das Fibu Buch.-Blatt anlegen, auf dem das Zahlungsausgangs Buch.-Blatt basiert. Sie bereiten dann Zahlungen an Kreditoren vor, indem Sie das Fenster **Zahlungsjournal** automatisch mit fälligen Zahlungen mit angegebenen Buchungsdaten ausfüllen.  

> [!NOTE]  
>  Wenn Sie geprüft haben, ob die Zahlungen erfolgreich von der Bank verarbeitet wurden, können Sie mit der Buchung der Zahlungsausgangs Buch.-Blattzeilen fortfahren.  

 In der folgenden Tabelle wird eine Reihe von Aufgaben mit Verknüpfungen zu den beschriebenen Themen erläutert.   

|**Aufgabe**|**Siehe**|  
|------------|-------------|  
|Aktivieren Sie Bankdatenkonvertierungsfunktion, um eine beliebige Bankkontoauszugsdatei in ein Format umzuwandeln, das Sie importieren können, oder um Ihre exportierten Zahlungsdateien in das Format umzuwandeln, das Ihre Bank verlangt.|[Gewusst wie: Einrichten des Bankdatenkonvertierungsservice](bank-how-setup-bank-data-conversion-service.md)|  
|Richten Sie ein Bankkonto, einen Lieferanten und ein Zahlungsbuch für SEPA-Banküberweisung ein.|[So wird's gemacht: SEPA-Kreditübertragungen einrichten](finance-how-to-set-up-sepa-credit-transfer.md)|  
|Füllen Sie das Zahlungsausgangs Buch.-Blatt mit Zeilen für fällige Zahlungen an Kreditoren, mit der Option, Buchungsdaten basierend auf dem Fälligkeitsdatum der zugehörigen Einkaufsbelege einzufügen.|[Verwalten von Verbindlichkeiten](payables-manage-payables.md)|  
|Exportieren von Zahlungsausgangs Buch.-Blattzeilen in eine Datei im SEPA-Banküberweisungsformat.|[Vorgehensweise: Zahlungen in eine Bankdatei exportieren](payables-how-export-payments-bank-file.md)|  
|Prüfen Sie, welche Zahlungen exportiert wurden und in welche Dateien.|Kreditübertragungsjournale|  
|Wenn die elektronische Zahlung erfolgreich von der Bank verarbeitet wird, buchen Sie die Zahlungen.|[Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)A|  

## <a name="see-also"></a>Siehe auch  
[Gewusst wie: Einrichten des Bankdatenkonvertierungsservice](bank-how-setup-bank-data-conversion-service.md)  
[So wird's gemacht: SEPA-Kreditübertragungen einrichten](finance-how-to-set-up-sepa-credit-transfer.md)  
[Verwalten von Verbindlichkeiten](payables-manage-payables.md)   
[Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)A  
[Einziehen von Zahlungen per Lastschriftverfahren SEPA](finance-collect-payments-with-sepa-direct-debit.md)   


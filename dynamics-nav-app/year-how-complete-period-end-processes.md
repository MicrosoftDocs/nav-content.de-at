---
title: "Optionale Aktivitäten beispielsweise für Abschlussperioden"
description: "In diesem Thema werden die optionalen Vorgänge und Aktivitäten Abschlussbuchhaltungsperioden in Dynamics NAV dargelegt."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 06/19/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca22e72552c69d3bcb0b85101b586796ff026896
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="overview-of-tasks-to-close-accounting-periods"></a>Überblick zu Aufgaben, Buchhaltungsperioden zu schließen
[!INCLUDE[d365fin](includes/d365fin_md.md)] zwingt Sie nicht, Perioden zu schließen, aber es gibt viele Aktivitäten am Periodenende (Monatsende), die Sie ausführen können. Dieses Thema zeigt eine Übersicht von optionalen Vorgängen und Aktivitäten für Perioden, die bereitstehen.  

## <a name="general-ledger"></a>Sachposten
* Geben Sie systemweite und benutzerspezifische Buchungsperioden an.  

    Dies gibt die Daten an, zwischen denen Buchungen zulässig sind. Je nach Geschäftsanforderungen empfiehlt es sich, die Buchungsdatumsbereiche für Benutzer zu Beginn des Periodenabschlusses einzugrenzen. Weitere Informationen finden Sie unter [Vorgehensweise: Abschließen von Buchhaltungsperioden](finance-how-specify-posting-periods.md).  
* Führen Sie alle notwendigen Sachpostenregulierungen durch.  
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter.  
  <!--* Process Consolidations-->
* Führen Sie Kontenschemata wie folgt aus:  
  * Öffnen Sie das Fenster **Kontenschema** und klicken Sie auf **Drucken**.  

## <a name="sales-and-receivables"></a>Debitoren und Verkauf
* Alle Aufträge, Rechnungen, Gutschriften und Reklamationen werden gebucht.  
* Buchen Sie alle Barzahlungseingangs-Buch.-Blätter.  
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Debitoren und Verkauf beziehen.  
* Stimmen Sie die Debitoren mit der Finanzbuchhaltung ab.  
* Führen Sie die Stapelverarbeitung **Fakturierte Aufträge löschen** aus.  

## <a name="purchases-and-payables"></a>Kreditoren und Einkauf
* Alle Aufträge, Rechnungen, Gutschriften und Reklamationen für Kreditoren werden gebucht.  
* Buchen Sie das Zahlungsausgangs Buch.-Blatt.  
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Kreditoren und Einkäufe beziehen.  
* Führen Sie den Bericht **Kreditor - Saldenrückblick** aus, und stimmen Sie die Kreditoren mit der Finanzbuchhaltung ab.  
* Führen Sie die Stapelverarbeitung **Erledigte fakturierte Bestellungen löschen** aus.  

Anlagen
* Alle Wartungskosten wurden über die Anlagen-Buch.-Blätter oder Rechnungen gebucht.
* Buchen Sie Regulierungen.
* Buchen Sie die Zuschreibung.
* Buchen Sie die Abschreibung.
* Aktualisieren und buchen Sie das Buch.-Blatt für wiederkehrende Anlagen

Intercompany
* Verarbeiten von Intercompanytransaktionen

## <a name="calculate-and-process-sales-tax"></a>Berechnen und erfassen Sie die MwSt.
* Schließen Sie Steuer-Abrechnungen ab.  

## <a name="see-also"></a>Siehe auch
[Beenden von Jahresabschluss und Perioden](year-close-years-periods.md)  
[Schließen der Bücher](year-close-books.md)  
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


---
title: "Periode schließen"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a>Periode schließen
Die Anwendung zwingt Sie nicht dazu Perioden abzuschließen, aber es gibt viele Aktivitäten am Ende der Periode (Monatsende), die in der Anwendung ausgeführt werden können, wenn Sie möchten. Dieses Thema enthält eine Übersicht dieser Prozesse und Aktivitäten, die für Ihren Mandanten möglicherweise erforderlich sind.

## <a name="general-ledger"></a>Sachposten
* Geben Sie systemweite und benutzerspezifische Buchungsdatumsbereiche an.

    Dies gibt die Daten an, zwischen denen Buchungen zulässig sind. Je nach Geschäftsanforderungen empfiehlt es sich, die Buchungsdatumsbereiche für Benutzer zu Beginn des Periodenabschlusses einzugrenzen. Weitere Informationen finden Sie unter [Vorgehensweise: Abschließen von Buchhaltungsperioden](finance-setup-how-specify-posting-periods.md).
* Führen Sie alle notwendigen Sachpostenregulierungen durch.
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter.
<!--* Process Consolidations-->
* Führen Sie Kontenschemata wie folgt aus:
  1. Öffnen Sie das Fenster **Kontenschema** und klicken Sie auf **Drucken**.
  2. Füllen Sie das Fenster **Kontenschema** aus und klicken Sie auf **Drucken**.

## <a name="sales--receivables"></a>Debitoren & Verkauf
* Alle Aufträge, Rechnungen, Gutschriften und Reklamationen werden gebucht.
* Buchen Sie alle Barzahlungseingangs-Buch.-Blätter.
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Debitoren und Verkauf beziehen.
* Stimmen Sie die Debitoren mit der Finanzbuchhaltung ab.
* Führen Sie die Stapelverarbeitung **Fakturierte Aufträge löschen** aus.

## <a name="purchases--payables"></a>Kreditoren & Einkauf
* Alle Aufträge, Rechnungen, Gutschriften und Reklamationen für Kreditoren werden gebucht.
* Buchen Sie das Zahlungsausgangs Buch.-Blatt.
* Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Kreditoren und Einkäufe beziehen.
* Führen Sie den Bericht **Kreditor - Saldenrückblick** aus, und stimmen Sie die Kreditoren mit der Finanzbuchhaltung ab.
* Führen Sie die Stapelverarbeitung **Erledigte fakturierte Bestellungen löschen** aus.

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a>Berechnen und erfassen Sie die MwSt.
*  Schließen Sie Steuer-Abrechnungen ab.

## <a name="see-also"></a>Siehe auch
[Beenden von Jahresabschluss und Perioden](year-close-years-periods.md)  
[Buchabschluss](year-close-books.md)


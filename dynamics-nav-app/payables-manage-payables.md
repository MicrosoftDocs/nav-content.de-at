---
title: Verwalten von Verbindlichkeiten
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 50a68e1eaf0d6057420635f85b473639e39caa5a
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="manage-payables"></a>Verwalten von Verbindlichkeiten
Eine zentrale Aufgabe beim Verwalten von Kreditoren ist die Bezahlung der Kreditoren. Sie können Funktionen verwenden, um das Fenster **Zahlung Buch.-Blatt** automatisch mit Zahlungszeilen für fällige Einkaufsrechnungen auszufüllen. Um die entsprechenden Banktransaktionen schnell auszuführen, können Sie mehrere Zahlungsausgangs Buch.-Blattzeilen in eine Datei exportieren, die Sie dann zu Ihrer Bank für die Verarbeitung hochgeladen werden. Sie können Zahlungen auch mit Scheck leisten inkl. Schecks als elektronischer Zahlungsverkehr zu senden.

Eine weitere typische Aufgabe ist die Ausgleichung von ausgehenden Zahlungen zu ihrem zugehörigen Debitor bzw. an Kreditorenposten zuzuordnen und die entsprechenden Einkaufsrechnungen oder Einkaufsgutschriften dadurch zu schließen, wenn sie bezahlt sind. Diese Arbeit können Sie dann im Fenster **Zahlungs-Abstimmungs-Buch.-Blatt** ausführen, indem Sie eine Bankkontoauszugsdatei importieren, um die Zahlungen in Dynamics NAV schnell zu erfassen. Eine automatische Anwendungsfunktion gleicht die Zahlungen in ihrem zugehörigen offenen Debitoren- bzw. Kreditorenposten auf Grundlage der Datenabgleichungen zwischen Zahlungstext und Posteninformationen aus. Sie können verschiedene Funktionen nutzen, um automatische Anwendungen zu überprüfen und zu ändern, bevor Sie das Blatt buchen. Sie können die offenen Bankkontoposten für ausgeglichenen Posten schließen, wenn Sie das Buch.-Blatt buchen. Das bedeutet, dass das Bankkonto automatisch abgestimmt wird, wenn alle Zahlungen ausgeglichen werden.

Alternativ können Sie ausgehende Zahlungen im **Zahlungsausgangs Buch.-Blatt**-Fenster oder aus den zugehörigen Kreditorenposten manuell ausgleichen.

Die folgende Tabelle enthält eine Abfolge von Aufgaben sowie Links zu den Kreditoren, in denen diese Aufgaben erläutert werden.

|Aktion |Siehe |
|---|----|
|Generieren Sie fällig Kreditorenzahlungen priorisiert nach dem Skonto und den überfälligen Zahlungen. Optional exportieren Sie die Zahlungen in eine Bankdatei beim Buchen.|[Zahlungen vornehmen](payables-make-payments.md)|
|Gleichen Sie Kreditorenzahlungen automatisch für unbezahlte Einkaufsrechnungen aus, indem Sie eine Bankkontoauszugsdatei importieren.|[Zahlungen automatisch vornehmen und Bankkonten abstimmen](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|Gleichen Sie Kreditorenzahlungen für unbezahlten Einkaufsrechnungen manuell aus.|[Gewusst wie: Kreditorenzahlungen manuell anwenden](payables-how-apply-purchase-transactions-manually.md)|

## <a name="see-also"></a>Siehe auch
[Einkauf verwalten](purchasing-manage-purchasing.md)  
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)  
[Übergreifende Geschäftsbereiche](ui-across-business-areas.md)


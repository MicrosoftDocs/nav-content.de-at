---
title: Lieferbenachrichtigungen
description: "Lieferbenachrichtigungen dienen dazu, überfällige Kreditorlieferungen zu verfolgen und Kreditoren an überfällige Lieferungen zu erinnern."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 263a1a00f4e0511b6e49ffb749ac06518828e30a
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---
# <a name="delivery-reminders"></a>Lieferbenachrichtigungen
Lieferbenachrichtigungen dienen dazu, überfällige Kreditorlieferungen zu verfolgen und Kreditoren an überfällige Lieferungen zu erinnern. Zur Erstellung von Lieferbenachrichtigungen müssen Sie Folgendes einrichten:  

- Lieferbenachrichtigungsmethoden  

    Lieferbenachrichtigungsmethoden werden durch einen Code identifiziert, der Kreditoren zugewiesen werden muss. Um mehrere Einstellungskombinationen verwenden zu können, müssen Sie jeweils für jede Einstellung getrennt einen Code festlegen. Sie können eine beliebige Anzahl an Lieferbenachrichtigungsmethoden einrichten.  

- Lieferbenachrichtigungsstufen  

    Für jede Lieferbenachrichtigungsmethode müssen gesonderte Lieferbenachrichtigungstexte festgelegt werden. Diese Stufen bestimmen, wie oft Lieferbenachrichtigungen für eine bestimmte Methode erzeugt werden können. Stufe 1 ist die erste Lieferbenachrichtigung, die Sie für eine überfällige Lieferung erstellen. Stufe 2 ist die zweite Lieferbenachrichtigung und so weiter. Bei der Erstellung von Lieferbenachrichtigungen wird die Anzahl der zuvor erstellten Benachrichtigungen berücksichtigt und die für die aktuelle Anzahl definierte Methode verwendet.  

- Lieferbenachrichtigungstexte  

    Sie müssen für jede Lieferbenachrichtigungsstufe gesonderte Lieferbenachrichtigungstexte festlegen. Es gibt zwei Arten von Lieferbenachrichtigungstexten: Vortexte und Nachtexte. Der Vortext wird unter dem Kopf vor der Liste von Einträgen, die angemahnt werden, gedruckt. Der Nachtext wird nach dieser Liste gedruckt.  

Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminder-terms-levels-and-text.md).  

Nachdem Sie die Liefermethoden eingerichtet haben, müssen Sie den Kreditoren Lieferbenachrichtigungsmethodencodes zuweisen. Weitere Informationen finden Sie unter [Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md).  

Lieferbenachrichtigungen können manuell oder automatisch erstellt werden. Sie können den Batchauftrag **Lieferbenachrichtigung erstellen** zum automatischen Erstellen von Lieferbenachrichtigungen nutzen. Bei Verwendung dieses Batchauftrags können Sie die Bestellungen auswählen, für die Lieferbenachrichtigungen erstellt werden müssen. Weitere Informationen finden Sie unter [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-issue-delivery-reminders.md).  

Sie können Dokumente auch in Bezug auf Bestell- oder Auftragspositionen verfolgen.  

[!INCLUDE[navnow](../../includes/navnow_md.md)] stellt die folgenden Berichte bereit:  

- **Reg. Lieferbenachrichtigung** – Zum Anzeigen der Lieferbenachrichtigungen für Kreditoren.  
- **Lieferbenachrichtigung - Test** - Zum Überprüfen der Lieferbenachrichtigungen vor deren Ausgabe.  

Weitere Informationen finden Sie unter [Gewusst wie: Drucken von Testberichten für Lieferbenachrichtigungen](how-to-print-test-reports-for-delivery-reminders.md).  

## <a name="see-also"></a>Siehe auch  
 [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminders.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungsbedingungen, -stufen und -text](how-to-set-up-delivery-reminder-terms-levels-and-text.md)   
 [Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-generate-delivery-reminders.md)   
 [Gewusst wie: Lieferbenachrichtigungen manuell erstellen](how-to-create-delivery-reminders-manually.md)   
 [Gewusst wie: Lieferbenachrichtigungen ausstellen](how-to-issue-delivery-reminders.md)   
 [So drucken Sie Testberichte vor dem Registrieren von Lieferanmahnungen](how-to-print-test-reports-for-delivery-reminders.md)


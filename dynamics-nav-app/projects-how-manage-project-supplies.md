---
title: 'Vorgehensweise: Verwalten von Projektmitteln'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a>Vorgehensweise: Verwalten von Projektlieferungen
Die Verwaltung der Projektmittel für Artikel, Services und Aufwendungen ist ein integraler und wichtiger Bestandteil der Ausführung von Projekten. Sie können entweder verfügbaren Lagerbestand verwenden oder projektspezifische Einkäufe mithilfe von Bestellungen und/oder Einkaufsrechnungen durchführen. Beispiel: Bei einem Serviceprojekt für einen Computer wird eine neue Festplatte benötigt. Sie erstellen eine Einkaufsrechnung für den Kauf einer neuen Festplatte und erfassen das Projekt, für das die Festplatte verwendet wird.

Falls für den Verkaufsprozess keine separate Erfassung von physischen Transaktionen erforderlich ist, kann ein Verkauf möglicherweise nur in einer Einkaufsrechnung oder im Fenster **Fibu Buch.-Blatt** verarbeitet werden. Weitere Informationen finden Sie unter [So gehts: Nutzung von Projekten](projects-how-record-job-usage.md).

## <a name="to-purchase-items-or-services-for-a-job"></a>Um Artikel oder Services für ein Projekt kaufen
Der folgende Ablauf zeigt, wie eine Einkaufsrechnung zum Kauf von Produkten für ein Projekt verwendet wird. Die gleichen Schritte gelten auch, wenn sie eine Bestellung verwenden.  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einkaufsrechnungen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Aktion **Neu** aus, und füllen Sie die Felder nach Bedarf aus. Weitere Informationen finden Sie unter [So gehts: Erfassen eines Einkaufs](purchasing-how-record-purchases.md).
3. Im Feld **Projektnummer** und Feld **Projektaufgabennummer** wählen Sie die Informationen des Projektes aus, für das Sie Artikel oder Services kaufen möchten.  

    Den Wert, den Sie im Feld **Projektzeilenart** auswählen, definiert, ob eine Planungszeile erstellt wird, wenn Sie den Verbrauch eines Artikels buchen. Wenn das Feld **Fakturierbar** enthält, dann werden die Projektzeilen erstellt, die bereit sind, um dem Kunden in Rechnung zu stellen. Weitere Informationen finden Sie unter [Gewusst wie: Projekte fakturieren](projects-how-invoice-jobs.md).

4. Wählen Sie die Aktion **Buchen** aus.

## <a name="to-view-the-value-of-purchases-for-a-job"></a>So zeigen Sie den Wert eines Kaufes für ein Projekt  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Projekt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Eine relevante Projektkarte öffnen.

    In der **Registerkarte** Inforegister zeigt das Feld **Ausstehende Bestellungen** den gesamten ausstehenden Betrag in Landeswährung, , den gesamten Lagerbestand und die Services für den Kauf von Dokumenten für die Projektaufgabenzeile.  

    Das Feld **Nicht fakturierter Lieferbetrag** zeigt den Wert der Artikel, die mit Verkaufsdokumenten geliefert aber noch nicht fakturiert wurden.  

3. Klicken Sie auf eines der Felder, um das Fenster **Verkaufszeilen** zu öffnen. In diesem Fenster können Sie Informationen aus der Bestellung nachlesen – einschließlich Informationen zu eingegangenen Artikeln oder Ressourcen.

## <a name="to-post-a-job-related-expense"></a>Projektbezogene Aufwendung buchen  
Wenn Sie die außerordentlichen oder einmalige Projektausgaben verursachen, können Sie das Fenster **Projekt Buch.-Blatt** verwenden, um diese direkt auf das Konto des entsprechenden Projekts zu buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Projekt Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Erstellen Sie eine neue Zeile, und geben Sie Informationen zur Aufwendung einschließlich Informationen zur **Projektnummer.** und zur **Projektaufgabennummer** ein.  
3. Wenn der Verkaufsauftrag ausgeführt wurde, wählen Sie die Aktion **Buchen** aus.


## <a name="see-also"></a>Siehe auch
[Projekte verwalten](projects-manage-projects.md)  
[Finanzen](finance-setup.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)         
[Verkauf verwalten](sales-manage-sales.md)      
[Arbeiten mit Dynamics NAV](ui-work-product.md)  

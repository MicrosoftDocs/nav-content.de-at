---
title: Verwalten von Forderungen
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
ms.openlocfilehash: 3f2be627dfda9720e9f31fd227164d1c27116d2c
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="manage-receivables"></a>Verwalten von Forderungen#
Eine zentrale Aufgabe, wenn Sie Forderungen verwalten, ist es, eingehende Zahlungen zu ihrem zugehörigen Debitor bzw. an Kreditorenposten zuzuordnen und die entsprechenden Verkaufsrechnungen oder Einkaufsgutschriften dadurch zu schließen, wenn sie bezahlt sind. Wenn alle Zahlungen ausgeglichen werden, können Sie das Bankkonto abstimmen.  

Diese Aufgabe können Sie dann im Fenster **Zahlungs-Abstimmungs-Buch.-Blatt** ausführen, indem Sie eine Bankkontoauszugsdatei oder -Feed importieren, um die Zahlungen in Dynamics NAV schnell zu erfassen. Eine automatische Anwendungsfunktion gleicht die Zahlungen in ihrem zugehörigen offenen Debitoren- bzw. Kreditorenposten auf Grundlage der Datenabgleichungen zwischen Zahlungstext und Posteninformationen aus. Sie können auch automatische Anwendungen überprüfen und ändern, bevor Sie das Blatt buchen. Sie können die offenen Bankkontoposten für ausgeglichenen Posten schließen, wenn Sie das Buch.-Blatt buchen. Das bedeutet, dass das Bankkonto automatisch abgestimmt wird, wenn alle Zahlungen ausgeglichen werden.

**Hinweis**: Sie können Bankkonten als separate Aufgabe im Fenster **Bankkonto Abstimmung** abstimmen. Es unterstützt auch Scheckposten. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Bankkonten](bank-how-reconcile-bank-accounts-separately.md).

Alternativ können Sie Zahlungen im Fenster **Zahlungs-Registrierung** anwenden, indem Sie manuell Zahlungseingänge wie Kasse, Scheck oder Bankbuchung für eine generierte Liste der unbezahlten Verkaufsbelegen überprüfen. Beachten Sie, dass diese Funktionen nur für Verkaufsbelege verfügbar sind.

Wie eine andere manuelle Abstimmung der Zahlungen können Sie jede Lieferung in die entsprechende Finanzbuchhaltung, in ein Debitoren- oder anderes Konto buchen, indem Sie eine Zahlungszeile im **Zahlungseingangs Buch.-Blatt** ** Fenster eingeben. In diesem Fall können Sie entweder den Wareneingang oder die Rückerstattung mit einem oder mehreren offenen Posten anwenden, bevor Sie das Zahlungseingangs Buch.-Blatt buchen, oder Sie können sie aus den erstellten Debitorenposten erstellen.

Eine andere Aufgabe, wenn sie Forderungen verwalten, ist es, offene Salden zu erfassen, einschließlich Finanzeinrichtungsgbühren zu verwalten und Mahnungen auszugeben.

In der folgenden Tabelle wird eine Reihe von Aufgaben mit Verknüpfungen zu den beschriebenen Themen erläutert.

|Aktion |Siehe |
|---|----|
|Zahlungen verwenden, um Debitoren- oder Kreditorenposten zu öffnen, indem Sie einen Bankkontoauszug importieren und das Bankkonto abstimmen, wenn alle Zahlungen ausgeglichen werden.|[Zahlungen automatisch vornehmen und Bankkonten abstimmen](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|Ausgleichen von Zahlungen mit offenen Debitorenposten auf Grundlage der manuellen Eingabe in einer Liste von unbezahlten Verkaufsbelegen. | [Gewusst wie: Debitoren-Zahlungen aus einer Liste mit unbezahlten Verkaufsbelegen abstimmen](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)|
|Buchen Sie Zahlungseingänge oder Erstattungen für Debitoren im Zahlungseingangs Buch.-Blatt für Debitorenposten, entweder aus dem Buch.-Blatt oder von gebuchten Posten. | [Vorgehensweise: Manuelle Abstimmung vom Zahlungen](receivables-how-apply-sales-transactions-manually.md) |
|Erinnern von Debitoren an überfällige Beträge, Berechnen von Zinsen und Finanzeinrichtungs-Gebühren sowie Verwalten von Debitoren | [Vorgehensweise: Einziehen von Restbeträgen](receivables-collect-outstanding-balances.md) |

## <a name="see-also"></a>Siehe auch
[Verkauf verwalten](sales-manage-sales.md)  
[Verwalten von Verbindlichkeiten](payables-manage-payables.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)  
[Übergreifende Geschäftsbereiche](ui-across-business-areas.md)


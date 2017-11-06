---
title: 'Vorgehensweise: Drucken von Zahlungsanzeigen'
description: "Sie können Ihren Kreditoren helfen, Abstimmungen auszuführen, indem Sie Zahlungsanzeige ausdrucken, bevor Sie ein Buch.-Blatt buchen oder wenn Sie eine Zahlung buchen."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/26/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 71c84b4a7bad83e6008c0fa34f908e133b014a59
ms.contentlocale: de-at
ms.lasthandoff: 10/26/2017

---

#<a name="how-to-print-remittance-advice"></a>Vorgehensweise: Drucken von Zahlungsanzeigen
Sie können Zahlungsanzeigen ausdrucken, bevor Sie ein Buch.-Blatt buchen oder wenn Sie eine Zahlung gebucht haben. Diese Anzeige zeigt die Kreditors-Nummern an, was hilft, die Abstimmungen auszuführen.

##<a name="to-print-remittance-advice"></a>Vorgehensweise: Drucken von Zahlungsanzeigen
1. Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Buchblatt** ein und wählen den zugehörenden Link aus.  
2. Im Fenster **Zahlungsausgangs Buch.-Blatt** wählen Sie die Zahlung aus, für die die Zahlungsanzeige gedruckt werden muss.  
3. Wählen Sie die **Zahlungsanzeige drucken** Aktion aus.  
4. In der Stapelverarbeitung **Zahlungsanzeige - Buch.-Blatt** im Inforegister **Fen. Buch.-Blattzeile**, wählen Sie die entsprechenden Filter aus.  
  
    >[!Note]
    > Sie können anhand der externen Belegnummer des Kreditors filtern, um Zahlungen mit Rechnungen zu finden.

5. Wählen Sie im Inforegister **Verkäufer** die entsprechenden Filter aus.  
6. Wählen Sie **Drucken**, um den Bericht zu drucken oder **Seitenansicht**, um den Bericht am Bildschirm anzuzeigen.  

## <a name="using-remittance-advice-reports"></a>Zahlungsanzeige-Berichte verwenden
Die folgende Tabelle beschreibt die Berichte, die Sie mit Zahlungsanzeigen verwenden können:

|Bericht|Description|
|----|----|
|Rimessenavis – Buch.-Blatt-Bericht|Dieser Bericht zeigt, welche Belege in der Zahlung erfasst werden. Für Fibu Buch.-Blattzeilen können Sie die Buch.-Blattvorlage und den Buch.-Blattname definieren, aus denen die Zahlungsanzeigen gedruckt werden, das Datum der ersten Aktivität, die gedruckt wird und den Filter auf einer Belegnummer. Sie können die Anzahl der Kreditoren festlegen, die in den Bericht aufgenommen werden sollen. |
|Rimessenavis – Eintragsbericht| Dieser Bericht zeigt, welche Belege in der Zahlung erfasst werden. Sie definieren die Berichtsinhalte, indem Sie Filter setzen. Sie können weitere Felder im Register einrichten, indem Sie das Feld **Feld** auswählen. Für Kreditorenposten können Sie die Kreditoren angeben, die im Bericht, in Datum der ersten zu druckenden Aktivität, in der Währung und der zu berücksichtigen Postennummer zu berücksichtigen sind. |

> [!Note]
> Die Zahlungsanzeige - Buch.-Blatt-Bericht unterstützt keine Querwährungs-Anwendungsszenarien oder -Zahlungstoleranzen. Weitere Informationen finden Sie unter [So geht's: Anwendung von Kreditorenposten in unterschiedlichen Währungen aktivieren](finance-how-enable-application-ledger-entries-different-currencies.md)

> [!Tip]
> Weitere Informationen darüber, wie Sie mit Berichten arbeiten, finden Sie unter [Anzeigen von Testberichten vor dem Buchen](ui-how-view-test-reports-posting.md) [Arbeiten mit Berichten](ui-work-report.md) und [Ermitteln, Filtern und Sortieren von Daten](ui-enter-criteria-filters.md).

##<a name="see-also"></a>Siehe auch  
[Willkommen bei Dynamics NAV](across-get-started.md)

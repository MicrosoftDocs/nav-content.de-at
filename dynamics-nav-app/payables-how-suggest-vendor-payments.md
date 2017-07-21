---
title: "Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren"
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
ms.openlocfilehash: 11bfba9f279f6bd84c5d169f6f97fd48759bc6df
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-suggest-vendor-payments"></a>Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren
Im **Zahlungsausgangs Buch.-Blatt**-Fenster können Sie eine Funktion verwenden, um Zahlungszeilen entsprechend den Einstellungen vorzuschlagen (z. B. Zahlungen, die in Kürze fällig sind oder Zahlungen, bei denen ein Rabatt verfügbar ist).

Um von den Zahlungsvorschlägen vollständig zu profitieren, müssen Sie Ihre Kreditoren zuerst priorisieren. Weitere Informationen finden Sie unter [Vorgehensweise: Priorisieren von Kreditoren](purchasing-how-prioritize-vendors.md).

Kreditorenposten, die nicht als **Abwarten** markiert sind, werden nicht in die Stapelverarbeitung einbezogen.  

**Wichtig**: Falls Sie Rechnungsrabatte für fristgerechte Zahlung in Anspruch nehmen wollen und einen verfügbaren Betrag angegeben haben, wird der Betrag zuerst für die fälligen Kreditorenposten nach der Priorität und dann für die fälligen Kreditorenposten ohne Priorität verwendet. Danach werden die offenen Kreditorenposten mit Rabattmöglichkeiten, geordnet nach der Kreditorennummer, berücksichtigt.

## <a name="to-use-the-suggest-vendor-payments-function"></a>Die Zahlungsvorschlagfunktion verwenden
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlung Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie das relevante Buch.-Blatt, und klicken Sie dann auf die Aktion **Zahlungsvorschlag**.
3. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
4. Wählen Sie die Schaltfläche **OK**.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Einfügen des Fälligkeitsdatum als Buchungsdatum auf Zahlungsausgangs Buch.-Blattzeilen
Wenn Sie die Stapelverarbeitung **Zahlungsvorschlag** verwenden, um Zahlungszeilen für Ihre Kreditoren zu erstellen, können Sie zwei Felder ausfüllen, um sicherzustellen, dass die erzeugten Zeilen das Fälligkeitsdatum verwenden, um das Buchungsdatum zu berechnen. Diese Felder sind **Buchungsdatum von Fälligkeitsdatum für Ausgleich mit Beleg berechnen** und **Offset für Fälligkeitsdatum für Ausgleich mit Beleg**.

**Wichtig**: Sie können das Feld **Buchungsdatum von Fälligkeitsdatum für Ausgleich mit Beleg berechnen** nicht zusammen mit den Feldern **Skonto finden** oder **Pro Kreditor summieren** verwenden. Der Grund besteht darin, dass, wenn das Buchungsdatum auf dem Fälligkeitsdatum liegt, einige Zahlungsrabatte nicht korrekt berechnet werden, da das Buchungsdatum nach dem Zahlungsrabattdatum liegen kann.
Wenn das berechnete Buchungsdatum in der Vergangenheit liegt, wird das Buchungsdatum auf das Arbeitsdatum verschoben, und eine Warnung wird angezeigt.

Alternativ können Sie Zahlungspositionen mithilfe des Fälligkeitsdatums manuell generieren, um das Buchungsdatum zu berechnen Nachdem Sie die Kreditorenposten ausgeglichen haben, können Sie die **Buchungsdatum berechnen**-Aktion verwenden. Das Buchungsdatum auf der Buch.-Blattzeile wird jetzt zu dem Fälligkeitsdatum der zugehörigen Einkaufsrechnung aktualisiert. Weitere Informationen finden Sie unter [So gehts: Einkaufstransaktionen manuell ausgleichen](payables-how-apply-purchase-transactions-manually.md).  

**Hinweis**: Wenn die Einkaufsrechnung überfällig ist, wird das Buchungsdatum auf das Arbeitsdatum festgelegt, und die Schrift auf der Zeile wird in roter Farbe angezeigt.

## <a name="see-also"></a>Siehe auch
[Verwalten von Verbindlichkeiten](payables-manage-payables.md)  
[Zahlungen vornehmen](payables-make-payments.md)  
[Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)


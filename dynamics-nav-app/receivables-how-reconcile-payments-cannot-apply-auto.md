---
title: "Vorgehensweise: Abstimmen von Zahlungen, die nicht automatisch übernommen werden können"
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
ms.openlocfilehash: f9fd7c2958aaa359d2f6af5dde2e8be81349e900
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-payments-that-cannot-be-applied-automatically"></a>Vorgehensweise: Abstimmen von Zahlungen, die nicht automatisch übernommen werden können
Gelegentlich müssen Sie Zahlungen an Ihr Bankkonto bearbeiten, die nicht mit einem zugehörigen offenen Debitor, Kreditor oder einem Bankposten ausgeglichen werden kann. Gründe können sein, dass kein Beleg im Dynamics NAV vorhanden ist, damit die Zahlung ausgeglichen werden kann oder dass der zugehörige Beleg in Dynamics NAV einen anderen Betrag aufweist als der Transaktionsbetrag, zum Beispiel aufgrund von "Währungswechselkursen". Im Fenster **Zahlungs-Abstimmungs-Buch** erscheinen alle Transaktion für Zahlungen, die noch nicht ausgeführt wurden im Feld **Differenz**, einschließlich Beträge, die aufgrund der Gründe wie oben nicht ausgeglichen werden können.

Zahlungen, die nicht angewendet werden können, können in Zahlungsabstimmungsbuch.-Blattzeilen auf die folgenden Arten erscheinen:

- Der Wert im Feld **Differenz** entspricht dem Wert im Feld **Transaktions-Betrag**, das angibt, dass kein Teil der Zahlung mit einem zugehörigen offenen Debitor, Kreditor oder einem Bankposten ausgeglichen werden kann.

- Der Wert im Feld **Differenz** ist tiefer als der Wert im Feld **Transaktions-Betrag**, das angibt, dass ein Teil der Zahlung mit einem zugehörigen offenen Debitor, Kreditor oder einem Bankposten ausgeglichen werden kann. Der restliche Teil der Zahlung kann nicht angewendet und muss manuell oder durch direktes Buchen auf ein Konto erfolgen.

Um solche Zahlungen abzustimmen, können Sie die Übergangsdifferenz zur Kontoschaltfläche auswählen und dann definieren, auf welches Konto im Feld Differenz er gebucht wird wenn Sie das Zahlungsabstimmungsbuch.-Blatt buchen.

**Hinweis**: Ähnliche Funktionen sind vorhanden, um automatische Abstimmung von wiederkehrenden Zahlungen einzurichten, die mit keinem zugehörigen offenen Debitor, Kreditor oder die Bankposten ausgeglichen werden können.. [Weitere Informationen finden Sie unter: Vorgehensweise: Zuordnen von sich wiederholenden Zahlungen an Konten bei der automatischen Abstimmung](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)

## <a name="to-reconcile-payments-that-cannot-be-applied"></a>Abstimmen von Zahlungen, die nicht zugeordnet werden können
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlungsabstimmungsbuch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie ein Zahlungsabstimmungsbuch.-Blatt. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).
3. Wählen Sie **Differenz auf Konto buchen**. Die **Differenz auf Konto übertragen** 3. Fenster wird geöffnet.
4. Im Feld **Kontoart** definieren Sie die Kontoart, auf die der Zahlungsbetrag gebucht werden soll.
5. Wählen Sie im Feld **Kontonummer** Feld definieren Sie das Konto, auf das die Zahlung gebucht werden soll.
6. Geben Sie im Feld **Beschreibung** den Text an, der diese direkte Zahlungsbuchung beschreibt. Standardmäßig wird der Text im Feld **Transaktionstext** auf der Zahlungsabstimmungsbuch.-Blattzeile eingefügt.
7. Wählen Sie die Schaltfläche **OK**.

Wenn der Wert im Feld **Differenz** dem Wert im Feld **Transaktions-Betrag** entspricht, wenn Sie das Zahlungsabstimmungsbuch.-Blatt buchen, werden alle Zahlungen der Buch.-Blattzeile direkt auf das angegebene Gegenkonto gebucht.

Wenn der Wert im Feld **Differenz** kleiner ist als der Wert im Feld **Transaktions-Betrag** wird eine zusätzliche Buch.-Blattzeile mit dem gleichen Text und Datum und mit der Differenz erstellt, die im Feld **Transaktions-Betrag** eingefügt wird. In der ursprünglichen Buch.-Blattzeile wird die Differenz vom Wert im Feld **Transaktions-Betrag** abgezogen und die Zahlung muss dem entsprechenden Debitor, Kreditor oder Bankposteneintrag zugewiesen werden. Wenn Sie im Zahlungsabstimmungsbuch.-Blatt buchen, wird ein Teil der Zahlung als zugewiesene Zahlung gebucht. Der andere Teil der Zahlung wird direkt auf das angegebene Konto gebucht.

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Verkauf verwalten](sales-manage-sales.md)


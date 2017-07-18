---
title: "Vorgehensweise: Zahlungen manuell zuordnen oder überprüfen nach der automatischen Zuordnung."
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
ms.openlocfilehash: 556a0f74a7407d247008e2d74420803123056eff
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-review-or-apply-payments-manually-after-automatic-application"></a>Vorgehensweise: Zahlungen manuell zuordnen oder überprüfen nach der automatischen Zuordnung.
Für jede Buch.-Blattzeile, die ein Zahlung im Fenster **Zahlungsabstimmungsbuch.-Blatt** darstellt, können Sie das Fenster **Zahlungsanwendung** öffnen, um alle offenen Kandidatenposten für die Zahlung anzuzeigen und detaillierte Informationen für jeden Posten zum Datenabgleich anzuzeigen, auf denen eine Zahlungsanwendung basiert. Hier können Sie manuell Zahlungen ausgleichen, oder Zahlungen erneut ausgleichen, die automatisch auf einen falschen offenen Posten angewendet wurden,. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).

**Wichtig**: Wenn das Bankkonto, für das Sie Zahlungen abstimmen, für die Mandantenwährung eingerichtet ist, zeigt das Fenster **Zahlungsanwendung** alle offenen Posten in Mandantenwährung, einschließlich offener Posten für Belege, die ursprünglich in Fremdwährungen fakturiert wurden. Zahlungen, die mit Posten mit umgerechneten Währungen ausgeglichen wurden, könnten daher mit unterschiedlichen Beträgen gebucht werden als im ursprünglichen Beleg angegeben, aufgrund von eventuell abweichenden Wechselkursen, die von der Bank bzw. Dynamics NAV verwendet werden.

Daher empfiehlt es sich, dass Sie nach Fremdwährungscodes im Feld **Fremdwährungscode** im Fenster **Zahlungsanwendung** suchen, um zu überprüfen, ob Anwendungen auf umgerechneten Währungen basieren. Um den Originaldokumentbetrag in der Fremdwährung zu überprüfen und den verwendeten Wechselkurs anzuzeigen, aktivieren Sie **Auf Posten-Nr. anwenden** und wählen dann im Kontextmenü die , wählen die Drilldownschaltfläche, um das Fenster **Debitorenposten** oder **Kreditorenposten** zu öffnen.

Gewinn-und-Verlust-Ausgleich, der aufgrund der Fakturierung des Projekts erforderlich ist, wird nicht automatisch durch Dynamics NAV verarbeitet.

**Hinweis**: Sie können Posten mit einem anderen Vorzeichen als dem Vorzeichen der Zahlung nicht ausgleichen. Um beispielsweise sowohl eine Gutschrift mit negativem Vorzeichen als auch die zugehörige Rechnung mit positivem Vorzeichen abzuschließen, müssen Sie zuerst die Gutschrift mit der Rechnung ausgleichen und dann die Zahlung mit der Rechnung mit dem reduzierten Restbetrag ausgleichen.

**Warnung**: Falls Sie Rechnungsrabatte verwenden, und wenn das Fälligkeitsdatum vor dem Zahlungsfälligkeitsdatum ist, wird das Feld **Verbleibender Betrag inkl. Rabatt** im Fenster **Zahlungsanwendung** verwendet. Ansonsten wird der Wert aus dem Feld **Verbleibender Betrag** verwendet. Wenn die Zahlung mit einem verbilligten Betrag nach dem Zahlungsfälligkeitsdatum geleistet wurde oder der Totalbetrag bezahlt wurde, aber ein Skonto gewährt wurde, wird der Betrag nicht abgeglichen.

**Hinweis:** Sie können eine Zahlung nur mit einem Konto ausgleichen. Wenn die Anwendung auf mehrere offene Posten aufteilen möchten, zum Beispiel, um eine Pauschalzahlung auszugleichen, müssen die offenen Posten für das gleiche Konto sein. Weitere Informationen finden Sie in den Schritten 7 und 8 dieses Themas.

## <a name="to-review-or-apply-payments-after-automatic-application"></a>Vorgehensweise: Überprüfen oder Ausgleichen von Zahlungen nach automatischer Anwendung
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlungsabstimmungsbuch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie das Zahlungsabstimmungsbuch.-Blatt für ein Bankkonto, für das Sie Zahlungen abstimmen möchten. Weitere Informationen finden Sie unter [So gehts: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).
3. Im Fenster **Zahlungsabstimmungsbuch.-Blatt** wählen Sie eine Zahlung, die Sie mit einem oder mehreren offenen Posten manuell anwenden oder überprüfen möchten und wählen dann **Manuell Anwenden** aus.
4. Aktivieren Sie das Kontrollkästchen **Angewendet** für die Position mit dem offenen Eintrag aus, auf den die Zahlung angewendet werden soll.
5. Der Zahlungsbetrag, der auch im Feld **Transaktionsbetrag** unter **Zahlungszuordnung** angezeigt wird, wird im Feld **Zugeordneter Betrag** angezeigt wird, aber Sie können das Feld bearbeiten, wenn Sie zum Beispiel den Betrag auf mehrere offene Posten anwenden möchten.
6. Um einen Teil des bezahlten Betrag in einem anderen offenen Posten für das Konto auszugleichen, beispielsweise um eine Pauschalzahlung auszugleichen, aktivieren Sie das Kontrollkästchen **Zugeordnet** für die Position. Der Ausgleichsbetrag wird automatisch von dem Transaktionsbetrag abgezogen, um die Verteilung in den beiden offenen Posten widerzuspiegeln.
7. Um einen Teil einer Zahlung mit einem oder mehreren offenen Posten zu übernehmen die nicht in der Datenbank vorhanden sind, erstellen Sie eine neue Zeile unter der Zeile für das gleiche Konto. Geben Sie im Feld **Zugeordneter Betrag** den Betrag ein, der der neuen Zeile zugeordnet werden soll und passen Sie dann das Feld **Zugeordneter Betrag** auf der bestehenden Zeile an.
8. Wiederholen Sie Schritt 5, 6 oder 7 für andere offene Posten, auf die Sie einen vollständige Zahlung oder Teilzahlung anwenden möchten.
9. Wenn Sie eine Zahlungs-Anwendung überprüft oder manuell auf einen oder mehrere offene Posten angewendet haben, wählen **Anwendung akzeptieren** aus.

Das Fenster **Zugeordnete Zahlung** wird geschlossen und im Fenster **Zahlungsabstimmungsbuch.-Blatt** wird der Wert im Feld **Übereinstimmungsgenauigkeit** auf **Zugeordnet** geändert, um Ihnen mitzuteilen, dass Sie die Zahlung überprüft oder manuell angewendet haben.

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Verkauf verwalten](sales-manage-sales.md)


---
title: "Vorgehensweise: Verarbeiten einerVerkaufsrücklieferung oder von Stornierungen"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 92b65379f2ec633712a2b2c0f06615c6de61cc6e
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-sales-returns-or-cancellations"></a>Vorgehensweise: Verarbeiten einerVerkaufsrücklieferung oder von Stornierungen
Wenn Ihr Debitor Artikel zurückschicken oder Dienstleistungen löschen will, die Sie verkauft haben, können Sie eine Einkaufsgutschrift erstellen und buchen, die die angeforderte Änderung im Hinblick auf die ursprünglichen Einkaufsrechnung angibt. Um korrekte Verkaufsrechnungsinformationen zu berücksichtigen, können Sie die Verkaufsgutschrift aus der gebuchten Verkaufsrechnung erstellen oder eine Kopierfunktion verwenden.

Zusätzlich zur ursprünglich gebuchten Verkaufsrechnung können Sie die Verkaufsgutschrift für andere Verkaufsbelege übernehmen, beispielsweise einer anderen gebuchten Verkaufsrechnung, da der Debitor auch die Artikel zurücksendet, die mit dieser Rechnung geliefert werden.

Eine Rücklieferungs- oder eine Vergütung kann sich nur auf einige der Artikel oder der Services in der ursprünglichen Verkaufsrechnung beziehen. In diesem Fall müssen Sie Informationen in den Zeilen der Verkaufsgutschrift bearbeiten. Wenn Sie die Verkaufsgutschrift buchen, werden die Verkaufsbelege, die von Änderungen betroffen sind rückgängig gemacht und eine Rückerstattung für den Debitor wird erstellt.

Sie können die gebuchte Verkaufsgutschrift an den Debitor senden, um die Rücksendung oder Stornierung zu bestätigen und mitzuteilen, dass der zugehörige Wert erstattet werden wird, wenn zum Beispiel Artikel zurückgegeben werden oder eine Service-Stornierung vereinbart wurde.

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>Erstellt eine neue Verkaufsgutschrift, um eine gebuchte Verkaufsrechnung zurückzusetzen.
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Gebuchte Verkaufsrechnungen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie das Feld **Gebuchte Verkaufsrechnung**, um das Fenster **Korrekturgutschrift erstellen** zu öffnen, und wählen Sie die gebuchte Verkaufsrechnung aus, die Sie stornieren möchten.

    Die meisten Felder im Verkaufsgutschriftskopf werden mit den Informationen aus der gebuchten Verkaufsrechnung ausgefüllt. Sie können alle Felder bearbeiten, zum Beispiel mit neuen Daten, die die Rückholvereinbarung wiedergeben.
3. Bearbeiten Sie Informationen über die Zeilen entsprechend der Vereinbarung, wie die Anzahl der zurückzuerstattenden Artikel oder der gutzuschreibende Betrag.
4. Wählen Sie die Aktion **Posten ausgleichen...** aus.
5. Im Fenster **Debitorenposten zuweisen** wählen Sie die Zeile mit dem gebuchten Verkaufsbeleg, die Sie der Verkaufsgutschrift zuordnen möchten, und wählen Sie dann **Zuweisungs-ID festlegen** aus.

    Die Nummer der Verkaufsgutschrift wird im Feld **Zuweisungs-ID** eingefügt.  
6. Geben Sie in jeder Zeile im Feld **Anzuwendender Betrag** den Betrag ein, den Sie ausgleichen möchten, wenn dieser kleiner ist als der ursprüngliche Betrag.

    Im unteren Bereich des Fensters **Debitorenposten zuweisen** können Sie den Gesamtbetrag sehen, um alle beteiligten Posten zu stornieren, nämlich wenn der Wert im Feld **Saldo** Null ist.  
7. Wählen Sie die Schaltfläche **OK**. Wenn Sie die Verkaufsgutschrift buchen, wird sie für die angegebenen gebuchten Verkaufsrechnungen angewandt.

    Nachdem Sie die erforderlichen Verkaufsgutschriftszeilen erstellt oder bearbeitet haben und der Ausgleich einzelner oder mehrerer Posten angegeben wird, können Sie fortfahren, die Verkaufsgutschrift zu buchen.
8. Wählen Sie die Aktion **Buchen und Senden** aus.

Das Dialogfeld **Buchungs- und Sendebestätigung** wird geöffnet und zeigt die bevorzugte Sendemethode für den Debitor an. Sie können die Sendemethode ändern, indem Sie die Schaltfläche vom Feld **Beleg senden an** auswählen. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Sendeprofilen](sales-how-setup-document-send-profiles.md).

Die gebuchten Verkaufsdokumente für die entsprechende Gutschrift werden nun storniert und eine Erstattung der Zahlung kann für den Debitor erstellt werden. Die Verkaufsgutschrift wird entfernt und durch einen neuen Beleg in der Liste der gebuchten Verkaufsgutschriften ersetzt.

## <a name="to-create-a-sales-credit-memo-from-scratch"></a>So erstellen Sie eine Verkaufsgutschrift von Grund auf
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Gebuchte Verkaufsrechnungen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie **Neu**, um eine neue leere Verkaufsgutschrift zu öffnen.
3. Geben Sie im Feld **Debitor** den Namen eines vorhandenen Debitors ein.
4. Wählen Sie die **Beleg kopieren**-Aktion aus.
5. Wählen Sie im Fenster **Verkaufsdokument kopieren** im Feld **Dokumenttyp** **Rechnung buchen** aus.
6. Wählen Sie das Feld **Belegnummer**, Wählen Sie das Feld **Gebuchte Verkaufsrechnung.** und wählen Sie dann die gebuchte Verkaufsrechnung aus, die die Zeile enthält, die Sie stornieren möchten.
7. Wählen Sie das Kontrollkästchen **Zeilen neu berechnen**, wenn die kopierten gebuchten Verkaufsrechnungszeilen, mit einzelnen Änderungen im Artikelpreis und im Einstandspreis, aktualisiert werden sollen, da die Rechnung gebucht wurde.
8. Wählen Sie die Schaltfläche **OK**. Die kopierten Rechnungszeilen werden in die Verkaufsgutschrift eingefügt.
9. Schließen Sie die Verkaufsgutschrift ab, so wie dies unter "Verkaufsgutschrift von Grund auf erstellen" in diesem Thema erklärt ist.

## <a name="see-also"></a>Siehe auch  
[Verkauf verwalten](sales-manage-sales.md)  
[Auftrag einrichten](sales-setup-sales.md)  
[Gewusst wie: Senden von Belegen über E-Mail](ui-how-send-documents-email.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


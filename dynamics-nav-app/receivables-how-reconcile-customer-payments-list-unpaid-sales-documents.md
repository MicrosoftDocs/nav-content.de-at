---
title: Ausgleichen von Zahlungen mit nicht geleisteten Verkaufsbelegen
description: "Sie gleichen die Beträge aus, die von den Debitoren mit Bezug auf den entsprechenden Verkaufsbeleg bezahlt werden und buchen die Zahlungen, um den Debitor, die Finanzbuchhaltung und die Bankposten zu aktualisieren."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, cash receipts, customer payment
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c39a45d513ef6d5f6d4da7a052888a051d9f06d6
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-customer-payments-manually-from-a-list-of-unpaid-sales-documents"></a>Gewusst wie: Debitoren-Zahlungen aus einer Liste mit unbezahlten Verkaufsbelegen abstimmen
Wenn Ihre Debitoren Zahlungen an Ihr elektronisches Bankkonto getätigt haben, müssen Sie jeden gezahlten Betrag auf den zugehörigen Verkaufsbeleg anwenden und dann die Zahlung buchen, um die Debitoren-, Sachkonto- und Bankposten zu aktualisieren.

> [!NOTE]  
>   Sie können die selben Aufgaben einschließlich Debitorenzahlungen im Fenster **Zahlungsabstimmungsbuch.-Blatt** mithilfe von Funktionalitäten für den Bankkontoauszugsimport ausführen, die automatische Anwendung und die Bankkontoabstimmung verwenden. Weitere Informationen finden Sie unter [Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md).

Das Fenster **Zahlungsanmeldung** ist dafür ausgelegt, Sie bei Aufgaben im Zusammenhang mit dem Ausgleich interner Konten unter Verwendung von tatsächlichen Barmittelzahlen zu unterstützen, um sicherzustellen, dass Zahlungen effektiv von Kunden eingeholt werden. Mit diesem Zahlungsverarbeitungstool können Sie individuelle oder Pauschalzahlungen schnell prüfen und buchen, finanzielle Gebühren für überfällige Zahlungen initiieren, diskontierte Zahlungen in verschiedenen Szenarien verarbeiten und bestimmte unbezahlte Belege finden, für die Zahlungen erfolgt sind.

Zahlungen für verschiedene Debitoren, die verschiedene Fälligkeitsdaten haben, müssen als einzelne Zahlungen gebucht werden. Zahlungen für denselben Debitor, der das gleiche Fälligkeitsdatum hat, können als einmalige Zahlung gebucht werden. Dies ist beispielsweise dann nützlich, wenn ein Debitor eine einzelne Zahlung getätigt hat, die mehrere Verkaufsrechnungen umfasst.

## <a name="to-set-up-the-payment-registration-journal"></a>Zahlungsregistrierungsbuch.-Blatt einrichten
Da Sie verschiedene Zahlungsarten auf verschiedene Gegenkonten buchen können, müssen Sie ein Gegenkonto in Fenster **Zahlungsanmeldungs-Einrichtung** auswählen, bevor Sie die Bearbeitung von Debitorenzahlungen starten. Wenn Sie immer auf das gleiche Gegenkonto buchen, können Sie dieses Konto als Standardwert festlegen und diesen Schritt jedes Mal vermeiden, wenn Sie das Fenster **Zahlungserfassung** öffnen.  

1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Einrichtung der Zahlungserfassung** ein. Wählen Sie dann den zugehörigen Link aus.

    Alternativ wählen Sie im Fenster **Zahlungserfassung** die Aktion **Einrichten** aus.    
2. Füllen Sie die Felder im Fenster **Zahlungserfassungseinrichtung** aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.  

## <a name="to-reconcile-payments-individually"></a>Manuelles Abstimmen von Zahlungen
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie das Kontrollkästchen **Zahlung erfolgt** in der Zeile, die den gebuchten Beleg darstellt, für den eine Zahlung geleistet wurde.

    Wenn das Kontrollkästchen **Automatische Datumseingabe** im Fenster **Einrichtung der Zahlungserfassung** aktiviert ist, wird das Arbeitsdatum in Feld **Empfangsdatum** eingegeben.  
3. Geben Sie im Feld **Empfangsdatum** das Datum ein, an dem die Zahlung gemacht wurde. Dieses Datum kann vom Arbeitsdatum abweichen.  
4. In dem Feld **Betrag erhalten** geben Sie den Betrag ein, der bezahlt worden ist.

    Für gesamte Zahlungen ist es der gleiche Betrag wie der Betrag im Feld **Verbleibender Betrag** in der Zeile. Für Teilzahlungen ist der Betrag niedriger als der Betrag im Feld **Verbleibender Betrag** in der Zeile.    
5. Wiederholen Sie die Schritte 2-4 für andere Zeilen, die gebuchte Belege darstellen, für die Zahlungen getätigt wurden.  
6. Wählen Sie die Aktion **Zahlung buchen** aus.  

Die eingegebene Zahlungsinformation ist für Belege gebucht, die durch Zeilen dargestellt werden, in denen das Kontrollkästchen **Zahlung erhalten** aktiviert ist.  

Zahlungsposten werden in der Finanzbuchhaltung, Bank und in Debitorenkonten gebucht. Jede Zahlung wird für den entsprechenden gebuchten Verkaufsbeleg angewandt.  

## <a name="to-reconcile-lump-payments"></a>Pauschalzahlungen verarbeiten
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie das Kontrollkästchen **Zahlung erfolgt** in der Zeile, die die gebuchten Belege für denselben Debitor darstellen, für den eine einmalige Zahlung gemacht wurde.  

    > [!NOTE]  
>   Der Debitor im Feld **Name** muss der Gleiche in allen Zeilen sein, die als einmalige Zahlung gebucht werden.  

    Wenn das Kontrollkästchen **Automatische Datumseingabe** im Fenster **Einrichtung der Zahlungserfassung** aktiviert ist, wird das Arbeitsdatum in Feld **Empfangsdatum** eingegeben.  
3. Geben Sie im Feld **Empfangsdatum** das Datum ein, an dem die Zahlung gemacht wurde. Dieses Datum kann vom Arbeitsdatum abweichen.  

    > [!NOTE]  
>   Dieses Datum muss das gleiche in allen Zeilen sein, die als einmalige Zahlung gebucht werden.  
4. Geben Sie im Feld **Betrag erhalten** die Beträge in mehreren Zeilen ein, die den einmaligen Zahlungsbetrag zusammenfassen.  

    > [!TIP]  
>   Versuchen Sie, mit dem Pauschalbetrag so viele volle Zahlungen wie möglich zu buchen. Geben Sie Beträge auf so viele Zeilen wie möglich ein, die dieselben sind, wie der Betrag im Feld **Verbleibender Betrag**.  
5. Wiederholen Sie die Schritte 2-4 für andere Zeilen, die für gebuchte Belege für denselben Debitor stehen, für den eine einzelne Zahlung geleistet wurde.  
6. Wählen Sie die Aktion **Als einmalige Zahlung buchen** aus. Die eingegebene Zahlungsinformation ist für Belege gebucht, die durch Zeilen dargestellt werden, in denen das Kontrollkästchen **Zahlung getätigt** aktiviert ist.  

Zahlungseingänge werden in Finanzbuchhaltung, Bank und in Debitorenkonten gebucht. Jede Zahlung wird für den entsprechenden gebuchten Verkaufsbeleg angewandt.  

Wenn eine Zahlung in der Bank nicht durch Zeile im Fenster **Zahlungserfassung** angegeben wird, kann dies sein, da der zugehörige Beleg noch nicht gebucht wurde. In diesem Fall können Sie eine Suchfunktion verwenden, um den Beleg zu buchen und schnell zu suchen, um die Zahlung zu verarbeiten. Weitere Informationen finden unter "Bestimmte Verkaufsbeleg finden, die nicht vollständig fakturiertet sind".  

Wenn eine Zahlung in der Bank nicht durch einen Beleg in [!INCLUDE[d365fin](includes/d365fin_md.md)] angegeben wird, dann können Sie eine Fibu Buch.-Blattzeile aus dem Fenster **Zahlungserfassung** öffnen, um die Zahlung direkt auf das Hauptkonto zu buchen, ohne die Zahlung auf einen Beleg anzuwenden. Alternativ können Sie die Zahlung im Buch.-Blatt buchen, bis der Ursprung der Zahlung gelöst wurde. Weitere Informationen finden Sie unter "Zahlung ohne einen zugehörigen Belegabschnitt zu erfassen oder zu buchen."  

## <a name="to-process-customer-payments-with-discounts-manually"></a>Vorgehensweise: Manuelle Verarbeitung von Zahlungen mit Rabatten
Wenn Sie einen Rabatt mit dem Debitor vereinbart haben, können die Zahlungsbeträge niedriger als die fakturierten Beträge sein, wenn die Zahlung vor dem vereinbarten Skontodatum auftritt.  

Dieses Thema erläutert vier verschiedene Verfahren zum Buchen von verbilligten Zahlungen im Fenster **Zahlungserfassung**.  

* Der Zahlungsbetrag entspricht dem diskontierten Betrag und dessen Zahlungsdatum liegt vor dem Skontodatum. Sie buchen die Zahlung, wie sie ist.  
* Der Zahlungsbetrag entspricht dem diskontierten Betrag, aber dessen Zahlungsdatum liegt nach dem Skontodatum. Sie buchen die Zahlung als Teilzahlung. Der Beleg bleibt offen, um den Restbetrag einzufordern/zu bezahlen. Alternativ legen Sie das Skontodatum später fest, um die vollständige Bezahlung zu ermöglichen.  
* Die Zahlungssumme ist niedriger als der verbleibende diskontierte Betrag. Sie buchen die Zahlung als Teilzahlung. Der Beleg bleibt offen, um den Restbetrag einzufordern/zu bezahlen.  
* Die Zahlungssumme ist höher als der verbleibende diskontierte Betrag. Sie buchen die Zahlungen, wie sie sind. Nur der Restbetrag wird gebucht. Der zusätzliche Betrag wird dem Debitor gutgeschrieben.  

### <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-and-where-the-payment-date-is-before-the-discount-date"></a>Zahlungsbetrag verarbeiten, der dem diskontierten Betrag entspricht und dessen Zahlungsdatum vor dem Skontodatum liegt
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Geben Sie den Zahlungsbetrag im Feld **Betrag erhalten** ein. Der Betrag ist gleich wie der Betrag im Feld **Restbetrag nach Rabatt**.

    Das Kontrollkästchen **Zahlung erfolgt** wird automatisch aktiviert, und das Feld **Empfangsdatum** wird mit dem Arbeitsdatum ausgefüllt.    
3. Geben Sie im Feld **Datum erhalten** das Zahlungsdatum ein. Das Datum steht vor dem Datum im Feld **Skontodatum**.
4. Vergewissern Sie sich, dass das Feld **Restbetrag** den Wert Null (0) enthält.  
5. Wählen Sie auf der Registerkarte **Zahlung buchen**, um den Gesamtbetrag auf Sach-, Bank- und Debitorenkonten zu buchen.

### <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-but-where-the-payment-date-is-after-the-discount-date"></a>Zahlungsbetrag verarbeiten, der dem diskontierten Betrag entspricht, dessen Zahlungsdatum jedoch nach dem Skontodatum liegt
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Geben Sie den Zahlungsbetrag im Feld **Betrag erhalten** ein. Der Betrag ist gleich wie der Betrag im Feld **Restbetrag nach Rabatt**.

    Das Kontrollkästchen **Zahlung erfolgt** wird automatisch aktiviert, und das Feld **Empfangsdatum** wird mit dem Arbeitsdatum ausgefüllt.
3. Geben Sie im Feld **Eingangsdatum** ein Zahlungsdatum an, das nach dem Datum im Feld **Skontodatum** liegt. Datumsfelder ändern zu roter Schrift, und eine Fehlermeldung wird unten im Fenster angezeigt.

    > [!TIP]  
>   Wenn Sie eine Ausnahme erstellen möchten und den Rabatt gewähren, selbst wenn die Zahlung spät ist, dann führen Sie die folgenden Schritte durch:
4. Wählen Sie die Aktion **Details** aus.  
5. Geben Sie im Fenster **Zahlungserfassungsdatum** im Feld **Skontodatum** im Inforegister **Zahlungsrabatt** ein Datum ein, das nach dem **Empfangsdatum** im Feld **Zahlungserfassung** liegt.  

    Die Fehlermeldung und die rote Schriftart verschwinden, und Sie können fortfahren, die verbilligte Zahlung zu bearbeiten.    
6. Vergewissern Sie sich, dass das Feld **Restbetrag** den Betrag enthält, der verbleibt, um den vollständigen Rechnungsbetrag zu bezahlen.  
7. Wählen Sie die Aktion **Zahlung buchen**, um den Teilbetrag auf Sach-, Bank- und Debitorenkonten zu buchen.  

Der zugehörige Beleg bleibt offen.

### <a name="to-process-a-payment-that-is-lower-than-the-remaining-discounted-amount"></a>Zahlung verarbeiten, die niedriger als der verbleibende diskontierte Betrag ist
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Geben Sie den Zahlungsbetrag im Feld **Betrag erhalten** ein. Der Betrag ist kleiner als der Betrag im Feld **Restbetrag nach Rabatt**.

    Das Kontrollkästchen **Zahlung erfolgt** wird automatisch aktiviert, und das Feld **Empfangsdatum** wird mit dem Arbeitsdatum ausgefüllt.  
3. Geben Sie im Feld **Datum erhalten** das Zahlungsdatum ein. Das Datum steht vor dem Datum im Feld **Skontodatum**.
4. Vergewissern Sie sich, dass das Feld **Restbetrag** den Betrag enthält, der verbleibt, um den rabattierten Rechnungsbetrag zu bezahlen.  
5. Wählen Sie die Aktion **Zahlung buchen**, um den Teilbetrag auf Sach-, Bank- und Debitorenkonten zu buchen.  

Der zugehörige Beleg bleibt offen.

### <a name="to-process-a-payment-that-is-more-than-the-remaining-discounted-amount"></a>Zahlung verarbeiten, die höher als der verbleibende diskontierte Betrag ist
1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Geben Sie den Zahlungsbetrag im Feld **Betrag erhalten** ein. Der Betrag ist grösser als der Betrag im Feld **Restbetrag nach Rabatt**.  

    Das Kontrollkästchen **Zahlung erfolgt** wird automatisch aktiviert, und das Feld **Empfangsdatum** wird mit dem Arbeitsdatum ausgefüllt.    
3. Geben Sie im Feld **Datum erhalten** das Zahlungsdatum ein. Das Datum steht vor dem Datum im Feld **Skontodatum**.
4. Vergewissern Sie sich, dass das Feld **Restbetrag** den Wert Null (0) enthält.  
5. Wählen Sie auf der Registerkarte **Zahlung buchen**, um den Gesamtbetrag auf Sach-, Bank- und Debitorenkonten zu buchen.  

Der zugehörige Beleg ist abgeschlossen, und dem Debitor wird der Überzahlungsbetrag gutgeschrieben.  

## <a name="to-find-a-specific-sales-document-that-is-not-fully-invoiced"></a>Bestimmten Verkaufsbeleg suchen, der nicht vollständig fakturiert wurde
Das **Zahlungserfassungs**-Fenster unterstützt Sie bei Aufgaben, die interne Konten mit tatsächlichen Bargeldabbildungen ausgleichen müssen, um die effektive Sammlung von Debitoren und fällige Zahlung an Kreditoren sicher zu stellen. Es zeigt ausstehende eingehende Zahlungen als Zeilen an, welche Verkaufsbelege darstellen, in denen ein Betrag zur Zahlung fällig ist.  

Wenn eine Zahlung erfolgt ist, auf der Bank oder anderweitig verzeichnet wurde, wird normalerweise der zugehörige Verkaufs- oder Einkaufsbeleg als Zeile im Fenster **Zahlungserfassung** dargestellt, da für den betreffenden Beleg die Zahlung noch für den ausstehenden Betrag gebucht werden muss. Manchmal wird jedoch eine Zahlung, die geleistet wurde, nicht durch eine Zeile im Fenster **Zahlungserfassung** dargestellt, da der jeweilige Beleg üblicherweise nicht vollständig fakturiert wurde.

Im Fenster **Dokument suchen** können Sie aus Belegen suchen, die nicht vollständig fakturiert wurden. Sie können basierend auf einer oder mehrerer der folgenden Kriterien suchen:  

* Belegnummer  
* Betrag oder Betragsbereich  

Nachfolgend wird erklärt, wie man einen bestimmten Beleg findet, indem man beide Suchkriterien verwendet.  

1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Zeigen Sie mit dem Mauszeiger auf eine beliebige Zeile und wählen Sie **Dokument suchen**.
3. Im Fenster **Dokumentsuche** geben Sie einen Suchwert im Feld **Dokumentennummer** ein.  

    > [!NOTE]  
>   Der Wert, den Sie hier eingeben, ist in den ausgeblendeten Platzhalterzeichen enthalten. Das bedeutet, dass die Funktion in allen Belegnummern sucht, die den eingegebenen Wert enthalten.    
4. Geben Sie in dem Feld **Betrag** den entsprechenden Betrag ein, der auf dem Beleg vorhanden ist, den Sie finden möchten.  
5. Geben Sie im Feld **Betragsabwicklung in %** einen Prozentwert ein, um den Bereich von Beträgen zu definieren, die Sie sehen möchten, um den offenen Beleg zu finden.  

    Wenn Sie 10 eingeben, dann sucht die Funktion nach Beträgen in einem Bereich zwischen zehn Prozent unter und zehn Prozent über dem Feld **Betrag**.    
6. Wählen Sie die Aktion **Suchen** aus.  

Die Suchfunktion sucht unter Belegen, die nicht vollständig fakturiert sind basierend auf den angegebenen Kriterien.  

Wenn einer oder mehrere Belege mit den Suchkriterien im Feld **Ergebnis Dokumentsuche** übereinstimmen, dann öffnet sich das Fenster, um Zeilen anzuzeigen, die diese Dokumente darstellen. Jede Zeile enthält eine Belegnummer, eine Beschreibung und Betrag, sodass Sie einen bestimmten Beleg einfach suchen können, zum Beispiel basierend auf Informationen über Ihren Bankkontoauszug.  

Wenn eine Zahlung in der Bank nicht durch einen Beleg in [!INCLUDE[d365fin](includes/d365fin_md.md)] angegeben wird, dann können Sie eine Fibu Buch.-Blattzeile aus dem Fenster **Zahlungserfassung** öffnen, um die Zahlung direkt auf das Hauptkonto zu buchen, ohne die Zahlung auf einen Beleg anzuwenden. Alternativ können Sie die Zahlung im Buch.-Blatt buchen, bis der Ursprung der Zahlung gelöst wurde.  

## <a name="to-record-or-post-a-payment-without-a-related-document"></a>Zahlung ohne zugehörigen Beleg erfassen oder buchen
Wenn eine Zahlung in der Bank nicht durch einen Beleg in [!INCLUDE[d365fin](includes/d365fin_md.md)] angegeben wird, dann können Sie eine Fibu Buch.-Blattzeile aus dem Fenster **Zahlungserfassung** öffnen, um die Zahlung direkt auf das Hauptkonto zu buchen, ohne die Zahlung auf einen Beleg anzuwenden. Alternativ können Sie die Zahlung im Buch.-Blatt buchen, bis der Ursprung der Zahlung geklärt wurde.  

1. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Anmeldung** ein. Wählen Sie dann den zugehörigen Link aus.  

Fahren Sie fort, um eine nicht dokumentierte Zahlung zu erfassen.  

1. Wählen Sie die Aktion **Fibu Buch.-Blatt** aus.  

    Das Fenster **Fibu Buch.-Blatt** wird mit einer Zeile geöffnet, die das Saldokonto des Buch.-Blatts enthält, das im Fenster **Zahlungserfassungs-Einrichtung** festgelegt ist.  
2. Füllen Sie die restlichen Felder in der Fibu Buch.-Blattzeile aus, wie den Betrag und die Debitorennummer oder andere Informationen des Kontoauszuges. Weitere Informationen finden Sie unter [So gehts: Transaktionen direkt in der Finanzbuchhaltung buchen.](finance-how-post-transactions-directly.md).  

Sie können entweder die Buch.-Blattzeile buchen, um die Summe in dem Gegenkonto zu aktualisieren. Alternativ können Sie die Buch.-Blattzeile ungebucht lassen und fügen ggf. mit einer Notiz an, dass die Zahlung mehr Analyse benötigt.  

Wenn Sie die Buch.-Blattzeile nicht buchen lassen, wird der Wert im Feld **Ungebuchter Saldo** am unteren Rand des Fenster **Zahlungserfassung** hinzugefügt.  

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Verkauf](sales-manage-sales.md)  
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


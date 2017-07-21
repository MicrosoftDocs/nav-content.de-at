---
title: Zahlungen automatisch vornehmen Bankkonten abstimmen
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
ms.openlocfilehash: 11df387c16e19421090531fd03c209103b9989d9
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="apply-payments-automatically-and-reconcile-bank-accounts"></a>Zahlungen automatisch vornehmen Bankkonten abstimmen
Sie müssen Ihre Bank, Debitoren- und Kreditorensammelkonten im Dynamics NAV routinemäßig abstimmen, indem Sie die Zahlungen, die in Ihrem Bankkonto aufgezeichnet sind, mit ihren entsprechenden unbezahlten Rechnungen und Gutschriften oder anderen offenen Posten in Dynamics NAV ausgleichen, die Sie dann als Zahlungsausgleich buchen.

Diese Aufgabe können Sie dann im Fenster **Zahlungs-Abstimmungs-Buch.-Blatt** ausführen, indem Sie eine Bankkontoauszugsdatei oder -Feed importieren, um die Zahlungen in Dynamics NAV schnell zu erfassen. Eine automatische Anwendungsfunktion gleicht die Zahlungen in ihrem zugehörigen offenen Debitoren- bzw. Kreditorenposten auf Grundlage der Datenabgleichungen zwischen Zahlungstext und Posteninformationen aus. Sie können auch automatische Anwendungen überprüfen und ändern, bevor Sie das Blatt buchen. Sie können die offenen Bankkontoposten für ausgeglichenen Posten schließen, wenn Sie das Buch.-Blatt buchen. Das bedeutet, dass das Bankkonto automatisch abgestimmt wird, wenn alle Zahlungen ausgeglichen werden.

Um den Import von Bankkontoauszügen als Bankfeed zu aktivieren, müssen Sie den Bank-Feed-Service Envestnet Yodlee anlegen und aktivieren und dann Ihr Bankkonto mit den entsprechenden Online Bankkonten verbinden. Für weitere Informationen, siehe [So gehts: Einrichten des Envestnet Yodlee Bank-Feed-Service](bank-how-setup-bank-statement-service.md).

**Notiz**: Der Bank-Feed-Service Envestnet Yodlee oder ein anderer Bankfeeddienstservice Anbieters stehen möglicherweise nicht in der Anwendung zur Verfügung. Erkundigen Sie sich beim zuständigen Microsoft-Partner, wenn Sie einen Bankfeeddienst verwenden möchten, um Bankkontoauszüge zu importieren.

Sie können auch die Funktion für den Bankdatenkonvertierungsdienst verwenden, um eine Bankkontoauszugsdatei, die Sie von Ihrer Bank erhalten, in einen Datenstream zu konvertieren, den Sie in Dynamics NAV importieren können. Für weitere Informationen, siehe [Gewusst wie: Einrichten des Bankdatenkonvertierungsservice](bank-how-setup-bank-data-conversion-service.md).

In der folgenden Tabelle wird eine Reihe von Aufgaben mit Verknüpfungen zu den beschriebenen Themen erläutert.

|Aktion |Siehe |
|---|----|
|Zahlungen verwenden, um Debitoren- oder Kreditorenposten zu öffnen, indem Sie einen Bankkontoauszug importieren und das Bankkonto abstimmen, wenn alle Zahlungen ausgeglichen werden. | [Vorgehensweise: Abstimmen von Zahlungen mithilfe der automatischen Anwendung](receivables-how-reconcile-payments-auto-application.md) |
|Gleichen Sie manuell Zahlungen aus, indem Sie detaillierte Informationen über zugeordnete Daten und Vorschläge für offene Kandidatenposten anzeigen, mit denen Zahlungen ausgeglichen werden sollen. | [Vorgehensweise: Überprüfen oder Ausgleichen von Zahlungen nach automatischer Anwendung](receivables-how-review-apply-payments-auto-application.md)
|Lösen Sie Zahlungen auf, die nicht in ihre entsprechenden offenen Posten automatisch ausgeglichen werden können, weil beispielsweise die Beträge abweichen, oder weil ein verwandter Posten nicht vorhanden ist. | [Vorgehensweise: Abstimmen von Zahlungen, die nicht automatisch übernommen werden können](receivables-how-reconcile-payments-cannot-apply-auto.md)
|Verknüpfen Sie Text auf Zahlungen mit bestimmten Debitoren-, Kreditoren- oder Sachkonten, um solche wiederkehrenden Zahlungseingänge oder Ausgaben immer auf diesen Konten als Zahlungen ohne zugehörige Belege zu buchen, wenn keine entsprechenden Belege vorhanden sind.| [Vorgehensweise: Zuordnen von sich wiederholenden Zahlungen an Konten bei der automatischen Abstimmung](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)|

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Verkauf verwalten](sales-manage-sales.md)


---
title: "Arbeiten mit Fibu Buch.-Blättern"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2dc2b22fbc0ff70addd16ca14e8c5416c49915e7
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="work-with-general-journals"></a>Arbeiten mit Fibu Buch.-Blättern
Fibu Buch.-Blätter dienen zum Buchen auf Sachkonten sowie auf andere Konten wie Bank-, Debitoren-, Kreditoren- oder Anlagekonten. Bei der Buchung mit einem Fibu Buch.-Blatt werden immer Posten für Sachkonten erstellt. Dies gilt auch, wenn beispielsweise eine Buch.-Blattzeile auf ein Debitorenkonto gebucht wird, da ein Posten im Rahmen einer Buchungsgruppe auf ein Fibu-Debitorenkonto gebucht wird.

Die in ein Buch.-Blatt eingegebenen Informationen sind temporär und können geändert werden, solange sie sich im Buch.-Blatt befinden. Durch Buchen des Buch.-Blatts werden die Informationen in Posten auf Konten übertragen und können nicht mehr geändert werden. Der Ausgleich gebuchter Posten kann jedoch aufgehoben werden, und Sie haben die Möglichkeit zum Buchen von Storno- oder Korrekturposten.

## <a name="journal-templates-and-batches"></a>Buch-Blattvorlagen und -namen
Es gibt mehrere Fibu Buch.-Blattvorlagen. Jede Buch.-Blattvorlage wird durch ein spezifisches Fenster mit bestimmten Funktionen und den Feldern dargestellt, die benötigt werden, um diese Funktionen zu unterstützen, wie das Fenster **Zahlungs-Abstimmungs-Buch.-Blatt**, um Bankzahlungen und das Fenster **Zahlungsausgangs Buch.-Blatt** zu verarbeiten, um Ihre Kreditoren zu bezahlen.

Sie können zu jeder Buch.-Blattvorlage mehrere Buch.-Blattnamen als Buch-Stapel erstellen. Beispielsweise können Sie Ihre eigenen Buch-Stapel für das Zahlungsausgangsbuch erstellen, das Ihr persönliches Layout und Ihre Einstellungen hat.

**Hinweis**: Ein Beispiel einer persönlichen Einstellungen, die Sie in Ihrem Fibu Buch.-Stapel festlegen können, ist es, mit der Systemhilfe die Betrag-Felder auszufüllen. Wenn Sie das Kontrollkästchen **Ausgleichsbetrag vorschlagen** in der Zeile für Ihren Stapel im **Fibu Buch.-Blattnamen** auswählen, dann werden das Feld **Betrag**, beispielsweise Fibu Buch.-Blattzeilen für dieselbe Belegnummer automatisch mit dem Wert, der zum Ausgleichen des Belegs erforderlich ist, ausgefüllt. Weitere Informationen finden Sie unter [Dynamics NAV Werte vorschlagen lassen](ui-let-system-suggest-values.md).

## <a name="main-accounts-and-balancing-accounts"></a>Hauptkonten und Gegenkonten
Wurden Standardgegenkonten für die Buch.-Blattnamen eingerichtet, wird das Gegenkonto beim Ausfüllen des Felds **Kontonr.** automatisch ausgefüllt. Feld Sie müssen auch das Feld **Kontonr.**ausfüllen, Feld und **Gegenkonto-Nummer** Feld manuell. Bei einem positiven Betrag im Feld **Betrag** wird das Hauptkonto belastet, und auf dem Gegenkonto erfolgt eine Gutschrift. Bei einem negativen Betrag erfolgt eine Gutschrift auf dem Hauptkonto, und das Gegenkonto wird entsprechend belastet.

**Hinweis**: Die MwSt. für Haupt- und Gegenkonto wird getrennt berechnet, damit für die Konten unterschiedliche MwSt.-Prozentsätze verwendet werden können.

## <a name="recurring-journals"></a>Wiederkehrende Buch.-Blätter
Bei einem wiederkehrenden Buch.-Blatt handelt es sich um ein Fibu Buch.-Blatt mit speziellen Feldern für die Verwaltung von Transaktionen, die häufig mit geringen oder keinen Änderungen gebucht werden. Mithilfe dieser speziellen Felder für wiederkehrende Transaktionen können Sie feste und variable Beträge buchen. Sie können auch ein automatisches Storno für den Tag nach dem Buchungsdatum festlegen und wiederkehrende Posten zusammen mit Verteilungsschlüsseln verwenden.

## <a name="see-also"></a>Siehe auch
[Vorgehensweise: Verwenden von Verteilungsschlüsseln in Fibu Buch.-Blättern](ui-how-use-allocation-keys-general-journals.md)  
[Finanzen](finance-setup.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


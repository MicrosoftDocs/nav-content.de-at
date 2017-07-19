---
title: "Gewusst wie: Bank-Geldmittel überweisen"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f34bef80c64cbad0a0b20d4d021cefbdc5a1cb64
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-transfer-bank-funds"></a>Gewusst wie: Bank-Geldmittel überweisen
Manchmal ist es erforderlich, einen Betrag von einem Bankkonto auf ein anderes Bankkonto zu überweisen. Dafür müssen Sie eine Transaktion im Fibu Buch.-Blatt buchen. Die Aufgabe variiert abhängig davon, ob die Bankkonten dieselbe Währung oder unterschiedlichen Währungen verwenden.

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a>So buchen Sie Überweisungen zwischen Bankkonten mit demselben Währungscode:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Füllen Sie in einer Buch.-Blattzeile die Felder **Buchungsdatum** und **Belegnr.** aus. Felder.
3. Wählen Sie im Feld **Kontoart** die Option **Bankkonto** aus.
4. Wählen Sie im Feld **Kontonummer** die Bank, von der Sie den Betrag überweisen möchten.
5. Geben Sie im Feld **Betrag** den Betrag ein, der überwiesen werden soll.
6. Wählen Sie im Feld **Gegenkontoart** die Option **Bankkonto** aus.
7. Wählen Sie im Feld **Gegenkontonummer** das Bankkonto aus, an das Sie den Betrag überweisen möchten.
8. Buchen Sie die Buch.-Blattzeile.

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a>Überweisungen zwischen Bankkonten mit verschiedenen Währungscodes buchen:
Um Beträge zwischen Bankkonten zu transferieren, die unterschiedliche Währungen verwenden, müssen Sie zwei Fibu Buch.-Blattzeilen buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.
2. Erstellen Sie zwei Buch.-Bl.-Zeilen und füllen Sie **Buchungsdatum** und **Belegnr.** aus. Felder.
3. Wählen Sie in der ersten Buch.-Blattzeile des Feldes **Art** **Bankkonto** aus.
4. Wählen Sie im Feld **Kontonummer** das Bankkonto aus, von dem Sie die Beträge überweisen möchten.
5. Geben Sie im Feld **Betrag** den Betrag in der Währung des Bankkontos ein. Geben Sie die Habenbeträge mit einem Minuszeichen ein. Geben Sie die Sollbeträge ohne ein Minuszeichen ein.
6. Wählen Sie im Feld **Gegenkontoart** die Option **Bankkonto** aus.
7. Wählen Sie im Feld **Gegenkontonummer** das Bankkonto aus, an das Sie den Betrag überweisen möchten.
8. Wählen Sie in der zweiten Buch.-Blattzeile des Feldes **Art** **Bankkonto** aus.
9. Wählen Sie im Feld **Kontonummer** das Bankkonto aus, an das Sie den Betrag überweisen möchten.
10. Geben Sie im Feld **Betrag** den Betrag in der Währung des Bankkontos ein. Geben Sie die Habenbeträge mit einem Minuszeichen ein. Geben Sie die Sollbeträge ohne ein Minuszeichen ein.
11. Wählen Sie im Feld **Gegenkontoart** die Option **Bankkonto** aus.  
12. Wählen Sie im Feld **Gegenkontonummer** das Bankkonto aus, von dem Sie die Beträge überweisen möchten.

    **Hinweis**: Wenn die im Buch.-Blatt verwendeten Wechselkurse von den Wechselkursen im Fenster **Währungswechselkurse** abweichen, geben Sie eine dritte Zeile für den Wechselkursgewinn oder -verlust ein. Geben Sie **Sachkonto** im Feld **Kontoart** ein. Geben Sie die Sachkontonummer für Wechselkursgewinn oder -verlust im Feld **Kontonr.** ein. Feld Geben Sie den Wechselkursgewinn oder - verlust im Feld **Amount** mit oder ohne Minuszeichen jeweils für Soll- und Habenbeträge ein.
13. Buchen Sie die Buch.-Blattzeile.

## <a name="see-also"></a>Siehe auch  
[Verwalten von Bankkonten](bank-manage-bank-accounts.md)  
[Bank einrichten](bank-setup-banking.md)  
[Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md)


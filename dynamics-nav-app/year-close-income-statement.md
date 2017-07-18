---
title: GuV-Konten Nullstellung
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 83dfa0db1345aa18d6900470c93ccdc00bd1b403
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
# <a name="close-income-statement"></a>GuV-Konten Nullstellung
Wenn ein Geschäftsjahr vorbei ist, müssen die Perioden, aus denen es besteht, geschlossen werden. Verwenden Sie dazu den Stapelverarbeitungsjob **GuV-Konten Nullstellung**. Dieser Job überträgt die Ergebnisse des Jahrs auf ein Bilanzkonto und führt die GuV-Kontennullstellung durch. Hierfür erstellen Sie Zeilen in einem Buch.-Blatt, die Sie dann buchen können.

## <a name="to-run-the-close-income-statement-batch-job"></a>Verwenden Sie dazu den Stapelverarbeitungsjob GuV-Konten Nullstellung.
1. Schließen Sie das Geschäftsjahr ab. Das Geschäftsjahr muss geschlossen werden, bevor die Stapelverarbeitung aufgerufen werden kann. Weitere Informationen finden Sie unter [Vorgehensweise: Abschließen von Buchhaltungsperioden](year-close-account-periods.md).
2. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **GuV-Konten-Nullstellung** ein. Wählen Sie dann den zugehörigen Link aus.
3. Wählen Sie die Schaltfläche **OK**, um den Batchauftrag zu starten.

## <a name="about-the-close-income-statement-batch-job"></a>Mehr Informationen zum Stapelverarbeitungsjob GuV-Konten Nullstellung.
Mithilfe dieses Batchauftrags werden alle Sachkonten der Art "GuV" bearbeitet und Buchungszeilen erzeugt, die eine Nullstellung ihrer Salden bewirken. Anders ausgedrückt,entspricht jeder Posten der Summe aller Sachposten auf dem Konto im Geschäftsjahr. Diese neuen Posten werden in ein Buch.-Blatt eingefügt, in dem Sie ein Gegenkonto und ein Abschlusskonto GuV in der Bilanz angeben müssen, bevor diese gebucht werden. Wenn Sie das Buch.-Blatt buchen, wird ein Posten auf jedes GuV-Konto gebucht, sodass der Saldo des Kontos Null ist und gleichzeitig das Jahresergebnis in die Bilanz übertragen wird.

Sie müssen das Buch.-Blatt manuell buchen. Durch den Batchauftrag erfolgt keine automatische Buchung der Posten, es sei denn, es wird eine Berichtswährung verwendet. Wenn eine zusätzliche Berichtswährung verwendet wird, bucht die Stapelverarbeitung die Posten direkt in die Finanzbuchhaltung.

Das Datum, das von dem Batchauftrag in die Zeilen eingefügt wird, ist stets das Ultimodatum des Geschäftsjahrs. Das Ultimodatum ist ein fiktives Datum zwischen dem letzten Tag des alten und dem ersten Tag des neuen Geschäftsjahres. Der Vorteil des Buchens zu einem Ultimodatum liegt darin, dass die Salden des Geschäftsjahres mit normalen Datumsangaben erhalten bleiben.

Die Stapelverarbeitung **GuV Konten-Nullstellung** kann mehrmals aufgerufen werden. Sie können im vorigen Geschäftsjahr buchen, selbst wenn die GuV Konten Nullstellung bereits vorgenommen wurde, sofern Sie die Stapelverarbeitung erneut ausführen.

## <a name="see-also"></a>Siehe auch
[Buchabschluss](year-close-books.md)  
[Vorgehensweise: Buchen des Jahresabschlusspostens](year-how-post-year-end-close-entry.md)  
[So geht's: Ein neues Geschäftsjahr eröffnen](finance-setup-how-open-new-fiscal-year.md)


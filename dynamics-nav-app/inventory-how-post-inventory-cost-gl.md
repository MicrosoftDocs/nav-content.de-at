---
title: 'Vorgehensweise: Buchen der Lagerregulierung in die Finanzbuchhaltung'
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
ms.openlocfilehash: 59815db9c7b435ff585e1174b570029a360dea6e
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-post-inventory-costs-to-the-general-ledger"></a>Vorgehensweise: Buchen der Lagerregulierung in die Finanzbuchhaltung   
Wenn Sie Lagertransaktionen buchen, z. B. Verkaufslieferungen, Einkaufsrechnungen oder Lagerregulierungen, werden die Mengen- und die Wertänderungen in den Artikelposten bzw. in den Wertposten festgehalten. Um diese Änderung des Lagerwerts in Ihren Finanzbüchern wiederzugeben, müssen Sie Lagerkosten auf die entsprechenden Lagerkonten in der Finanzbuchhaltung buchen.

Sie können Lagerkosten in der Finanzbuchhaltung auf zwei Arten buchen:

- Automatisch, sodass die Lagerkosten jedes Mal in der Finanzbuchhaltung gebucht werden, wenn Sie eine Lagertransaktion buchen.
- Manuell, sodass Lagerkosten nur in der Finanzbuchhaltung gebucht werden, wenn Sie einen Batchauftrag ausführen.


## <a name="to-post-inventory-costs-automatically"></a>Lagerkosten automatisch buchen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Lagereinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Lagereinrichtung** das Kontrollkästchen **Automatische Lagerbuchung**.

Für jede Lagertransaktion, die Sie buchen, werden die entsprechenden Werte in der Hauptbuchhaltung im Lagerkonto, im Korrekturkonto und im Lagerverbrauchskonto gebucht.

Selbst wenn Sie mit automatischer Kostenbuchung arbeiten, müssen Sie regelmäßig den Batchauftrag Kostenanpassung – Artikelposten durchführen, um sicherzustellen, dass die Warenkosten an die entsprechenden ausgehenden Transaktionen wie Verkauf oder Umlagerung weitergeleitet werden. Dies ist insbesondere dann wichtig, wenn Sie Waren verkaufen, bevor der Kauf dieser Waren in Rechnung gestellt wurde.

Wenn ein Fehler in der Dimensionseinrichtung passiert, während Sie die Lagerkosten in der Hauptbuchhaltung zu buchen, wird der Buchungsvorgang mit einem Fehler beendet.

## <a name="to-post-inventory-costs-manually"></a>Lagerkosten manuell buchen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Lagerreg. buchen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Sie buchen eine Lagerkosten manuell in der Hauptbuchhaltung, indem Sie den Batchauftrag ausführen. Wenn Sie diesen Batchauftrag ausführen, werden auf Basis der Wertposten Hauptbuchungsposten erstellt. Sie können die Posten so buchen, dass sie pro Buchungsgruppe zusammengefasst werden.

**Hinweis**: Beim Ausführen dieses Batchauftrags können Fehler auftreten, die ihre Ursache in fehlender Einrichtung oder nicht kompatibler Dimensionseinrichtung haben. Wenn die Stapelverarbeitung auf Fehler in der Dimensionseinrichtung stößt, setzt sie diese Fehler außer Kraft und verwendet die Dimensionen des Wertpostens. Bei allen anderen Fehlern überspringt der Batchauftrag das Buchen der Wertposten und listet sie am Ende des Berichts im Abschnitt “Übersprungene Artikel” auf. Solen diese Artikel gebucht werden, müssen Sie die Fehler beheben.

Wenn Sie eine Liste der Fehler anzeigen möchten, bevor Sie den Batchauftrag ausführen, führen Sie den Bericht **Lagereinstandspreise buchen - Test** aus. In dem Testbericht werden alle gefundenen Fehler aufgelistet, die während der Testbuchung aufgetreten sind. Sie können die Fehler dann beheben und die Stapelverarbeitung zum Buchen der Lagerregulierung ausführen, ohne dass Posten übersprungen werden.

Wenn Sie sich nur einen Überblick verschaffen möchten, welche Werte in der Finanzbuchhaltung gebucht werden können, das Buchen selbst aber nicht vornehmen möchten, können Sie die Stapelverarbeitung Lagerregulierung buchen ausführen, ohne dass die Werte tatsächlich in der Finanzbuchhaltung gebucht werden. Dazu müssen Sie auf der Anforderungsseite das Häkchen im Feld Buchen entfernen. In diesem Fall wird, wenn Sie der Batchauftrag ausführen, nur der Bericht erzeugt, der die Werte enthält, die in der Hauptbuchhaltung bereit stehen, aber nicht gebucht sind.

## <a name="see-also"></a>Siehe auch
[Verwalten des Lagerbestands](inventory-manage-inventory.md)    
[Gewusst wie: Artikelpreise anpassen](inventory-how-adjust-item-costs.md)  
[Verkauf verwalten](sales-manage-sales.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)


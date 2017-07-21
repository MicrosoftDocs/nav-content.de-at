---
title: 'Gewusst wie: Artikelpreise anpassen'
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
ms.openlocfilehash: 59db38c159dd2810656edc668ee431c6414b9d90
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-adjust-item-costs"></a>Gewusst wie: Artikelpreise anpassen   
Die Kosten eines Artikels (Lagerwert), den Sie ein- und später verkaufen, ändert sich im Laufe der Nutzungsdauer, weil beispielsweise Frachtkosten dem Kaufpreis hinzugefügt werden, nachdem Sie den Artikel verkauft haben. Um immer den richtigen Lagerwert zu kennen, müssen Artikelkosten daher regelmäßig reguliert werden.
Dadurch ist sichergestellt, dass die Verkaufs- und Gewinnstatistiken auf dem neuesten Stand sind und die finanziellen Kennziffern korrekt sind.

**Hinweis**: Artikelkosten werden nur durch die FIFO-Lagerabgangsmethode reguliert. Das bedeutet, dass der Einstandspreis eines Artikels der tatsächliche Wert jedes möglichen Eingangs des Artikels ist und dass das Lager mit der Annahme validiert wird, dass die ersten Artikel im Bestand zuerst verkauft werden.

Die Kostenregulierungsfunktion verarbeitet nur Wertposten, die noch nicht reguliert wurden. Liegt eine Situation vor, in der geänderte eingehende Kosten an zugehörige ausgehende Posten weitergeleitet werden müssen, werden dafür neue Regulierungswertposten erstellt, die zwar auf den Informationen der ursprünglichen Wertposten basieren, aber den Regulierungsbetrag enthalten. Die Kostenregulierungsfunktion verwendet das Buchungsdatum des ursprünglichen Wertpostens in den Regulierungsposten, es sei denn, das Datum befindet sich in einer geschlossenen Lagerbuchungsperiode. Ist Letzteres der Fall, wird das Startdatum der nächsten offenen Lagerbuchungsperiode verwendet. Werden keine Lagerbuchungsperioden verwendet, definiert das Datum im Feld **Buchungen zugel. ab** im Fenster **Finanzbuchhaltung Einrichtung**, wann der Regulierungsposten gebucht wird.

**Hinweis**: Nachdem Artikelkosten reguliert wurden, muss die Lagerregulierung entweder automatisch oder manuell auf das Sachkonto gebucht werden. Weitere Informationen finden Sie unter [So gehts: Buchen der Lagerregulierung in die Finanzbuchhaltung](inventory-how-post-inventory-cost-gl.md).

Sie können Artikelkosten auf zwei Arten regulieren:
 - Automatisch, indem das System jede Kostenänderung beim Buchen von Lagertransaktionen reguliert.
 - Manuell, durch Ausführen der Stapelverarbeitung **Lagerreg. fakt. Einst. Preise** für einen oder mehrere Artikel, wenn Sie wissen, dass sich ihre Kosten geändert haben.  

## <a name="to-adjust-item-costs-automatically"></a>So regulieren Sie Artikelpreise automatisch
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Lagereinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Lagereinrichtung** im Feld **Automatische Lagerregulierung** einen der folgenden Werte aus.

|Option |Verhalten |
|-------|---------|
|Nie|Kosten werden beim Buchen nicht reguliert.|
|Tag|Kosten werden reguliert, wenn die Buchung innerhalb eines Tages ab dem Arbeitsdatum erfolgt.|
|Woche|Kosten werden reguliert, wenn die Buchung innerhalb einer Woche ab dem Arbeitsdatum erfolgt.|
|Monat|Kosten werden reguliert, wenn die Buchung innerhalb eines Monats ab dem Arbeitsdatum erfolgt.|
|Quartal|Kosten werden reguliert, wenn die Buchung innerhalb eines Quartals ab dem Arbeitsdatum erfolgt.|
|Jahr|Kosten werden reguliert, wenn die Buchung innerhalb eines Jahres ab dem Arbeitsdatum erfolgt.|
|Immer|Kosten werden beim Buchen immer reguliert, unabhängig vom Buchungsdatum.|

## <a name="to-adjust-item-costs-manually"></a>So regulieren Sie Artikelpreise manuell
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Lagerreg. fakt. Einst. Preise** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie im Fenster **Lagerreg. fakt. Einst. Preise** an, bei welchen Artikeln Kosten reguliert werden sollen und ob die regulierten Kosten gleichzeitig auf das Sachkonto gebucht werden sollen.

## <a name="see-also"></a>Siehe auch
[Verwalten des Lagerbestands](inventory-manage-inventory.md)  
[Vorgehensweise: Buchen der Lagerregulierung in die Finanzbuchhaltung](inventory-how-post-inventory-cost-gl.md)  
[Verkauf verwalten](sales-manage-sales.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)


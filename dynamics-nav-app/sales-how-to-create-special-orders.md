---
title: "Vorgehensweise: Spezialaufträge erstellen"
description: "Sie können einen Spezialauftrag für einen bestimmten Katalogartikel erstellen, der an einen bestimmten Kunden geliefert werden soll. Ihr Lieferant liefert den Artikel an Ihr Lager und Sie können den Artikel dann an Ihren Kunden weiterleiten, entweder unabhängig von anderen Artikeln oder zusammen mit anderen Artikeln in einem anderen Auftrag."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6460c643a07f92e478aafb84044c90ff3ed3a236
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-special-orders"></a>Vorgehensweise: Spezialaufträge erstellen
Sie können einen Spezialauftrag für einen bestimmten Katalogartikel erstellen, der an einen bestimmten Kunden geliefert werden soll. Ihr Lieferant liefert den Artikel an Ihr Lager und Sie können den Artikel dann an Ihren Kunden weiterleiten, entweder unabhängig von anderen Artikeln oder zusammen mit anderen Artikeln in einem anderen Auftrag.  

Spezialaufträge setzen voraus, dass die Bestellung und der Verkaufsauftrag verknüpft sind, um sicherzustellen, dass der bestimmte Katalogartikel entnommen und an den Debitor geliefert wird.  

Bevor Sie diese Funktion verwenden können, müssen Sie die Karten für den Debitor, den Kreditor und die Artikel in dem Auftrag erstellen.  

## <a name="to-create-a-special-order"></a>So erstellen Sie Spezialaufträge:  
1.  Alternativ wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Verkaufsauftrag** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Aktion **Neu** aus. Erstellen Sie einen  Verkaufsauftrag für den Artikel, und füllen Sie diesen aus. Weitere Informationen finden Sie unter [So geht's: Produkte verkaufen](sales-how-sell-products.md)
3.  Geben Sie auf dem Inforegister **Zeilen** die Verkaufszeile ein. Wählen Sie im Feld **Einkaufscode** einen Einkaufscode mit einem Häkchen im Feld **Spezialauftrag** aus .

    Sie müssen nun aus einem Bestellvorschlag eine Bestellung erstellen.  
4. Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen")und geben **Bestellvorschlag** ein. Wählen Sie dann den zugehörigen Link aus.  
5. Wählen Sie die Aktion **Spezialauftrag** aus, und dann die Aktion **Auftrag holen**.  
6.  Im Fenster **Aufträge holen** werden Ergebnisse angezeigt, wobei **Belegnr.** die Verkaufsauftragsnummer ist. Wählen Sie die Schaltfläche **OK** aus. Es wird eine Bestellvorschlagszeile für den Artikel erstellt.  
7.  Wählen Sie in der Bestellvorschlagszeile im Feld **Ereignismeldung** die Option **Neu** aus.  
8.  Im Fenster **Bestellauftrags-Arbeitsblatt** wählen Sie **Aktionsnachricht ausführen**. Das Fenster **Ereignismeld. durchf. - Best.** wird geöffnet. Wählen Sie die Schaltfläche **OK** aus.  

    Es erscheint eine Meldung, dass die Einkaufsbestellungen erstellt wurden. Wählen Sie die Schaltfläche **OK**.  

Eine als Spezialauftrag für einen Verkaufsauftrag erstellte Bestellung wird vom Planungssystem berücksichtigt, da es Nachfrage und Angebot ausgleicht. Die Bestellung (Angebot) bleibt also auch dann mit dem Auftrag (Nachfrage) verknüpft, wenn mit der Bestellung ein früherer Bedarf gedeckt werden könnte. Weitere Informationen finden Sie unter [Designdetails: Behandlungs-Wiederbeschaffungsverfahren](design-details-reservation-order-tracking-and-action-messaging.md).  

> [!NOTE]  
>  Sie können die Spezialauftragsfunktion nicht verwenden, wenn der Artikel bereits reserviert ist. Stellen Sie daher für Artikel, die im Rahmen von Spezialaufträgen verkauft werden, sicher, dass das Feld **Reserve** auf der Artikelkarte nicht auf **Immer** gesetzt ist.  

## <a name="see-also"></a>Siehe auch  
[So geht's: Arbeiten mit Katalogartikeln](inventory-how-work-nonstock-items.md)  
[Verkauf](sales-manage-sales.md)  
[So geht's: Direktlieferungen erstellen](sales-how-drop-shipment.md)   
[Designdetails: Wiederbeschaffungsverfahren](design-details-reservation-order-tracking-and-action-messaging.md)  
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


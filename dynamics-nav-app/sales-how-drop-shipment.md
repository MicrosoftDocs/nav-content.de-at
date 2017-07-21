---
title: 'So geht''s: Direktlieferungen erstellen'
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
ms.openlocfilehash: f636de789dc6b006a449ec59c390fab85e62b443
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-drop-shipments"></a>So geht's: Direktlieferungen erstellen
Eine Direktlieferung ist die Lieferung von Artikeln, von einem Ihrer Kreditoren direkt an einen Ihrer Debitoren.

Wenn ein Verkaufsauftrag für Direktlieferung markiert wird und Sie eine Bestellung erstellen, in der der Debitor im Feld **Verk. an Deb.-Nr.** angegeben wird, können Sie die beiden Belege verknüpfen und somit den Kreditor anweisen, direkt an den Kunden zu versenden.

## <a name="to-create-a-sales-order-for-drop-shipment"></a>So erstellen Sie einen Verkaufsauftrag für eine Direktlieferung
Um eine Direktlieferung vorzubereiten, erstellen Sie einen normalen Verkaufsauftrag für einen Artikel, außer dass Sie in der Verkaufsauftragszeile angeben müssen, dass für den Verkauf Direktlieferung benötigt wird.

1. Legen Sie einen Verkaufsauftrag für einen Artikel an. Weitere Informationen finden Sie unter [So geht's: Produkte verkaufen](sales-how-sell-products.md)
2. Aktivieren Sie in der Verkaufsauftragszeile für den Direktlieferungsartikel das Kontrollkästchen **Direktlieferung**.

## <a name="to-create-the-purchase-order-for-drop-shipment"></a>So erstellen Sie Bestellungen für Direktlieferungen:
Um eine Direktlieferung für den Artikel, der verkauft werden soll, vorzubereiten, erstellen Sie eine normale Bestellung, außer dass Sie in der Bestellung angeben müssen, dass direkt an den Debitoren geliefert wird, nicht an Sie selbst.

1. Erstellen Sie eine Bestellung. Füllen Sie keines dieser Felder in den Zeilen aus. Weitere Informationen finden Sie unter [So gehts: Erfassen eines Einkaufs](purchasing-how-record-purchases.md).
2. Wählen Sie im Feld **Verk. an Deb.-Nr.** den Debitor aus, an die Sie verkaufen.
3. Wählen Sie die Aktion **Direktlieferungen** aus, und dann die Aktion **Auftrag holen**.
4. Im Fenster **Verkaufsübersicht** wählen Sie den Auftrag, den Sie im Abschnitt "So erstellen Sie einen Verkaufsauftrag für Direktlieferung" vorbereitet haben.
5. Wählen Sie die Schaltfläche **OK** aus.

Die Zeileninformation aus dem Auftrag werden in die Bestellzeile eingetragen.

Sie können nun den Kreditor anweisen, die Artikel an Ihren Kunden zu versenden, indem Sie ihm beispielsweise die Bestellung als PDF-Datei senden.     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a>So zeigen Sie den verknüpften Auftrag aus der Bestellung an
1. Wählen Sie die Verkaufsauftragszeile der Direktlieferung aus, dann die Aktion **Bestellung**, die Aktion **Direktlieferung** und die Aktion **Bestellung**.

Die verknüpfte Bestellung wird geöffnet.

## <a name="to-post-a-drop-shipment"></a>So buchen Sie eine Direktlieferung:
Wenn der Kreditor die Artikel geliefert hat, können Sie den Verkaufsauftrag als geliefert buchen. Sie können auch die Bestellung buchen, aber nur mit der Option **Erhalten** bis der Verkaufsauftrag fakturiert wurde.
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufsaufträge** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie den Verkaufsauftrag, den Sie im Abschnitt "So erstellen Sie einen Verkaufsauftrag für Direktlieferung" erstellt haben.
3. Geben Sie im Feld **Zu liefern** an, wieviele der Bestellmengen geliefert werden sollen, die gesamte Menge oder eine Teilmenge.
3. Wählen Sie die Aktion **Buchen** oder **Buchen und Senden** aus.
4. Wählen Sie dann entweder die Option **Liefern**, um zu einem späteren Zeitpunkt zu fakturieren oder **Liefern und Fakturieren**, um sofort zu fakturieren.

## <a name="see-also"></a>Siehe auch
[Gewusst wie: Produkte verkaufen](sales-how-sell-products.md)    
[Vorgehensweise: Erfassen eines Einkaufs](purchasing-how-record-purchases.md)  
[Verkauf verwalten](sales-manage-sales.md)  
[Verwalten des Lagerbestands](inventory-manage-inventory.md)      
[Arbeiten mit Dynamics NAV](ui-work-product.md)


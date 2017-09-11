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
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="d0126-102">So geht's: Direktlieferungen erstellen</span><span class="sxs-lookup"><span data-stu-id="d0126-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="d0126-103">Eine Direktlieferung ist die Lieferung von Artikeln, von einem Ihrer Kreditoren direkt an einen Ihrer Debitoren.</span><span class="sxs-lookup"><span data-stu-id="d0126-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="d0126-104">Wenn ein Verkaufsauftrag für Direktlieferung markiert wird und Sie eine Bestellung erstellen, in der der Debitor im Feld **Verk. an Deb.-Nr.**</span><span class="sxs-lookup"><span data-stu-id="d0126-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="d0126-105">angegeben wird, können Sie die beiden Belege verknüpfen und somit den Kreditor anweisen, direkt an den Kunden zu versenden.</span><span class="sxs-lookup"><span data-stu-id="d0126-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="d0126-106">So erstellen Sie einen Verkaufsauftrag für eine Direktlieferung</span><span class="sxs-lookup"><span data-stu-id="d0126-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="d0126-107">Um eine Direktlieferung vorzubereiten, erstellen Sie einen normalen Verkaufsauftrag für einen Artikel, außer dass Sie in der Verkaufsauftragszeile angeben müssen, dass für den Verkauf Direktlieferung benötigt wird.</span><span class="sxs-lookup"><span data-stu-id="d0126-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="d0126-108">Legen Sie einen Verkaufsauftrag für einen Artikel an.</span><span class="sxs-lookup"><span data-stu-id="d0126-108">Create a sales order for an item.</span></span> <span data-ttu-id="d0126-109">Weitere Informationen finden Sie unter [So geht's: Produkte verkaufen](sales-how-sell-products.md)</span><span class="sxs-lookup"><span data-stu-id="d0126-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="d0126-110">Aktivieren Sie in der Verkaufsauftragszeile für den Direktlieferungsartikel das Kontrollkästchen **Direktlieferung**.</span><span class="sxs-lookup"><span data-stu-id="d0126-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="d0126-111">So erstellen Sie Bestellungen für Direktlieferungen:</span><span class="sxs-lookup"><span data-stu-id="d0126-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="d0126-112">Um eine Direktlieferung für den Artikel, der verkauft werden soll, vorzubereiten, erstellen Sie eine normale Bestellung, außer dass Sie in der Bestellung angeben müssen, dass direkt an den Debitoren geliefert wird, nicht an Sie selbst.</span><span class="sxs-lookup"><span data-stu-id="d0126-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="d0126-113">Erstellen Sie eine Bestellung.</span><span class="sxs-lookup"><span data-stu-id="d0126-113">Create a purchase order.</span></span> <span data-ttu-id="d0126-114">Füllen Sie keines dieser Felder in den Zeilen aus.</span><span class="sxs-lookup"><span data-stu-id="d0126-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="d0126-115">Weitere Informationen finden Sie unter [So gehts: Erfassen eines Einkaufs](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="d0126-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="d0126-116">Wählen Sie im Feld **Verk. an Deb.-Nr.**</span><span class="sxs-lookup"><span data-stu-id="d0126-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="d0126-117">den Debitor aus, an die Sie verkaufen.</span><span class="sxs-lookup"><span data-stu-id="d0126-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="d0126-118">Wählen Sie die Aktion **Direktlieferungen** aus, und dann die Aktion **Auftrag holen**.</span><span class="sxs-lookup"><span data-stu-id="d0126-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="d0126-119">Im Fenster **Verkaufsübersicht** wählen Sie den Auftrag, den Sie im Abschnitt "So erstellen Sie einen Verkaufsauftrag für Direktlieferung" vorbereitet haben.</span><span class="sxs-lookup"><span data-stu-id="d0126-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="d0126-120">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="d0126-120">Choose the **OK** button.</span></span>

<span data-ttu-id="d0126-121">Die Zeileninformation aus dem Auftrag werden in die Bestellzeile eingetragen.</span><span class="sxs-lookup"><span data-stu-id="d0126-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="d0126-122">Sie können nun den Kreditor anweisen, die Artikel an Ihren Kunden zu versenden, indem Sie ihm beispielsweise die Bestellung als PDF-Datei senden.</span><span class="sxs-lookup"><span data-stu-id="d0126-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="d0126-123">So zeigen Sie den verknüpften Auftrag aus der Bestellung an</span><span class="sxs-lookup"><span data-stu-id="d0126-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="d0126-124">Wählen Sie die Verkaufsauftragszeile der Direktlieferung aus, dann die Aktion **Bestellung**, die Aktion **Direktlieferung** und die Aktion **Bestellung**.</span><span class="sxs-lookup"><span data-stu-id="d0126-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="d0126-125">Die verknüpfte Bestellung wird geöffnet.</span><span class="sxs-lookup"><span data-stu-id="d0126-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="d0126-126">So buchen Sie eine Direktlieferung:</span><span class="sxs-lookup"><span data-stu-id="d0126-126">To post a drop shipment</span></span>
<span data-ttu-id="d0126-127">Wenn der Kreditor die Artikel geliefert hat, können Sie den Verkaufsauftrag als geliefert buchen.</span><span class="sxs-lookup"><span data-stu-id="d0126-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="d0126-128">Sie können auch die Bestellung buchen, aber nur mit der Option **Erhalten** bis der Verkaufsauftrag fakturiert wurde.</span><span class="sxs-lookup"><span data-stu-id="d0126-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="d0126-129">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufsaufträge** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="d0126-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="d0126-130">Öffnen Sie den Verkaufsauftrag, den Sie im Abschnitt "So erstellen Sie einen Verkaufsauftrag für Direktlieferung" erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="d0126-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="d0126-131">Geben Sie im Feld **Zu liefern** an, wieviele der Bestellmengen geliefert werden sollen, die gesamte Menge oder eine Teilmenge.</span><span class="sxs-lookup"><span data-stu-id="d0126-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="d0126-132">Wählen Sie die Aktion **Buchen** oder **Buchen und Senden** aus.</span><span class="sxs-lookup"><span data-stu-id="d0126-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="d0126-133">Wählen Sie dann entweder die Option **Liefern**, um zu einem späteren Zeitpunkt zu fakturieren oder **Liefern und Fakturieren**, um sofort zu fakturieren.</span><span class="sxs-lookup"><span data-stu-id="d0126-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="d0126-134">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="d0126-134">See Also</span></span>
<span data-ttu-id="d0126-135">[Gewusst wie: Produkte verkaufen](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="d0126-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="d0126-136">Vorgehensweise: Erfassen eines Einkaufs</span><span class="sxs-lookup"><span data-stu-id="d0126-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="d0126-137">Verkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="d0126-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="d0126-138">[Verwalten des Lagerbestands](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="d0126-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
[<span data-ttu-id="d0126-139">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d0126-139">Work with Dynamics NAV</span></span>](ui-work-product.md)


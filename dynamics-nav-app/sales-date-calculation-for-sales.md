---
title: "Terminberechnung für Verkäufe"
description: "Das Programm berechnet automatisch das Datum, an dem Sie einen Artikel bestellen müssen, damit er zu einem bestimmten Datum im Lagerbestand vorhanden ist. Dies ist das Datum, an dem Sie erwarten können, dass Artikel, die an einem bestimmten Datum bestellt wurden, zur Kommissionierung verfügbar sind."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: c59bfb43a43fb53309e79d6dbde1d95decf050e8
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="date-calculation-for-sales"></a><span data-ttu-id="c2e4b-104">Terminberechnung für Verkäufe</span><span class="sxs-lookup"><span data-stu-id="c2e4b-104">Date Calculation for Sales</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="c2e4b-105"> berechnet automatisch das frühestmögliche Datum, an dem ein Artikel in einer Verkaufsauftragszeile geliefert werden kann.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-105"> automatically calculates the earliest possible date that an item on a sales order line can be shipped.</span></span>

<span data-ttu-id="c2e4b-106">Wenn der Debitor ein bestimmtes Lieferdatum wünscht, wird das Datum berechnet, an dem die Artikel für die Kommissionierung zur Verfügung stehen müssen, damit dieser Liefertermin eingehalten werden kann.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-106">If the customer has requested a specific delivery date, then the date on which the items must be available to pick to meet that delivery date is calculated.</span></span>

<span data-ttu-id="c2e4b-107">Falls der Debitor kein bestimmtes Lieferdatum wünscht, wird das Datum berechnet, an dem die Artikel geliefert werden können, ausgehend von dem Datum, an dem die Artikel für die Kommissionierung zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-107">If the customer does not request a specific delivery date, then the date on which the items can be delivered is calculated, starting from the date on which the items are available for picking.</span></span>

## <a name="calculating-a-requested-delivery-date"></a><span data-ttu-id="c2e4b-108">So berechnen Sie ein gewünschtes Wareneingangsdatum:</span><span class="sxs-lookup"><span data-stu-id="c2e4b-108">Calculating a Requested Delivery Date</span></span>
<span data-ttu-id="c2e4b-109">Wenn Sie in einer Verkaufszeile ein gewünschtes Lieferdatum eingeben, wird dieses Datum als Ausgangspunkt für die folgenden Berechnungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-109">If you specify a requested delivery date on the sales order line, then that date is used as the starting point for the following calculations.</span></span>

- <span data-ttu-id="c2e4b-110">Gewünschtes Lieferdatum - Transportzeit = Geplantes Warenausgangsdatum</span><span class="sxs-lookup"><span data-stu-id="c2e4b-110">requested delivery date - shipping time = planned shipment date</span></span>
- <span data-ttu-id="c2e4b-111">Geplantes Warenausgangsdatum - Ausgeh. Lagerdurchlaufzeit = Warenausgangsdatum</span><span class="sxs-lookup"><span data-stu-id="c2e4b-111">planned shipment date - outbound whse. handling time = shipment date</span></span>

<span data-ttu-id="c2e4b-112">Falls die Artikel am Lieferdatum zur Kommissionierung zur Verfügung stehen, kann der Verkaufsvorgang fortgesetzt werden.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-112">If the items are available to pick on the shipment date, then the sales process can continue.</span></span>

<span data-ttu-id="c2e4b-113">Falls die Artikel am Lieferdatum nicht zur Kommissionierung zur Verfügung stehen, erscheint eine Warnmeldung die auf diesen Umstand hinweist.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-113">If the items are not available to be picked on the shipment date, then a stock-out warning is displayed.</span></span>

## <a name="calculating-the-earliest-possible-delivery-date"></a><span data-ttu-id="c2e4b-114">So berechnen Sie das frühestmögliche Lieferdatum:</span><span class="sxs-lookup"><span data-stu-id="c2e4b-114">Calculating the Earliest Possible Delivery Date</span></span>
<span data-ttu-id="c2e4b-115">Wenn Sie kein angefordertes Lieferdatum auf der Verkaufsauftragszeile angeben oder das angeforderte Lieferdatum nicht eingehalten werden kann, wird das früheste Datum, an dem die Artikel verfügbar sind, berechnet.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-115">If you do not specify a requested delivery date on the sales order line, or if the requested delivery date cannot be met, then the earliest date on which that the items are available is calculated.</span></span> <span data-ttu-id="c2e4b-116">Dieses Datum wird dann im Feld Versanddatum auf der Zeile eingegeben, und das Datum, an dem Sie planen, die Artikel zu liefern, sowie das Datum, an dem Sie an den Kunden ausgeliefert werden, werden anhand der nachfolgenden Formeln berechnet.</span><span class="sxs-lookup"><span data-stu-id="c2e4b-116">That date is then entered in the Shipment Date field on the line, and the date on which you plan to ship the items as well as the date on which they will be delivered to the customer are calculated using the following formulas.</span></span>

- <span data-ttu-id="c2e4b-117">Warenausgangsdatum + Ausgeh. Lagerdurchlaufzeit = Geplantes Warenausgangsdatum</span><span class="sxs-lookup"><span data-stu-id="c2e4b-117">shipment date + outbound whse. handling time = planned shipment date</span></span>
- <span data-ttu-id="c2e4b-118">Geplantes Warenausgangsdatum + Transportzeit = Geplantes Lieferdatum</span><span class="sxs-lookup"><span data-stu-id="c2e4b-118">planned shipment date + shipping time = planned delivery date</span></span>


## <a name="see-also"></a><span data-ttu-id="c2e4b-119">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="c2e4b-119">See Also</span></span>  
 <span data-ttu-id="c2e4b-120">[Terminberechnung für Einkäufe](purchasing-date-calculation-for-purchases.md) </span><span class="sxs-lookup"><span data-stu-id="c2e4b-120">[Date Calculation for Purchases](purchasing-date-calculation-for-purchases.md) </span></span>  
 [<span data-ttu-id="c2e4b-121">So wird's gemacht: Lieferterminzusagen berechnen</span><span class="sxs-lookup"><span data-stu-id="c2e4b-121">How to: Calculate Order Promising Dates</span></span>](sales-how-to-calculate-order-promising-dates.md)  
 <span data-ttu-id="c2e4b-122">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c2e4b-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


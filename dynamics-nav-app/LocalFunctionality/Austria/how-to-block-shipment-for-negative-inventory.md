---
title: Vorgehensweise beim Sperren der Lieferung bei negativem Lagerbestand
description: "Sie können ausgehende Lieferungen für einen Artikel sperren, wenn eine Transaktion zu einem negativen Lagerbestand für den betreffenden Artikel führen würde."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 8687c40202ad90e95753ceae09818160ed1ed663
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-block-shipment-for-negative-inventory"></a><span data-ttu-id="1b4c8-103">Gewusst wie: Sperren der Lieferung bei negativem Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="1b4c8-103">How to: Block Shipment for Negative Inventory</span></span>
<span data-ttu-id="1b4c8-104">Sie können ausgehende Lieferungen für einen Artikel sperren, wenn eine Transaktion zu einem negativen Lagerbestand für den betreffenden Artikel führen würde.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-104">You can block outbound shipment for an item when a transaction results in a negative inventory for that item.</span></span>  

## <a name="to-block-shipment-for-negative-inventory"></a><span data-ttu-id="1b4c8-105">So sperren Sie Lieferungen bei einem negativen Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="1b4c8-105">To block shipment for negative inventory</span></span>  

1.  <span data-ttu-id="1b4c8-106">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](../../media/ui-search/search_small.png "Symbol „Nach Seite oder Bericht suchen”"), geben Sie **Debitoren & Verkauf Einr.** ein, und wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivable Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="1b4c8-107">Aktivieren Sie im Fenster **Debitoren & Verkauf Einr.** im Inforegister **Allgemein** das Kontrollkästchen **Lief. bei neg. Lager sperren**.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-107">In the **Sales & Receivable Setup** window, on the **General** FastTab, select the **Block ship. when neg. invent.**</span></span> <span data-ttu-id="1b4c8-108">Kontrollkästchen aktivieren.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-108">check box.</span></span>  

    <span data-ttu-id="1b4c8-109">Wenn dieses Kontrollkästchen aktiviert wird, wird der Lagerbestand beim Buchen einer Verkaufslieferung für alle Artikel berechnet.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-109">When this check box is selected, the inventory for all items is calculated when you post a sales shipment.</span></span> <span data-ttu-id="1b4c8-110">Wird durch die Transaktion der Lagerbestand eines Artikels negativ, wird eine Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-110">If the transaction leads to a negative quantity in inventory for an item, an error message appears.</span></span>  

3.  <span data-ttu-id="1b4c8-111">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="1b4c8-111">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1b4c8-112">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="1b4c8-112">See Also</span></span>  
[<span data-ttu-id="1b4c8-113">Einrichten von Verkäufen</span><span class="sxs-lookup"><span data-stu-id="1b4c8-113">Setting Up Sales</span></span>](../../sales-setup-sales.md)


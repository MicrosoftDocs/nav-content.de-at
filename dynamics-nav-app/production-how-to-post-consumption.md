---
title: Vorgehensweise beim Stapelbuchen von Verbrauch
description: "Wenn die Buchungsmethode **Manuell** ist, müssen Sie den Verbrauch manuell mit einem Verbrauchsprotokoll buchen."
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
ms.openlocfilehash: 765e315a5fd1b886e9e04222a6fcfa983f2df31a
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-batch-post-production-consumption"></a><span data-ttu-id="77c23-103">So wird's gemacht: Produktionsverbrauch mit Stapelverarbeitung buchen</span><span class="sxs-lookup"><span data-stu-id="77c23-103">How to: Batch Post Production Consumption</span></span>
<span data-ttu-id="77c23-104">Wenn die Buchungsmethode **Manuell** ist, müssen Sie den Verbrauch manuell mit einem Verbrauchsprotokoll buchen.</span><span class="sxs-lookup"><span data-stu-id="77c23-104">If the flushing method is **Manual**, you must post the components manually, using a consumption journal.</span></span>

<span data-ttu-id="77c23-105">Sie können das System so einstellen, um automatisch (*flush*) Komponenten zu buchen, wenn Sie beginnen oder Fertigungsaufträge beenden.</span><span class="sxs-lookup"><span data-stu-id="77c23-105">You can also set the system up to automatically post (*flush*) components when you start or finish production orders.</span></span> <span data-ttu-id="77c23-106">Weitere Informationen finden Sie unter [Vorgehensweise: Komponenten entsprechend dem Arbeitsgangs-Ausstoß leeren](production-how-to-flush-components-according-to-operation-output.md).</span><span class="sxs-lookup"><span data-stu-id="77c23-106">For more information, see [Enable Flushing of Components According to Operation Output](production-how-to-flush-components-according-to-operation-output.md).</span></span>

## <a name="to-post-consumption-for-one-or-more-production-order-lines"></a><span data-ttu-id="77c23-107">Die Laufzeit für eine oder mehrere Verbrauchszeile buchen</span><span class="sxs-lookup"><span data-stu-id="77c23-107">To post consumption for one or more production order lines</span></span>  
1.  <span data-ttu-id="77c23-108">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen] (media/ui-search/search_small.png "Nach Seite oder Bericht suchen")und geben **Verbrauchs-Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="77c23-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Consumption Journal**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="77c23-109">Füllen Sie die Felder mit den Daten des Fertigungsauftrags und den Verbrauchsdaten aus.</span><span class="sxs-lookup"><span data-stu-id="77c23-109">Fill in the fields with the production order data and the consumption data.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    <span data-ttu-id="77c23-110">Wenn der Lagerort, an dem sich die Komponenten befinden, so eingerichtet ist, dass Lagerplätze verwendet werden, die Bearbeitung der Kommissionierung jedoch nicht erforderlich ist, dann geben Sie in der Buch.-Blattzeile einen Lagerplatz ein, um festzulegen, von welchem Lagerplatz die Artikel aus dem Lager entnommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="77c23-110">If the warehouse location where the components are stored is set up to use bins but does not require pick processing, assign a bin code to the journal line to indicate where the items should be taken from in the warehouse.</span></span> <span data-ttu-id="77c23-111">Weitere Informationen finden Sie unter [Vorgehensweise: Kommissionierung für die Produktion oder Montage](warehouse-how-to-pick-for-production.md).</span><span class="sxs-lookup"><span data-stu-id="77c23-111">For more information, see [How to: Pick for Production or Assembly](warehouse-how-to-pick-for-production.md).</span></span>  
3.  <span data-ttu-id="77c23-112">Um den Verbrauch zu buchen, wählen Sie die Aktion **Buchen** aus.</span><span class="sxs-lookup"><span data-stu-id="77c23-112">Choose the **Post** action to post the consumption.</span></span> <span data-ttu-id="77c23-113">Die verknüpften Artikelposten werden verringert.</span><span class="sxs-lookup"><span data-stu-id="77c23-113">The related item ledger entries are reduced.</span></span>

## <a name="see-also"></a><span data-ttu-id="77c23-114">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="77c23-114">See Also</span></span>  
<span data-ttu-id="77c23-115">[Produktion](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="77c23-115">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="77c23-116">Produktion einrichten</span><span class="sxs-lookup"><span data-stu-id="77c23-116">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="77c23-117">[Planung](production-planning.md)    </span><span class="sxs-lookup"><span data-stu-id="77c23-117">[Planning](production-planning.md)    </span></span>  
[<span data-ttu-id="77c23-118">Lagerbesttand</span><span class="sxs-lookup"><span data-stu-id="77c23-118">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="77c23-119">Einkauf</span><span class="sxs-lookup"><span data-stu-id="77c23-119">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="77c23-120">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="77c23-120">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


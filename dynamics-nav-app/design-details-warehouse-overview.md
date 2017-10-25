---
title: "Designdetails – Lagerübersicht"
description: "Um die physische Bewegung der Artikel auf dieser Zonen- und Lagerplatzebene zu unterstützen, müssen alle Informationen für jede Transaktion oder Umlagerung im Lager nachverfolgt werden. Dies wird in der Tabelle **Lagerplatzposten** verwaltet. Jede Transaktion wird in einem Lagerplatzjournal gespeichert."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 36fc951668580b4a74d8642a734f321312aaaab7
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-warehouse-overview"></a><span data-ttu-id="d46bd-105">Designdetails: Lagerübersicht</span><span class="sxs-lookup"><span data-stu-id="d46bd-105">Design Details: Warehouse Overview</span></span>
<span data-ttu-id="d46bd-106">Um die physische Bewegung der Artikel auf dieser Zonen- und Lagerplatzebene zu unterstützen, müssen alle Informationen für jede Transaktion oder Umlagerung im Lager nachverfolgt werden.</span><span class="sxs-lookup"><span data-stu-id="d46bd-106">To support the physical handling of items on the zone and bin level, all information must be traced for each transaction or movement in the warehouse.</span></span> <span data-ttu-id="d46bd-107">Dies wird in der Tabelle **Lagerplatzposten** verwaltet.</span><span class="sxs-lookup"><span data-stu-id="d46bd-107">This is managed in the **Warehouse Entry** table.</span></span> <span data-ttu-id="d46bd-108">Jede Transaktion wird in einem Lagerplatzjournal gespeichert.</span><span class="sxs-lookup"><span data-stu-id="d46bd-108">Each transaction is stored in a warehouse register.</span></span>  

<span data-ttu-id="d46bd-109">Logistikbelege und ein Logistik Buch.-Blatt werden verwendet, um Artikelumlagerungen im Lager zu erfassen.</span><span class="sxs-lookup"><span data-stu-id="d46bd-109">Warehouse documents and a warehouse journal are used to register item movements in the warehouse.</span></span> <span data-ttu-id="d46bd-110">Immer wenn ein Artikel im Lager umgelagert, erhalten, eingelagert, kommissioniert, geliefert oder angepasst wird, werden Lagerposten registriert, um die physischen Informationen zu Zone, Lagerplatz und Menge zu speichern.</span><span class="sxs-lookup"><span data-stu-id="d46bd-110">Every time that an item in the warehouse is moved, received, put away, picked, shipped, or adjusted, warehouse entries are registered to store the physical information about zone, bin, and quantity.</span></span> <span data-ttu-id="d46bd-111">Weitere Informationen finden Sie unter [Designdetails: Eingehender Lagerfluss](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="d46bd-111">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

<span data-ttu-id="d46bd-112">Die Tabelle **Lagerplatzinhalt** wird verwendet, um alle verschiedenen Dimensionen des Inhalts eines Lagerplatzes pro Artikel zu bearbeiten, wie etwa Mengeneinheit, Höchstmenge oder Mindestmenge.</span><span class="sxs-lookup"><span data-stu-id="d46bd-112">The **Bin Content** table is used to handle all the different dimensions of the contents of a bin per item, such as unit of measure, maximum quantity, and minimum quantity.</span></span> <span data-ttu-id="d46bd-113">Die Tabelle **Lagerplatzinhalt** enthält auch Flussfelder zu den Lagerplatzposten, Lageranweisungen und Logistik-Buch.-Blattzeilen, wodurch sichergestellt wird, dass die Verfügbarkeit eines Artikels pro Lagerplatz und eines Lagerplatzes für einen Artikel schnell berechnet werden kann.</span><span class="sxs-lookup"><span data-stu-id="d46bd-113">The **Bin Content** table also contains flow fields to the warehouse entries, warehouse instructions, and warehouse journal lines, which ensures that the availability of an item per bin and a bin for an item can be calculated quickly.</span></span> <span data-ttu-id="d46bd-114">Weitere Informationen finden Sie unter [Designdetails: Verfügbarkeit im Lager](design-details-availability-in-the-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="d46bd-114">For more information, see [Design Details: Availability in the Warehouse](design-details-availability-in-the-warehouse.md).</span></span>  

<span data-ttu-id="d46bd-115">Wenn Artikelbuchungen außerhalb des Lagermoduls auftreten, wird ein Standard-Ausgleichslagerplatz pro Lagerort verwendet, um Lagerplatzposten mit Inventurposten zu synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="d46bd-115">When item postings occur outside the warehouse module, a default adjustment bin per location is used to synchronize warehouse entries with inventory entries.</span></span> <span data-ttu-id="d46bd-116">Während der Inventur des Lagers werden jegliche Abweichungen zwischen berechneten und gezählten Mengen am Regulierungslagerplatz erfasst und dann als korrigierende Artikelposten gebucht.</span><span class="sxs-lookup"><span data-stu-id="d46bd-116">During physical inventory of the warehouse, any differences between the calculated and counted quantities are recorded in the adjustment bin and then posted as correcting item ledger entries.</span></span> <span data-ttu-id="d46bd-117">Weitere Informationen finden Sie unter [Designdetails: Bestandintegration](design-details-integration-with-inventory.md).</span><span class="sxs-lookup"><span data-stu-id="d46bd-117">For more information, see [Design Details: Integration with Inventory](design-details-integration-with-inventory.md).</span></span>  

<span data-ttu-id="d46bd-118">Die folgenden Abbildung zeigt typische Warenflüsse.</span><span class="sxs-lookup"><span data-stu-id="d46bd-118">The following illustration outlines typical warehouse flows.</span></span>  

<span data-ttu-id="d46bd-119">![Übersicht Lagerprozesse](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span><span class="sxs-lookup"><span data-stu-id="d46bd-119">![Overview of warehouse processes](media/design_details_warehouse_management_overview.png "design_details_warehouse_management_overview")</span></span>  

## <a name="basic-or-advanced-warehousing"></a><span data-ttu-id="d46bd-120">Grundlegende oder erweiterte Lagerhaltung</span><span class="sxs-lookup"><span data-stu-id="d46bd-120">Basic or Advanced Warehousing</span></span>  
<span data-ttu-id="d46bd-121">Lagerfunktionen in [!INCLUDE[d365fin](includes/d365fin_md.md)] können in unterschiedlichen Komplexitätsebenen implementiert werden, abhängig von den Prozessen eines Unternehmens und dem Auftragsvolumen.</span><span class="sxs-lookup"><span data-stu-id="d46bd-121">Warehouse functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] can be implemented in different complexity levels, depending on a company’s processes and order volume.</span></span> <span data-ttu-id="d46bd-122">Der wichtigste Unterschied besteht darin, dass Aktivitäten in der einfachen Logistik Auftrag für Auftrag durchgeführt werden, während sie in der erweiterten Logistik für mehrere Aufträge konsolidiert werden.</span><span class="sxs-lookup"><span data-stu-id="d46bd-122">The main difference is that activities are performed order-by-order in basic warehousing when they are consolidated for multiple orders in advanced warehousing.</span></span>  

 <span data-ttu-id="d46bd-123">Um zwischen den verschiedenen Komplexitätsebenen zu unterscheiden, verwendet diese Dokumentation zwei allgemeine Bezeichnungen, grundlegende und erweiterte Lagerhaltung.</span><span class="sxs-lookup"><span data-stu-id="d46bd-123">To differentiate between the different complexity levels, this documentation refers to two general denominations, Basic and Advanced Warehousing.</span></span> <span data-ttu-id="d46bd-124">Diese einfache Unterscheidung umfasst mehrere verschiedene Komplexitätsebenen, die durch definierte Produktdetails und Lagerorteinrichtung definiert sind, wobei jede durch unterschiedliche UI-Dokumente unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="d46bd-124">This simple differentiation covers several different complexity levels as defined by product granules and location setup, each supported by different UI documents.</span></span> <span data-ttu-id="d46bd-125">Weitere Informationen finden Sie unter [Designdetails: Lagerhaus einrichten](design-details-warehouse-setup.md).</span><span class="sxs-lookup"><span data-stu-id="d46bd-125">For more information, see [Design Details: Warehouse Setup](design-details-warehouse-setup.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="d46bd-126">Die höchstentwickelte Ebene der Logistik wird in dieser Dokumentation als „WMS-Installationen“ bezeichnet, da diese Methode die höchstentwickelten Elemente und Logistiksysteme erfordert.</span><span class="sxs-lookup"><span data-stu-id="d46bd-126">The most advanced level of warehousing is referred to as “WMS installations” in this documentation, since this level requires the most advanced granule, Warehouse Management Systems.</span></span>  

 <span data-ttu-id="d46bd-127">Die folgenden verschiedenen UI-Dokumente werden in der einfachen und der erweiterten Logistik verwendet.</span><span class="sxs-lookup"><span data-stu-id="d46bd-127">The following different UI documents are used in basic and advanced warehousing.</span></span>  

## <a name="basic-ui-documents"></a><span data-ttu-id="d46bd-128">Grundlegende UI-Dokumente</span><span class="sxs-lookup"><span data-stu-id="d46bd-128">Basic UI Documents</span></span>  

-   <span data-ttu-id="d46bd-129">**Lagereinlagerung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-129">**Inventory Put-away**</span></span>  
-   <span data-ttu-id="d46bd-130">**Lagerkommissionierung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-130">**Inventory Pick**</span></span>  
-   <span data-ttu-id="d46bd-131">**Lagerbewegung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-131">**Inventory Movement**</span></span>  
-   <span data-ttu-id="d46bd-132">**Artikel Buch.-Blatt**</span><span class="sxs-lookup"><span data-stu-id="d46bd-132">**Item Journal**</span></span>  
-   <span data-ttu-id="d46bd-133">**Artikel Umlag. Buch.-Blatt**</span><span class="sxs-lookup"><span data-stu-id="d46bd-133">**Item Reclassification Journal**</span></span>  
-   <span data-ttu-id="d46bd-134">(Verschiedene Berichte)</span><span class="sxs-lookup"><span data-stu-id="d46bd-134">(Various reports)</span></span>  

## <a name="advanced-ui-documents"></a><span data-ttu-id="d46bd-135">Erweiterte UI-Dokumente</span><span class="sxs-lookup"><span data-stu-id="d46bd-135">Advanced UI Documents</span></span>  

-   <span data-ttu-id="d46bd-136">**Wareneingang**</span><span class="sxs-lookup"><span data-stu-id="d46bd-136">**Warehouse Receipt**</span></span>  
-   <span data-ttu-id="d46bd-137">**Einlagerungsvorschlag**</span><span class="sxs-lookup"><span data-stu-id="d46bd-137">**Put-away Worksheet**</span></span>  
-   <span data-ttu-id="d46bd-138">**Einlagerung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-138">**Warehouse Put-away**</span></span>  
-   <span data-ttu-id="d46bd-139">**Kommissioniervorschlag**</span><span class="sxs-lookup"><span data-stu-id="d46bd-139">**Pick Worksheet**</span></span>  
-   <span data-ttu-id="d46bd-140">**Kommissionierung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-140">**Warehouse Pick**</span></span>  
-   <span data-ttu-id="d46bd-141">**Lagerplatzumlagerungsvorschlag**</span><span class="sxs-lookup"><span data-stu-id="d46bd-141">**Movement Worksheet**</span></span>  
-   <span data-ttu-id="d46bd-142">**Lagerplatzumlagerung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-142">**Warehouse Movement**</span></span>  
-   <span data-ttu-id="d46bd-143">**Interne Kommissionierung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-143">**Internal Whse. Pick**</span></span>  
-   <span data-ttu-id="d46bd-144">**Interne Einlag.-Anforderung**</span><span class="sxs-lookup"><span data-stu-id="d46bd-144">**Internal Whse. Put-away**</span></span>  
-   <span data-ttu-id="d46bd-145">**Lagerplatz Erst.-Vorschlag**</span><span class="sxs-lookup"><span data-stu-id="d46bd-145">**Bin Creation Worksheet**</span></span>  
-   <span data-ttu-id="d46bd-146">**Lagerplatzinh. Erst.-Vorschlag**</span><span class="sxs-lookup"><span data-stu-id="d46bd-146">**Bin Content Creation Worksheet**</span></span>  
-   <span data-ttu-id="d46bd-147">**Logistik Artikel Buch.-Blatt**</span><span class="sxs-lookup"><span data-stu-id="d46bd-147">**Whse. Item Journal**</span></span>  
-   <span data-ttu-id="d46bd-148">**Umlagerung Logistik Artikel Buch.-Blatt**</span><span class="sxs-lookup"><span data-stu-id="d46bd-148">**Whse. Item Reclass. Journal**</span></span>  
-   <span data-ttu-id="d46bd-149">(Verschiedene Berichte)</span><span class="sxs-lookup"><span data-stu-id="d46bd-149">(Various reports)</span></span>  

<span data-ttu-id="d46bd-150">Weitere Informationen über jeden Beleg finden Sie den entsprechenden Fensterthemen.</span><span class="sxs-lookup"><span data-stu-id="d46bd-150">For more information about each document, see the respective window topics.</span></span>  

### <a name="terminology"></a><span data-ttu-id="d46bd-151">Terminologie</span><span class="sxs-lookup"><span data-stu-id="d46bd-151">Terminology</span></span>  
<span data-ttu-id="d46bd-152">Um mit den Finanzbegriffen Einkauf und von Verkauf zu entsprechen, verwendet [!INCLUDE[d365fin](includes/d365fin_md.md)] Lagerdokumentation die folgenden Begriffe für Warenfluss im Lager.</span><span class="sxs-lookup"><span data-stu-id="d46bd-152">To align with the financial concepts of purchases and sales, [!INCLUDE[d365fin](includes/d365fin_md.md)] warehouse documentation refers to the following terms for item flow in the warehouse.</span></span>  

|<span data-ttu-id="d46bd-153">Begriff</span><span class="sxs-lookup"><span data-stu-id="d46bd-153">Term</span></span>|<span data-ttu-id="d46bd-154">Description</span><span class="sxs-lookup"><span data-stu-id="d46bd-154">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="d46bd-155">Eingehender Fluss</span><span class="sxs-lookup"><span data-stu-id="d46bd-155">Inbound flow</span></span>|<span data-ttu-id="d46bd-156">Artikel, die in den Lagerort eingehen, z.B. Einkäufe und eingehende Umlagerungen.</span><span class="sxs-lookup"><span data-stu-id="d46bd-156">Items moving into the warehouse location, such as purchases and inbound transfers.</span></span>|  
|<span data-ttu-id="d46bd-157">Interne Flüsse</span><span class="sxs-lookup"><span data-stu-id="d46bd-157">Internal flow</span></span>|<span data-ttu-id="d46bd-158">Artikel, die innerhalb des Lagerorts verschoben werden, wie z.B. Produktionskomponenten und fertiggestellte Artikel.</span><span class="sxs-lookup"><span data-stu-id="d46bd-158">Items moving inside the warehouse location, such as production components and output.</span></span>|  
|<span data-ttu-id="d46bd-159">Ausgehender Warenfluss</span><span class="sxs-lookup"><span data-stu-id="d46bd-159">Outbound flow</span></span>|<span data-ttu-id="d46bd-160">Artikel, die aus dem Lagerort ausgehen, z.B. Verkäufe und ausgehende Umlagerungen.</span><span class="sxs-lookup"><span data-stu-id="d46bd-160">Items moving out of the warehouse location, such as sales and outbound transfers.</span></span>|  

## <a name="see-also"></a><span data-ttu-id="d46bd-161">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="d46bd-161">See Also</span></span>  
 [<span data-ttu-id="d46bd-162">Designdetails: Logistik</span><span class="sxs-lookup"><span data-stu-id="d46bd-162">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)


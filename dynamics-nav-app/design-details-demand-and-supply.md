---
title: "Designdetails – Bedarf und Vorrat"
description: "Bedarf ist der Oberbegriff, der für jede Art Brutto-Bedarf verwendet wird, beispielsweise für Verkaufsauftrags und Komponentenbedarf aus einem Fertigungsauftrag. Darüber hinaus ermöglicht die Anwendung weitere technische Bedarfsarten, wie z.B. negative Lagerbestände und Einkaufsreklamationen."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 933b5518e81edb07acb84f79b19bae6c20966c16
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-demand-and-supply"></a><span data-ttu-id="6df31-104">Designdetails: Bedarf und Vorrat</span><span class="sxs-lookup"><span data-stu-id="6df31-104">Design Details: Demand and Supply</span></span>
<span data-ttu-id="6df31-105">Bedarf ist der Oberbegriff, der für jede Art Brutto-Bedarf verwendet wird, beispielsweise für Verkaufsauftrags und Komponentenbedarf aus einem Fertigungsauftrag.</span><span class="sxs-lookup"><span data-stu-id="6df31-105">Demand is the common term used for any kind of gross demand, such as a sales order and component need from a production order.</span></span> <span data-ttu-id="6df31-106">Darüber hinaus ermöglicht die Anwendung weitere technische Bedarfsarten, wie z.B. negative Lagerbestände und Einkaufsreklamationen.</span><span class="sxs-lookup"><span data-stu-id="6df31-106">In addition, the program allows more technical types of demand, such as negative inventory and purchase returns.</span></span>  
  
 <span data-ttu-id="6df31-107">Vorrat ist der allgemeine Begriff für jede Art von positiver oder eingehender Menge, wie etwa Bestands-, Einkauf-, Montage-, Fertigungs- oder eingehende Umlagerungen.</span><span class="sxs-lookup"><span data-stu-id="6df31-107">Supply is the common term used for any kind of positive or inbound quantity, such as inventory, purchases, assembly, production, or inbound transfers.</span></span> <span data-ttu-id="6df31-108">Darüber hinaus stellt möglicherweise eine Verkaufsreklamation ebenfalls einen Vorrat dar.</span><span class="sxs-lookup"><span data-stu-id="6df31-108">In addition, a sales return may also represent supply.</span></span>  
  
 <span data-ttu-id="6df31-109">Um die vielen Quellen von Nachfrage und Angebot zu sortieren, organisiert das Planungssystem sie auf zwei Zeitachsen, die Bestandsprofile genannt werden.</span><span class="sxs-lookup"><span data-stu-id="6df31-109">To sort out the many sources of demand and supply, the planning system organizes them on two time lines called inventory profiles.</span></span> <span data-ttu-id="6df31-110">Das eine Profil enthält Bedarfsereignisse und das andere enthält die entsprechenden Zubehörereignisse.</span><span class="sxs-lookup"><span data-stu-id="6df31-110">One profile holds demand events, and the other holds the corresponding supply events.</span></span> <span data-ttu-id="6df31-111">Jedes Ereignis repräsentiert eine Auftragsnetzwerkeinheit, wie etwa eine Verkaufsauftragszeile, einen Artikelposten oder eine Fertigungsauftragszeile.</span><span class="sxs-lookup"><span data-stu-id="6df31-111">Each event represents one order network entity, such as a sales order line, an item ledger entry, or a production order line.</span></span>  
  
 <span data-ttu-id="6df31-112">Wenn Bestandsprofile geladen werden, werden die verschiedenen BBedarf-Vorrat-Sätze ausgeglichen, um einen Beschaffungsplan auszustellen, der die aufgeführten Ziele erfüllt.</span><span class="sxs-lookup"><span data-stu-id="6df31-112">When inventory profiles are loaded, the different demand-supply sets are balanced to output a supply plan that fulfills the listed goals.</span></span>  
  
 <span data-ttu-id="6df31-113">Planungsparameter und Lagerbestände sind andere Arten von Bedarf und Vorrat bzw. sind einem integrierten Ausgleich unterworfen, um den Lagerbestand wieder aufzufüllen.</span><span class="sxs-lookup"><span data-stu-id="6df31-113">Planning parameters and inventory levels are other types of demand and supply respectively, which undergo integrated balancing to replenish stock items.</span></span> <span data-ttu-id="6df31-114">Weitere Informationen finden Sie unter [Designdetails: Behandlungs-Wiederbeschaffungsverfahren](design-details-handling-reordering-policies.md).</span><span class="sxs-lookup"><span data-stu-id="6df31-114">For more information, see [Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="6df31-115">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="6df31-115">See Also</span></span>  
 <span data-ttu-id="6df31-116">[Designdetails: Ausgleich von Bedarf und Vorrat](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="6df31-116">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
 <span data-ttu-id="6df31-117">[Designdetails: Zentrale Konzepte des Planungssystems](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="6df31-117">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
 [<span data-ttu-id="6df31-118">Designdetails: Vorratsplanung</span><span class="sxs-lookup"><span data-stu-id="6df31-118">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)

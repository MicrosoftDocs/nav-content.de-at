---
title: "Designdetails – Vorratsplanung"
description: Diese Dokumentation stellt einen detaillierten technischen Einblick in die Konzepte und Prinzipien bereit, die in den Beschaffungsplanungsfunktionen in [!INCLUDE[d365fin](includes/d365fin_md.md)] verwendet werden.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, planning, reordering, replenishment
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: a362452c7ee7a115751ce665e5ea6c3c96b1f27c
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-supply-planning"></a><span data-ttu-id="9a2ed-103">Designdetails: Vorratsplanung</span><span class="sxs-lookup"><span data-stu-id="9a2ed-103">Design Details: Supply Planning</span></span>
<span data-ttu-id="9a2ed-104">Diese Dokumentation stellt einen detaillierten technischen Einblick in die Konzepte und Prinzipien bereit, die in den Beschaffungsplanungsfunktionen in [!INCLUDE[d365fin](includes/d365fin_md.md)] verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9a2ed-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Supply Planning features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="9a2ed-105">Erläutert, wie das Planungssystem arbeitet und wie die Algorithmen angepasst werden, um Planungsbedingungen in verschiedenen Umgebungen zu erfüllen.</span><span class="sxs-lookup"><span data-stu-id="9a2ed-105">It explains how the planning system works and how to adjust the algorithms to meet planning requirements in different environments.</span></span> <span data-ttu-id="9a2ed-106">Stellt zuerst die zentralen Lösungskonzepte vor und beschreibt dann die Logik des zentralen Mechanismus, des Vorratsausgleichs, und erläutert dann, wie die Bestandsplanung mithilfe von Wiederbeschaffungsverfahren ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9a2ed-106">It first introduces central solution concepts and then describes the logic of the central mechanism, supply balancing, before proceeding to explain how inventory planning is performed with the use of reordering policies.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="9a2ed-107">In diesem Abschnitt</span><span class="sxs-lookup"><span data-stu-id="9a2ed-107">In This Section</span></span>  
[<span data-ttu-id="9a2ed-108">Designdetails: Zentrale Konzepte des Planungssystems</span><span class="sxs-lookup"><span data-stu-id="9a2ed-108">Design Details: Central Concepts of the Planning System</span></span>](design-details-central-concepts-of-the-planning-system.md)  
[<span data-ttu-id="9a2ed-109">Designdetails: Reservierung, Auftragsnachverfolgung und Aktionsmeldungen</span><span class="sxs-lookup"><span data-stu-id="9a2ed-109">Design Details: Reservation, Order Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
[<span data-ttu-id="9a2ed-110">Designdetails: Ausgleich von Bedarf und Vorrat</span><span class="sxs-lookup"><span data-stu-id="9a2ed-110">Design Details: Balancing Demand and Supply</span></span>](design-details-balancing-demand-and-supply.md)  
[<span data-ttu-id="9a2ed-111">Designdetails: Umgang mit Wiederbeschaffungsverfahren</span><span class="sxs-lookup"><span data-stu-id="9a2ed-111">Design Details: Handling Reordering Policies</span></span>](design-details-handling-reordering-policies.md)  
[<span data-ttu-id="9a2ed-112">Designdetails: Planungsparameter</span><span class="sxs-lookup"><span data-stu-id="9a2ed-112">Design Details: Planning Parameters</span></span>](design-details-planning-parameters.md)  
[<span data-ttu-id="9a2ed-113">Designdetails: Planungs-Zuordnungstabelle</span><span class="sxs-lookup"><span data-stu-id="9a2ed-113">Design Details: Planning Assignment Table</span></span>](design-details-planning-assignment-table.md)  
[<span data-ttu-id="9a2ed-114">Designdetails: Bedarf an leerem Lagerort</span><span class="sxs-lookup"><span data-stu-id="9a2ed-114">Design Details: Demand at Blank Location</span></span>](design-details-demand-at-blank-location.md)  
[<span data-ttu-id="9a2ed-115">Designdetails: Umlagerungen in Planung</span><span class="sxs-lookup"><span data-stu-id="9a2ed-115">Design Details: Transfers in Planning</span></span>](design-details-transfers-in-planning.md)


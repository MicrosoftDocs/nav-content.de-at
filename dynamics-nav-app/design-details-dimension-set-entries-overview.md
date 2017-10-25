---
title: "Dimensionssatz-Eintrags-Übersicht"
description: In diesem Thema wird beschrieben, wie Dimensionssatzposten in  [!INCLUDE[d365fin](includes/d365fin_md.md)].gespeichert und gebucht werden.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: dimension
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ce9459785ee39fa89baf61b2e97be41ddde661f6
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="dimension-set-entries-overview"></a><span data-ttu-id="068de-103">Dimensionssatz-Eintrags-Übersicht</span><span class="sxs-lookup"><span data-stu-id="068de-103">Dimension Set Entries Overview</span></span>
<span data-ttu-id="068de-104">In diesem Thema wird beschrieben, wie Dimensionssatzposten in [!INCLUDE[d365fin](includes/d365fin_md.md)] gespeichert und gebucht werden.</span><span class="sxs-lookup"><span data-stu-id="068de-104">This topic describes how dimension set entries are stored and posted in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
  
## <a name="dimension-sets"></a><span data-ttu-id="068de-105">Dimensionssätze</span><span class="sxs-lookup"><span data-stu-id="068de-105">Dimension Sets</span></span>  
<span data-ttu-id="068de-106">Ein Dimensionssatz ist eine eindeutige Kombination von Dimensionswerten.</span><span class="sxs-lookup"><span data-stu-id="068de-106">A dimension set is a unique combination of dimension values.</span></span> <span data-ttu-id="068de-107">Er wird als Dimensionssatzposten in die Datenbank gespeichert.</span><span class="sxs-lookup"><span data-stu-id="068de-107">It is stored as dimension set entries in the database.</span></span> <span data-ttu-id="068de-108">Jeder Dimensionssatzposten stellt einen einzelnen Dimensionswert dar.</span><span class="sxs-lookup"><span data-stu-id="068de-108">Each dimension set entry represents a single dimension value.</span></span> <span data-ttu-id="068de-109">Der Dimensionssatz wird durch eine allgemeine Dimensionssatz-ID identifiziert, die jedem Dimensionssatzposten zugewiesen wird, der zum Dimensionssatz gehört.</span><span class="sxs-lookup"><span data-stu-id="068de-109">The dimension set is identified by a common dimension set ID that is assigned to each dimension set entry that belongs to the dimension set.</span></span>  
  
<span data-ttu-id="068de-110">Im folgenden Beispiel wird ein Dimensionssatz gezeigt, der drei Dimensionssatzposten aufweist.</span><span class="sxs-lookup"><span data-stu-id="068de-110">The following example shows a dimension set that has three dimension set entries.</span></span> <span data-ttu-id="068de-111">Der Dimensionssatz wird durch eine Dimensionssatz-ID, nämlich 108, identifiziert.</span><span class="sxs-lookup"><span data-stu-id="068de-111">The dimension set is identified by a dimension set ID, which is 108.</span></span>  
  
|<span data-ttu-id="068de-112">Dimensionssatz-ID</span><span class="sxs-lookup"><span data-stu-id="068de-112">Dimension Set ID</span></span>|<span data-ttu-id="068de-113">Dimensionscode</span><span class="sxs-lookup"><span data-stu-id="068de-113">Dimension Code</span></span>|<span data-ttu-id="068de-114">Dimensionswertcode</span><span class="sxs-lookup"><span data-stu-id="068de-114">Dimension Value Code</span></span>|<span data-ttu-id="068de-115">Dimensionswertname</span><span class="sxs-lookup"><span data-stu-id="068de-115">Dimension Value Name</span></span>|  
|----------------------|--------------------|--------------------------|--------------------------|  
|<span data-ttu-id="068de-116">108</span><span class="sxs-lookup"><span data-stu-id="068de-116">108</span></span>|<span data-ttu-id="068de-117">BEREICH</span><span class="sxs-lookup"><span data-stu-id="068de-117">AREA</span></span>|<span data-ttu-id="068de-118">70</span><span class="sxs-lookup"><span data-stu-id="068de-118">70</span></span>|<span data-ttu-id="068de-119">Nordamerika</span><span class="sxs-lookup"><span data-stu-id="068de-119">America North</span></span>|  
|<span data-ttu-id="068de-120">108</span><span class="sxs-lookup"><span data-stu-id="068de-120">108</span></span>|<span data-ttu-id="068de-121">UNTERNEHMENSGRUPPE</span><span class="sxs-lookup"><span data-stu-id="068de-121">BUSINESSGROUP</span></span>|<span data-ttu-id="068de-122">POS1</span><span class="sxs-lookup"><span data-stu-id="068de-122">HOME</span></span>|<span data-ttu-id="068de-123">Start</span><span class="sxs-lookup"><span data-stu-id="068de-123">Home</span></span>|  
|<span data-ttu-id="068de-124">108</span><span class="sxs-lookup"><span data-stu-id="068de-124">108</span></span>|<span data-ttu-id="068de-125">KOSTENSTELLE</span><span class="sxs-lookup"><span data-stu-id="068de-125">DEPARTMENT</span></span>|<span data-ttu-id="068de-126">VERKAUF</span><span class="sxs-lookup"><span data-stu-id="068de-126">SALES</span></span>|<span data-ttu-id="068de-127">Verkauf</span><span class="sxs-lookup"><span data-stu-id="068de-127">Sales</span></span>|  
  
## <a name="dimension-set-entries"></a><span data-ttu-id="068de-128">Dimensionssatzposten</span><span class="sxs-lookup"><span data-stu-id="068de-128">Dimension Set Entries</span></span>  
<span data-ttu-id="068de-129">Dimensionssätze werden in der Tabelle als **Dimensionssatzposten** mit derselben Dimensionssatz-ID gespeichert.</span><span class="sxs-lookup"><span data-stu-id="068de-129">Dimension sets are stored in the **Dimension Set Entry** table as dimension set entries with the same dimension set ID.</span></span>  
  
<span data-ttu-id="068de-130">![Dimensions-Postenübersicht](media/dimensionentrynav7.png "DimensionEntryNAV7")</span><span class="sxs-lookup"><span data-stu-id="068de-130">![Dimension Entry overview](media/dimensionentrynav7.png "DimensionEntryNAV7")</span></span>  
  
<span data-ttu-id="068de-131">Wenn Sie eine neue Buch.-Blattzeile, einen Belegkopf oder eine Belegzeile erstellen, können Sie eine Kombination von Dimensionswerten angeben.</span><span class="sxs-lookup"><span data-stu-id="068de-131">When you create a new journal line, document header, or document line, you can specify a combination of dimension values.</span></span> <span data-ttu-id="068de-132">Anstatt jeden Dimensionswert explizit in der Datenbank zu speichern, wird eine Dimensionssatz-ID der Buch.-Blattzeile, dem Belegkopf oder der Belegzeile zugewiesen, um den Dimensionssatz anzugeben.</span><span class="sxs-lookup"><span data-stu-id="068de-132">Instead of explicitly storing each dimension value in the database, a dimension set ID is assigned to the journal line, document header, or document line to specify the dimension set.</span></span>  
  
<span data-ttu-id="068de-133">Wenn Sie das Fenster **Dimensionssatzeinträge bearbeiten**bearbeiten und schließen, wird eine Prüfung ausgeführt, um festzustellen, ob die Kombination aus Dimensionswerten als Dimensionssatz in der Tabelle existiert.</span><span class="sxs-lookup"><span data-stu-id="068de-133">When you edit and close the **Edit Dimension Set Entries** window, a check is performed to see whether the combination of dimension values exists as a dimension set in the table.</span></span> <span data-ttu-id="068de-134">Wenn die Kombination in der Tabelle auftritt, wird die entsprechende Dimensionssatz-ID der Buch.-Blattzeile, dem Belegkopf oder der Belegzeile zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="068de-134">If the combination occurs in the table, then the corresponding dimension set ID is assigned to the journal line, document header, or document line.</span></span> <span data-ttu-id="068de-135">Andernfalls wird ein neuer Dimensionssatz der Tabelle hinzugefügt, und die neue Dimensionssatz-ID wird der Buch.-Blattzeile, dem Belegkopf oder der Belegzeile zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="068de-135">Otherwise, a new dimension set is added to the table, and the new dimension set ID is assigned to the journal line, document header, or document line.</span></span>  
  
## <a name="performance-improvement"></a><span data-ttu-id="068de-136">Leistungsverbesserung</span><span class="sxs-lookup"><span data-stu-id="068de-136">Performance Improvement</span></span>  
<span data-ttu-id="068de-137">Durch das einmalige Speichern von Dimensionssätzen in der Datenbank wird Datenbankplatz beibehalten und die Gesamtleistung verbessert.</span><span class="sxs-lookup"><span data-stu-id="068de-137">By storing dimension sets once in the database, database space is preserved, and overall performance is improved.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="068de-138">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="068de-138">See Also</span></span>  
<span data-ttu-id="068de-139">[Designdetails: Suche nach Dimensionskombinationen](design-details-searching-for-dimension-combinations.md) </span><span class="sxs-lookup"><span data-stu-id="068de-139">[Design Details: Searching for Dimension Combinations](design-details-searching-for-dimension-combinations.md) </span></span>  
<span data-ttu-id="068de-140">[Designdetails: Tabellenstruktur](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="068de-140">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
<span data-ttu-id="068de-141">[Designdetails: Codeunit 408 Dimension Management](design-details-codeunit-408-dimension-management.md) </span><span class="sxs-lookup"><span data-stu-id="068de-141">[Design Details: Codeunit 408 Dimension Management](design-details-codeunit-408-dimension-management.md) </span></span>  
<span data-ttu-id="068de-142">[Designdetails: Codebeispiele von geänderten Mustern in Änderungen](design-details-code-examples-of-changed-patterns-in-modifications.md) </span><span class="sxs-lookup"><span data-stu-id="068de-142">[Design Details: Code Examples of Changed Patterns in Modifications](design-details-code-examples-of-changed-patterns-in-modifications.md) </span></span>  
[<span data-ttu-id="068de-143">Designdetails: Dimensionssatzposten</span><span class="sxs-lookup"><span data-stu-id="068de-143">Design Details: Dimension Set Entries</span></span>](design-details-dimension-set-entries.md)   


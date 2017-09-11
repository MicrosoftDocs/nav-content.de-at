---
title: "Vorgehensweise: Einrichten von Verkaufschancen für Verkaufsprozesse und Prozess-Stufen"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 756e9b2f33fe66cd4c2b4e26ca4390683bd087af
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---
# <a name="how-to-set-up-opportunity-sales-cycles-and-cycle-stages"></a><span data-ttu-id="6ccf0-102">Vorgehensweise: Einrichten von Verkaufschancen für Verkaufsprozesse und Prozess-Stufen</span><span class="sxs-lookup"><span data-stu-id="6ccf0-102">How to: Set Up Opportunity Sales Cycles and Cycle Stages</span></span>
<span data-ttu-id="6ccf0-103">Damit die Verkaufschancen verwendet werden kann, müssen zunächst Verkaufsprozesse sowie Verkaufsprozess-Stufen eingerichtet werden.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-103">Before you can start using sales opportunities, you must set up sales cycles and sales cycle stages.</span></span> <span data-ttu-id="6ccf0-104">Ein Verkaufsprozess setzt sich aus einer Reihe von Schritten zusammen, die vom ersten Kontakt bis zu einem Verkaufsabschluss reichen.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-104">A sales cycle is made up of a series of stages that go from the initial contact to the closing of a sale.</span></span> <span data-ttu-id="6ccf0-105">Jeder Stufe kann bestimmten Bedingungen haben, die erfüllen sein müssen (z. B. ein Verkaufsangebot), bevor eine Verkaufschance in die nächste Stufe gehen kann.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-105">Each stage can have certain requirements that must be met, such as requiring a sales quote, before an opportunity can go to the next stage.</span></span> <span data-ttu-id="6ccf0-106">Sie können auch festlegen, ob eine Stufe übersprungen werden kann.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-106">You can also specify whether a stage can be skipped.</span></span> <span data-ttu-id="6ccf0-107">Verkaufsprozesse können in beliebiger Anzahl eingerichtet werden. Gleiches gilt auch für die Anzahl der Verkaufsprozess-Stufen, die innerhalb eines Verkaufsprozesses eingerichtet werden.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-107">You can setup as many sales cycles as you need, and you can set up as many sales cycle stages as necessary within a sales cycle.</span></span>

<span data-ttu-id="6ccf0-108">Das Implementieren des Verkaufsprozesses für Verkaufschancen umfasst das Einrichten des Verkaufsprozesscodes, das Definiert der verschiedenen Stufen des Zyklus, und das Zuweisen des Zyklus zu den Verkaufschancen.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-108">Implementing opportunity sales cycles involves setting up the sales cycle code, defining the different stages of the cycle, and then assigning the cycle to opportunities.</span></span>

## <a name="to-set-up-an-opportunity-sales-cycle-code"></a><span data-ttu-id="6ccf0-109">Einrichten eines Verkaufsprozesscodes</span><span class="sxs-lookup"><span data-stu-id="6ccf0-109">To set up an opportunity sales cycle code</span></span>
1. <span data-ttu-id="6ccf0-110">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Verkaufsprozesse** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Cycles**, and then choose the related link.</span></span> <span data-ttu-id="6ccf0-111">Das **Verkaufsprozesse**-Fenster wird geöffnet und führt alle vorhandenen Verkaufsprozesse auf.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-111">The **Sales Cycles** window opens, and lists all the existing sales cycles.</span></span>
2. <span data-ttu-id="6ccf0-112">Wählen Sie Aktion **Neu** aus, und füllen Sie die Felder aus.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-112">Choose the **New** action, and fill in the fields.</span></span>

<span data-ttu-id="6ccf0-113">Wiederholen Sie diese Schritte, um weitere Verkaufsprozesse einzurichten.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-113">Repeat these steps to set up as many sales cycles as you want.</span></span> <span data-ttu-id="6ccf0-114">Nachdem Sie Verkaufsprozesse für Verkaufschancen eingerichtet haben, können Sie die verschiedenen Stufen innerhalb jedes Prozesses einrichten.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-114">After you have set up opportunity sales cycles, you may want to set up the different stages within each cycle.</span></span>

## <a name="to-define-opportunity-sales-cycle-stages"></a><span data-ttu-id="6ccf0-115">Verkaufsprozessstufe der Verkaufschance definieren</span><span class="sxs-lookup"><span data-stu-id="6ccf0-115">To define opportunity sales cycle stages</span></span>
1. <span data-ttu-id="6ccf0-116">Wählen Sie im Fenster **Verkaufsprozesse** den Verkaufsprozess für Verkaufschancen aus, für den Sie Stufen einrichten möchten, und wählen Sie dann die Aktion **Stufen**.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-116">In the **Sales Cycles** window, select the opportunity sales cycle for which you want to set up stages, and then choose the **Stages** action.</span></span> <span data-ttu-id="6ccf0-117">Das Fenster **Verkaufsprozess-Stufen** wird geöffnet.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-117">The **Sales Cycle Stages** window opens.</span></span>
2. <span data-ttu-id="6ccf0-118">Klicken Sie auf **Neu**, um eine neue Stufe für den Verkaufsprozess einzugeben.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-118">Choose the **New** action to enter a new stage in the sales cycle.</span></span>

<span data-ttu-id="6ccf0-119">Wiederholen Sie diese Schritte, um beliebig viele Stufen innerhalb des Verkaufsprozesses einzurichten.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-119">Repeat these steps to set up as many stages as you want within the sales cycle.</span></span>

## <a name="to-assign-stage-cycle-to-an-opportunity"></a><span data-ttu-id="6ccf0-120">Eine Verkaufsprozessstufe zu einer Verkaufschance zuordnen</span><span class="sxs-lookup"><span data-stu-id="6ccf0-120">To assign stage cycle to an opportunity</span></span>
<span data-ttu-id="6ccf0-121">Nachdem Sie die Stufe des Verkaufprozesses hinzugefügt haben, können Sie Verkaufschancen hinzufügen und dann die Stufe des Verkaufprozesses zu Verkaufschancen hinzufügen, indem Sie das Feld **Verkaufsprozesscode** verwenden.</span><span class="sxs-lookup"><span data-stu-id="6ccf0-121">After you add the opportunities stage cycle, you can start to add sales opportunities, and then assign the stage cycle to opportunities by setting the **Sales Cycle Code** field.</span></span> <span data-ttu-id="6ccf0-122">Weitere Informationen finden Sie unter [Gewusst wie: Erstellen von Verkaufschancen](marketing-how-create-opportunities.md).</span><span class="sxs-lookup"><span data-stu-id="6ccf0-122">For more information, see [How to: Create Sales Opportunities](marketing-how-create-opportunities.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="6ccf0-123">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="6ccf0-123">See Also</span></span>  
[<span data-ttu-id="6ccf0-124">Verarbeiten von Verkaufschancen</span><span class="sxs-lookup"><span data-stu-id="6ccf0-124">Processing Sales Opportunities</span></span>](marketing-processing-sales-opportunities.md)  
[<span data-ttu-id="6ccf0-125">Verkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="6ccf0-125">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="6ccf0-126">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6ccf0-126">Working with Dynamics NAV</span></span>](ui-work-product.md)


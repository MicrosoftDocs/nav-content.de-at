---
title: 'Vorgehensweise: Verwalten von Projektmitteln'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="44ed3-102">Vorgehensweise: Verwalten von Projektlieferungen</span><span class="sxs-lookup"><span data-stu-id="44ed3-102">How to: Manage Job Supplies</span></span>
<span data-ttu-id="44ed3-103">Die Verwaltung der Projektmittel für Artikel, Services und Aufwendungen ist ein integraler und wichtiger Bestandteil der Ausführung von Projekten.</span><span class="sxs-lookup"><span data-stu-id="44ed3-103">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="44ed3-104">Sie können entweder verfügbaren Lagerbestand verwenden oder projektspezifische Einkäufe mithilfe von Bestellungen und/oder Einkaufsrechnungen durchführen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-104">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="44ed3-105">Beispiel: Bei einem Serviceprojekt für einen Computer wird eine neue Festplatte benötigt.</span><span class="sxs-lookup"><span data-stu-id="44ed3-105">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="44ed3-106">Sie erstellen eine Einkaufsrechnung für den Kauf einer neuen Festplatte und erfassen das Projekt, für das die Festplatte verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="44ed3-106">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="44ed3-107">Falls für den Verkaufsprozess keine separate Erfassung von physischen Transaktionen erforderlich ist, kann ein Verkauf möglicherweise nur in einer Einkaufsrechnung oder im Fenster **Fibu Buch.-Blatt** verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="44ed3-107">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="44ed3-108">Weitere Informationen finden Sie unter [So gehts: Nutzung von Projekten](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="44ed3-108">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="44ed3-109">Um Artikel oder Services für ein Projekt kaufen</span><span class="sxs-lookup"><span data-stu-id="44ed3-109">To purchase items or services for a job</span></span>
<span data-ttu-id="44ed3-110">Der folgende Ablauf zeigt, wie eine Einkaufsrechnung zum Kauf von Produkten für ein Projekt verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="44ed3-110">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="44ed3-111">Die gleichen Schritte gelten auch, wenn sie eine Bestellung verwenden.</span><span class="sxs-lookup"><span data-stu-id="44ed3-111">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="44ed3-112">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einkaufsrechnungen** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="44ed3-113">Wählen Sie die Aktion **Neu** aus, und füllen Sie die Felder nach Bedarf aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-113">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="44ed3-114">Weitere Informationen finden Sie unter [So gehts: Erfassen eines Einkaufs](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="44ed3-114">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="44ed3-115">Im Feld **Projektnummer**</span><span class="sxs-lookup"><span data-stu-id="44ed3-115">In the **Job No.**</span></span> <span data-ttu-id="44ed3-116">und Feld **Projektaufgabennummer**</span><span class="sxs-lookup"><span data-stu-id="44ed3-116">and **Job Task No.**</span></span> <span data-ttu-id="44ed3-117">wählen Sie die Informationen des Projektes aus, für das Sie Artikel oder Services kaufen möchten.</span><span class="sxs-lookup"><span data-stu-id="44ed3-117">fields, select the information of the job that you want to purchase items or services for.</span></span>  

    <span data-ttu-id="44ed3-118">Den Wert, den Sie im Feld **Projektzeilenart** auswählen, definiert, ob eine Planungszeile erstellt wird, wenn Sie den Verbrauch eines Artikels buchen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-118">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="44ed3-119">Wenn das Feld **Fakturierbar** enthält, dann werden die Projektzeilen erstellt, die bereit sind, um dem Kunden in Rechnung zu stellen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-119">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="44ed3-120">Weitere Informationen finden Sie unter [Gewusst wie: Projekte fakturieren](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="44ed3-120">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>

4. <span data-ttu-id="44ed3-121">Wählen Sie die Aktion **Buchen** aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-121">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="44ed3-122">So zeigen Sie den Wert eines Kaufes für ein Projekt</span><span class="sxs-lookup"><span data-stu-id="44ed3-122">To view the value of purchases for a job</span></span>  

1. <span data-ttu-id="44ed3-123">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Projekt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="44ed3-124">Eine relevante Projektkarte öffnen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-124">Open a relevant job card.</span></span>

    <span data-ttu-id="44ed3-125">In der **Registerkarte** Inforegister zeigt das Feld **Ausstehende Bestellungen** den gesamten ausstehenden Betrag in Landeswährung, , den gesamten Lagerbestand und die Services für den Kauf von Dokumenten für die Projektaufgabenzeile.</span><span class="sxs-lookup"><span data-stu-id="44ed3-125">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="44ed3-126">Das Feld **Nicht fakturierter Lieferbetrag** zeigt den Wert der Artikel, die mit Verkaufsdokumenten geliefert aber noch nicht fakturiert wurden.</span><span class="sxs-lookup"><span data-stu-id="44ed3-126">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  

3. <span data-ttu-id="44ed3-127">Klicken Sie auf eines der Felder, um das Fenster **Verkaufszeilen** zu öffnen. In diesem Fenster können Sie Informationen aus der Bestellung nachlesen – einschließlich Informationen zu eingegangenen Artikeln oder Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-127">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="44ed3-128">Projektbezogene Aufwendung buchen</span><span class="sxs-lookup"><span data-stu-id="44ed3-128">To post a job-related expense</span></span>  
<span data-ttu-id="44ed3-129">Wenn Sie die außerordentlichen oder einmalige Projektausgaben verursachen, können Sie das Fenster **Projekt Buch.-Blatt** verwenden, um diese direkt auf das Konto des entsprechenden Projekts zu buchen.</span><span class="sxs-lookup"><span data-stu-id="44ed3-129">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="44ed3-130">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Projekt Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="44ed3-131">Erstellen Sie eine neue Zeile, und geben Sie Informationen zur Aufwendung einschließlich Informationen zur **Projektnummer.**</span><span class="sxs-lookup"><span data-stu-id="44ed3-131">Create a new line and enter information about the expense, including information in the **Job No.**</span></span> <span data-ttu-id="44ed3-132">und zur **Projektaufgabennummer** ein.</span><span class="sxs-lookup"><span data-stu-id="44ed3-132">and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="44ed3-133">Wenn der Verkaufsauftrag ausgeführt wurde, wählen Sie die Aktion **Buchen** aus.</span><span class="sxs-lookup"><span data-stu-id="44ed3-133">When the journal is complete, choose the **Post** action.</span></span>


## <a name="see-also"></a><span data-ttu-id="44ed3-134">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="44ed3-134">See Also</span></span>
[<span data-ttu-id="44ed3-135">Projekte verwalten</span><span class="sxs-lookup"><span data-stu-id="44ed3-135">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="44ed3-136">Finanzen</span><span class="sxs-lookup"><span data-stu-id="44ed3-136">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="44ed3-137">[Einkauf verwalten](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="44ed3-137">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="44ed3-138">[Verkauf verwalten](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="44ed3-138">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="44ed3-139">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="44ed3-139">Work With Dynamics NAV</span></span>](ui-work-product.md)  


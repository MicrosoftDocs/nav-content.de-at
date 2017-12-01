---
title: Lieferbenachrichtigungen
description: "Lieferbenachrichtigungen dienen dazu, überfällige Kreditorlieferungen zu verfolgen und Kreditoren an überfällige Lieferungen zu erinnern."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: da33a4b683d04669dd33e3ed715de0e91b861f23
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="delivery-reminders"></a><span data-ttu-id="cdb0f-103">Lieferbenachrichtigungen</span><span class="sxs-lookup"><span data-stu-id="cdb0f-103">Delivery Reminders</span></span>
<span data-ttu-id="cdb0f-104">Lieferbenachrichtigungen dienen dazu, überfällige Kreditorlieferungen zu verfolgen und Kreditoren an überfällige Lieferungen zu erinnern.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-104">Delivery reminders are used to track overdue vendor shipments, and to remind vendors about overdue deliveries.</span></span> <span data-ttu-id="cdb0f-105">Zur Erstellung von Lieferbenachrichtigungen müssen Sie Folgendes einrichten:</span><span class="sxs-lookup"><span data-stu-id="cdb0f-105">To create delivery reminders, you must set up the following:</span></span>  

- <span data-ttu-id="cdb0f-106">Lieferbenachrichtigungsmethoden</span><span class="sxs-lookup"><span data-stu-id="cdb0f-106">Delivery reminder terms</span></span>  

    <span data-ttu-id="cdb0f-107">Lieferbenachrichtigungsmethoden werden durch einen Code identifiziert, der Kreditoren zugewiesen werden muss.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-107">Delivery reminder terms are identified by a code that must be assigned to vendors.</span></span> <span data-ttu-id="cdb0f-108">Um mehrere Einstellungskombinationen verwenden zu können, müssen Sie jeweils für jede Einstellung getrennt einen Code festlegen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-108">To use more than one combination of settings, you must set up a code for each setting separately.</span></span> <span data-ttu-id="cdb0f-109">Sie können eine beliebige Anzahl an Lieferbenachrichtigungsmethoden einrichten.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-109">You can set up any number of delivery reminder terms.</span></span>  

- <span data-ttu-id="cdb0f-110">Lieferbenachrichtigungsstufen</span><span class="sxs-lookup"><span data-stu-id="cdb0f-110">Delivery reminder levels</span></span>  

    <span data-ttu-id="cdb0f-111">Für jede Lieferbenachrichtigungsmethode müssen gesonderte Lieferbenachrichtigungstexte festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-111">For every delivery reminder term, you must set up delivery reminder levels.</span></span> <span data-ttu-id="cdb0f-112">Diese Stufen bestimmen, wie oft Lieferbenachrichtigungen für eine bestimmte Methode erzeugt werden können.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-112">These levels determine how often delivery reminders can be created for a specific term.</span></span> <span data-ttu-id="cdb0f-113">Stufe 1 ist die erste Lieferbenachrichtigung, die Sie für eine überfällige Lieferung erstellen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-113">Level 1 is the first delivery reminder that you create for an overdue delivery.</span></span> <span data-ttu-id="cdb0f-114">Stufe 2 ist die zweite Lieferbenachrichtigung und so weiter.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-114">Level 2 is the second delivery reminder, and so on.</span></span> <span data-ttu-id="cdb0f-115">Bei der Erstellung von Lieferbenachrichtigungen wird die Anzahl der zuvor erstellten Benachrichtigungen berücksichtigt und die für die aktuelle Anzahl definierte Methode verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-115">When delivery reminders are created, the number of reminders that were created previously is considered, and the current number is used to apply terms.</span></span>  

- <span data-ttu-id="cdb0f-116">Lieferbenachrichtigungstexte</span><span class="sxs-lookup"><span data-stu-id="cdb0f-116">Delivery reminder texts messages</span></span>  

    <span data-ttu-id="cdb0f-117">Sie müssen für jede Lieferbenachrichtigungsstufe gesonderte Lieferbenachrichtigungstexte festlegen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-117">You must set up delivery reminder text messages for every delivery reminder level.</span></span> <span data-ttu-id="cdb0f-118">Es gibt zwei Arten von Lieferbenachrichtigungstexten: Vortexte und Nachtexte.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-118">There are two types of delivery reminder text messages: beginning and ending.</span></span> <span data-ttu-id="cdb0f-119">Der Vortext wird unter dem Kopf vor der Liste von Einträgen, die angemahnt werden, gedruckt.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-119">The beginning text message is printed under the header section, before the list of entries that are marked for reminder.</span></span> <span data-ttu-id="cdb0f-120">Der Nachtext wird nach dieser Liste gedruckt.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-120">The ending text message is printed after this list.</span></span>  

<span data-ttu-id="cdb0f-121">Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminder-terms-levels-and-text.md).</span><span class="sxs-lookup"><span data-stu-id="cdb0f-121">For more information, see [How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md).</span></span>  

<span data-ttu-id="cdb0f-122">Nachdem Sie die Liefermethoden eingerichtet haben, müssen Sie den Kreditoren Lieferbenachrichtigungsmethodencodes zuweisen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-122">After you have set up the delivery terms, you must assign the delivery reminder term codes to vendors.</span></span> <span data-ttu-id="cdb0f-123">Weitere Informationen finden Sie unter [Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="cdb0f-123">For more information, see [How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md).</span></span>  

<span data-ttu-id="cdb0f-124">Lieferbenachrichtigungen können manuell oder automatisch erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-124">You can create delivery reminders manually or automatically.</span></span> <span data-ttu-id="cdb0f-125">Sie können den Batchauftrag **Lieferbenachrichtigung erstellen** zum automatischen Erstellen von Lieferbenachrichtigungen nutzen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-125">You can use the **Create Delivery Reminder** batch job to create delivery reminders automatically.</span></span> <span data-ttu-id="cdb0f-126">Bei Verwendung dieses Batchauftrags können Sie die Bestellungen auswählen, für die Lieferbenachrichtigungen erstellt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-126">This batch job allows you to select the purchase orders for which delivery reminders must be created.</span></span> <span data-ttu-id="cdb0f-127">Weitere Informationen finden Sie unter [Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-issue-delivery-reminders.md).</span><span class="sxs-lookup"><span data-stu-id="cdb0f-127">For more information, see [How to: Generate Delivery Reminders](how-to-issue-delivery-reminders.md).</span></span>  

<span data-ttu-id="cdb0f-128">Sie können Dokumente auch in Bezug auf Bestell- oder Auftragspositionen verfolgen.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-128">You can also track documents in relation to purchase order lines and sales order lines.</span></span>  

[!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="cdb0f-129"> stellt die folgenden Berichte bereit:</span><span class="sxs-lookup"><span data-stu-id="cdb0f-129"> provides the following reports:</span></span>  

- <span data-ttu-id="cdb0f-130">**Reg. Lieferbenachrichtigung** – Zum Anzeigen der Lieferbenachrichtigungen für Kreditoren.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-130">**Issued Delivery Reminder** - To view the delivery reminders for vendors.</span></span>  
- <span data-ttu-id="cdb0f-131">**Lieferbenachrichtigung - Test** - Zum Überprüfen der Lieferbenachrichtigungen vor deren Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="cdb0f-131">**Delivery Reminder - Test** - To verify the delivery reminders before you issue them.</span></span>  

<span data-ttu-id="cdb0f-132">Weitere Informationen finden Sie unter [Gewusst wie: Drucken von Testberichten für Lieferbenachrichtigungen](how-to-print-test-reports-for-delivery-reminders.md).</span><span class="sxs-lookup"><span data-stu-id="cdb0f-132">For more information, see [How to: Print Test Reports for Delivery Reminders](how-to-print-test-reports-for-delivery-reminders.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="cdb0f-133">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="cdb0f-133">See Also</span></span>  
 <span data-ttu-id="cdb0f-134">[Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-set-up-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-134">[How to: Set Up Delivery Reminders](how-to-set-up-delivery-reminders.md) </span></span>  
 <span data-ttu-id="cdb0f-135">[Gewusst wie: Einrichten von Lieferbenachrichtigungsbedingungen, -stufen und -text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-135">[How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span></span>  
 <span data-ttu-id="cdb0f-136">[Gewusst wie: Zuweisen von Lieferbenachrichtigungscodes zu Kreditoren](how-to-assign-delivery-reminder-codes-to-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-136">[How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md) </span></span>  
 <span data-ttu-id="cdb0f-137">[Gewusst wie: Einrichten von Lieferbenachrichtigungen](how-to-generate-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-137">[How to: Generate Delivery Reminders](how-to-generate-delivery-reminders.md) </span></span>  
 <span data-ttu-id="cdb0f-138">[Gewusst wie: Lieferbenachrichtigungen manuell erstellen](how-to-create-delivery-reminders-manually.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-138">[How to: Create Delivery Reminders Manually](how-to-create-delivery-reminders-manually.md) </span></span>  
 <span data-ttu-id="cdb0f-139">[Gewusst wie: Lieferbenachrichtigungen ausstellen](how-to-issue-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="cdb0f-139">[How to: Issue Delivery Reminders](how-to-issue-delivery-reminders.md) </span></span>  
 [<span data-ttu-id="cdb0f-140">So drucken Sie Testberichte vor dem Registrieren von Lieferanmahnungen</span><span class="sxs-lookup"><span data-stu-id="cdb0f-140">How to: Print Test Reports for Delivery Reminders</span></span>](how-to-print-test-reports-for-delivery-reminders.md)


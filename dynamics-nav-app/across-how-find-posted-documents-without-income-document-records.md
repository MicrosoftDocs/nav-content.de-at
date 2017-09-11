---
title: 'So wird''s gemacht: Gebuchte Belege ohne Eingangsbelege finden'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: eca38d238361a9ac50aac117199fa97fbba4374f
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="99b4e-102">So wird's gemacht: Gebuchte Belege ohne Eingangsbelege finden</span><span class="sxs-lookup"><span data-stu-id="99b4e-102">How to: Find Posted Documents without Incoming Document Records</span></span>
<span data-ttu-id="99b4e-103">In den Fenstern **Kontenplan** und **Sachposten** können Sie eine Suchfunktion verwenden, um Sachposten für gebuchte Einkaufs- und Verkaufsbelege zu finden, für die keine eingehende Belegdatensätze vorhanden sind, und dann zentral eine Verknüpfung zu vorhandenen Datensätzen herstellen oder neue mit angefügten Belegdateien erstellen.</span><span class="sxs-lookup"><span data-stu-id="99b4e-103">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span>

## <a name="to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="99b4e-104">So finden Sie gebuchte Belege ohne zugehörige Eingangsbelege</span><span class="sxs-lookup"><span data-stu-id="99b4e-104">To find posted documents without incoming document records</span></span>
1. <span data-ttu-id="99b4e-105">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Kontenplan** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="99b4e-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="99b4e-106">Wählen Sie eine Zeile für ein Sachkonto aus, für dessen Sachposten Sie gebuchte Einkaufs- und Verkaufsbelege abrufen möchten, zu denen keine Eingangsbelege vorhanden sind, und wählen Sie dann die Aktion **Gebuchte Belege ohne Eingangsbeleg**.</span><span class="sxs-lookup"><span data-stu-id="99b4e-106">Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.</span></span>
3. <span data-ttu-id="99b4e-107">Alternativ wählen Sie die Aktion **Ledger Entries** aus.</span><span class="sxs-lookup"><span data-stu-id="99b4e-107">Alternatively, choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="99b4e-108">Wählen Sie im Fenster **Sachposten** die Aktion **Gebuchte Belege ohne Eingangsbelege** aus.</span><span class="sxs-lookup"><span data-stu-id="99b4e-108">In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.</span></span>

<span data-ttu-id="99b4e-109">Daraufhin wird das Fenster **Gebuchte Belege ohne Eingangsbeleg** geöffnet, dass die gebuchten Einkaufs- und Verkaufsbelege ohne zugehörige Eingangsbelege enthält, die von Sachposten auf dem Sachkonto dargestellt werden, für das Sie das Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="99b4e-109">The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for.</span></span> <span data-ttu-id="99b4e-110">Das Fenster kann maximal 1000 Zeilen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="99b4e-110">The window can show a maximum of 1000 lines.</span></span> <span data-ttu-id="99b4e-111">Standardmäßig enthält das Feld **Datumsfilter** daher einen Filter, der die Anzeige auf Einträge beschränkt, deren Buchungsdatum zwischen dem Beginn der Buchhaltungsperiode und dem Arbeitsdatum liegt.</span><span class="sxs-lookup"><span data-stu-id="99b4e-111">By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.</span></span>

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a><span data-ttu-id="99b4e-112">So verknüpfen Sie gefundene Dokumente mit vorhandenen Eingangsbelegen</span><span class="sxs-lookup"><span data-stu-id="99b4e-112">To connect found documents to existing incoming document records</span></span>
1. <span data-ttu-id="99b4e-113">Wählen Sie im Fenster **Gebuchte Belege ohne Eingangsbeleg** die Zeile für einen gebuchten Beleg aus, den Sie mit einem vorhandenen Eingangsbeleg verknüpfen möchten, und wählen Sie dann die Aktion **Eingehenden Beleg auswählen** aus.</span><span class="sxs-lookup"><span data-stu-id="99b4e-113">In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.</span></span>
2. <span data-ttu-id="99b4e-114">Wählen Sie im Fenster **Eingehende Belege** den Eingangsbeleg aus, den Sie der gefundenen Buchung zuordnen möchten, und klicken Sie anschließend auf die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="99b4e-114">In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.</span></span>
3. <span data-ttu-id="99b4e-115">Im Fenster **Gebuchte Belege ohne Eingangsbeleg** wird der gewählte Eingangsbeleg nun mit dem gebuchten Beleg verknüpft und in der InfoBox **Eingehende Belegdateien** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="99b4e-115">In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.</span></span>

<span data-ttu-id="99b4e-116">Wenn das Fenster **Eingehende Belege** keinen relevanten Eingangsbeleg-Datensatz enthält, können Sie einen erstellen.</span><span class="sxs-lookup"><span data-stu-id="99b4e-116">If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it.</span></span> <span data-ttu-id="99b4e-117">Weitere Informationen finden Sie unter [So gehts: Eingehende Dokumente erstellen](across-how-create-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="99b4e-117">For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="99b4e-118">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="99b4e-118">See Also</span></span>  
[<span data-ttu-id="99b4e-119">Eingehende Dokumente verarbeiten</span><span class="sxs-lookup"><span data-stu-id="99b4e-119">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="99b4e-120">Eingehende Belege</span><span class="sxs-lookup"><span data-stu-id="99b4e-120">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="99b4e-121">Einkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="99b4e-121">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="99b4e-122">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="99b4e-122">Work With Dynamics NAV</span></span>](ui-work-product.md)


---
title: 'Vorgehensweise: Drucken von Zahlungsanzeigen'
description: "Sie können Ihren Kreditoren helfen, Abstimmungen auszuführen, indem Sie Zahlungsanzeige ausdrucken, bevor Sie ein Buch.-Blatt buchen oder wenn Sie eine Zahlung buchen."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/26/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7c7004ac5ded9436861bf5034f59a9c2bcd99dd0
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---

#<a name="how-to-print-remittance-advice"></a><span data-ttu-id="6b0ec-103">Vorgehensweise: Drucken von Zahlungsanzeigen</span><span class="sxs-lookup"><span data-stu-id="6b0ec-103">How to: Print Remittance Advice</span></span>
<span data-ttu-id="6b0ec-104">Sie können Zahlungsanzeigen ausdrucken, bevor Sie ein Buch.-Blatt buchen oder wenn Sie eine Zahlung gebucht haben.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-104">You can print remittance advice before posting a payment journal and after posting a payment.</span></span> <span data-ttu-id="6b0ec-105">Diese Anzeige zeigt die Kreditors-Nummern an, was hilft, die Abstimmungen auszuführen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-105">This advice displays vendor invoice numbers, which helps vendors to perform reconciliations.</span></span>

##<a name="to-print-remittance-advice"></a><span data-ttu-id="6b0ec-106">Vorgehensweise: Drucken von Zahlungsanzeigen</span><span class="sxs-lookup"><span data-stu-id="6b0ec-106">To print remittance advice</span></span>
1. <span data-ttu-id="6b0ec-107">Alternativ wählen Sie in der rechten oberen Ecke das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Nach Seite oder Bericht suchen") und geben **Zahlungs-Buchblatt** ein und wählen den zugehörenden Link aus.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6b0ec-108">Im Fenster **Zahlungsausgangs Buch.-Blatt** wählen Sie die Zahlung aus, für die die Zahlungsanzeige gedruckt werden muss.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-108">In the **Payment Journal** window, select the payment for which remittance advice must be printed.</span></span>  
3. <span data-ttu-id="6b0ec-109">Wählen Sie die **Zahlungsanzeige drucken** Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-109">Choose the **Print Remittance Advice** action.</span></span>  
4. <span data-ttu-id="6b0ec-110">In der Stapelverarbeitung **Zahlungsanzeige - Buch.-Blatt** im Inforegister **Fen. Buch.-Blattzeile**, wählen Sie die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-110">In the **Remittance Advice - Journal** batch job, on the **Fen. Journal Line** FastTab, choose the appropriate filters.</span></span>  
  
    >[!Note]
    > <span data-ttu-id="6b0ec-111">Sie können anhand der externen Belegnummer des Kreditors filtern, um Zahlungen mit Rechnungen zu finden.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-111">You can filter using the vendor's external document number to match payments with invoices.</span></span>

5. <span data-ttu-id="6b0ec-112">Wählen Sie im Inforegister **Verkäufer** die entsprechenden Filter aus.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-112">On the **Vendor** FastTab, choose the appropriate filters.</span></span>  
6. <span data-ttu-id="6b0ec-113">Wählen Sie **Drucken**, um den Bericht zu drucken oder **Seitenansicht**, um den Bericht am Bildschirm anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-113">Choose **Print** to print the report, or choose **Preview** to view it now.</span></span>  

## <a name="using-remittance-advice-reports"></a><span data-ttu-id="6b0ec-114">Zahlungsanzeige-Berichte verwenden</span><span class="sxs-lookup"><span data-stu-id="6b0ec-114">Using Remittance Advice Reports</span></span>
<span data-ttu-id="6b0ec-115">Die folgende Tabelle beschreibt die Berichte, die Sie mit Zahlungsanzeigen verwenden können:</span><span class="sxs-lookup"><span data-stu-id="6b0ec-115">The following table describes the reports that you can use with remittance advice:</span></span>

|<span data-ttu-id="6b0ec-116">Bericht</span><span class="sxs-lookup"><span data-stu-id="6b0ec-116">Report</span></span>|<span data-ttu-id="6b0ec-117">Description</span><span class="sxs-lookup"><span data-stu-id="6b0ec-117">Description</span></span>|
|----|----|
|<span data-ttu-id="6b0ec-118">Rimessenavis – Buch.-Blatt-Bericht</span><span class="sxs-lookup"><span data-stu-id="6b0ec-118">Remittance Advice - Journal Report</span></span>|<span data-ttu-id="6b0ec-119">Dieser Bericht zeigt, welche Belege in der Zahlung erfasst werden.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-119">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="6b0ec-120">Für Fibu Buch.-Blattzeilen können Sie die Buch.-Blattvorlage und den Buch.-Blattname definieren, aus denen die Zahlungsanzeigen gedruckt werden, das Datum der ersten Aktivität, die gedruckt wird und den Filter auf einer Belegnummer.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-120">For general journal lines, you can specify the journal template and journal batch from which the remittance advices will be printed, the date of the first activity to print, and filter on a document number.</span></span> <span data-ttu-id="6b0ec-121">Sie können die Anzahl der Kreditoren festlegen, die in den Bericht aufgenommen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-121">For vendors, you can enter the vendor numbers to include in the report.</span></span> |
|<span data-ttu-id="6b0ec-122">Rimessenavis – Eintragsbericht</span><span class="sxs-lookup"><span data-stu-id="6b0ec-122">Remittance Advice - Entries Report</span></span>| <span data-ttu-id="6b0ec-123">Dieser Bericht zeigt, welche Belege in der Zahlung erfasst werden.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-123">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="6b0ec-124">Sie definieren die Berichtsinhalte, indem Sie Filter setzen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-124">You define the report contents by setting filters.</span></span> <span data-ttu-id="6b0ec-125">Sie können weitere Felder im Register einrichten, indem Sie das Feld **Feld** auswählen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-125">You can set additional fields on the tab by choosing the **Field** field.</span></span> <span data-ttu-id="6b0ec-126">Für Kreditorenposten können Sie die Kreditoren angeben, die im Bericht, in Datum der ersten zu druckenden Aktivität, in der Währung und der zu berücksichtigen Postennummer zu berücksichtigen sind.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-126">For vendor ledger entries, you can specify the vendors to include in the report, the date of the first activity to print, the currency, and the entry number to include.</span></span> |

> [!Note]
> <span data-ttu-id="6b0ec-127">Die Zahlungsanzeige - Buch.-Blatt-Bericht unterstützt keine Querwährungs-Anwendungsszenarien oder -Zahlungstoleranzen.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-127">The Remittance Advice - Journal Report does not support cross currency application scenarios or payment tolerances.</span></span> <span data-ttu-id="6b0ec-128">Weitere Informationen finden Sie unter [So geht's: Anwendung von Kreditorenposten in unterschiedlichen Währungen aktivieren](finance-how-enable-application-ledger-entries-different-currencies.md)</span><span class="sxs-lookup"><span data-stu-id="6b0ec-128">For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-how-enable-application-ledger-entries-different-currencies.md).</span></span>

> [!Tip]
> <span data-ttu-id="6b0ec-129">Weitere Informationen darüber, wie Sie mit Berichten arbeiten, finden Sie unter [Anzeigen von Testberichten vor dem Buchen](ui-how-view-test-reports-posting.md) [Arbeiten mit Berichten](ui-work-report.md) und [Ermitteln, Filtern und Sortieren von Daten](ui-enter-criteria-filters.md).</span><span class="sxs-lookup"><span data-stu-id="6b0ec-129">For more information about how to work with reports, see [Viewing Test Reports before Posting](ui-how-view-test-reports-posting.md), [Work with Reports](ui-work-report.md), and [Searching, Filtering, and Sorting Data](ui-enter-criteria-filters.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="6b0ec-130">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="6b0ec-130">See Also</span></span>  
[<span data-ttu-id="6b0ec-131">Willkommen bei Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6b0ec-131">Welcome to Dynamics NAV</span></span>](across-get-started.md)

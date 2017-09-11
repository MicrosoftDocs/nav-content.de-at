---
title: "Periode schließen"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a><span data-ttu-id="11f9e-102">Periode schließen</span><span class="sxs-lookup"><span data-stu-id="11f9e-102">Close Periods</span></span>
<span data-ttu-id="11f9e-103">Die Anwendung zwingt Sie nicht dazu Perioden abzuschließen, aber es gibt viele Aktivitäten am Ende der Periode (Monatsende), die in der Anwendung ausgeführt werden können, wenn Sie möchten.</span><span class="sxs-lookup"><span data-stu-id="11f9e-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="11f9e-104">Dieses Thema enthält eine Übersicht dieser Prozesse und Aktivitäten, die für Ihren Mandanten möglicherweise erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="11f9e-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="11f9e-105">Sachposten</span><span class="sxs-lookup"><span data-stu-id="11f9e-105">General Ledger</span></span>
* <span data-ttu-id="11f9e-106">Geben Sie systemweite und benutzerspezifische Buchungsdatumsbereiche an.</span><span class="sxs-lookup"><span data-stu-id="11f9e-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="11f9e-107">Dies gibt die Daten an, zwischen denen Buchungen zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="11f9e-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="11f9e-108">Je nach Geschäftsanforderungen empfiehlt es sich, die Buchungsdatumsbereiche für Benutzer zu Beginn des Periodenabschlusses einzugrenzen.</span><span class="sxs-lookup"><span data-stu-id="11f9e-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="11f9e-109">Weitere Informationen finden Sie unter [Vorgehensweise: Abschließen von Buchhaltungsperioden](finance-setup-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="11f9e-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="11f9e-110">Führen Sie alle notwendigen Sachpostenregulierungen durch.</span><span class="sxs-lookup"><span data-stu-id="11f9e-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="11f9e-111">Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter.</span><span class="sxs-lookup"><span data-stu-id="11f9e-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="11f9e-112">Führen Sie Kontenschemata wie folgt aus:</span><span class="sxs-lookup"><span data-stu-id="11f9e-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="11f9e-113">Öffnen Sie das Fenster **Kontenschema** und klicken Sie auf **Drucken**.</span><span class="sxs-lookup"><span data-stu-id="11f9e-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="11f9e-114">Füllen Sie das Fenster **Kontenschema** aus und klicken Sie auf **Drucken**.</span><span class="sxs-lookup"><span data-stu-id="11f9e-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="11f9e-115">Debitoren & Verkauf</span><span class="sxs-lookup"><span data-stu-id="11f9e-115">Sales & Receivables</span></span>
* <span data-ttu-id="11f9e-116">Alle Aufträge, Rechnungen, Gutschriften und Reklamationen werden gebucht.</span><span class="sxs-lookup"><span data-stu-id="11f9e-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="11f9e-117">Buchen Sie alle Barzahlungseingangs-Buch.-Blätter.</span><span class="sxs-lookup"><span data-stu-id="11f9e-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="11f9e-118">Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Debitoren und Verkauf beziehen.</span><span class="sxs-lookup"><span data-stu-id="11f9e-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="11f9e-119">Stimmen Sie die Debitoren mit der Finanzbuchhaltung ab.</span><span class="sxs-lookup"><span data-stu-id="11f9e-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="11f9e-120">Führen Sie die Stapelverarbeitung **Fakturierte Aufträge löschen** aus.</span><span class="sxs-lookup"><span data-stu-id="11f9e-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="11f9e-121">Kreditoren & Einkauf</span><span class="sxs-lookup"><span data-stu-id="11f9e-121">Purchases & Payables</span></span>
* <span data-ttu-id="11f9e-122">Alle Aufträge, Rechnungen, Gutschriften und Reklamationen für Kreditoren werden gebucht.</span><span class="sxs-lookup"><span data-stu-id="11f9e-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="11f9e-123">Buchen Sie das Zahlungsausgangs Buch.-Blatt.</span><span class="sxs-lookup"><span data-stu-id="11f9e-123">Post all payment journals.</span></span>
* <span data-ttu-id="11f9e-124">Aktualisieren und buchen Sie wiederkehrende Buch.-Blätter, die sich auf Kreditoren und Einkäufe beziehen.</span><span class="sxs-lookup"><span data-stu-id="11f9e-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="11f9e-125">Führen Sie den Bericht **Kreditor - Saldenrückblick** aus, und stimmen Sie die Kreditoren mit der Finanzbuchhaltung ab.</span><span class="sxs-lookup"><span data-stu-id="11f9e-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="11f9e-126">Führen Sie die Stapelverarbeitung **Erledigte fakturierte Bestellungen löschen** aus.</span><span class="sxs-lookup"><span data-stu-id="11f9e-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="11f9e-127">Berechnen und erfassen Sie die MwSt.</span><span class="sxs-lookup"><span data-stu-id="11f9e-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="11f9e-128">Schließen Sie Steuer-Abrechnungen ab.</span><span class="sxs-lookup"><span data-stu-id="11f9e-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="11f9e-129">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="11f9e-129">See Also</span></span>
[<span data-ttu-id="11f9e-130">Beenden von Jahresabschluss und Perioden</span><span class="sxs-lookup"><span data-stu-id="11f9e-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="11f9e-131">Buchabschluss</span><span class="sxs-lookup"><span data-stu-id="11f9e-131">Close Books</span></span>](year-close-books.md)


---
title: 'Vorgehensweise: Lohntransaktion importieren '
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d5e70a0a1659c7facdeec3f0971eda43ff8a03cc
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="486b2-102">Vorgehensweise: Lohntransaktion importieren </span><span class="sxs-lookup"><span data-stu-id="486b2-102">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="486b2-103">Um Gehaltszahlungen und verwandte Transaktionen zu berücksichtigen, müssen Sie die Gehaltstransaktionen importieren und finanzielle Transaktionen buchen, die durch Ihr Gehaltsabrechnungsanbieter in die Finanzbuchhaltung gebucht werden.</span><span class="sxs-lookup"><span data-stu-id="486b2-103">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="486b2-104">Hierzu importieren Sie zuerst eine csv.</span><span class="sxs-lookup"><span data-stu-id="486b2-104">To do this, you first import a csv.</span></span> <span data-ttu-id="486b2-105">Datei, die Sie vom Gehaltsabrechnungsanbieter erhalten in das Fenster **Fibur Buch.Blatt**.</span><span class="sxs-lookup"><span data-stu-id="486b2-105">file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="486b2-106">Anschließend ordnen Sie die externen Konten in der Gehaltsabrechnungsdatei den jeweiligen Sachkonten zu.</span><span class="sxs-lookup"><span data-stu-id="486b2-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="486b2-107">Zuletzt buchen Sie die Gehaltsabrechnungstransaktionen entsprechend der Kontozuordnung.</span><span class="sxs-lookup"><span data-stu-id="486b2-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="486b2-108">Um eine Lohndatei zu importieren</span><span class="sxs-lookup"><span data-stu-id="486b2-108">To import a payroll file</span></span>
1. <span data-ttu-id="486b2-109">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="486b2-109">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="486b2-110">Wählen Sie im relevanten Fibu Buch.-Blattname die Aktion **Gehaltsabrechnungstransaktionen importieren** aus.</span><span class="sxs-lookup"><span data-stu-id="486b2-110">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span>
3. <span data-ttu-id="486b2-111">Wählen Sie im Fenster **Importieren** die entsprechende Lohndatei aus und wählen sie dann die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="486b2-111">In the **Import** window, select the relevant payroll file, and then choose the **OK** button.</span></span> <span data-ttu-id="486b2-112">Die Datei muss im CSV-Format sein.</span><span class="sxs-lookup"><span data-stu-id="486b2-112">The file must be in CSV format.</span></span> 
4. <span data-ttu-id="486b2-113">Befolgen Sie die Schritte im Fenster **Gehaltsabrechnungstransaktionen importieren**, um die Transaktionen zu importieren und die Konten zuzuordnen und wählen Sie dann die Schaltfläche **Beenden**.</span><span class="sxs-lookup"><span data-stu-id="486b2-113">Follow the steps in the **Import Payroll Transactions** window to import transactions and map accounts, and then choose the **Finish** button.</span></span>

    <span data-ttu-id="486b2-114">Das Fibu Buch-Blatt wird mit den Zeilen aufgefüllt, die Transaktionen darstellen, die die Gehaltsabrechnungsdatei und die relevanten Konten in der Spalte **Sachkonto** enthält.</span><span class="sxs-lookup"><span data-stu-id="486b2-114">The general journal is filled with lines representing the transactions that the payroll file contains and with the relevant accounts in the **G/L Account** column.</span></span>
4. <span data-ttu-id="486b2-115">Bearbeiten oder buchen Sie die Buch.-Blattzeilen für andere Finanzbuchhaltungstransaktionen.</span><span class="sxs-lookup"><span data-stu-id="486b2-115">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="486b2-116">Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="486b2-116">For more information, see [How to: Work With General Journals](ui-work-general-journals.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="486b2-117">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="486b2-117">See Also</span></span>
[<span data-ttu-id="486b2-118">Finanzen</span><span class="sxs-lookup"><span data-stu-id="486b2-118">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="486b2-119">Vorgehensweise: Arbiet mit n mit Fibu-Buch.-Blättern</span><span class="sxs-lookup"><span data-stu-id="486b2-119">How to: Work With General Journals</span></span>](ui-work-general-journals.md)  


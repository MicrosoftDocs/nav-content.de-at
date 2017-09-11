---
title: 'So gehts: Arbeiten mit Schecks'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="bc582-102">So gehts: Arbeiten mit Schecks</span><span class="sxs-lookup"><span data-stu-id="bc582-102">How to: Work With Checks</span></span>
<span data-ttu-id="bc582-103">Dynamics NAV unterstützt die elektronische und die manuelle Scheckausstellung.</span><span class="sxs-lookup"><span data-stu-id="bc582-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="bc582-104">Bei beiden Verfahren erfolgt die Ausstellung von Schecks an Kreditoren über das Zahlungsausgangs-Buch.-Blatt.</span><span class="sxs-lookup"><span data-stu-id="bc582-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="bc582-105">Sie können auch Schecks annullieren und Scheckposten anzeigen.</span><span class="sxs-lookup"><span data-stu-id="bc582-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="bc582-106">Bei dem Verfahren zum Ausstellen von Schecks werden Zahlungsvorschläge gemacht, Scheckposten erstellt und die Computerschecks gedruckt.</span><span class="sxs-lookup"><span data-stu-id="bc582-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="bc582-107">Der Drucker muss für den Ausdruck von Scheckformularen eingerichtet werden, und Sie müssen festlegen welches Layout verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="bc582-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="bc582-108">Weitere Informationen zum Definieren von Attributen finden Sie unter [So gehts: Definieren von Scheck-Layouts](finance-setup-how-define-check-layouts.md).</span><span class="sxs-lookup"><span data-stu-id="bc582-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="bc582-109">Um Schecks auszustellen</span><span class="sxs-lookup"><span data-stu-id="bc582-109">To issue checks</span></span>
1. <span data-ttu-id="bc582-110">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Zahlung Buch.-Blätter** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="bc582-111">Füllen Sie das Buch.-Blatt mit den entsprechenden Zahlungen aus, z. B. indem Sie die Zahlungsvorschläge verwenden.</span><span class="sxs-lookup"><span data-stu-id="bc582-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="bc582-112">Weitere Informationen finden Sie unter [Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="bc582-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="bc582-113">Im Feld **Bankkontozahlungsart** der Buch.-Blattzeilen zur Zahlung, die Sie mit Schecks vornehmen möchten, wählen Sie eine der folgenden Optionen:</span><span class="sxs-lookup"><span data-stu-id="bc582-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="bc582-114">**Computer Scheck**: Wählen Sie diese Option, wenn Sie einen Scheck über den in der Buch.-Blattzeile angezeigten Betrag drucken wollen.</span><span class="sxs-lookup"><span data-stu-id="bc582-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="bc582-115">Sie müssen die Schecks drucken, bevor Sie die Buch.-Blattzeilen buchen können.</span><span class="sxs-lookup"><span data-stu-id="bc582-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="bc582-116">Sie können **Computer Scheck** nur auswählen, wenn **Gegenkontoart** oder **Kontoart** den Wert **Bankkonto** hat.</span><span class="sxs-lookup"><span data-stu-id="bc582-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="bc582-117">**Manueller Scheck**: Wählen Sie diese Option, wenn Sie einen Scheck manuell ausstellen und einen entsprechenden Scheckposten über diesen Betrag anlegen möchten.</span><span class="sxs-lookup"><span data-stu-id="bc582-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="bc582-118">Mit dieser Option ist das automatische Drucken von Schecks in Dynamics NAV nicht möglich.</span><span class="sxs-lookup"><span data-stu-id="bc582-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="bc582-119">Sie können **Manueller Scheck** nur auswählen, wenn **Gegenkontoart** oder **Kontoart** den Wert **Bankkonto** hat.</span><span class="sxs-lookup"><span data-stu-id="bc582-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="bc582-120">**Hinweis**: Sie müssen die Computer Schecks drucken, bevor Sie die entsprechenden Buch.-Blattzeilen buchen können.</span><span class="sxs-lookup"><span data-stu-id="bc582-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="bc582-121">Im Falle von Computer Schecks wählen Sie **Scheck drucken** aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="bc582-122">Füllen Sie im Fenster **Check** die Felder wie benötigt aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="bc582-123">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="bc582-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="bc582-124">Wählen Sie die Schaltfläche **Drucken** aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-124">Choose the **Print** button.</span></span>

<span data-ttu-id="bc582-125">**Hinweis**: Wenn Sie Schecks in mehreren Währungen von mehreren Bankkonten aus ausdrucken möchten, muss die Stapelverarbeitung **Scheck drucken** für jede einzelne Währung ausgeführt und das entsprechende Bankkonto muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="bc582-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="bc582-126">So stornieren Sie gedruckte Schecks, die nicht gebucht wurden</span><span class="sxs-lookup"><span data-stu-id="bc582-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="bc582-127">Sie können nicht gebuchte Schecks stornieren, nachdem sie gedruckt wurden, indem Sie die Aktion **Scheck annullieren** im Fenster **Zahlungsausgangs Buch.-Blatt** verwenden.</span><span class="sxs-lookup"><span data-stu-id="bc582-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="bc582-128">Wählen Sie im Fenster **Zahlungsausgangs Buch.-Blatt** **Scheck annullieren** aus, und wählen Sie aus, welche Prüfungen durchgeführt zum stornieren mit den Schecks durchgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="bc582-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="bc582-129">Annullieren von Schecks</span><span class="sxs-lookup"><span data-stu-id="bc582-129">To void checks</span></span>
<span data-ttu-id="bc582-130">Wenn Scheckzahlung gebucht wurden, können Sie Schecks aus den resultierenden Bankposten nur stornieren (annulieren).</span><span class="sxs-lookup"><span data-stu-id="bc582-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="bc582-131">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="bc582-132">Wählen Sie das entsprechende Bankkonto aus, wählen Sie die **Bearbeiten**-Aktion aus, und wählen Sie dann die **Scheckposten**-Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="bc582-133">Im **Scheckposten**-Fenster wählen Sie die **Scheck annullieren**-Aktion aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="bc582-134">Wählen das Kontrollkästchen **Scheck nur annullieren**.</span><span class="sxs-lookup"><span data-stu-id="bc582-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="bc582-135">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="bc582-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="bc582-136">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="bc582-136">See Also</span></span>
[<span data-ttu-id="bc582-137">Verwalten von Verbindlichkeiten</span><span class="sxs-lookup"><span data-stu-id="bc582-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="bc582-138">Bank einrichten</span><span class="sxs-lookup"><span data-stu-id="bc582-138">Set Up Banking</span></span>](bank-setup-banking.md)  


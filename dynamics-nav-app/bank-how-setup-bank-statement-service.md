---
title: 'Gewusst wie: Einrichten des Envestnet Yodlee Bank-Feed-Service'
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
ms.openlocfilehash: 63d0a895b6f98a250ea5cbd73ee62187f25f92f6
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-the-envestnet-yodlee-bank-feeds-service"></a><span data-ttu-id="affc2-102">Gewusst wie: Einrichten des Envestnet Yodlee Bank-Feed-Service</span><span class="sxs-lookup"><span data-stu-id="affc2-102">How to: Set Up the Envestnet Yodlee Bank Feeds Service</span></span>
<span data-ttu-id="affc2-103">Sie können elektronische Bankauszüge von Ihrer Bank importieren, um das Fenster **Zahlungsabstimmungsbuch.-Blatt** schnell auszufüllen und so Zahlungen zu begleichen und das Bankkonto auszugleichen.</span><span class="sxs-lookup"><span data-stu-id="affc2-103">You can import electronic bank statements from your bank to quickly fill in the **Payment Reconciliation Journal** window so you can apply payments and reconcile the bank account.</span></span> <span data-ttu-id="affc2-104">Weitere Informationen finden Sie unter [Zahlungen automatisch vornehmen und Bankkonten abstimmen](receivables-apply-payments-auto-reconcile-bank-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="affc2-104">For more information, see [Apply Payments Automatically and Reconcile Bank Accounts](receivables-apply-payments-auto-reconcile-bank-accounts.md).</span></span>

<span data-ttu-id="affc2-105">**Notiz**: Der Bank-Feed-Service Envestnet Yodlee oder ein anderer Bankfeeddienstservice Anbieters stehen möglicherweise nicht in der Anwendung zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="affc2-105">**Note**: The Envestnet Yodlee Bank Feeds service, or anther provider's bank feed service, may not be available in your system.</span></span> <span data-ttu-id="affc2-106">Erkundigen Sie sich beim zuständigen Microsoft-Partner, wenn Sie einen Bankfeeddienst verwenden möchten, um Bankkontoauszüge zu importieren.</span><span class="sxs-lookup"><span data-stu-id="affc2-106">Contact your Microsoft partner if you want to use a bank feed service to import bank statements.</span></span>

<span data-ttu-id="affc2-107">Wenn Sie den Bankfeeddienst aktiviert haben, müssen Sie das beteiligte Bankkonto mit dem Onlinebankkonto verknüpfen, von dem der Feed stammt.</span><span class="sxs-lookup"><span data-stu-id="affc2-107">When you have enabled the bank feed service, you must link the involved bank account to the online bank account that the feed will come from.</span></span> <span data-ttu-id="affc2-108">In den folgenden unterschiedlichen Szenarios verknüpfen Sie Bankkonten mit Onlinebankkonten:</span><span class="sxs-lookup"><span data-stu-id="affc2-108">You link bank accounts to online bank accounts in the following different scenarios:</span></span>

- <span data-ttu-id="affc2-109">Im Dynamics NAV ist kein Bankkonto für Ihr Onlinebankkonto vorhanden.</span><span class="sxs-lookup"><span data-stu-id="affc2-109">A bank account does not exist in Dynamics NAV for your online bank account.</span></span> <span data-ttu-id="affc2-110">Daher erstellen Sie das Bankkonto über eine Verknüpfung mit dem Onlinebankkonto.</span><span class="sxs-lookup"><span data-stu-id="affc2-110">Therefore, you create the bank account by linking from the online bank account.</span></span>
- <span data-ttu-id="affc2-111">In Dynamics NAV ist bereits ein Bankkonto vorhanden, das Sie mit einem Onlinebankkonto verknüpfen möchten.</span><span class="sxs-lookup"><span data-stu-id="affc2-111">A bank account exists in Dynamics NAV, which you want to link to an online bank account.</span></span>
- <span data-ttu-id="affc2-112">Bei einem verknüpften Bankkonto muss die Verknüpfung entfernt werden, da Sie den Bankfeeddienst für dieses Konto beenden möchten.</span><span class="sxs-lookup"><span data-stu-id="affc2-112">A linked bank account must be unlinked because you want to stop using the bank feed service for the account.</span></span>
- <span data-ttu-id="affc2-113">Die Onlinebankkonten haben geändert und Sie möchten die Informationen zu den Bankkonten in Dynamics NAV aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="affc2-113">Online bank accounts have changed and you want to update the information on bank accounts in Dynamics NAV.</span></span>

<span data-ttu-id="affc2-114">Wenn der Bankfeeddienst aktiviert ist, können Sie ein Bankkonto so einrichten, dass automatisch alle zwei Stunden neue Bankauszüge in das Fenster **Zahlungsabstimmungsbuch.-Blatt** importiert werden.</span><span class="sxs-lookup"><span data-stu-id="affc2-114">When the bank feed service is enabled, you can set a bank account up to automatically import new bank statements into the **Payment Reconciliation Journal** window every two hour.</span></span> <span data-ttu-id="affc2-115">Transaktionen für Zahlungen, die bereits als ausgeführt und/oder abgestimmt im Fenster **Zahlungsabstimmungsbuch.-Blatt** gebucht wurden, werden nicht importiert.</span><span class="sxs-lookup"><span data-stu-id="affc2-115">Transactions for payments that have already been posted as applied and/or reconciled in the **Payment Reconciliation Journal** window will not be imported.</span></span> <span data-ttu-id="affc2-116">Weitere Informationen finden Sie im Abschnitt “So aktivieren Sie das automatische Importieren von Bankauszügen”.</span><span class="sxs-lookup"><span data-stu-id="affc2-116">For more information, see the “To enable automatic import of bank statements” section.</span></span>

<span data-ttu-id="affc2-117">**Hinweis**: Wenn Sie unterstützte Einrichtung über "Unternehmen einrichten", werden einige der folgenden Schritte automatisch beim Einrichten von Unternehmensbankkonten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="affc2-117">**Note**: If you use the Set Up Company assisted setup, then some of the steps in the following procedures will be performed automatically when you get to the company bank account setup.</span></span> <span data-ttu-id="affc2-118">Weitere Informationen finden Sie unter [Willkommen bei Dynamics NAV](across-get-started.md).</span><span class="sxs-lookup"><span data-stu-id="affc2-118">For more information, see [Welcome to Dynamics NAV](across-get-started.md).</span></span>

## <a name="to-enable-the-bank-feed-service"></a><span data-ttu-id="affc2-119">So aktivieren Sie den Bankfeeddienst</span><span class="sxs-lookup"><span data-stu-id="affc2-119">To enable the bank feed service</span></span>
1. <span data-ttu-id="affc2-120">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-120">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="affc2-121">Öffnen Sie das Bankkonto, das Sie für den Bankfeeddienst verwenden werden.</span><span class="sxs-lookup"><span data-stu-id="affc2-121">Open the bank account that you will use for the bank feed service.</span></span>
3. <span data-ttu-id="affc2-122">Wählen Sie im Fenster **Bankkonto** im Feld **Format Bankauszugimport** YODLEEBANKFEED aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-122">In the **Bank Account** window, in the **Bank Statement Import Format** field, select YODLEEBANKFEED.</span></span>  

<span data-ttu-id="affc2-123">Der Bankfeeddienst wird aktiviert, wenn Sie ein Bankkonto mit den dazugehörigen Onlinebankkonto verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="affc2-123">The bank feed service will be enabled when you link a bank account to its related online bank account.</span></span> <span data-ttu-id="affc2-124">Siehe das folgende Verfahren.</span><span class="sxs-lookup"><span data-stu-id="affc2-124">See the next procedure.</span></span>  

## <a name="to-create-a-new-linked-bank-account"></a><span data-ttu-id="affc2-125">So erstellen Sie ein neues verknüpftes Bankkonto</span><span class="sxs-lookup"><span data-stu-id="affc2-125">To create a new linked bank account</span></span>
1. <span data-ttu-id="affc2-126">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="affc2-127">Wählen Sie das entsprechende Bankkonto aus, und wählen Sie dann **Neues verknüpftes Bankkonto erstellen**.</span><span class="sxs-lookup"><span data-stu-id="affc2-127">Select the relevant bank account, and then choose the **Create New Linked Bank Account**.</span></span> <span data-ttu-id="affc2-128">Das Fenster **Bankkontenverknüpfung** wird nach wenigen Augenblicken geöffnet.</span><span class="sxs-lookup"><span data-stu-id="affc2-128">The **Bank Account Linking** window opens after a few moments.</span></span>

    <span data-ttu-id="affc2-129">**Hinweis**: Dieses Fenster zeigt die tatsächliche Webseite des Bankfeeddienstes Envestnet Yodlee an.</span><span class="sxs-lookup"><span data-stu-id="affc2-129">**Note**: This window shows the actual web page of the Envestnet Yodlee Bank Feeds service.</span></span> <span data-ttu-id="affc2-130">Die Terminologie und die Funktionen im Fenster weichen möglicherweise von den Anweisungen ab, die in diesem Thema bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="affc2-130">Terminology and functionality in the window may not match instructions provided in this topic.</span></span>  
3. <span data-ttu-id="affc2-131">Verwenden Sie die Suchfunktion im Fenster **Onlinebankkonto-Verknüpfung** im Bereich **Konto verknüpfen**, um die Bank zu suchen, bei der Sie ein oder mehrere Onlinebankkonten haben.</span><span class="sxs-lookup"><span data-stu-id="affc2-131">In the **Online Bank Account Linking** window, in the **Link Account** pane, use the Search function to find the bank where you have one or more online bank accounts.</span></span>
4. <span data-ttu-id="affc2-132">Wählen Sie den Banknamen aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-132">Choose the bank name.</span></span> <span data-ttu-id="affc2-133">Der Bereich **Anmeldung** wird geöffnet.</span><span class="sxs-lookup"><span data-stu-id="affc2-133">The **Log In** pane opens.</span></span>
5. <span data-ttu-id="affc2-134">Geben Sie den Benutzernamen und das Kennwort, das Sie für die Ameldung bei der Onlinebank verwenden, an, und wählen Sie dann die Schaltfläche **Weiter** .</span><span class="sxs-lookup"><span data-stu-id="affc2-134">Enter the username and password that you use to log on to the online bank, and then choose the **Next** button.</span></span>  
6. <span data-ttu-id="affc2-135">Der Bankfeeddienst bereitet die Verknüpfung des ersten Onlinebankkontos der angegebenen Bank mit einem neuen Bankkonto in Dynamics NAV vor.</span><span class="sxs-lookup"><span data-stu-id="affc2-135">The bank feed service prepares to link the first online bank account at the specified bank to a new bank account in Dynamics NAV.</span></span>

    <span data-ttu-id="affc2-136">**Hinweis**: Wenn Sie mehr als ein Onlinebankkonto bei der Bank haben, müssen Sie für alle zusätzlichen Onlinebankkonten weitere Bankkonten in Dynamics NAV erstellen.</span><span class="sxs-lookup"><span data-stu-id="affc2-136">**Note**: If you have more than one online bank account at the bank, you must create additional bank accounts in Dynamics NAV for those additional online bank accounts.</span></span> <span data-ttu-id="affc2-137">Siehe Schritte 8 bis 10.</span><span class="sxs-lookup"><span data-stu-id="affc2-137">See steps 8 through 10.</span></span>

    <span data-ttu-id="affc2-138">Wenn der Prozess erfolgreich abgeschlossen ist, erscheint der Bankname im Bereich **Meine Konten** der Registerkarte **Verknüpft** .</span><span class="sxs-lookup"><span data-stu-id="affc2-138">When the process has completed successfully, the bank name will appear in the **My Accounts** pane on the **Linked** tab.</span></span> <span data-ttu-id="affc2-139">Die Nummer in Klammern gibt an, wie viele Onlinebankkonten verknüpft wurden.</span><span class="sxs-lookup"><span data-stu-id="affc2-139">The number in brackets indicates how many online bank accounts were linked.</span></span>
7. <span data-ttu-id="affc2-140">Wählen Sie die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="affc2-140">Choose the **OK** button.</span></span>

    <span data-ttu-id="affc2-141">Wenn nur ein Onlinebankkonto verknüpft ist, wird das Fenster **Bankkontokarte** für ein neues Bankkonto geöffnet und der Name des Onlinebankkontos ist bereits eingefügt.</span><span class="sxs-lookup"><span data-stu-id="affc2-141">If only one online bank account is linked, the **Bank Account Card** window for a new bank account opens, prefilled with the name of the online bank account.</span></span> <span data-ttu-id="affc2-142">In diesem Fall ist die Bankkontoverknüpfung abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="affc2-142">In this case, the bank account linking task is completed.</span></span> <span data-ttu-id="affc2-143">Jetzt müssen Sie nur noch das Bankkonto einrichten.</span><span class="sxs-lookup"><span data-stu-id="affc2-143">All that remains is to set up the bank account.</span></span> <span data-ttu-id="affc2-144">Weitere Informationen finden Sie unter [So gehts: Einrichten von Bankkonten](bank-how-setup-bank-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="affc2-144">For more information, see [How to: Set Up Bank Accounts](bank-how-setup-bank-accounts.md).</span></span>

    <span data-ttu-id="affc2-145">Wenn mehr als ein Onlinebankkonto verknüpft wurde, öffnet sich das Fenster **Bankkontenverknüpfung** und die zusätzlichen Onlinebankkonten, die nicht mit den Bankkonten in Dynamics NAV verknüpft sind, werden aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="affc2-145">If more than one online bank accounts were linked, the **Bank Account Linking** window opens listing the additional online bank accounts that are not linked to bank accounts in Dynamics NAV yet.</span></span> <span data-ttu-id="affc2-146">In diesem Fall, folgen Sie dem nächsten Schritt.</span><span class="sxs-lookup"><span data-stu-id="affc2-146">In that case, follow the next step.</span></span>  
8. <span data-ttu-id="affc2-147">Wählen Sie im Fenster **Bankkontenverknüpfung** die Zeile für ein Onlinebankkonto aus, und wählen Sie dann die Aktion **Mit neuem Onlinebankkonto verknüpfen**.</span><span class="sxs-lookup"><span data-stu-id="affc2-147">In the **Bank Account Linking** window, select the line for an online bank account, and then choose the **Link to New Bank Account** action.</span></span>

    <span data-ttu-id="affc2-148">Das Fenster **Bankkontokarte** wird für ein neues Bankkonto geöffnet und der Name des Onlinebankkontos ist bereits eingefügt.</span><span class="sxs-lookup"><span data-stu-id="affc2-148">The **Bank Account Card** window for a new bank account opens, prefilled with the name of the online bank account.</span></span>

    <span data-ttu-id="affc2-149">Wenn in Dynamics NAV bereits ein Bankkonto vorhanden ist, mit dem Sie das zusätzliche Onlinebankkonto verknüpfen möchten, folgen Sie dem nächsten Schritt.</span><span class="sxs-lookup"><span data-stu-id="affc2-149">If a bank account already exists in Dynamics NAV that you want to link the additional online bank account to, follow the next step.</span></span>  
9. <span data-ttu-id="affc2-150">Wählen Sie im Fenster **Bankkontenverknüpfung** die Zeile für ein Onlinebankkonto aus, und wählen Sie dann die Aktion **Mit vorhandenem Onlinebankkonto verknüpfen**.</span><span class="sxs-lookup"><span data-stu-id="affc2-150">In the **Bank Account Linking** window, select the line for an online bank account, and then choose the **Link to Existing Bank Account** action.</span></span>
10. <span data-ttu-id="affc2-151">Wählen Sie im Fenster **Bankkontenübersicht** das Bankkonto aus, mit dem Sie eine Verknüpfung erstellen möchten, und klicken Sie anschließend auf **OK**.</span><span class="sxs-lookup"><span data-stu-id="affc2-151">In the **Bank Account List** window, select the bank account that you want to link to, and then choose the **OK** button.</span></span>

## <a name="to-link-a-bank-account-to-an-online-bank-account"></a><span data-ttu-id="affc2-152">So verknüpfen Sie ein Bankkonto mit einem Onlinebankkonto</span><span class="sxs-lookup"><span data-stu-id="affc2-152">To link a bank account to an online bank account</span></span>
1. <span data-ttu-id="affc2-153">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-153">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="affc2-154">Wählen Sie die Zeile des Bankkontos aus, das nicht mit einem Onlinebankkonto verknüpft ist, und wählen Sie dann die Aktion **Verknüpfen mit Onlinebankkonto** .</span><span class="sxs-lookup"><span data-stu-id="affc2-154">Select the line for a bank account that is not linked to an online bank account, and then choose the **Link to Online Bank Account** action.</span></span> <span data-ttu-id="affc2-155">Das Fenster **Onlinebankkonto-Verknüpfung** wird für ein neues Bankkonto geöffnet und der Name des Onlinebankkontos ist bereits im Bereich **Konto verknüpfen** eingefügt.</span><span class="sxs-lookup"><span data-stu-id="affc2-155">The **Online Bank Account Linking** window opens with the name of the bank prefilled in the **Link Account** pane.</span></span>
3. <span data-ttu-id="affc2-156">Wählen Sie den Banknamen aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-156">Choose the bank name.</span></span> <span data-ttu-id="affc2-157">Der Bereich **Anmeldung** wird geöffnet.</span><span class="sxs-lookup"><span data-stu-id="affc2-157">The **Log In** pane opens.</span></span>
4. <span data-ttu-id="affc2-158">Geben Sie den Benutzernamen und das Kennwort, das Sie für die Ameldung bei der Onlinebank verwenden, an, und wählen Sie dann die Schaltfläche **Weiter** .</span><span class="sxs-lookup"><span data-stu-id="affc2-158">Enter the username and password that you use to log on to the online bank, and then choose the **Next** button.</span></span>

    <span data-ttu-id="affc2-159">Der Bankfeeddienst bereitet die Verknüpfung Ihres Bankkontos in Dynamics NAV mit dem entsprechenden Onlinebankkonto vor.</span><span class="sxs-lookup"><span data-stu-id="affc2-159">The bank feed service prepares to link your bank account in Dynamics NAV to the related online bank account.</span></span>

    <span data-ttu-id="affc2-160">Wenn der Prozess erfolgreich abgeschlossen ist, erscheint der Bankname im Bereich **Meine Konten** der Registerkarte **Verknüpft** .</span><span class="sxs-lookup"><span data-stu-id="affc2-160">When the process has completed successfully, the bank name will appear in the **My Accounts** pane on the **Linked** tab.</span></span> <span data-ttu-id="affc2-161">Wenn die Bank mehr als ein Bankkonto hat, wird nur das Bankkonto, das Sie in Schritt 2 ausgewählt haben, verknüpft.</span><span class="sxs-lookup"><span data-stu-id="affc2-161">If the bank has more than one bank account, only the bank account that you selected in step 2 is linked.</span></span>
5. <span data-ttu-id="affc2-162">Wählen Sie die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="affc2-162">Choose the **OK** button.</span></span>

<span data-ttu-id="affc2-163">Im Fenster **Bankkontenübersicht** ist das Kontrollkästchen **Verknüpft** aktiviert.</span><span class="sxs-lookup"><span data-stu-id="affc2-163">In the **Bank Account List** window, the **Linked** check box is selected.</span></span>

## <a name="to-unlink-a-bank-account"></a><span data-ttu-id="affc2-164">So heben Sie die Verknüpfung mit dem Bankkonto auf</span><span class="sxs-lookup"><span data-stu-id="affc2-164">To unlink a bank account</span></span>
1. <span data-ttu-id="affc2-165">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-165">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="affc2-166">Wählen Sie die Zeile des verknüpften Bankkontos aus, dessen Verknüpfung mit einem Onlinebankkonto aufgehoben werden soll, und wählen Sie dann die Aktion **Verknüpfung mit Onlinebankkonto aufheben**.</span><span class="sxs-lookup"><span data-stu-id="affc2-166">Select the line for a linked bank account that you want to unlink from its related online bank account, and the choose the **Unlink Online Bank Account** action.</span></span>

<span data-ttu-id="affc2-167">**Hinweis**: Wenn Sie **Ja** im Bestätigungsdialogfeld auswählen, wird die Verknüpfung mit dem Onlinebankkonto entfernt und die Anmeldedaten gelöscht.</span><span class="sxs-lookup"><span data-stu-id="affc2-167">**Note**: If you choose **Yes** on the confirmation dialog, the link to the online bank account is removed, and the log-in details are cleared.</span></span> <span data-ttu-id="affc2-168">Um das Bankkonto wieder mit dem Onlinebankkonto zu verknüpfen, müssen Sie sich erneut bei der Bank anmelden.</span><span class="sxs-lookup"><span data-stu-id="affc2-168">To link the bank account to the online bank account again, you must log on to the bank again.</span></span> <span data-ttu-id="affc2-169">Weitere Informationen finden Sie im Abschnitt “So verknüpfen Sie ein Bankkonto mit einem Onlinebankkonto“.</span><span class="sxs-lookup"><span data-stu-id="affc2-169">For more information, see the “To link a bank account to an online bank account“ section.</span></span>

## <a name="to-update-bank-account-linking"></a><span data-ttu-id="affc2-170">So aktualisieren Sie die Bankkontoverknüpfung</span><span class="sxs-lookup"><span data-stu-id="affc2-170">To update bank account linking</span></span>
1. <span data-ttu-id="affc2-171">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-171">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="affc2-172">Wählen Sie das entsprechende Bankkonto aus, und wählen Sie dann die Aktion **Bankkontoverknüpfung aktualisieren**.</span><span class="sxs-lookup"><span data-stu-id="affc2-172">Select the relevant bank account, and then choose the **Update Bank Account Linking** action.</span></span>

<span data-ttu-id="affc2-173">Wenn Probleme für ein oder mehrere der verknüpften Bankkonten im Fenster **Bankkontenübersicht** vorhanden sind, wird das Fenster **Bankkontenverknüpfung** geöffnet und zeigt an, welche der Bankkonten Probleme haben.</span><span class="sxs-lookup"><span data-stu-id="affc2-173">If issues exist for any of the linked bank accounts in the **Bank Account List** window, the **Bank Account Linking** window opens specifying which bank accounts have issues.</span></span> <span data-ttu-id="affc2-174">Probleme werden am besten gelöst, indem sie die Verknüpfung mit dem Onlinebankkonto entfernen und dann die Verknüpfung neu erstellen.</span><span class="sxs-lookup"><span data-stu-id="affc2-174">Issues can best be resolved by unlinking the online bank account and then re-creating the link.</span></span> <span data-ttu-id="affc2-175">Weitere Informationen finden Sie im Abschnitt “So verknüpfen Sie ein Bankkonto mit einem Onlinebankkonto“.</span><span class="sxs-lookup"><span data-stu-id="affc2-175">For more information, see the “To link a bank account to an online bank account“ section.</span></span>

## <a name="to-enable-automatic-import-of-bank-statements"></a><span data-ttu-id="affc2-176">So aktivieren Sie das automatische Importieren von Bankauszügen</span><span class="sxs-lookup"><span data-stu-id="affc2-176">To enable automatic import of bank statements</span></span>
1. <span data-ttu-id="affc2-177">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Bankkonten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-177">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="affc2-178">Wählen Sie die Zeile für ein verknüpftes Bankkonto aus, und wählen Sie dann die Aktion **Setup für automatischen Bankauszugsimport** aus.</span><span class="sxs-lookup"><span data-stu-id="affc2-178">Select the line for a linked bank account, and then choose the **Automatic Bank Statement Import Setup** action.</span></span>
3. <span data-ttu-id="affc2-179">Geben Sie im Fenster **Setup für automatischen Bankauszugsimport** im Feld **Anzahl der inbegriffenen Tage** an, für wie weit zurück Sie neue Banktransaktionen erhalten.</span><span class="sxs-lookup"><span data-stu-id="affc2-179">In the **Automatic Bank Statement Import Setup** window, in the **Number of Days Included** field, specify how far back in time to get new bank transactions for.</span></span>

    <span data-ttu-id="affc2-180">**Hinweis**: Es wird empfohlen diesen Wert auf 7 Tage oder mehr festzulegen.</span><span class="sxs-lookup"><span data-stu-id="affc2-180">**Note**: It is recommended that you set this value to 7 days or more.</span></span>
4. <span data-ttu-id="affc2-181">Aktivieren Sie das Kontrollkästchen **Aktiviert**.</span><span class="sxs-lookup"><span data-stu-id="affc2-181">Select the **Enabled** check box.</span></span>  
<span data-ttu-id="affc2-182">Jede Stunde wird das Fenster **Zahlungsabstimmungsbuch.-Blatt** jetzt mit allen neuen Zahlungen ausgefüllt, die auf dem Onlinebankkonto getätigt wurden.</span><span class="sxs-lookup"><span data-stu-id="affc2-182">Every hour, the **Payment Reconciliation Journal** window will now be filled with any new payments that are made on the online bank account.</span></span>

<span data-ttu-id="affc2-183">**Hinweis**: Transaktionen für Zahlungen, die bereits als ausgeführt und/oder abgestimmt im Fenster **Zahlungsabstimmungsbuch.-Blatt** gebucht wurden, werden nicht importiert.</span><span class="sxs-lookup"><span data-stu-id="affc2-183">**Note**: Transactions for payments that have already been posted as applied and/or reconciled in the **Payment Reconciliation Journal** window will not be imported.</span></span>

## <a name="see-also"></a><span data-ttu-id="affc2-184">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="affc2-184">See Also</span></span>  
[<span data-ttu-id="affc2-185">Bank einrichten</span><span class="sxs-lookup"><span data-stu-id="affc2-185">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="affc2-186">Verwalten von Bankkonten</span><span class="sxs-lookup"><span data-stu-id="affc2-186">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="affc2-187">Zahlungen automatisch vornehmen und Bankkonten abstimmen</span><span class="sxs-lookup"><span data-stu-id="affc2-187">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)  
[<span data-ttu-id="affc2-188">Anpassen des Dynamics NAV mithilfe der Erweiterungen </span><span class="sxs-lookup"><span data-stu-id="affc2-188">Customizing Dynamics NAV Using Extensions </span></span>](ui-extensions.md)

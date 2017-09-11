---
title: 'Vorgehensweise: Erstellen von Eingangsbelegen'
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
ms.openlocfilehash: e91c4570ff60d991974ac6afd16ba3bc3e73e44f
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="6e644-102">Vorgehensweise: Erstellen von Eingangsbelegen</span><span class="sxs-lookup"><span data-stu-id="6e644-102">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="6e644-103">Im Fenster **Eingehende Dokumente** können Sie verschiedene Funktionen zum Überprüfen von Ausgabenbelegen, Verwalten von OCR-Aufgaben und Konvertieren eingehender Belege, manuell oder automatisch, in den entsprechenden Belegen oder Buch.-Blattzeilen verwenden.</span><span class="sxs-lookup"><span data-stu-id="6e644-103">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="6e644-104">Die externen Dateien können jeder Prozessphase zugeordnet werden, auch gebuchten Belegen und den resultierenden Kreditoren-, Debitoren- und Sachposten.</span><span class="sxs-lookup"><span data-stu-id="6e644-104">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="6e644-105">Um einen externen Beleg in Dynamics NAV aufzuzeichnen, müssen Sie zuerst einen Datensatz des eingehenden Belegdatensatzes anlegen oder ausfüllen.</span><span class="sxs-lookup"><span data-stu-id="6e644-105">To record an external document in Dynamics NAV, you must first create or complete an incoming document record.</span></span> <span data-ttu-id="6e644-106">Dies kann manuell erfolgen, oder Sie können ein Foto des externen Belegs machen und einen Eingangsbelegsdatensatz mit der angehängten Bilddatei erstellen.</span><span class="sxs-lookup"><span data-stu-id="6e644-106">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="6e644-107">Bevor Sie die Funktion für Eingangsbelege verwenden können, müssen Sie sie entsprechend einrichten.</span><span class="sxs-lookup"><span data-stu-id="6e644-107">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="6e644-108">Weitere Informationen finden Sie unter [So gehts: Einrichten von eingehenden Belegen](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="6e644-108">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="6e644-109">So können Sie einen eingehenden Beleg genehmigen oder ablehnen</span><span class="sxs-lookup"><span data-stu-id="6e644-109">To approve or reject an incoming document</span></span>
<span data-ttu-id="6e644-110">Wenn Sie wünschen, dass Benutzer Rechnungen oder Hauptjournalzeilen aus Eingangsbelegen nur dann erstellen dürfen, wenn diese genehmigt sind, können Sie Genehmiger einrichten, die alle Belege genehmigen müssen, bevor sie verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="6e644-110">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="6e644-111">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Eingehende Belege** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="6e644-112">Wählen Sie die Zeile mit dem Beleg, den Sie genehmigen oder ablehnen möchten, und wählen Sie dann die Aktion **Genehmigen** oder **Ablehnen** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-112">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="6e644-113">Das Kontrollkästchen **Freigegeben** in der Zeile für den Eingangsbeleg ist aktiviert, wenn dieser genehmigt wurde.</span><span class="sxs-lookup"><span data-stu-id="6e644-113">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="6e644-114">Der jeweilige Benutzer, beispielsweise der für das Erstellen von Einkaufsrechnungen zuständige, kann dann fortfahren, den Datensatz zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="6e644-114">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="6e644-115">So erstellen Sie Eingangsbelegdatensätze indem Sie ein Foto machen</span><span class="sxs-lookup"><span data-stu-id="6e644-115">To create an incoming document record by taking a photo</span></span>
<span data-ttu-id="6e644-116">**Hinweis**: Der folgende Vorgang gilt nur für Dynamics NAV-Tablet- und Smarpthone-Clients.</span><span class="sxs-lookup"><span data-stu-id="6e644-116">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="6e644-117">Wählen Sie auf der App-Leiste die Kachel **Erstellen von eingehendem Beleg von Kamera**, und wechseln Sie dann zu Schritt 4.</span><span class="sxs-lookup"><span data-stu-id="6e644-117">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="6e644-118">Wählen Sie alternativ in er Anwendungsleiste die Optionsschaltfläche aus, wählen Sie **Eingehende Belege** und wählen Sie dann **Alle** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-118">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="6e644-119">Verwenden Sie im Fenster **Eingehende Belege** die Auslassungspunkt-Schaltfläche, und wählen Sie dann **Von Kamera erstellen** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-119">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="6e644-120">Die Kamera im Tablet oder dem Smartphone wird aktiviert.</span><span class="sxs-lookup"><span data-stu-id="6e644-120">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="6e644-121">Nehmen Sie ein Foto eines Belegs, wie einer Einkaufsquittung, die Sie als eingehender Beleg bearbeiten wollen, und wählen Sie dann die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="6e644-121">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="6e644-122">Ein neuer Datensatz für den eingehenden Beleg wird erstellt und das Bild wird angehängt.</span><span class="sxs-lookup"><span data-stu-id="6e644-122">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="6e644-123">So hängen Sie ein Bild an ein Eingangsbelegdatensatz an, indem Sie ein Foto machen</span><span class="sxs-lookup"><span data-stu-id="6e644-123">To attach an image to an incoming document record by taking a photo</span></span>
<span data-ttu-id="6e644-124">**Hinweis**: Der folgende Vorgang gilt nur für Dynamics NAV-Tablet- und Smarpthone-Clients.</span><span class="sxs-lookup"><span data-stu-id="6e644-124">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="6e644-125">Wählen Sie auf der App-Leiste die Optionsschaltfläche aus, wählen Sie **Eingehende Belege** und wählen Sie dann **Alle** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-125">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="6e644-126">Öffnen Sie die Karte eines vorhandenen eingehenden Belegsdatensatzes.</span><span class="sxs-lookup"><span data-stu-id="6e644-126">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="6e644-127">Verwenden Sie im Fenster **Eingehende Belege** die Auslassungspunkt-Schaltfläche, und wählen Sie dann **Bild von Kamera anhängen** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-127">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="6e644-128">Die Kamera im Tablet oder dem Smartphone wird aktiviert.</span><span class="sxs-lookup"><span data-stu-id="6e644-128">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="6e644-129">Nehmen Sie ein Foto eines Belegs, wie einer Einkaufsquittung, die Sie als eingehender Beleg bearbeiten wollen, und wählen Sie dann die Schaltfläche **OK**.</span><span class="sxs-lookup"><span data-stu-id="6e644-129">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="6e644-130">Das Bild wurde dem Datensatz des eingehenden Beleges angehängt.</span><span class="sxs-lookup"><span data-stu-id="6e644-130">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="6e644-131">Eingangsbelege manuell erstellen</span><span class="sxs-lookup"><span data-stu-id="6e644-131">To create an incoming document record manually</span></span>
1. <span data-ttu-id="6e644-132">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Eingehende Belege** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-132">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="6e644-133">Wählen Sie die Aktion **Aus Datei erstellen** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-133">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="6e644-134">Wählen Sie im Fenster **Datei einfügen** eine Datei aus und wählen Sie dann **Offen** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-134">In the **Insert File** window, select a file, and then choose **Open**.</span></span>

    <span data-ttu-id="6e644-135">Die Datei wird automatisch angehängt.</span><span class="sxs-lookup"><span data-stu-id="6e644-135">The file is automatically attached.</span></span>
4. <span data-ttu-id="6e644-136">Wählen Sie alternativ die Aktion **Neu** aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-136">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="6e644-137">Um eine Datei hinzuzufügen, wählen Sie die Aktion **Datei anhängen**.</span><span class="sxs-lookup"><span data-stu-id="6e644-137">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="6e644-138">Im **Datei einfügen**-Fenster wählen Sie die Datei, die den jeweiligen Eingangsbeleg darstellt, und wählen Sie die Schaltfläche **Öffnen**.</span><span class="sxs-lookup"><span data-stu-id="6e644-138">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="6e644-139">Füllen Sie im Fenster **Eingehende Belege** die Felder wie benötigt aus.</span><span class="sxs-lookup"><span data-stu-id="6e644-139">In the **Incoming Document** window, fill in the fields as necessary.</span></span> <span data-ttu-id="6e644-140">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="6e644-140">Choose a field to read a short description of the field or link to more information.</span></span>

##<a name="see-also"></a><span data-ttu-id="6e644-141">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="6e644-141">See Also</span></span>  
[<span data-ttu-id="6e644-142">Eingehende Dokumente verarbeiten</span><span class="sxs-lookup"><span data-stu-id="6e644-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="6e644-143">Eingehende Belege</span><span class="sxs-lookup"><span data-stu-id="6e644-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="6e644-144">Einkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="6e644-144">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="6e644-145">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6e644-145">Work With Dynamics NAV</span></span>](ui-work-product.md)


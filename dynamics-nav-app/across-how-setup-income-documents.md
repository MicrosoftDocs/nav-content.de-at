---
title: 'Gewusst wie: Eingehende Dokumente einrichten'
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
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="ed8f5-102">Gewusst wie: Eingehende Dokumente einrichten</span><span class="sxs-lookup"><span data-stu-id="ed8f5-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="ed8f5-103">Wenn Sie Fibu Buch.-Blattzeilen für eingehende Belegdatensätze erstellen, müssen Sie im Fenster **Einrichtung für eingehende Dokumente** angeben, welche Buch.-Blattvorlage und welches Buch.-Blatt verwendet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="ed8f5-104">Wenn Sie nicht möchten, dass Benutzer Rechnungen oder Fibu Buch.-Blattzeilen anhand von eingehende Belegdatensätzen erstellen können, ausser, wenn diese genehmigt sind, müssen Sie Genehmiger im Fenster **Genehmiger für eingehendes Dokument** einrichten.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="ed8f5-105">Um PDF und Bilddateien in elektronische Dokumente umzuwandeln, zum Beispiel Einkaufsrechnungen innerhalb von Dynamics NAV, müssen Sie zuerst die OCR-Funktion einrichten und den Dienst aktivieren.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="ed8f5-106">Wenn die Funktion für Eingangsbelege eingerichtet ist, können Sie verschiedene Funktionen zum Überprüfen von Ausgabenbelegen, Verwalten von OCR-Aufgaben und Konvertieren von Eingangsbelegen, manuell oder automatisch, in den entsprechenden Belegen oder Buch.-Blattzeilen verwenden.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="ed8f5-107">Die externen Dateien können jeder Prozessphase zugeordnet werden, auch gebuchten Belegen und den resultierenden Kreditoren-, Debitoren- und Sachposten.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="ed8f5-108">Weitere Informationen finden Sie unter [So gehts: Eingehende Dokumente verarbeiten](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="ed8f5-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="ed8f5-109">So richten Sie die Funktion für Eingangsbelege ein</span><span class="sxs-lookup"><span data-stu-id="ed8f5-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="ed8f5-110">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung für eingehende Dokumente** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="ed8f5-111">Füllen Sie die Felder je nach Bedarf aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="ed8f5-112">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="ed8f5-113">So richten Sie Genehmiger für Eingangsbelege ein</span><span class="sxs-lookup"><span data-stu-id="ed8f5-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="ed8f5-114">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Einrichtung für eingehende Dokumente** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="ed8f5-115">Wählen Sie im Fenster **Einrichtung für eingehende Dokumente** die Aktion **Genehmiger** aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="ed8f5-116">Im Fenster **Genehmiger für eingehendes Dokument** werden alle Benutzer angezeigt, die in Ihrem Dynamics NAV eingerichtet sind.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="ed8f5-117">Wählen Sie mindestens einen Benutzer aus, der einen eingehenden Beleg genehmigen kann, bevor eine zugehörige Beleg- oder Buch.-Blattzeile erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="ed8f5-118">Nachdem Sie Genehmiger im Fenster **Genehmiger für eingehendes Dokument** eingerichtet haben, können nur diese Benutzer ein eingehendes Dokument genehmigen, wenn im Fenster **Einrichtung für eingehende Dokumente** das Kontrollkästchen **Genehmigung zum Erstellen anfordern** aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="ed8f5-119">**Hinweis**: Diese Genehmigungseinrichtung ist nicht mit den Genehmigungsworkflows verknüpft.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="ed8f5-120">Weitere Informationen erhalten Sie unter [So gehts: Genehmigungsworkflow verwenden](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="ed8f5-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="ed8f5-121">So richten Sie einen OCR-Service ein</span><span class="sxs-lookup"><span data-stu-id="ed8f5-121">To set up an OCR service</span></span>
1. <span data-ttu-id="ed8f5-122">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **OCR-Dienst einrichten** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="ed8f5-123">Füllen Sie die Felder je nach Bedarf aus.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="ed8f5-124">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="ed8f5-125">So verschlüsseln Sie Ihre Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="ed8f5-125">To encrypt your login information</span></span>
<span data-ttu-id="ed8f5-126">Es wird empfohlen, dass Sie die Anmeldeinformationen, die Sie im Fenster **OCR-Dienst einrichten** eingeben, schützen.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="ed8f5-127">Sie können Daten auf dem Server verschlüsseln, indem Sie neue Verschlüsselungsschlüssel erstellen oder vorhandene importieren, die Sie auf der Serverinstanz aktivieren, die mit der Datenbank verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="ed8f5-128">Wählen Sie im Fenster **OCR-Dienst einrichten** die Aktion **Verschlüsselungsverwaltung**.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="ed8f5-129">Aktivieren Sie im Fenster **Datenverschlüsselungsverwaltung** die Verschlüsselung der Daten.</span><span class="sxs-lookup"><span data-stu-id="ed8f5-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="ed8f5-130">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="ed8f5-130">See Also</span></span>  
[<span data-ttu-id="ed8f5-131">Eingehende Dokumente verarbeiten</span><span class="sxs-lookup"><span data-stu-id="ed8f5-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="ed8f5-132">Eingehende Belege</span><span class="sxs-lookup"><span data-stu-id="ed8f5-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="ed8f5-133">Einkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="ed8f5-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="ed8f5-134">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="ed8f5-134">Work With Dynamics NAV</span></span>](ui-work-product.md)


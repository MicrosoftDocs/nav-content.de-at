---
title: Daten aus anderen Finanzsystemen importieren
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: b5bd6092046f9a8d75498ddcf3b1ce73f674e687
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="import-data-from-other-finance-systems"></a><span data-ttu-id="a4b3b-102">Daten aus anderen Finanzsystemen importieren</span><span class="sxs-lookup"><span data-stu-id="a4b3b-102">Import Data from Other Finance Systems</span></span>
<span data-ttu-id="a4b3b-103">In Dynamics NAV können Sie einen leeren Mandanten erstellen, sodass Sie Daten aus anderen Finanzeinrichtungssystemen hochladen können, um in Ihrem neuen Dynamics NAV zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-103">In Dynamics NAV, you can choose to create an empty company so that you can upload data from other finance-setup systems to use in your new Dynamics NAV.</span></span> <span data-ttu-id="a4b3b-104">Abhängig von der Finanzeinrichtungslösung, die Ihr Unternehmen heute verwendet, können Sie Informationen zu Debitoren, Kreditoren, Lagerbestand und Bankkonten vornehmen.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-104">Depending on the finance-setup solution that your business uses today, you can transfer information about customers, vendors, inventory, and bank accounts.</span></span>
<span data-ttu-id="a4b3b-105">Im Unternehmensbesitzer-Rollencenter können Sie eine unterstützte Einrichtung vornehmen, mit der Sie die Daten einer Exceldatei oder aus anderen Formaten übertragen können.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-105">In the Business Owner Role Center, you can access an assisted setup guide that helps you transfer the business data from an Excel file or from other formats.</span></span> <span data-ttu-id="a4b3b-106">Die Art der Dateien, die Sie hochladen können, hängt von den Erweiterungen ab, die verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-106">The type of files you can upload depends on the extensions that are available.</span></span> <span data-ttu-id="a4b3b-107">Beispielsweise können Sie Daten aus QuickBooks hochladen, da Dynamics NAV eine Erweiterung umfasst, die die Umwandlung von QuickBooks behandelt.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-107">For example, you can upload data from QuickBooks because Dynamics NAV includes an extension that handles the conversion from QuickBooks.</span></span> <span data-ttu-id="a4b3b-108">Wenn Sie Daten aus anderen Finanzeinrichtungslösungen hochladen möchten, müssen Sie überprüfen, ob eine Erweiterung für diese Lösung verfügbar ist oder aus Excel importieren.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-108">If you want to upload data from other finance-setup solutions, you must either check if an extension is available for that solution or import from Excel.</span></span>  
<span data-ttu-id="a4b3b-109">Dynamics NAV umfasst Vorlagen für Debitoren, Kreditoren und Lagerartikel, die Sie zum Anwenden wählen können, wenn Sie Ihre Daten hochladen.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-109">Dynamics NAV includes templates for customers, vendors, and inventory items that you can choose to apply when you upload your data.</span></span>  

## <a name="transfer-from-quickbooks"></a><span data-ttu-id="a4b3b-110">Umlagerung von QuickBooks</span><span class="sxs-lookup"><span data-stu-id="a4b3b-110">Transfer from QuickBooks</span></span>
<span data-ttu-id="a4b3b-111">Wenn Ihr Geschäft QuickBooks heute verwendet, können Sie die Daten in eine Datei mit Intuit-Interchange-Format (IIF) exportieren.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-111">If your business uses QuickBooks today, you can export the relevant information to an Intuit Interchange Format (IIF) file.</span></span> <span data-ttu-id="a4b3b-112">Sie können dann die unterstütze Einrichtung öffnen, um die Daten zu übertragen.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-112">You can then open the assisted setup guide to transfer the data.</span></span>
<span data-ttu-id="a4b3b-113">Wenn beispielsweise Ihre IIF-Datei Debitoren und Kreditoren umfasst, können Sie wählen, nur die Debitorendaten umzulagern.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-113">For example, if your IIF file includes customers and vendors, you can choose to transfer only the customer data.</span></span> <span data-ttu-id="a4b3b-114">Sie können die restlichen Daten dann später übertragen.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-114">You can then transfer the rest of the information later.</span></span>  
<span data-ttu-id="a4b3b-115">Die unterstützte Einrichtung umfasst eine Option, die Vorgabe Konfiguration der Übertragung zu ändern. Wir empfehlen aber, dass nur dieses erweiterte Einrichtung eingeben wird, wenn Sie mit Datenbanktabellen vertraut sind.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-115">The assisted setup includes an option to change the default configuration of the transfer, but we recommend that you only enter this advanced setup if you are familiar with database tables.</span></span> <span data-ttu-id="a4b3b-116">In der überwiegenden Mehrheit von Geschäften überträgt die Standardzuordnung von QuickBook zu Dynamics NAV die Informationen, die Sie möchten.</span><span class="sxs-lookup"><span data-stu-id="a4b3b-116">In the vast majority of businesses, the default mapping from QuickBooks to Dynamics NAV will transfer the information that you want.</span></span>

## <a name="see-also"></a><span data-ttu-id="a4b3b-117">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="a4b3b-117">See Also</span></span>
[<span data-ttu-id="a4b3b-118">Finanzen</span><span class="sxs-lookup"><span data-stu-id="a4b3b-118">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="a4b3b-119">[Anpassen des Dynamics NAV mithilfe der Erweiterungen](ui-extensions.md) </span><span class="sxs-lookup"><span data-stu-id="a4b3b-119">[Customizing Dynamics NAV Using Extensions](ui-extensions.md) </span></span>  
[<span data-ttu-id="a4b3b-120">Dynamics NAV einrichten</span><span class="sxs-lookup"><span data-stu-id="a4b3b-120">Set Up Your Dynamics NAV</span></span>](setup.md)


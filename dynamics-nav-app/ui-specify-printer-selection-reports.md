---
title: "Angeben der Druckerauswahl für Berichte"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="8a06e-102">Angeben der Druckerauswahl für Berichte</span><span class="sxs-lookup"><span data-stu-id="8a06e-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="8a06e-103">Sie können Berichte so einrichten, dass sie auf einem bestimmten Drucker gedruckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="8a06e-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="8a06e-104">Im Folgenden sind einige Verwendungen der Druckerauswahl aufgeführt:</span><span class="sxs-lookup"><span data-stu-id="8a06e-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="8a06e-105">Sie können Berichte auf Papier mit dem Unternehmensbriefkopf drucken.</span><span class="sxs-lookup"><span data-stu-id="8a06e-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="8a06e-106">Sie können Berichte in verschiedenen Papierformaten drucken.</span><span class="sxs-lookup"><span data-stu-id="8a06e-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="8a06e-107">Sie können Berichte auf dem Standarddrucker eines bestimmten Mitarbeiters drucken.</span><span class="sxs-lookup"><span data-stu-id="8a06e-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="8a06e-108">Sie verwenden das Fenster **Druckerauswahl**, um unterschiedliche Werte festzulegen, um unterschiedliche Ausgaben sofort sehen zu können.</span><span class="sxs-lookup"><span data-stu-id="8a06e-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="8a06e-109">Wenn dieses eine spezielle Druckerauswahl treffen, hat diese Vorrang vor einer allgemeineren Druckerauswahl.</span><span class="sxs-lookup"><span data-stu-id="8a06e-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="8a06e-110">Beispielsweise können Sie eine Druckerauswahl setzen, die die Werte in den Feldern **Benutzer-ID**, **Berichts-ID** und **Druckername** betrifft.</span><span class="sxs-lookup"><span data-stu-id="8a06e-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="8a06e-111">Diese Druckerauswahl hat dann Vorrang vor einer Druckerauswahl, die die Felder **Benutzer-ID** oder **Berichts-ID** unausgefüllt lässt.</span><span class="sxs-lookup"><span data-stu-id="8a06e-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="8a06e-112">In der folgenden Tabelle werden die Werte-Kombinationen beschrieben, die Sie bestimmen müssen, wenn Sie die Druckerauswahl für einen Bericht einrichten.</span><span class="sxs-lookup"><span data-stu-id="8a06e-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="8a06e-113">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="8a06e-113">To</span></span>                                                 |<span data-ttu-id="8a06e-114">Legen Sie folgende Werte fest</span><span class="sxs-lookup"><span data-stu-id="8a06e-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="8a06e-115">Drucken eines Berichts mit einem bestimmten Drucker für alle Benutzer</span><span class="sxs-lookup"><span data-stu-id="8a06e-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="8a06e-116">Geben Sie Werte in den Feldern **Berichts-ID** und **Druckername** an und lassen Sie das Feld **Benutzer-ID** leer.</span><span class="sxs-lookup"><span data-stu-id="8a06e-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="8a06e-117">Drucken aller Berichte mit einem bestimmten Drucker für einen bestimmten Benutzer</span><span class="sxs-lookup"><span data-stu-id="8a06e-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="8a06e-118">Geben Sie Werte in den Feldern **Benutzer-ID** und **Druckername** an und lassen Sie das Feld **Berichts-ID** leer.</span><span class="sxs-lookup"><span data-stu-id="8a06e-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="8a06e-119">Standarddrucker für alle Berichte festlegen</span><span class="sxs-lookup"><span data-stu-id="8a06e-119">Set the default printer for all reports</span></span>|<span data-ttu-id="8a06e-120">Geben Sie einen Wert in das Feld **Druckername** ein und lassen Sie die Felder **Benutzer-ID** und **Berichts-ID** leer.</span><span class="sxs-lookup"><span data-stu-id="8a06e-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="8a06e-121">Drucken eines bestimmten Berichts auf dem Standarddrucker des Benutzers</span><span class="sxs-lookup"><span data-stu-id="8a06e-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="8a06e-122">Geben Sie einen Wert in das Feld **Berichts-ID** ein und lassen Sie die Felder **Benutzer-ID** und **Druckername** leer.</span><span class="sxs-lookup"><span data-stu-id="8a06e-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="8a06e-123">Drucken eines bestimmten Berichts mit einem bestimmten Drucker für einen bestimmten Benutzer</span><span class="sxs-lookup"><span data-stu-id="8a06e-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="8a06e-124">Geben Sie Werte in den drei Feldern an.</span><span class="sxs-lookup"><span data-stu-id="8a06e-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="8a06e-125">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="8a06e-125">See Also</span></span>
[<span data-ttu-id="8a06e-126">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="8a06e-126">Work with Dynamics NAV</span></span>](ui-work-product.md)


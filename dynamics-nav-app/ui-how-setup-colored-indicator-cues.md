---
title: 'Vorgehensweise: Einrichten eines farbigen Indikators auf Stapeln des Rollencenters'
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
ms.openlocfilehash: 38cd904d0cf22374eac430d035e6ea6d205bcab8
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="f2504-102">Vorgehensweise: Einrichten eines farbigen Indikators auf Stapeln des Rollencenters</span><span class="sxs-lookup"><span data-stu-id="f2504-102">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="f2504-103">Richten Sie Stapel ein, die auf der **Start**seite mit einem Indikator angezeigt werden, dessen Farbe sich basierend auf den Datenwerten in den Stapeln ändert.</span><span class="sxs-lookup"><span data-stu-id="f2504-103">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span> 

<span data-ttu-id="f2504-104">Der Indikator erscheint als farbige Leiste an der oberen Kante der Stapelfläche.</span><span class="sxs-lookup"><span data-stu-id="f2504-104">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="f2504-105">Es wird ein optisches Signal zu dem Status der Aktivität des Stapels angezeigt, dss Bedingungen (vorteilhaft oder ungünstig) angeben kann, und den Benutzer auffordern kann, Maßnahmen zu ergreifen.</span><span class="sxs-lookup"><span data-stu-id="f2504-105">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="f2504-106">Wenn beispielsweise ein Stapel laufende Verkaufsrechnungen angezeigt, können Sie die Markierung so einrichten, dass sie grün (vorteilhaft) angezeigt wird, wenn die Gesamtanzahl laufender Verkaufsrechnungen unter 10 ist, und in Rot (ungünstig), wenn die Anzahl größer als 20 ist.</span><span class="sxs-lookup"><span data-stu-id="f2504-106">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="f2504-107">Im Fenster **Stapel einrichten** können Sie Indikatoren für alle Stapel einrichten, die in der Unternehmensdatenbank verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="f2504-107">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="f2504-108">Um den Indikator einzurichten, geben Sie bis zu zwei Schwellenwerte an, die drei Bereiche von Datenwerten definieren (niedrig, mittel und hoch), die Sie jeweils mit einer anderen Farbe (oder einem anderen Format) anzeigen können.</span><span class="sxs-lookup"><span data-stu-id="f2504-108">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="f2504-109">So richten Sie farbige Indikatoren auf Stapeln ein.</span><span class="sxs-lookup"><span data-stu-id="f2504-109">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="f2504-110">Unter **Aktivitäten** auf Ihrer **Start**seite wählen Sie **Stapel einrichten**.</span><span class="sxs-lookup"><span data-stu-id="f2504-110">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
<span data-ttu-id="f2504-111">Das Fenster **Stapel einrichten** wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="f2504-111">The **Cue Setup** window appears.</span></span> <span data-ttu-id="f2504-112">Das Fenster listet die Indikatoren auf, die derzeit in Stapeln für den Mandanten eingerichtet sind.</span><span class="sxs-lookup"><span data-stu-id="f2504-112">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="f2504-113">Um einen Indikator zu ändern, bearbeiten Sie die Felder und ändern Sie beispielsweise die Werte für die verschiedenen Schwellenwerte.</span><span class="sxs-lookup"><span data-stu-id="f2504-113">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="f2504-114">Die folgende Tabelle enthält die Farben, die den Optionen der **Format des unteren Bereichs**, **Format des mittleren Bereichs** und **Format des oberen Bereichs** entsprechen.</span><span class="sxs-lookup"><span data-stu-id="f2504-114">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

|<span data-ttu-id="f2504-115">Option</span><span class="sxs-lookup"><span data-stu-id="f2504-115">Option</span></span>|<span data-ttu-id="f2504-116">Farbe</span><span class="sxs-lookup"><span data-stu-id="f2504-116">Color</span></span>|
|------|-----|
|<span data-ttu-id="f2504-117">**Keine**</span><span class="sxs-lookup"><span data-stu-id="f2504-117">**None**</span></span>|<span data-ttu-id="f2504-118">Keine Farbe (dieselbe Farbe wie die Stapelfläche</span><span class="sxs-lookup"><span data-stu-id="f2504-118">No color (same color as the Cue tile</span></span>|
|<span data-ttu-id="f2504-119">**Vorteilhaft**</span><span class="sxs-lookup"><span data-stu-id="f2504-119">**Favorable**</span></span>|<span data-ttu-id="f2504-120">Grün</span><span class="sxs-lookup"><span data-stu-id="f2504-120">Green</span></span>|
|<span data-ttu-id="f2504-121">**Ungünstig**</span><span class="sxs-lookup"><span data-stu-id="f2504-121">**Unfavorable**</span></span>|<span data-ttu-id="f2504-122">Rot</span><span class="sxs-lookup"><span data-stu-id="f2504-122">Red</span></span>|
|<span data-ttu-id="f2504-123">**Mehrdeutig**</span><span class="sxs-lookup"><span data-stu-id="f2504-123">**Ambiguous**</span></span>|<span data-ttu-id="f2504-124">Gelb</span><span class="sxs-lookup"><span data-stu-id="f2504-124">Yellow</span></span>|
|<span data-ttu-id="f2504-125">**Untergeordnet**</span><span class="sxs-lookup"><span data-stu-id="f2504-125">**Subordinate**</span></span>|<span data-ttu-id="f2504-126">Grau</span><span class="sxs-lookup"><span data-stu-id="f2504-126">Gray</span></span>|

## <a name="see-also"></a><span data-ttu-id="f2504-127">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="f2504-127">See Also</span></span>
[<span data-ttu-id="f2504-128">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="f2504-128">Work with Dynamics NAV</span></span>](ui-work-product.md)



<properties
                pageTitle="So gehts: Bestand| Dynamics NAV neu bewerten"
                description="Beschreiben Sie, wie der Wert eines oder mehrerer Artikel im Lager abgeschrieben oder neu bewertet wird, indem Sie den aktuellen, berechneten Wert buchen."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/07/2016"
    ms.author="SorenGP" />


# <a name="how-to-revalue-inventory"></a><span data-ttu-id="6fff0-103">Vorgehensweise: Neubewerten von Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="6fff0-103">How to: Revalue Inventory</span></span>   
<span data-ttu-id="6fff0-104">Wenn Sie den Lagerwert eines Artikels oder den eines bestimmten Artikelpostens nach oben oder unten verändern möchten, müssen Sie das Neubewertungs Buch.-Blatt verwenden.</span><span class="sxs-lookup"><span data-stu-id="6fff0-104">If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.</span></span>

## <a name="to-revalue-inventory"></a><span data-ttu-id="6fff0-105">Neubewerten von Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="6fff0-105">To revalue inventory</span></span>
1. <span data-ttu-id="6fff0-106">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Neubewertung Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="6fff0-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Revaluation Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="6fff0-107">Wählen Sie die Aktion **Lagerwert berechnen** aus.</span><span class="sxs-lookup"><span data-stu-id="6fff0-107">Choose the **Calculate Inventory Value** action.</span></span>
3. <span data-ttu-id="6fff0-108">Füllen Sie im Fenster **Lagerwert berechnen** die Felder nach Bedarf aus.</span><span class="sxs-lookup"><span data-stu-id="6fff0-108">In the **Calculate Inventory Value** window, fill in the fields as necessary.</span></span> <span data-ttu-id="6fff0-109">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="6fff0-109">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="6fff0-110">Wählen Sie die Schaltfläche **OK** aus.</span><span class="sxs-lookup"><span data-stu-id="6fff0-110">Choose the **OK** button.</span></span>
5. <span data-ttu-id="6fff0-111">In jeder Zeile im Fenster **Neubewertungs-Blatt-Blatt** im Feld **Einheitskosten (neu bewertet)** geben Sie den neuen Einstandspreis ein.</span><span class="sxs-lookup"><span data-stu-id="6fff0-111">On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost.</span></span> <span data-ttu-id="6fff0-112">Oder geben Sie den Gesamtbetrag im Feld **Lagerwert (neu bewertet)** ein.</span><span class="sxs-lookup"><span data-stu-id="6fff0-112">Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.</span></span>

    <span data-ttu-id="6fff0-113">Die entsprechenden Felder werden automatisch aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="6fff0-113">The relevant fields are automatically updated.</span></span> <span data-ttu-id="6fff0-114">Beachten Sie, dass das Feld **Betrag** die tatsächliche Änderung des Lagerwertes für den ausgewählten Artikelposten zeigt.</span><span class="sxs-lookup"><span data-stu-id="6fff0-114">Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry.</span></span> <span data-ttu-id="6fff0-115">Es berechnet die Differenz zwischen den Feldern **Lagerwert (berechnet)** und **Lagerwert (neu bewertet)**.</span><span class="sxs-lookup"><span data-stu-id="6fff0-115">It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.</span></span>

6. <span data-ttu-id="6fff0-116">Wenn Sie das Einlagern der Artikel abgeschlossen haben, wählen Sie die Aktion **Buchen** aus.</span><span class="sxs-lookup"><span data-stu-id="6fff0-116">When you have completed all lines in the revaluation journal, choose the **Post** action.</span></span>

<span data-ttu-id="6fff0-117">Neue Wertposten werden nun erstellt, um die Neubewertungen abzubilden, die Sie gebucht haben.</span><span class="sxs-lookup"><span data-stu-id="6fff0-117">New value entries are now created to reflect the revaluations that you have posted.</span></span> <span data-ttu-id="6fff0-118">Sie können die neuen Werte in der entsprechenden Artikelkarten sehen.</span><span class="sxs-lookup"><span data-stu-id="6fff0-118">You can see the new values on the respective item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="6fff0-119">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="6fff0-119">See Also</span></span>
[<span data-ttu-id="6fff0-120">Verwalten des Lagerbestands</span><span class="sxs-lookup"><span data-stu-id="6fff0-120">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="6fff0-121">Verkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="6fff0-121">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="6fff0-122">Einkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="6fff0-122">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="6fff0-123">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6fff0-123">Work With Dynamics NAV</span></span>](ui-work-product.md)


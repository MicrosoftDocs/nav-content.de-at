---
title: 'Vorgehensweise: Buchen des Jahresabschlusspostens'
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: fe32ee973c90ba857852ae092acf03db09e648ee
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---
# <a name="how-to-post-year-end-closing-entry"></a><span data-ttu-id="3d767-102">Vorgehensweise: Buchen des Jahresabschlusspostens</span><span class="sxs-lookup"><span data-stu-id="3d767-102">How to: Post Year-End Closing Entry</span></span>
<span data-ttu-id="3d767-103">Als Teil des Abschlusses der Bühcer für ein Geschäftsjahr müssen Sie die GuV-Kontennullstellung durchführen und das Ergebnis auf ein Bilanzkonto übertragen lassen und die die GuV-Konten abschliessen.</span><span class="sxs-lookup"><span data-stu-id="3d767-103">As part of closing the books for a fiscal year, you will run the Close Income Statement batch job to transfer the year's result to an account in the balance sheet and close the income statement accounts.</span></span> <span data-ttu-id="3d767-104">Nachdem Sie die Stapelverarbeitung "GuV-Konten Nullstellung" ausgeführt haben, um den bzw. die Ultimoposten für den Jahresabschluss zu generieren, müssen Sie das in der Stapelverarbeitung angegebene Buchungsblatt öffnen und die Posten überprüfen und buchen.</span><span class="sxs-lookup"><span data-stu-id="3d767-104">After you run the Close Income Statement batch job, you must open the journal you specified in the batch job, and then review and post the entries.</span></span>

## <a name="to-post-the-year-end-closing-entry"></a><span data-ttu-id="3d767-105">So buchen Sie den Jahresabschlussposten</span><span class="sxs-lookup"><span data-stu-id="3d767-105">To post the year end closing entry</span></span>
1. <span data-ttu-id="3d767-106">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Fibu Buch.-Blatt** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="3d767-106">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="3d767-107">Wählen Sie im Fenster **Fibu Buch.Blatt** im Feld **Buch.-Blattname** das Buch.-Blatt mit den Abschlussposten aus.</span><span class="sxs-lookup"><span data-stu-id="3d767-107">In the **General Journal** window, in the **Batch Name** field, select the batch that contains the closing entries.</span></span>
3. <span data-ttu-id="3d767-108">Überprüfen Sie die Posten.</span><span class="sxs-lookup"><span data-stu-id="3d767-108">Review the entries.</span></span>
4. <span data-ttu-id="3d767-109">Wählen Sie auf der Registerkarte **Start** die Option Buchen aus, um das Buch.-Blatt zu buchen.</span><span class="sxs-lookup"><span data-stu-id="3d767-109">To post the journal, choose the **Post** action.</span></span>

<span data-ttu-id="3d767-110">**Hinweis**: Wenn ein Fehler erkannt wird, wird eine Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3d767-110">**Note**: If an error is detected, an error message is displayed.</span></span> <span data-ttu-id="3d767-111">Wurde die Buchung ordnungsgemäß durchgeführt, werden die gebuchten Posten aus dem Buch.-Blatt entfernt.</span><span class="sxs-lookup"><span data-stu-id="3d767-111">If the posting is successful, the posted entries are removed from the journal.</span></span> <span data-ttu-id="3d767-112">Nachdem die Buchung abgeschlossen ist, wird ein Posten auf jedes GuV-Konto gebucht, sodass der Saldo des Kontos Null ist und das Jahresergebnis in die Bilanz übertragen wird.</span><span class="sxs-lookup"><span data-stu-id="3d767-112">After posting is complete, an entry is posted to each income statement account so that its balance becomes zero and the year's result is transferred to the balance sheet.</span></span>

## <a name="see-also"></a><span data-ttu-id="3d767-113">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="3d767-113">See Also</span></span>
[<span data-ttu-id="3d767-114">Buchabschluss</span><span class="sxs-lookup"><span data-stu-id="3d767-114">Close Books</span></span>](year-close-books.md)  
[<span data-ttu-id="3d767-115">GuV-Konten Nullstellung</span><span class="sxs-lookup"><span data-stu-id="3d767-115">Close Income Statement</span></span>](year-close-income-statement.md)  
[<span data-ttu-id="3d767-116">So geht's: Buchhaltungsperioden schließen</span><span class="sxs-lookup"><span data-stu-id="3d767-116">How to: Close Accounting Periods</span></span>](year-close-account-periods.md)  

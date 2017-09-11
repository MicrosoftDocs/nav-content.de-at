---
title: 'So geht''s: Einrichten der Anlagenwartung'
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
ms.openlocfilehash: ace0fb13d2be71c7204f16f34f6b65b54ff98230
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-maintenance"></a><span data-ttu-id="da71a-102">So geht's: Einrichten der Anlagenwartung</span><span class="sxs-lookup"><span data-stu-id="da71a-102">How to: Set Up Fixed Asset Maintenance</span></span>
<span data-ttu-id="da71a-103">Um die Anlagenwartung zu verwalten, müssen Sie erst einige allgemeine Wartungsinformationen einrichten, ein Buchungskonto für Wartungskosten und Wartungscodes für die Arten von Arbeit, beispielsweise Instandhaltung oder Reparatur.</span><span class="sxs-lookup"><span data-stu-id="da71a-103">To manage fixed asset maintenance, you must first set up some general maintenance information, a posting account for maintenance costs, and maintenance codes for types of work, such as Routine Service or Repair.</span></span>

## <a name="to-set-up-general-maintenance-information"></a><span data-ttu-id="da71a-104">So richten Sie allgemeine Wartungsinformationen ein:</span><span class="sxs-lookup"><span data-stu-id="da71a-104">To set up general maintenance information</span></span>
<span data-ttu-id="da71a-105">Wenn Sie die Felder für Wartung eingerichtet haben, können Sie Wartungsausgaben aus einem Buch.-Blatt buchen.</span><span class="sxs-lookup"><span data-stu-id="da71a-105">If you set up the fields for maintenance, you can post maintenance expenses from the fixed asset journal.</span></span>
1. <span data-ttu-id="da71a-106">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlagen** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="da71a-107">Wählen Sie die Anlage, für die Sie den Versicherungsposten festlegen wollen, und wählen die Aktion **Bearbeiten** aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-107">Select the fixed asset that you to define insurance coverage for, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="da71a-108">Füllen Sie auf dem Inforegister **Wartung** die notwendigen Felder aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-108">On the **Maintenance** FastTab, fill in the fields as necessary.</span></span> <span data-ttu-id="da71a-109">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="da71a-109">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-maintenance-codes"></a><span data-ttu-id="da71a-110">So richten Sie Wartungscodes ein</span><span class="sxs-lookup"><span data-stu-id="da71a-110">To set up maintenance codes</span></span>  
<span data-ttu-id="da71a-111">Wenn Sie Wartungskosten aus einem Fibu Buch.-Blatt buchen, füllen Sie das Feld **Wartungscode** aus. So erfassen Sie, welche Art von Wartung durchgeführt wurde, beispielsweise Instandhaltung oder Reparatur.</span><span class="sxs-lookup"><span data-stu-id="da71a-111">When you post maintenance costs from a general journal, you fill in the **Maintenance Code** field to record what kind of maintenance has been performed, such as routine service or repair.</span></span>
1. <span data-ttu-id="da71a-112">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Wartung** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance**, and then choose the related link.</span></span>
2. <span data-ttu-id="da71a-113">Legen Sie im Fenster **Wartung** Codes für unterschiedliche Arten von Wartungsarbeiten fest.</span><span class="sxs-lookup"><span data-stu-id="da71a-113">In the **Maintenance** window, set up codes for different types of maintenance work.</span></span>

## <a name="to-set-up-maintenance-expense-accounts"></a><span data-ttu-id="da71a-114">So richten Sie Aufwandskonten für die Wartung ein</span><span class="sxs-lookup"><span data-stu-id="da71a-114">To set up maintenance expense accounts</span></span>  
<span data-ttu-id="da71a-115">Um Wartungskosten zu buchen, müssen Sie erst eine Kontonummer im Fenster **Anlagenbuchungsgruppen** eingeben.</span><span class="sxs-lookup"><span data-stu-id="da71a-115">To post maintenance costs, you must first enter an account number in the **FA Posting Groups** window.</span></span>
1. <span data-ttu-id="da71a-116">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagenbuchungsgruppen** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-116">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Posting Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="da71a-117">Füllen Sie das Feld **Aufwandskto. Wartung** für jede einzelne Buchungsgruppe aus.</span><span class="sxs-lookup"><span data-stu-id="da71a-117">Fill in the **Maintenance Expense Account** field for each posting group.</span></span>

<span data-ttu-id="da71a-118">**Hinweis**: Um festzulegen, dass Wartungskosten auf Kostenstellen und/oder Kostenträger verteilt werden, müssen Sie einen Verteilungsschlüssel einrichten.</span><span class="sxs-lookup"><span data-stu-id="da71a-118">**Note**: To define that maintenance costs are allocated to departments or projects, set up an allocation keys.</span></span> <span data-ttu-id="da71a-119">Weitere Informationen finden Sie unter [So geht's: Allgemeine Anlagenfeatures einrichten](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="da71a-119">For more information, see [How to: Set Up General Fixed Assets Features](fa-how-setup-general.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="da71a-120">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="da71a-120">See Also</span></span>
[<span data-ttu-id="da71a-121">Anlageneinrichtung</span><span class="sxs-lookup"><span data-stu-id="da71a-121">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="da71a-122">Verwalten von Anlagen</span><span class="sxs-lookup"><span data-stu-id="da71a-122">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="da71a-123">Finanzen</span><span class="sxs-lookup"><span data-stu-id="da71a-123">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="da71a-124">Willkommen bei Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="da71a-124">Welcome to Dynamics NAV</span></span>](across-get-started.md)


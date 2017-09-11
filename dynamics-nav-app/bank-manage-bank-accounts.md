---
title: Verwalten von Bankkonten
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
ms.openlocfilehash: d97c3afba0e899768bda1b637c4f288db210d38c
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="manage-bank-accounts"></a><span data-ttu-id="3bd1c-102">Verwalten von Bankkonten</span><span class="sxs-lookup"><span data-stu-id="3bd1c-102">Manage Bank Accounts</span></span>
<span data-ttu-id="3bd1c-103">In regelmäßigen Abständen müssen Sie Ihre Bankposten in Dynamics NAV mit den entsprechenden Banktransaktionen auf den Konten bei Ihrer Bank abstimmen, und dann den Saldo auf Ihrem Bankkonto buchen.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-103">At regular intervals, you must reconcile your bank ledger entries in Dynamics NAV with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="3bd1c-104">Diese Aufgabe kann als Teil der Zahlungsverarbeitung auf einem Bankauszug im **Zahlungsabstimmungsbuch.-Blatt** dargestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-104">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="3bd1c-105">Alternativ können Sie die Aufgabe unabhängig von der Zahlungsverarbeitung im Fenster **Bankkontoabstimmung** ausführen, in dem Scheckposten unterstützt werden.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-105">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="3bd1c-106">In beiden Fällen füllen Sie das Fenster aus, indem Sie den Bankkontoauszug in Dynamics NAV importieren.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-106">In both cases, you fill the windows by importing the bank statement into Dynamics NAV.</span></span>

<span data-ttu-id="3bd1c-107">Manchmal müssen Sie Beträge zwischen Bankkonten in Dynamics NAV transferieren, um Überweisungen bei Ihrer Bank widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-107">Sometimes, you need to transfer amounts between bank account in Dynamics NAV to reflect transfers at your bank.</span></span> <span data-ttu-id="3bd1c-108">Diese Aufgabe wird im Fenster **Fibu Buch.-Blatt** auf unterschiedliche Arten, abhängig von der Währung der Geldmittel ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-108">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="3bd1c-109">Bevor Sie Bankkonten verwalten können, müssen Sie jedes Bankkonto als Bankkontokarte einrichten.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-109">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="3bd1c-110">Darüber hinaus müssen Sie elektronische Dienste einrichten, die Sie ggf. für den Bankauszugsimport und Zahlungsdateiexport verwenden.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-110">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="3bd1c-111">Weitere Informationen finden Sie unter [So gehts: Einrichten von Bankkonten](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="3bd1c-111">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="3bd1c-112">In der folgenden Tabelle wird eine Reihe von Aufgaben mit Verknüpfungen zu den beschriebenen Themen erläutert.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="3bd1c-113">Aktion</span><span class="sxs-lookup"><span data-stu-id="3bd1c-113">To</span></span> |<span data-ttu-id="3bd1c-114">Siehe</span><span class="sxs-lookup"><span data-stu-id="3bd1c-114">See</span></span> |
|---|----|
|<span data-ttu-id="3bd1c-115">Abstimmen von Bankkonten in Verbindung mit der Zahlungsverarbeitung im Fenster **Zahlungsabstimmungsbuch.-Blatt**.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-115">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span>|[<span data-ttu-id="3bd1c-116">Zahlungen automatisch vornehmen und Bankkonten abstimmen</span><span class="sxs-lookup"><span data-stu-id="3bd1c-116">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="3bd1c-117">Abstimmen von Bankkonten, inklusive Scheckposten, als separate Aufgabe im Fenster **Bankkontoabstimmung**.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-117">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span>|[<span data-ttu-id="3bd1c-118">Gewusst wie: Bankkonten separat abstimmen</span><span class="sxs-lookup"><span data-stu-id="3bd1c-118">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md)|
|<span data-ttu-id="3bd1c-119">Buchen von Überweisungen zwischen Bankkonten in der gleichen oder in unterschiedlichen Währungen.</span><span class="sxs-lookup"><span data-stu-id="3bd1c-119">Post transfers between bank accounts in the same currency or in different currencies.</span></span>|[<span data-ttu-id="3bd1c-120">Gewusst wie: Bank-Geldmittel überweisen</span><span class="sxs-lookup"><span data-stu-id="3bd1c-120">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md)
## <a name="see-also"></a><span data-ttu-id="3bd1c-121">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="3bd1c-121">See Also</span></span>  
[<span data-ttu-id="3bd1c-122">Bank einrichten</span><span class="sxs-lookup"><span data-stu-id="3bd1c-122">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="3bd1c-123">Verwalten von Forderungen</span><span class="sxs-lookup"><span data-stu-id="3bd1c-123">Manage Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="3bd1c-124">[Verwalten von Verbindlichkeiten](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="3bd1c-124">[Manage Payables](payables-manage-payables.md)  </span></span>  
[<span data-ttu-id="3bd1c-125">Arbeiten mit Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="3bd1c-125">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="3bd1c-126">Übergreifende Geschäftsbereiche</span><span class="sxs-lookup"><span data-stu-id="3bd1c-126">Across Business Areas</span></span>](ui-across-business-areas.md)


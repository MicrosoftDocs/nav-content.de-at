---
title: "Einrichten oder Ändern des Kontenplans"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 2a2f1f2ec3ac5bdd935ec19c11d74e16bdee7686
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="set-up-or-change-the-chart-of-accounts"></a><span data-ttu-id="0d3eb-102">Einrichten oder Ändern des Kontenplans</span><span class="sxs-lookup"><span data-stu-id="0d3eb-102">Set Up or Change the Chart of Accounts</span></span>
<span data-ttu-id="0d3eb-103">Der Kontenplan zeigt die Sachkonten an, die Ihre Finanzdaten speichern.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-103">The chart of accounts shows the ledger accounts that store your financial data.</span></span> <span data-ttu-id="0d3eb-104">Dynamics NAV umfasst einen Standardkontenplan, der zur Unterstützung Ihres Unternehmens bereit steht.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-104">Dynamics NAV includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="0d3eb-105">Sie können jedoch die Standardkonten ändern und neue Konten hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-105">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="0d3eb-106">Konten hinzufügen oder ändern</span><span class="sxs-lookup"><span data-stu-id="0d3eb-106">Adding or Changing Accounts</span></span>
<span data-ttu-id="0d3eb-107">Im Kontenplan können Sie jedes Sachkonto öffnen und Einstellungen hinzufügen oder ändern.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-107">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

<span data-ttu-id="0d3eb-108">**Hinweis**: Sie können ein Sachkonto löschen.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-108">**Note**: You can delete a general ledger account.</span></span> <span data-ttu-id="0d3eb-109">Bevor es gelöscht wird, müssen allerdings folgende Bedingungen erfüllt sein:</span><span class="sxs-lookup"><span data-stu-id="0d3eb-109">However, before you delete it, the following must be true:</span></span>  
- <span data-ttu-id="0d3eb-110">Der Saldo des Kontos muss Null betragen.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-110">The balance on the account must be zero.</span></span>  
- <span data-ttu-id="0d3eb-111">Das Feld **Löschen v. Sachkonten zul. vor** im Fenster **Finanzbuchhaltung Einrichtung** muss ausgefüllt sein, und das Konto darf keine Posten an oder nach diesem Datum enthalten.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-111">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
- <span data-ttu-id="0d3eb-112">Ist das Feld **Sachkontoverwendung prüfen** im Fenster **Finanzbuchhaltung Einrichtung** ausgewählt, darf dieses Konto nicht in Buchungsgruppen oder der Buchungsmatrix Einrichtung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-112">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

<span data-ttu-id="0d3eb-113">Dynamics NAV verhindert, dass Sie ein Sachkonto löschen, in dem Daten gespeichert werden, die im Kontenplan erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="0d3eb-113">Dynamics NAV will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

##<a name="see-also"></a><span data-ttu-id="0d3eb-114">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="0d3eb-114">See Also</span></span>  
[<span data-ttu-id="0d3eb-115">Die Finanzbuchhaltung und der Kontenplan</span><span class="sxs-lookup"><span data-stu-id="0d3eb-115">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
[<span data-ttu-id="0d3eb-116">Verwalten von Bankkonten</span><span class="sxs-lookup"><span data-stu-id="0d3eb-116">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="0d3eb-117">Dimensionen</span><span class="sxs-lookup"><span data-stu-id="0d3eb-117">Dimensions</span></span>](finance-setup-dimensions.md)  
[<span data-ttu-id="0d3eb-118">So gehts: Arbeiten mit GIFI-Codes in Kanada</span><span class="sxs-lookup"><span data-stu-id="0d3eb-118">How to: Work With GIFI Codes in Canada</span></span>](ca-finance-setup-work-GiFI-codes.md)


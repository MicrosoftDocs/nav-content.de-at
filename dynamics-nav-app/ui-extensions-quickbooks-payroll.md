---
title: Die Quickbooks-Gehaltsabrechnungsdatei-Importerweiterung verwenden
description: Beschreibt, wie die Erweiterung verwendet wird, um Gehalts- und Lohntransaktionen aus dem Quickbooks-Gehaltsabrechnungsdienst zu importieren.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, salary, wage
ms.date: 03/29/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e1b47161b7fdd4238ff4590c2139c9622d5d3fbb
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="the-quickbooks-payroll-file-import-extension-to-dynamics-nav"></a><span data-ttu-id="0cfa9-103">Die Quickbooks-Gehaltsabrechnungsdatei-Importerweiterung in Dynamics NAV verwenden</span><span class="sxs-lookup"><span data-stu-id="0cfa9-103">The Quickbooks Payroll File Import Extension to Dynamics NAV</span></span>
<span data-ttu-id="0cfa9-104">Um Gehaltszahlungen und verwandte Transaktionen zu berücksichtigen, müssen Sie die Gehaltstransaktionen importieren und finanzielle Transaktionen buchen, die durch Ihr Gehaltsabrechnungsanbieter in die Finanzbuchhaltung gebucht werden.</span><span class="sxs-lookup"><span data-stu-id="0cfa9-104">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span>

<span data-ttu-id="0cfa9-105">Dazu importieren Sie zuerst eine Datei, die Sie vom Gehaltsabrechnungsanbieter erhalten in das Fenster **Fibur Buch.Blatt**.</span><span class="sxs-lookup"><span data-stu-id="0cfa9-105">To do this, you first import a file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="0cfa9-106">Anschließend ordnen Sie die externen Konten in der Gehaltsabrechnungsdatei den jeweiligen Sachkonten zu.</span><span class="sxs-lookup"><span data-stu-id="0cfa9-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="0cfa9-107">Zuletzt buchen Sie die Gehaltsabrechnungstransaktionen entsprechend der Kontozuordnung.</span><span class="sxs-lookup"><span data-stu-id="0cfa9-107">Lastly, you post the payroll transactions according to the account mapping.</span></span> <span data-ttu-id="0cfa9-108">Weitere Informationen finden Sie unter [So geht's: Gehaltsabrechnungstransaktionen importieren](finance-how-import-payroll-transactions.md).</span><span class="sxs-lookup"><span data-stu-id="0cfa9-108">For more information, see [How to: Import Payroll Transactions](finance-how-import-payroll-transactions.md).</span></span>

<span data-ttu-id="0cfa9-109">Die Quickbooks-Gehaltsabrechnungsdatei-Importerweiterung ermöglicht es Ihnen, Gehaltsabrechnungstransaktionen aus dem Quickbooks-Gehaltsabrechnungsservice zu importieren.</span><span class="sxs-lookup"><span data-stu-id="0cfa9-109">The Quickbooks Payroll File Import extension allows you to import payroll transaction from the Quickbooks Payroll service.</span></span>

## <a name="see-also"></a><span data-ttu-id="0cfa9-110">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="0cfa9-110">See Also</span></span>
<span data-ttu-id="0cfa9-111">[Anpassen[!INCLUDE[d365fin](includes/d365fin_md.md)]Erweiterungen nutzen ](ui-extensions.md)  </span><span class="sxs-lookup"><span data-stu-id="0cfa9-111">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)  </span></span>  
<span data-ttu-id="0cfa9-112">[Finanzen](finance.md)  </span><span class="sxs-lookup"><span data-stu-id="0cfa9-112">[Finance](finance.md)  </span></span>  
<span data-ttu-id="0cfa9-113">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0cfa9-113">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


---
title: "Designdetails – Buchungs-Schnittstellenstruktur"
description: "Dieses Thema enthält einen Überblick zu den globalen Verfahren in der Buchungsschnittstellenstruktur."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: posting, interface, design
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e262cb3f6464942f6e123d8545ec4fd8d386190b
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-posting-interface-structure"></a><span data-ttu-id="892e2-103">Designdetails: Buchungs-Schnittstellenstruktur</span><span class="sxs-lookup"><span data-stu-id="892e2-103">Design Details: Posting Interface Structure</span></span>
<span data-ttu-id="892e2-104">In [!INCLUDE[d365fin](includes/d365fin_md.md)]-Buchungsschnittstellenstruktur gibt es mehrere globale Verfahren, die dieselbe Struktur verwenden:</span><span class="sxs-lookup"><span data-stu-id="892e2-104">In the [!INCLUDE[d365fin](includes/d365fin_md.md)] posting interface structure, there are several global procedures that use the same structure:</span></span>  
  
* <span data-ttu-id="892e2-105">Anrufprozedurcode RunWithCheck und RunWithoutCheck - generische Buchungsschnittstelle für Fibu Buch.-Blattzeile.</span><span class="sxs-lookup"><span data-stu-id="892e2-105">RunWithCheck and RunWithoutCheck call procedure Code – generic posting interface for Gen. Jnl Line.</span></span>  
* <span data-ttu-id="892e2-106">CustPostApplyCustLedgEntry - Debitoren-Anwendung buchen, aufgerufen aus Codeunit 226 CustEntry-Gebuchte Posten übernehmen.</span><span class="sxs-lookup"><span data-stu-id="892e2-106">CustPostApplyCustLedgEntry – post customer application, called from codeunit 226 CustEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="892e2-107">VendPostApplyVendLedgEntry - Buchen von Kreditoren-Anwendung, aufgerufen aus Codeunit 227 VendEntry-Gebuchte Posten übernehmen.</span><span class="sxs-lookup"><span data-stu-id="892e2-107">VendPostApplyVendLedgEntry – post vendor application, called from codeunit 227 VendEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="892e2-108">UnapplyCustLedgEntry - Buchen von Debitoren-Anwendung rückgängig machen, aufgerufen aus Codeunit 226 CustEntry-Gebuchte Posten übernehmen.</span><span class="sxs-lookup"><span data-stu-id="892e2-108">UnapplyCustLedgEntry – post unapply of customer application, called from codeunit 226 CustEntry-Apply Posted Entries</span></span>  
* <span data-ttu-id="892e2-109">UnapplyVendLedgEntry - Buchen von Kreditoren-Anwendung rückgängig machen, aufgerufen aus Codeunit 227 VendEntry-Gebuchte Posten übernehmen.</span><span class="sxs-lookup"><span data-stu-id="892e2-109">UnapplyVendLedgEntry – post unapply of vendor application, called from codeunit 227 VendEntry-Apply Posted Entries</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="892e2-110">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="892e2-110">See Also</span></span>  
[<span data-ttu-id="892e2-111">Designdetails: Buchungs-Modul-Struktur</span><span class="sxs-lookup"><span data-stu-id="892e2-111">Design Details: Posting Engine Structure</span></span>](design-details-posting-engine-structure.md)

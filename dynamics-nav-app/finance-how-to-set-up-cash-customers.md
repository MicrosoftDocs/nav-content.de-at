---
title: Vorgehensweise beim Barkunden einrichten
description: Dieses Thema beschreibt die Schritte, um Kunden einzurichten, der in bar bezahlt.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/11/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: dca1e2b58d22a9d27766a731a085278f1200b570
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-cash-customers"></a>Vorgehensweise: Barkunden einrichten
Sie können keine Rechnung ohne Debitorennummer erstellen. Dies trifft auch zu, wenn Sie einen Barverkauf tätigen und kein Debitorenkonto aktualisieren müssen.  

## <a name="to-set-up-a-cash-customer"></a>So richten Sie Bargelddebitoren ein:  
1.  Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Kunde** ein und wählen dann den zugehörigen Link aus.  
2.  Erstellen Sie eine neue Karte **Debitor**. Weitere Informationen finden Sie unter [Vorgehensweise: Einrichten neuer Debitoren](sales-how-register-new-customers.md).
3.  Geben Sie im Feld **Nr.** Geben Sie beispielsweise **Bar** ein.  
4.  Geben Sie in dem Feld **Name** z. B. **BARVERKAUF** ein.  
5.  Füllen Sie auf dem Inforegister **Fakturierung** die Felder **Debitorenbuchungsgruppe** und **Geschäftsbuchungsgruppe** aus.  

 Sie haben jetzt einen neuen Debitor und die notwendigen Informationen für die Fakturierung eingerichtet.  

> [!NOTE]  
>  Es kann sein, dass Sie eine Buchungsgruppe gewählt haben, die auch für inländische Kreditverkäufe verwendet wird. Falls Sie gesonderte Daten für Barverkäufe benötigen, z. B. mit einem Verkaufs- oder Sammelkonto, können Sie zu diesem Zweck eine gesonderte Buchungsgruppe einrichten.  
>   
>  Sie müssen in dieser Buchungsgruppe die Nummer für ein Sammelkonto angeben, obwohl der Saldo auf diesem Konto immer 0 sein wird, nachdem Sie die Rechnung gebucht haben.  

## <a name="see-also"></a>Siehe auch
[Verwalten von Forderungen](receivables-manage-receivables.md)  
[Vorgehensweise: Einen neuen Debitor registrieren](sales-how-register-new-customers.md)    
[Finanzen](finance.md)  



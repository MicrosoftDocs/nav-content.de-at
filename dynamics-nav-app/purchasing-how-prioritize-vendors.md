---
title: 'Vorgehensweise: Priorisieren von Kreditoren'
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
ms.openlocfilehash: 3b89bf07e1e9d1839b6c86a01111e936fb62c9f3
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-prioritize-vendors"></a>Vorgehensweise: Priorisieren von Kreditoren
Dynamics NAV kann verschiedene Zahlungen an Kreditoren vorschlagen. Dies können z. B. Zahlungen sein, die in Kürze fällig sind, oder Zahlungen, bei denen Sie einen Rabatt erhalten können. Weitere Informationen finden Sie unter [Vorgehensweise: Erstellen von Zahlungsvorschlägen für Kreditoren](payables-how-suggest-vendor-payments.md).

Zuerst müssen Sie den Kreditoren priorisieren, indem Sie ihm Nummern zuweisen.

## <a name="to-prioritize-vendors"></a>So priorisieren Sie Kreditoren
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Kreditoren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die entsprechende Kreditor, und klicken Sie dann auf **Bearbeiten**.
3. Geben Sie im Feld **Priorität** eine Zahl ein.

Dynamics NAV geht davon aus, dass die niedrigsten Nummern, außer 0, die höchste Priorität haben. Wenn Sie also z. B. 1, 2 und 3 verwenden, erhält 1 die höchste Priorität.

Falls Sie einem Kreditor keine Priorität zuweisen wollen, lassen Sie das Feld **Priorität** leer. Wenn Sie dann die Funktion "Zahlungsvorschlag" verwenden, wird dieser Kreditor nach den Kreditoren aufgeführt, die eine Priorität haben. Sie können so viele Prioritäten einrichten wie Sie benötigen.

## <a name="see-also"></a>Siehe auch
[Einkauf einrichten:](purchasing-setup-purchasing.md)  
[Verwalten von Verbindlichkeiten](payables-manage-payables.md)


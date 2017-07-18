---
title: "Angeben der Druckerauswahl für Berichte"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 55b48aef2bc108ced7f581f0ff6c11263ee467df
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
    
# <a name="specify-printer-selection-for-reports"></a>Angeben der Druckerauswahl für Berichte
Sie können Berichte so einrichten, dass sie auf einem bestimmten Drucker gedruckt werden müssen. Im Folgenden sind einige Verwendungen der Druckerauswahl aufgeführt: 

- Sie können Berichte auf Papier mit dem Unternehmensbriefkopf drucken.
- Sie können Berichte in verschiedenen Papierformaten drucken.
- Sie können Berichte auf dem Standarddrucker eines bestimmten Mitarbeiters drucken.

Sie verwenden das Fenster **Druckerauswahl**, um unterschiedliche Werte festzulegen, um unterschiedliche Ausgaben sofort sehen zu können. Wenn dieses eine spezielle Druckerauswahl treffen, hat diese Vorrang vor einer allgemeineren Druckerauswahl. Beispielsweise können Sie eine Druckerauswahl setzen, die die Werte in den Feldern **Benutzer-ID**, **Berichts-ID** und **Druckername** betrifft. Diese Druckerauswahl hat dann Vorrang vor einer Druckerauswahl, die die Felder **Benutzer-ID** oder **Berichts-ID** unausgefüllt lässt. 

In der folgenden Tabelle werden die Werte-Kombinationen beschrieben, die Sie bestimmen müssen, wenn Sie die Druckerauswahl für einen Bericht einrichten.

|Aufgabe                                                 |Legen Sie folgende Werte fest                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|Drucken eines Berichts mit einem bestimmten Drucker für alle Benutzer |Geben Sie Werte in den Feldern **Berichts-ID** und **Druckername** an und lassen Sie das Feld **Benutzer-ID** leer.|
|Drucken aller Berichte mit einem bestimmten Drucker für einen bestimmten Benutzer|Geben Sie Werte in den Feldern **Benutzer-ID** und **Druckername** an und lassen Sie das Feld **Berichts-ID** leer.|
|Standarddrucker für alle Berichte festlegen|Geben Sie einen Wert in das Feld **Druckername** ein und lassen Sie die Felder **Benutzer-ID** und **Berichts-ID** leer.|
|Drucken eines bestimmten Berichts auf dem Standarddrucker des Benutzers|Geben Sie einen Wert in das Feld **Berichts-ID** ein und lassen Sie die Felder **Benutzer-ID** und **Druckername** leer.|
|Drucken eines bestimmten Berichts mit einem bestimmten Drucker für einen bestimmten Benutzer|Geben Sie Werte in den drei Feldern an.|

## <a name="see-also"></a>Siehe auch
[Arbeiten mit Dynamics NAV](ui-work-product.md)


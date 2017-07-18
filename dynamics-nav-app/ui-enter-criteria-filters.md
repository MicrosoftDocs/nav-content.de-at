---
title: Eingeben von Kriterien in Filtern
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
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Eingeben von Kriterien in Filtern
Wenn Sie nach Daten, wie Debitorennamen, Adressen oder Produktgruppen suchen möchten, geben Sie Kriterien ein. Beim Eingeben von Filterkriterien können alle Ziffern und Buchstaben verwendet werden, die auch normalerweise im Feld zulässig sind. Zudem können Sie Sonderzeichen verwenden, um eine zusätzliche Filterung der Ergebnisse zu erreichen.

## <a name="searching-using-the-quick-filter"></a>Suchen mithilfe des Schnellfilters
Sie können allen Seiten Filter hinzufügen, indem Sie Schnellfilter oder erweiterte Filter verwenden. Der Schnellfilter wird aktiviert, indem Sie das Lupensymbol in der oberen rechten Ecke einer Seite auswählen. Diese Filterart wird für die schnelle Eingabe von Kriterien verwendet.

**Wichtig**: Der Schnellfilter bietet einen einfachen Zugriff auf Filterdaten durch die Eingabe reinen Texts, bietet aber auch zahlreiche Optionen für Suchkriterien. Abhängig davon, ob Sie Freitext oder Text mit Symbolen eingeben, verhält sich der Schnellfilter unterschiedlich.  
- Wenn Sie Freitextangaben in den Suchkriterien eingeben, werden die Suchkriterien als die Groß-/Kleinschreibung nicht beachtend angesehen.  
- Wenn Sie Text mit Symbolen in den Suchkriterien eingeben, werden die Suchkriterien genau wie angegeben interpretiert, und die Groß-/Kleinschreibung wird berücksichtigt.

### <a name="quick-filter-criteria"></a>Schnelle Filterkriterien
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Suchkriterien</TH>
    <TH>Interpretiert als...</TH>
    <TH>Reklamationen...</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>Alle Datensätze, die den Text Mann enthalten und die Groß-/Kleinschreibung nicht beachten.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>Alle Datensätze, die den Text se enthalten und die Groß-/Kleinschreibung nicht beachten.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Beginnt mit „Man“, Groß-/Kleinschreibung beachtet</TD>
    <TD>Alle Datensätze, die mit dem Text Mann beginnen.</TD>
  </TR>
  <TR>
    <TD>'man'</TD>
    <TD>Exakter Text unter Berücksichtigung der Groß-/Kleinschreibung</TD>
    <TD>Alle Datensätze, die mit Mann genau übereinstimmen.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Endet mit, Groß-/Kleinschreibung beachtet</TD>
    <TD>Alle Datensätze, die mit mann enden.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Beginnt mit, Groß-/Kleinschreibung beachtet</TD>
    <TD>Alle Datensätze, die mit Mann beginnen.</TD>
  </TR>
</TABLE>

**Hinweis**: Sie können keinen Platzhalter beim Filtern in Aufzählungsfeldern, wie das Feld **Status** in Verkaufsaufträgen verwenden. Wenn Sie einen Filter für diese Art von Feld eingeben möchten, können Sie den numerischen Wert als Filterparameter eingeben. Beispielsweise im Feld **Status** in einem Verkaufsauftrag, der die Werte **Offen**, **Freigegeben**, **Genehmigung ausstehend** und **Vorauszahlung ausstehend** hat, verwenden Sie die Werte **0**, **1**, **2** und **3**, um für diese Optionen zu filtern.  

## <a name="see-also"></a>Siehe auch
[Arbeiten mit Dynamics NAV](ui-work-product.md)


---
title: Dimensionen
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: a1b38e74717e87bea6efb46f8f4e5236b6ec4e64
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

#<a name="dimensions"></a>Dimensionen
Bei Dimensionen handelt es sich um Daten, die Posten hinzugefügt werden, um diese für die Analyse zu kategorisieren. So können Sie beispielsweise Dimensionen einrichten, mit denen angegeben wird, aus welchem Projekt oder aus welcher Abteilung ein Posten stammt.
Dies ermöglicht die Verwendung von Dimensionen anstelle der Einrichtung separater Sachkonten für einzelne Abteilungen und Projekte. Die Daten können somit mit umfangreichen Informationen für die Analyse versehen werden, ohne dazu einen komplizierten Kontenplan einrichten zu müssen.
Dimensionen und Dimensionswerte können in unbegrenzter Anzahl eingerichtet werden.  

Sie richten beispielsweise eine Dimension mit dem Namen *Abteilung* ein und verwenden diese Dimension und einen Dimensionswert, wenn Sie Verkaufsbelege buchen. Dann können Sie beispielsweise später Business Intelligence-Daten danach abrufen, welche Artikel von welchen Abteilungen verkauft wurden.
Je mehr Dimensionen Sie einrichten und verwenden, auf desto detaillierteren Berichten können Sie Ihre Geschäftsentscheidungen basieren. Zum Beispiel kann ein einzelner Verkaufsposten mehrfache Dimensionsinformationen enthalten, auf welches Konto der Artikelverkauf gebucht wurde, wo der Artikel verkauft wurde, wer den Artikel verkauft hat und was für ein Debitor den Kauf getätigt hat.  

## <a name="using-dimensions"></a>Dimensionen verwenden
In einem Beleg, z. B. einem Verkaufsauftrag, können Sie Dimensionsinformationen sowohl für eine einzelne Belegzeile als auch für den Beleg selbst hinzufügen. Sie können beispielsweise im Fenster **Verkaufsauftrag** Dimensionswerte für die ersten beiden Shortcutdimensionen direkt in den Beleg eingeben und weitere Dimensionsinformationen hinzufügen, wenn Sie auf die Schaltfläche **Dimensionen** klicken.  
Wenn Sie stattdessen in einem Buch.-Blatt arbeiten, können Sie auf dieselbe Art und Weise Dimensionsinformationen hinzufügen, wenn Sie Shortcutdimensionen direkt als Felder in Buch.-Blattzeilen eingerichtet haben.  
Sie können Standarddimensionen für Konten oder Kontenarten festlegen, sodass Dimensionen und Dimensionswerte automatisch ausgefüllt werden.  

## <a name="dimension-sets"></a>Dimensionssätze
Ein Dimensionssatz ist eine eindeutige Kombination von Dimensionswerten. Er wird als Dimensionssatzposten in die Datenbank gespeichert. Jeder Dimensionssatzposten stellt einen einzelnen Dimensionswert dar. Der Dimensionssatz wird durch eine allgemeine Dimensionssatz-ID identifiziert, die jedem Dimensionssatzposten zugewiesen wird, der zum Dimensionssatz gehört.  

Wenn Sie eine neue Buch.-Blattzeile, einen Belegkopf oder eine Belegzeile erstellen, können Sie eine Kombination von Dimensionswerten angeben. Anstatt jeden Dimensionswert explizit in der Datenbank zu speichern, wird eine Dimensionssatz-ID der Buch.-Blattzeile, dem Belegkopf oder der Belegzeile zugewiesen, um den Dimensionssatz anzugeben.  

## <a name="see-also"></a>Siehe auch
[Finanzen](finance-setup.md)  
[Einrichtung von Dimensionen](finance-setup-setup-dimensions.md)  


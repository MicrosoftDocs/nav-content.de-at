---
title: 'Vorgehensweise: Ressourcen einrichten:'
author: SorenGP
ms.custom: na
ms.date: 12/14/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 72f5304e6a69a736c9df2cbb9ca64c5f3c5261a2
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-resources"></a>Vorgehensweise: Ressourcen einrichten:
Zur ordnungsgemäßen Verwaltung von Ressourcenaktivitäten ist die Einrichtung von Ressourcen sowie der zugehörigen Kosten und Preise erforderlich. Die projektbezogenen Preise, Rabatte und Kostenfaktorregeln werden auf der Projektkarte eingerichtet. Die Kosten und Preise können für einzelne Ressourcen, für Ressourcengruppen oder für alle verfügbaren Ressourcen des Unternehmens angegeben werden.

Wenn Ressourcen im Rahmen eines Projekts verbraucht oder verkauft werden, werden die zugehörigen Preise/Kosten aus den Informationen abgerufen, die Sie eingerichtet haben.

Der standardmäßige Betrag pro Stunde wird bei der Ressourcenerstellung angegeben. Wird also beispielsweise eine bestimmte Maschine fünf Stunden lang für ein Projekt verwendet, erfolgt die Berechnung des Projekts auf der Grundlage des Betrags pro Stunde.

## <a name="to-set-up-a-resource"></a>So richten Sie eine Ressource ein
Erstellen Sie für jede Ressource eine Karte,die Sie in " Projekte verwenden möchten.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus.
3. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.  

## <a name="to-set-up-a-resource-group"></a>Eine Ressourcengruppe einrichten
Mehrere Ressourcen können in einer Ressourcengruppe zusammengefasst werden. Alle Kapazitäten und Budgets der einzelnen Ressourcen werden für die Ressourcengruppe aufsummiert. Es ist ebenfalls möglich, Kapazitäten unabhängig von den summierten Werten oder zusätzlich einzugeben.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcengruppe** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Aktion **Neu** aus.
3. Füllen Sie die Felder je nach Bedarf aus.

## <a name="to-set-capacity-for-a-resource"></a>So legen Sie die Kapazität für eine Ressource fest 
Um zu berechnen wie viel Zeit eine Ressource in Projekten verbringen kann, muss deren Kapazität zuerst als verfügbare Zeit pro Periode im Arbeitskalender eingerichtet werden. Diese Einstellungen werden verwendet, wenn Sie Projektplanungszeilen ausfüllen, die die Ressource enthalten. Weitere Informationen finden Sie unter [Gewusst wie: Projekte erstellen](projects-how-create-jobs.md).

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Öffnen Sie die entsprechende Debitorenkarte und klicken dann auf die Aktion **Ressourcenkapazität**.
3. Geben Sie im Fenster **Ressourcenkapazität** im Feld **Anzeigen nach** die Länge der Periode an, wie beispielsweise **Tag**, die in Spalten im Inforegister **Ressourcenkapazität – Matrix** angezeigt wird.
4. Für jede Ressource in einer Zeile geben Sie für jede Periode in den Spalten die Anzahl von Stunden an, für die die Ressource verfügbar ist.
5. Alternativ, um die wöchentliche Kapazität der Ressource im Detail innerhalb eines Start- und Enddatums anzugeben, wählen Sie die Aktion **Kapazität festlegen** aus.
6. Füllen Sie im Fenster **Res.-Kapazität Einstellungen** die Felder nach Bedarf aus.
7. Wählen Sie die Aktion **Kapazität aktualisieren** aus. Das Fenster **Ressourcenkapazität** wird mit der eingegebenen Kapazität aktualisiert.
8. Schließen Sie das Fenster.

## <a name="to-set-up-alternate-resource-costs"></a>Um alternative Ressourcenkosten einzurichten:
Zusätzlich zu den Kosten, die in der Ressourcenkarte angegeben werden, können Sie auch alternative Kosten für jede Ressource einrichten. Wenn z. B. ein Mitarbeiter einen anderen Stundensatz für Überstunden hat, können Sie für diesen Arbeitstyp einen Einstandspreis einrichten. Die alternativen Kosten, die Sie für die Ressource einrichten, übersteuert den Einstandspreis auf der Ressourcenkarte, wenn Sie die Ressource im Ressourcen Buch.-Blatt buchen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Ressource, für die das Sie mindestens alternativen Einstandspreis einrichten möchten, und wählen die Aktion **Kosten** aus.  
3. Füllen Sie im Fenster **Ressourcenkosten** die Felder auf einer Zeile nach Bedarf aus.  
4. Wiederholen Sie Schritt 3 für jeden alternativen Einstandspreis, den Sie einrichten möchten.

**Hinweis**. Wenn Sie einen Ressourcenpreis einrichten möchten, der für alle Ressourcen und Ressourcengruppen gültig ist, öffnen Sie das Fenster **Ressourcen Einst.-Pr.**, und füllen Sie die Felder aus.

## <a name="to-set-up-alternate-resource-prices"></a>Um alternative Ressourcenkosten einzurichten:  
Zusätzlich zu den Kosten, die in der Ressourcenkarte angegeben werden, können Sie auch alternative Kosten für jede Ressource einrichten. Diese alternativen Preise können von Bedingungen abhängig sein. D. h. sie können davon abhängen, ob diese Ressource in einem bestimmten Projekt oder für einen bestimmten Arbeitstyp verwendet wird.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Ressource, für die das Sie mindestens alternativen Einstandspreis einrichten möchten, und wählen die Aktion **Kosten** aus.
3. Füllen Sie im Fenster **Ressourcenpreis** die Felder auf einer Zeile nach Bedarf aus.
4. Wiederholen Sie Schritt 3 für jeden alternativen Ressourcenpreis, den Sie einrichten möchten.

## <a name="see-also"></a>Siehe auch
[Projektmanagement einrichten](projects-setup-projects.md)  
[Projekte verwalten](projects-manage-projects.md)  
[Finanzen](finance-setup.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)         
[Verkauf verwalten](sales-manage-sales.md)      
[Arbeiten mit Dynamics NAV](ui-work-product.md)  

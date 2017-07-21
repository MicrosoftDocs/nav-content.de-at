---
title: 'Gewusst wie: Arbeiten mit Artikel-Attributen'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>Gewusst wie: Arbeiten mit Artikel-Attributen
Wenn Kundenanfragen zu einem Artikel, entweder über Korrespondenz oder über einen integrierten Webshop, gestellt werden, fragen oder suchen sie möglicherweise nach bestimmten Eigenschaften, wie z. B. Höhe und Modelljahr. Um diesen Kundenservice zu bieten, können Sie Ihren Artikeln Artikelattributwerte verschiedener Art zuordnen, die dann bei der Suche nsch Artikeln verwendet werden können.

Sie können den Artikelkategorien auch Artikelattribute zuordnen, die dann für die Artikel gelten, die die Artikelkategorien verwenden. Weitere Informationen finden Sie unter [So geht's: Artikel kategorisieren](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>So erstellen Sie Artikelattribute
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Artikelattribute** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Artikelattribute** die Aktion **Neu** aus.
3. Füllen Sie im Fenster **Artikelattribute** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

**Hinweis**: Wenn Sie im Feld **Art** **Option** ausgewählt haben, können Sie die Aktion **Artikelattributwerte** wählen, um Werte für die Artikelattribute zu erstellen. Weitere Informationen finden Sie im Abschnitt "So erstellen Sie Werte für Artikelattribute vom Typ Option".  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>So erstellen Sie Werte für Artikelattribute vom Typ Option
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Artikelattribute** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Artikelattribute** ein Artikelattribut vom Typ Option, für das Sie Werte erstellen möchten, und wählen Sie dann die Aktion **Artikelattributwerte** aus.
3. Füllen Sie im Fenster **Artikelattributwerte** die Felder wie benötigt aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

## <a name="to-assign-item-attributes-to-items"></a>So ordnen Sie Artikelattribute Artikeln zu:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Artikel** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Artikel** den Artikel, dem Sie Artikelattribute zuordnen möchten, und wählen Sie die Aktion **Attribute** aus.
3. Wählen Sie im Fenster **Artikelattributewerte** die Aktion **Neu** aus.
4. Klicken Sie im Feld **Attribute** auf die AssistEdit-Schaltfläche und wählen Sie ein bereits vorhandenes Artikelattribut aus. Alternativ wählen Sie die Aktion **Neu**, um zuerst ein neues Artikelattribut so zu erstellen, wie es im Abschnitt "So erstellen Sie Artikelattribute" erklärt wird.
5. Geben Sie im Feld **Wert** den Artikelattributwert ein, z. B. "2010" als Modelljahr-Attribut.
6. Für Artikelattribute vom Typ Option, klicken Sie die AssistEdit-Schaltfläche im Feld **Wert** und wählen einen Artikelattributwert aus. Alternativ wählen Sie die Aktion **Neu**, um zuerst einen neuen Artikelattributwert so zu erstellen, wie es im Abschnitt "So erstellen Sie Werte für Artikelattribute vom Typ Option" erklärt wird.
7. Wiederholen Sie die Schritte 4 bis 6 für alle Artikelattribute, die Sie dem Artikel zuweisen möchten.

## <a name="to-assign-item-attributes-to-item-categories"></a>So ordnen Sie ein Artikelattribut einer Artikelkategorie zu:
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Atrikelkategorien** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Artikelkategorie** die Artikelkategorie, der Sie den Artikelattributen zuordnen möchten, und wählen Sie die Aktion **Bearbeiten** aus.
3. Wählen Sie im Fenster **Artikelkategorie-Karte** im Inforegister **Attribute** die Aktion **Neu** aus.
4. Klicken Sie im Feld **Attribute** auf die AssistEdit-Schaltfläche und wählen Sie ein bereits vorhandenes Artikelattribut aus. Alternativ wählen Sie die Aktion **Neu**, um zuerst ein neues Artikelattribut so zu erstellen, wie es im Abschnitt "So erstellen Sie ein Artikelattribut" erklärt wird.
5. Klicken Sie im Feld **Standardwert** auf die AssistEdit-Schaltfläche und wählen Sie einen bereits vorhandenen Attributwert aus.
6. Wiederholen Sie die Schritte 4 bis 5 für alle Artikelattribute, die Sie der Artikelkategorie zuweisen möchten.

**Hinweis**: Artikelattribute für übergeordnete Artikelkategorien werden in untergeordneten Artikelkategorien übernommen. Dies wird durch das Feld **Geerbt von** im Inforegister **Attribute** angegeben. Weitere Informationen finden Sie unter [So geht's: Artikel kategorisieren](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>So filtern Sie nach Artikelattributen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Artikel** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **Attribute** die Aktion **Nach Attributen filtern** aus.
3. Klicken Sie im Fenster **Artikel nach Attributen filtern** auf die AssistEdit-Schaltfläche im Feld **Attribute**, und wählen Sie ein Artikelattribut aus.
4. Klicken Sie im Feld **Wert** auf die AssistEdit-Schaltfläche und wählen Sie einen Attributwert aus, mit dem Sie die Artikel filtern wollen.

    **Hinweis**: Sie können nur direkt Werte für Artikelattribute auswählen, die über feste Werte , wie z. B. Farbe, verfügen. Für Artikelattribute, die variable Werte, wie z. B. Breite haben, müssen Sie den Artikelattributwert festlegen, indem Sie zuerst eine Bedingung auswählen. Siehe dazu auch Schritt 5.
5. Klicken Sie im Feld **Wert** für ein variables Artikelattribut auf die AssistEdit-Schaltfläche.
6. Wählen Sie im Fenster **Filterwert angeben** im Feld **Bedingung** den Dropdownpfeil aus, und wählen Sie dann eine Bedingung aus.
7. Geben Sie im Feld **Wert** einen Attributwert ein, mit dem Sie die Artikel filtern wollen.

    **Beispiel**: Um Artikel zu filtern deren Beschreibung mit "blau" beginnt, füllen Sie die Felder wie folgt aus: **Attribut** -Feld: Materialbeschreibung, **Bedingung**-Feld: beginnt mit, **Wert**-Feld: blau.
8. Wählen Sie die Schaltfläche **OK** aus.   

Die Artikel im Fenster **Artikel** werden mit den angegebenen Artikelattributwerten gefiltert.

## <a name="see-also"></a>Siehe auch
[So geht'S: Artikel kategorisieren](inventory-how-categorize-items.md)    
[Vorgehensweise: Ein neues Produkt registrieren](inventory-how-register-new-products.md)  
[Verwalten des Lagerbestands](inventory-manage-inventory.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)


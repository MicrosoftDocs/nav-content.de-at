---
title: 'Vorgehensweise: Ein neues Produkt registrieren'
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
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a>Vorgehensweise: Ein neues Produkt registrieren

Produkte sind die Basis Ihres Unternehmens, die Waren oder Dienstleistungen, mit denen Sie handeln. Jedes Produkt muss als Artikelkarte registriert werden.

**Hinweis**: In Dynamics NAV wird ein Produkt als “Artikel” bezeichnet.

Artikelkarten verwahren die Informationen, die benötigt werden, um Produkte einzukaufen, einzulagern, zu liefern und zu berechnen.

Die Artikelkarte kann den Typ Bestand oder Service haben, um anzuzeigen, ob das Produkt eine physische Einheit oder eine Arbeitszeiteinheit ist. Neben einiger Felder, die sich mit den physischen Aspekten eines Artikels verknüpfen, arbeiten alle Felder auf einer Artikelkarte auf die gleiche Weise für Lagerartikel und Dienstleistungen. Weitere Informationen über den Verkauf von Artikeln finden Sie unter [So gehts: Produkte verkaufen](sales-how-sell-products.md) oder [So gehts: Fakturieren](sales-how-invoice-sales.md).

**Hinweis**: Wenn für verschiedene Artikelarten Artikelvorlagen existieren, öffnet sich ein Fenster, aus dem Sie eine entsprechende Artikelvorlage auswählen können, sobald eine neue Artikelkarte erstellt wird . Wenn nur eine Artikelvorlage vorhanden ist, verwenden neue Artikelkarten immer diese Vorlage.

## <a name="to-create-a-new-item-card"></a>So erstellen Sie eine neue Artikelkarte
1. Wählen Sie auf der Startseite die Aktion **Artikel**, um die Liste der vorhandenen Artikel zu öffnen.  
2. Wählen Sie im Fenster **Artikel** die Aktion **Neu** aus.

    Wenn nur eine Artikelvorlage vorhanden ist, öffnet sich eine neue Artikelkarte bei der einige Felder mit Informationen aus der Vorlage ausgefüllt sind.
3. Wählen Sie im Fenster **Vorlage für neuen Artikel auswählen** die Vorlage, die Sie für die neue Artikelkarte verwenden möchten.
4. Wählen Sie die Schaltfläche **OK**. Eine neue Artikelkarte wird geöffnet, in der einige Felder mit Daten aus der Vorlage ausgefüllt sind.
5. Wenn nötig, fahren Sie mit dem Ausfüllen oder Ändern der Felder auf der Artikelkarte fort. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

Im Inforegister **Verkaufspreise** können Sie spezielle Preise oder Rabatte anzeigen, die Sie für den Artikel gewähren, wenn bestimmte Kriterien, wie z.B. Debitor, Mindestbestellmenge oder Enddatum erfüllt sind. Jede Zeile stellt einen Sonderpreis oder einen Zeilenrabatt dar. Jede Spalte stellt ein Kriterium an, das gelten muss, um den Sonderpreis, den Sie im **Einheitenpreis**-Feld eingeben, oder den Zeilenrabatt, den Sie im **Zeilenrabatt**-Feld eingeben, zu rechtfertigen. Weitere Informationen finden Sie unter [Erfassen von Verkaufspreisen, Skonti und Zahlungsvereinbarungen](sales-how-record-sales-price-discount-payment-agreements.md)

Der Artikel ist nun erfasst und die Debitorenkarte ist bereit, in Einkaufs- und Verkaufsbelegen verwendet zu werden.

Wenn Sie diese Artikelkarte als Vorlage zum Erstellen neuer Artikelkarten verwenden möchten, können Sie sie als Vorlage speichern. Weitere Informationen finden Sie im folgenden Abschnitt.

## <a name="to-save-the-item-card-as-a-template"></a>So speichern Sie die Artikelkarte als Vorlage
1. Wählen Sie im Fenster **Artikelkarte** die Aktion **Als Vorlage speichern** aus. Das Fenster **Arikelvorlage** wird geöffnet und zeigt die Artikelkarte als Vorlage.
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Um Dimensionen in den Vorlagen wiederzuverwenden, wählen Sie die Aktion **Dimensionen**. Das Fenster **Dimensionen Vorlagenübersicht** wird geöffnet und zeigt alle Dimensionscodes, die für den Artikel eingerichtet werden.
4. Bearbeiten Sie oder geben Sie Dimensionscodes ein, die für die neuen Artikelkarten gelten, die mit der Vorlage erstellt wurden.
5. Wenn Sie die neue Artikelvorlage abgeschlossen haben, klicken Sie auf die Schaltfläche **OK**.

Die Artikelvorlage wird der Liste von Artikelvorlagen hinzugefügt, damit Sie diese verwenden können, um neue Debitorenkarten zu erstellen.

## <a name="see-also"></a>Siehe auch
  [Verwalten des Lagerbestands](inventory-manage-inventory.md)  
  [Einkauf verwalten](purchasing-manage-purchasing.md)  
  [Verkauf verwalten](sales-manage-sales.md)


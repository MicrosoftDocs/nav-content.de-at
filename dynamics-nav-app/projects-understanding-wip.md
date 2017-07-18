---
title: "Verständnis - WIP-Methoden"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f21357897dd730d96db7abab469d5958c6fe117c
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="understanding-wip-methods"></a>Verständnis - WIP-Methoden

Dynamics NAV unterstützt die folgenden Methoden zum Berechnen und Aufzeichnen des Werts des Umlaufbestands.

|WIP-Methode |Formel |Berechnungsbeschreibung|
|-----------|--------------------|-----------------------|
|Einstandswert|Realisierte Einnahmen = Fakturierbarer, verrechneter Preis<br /><br /> Erwarteter Einstandsbetrag = Fakturierbarer Gesamtbetrag * geplanter Einstandspreisanteil<br /><br /> WIP-Kosten = \((Prozentsatz der Fertigung -In Rechnung gestellt %)\) x Erwarteter Einstandsbetrag<br /><br /> Prozentsatz der Fertigung = Gesamtverbrauchskosten / Geplante Gesamtkosten<br /> Fakturiert % = Fakturierbarer verrechneter Preis<br /><br /> Verrechenbarer Gesamtpreis der deklarierten Kosten = Verbrauch Gesamtkosten - WIP|Berechnungen vom Typ "Einstandswert" beginnen mit der Berechnung des Werts dessen, was bereitgestellt wurde. Zu diesem Zweck wird ein Anteil des erwarteten Einstandsbetrags (basierend auf dem Prozentsatz der Fertigstellung) herangezogen. Fakturierte Einstandsbeträge werden abgezogen, indem ein Anteil des erwarteten Einstandsbetrags (basierend auf dem fakturierten Prozentsatz) herangezogen wird.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag", "Plan Gesamtpreis" und "Plan Gesamtkosten" eingegeben werden.|
|Vertriebskosten|Realisierte Einnahmen = Fakturierbarer, verrechneter Preis<br /><br /> Deklarierte Kosten = Plan Gesamtkosten x Fakturierter Prozentbetrag<br /><br /> Fakturiert % = Fakturierbarer Rechnungsbetrag / Fakturierbarer Gesamtpreis<br /><br /> \(Fakturiert % ist als Spalte in Projektaufgabenzeilen vorhanden\)<br /><br /> WIP-Kosten = Verbrauch (Einstandsbetrag) - deaktivierte Kosten|Berechnungen vom Typ "Vertriebskosten" beginnen mit der Berechnung der deklarierten Kosten. Kosten werden proportional auf der Grundlage von "Plan Gesamtkosten" realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden.|
|Verkaufswert|Deaktivierte Kosten = Verbrauch (Einstandsbetrag)<br /><br /> Realisierte Einnahmen = Verbrauch (Verkaufspreis) x geplanter Rechnungsanteil<br /><br /> Kosten Zu-/Abschlag % = Fakturierbarer Gesamtbetrag / Plan Gesamtkosten<br /><br /> WIP Verkäufe = deklarierte Verkäufe - Fakturierbarer Rechnungspreis|Bei Berechnungen vom Typ "Verkaufswert" werden die Einnahmen proportional basierend auf "Verbrauch Gesamtkosten" und dem erwarteten Kostenzu-/-abschlagsanteil realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden.|
|Prozentsatz der Fertigung|Deaktivierte Kosten = Verbrauch (Einstandsbetrag)<br /><br /> Realisierte Einnahmen = Fakturierbarer Gesamtbetrag x Prozentsatz der Fertigung<br /><br /> Prozentsatz der Fertigung = Gesamtverbrauchskosten / Geplante Gesamtkosten<br /><br /> \(Wird in Projektplanungszeilen als "Kosten Abschluss %" angegeben\)<br /> WIP Verkäufe = deklarierte Verkäufe - Fakturierbarer Rechnungspreis|Bei Berechnungen vom Typ "Prozentsatz der Fertigung" werden Einnahmen proportional – auf der Grundlage des Prozentsatzes der Fertigstellung, also "Verbrauch" contra "Einstandspreis" – realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden.|
|Abgeschl. Vertrag|WIP-Betrag = WIP-Einstandsbetrag = Verbrauch \(Gesamtkosten\)<br /><br /> WIP-Verkaufsbetrag = Fakturierbarer \(Rechnungsbetrag\)|Bei der Option "Abgeschl. Vertrag" werden Einnahmen und Kosten erst nach Abschluss des Projekts realisiert. Dies kann nützlich sein, wenn die Schätzungen der Kosten und Einnahmen für das Projekt äußerst unsicher sind.<br /><br /> Der gesamte Verbrauch wird auf das Konto für Kosten nicht abgeschlossener Arbeiten \(Aktiva\) gebucht, und alle fakturierten Verkäufe werden auf das Konto für fakturierte Verkäufe nicht abgeschlossener Arbeiten \(Passiva\) gebucht, bis das Projekt abgeschlossen ist.|

## <a name="see-also"></a>Siehe auch
[Projekte verwalten](projects-manage-projects.md)  
[Finanzen](finance-setup.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)         
[Verkauf verwalten](sales-manage-sales.md)      
[Arbeiten mit Dynamics NAV](ui-work-product.md)  


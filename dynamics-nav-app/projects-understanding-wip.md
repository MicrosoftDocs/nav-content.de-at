---
title: "WIP-Methoden für die Berechnung und die Aufzeichnung des Projektstatus"
description: "Beschreibt die unterschiedlichen Umlaufbestand (WIP)-Methoden, die verwendet werden können, um Finanzdaten für Projekte zu senden und zu überwachen, die im Umlaufbestand sind."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: work in process, work in progress, calculate project WIP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4a472d7a45cacfe4cd2534747f447a1e4ca7a303
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="understanding-wip-methods"></a>Verständnis - WIP-Methoden
[!INCLUDE[d365fin](includes/d365fin_md.md)]unterstützt die folgenden Methoden zum Berechnen der Inventur und der Wert der unfertigen Arbeit.

| WIP-Methode | Formel | Berechnungsbeschreibung |
| --- | --- | --- |
| Einstandswert |Realisierte Einnahmen = Fakturierbarer, verrechneter Preis<br /><br /> Erwarteter Einstandsbetrag = Fakturierbarer Gesamtbetrag * geplanter Einstandspreisanteil<br /><br /> WIP-Kosten = (Prozentsatz der Fertigung -In Rechnung gestellt %) x Erwarteter Einstandsbetrag<br /><br /> Prozentsatz der Fertigung = Gesamtverbrauchskosten / Geplante Gesamtkosten<br /> Fakturiert % = Fakturierbarer verrechneter Preis<br /><br /> Verrechenbarer Gesamtpreis der deklarierten Kosten = Verbrauch Gesamtkosten - WIP |Berechnungen vom Typ "Einstandswert" beginnen mit der Berechnung des Werts dessen, was bereitgestellt wurde. Zu diesem Zweck wird ein Anteil des erwarteten Einstandsbetrags (basierend auf dem Prozentsatz der Fertigstellung) herangezogen. Fakturierte Einstandsbeträge werden abgezogen, indem ein Anteil des erwarteten Einstandsbetrags (basierend auf dem fakturierten Prozentsatz) herangezogen wird.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag", "Plan Gesamtpreis" und "Plan Gesamtkosten" eingegeben werden. |
| Vertriebskosten |Realisierte Einnahmen = Fakturierbarer, verrechneter Preis<br /><br /> Deklarierte Kosten = Plan Gesamtkosten x Fakturierter Prozentbetrag<br /><br /> Fakturiert % = Fakturierbarer Rechnungsbetrag / Fakturierbarer Gesamtpreis<br /><br /> (Fakturiert % ist als Spalte in Projektaufgabenzeilen vorhanden)<br /><br /> WIP-Kosten = Verbrauch (Einstandsbetrag) - deaktivierte Kosten |Berechnungen vom Typ "Vertriebskosten" beginnen mit der Berechnung der deklarierten Kosten. Kosten werden proportional auf der Grundlage von "Plan Gesamtkosten" realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden. |
| Verkaufswert |Deaktivierte Kosten = Verbrauch (Einstandsbetrag)<br /><br /> Realisierte Einnahmen = Verbrauch (Verkaufspreis) x geplanter Rechnungsanteil<br /><br /> Kosten Zu-/Abschlag % = Fakturierbarer Gesamtbetrag / Plan Gesamtkosten<br /><br /> WIP Verkäufe = deklarierte Verkäufe - Fakturierbarer Rechnungspreis |Bei Berechnungen vom Typ "Verkaufswert" werden die Einnahmen proportional basierend auf "Verbrauch Gesamtkosten" und dem erwarteten Kostenzu-/-abschlagsanteil realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden. |
| Prozentsatz der Fertigung |Deaktivierte Kosten = Verbrauch (Einstandsbetrag)<br /><br /> Realisierte Einnahmen = Fakturierbarer Gesamtbetrag x Prozentsatz der Fertigung<br /><br /> Prozentsatz der Fertigung = Gesamtverbrauchskosten / Geplante Gesamtkosten<br /> (Wird in Projektplanungszeilen als "Kosten Abschluss %" angegeben)<br /><br /> WIP Verkäufe = deklarierte Verkäufe - Fakturierbarer Rechnungspreis |Bei Berechnungen vom Typ "Prozentsatz der Fertigung" werden Einnahmen proportional – auf der Grundlage des Prozentsatzes der Fertigstellung, also "Verbrauch" contra "Einstandspreis" – realisiert.<br /><br /> Damit korrekte Ergebnisse erzielt werden können, müssen für das gesamte Projekt Werte für "Fakturierbarer Gesamtbetrag" und "Plan Gesamtkosten" eingegeben werden. |
| Abgeschl. Vertrag |WIP-Betrag = WIP-Einstandsbetrag = Verbrauch (Einstandsbetrag)<br /><br /> WIP-Verkaufsbetrag = Fakturierbarer (Rechnungsbetrag) |Bei der Option "Abgeschl. Vertrag" werden Einnahmen und Kosten erst nach Abschluss des Projekts realisiert. Dies kann nützlich sein, wenn die Schätzungen der Kosten und Einnahmen für das Projekt äußerst unsicher sind.<br /><br /> Der gesamte Verbrauch wird auf das Konto für Kosten nicht abgeschlossener Arbeiten (Aktiva) gebucht, und alle fakturierten Verkäufe werden auf das Konto für fakturierte Verkäufe nicht abgeschlossener Arbeiten (Passiva) gebucht, bis das Projekt abgeschlossen ist. |

## <a name="see-also"></a>Siehe auch
[Projektmanagement](projects-manage-projects.md)  
[Finanzen](finance.md)  
[Einkauf](purchasing-manage-purchasing.md)         
[Verkauf](sales-manage-sales.md)      
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  


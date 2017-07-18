---
title: Geplanter voraussichtlicher Verkauf und Lagerbestand
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 765527ed4f4800acec20f0abbd4374e95c9c36dc
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Geplanter voraussichtlicher Verkauf und Lagerbestand für Dynamics NAV
Lagerverwaltung ist ein Austausch zwischen Serviceabteilung und Verwaltung der Kosten. Auf der einen Seite benötigt ein niedriger Bestand weniger Betriebskapital, andererseits führen fehlende Lagerbestände evtl. zu entgangenen Verkäufen. Die Erweiterung "Geplanter voraussichtlicher Verkauf und Lagerbestand" sagt potenzielle Verkäufe anhand der historischen Daten voraus und gibt eine klare Übersicht über erwartete fehlende Lagerbestände. Auf Grundlage der Planung helfen die Erweiterungen dabei, Beschaffungsanfragen an Ihre Kreditoren zu stellen und Zeit zu spraren.  

## <a name="setting-up-forecasting"></a>Einrichten der Planung
In Dynamics NAV müssen Sie die Verbindung zu Azure Machine Learning (Azure ML) einrichten. Weitere Informationen finden Sie unter [Vorgehensweise: Anmelden von Dynamics NAV im Azure Management Portal](ui-how-register-dynamics-nav-azure.md). Wenn Sie eine Verbindung erstellt haben, können Sie die Planung konfigurieren, um eine andere Art von Periode zu erfassen, zum Beispiel von der Planung nach Monaten auf die Planung nach Quartal. Sie können außerdem die Anzahl von Perioden zur Berechnung der Planung festlegen, abhängig davon, wie differenziert die Planung sein soll. Wir empfehlen, dass Sie die Planung nach Monaten und über einen Zeitraum von 12 Monaten prognostizieren.  

## <a name="using-the-forecasts"></a>Planungen verwenden
Die Erweiterung verwendet Azure ML Funktionen, um künftige Verkäufe basierend auf dem Verkaufsverlauf vorauszusagen und so fehlenden Lagerbestand zu vermeiden. Wenn Sie beispielsweise einen Artikel im Fenster **Artikel** auswählen, zeigt das Diagramm im Bereich **Artikelplanung** die geschätzten Verkäufe dieses Artikels in der kommenden Periode an. Auf diese Weise können Sie sehen, ob der Artikel evtl. in Kürze nicht mehr am Lager sein wird.  

Sie können auch die Erweiterung verwenden, um vorzuschlagen, wann der Lagerbestand aufgefüllt werden soll. Wenn Sie beispielsweise eine Einkaufsbestellung für Fabrikam erstellen, da Sie deren neuen Schreibtischstuhl kaufen möchten, wird die Erweiterung "Geplanter voraussichtlicher Verkauf und Lagerbestand" vorschlagen, dass Sie ebenfalls den LONDON-Schreibtischstuhl wiedereinlagern, den Sie üblicherweise von diesem Kreditor kaufen. Der Grund dafür ist, dass die Erweiterung vorausplant, dass der LONDON-Schreibtischstuhl in den kommenden zwei Monaten nicht mehr am Lager verfügbar sein wird und Sie bereits jetzt mehr Stühle bestellen sollten.  

## <a name="see-also"></a>Siehe auch
[Verkauf verwalten](sales-manage-sales.md)  
[Verwalten des Lagerbestands](inventory-manage-inventory.md)  
[Anpassen des Dynamics NAV mithilfe der Erweiterungen](ui-extensions.md)  
[Vorgehensweise: Dynamics NAV im Azure Management Portal anmelden](ui-how-register-dynamics-nav-azure.md)  


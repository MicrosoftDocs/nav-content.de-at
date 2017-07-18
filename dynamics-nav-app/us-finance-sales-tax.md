---
title: Verkaufssteuer sowie Steuergruppen in den USA und in Kanada
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
ms.openlocfilehash: f70a191fc8392bf1685c08c7e905ac96ba7ed069
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-tax-groups-in-the-us-and-canada"></a>Verkaufssteuer sowie Steuergruppen in den USA und in Kanada
Wenn Sie Dynamics NAV zum ersten Mal starten, können Sie eine unterstützte Einrichtung in Anspruch nehmen, um Verkaufssteuersteuerinformationen für Ihre Firma und optional für Ihre Debitoren und Kreditoren schnell und einfach zu einrichten. In Minutenschnelle sind Sie bereit, Verkaufsbelege und Einkaufsbelege mit der Verkaufssteuer zu erstellen, die richtig berechnet werden kann.
Wenn Sie auf das leere "Mein Unternehmen" umlagern, empfiehlt es sich, dass Sie beginnen, jedes einzelne der unterstützen Setuphandbücher zu verwenden, einschließlich demjenigen für die Verkaufssteuer. Wenn Sie es vorziehen, die Verkaufssteuer selber einzurichten, beschreibt dieser Artikel, was Sie berücksichtigen müssen.  

## <a name="tax-groups-tax-areas-and-tax-jurisdictions"></a>Steuergruppen, Steuergebiete und Steuerzuständigkeiten
In Dynamics NAV besteht eine Steuergruppe aus einer Gruppe von Artikeln oder Ressourcen, die den gleichen Steuersätzen unterliegen. Beispielsweise können Sie eine Steuergruppe für steuerpflichtige Artikel und eine weitere für nicht zu versteuernde Artikel einrichten. Sie müssen Steuergruppencodes den Lagerartikeln und den Sachkonten zuweisen. Ebenso müssen Sie Steuergebietscodes, Lagerorte und Ihren eigenen Mandanteneinstellungen den Debitoren zuweisen. Das unterstützende Setuphandbuch hilft Ihnen dabei.  

Jedes Steuergebiet ist ein Gruppierung von Verkaufssteuerzuständigkeitsbereichen auf Grundlage einer bestimmten geografischen Lage. Beispielsweise hat das Steuergebiet in Miami, Florida, drei Verkaufssteuerzuständigkeitsbereiche: Stadt (Miami), Gemeinde (Dade) und Staat (Florida). Dynamics NAV schließt eine begrenzte Zahl von Steuergebieten mit einer Standardkonfiguration ein, Sie können sie aber ändern und neue Steuergebiete hinzufügen.  

Wenn Sie neue Steuergebiete und Steuerzuständigkeiten einrichten, müssen Sie sicherstellen, dass Sie die richtig Felder ausfüllen. In den Vereinigten Staaten von Amerika können Staaten, Gemeinden, Orte und Lokale Verkaufssteuern belasten. In Kanada verlangen die Bundesregierung und die Provinzen Verkaufssteuern. Unternehmen erheben und leisten Verkaufssteuern an diese Regierungsbehörden für die Produkte, die an Endbenutzer verkauft werden. Verkaufssteuer kann auch zur vorhandenen Verkaufssteuer berechnet werden. Beispielsweise kann Steuer auf einem Verkaufsrechnungsbetrag berechnet werden, der bereits die Steuerbeträge von anderen Zuständigkeitsbereichen umfasst.  

In Kanada müssen Steuerbeträge für jede Steuerzuständigkeit detailliert dokumentiert sein. Bis zu vier Zuständigkeiten können in einem Beleg angezeigt werden und die Zuständigkeiten, die die gleiche Druckreihenfolge haben, werden zusammengefasst, wenn diese gedruckt werden.

## <a name="tax-details"></a>Steuerdetails
Das Fenster **Steuerdetails** zeigt verschiedene Kombinationen von Verkaufssteuerzuständigkeitsbereichen und Mehrwertsteuergruppen an, um Verkaufssteuersätze einzurichten. Für jede Steuerzuständigkeit empfiehlt es sich, dass Sie eine Steuergruppe für normale Verkaufssteuer, eine andere Steuergruppe für Artikel oder Services, die nicht besteuert werden, und eine Nachsteuergruppe für jede Art Artikel oder Service einrichten, die mit einem anderen Verkaufssteuersteuersatz in diesem Steuerzuständigkeitsbereich vorhanden ist.  

Wenn Sie in den USA einem Debitor an einem Lagerort verkaufen, in dem Sie keinen ** *Status oder gültigen Lagerort haben, erheben Sie keine Verkaufssteuer. Bei Lagerorten, in denen Sie keinen Status haben, ist sichergestellt, dass sowohl die Felder **Steuer unter dem Minimum** und die **Steuer über dem Maximum** 0.00 aufweisen.  

## <a name="see-also"></a>Siehe auch
[Finanzen](finance-setup.md)  
[Finanzen Einrichten](finance-setup-setup-finance-setup.md)  
[Verkaufssteuer sowie Steuern auf Waren und Dienstleistungen in Kanada](ca-finance-setup-tax.md)  
[Einfaches Einrichten der Verkaufssteuer](https://madeira.microsoft.com/en-us/blog/sales-tax-setup-made-easy)  


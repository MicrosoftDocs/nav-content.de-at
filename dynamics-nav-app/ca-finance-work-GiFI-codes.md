---
title: 'So gehts: Arbeiten mit GIFI-Codes in Kanada'
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a>So gehts: Arbeiten mit GIFI-Codes in Kanada
Steuerinformationen können Sachkonten, Berichte, GuV, Bilanzen und Auszüge nicht ausgeschütteter Gewinne beinhalten. Steuerinformationen werden mithilfe von Codes klassifiziert. Die Verwendung von Codes hilft den Behörden, Daten zu bearbeiten, sie für die elektronische Speicherung vorzubereiten und Steuerdaten elektronisch zu überprüfen . Außerdem hilft die Verwendung von Codes statistischen Organisationen, effizienter zu arbeiten, da Finanzdaten zeitnah zur Verfügung stehen. Weitere Informationen finden Sie auf der [Webseite der Canada Revenue Agency](http://www.cra-arc.gc.ca/).

Die Canada Revenue Agency verwendet den General Index of Financial Information (GIFI), um Finanz- und Steuerdaten zu erfassen, zu überprüfen und elektronisch zu verarbeiten. Üblicher Weise werden GIFI-Codes nur für die Buchungskonten zugewiesen, sodass jede Zusammenzählung durch die Steuervorbereitungs-Software ausgeführt wird.

Wenn ein Konto einem GIFI-Code zugeordnet ist, wird es der Einnahmenenagentur unter diesem Code gemeldet. Mehrere Konten können alle denselben GIFI-Code haben, aber jedes Konto kann nur einen GIFI-Code haben.

Sie können Saldoinformationen mit dem GIFI-Code exportieren und die exportierte Datei in Excel speichern. Dies ist nützlich, wenn Sie Informationen an Ihre Steuervorbereitungs-Software übertragen wollen.

## <a name="to-set-up-gifi-codes"></a>So richten Sie GIFI-Codes ein:
In Dynamics NAV müssen Sie GIFI-Codes für Sachkonten, Berichte, Bilanzen, Einkommensblätter und Auszüge nicht ausgeschütteter Gewinne einrichten.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **GIFI-Codes** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie im Fenster **GIFI Codes** die Aktion **Neu** aus.
3. Richten Sie GIFI-Codes ein, indem Sie die Felder ausfüllen. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

## <a name="to-associate-gifi-codes-with-gl-accounts"></a>So ordnen Sie GIFI-Codes Sachkonten zu
Um Finanzdaten mit GIFI-Code zu übermitteln, muss jeder GIFI-Code den entsprechenden Konten im Kontenplan zugeordnet werden.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Kontenplan** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie ein entsprechendes Sachkonto, und wählen Sie dann die Aktion **Bearbeiten** aus.
3. Wählen Sie im Inforegister **Kostenrechnung** im Feld **GIFI Code** den entsprechenden GIFI-Code aus.

## <a name="to-view-account-balances-using-the-gifi-code-report"></a>So verwenden Sie den GIFI-Code-Bericht, um Kontosalden anzuzeigen
Sie können Ihre Kontosalden mit dem GIFI-Code überprüfen, indem Sie den **Kontosalden durch GIFI-Code**-Bericht verwenden.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Kontosalden durch GIFI-Code** ein. Wählen Sie dann den zugehörigen Link aus.
2. Legen Sie fest, was in den Bericht einbezogen werden soll, indem Sie die Felder ausfüllen. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Wählen Sie die **Druck** oder **Vorschau** Schaltfläche.

## <a name="to-export-balance-information-using-gifi-codes"></a>So exportieren Sie Saldoinformationen mithilfe von GIFI-Codes
Sie können Saldoinformationen mithilfe von GIFI-Codes exportieren und die exportierte Datei in Excel speichern. Sie können die Datei ändern, speichern oder löschen. Sie können die Datei verwenden, um Informationen an Ihre Steuervorbereitungs-Software zu übertragen.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **GIFI Info. in Excel exportieren** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie an, was Sie in Excel exportieren wollen, indem Sie die Felder ausfüllen. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Wählen Sie die Schaltfläche **OK**.

**Hinweis:** Die Excel-Datei hat folgende Eigenschaften:

* Der Saldo wird auf den nächsten Prozentsatz gerundet, aber der Zellenwert behält den gleichen Prozentsatz bei, den er auch in der Finanzbuchhaltung hat.

* Negative Zahlen werden als positive Zahl in Klammern dargestellt. Dementsprechend wird -123 als (123) dargestellt.

## <a name="see-also"></a>Siehe auch
[Finanzen](finance-setup.md)   
[Zentrale Finanzprozesse einrichten](finance-setup-setup-finance-setup.md)


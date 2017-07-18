---
title: 'So geht''s: Allgemeine Anlagen-Informationen einrichten'
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
ms.openlocfilehash: 8c0e33a78d47ccfbe39a78f81e31b69f61fd4f80
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-general-fixed-assets-information"></a>So geht's: Allgemeine Anlagen-Informationen einrichten
Bevor Sie Anlagen verwalten können, müssen Sie Standardsachkonten, Verteilungsschlüssel, Buch.-Blattvorlagen und -namen für Anlagenbuchungen und -umbuchungen einrichten, und Sie können Anlagen in Klassen, wie beispielsweise materiell und immateriell, klassifizieren.

## <a name="to-set-up-general-default-values-for-fixed-assets"></a>So richten Sie allgemeine Vorgabewerte für Anlagen ein
Im Fenster **Anlagen Einrichtung** definieren Sie das allgemeine Verhalten oder die Anlagenfunktionalität und richten Belegnummernserien ein.

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlageneinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

## <a name="to-set-up-fixed-asset-posting-groups"></a>So richten Sie Anlagenbuchungsgruppen ein  
Sie können Buchungsgruppen verwenden, um Gruppen von Anlagen zu definieren. Posten in diesen Buchungsgruppen werden auf die gleichen Sachkonten gebucht.  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagenbuchungsgruppen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die Aktion **Neu** aus.
3. Füllen Sie im Fenster **Anlagenbuchungsgruppenkarte** die notwendigen Felder aus.

    **Hinweis**: Um sicherzustellen, dass Gegenkonten für verschiedene Anlagenbuchungen automatisch eingefügt werden, wenn Sie die Aktion **Anlagengegenkonto einfügen** in den Buch.-Blattzeilen auswählen, führen Sie den nächsten Schritt auf Grundlage der Buchung von Zuschreibungen aus.
4. Geben Sie im Inforegister **Gegenkonto** im Feld **Gegenkto. Zuschreibung** das Sachkonto ein, auf das die Gegenposten für Zuschreibungen gebucht werden sollen.

Weitere Informationen zur Verwendung der Aktion **Anlagengegenkonto einfügen** in den Anlagen Fibu Buch.-Blattzeilen, finden Sie beispielsweise unter [So geht's: Neubewerten von Anlagen](fa-how-revalue.md).

## <a name="to-set-up-fixed-asset-allocation-keys"></a>So richten Sie Anlagenverteilungsschlüssel ein  
Transaktionen können auf verschiedene Kostenstellen und/oder Kostenträger verteilt werden, abhängig von benutzerdefinierten Verteilungsschlüsseln. Sie können z. B. einen Verteilungsschlüssel einrichten, um die AfA-Beträge von Autos zu 35 Prozent auf die Verwaltung und zu 65 Prozent auf den Verkauf zu verteilen. Weitere Informationen finden Sie unter [So geht's: Verteilungsschlüssel in Fibu Buch.-Blättern einrichten](ui-how-use-allocation-keys-general-journals.md).

Verteilungsschlüssel gelten für feste Anlagenklassen, nicht für einzelne Anlagen.  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagenbuchungsgruppen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie im Fenster **Anlagenbuchungsgruppen** die Aktion **Verteilungen**, und wählen Sie dann eine Buchungsart aus.
3. Füllen Sie im Fenster **Anlagenverteilungen** die notwendigen Felder aus.
4. Wiederholen Sie Schritt 2 und 3 für alle Buchungsarten, für die Sie Verteilungsschlüssel einrichten wollen.

## <a name="to-set-up-fixed-asset-journal-templates"></a>So richten Sie Anlagen Buch.-Blattvorlagen ein  
Eine Vorlage ist ein vordefiniertes Layout für ein Buch.-Blatt. Eine Vorlage enthält Informationen über Verfolgungscodes, Berichte und Nummernserien. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).

Dynamics NAV erstellt automatisch eine Anlagen Buch.-Blattvorlage, wenn Sie zum ersten Mal das Fenster **Anlagen Buch.-Blatt** öffnen. Sie können aber auch zusätzliche Buch.-Blattvorlagen einrichten.  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anl. Buch.-Blattvorlagen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Felder je nach Bedarf aus.

## <a name="to-set-up-fixed-asset-journal-batches"></a>So richten Sie Anlagen Buch.-Blattnamen ein
Sie können mehrere Buch.-Blattnamen erstellen, d. h. mehrere individuelle Buch.-Blätter für jede Buch.-Blattvorlage. Sie können z. B. für jeden Mitarbeiter ein eigenes Buch.-Blatt benutzen, dass die Initialien des Mitarbeiters im Namen verwendet. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anl. Buch.-Blattvorlagen** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die entsprechende Buch.-Blattvorlage und dann die Aktion **Buch.-Blattnamen** aus.
3. Füllen Sie im Fenster **Anlagen Buch.-Blattnamen** die notwendigen Felder aus.

## <a name="to-set-up-fixed-asset-reclassification-journal-templates"></a>So richten Sie Vorlagen für Anlagenumbuchung ein  
Spezifische Umbuch.-Blätter dienen zum Transferieren, Teilen oder Zusammenfassen von Anlagen. Dynamics NAV erstellt automatisch eine Anlagen Umbuch.-Blattvorlage, wenn Sie zum ersten Mal das Fenster **Anlagen Umbuch.-Blatt** öffnen. Sie können aber auch zusätzliche Anlagen Umbuch.-Blattvorlagen einrichten. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen Umbuch.-Blattvorl.** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Felder je nach Bedarf aus.

## <a name="to-set-up-fixed-asset-reclassification-journal-batches"></a>So richten Sie Anlagen-Umbuchungsblätter ein  
Sie können mehrere Buch.-Blattnamen erstellen, d. h. mehrere individuelle Buch.-Blätter für jede Umbuch.-Blattvorlage. Sie können z. B. für jeden Mitarbeiter ein eigenes Umbuch.-Blatt verwenden, das die Initialen des Mitarbeiters im Namen verwendet. Weitere Informationen finden Sie unter [Arbeiten mit Fibu Buch.-Blättern](ui-work-general-journals.md).
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Anlagen Umbuch.-Blattvorl.** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie die entsprechende Buch.-Blattvorlage und dann die Aktion **Buch.-Blattnamen** aus.
3. Füllen Sie im Fenster **Anlagen Umbuch.-Blattnamen** die notwendigen Felder aus.

## <a name="to-set-up-fixed-asset-class-codes"></a>So richten Sie Anlagenklassencodes ein  
Die Anlagenklassencodes können zur Gruppierung von Anlagen dienen, beispielsweise in materielle und immaterielle Anlagen.
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlagenklassen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie die Codes und die Namen für die Klassen ein, die Sie erstellen möchten.

## <a name="to-set-up-fixed-asset-subclass-codes"></a>So richten Sie Anlagensachgruppencodes ein
Sie können Anlagensachgruppencodes verwenden, um Anlagen innerhalb der Hauptgruppen zu gruppieren, z. B. in Gebäude, Fahrzeuge, Möbel oder Maschinen.  
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlagensachgruppen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie die Codes und die Namen für die Klassen ein, die Sie erstellen möchten.

## <a name="to-set-up-fixed-asset-location-codes"></a>So richten Sie Anlagenstandortcodes ein
Verwenden Sie diese Anlagenstandortcodes, um den Standort von Anlagen zu erfassen, beispielsweise Vertrieb, Empfang, Verwaltung, Produktion oder Lager. Diese Information dient beispielsweise dazu, für Versicherungen anzugeben, in welchem Bereich des Unternehmens oder an welchem Ort sich eine Anlage im Einsatz befindet.
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Anlagenstandorte** ein. Wählen Sie dann den zugehörigen Link aus.
2. Geben Sie die Codes und die Namen für die Anlagenstandorte ein, die Sie erstellen möchten.

## <a name="to-register-opening-entries"></a>So erfassen Sie Eröffnungsposten  
Falls Sie die Anlagen in Dynamics NAV zum ersten Mal verwenden, müssen Sie zuerst den Anwendungsbereich "Finanzbuchhaltung" einrichten, bevor Sie Anlagen einrichten können. Wie dies erfolgt, hängt davon ab, ob Anlagen in die Finanzbuchhaltung integriert sind.  

 Die folgende Vorgehensweise wird verwendet, wenn Anlagentransaktionen in die Finanzbuchhaltung gebucht werden.  

1. Stellen Sie sicher, dass Sie alle grundlegenden Einrichtungsschritte für Anlagen ausgeführt haben.  
2. Erstellen Sie eine Anlagenkarte für jede bestehende Anlage.  
3. Richten Sie Anlagenabschreibungsbücher ein.  
4. Aktivieren Sie die Fibu-Integration, indem Sie die folgenden Schritte ausführen.
5. Geben Sie im Feld **Suchen** einen Wert für **AfA-Bücher** ein, und wählen Sie dann den zugehörigen Link aus.  
6. Wählen Sie das entsprechende AfA-Buch aus. Wählen Sie auf der Registerkarte **Start** in der Gruppe **Verwalten** die Option **Bearbeiten** aus, um das Fenster **AfA-Buch - Karte** zu öffnen.
7. Vergewissern Sie sich im Inforegister **Integration**, dass alle Felder leer sind, indem Sie alle Häkchen löschen. Sind mehrere AfA-Bücher vorhanden, aktivieren Sie die Fibu-Integration für jedes Buch.  
8. Geben Sie im Anlagen Buch.-Blatt die folgenden Zeilen für jede Anlage ein:
    - eine Zeile mit den Anschaffungskosten
    - Eine Zeile mit der kumulierten AfA zum Ende des vorigen Geschäftsjahres.
    - Eine Zeile mit der kumulierten AfA vom Anfang des laufenden Geschäftsjahres bis zu dem Datum, ab dem Dynamics NAV mit der Berechnung der Abschreibung beginnen soll.

Falls Sie andere Anfangssalden haben, zum Beispiel Ab\-Zuschreibung, können Sie diese ebenfalls jetzt eingeben.  

Falls die Anlagen nicht in der Finanzbuchhaltung integriert sind, können Sie die Schritte 4 bis 7 übergehen.

## <a name="see-also"></a>Siehe auch
[Anlageneinrichtung](fa-setup.md)  
[Verwalten von Anlagen](fa-manage.md)  
[Finanzen](finance-setup.md)  
[Willkommen bei Dynamics NAV](across-get-started.md)


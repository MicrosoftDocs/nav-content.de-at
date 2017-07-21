---
title: Verwalten von Berichtslayouts
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 57cd575c1f72841dae162b077d1f676720ee24e7
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
    
# <a name="manage-report-layouts"></a>Verwalten von Berichtslayouts
Ein Berichtlayout steuert Inhalt und Format des Berichts, auch, welche Datenfelder eines Berichtsdatasets im Bericht erscheinen und wie sie angeordnet werden, Text-Format, Bilder und mehr. Von den Dynamics NAV-Clients aus können Sie ändern, welches Layout in einem Bericht verwendet wird, ein neues Layout erstellen oder vorhandene Layouts ändern. 

Insbesondere richtet ein Berichtlayout Folgendes ein:

- Die Beschriftungs- und die Datenfelder, die aus dem Dataset des Dynamics NAV-Berichts einzuschließen sind.
- Das Text-Format, wie Schriftarttyp, Größe und Farbe.
- Das Firmenlogo und seine Position.
- Allgemeine Seiteneinstellungen, wie Seitenränder und Hintergrundbilder. 

Dynamics NAV kann mit mehreren Berichtlayouts eingerichtet werden, die bei Bedarf ausgewechselt werden können. Sie können ggf. einen der integrierten Berichtlayouts verwenden, oder Sie können angepasste Berichtlayouts erstellen und sie Ihren Berichten nach Bedarf zuordnen.

Es gibt zwei Arten Berichtlayouts, die Sie in Berichten verwenden können: Word und RDLC.

## <a name="word-report-layout-overview"></a>Word-Berichtlayout - Übersicht
Ein Word-Berichtlayout basiert auf einem Word-Dokument (DOCX-Datei-Typ). Word-Berichtslayouts ermöglichen es Ihnen, Berichtslayouts zu gestalten, indem Sie Microsoft Word 2013 oder später verwenden. Ein Word-Berichtslayout bestimmt den Inhalt des Berichts und steuert, wie diese Inhaltselemente angeordnet werden und wie diese aussehen. Ein Word-Berichtlayoutbeleg verwendet normalerweise Tabellen, um Inhalt zu organisieren, wobei die Zellen Datenfelder, Text oder Bilder enthalten können.

## <a name="rdlc-layout-overview"></a>RDLC-Layout - Übersicht
RDLC-Layouts basieren auf Client-Berichtsdefinitionslayouts (.rdlc- oder .rdl-Dateitypen). Diese Layouts werden erstellt und geändert, indem Sie SQL Server-Bericht-Generator verwenden. Das Entwurfskonzept für RDLC-Layouts ist ähnlich den Word-Layouts, in denen das Layout das Muster des Berichts definiert und die Felder der Dataset bestimmt, die enthalten sein sollen. RDLC-Layouts bieten, verglichen mit Word-Layouts, eine größere Fülle an Funktionen und Gestaltungsmöglichkeiten.

## <a name="built-in-and-custom-report-layouts"></a>Integrierte und benutzerdefinierte Berichtslayouts
Dynamics NAV umfasst mehrere integrierte Layouts. Integrierte Layouts sind vordefinierte Layouts, die für bestimmte Berichte vorgesehen sind. Dynamics NAV-Berichte haben ein integriertes Layout entweder als RDLC-Berichtslayout, Word-Berichtslayout oder in einigen Fällen beides. Sie können ein integriertes Berichtslayout aus Dynamics NAV nicht ändern, Sie können es jedoch als Ausgangspunkt für das Erstellen Ihrer eigenen benutzerdefinierten Berichtslayouts verwenden. 

Kundenspezifische Layouts sind Berichtslayouts, die Sie erstellen, um zdie Darstellung eines Berichts zu ändern. Sie erstellen normalerweise ein benutzerdefiniertes Layout basierend auf einem integrierten Layout, aber Sie können es von einer Kopie eines vorhandenen benutzerdefinierten Layouts von Grund auf neu erstellen. Benutzerdefinierete Layouts ermöglichen Ihnen, mehrere Layouts für den gleichen Bericht einzurichten, zwischen denen Sie nach Bedarf wechseln können. Beispielsweise können Sie verschiedene Layouts für jedes Dynamics NAV-Unternehmen haben, oder Sie können verschiedene Layouts für das gleiche Unternehmen für bestimmte Gelegenheiten oder Ereignisse verwenden, wie eine spezielle Kampagne oder eine Feiertagssaison.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Angeben, ob ein Word- oder RDLC-Berichtslayout verwendet werden soll 
Ein Berichtlayout kann auf einem Word-Dokument oder RDLC-Datei basieren. Die Entscheidung, ob ein Word-Berichtslayout oder RDLC-Berichtslayout verwendet davon, hängt davon ab, wie der generierten Bericht aussehen soll, sowie von Ihren Kenntnissen in Word und dem SQL Server-Bericht-Generator. 

Die allgemeinen Entwurfskonzepte für Word- und RDLC-Layouts sind sehr ähnlich. Jedoch hat jeder Typ bestimmte Design-Funktionalitäten, die beeinflussen, wie der generierte Bericht im Dynamics NAV-Client erscheint. Das bedeutet, dass derselbe Bericht möglicherweise bei Verwendung eines Word-Berichtslayout möglicherweise anders aussieht als bei einem RDLC-Berichtslayout.

Der Prozess für die Einrichtung von Word-Berichtslayouts und RDLC-Berichtslayouts in Berichten ist derselbe. Der wichtigste Unterschied besteht in der Art, wie die Sie die Layouts ändern. Word-Berichtslayouts sind in der Regel einfacher als RDLC-Berichtslayouts zu erstellen und zu ändern, da Sie Word bereits kennen. RDLC-Berichtslayouts werden geändert, indem Sie den SQL Server-Bericht-Generator verwenden, der für fortgeschrittene Benutzer entwickelt wurde.

Weitere Informationen darüber, wie das Layout, das verwendet wird, geändert werden kann, finden Sie unter [Vorgehensweise: Ändern, welches Layout zur Zeit in einem Bericht verwendet wird](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Siehe auch
[Arbeiten mit Dynamics NAV](ui-work-product.md)  
[Vorgehensweise: Erstellen eines benutzerdefinierten Berichtlayouts](ui-how-create-custom-report-layout.md)  
[Gewusst wie: Senden von Belegen über E-Mail](ui-how-send-documents-email.md)


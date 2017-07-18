---
title: 'Gewusst wie: Einrichten von Arbeitszeittabellen'
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
ms.openlocfilehash: 6cbacce79ce185d6ed00ea8383259d1b28f9e11b
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-time-sheets"></a>Gewusst wie: Einrichten von Arbeitszeittabellen
Arbeitszeittabellen in Dynamics NAV erfassen die Zeit in wöchentlichen Schritten von sieben Tagen. Sie verwenden sie, um die Zeit zu verfolgen, die für Projekte verwendet wird, und Sie können sie verwenden, um Ressourcenzeiterfassung um zu erfassen. Bevor Sie Arbeitszeittabellen verwenden können, müssen Sie festlegen, wie sie eingerichtet und konfiguriert werden sollen.

Nachdem Sie eingerichtet haben, wie Ihre Organisation Arbeitszeittabellen verwendet, können Sie angeben, wann und wie Arbeitszeittabellen genehmigt werden. Abhängig von den Anforderungen Ihrer Organisation, können Sie festlegen:

- Einen oder mehrere Benutzer als Arbeitszeittabellenadministrator und Genehmiger für alle Arbeitszeittabellen.
- Ein Arbeitszeittabellengenehmiger für jede Ressource.

Wenn Sie Arbeitszeittabellen eingerichtet haben, können Sie Arbeitszeittabellen für Ressourcen erstellen, sie Projektplanungszeilen zuweisen und Arbeitszeittabellenzeilen buchen. Weitere Informationen finden Sie unter [Vorgehensweise: Verwenden von Arbeitszeittabellen](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Um allgemeine Informationen für Arbeitszeittabellen einzurichten:  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Ressourceneinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.
3. Für das Feld **Arbeitszeittabelle nach Projekt-Genehmigung** wählen Sie eine der folgenden Optionen aus.

|Option |Description|
|---|---|
|**Nie**|Der Benutzer im Feld **Arbeitszeittabellengenehmiger-Benutzer-ID** der Ressourcenkarte genehmigt die Arbeitszeittabelle.|
|**Immer**|Der Benutzer im Feld **Verantwortliche Person** der Projektkarte genehmigt die Arbeitszeittabelle.|
|**Nur Arbeitsplätze**|Wenn die Arbeitsplatzzeittabelle mit einem Projekt verknüpft ist, dann genehmigt der Benutzer im Feld **Verantwortliche Person** auf der Projektkarte die Arbeitszeittabelle. Wenn die Arbeitsplatzzeittabelle mit einer Ressource verknüpft ist, dann genehmigt der Benutzer im Feld **Arbeitszeittabelle Genehmiger-Benutzer-ID** auf der Ressourcenkarte die Arbeitszeittabelle.

## <a name="to-assign-a-time-sheet-administrator"></a>So weisen Sie einen Arbeitszeittabellenadministrator zu:  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Benutzeinrichtung** ein. Wählen Sie dann den zugehörigen Link aus.  
2.  Fügen Sie einen neuen Benutzer hinzu, wenn die Benutzerliste nicht die Person enthält, die Arbeitszeittabelleadministrator sein soll. Für weitere Informationen wenden Sie bitte an Ihren Administrator.  
3. Wählen Sie einen Benutzer aus, der Arbeitszeittabellenadministrator sein soll, und wählen Sie dann den **Arbeitszeittabellen-Administrator** aus. Kontrollkästchen aktivieren.  

**Hinweis**: Es wird empfohlen, nur einen Benutzer als Arbeitszeittabellenadministrator für ein Unternehmen festzulegen. Im folgenden Verfahren richten Sie einen Arbeitszeittabellenbesitzer und - genehmiger ein, wenn der Arbeitszeittabellengenehmiger für jede Ressource zugeordnet ist.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>So legen Sie einen Arbeitszeittabellenbesitzer und -genehmiger fest:  

1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Ressourcen** ein. Wählen Sie dann den zugehörigen Link aus.
2. Wählen Sie die Ressource, für die Sie die Möglichkeit einrichten möchten, Arbeitszeittabellen zu verwenden, und wählen Sie dann das Kontrollkästchen **Arbeitszeittabelle verwenden**.  
3. Geben Sie im Feld **Arbeitszeittabellenbesitzer-Benutzer-ID** die ID des Besitzers der Arbeitszeittabelle ein. Der Eigentümer kann Bearbeitungszeit auf der Arbeitszeittabelle eingeben und ihn zur Genehmigung senden. Wenn es sich bei der Ressource um eine Person handelt, ist diese Person im Allgemeinen auch der Besitzer.  
4. Geben Sie im Feld **Arbeitszeittabellengenehmiger-Benutzer-ID** die ID des Genehmigers der Arbeitszeittabelle ein. Der Genehmiger kann eine Arbeitszeittabelle genehmigen, ablehnen oder erneut öffnen.  

**Hinweis**: Sie können die ID des Arbeitszeittabellengenehmigers nicht ändern, wenn Arbeitszeittabellen vorhanden sind, die noch nicht verarbeitet wurden und die den Status Übermittelt oder **Übermittelt** oder **Offen** haben.

## <a name="see-also"></a>Siehe auch
[Projektmanagement einrichten](projects-setup-projects.md)  
[Projekte verwalten](projects-manage-projects.md)  
[Finanzen](finance-setup.md)  
[Einkauf verwalten](purchasing-manage-purchasing.md)         
[Verkauf verwalten](sales-manage-sales.md)      
[Arbeiten mit Dynamics NAV](ui-work-product.md)  


---
title: "Designdetails – Codeunit 408 Dimension Management"
description: "Codeunit 408 Dimension Management ist eine Funktionsbibliothek, die häufige Aufgaben im Zusammenhang mit Dimensionen behandelt, wie etwa das Kopieren von einer Tabelle zu einer anderen oder von einem Beleg zu einem anderen."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: c1b3c745597f96165aec92a08bba50ecb6727a84
ms.contentlocale: de-at
ms.lasthandoff: 10/23/2017

---
# <a name="design-details-codeunit-408-dimension-management"></a>Designdetails: Codeunit 408 Dimension Management
Codeunit 408 Dimension Management ist eine Funktionsbibliothek, die häufige Aufgaben im Zusammenhang mit Dimensionen behandelt, wie etwa das Kopieren von einer Tabelle zu einer anderen oder von einem Beleg zu einem anderen. Dieses Thema listet die Funktionen auf, die in Microsoft Dynamics NAV 2013 R2 geändert werden und gibt an, was mit den Funktionen durchgeführt werden muss. Viele Funktionalitäten werden gelöscht, da ein Kopieren zwischen Dimensionstabellen nicht erforderlich gibt.  

## <a name="modified-functions"></a>Geänderte Funktionen  

|Funktionsname|Modifizierungsbeschreibung|  
|-------------------|------------------------------|  
|CheckDimSetIDComb|Neue Funktion, die die anderen Scheckfunktionen ersetzt und nimmt eine Dimensionssatz-ID als ein Argument anstelle einer Dimensionstabelle.|  
|CheckDimSetIDComb<br /><br /> CheckDocDimComb<br /><br /> CheckServContractDimComb<br /><br /> CheckDimBuffer<br /><br /> CheckDimComb<br /><br /> CheckDimValueComb|LÖSCHEN. Die gesamte Nutzung sollte zu CheckDimSetIDComb geändert werden.|  
|GetDefaultDim|"Ändern", um eine ganzzahlige Dimensionssatz-ID anstelle eines Satzes von Datensätzen zurückzusenden.|  
|CopyJnlLineDimToICJnlDim<br /><br /> CopyICJnlDimToJnlLineDim<br /><br /> CopyDocDimtoICDocDim<br /><br /> CopyICDocDimtoICDocDim|Ändern, um mit DimSetID zu arbeiten - > ICJnlLineDim|  

## <a name="deleted-functions"></a>Gelöschte Funktionen  
 Funktionen, die aus Codeunit 408 in Verbindung mit den Dimensionssatzposten gelöscht werden, werden unten aufgelistet.  

> [!CAUTION]  
>  Während des Upgrades des Anwendungscodes von Microsoft Dynamics NAV 2009 oder früheren Versionen zu Microsoft Dynamics NAV 2016 sind die folgenden Funktionen nicht in Microsoft Dynamics NAV 2016 verfügbar. Wenn Sie Anpassungen haben, die einen oder mehrere der Funktionalitäten verwenden, müssen Sie diesen Code entsprechend aktualisieren.

 InsertJnlLineDim  

 UpdateJnlLineDefaultDim  

 GetJnlLineDefaultDim  

 GetPreviousDocDefaultDim  

 GetPreviousProdDocDefaultDim  

 InsertDocDim  

 UpdateDocDefaultDim  

 ExtractDocDefaultDim  

 InsertProdDocDim  

 UpdateProdDocDefaultDim  

 InsertServContractDim  

 UpdateServcontractDim  

 UpdateDefaultDimNewDimValue  

 GetDocDim  

 GetProdDocDim  

 TypeToTableID1  

 TypeToTableID2  

 TypeToTableID3  

 TypeToTableID4  

 TypeToTableID5  

 DeleteJnlLineDim  

 DeleteDocDim  

 DeletePostedDocDim  

 DeleteProdDocDim  

 DeleteServContractDim  

 ShowJnlLineDim  

 SaveJnlLineDim  

 ShowJnlLineNewDim  

 SaveJnlLineNewDim  

 ShowDocDim  

 SaveDocDim  

 ShowProdDocDim  

 SaveProdDocDim  

 ShowTempDim  

 SaveTempDim  

 ShowTempNewDim  

 SaveTempNewDim  

 SaveServContractDim  

 CopyLedgEntryDimToJnlLineDim  

 MoveDocDimToPostedDocDim  

 MoveDocDimToPostedDocDim  

 CopyLedgEntryDimToJnlLineDim  

 MoveDimBufToJnlLineDim  

 MoveDimBufToLedgEntryDim  

 MoveDimBufToPostedDocDim  

 MoveDimBufToGLBudgetDim  

 CopyJnlLineDimToJnlLineDim  

 CopyLedgEntryDimToJnlLineDim  

 CopyDocDimToDocDim  

 CopyPostedDocDimToPostedDocDim  

 CopyDocDimToJnlLineDim  

 CopyDimBufToJnlLineDim  

 CopyDimBufToDocDim  

 CopySCDimToDocDim  

 MoveDocDimToLedgEntryDim  

 MoveDocDimToDocDim  

 MoveDocDimArchvToDocDim  

 MoveDocDimToLedgEntryDim  

 MoveProdDocDimToProdDocDim  

 CopyDocDimToJnlLineDim  

 CopyDocDimToJnlLineDim  

 MoveJnlLineDimToJnlLineDim  

 CopyLedgEntryDimToLedgEntryDim  

 MoveTempFromDimToTempToDim  

 TransferTempToDimToDocDim  

 MoveJnlLineDimToBuf  

 CopyICJnlDimToICJnlDim  

 TestDimValue  

 TestNewDimValue  

 MoveDimBufToItemBudgetDim. (Löschen, da die ItemBudgetDim-Tabelle gelöscht ist.)  

 GetServContractDim  

 MoveTempDimToBuf  

 UpdateSCInvLineDim  

 CopyJnlLineDimToBuffer  

 UpdateDocDefaultDim2  

## <a name="see-also"></a>Siehe auch
 [Designdetails: Dimensionssatzposten](design-details-dimension-set-entries.md)   
 [Designdetails: Dimensionssatzposten Übersicht](design-details-dimension-set-entries-overview.md)   
 [Designdetails: Suche nach Dimensionskombinationen](design-details-searching-for-dimension-combinations.md)   
 [Designdetails: Tabellenstruktur](design-details-table-structure.md)   
 [Designdetails: Codebeispiele von geänderten Mustern in Änderungen](design-details-code-examples-of-changed-patterns-in-modifications.md)


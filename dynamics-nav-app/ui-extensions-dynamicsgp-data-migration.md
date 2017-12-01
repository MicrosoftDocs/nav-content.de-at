---
title: Migrieren von Daten von Dynamics GP mit der Datenmigrations-Erweiterung
description: Verwenden Sie die GP-Datenmigrationserweiterung, um Debitoren, Kreditoren, Artikel und Konten von Dynamics GP auf Dynamics NAV zu migrieren.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0156ec040b96f007674161361e4368b81f7c42d9
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---
# <a name="the-dynamics-gp-data-migration-extension-for-dynamics-nav"></a>Die Dynamics GP-Datenmigrations-Erweiterung für Dynamics NAV
Diese Erweiterung macht es einfach, Debitoren, Kreditoren und Artikel aus Dynamics GP in [!INCLUDE[d365fin](includes/d365fin_md.md)] zu migrieren. Wenn Ihr Geschäft Dynamics GP heute verwendet, können Sie die Daten exportieren und dann eine unterstützte Einrichtungsanleitung öffnen, um die Daten hochzuladen und in [!INCLUDE[d365fin](includes/d365fin_md.md)] zu migrieren. Weitere Informationen finden Sie unter [Geschäftsdaten aus anderen Finanzsystemen migrieren](upload-data.md).

## <a name="exporting-data-from-dynamics-gp"></a>Exportieren von Daten aus Dynamics GP
Sie müssen Ihre bestehenden Debitoren, Kreditoren, Artikel und Konten mit der Exportdatenenfunktionalität in Dynamics GP exportiert haben. Zum Zweck des [!INCLUDE[d365fin](includes/d365fin_md.md)] können Sie die folgenden Datentypen exportieren:

* Konto  
* Debitor  
* Option  
* Kreditor  

Die Dynamics GP-Datenmigrationserweiterung ordnet automatisch die exportierten Daten zu, so dass Sie Ihre bestehenden Daten rasch im [!INCLUDE[d365fin](includes/d365fin_md.md)] Unternehmen bereitstehen. Während des Prozesses werden unterstützende Einrichtungsinformationen wie z. B. Buchungsgruppen erstellt. Lagerartikel werden im System mit FIFO als die Bewertungsmethode mit Kosten angezeigt. Konten werden als das Hauptkontosegment von Dynamics GP mit Dimensionen eingerichtet, da sie keine[!INCLUDE[d365fin](includes/d365fin_long_md.md)] Kontensegmente haben.

## <a name="see-also"></a>Siehe auch
[Geschäftsdaten aus anderen Finanzsystemen migrieren](upload-data.md)  
[Anpassen [!INCLUDE[d365fin](includes/d365fin_md.md)] Erweiterungen nutzenb](ui-extensions.md)  


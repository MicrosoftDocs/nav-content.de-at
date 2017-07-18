---
title: Einrichtung von Dimensionen
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
ms.openlocfilehash: 18237c4b755926222a36bc97dec5d6783c11454d
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="set-up-dimensions"></a>Einrichtung von Dimensionen
Sie müssen die Dimensionen und Dimensionswerte festlegen, die Sie in Ihrem Mandanten verwenden möchten. Sie sollten auch festlegen, welche Dimensionen Sie als globale und Shortcutdimensionen verwenden möchten. Prüfen Sie eingehend, welche Dimensionen als globale und Shortcutdimensionen für Ihren Mandanten am effektivsten sind.  
Die Einrichtung aller gewünschten Nachverfolgungsdimensionen erfolgt im Fenster **Dimensionen**. Das Fenster "Dimensionen" enthält jeweils eine Zeile für die einzelnen Dimensionen (wie z. B. *Projekt*, *Abteilung*, *Bereich* oder *Verkäufer*).  

Für jede Dimension müssen ausserdem Dimensionswerte eingerichtet werden (beispielsweise alle Abteilungen innerhalb des Unternehmens). Dimensionswerte können in einer hierarchischen Struktur eingerichtet werden, die der Struktur des Kontenplans gleicht, sodass die Daten in unterschiedlichen Granularitätsstufen aufgeschlüsselt und Untergruppen von Dimensionswerten summiert werden können.  

Zwei globale Dimensionen, die automatisch überall verfügbar sind (beispielsweise in Berichten und Stapelverarbeitungen) können angegeben werden. Darüber hinaus können sechs zusätzliche Shortcutdimensionen angegeben werden, die in Buch.-Blattzeilen und Belegzeilen als Feld zur Verfügung stehen. Zur Verwendung der übrigen Dimensionen muss ein separates Fenster geöffnet werden, in dem die Dimensionen für die Zeile angezeigt werden.  

Sie können beliebig viele Dimensionen in Ihrem Mandanten definieren und Sie können eine unbegrenzte Anzahl von Dimensionswerten für jede Dimension festlegen. Alle von Ihnen definierten Dimensionen können für Posten in Buch.-Blättern und Belegen sowie mit Dimensionen in Verbindung stehenden Berichten und Stapelverarbeitungen verwendet werden.  

## <a name="set-up-default-dimensions-for-customers-vendors-and-other-accounts"></a>Standarddimensionen für Debitoren, Kreditoren und andere Konten einrichten
Sie können für ein bestimmtes einzelnes Konto Vorgabedimensionen einrichten. Dieser Code wird in das Buch.-Blatt oder den Beleg kopiert, wenn das Feld "Kontonr." der Zeile ausgefüllt wird. Sie können den Code jedoch bei Bedarf ändern. Sie können eine Dimension auch erforderlich machen, sodass ein Posten mit einer bestimmten Kontoart nur gebucht werden kann, wenn dem Konto ein Dimensionswert zugeordnet ist.  

Außerdem können Sie eine Standarddimension für jede Kontoart einrichten, sodass der Code in das Buch.-Blatt oder den Beleg kopiert wird, wenn die Kontoart in die Zeile eingegeben wird. Sie können den Code des Belegs immer ändern, falls nötig.  

Zuletzt können Sie eine Dimension auch erforderlich machen, sodass ein Posten mit einer bestimmten Kontoart nur gebucht werden kann, wenn dem Konto ein Dimensionswert zugeordnet ist.

## <a name="see-also"></a>Siehe auch
[Dimensionen](finance-setup-dimensions.md)  
[Zentrale Finanzprozesse einrichten](finance-setup-setup-finance-setup.md)


---
title: Verkaufssteuer sowie Steuern auf Waren und Dienstleistungen in Kanada
author: edupont04
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c032a02b545441b927ef5c4facc9f77731f37ab7
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a>Verkaufssteuer sowie Steuern auf Waren und Dienstleistungen in Kanada
Wenn ein Kreditor in Kanada keine Geschäftspräsenz in der Provinz hat, in der die Einkäufe getätigt werden, berechnet der Kreditor nur Steuern auf Waren und Dienstleistungen (Goods and Services Tax, GST) oder Harmonised Sales Tax (HST). Wenn jedoch die Provinz eine Provincial Sales Tax (PST) erhebt, dann muß der Einkäufer noch die PST berechnen und sie direkt an die Provinz bezahlen. Wenn ein Steuergebietscode für Provinzen aktiviert ist, verwendet Dynamics NAV diesen, um die PST zu berechnen und zu buchen, sodass sowohl im Sachkonto als auch in den Steuerpostendatensätzen Steuerverbindlichkeiten vermerkt sind. Daher sollte der Steuergebietscode, der hier aktiviert ist, nur die PST enthalten, nicht die GST.  
Weitere Informationen zur Verkaufssteuer, finden Sie unter [Verkaufssteuer sowie Steuergruppen in den USA und in Kanada](us-finance-setup-sales-tax.md).  

## <a name="submitting-the-gsthst-file"></a>Übermitteln der GST-/HST-Datei
Die Steuerdaten in Einkaufsbelegen werden verwendet, um eine GST/HST-Internetdateiübertragung (GIFT) zu generieren, die Sie dem Finanzamt bereitstellen müssen. Diese Datei umfasst Steuern auf Waren und Dienstleistungen (GST) und die Harmonised Sales Tax (HST). Die Datei wird in einem .tax-Dateiformat erstellt, das über das Internet übertragen werden kann.  

## <a name="see-also"></a>Siehe auch
[Finanzen](finance-setup.md)  
[Finanzen Einrichten](finance-setup-setup-finance-setup.md)  
[Verkaufssteuer sowie Steuergruppen in den USA und in Kanada](us-finance-setup-sales-tax.md)


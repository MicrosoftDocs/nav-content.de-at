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

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a><span data-ttu-id="f06bb-102">Verkaufssteuer sowie Steuern auf Waren und Dienstleistungen in Kanada</span><span class="sxs-lookup"><span data-stu-id="f06bb-102">Sales Tax and Goods and Services Tax in Canada</span></span>
<span data-ttu-id="f06bb-103">Wenn ein Kreditor in Kanada keine Geschäftspräsenz in der Provinz hat, in der die Einkäufe getätigt werden, berechnet der Kreditor nur Steuern auf Waren und Dienstleistungen (Goods and Services Tax, GST) oder Harmonised Sales Tax (HST).</span><span class="sxs-lookup"><span data-stu-id="f06bb-103">In Canada, when a vendor does not have a business presence in the province in which purchases are made, the vendor will charge the Goods and Services Tax (GST) or Harmonized Sales Tax (HST) only.</span></span> <span data-ttu-id="f06bb-104">Wenn jedoch die Provinz eine Provincial Sales Tax (PST) erhebt, dann muß der Einkäufer noch die PST berechnen und sie direkt an die Provinz bezahlen.</span><span class="sxs-lookup"><span data-stu-id="f06bb-104">However, if the province has a Provincial Sales Tax (PST), then the purchaser must still calculate the PST and pay it directly to the province.</span></span> <span data-ttu-id="f06bb-105">Wenn ein Steuergebietscode für Provinzen aktiviert ist, verwendet Dynamics NAV diesen, um die PST zu berechnen und zu buchen, sodass sowohl im Sachkonto als auch in den Steuerpostendatensätzen Steuerverbindlichkeiten vermerkt sind.</span><span class="sxs-lookup"><span data-stu-id="f06bb-105">When a Provincial Tax Area Code is selected, Dynamics NAV uses it to calculate the PST and post it so that there is a tax liability in both the general ledger and the tax entry records.</span></span> <span data-ttu-id="f06bb-106">Daher sollte der Steuergebietscode, der hier aktiviert ist, nur die PST enthalten, nicht die GST.</span><span class="sxs-lookup"><span data-stu-id="f06bb-106">Therefore, the tax area code selected here should be one where only the PST is included, not the GST.</span></span>  
<span data-ttu-id="f06bb-107">Weitere Informationen zur Verkaufssteuer, finden Sie unter [Verkaufssteuer sowie Steuergruppen in den USA und in Kanada](us-finance-setup-sales-tax.md).</span><span class="sxs-lookup"><span data-stu-id="f06bb-107">For more information about sales tax, see [Sales Tax and Tax Groups in the US and Canada](us-finance-setup-sales-tax.md).</span></span>  

## <a name="submitting-the-gsthst-file"></a><span data-ttu-id="f06bb-108">Übermitteln der GST-/HST-Datei</span><span class="sxs-lookup"><span data-stu-id="f06bb-108">Submitting the GST/HST File</span></span>
<span data-ttu-id="f06bb-109">Die Steuerdaten in Einkaufsbelegen werden verwendet, um eine GST/HST-Internetdateiübertragung (GIFT) zu generieren, die Sie dem Finanzamt bereitstellen müssen.</span><span class="sxs-lookup"><span data-stu-id="f06bb-109">The tax information in purchase documents is used to generate a GST/HST internet file transfer that you must  provided to the tax authorities.</span></span> <span data-ttu-id="f06bb-110">Diese Datei umfasst Steuern auf Waren und Dienstleistungen (GST) und die Harmonised Sales Tax (HST).</span><span class="sxs-lookup"><span data-stu-id="f06bb-110">This file includes goods and services tax (GST) and harmonized sales tax (HST).</span></span> <span data-ttu-id="f06bb-111">Die Datei wird in einem .tax-Dateiformat erstellt, das über das Internet übertragen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f06bb-111">The file is created in a .tax file format, which can be transferred via the internet.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f06bb-112">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="f06bb-112">See Also</span></span>
[<span data-ttu-id="f06bb-113">Finanzen</span><span class="sxs-lookup"><span data-stu-id="f06bb-113">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="f06bb-114">Finanzen Einrichten</span><span class="sxs-lookup"><span data-stu-id="f06bb-114">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="f06bb-115">Verkaufssteuer sowie Steuergruppen in den USA und in Kanada</span><span class="sxs-lookup"><span data-stu-id="f06bb-115">Sales Tax and Tax Groups in the US and Canada</span></span>](us-finance-setup-sales-tax.md)


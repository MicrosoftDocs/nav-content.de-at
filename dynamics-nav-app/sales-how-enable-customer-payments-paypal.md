---
title: 'Gewusst wie: Aktivieren von Debitoren-Zahlungen durch Paypal'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: de-at
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="935f8-102">Gewusst wie: Aktivieren von Debitoren-Zahlungen durch Paypal#</span><span class="sxs-lookup"><span data-stu-id="935f8-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="935f8-103">Als Alternative zu Zahlungen per Banktransfer oder Kreditkarten können Sie Ihren Debitoren anbieten, über Paypal zu bezahlen.</span><span class="sxs-lookup"><span data-stu-id="935f8-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="935f8-104">Wenn ein Debitor den Paypal-Link in einer Verkaufsrechnung oder einem Verkaufsauftragsbeleg auswählt, erscheint die Service-Seite für ihr Paypal-Konto, das die Zahlungsdetails für den Verkauf enthält.</span><span class="sxs-lookup"><span data-stu-id="935f8-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="935f8-105">Der Kunde kann die Rechnung wie jede andere PayPal-Zahlung bezahlen.</span><span class="sxs-lookup"><span data-stu-id="935f8-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="935f8-106">Um Debitorenzahlungen durch PayPal zu aktivieren, müssen Sie Folgendes tun:</span><span class="sxs-lookup"><span data-stu-id="935f8-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="935f8-107">Setup-Paypal-Zahlungs-Standard als Zahlungsservice im Fenster **Zahlungs-Service**.</span><span class="sxs-lookup"><span data-stu-id="935f8-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="935f8-108">Paypal-Zahlungs-Standard im Feld **Zahlungsverkehr** im betreffenden Verkaufsbeleg auswählen.</span><span class="sxs-lookup"><span data-stu-id="935f8-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="935f8-109">Der Paypal-Zahlungsstandard-Service wird als eine Erweiterung im Dynamics NAV eingerichtet und ist bereit, aktiviert zu werden.</span><span class="sxs-lookup"><span data-stu-id="935f8-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="935f8-110">Weitere Informationen finden Sie unter [Anpassen von Dynamics NAV](ui-extensions.md) mithilfe der Erweiterungen .</span><span class="sxs-lookup"><span data-stu-id="935f8-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="935f8-111">Zur Aktivierung des Paypal-Zahlungsstandard-Service</span><span class="sxs-lookup"><span data-stu-id="935f8-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="935f8-112">Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Zahlungsverkehr** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="935f8-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="935f8-113">Wählen Sie im Fenster **Zahlungsverkehr** die Aktion **Neu** aus.</span><span class="sxs-lookup"><span data-stu-id="935f8-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="935f8-114">Wählen Sie **PayPal Standard** aus, und schließen Sie das Fenster.</span><span class="sxs-lookup"><span data-stu-id="935f8-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="935f8-115">Wählen Sie im Fenster **Zahlungsverkehr** die Aktion **Einrichten** aus.</span><span class="sxs-lookup"><span data-stu-id="935f8-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="935f8-116">Füllen Sie die Felder je nach Bedarf aus.</span><span class="sxs-lookup"><span data-stu-id="935f8-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="935f8-117">Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="935f8-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="935f8-118">**Hinweis**: Wählen Sie **Immer auf Dokument aufführen** aus und aktivieren Sie dazu das Kontrollkästchen, wenn der Link für den Paypal-Zahlungsverkehr immer in Verkaufsbelegen sichtbar sein soll, bei denen Zahlung mit Paypal ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="935f8-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="935f8-119">Schließen Sie das Fenster.</span><span class="sxs-lookup"><span data-stu-id="935f8-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="935f8-120">So wählen Sie Paypal-Zahlung-Standards auf einer Verkaufsrechnung aus</span><span class="sxs-lookup"><span data-stu-id="935f8-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="935f8-121">Auf der Startseite wählen Sie **Verkaufsrechnung** aus.</span><span class="sxs-lookup"><span data-stu-id="935f8-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="935f8-122">Öffnen Sie die Verkaufsrechnung, auf der Sie Paypal-Zahlungen aktivieren möchten.</span><span class="sxs-lookup"><span data-stu-id="935f8-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="935f8-123">Geben Sie im Feld **Zahlungsverkehr** Standard Paypal-Zahlungen ein.</span><span class="sxs-lookup"><span data-stu-id="935f8-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="935f8-124">**Hinweis**: Das Feld **Zahlungsverkehr** ist nur sichtbar, wenn der Paypal-Zahlungsstandard-Service ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="935f8-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="935f8-125">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="935f8-125">See Also</span></span>  
[<span data-ttu-id="935f8-126">Auftrag einrichten</span><span class="sxs-lookup"><span data-stu-id="935f8-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="935f8-127">Verkauf verwalten</span><span class="sxs-lookup"><span data-stu-id="935f8-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="935f8-128">Anpassen Dynamics NAV Erweiterungen nutzenb</span><span class="sxs-lookup"><span data-stu-id="935f8-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)


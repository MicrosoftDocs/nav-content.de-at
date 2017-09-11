---
title: Anpassen des Dynamics NAV mithilfe der Erweiterungen
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: cc832772a255c7c801a7b956c74da827caca3765
ms.contentlocale: de-at
ms.lasthandoff: 07/19/2017

---

# <a name="customizing-dynamics-nav-using-extensions"></a><span data-ttu-id="c1556-102">Anpassen des Dynamics NAV mithilfe der Erweiterungen</span><span class="sxs-lookup"><span data-stu-id="c1556-102">Customizing Dynamics NAV Using Extensions</span></span>
<span data-ttu-id="c1556-103">Sie können Dynamics NAV ändern, indem Sie beispielsweise Erweiterungen installieren, die Funktionalität hinzufügen, das Verhalten ändern oder Zugriff auf die neuen Onlinedienste geben.</span><span class="sxs-lookup"><span data-stu-id="c1556-103">You can change Dynamics NAV by installing extensions that add functionality, change behavior, or give you access to new online services, for example.</span></span>
<span data-ttu-id="c1556-104">Wenn Sie Dynamics NAV zuerst starten, werden bestimmte Erweiterungen bereits eingerichtet.</span><span class="sxs-lookup"><span data-stu-id="c1556-104">When you first launch Dynamics NAV, some extensions are already installed for you.</span></span> <span data-ttu-id="c1556-105">Im Zeitverlauf werden mehr Erweiterungen für Sie zugänglich und Sie können auswählen, ob Sie die Erweiterung verwenden möchten oder nicht.</span><span class="sxs-lookup"><span data-stu-id="c1556-105">Over time, more extensions can be made available to you, and you can then choose if you want to use the extension or not.</span></span>

<span data-ttu-id="c1556-106">Beispielsweise bietet Microsoft eine Erweiterung an, die die Integration mit Standard Paypal-Zahlungen ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="c1556-106">For example, Microsoft provides an extension that provides integration with PayPal Payments Standard.</span></span> <span data-ttu-id="c1556-107">Diese Erweiterung wird standardmäßig eingerichtet.</span><span class="sxs-lookup"><span data-stu-id="c1556-107">This extension is installed by default.</span></span>
<span data-ttu-id="c1556-108">Wenn aber keine andere Erweiterung bereitgestellt wird, die die Integration mit einem anderen Zahlungsservice anbietet, können Sie die neue Erweiterung einrichten und dann auswählen, welcher der beiden Services verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c1556-108">But if another extension is made available that offers integration with another payment service, you can install the new extension and then choose which of the two services to use.</span></span>  

<span data-ttu-id="c1556-109">Sie verwalten die Erweiterung des **Erweiterungs-Verwaltungs**-Fenster.</span><span class="sxs-lookup"><span data-stu-id="c1556-109">You manage the extensions in the **Extension Management** window.</span></span> <span data-ttu-id="c1556-110">Sie können vom Startbildschirm auf dieses Fenster zugreifen.</span><span class="sxs-lookup"><span data-stu-id="c1556-110">You can access this window from Home.</span></span> <span data-ttu-id="c1556-111">Alternativ wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben **Erweiterung** ein. Wählen Sie dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="c1556-111">Alternatively, choose the **Search for Page or Report** icon in the top right corner, enter **Extension**, and then choose the related link.</span></span>   

## <a name="installing-an-extension"></a><span data-ttu-id="c1556-112">Eine Erweiterung wird installiert</span><span class="sxs-lookup"><span data-stu-id="c1556-112">Installing an Extension</span></span>
<span data-ttu-id="c1556-113">Wenn neue Erweiterungen zugänglich für Sie erstellt werden, da sie mit dem Server veröffentlicht wurden, werden sie im Fenster **Erweiterungs-Verwaltung** angezeigt.</span><span class="sxs-lookup"><span data-stu-id="c1556-113">If new extensions are made available to you because they have been published to your server, they will be shown in the **Extension Management** window.</span></span> <span data-ttu-id="c1556-114">Hier können Sie Erweiterungen einrichten und deinstallieren.</span><span class="sxs-lookup"><span data-stu-id="c1556-114">From here, you can choose to install and uninstall extensions.</span></span>  

<span data-ttu-id="c1556-115">Wenn Sie eine Erweiterung auswählen, können Sie erfahren, was die Erweiterung ausführt, und auf die Hilfe für die Erweiterung zugreifen, um mehr darüber zu erfahren.</span><span class="sxs-lookup"><span data-stu-id="c1556-115">If you choose an extension, you can read about what the extension does, and you can access Help for the extension to learn more.</span></span> <span data-ttu-id="c1556-116">Wenn Sie eine Erweiterung erhalten möchten, müssen Sie die Nutzungsbedingungen zustimmen.</span><span class="sxs-lookup"><span data-stu-id="c1556-116">When you choose to get an extension, you must agree to the terms of use.</span></span>  

<span data-ttu-id="c1556-117">Wenn Sie eine Erweiterung einrichten, müssen Sie diese möglicherweise einrichten und möglicherweise ein Konto zur Verwendung mit der Erweiterung für **Paypal-Zahlungen Standard für Dynamics NAV** definieren.</span><span class="sxs-lookup"><span data-stu-id="c1556-117">When you install an extension, you might have to set it up, such as specifying an account for use with the **PayPal Payments Standard for Dynamics NAV** extension.</span></span>
<span data-ttu-id="c1556-118">Andere Erweiterungen fügen einfach Felder einer vorhandenen Seite hinzu, oder sie fügen beispielsweise eine neue Seite hinzu.</span><span class="sxs-lookup"><span data-stu-id="c1556-118">Other extensions simply add fields to an existing page, or they add a new page, for example.</span></span>   

<span data-ttu-id="c1556-119">Wenn Sie eine Erweiterung deinstallieren und Sie dann Ihre Absicht ändern, können Sie sie wieder einrichten.</span><span class="sxs-lookup"><span data-stu-id="c1556-119">If you uninstall an extension, and you then change your mind, you can install it again.</span></span> <span data-ttu-id="c1556-120">Wenn Sie eine Erweiterung deinstallieren, die Sie verwendet haben, werden die Daten beibehalten, sodass, wenn Sie die Erweiterung erneut einrichten, die Daten noch verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="c1556-120">When you uninstall an extension that you have been using, the data is preserved so that if you install the extension again, your data is still available.</span></span>  

<span data-ttu-id="c1556-121">Microsoft stellt die folgenden Erweiterungen bereit:</span><span class="sxs-lookup"><span data-stu-id="c1556-121">Microsoft provides the following extensions:</span></span>  
- [<span data-ttu-id="c1556-122">PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="c1556-122">PayPal Payments Standard</span></span>](ui-extensions-paypal-payments-standard.md)  
- [<span data-ttu-id="c1556-123">Geplanter voraussichtlicher Verkauf und Lagerbestand</span><span class="sxs-lookup"><span data-stu-id="c1556-123">Sales and Inventory Forecast</span></span>](ui-extensions-sales-forecast.md)  

<span data-ttu-id="c1556-124">Andere Erweiterungen sind standardmäßig verfügbar, abhängig von Ihrem Land/Ihrer Region.</span><span class="sxs-lookup"><span data-stu-id="c1556-124">Other extensions are also available by default, depending on your country/region.</span></span>

## <a name="see-also"></a><span data-ttu-id="c1556-125">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="c1556-125">See Also</span></span>  
[<span data-ttu-id="c1556-126">Gewusst wie: Aktivieren von Debitoren-Zahlungen durch Paypal</span><span class="sxs-lookup"><span data-stu-id="c1556-126">How to: Enable Customer Payment Through PayPal</span></span>](sales-how-enable-customer-payments-paypal.md)  
[<span data-ttu-id="c1556-127">Willkommen bei Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="c1556-127">Welcome to Dynamics NAV</span></span>](across-get-started.md)  


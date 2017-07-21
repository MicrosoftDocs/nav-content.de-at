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
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: a2268d8454af761c40b11d89b01778a3f92090fb
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a>Gewusst wie: Aktivieren von Debitoren-Zahlungen durch Paypal#
Als Alternative zu Zahlungen per Banktransfer oder Kreditkarten können Sie Ihren Debitoren anbieten, über Paypal zu bezahlen.

Wenn ein Debitor den Paypal-Link in einer Verkaufsrechnung oder einem Verkaufsauftragsbeleg auswählt, erscheint die Service-Seite für ihr Paypal-Konto, das die Zahlungsdetails für den Verkauf enthält. Der Kunde kann die Rechnung wie jede andere PayPal-Zahlung bezahlen.

Um Debitorenzahlungen durch PayPal zu aktivieren, müssen Sie Folgendes tun:

1. Setup-Paypal-Zahlungs-Standard als Zahlungsservice im Fenster **Zahlungs-Service**.
2. Paypal-Zahlungs-Standard im Feld **Zahlungsverkehr** im betreffenden Verkaufsbeleg auswählen.

Der Paypal-Zahlungsstandard-Service wird als eine Erweiterung im Dynamics NAV eingerichtet und ist bereit, aktiviert zu werden. Weitere Informationen finden Sie unter [Anpassen von Dynamics NAV mithilfe von Erweiterungen ](ui-extensions.md).

## <a name="to-enable-the-paypal-payments-standard-service"></a>Zur Aktivierung des Paypal-Zahlungsstandard-Service
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** aus und geben Sie **Zahlungsverkehr** ein. Wählen Sie dann den zugehörigen Link aus.  
2. Wählen Sie im Fenster **Zahlungsverkehr** die Aktion **Neu** aus.
3. Wählen Sie **PayPal Standard** aus, und schließen Sie das Fenster.
4. Wählen Sie im Fenster **Zahlungsverkehr** die Aktion **Einrichten** aus.
5. Füllen Sie die Felder je nach Bedarf aus. Wählen Sie ein Feld aus, um eine kurze Beschreibung des Feldes zu lesen oder einen Link für weitere Informationen zu öffnen.

    **Hinweis**: Wählen Sie **Immer auf Dokument aufführen** aus und aktivieren Sie dazu das Kontrollkästchen, wenn der Link für den Paypal-Zahlungsverkehr immer in Verkaufsbelegen sichtbar sein soll, bei denen Zahlung mit Paypal ausgeführt werden.

6. Schließen Sie das Fenster.

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a>So wählen Sie Paypal-Zahlung-Standards auf einer Verkaufsrechnung aus
1. Auf der Startseite wählen Sie **Verkaufsrechnung** aus.
2. Öffnen Sie die Verkaufsrechnung, auf der Sie Paypal-Zahlungen aktivieren möchten.
3. Geben Sie im Feld **Zahlungsverkehr** Standard Paypal-Zahlungen ein.

**Hinweis**: Das Feld **Zahlungsverkehr** ist nur sichtbar, wenn der Paypal-Zahlungsstandard-Service ausgeführt wird.   

## <a name="see-also"></a>Siehe auch  
[Auftrag einrichten](sales-setup-sales.md)  
[Verkauf verwalten](sales-manage-sales.md)  
[Anpassen des Dynamics NAV mithilfe der Erweiterungen](ui-extensions.md)


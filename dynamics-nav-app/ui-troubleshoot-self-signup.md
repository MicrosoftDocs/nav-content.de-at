---
title: Problembehandlungs-Selbstbedienungs-Registrierung
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 931c427518694cbd0003ea82735292a019b388d5
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---

# <a name="troubleshooting-self-service-sign-up"></a>Problembehandlungs-Selbstbedienungs-Registrierung
Die Anmeldung für das Dynamics NAV kann einfach und kann sehr schnell vorgenommen werden. Sie können ein freies Konto erstellen, wenn es sich um eine vorhandene Organisation handelt. Dieser Artikel bezieht sich Probleme an, die Sie möglicherweise für die die Anmeldung haben.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>Welche E-Mail-Adresse kann ich mit Dynamics NAV verwenden?
Für die Anmeldung in Dynamics NAV benötigen Sie eine Arbeits- oder Schul-E-Mail-Adresse. Dynamics NAV unterstützt keine E-Mail-Adressen, die von E-Mail-Diensten für Endverbraucher oder Telekommunikationsanbietern bereitgestellt werden. Dieses schließt outlook.com, hotmail.com, gmail.com und andere ein.

Wenn Sie versuchen, sich mit einer persönlichen E-Mail-Adresse anzumelden, erhalten Sie eine Meldung die angibt, eine Arbeits- oder Schul-E-mail-Adresse zu verwenden.

## <a name="troubleshooting"></a>Problembehebung
In vielen Fällen kann das Registrieren für Dynamics NAV mit folgendem Registrierungsprozess erfolgen. Es gibt jedoch verschiedene Gründe, warum Sie möglicherweise nicht in der Lage sind, die Selbstregistrierung abzuschließen. Die folgende Tabelle fasst einige der meisten allgemeinen Ursachen zusammen, die verhindern können, wieso Sie möglicherweise nicht in der Lage sind, die Anmeldung abzuschließen und Arten, wie Sie die diese Probleme umgehen können.

|Symptom / Fehlermeldung                                                                             |Codes und Problemumgehung|
|--------------------------------------------------------------------------------------------------|--------------------|
|Für Office 365-E-Mail-Adressen, die nicht in den USA erfasst werden, erhalten Sie eine Meldung wie die Folgende während der Anmeldung: <br>**Das funktioniert nicht, wir unterstützen Ihr Land oder Region nicht.**<br> |Dynamics NAV unterstützt nur registrierte E- Mail-Konten von Office 365 in den USA.|
|Persönliche E-Mail-Adressen wie nancy@gmail.com werden nicht unterstützt. Sie erhalten eine Meldung wie die Folgende während der Anmeldung: <br>**Sie haben eine persönliche E-Mail-Adresse eingegeben: Geben Sie die Arbeits-E-Mail-Adresse ein, sodass wir die Daten der Unternehmung speichern können.**<br> Oder <br> **Diese sieht wie eine persönliche E-Mail-Adresse aus. Geben Sie Ihre Arbeitsadresse ein, so können wir Sie mit anderen in Ihrem Unternehmens verknüpfen. Und sorgen Sie sich nicht. Wir geben Ihre Adresse niemandem weiter** | Dynamics NAV unterstützt keine E-Mail-Adressen, die von E-Mail-Diensten für Endverbraucher oder Telekommunikationsanbietern bereitgestellt werden. Um die Anmeldung abzuschließen, versuchen Sie eine E-Mail-Adresse zu verwenden, die von Ihrer Arbeit oder Schule zugeordnet ist. Wenn Sie sich immer noch nicht anmelden können und bereit sind, eine erweiterte Einrichtung abzuschließen, können Sie sich für ein neues Probeabonnement des neuen Office 365 anmelden und diese E-Mail-Adresse verwenden, um sich anzumelden.
|.gov- oder .mil-E-Mail-Adressen: Sie erhalten Sie eine Meldung wie die Folgende für die Anmeldung: <br>**Dynamics NAV** nicht verfügbar: Dynamics NAV ist nicht für Benutzer mit .gov oder .mil-E-Mail-Adressen. Verwenden Sie eine andere Arbeits-E-Mail-Adresse oder kehren Sie zu einem späteren Zeitpunkt zurück. <br>Oder <br>**Wir können Ihre Anmeldung nicht beenden. Sie sieht so aus, als ob Dynamics NAV zurzeit nicht für die Arbeit oder Schule verfügbar ist.**|Dynamics NAV unterstützt keine .gov oder .mil-Adressen.|
|Der Selbstregistrierungsprozess ist nicht aktiviert. Sie erhalten eine Meldung wie die Folgende während der Anmeldung: <br>**Wir können Ihre Anmeldung nicht beenden. Ihre IT-Abteilung hat die Anmeldung abgeschaltet für Dynamics NAV. Erkundigen Sie sich bei ihnen, um die Anmeldung zu beenden.** <br>Oder <br> **Diese sieht wie eine persönliche E-Mail-Adresse aus. Geben Sie Ihre Arbeitsadresse ein, so können wir Sie mit anderen in Ihrem Unternehmens verknüpfen. Und sorgen Sie sich nicht. Wir geben Ihre Adresse niemandem weiter**|Der IT-Administrator Ihrer Organisation hat die Selbstregistrierung für Dynamics NAV deaktiviert. Um die Anmeldung abzuschließen, wenden Sie sich an Ihren IT-Administrator und bitten Sie diesen, den Instruktionen auf der Seite unten zu folgen, um vorhandenen Benutzern zu ermöglichen, sich für Dynamics NAV anzumelden und neuen Benutzern zu ermöglichen, Ihrem bestehenden Tenant beizutreten. Möglicherweise haben Sie das selbe Problem, wenn Sie sich bei Office 365 über einen Partner anmeldeten.|
|E-Mail-Adresse ist keine Office 365 ID Sie erhalten eine Meldung wie die Folgende während der Anmeldung: <br>**Wir können Sie nicht im contoso.com finden. Verwenden Sie eine andere ID bei der Arbeit oder an der Schule? Versuchen Sie, sich damit anzumelden, falls dies nicht geht, wenden Sie sich an die  IT-Abteilung**|Ihre Organisation verwendet IDs, um sich bei Office 365 und anderen Microsoft-Services anzumelden, die anders sind als Ihre E-Mail-Adresse. Beispielsweise kann Ihre E-Mail-Adresse Nancy.Smith@contoso.com lauten aber Ihre ID ist nancys@contoso.com. Um die Anmeldung abzuschließen, verwenden Sie die ID, die Ihre Organisation zugewiesen hat, um sich bei Office 365 oder anderen Microsoft-Dienstleistungen anzumelden. Wenn Sie nicht wissen, was das ist, wenden Sie sich an Ihren IT-Administrator. Wenn Sie sich immer noch nicht anmelden können und bereit sind, eine erweiterte Einrichtung abzuschließen, können Sie sich für ein neues Probeabonnement des neuen Office 365 anmelden und diese E-Mail-Adresse verwenden, um sich anzumelden.|


## <a name="see-also"></a>Siehe auch
[Willkommen bei Dynamics NAV](across-get-started.md)  
[Arbeiten mit Dynamics NAV](ui-work-product.md)





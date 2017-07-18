---
title: 'Vorgehensweise: Dynamics NAV im Azure Management Portal anmelden'
author: edupont04
manager: edupont
ms.author: edupont
ms.custom: na
ms.date: 11/15/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 225773f7f686dd6e9a79f759d520d66f7e7b9d0a
ms.contentlocale: de-at
ms.lasthandoff: 06/26/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Vorgehensweise: Dynamics NAV im Azure Management Portal anmelden
Wenn Sie Services verwenden wollen, die auf Microsoft Azure sind, müssen Sie Ihr Dynamics NAV im Azure Management Portal erfassen. Beispielsweise benötigt die Erweiterung [Verkauf- und Lagerplanung](ui-extensions-sales-forecast.md), dass Sie einen API-Schlüssel und API URI festlegen, und andere Services können ähnliche Informationen erfordern. Wo findet man diese Informationen?

Sie können das** **Einrichtung des Azure Management Portals** verwenden, um Dynamics NAV im Azure Management Portal zu registrieren, um Informationen, die Sie für Dienste wie für die Verkaufs- und Lagerbestand-Planungserweiterung, Power BI, Office 365 etc. brauchen, abzurufen. Sie müssen sich nur einmal im Azure Management Portal anmelden und Sie müssen ein Administrator oder Superbenutzer in Dynamics NAV sein.

Grund dafür ist, dass Dynamics NAV und der Dienst, mit dem Sie sich verbinden möchten, voneinander die Details für das Azure Active Directory (Azure AD) kennen muss.

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Um sich bei Dynamics NAV im Azure Management Portal anzumelden
1. Melden Sie sich beim Azure Management Portal an unter [https://portal.azure.com](https://portal.azure.com).
    Wenn Sie nicht mit Azure Management Portal vertraut sind, finden Sie bestimme Anleitung in der [Azure Dokumentenbibliothek](https://azure.microsoft.com/en-us/documentation/articles).
2. Im Navigationsbereich links wählen Sie **Weitere Dienste** und wählen dann **App Anmeldung**.
3. Im ersten Menü wählen Sie **Hinzufügen** und **Bereich erstellen**, füllen Sie die Felder mit den folgenden Informationen aus:
    - **Name**: Geben Sie einen Namen für Ihre Dynamics NAV wie *Dynamics NAV* an.
    - **Anwendungstyp**: Wählen Sie **Web-Anwendung* / API**.
    - **Anmeldungs-URL**: Geben Sie die URL für Ihren Dynamics NAV-Browserclient ein, wie *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        Die OAuthLanding.htm- Datei ist eine Datei, die Ihnen dabei hilft den Austausch von Daten zwischen Dynamics NAV und anderen Diensten über Azure AD zu verwalten.
4. Klicken Sie auf die Schaltfläche **Erstellen**.
    Dadurch wird Ihr Dynamics NAV dem **App-Registrierungsbereich** hinzugefügt, sodass Sie jetzt Einstellungen hinzufügen können.
5. In der **App-Registrierungsliste** wählen Sie Ihre neue App aus. Wenn sich der Bereich **Einstellungen** nicht öffnet, sollten Sie eine Aktion vornehmen, um **Einstellungen** zu öffnen.
6. Im Bereich **Einstellungen** im Abschnitt **API-Zugang** wählen Sie **Schlüssel** aus.
7. Im Bereich **Schlüssel** geben Sie eine Beschreibung ein und wenn Sie den Schlüssel ablaufen lassen möchten, wählen Sie **Speichern**.
8. Kopieren Sie den generierten Schlüssel an einen temporäres Lagerort - Sie benötigen dies im folgenden Verfahren.
9. Im Abschnitt **API Access** wählen Sie **Erforderliche Berechtigungen**.
    - Fügen Sie "Delegierute Berechtigungen" hinzu, um alle Berichte im Power BI-Dienst zu sehen.
    - Fügen Sie "Delegierte Berechtigungen" hinzu, um Lesebenutzerprofile zu Windows Azure Active Directory zu unterzeichnen und zu lesen.
    - Wiederholen Sie diesen Vorgang für andere Diensten, für den Sie Zugriff auf Ihren Dynamics NAV gewähren wollen.
10. Schließen Sie den Bereich **Einstellungen** und kopieren Sie im Abschnitt **Grundlagen** den Wert der **Anwendungs-ID** an einen temporären Ort.

Sie haben jetzt Ihr Dynamics NAV im Azure Management Portal erfasst, Sie haben Zugang zu den relevanten Diensten gewährt und Sie haben die Daten extrahiert, die Sie in Dynamics NAV benötigen.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Um Informationen Dynamics NAV hinzuzufügen
1. Wählen Sie in der rechten oberen Ecke das Symbol **Nach Seite oder Bericht suchen** und geben Sie den **Azure AD Anwendungseinrichtungsassistenten** ein. Wählen Sie dann den zugehörigen Link aus.
2. Im Assistenten wählen Sie **Weiter**.
3. Im Feld **Client ID** geben Sie den Inhalt an, den Sie zuvor vom Feld **Anwendungs-ID** kopiert haben.
4. Im Feld **Geheimschlüssel** geben Sie den Inhalt an, den Sie zuvor vom Feld **Schlüssel** kopiert haben.
5. Wählen Sie **Weiter** aus. Sofern Sie keine Fehlermeldung erhalten, ist der Prozess abgeschlossen.

Ihr Dynamics NAV wurde erfasst und vorbereitet, um eine Verbindung zu einem Dienst wie Cortana Intelligence und Power BI herzustellen.

## <a name="see-also"></a>Siehe auch
[Geplanter voraussichtlicher Verkauf und Lagerbestand](ui-extensions-sales-forecast.md)  
[Dynamics NAV einrichten](setup.md)  


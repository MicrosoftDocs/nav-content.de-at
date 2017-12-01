---
title: Verwaltungsaufgaben in Dynamics NAV
description: "Einige Aufgaben in [!INCLUDE[d365fin](includes/d365fin_md.md)] benötigen zentrale Administration und Einrichtung. Erfahren, welche das sind und was zu tun ist."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 3ddb647d28a4065be248a265316b38e8d37d28c2
ms.contentlocale: de-at
ms.lasthandoff: 12/01/2017

---
# <a name="setup-and-administration-in-dynamics-nav"></a><span data-ttu-id="bf35d-104">Einrichtung und Verwaltung in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="bf35d-104">Setup and Administration in Dynamics NAV</span></span>
<span data-ttu-id="bf35d-105">Zentrale Verwaltungsaufgaben werden in der Regel von einer Rolle im Unternehmen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="bf35d-105">Central administration tasks are usually performed by one role in the company.</span></span> <span data-ttu-id="bf35d-106">Der Bereich dieser Aufgaben kann von der Größe des Unternehmens und der Verantwortlichkeiten des Administrators abhängig sein.</span><span class="sxs-lookup"><span data-stu-id="bf35d-106">The scope of these tasks can depend on the company's size and the administrator's job responsibilities.</span></span> <span data-ttu-id="bf35d-107">Diese Aufgaben können die Verwaltung von Datenbanksynchronisierung von Projekt- und E-Mail-Warteschlangen, das Einrichten von Benutzern, das Anpassen der Benutzeroberfläche und Verwalten von Verschlüsselungsschlüsseln enthalten.</span><span class="sxs-lookup"><span data-stu-id="bf35d-107">These tasks can include managing database synchronization of job and email queues, setting up users, customizing the user interface, and managing encryption keys.</span></span>  

<span data-ttu-id="bf35d-108">Die Eingabe der richtigen Einrichtungswerte ist entscheidend für den Erfolg jeder neuen Geschäftssoftware.</span><span class="sxs-lookup"><span data-stu-id="bf35d-108">Entering the correct setup values from the start is important to the success of any new business software.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="bf35d-109"> enthält mehrere Einrichtungshandbücher, die Ihnen dabei helfen, Kerndaten einzurichten.</span><span class="sxs-lookup"><span data-stu-id="bf35d-109"> includes a number of setup guides that help you set up core data.</span></span> <span data-ttu-id="bf35d-110">Weitere Informationen finden Sie unter [EinrichtenDynamics NAV](setup.md)</span><span class="sxs-lookup"><span data-stu-id="bf35d-110">For more information, see [Setting Up Dynamics NAV](setup.md).</span></span>

<!--Whether you use [!INCLUDE[rim](../../includes/rim_md.md)] to implement setup values or you manually enter them in the new company, you can support your setup decisions with some general recommendations for selected setup fields that are known to potentially cause the solution to be inefficient if defined incorrectly.-->  

<span data-ttu-id="bf35d-111">Ein Superuser oder ein Administrator kann das Daten-Exchange-Framework einrichten, um Benutzern zu ermöglichen, Daten in den Bank- und Lohndateien, beispielsweise für verschiedene Bankmanagementprozesse, zu exportieren und zu importieren.</span><span class="sxs-lookup"><span data-stu-id="bf35d-111">A super user or an administrator can set up the Data Exchange Framework to enable users to export and import data in bank and payroll files, for example for various cash management processes.</span></span>  

<span data-ttu-id="bf35d-112">In der folgenden Tabelle wird eine Reihe von Aufgaben mit Verknüpfungen zu den beschriebenen Themen erläutert.</span><span class="sxs-lookup"><span data-stu-id="bf35d-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>   

|<span data-ttu-id="bf35d-113">**Aufgabe**</span><span class="sxs-lookup"><span data-stu-id="bf35d-113">**To**</span></span>|<span data-ttu-id="bf35d-114">**Siehe**</span><span class="sxs-lookup"><span data-stu-id="bf35d-114">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="bf35d-115">Fügen Sie Benutzer hinzu, und verwalten Sie Berechtigungen und den Zugriff auf Daten.</span><span class="sxs-lookup"><span data-stu-id="bf35d-115">Add users, manage permissions and access to data, assign roles.</span></span>|[<span data-ttu-id="bf35d-116">Benutzer, Profile und Rollencenter in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="bf35d-116">Users, Profiles, and Role Centers in Dynamics NAV</span></span>](admin-users-profiles-roles.md)|  
|<span data-ttu-id="bf35d-117">Verfolgen aller direkten Änderungen, die von Benutzern an den Daten in der Datenbank vorgenommen werden, um die Quelle von Fehlern und Datenänderungen zu identifizieren</span><span class="sxs-lookup"><span data-stu-id="bf35d-117">Track all direct modifications that users make to data in the database to identify the origin of errors and data changes.</span></span>|[<span data-ttu-id="bf35d-118">Protokollieren von Änderungen in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="bf35d-118">Logging Changes in Dynamics NAV</span></span>](across-log-changes.md)|  
|<span data-ttu-id="bf35d-119">Unterstützen Sie Ihre Setupentscheidungen mit Empfehlungen für ausgewählte Felder, von denen bekannt ist, dass Sie die Lösung möglicherweise dazu veranlassen, ineffizient zu arbeiten, wenn sie falsch definiert werden.</span><span class="sxs-lookup"><span data-stu-id="bf35d-119">Support your setup decisions with recommendations for selected fields that are known to potentially cause the solution to be inefficient if set up incorrectly</span></span>|[<span data-ttu-id="bf35d-120">Richten Sie komplexe Anwendungsbereiche mithilfe bewährter Methoden ein</span><span class="sxs-lookup"><span data-stu-id="bf35d-120">Set Up Complex Application Areas Using Best Practices</span></span>](set-up-complex-application-areas-using-best-practices.md)|  
|<span data-ttu-id="bf35d-121">Sie können Seiten, Codeunits und Abfragen als Webdienste zur Verfügung stellen.</span><span class="sxs-lookup"><span data-stu-id="bf35d-121">Expose pages, codeunits, and queries as web services.</span></span>|[<span data-ttu-id="bf35d-122">Vorgehensweise: Veröffentlichen eines Webdiensts</span><span class="sxs-lookup"><span data-stu-id="bf35d-122">How to: Publish a Web Service</span></span>](across-how-publish-web-service.md)|  
|<span data-ttu-id="bf35d-123">Richten Sie einen SMTP-Server so ein, dass die E-Mail-Kommunikation mit Dynamics NAV aktiviert ist</span><span class="sxs-lookup"><span data-stu-id="bf35d-123">Set up an SMTP server to enable e-mail communication in and out of Dynamics NAV</span></span>| [<span data-ttu-id="bf35d-124">Vorgehensweise: Richten Sie E-Mail Nachricht manuell oder mit der unterstützten Einrichtung ein</span><span class="sxs-lookup"><span data-stu-id="bf35d-124">How to: Set Up Email Manually or Using the Assisted Setup</span></span>](madeira-how-setup-email.md)|  
|<span data-ttu-id="bf35d-125">Eingeben einzelner oder wiederkehrender Anforderungen zum Ausführen von Berichten oder Codeunits</span><span class="sxs-lookup"><span data-stu-id="bf35d-125">Enter single or recurring requests to run reports or codeunits.</span></span>|[<span data-ttu-id="bf35d-126">Verwenden von Aufgabenwarteschlangen für die Aufgabenplanung</span><span class="sxs-lookup"><span data-stu-id="bf35d-126">Use Job Queues to Schedule Tasks</span></span>](admin-job-queues-schedule-tasks.md)|  
|<span data-ttu-id="bf35d-127">Verwalten, löschen oder komprimieren von Belegen</span><span class="sxs-lookup"><span data-stu-id="bf35d-127">Manage, delete, or compress documents</span></span>|[<span data-ttu-id="bf35d-128">Verwalten von Belegen</span><span class="sxs-lookup"><span data-stu-id="bf35d-128">Manage Documents</span></span>](admin-manage-documents.md)|  

## <a name="see-also"></a><span data-ttu-id="bf35d-129">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="bf35d-129">See Also</span></span>
[<span data-ttu-id="bf35d-130">Überblick über Geschäfts-Funktionalität</span><span class="sxs-lookup"><span data-stu-id="bf35d-130">Overview of Business Functionality</span></span>](madeira-business-functionality.md)  
[<span data-ttu-id="bf35d-131">Allgemeine Geschäftsfunktionen</span><span class="sxs-lookup"><span data-stu-id="bf35d-131">General Business Functionality</span></span>](ui-across-business-areas.md)  
<span data-ttu-id="bf35d-132">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="bf35d-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
<span data-ttu-id="bf35d-133">[Willkommen bei [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="bf35d-133">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  


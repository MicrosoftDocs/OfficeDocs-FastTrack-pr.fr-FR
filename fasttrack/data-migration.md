---
title: Migration des données
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319946"
---
# <a name="data-migration"></a><span data-ttu-id="c4287-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="c4287-104">Data Migration</span></span>

<span data-ttu-id="c4287-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="c4287-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="c4287-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="c4287-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="c4287-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="c4287-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="c4287-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="c4287-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="c4287-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="c4287-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="c4287-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-111">You create and schedule your migration events.</span></span> <span data-ttu-id="c4287-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="c4287-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="c4287-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="c4287-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="c4287-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="c4287-115">Considerations</span></span>

  - <span data-ttu-id="c4287-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="c4287-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="c4287-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="c4287-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="c4287-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="c4287-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="c4287-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="c4287-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="c4287-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="c4287-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="c4287-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="c4287-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="c4287-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="c4287-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-124">Migration service availability</span></span>

  - <span data-ttu-id="c4287-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="c4287-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="c4287-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="c4287-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="c4287-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c4287-127">Migration to Exchange Online</span></span>

<span data-ttu-id="c4287-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4287-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="c4287-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="c4287-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-130">You create and schedule your migration events.</span></span> <span data-ttu-id="c4287-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="c4287-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4287-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c4287-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="c4287-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="c4287-133">Considerations</span></span>

  - <span data-ttu-id="c4287-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c4287-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="c4287-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="c4287-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c4287-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="c4287-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="c4287-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="c4287-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="c4287-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c4287-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="c4287-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="c4287-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="c4287-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="c4287-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="c4287-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="c4287-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="c4287-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="c4287-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="c4287-143">Source environments</span></span>

<span data-ttu-id="c4287-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="c4287-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="c4287-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="c4287-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="c4287-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="c4287-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="c4287-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="c4287-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="c4287-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="c4287-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c4287-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c4287-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c4287-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="c4287-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4287-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="c4287-154">
<strong>Remarque :</strong> pur les dépendances Exchange locales, reportez-vous à  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Configuration requise pour un déploiement hybride</span></a>.</span><span class="sxs-lookup"><span data-stu-id="c4287-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="c4287-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="c4287-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="c4287-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="c4287-156">Emails</span></span></li>
<li><span data-ttu-id="c4287-157">Règles de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="c4287-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="c4287-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="c4287-158">Delegates</span></span></li>
<li><span data-ttu-id="c4287-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="c4287-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c4287-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="c4287-160">Calendar</span></span> </li>
<li> <span data-ttu-id="c4287-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="c4287-161">Tasks</span></span> </li>
<li> <span data-ttu-id="c4287-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="c4287-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="c4287-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="c4287-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="c4287-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="c4287-164">Signatures</span></span> </li>
<li> <span data-ttu-id="c4287-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="c4287-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="c4287-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="c4287-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="c4287-167">Public folders</span></span> </li>
<li> <span data-ttu-id="c4287-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="c4287-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4287-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="c4287-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="c4287-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="c4287-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="c4287-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4287-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="c4287-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4287-174"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="c4287-175">
<strong>Remarque :</strong> votre environnement G Suite doit respecter les conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Effectuer une migration de G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="c4287-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="c4287-176">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="c4287-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-177">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="c4287-177">Emails</span></span> </li>
<li> <span data-ttu-id="c4287-178">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="c4287-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="c4287-179">Calendrier</span><span class="sxs-lookup"><span data-stu-id="c4287-179">Calendar</span></span> </li>
<li> <span data-ttu-id="c4287-180">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="c4287-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-181">Règles</span><span class="sxs-lookup"><span data-stu-id="c4287-181">Rules</span></span> </li>
<li> <span data-ttu-id="c4287-182">Délégués</span><span class="sxs-lookup"><span data-stu-id="c4287-182">Delegates</span></span> </li>
<li> <span data-ttu-id="c4287-183">Signatures</span><span class="sxs-lookup"><span data-stu-id="c4287-183">Signatures</span></span> </li>
<li> <span data-ttu-id="c4287-184">Tâches</span><span class="sxs-lookup"><span data-stu-id="c4287-184">Tasks</span></span> </li>
<li> <span data-ttu-id="c4287-185">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="c4287-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4287-186">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-187">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="c4287-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="c4287-188">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="c4287-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="c4287-189">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4287-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="c4287-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="c4287-191">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="c4287-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="c4287-192">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="c4287-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="c4287-193">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="c4287-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c4287-194">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="c4287-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="c4287-195">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="c4287-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="c4287-196">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4287-197"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="c4287-198">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="c4287-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="c4287-199">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="c4287-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="c4287-200">Règles</span><span class="sxs-lookup"><span data-stu-id="c4287-200">Rules</span></span> </li>
<li> <span data-ttu-id="c4287-201">Délégués</span><span class="sxs-lookup"><span data-stu-id="c4287-201">Delegates</span></span> </li>
<li> <span data-ttu-id="c4287-202">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="c4287-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="c4287-203">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="c4287-203">External contacts</span></span> </li>
<li> <span data-ttu-id="c4287-204">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="c4287-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="c4287-205">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-206">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="c4287-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c4287-207">Calendrier</span><span class="sxs-lookup"><span data-stu-id="c4287-207">Calendar</span></span> </li>
<li> <span data-ttu-id="c4287-208">Signatures</span><span class="sxs-lookup"><span data-stu-id="c4287-208">Signatures</span></span> </li>
<li> <span data-ttu-id="c4287-209">Tâches</span><span class="sxs-lookup"><span data-stu-id="c4287-209">Tasks</span></span> </li>
<li> <span data-ttu-id="c4287-210">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="c4287-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4287-211">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="c4287-211">Archive data</span></span> </li>
<li> <span data-ttu-id="c4287-212">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="c4287-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="c4287-213">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4287-214">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="c4287-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4287-215">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="c4287-215">FastTrack responsibilities</span></span>

<span data-ttu-id="c4287-216">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-217">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4287-218">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="c4287-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="c4287-219">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="c4287-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4287-220">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="c4287-220">Your responsibilities</span></span>

<span data-ttu-id="c4287-221">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-222">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4287-223">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="c4287-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="c4287-224">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c4287-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="c4287-225">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="c4287-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c4287-226">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="c4287-227">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="c4287-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="c4287-228">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="c4287-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="c4287-229">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="c4287-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c4287-230">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="c4287-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="c4287-231">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="c4287-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="c4287-232">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="c4287-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="c4287-233">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="c4287-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="c4287-234">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="c4287-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="c4287-235">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="c4287-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="c4287-236">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="c4287-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="c4287-237">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="c4287-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="c4287-238">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c4287-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="c4287-239">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4287-240">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="c4287-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c4287-241">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-241">You create and schedule your migration events.</span></span> <span data-ttu-id="c4287-242">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="c4287-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4287-243">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c4287-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="c4287-244">Considérations</span><span class="sxs-lookup"><span data-stu-id="c4287-244">Considerations</span></span>

  - <span data-ttu-id="c4287-245">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c4287-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c4287-246">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="c4287-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c4287-247">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="c4287-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c4287-248">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="c4287-248">Source environment details</span></span>

<span data-ttu-id="c4287-249">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="c4287-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c4287-250">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="c4287-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c4287-251">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="c4287-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c4287-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c4287-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c4287-253">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="c4287-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c4287-254">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="c4287-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c4287-255"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c4287-256"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c4287-257"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c4287-258"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4287-259"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c4287-260">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-261">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-261">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-262">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-263">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="c4287-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4287-264">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="c4287-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4287-265">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-266">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-267">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-267">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-268">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-268">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-269">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-269">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-270">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="c4287-271">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="c4287-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c4287-272">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c4287-273">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c4287-274">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-275">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="c4287-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c4287-276">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-277">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="c4287-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="c4287-278">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="c4287-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c4287-279">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="c4287-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c4287-280">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="c4287-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c4287-281">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="c4287-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c4287-282">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="c4287-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c4287-283">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-284">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="c4287-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c4287-285">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="c4287-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c4287-286">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4287-287"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c4287-288">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-289">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="c4287-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="c4287-290">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-291">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-292">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-293">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-294">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-295">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-295">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-296">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-296">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-297">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-297">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-298">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-299">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="c4287-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c4287-300">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-301">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-302">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c4287-303">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-304">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-305">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="c4287-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-306">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-307">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-308">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-309">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-310">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-311">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="c4287-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c4287-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="c4287-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c4287-313">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="c4287-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c4287-314">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="c4287-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c4287-315">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-316">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-317">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="c4287-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c4287-318">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-319">Fichiers marqués comme étant restreints ou ne peuvent pas être copiés</span><span class="sxs-lookup"><span data-stu-id="c4287-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="c4287-320">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4287-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c4287-322">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-323">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-323">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-324">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-325">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-326">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-327">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-328">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-329">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-329">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-330">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-330">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-331">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-331">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-332">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-333">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-334">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-335">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4287-336">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-337">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-338">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="c4287-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-339">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-340">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-341">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-342">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-343">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-344">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="c4287-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c4287-345">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="c4287-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c4287-346">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-347">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-348">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4287-349"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c4287-350">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-351">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-351">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-352">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-353">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-354">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-355">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-356">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-357">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-357">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-358">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-358">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-359">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-359">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-360">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-361">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="c4287-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c4287-362">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-363">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-364">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4287-365">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-366">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-367">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="c4287-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-368">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-369">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-370">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-371">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-372">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="c4287-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c4287-373">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="c4287-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c4287-374">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="c4287-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c4287-375">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="c4287-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c4287-376">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="c4287-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c4287-377">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-378">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="c4287-379">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4287-380">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="c4287-380">FastTrack responsibilities</span></span>

<span data-ttu-id="c4287-381">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-382">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4287-383">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="c4287-383">Your responsibilities</span></span>

<span data-ttu-id="c4287-384">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-385">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="c4287-386">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="c4287-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="c4287-387">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="c4287-388">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="c4287-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="c4287-389">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="c4287-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4287-390">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="c4287-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c4287-391">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-391">You create and schedule your migration events.</span></span> <span data-ttu-id="c4287-392">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="c4287-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4287-393">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="c4287-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="c4287-394">Considérations</span><span class="sxs-lookup"><span data-stu-id="c4287-394">Considerations</span></span>

  - <span data-ttu-id="c4287-395">Toutes les migrations sont soumises aux quotas OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="c4287-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="c4287-396">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="c4287-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c4287-397">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="c4287-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="c4287-398">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="c4287-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c4287-399">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="c4287-399">Source environment details</span></span>

<span data-ttu-id="c4287-400">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="c4287-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c4287-401">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="c4287-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c4287-402">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="c4287-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c4287-403">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c4287-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c4287-404">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="c4287-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c4287-405">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="c4287-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c4287-406"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c4287-407"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c4287-408"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c4287-409"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4287-410"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c4287-411">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-412">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-412">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-413">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-414">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="c4287-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4287-415">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="c4287-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4287-416">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-417">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-418">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-418">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-419">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-419">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-420">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-420">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-421">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c4287-422">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="c4287-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c4287-423">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c4287-424">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c4287-425">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="c4287-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c4287-426">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="c4287-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c4287-427">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-428">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="c4287-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="c4287-429">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="c4287-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c4287-430">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="c4287-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c4287-431">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="c4287-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c4287-432">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="c4287-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c4287-433">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="c4287-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c4287-434">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-435">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="c4287-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c4287-436">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="c4287-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c4287-437">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4287-438"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c4287-439">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-440">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="c4287-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c4287-441">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-442">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-443">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-444">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-445">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-446">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-446">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-447">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-447">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-448">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-448">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-449">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-450">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="c4287-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c4287-451">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-452">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-453">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c4287-454">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-455">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-456">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="c4287-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-457">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-458">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-459">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-460">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-461">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-462">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="c4287-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c4287-463">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="c4287-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c4287-464">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="c4287-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c4287-465">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="c4287-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c4287-466">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-467">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-468">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="c4287-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c4287-469">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-470">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4287-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c4287-472">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-473">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-473">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-474">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-475">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-476">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-477">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-478">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-479">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-479">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-480">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-480">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-481">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-481">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-482">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-483">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-484">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-485">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4287-486">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-487">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-488">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="c4287-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-489">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-490">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-491">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-492">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-493">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="c4287-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4287-494">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="c4287-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c4287-495">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="c4287-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c4287-496">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-497">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-498">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4287-499"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="c4287-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c4287-500">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="c4287-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4287-501">Documents</span><span class="sxs-lookup"><span data-stu-id="c4287-501">Documents</span></span> </li>
<li> <span data-ttu-id="c4287-502">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4287-503">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-504">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4287-505">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="c4287-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4287-506">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="c4287-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4287-507">Date de création</span><span class="sxs-lookup"><span data-stu-id="c4287-507">Created date</span></span> </li>
<li> <span data-ttu-id="c4287-508">Date de modification</span><span class="sxs-lookup"><span data-stu-id="c4287-508">Modified date</span></span> </li>
<li> <span data-ttu-id="c4287-509">Créé par</span><span class="sxs-lookup"><span data-stu-id="c4287-509">Created by</span></span> </li>
<li> <span data-ttu-id="c4287-510">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="c4287-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4287-511">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="c4287-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c4287-512">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="c4287-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4287-513">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="c4287-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4287-514">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="c4287-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4287-515">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="c4287-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-516">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="c4287-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4287-517">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="c4287-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4287-518">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="c4287-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4287-519">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="c4287-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4287-520">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="c4287-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4287-521">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="c4287-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4287-522">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="c4287-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c4287-523">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="c4287-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c4287-524">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="c4287-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c4287-525">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="c4287-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c4287-526">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="c4287-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c4287-527">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="c4287-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c4287-528">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="c4287-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4287-529">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4287-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4287-530">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="c4287-530">FastTrack responsibilities</span></span>

<span data-ttu-id="c4287-531">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-532">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4287-533">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="c4287-533">Your responsibilities</span></span>

<span data-ttu-id="c4287-534">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4287-535">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="c4287-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4287-536">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="c4287-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="c4287-537">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="c4287-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

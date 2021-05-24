---
title: Migration des données
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: 437da2c12375bfc2d9614c452b0685f18ad3d188
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592425"
---
# <a name="data-migration"></a><span data-ttu-id="01ed2-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="01ed2-104">Data Migration</span></span>

<span data-ttu-id="01ed2-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="01ed2-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="01ed2-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="01ed2-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="01ed2-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="01ed2-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="01ed2-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="01ed2-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="01ed2-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="01ed2-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-111">You create and schedule your migration events.</span></span> <span data-ttu-id="01ed2-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="01ed2-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="01ed2-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="01ed2-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="01ed2-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="01ed2-115">Considerations</span></span>

  - <span data-ttu-id="01ed2-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="01ed2-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="01ed2-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="01ed2-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="01ed2-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="01ed2-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="01ed2-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="01ed2-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="01ed2-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="01ed2-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="01ed2-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="01ed2-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="01ed2-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-124">Migration service availability</span></span>

  - <span data-ttu-id="01ed2-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="01ed2-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="01ed2-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="01ed2-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="01ed2-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="01ed2-127">Migration to Exchange Online</span></span>

<span data-ttu-id="01ed2-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="01ed2-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="01ed2-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="01ed2-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-130">You create and schedule your migration events.</span></span> <span data-ttu-id="01ed2-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="01ed2-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="01ed2-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="01ed2-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="01ed2-133">Considerations</span></span>

  - <span data-ttu-id="01ed2-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="01ed2-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="01ed2-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="01ed2-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="01ed2-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="01ed2-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="01ed2-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="01ed2-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="01ed2-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="01ed2-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="01ed2-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="01ed2-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="01ed2-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="01ed2-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="01ed2-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="01ed2-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="01ed2-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="01ed2-143">Source environments</span></span>

<span data-ttu-id="01ed2-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="01ed2-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="01ed2-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="01ed2-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="01ed2-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="01ed2-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="01ed2-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="01ed2-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="01ed2-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="01ed2-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="01ed2-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="01ed2-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="01ed2-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="01ed2-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="01ed2-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="01ed2-154">
<strong>Remarque :</strong> Pour les dépendances de Exchange sur site, consultez les <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">conditions préalables au déploiement hybride.</span></a></span><span class="sxs-lookup"><span data-stu-id="01ed2-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="01ed2-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="01ed2-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="01ed2-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="01ed2-156">Emails</span></span></li>
<li><span data-ttu-id="01ed2-157">Règles de boîte aux lettres côté serveur</span><span class="sxs-lookup"><span data-stu-id="01ed2-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="01ed2-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="01ed2-158">Delegates</span></span></li>
<li><span data-ttu-id="01ed2-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="01ed2-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="01ed2-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="01ed2-160">Calendar</span></span> </li>
<li> <span data-ttu-id="01ed2-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="01ed2-161">Tasks</span></span> </li>
<li> <span data-ttu-id="01ed2-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="01ed2-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="01ed2-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="01ed2-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="01ed2-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="01ed2-164">Signatures</span></span> </li>
<li> <span data-ttu-id="01ed2-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="01ed2-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="01ed2-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="01ed2-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="01ed2-167">Public folders</span></span> </li>
<li> <span data-ttu-id="01ed2-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="01ed2-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="01ed2-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="01ed2-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="01ed2-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="01ed2-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="01ed2-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="01ed2-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="01ed2-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="01ed2-174">Règles de boîte aux lettres côté client</span><span class="sxs-lookup"><span data-stu-id="01ed2-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-175"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="01ed2-176">
<strong>Remarque :</strong> Votre environnement G Suite doit respecter les conditions préalables décrites dans [Effectuer une migration G Suite.](/Exchange/mailbox-migration/perform-g-suite-migration)</span><span class="sxs-lookup"><span data-stu-id="01ed2-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in [Perform a G Suite migration](/Exchange/mailbox-migration/perform-g-suite-migration).</span></span></td>
<td><span data-ttu-id="01ed2-177">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="01ed2-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-178">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="01ed2-178">Emails</span></span> </li>
<li> <span data-ttu-id="01ed2-179">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="01ed2-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="01ed2-180">Calendrier</span><span class="sxs-lookup"><span data-stu-id="01ed2-180">Calendar</span></span> </li>
<li> <span data-ttu-id="01ed2-181">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="01ed2-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-182">Règles</span><span class="sxs-lookup"><span data-stu-id="01ed2-182">Rules</span></span> </li>
<li> <span data-ttu-id="01ed2-183">Délégués</span><span class="sxs-lookup"><span data-stu-id="01ed2-183">Delegates</span></span> </li>
<li> <span data-ttu-id="01ed2-184">Signatures</span><span class="sxs-lookup"><span data-stu-id="01ed2-184">Signatures</span></span> </li>
<li> <span data-ttu-id="01ed2-185">Tâches</span><span class="sxs-lookup"><span data-stu-id="01ed2-185">Tasks</span></span> </li>
<li> <span data-ttu-id="01ed2-186">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="01ed2-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="01ed2-187">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-188">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="01ed2-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="01ed2-189">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="01ed2-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="01ed2-190">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="01ed2-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="01ed2-192">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="01ed2-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="01ed2-193">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="01ed2-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="01ed2-194">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="01ed2-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="01ed2-195">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="01ed2-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="01ed2-196">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="01ed2-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="01ed2-197">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="01ed2-198"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="01ed2-199">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="01ed2-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="01ed2-200">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="01ed2-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="01ed2-201">Règles</span><span class="sxs-lookup"><span data-stu-id="01ed2-201">Rules</span></span> </li>
<li> <span data-ttu-id="01ed2-202">Délégués</span><span class="sxs-lookup"><span data-stu-id="01ed2-202">Delegates</span></span> </li>
<li> <span data-ttu-id="01ed2-203">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="01ed2-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="01ed2-204">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="01ed2-204">External contacts</span></span> </li>
<li> <span data-ttu-id="01ed2-205">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="01ed2-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="01ed2-206">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-207">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="01ed2-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="01ed2-208">Calendrier</span><span class="sxs-lookup"><span data-stu-id="01ed2-208">Calendar</span></span> </li>
<li> <span data-ttu-id="01ed2-209">Signatures</span><span class="sxs-lookup"><span data-stu-id="01ed2-209">Signatures</span></span> </li>
<li> <span data-ttu-id="01ed2-210">Tâches</span><span class="sxs-lookup"><span data-stu-id="01ed2-210">Tasks</span></span> </li>
<li> <span data-ttu-id="01ed2-211">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="01ed2-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="01ed2-212">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="01ed2-212">Archive data</span></span> </li>
<li> <span data-ttu-id="01ed2-213">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="01ed2-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="01ed2-214">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="01ed2-215">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="01ed2-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="01ed2-216">Responsabilités fastTrack pour les migrations Exchange Online migrations</span><span class="sxs-lookup"><span data-stu-id="01ed2-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="01ed2-217">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-218">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="01ed2-219">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="01ed2-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="01ed2-220">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="01ed2-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="01ed2-221">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="01ed2-221">Your responsibilities</span></span>

<span data-ttu-id="01ed2-222">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-223">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="01ed2-224">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="01ed2-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="01ed2-225">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="01ed2-226">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="01ed2-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="01ed2-227">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="01ed2-228">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="01ed2-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="01ed2-229">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="01ed2-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="01ed2-230">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="01ed2-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="01ed2-231">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="01ed2-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="01ed2-232">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="01ed2-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="01ed2-233">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="01ed2-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="01ed2-234">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="01ed2-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="01ed2-235">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="01ed2-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="01ed2-236">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="01ed2-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="01ed2-237">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="01ed2-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="01ed2-238">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="01ed2-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="01ed2-239">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="01ed2-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="01ed2-240">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="01ed2-241">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="01ed2-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="01ed2-242">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-242">You create and schedule your migration events.</span></span> <span data-ttu-id="01ed2-243">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="01ed2-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="01ed2-244">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="01ed2-245">Considérations</span><span class="sxs-lookup"><span data-stu-id="01ed2-245">Considerations</span></span>

 - <span data-ttu-id="01ed2-246">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="01ed2-247">Reportez-vous <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limites pour</a> plus d’informations.</span><span class="sxs-lookup"><span data-stu-id="01ed2-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="01ed2-248">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="01ed2-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="01ed2-249">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="01ed2-249">Source environment details</span></span>

<span data-ttu-id="01ed2-250">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="01ed2-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="01ed2-251">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="01ed2-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="01ed2-252">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="01ed2-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="01ed2-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="01ed2-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="01ed2-254">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="01ed2-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="01ed2-255">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="01ed2-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="01ed2-256"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="01ed2-257"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="01ed2-258"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="01ed2-259"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="01ed2-260"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="01ed2-261">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-262">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-262">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-263">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-264">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-265">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-266">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-267">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-268">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-268">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-269">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-269">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-270">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-270">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-271">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="01ed2-272">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="01ed2-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="01ed2-273">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="01ed2-274">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="01ed2-275">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-276">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-277">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-278">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-279">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="01ed2-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="01ed2-280">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="01ed2-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="01ed2-281">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="01ed2-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="01ed2-282">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="01ed2-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="01ed2-283">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="01ed2-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="01ed2-284">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-285">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="01ed2-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="01ed2-286">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="01ed2-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="01ed2-287">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-288"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="01ed2-289">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-290">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="01ed2-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="01ed2-291">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-292">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-293">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-294">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-295">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-296">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-296">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-297">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-297">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-298">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-298">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-299">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-300">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="01ed2-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="01ed2-301">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-302">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-303">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="01ed2-304">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-305">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-306">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-307">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-308">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-309">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-310">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-311">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-312">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="01ed2-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="01ed2-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="01ed2-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="01ed2-314">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="01ed2-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="01ed2-315">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="01ed2-316">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-317">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-318">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="01ed2-319">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-320">Fichiers marqués comme étant restreints ou non copiables</span><span class="sxs-lookup"><span data-stu-id="01ed2-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="01ed2-321">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="01ed2-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="01ed2-323">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-324">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-324">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-325">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-326">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-327">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-328">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-329">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-330">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-330">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-331">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-331">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-332">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-332">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-333">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-334">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="01ed2-335">Notes Box (converties au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="01ed2-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-336">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-337">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-338">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-339">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-340">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-341">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-342">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-343">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-344">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-345">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-346">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="01ed2-347">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="01ed2-348">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-349">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-350">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-351"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="01ed2-352">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-353">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-353">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-354">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-355">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-356">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-357">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-358">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-359">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-359">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-360">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-360">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-361">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-361">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-362">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-363">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="01ed2-364">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-365">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-366">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-367">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-368">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-369">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-370">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-371">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-372">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-373">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-374">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="01ed2-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="01ed2-375">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="01ed2-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="01ed2-376">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="01ed2-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="01ed2-377">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="01ed2-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="01ed2-378">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="01ed2-379">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-380">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="01ed2-381">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="01ed2-382">Responsabilités fastTrack pour les migrations SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="01ed2-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="01ed2-383">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-384">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="01ed2-385">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="01ed2-385">Your responsibilities</span></span>

<span data-ttu-id="01ed2-386">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-387">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="01ed2-388">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="01ed2-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="01ed2-389">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="01ed2-390">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="01ed2-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="01ed2-391">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="01ed2-392">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="01ed2-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="01ed2-393">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-393">You create and schedule your migration events.</span></span> <span data-ttu-id="01ed2-394">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="01ed2-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="01ed2-395">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="01ed2-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="01ed2-396">Considérations</span><span class="sxs-lookup"><span data-stu-id="01ed2-396">Considerations</span></span>

  - <span data-ttu-id="01ed2-397">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="01ed2-398">Reportez-vous <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limites pour</a> plus d’informations.</span><span class="sxs-lookup"><span data-stu-id="01ed2-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="01ed2-399">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="01ed2-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="01ed2-400">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="01ed2-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="01ed2-401">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="01ed2-401">Source environment details</span></span>

<span data-ttu-id="01ed2-402">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="01ed2-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="01ed2-403">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="01ed2-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="01ed2-404">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="01ed2-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="01ed2-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="01ed2-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="01ed2-406">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="01ed2-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="01ed2-407">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="01ed2-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="01ed2-408"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="01ed2-409"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="01ed2-410"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="01ed2-411"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="01ed2-412"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="01ed2-413">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-414">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-414">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-415">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-416">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-417">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-418">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-419">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-420">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-420">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-421">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-421">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-422">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-422">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-423">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="01ed2-424">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="01ed2-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="01ed2-425">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="01ed2-426">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="01ed2-427">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="01ed2-428">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-429">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-430">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-431">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="01ed2-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="01ed2-432">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="01ed2-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="01ed2-433">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="01ed2-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="01ed2-434">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="01ed2-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="01ed2-435">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="01ed2-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="01ed2-436">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-437">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="01ed2-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="01ed2-438">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="01ed2-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="01ed2-439">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-440"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="01ed2-441">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-442">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="01ed2-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="01ed2-443">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-444">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-445">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-446">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-447">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-448">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-448">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-449">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-449">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-450">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-450">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-451">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-452">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="01ed2-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="01ed2-453">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-454">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-455">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="01ed2-456">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-457">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-458">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-459">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-460">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-461">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-462">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-463">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-464">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="01ed2-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="01ed2-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="01ed2-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="01ed2-466">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="01ed2-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="01ed2-467">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="01ed2-468">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-469">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-470">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="01ed2-471">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-472">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="01ed2-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="01ed2-474">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-475">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-475">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-476">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-477">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-478">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-479">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-480">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-481">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-481">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-482">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-482">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-483">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-483">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-484">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-485">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-486">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-487">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-488">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-489">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-490">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-491">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-492">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-493">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-494">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-495">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-496">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="01ed2-497">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="01ed2-498">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-499">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-500">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-501"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="01ed2-502">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-503">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-503">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-504">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-505">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-506">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-507">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-508">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-509">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-509">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-510">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-510">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-511">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-511">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-512">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-513">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="01ed2-514">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="01ed2-515">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-516">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-517">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-518">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-519">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-520">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-521">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-522">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-523">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-524">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="01ed2-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="01ed2-525">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="01ed2-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="01ed2-526">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="01ed2-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="01ed2-527">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="01ed2-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="01ed2-528">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="01ed2-529">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-530">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-531">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="01ed2-532">Responsabilités fastTrack pour les migrations OneDrive Entreprise migrations</span><span class="sxs-lookup"><span data-stu-id="01ed2-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="01ed2-533">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-534">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="01ed2-535">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="01ed2-535">Your responsibilities</span></span>

<span data-ttu-id="01ed2-536">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-537">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="01ed2-538">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="01ed2-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="01ed2-539">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="01ed2-540">Migration vers Microsoft Teams et Microsoft 365 groupes</span><span class="sxs-lookup"><span data-stu-id="01ed2-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="01ed2-541">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers des groupes Microsoft Teams et Microsoft 365, nous fournissons des conseils de migration et des services de migration de données.</span><span class="sxs-lookup"><span data-stu-id="01ed2-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="01ed2-542">Nous vous fournissons des conseils pour vous aider à planifier votre migration, à configurer vos environnements sources et vos groupes Teams et Microsoft 365, et à tirer parti de nos services de migration de données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="01ed2-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="01ed2-543">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-543">You create and schedule your migration events.</span></span> <span data-ttu-id="01ed2-544">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="01ed2-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="01ed2-545">Une fois vos événements de migration terminés, vous pouvez vous attendre à ce que les fichiers provenant de sources éligibles et correctement programmées de vos environnements sources soient migrés vers les groupes Teams et Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="01ed2-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="01ed2-546">Teams et Microsoft 365 groupes doivent être pré-mis en service par le client avant de pouvoir migrer les données vers ces types de destination.</span><span class="sxs-lookup"><span data-stu-id="01ed2-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="01ed2-547">Teams et Microsoft 365 groupes de données ont une incidence sur vos autorisations sur l’emplacement de destination du fichier.</span><span class="sxs-lookup"><span data-stu-id="01ed2-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="01ed2-548">Teams et Microsoft 365 groupes sont conçus pour permettre la collaboration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="01ed2-549">Le Teams ou le groupe Microsoft 365 déterminer qui a accès à ces fichiers lors de la migration vers ces destinations.</span><span class="sxs-lookup"><span data-stu-id="01ed2-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="01ed2-550">FastTrack n’ajoute pas d’utilisateurs finaux ou de groupes aux autorisations Teams canal ou Microsoft 365 groupes au cours de la migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="01ed2-551">Considérations</span><span class="sxs-lookup"><span data-stu-id="01ed2-551">Considerations</span></span>

- <span data-ttu-id="01ed2-552">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="01ed2-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="01ed2-553">Reportez-vous <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limites pour</a> plus d’informations.</span><span class="sxs-lookup"><span data-stu-id="01ed2-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="01ed2-554">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="01ed2-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="01ed2-555">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="01ed2-555">Source environment details</span></span>

<span data-ttu-id="01ed2-556">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="01ed2-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="01ed2-557">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="01ed2-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="01ed2-558">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="01ed2-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="01ed2-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="01ed2-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="01ed2-560">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="01ed2-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="01ed2-561">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="01ed2-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="01ed2-562"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="01ed2-563"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="01ed2-564"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="01ed2-565"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="01ed2-566"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="01ed2-567">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-568">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-568">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-569">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-570">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-571">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-572">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-573">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-574">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-574">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-575">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-575">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-576">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-576">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-577">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="01ed2-578">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="01ed2-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="01ed2-579">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="01ed2-580">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="01ed2-581">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="01ed2-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="01ed2-582">Les autorisations sont impactées par Microsoft 365 groupe et/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="01ed2-583">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil d’autorisations final sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="01ed2-584">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-585">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-586">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-587">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="01ed2-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="01ed2-588">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="01ed2-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="01ed2-589">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="01ed2-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="01ed2-590">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="01ed2-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="01ed2-591">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="01ed2-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="01ed2-592">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="01ed2-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="01ed2-593">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-594">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="01ed2-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="01ed2-595">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="01ed2-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="01ed2-596">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-597"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="01ed2-598">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-599">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="01ed2-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="01ed2-600">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-601">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-602">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-603">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-604">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-605">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-605">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-606">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-606">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-607">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-607">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-608">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-609">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="01ed2-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="01ed2-610">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="01ed2-611">\*Les autorisations sont impactées par le Microsoft 365 groupe et/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="01ed2-612">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil d’autorisations final sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="01ed2-613">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="01ed2-614">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-615">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="01ed2-616">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-617">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-618">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-619">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-620">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-621">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-622">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-623">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-624">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="01ed2-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="01ed2-625">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="01ed2-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="01ed2-626">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="01ed2-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="01ed2-627">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="01ed2-628">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-629">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-630">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="01ed2-631">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-632">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="01ed2-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="01ed2-634">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-635">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-635">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-636">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-637">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-638">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-639">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-640">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-641">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-641">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-642">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-642">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-643">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-643">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-644">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-645">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="01ed2-646">Notes Box (converties au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="01ed2-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="01ed2-647">\*Les autorisations sont impactées par le Microsoft 365 groupe et/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="01ed2-648">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil d’autorisations final sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="01ed2-649">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="01ed2-650">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-651">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-652">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-653">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-654">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-655">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-656">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-657">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-658">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-659">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="01ed2-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="01ed2-660">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="01ed2-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="01ed2-661">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="01ed2-662">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-663">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-664">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="01ed2-665"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="01ed2-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="01ed2-666">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="01ed2-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="01ed2-667">Documents</span><span class="sxs-lookup"><span data-stu-id="01ed2-667">Documents</span></span> </li>
<li> <span data-ttu-id="01ed2-668">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="01ed2-669">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-670">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="01ed2-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="01ed2-671">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="01ed2-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="01ed2-672">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="01ed2-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="01ed2-673">Date de création</span><span class="sxs-lookup"><span data-stu-id="01ed2-673">Created date</span></span> </li>
<li> <span data-ttu-id="01ed2-674">Date de modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-674">Modified date</span></span> </li>
<li> <span data-ttu-id="01ed2-675">Créé par</span><span class="sxs-lookup"><span data-stu-id="01ed2-675">Created by</span></span> </li>
<li> <span data-ttu-id="01ed2-676">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="01ed2-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="01ed2-677">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="01ed2-678">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="01ed2-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="01ed2-679">\*Les autorisations sont impactées par le Microsoft 365 groupe et/ou Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="01ed2-680">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil d’autorisations final sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="01ed2-681">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un Microsoft Teams canal.</span><span class="sxs-lookup"><span data-stu-id="01ed2-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="01ed2-682">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="01ed2-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="01ed2-683">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="01ed2-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="01ed2-684">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="01ed2-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-685">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="01ed2-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="01ed2-686">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="01ed2-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="01ed2-687">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="01ed2-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="01ed2-688">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="01ed2-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="01ed2-689">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="01ed2-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="01ed2-690">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="01ed2-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="01ed2-691">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="01ed2-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="01ed2-692">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="01ed2-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="01ed2-693">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="01ed2-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="01ed2-694">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="01ed2-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="01ed2-695">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="01ed2-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="01ed2-696">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="01ed2-697">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="01ed2-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="01ed2-698">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations SharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="01ed2-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="01ed2-699">Responsabilités fastTrack pour les migrations Microsoft Teams et Microsoft 365 groupes</span><span class="sxs-lookup"><span data-stu-id="01ed2-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="01ed2-700">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-701">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="01ed2-702">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="01ed2-702">Your responsibilities</span></span> 

<span data-ttu-id="01ed2-703">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="01ed2-704">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="01ed2-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="01ed2-705">Vous effectuez également les activités suivantes, spécifiques aux migrations Microsoft Teams et Microsoft 365 groupes :</span><span class="sxs-lookup"><span data-stu-id="01ed2-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="01ed2-706">Approvisionnement de tous Microsoft Teams et groupes Microsoft 365 comme ciblé par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="01ed2-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="01ed2-707">FastTrack ne pré-provisione pas les Microsoft Teams ou Microsoft 365 groupes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="01ed2-708">FastTrack n’ajoute pas d’utilisateurs finaux ou de groupes à Microsoft Teams canaux ou Microsoft 365 groupes.</span><span class="sxs-lookup"><span data-stu-id="01ed2-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="01ed2-709">Vous devez ajouter vos utilisateurs finaux ou groupes à tous les canaux Microsoft Teams et groupes Microsoft 365 avant de migrer les données vers ces destinations afin que ces utilisateurs finaux ont accès à ces documents récemment migrés.</span><span class="sxs-lookup"><span data-stu-id="01ed2-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>
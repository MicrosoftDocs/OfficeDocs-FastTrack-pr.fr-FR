---
title: Migration des données
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817711"
---
# <a name="data-migration"></a><span data-ttu-id="cb6d7-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="cb6d7-104">Data Migration</span></span>

<span data-ttu-id="cb6d7-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="cb6d7-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="cb6d7-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="cb6d7-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="cb6d7-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="cb6d7-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="cb6d7-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-111">You create and schedule your migration events.</span></span> <span data-ttu-id="cb6d7-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="cb6d7-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="cb6d7-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="cb6d7-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb6d7-115">Considerations</span></span>

  - <span data-ttu-id="cb6d7-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="cb6d7-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="cb6d7-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="cb6d7-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="cb6d7-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="cb6d7-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="cb6d7-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="cb6d7-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="cb6d7-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-124">Migration service availability</span></span>

  - <span data-ttu-id="cb6d7-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="cb6d7-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="cb6d7-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="cb6d7-127">Migration to Exchange Online</span></span>

<span data-ttu-id="cb6d7-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb6d7-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="cb6d7-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-130">You create and schedule your migration events.</span></span> <span data-ttu-id="cb6d7-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb6d7-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="cb6d7-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb6d7-133">Considerations</span></span>

  - <span data-ttu-id="cb6d7-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="cb6d7-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="cb6d7-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="cb6d7-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="cb6d7-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="cb6d7-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="cb6d7-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="cb6d7-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="cb6d7-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="cb6d7-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="cb6d7-143">Source environments</span></span>

<span data-ttu-id="cb6d7-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="cb6d7-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="cb6d7-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="cb6d7-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="cb6d7-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="cb6d7-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="cb6d7-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="cb6d7-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="cb6d7-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb6d7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="cb6d7-154">
<strong>Remarque :</strong> pur les dépendances Exchange locales, reportez-vous à  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Configuration requise pour un déploiement hybride</span></a>.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="cb6d7-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="cb6d7-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="cb6d7-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb6d7-156">Emails</span></span></li>
<li><span data-ttu-id="cb6d7-157">Règles de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="cb6d7-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="cb6d7-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb6d7-158">Delegates</span></span></li>
<li><span data-ttu-id="cb6d7-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="cb6d7-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="cb6d7-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-160">Calendar</span></span> </li>
<li> <span data-ttu-id="cb6d7-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb6d7-161">Tasks</span></span> </li>
<li> <span data-ttu-id="cb6d7-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="cb6d7-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="cb6d7-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="cb6d7-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-164">Signatures</span></span> </li>
<li> <span data-ttu-id="cb6d7-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="cb6d7-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="cb6d7-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="cb6d7-167">Public folders</span></span> </li>
<li> <span data-ttu-id="cb6d7-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb6d7-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb6d7-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="cb6d7-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="cb6d7-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="cb6d7-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb6d7-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb6d7-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb6d7-174"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="cb6d7-175">
<strong>Remarque :</strong> votre environnement G Suite doit respecter les conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Effectuer une migration de G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="cb6d7-176">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="cb6d7-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-177">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb6d7-177">Emails</span></span> </li>
<li> <span data-ttu-id="cb6d7-178">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="cb6d7-179">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-179">Calendar</span></span> </li>
<li> <span data-ttu-id="cb6d7-180">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="cb6d7-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-181">Règles</span><span class="sxs-lookup"><span data-stu-id="cb6d7-181">Rules</span></span> </li>
<li> <span data-ttu-id="cb6d7-182">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb6d7-182">Delegates</span></span> </li>
<li> <span data-ttu-id="cb6d7-183">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-183">Signatures</span></span> </li>
<li> <span data-ttu-id="cb6d7-184">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb6d7-184">Tasks</span></span> </li>
<li> <span data-ttu-id="cb6d7-185">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb6d7-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb6d7-186">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-187">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="cb6d7-188">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="cb6d7-189">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb6d7-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="cb6d7-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="cb6d7-191">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="cb6d7-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="cb6d7-192">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="cb6d7-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="cb6d7-193">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb6d7-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="cb6d7-194">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="cb6d7-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="cb6d7-195">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="cb6d7-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="cb6d7-196">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb6d7-197"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-198">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="cb6d7-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="cb6d7-199">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb6d7-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-200">Règles</span><span class="sxs-lookup"><span data-stu-id="cb6d7-200">Rules</span></span> </li>
<li> <span data-ttu-id="cb6d7-201">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb6d7-201">Delegates</span></span> </li>
<li> <span data-ttu-id="cb6d7-202">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="cb6d7-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="cb6d7-203">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="cb6d7-203">External contacts</span></span> </li>
<li> <span data-ttu-id="cb6d7-204">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="cb6d7-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="cb6d7-205">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-206">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="cb6d7-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="cb6d7-207">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-207">Calendar</span></span> </li>
<li> <span data-ttu-id="cb6d7-208">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-208">Signatures</span></span> </li>
<li> <span data-ttu-id="cb6d7-209">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb6d7-209">Tasks</span></span> </li>
<li> <span data-ttu-id="cb6d7-210">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb6d7-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb6d7-211">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="cb6d7-211">Archive data</span></span> </li>
<li> <span data-ttu-id="cb6d7-212">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="cb6d7-213">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb6d7-214">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb6d7-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb6d7-215">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb6d7-215">FastTrack responsibilities</span></span>

<span data-ttu-id="cb6d7-216">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-217">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb6d7-218">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="cb6d7-219">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb6d7-220">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb6d7-220">Your responsibilities</span></span>

<span data-ttu-id="cb6d7-221">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-222">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb6d7-223">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="cb6d7-224">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="cb6d7-225">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="cb6d7-226">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="cb6d7-227">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="cb6d7-228">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="cb6d7-229">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="cb6d7-230">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="cb6d7-231">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="cb6d7-232">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="cb6d7-233">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="cb6d7-234">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="cb6d7-235">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="cb6d7-236">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="cb6d7-237">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="cb6d7-238">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="cb6d7-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="cb6d7-239">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb6d7-240">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="cb6d7-241">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-241">You create and schedule your migration events.</span></span> <span data-ttu-id="cb6d7-242">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb6d7-243">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="cb6d7-244">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb6d7-244">Considerations</span></span>

  - <span data-ttu-id="cb6d7-245">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="cb6d7-246">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="cb6d7-247">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="cb6d7-248">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="cb6d7-248">Source environment details</span></span>

<span data-ttu-id="cb6d7-249">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="cb6d7-250">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="cb6d7-251">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="cb6d7-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="cb6d7-253">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="cb6d7-254">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="cb6d7-255"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="cb6d7-256"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="cb6d7-257"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="cb6d7-258"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb6d7-259"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="cb6d7-260">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-261">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-261">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-262">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-263">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb6d7-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb6d7-264">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb6d7-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb6d7-265">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-266">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-267">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-267">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-268">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-268">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-269">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-269">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-270">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="cb6d7-271">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="cb6d7-272">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="cb6d7-273">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="cb6d7-274">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-275">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="cb6d7-276">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-277">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="cb6d7-278">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="cb6d7-279">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="cb6d7-280">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="cb6d7-281">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="cb6d7-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="cb6d7-282">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="cb6d7-283">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-284">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="cb6d7-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="cb6d7-285">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="cb6d7-286">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb6d7-287"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-288">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-289">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="cb6d7-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="cb6d7-290">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-291">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-292">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-293">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-294">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-295">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-295">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-296">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-296">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-297">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-297">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-298">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-299">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="cb6d7-300">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-301">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-302">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="cb6d7-303">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-304">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-305">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-306">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-307">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-308">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-309">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-310">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-311">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="cb6d7-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="cb6d7-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="cb6d7-313">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="cb6d7-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="cb6d7-314">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="cb6d7-315">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-316">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-317">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="cb6d7-318">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-319">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb6d7-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-321">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-322">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-322">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-323">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-324">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-325">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-326">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-327">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-328">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-328">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-329">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-329">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-330">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-330">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-331">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-332">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-333">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-334">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb6d7-335">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-336">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-337">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="cb6d7-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-338">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-339">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-340">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-341">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-342">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-343">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="cb6d7-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="cb6d7-344">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="cb6d7-345">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-346">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-347">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb6d7-348"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-349">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-350">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-350">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-351">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-352">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-353">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-354">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-355">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-356">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-356">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-357">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-357">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-358">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-358">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-359">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-360">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="cb6d7-361">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-362">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-363">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb6d7-364">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-365">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-366">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-367">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-368">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-369">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-370">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-371">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="cb6d7-372">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="cb6d7-373">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="cb6d7-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="cb6d7-374">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="cb6d7-375">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="cb6d7-376">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-377">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="cb6d7-378">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb6d7-379">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb6d7-379">FastTrack responsibilities</span></span>

<span data-ttu-id="cb6d7-380">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-381">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb6d7-382">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb6d7-382">Your responsibilities</span></span>

<span data-ttu-id="cb6d7-383">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-384">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="cb6d7-385">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="cb6d7-386">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="cb6d7-387">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="cb6d7-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="cb6d7-388">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb6d7-389">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="cb6d7-390">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-390">You create and schedule your migration events.</span></span> <span data-ttu-id="cb6d7-391">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb6d7-392">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="cb6d7-393">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb6d7-393">Considerations</span></span>

  - <span data-ttu-id="cb6d7-394">Toutes les migrations sont soumises aux quotas OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="cb6d7-395">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="cb6d7-396">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="cb6d7-397">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="cb6d7-398">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="cb6d7-398">Source environment details</span></span>

<span data-ttu-id="cb6d7-399">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="cb6d7-400">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="cb6d7-401">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="cb6d7-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="cb6d7-403">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="cb6d7-404">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="cb6d7-405"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="cb6d7-406"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="cb6d7-407"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="cb6d7-408"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb6d7-409"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="cb6d7-410">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-411">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-411">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-412">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-413">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb6d7-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb6d7-414">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb6d7-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb6d7-415">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-416">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-417">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-417">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-418">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-418">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-419">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-419">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-420">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="cb6d7-421">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="cb6d7-422">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="cb6d7-423">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="cb6d7-424">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="cb6d7-425">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="cb6d7-426">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-427">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb6d7-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="cb6d7-428">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="cb6d7-429">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="cb6d7-430">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="cb6d7-431">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="cb6d7-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="cb6d7-432">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="cb6d7-433">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-434">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="cb6d7-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="cb6d7-435">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="cb6d7-436">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb6d7-437"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-438">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-439">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="cb6d7-440">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-441">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-442">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-443">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-444">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-445">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-445">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-446">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-446">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-447">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-447">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-448">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-449">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="cb6d7-450">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-451">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-452">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="cb6d7-453">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-454">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-455">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-456">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-457">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-458">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-459">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-460">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-461">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="cb6d7-462">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="cb6d7-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="cb6d7-463">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="cb6d7-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="cb6d7-464">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="cb6d7-465">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-466">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-467">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="cb6d7-468">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-469">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb6d7-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-471">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-472">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-472">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-473">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-474">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-475">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-476">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-477">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-478">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-478">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-479">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-479">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-480">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-480">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-481">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-482">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-483">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-484">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb6d7-485">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-486">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-487">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="cb6d7-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-488">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-489">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-490">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-491">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-492">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb6d7-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb6d7-493">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="cb6d7-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="cb6d7-494">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="cb6d7-495">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-496">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-497">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb6d7-498"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="cb6d7-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="cb6d7-499">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb6d7-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-500">Documents</span><span class="sxs-lookup"><span data-stu-id="cb6d7-500">Documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-501">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb6d7-502">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-503">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-504">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb6d7-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb6d7-505">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb6d7-506">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb6d7-506">Created date</span></span> </li>
<li> <span data-ttu-id="cb6d7-507">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-507">Modified date</span></span> </li>
<li> <span data-ttu-id="cb6d7-508">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb6d7-508">Created by</span></span> </li>
<li> <span data-ttu-id="cb6d7-509">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb6d7-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb6d7-510">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="cb6d7-511">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb6d7-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb6d7-512">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb6d7-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb6d7-513">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb6d7-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb6d7-514">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb6d7-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-515">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb6d7-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb6d7-516">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb6d7-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb6d7-517">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb6d7-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb6d7-518">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb6d7-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb6d7-519">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb6d7-520">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb6d7-521">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="cb6d7-522">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="cb6d7-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="cb6d7-523">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="cb6d7-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="cb6d7-524">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="cb6d7-525">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="cb6d7-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="cb6d7-526">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="cb6d7-527">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb6d7-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb6d7-528">Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb6d7-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb6d7-529">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb6d7-529">FastTrack responsibilities</span></span>

<span data-ttu-id="cb6d7-530">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-531">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb6d7-532">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb6d7-532">Your responsibilities</span></span>

<span data-ttu-id="cb6d7-533">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb6d7-534">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb6d7-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb6d7-535">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="cb6d7-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="cb6d7-536">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb6d7-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

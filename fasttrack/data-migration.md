---
title: Migration des données
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: b02c7c863cdc689fab4a6545ac1acc84f6b03fc2
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416611"
---
# <a name="data-migration"></a><span data-ttu-id="94c1f-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="94c1f-104">Data Migration</span></span>

<span data-ttu-id="94c1f-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="94c1f-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="94c1f-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="94c1f-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="94c1f-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="94c1f-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="94c1f-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="94c1f-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="94c1f-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="94c1f-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-111">You create and schedule your migration events.</span></span> <span data-ttu-id="94c1f-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="94c1f-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="94c1f-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="94c1f-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="94c1f-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="94c1f-115">Considerations</span></span>

  - <span data-ttu-id="94c1f-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="94c1f-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="94c1f-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="94c1f-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="94c1f-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="94c1f-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="94c1f-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="94c1f-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="94c1f-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="94c1f-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="94c1f-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="94c1f-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="94c1f-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-124">Migration service availability</span></span>

  - <span data-ttu-id="94c1f-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="94c1f-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="94c1f-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="94c1f-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="94c1f-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="94c1f-127">Migration to Exchange Online</span></span>

<span data-ttu-id="94c1f-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="94c1f-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="94c1f-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="94c1f-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-130">You create and schedule your migration events.</span></span> <span data-ttu-id="94c1f-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="94c1f-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="94c1f-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="94c1f-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="94c1f-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="94c1f-133">Considerations</span></span>

  - <span data-ttu-id="94c1f-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="94c1f-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="94c1f-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="94c1f-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="94c1f-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="94c1f-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="94c1f-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="94c1f-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="94c1f-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="94c1f-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="94c1f-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="94c1f-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="94c1f-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="94c1f-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="94c1f-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="94c1f-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="94c1f-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="94c1f-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="94c1f-143">Source environments</span></span>

<span data-ttu-id="94c1f-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="94c1f-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="94c1f-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="94c1f-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="94c1f-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="94c1f-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="94c1f-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="94c1f-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="94c1f-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="94c1f-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="94c1f-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="94c1f-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="94c1f-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="94c1f-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="94c1f-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="94c1f-154">
<strong>Remarque :</strong> Pour les dépendances Exchange sur site, consultez <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">les conditions préalables au déploiement hybride.</span></a></span><span class="sxs-lookup"><span data-stu-id="94c1f-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="94c1f-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="94c1f-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="94c1f-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="94c1f-156">Emails</span></span></li>
<li><span data-ttu-id="94c1f-157">Règles de boîte aux lettres côté serveur</span><span class="sxs-lookup"><span data-stu-id="94c1f-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="94c1f-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="94c1f-158">Delegates</span></span></li>
<li><span data-ttu-id="94c1f-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="94c1f-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="94c1f-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="94c1f-160">Calendar</span></span> </li>
<li> <span data-ttu-id="94c1f-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="94c1f-161">Tasks</span></span> </li>
<li> <span data-ttu-id="94c1f-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="94c1f-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="94c1f-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="94c1f-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="94c1f-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="94c1f-164">Signatures</span></span> </li>
<li> <span data-ttu-id="94c1f-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="94c1f-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="94c1f-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="94c1f-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="94c1f-167">Public folders</span></span> </li>
<li> <span data-ttu-id="94c1f-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="94c1f-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="94c1f-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="94c1f-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="94c1f-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="94c1f-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="94c1f-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="94c1f-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="94c1f-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="94c1f-174">Règles de boîte aux lettres côté client</span><span class="sxs-lookup"><span data-stu-id="94c1f-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="94c1f-175"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="94c1f-176">
<strong>Remarque :</strong> Votre environnement G Suite doit respecter les conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Effectuer une migration G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="94c1f-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="94c1f-177">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="94c1f-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-178">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="94c1f-178">Emails</span></span> </li>
<li> <span data-ttu-id="94c1f-179">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="94c1f-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="94c1f-180">Calendrier</span><span class="sxs-lookup"><span data-stu-id="94c1f-180">Calendar</span></span> </li>
<li> <span data-ttu-id="94c1f-181">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="94c1f-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-182">Règles</span><span class="sxs-lookup"><span data-stu-id="94c1f-182">Rules</span></span> </li>
<li> <span data-ttu-id="94c1f-183">Délégués</span><span class="sxs-lookup"><span data-stu-id="94c1f-183">Delegates</span></span> </li>
<li> <span data-ttu-id="94c1f-184">Signatures</span><span class="sxs-lookup"><span data-stu-id="94c1f-184">Signatures</span></span> </li>
<li> <span data-ttu-id="94c1f-185">Tâches</span><span class="sxs-lookup"><span data-stu-id="94c1f-185">Tasks</span></span> </li>
<li> <span data-ttu-id="94c1f-186">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="94c1f-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="94c1f-187">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-188">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="94c1f-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="94c1f-189">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="94c1f-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="94c1f-190">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="94c1f-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="94c1f-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="94c1f-192">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="94c1f-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="94c1f-193">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="94c1f-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="94c1f-194">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="94c1f-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="94c1f-195">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="94c1f-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="94c1f-196">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="94c1f-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="94c1f-197">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="94c1f-198"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="94c1f-199">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="94c1f-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="94c1f-200">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="94c1f-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="94c1f-201">Règles</span><span class="sxs-lookup"><span data-stu-id="94c1f-201">Rules</span></span> </li>
<li> <span data-ttu-id="94c1f-202">Délégués</span><span class="sxs-lookup"><span data-stu-id="94c1f-202">Delegates</span></span> </li>
<li> <span data-ttu-id="94c1f-203">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="94c1f-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="94c1f-204">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="94c1f-204">External contacts</span></span> </li>
<li> <span data-ttu-id="94c1f-205">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="94c1f-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="94c1f-206">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-207">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="94c1f-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="94c1f-208">Calendrier</span><span class="sxs-lookup"><span data-stu-id="94c1f-208">Calendar</span></span> </li>
<li> <span data-ttu-id="94c1f-209">Signatures</span><span class="sxs-lookup"><span data-stu-id="94c1f-209">Signatures</span></span> </li>
<li> <span data-ttu-id="94c1f-210">Tâches</span><span class="sxs-lookup"><span data-stu-id="94c1f-210">Tasks</span></span> </li>
<li> <span data-ttu-id="94c1f-211">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="94c1f-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="94c1f-212">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="94c1f-212">Archive data</span></span> </li>
<li> <span data-ttu-id="94c1f-213">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="94c1f-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="94c1f-214">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="94c1f-215">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="94c1f-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="94c1f-216">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c1f-216">FastTrack responsibilities</span></span>

<span data-ttu-id="94c1f-217">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-218">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="94c1f-219">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="94c1f-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="94c1f-220">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="94c1f-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="94c1f-221">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="94c1f-221">Your responsibilities</span></span>

<span data-ttu-id="94c1f-222">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-223">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="94c1f-224">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="94c1f-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="94c1f-225">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="94c1f-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="94c1f-226">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="94c1f-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="94c1f-227">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="94c1f-228">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="94c1f-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="94c1f-229">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="94c1f-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="94c1f-230">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="94c1f-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="94c1f-231">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="94c1f-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="94c1f-232">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="94c1f-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="94c1f-233">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="94c1f-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="94c1f-234">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="94c1f-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="94c1f-235">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="94c1f-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="94c1f-236">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="94c1f-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="94c1f-237">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="94c1f-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="94c1f-238">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="94c1f-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="94c1f-239">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="94c1f-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="94c1f-240">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="94c1f-241">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="94c1f-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="94c1f-242">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-242">You create and schedule your migration events.</span></span> <span data-ttu-id="94c1f-243">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="94c1f-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="94c1f-244">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="94c1f-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="94c1f-245">Considérations</span><span class="sxs-lookup"><span data-stu-id="94c1f-245">Considerations</span></span>

  - <span data-ttu-id="94c1f-246">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="94c1f-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="94c1f-247">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="94c1f-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="94c1f-248">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="94c1f-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="94c1f-249">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="94c1f-249">Source environment details</span></span>

<span data-ttu-id="94c1f-250">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="94c1f-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="94c1f-251">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="94c1f-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="94c1f-252">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="94c1f-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="94c1f-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="94c1f-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="94c1f-254">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="94c1f-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="94c1f-255">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="94c1f-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="94c1f-256"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="94c1f-257"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="94c1f-258"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="94c1f-259"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="94c1f-260"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="94c1f-261">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-262">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-262">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-263">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-264">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="94c1f-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="94c1f-265">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="94c1f-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="94c1f-266">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-267">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-268">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-268">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-269">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-269">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-270">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-270">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-271">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="94c1f-272">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="94c1f-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="94c1f-273">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="94c1f-274">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="94c1f-275">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-276">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="94c1f-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="94c1f-277">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-278">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="94c1f-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="94c1f-279">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="94c1f-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="94c1f-280">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="94c1f-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="94c1f-281">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="94c1f-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="94c1f-282">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="94c1f-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="94c1f-283">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="94c1f-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="94c1f-284">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-285">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="94c1f-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="94c1f-286">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="94c1f-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="94c1f-287">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="94c1f-288"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="94c1f-289">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-290">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="94c1f-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="94c1f-291">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-292">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-293">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-294">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-295">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-296">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-296">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-297">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-297">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-298">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-298">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-299">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-300">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="94c1f-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="94c1f-301">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-302">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-303">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="94c1f-304">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-305">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-306">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="94c1f-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-307">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-308">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-309">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-310">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-311">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-312">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="94c1f-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="94c1f-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="94c1f-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="94c1f-314">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="94c1f-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="94c1f-315">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="94c1f-316">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-317">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-318">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="94c1f-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="94c1f-319">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-320">Fichiers marqués comme étant restreints ou non copiables</span><span class="sxs-lookup"><span data-stu-id="94c1f-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="94c1f-321">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="94c1f-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="94c1f-323">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-324">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-324">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-325">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-326">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-327">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-328">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-329">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-330">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-330">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-331">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-331">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-332">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-332">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-333">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-334">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="94c1f-335">Notes Box (converties au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="94c1f-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-336">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-337">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="94c1f-338">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-339">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-340">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="94c1f-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-341">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-342">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-343">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-344">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-345">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-346">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="94c1f-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="94c1f-347">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="94c1f-348">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-349">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-350">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="94c1f-351"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="94c1f-352">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-353">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-353">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-354">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-355">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-356">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-357">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-358">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-359">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-359">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-360">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-360">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-361">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-361">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-362">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-363">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="94c1f-364">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-365">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-366">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="94c1f-367">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-368">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-369">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="94c1f-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-370">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-371">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-372">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-373">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-374">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="94c1f-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="94c1f-375">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="94c1f-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="94c1f-376">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="94c1f-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="94c1f-377">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="94c1f-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="94c1f-378">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="94c1f-379">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-380">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="94c1f-381">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="94c1f-382">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c1f-382">FastTrack responsibilities</span></span>

<span data-ttu-id="94c1f-383">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-384">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="94c1f-385">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="94c1f-385">Your responsibilities</span></span>

<span data-ttu-id="94c1f-386">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-387">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="94c1f-388">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="94c1f-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="94c1f-389">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="94c1f-390">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="94c1f-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="94c1f-391">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="94c1f-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="94c1f-392">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="94c1f-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="94c1f-393">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-393">You create and schedule your migration events.</span></span> <span data-ttu-id="94c1f-394">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="94c1f-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="94c1f-395">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="94c1f-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="94c1f-396">Considérations</span><span class="sxs-lookup"><span data-stu-id="94c1f-396">Considerations</span></span>

  - <span data-ttu-id="94c1f-397">Toutes les migrations sont soumises aux quotas OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="94c1f-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="94c1f-398">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="94c1f-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="94c1f-399">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="94c1f-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="94c1f-400">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="94c1f-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="94c1f-401">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="94c1f-401">Source environment details</span></span>

<span data-ttu-id="94c1f-402">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="94c1f-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="94c1f-403">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="94c1f-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="94c1f-404">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="94c1f-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="94c1f-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="94c1f-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="94c1f-406">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="94c1f-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="94c1f-407">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="94c1f-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="94c1f-408"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="94c1f-409"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="94c1f-410"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="94c1f-411"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="94c1f-412"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="94c1f-413">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-414">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-414">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-415">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-416">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="94c1f-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="94c1f-417">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="94c1f-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="94c1f-418">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-419">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-420">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-420">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-421">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-421">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-422">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-422">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-423">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="94c1f-424">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="94c1f-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="94c1f-425">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="94c1f-426">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="94c1f-427">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="94c1f-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="94c1f-428">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="94c1f-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="94c1f-429">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-430">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="94c1f-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="94c1f-431">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="94c1f-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="94c1f-432">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="94c1f-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="94c1f-433">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="94c1f-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="94c1f-434">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="94c1f-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="94c1f-435">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="94c1f-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="94c1f-436">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-437">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="94c1f-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="94c1f-438">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="94c1f-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="94c1f-439">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="94c1f-440"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="94c1f-441">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-442">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="94c1f-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="94c1f-443">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-444">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-445">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-446">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-447">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-448">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-448">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-449">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-449">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-450">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-450">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-451">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-452">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="94c1f-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="94c1f-453">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-454">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-455">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="94c1f-456">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-457">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-458">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="94c1f-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-459">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-460">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-461">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-462">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-463">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-464">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="94c1f-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="94c1f-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="94c1f-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="94c1f-466">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="94c1f-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="94c1f-467">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="94c1f-468">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-469">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-470">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="94c1f-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="94c1f-471">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-472">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="94c1f-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="94c1f-474">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-475">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-475">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-476">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-477">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-478">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-479">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-480">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-481">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-481">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-482">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-482">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-483">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-483">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-484">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-485">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-486">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-487">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="94c1f-488">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-489">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-490">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="94c1f-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-491">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-492">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-493">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-494">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-495">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="94c1f-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="94c1f-496">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="94c1f-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="94c1f-497">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="94c1f-498">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-499">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-500">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="94c1f-501"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="94c1f-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="94c1f-502">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="94c1f-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="94c1f-503">Documents</span><span class="sxs-lookup"><span data-stu-id="94c1f-503">Documents</span></span> </li>
<li> <span data-ttu-id="94c1f-504">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="94c1f-505">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-506">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-507">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="94c1f-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="94c1f-508">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="94c1f-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="94c1f-509">Date de création</span><span class="sxs-lookup"><span data-stu-id="94c1f-509">Created date</span></span> </li>
<li> <span data-ttu-id="94c1f-510">Date de modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-510">Modified date</span></span> </li>
<li> <span data-ttu-id="94c1f-511">Créé par</span><span class="sxs-lookup"><span data-stu-id="94c1f-511">Created by</span></span> </li>
<li> <span data-ttu-id="94c1f-512">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="94c1f-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="94c1f-513">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="94c1f-514">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="94c1f-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="94c1f-515">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="94c1f-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="94c1f-516">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="94c1f-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="94c1f-517">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="94c1f-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-518">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="94c1f-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="94c1f-519">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="94c1f-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="94c1f-520">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="94c1f-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="94c1f-521">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="94c1f-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="94c1f-522">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="94c1f-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="94c1f-523">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="94c1f-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="94c1f-524">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="94c1f-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="94c1f-525">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="94c1f-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="94c1f-526">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="94c1f-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="94c1f-527">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="94c1f-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="94c1f-528">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="94c1f-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="94c1f-529">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="94c1f-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="94c1f-530">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="94c1f-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="94c1f-531">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="94c1f-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="94c1f-532">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c1f-532">FastTrack responsibilities</span></span>

<span data-ttu-id="94c1f-533">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-534">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="94c1f-535">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="94c1f-535">Your responsibilities</span></span>

<span data-ttu-id="94c1f-536">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="94c1f-537">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="94c1f-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="94c1f-538">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="94c1f-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="94c1f-539">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="94c1f-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

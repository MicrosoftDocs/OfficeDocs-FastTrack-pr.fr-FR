---
title: Migration des données
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: f518e8dbda9200318022bad2cc12d1ba68263df8
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188019"
---
# <a name="data-migration"></a><span data-ttu-id="cb464-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="cb464-104">Data Migration</span></span>

<span data-ttu-id="cb464-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="cb464-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="cb464-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="cb464-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="cb464-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="cb464-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="cb464-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="cb464-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="cb464-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="cb464-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="cb464-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-111">You create and schedule your migration events.</span></span> <span data-ttu-id="cb464-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb464-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="cb464-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="cb464-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="cb464-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb464-115">Considerations</span></span>

  - <span data-ttu-id="cb464-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb464-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="cb464-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="cb464-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="cb464-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="cb464-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="cb464-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="cb464-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="cb464-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb464-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="cb464-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="cb464-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="cb464-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="cb464-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-124">Migration service availability</span></span>

  - <span data-ttu-id="cb464-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="cb464-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="cb464-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="cb464-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="cb464-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="cb464-127">Migration to Exchange Online</span></span>

<span data-ttu-id="cb464-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb464-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="cb464-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="cb464-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-130">You create and schedule your migration events.</span></span> <span data-ttu-id="cb464-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb464-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb464-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="cb464-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb464-133">Considerations</span></span>

  - <span data-ttu-id="cb464-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="cb464-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="cb464-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="cb464-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="cb464-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="cb464-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="cb464-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="cb464-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="cb464-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="cb464-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="cb464-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="cb464-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="cb464-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="cb464-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="cb464-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="cb464-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="cb464-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="cb464-143">Source environments</span></span>

<span data-ttu-id="cb464-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb464-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="cb464-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="cb464-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="cb464-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="cb464-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="cb464-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb464-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="cb464-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb464-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="cb464-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="cb464-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="cb464-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="cb464-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb464-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="cb464-154">
<strong>Remarque :</strong> Pour les dépendances Exchange sur site, consultez <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">les conditions préalables au déploiement hybride.</span></a></span><span class="sxs-lookup"><span data-stu-id="cb464-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="cb464-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="cb464-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="cb464-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb464-156">Emails</span></span></li>
<li><span data-ttu-id="cb464-157">Règles de boîte aux lettres côté serveur</span><span class="sxs-lookup"><span data-stu-id="cb464-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="cb464-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb464-158">Delegates</span></span></li>
<li><span data-ttu-id="cb464-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="cb464-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="cb464-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb464-160">Calendar</span></span> </li>
<li> <span data-ttu-id="cb464-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb464-161">Tasks</span></span> </li>
<li> <span data-ttu-id="cb464-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="cb464-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="cb464-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="cb464-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="cb464-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb464-164">Signatures</span></span> </li>
<li> <span data-ttu-id="cb464-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="cb464-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="cb464-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="cb464-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="cb464-167">Public folders</span></span> </li>
<li> <span data-ttu-id="cb464-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb464-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb464-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="cb464-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="cb464-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="cb464-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="cb464-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb464-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb464-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="cb464-174">Règles de boîte aux lettres côté client</span><span class="sxs-lookup"><span data-stu-id="cb464-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-175"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="cb464-176">
<strong>Remarque :</strong> Votre environnement G Suite doit respecter les conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Effectuer une migration G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="cb464-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="cb464-177">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="cb464-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-178">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb464-178">Emails</span></span> </li>
<li> <span data-ttu-id="cb464-179">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="cb464-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="cb464-180">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb464-180">Calendar</span></span> </li>
<li> <span data-ttu-id="cb464-181">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="cb464-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-182">Règles</span><span class="sxs-lookup"><span data-stu-id="cb464-182">Rules</span></span> </li>
<li> <span data-ttu-id="cb464-183">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb464-183">Delegates</span></span> </li>
<li> <span data-ttu-id="cb464-184">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb464-184">Signatures</span></span> </li>
<li> <span data-ttu-id="cb464-185">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb464-185">Tasks</span></span> </li>
<li> <span data-ttu-id="cb464-186">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb464-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb464-187">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-188">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="cb464-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="cb464-189">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="cb464-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="cb464-190">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb464-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="cb464-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="cb464-192">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="cb464-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="cb464-193">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="cb464-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="cb464-194">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb464-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="cb464-195">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="cb464-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="cb464-196">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="cb464-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="cb464-197">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb464-198"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="cb464-199">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="cb464-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="cb464-200">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="cb464-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="cb464-201">Règles</span><span class="sxs-lookup"><span data-stu-id="cb464-201">Rules</span></span> </li>
<li> <span data-ttu-id="cb464-202">Délégués</span><span class="sxs-lookup"><span data-stu-id="cb464-202">Delegates</span></span> </li>
<li> <span data-ttu-id="cb464-203">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="cb464-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="cb464-204">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="cb464-204">External contacts</span></span> </li>
<li> <span data-ttu-id="cb464-205">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="cb464-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="cb464-206">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-207">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="cb464-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="cb464-208">Calendrier</span><span class="sxs-lookup"><span data-stu-id="cb464-208">Calendar</span></span> </li>
<li> <span data-ttu-id="cb464-209">Signatures</span><span class="sxs-lookup"><span data-stu-id="cb464-209">Signatures</span></span> </li>
<li> <span data-ttu-id="cb464-210">Tâches</span><span class="sxs-lookup"><span data-stu-id="cb464-210">Tasks</span></span> </li>
<li> <span data-ttu-id="cb464-211">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="cb464-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="cb464-212">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="cb464-212">Archive data</span></span> </li>
<li> <span data-ttu-id="cb464-213">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="cb464-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="cb464-214">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="cb464-215">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="cb464-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb464-216">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb464-216">FastTrack responsibilities</span></span>

<span data-ttu-id="cb464-217">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-218">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb464-219">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="cb464-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="cb464-220">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb464-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb464-221">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb464-221">Your responsibilities</span></span>

<span data-ttu-id="cb464-222">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-223">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb464-224">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="cb464-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="cb464-225">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="cb464-226">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="cb464-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="cb464-227">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="cb464-228">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="cb464-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="cb464-229">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="cb464-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="cb464-230">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="cb464-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="cb464-231">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="cb464-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="cb464-232">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb464-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="cb464-233">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb464-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="cb464-234">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="cb464-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="cb464-235">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="cb464-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="cb464-236">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="cb464-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="cb464-237">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="cb464-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="cb464-238">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="cb464-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="cb464-239">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="cb464-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="cb464-240">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb464-241">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb464-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="cb464-242">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-242">You create and schedule your migration events.</span></span> <span data-ttu-id="cb464-243">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb464-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb464-244">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="cb464-245">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb464-245">Considerations</span></span>

 - <span data-ttu-id="cb464-246">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="cb464-247">Pour plus <a href="https://go.microsoft.com/fwlink/?LinkId=698855">d’informations,</a> reportez-vous aux limites de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb464-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="cb464-248">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="cb464-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="cb464-249">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="cb464-249">Source environment details</span></span>

<span data-ttu-id="cb464-250">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb464-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="cb464-251">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="cb464-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="cb464-252">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb464-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="cb464-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="cb464-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="cb464-254">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="cb464-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="cb464-255">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb464-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="cb464-256"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="cb464-257"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="cb464-258"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="cb464-259"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb464-260"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="cb464-261">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-262">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-262">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-263">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-264">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-265">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-266">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-267">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-268">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-268">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-269">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-269">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-270">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-270">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-271">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="cb464-272">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="cb464-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="cb464-273">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="cb464-274">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="cb464-275">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-276">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-277">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-278">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-279">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="cb464-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="cb464-280">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="cb464-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="cb464-281">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="cb464-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="cb464-282">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="cb464-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="cb464-283">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="cb464-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="cb464-284">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-285">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="cb464-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="cb464-286">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="cb464-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="cb464-287">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-288"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="cb464-289">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-290">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="cb464-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="cb464-291">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-292">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-293">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-294">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-295">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-296">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-296">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-297">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-297">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-298">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-298">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-299">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-300">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="cb464-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="cb464-301">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-302">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-303">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="cb464-304">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-305">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-306">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-307">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-308">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-309">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-310">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-311">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-312">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="cb464-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="cb464-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="cb464-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="cb464-314">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="cb464-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="cb464-315">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="cb464-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="cb464-316">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-317">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-318">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="cb464-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="cb464-319">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-320">Fichiers marqués comme étant restreints ou non copiables</span><span class="sxs-lookup"><span data-stu-id="cb464-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="cb464-321">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb464-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="cb464-323">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-324">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-324">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-325">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-326">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-327">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-328">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-329">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-330">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-330">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-331">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-331">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-332">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-332">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-333">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-334">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="cb464-335">Notes Box (converties au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="cb464-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-336">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-337">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-338">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-339">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-340">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="cb464-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-341">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-342">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-343">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-344">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-345">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-346">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="cb464-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="cb464-347">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="cb464-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="cb464-348">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-349">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-350">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-351"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="cb464-352">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-353">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-353">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-354">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-355">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-356">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-357">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-358">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-359">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-359">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-360">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-360">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-361">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-361">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-362">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-363">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="cb464-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="cb464-364">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-365">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-366">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-367">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-368">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-369">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-370">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-371">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-372">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-373">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-374">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="cb464-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="cb464-375">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="cb464-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="cb464-376">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="cb464-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="cb464-377">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="cb464-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="cb464-378">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="cb464-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="cb464-379">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-380">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="cb464-381">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb464-382">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb464-382">FastTrack responsibilities</span></span>

<span data-ttu-id="cb464-383">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-384">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb464-385">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb464-385">Your responsibilities</span></span>

<span data-ttu-id="cb464-386">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-387">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="cb464-388">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="cb464-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="cb464-389">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="cb464-390">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="cb464-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="cb464-391">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb464-392">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb464-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="cb464-393">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-393">You create and schedule your migration events.</span></span> <span data-ttu-id="cb464-394">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb464-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb464-395">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="cb464-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="cb464-396">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb464-396">Considerations</span></span>

  - <span data-ttu-id="cb464-397">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="cb464-398">Pour plus <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> d’informations,</a> reportez-vous aux limites de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb464-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="cb464-399">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="cb464-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="cb464-400">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="cb464-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="cb464-401">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="cb464-401">Source environment details</span></span>

<span data-ttu-id="cb464-402">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb464-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="cb464-403">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="cb464-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="cb464-404">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb464-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="cb464-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="cb464-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="cb464-406">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="cb464-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="cb464-407">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb464-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="cb464-408"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="cb464-409"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="cb464-410"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="cb464-411"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb464-412"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="cb464-413">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-414">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-414">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-415">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-416">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-417">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-418">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-419">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-420">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-420">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-421">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-421">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-422">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-422">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-423">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="cb464-424">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="cb464-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="cb464-425">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="cb464-426">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="cb464-427">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="cb464-428">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-429">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-430">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-431">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="cb464-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="cb464-432">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="cb464-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="cb464-433">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="cb464-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="cb464-434">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="cb464-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="cb464-435">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="cb464-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="cb464-436">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-437">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="cb464-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="cb464-438">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="cb464-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="cb464-439">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-440"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="cb464-441">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-442">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="cb464-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="cb464-443">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-444">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-445">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-446">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-447">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-448">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-448">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-449">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-449">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-450">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-450">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-451">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-452">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="cb464-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="cb464-453">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-454">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-455">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="cb464-456">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-457">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-458">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-459">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-460">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-461">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-462">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-463">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-464">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="cb464-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="cb464-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="cb464-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="cb464-466">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="cb464-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="cb464-467">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="cb464-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="cb464-468">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-469">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-470">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="cb464-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="cb464-471">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-472">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb464-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="cb464-474">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-475">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-475">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-476">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-477">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-478">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-479">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-480">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-481">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-481">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-482">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-482">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-483">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-483">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-484">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-485">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-486">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-487">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-488">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-489">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-490">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="cb464-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-491">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-492">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-493">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-494">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-495">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-496">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="cb464-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="cb464-497">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="cb464-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="cb464-498">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-499">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-500">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-501"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="cb464-502">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-503">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-503">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-504">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-505">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-506">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="cb464-507">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-508">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-509">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-509">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-510">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-510">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-511">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-511">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-512">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-513">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="cb464-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="cb464-514">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="cb464-515">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-516">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-517">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-518">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-519">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-520">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-521">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-522">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-523">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-524">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="cb464-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="cb464-525">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="cb464-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="cb464-526">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="cb464-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="cb464-527">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="cb464-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="cb464-528">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="cb464-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="cb464-529">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-530">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-531">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb464-532">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb464-532">FastTrack responsibilities</span></span>

<span data-ttu-id="cb464-533">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-534">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb464-535">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb464-535">Your responsibilities</span></span>

<span data-ttu-id="cb464-536">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-537">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="cb464-538">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="cb464-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="cb464-539">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="cb464-540">Migration vers Microsoft Teams et les groupes Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="cb464-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="cb464-541">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers Microsoft Teams et les groupes Microsoft 365, nous fournissons des conseils de migration et des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="cb464-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="cb464-542">Nous vous fournissons des conseils pour vous aider à planifier votre migration, à configurer vos environnements sources, Teams et groupes Microsoft 365, et à tirer parti de nos services de migration de données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="cb464-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="cb464-543">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-543">You create and schedule your migration events.</span></span> <span data-ttu-id="cb464-544">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="cb464-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="cb464-545">Une fois vos événements de migration terminés, vous pouvez vous attendre à ce que les fichiers provenant de sources éligibles et correctement programmées de vos environnements sources soient migrés vers Teams et groupes Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="cb464-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="cb464-546">Les canaux Teams et les groupes Microsoft 365 doivent être pré-mis en service par le client avant de pouvoir migrer les données vers ces types de destination.</span><span class="sxs-lookup"><span data-stu-id="cb464-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="cb464-547">Teams et les groupes Microsoft 365 ont une incidence sur vos autorisations sur l’emplacement de destination du fichier.</span><span class="sxs-lookup"><span data-stu-id="cb464-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="cb464-548">Teams et les groupes Microsoft 365 sont conçus pour permettre la collaboration.</span><span class="sxs-lookup"><span data-stu-id="cb464-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="cb464-549">Le canal Teams ou le groupe Microsoft 365 déterminent qui a accès à ces fichiers lors de la migration vers ces destinations.</span><span class="sxs-lookup"><span data-stu-id="cb464-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="cb464-550">FastTrack n’ajoute pas d’utilisateurs finaux ou de groupes à une autorisation de canal Teams ou de groupes Microsoft 365 pendant la migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="cb464-551">Considérations</span><span class="sxs-lookup"><span data-stu-id="cb464-551">Considerations</span></span>

- <span data-ttu-id="cb464-552">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cb464-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="cb464-553">Pour plus <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> d’informations,</a> reportez-vous aux limites de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb464-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="cb464-554">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="cb464-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="cb464-555">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="cb464-555">Source environment details</span></span>

<span data-ttu-id="cb464-556">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="cb464-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="cb464-557">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="cb464-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="cb464-558">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb464-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="cb464-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="cb464-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="cb464-560">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="cb464-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="cb464-561">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="cb464-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="cb464-562"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="cb464-563"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="cb464-564"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="cb464-565"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="cb464-566"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="cb464-567">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-568">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-568">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-569">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-570">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-571">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-572">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-573">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-574">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-574">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-575">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-575">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-576">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-576">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-577">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="cb464-578">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="cb464-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="cb464-579">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="cb464-580">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="cb464-581">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="cb464-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="cb464-582">Les autorisations sont impactées par le groupe Microsoft 365 et/ou le canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="cb464-583">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil des autorisations finales sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="cb464-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="cb464-584">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-585">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-586">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-587">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="cb464-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="cb464-588">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="cb464-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="cb464-589">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="cb464-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="cb464-590">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="cb464-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="cb464-591">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="cb464-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="cb464-592">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="cb464-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="cb464-593">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-594">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="cb464-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="cb464-595">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="cb464-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="cb464-596">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-597"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="cb464-598">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-599">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="cb464-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="cb464-600">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-601">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-602">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-603">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-604">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-605">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-605">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-606">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-606">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-607">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-607">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-608">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-609">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="cb464-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="cb464-610">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="cb464-611">\*Les autorisations sont impactées par le groupe Microsoft 365 et/ou le canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="cb464-612">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil des autorisations finales sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="cb464-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="cb464-613">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="cb464-614">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-615">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="cb464-616">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-617">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-618">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-619">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-620">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-621">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-622">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-623">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-624">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="cb464-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="cb464-625">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="cb464-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="cb464-626">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="cb464-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="cb464-627">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="cb464-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="cb464-628">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-629">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-630">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="cb464-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="cb464-631">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-632">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="cb464-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="cb464-634">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-635">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-635">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-636">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-637">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-638">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-639">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-640">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-641">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-641">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-642">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-642">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-643">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-643">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-644">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-645">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="cb464-646">Notes Box (converties au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="cb464-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="cb464-647">\*Les autorisations sont impactées par le groupe Microsoft 365 et/ou le canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="cb464-648">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil des autorisations finales sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="cb464-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="cb464-649">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="cb464-650">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-651">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-652">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-653">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-654">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="cb464-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-655">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-656">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-657">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-658">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-659">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="cb464-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="cb464-660">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="cb464-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="cb464-661">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="cb464-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="cb464-662">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-663">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-664">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="cb464-665"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="cb464-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="cb464-666">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="cb464-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="cb464-667">Documents</span><span class="sxs-lookup"><span data-stu-id="cb464-667">Documents</span></span> </li>
<li> <span data-ttu-id="cb464-668">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="cb464-669">Autorisations de dossier au niveau de l’utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="cb464-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-670">Autorisations de dossier au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="cb464-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="cb464-671">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="cb464-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="cb464-672">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="cb464-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="cb464-673">Date de création</span><span class="sxs-lookup"><span data-stu-id="cb464-673">Created date</span></span> </li>
<li> <span data-ttu-id="cb464-674">Date de modification</span><span class="sxs-lookup"><span data-stu-id="cb464-674">Modified date</span></span> </li>
<li> <span data-ttu-id="cb464-675">Créé par</span><span class="sxs-lookup"><span data-stu-id="cb464-675">Created by</span></span> </li>
<li> <span data-ttu-id="cb464-676">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="cb464-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="cb464-677">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="cb464-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="cb464-678">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="cb464-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="cb464-679">\*Les autorisations sont impactées par le groupe Microsoft 365 et/ou le canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="cb464-680">Si la destination est un groupe Microsoft 365 ou un canal Microsoft Teams, le groupe ou le canal détermine le profil des autorisations finales sur les fichiers migrés.</span><span class="sxs-lookup"><span data-stu-id="cb464-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="cb464-681">Nous vous recommandons de ne pas migrer les autorisations sur les fichiers migrés vers un groupe Microsoft 365 ou un canal Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cb464-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="cb464-682">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="cb464-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="cb464-683">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="cb464-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="cb464-684">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="cb464-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-685">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="cb464-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="cb464-686">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="cb464-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="cb464-687">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="cb464-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="cb464-688">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="cb464-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="cb464-689">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="cb464-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="cb464-690">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="cb464-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="cb464-691">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="cb464-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="cb464-692">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="cb464-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="cb464-693">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="cb464-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="cb464-694">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="cb464-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="cb464-695">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="cb464-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="cb464-696">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="cb464-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="cb464-697">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="cb464-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="cb464-698">Fichiers ou dossiers dépassant les restrictions et <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limitations sharePoint Online actuelles</span></a> </span><span class="sxs-lookup"><span data-stu-id="cb464-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="cb464-699">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="cb464-699">FastTrack responsibilities</span></span>

<span data-ttu-id="cb464-700">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-701">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="cb464-702">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="cb464-702">Your responsibilities</span></span> 

<span data-ttu-id="cb464-703">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="cb464-704">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="cb464-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="cb464-705">Vous effectuez également les activités suivantes, spécifiques aux migrations Microsoft Teams et Groupes Microsoft 365 :</span><span class="sxs-lookup"><span data-stu-id="cb464-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="cb464-706">Provisionnez tous les canaux Microsoft Teams et les groupes Microsoft 365 comme ciblé par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="cb464-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="cb464-707">FastTrack ne pré-provisionnise pas les canaux Microsoft Teams ou les groupes Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="cb464-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="cb464-708">FastTrack n’ajoute pas d’utilisateurs finaux ou de groupes aux canaux Microsoft Teams ou aux groupes Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="cb464-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="cb464-709">Vous devez ajouter vos utilisateurs finaux ou groupes à tous les canaux Microsoft Teams et groupes Microsoft 365 avant de migrer les données vers ces destinations afin que ces utilisateurs finaux ont accès à ces documents récemment migrés.</span><span class="sxs-lookup"><span data-stu-id="cb464-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>
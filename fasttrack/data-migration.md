---
title: Migration des données
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750041"
---
# <a name="data-migration"></a><span data-ttu-id="d5c13-104">Migration des données</span><span class="sxs-lookup"><span data-stu-id="d5c13-104">Data Migration</span></span>

<span data-ttu-id="d5c13-105">FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).</span><span class="sxs-lookup"><span data-stu-id="d5c13-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="d5c13-106">Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :</span><span class="sxs-lookup"><span data-stu-id="d5c13-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="d5c13-107">**Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="d5c13-108">Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.</span><span class="sxs-lookup"><span data-stu-id="d5c13-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="d5c13-109">**Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="d5c13-110">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="d5c13-111">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-111">You create and schedule your migration events.</span></span> <span data-ttu-id="d5c13-112">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="d5c13-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="d5c13-113">Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="d5c13-114">En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="d5c13-115">Considérations</span><span class="sxs-lookup"><span data-stu-id="d5c13-115">Considerations</span></span>

  - <span data-ttu-id="d5c13-116">Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="d5c13-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="d5c13-117">Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="d5c13-118">Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="d5c13-119">Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="d5c13-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="d5c13-120">Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).</span><span class="sxs-lookup"><span data-stu-id="d5c13-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="d5c13-121">Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.</span><span class="sxs-lookup"><span data-stu-id="d5c13-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="d5c13-122">Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="d5c13-123">Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="d5c13-124">Disponibilité des services de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-124">Migration service availability</span></span>

  - <span data-ttu-id="d5c13-125">**Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.</span><span class="sxs-lookup"><span data-stu-id="d5c13-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="d5c13-126">**Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.</span><span class="sxs-lookup"><span data-stu-id="d5c13-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="d5c13-127">Migration vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d5c13-127">Migration to Exchange Online</span></span>

<span data-ttu-id="d5c13-128">Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d5c13-129">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception.</span><span class="sxs-lookup"><span data-stu-id="d5c13-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="d5c13-130">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-130">You create and schedule your migration events.</span></span> <span data-ttu-id="d5c13-131">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="d5c13-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d5c13-132">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d5c13-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="d5c13-133">Considérations</span><span class="sxs-lookup"><span data-stu-id="d5c13-133">Considerations</span></span>

  - <span data-ttu-id="d5c13-134">Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d5c13-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="d5c13-135">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="d5c13-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="d5c13-136">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="d5c13-137">FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.</span><span class="sxs-lookup"><span data-stu-id="d5c13-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="d5c13-138">Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="d5c13-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="d5c13-139">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="d5c13-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="d5c13-140">Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.</span><span class="sxs-lookup"><span data-stu-id="d5c13-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="d5c13-141">Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="d5c13-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="d5c13-142">Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="d5c13-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="d5c13-143">Environnements sources</span><span class="sxs-lookup"><span data-stu-id="d5c13-143">Source environments</span></span>

<span data-ttu-id="d5c13-144">Notre service de migration des données migre les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="d5c13-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="d5c13-145">Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="d5c13-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="d5c13-146">Environnement de messagerie IMAP unique.</span><span class="sxs-lookup"><span data-stu-id="d5c13-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="d5c13-147">Environnement G Suite (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="d5c13-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="d5c13-148">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="d5c13-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d5c13-149"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="d5c13-150"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="d5c13-151"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="d5c13-152"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d5c13-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="d5c13-154">
<strong>Remarque :</strong> Pour les dépendances Exchange locales, consultez la rubrique <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Configuration requise pour un déploiement hybride</span></a>.</span><span class="sxs-lookup"><span data-stu-id="d5c13-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="d5c13-155">Migration avec déploiement hybride</span><span class="sxs-lookup"><span data-stu-id="d5c13-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="d5c13-156">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="d5c13-156">Emails</span></span></li>
<li><span data-ttu-id="d5c13-157">Règles de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="d5c13-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="d5c13-158">Délégués</span><span class="sxs-lookup"><span data-stu-id="d5c13-158">Delegates</span></span></li>
<li><span data-ttu-id="d5c13-159">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="d5c13-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="d5c13-160">Calendrier</span><span class="sxs-lookup"><span data-stu-id="d5c13-160">Calendar</span></span> </li>
<li> <span data-ttu-id="d5c13-161">Tâches</span><span class="sxs-lookup"><span data-stu-id="d5c13-161">Tasks</span></span> </li>
<li> <span data-ttu-id="d5c13-162">E-mails gérés par des droits</span><span class="sxs-lookup"><span data-stu-id="d5c13-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="d5c13-163">E-mails chiffrés</span><span class="sxs-lookup"><span data-stu-id="d5c13-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="d5c13-164">Signatures</span><span class="sxs-lookup"><span data-stu-id="d5c13-164">Signatures</span></span> </li>
<li> <span data-ttu-id="d5c13-165">Archives personnelles migrées avec la boîte aux lettres des utilisateurs</span><span class="sxs-lookup"><span data-stu-id="d5c13-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="d5c13-166">Éléments récupérables</span><span class="sxs-lookup"><span data-stu-id="d5c13-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-167">Dossiers publics</span><span class="sxs-lookup"><span data-stu-id="d5c13-167">Public folders</span></span> </li>
<li> <span data-ttu-id="d5c13-168">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="d5c13-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d5c13-169">Archivage de journalisation ou toute solution d’archivage tierce</span><span class="sxs-lookup"><span data-stu-id="d5c13-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="d5c13-170">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-171">Données d’archive à partir de fichiers PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="d5c13-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="d5c13-172">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d5c13-173">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="d5c13-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d5c13-174"><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="d5c13-175">
<strong>Remarque :</strong> Votre environnement G suite doit répondre aux conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">perform a G suite migration</a>.</span><span class="sxs-lookup"><span data-stu-id="d5c13-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="d5c13-176">À basculement ou intermédiaire</span><span class="sxs-lookup"><span data-stu-id="d5c13-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-177">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="d5c13-177">Emails</span></span> </li>
<li> <span data-ttu-id="d5c13-178">Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées)</span><span class="sxs-lookup"><span data-stu-id="d5c13-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="d5c13-179">Calendrier</span><span class="sxs-lookup"><span data-stu-id="d5c13-179">Calendar</span></span> </li>
<li> <span data-ttu-id="d5c13-180">Étiquettes</span><span class="sxs-lookup"><span data-stu-id="d5c13-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-181">Règles</span><span class="sxs-lookup"><span data-stu-id="d5c13-181">Rules</span></span> </li>
<li> <span data-ttu-id="d5c13-182">Délégués</span><span class="sxs-lookup"><span data-stu-id="d5c13-182">Delegates</span></span> </li>
<li> <span data-ttu-id="d5c13-183">Signatures</span><span class="sxs-lookup"><span data-stu-id="d5c13-183">Signatures</span></span> </li>
<li> <span data-ttu-id="d5c13-184">Tâches</span><span class="sxs-lookup"><span data-stu-id="d5c13-184">Tasks</span></span> </li>
<li> <span data-ttu-id="d5c13-185">Tout e-mail ou pièce jointe dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="d5c13-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d5c13-186">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-187">Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="d5c13-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="d5c13-188">Droits gérés ou messages électroniques chiffrés</span><span class="sxs-lookup"><span data-stu-id="d5c13-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="d5c13-189">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d5c13-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="d5c13-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="d5c13-191">Groupes Google</span><span class="sxs-lookup"><span data-stu-id="d5c13-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="d5c13-192">Boîtes aux lettres de ressources</span><span class="sxs-lookup"><span data-stu-id="d5c13-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="d5c13-193">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="d5c13-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="d5c13-194">Paramètres des congés et de la réponse automatique</span><span class="sxs-lookup"><span data-stu-id="d5c13-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="d5c13-195">Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement</span><span class="sxs-lookup"><span data-stu-id="d5c13-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="d5c13-196">\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d5c13-197"><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="d5c13-198">Migration à l’aide des outils natifs IMAP4</span><span class="sxs-lookup"><span data-stu-id="d5c13-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="d5c13-199">Messages électroniques</span><span class="sxs-lookup"><span data-stu-id="d5c13-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="d5c13-200">Règles</span><span class="sxs-lookup"><span data-stu-id="d5c13-200">Rules</span></span> </li>
<li> <span data-ttu-id="d5c13-201">Délégués</span><span class="sxs-lookup"><span data-stu-id="d5c13-201">Delegates</span></span> </li>
<li> <span data-ttu-id="d5c13-202">Listes de distribution</span><span class="sxs-lookup"><span data-stu-id="d5c13-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="d5c13-203">Contacts externes</span><span class="sxs-lookup"><span data-stu-id="d5c13-203">External contacts</span></span> </li>
<li> <span data-ttu-id="d5c13-204">Utilisateurs à extension messagerie</span><span class="sxs-lookup"><span data-stu-id="d5c13-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="d5c13-205">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-206">Contacts de boîte aux lettres</span><span class="sxs-lookup"><span data-stu-id="d5c13-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="d5c13-207">Calendrier</span><span class="sxs-lookup"><span data-stu-id="d5c13-207">Calendar</span></span> </li>
<li> <span data-ttu-id="d5c13-208">Signatures</span><span class="sxs-lookup"><span data-stu-id="d5c13-208">Signatures</span></span> </li>
<li> <span data-ttu-id="d5c13-209">Tâches</span><span class="sxs-lookup"><span data-stu-id="d5c13-209">Tasks</span></span> </li>
<li> <span data-ttu-id="d5c13-210">Tout message électronique dépassant la limite de taille de message</span><span class="sxs-lookup"><span data-stu-id="d5c13-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d5c13-211">Données d’archive</span><span class="sxs-lookup"><span data-stu-id="d5c13-211">Archive data</span></span> </li>
<li> <span data-ttu-id="d5c13-212">Message électronique chiffré</span><span class="sxs-lookup"><span data-stu-id="d5c13-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="d5c13-213">Éléments endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d5c13-214">Boîtes aux lettres inactives</span><span class="sxs-lookup"><span data-stu-id="d5c13-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d5c13-215">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5c13-215">FastTrack responsibilities</span></span>

<span data-ttu-id="d5c13-216">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-217">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d5c13-218">Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="d5c13-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="d5c13-219">Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="d5c13-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d5c13-220">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="d5c13-220">Your responsibilities</span></span>

<span data-ttu-id="d5c13-221">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-222">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d5c13-223">Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :</span><span class="sxs-lookup"><span data-stu-id="d5c13-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="d5c13-224">Intégration principale de FastTrack pour Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d5c13-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="d5c13-225">Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables.</span><span class="sxs-lookup"><span data-stu-id="d5c13-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="d5c13-226">Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="d5c13-227">Installation du niveau approprié de logiciel client conformément aux instructions Office 365.</span><span class="sxs-lookup"><span data-stu-id="d5c13-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="d5c13-228">Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="d5c13-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="d5c13-229">Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local.</span><span class="sxs-lookup"><span data-stu-id="d5c13-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="d5c13-230">Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="d5c13-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="d5c13-231">Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="d5c13-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="d5c13-232">Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="d5c13-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="d5c13-233">Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="d5c13-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="d5c13-234">Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.</span><span class="sxs-lookup"><span data-stu-id="d5c13-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="d5c13-235">Migrez les données côté client, le cas échéant.</span><span class="sxs-lookup"><span data-stu-id="d5c13-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="d5c13-236">Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.</span><span class="sxs-lookup"><span data-stu-id="d5c13-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="d5c13-237">Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.</span><span class="sxs-lookup"><span data-stu-id="d5c13-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="d5c13-238">Migrer vers SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="d5c13-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="d5c13-239">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d5c13-240">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="d5c13-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="d5c13-241">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-241">You create and schedule your migration events.</span></span> <span data-ttu-id="d5c13-242">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="d5c13-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d5c13-243">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d5c13-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="d5c13-244">Considérations</span><span class="sxs-lookup"><span data-stu-id="d5c13-244">Considerations</span></span>

  - <span data-ttu-id="d5c13-245">Toutes les migrations sont soumises aux quotas SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d5c13-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="d5c13-246">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="d5c13-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="d5c13-247">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="d5c13-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="d5c13-248">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="d5c13-248">Source environment details</span></span>

<span data-ttu-id="d5c13-249">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="d5c13-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="d5c13-250">Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="d5c13-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="d5c13-251">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="d5c13-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="d5c13-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="d5c13-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="d5c13-253">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="d5c13-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="d5c13-254">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="d5c13-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d5c13-255"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="d5c13-256"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="d5c13-257"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="d5c13-258"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d5c13-259"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="d5c13-260">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-261">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-261">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-262">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-263">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="d5c13-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d5c13-264">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="d5c13-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d5c13-265">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-266">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-267">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-267">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-268">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-268">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-269">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-269">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-270">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="d5c13-271">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="d5c13-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="d5c13-272">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="d5c13-273">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="d5c13-274">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-275">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="d5c13-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="d5c13-276">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-277">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="d5c13-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="d5c13-278">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="d5c13-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="d5c13-279">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="d5c13-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="d5c13-280">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="d5c13-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="d5c13-281">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="d5c13-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="d5c13-282">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="d5c13-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="d5c13-283">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-284">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="d5c13-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="d5c13-285">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="d5c13-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="d5c13-286">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d5c13-287"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="d5c13-288">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-289">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo</span><span class="sxs-lookup"><span data-stu-id="d5c13-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="d5c13-290">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-291">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-292">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-293">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-294">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-295">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-295">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-296">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-296">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-297">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-297">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-298">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-299">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="d5c13-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="d5c13-300">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-301">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-302">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="d5c13-303">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-304">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-305">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="d5c13-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-306">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-307">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-308">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-309">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-310">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-311">Google Photos. Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="d5c13-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="d5c13-312">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="d5c13-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="d5c13-313">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="d5c13-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="d5c13-314">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="d5c13-315">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-316">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-317">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="d5c13-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="d5c13-318">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-319">Fichiers marqués comme étant restreints ou ne peuvent pas être copiés</span><span class="sxs-lookup"><span data-stu-id="d5c13-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="d5c13-320">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d5c13-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="d5c13-322">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-323">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-323">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-324">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-325">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-326">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-327">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-328">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-329">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-329">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-330">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-330">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-331">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-331">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-332">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-333">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="d5c13-334">Notes de zone (conversion au format de document Word)</span><span class="sxs-lookup"><span data-stu-id="d5c13-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-335">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-336">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d5c13-337">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-338">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-339">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="d5c13-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-340">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-341">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-342">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-343">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-344">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-345">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="d5c13-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="d5c13-346">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="d5c13-347">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-348">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-349">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d5c13-350"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="d5c13-351">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-352">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-352">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-353">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-354">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-355">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-356">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-357">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-358">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-358">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-359">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-359">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-360">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-360">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-361">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-362">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="d5c13-363">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-364">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-365">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d5c13-366">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-367">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-368">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="d5c13-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-369">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-370">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-371">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-372">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-373">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="d5c13-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="d5c13-374">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="d5c13-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="d5c13-375">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="d5c13-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="d5c13-376">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="d5c13-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="d5c13-377">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="d5c13-378">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-379">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="d5c13-380">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d5c13-381">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5c13-381">FastTrack responsibilities</span></span>

<span data-ttu-id="d5c13-382">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-383">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d5c13-384">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="d5c13-384">Your responsibilities</span></span>

<span data-ttu-id="d5c13-385">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-386">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="d5c13-387">Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :</span><span class="sxs-lookup"><span data-stu-id="d5c13-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="d5c13-388">Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="d5c13-389">Migration vers OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="d5c13-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="d5c13-390">Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données.</span><span class="sxs-lookup"><span data-stu-id="d5c13-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d5c13-391">Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers.</span><span class="sxs-lookup"><span data-stu-id="d5c13-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="d5c13-392">Vous créez et planifiez vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-392">You create and schedule your migration events.</span></span> <span data-ttu-id="d5c13-393">Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.</span><span class="sxs-lookup"><span data-stu-id="d5c13-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d5c13-394">Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="d5c13-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="d5c13-395">Considérations</span><span class="sxs-lookup"><span data-stu-id="d5c13-395">Considerations</span></span>

  - <span data-ttu-id="d5c13-396">Toutes les migrations sont soumises aux quotas OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="d5c13-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="d5c13-397">Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="d5c13-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="d5c13-398">Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).</span><span class="sxs-lookup"><span data-stu-id="d5c13-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="d5c13-399">FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.</span><span class="sxs-lookup"><span data-stu-id="d5c13-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="d5c13-400">Détails de l’environnement source</span><span class="sxs-lookup"><span data-stu-id="d5c13-400">Source environment details</span></span>

<span data-ttu-id="d5c13-401">Nos services de migration des données migrent les données de ces environnements sources :</span><span class="sxs-lookup"><span data-stu-id="d5c13-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="d5c13-402">Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).</span><span class="sxs-lookup"><span data-stu-id="d5c13-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="d5c13-403">Environnement G Suite unique (Google Drive uniquement).</span><span class="sxs-lookup"><span data-stu-id="d5c13-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="d5c13-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="d5c13-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="d5c13-405">Dropbox pour Teams (Standard et avancée).</span><span class="sxs-lookup"><span data-stu-id="d5c13-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="d5c13-406">Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :</span><span class="sxs-lookup"><span data-stu-id="d5c13-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="d5c13-407"><strong>Environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="d5c13-408"><strong>Type de migration</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="d5c13-409"><strong>Ce qui est migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="d5c13-410"><strong>Ce qui n’est pas migré</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d5c13-411"><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="d5c13-412">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-413">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-413">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-414">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-415">Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*</span><span class="sxs-lookup"><span data-stu-id="d5c13-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d5c13-416">Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*</span><span class="sxs-lookup"><span data-stu-id="d5c13-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d5c13-417">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-418">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-419">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-419">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-420">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-420">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-421">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-421">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-422">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="d5c13-423">\*Configuration de la synchronisation d’annuaires requise.</span><span class="sxs-lookup"><span data-stu-id="d5c13-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="d5c13-424">Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="d5c13-425">Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="d5c13-426">Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</span><span class="sxs-lookup"><span data-stu-id="d5c13-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="d5c13-427">Historique d’appartenance et versions antérieures</span><span class="sxs-lookup"><span data-stu-id="d5c13-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="d5c13-428">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-429">Versions antérieures</span><span class="sxs-lookup"><span data-stu-id="d5c13-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="d5c13-430">Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)</span><span class="sxs-lookup"><span data-stu-id="d5c13-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="d5c13-431">Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :</span><span class="sxs-lookup"><span data-stu-id="d5c13-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="d5c13-432">Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)</span><span class="sxs-lookup"><span data-stu-id="d5c13-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="d5c13-433">Configuration de l’audit NTFS</span><span class="sxs-lookup"><span data-stu-id="d5c13-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="d5c13-434">Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)</span><span class="sxs-lookup"><span data-stu-id="d5c13-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="d5c13-435">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-436">Partages masqués</span><span class="sxs-lookup"><span data-stu-id="d5c13-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="d5c13-437">Partage (par exemple, autorisations accordées au niveau de partage)</span><span class="sxs-lookup"><span data-stu-id="d5c13-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="d5c13-438">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d5c13-439"><strong>Environnement G Suite unique (Google Drive uniquement)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="d5c13-440">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-441">Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo)</span><span class="sxs-lookup"><span data-stu-id="d5c13-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="d5c13-442">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-443">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-444">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-445">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-446">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-447">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-447">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-448">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-448">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-449">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-449">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-450">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-451">Lecteurs partagés (dossiers et fichiers)</span><span class="sxs-lookup"><span data-stu-id="d5c13-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="d5c13-452">Contenu partagé appartenant au compte Google Drive en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-453">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-454">Descriptions des fichiers et des dossiers, couleurs des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="d5c13-455">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-456">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-457">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="d5c13-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-458">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-459">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-460">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-461">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-462">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-463">Google Photos, Forms, Maps et autres applications connectées</span><span class="sxs-lookup"><span data-stu-id="d5c13-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="d5c13-464">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="d5c13-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="d5c13-465">Contenu partagé externe à votre organisation</span><span class="sxs-lookup"><span data-stu-id="d5c13-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="d5c13-466">Le contenu n’appartient pas au compte Google Drive migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="d5c13-467">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-468">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-469">Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés.</span><span class="sxs-lookup"><span data-stu-id="d5c13-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="d5c13-470">Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-471">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d5c13-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="d5c13-473">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-474">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-474">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-475">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-476">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-477">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-478">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-479">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-480">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-480">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-481">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-481">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-482">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-482">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-483">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-484">Contenu partagé appartenant au compte Box en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-485">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-486">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d5c13-487">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-488">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-489">Métadonnées avancées et balises Box</span><span class="sxs-lookup"><span data-stu-id="d5c13-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-490">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-491">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-492">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-493">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-494">Utilisateurs bloqués ou inactifs</span><span class="sxs-lookup"><span data-stu-id="d5c13-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d5c13-495">Applications, signets, favoris et flux de travail Box</span><span class="sxs-lookup"><span data-stu-id="d5c13-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="d5c13-496">Contenu n’appartenant pas au compte Box migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="d5c13-497">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-498">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-499">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d5c13-500"><strong>Dropbox pour Teams (Standard et avancée)</strong></span><span class="sxs-lookup"><span data-stu-id="d5c13-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="d5c13-501">Un ou plusieurs passages</span><span class="sxs-lookup"><span data-stu-id="d5c13-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d5c13-502">Documents</span><span class="sxs-lookup"><span data-stu-id="d5c13-502">Documents</span></span> </li>
<li> <span data-ttu-id="d5c13-503">Structure des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d5c13-504">Autorisations liées aux dossiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-505">Autorisations liées aux dossiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-506">Fichiers inférieurs à 15 Go</span><span class="sxs-lookup"><span data-stu-id="d5c13-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d5c13-507">Métadonnées de dossier et document de base :</span><span class="sxs-lookup"><span data-stu-id="d5c13-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d5c13-508">Date de création</span><span class="sxs-lookup"><span data-stu-id="d5c13-508">Created date</span></span> </li>
<li> <span data-ttu-id="d5c13-509">Date de modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-509">Modified date</span></span> </li>
<li> <span data-ttu-id="d5c13-510">Créé par</span><span class="sxs-lookup"><span data-stu-id="d5c13-510">Created by</span></span> </li>
<li> <span data-ttu-id="d5c13-511">Auteur de la dernière modification</span><span class="sxs-lookup"><span data-stu-id="d5c13-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d5c13-512">Dossiers et contenus collaboratifs partagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="d5c13-513">Contenu partagé appartenant au compte Dropbox en cours de migration</span><span class="sxs-lookup"><span data-stu-id="d5c13-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d5c13-514">Historique d’appartenance, versions précédentes et commentaires</span><span class="sxs-lookup"><span data-stu-id="d5c13-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d5c13-515">Descriptions des fichiers et des dossiers</span><span class="sxs-lookup"><span data-stu-id="d5c13-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d5c13-516">Autorisations liées aux fichiers au niveau de l’utilisateur</span><span class="sxs-lookup"><span data-stu-id="d5c13-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-517">Autorisations liées aux fichiers au niveau du groupe</span><span class="sxs-lookup"><span data-stu-id="d5c13-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d5c13-518">Métadonnées avancées</span><span class="sxs-lookup"><span data-stu-id="d5c13-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d5c13-519">Attributs de verrouillage de fichier</span><span class="sxs-lookup"><span data-stu-id="d5c13-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d5c13-520">Conversion d’URL incorporées dans le contenu</span><span class="sxs-lookup"><span data-stu-id="d5c13-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d5c13-521">Éléments jetés</span><span class="sxs-lookup"><span data-stu-id="d5c13-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="d5c13-522">Documents inaccessibles ou endommagés</span><span class="sxs-lookup"><span data-stu-id="d5c13-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d5c13-523">Dossiers Dropbox non montés</span><span class="sxs-lookup"><span data-stu-id="d5c13-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="d5c13-524">Utilisateurs supprimés ou déconnectés</span><span class="sxs-lookup"><span data-stu-id="d5c13-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="d5c13-525">Papier, vitrines et espaces Dropbox</span><span class="sxs-lookup"><span data-stu-id="d5c13-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="d5c13-526">Applications et favoris Dropbox (épingles/étoiles)</span><span class="sxs-lookup"><span data-stu-id="d5c13-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="d5c13-527">Contenu n’appartenant pas au compte Dropbox migré</span><span class="sxs-lookup"><span data-stu-id="d5c13-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="d5c13-528">Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="d5c13-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="d5c13-529">Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.)</span><span class="sxs-lookup"><span data-stu-id="d5c13-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d5c13-530">Fichiers ou dossiers dépassant <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">les restrictions et limitations SharePoint Online</span> actuelles</a> </span><span class="sxs-lookup"><span data-stu-id="d5c13-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d5c13-531">Responsabilités FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5c13-531">FastTrack responsibilities</span></span>

<span data-ttu-id="d5c13-532">Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-533">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d5c13-534">Vos responsabilités</span><span class="sxs-lookup"><span data-stu-id="d5c13-534">Your responsibilities</span></span>

<span data-ttu-id="d5c13-535">Vous effectuez les activités standard pendant le projet de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d5c13-536">Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="d5c13-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d5c13-537">Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :</span><span class="sxs-lookup"><span data-stu-id="d5c13-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="d5c13-538">Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.</span><span class="sxs-lookup"><span data-stu-id="d5c13-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

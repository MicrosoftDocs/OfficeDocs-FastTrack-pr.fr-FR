---
title: Produits et fonctionnalités
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour l’intégration réussie.
ms.openlocfilehash: 9a4546b248a739ee980f1300b9575e780e383c1a
ms.sourcegitcommit: 736a256276ead91385e1ec37b8a120b22259c4ea
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/24/2021
ms.locfileid: "52626683"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="88d7b-104">Produits et fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="88d7b-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="88d7b-105">Services et scénarios pris en charge par FastTrack</span><span class="sxs-lookup"><span data-stu-id="88d7b-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="88d7b-106">Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer.</span><span class="sxs-lookup"><span data-stu-id="88d7b-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="88d7b-107">En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour l’intégration réussie.</span><span class="sxs-lookup"><span data-stu-id="88d7b-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="88d7b-108">FastTrack fournit des conseils pour vous aider tout d’abord avec les fonctionnalités principales (courantes pour tous les Microsoft Online Services), puis avec l’intégration de chaque service éligible :</span><span class="sxs-lookup"><span data-stu-id="88d7b-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="88d7b-109">Général</span><span class="sxs-lookup"><span data-stu-id="88d7b-109">General</span></span>](#general)
  - [<span data-ttu-id="88d7b-110">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="88d7b-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="88d7b-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="88d7b-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="88d7b-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="88d7b-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="88d7b-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="88d7b-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="88d7b-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="88d7b-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="88d7b-115">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="88d7b-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="88d7b-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="88d7b-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="88d7b-117">Pour en savoir plus sur les conditions requises dans votre environnement source pour Office 365 US Government, consultez l’article relatif aux [conditions attendues dans l’environnement source pour Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="88d7b-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="88d7b-118">Général</span><span class="sxs-lookup"><span data-stu-id="88d7b-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-119"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-120"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-121"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88d7b-122"><strong>Intégration de base</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-123">Nous fournissons des conseils à distance sur l’intégration de base, qui implique l’approvisionnement de service, le client et l’intégration des identités.</span><span class="sxs-lookup"><span data-stu-id="88d7b-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="88d7b-124">Il inclut également des étapes pour fournir une base pour l’intégration de services tels que Exchange Online, SharePoint Online et Microsoft Teams, y compris une discussion sur la sécurité, la connectivité réseau et la <a href="/office365/enterprise/office-365-network-connectivity-principles">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="88d7b-125">L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="88d7b-126"></li>
</ul>  

<strong> Intégration des identités </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="88d7b-127">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="88d7b-128">Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), notamment l’installation et la configuration d’Azure AD Connecter (à forêt unique ou multi-forêts) et la gestion des licences (y compris les licences basées sur un groupe).</span><span class="sxs-lookup"><span data-stu-id="88d7b-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="88d7b-129">Création d’identités cloud, y compris l’importation et la gestion des licences en bloc, y compris l’utilisation de licences basées sur des groupes.</span><span class="sxs-lookup"><span data-stu-id="88d7b-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="88d7b-130">Choix et activation de la méthode d’authentification correcte pour votre parcours dans le cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou les services AD FS (Active Directory Federation Services).</span><span class="sxs-lookup"><span data-stu-id="88d7b-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="88d7b-131">Choix et activation d’une expérience d’authentification plus pratique pour vos utilisateurs avec l’authentification sans mot de passe (Fast Identity Online (FIDO)2 ou Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="88d7b-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="88d7b-132">Activation d’AD FS pour les clients avec une forêt Active Directory unique et des identités synchronisées avec l’outil de gestion Connecter Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="88d7b-133">Cela nécessite Windows Server 2012 R2 Active Directory Federation Services 2.0 ou supérieur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="88d7b-134">Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</span><span class="sxs-lookup"><span data-stu-id="88d7b-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="88d7b-135">Migration d’applications pré-intégrées (telles que les applications SaaS (software-as-a-service) azure AD AD gallery) vers Azure AD pour l' sign-on unique (SSO).</span><span class="sxs-lookup"><span data-stu-id="88d7b-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="88d7b-136">Activation des intégrations d’applications SaaS avec l' luiso à partir de la galerie Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="88d7b-137">Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme indiqué dans la liste de didacticiels sur l’intégration des applications <a href="/azure/active-directory/saas-apps/tutorial-list">(limitée </a> aux applications SaaS de la galerie Azure AD et à la mise en service sortante uniquement).</span><span class="sxs-lookup"><span data-stu-id="88d7b-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="88d7b-138"><strong>Activer le réseau </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="88d7b-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="88d7b-139">Dans le cadre des avantages de FastTrack, nous vous conseillons d’indiquer les meilleures pratiques en matière de connexion aux services cloud afin de garantir les niveaux de performances les plus élevés des Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="88d7b-140"><strong>Forêts Active Directory</strong> Le niveau de forêt fonctionnel est Windows Server 2003 et les autres, avec la configuration de forêt suivante :</span><span class="sxs-lookup"><span data-stu-id="88d7b-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-141">Forêt Active Directory unique.</span><span class="sxs-lookup"><span data-stu-id="88d7b-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-142">Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .</span><span class="sxs-lookup"><span data-stu-id="88d7b-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-143">Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).</span><span class="sxs-lookup"><span data-stu-id="88d7b-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-144">Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="88d7b-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-145">Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.</span><span class="sxs-lookup"><span data-stu-id="88d7b-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-146">Tâches requises pour la configuration et l’intégration des Azure Active Directory client, si nécessaire.</span><span class="sxs-lookup"><span data-stu-id="88d7b-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="88d7b-147">
  <strong>Important</strong>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="88d7b-148">Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype Entreprise est déployé, il doit être déployé dans la même forêt Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="88d7b-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-149">Lorsque vous implémentez plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration multi-hybride Exchange, les espaces de noms d’utilisateur principal (UPN) partagés entre les forêts sources ne sont pas pris en charge.</span><span class="sxs-lookup"><span data-stu-id="88d7b-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="88d7b-150">Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="88d7b-151">Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-152">Pour toutes les configurations à forêts multiples, le déploiement des services AD FS (Active Directory Federation Services) est hors de portée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="88d7b-153">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="88d7b-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-155">Nous fournissons des conseils de déploiement à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-156">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-157">Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="88d7b-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-158">Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="88d7b-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-159">Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="88d7b-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-160">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-161">Sélection et configuration d’une installation locale ou dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="88d7b-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-162">Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-163">Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="88d7b-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="88d7b-164">En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures de Office et que vous avez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème de compatibilité sans frais supplémentaires via le programme Soutien aux applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="88d7b-165">Pour plus <strong>d’informations,</strong> voir la partie <a href="#windows-10">Assurer Windows 10'application.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="88d7b-166">Les logiciels clients en ligne doivent être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .</span><span class="sxs-lookup"><span data-stu-id="88d7b-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-167"><strong>État du réseau</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-168">Nous fournissons des conseils à distance pour obtenir et interpréter les données de connectivité réseau clés de votre environnement, montrant comment les sites de votre organisation sont <a href="/office365/enterprise/office-365-network-connectivity-principles">alignés</a>sur les principes de connectivité réseau de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="88d7b-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="88d7b-169">Cela met en évidence votre score réseau qui a un impact direct sur la vitesse de migration, l’expérience utilisateur, les performances du service et la fiabilité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="88d7b-170">Nous vous guidons également à travers les étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="88d7b-171">Microsoft 365 Accès au Centre d’administration.</span><span class="sxs-lookup"><span data-stu-id="88d7b-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-172">Les versions à jour des applications Microsoft 365 sont requises.</span><span class="sxs-lookup"><span data-stu-id="88d7b-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-173">Services d’emplacement activés en tant que recommandations de performances réseau dans le <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">centre d’administration Microsoft 365 (prévisualisation).</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="88d7b-174">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="88d7b-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-175"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-176"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-177"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="88d7b-178"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-179">Nous fournissons des conseils à distance pour la sécurisation de vos identités cloud pour les scénarios suivants.</span><span class="sxs-lookup"><span data-stu-id="88d7b-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="88d7b-180">

<strong>Infrastructure de base sécurisée</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="88d7b-181">La configuration et l’activation d’une authentification forte pour vos identités, y compris la protection avec Azure Multi-Factor Authentication (MFA) (cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et la réinitialisation de mot de passe libre-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="88d7b-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="88d7b-182">Déploiement de FIDO2 ou Microsoft Authenticator App.</span><span class="sxs-lookup"><span data-stu-id="88d7b-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="88d7b-183">Pour les clients non-Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.</span><span class="sxs-lookup"><span data-stu-id="88d7b-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-184">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec l’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-185">Détection et blocage de l’utilisation de mots de passe faibles avec Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-186">Sécurisation de l’accès à distance aux applications web sur site avec le proxy d’application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-187">Activation de la détection et de la correction basées sur les risques avec Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-188">Activation d’un écran de personnalisation, y compris le logo, le texte et les images avec une personnalisation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-189">Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="88d7b-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-190">Gestion de l’accès pour vos administrateurs Office 365 à l’aide des rôles d’administration intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateur privilégiés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-191">Configuration de la jointation Azure AD hybride.</span><span class="sxs-lookup"><span data-stu-id="88d7b-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-192">Configuration de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="88d7b-193">
  
<strong>Surveiller et signaler</strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-194">Activation de la surveillance à distance pour les services AD FS, les Connecter Azure AD et les contrôleurs de domaine avec Azure AD Connecter Health.</span><span class="sxs-lookup"><span data-stu-id="88d7b-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="88d7b-195">
  
<strong>Gouvernance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-196">Gestion de votre cycle de vie d’accès et d’identité Azure AD à grande échelle avec la gestion des droits Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="88d7b-197">Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions d’accès Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-198">Examen des conditions d’utilisation d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-199">Gestion et contrôle de l’accès aux comptes d’administrateur privilégiés avec Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="88d7b-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="88d7b-200">
  
<strong>Automatisation et efficacité </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-201">Activation d’Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="88d7b-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="88d7b-202">Permettre aux utilisateurs de créer et de gérer leurs propres groupes de sécurité Office 365 cloud ou de gestion des groupes en libre-service Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-203">Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-204">Activation des groupes dynamiques Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-205">Organisation des applications dans le portail Mes applications à l’aide de collections.</span><span class="sxs-lookup"><span data-stu-id="88d7b-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="88d7b-206">Active Directory local et son environnement ont été préparés pour azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="88d7b-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-207"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="88d7b-208">Pour plus d’informations sur Azure Information Protection, voir <strong>Microsoft Information Protection</strong> plus loin dans ce tableau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="88d7b-209"><strong>Découvrir & répondre</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="88d7b-210"><strong>eDiscovery (découverte électronique) avancée</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="88d7b-211">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="88d7b-212">Création d’un cas.</span><span class="sxs-lookup"><span data-stu-id="88d7b-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="88d7b-213">Mise en attente des dépositaires.</span><span class="sxs-lookup"><span data-stu-id="88d7b-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-214">Effectuer des recherches.</span><span class="sxs-lookup"><span data-stu-id="88d7b-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="88d7b-215">Ajouter des résultats de recherche à un jeu à réviser.</span><span class="sxs-lookup"><span data-stu-id="88d7b-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="88d7b-216">Exécution de l’analyse sur un groupe de révision.</span><span class="sxs-lookup"><span data-stu-id="88d7b-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-217">Révision et marquage de documents.</span><span class="sxs-lookup"><span data-stu-id="88d7b-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-218">Exportation de données à partir du jeu à réviser.</span><span class="sxs-lookup"><span data-stu-id="88d7b-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="88d7b-219">Importation de données non Office 365 données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="88d7b-220"><strong>Audit avancé</strong> (uniquement pris en charge dans E5)</span><span class="sxs-lookup"><span data-stu-id="88d7b-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="88d7b-221">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="88d7b-222">Activation de l’audit avancé.</span><span class="sxs-lookup"><span data-stu-id="88d7b-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="88d7b-223">Exécuter une interface utilisateur du journal d’audit de recherche et des commandes PowerShell d’audit de base.</span><span class="sxs-lookup"><span data-stu-id="88d7b-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="88d7b-224">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="88d7b-225">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="88d7b-226">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="88d7b-227">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="88d7b-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="88d7b-228">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="88d7b-229">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="88d7b-230">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="88d7b-231">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="88d7b-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="88d7b-232">Scripts ou codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="88d7b-233">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="88d7b-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="88d7b-234">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="88d7b-235">Limites de conformité et filtres de sécurité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="88d7b-236">Enquêtes sur les données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="88d7b-237">Demandes des personnes à l’objet de données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="88d7b-238">Conception, architecte et révision de documents tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="88d7b-239">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="88d7b-240">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="88d7b-241">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="88d7b-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="88d7b-242"><strong>Gestion des risques internes</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="88d7b-243">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="88d7b-244">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="88d7b-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="88d7b-245">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="88d7b-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="88d7b-246">Créer des cas.</span><span class="sxs-lookup"><span data-stu-id="88d7b-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="88d7b-247">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="88d7b-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="88d7b-248">Recommandations sur la création du connecteur de ressources humaines (RH).</span><span class="sxs-lookup"><span data-stu-id="88d7b-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="88d7b-249">

<strong> Conformité des communications </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="88d7b-250">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="88d7b-251">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="88d7b-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="88d7b-252">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="88d7b-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="88d7b-253">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="88d7b-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="88d7b-254">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="88d7b-255">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="88d7b-256">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="88d7b-257">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="88d7b-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="88d7b-258">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="88d7b-259">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="88d7b-260">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="88d7b-261">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="88d7b-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="88d7b-262">La création et la gestion Power Automate flux de données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="88d7b-263">Connecteurs de données (au-delà du connecteur RH).</span><span class="sxs-lookup"><span data-stu-id="88d7b-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="88d7b-264">Configurations d’expression régulière personnalisées (RegEx).</span><span class="sxs-lookup"><span data-stu-id="88d7b-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="88d7b-265">Conception, architecte et révision de documents tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="88d7b-266">Obstacles à l’information.</span><span class="sxs-lookup"><span data-stu-id="88d7b-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="88d7b-267">Gestion des accès privilégiés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="88d7b-268">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="88d7b-269">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="88d7b-270">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="88d7b-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="88d7b-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="88d7b-272">Microsoft 365 Defender est une suite unifiée de défense d’entreprise avant et après la violation qui coordonne en natif la détection, la prévention, l’examen et la réponse entre les points de terminaison, les identités, le courrier électronique et les applications afin de fournir une protection intégrée contre les attaques sophistiquées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="88d7b-273">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="88d7b-274">Présentation du centre de Microsoft 365 de sécurité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-275">Passer en revue les incidents entre produits, notamment en vous concentrant sur les éléments critiques en garantissant l’étendue complète des attaques, les ressources impactées et les actions de correction automatisées regroupées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-276">Démonstration de la façon dont Microsoft 365 Defender peut orchestrer l’examen des biens, des utilisateurs, des appareils et des boîtes aux lettres qui ont pu être compromis par le biais d’une auto-ressource automatisée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="88d7b-277">Explication et fourniture d’exemples de la façon dont les clients peuvent chercher de manière proactive les tentatives d’intrusion et l’activité de violation affectant vos e-mails, données, appareils et comptes dans plusieurs ensembles de données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="88d7b-278">Montrer aux clients comment ils peuvent examiner et améliorer leur posture de sécurité globalement à l’aide du Niveau de sécurité Microsoft.</span><span class="sxs-lookup"><span data-stu-id="88d7b-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="88d7b-279"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="88d7b-280">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="88d7b-281">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="88d7b-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="88d7b-282">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="88d7b-283">Comment corriger ou interpréter les différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="88d7b-284">Comment examiner un utilisateur, un ordinateur, un chemin de mouvement latéral ou une entité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="88d7b-285">Recherche de menace personnalisée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="88d7b-286">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API.</span><span class="sxs-lookup"><span data-stu-id="88d7b-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-288">Microsoft Cloud App Security est un service Broker de sécurité d’accès au cloud (CASB) qui offre une visibilité enrichie, un contrôle sur les déplacements de données et des analyses sophistiquées pour identifier et lutter contre les cybermenaces dans tous vos services Cloud Microsoft et tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="88d7b-289">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-290">Configuration du portail, notamment :</span><span class="sxs-lookup"><span data-stu-id="88d7b-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="88d7b-291">Importation de groupes d’utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="88d7b-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="88d7b-292">Gestion de l’accès et des paramètres de l’administrateur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="88d7b-293">La portée de votre déploiement pour sélectionner certains groupes d’utilisateurs à surveiller ou exclure de la surveillance.</span><span class="sxs-lookup"><span data-stu-id="88d7b-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="88d7b-294">Définition de plages IP et de balises.</span><span class="sxs-lookup"><span data-stu-id="88d7b-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="88d7b-295">Personnalisation de l’expérience utilisateur final avec votre logo et votre messagerie personnalisée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="88d7b-296">Configuration de la découverte dans le cloud pour fournir des services informatiques de l’ombre à l’aide des :</span><span class="sxs-lookup"><span data-stu-id="88d7b-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="88d7b-297">Microsoft Defender pour les points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="88d7b-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="88d7b-298">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="88d7b-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="88d7b-299">iboss.</span><span class="sxs-lookup"><span data-stu-id="88d7b-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="88d7b-300">Connexion <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> d’applications featured à l’aide</a> de connecteurs d’application.</span><span class="sxs-lookup"><span data-stu-id="88d7b-300">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="88d7b-301">Configuration du contrôle d’application d’accès conditionnel dans les portails d Sécurité des applications cloud et d’accès conditionnel pour appliquer des contrôles de session en temps réel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="88d7b-302">Déploiement des tableaux de bord Sécurité des applications cloud de découverte cloud.</span><span class="sxs-lookup"><span data-stu-id="88d7b-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="88d7b-303">Personnalisation des scores de risque des applications en fonction des priorités de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="88d7b-304">Création de balises et de catégories d’application.</span><span class="sxs-lookup"><span data-stu-id="88d7b-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="88d7b-305">Application de sanctions et d’inséance.</span><span class="sxs-lookup"><span data-stu-id="88d7b-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="88d7b-306">Utilisation des journaux d’activité et de fichiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="88d7b-307">Gestion des applications OAuth.</span><span class="sxs-lookup"><span data-stu-id="88d7b-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="88d7b-308">Comprendre la corrélation d’incidents dans Microsoft 365 Portail Defender.</span><span class="sxs-lookup"><span data-stu-id="88d7b-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="88d7b-309">Fourniture d’une assistance à la configuration avec les 20 principaux cas d’utilisation pour les cas de base de données d’accès au détail (y compris la création ou la mise à jour de six (6) <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">stratégies),</a> sauf :</span><span class="sxs-lookup"><span data-stu-id="88d7b-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="88d7b-310">Audit de la configuration de vos environnements Internet en tant que service (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="88d7b-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="88d7b-311">Surveillance des activités des utilisateurs pour se protéger contre les menaces dans vos environnements IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="88d7b-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="88d7b-312"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="88d7b-313">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="88d7b-314">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="88d7b-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="88d7b-315">Configuration de l’infrastructure, de l’installation ou du déploiement des téléchargements automatiques de journaux pour les rapports continus à l’aide de Docker ou d’un collecteur de journaux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="88d7b-316">Pour <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">plus d’informations, consultez les 20 principaux cas d’utilisation</a> des cas d’analyse de cas d’analyse de cas.</span><span class="sxs-lookup"><span data-stu-id="88d7b-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="88d7b-317">Création d’un rapport instantané de découverte cloud.</span><span class="sxs-lookup"><span data-stu-id="88d7b-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="88d7b-318">Blocage de l’utilisation de l’application à l’aide de scripts de blocage.</span><span class="sxs-lookup"><span data-stu-id="88d7b-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="88d7b-319">Connexion d’applications personnalisées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="88d7b-320">Intégration avec des fournisseurs d’identité tiers (ISP) et des fournisseurs de protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="88d7b-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="88d7b-321">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="88d7b-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="88d7b-322">Examen et correction automatisés, y compris les manuels Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="88d7b-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="88d7b-323">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="88d7b-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="88d7b-324">Déploiement de la découverte d’applications cloud comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="88d7b-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="88d7b-325"><strong>Microsoft Defender pour point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-326">Microsoft Defender pour point de terminaison est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter, examiner et répondre aux menaces avancées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="88d7b-327">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-328">Déploiement des technologies pour sécuriser vos points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="88d7b-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-329">Configuration des profils de protection des points de terminaison et de restriction d’appareil.</span><span class="sxs-lookup"><span data-stu-id="88d7b-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-330">Évaluation de la version du système d’exploitation et de la gestion des appareils (notamment Intune, Microsoft Endpoint Configuration Manager, objets de stratégie de groupe et configurations tierces), ainsi que l’état de vos services antivirus Windows Defender ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="88d7b-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-331">Évaluation de l’état de vos services Windows antivirus ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="88d7b-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-332">Évaluation des proxies et des pare-feu limitant le trafic réseau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-333">Activation du service Microsoft Defender for Endpoint en expliquant comment déployer un profil d’agent Defender pour Endpoint à l’aide d’un point de terminaison intégré.</span><span class="sxs-lookup"><span data-stu-id="88d7b-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-334">Conseils de déploiement, assistance à la configuration et formation sur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-335">La gestion des menaces et des vulnérabilités.</span><span class="sxs-lookup"><span data-stu-id="88d7b-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-336">La réduction de la surface d’attaque.</span><span class="sxs-lookup"><span data-stu-id="88d7b-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-337">La nouvelle génération de protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-338">La détection de point de terminaison et réponse.</span><span class="sxs-lookup"><span data-stu-id="88d7b-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-339">Les enquêtes et résolutions automatiques.</span><span class="sxs-lookup"><span data-stu-id="88d7b-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-340">Le niveau de sécurité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-341">Examen des simulations et didacticiels (tels que les scénarios pratiques, les programmes malveillants factices et les enquêtes automatisées).</span><span class="sxs-lookup"><span data-stu-id="88d7b-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-342">Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.</span><span class="sxs-lookup"><span data-stu-id="88d7b-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-343">Intégration de Microsoft Defender for Office 365 à Microsoft Defender for Endpoint.</span><span class="sxs-lookup"><span data-stu-id="88d7b-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-344">Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="88d7b-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-345">Les systèmes d’exploitation suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-346">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-347">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="88d7b-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-348">Windows Serveur 2019.</span><span class="sxs-lookup"><span data-stu-id="88d7b-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-349">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="88d7b-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span><span class="sxs-lookup"><span data-stu-id="88d7b-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-351">macOS versions 10.13, 10.14 et 10.15.</span><span class="sxs-lookup"><span data-stu-id="88d7b-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="88d7b-352">
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou Microsoft Endpoint Configuration Manager (version 2002 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="88d7b-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="88d7b-353"></li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="88d7b-354">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-355">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="88d7b-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-356">Gestion continue et réponse aux menaces.</span><span class="sxs-lookup"><span data-stu-id="88d7b-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-357">Intégration ou configuration pour les agents Microsoft Defender pour points de terminaison suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-358">Windows Server 2008</span><span class="sxs-lookup"><span data-stu-id="88d7b-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-359">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="88d7b-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-360">Linux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-361">Appareils mobiles (Android et iOS).</span><span class="sxs-lookup"><span data-stu-id="88d7b-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="88d7b-362">Infrastructure VDI (Virtual Desktop Infrastructure) (persistante ou non persistante).</span><span class="sxs-lookup"><span data-stu-id="88d7b-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-363">Intégration et configuration du serveur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-364">Configuration d’un serveur proxy pour les communications hors connexion.</span><span class="sxs-lookup"><span data-stu-id="88d7b-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-365">Configuration des packages de déploiement Configuration Manager sur les instances et versions de Configuration Manager de bas niveau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-366">Intégration de serveurs au Centre de sécurité Azure.</span><span class="sxs-lookup"><span data-stu-id="88d7b-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-367">Serveurs non gérés par Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="88d7b-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-368">Intégration et configuration macOS :</span><span class="sxs-lookup"><span data-stu-id="88d7b-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-369">Déploiement intune manuel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-370">Déploiement basé sur JAMF.</span><span class="sxs-lookup"><span data-stu-id="88d7b-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="88d7b-371">Autres déploiements basés sur des produits de gestion des périphériques mobiles (MDM).</span><span class="sxs-lookup"><span data-stu-id="88d7b-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-372">Déploiement manuel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-373">Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :</span><span class="sxs-lookup"><span data-stu-id="88d7b-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-374">Isolation basée sur le matériel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-375">Contrôle d’application.</span><span class="sxs-lookup"><span data-stu-id="88d7b-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="88d7b-376">Contrôle d’appareil.</span><span class="sxs-lookup"><span data-stu-id="88d7b-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="88d7b-377">Exploit Protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-378">Pare-feu du réseau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="88d7b-379">Configuration ou gestion des fonctionnalités de protection des comptes telles que :</span><span class="sxs-lookup"><span data-stu-id="88d7b-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="88d7b-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="88d7b-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="88d7b-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="88d7b-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="88d7b-382">Configuration ou gestion des BitLocker.</span><span class="sxs-lookup"><span data-stu-id="88d7b-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="88d7b-383">Inscription ou configuration des Spécialistes des menaces Microsoft.</span><span class="sxs-lookup"><span data-stu-id="88d7b-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-384">Révision de la configuration ou de la formation sur les CONNEXIONS API ou informations de sécurité et de gestion des événements (SIEM).</span><span class="sxs-lookup"><span data-stu-id="88d7b-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-385">Inscription ou configuration de la Protection Microsoft contre les menaces (MTP).</span><span class="sxs-lookup"><span data-stu-id="88d7b-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-386">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="88d7b-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-387">Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</span><span class="sxs-lookup"><span data-stu-id="88d7b-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="88d7b-388">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="88d7b-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="88d7b-389"><strong>Microsoft Defender pour l’identité </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="88d7b-390">Microsoft Defender pour Identity est une solution de sécurité basée sur le cloud qui exploite vos signaux Active Directory sur site pour identifier, détecter et examiner les menaces avancées, les identités compromises et les actions des utilisateurs malveillants ciblant votre organisation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="88d7b-391">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="88d7b-392">Création de votre instance de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="88d7b-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="88d7b-393">Connexion de Defender pour l’identité à Active Directory.</span><span class="sxs-lookup"><span data-stu-id="88d7b-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="88d7b-394">Évaluation de la préparation de votre environnement pour déployer le capteur Defender for Identity sur vos contrôleurs de domaine, notamment :</span><span class="sxs-lookup"><span data-stu-id="88d7b-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="88d7b-395">Exécution de l’outil de taille pour la planification de la capacité des ressources.</span><span class="sxs-lookup"><span data-stu-id="88d7b-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="88d7b-396">Exécution de l’outil d’audit pour évaluer la compatibilité de vos contrôleurs de domaine avec le capteur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="88d7b-397">Déploiement du capteur pour capturer et parer le trafic réseau et Windows événements directement à partir de vos contrôleurs de domaine, notamment :</span><span class="sxs-lookup"><span data-stu-id="88d7b-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="88d7b-398">Téléchargement du package de capteur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="88d7b-399">Configuration du capteur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="88d7b-400">Installation silencieuse du capteur sur votre contrôleur de domaine.</span><span class="sxs-lookup"><span data-stu-id="88d7b-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="88d7b-401">Déploiement du capteur dans votre environnement à forêts multiples.</span><span class="sxs-lookup"><span data-stu-id="88d7b-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="88d7b-402">Intégration de Defender for Identity à Microsoft Cloud App Security (Sécurité des applications cloud licences n’est pas requise).</span><span class="sxs-lookup"><span data-stu-id="88d7b-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="88d7b-403">Fourniture d’instructions de déploiement, d’assistance à la configuration et de formation sur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="88d7b-404">Réglage de l’environnement pour réduire le « bruit ».</span><span class="sxs-lookup"><span data-stu-id="88d7b-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="88d7b-405">Comprendre le rapport d’évaluation de la sécurité des identités.</span><span class="sxs-lookup"><span data-stu-id="88d7b-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="88d7b-406">Comprendre le score de priorité d’examen de l’utilisateur et le rapport de classement de l’examen utilisateur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="88d7b-407">Comprendre le rapport utilisateur inactif.</span><span class="sxs-lookup"><span data-stu-id="88d7b-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="88d7b-408">Fourniture d’options de correction sur un compte compromis.</span><span class="sxs-lookup"><span data-stu-id="88d7b-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="88d7b-409">Faciliter la migration de Advanced Threat Analytics (ATA) vers Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="88d7b-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="88d7b-410"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="88d7b-411">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="88d7b-412">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="88d7b-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="88d7b-413">Déploiement du capteur Defender pour l’identité, notamment :</span><span class="sxs-lookup"><span data-stu-id="88d7b-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="88d7b-414">Planification manuelle de la capacité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="88d7b-415">Déploiement du capteur dans une capacité autonome.</span><span class="sxs-lookup"><span data-stu-id="88d7b-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="88d7b-416">Déploiement du capteur à l’aide d’un adaptateur d’équipe carte d’interface réseau (NIC).</span><span class="sxs-lookup"><span data-stu-id="88d7b-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="88d7b-417">Déploiement du capteur via un outil tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="88d7b-418">Connexion au service cloud Defender for Identity via une connexion proxy web.</span><span class="sxs-lookup"><span data-stu-id="88d7b-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="88d7b-419">Création et gestion de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="88d7b-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="88d7b-420">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="88d7b-421">Correction ou interprétation de différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="88d7b-422">Recherche d’un utilisateur, d’un ordinateur, d’un chemin de mouvement latéral ou d’une entité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="88d7b-423">Menace ou recherche avancée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="88d7b-424">Réponse aux incidents.</span><span class="sxs-lookup"><span data-stu-id="88d7b-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="88d7b-425">Fourniture d’un didacticiel de laboratoire d’alertes de sécurité pour Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="88d7b-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="88d7b-426">Envoi d’une notification lorsque Defender for Identity détecte des activités suspectes en envoyant des alertes de sécurité à votre serveur syslog via un capteur désigné.</span><span class="sxs-lookup"><span data-stu-id="88d7b-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="88d7b-427">Configuration de Defender for Identity pour effectuer des requêtes à l’aide du protocole SAMR (Security Account Manager remote) pour identifier les administrateurs locaux sur des ordinateurs spécifiques.</span><span class="sxs-lookup"><span data-stu-id="88d7b-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="88d7b-428">Configuration de solutions VPN pour ajouter des informations à partir de la connexion VPN à la page de profil d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="88d7b-429">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="88d7b-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="88d7b-430">Déploiement des capteurs Defender pour l’identité comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="88d7b-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="88d7b-431">Active Directory déployé.</span><span class="sxs-lookup"><span data-stu-id="88d7b-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-432">Les contrôleurs de domaine sur qui vous avez l’intention d’installer les capteurs Defender for Identity ont une connectivité Internet au service cloud de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="88d7b-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="88d7b-433">Votre pare-feu et votre proxy doivent être ouverts pour communiquer avec le service cloud Defender for Identity (\*.atp.azure.com port 443 doit être ouvert).</span><span class="sxs-lookup"><span data-stu-id="88d7b-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="88d7b-434">Contrôleurs de domaine en cours d’exécution sur l’une des suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="88d7b-435">Windows Serveur 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="88d7b-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="88d7b-436">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="88d7b-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="88d7b-437">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="88d7b-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="88d7b-438">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="88d7b-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="88d7b-439">Windows Serveur 2019 avec KB4487044 (build de système d’exploitation 17763.316).</span><span class="sxs-lookup"><span data-stu-id="88d7b-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="88d7b-440"><strong>Microsoft Defender pour Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-441">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-442">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="88d7b-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-443">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="88d7b-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-444">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="88d7b-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-445">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="88d7b-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="88d7b-446">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="88d7b-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="88d7b-447"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="88d7b-448">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-449">Création et publication d’étiquettes et de stratégies de rétention (uniquement pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="88d7b-450">Gestion des enregistrements (prise en charge uniquement dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="88d7b-451">Examen de la création d’un plan de fichiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="88d7b-452">Création et gestion des enregistrements (y compris les enregistrements basés sur des événements).</span><span class="sxs-lookup"><span data-stu-id="88d7b-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-453">Révision de la disposition.</span><span class="sxs-lookup"><span data-stu-id="88d7b-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="88d7b-454">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="88d7b-455">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="88d7b-456">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="88d7b-457">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="88d7b-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="88d7b-458">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="88d7b-459">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="88d7b-460">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="88d7b-461">

  <strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="88d7b-462">Développement d’un plan de gestion des fichiers de gestion des enregistrements.</span><span class="sxs-lookup"><span data-stu-id="88d7b-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="88d7b-463">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="88d7b-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="88d7b-464">Développement de l’architecture des informations dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="88d7b-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="88d7b-465">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="88d7b-466">Conception, architecte et révision de documents tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="88d7b-467">Prise en charge de l’E3.</span><span class="sxs-lookup"><span data-stu-id="88d7b-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="88d7b-468">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="88d7b-469">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="88d7b-470">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="88d7b-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-471"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-472">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-473">Classification des données (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-474">Types d’informations sensibles (pris en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-475">Création d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-476">Application d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-477">Classifieurs entra nessables (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-478">Connaissance de vos données avec l’Explorateur de contenu et l’Explorateur d’activités (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-479">Publication d’étiquettes à l’aide de stratégies (manuelles et automatiques) (prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-480">Création de stratégies de protection contre la perte de données (DLP) de point de terminaison pour Windows 10 appareils mobiles (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="88d7b-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-481">Création de stratégies DLP pour Microsoft Teams conversations et canaux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="88d7b-482">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="88d7b-483">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="88d7b-484">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="88d7b-485">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="88d7b-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="88d7b-486">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="88d7b-487">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="88d7b-488">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="88d7b-489">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="88d7b-490">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="88d7b-491">Activation et configuration de votre client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-492">Création et configuration d’étiquettes et de stratégies (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="88d7b-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-493">Application de la protection des informations aux documents (prise en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="88d7b-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-494">Classification et étiquetage automatiques des informations dans les applications Office (telles que Word, PowerPoint, Excel et Outlook) en cours d’exécution sur Windows et à l’aide du client Azure Information Protection (pris en charge dans P2).</span><span class="sxs-lookup"><span data-stu-id="88d7b-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-495">Découverte et étiquetage des fichiers au repos à l’aide du scanneur Azure Information Protection (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="88d7b-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-496">Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="88d7b-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="88d7b-497">Nous fournissons également des conseils si vous souhaitez appliquer la protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), chiffrement de messages Office 365 (OME) et la protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="88d7b-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="88d7b-498"><strong>Ce qui suit est hors de portée </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="88d7b-499">Clé client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-499">Customer key.</span></span></li>
<li><span data-ttu-id="88d7b-500">Développement d’expressions régulières personnalisées (RegEx) pour les types d’informations sensibles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="88d7b-501">Création ou modification de dictionnaires de mots clés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="88d7b-502">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="88d7b-503">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="88d7b-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="88d7b-504">Conception, architecte et révision de documents tiers.</span><span class="sxs-lookup"><span data-stu-id="88d7b-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="88d7b-505">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="88d7b-506">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="88d7b-507">En dehors <strong>de la</strong> partie Intégration de base en <a href="#general">général,</a>il n’existe aucune exigence système minimale à l’exception d’Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="88d7b-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="88d7b-509">Les responsabilités préalables du client sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="88d7b-510">Liste des emplacements de partage de fichiers à scanner.</span><span class="sxs-lookup"><span data-stu-id="88d7b-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-511">Taxonomie de classification approuvée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="88d7b-512">Comprendre les restrictions ou exigences réglementaires relatives à la gestion des clés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-513">Un compte de service créé pour votre annuaire Active Directory local qui a été synchronisé avec Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="88d7b-514">Étiquettes configurées pour la classification et la protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="88d7b-515">Toutes les conditions préalables pour le scanneur Azure Information Protection sont en place.</span><span class="sxs-lookup"><span data-stu-id="88d7b-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="88d7b-516">Pour plus d’informations, voir <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Conditions préalables à l’installation</a>et au déploiement du scanneur d’étiquetage unifié Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="88d7b-516">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="88d7b-517">Assurez-vous que les appareils utilisateur exécutent un système d’exploitation pris en charge et que les conditions préalables nécessaires sont installées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="88d7b-518">Pour plus d’informations, voir les informations suivantes.</span><span class="sxs-lookup"><span data-stu-id="88d7b-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="88d7b-519"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guide d’administration : Installer le client d’étiquetage unifié Azure Information Protection pour les utilisateurs</a>   </span><span class="sxs-lookup"><span data-stu-id="88d7b-519"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="88d7b-520"><a href="/azure/information-protection/rms-client/mobile-app-faq">Qu’est-ce que l’application Azure Information Protection pour iOS ou Android ?</a>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-520"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="88d7b-521">Installation et configuration du connecteur et des serveurs Azure RMS, y compris le connecteur AD RMS (Active Directory RMS) pour la prise en charge hybride.</span><span class="sxs-lookup"><span data-stu-id="88d7b-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="88d7b-522">Si vous avez besoin de l’une de ces options pour votre déploiement, vous devez installer et configurer Bring Your Own Key (BYOK), DKE (Double Key Encryption) (client d’étiquetage unifié uniquement) ou Hold Your Own Key (HYOK) (client classique uniquement).</span><span class="sxs-lookup"><span data-stu-id="88d7b-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-524">Nous fournissons des conseils à distance sur la préparation à l’utilisation d’Intune en tant que fournisseur de gestion des périphériques mobiles (MDM) et de gestion des applications mobiles (MAM) dans le cloud pour vos applications et appareils.</span><span class="sxs-lookup"><span data-stu-id="88d7b-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="88d7b-525">Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="88d7b-526">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-527">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-528">Configuration des identités à utiliser par Intune en tirant parti de vos identités Active Directory locales ou cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="88d7b-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-529">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="88d7b-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-530">Configuration de votre autorité de gestion des projets, en fonction de vos besoins en matière de gestion, notamment :</span><span class="sxs-lookup"><span data-stu-id="88d7b-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-531">Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-532">Recommandations en matière de gestion des appareils mobiles pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-533">Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.</span><span class="sxs-lookup"><span data-stu-id="88d7b-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-534">Configuration des stratégies de gestion et des services de gestion du service MDM tels que :</span><span class="sxs-lookup"><span data-stu-id="88d7b-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-535">Déploiement d’application pour chaque plateforme prise en charge par le biais de liens web ou de liens profonds.</span><span class="sxs-lookup"><span data-stu-id="88d7b-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-536">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-537">Déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous avez une autorité de certification, un réseau sans fil ou une infrastructure VPN existante dans votre organisation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-538">Connexion à l’entrepôt de données Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-539">Intégration de Intune avec :</span><span class="sxs-lookup"><span data-stu-id="88d7b-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-540">Visionneuse d’équipe pour l’assistance à distance (un abonnement Team Viewer est requis).</span><span class="sxs-lookup"><span data-stu-id="88d7b-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-541">Solutions de partenaires de protection contre les menaces mobiles (MTD) (un abonnement MTD est requis).</span><span class="sxs-lookup"><span data-stu-id="88d7b-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-542">Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).</span><span class="sxs-lookup"><span data-stu-id="88d7b-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="88d7b-543">Inscription de périphériques de chaque plateforme prise en charge sur Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="88d7b-544">Fournir des conseils sur la protection des applications sur :</span><span class="sxs-lookup"><span data-stu-id="88d7b-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-545">Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.</span><span class="sxs-lookup"><span data-stu-id="88d7b-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-546">Configuration des stratégies d’accès conditionnel pour les applications gérées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-547">Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées précédemment.</span><span class="sxs-lookup"><span data-stu-id="88d7b-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-548">Utilisation des rapports d’utilisation des applications gérées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-549">Fourniture de conseils de migration de la gestion des PC hérités vers la gestion des systèmes de gestion Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="88d7b-550">
 
</li>
</ul>
  
<strong>Attachement via le cloud</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="88d7b-551">Nous vous guidons tout au long de la préparation à l’attachement dans le cloud des environnements Configuration Manager existants avec Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="88d7b-552">Les étapes exactes dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="88d7b-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="88d7b-553">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="88d7b-554">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-555">Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.</span><span class="sxs-lookup"><span data-stu-id="88d7b-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-556">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="88d7b-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-557">Fourniture de conseils pour la configuration hybride de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="88d7b-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-558">Fourniture de conseils sur la configuration d’Azure AD pour l’inscription automatique À la gestion des paramètres de gestion des logiciels.</span><span class="sxs-lookup"><span data-stu-id="88d7b-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-559">Fourniture d’instructions sur la façon de configurer la passerelle de gestion cloud lorsqu’elle est utilisée comme solution pour la cogestion de la gestion des appareils basés sur Internet à distance.</span><span class="sxs-lookup"><span data-stu-id="88d7b-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-560">Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-561">Installation du client Configuration Manager dans les appareils inscrits sur Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="88d7b-562"><strong>Déployer Outlook mobile pour iOS et Android en toute sécurité</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook mobile pour iOS et Android en toute sécurité dans votre organisation afin de vous assurer que toutes les applications requises sont installées pour vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="88d7b-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="88d7b-563">Les étapes à suivre pour déployer Outlook mobile pour iOS et Android avec Intune en toute sécurité dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="88d7b-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="88d7b-564">Il peut inclure les suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-565">Téléchargement du Outlook applications pour iOS et Android, Microsoft Authenticator et Portail d’entreprise Intune par le biais de l’App Store d’Apple ou de Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="88d7b-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-566">Fourniture d’instructions sur la configuration :</span><span class="sxs-lookup"><span data-stu-id="88d7b-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-567">La Outlook pour iOS et Android, Microsoft Authenticator et Portail d’entreprise Intune applications avec Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-568">Stratégies de protection des applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-569">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-570">Stratégies de configuration d’application.</span><span class="sxs-lookup"><span data-stu-id="88d7b-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="88d7b-571">Les administrateurs informatiques doivent avoir une autorité de certification, un réseau sans fil et des infrastructures VPN existants qui fonctionnent déjà dans leurs environnements de production lors de la planification du déploiement de réseau sans fil et de profils VPN avec Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="88d7b-572"><strong>Remarque</strong>: l’avantage du service FastTrack n’inclut pas d’assistance pour la configuration des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats Push Apple MDM pour Intune.</span><span class="sxs-lookup"><span data-stu-id="88d7b-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="88d7b-573"><strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud.</span><span class="sxs-lookup"><span data-stu-id="88d7b-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="88d7b-574">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="88d7b-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="88d7b-575"><strong>Intune intégré à Microsoft Defender pour le point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="88d7b-576"><strong>Remarque</strong>: nous fournissons de l’aide sur l’intégration d’Intune à Microsoft Defender pour Endpoint et la création de stratégies de conformité des appareils en fonction de son évaluation Windows 10 niveau de risque.</span><span class="sxs-lookup"><span data-stu-id="88d7b-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="88d7b-577">Nous ne fournissons pas d’aide sur les achats, les licences ou l’activation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="88d7b-578">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="88d7b-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="88d7b-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="88d7b-580">Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.</span><span class="sxs-lookup"><span data-stu-id="88d7b-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="88d7b-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="88d7b-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-582"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-583"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-584"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88d7b-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-586">Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique.</span><span class="sxs-lookup"><span data-stu-id="88d7b-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="88d7b-587">Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.</span><span class="sxs-lookup"><span data-stu-id="88d7b-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="88d7b-588">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-589">La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-590">Pointage de vos enregistrements MX (mail exchange) vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-591">La configuration de Microsoft Defender pour Office 365 fonctionnalité si elle fait partie de votre service d’abonnement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="88d7b-592">Pour plus d’informations, <strong>voir Microsoft Defender pour Office 365</strong> partie de ce tableau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-p126">La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="88d7b-p127">La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="88d7b-597">
  <strong>Remarque :</strong> Le service de réplication de boîte aux lettres (MRS) tente de migrer des messages électroniques gérés par des droits d’information (IRM) de votre boîte aux lettres sur site vers la boîte aux lettres Exchange Online correspondante.</span><span class="sxs-lookup"><span data-stu-id="88d7b-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="88d7b-598">La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="88d7b-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="88d7b-599">La configuration de ports de pare-feu.</span><span class="sxs-lookup"><span data-stu-id="88d7b-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-600">Configuration du DNS, y compris les enregistrements DMARC (Autodiscover, Sender Policy Framework) requis, DKIM (DomainKeys Identified Mail), DMARC (Domain-based Message Authentication, Reporting and Conformance) et MX (selon vos besoins).</span><span class="sxs-lookup"><span data-stu-id="88d7b-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-601">la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).</span><span class="sxs-lookup"><span data-stu-id="88d7b-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-602">La migration de messagerie de votre environnement de messagerie source vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-603">La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="88d7b-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="88d7b-604">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="88d7b-605">Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="88d7b-606">Votre environnement source doit avoir l’un des niveaux minimum suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-607">Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.</span><span class="sxs-lookup"><span data-stu-id="88d7b-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-608">Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.</span><span class="sxs-lookup"><span data-stu-id="88d7b-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-609">Environnement G Suite unique (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="88d7b-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-610">Pour plus d’informations sur les fonctionnalités multigé géographiques, voir <a href="https://go.microsoft.com/fwlink/?linkid=872776">Fonctionnalités multigéo</a>géographiques dans Exchange Online .</span><span class="sxs-lookup"><span data-stu-id="88d7b-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="88d7b-611">Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive Entreprise, les Power BI Desktop et les Skype Entreprise doivent se trouver à un niveau minimal tel que défini dans la norme système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="88d7b-612"><strong>Microsoft Defender pour Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-613">Pour plus d’informations, <strong>voir Microsoft Defender pour Office 365</strong> sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="88d7b-614"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-615">Pour plus d’informations, voir Gouvernance des <strong>informations Microsoft</strong> en matière de sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">de conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-616"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="88d7b-617">Pour plus d’informations, voir <strong>Protection des informations Microsoft</strong> en matière de sécurité et de <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-619">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-620">Confirmation de la demande minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour prendre en charge Teams.</span><span class="sxs-lookup"><span data-stu-id="88d7b-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-621">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-622">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="88d7b-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-623">Confirmation que Teams est activé sur votre client Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-624">Activation ou désactivation des licences utilisateur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-625">Évaluation réseau pour les Teams :</span><span class="sxs-lookup"><span data-stu-id="88d7b-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-626">Vérifications des ports et des points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="88d7b-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-627">Contrôles de la qualité de connexion.</span><span class="sxs-lookup"><span data-stu-id="88d7b-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-628">Estimations de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="88d7b-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="88d7b-629">Configuration de Teams d’application (Teams application web, Teams application de bureau et Teams pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="88d7b-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="88d7b-630">Le cas échéant, nous fournissons également des conseils pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-631">Microsoft Teams Appareils de salle :</span><span class="sxs-lookup"><span data-stu-id="88d7b-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="88d7b-632">Création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge répertoriés dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-633">Assistance à distance avec la configuration côté service des appareils Salles Microsoft Teams certifiés.</span><span class="sxs-lookup"><span data-stu-id="88d7b-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-634">Activation de l’audioconférence :</span><span class="sxs-lookup"><span data-stu-id="88d7b-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="88d7b-635">Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.</span><span class="sxs-lookup"><span data-stu-id="88d7b-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-636">Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="88d7b-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="88d7b-637">Système téléphonique :</span><span class="sxs-lookup"><span data-stu-id="88d7b-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-638">Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="88d7b-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-639">Conseils sur les forfaits d’appels<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(marchés disponibles)</a>:</span><span class="sxs-lookup"><span data-stu-id="88d7b-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-640">Affectation de numéros aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="88d7b-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-641">Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.</span><span class="sxs-lookup"><span data-stu-id="88d7b-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-642">Prise en charge des demandes de service de portage de numéro local au-delà de 999.</span><span class="sxs-lookup"><span data-stu-id="88d7b-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="88d7b-643">Conseils de routage direct :</span><span class="sxs-lookup"><span data-stu-id="88d7b-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-644">Conseils de configuration de l’organisation pour la conception du routage direct des scénarios hébergés par un partenaire ou des scénarios déployés par le client pour un nombre de sites au plus de 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="88d7b-645">Révision de la configuration du contrôleur de frontière de session (SBC).</span><span class="sxs-lookup"><span data-stu-id="88d7b-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="88d7b-646">Assistance à distance avec la configuration du plan de numérotation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="88d7b-647">Configuration de l’itinéraire des voix.</span><span class="sxs-lookup"><span data-stu-id="88d7b-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="88d7b-648">Contournement de média et optimisation des médias locaux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="88d7b-649">Activation des événements en direct Teams.</span><span class="sxs-lookup"><span data-stu-id="88d7b-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-650">Configuration de l’organisation et intégration à Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="88d7b-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-651">Recommandations pour Skype Entreprise transition Teams transition.</span><span class="sxs-lookup"><span data-stu-id="88d7b-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="88d7b-652">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-653">Utilisateurs activés pour SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="88d7b-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-654">Exchange boîtes aux lettres sont présentes (en ligne et en local dans une configuration Exchange hybride).</span><span class="sxs-lookup"><span data-stu-id="88d7b-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-655">Activation pour les groupes Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="88d7b-656">
  <strong>Remarque :</strong> Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas OneDrive Entreprise stockage dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="88d7b-657">Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans des conversations sans OneDrive Entreprise stockage dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="88d7b-658">Teams ne prend pas en charge SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="88d7b-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="88d7b-659">
  <strong>Remarque :</strong> L’état idéal est que tous les utilisateurs ont leurs boîtes aux lettres Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="88d7b-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="88d7b-660">Les utilisateurs avec des boîtes aux lettres locales doivent avoir leur identité synchronisée avec le répertoire Office 365 via Azure AD Connecter.</span><span class="sxs-lookup"><span data-stu-id="88d7b-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="88d7b-661">Pour ces Exchange hybrides, si la boîte aux lettres de l’utilisateur est en local, l’utilisateur ne peut ni ajouter ni configurer de connecteurs.</span><span class="sxs-lookup"><span data-stu-id="88d7b-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="88d7b-662">Les programmes d’installation pour les clients de bureau Microsoft Teams Windows et Mac peuvent être téléchargés sur <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="88d7b-663"><strong>Outlook pour iOS et Android</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-664">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-665">Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.</span><span class="sxs-lookup"><span data-stu-id="88d7b-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-666">Configuration des comptes et accès à la boîte aux lettres Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="88d7b-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-667">Sécurisation Outlook mobile (voir <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sécurisation Outlook pour iOS</a> et Android dans Exchange Online pour plus d’informations).</span><span class="sxs-lookup"><span data-stu-id="88d7b-667">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="88d7b-668">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-669">Exchange Online configuré et licences attribuées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-671">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-672">Attribution de licences Power BI.</span><span class="sxs-lookup"><span data-stu-id="88d7b-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-673">Déploiement de l'application Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="88d7b-674">Les logiciels clients en ligne tels que Power BI Desktop doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-676">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-677">la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-678">l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-679">la configuration de la liste des ressources d’entreprise (ERP) ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-680">la création de votre premier projet.</span><span class="sxs-lookup"><span data-stu-id="88d7b-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="88d7b-681">Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88d7b-682"><strong>Project Online Professionnel et Premium</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-683">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-684">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-685">Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="88d7b-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-686">Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="88d7b-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-687">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-688">Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-689">Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="88d7b-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="88d7b-690">Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-691"><strong>SharePoint Online et OneDrive Entreprise</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-692">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-693">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="88d7b-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-694">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-695">la mise en service des utilisateurs et des licences ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="88d7b-696">l'activation de la création de sites pour votre administrateur SharePoint Online ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="88d7b-697">la planification des collections de sites ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="88d7b-698">la sécurisation du contenu et la gestion des autorisations ;</span><span class="sxs-lookup"><span data-stu-id="88d7b-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="88d7b-699">la configuration des fonctionnalités SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="88d7b-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="88d7b-700">la configuration des fonctionnalités Environnement hybride SharePoint, telles que la recherche hybride, les sites hybrides, la taxonomie hybride, les types de contenu, la création de sites en libre-service hybride (SharePoint Server 2013 uniquement), le lanceur d’applications étendu, OneDrive Entreprise hybride et les sites extranet.</span><span class="sxs-lookup"><span data-stu-id="88d7b-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-701">Votre approche de migration.</span><span class="sxs-lookup"><span data-stu-id="88d7b-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="88d7b-702">Des instructions supplémentaires sont fournies pour OneDrive Entreprise en fonction de votre version SharePoint, par exemple :</span><span class="sxs-lookup"><span data-stu-id="88d7b-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-703">Identification des options d’intégration et examen de l’infrastructure réseau locale et en ligne et de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="88d7b-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-704">Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et mise en œuvre des exigences de synchronisation et d’identité, et identification de votre client OneDrive Entreprise synchronisation.</span><span class="sxs-lookup"><span data-stu-id="88d7b-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-705">Planification et mise en œuvre d’un déploiement unique pour tous les utilisateurs (ou d’un déploiement par phases).</span><span class="sxs-lookup"><span data-stu-id="88d7b-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-706">Attribution de licences, redirection des sites Mon site et des bibliothèques de documents personnels vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="88d7b-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="88d7b-707">Redirection ou déplacement de dossiers connus vers OneDrive.</span><span class="sxs-lookup"><span data-stu-id="88d7b-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="88d7b-708">Déploiement de la synchronisation OneDrive Entreprise client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="88d7b-709">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="88d7b-710">Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="88d7b-711"><strong>Pour SharePoint hybride :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="88d7b-712">SharePoint configuration hybride inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, des OneDrive Entreprise, un lanceur d’applications étendu, des sites extranet et la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.</span><span class="sxs-lookup"><span data-stu-id="88d7b-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="88d7b-713">
  <strong>Remarque :</strong> La création de sites libre-service n’est pas limitée aux serveurs locaux SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="88d7b-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="88d7b-714">Pour activer SharePoint hybride, vous devez avoir l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.</span><span class="sxs-lookup"><span data-stu-id="88d7b-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="88d7b-715">
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue.</span><span class="sxs-lookup"><span data-stu-id="88d7b-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="88d7b-716">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide.</span><span class="sxs-lookup"><span data-stu-id="88d7b-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="88d7b-717">Pour plus d’informations, voir Niveaux de mise à jour publique <a href="https://go.microsoft.com/fwlink/?linkid=853548">minimale pour SharePoint fonctionnalités hybrides.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="88d7b-718">
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigé géographiques, voir Fonctionnalités <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigéo</a>géographiques dans OneDrive et SharePoint Online dans Office 365<em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="88d7b-720">Nous fournissons des conseils à distance pour l’activation Yammer Entreprise service.</span><span class="sxs-lookup"><span data-stu-id="88d7b-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="88d7b-721">Les logiciels clients en ligne doivent être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .</span><span class="sxs-lookup"><span data-stu-id="88d7b-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="88d7b-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="88d7b-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-723"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-724"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-725"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="88d7b-726"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-727">Pour plus d’informations, <strong>voir Azure Active Directory (Azure AD)</strong> et Azure AD Premium sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="88d7b-728">#sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="88d7b-728">#security-and-compliance</span></span>
<td><span data-ttu-id="88d7b-729"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-729"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="88d7b-730">Pour plus d’informations sur Azure Information Protection, voir <strong>Microsoft Information Protection</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-730">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="88d7b-731"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-731"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-732">Pour plus d’informations, <strong>voir Microsoft Intune</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-732">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="88d7b-733">Windows 10</span><span class="sxs-lookup"><span data-stu-id="88d7b-733">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-734"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-734"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-735"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-735"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-736"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-736"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88d7b-737"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-737"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-738">Nous fournissons des conseils pour la mise à niveau de Windows 7 Professionnel et Windows 8.1 Professional vers Windows 10 Entreprise.</span><span class="sxs-lookup"><span data-stu-id="88d7b-738">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="88d7b-739">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-739">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-740">Comprendre l’Windows 10 de votre entreprise.</span><span class="sxs-lookup"><span data-stu-id="88d7b-740">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-741">Évaluation de votre environnement source et des conditions requises (assurez-vous Microsoft Endpoint Configuration Manager niveau requis pour prendre en charge le déploiement Windows 10 déploiement).</span><span class="sxs-lookup"><span data-stu-id="88d7b-741">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-742">Déploiement de Windows 10 Entreprise et de Microsoft 365 Apps à l’aide Microsoft Endpoint Configuration Manager ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-742">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-743">Recommandations d’options pour évaluer vos applications Windows 10 applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-743">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-744">Activation de l’utilisation de Desktop Analytics et de conseils via la création d’un plan de déploiement Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="88d7b-744">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-745">Microsoft 365 Apps’évaluation de la compatibilité en tirant parti du tableau de bord de préparation Office 365 dans Configuration Manager ou avec la Shared Computer Toolkit de préparation autonome pour Office plus l’aide au déploiement Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="88d7b-745">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-746">Création d’une liste de vérification de correction sur ce que vous devez faire pour mettre votre environnement source au niveau minimal requis pour un déploiement réussi.</span><span class="sxs-lookup"><span data-stu-id="88d7b-746">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-747">Fournir des conseils de mise à niveau pour vos appareils existants Windows 10 Entreprise s’ils répondent à la configuration matérielle requise.</span><span class="sxs-lookup"><span data-stu-id="88d7b-747">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-748">Fournir des instructions de mise à niveau pour prendre en charge votre mouvement de déploiement existant.</span><span class="sxs-lookup"><span data-stu-id="88d7b-748">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="88d7b-749">FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-749">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="88d7b-750">Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.</span><span class="sxs-lookup"><span data-stu-id="88d7b-750">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-751">Déploiement de Microsoft 365 Apps à l’aide de Configuration Manager dans le cadre du Windows 10 déploiement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-751">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="88d7b-752">Fournir des conseils pour aider votre organisation à rester à jour avec Windows 10 Entreprise et Microsoft 365 Apps l’aide de votre environnement Configuration Manager ou de votre Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-752">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="88d7b-753">
  
<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-753">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="88d7b-754">Mettre à niveau Configuration Manager vers la branche actuelle.</span><span class="sxs-lookup"><span data-stu-id="88d7b-754">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-755">Créer des images personnalisées pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-755">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-756">Créer et prendre en charge des scripts de déploiement pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-756">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-757">Convertir un système Windows 10 à partir du BIOS vers Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="88d7b-757">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-758">Activer les fonctionnalités de sécurité Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-758">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-759">Configurer les services de déploiement Windows (WDS) pour le démarrage de l’environnement PXE (Preboot Execution Environment).</span><span class="sxs-lookup"><span data-stu-id="88d7b-759">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-760">Utiliser le Microsoft Deployment Toolkit (MDT) pour capturer et déployer des images Windows 10.</span><span class="sxs-lookup"><span data-stu-id="88d7b-760">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-761">Utiliser l’outil de migration de l’état utilisateur (USMT).</span><span class="sxs-lookup"><span data-stu-id="88d7b-761">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="88d7b-762">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="88d7b-762">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="88d7b-763">Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-763">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-764">Système d’exploitation source : Windows 7 Entreprise ou Professional, Windows 8.1 Entreprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="88d7b-764">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-765">Appareils : facteur de forme de bureau, de bloc-notes ou de tablette.</span><span class="sxs-lookup"><span data-stu-id="88d7b-765">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-766">Système d’exploitation cible : fenêtre 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="88d7b-766">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="88d7b-767">Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-767">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-768">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="88d7b-768">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-769">La version de Configuration Manager doit être prise en charge par la version Windows 10 cible.</span><span class="sxs-lookup"><span data-stu-id="88d7b-769">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="88d7b-770">Pour plus d’informations, voir le tableau de prise en charge de Configuration Manager de l’article <a href="/sccm/core/plan-design/configs/support-for-windows-10">Prise en charge de Windows 10 dans Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-770">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="88d7b-771"><strong>Microsoft Defender pour point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-771"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-772">Pour plus d’informations, <strong> voir Microsoft Defender for Endpoint</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-772">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="88d7b-773">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="88d7b-773">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-774"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-774"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-775"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-775"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-776"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-776"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88d7b-777"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-777"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="88d7b-778">Nous fournissons des conseils de déploiement pour l’intégration Windows Virtual Desktop (un service de virtualisation de bureau et d’application).</span><span class="sxs-lookup"><span data-stu-id="88d7b-778">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="88d7b-779">Windows Virtual Desktop tire parti de Windows 10 multisessage et est optimisé pour les Microsoft 365 Apps de Enterprise avec une sécurité et une gestion intégrées pour Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="88d7b-779">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="88d7b-780">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-780">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="88d7b-781">Déploiement de votre environnement Windows Virtual Desktop avec Windows 10 Entreprise sessions multiples et Microsoft 365 Apps pour Enterprise à l’aide des outils suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-781">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="88d7b-782">Image Marketplace Azure.</span><span class="sxs-lookup"><span data-stu-id="88d7b-782">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="88d7b-783">Image partagée.</span><span class="sxs-lookup"><span data-stu-id="88d7b-783">Shared image.</span></span></li>
<li><span data-ttu-id="88d7b-784">Office Déploiement Shared Computer Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="88d7b-784">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="88d7b-785">Configuration de FSLogix :</span><span class="sxs-lookup"><span data-stu-id="88d7b-785">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="88d7b-786">Déploiement de l’agent FSLogix avec conteneur de profils.</span><span class="sxs-lookup"><span data-stu-id="88d7b-786">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="88d7b-787">Déploiement de l’agent FSLogix Office conteneur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-787">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="88d7b-788">Configuration du dossier FSLogix avec des exclusions de contenu.</span><span class="sxs-lookup"><span data-stu-id="88d7b-788">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="88d7b-789">Déploiement de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="88d7b-789">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="88d7b-790">Déploiement de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="88d7b-790">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="88d7b-791">Connexion à l’Windows clients Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-791">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="88d7b-792">

<strong>Ce qui suit est hors de portée</strong>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-792">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="88d7b-793">Project gestion du déploiement de bureau virtuel Windows client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-793">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="88d7b-794">Virtualisation et déploiement d’applications tierces.</span><span class="sxs-lookup"><span data-stu-id="88d7b-794">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="88d7b-795">Images personnalisées.</span><span class="sxs-lookup"><span data-stu-id="88d7b-795">Custom images.</span></span></li>
<li><span data-ttu-id="88d7b-796">Migrations et scénarios impliquant VMware et Citrix.</span><span class="sxs-lookup"><span data-stu-id="88d7b-796">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="88d7b-797">Scénarios Linux.</span><span class="sxs-lookup"><span data-stu-id="88d7b-797">Linux scenarios.</span></span></li>
<li><span data-ttu-id="88d7b-798">Conversion ou migrations de profils utilisateur.</span><span class="sxs-lookup"><span data-stu-id="88d7b-798">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="88d7b-799">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="88d7b-799">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="88d7b-800">Vous devez déjà avoir les choses suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-800">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="88d7b-801"><a href="/azure/virtual-desktop/overview#requirements">Windows licences Virtual Desktop requises.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-801"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="88d7b-802">Mise en réseau Azure :</span><span class="sxs-lookup"><span data-stu-id="88d7b-802">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="88d7b-803">Création et sous-réseau de réseau virtuel (VNET).</span><span class="sxs-lookup"><span data-stu-id="88d7b-803">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="88d7b-804">Pare-feu et groupes de sécurité réseau.</span><span class="sxs-lookup"><span data-stu-id="88d7b-804">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="88d7b-805">VPN et ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="88d7b-805">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="88d7b-806">Routage vers Azure à partir de l’local.</span><span class="sxs-lookup"><span data-stu-id="88d7b-806">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="88d7b-807">Règles de pare-feu pour autoriser la connectivité Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-807">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="88d7b-808">Pour plus d’informations, voir <a href="//azure/virtual-desktop/overview#supported-remote-desktop-clients">Clients Bureau à distance pris en charge.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-808">For more information, see <a href="//azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="88d7b-809">Configuration générale d’Azure AD :</span><span class="sxs-lookup"><span data-stu-id="88d7b-809">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="88d7b-810">Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-810">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="88d7b-811">Active Directory avec Azure AD Connecter azure.</span><span class="sxs-lookup"><span data-stu-id="88d7b-811">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="88d7b-812">Active Directory avec Azure AD Connecter local sur VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="88d7b-812">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="88d7b-813">Services de domaine Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="88d7b-813">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="88d7b-814">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="88d7b-814">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-815"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-815"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-816"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-816"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-817"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-817"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="88d7b-818"><strong>Soutien aux Applications</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-818"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="88d7b-819">L’App Assure est un service conçu pour résoudre les problèmes de Windows 10 et Microsoft 365 Apps compatibilité des applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-819">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="88d7b-820">Lorsque vous demandez le service Soutien aux applications, nous travaillons avec vous pour résoudre les problèmes d’application valides sans frais supplémentaires pour vous avec un abonnement éligible.</span><span class="sxs-lookup"><span data-stu-id="88d7b-820">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="88d7b-821">Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et Microsoft Edge et nous faisons tout ce qui est raisonnable pour résoudre les problèmes de compatibilité.</span><span class="sxs-lookup"><span data-stu-id="88d7b-821">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="88d7b-822">Nous fournissons une assistance de correction pour les applications déployées sur les produits Microsoft suivants :</span><span class="sxs-lookup"><span data-stu-id="88d7b-822">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="88d7b-823"><strong>Windows 10</strong> (y compris les appareils ARM64)</span><span class="sxs-lookup"><span data-stu-id="88d7b-823"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="88d7b-824"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="88d7b-824"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="88d7b-825"><strong>Microsoft Edge -</strong> Pour obtenir des conseils de déploiement, voir <a href="/DeployEdge/microsoft-edge-channels">Vue d’ensemble Microsoft Edge canaux de déploiement.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-825"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-826"><strong>Windows Virtual Desktop</strong> - Pour plus d’informations, voir <a href="/azure/virtual-desktop/overview">Qu’est-ce Windows Virtual Desktop ?</a> et Windows 10 Entreprise faq sur les <a href="/azure/virtual-desktop/windows-10-multisession-faq">sessions multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-826"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="88d7b-827">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-827">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="88d7b-828">Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="88d7b-828">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="88d7b-829">Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-829">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="88d7b-830">Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-830">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="88d7b-831">Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces.</span><span class="sxs-lookup"><span data-stu-id="88d7b-831">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="88d7b-832">Pour plus d’informations, consultez <a href="/sccm/desktop-analytics/overview">Analytique de bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-832">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="88d7b-833">Services uniquement pour le conditionnement des applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-833">App packaging-only services.</span></span> <span data-ttu-id="88d7b-834">Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-834">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="88d7b-835">

<strong>Les responsabilités du client sont les suivantes :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-835">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="88d7b-836">Création d’un inventaire d’applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-836">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="88d7b-837">Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="88d7b-837">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="88d7b-838">
<strong>Remarque :</strong>  Microsoft ne peut pas apporter de modifications à votre code source.</span><span class="sxs-lookup"><span data-stu-id="88d7b-838">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="88d7b-839">Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications.</span><span class="sxs-lookup"><span data-stu-id="88d7b-839">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="88d7b-840">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="88d7b-840">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="88d7b-841"><strong>Windows 10 et Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-841"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-842">Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="88d7b-842">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="88d7b-843">
<strong>Windows 10 sur ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-843">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="88d7b-844">Les applications qui fonctionnaient sur Windows 7, Office 2010 ou versions ultérieures fonctionnent également sur Windows 10 et Microsoft 365 Apps sur les appareils ARM64.</span><span class="sxs-lookup"><span data-stu-id="88d7b-844">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="88d7b-845">
  <strong>Remarque :</strong> 
</span><span class="sxs-lookup"><span data-stu-id="88d7b-845">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="88d7b-846">L’émulation x64 (64 bits) est disponible en prévisualisation pour les clients participant au programme <a href="https://insider.windows.com/">Insider Windows.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-846">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="88d7b-847">Pour les clients Insider Windows qui ne sont pas abonnés à Windows 10 version 2004 (ou ultérieure), ARM64 Photoshop est pris en charge à l’aide du pack de compatibilité OpenCL et <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-847">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="88d7b-848">Les clients du Windows Insider peuvent télécharger une version Insider du pack de compatibilité OpenCL et OpenGL pour une utilisation avec des applications supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="88d7b-848">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="88d7b-849">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="88d7b-849">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-850">Si vos applications ou sites web fonctionnent sur Internet Explorer 11, les versions de Google Chrome ou toute version de Microsoft Edge, elles fonctionneront également avec Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="88d7b-850">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-851">Comme le site web évolue constamment, n’oubliez pas de passer en revue cette liste publiée des modifications qui ont un impact sur la compatibilité des sites <a href="/microsoft-edge/web-platform/site-impacting-changes">connues pour Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="88d7b-851">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="88d7b-852">
  <strong>Windows Virtual Desktop</strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-852">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="88d7b-853">Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-853">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-854">Les applications s’exécutant sur n’importe quel environnement VDI (Virtual Desktop Infrastructure) Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-854">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-855">Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="88d7b-855">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="88d7b-856">
  <strong>Remarque : Windows 10 Entreprise</strong> exclusions et limitations de compatibilité à plusieurs sessions sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="88d7b-856">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="88d7b-857">Redirection limitée du matériel.</span><span class="sxs-lookup"><span data-stu-id="88d7b-857">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-858">Les applications ayant une grande quantité de A/V peuvent avoir une capacité réduite.</span><span class="sxs-lookup"><span data-stu-id="88d7b-858">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="88d7b-859">Les applications 16 bits ne sont pas prises en charge pour les applications Windows Virtual Desktop 64 bits.</span><span class="sxs-lookup"><span data-stu-id="88d7b-859">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="88d7b-860">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="88d7b-860">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88d7b-861"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-861"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="88d7b-862"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-862"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="88d7b-863"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="88d7b-863"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="88d7b-864"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="88d7b-864"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="88d7b-865">Nous fournissons des conseils sur le déploiement à distance et l’adoption, ainsi que l’assistance à la compatibilité pour :</span><span class="sxs-lookup"><span data-stu-id="88d7b-865">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="88d7b-866">Déploiement de Microsoft Edge sur Windows 10 avec Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="88d7b-866">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-867">Configuration des Microsoft Edge (à l’aide de stratégies de groupe ou de configuration d’application Intune et de stratégies d’application).</span><span class="sxs-lookup"><span data-stu-id="88d7b-867">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="88d7b-868">Inventaire de la liste des sites qui peuvent nécessiter une utilisation en mode Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="88d7b-868">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="88d7b-869">Activation du mode Internet Explorer avec la liste Enterprise sites existante.</span><span class="sxs-lookup"><span data-stu-id="88d7b-869">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="88d7b-870">(Pour plus d’informations, voir <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engager FastTrack.</a></span><span class="sxs-lookup"><span data-stu-id="88d7b-870">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="88d7b-871">En outre, si vous avez une application web ou un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="88d7b-871">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="88d7b-872">Pour demander la prise en charge de la compatibilité pour Soutien aux applications, connectez-vous au <a href="https://fasttrack.microsoft.com/portal#/signin">portail FastTrack</a> pour démarrer un engagement.</span><span class="sxs-lookup"><span data-stu-id="88d7b-872">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="88d7b-873">Conseils de planification pour l’adoption edge et les conseils de configuration pour les signets de recherche Microsoft.</span><span class="sxs-lookup"><span data-stu-id="88d7b-873">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="88d7b-874">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="88d7b-874">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="88d7b-875">Gestion de projet du déploiement Microsoft Edge du client.</span><span class="sxs-lookup"><span data-stu-id="88d7b-875">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="88d7b-876">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="88d7b-876">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

---
title: Produits et fonctionnalités
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour réussir l’intégration.
ms.openlocfilehash: e49ada61aee869785f061bbebbee4ae14aaee045
ms.sourcegitcommit: 895a8b9df9a7cd26e27e95e5fd3145e7306c78e8
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464206"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="2da05-104">Produits et fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="2da05-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="2da05-105">Services et scénarios pris en charge par FastTrack</span><span class="sxs-lookup"><span data-stu-id="2da05-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="2da05-106">Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer.</span><span class="sxs-lookup"><span data-stu-id="2da05-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="2da05-107">En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour l’intégration réussie.</span><span class="sxs-lookup"><span data-stu-id="2da05-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="2da05-108">FastTrack fournit des conseils pour vous aider tout d’abord avec les fonctionnalités principales (courantes pour tous les Microsoft Online Services), puis avec l’intégration de chaque service éligible :</span><span class="sxs-lookup"><span data-stu-id="2da05-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="2da05-109">Général</span><span class="sxs-lookup"><span data-stu-id="2da05-109">General</span></span>](#general)
  - [<span data-ttu-id="2da05-110">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="2da05-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="2da05-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="2da05-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="2da05-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="2da05-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="2da05-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="2da05-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="2da05-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="2da05-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="2da05-115">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="2da05-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="2da05-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="2da05-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="2da05-117">Pour en savoir plus sur les conditions requises dans votre environnement source pour Office 365 US Government, consultez l’article relatif aux [conditions attendues dans l’environnement source pour Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="2da05-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="2da05-118">Général</span><span class="sxs-lookup"><span data-stu-id="2da05-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-119"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-120"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-121"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2da05-122"><strong>Intégration de base</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="2da05-123">Nous fournissons des conseils à distance sur l’intégration de base, qui implique l’approvisionnement de service, le client et l’intégration des identités.</span><span class="sxs-lookup"><span data-stu-id="2da05-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="2da05-124">Il inclut également des étapes pour fournir une base pour l’intégration de services tels qu’Exchange Online, SharePoint Online et Microsoft Teams, y compris une discussion sur la sécurité, la connectivité réseau et la <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="2da05-125">L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.</span><span class="sxs-lookup"><span data-stu-id="2da05-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="2da05-126"></li>
</ul>  

<strong> Intégration des identités </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="2da05-127">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="2da05-128">Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), notamment l’installation et la configuration d’Azure AD Connect (à forêt unique ou multi-forêts) et la gestion des licences (y compris les licences basées sur un groupe).</span><span class="sxs-lookup"><span data-stu-id="2da05-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="2da05-129">Création d’identités cloud, y compris l’importation et la gestion des licences en bloc, y compris l’utilisation de licences basées sur des groupes.</span><span class="sxs-lookup"><span data-stu-id="2da05-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="2da05-130">Choix et activation de la méthode d’authentification correcte pour votre parcours dans le cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou les services AD FS (Active Directory Federation Services).</span><span class="sxs-lookup"><span data-stu-id="2da05-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="2da05-131">Activation d’AD FS pour les clients avec une forêt Active Directory unique et des identités synchronisées avec l’outil Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="2da05-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="2da05-132">Cela nécessite Windows Server 2012 R2 Active Directory Federation Services 2.0 ou supérieur.</span><span class="sxs-lookup"><span data-stu-id="2da05-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="2da05-133">Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</span><span class="sxs-lookup"><span data-stu-id="2da05-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="2da05-134">Migration d’applications pré-intégrées (telles que les applications SaaS (software-as-a-service) azure AD AD gallery) vers Azure AD pour l' sign-on unique (SSO).</span><span class="sxs-lookup"><span data-stu-id="2da05-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="2da05-135">Activation des intégrations d’applications SaaS avec l' luiso à partir de la galerie Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="2da05-136">Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme indiqué dans la liste de didacticiels sur l’intégration des applications <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">(limitée</a> aux applications SaaS de la galerie Azure AD et à la mise en service sortante uniquement).</span><span class="sxs-lookup"><span data-stu-id="2da05-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="2da05-137"><strong>Activer le réseau </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="2da05-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="2da05-138">Dans le cadre des avantages de FastTrack, nous vous conseillons d’indiquer les meilleures pratiques en matière de connexion aux services cloud afin de garantir les niveaux de performances les plus élevés de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="2da05-139"><strong>Forêts Active Directory</strong> Celles-ci ont le niveau de forêt fonctionnel définie sur Windows Server 2003 et les autres, avec la configuration de forêt suivante :</span><span class="sxs-lookup"><span data-stu-id="2da05-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-140">Forêt Active Directory unique.</span><span class="sxs-lookup"><span data-stu-id="2da05-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="2da05-141">Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .</span><span class="sxs-lookup"><span data-stu-id="2da05-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-142">Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).</span><span class="sxs-lookup"><span data-stu-id="2da05-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-143">Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="2da05-144">Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.</span><span class="sxs-lookup"><span data-stu-id="2da05-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="2da05-145">Tâches requises pour la configuration du client et l’intégration à Azure Active Directory, si nécessaire.</span><span class="sxs-lookup"><span data-stu-id="2da05-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="2da05-146">
  <strong>Important</strong>  </span><span class="sxs-lookup"><span data-stu-id="2da05-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="2da05-147">Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype Entreprise est déployé, il doit être déployé dans la même forêt Active Directory qu’Exchange.</span><span class="sxs-lookup"><span data-stu-id="2da05-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="2da05-148">Lors de l’implémentation de plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration Exchange multi-hybride, les espaces de noms d’utilisateur principal (UPN) partagés entre les forêts sources ne sont pas pris en charge.</span><span class="sxs-lookup"><span data-stu-id="2da05-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="2da05-149">Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés.</span><span class="sxs-lookup"><span data-stu-id="2da05-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="2da05-150">Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="2da05-151">Pour toutes les configurations à forêts multiples, le déploiement des services AD FS (Active Directory Federation Services) est hors de portée.</span><span class="sxs-lookup"><span data-stu-id="2da05-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="2da05-152">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="2da05-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="2da05-154">Nous fournissons des conseils de déploiement à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-155">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="2da05-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="2da05-156">Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="2da05-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="2da05-157">Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="2da05-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="2da05-158">Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="2da05-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="2da05-159">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2da05-160">Sélection et configuration d’une installation locale ou dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="2da05-161">Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.</span><span class="sxs-lookup"><span data-stu-id="2da05-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="2da05-162">Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2da05-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="2da05-163">En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures d’Office et que vous avez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème de compatibilité sans frais supplémentaires par le biais du programme Soutien aux applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="2da05-164">Pour plus <strong>d’informations,</strong> voir la partie Assure des applications de <a href="#windows-10">Windows 10.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2da05-165">Les logiciels clients en ligne doivent être au niveau minimal défini dans la version système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 et Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-166"><strong>État du réseau</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="2da05-167">Nous fournissons des conseils à distance pour obtenir et interpréter les données de connectivité réseau clés de votre environnement, montrant comment les sites de votre organisation sont <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">alignés</a>sur les principes de connectivité réseau de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2da05-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="2da05-168">Cela met en évidence votre score réseau qui a un impact direct sur la vitesse de migration, l’expérience utilisateur, les performances du service et la fiabilité.</span><span class="sxs-lookup"><span data-stu-id="2da05-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="2da05-169">Nous vous guidons également à travers les étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="2da05-170">Accès au Centre d’administration Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="2da05-171">Les versions à jour des applications Microsoft 365 sont requises.</span><span class="sxs-lookup"><span data-stu-id="2da05-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="2da05-172">Services de localisation activés en tant que recommandations de performances réseau dans le Centre d’administration <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (prévisualisation).</a></span><span class="sxs-lookup"><span data-stu-id="2da05-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="2da05-173">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="2da05-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-174"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-175"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-176"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="2da05-177"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="2da05-178">Nous fournissons des conseils à distance pour la sécurisation de vos identités cloud pour les scénarios suivants.</span><span class="sxs-lookup"><span data-stu-id="2da05-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="2da05-179">

<strong>Infrastructure de base sécurisée</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="2da05-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="2da05-180">La configuration et l’activation d’une authentification forte pour vos identités, notamment la protection avec Azure Multi-Factor Authentication (MFA) (cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et la réinitialisation de mot de passe libre-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="2da05-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="2da05-181">Pour les clients autres qu’Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.</span><span class="sxs-lookup"><span data-stu-id="2da05-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="2da05-182">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec l’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="2da05-183">Détection et blocage de l’utilisation de mots de passe faibles avec Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="2da05-184">Sécurisation de l’accès à distance aux applications web sur site avec le proxy d’application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="2da05-185">Activation de la détection et de la correction basées sur les risques avec Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="2da05-186">Activation d’un écran de personnalisation, y compris le logo, le texte et les images avec une personnalisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="2da05-187">Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="2da05-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="2da05-188">Gestion de l’accès pour vos administrateurs Office 365 à l’aide des rôles d’administration intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateur privilégiés.</span><span class="sxs-lookup"><span data-stu-id="2da05-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="2da05-189">Configuration de la jointation Azure AD hybride.</span><span class="sxs-lookup"><span data-stu-id="2da05-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2da05-190">Configuration de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="2da05-191">
  
<strong>Surveiller et signaler</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-192">Activation de la surveillance à distance pour les services AD FS, Azure AD Connect et les contrôleurs de domaine avec Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="2da05-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-193">
  
<strong>Gouvernance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-194">Gestion de votre cycle de vie d’accès et d’identité Azure AD à grande échelle avec la gestion des droits Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="2da05-195">Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions d’accès Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-196">Examen des conditions d’utilisation d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-197">Gestion et contrôle de l’accès aux comptes d’administrateur privilégiés avec Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="2da05-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-198">
  
<strong>Automatisation et efficacité </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-199">Activation d’Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="2da05-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="2da05-200">Permettre aux utilisateurs de créer et de gérer leur propre sécurité cloud ou groupes Office 365 avec la gestion de groupes en libre-service Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-201">Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-202">Activation des groupes dynamiques Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-203">Organisation des applications dans le portail Mes applications à l’aide de collections.</span><span class="sxs-lookup"><span data-stu-id="2da05-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-204">Active Directory local et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="2da05-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="2da05-206">Pour plus d’informations sur Azure Information Protection, voir <strong>Microsoft Information Protection</strong> plus loin dans ce tableau.</span><span class="sxs-lookup"><span data-stu-id="2da05-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="2da05-207"><strong>Réponse & détection</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="2da05-208"><strong>Advanced eDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="2da05-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="2da05-209">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="2da05-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="2da05-210">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="2da05-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="2da05-211">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="2da05-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="2da05-212">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="2da05-213"><strong>Audit avancé</strong> (uniquement pris en charge dans E5)</span><span class="sxs-lookup"><span data-stu-id="2da05-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="2da05-214">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-214">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="2da05-215">Activation de l’audit avancé.</span><span class="sxs-lookup"><span data-stu-id="2da05-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="2da05-216">Exécuter une interface utilisateur du journal d’audit de recherche et des commandes PowerShell d’audit de base.</span><span class="sxs-lookup"><span data-stu-id="2da05-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="2da05-217">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-218">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-219">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-220">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-221">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-222">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-223">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-224">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="2da05-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="2da05-225">Scripts ou codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="2da05-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="2da05-226">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="2da05-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="2da05-227">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="2da05-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="2da05-228">Limites de conformité et filtres de sécurité.</span><span class="sxs-lookup"><span data-stu-id="2da05-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="2da05-229">Enquêtes sur les données.</span><span class="sxs-lookup"><span data-stu-id="2da05-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="2da05-230">Demandes des personnes à l’objet de données.</span><span class="sxs-lookup"><span data-stu-id="2da05-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="2da05-231">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-232">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-233">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="2da05-234">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="2da05-235"><strong>Gestion des menaces internes</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="2da05-236">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="2da05-237">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="2da05-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="2da05-238">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="2da05-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="2da05-239">Créer des cas.</span><span class="sxs-lookup"><span data-stu-id="2da05-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="2da05-240">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="2da05-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="2da05-241">Recommandations sur la création du connecteur de ressources humaines (RH).</span><span class="sxs-lookup"><span data-stu-id="2da05-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="2da05-242">

<strong> Conformité des communications </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="2da05-243">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="2da05-244">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="2da05-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="2da05-245">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="2da05-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="2da05-246">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="2da05-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="2da05-247">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-248">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-249">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-250">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-251">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-252">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-253">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-254">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="2da05-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="2da05-255">Création et gestion des flux Power Automate.</span><span class="sxs-lookup"><span data-stu-id="2da05-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="2da05-256">Connecteurs de données (au-delà du connecteur RH).</span><span class="sxs-lookup"><span data-stu-id="2da05-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="2da05-257">Configurations d’expression régulière personnalisées (RegEx).</span><span class="sxs-lookup"><span data-stu-id="2da05-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="2da05-258">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-259">Obstacles à l’information.</span><span class="sxs-lookup"><span data-stu-id="2da05-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="2da05-260">Gestion des accès privilégiés.</span><span class="sxs-lookup"><span data-stu-id="2da05-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="2da05-261">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-262">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="2da05-263">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="2da05-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="2da05-265">Microsoft 365 Defender est une suite unifiée de défense d’entreprise avant et après la violation qui coordonne en natif la détection, la prévention, l’examen et la réponse entre les points de terminaison, les identités, le courrier électronique et les applications afin de fournir une protection intégrée contre les attaques sophistiquées.</span><span class="sxs-lookup"><span data-stu-id="2da05-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="2da05-266">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="2da05-267">Présentation du Centre de sécurité Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="2da05-268">Passer en revue les incidents entre produits, notamment en vous concentrant sur les éléments critiques en garantissant l’étendue complète des attaques, les ressources impactées et les actions de correction automatisées regroupées.</span><span class="sxs-lookup"><span data-stu-id="2da05-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="2da05-269">Démonstration de la façon dont Microsoft 365 Defender peut orchestrer l’examen des biens, des utilisateurs, des appareils et des boîtes aux lettres qui ont pu être compromis par le biais d’une auto-ressource automatisée.</span><span class="sxs-lookup"><span data-stu-id="2da05-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="2da05-270">Explication et fourniture d’exemples de la façon dont les clients peuvent chercher de manière proactive les tentatives d’intrusion et l’activité de violation affectant vos e-mails, données, appareils et comptes dans plusieurs ensembles de données.</span><span class="sxs-lookup"><span data-stu-id="2da05-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="2da05-271">Montrer aux clients comment ils peuvent examiner et améliorer leur posture de sécurité globalement à l’aide du Niveau de sécurité Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2da05-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="2da05-272"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="2da05-273">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="2da05-274">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="2da05-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="2da05-275">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="2da05-276">Comment corriger ou interpréter les différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="2da05-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="2da05-277">Comment examiner un utilisateur, un ordinateur, un chemin de mouvement latéral ou une entité.</span><span class="sxs-lookup"><span data-stu-id="2da05-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="2da05-278">Recherche de menace personnalisée.</span><span class="sxs-lookup"><span data-stu-id="2da05-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="2da05-279">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API.</span><span class="sxs-lookup"><span data-stu-id="2da05-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="2da05-281">Microsoft Cloud App Security est un service Broker de sécurité d’accès au cloud (CASB) qui offre une visibilité enrichie, un contrôle sur les déplacements de données et des analyses sophistiquées pour identifier et lutter contre les cybermenaces dans tous vos services cloud Microsoft et tiers.</span><span class="sxs-lookup"><span data-stu-id="2da05-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="2da05-282">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-283">Configuration du portail, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="2da05-284">Importation de groupes d’utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="2da05-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="2da05-285">Gestion de l’accès et des paramètres de l’administrateur.</span><span class="sxs-lookup"><span data-stu-id="2da05-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="2da05-286">Portée de votre déploiement pour sélectionner certains groupes d’utilisateurs à surveiller ou exclure de la surveillance.</span><span class="sxs-lookup"><span data-stu-id="2da05-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="2da05-287">Définition de plages IP et de balises.</span><span class="sxs-lookup"><span data-stu-id="2da05-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="2da05-288">Personnalisation de l’expérience utilisateur final avec votre logo et votre messagerie personnalisée.</span><span class="sxs-lookup"><span data-stu-id="2da05-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="2da05-289">Configuration de la découverte cloud pour fournir des services informatiques de l’ombre à l’aide des :</span><span class="sxs-lookup"><span data-stu-id="2da05-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="2da05-290">Microsoft Defender pour les points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="2da05-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="2da05-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="2da05-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="2da05-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="2da05-293">Connexion <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">d’applications featured à l’aide</a> de connecteurs d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="2da05-294">Configuration du contrôle d’application d’accès conditionnel dans les portails Accès conditionnel et Sécurité des applications cloud pour appliquer des contrôles de session en temps réel.</span><span class="sxs-lookup"><span data-stu-id="2da05-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="2da05-295">Déploiement des tableaux de bord Cloud App Security et Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="2da05-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="2da05-296">Personnalisation des scores de risque d’application en fonction des priorités de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="2da05-297">Création de balises et de catégories d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="2da05-298">Application de sanctions et d’inséance.</span><span class="sxs-lookup"><span data-stu-id="2da05-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="2da05-299">Utilisation des journaux d’activité et de fichiers.</span><span class="sxs-lookup"><span data-stu-id="2da05-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="2da05-300">Gestion des applications OAuth.</span><span class="sxs-lookup"><span data-stu-id="2da05-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="2da05-301">Comprendre la corrélation des incidents dans le portail Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="2da05-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="2da05-302">Fourniture d’une assistance à la configuration avec les 20 principaux cas d’utilisation pour les cas de base de données d’accès au détail (y compris la création ou la mise à jour de six (6) <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">stratégies),</a> sauf :</span><span class="sxs-lookup"><span data-stu-id="2da05-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="2da05-303">Audit de la configuration de vos environnements Internet en tant que service (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="2da05-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="2da05-304">Surveillance des activités des utilisateurs pour se protéger contre les menaces dans vos environnements IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="2da05-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="2da05-305"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="2da05-306">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="2da05-307">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="2da05-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="2da05-308">Configuration de l’infrastructure, de l’installation ou du déploiement des téléchargements automatiques de journaux pour les rapports continus à l’aide de Docker ou d’un collecteur de journaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="2da05-309">Pour <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">plus d’informations, consultez les 20 principaux cas d’utilisation</a> des cas d’analyse de cas d’analyse de cas.</span><span class="sxs-lookup"><span data-stu-id="2da05-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="2da05-310">Création d’un rapport instantané de découverte cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="2da05-311">Blocage de l’utilisation de l’application à l’aide de scripts de blocage.</span><span class="sxs-lookup"><span data-stu-id="2da05-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="2da05-312">Connexion d’applications personnalisées.</span><span class="sxs-lookup"><span data-stu-id="2da05-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="2da05-313">Intégration avec des fournisseurs d’identité tiers (ISP) et des fournisseurs de protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="2da05-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="2da05-314">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="2da05-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="2da05-315">Examen et correction automatisés, y compris les manuels Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="2da05-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="2da05-316">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="2da05-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="2da05-317">Déploiement de la découverte d’applications cloud comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="2da05-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="2da05-318"><strong>Microsoft Defender – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2da05-319">Microsoft Defender – Protection avancée contre les menaces est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter et examiner les menaces avancées et à y répondre.</span><span class="sxs-lookup"><span data-stu-id="2da05-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="2da05-320">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-321">Déploiement des technologies pour sécuriser vos points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="2da05-322">Configuration des profils de protection des points de terminaison et de restriction d’appareil.</span><span class="sxs-lookup"><span data-stu-id="2da05-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="2da05-323">Évaluation de la version du système d’exploitation et de la gestion des appareils (notamment Intune, Microsoft Endpoint Configuration Manager, objets de stratégie de groupe et configurations tierces), ainsi que l’état de vos services antivirus Windows Defender ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2da05-324">Évaluation de l’état de vos services Antivirus Windows ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2da05-325">Évaluation des proxies et des pare-feu limitant le trafic réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="2da05-326">Activation du service Microsoft Defender ATP en expliquant comment déployer un profil d’agent ATP à l’aide d’un point de terminaison intégré.</span><span class="sxs-lookup"><span data-stu-id="2da05-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="2da05-327">Conseils de déploiement, assistance à la configuration et formation sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-328">La gestion des menaces et des vulnérabilités.</span><span class="sxs-lookup"><span data-stu-id="2da05-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-329">La réduction de la surface d’attaque.</span><span class="sxs-lookup"><span data-stu-id="2da05-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-330">La nouvelle génération de protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-331">La détection de point de terminaison et réponse.</span><span class="sxs-lookup"><span data-stu-id="2da05-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-332">Les enquêtes et résolutions automatiques.</span><span class="sxs-lookup"><span data-stu-id="2da05-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-333">Le niveau de sécurité.</span><span class="sxs-lookup"><span data-stu-id="2da05-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-334">Examen des simulations et didacticiels (tels que les scénarios pratiques, les programmes malveillants factices et les enquêtes automatisées).</span><span class="sxs-lookup"><span data-stu-id="2da05-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="2da05-335">Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="2da05-336">L’intégration d’Office 365 – Protection avancée contre les menaces avec Microsoft Defender – Protection avancée contre les menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="2da05-337">Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="2da05-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="2da05-338">Les systèmes d’exploitation suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="2da05-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="2da05-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-342">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="2da05-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span><span class="sxs-lookup"><span data-stu-id="2da05-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-344">macOS versions 10.13, 10.14 et 10.15.</span><span class="sxs-lookup"><span data-stu-id="2da05-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="2da05-345">
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou Microsoft Endpoint Configuration Manager (version 2002 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="2da05-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="2da05-346"></li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-347">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="2da05-348">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="2da05-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="2da05-349">Gestion continue et réponse aux menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="2da05-350">Intégration ou configuration des agents Microsoft Defender - PACM suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-351">Windows Server 2008</span><span class="sxs-lookup"><span data-stu-id="2da05-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="2da05-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="2da05-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-354">Appareils mobiles (Android et iOS).</span><span class="sxs-lookup"><span data-stu-id="2da05-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="2da05-355">Infrastructure VDI (Virtual Desktop Infrastructure) (persistante ou non persistante).</span><span class="sxs-lookup"><span data-stu-id="2da05-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-356">Intégration et configuration du serveur :</span><span class="sxs-lookup"><span data-stu-id="2da05-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-357">Configuration d’un serveur proxy pour les communications hors connexion.</span><span class="sxs-lookup"><span data-stu-id="2da05-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-358">Configuration des packages de déploiement Configuration Manager sur les instances et versions de Configuration Manager de bas niveau.</span><span class="sxs-lookup"><span data-stu-id="2da05-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-359">Intégration de serveurs au Centre de sécurité Azure.</span><span class="sxs-lookup"><span data-stu-id="2da05-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-360">Serveurs non gérés par Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2da05-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-361">Intégration et configuration macOS :</span><span class="sxs-lookup"><span data-stu-id="2da05-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-362">Déploiement intune manuel.</span><span class="sxs-lookup"><span data-stu-id="2da05-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-363">Déploiement basé sur JAMF.</span><span class="sxs-lookup"><span data-stu-id="2da05-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="2da05-364">Autres déploiements basés sur des produits de gestion des périphériques mobiles (MDM).</span><span class="sxs-lookup"><span data-stu-id="2da05-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-365">Déploiement manuel.</span><span class="sxs-lookup"><span data-stu-id="2da05-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-366">Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :</span><span class="sxs-lookup"><span data-stu-id="2da05-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-367">Isolation basée sur le matériel.</span><span class="sxs-lookup"><span data-stu-id="2da05-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-368">Contrôle d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="2da05-369">Contrôle d’appareil.</span><span class="sxs-lookup"><span data-stu-id="2da05-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="2da05-370">Exploit Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-371">Pare-feu du réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="2da05-372">Configuration ou gestion des fonctionnalités de protection des comptes telles que :</span><span class="sxs-lookup"><span data-stu-id="2da05-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="2da05-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="2da05-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="2da05-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="2da05-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="2da05-375">Configuration ou gestion de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="2da05-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="2da05-376">Inscription ou configuration des Spécialistes des menaces Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2da05-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="2da05-377">Révision de la configuration ou de la formation sur les CONNEXIONS API ou informations de sécurité et de gestion des événements (SIEM).</span><span class="sxs-lookup"><span data-stu-id="2da05-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="2da05-378">Inscription ou configuration de la Protection Microsoft contre les menaces (MTP).</span><span class="sxs-lookup"><span data-stu-id="2da05-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="2da05-379">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="2da05-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="2da05-380">Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</span><span class="sxs-lookup"><span data-stu-id="2da05-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="2da05-381">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="2da05-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="2da05-382"><strong>Microsoft Defender pour l’identité </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="2da05-383">Microsoft Defender pour Identity est une solution de sécurité basée sur le cloud qui exploite vos signaux Active Directory sur site pour identifier, détecter et examiner les menaces avancées, les identités compromises et les actions des utilisateurs malveillants ciblant votre organisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="2da05-384">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="2da05-385">Création de votre instance de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="2da05-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="2da05-386">Connexion de Defender pour l’identité à Active Directory.</span><span class="sxs-lookup"><span data-stu-id="2da05-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="2da05-387">Évaluation de la préparation de votre environnement pour déployer le capteur Defender for Identity sur vos contrôleurs de domaine, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="2da05-388">Exécution de l’outil de taille pour la planification de la capacité des ressources.</span><span class="sxs-lookup"><span data-stu-id="2da05-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="2da05-389">Exécution de l’outil d’audit pour évaluer la compatibilité de vos contrôleurs de domaine avec le capteur.</span><span class="sxs-lookup"><span data-stu-id="2da05-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="2da05-390">Déploiement du capteur pour capturer et parer le trafic réseau et les événements Windows directement à partir de vos contrôleurs de domaine, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="2da05-391">Téléchargement du package de capteur.</span><span class="sxs-lookup"><span data-stu-id="2da05-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="2da05-392">Configuration du capteur.</span><span class="sxs-lookup"><span data-stu-id="2da05-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="2da05-393">Installation silencieuse du capteur sur votre contrôleur de domaine.</span><span class="sxs-lookup"><span data-stu-id="2da05-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="2da05-394">Déploiement du capteur dans votre environnement à forêts multiples.</span><span class="sxs-lookup"><span data-stu-id="2da05-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="2da05-395">Intégration de Defender for Identity à Microsoft Cloud App Security (la gestion des licences Cloud App Security n’est pas requise).</span><span class="sxs-lookup"><span data-stu-id="2da05-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="2da05-396">Fourniture d’instructions de déploiement, d’assistance à la configuration et de formation sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="2da05-397">Réglage de l’environnement pour réduire le « bruit ».</span><span class="sxs-lookup"><span data-stu-id="2da05-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="2da05-398">Comprendre le rapport d’évaluation de la sécurité des identités.</span><span class="sxs-lookup"><span data-stu-id="2da05-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="2da05-399">Comprendre le score de priorité d’examen de l’utilisateur et le rapport de classement de l’examen utilisateur.</span><span class="sxs-lookup"><span data-stu-id="2da05-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="2da05-400">Comprendre le rapport de l’utilisateur inactif.</span><span class="sxs-lookup"><span data-stu-id="2da05-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="2da05-401">Fourniture d’options de correction sur un compte compromis.</span><span class="sxs-lookup"><span data-stu-id="2da05-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="2da05-402">Faciliter la migration de Advanced Threat Analytics (ATA) vers Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="2da05-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="2da05-403"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="2da05-404">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="2da05-405">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="2da05-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="2da05-406">Déploiement du capteur Defender pour l’identité, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="2da05-407">Planification manuelle de la capacité.</span><span class="sxs-lookup"><span data-stu-id="2da05-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="2da05-408">Déploiement du capteur dans une capacité autonome.</span><span class="sxs-lookup"><span data-stu-id="2da05-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="2da05-409">Déploiement du capteur à l’aide d’un adaptateur d’équipe carte d’interface réseau (NIC).</span><span class="sxs-lookup"><span data-stu-id="2da05-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="2da05-410">Déploiement du capteur via un outil tiers.</span><span class="sxs-lookup"><span data-stu-id="2da05-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="2da05-411">Connexion au service cloud Defender for Identity via une connexion proxy web.</span><span class="sxs-lookup"><span data-stu-id="2da05-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="2da05-412">Création et gestion de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="2da05-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="2da05-413">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="2da05-414">Correction ou interprétation de différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="2da05-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="2da05-415">Recherche d’un utilisateur, d’un ordinateur, d’un chemin de mouvement latéral ou d’une entité.</span><span class="sxs-lookup"><span data-stu-id="2da05-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="2da05-416">Menace ou recherche avancée.</span><span class="sxs-lookup"><span data-stu-id="2da05-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="2da05-417">Réponse aux incidents.</span><span class="sxs-lookup"><span data-stu-id="2da05-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="2da05-418">Fourniture d’un didacticiel de laboratoire d’alertes de sécurité pour Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="2da05-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="2da05-419">Envoi d’une notification lorsque Defender pour l’identité détecte des activités suspectes en envoyant des alertes de sécurité à votre serveur syslog via un capteur désigné.</span><span class="sxs-lookup"><span data-stu-id="2da05-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="2da05-420">Configuration de Defender for Identity pour effectuer des requêtes à l’aide du protocole SAMR (Security Account Manager remote) pour identifier les administrateurs locaux sur des ordinateurs spécifiques.</span><span class="sxs-lookup"><span data-stu-id="2da05-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="2da05-421">Configuration de solutions VPN pour ajouter des informations à partir de la connexion VPN à la page de profil d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="2da05-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="2da05-422">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="2da05-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="2da05-423">Déploiement des capteurs Defender for Identity comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="2da05-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2da05-424">Active Directory déployé.</span><span class="sxs-lookup"><span data-stu-id="2da05-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="2da05-425">Les contrôleurs de domaine sur qui vous avez l’intention d’installer les capteurs Defender for Identity ont une connectivité Internet au service cloud de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="2da05-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="2da05-426">Votre pare-feu et votre proxy doivent être ouverts pour communiquer avec le service cloud Defender for Identity (\*.atp.azure.com port 443 doit être ouvert).</span><span class="sxs-lookup"><span data-stu-id="2da05-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="2da05-427">Contrôleurs de domaine en cours d’exécution sur l’une des suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="2da05-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="2da05-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="2da05-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="2da05-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="2da05-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="2da05-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="2da05-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="2da05-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="2da05-432">Windows Server 2019 avec KB4487044 (build de système d’exploitation 17763.316).</span><span class="sxs-lookup"><span data-stu-id="2da05-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="2da05-433"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="2da05-434">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-435">Création et publication d’étiquettes et de stratégies de rétention (uniquement pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="2da05-436">Gestion des enregistrements (uniquement prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="2da05-437">Examen de la création d’un plan de fichiers.</span><span class="sxs-lookup"><span data-stu-id="2da05-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="2da05-438">Création et gestion des enregistrements (y compris les enregistrements basés sur des événements).</span><span class="sxs-lookup"><span data-stu-id="2da05-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="2da05-439">Révision de la disposition.</span><span class="sxs-lookup"><span data-stu-id="2da05-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="2da05-440">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-441">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-442">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-443">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-444">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-445">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-446">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-447">

  <strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="2da05-448">Développement d’un plan de gestion des fichiers de gestion des enregistrements.</span><span class="sxs-lookup"><span data-stu-id="2da05-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="2da05-449">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="2da05-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="2da05-450">Développement de l’architecture des informations dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2da05-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="2da05-451">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="2da05-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="2da05-452">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-453">Prise en charge de l’E3.</span><span class="sxs-lookup"><span data-stu-id="2da05-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="2da05-454">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-455">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="2da05-456">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-457"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="2da05-458">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-459">Classification des données (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-460">Types d’informations sensibles (pris en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-461">Création d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-462">Application d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-463">Classifieurs entra nessables (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-464">Connaissance de vos données avec l’Explorateur de contenu et l’Explorateur d’activités (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-465">Publication d’étiquettes à l’aide de stratégies (manuelles et automatiques) (prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-466">Création de stratégies de protection contre la perte de données (DLP) de point de terminaison pour les appareils Windows 10 (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-467">Création de stratégies DLP pour les conversations et les canaux Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="2da05-468">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-469">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-470">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-471">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-472">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-473">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-474">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-475">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="2da05-476">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-477">Activation et configuration de votre client.</span><span class="sxs-lookup"><span data-stu-id="2da05-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="2da05-478">Création et configuration d’étiquettes et de stratégies (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-479">Application de la protection des informations aux documents (prise en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-480">Classification et étiquetage automatiques des informations dans les applications Office (comme Word, PowerPoint, Excel et Outlook) en cours d’exécution sur Windows et à l’aide du client Azure Information Protection (pris en charge dans P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-481">Découverte et étiquetage des fichiers au repos à l’aide du scanneur Azure Information Protection (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-482">Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="2da05-483">Nous fournissons également des conseils si vous souhaitez appliquer une protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="2da05-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="2da05-484"><strong>Ce qui suit est hors de portée </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="2da05-485">Clé client.</span><span class="sxs-lookup"><span data-stu-id="2da05-485">Customer key.</span></span></li>
<li><span data-ttu-id="2da05-486">Développement d’expressions régulières personnalisées (RegEx) pour les types d’informations sensibles.</span><span class="sxs-lookup"><span data-stu-id="2da05-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="2da05-487">Création ou modification de dictionnaires de mots clés.</span><span class="sxs-lookup"><span data-stu-id="2da05-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="2da05-488">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="2da05-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="2da05-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="2da05-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="2da05-490">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-491">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-492">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="2da05-493">En dehors <strong>de la partie</strong> Intégration de base en <a href="#general">général,</a>il n’existe aucune exigence système minimale à l’exception d’Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="2da05-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="2da05-495">Les responsabilités préalables du client sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-496">Liste des emplacements de partage de fichiers à scanner.</span><span class="sxs-lookup"><span data-stu-id="2da05-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="2da05-497">Taxonomie de classification approuvée.</span><span class="sxs-lookup"><span data-stu-id="2da05-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="2da05-498">Comprendre les restrictions ou exigences réglementaires relatives à la gestion des clés.</span><span class="sxs-lookup"><span data-stu-id="2da05-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-499">Un compte de service créé pour votre annuaire Active Directory local qui a été synchronisé avec Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="2da05-500">Étiquettes configurées pour la classification et la protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="2da05-501">Toutes les conditions préalables pour le scanneur Azure Information Protection sont en place.</span><span class="sxs-lookup"><span data-stu-id="2da05-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="2da05-502">Pour plus d’informations, voir Conditions préalables à l’installation et au déploiement du scanneur d’étiquetage unifié <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="2da05-503">Assurez-vous que les appareils utilisateur exécutent un système d’exploitation pris en charge et que les conditions préalables nécessaires sont installées.</span><span class="sxs-lookup"><span data-stu-id="2da05-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="2da05-504">Pour plus d’informations, voir les informations suivantes.</span><span class="sxs-lookup"><span data-stu-id="2da05-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="2da05-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guide d’administration : Installer le client d’étiquetage unifié Azure Information Protection pour les utilisateurs</a>   </span><span class="sxs-lookup"><span data-stu-id="2da05-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="2da05-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Qu’est-ce que l’application Azure Information Protection pour iOS ou Android ?</a>  </span><span class="sxs-lookup"><span data-stu-id="2da05-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="2da05-507">Installation et configuration du connecteur et des serveurs Azure RMS, y compris le connecteur AD RMS (Active Directory RMS) pour la prise en charge hybride.</span><span class="sxs-lookup"><span data-stu-id="2da05-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="2da05-508">Si vous avez besoin de l’une de ces options pour votre déploiement, vous devez installer et configurer Bring Your Own Key (BYOK), DKE (Double Key Encryption) (client d’étiquetage unifié uniquement) ou Hold Your Own Key (HYOK) (client classique uniquement).</span><span class="sxs-lookup"><span data-stu-id="2da05-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="2da05-510">Nous fournissons des conseils à distance sur la préparation à l’utilisation d’Intune en tant que fournisseur de gestion des périphériques mobiles (MDM) et de gestion des applications mobiles (MAM) dans le cloud pour vos applications et appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="2da05-511">Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="2da05-512">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-513">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2da05-514">Configuration des identités à utiliser par Intune en tirant parti de vos identités Active Directory locales ou cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="2da05-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="2da05-515">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-516">Configuration de votre autorité de gestion des projets, en fonction de vos besoins en matière de gestion, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-517">Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-518">Recommandations en matière de gestion des appareils mobiles pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-519">Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-520">Configuration des stratégies de gestion et des services de gestion du service MDM tels que :</span><span class="sxs-lookup"><span data-stu-id="2da05-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-521">Déploiement d’application pour chaque plateforme prise en charge par le biais de liens web ou de liens profonds.</span><span class="sxs-lookup"><span data-stu-id="2da05-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="2da05-522">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-523">Déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous avez une autorité de certification, un réseau sans fil ou une infrastructure VPN existante dans votre organisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="2da05-524">Connexion à l’entrepôt de données Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="2da05-525">Intégration de Intune avec :</span><span class="sxs-lookup"><span data-stu-id="2da05-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-526">Visionneuse d’équipe pour l’assistance à distance (un abonnement Team Viewer est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2da05-527">Solutions de partenaires de protection contre les menaces mobiles (MTD) (un abonnement MTD est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2da05-528">Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="2da05-529">Inscription de périphériques de chaque plateforme prise en charge sur Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="2da05-530">Fournir des conseils sur la protection des applications sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-531">Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.</span><span class="sxs-lookup"><span data-stu-id="2da05-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="2da05-532">Configuration des stratégies d’accès conditionnel pour les applications gérées.</span><span class="sxs-lookup"><span data-stu-id="2da05-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="2da05-533">Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées précédemment.</span><span class="sxs-lookup"><span data-stu-id="2da05-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-534">Utilisation des rapports d’utilisation des applications gérées.</span><span class="sxs-lookup"><span data-stu-id="2da05-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-535">Fourniture de conseils de migration de la gestion des PC hérités vers la gestion des systèmes de gestion Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="2da05-536">
 
</li>
</ul>
  
<strong>Attachement via le cloud</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="2da05-537">Nous vous guidons tout au long de la préparation à l’attachement dans le cloud des environnements Configuration Manager existants avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="2da05-538">Les étapes exactes dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="2da05-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="2da05-539">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-540">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2da05-541">Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="2da05-542">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-543">Fourniture de conseils pour la configuration hybride de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2da05-544">Fourniture de conseils sur la configuration d’Azure AD pour l’inscription automatique À la gestion des paramètres de gestion des logiciels.</span><span class="sxs-lookup"><span data-stu-id="2da05-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-545">Fourniture d’instructions sur la façon de configurer la passerelle de gestion cloud lorsqu’elle est utilisée comme solution pour la cogestion de la gestion des appareils basés sur Internet à distance.</span><span class="sxs-lookup"><span data-stu-id="2da05-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-546">Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="2da05-547">Installation du client Configuration Manager dans les appareils inscrits sur Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="2da05-548"><strong>Déployer Outlook Mobile pour iOS et Android en toute sécurité</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook Mobile pour iOS et Android en toute sécurité dans votre organisation afin de vous assurer que toutes les applications requises sont installées pour vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="2da05-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="2da05-549">La procédure de déploiement sécurisé d’Outlook Mobile pour iOS et Android avec Intune dépend de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="2da05-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="2da05-550">Il peut inclure les suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-551">Téléchargement des applications Outlook pour iOS et Android, Microsoft Authenticator et le portail d’entreprise Intune via l’App Store d’Apple ou Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="2da05-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="2da05-552">Fourniture d’instructions sur la configuration :</span><span class="sxs-lookup"><span data-stu-id="2da05-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-553">Déploiement d’applications Outlook pour iOS et Android, Microsoft Authenticator et portail d’entreprise Intune avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="2da05-554">Stratégies de protection des applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-555">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-556">Stratégies de configuration d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="2da05-557">Les administrateurs informatiques doivent avoir une autorité de certification, un réseau sans fil et des infrastructures VPN existants qui fonctionnent déjà dans leurs environnements de production lors de la planification du déploiement de réseau sans fil et de profils VPN avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="2da05-558"><strong>Remarque</strong>: l’avantage du service FastTrack n’inclut pas d’assistance pour la configuration des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats Push Apple MDM pour Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="2da05-559"><strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="2da05-560">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="2da05-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="2da05-561"><strong>Intune intégré avec Microsoft Defender - Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="2da05-562"><strong>Remarque</strong>: nous fournissons de l’aide sur l’intégration d’Intune à Microsoft Defender ATP et la création de stratégies de conformité des appareils en fonction de son évaluation du niveau de risque Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="2da05-563">Nous ne fournissons pas d’aide sur les achats, les licences ou l’activation.</span><span class="sxs-lookup"><span data-stu-id="2da05-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="2da05-564">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="2da05-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="2da05-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="2da05-566">Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.</span><span class="sxs-lookup"><span data-stu-id="2da05-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="2da05-567"><strong>Office 365 – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2da05-568">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-569">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="2da05-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="2da05-570">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="2da05-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="2da05-571">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="2da05-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="2da05-572">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-573">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="2da05-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="2da05-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-575"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-576"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-577"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2da05-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="2da05-579">Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique.</span><span class="sxs-lookup"><span data-stu-id="2da05-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="2da05-580">Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.</span><span class="sxs-lookup"><span data-stu-id="2da05-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="2da05-581">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-582">La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-583">Pointage de vos enregistrements MX (mail exchange) vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-584">Configuration de la fonctionnalité Office 365 ATP si elle fait partie de votre service d’abonnement.</span><span class="sxs-lookup"><span data-stu-id="2da05-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="2da05-585">Pour plus d’informations, voir la partie <strong>Office 365 - Protection</strong> avancée contre les menaces de ce tableau.</span><span class="sxs-lookup"><span data-stu-id="2da05-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="2da05-p127">La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="2da05-p128">La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="2da05-590">
  <strong>Remarque :</strong> Le service de réplication de boîtes aux lettres (MRS) tente de migrer des messages électroniques gérés par des droits d’information (IRM) de votre boîte aux lettres sur site vers la boîte aux lettres Exchange Online correspondante.</span><span class="sxs-lookup"><span data-stu-id="2da05-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="2da05-591">La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="2da05-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-592">La configuration de ports de pare-feu.</span><span class="sxs-lookup"><span data-stu-id="2da05-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2da05-593">Configuration du DNS, y compris les enregistrements DMARC (Autodiscover, Sender Policy Framework) requis, DKIM (DomainKeys Identified Mail), DMARC (Domain-based Message Authentication, Reporting and Conformance) et MX (selon vos besoins).</span><span class="sxs-lookup"><span data-stu-id="2da05-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="2da05-594">la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).</span><span class="sxs-lookup"><span data-stu-id="2da05-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="2da05-595">La migration de messagerie de votre environnement de messagerie source vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-596">La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="2da05-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="2da05-597">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="2da05-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="2da05-598">Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="https://docs.microsoft.com/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="2da05-599">Votre environnement source doit avoir l’un des niveaux minimaux suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-600">Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.</span><span class="sxs-lookup"><span data-stu-id="2da05-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="2da05-601">Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.</span><span class="sxs-lookup"><span data-stu-id="2da05-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-602">Environnement G Suite unique (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="2da05-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="2da05-603">Pour plus d’informations sur les fonctionnalités multigé géographiques, voir <a href="https://go.microsoft.com/fwlink/?linkid=872776">Fonctionnalités multigéo géographiques dans Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="2da05-604">Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive Entreprise, Power BI Desktop et Skype Entreprise doivent se trouver à un niveau minimal tel que défini dans la version système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-605"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="2da05-606">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-607">Création et publication d’étiquettes et de stratégies de rétention (uniquement pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="2da05-608">Gestion des enregistrements (uniquement prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="2da05-609">Examen de la création d’un plan de fichiers.</span><span class="sxs-lookup"><span data-stu-id="2da05-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="2da05-610">Création et gestion des enregistrements (y compris les enregistrements basés sur des événements).</span><span class="sxs-lookup"><span data-stu-id="2da05-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="2da05-611">Révision de la disposition.</span><span class="sxs-lookup"><span data-stu-id="2da05-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="2da05-612">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-613">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-614">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-615">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-616">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-617">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-618">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-619">

  <strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="2da05-620">Développement d’un plan de gestion des fichiers de gestion des enregistrements.</span><span class="sxs-lookup"><span data-stu-id="2da05-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="2da05-621">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="2da05-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="2da05-622">Développement de l’architecture des informations dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2da05-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="2da05-623">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="2da05-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="2da05-624">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-625">Prise en charge de l’E3.</span><span class="sxs-lookup"><span data-stu-id="2da05-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="2da05-626">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-627">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="2da05-628">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-629"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="2da05-630">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-631">Classification des données (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-632">Types d’informations sensibles (pris en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-633">Création d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-634">Application d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-635">Classifieurs entra nessables (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-636">Connaissance de vos données avec l’Explorateur de contenu et l’Explorateur d’activités (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-637">Publication d’étiquettes à l’aide de stratégies (manuelles et automatiques) (prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-638">Création de stratégies de protection contre la perte de données (DLP) de point de terminaison pour les appareils Windows 10 (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="2da05-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="2da05-639">Création de stratégies DLP pour les conversations et les canaux Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="2da05-640">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="2da05-641">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="2da05-642">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="2da05-643">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="2da05-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="2da05-644">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="2da05-645">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="2da05-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="2da05-646">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="2da05-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="2da05-647">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="2da05-648">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-649">Activation et configuration de votre client.</span><span class="sxs-lookup"><span data-stu-id="2da05-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="2da05-650">Création et configuration d’étiquettes et de stratégies (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-651">Application de la protection des informations aux documents (prise en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-652">Classification et étiquetage automatiques des informations dans les applications Office (comme Word, PowerPoint, Excel et Outlook) en cours d’exécution sur Windows et à l’aide du client Azure Information Protection (pris en charge dans P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-653">Découverte et étiquetage des fichiers au repos à l’aide du scanneur Azure Information Protection (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="2da05-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="2da05-654">Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="2da05-655">Nous fournissons également des conseils si vous souhaitez appliquer une protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="2da05-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="2da05-656"><strong>Ce qui suit est hors de portée </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="2da05-657">Clé client.</span><span class="sxs-lookup"><span data-stu-id="2da05-657">Customer key.</span></span></li>
<li><span data-ttu-id="2da05-658">Développement d’expressions régulières personnalisées (RegEx) pour les types d’informations sensibles.</span><span class="sxs-lookup"><span data-stu-id="2da05-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="2da05-659">Création ou modification de dictionnaires de mots clés.</span><span class="sxs-lookup"><span data-stu-id="2da05-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="2da05-660">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="2da05-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="2da05-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="2da05-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="2da05-662">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="2da05-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="2da05-663">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="2da05-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="2da05-664">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="2da05-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="2da05-665">En dehors <strong>de la partie</strong> Intégration de base en <a href="#general">général,</a>il n’existe aucune exigence système minimale à l’exception d’Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="2da05-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="2da05-667">Les responsabilités préalables du client sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-668">Liste des emplacements de partage de fichiers à scanner.</span><span class="sxs-lookup"><span data-stu-id="2da05-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="2da05-669">Taxonomie de classification approuvée.</span><span class="sxs-lookup"><span data-stu-id="2da05-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="2da05-670">Comprendre les restrictions ou exigences réglementaires relatives à la gestion des clés.</span><span class="sxs-lookup"><span data-stu-id="2da05-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-671">Un compte de service créé pour votre annuaire Active Directory local qui a été synchronisé avec Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="2da05-672">Étiquettes configurées pour la classification et la protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="2da05-673">Toutes les conditions préalables pour le scanneur Azure Information Protection sont en place.</span><span class="sxs-lookup"><span data-stu-id="2da05-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="2da05-674">Pour plus d’informations, voir Conditions préalables à l’installation et au déploiement du scanneur d’étiquetage unifié <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="2da05-675">Assurez-vous que les appareils utilisateur exécutent un système d’exploitation pris en charge et que les conditions préalables nécessaires sont installées.</span><span class="sxs-lookup"><span data-stu-id="2da05-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="2da05-676">Pour plus d’informations, voir les informations suivantes.</span><span class="sxs-lookup"><span data-stu-id="2da05-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="2da05-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guide d’administration : Installer le client d’étiquetage unifié Azure Information Protection pour les utilisateurs</a>   </span><span class="sxs-lookup"><span data-stu-id="2da05-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="2da05-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Qu’est-ce que l’application Azure Information Protection pour iOS ou Android ?</a>  </span><span class="sxs-lookup"><span data-stu-id="2da05-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="2da05-679">Installation et configuration du connecteur et des serveurs Azure RMS, y compris le connecteur AD RMS (Active Directory RMS) pour la prise en charge hybride.</span><span class="sxs-lookup"><span data-stu-id="2da05-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="2da05-680">Si vous avez besoin de l’une de ces options pour votre déploiement, vous devez installer et configurer Bring Your Own Key (BYOK), DKE (Double Key Encryption) (client d’étiquetage unifié uniquement) ou Hold Your Own Key (HYOK) (client classique uniquement).</span><span class="sxs-lookup"><span data-stu-id="2da05-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="2da05-682">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-683">Confirmation de la demande minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour prendre en charge Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="2da05-684">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="2da05-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2da05-685">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="2da05-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="2da05-686">Confirmation que Teams est activé sur votre client Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="2da05-687">Activation ou désactivation des licences utilisateur.</span><span class="sxs-lookup"><span data-stu-id="2da05-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="2da05-688">Évaluation du réseau pour Teams :</span><span class="sxs-lookup"><span data-stu-id="2da05-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-689">Vérifications des ports et des points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="2da05-690">Contrôles de la qualité de connexion.</span><span class="sxs-lookup"><span data-stu-id="2da05-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="2da05-691">Estimations de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="2da05-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="2da05-692">Configuration de la stratégie d’application Teams (application web Teams, application de bureau Teams et application Teams pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="2da05-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="2da05-693">Le cas échéant, nous fournissons également des conseils pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-694">Appareils de salle Microsoft Teams :</span><span class="sxs-lookup"><span data-stu-id="2da05-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="2da05-695">Création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge répertoriés dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="2da05-696">Assistance à distance avec la configuration côté service des appareils de salles Microsoft Teams certifiés.</span><span class="sxs-lookup"><span data-stu-id="2da05-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="2da05-697">Activation de l’audioconférence :</span><span class="sxs-lookup"><span data-stu-id="2da05-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="2da05-698">Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.</span><span class="sxs-lookup"><span data-stu-id="2da05-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="2da05-699">Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="2da05-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="2da05-700">Système téléphonique :</span><span class="sxs-lookup"><span data-stu-id="2da05-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-701">Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="2da05-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="2da05-702">Conseils sur les forfaits d’appels<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(marchés disponibles)</a>:</span><span class="sxs-lookup"><span data-stu-id="2da05-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="2da05-703">Affectation de numéros aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="2da05-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="2da05-704">Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.</span><span class="sxs-lookup"><span data-stu-id="2da05-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="2da05-705">Prise en charge des demandes de service de portage de numéro local au-delà de 999.</span><span class="sxs-lookup"><span data-stu-id="2da05-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-706">Conseils de routage direct :</span><span class="sxs-lookup"><span data-stu-id="2da05-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-707">Conseils de configuration de l’organisation pour la conception du routage direct des scénarios hébergés par des partenaires ou des scénarios déployés par le client pour un nombre de sites au plus de 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="2da05-708">Révision de la configuration du contrôleur de frontière de session (SBC).</span><span class="sxs-lookup"><span data-stu-id="2da05-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="2da05-709">Assistance à distance avec la configuration du plan de numérotation.</span><span class="sxs-lookup"><span data-stu-id="2da05-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="2da05-710">Configuration de l’itinéraire des voix.</span><span class="sxs-lookup"><span data-stu-id="2da05-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="2da05-711">Contournement de média et optimisation des médias locaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="2da05-712">Activation des événements en direct Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="2da05-713">Configuration de l’organisation et intégration à Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="2da05-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="2da05-714">Conseils pour la transition de Skype Entreprise vers Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2da05-715">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-716">Utilisateurs activés pour SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="2da05-717">Les boîtes aux lettres Exchange sont présentes (en ligne et en local dans une configuration hybride Exchange).</span><span class="sxs-lookup"><span data-stu-id="2da05-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="2da05-718">Activation pour les groupes Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="2da05-719">
  <strong>Remarque :</strong> Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas de stockage OneDrive Entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="2da05-720">Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans des conversations sans stockage OneDrive Entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="2da05-721">Teams ne prend pas en charge SharePoint en local.</span><span class="sxs-lookup"><span data-stu-id="2da05-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="2da05-722">
  <strong>Remarque :</strong> L’état idéal est que tous les utilisateurs ont leurs boîtes aux lettres sur Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="2da05-723">Les utilisateurs avec des boîtes aux lettres locales doivent avoir leur identité synchronisée avec l’annuaire Office 365 via Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="2da05-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="2da05-724">Pour ces clients Exchange hybrides, si la boîte aux lettres de l’utilisateur est en local, l’utilisateur ne peut ni ajouter ni configurer de connecteurs.</span><span class="sxs-lookup"><span data-stu-id="2da05-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="2da05-725">Les programmes d’installation pour les clients de bureau Microsoft Teams Windows et Mac peuvent être téléchargés sur <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-726"><strong>Office 365 – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2da05-727">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-728">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="2da05-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="2da05-729">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="2da05-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="2da05-730">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="2da05-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="2da05-731">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-732">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="2da05-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-733"><strong>Outlook pour iOS et Android</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="2da05-734">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-735">Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.</span><span class="sxs-lookup"><span data-stu-id="2da05-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="2da05-736">Configuration des comptes et accès à la boîte aux lettres Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="2da05-737">Sécurisation d’Outlook Mobile (voir <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sécurisation d’Outlook pour iOS</a> et Android dans Exchange Online pour plus d’informations).</span><span class="sxs-lookup"><span data-stu-id="2da05-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2da05-738">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-739">Exchange Online configuré et licences attribuées.</span><span class="sxs-lookup"><span data-stu-id="2da05-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="2da05-741">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-742">Attribution de licences Power BI.</span><span class="sxs-lookup"><span data-stu-id="2da05-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="2da05-743">Déploiement de l'application Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-744">Les logiciels clients en ligne tels que Power BI Desktop doivent être à un niveau minimal tel que défini dans la version système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 et Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="2da05-746">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-747">la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;</span><span class="sxs-lookup"><span data-stu-id="2da05-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="2da05-748">l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;</span><span class="sxs-lookup"><span data-stu-id="2da05-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="2da05-749">la configuration de la liste des ressources d’entreprise (ERP) ;</span><span class="sxs-lookup"><span data-stu-id="2da05-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="2da05-750">la création de votre premier projet.</span><span class="sxs-lookup"><span data-stu-id="2da05-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-751">Les logiciels clients en ligne tels que Project pour Office 365 doivent être à un niveau minimal tel que défini dans la norme système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 et Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-752"><strong>Project Online Professionnel et Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="2da05-753">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-754">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="2da05-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="2da05-755">Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="2da05-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="2da05-756">Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="2da05-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="2da05-757">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2da05-758">Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2da05-759">Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="2da05-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-760">Les logiciels clients en ligne tels que Project pour Office 365 doivent être à un niveau minimal tel que défini dans la norme système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 et Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-761"><strong>SharePoint Online et OneDrive Entreprise</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="2da05-762">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-763">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="2da05-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="2da05-764">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="2da05-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2da05-765">la mise en service des utilisateurs et des licences ;</span><span class="sxs-lookup"><span data-stu-id="2da05-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="2da05-766">l'activation de la création de sites pour votre administrateur SharePoint Online ;</span><span class="sxs-lookup"><span data-stu-id="2da05-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="2da05-767">la planification des collections de sites ;</span><span class="sxs-lookup"><span data-stu-id="2da05-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="2da05-768">la sécurisation du contenu et la gestion des autorisations ;</span><span class="sxs-lookup"><span data-stu-id="2da05-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="2da05-769">la configuration des fonctionnalités SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2da05-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="2da05-770">la configuration des fonctionnalités Environnement hybride SharePoint, telles que la recherche hybride, les sites hybrides, la taxonomie hybride, les types de contenu, la création de sites en libre-service hybride (SharePoint Server 2013 uniquement), le lanceur d’applications étendu, OneDrive Entreprise hybride et les sites extranet.</span><span class="sxs-lookup"><span data-stu-id="2da05-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="2da05-771">Votre approche de migration.</span><span class="sxs-lookup"><span data-stu-id="2da05-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="2da05-772">Des conseils supplémentaires sont fournis pour OneDrive Entreprise en fonction de votre version de SharePoint, par exemple :</span><span class="sxs-lookup"><span data-stu-id="2da05-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-773">Identification des options d’intégration et examen de l’infrastructure réseau locale et en ligne et de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="2da05-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="2da05-774">Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et mise en œuvre des exigences de synchronisation et d’identité, et identification de votre client de synchronisation OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="2da05-775">Planification et mise en œuvre d’un déploiement unique pour tous les utilisateurs (ou d’un déploiement par phases).</span><span class="sxs-lookup"><span data-stu-id="2da05-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="2da05-776">Attribution de licences, redirection des sites Mon site et des bibliothèques de documents personnels vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="2da05-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="2da05-777">Redirection ou déplacement de dossiers connus vers OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2da05-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="2da05-778">Déploiement de la synchronisation du client OneDrive Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="2da05-779">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="2da05-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="2da05-780">Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="https://docs.microsoft.com/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="2da05-781"><strong>Pour SharePoint hybride :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-782">La configuration hybride de SharePoint inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, OneDrive Entreprise, un lanceur d’applications étendu, des sites extranet et la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.</span><span class="sxs-lookup"><span data-stu-id="2da05-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="2da05-783">
  <strong>Remarque :</strong> La création de sites libre-service n’est pas limitée aux serveurs locaux exécutant SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="2da05-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-784">Pour activer SharePoint hybride, vous devez avoir l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.</span><span class="sxs-lookup"><span data-stu-id="2da05-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="2da05-785">
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue.</span><span class="sxs-lookup"><span data-stu-id="2da05-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="2da05-786">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide.</span><span class="sxs-lookup"><span data-stu-id="2da05-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="2da05-787">Pour plus d’informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=853548">Niveaux de mise à jour publique minimale pour les fonctionnalités hybrides SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="2da05-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="2da05-788">
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigé géographiques, voir Fonctionnalités multigé géographiques dans OneDrive et <a href="https://go.microsoft.com/fwlink/?linkid=831056">SharePoint Online dans Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="2da05-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="2da05-790">Nous fournissons des conseils à distance pour l’activation Yammer service Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="2da05-791">Les logiciels clients en ligne doivent être au niveau minimal défini dans la version système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 et Office.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="2da05-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="2da05-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-793"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-794"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-795"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2da05-796"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="2da05-797">Nous fournissons des conseils à distance pour la sécurisation de vos identités cloud pour les scénarios suivants.</span><span class="sxs-lookup"><span data-stu-id="2da05-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="2da05-798">

<strong>Infrastructure de base sécurisée</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="2da05-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="2da05-799">La configuration et l’activation d’une authentification forte pour vos identités, notamment la protection avec Azure Multi-Factor Authentication (MFA) (cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et la réinitialisation de mot de passe libre-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="2da05-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="2da05-800">Pour les clients autres qu’Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.</span><span class="sxs-lookup"><span data-stu-id="2da05-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="2da05-801">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec l’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="2da05-802">Détection et blocage de l’utilisation de mots de passe faibles avec Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="2da05-803">Sécurisation de l’accès à distance aux applications web sur site avec le proxy d’application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="2da05-804">Activation de la détection et de la correction basées sur les risques avec Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="2da05-805">Activation d’un écran de personnalisation, y compris le logo, le texte et les images avec une personnalisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="2da05-806">Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="2da05-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="2da05-807">Gestion de l’accès pour vos administrateurs Office 365 à l’aide des rôles d’administration intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateur privilégiés.</span><span class="sxs-lookup"><span data-stu-id="2da05-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="2da05-808">Configuration de la jointation Azure AD hybride.</span><span class="sxs-lookup"><span data-stu-id="2da05-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2da05-809">Configuration de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="2da05-810">
  
<strong>Surveiller et signaler</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-811">Activation de la surveillance à distance pour les services AD FS, Azure AD Connect et les contrôleurs de domaine avec Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="2da05-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-812">
  
<strong>Gouvernance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-813">Gestion de votre cycle de vie d’accès et d’identité Azure AD à grande échelle avec la gestion des droits Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="2da05-814">Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions d’accès Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-815">Examen des conditions d’utilisation d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-816">Gestion et contrôle de l’accès aux comptes d’administrateur privilégiés avec Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="2da05-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-817">
  
<strong>Automatisation et efficacité </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-818">Activation d’Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="2da05-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="2da05-819">Permettre aux utilisateurs de créer et de gérer leur propre sécurité cloud ou groupes Office 365 avec la gestion de groupes en libre-service Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-820">Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-821">Activation des groupes dynamiques Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-822">Organisation des applications dans le portail Mes applications à l’aide de collections.</span><span class="sxs-lookup"><span data-stu-id="2da05-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2da05-823">Active Directory local et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="2da05-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2da05-824"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="2da05-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="2da05-825">Pour plus d’informations sur Azure Information Protection, voir <strong>Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Compliance.</span><span class="sxs-lookup"><span data-stu-id="2da05-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="2da05-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="2da05-827">Nous fournissons des conseils à distance sur la préparation à l’utilisation d’Intune en tant que fournisseur de gestion des périphériques mobiles (MDM) et de gestion des applications mobiles (MAM) dans le cloud pour vos applications et appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="2da05-828">Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="2da05-829">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-830">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2da05-831">Configuration des identités à utiliser par Intune en tirant parti de vos identités Active Directory locales ou cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="2da05-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="2da05-832">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-833">Configuration de votre autorité de gestion des projets, en fonction de vos besoins en matière de gestion, notamment :</span><span class="sxs-lookup"><span data-stu-id="2da05-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-834">Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-835">Recommandations en matière de gestion des appareils mobiles pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-836">Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.</span><span class="sxs-lookup"><span data-stu-id="2da05-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-837">Configuration des stratégies de gestion et des services de gestion du service MDM tels que :</span><span class="sxs-lookup"><span data-stu-id="2da05-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-838">Déploiement d’application pour chaque plateforme prise en charge par le biais de liens web ou de liens profonds.</span><span class="sxs-lookup"><span data-stu-id="2da05-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="2da05-839">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-840">Déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous avez une autorité de certification, un réseau sans fil ou une infrastructure VPN existante dans votre organisation.</span><span class="sxs-lookup"><span data-stu-id="2da05-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="2da05-841">Connexion à l’entrepôt de données Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="2da05-842">Intégration de Intune avec :</span><span class="sxs-lookup"><span data-stu-id="2da05-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-843">Visionneuse d’équipe pour l’assistance à distance (un abonnement Team Viewer est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2da05-844">Solutions de partenaires de protection contre les menaces mobiles (MTD) (un abonnement MTD est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2da05-845">Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).</span><span class="sxs-lookup"><span data-stu-id="2da05-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-846">Inscription de périphériques de chaque plateforme prise en charge sur Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="2da05-847">Fournir des conseils sur la protection des applications sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-848">Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.</span><span class="sxs-lookup"><span data-stu-id="2da05-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="2da05-849">Configuration des stratégies d’accès conditionnel pour les applications gérées.</span><span class="sxs-lookup"><span data-stu-id="2da05-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="2da05-850">Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées précédemment.</span><span class="sxs-lookup"><span data-stu-id="2da05-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-851">Utilisation des rapports d’utilisation des applications gérées.</span><span class="sxs-lookup"><span data-stu-id="2da05-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-852">Fourniture de conseils de migration de la gestion des PC hérités vers la gestion des systèmes de gestion Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="2da05-853">
  
</li>
</ul>
  
<strong>Attachement via le cloud</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="2da05-854">Nous vous guidons tout au long de la préparation à l’attachement dans le cloud des environnements Configuration Manager existants avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="2da05-855">Les étapes exactes dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="2da05-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="2da05-856">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="2da05-857">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="2da05-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2da05-858">Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="2da05-859">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="2da05-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2da05-860">Fourniture de conseils pour la configuration hybride de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2da05-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2da05-861">Fourniture de conseils sur la configuration d’Azure AD pour l’inscription automatique À la gestion des paramètres de gestion des logiciels.</span><span class="sxs-lookup"><span data-stu-id="2da05-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-862">Fourniture d’instructions sur la façon de configurer la passerelle de gestion cloud lorsqu’elle est utilisée comme solution pour la cogestion de la gestion des appareils basés sur Internet à distance.</span><span class="sxs-lookup"><span data-stu-id="2da05-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="2da05-863">Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="2da05-864">Installation du client Configuration Manager dans les appareils inscrits sur Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="2da05-865"><strong>Déployer Outlook Mobile pour iOS et Android en toute sécurité</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook Mobile pour iOS et Android en toute sécurité dans votre organisation afin de vous assurer que toutes les applications requises sont installées pour vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="2da05-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="2da05-866">La procédure de déploiement sécurisé d’Outlook Mobile pour iOS et Android avec Intune dépend de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="2da05-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="2da05-867">Il peut inclure les suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-868">Téléchargement des applications Outlook pour iOS et Android, Microsoft Authenticator et le portail d’entreprise Intune via l’App Store d’Apple ou Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="2da05-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="2da05-869">Fourniture d’instructions sur la configuration :</span><span class="sxs-lookup"><span data-stu-id="2da05-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-870">Déploiement d’applications Outlook pour iOS et Android, Microsoft Authenticator et portail d’entreprise Intune avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="2da05-871">Stratégies de protection des applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-872">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2da05-873">Stratégies de configuration d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="2da05-874">Les administrateurs informatiques doivent avoir une autorité de certification, un réseau sans fil et des infrastructures VPN existants qui fonctionnent déjà dans leurs environnements de production lors de la planification du déploiement de réseau sans fil et de profils VPN avec Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="2da05-875"><strong>Remarque</strong>: l’avantage du service FastTrack n’inclut pas d’assistance pour la configuration des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats Push Apple MDM pour Intune.</span><span class="sxs-lookup"><span data-stu-id="2da05-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="2da05-876"><strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud.</span><span class="sxs-lookup"><span data-stu-id="2da05-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="2da05-877">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="2da05-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="2da05-878"><strong>Intune intégré avec Microsoft Defender - Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="2da05-879"><strong>Remarque</strong>: nous fournissons de l’aide sur l’intégration d’Intune à Microsoft Defender ATP et la création de stratégies de conformité des appareils en fonction de son évaluation du niveau de risque Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="2da05-880">Nous ne fournissons pas d’aide sur les achats, les licences ou l’activation.</span><span class="sxs-lookup"><span data-stu-id="2da05-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="2da05-881">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="2da05-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="2da05-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="2da05-883">Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.</span><span class="sxs-lookup"><span data-stu-id="2da05-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="2da05-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="2da05-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-885"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-886"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-887"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2da05-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="2da05-889">Nous fournissons des conseils pour la mise à Windows 7 Professionnel de Windows 8.1 Professionnel vers Windows 10 Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="2da05-890">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-891">Comprendre votre intention de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="2da05-892">Évaluation de votre environnement source et de la configuration requise (assurez-vous que Microsoft Endpoint Configuration Manager est mis à niveau vers le niveau requis pour prendre en charge le déploiement de Windows 10).</span><span class="sxs-lookup"><span data-stu-id="2da05-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="2da05-893">Déploiement de Windows 10 Entreprise et Microsoft 365 Apps à l’aide de Microsoft Endpoint Configuration Manager ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="2da05-894">Recommandations d’options pour évaluer vos applications Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="2da05-895">Activation de l’utilisation de Desktop Analytics et de conseils via la création d’un plan de déploiement Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="2da05-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="2da05-896">Évaluation de la compatibilité des applications Microsoft 365 en tirant parti du tableau de bord de préparation d’Office 365 dans Configuration Manager ou avec le Shared Computer Toolkit de préparation autonome pour Office et une assistance pour le déploiement de Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="2da05-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="2da05-897">Création d’une liste de vérification de correction sur ce que vous devez faire pour mettre votre environnement source au niveau minimal requis pour un déploiement réussi.</span><span class="sxs-lookup"><span data-stu-id="2da05-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-898">Fournir des conseils de mise à niveau pour vos appareils existants vers Windows 10 Entreprise s’ils répondent à la configuration matérielle requise.</span><span class="sxs-lookup"><span data-stu-id="2da05-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="2da05-899">Fournir des instructions de mise à niveau pour prendre en charge votre mouvement de déploiement existant.</span><span class="sxs-lookup"><span data-stu-id="2da05-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="2da05-900">FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="2da05-901">Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.</span><span class="sxs-lookup"><span data-stu-id="2da05-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="2da05-902">Déploiement de Microsoft 365 Apps à l’aide de Configuration Manager dans le cadre du déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="2da05-903">Fournir des conseils pour aider votre organisation à rester à jour avec Windows 10 Entreprise et Microsoft 365 Apps à l’aide de votre environnement Configuration Manager existant ou de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="2da05-904">
  <strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-905">Mettre à niveau Configuration Manager vers la branche actuelle.</span><span class="sxs-lookup"><span data-stu-id="2da05-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="2da05-906">Créer des images personnalisées pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-907">Créer et prendre en charge des scripts de déploiement pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="2da05-908">Convertir un système Windows 10 à partir du BIOS vers Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="2da05-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="2da05-909">Activer les fonctionnalités de sécurité Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="2da05-910">Configurer les services de déploiement Windows (WDS) pour le démarrage de l’environnement PXE (Preboot Execution Environment).</span><span class="sxs-lookup"><span data-stu-id="2da05-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="2da05-911">Utiliser le Microsoft Deployment Toolkit (MDT) pour capturer et déployer des images Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="2da05-912">Utiliser l’outil de migration de l’état utilisateur (USMT).</span><span class="sxs-lookup"><span data-stu-id="2da05-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="2da05-913">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="2da05-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="2da05-914">Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-915">Système d’exploitation source Windows 7 Entreprise professionnel, Windows 8.1 Entreprise ou Professionnel.</span><span class="sxs-lookup"><span data-stu-id="2da05-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="2da05-916">Appareils : facteur de forme de bureau, de bloc-notes ou de tablette.</span><span class="sxs-lookup"><span data-stu-id="2da05-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="2da05-917">Système d’exploitation cible : Fenêtre 10 Entreprise.</span><span class="sxs-lookup"><span data-stu-id="2da05-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="2da05-918">Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2da05-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="2da05-920">La version de Configuration Manager doit être prise en charge par la version cible de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="2da05-921">Pour plus d’informations, voir le tableau de prise en charge de Configuration Manager de l’article <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Prise en charge de Windows 10 dans Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="2da05-922"><strong>Microsoft Defender – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2da05-923">Microsoft Defender – Protection avancée contre les menaces est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter et examiner les menaces avancées et à y répondre.</span><span class="sxs-lookup"><span data-stu-id="2da05-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="2da05-924">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-925">Déploiement des technologies pour sécuriser vos points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="2da05-926">Configuration des profils de protection des points de terminaison et de restriction d’appareil.</span><span class="sxs-lookup"><span data-stu-id="2da05-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="2da05-927">Évaluation de la version du système d’exploitation et de la gestion des appareils (notamment Intune, Microsoft Endpoint Configuration Manager, objets de stratégie de groupe et configurations tierces), ainsi que l’état de vos services antivirus Windows Defender ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2da05-928">Évaluation de l’état de vos services Antivirus Windows ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="2da05-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2da05-929">Évaluation des proxies et des pare-feu limitant le trafic réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="2da05-930">Activation du service Microsoft Defender ATP en expliquant comment déployer un profil d’agent ATP à l’aide d’un point de terminaison intégré.</span><span class="sxs-lookup"><span data-stu-id="2da05-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="2da05-931">Conseils de déploiement, assistance à la configuration et formation sur :</span><span class="sxs-lookup"><span data-stu-id="2da05-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-932">La gestion des menaces et des vulnérabilités.</span><span class="sxs-lookup"><span data-stu-id="2da05-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-933">La réduction de la surface d’attaque.</span><span class="sxs-lookup"><span data-stu-id="2da05-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-934">La nouvelle génération de protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-935">La détection de point de terminaison et réponse.</span><span class="sxs-lookup"><span data-stu-id="2da05-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-936">Les enquêtes et résolutions automatiques.</span><span class="sxs-lookup"><span data-stu-id="2da05-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="2da05-937">Microsoft Defender ATP (les licences Windows E5 ou Microsoft 365 E5 sont requises).</span><span class="sxs-lookup"><span data-stu-id="2da05-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="2da05-938">Le niveau de sécurité.</span><span class="sxs-lookup"><span data-stu-id="2da05-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-939">Examen des simulations et didacticiels (tels que les scénarios pratiques, les programmes malveillants factices et les enquêtes automatisées).</span><span class="sxs-lookup"><span data-stu-id="2da05-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="2da05-940">Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="2da05-941">L’intégration d’Office 365 – Protection avancée contre les menaces avec Microsoft Defender – Protection avancée contre les menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="2da05-942">Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="2da05-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="2da05-943">Les systèmes d’exploitation suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2da05-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="2da05-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="2da05-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-947">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="2da05-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span><span class="sxs-lookup"><span data-stu-id="2da05-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-949">macOS versions 10.13, 10.14 et 10.15.</span><span class="sxs-lookup"><span data-stu-id="2da05-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="2da05-950">
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou Microsoft Endpoint Configuration Manager (version 2002 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="2da05-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="2da05-951"></li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-952">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="2da05-953">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="2da05-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="2da05-954">Gestion continue et réponse aux menaces.</span><span class="sxs-lookup"><span data-stu-id="2da05-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="2da05-955">Intégration ou configuration des agents Microsoft Defender - PACM suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-956">Windows Server 2008</span><span class="sxs-lookup"><span data-stu-id="2da05-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="2da05-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="2da05-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-959">Appareils mobiles (Android et iOS).</span><span class="sxs-lookup"><span data-stu-id="2da05-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="2da05-960">Infrastructure VDI (Virtual Desktop Infrastructure) (persistante ou non persistante).</span><span class="sxs-lookup"><span data-stu-id="2da05-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-961">Intégration et configuration du serveur :</span><span class="sxs-lookup"><span data-stu-id="2da05-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-962">Configuration d’un serveur proxy pour les communications hors connexion.</span><span class="sxs-lookup"><span data-stu-id="2da05-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-963">Configuration des packages de déploiement Configuration Manager sur les instances et versions de Configuration Manager de bas niveau.</span><span class="sxs-lookup"><span data-stu-id="2da05-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-964">Intégration de serveurs au Centre de sécurité Azure.</span><span class="sxs-lookup"><span data-stu-id="2da05-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-965">Serveurs non gérés par Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2da05-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-966">Intégration et configuration macOS :</span><span class="sxs-lookup"><span data-stu-id="2da05-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-967">Déploiement intune manuel.</span><span class="sxs-lookup"><span data-stu-id="2da05-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-968">Déploiement basé sur JAMF.</span><span class="sxs-lookup"><span data-stu-id="2da05-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="2da05-969">Autres déploiements basés sur des produits de gestion des périphériques mobiles (MDM).</span><span class="sxs-lookup"><span data-stu-id="2da05-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-970">Déploiement manuel.</span><span class="sxs-lookup"><span data-stu-id="2da05-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2da05-971">Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :</span><span class="sxs-lookup"><span data-stu-id="2da05-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-972">Isolation basée sur le matériel.</span><span class="sxs-lookup"><span data-stu-id="2da05-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-973">Contrôle d’application.</span><span class="sxs-lookup"><span data-stu-id="2da05-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="2da05-974">Contrôle d’appareil.</span><span class="sxs-lookup"><span data-stu-id="2da05-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="2da05-975">Exploit Protection.</span><span class="sxs-lookup"><span data-stu-id="2da05-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-976">Pare-feu du réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="2da05-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="2da05-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="2da05-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="2da05-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="2da05-979">Configuration ou gestion de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="2da05-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="2da05-980">Inscription ou configuration des Spécialistes des menaces Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2da05-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="2da05-981">Révision de la configuration ou de la formation sur les CONNEXIONS API ou informations de sécurité et de gestion des événements (SIEM).</span><span class="sxs-lookup"><span data-stu-id="2da05-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="2da05-982">Inscription ou configuration de la Protection Microsoft contre les menaces (MTP).</span><span class="sxs-lookup"><span data-stu-id="2da05-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="2da05-983">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="2da05-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="2da05-984">Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</span><span class="sxs-lookup"><span data-stu-id="2da05-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="2da05-985">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="2da05-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="2da05-986">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="2da05-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-987"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-988"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-989"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2da05-990"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="2da05-991">Nous fournissons des conseils de déploiement pour l’intégration à Windows Virtual Desktop (un service de virtualisation de bureau et d’application).</span><span class="sxs-lookup"><span data-stu-id="2da05-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="2da05-992">Windows Virtual Desktop tire parti de l’expérience multisess session windows 10 et est optimisé pour Microsoft 365 Apps for Enterprise avec une sécurité et une gestion intégrées pour Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2da05-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="2da05-993">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="2da05-994">Déploiement de votre environnement Windows Virtual Desktop avec Windows 10 Entreprise multisesse et Microsoft 365 Apps for Enterprise à l’aide des outils suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="2da05-995">Image Marketplace Azure.</span><span class="sxs-lookup"><span data-stu-id="2da05-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="2da05-996">Image partagée.</span><span class="sxs-lookup"><span data-stu-id="2da05-996">Shared image.</span></span></li>
<li><span data-ttu-id="2da05-997">Office Deployment Shared Computer Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="2da05-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="2da05-998">Configuration de FSLogix :</span><span class="sxs-lookup"><span data-stu-id="2da05-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="2da05-999">Déploiement de l’agent FSLogix avec conteneur de profils.</span><span class="sxs-lookup"><span data-stu-id="2da05-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="2da05-1000">Déploiement de l’agent FSLogix avec le conteneur Office.</span><span class="sxs-lookup"><span data-stu-id="2da05-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="2da05-1001">Configuration du dossier FSLogix avec des exclusions de contenu.</span><span class="sxs-lookup"><span data-stu-id="2da05-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="2da05-1002">Déploiement de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="2da05-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="2da05-1003">Déploiement de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2da05-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="2da05-1004">Connexion à l’aide des clients Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="2da05-1005">

<strong>Ce qui suit est hors de portée</strong>
</span><span class="sxs-lookup"><span data-stu-id="2da05-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="2da05-1006">Gestion de projet du déploiement Windows Virtual Desktop du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="2da05-1007">Virtualisation et déploiement d’applications tierces.</span><span class="sxs-lookup"><span data-stu-id="2da05-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="2da05-1008">Images personnalisées.</span><span class="sxs-lookup"><span data-stu-id="2da05-1008">Custom images.</span></span></li>
<li><span data-ttu-id="2da05-1009">Migrations et scénarios impliquant VMware et Citrix.</span><span class="sxs-lookup"><span data-stu-id="2da05-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="2da05-1010">Scénarios Linux.</span><span class="sxs-lookup"><span data-stu-id="2da05-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="2da05-1011">Conversion ou migrations de profils utilisateur.</span><span class="sxs-lookup"><span data-stu-id="2da05-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="2da05-1012">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="2da05-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="2da05-1013">Vous devez déjà avoir les choses suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="2da05-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Conditions requises pour les licences Windows Virtual Desktop.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="2da05-1015">Mise en réseau Azure :</span><span class="sxs-lookup"><span data-stu-id="2da05-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="2da05-1016">Création et sous-réseau de réseau virtuel (VNET).</span><span class="sxs-lookup"><span data-stu-id="2da05-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="2da05-1017">Pare-feu et groupes de sécurité réseau.</span><span class="sxs-lookup"><span data-stu-id="2da05-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="2da05-1018">VPN et ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="2da05-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="2da05-1019">Routage vers Azure à partir de l’local.</span><span class="sxs-lookup"><span data-stu-id="2da05-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="2da05-1020">Règles de pare-feu pour autoriser la connectivité à Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="2da05-1021">Pour plus d’informations, voir <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clients Bureau à distance pris en charge.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="2da05-1022">Configuration générale d’Azure AD :</span><span class="sxs-lookup"><span data-stu-id="2da05-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="2da05-1023">Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
</span><span class="sxs-lookup"><span data-stu-id="2da05-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="2da05-1024">Active Directory avec Azure AD Connect dans Azure.</span><span class="sxs-lookup"><span data-stu-id="2da05-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="2da05-1025">Active Directory avec Azure AD Connect en local sur VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="2da05-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="2da05-1026">Services de domaine Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="2da05-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="2da05-1027">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="2da05-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-1028"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-1029"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-1030"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2da05-1031"><strong>Soutien aux Applications</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="2da05-1032">App Assure est un service conçu pour résoudre les problèmes de compatibilité des applications Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="2da05-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="2da05-1033">Lorsque vous demandez le service Soutien aux applications, nous travaillons avec vous pour résoudre les problèmes d’application valides sans frais supplémentaires pour vous avec un abonnement éligible.</span><span class="sxs-lookup"><span data-stu-id="2da05-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="2da05-1034">Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et De Microsoft Edge, et nous déployons tous les efforts raisonnables pour résoudre les problèmes de compatibilité.</span><span class="sxs-lookup"><span data-stu-id="2da05-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="2da05-1035">Nous fournissons une assistance de correction pour les applications déployées sur les produits Microsoft suivants :</span><span class="sxs-lookup"><span data-stu-id="2da05-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="2da05-1036"><strong>Windows 10 </strong> (y compris les appareils ARM64)</span><span class="sxs-lookup"><span data-stu-id="2da05-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="2da05-1037"><strong>Applications Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="2da05-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="2da05-1038"><strong>Microsoft Edge -</strong> Pour obtenir des conseils de déploiement, voir <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Vue d’ensemble des canaux Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="2da05-1039"><strong>Windows Virtual Desktop</strong> - Pour plus d’informations, voir Qu’est-ce que <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop ?</a> et WINDOWS <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">10 Entreprise multisesse FAQ</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="2da05-1040">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-1041">Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="2da05-1041">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="2da05-1042">Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-1042">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="2da05-1043">Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-1043">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="2da05-1044">Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces.</span><span class="sxs-lookup"><span data-stu-id="2da05-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="2da05-1045">Pour plus d’informations, consultez <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Analytique de bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="2da05-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="2da05-1046">Services uniquement pour le conditionnement des applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-1046">App packaging-only services.</span></span> <span data-ttu-id="2da05-1047">Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="2da05-1048">

<strong>Les responsabilités du client sont les suivantes :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="2da05-1049">Création d’un inventaire d’applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="2da05-1050">Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="2da05-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="2da05-1051">
<strong>Remarque :</strong>  Microsoft ne peut pas apporter de modifications à votre code source.</span><span class="sxs-lookup"><span data-stu-id="2da05-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="2da05-1052">Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications.</span><span class="sxs-lookup"><span data-stu-id="2da05-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="2da05-1053">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="2da05-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="2da05-1054"><strong>Applications Windows 10 et Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="2da05-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-1055">Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="2da05-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-1056">
<strong>Windows 10 sur ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="2da05-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="2da05-1057">Les applications qui fonctionnaient sur Windows 7, Office 2010 ou versions ultérieures fonctionnent également sur Les applications Windows 10 et Microsoft 365 sur les appareils ARM64.</span><span class="sxs-lookup"><span data-stu-id="2da05-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="2da05-1058">
  <strong>Remarque :</strong> 
</span><span class="sxs-lookup"><span data-stu-id="2da05-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="2da05-1059">L’émulation x64 (64 bits) est disponible en prévisualisation pour les clients participant au programme <a href="https://insider.windows.com/">Windows Insider.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="2da05-1060">Pour les clients autres que Windows Insider sur Windows 10 version 2004 (ou version ultérieure), ARM64 Photoshop est pris en charge à l’aide du pack de compatibilité OpenCL et <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="2da05-1061">Les clients du programme Windows Insider peuvent télécharger une version Insider du pack de compatibilité OpenCL et OpenGL pour une utilisation avec des applications supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="2da05-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="2da05-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="2da05-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-1063">Si vos applications ou sites web fonctionnent sur Internet Explorer 11, les versions de Google Chrome ou toute version de Microsoft Edge, elles fonctionneront également avec Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="2da05-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-1064">Comme le web évolue constamment, n’oubliez pas de passer en revue cette liste publiée des modifications connues qui ont un impact sur la compatibilité des sites <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">pour Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-1065">
  <strong>Windows Virtual Desktop </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2da05-1066">Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-1067">Les applications s’exécutant sur un environnement d’infrastructure de bureau virtuel Windows 7 ou Windows 10 (VDI) s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-1068">Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="2da05-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="2da05-1069">
  <strong>Remarque :</strong> Les exclusions et limitations de compatibilité multisessexe Windows 10 Entreprise sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="2da05-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="2da05-1070">Redirection limitée du matériel.</span><span class="sxs-lookup"><span data-stu-id="2da05-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-1071">Les applications ayant une grande quantité de A/V peuvent avoir une capacité réduite.</span><span class="sxs-lookup"><span data-stu-id="2da05-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2da05-1072">Les applications 16 bits ne sont pas prises en charge pour les applications Windows Virtual Desktop 64 bits.</span><span class="sxs-lookup"><span data-stu-id="2da05-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="2da05-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="2da05-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2da05-1074"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2da05-1075"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2da05-1076"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="2da05-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2da05-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="2da05-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="2da05-1078">Nous fournissons des conseils sur le déploiement à distance et l’adoption, ainsi que l’assistance à la compatibilité pour :</span><span class="sxs-lookup"><span data-stu-id="2da05-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="2da05-1079">Déploiement de Microsoft Edge sur Windows 10 avec Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="2da05-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="2da05-1080">Configuration de Microsoft Edge (à l’aide de stratégies de groupe ou de configuration d’application Intune et de stratégies d’application).</span><span class="sxs-lookup"><span data-stu-id="2da05-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="2da05-1081">Inventaire de la liste des sites qui peuvent nécessiter une utilisation en mode Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="2da05-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="2da05-1082">Activation du mode Internet Explorer avec la liste des sites d’entreprise existante.</span><span class="sxs-lookup"><span data-stu-id="2da05-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="2da05-1083">(Pour plus d’informations, voir <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engager FastTrack).</a></span><span class="sxs-lookup"><span data-stu-id="2da05-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="2da05-1084">En outre, si vous avez une application web ou un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="2da05-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="2da05-1085">Pour demander la prise en charge de la compatibilité pour Soutien aux applications, connectez-vous au <a href="https://fasttrack.microsoft.com/portal#/signin">portail FastTrack</a> pour démarrer un engagement.</span><span class="sxs-lookup"><span data-stu-id="2da05-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="2da05-1086">Conseils de planification pour l’adoption edge et les conseils de configuration pour les signets de recherche Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2da05-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="2da05-1087">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2da05-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="2da05-1088">Gestion de projet du déploiement Microsoft Edge du client.</span><span class="sxs-lookup"><span data-stu-id="2da05-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="2da05-1089">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="2da05-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

---
title: Produits et fonctionnalités
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour réussir l’intégration.
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994863"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="a36ba-104">Produits et fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a36ba-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="a36ba-105">Services et scénarios pris en charge par FastTrack</span><span class="sxs-lookup"><span data-stu-id="a36ba-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="a36ba-106">Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer.</span><span class="sxs-lookup"><span data-stu-id="a36ba-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="a36ba-107">En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour réussir l’intégration.</span><span class="sxs-lookup"><span data-stu-id="a36ba-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="a36ba-108">FastTrack fournit des conseils pour vous aider tout d’abord avec les fonctionnalités principales (communes à tous les Microsoft Online Services), puis avec l’intégration de chaque service éligible :</span><span class="sxs-lookup"><span data-stu-id="a36ba-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="a36ba-109">Général</span><span class="sxs-lookup"><span data-stu-id="a36ba-109">General</span></span>](#general)
  - [<span data-ttu-id="a36ba-110">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="a36ba-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="a36ba-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="a36ba-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="a36ba-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="a36ba-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="a36ba-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="a36ba-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="a36ba-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="a36ba-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="a36ba-115">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="a36ba-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="a36ba-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="a36ba-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="a36ba-117">Pour en savoir plus sur les conditions requises dans votre environnement source pour Office 365 US Government, consultez l’article relatif aux [conditions attendues dans l’environnement source pour Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="a36ba-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="a36ba-118">Général</span><span class="sxs-lookup"><span data-stu-id="a36ba-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-119"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-120"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-121"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a36ba-122"><strong>Intégration de base</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-123">Nous fournissons des conseils à distance sur l’intégration de base, qui implique l’approvisionnement de service, le client et l’intégration des identités.</span><span class="sxs-lookup"><span data-stu-id="a36ba-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="a36ba-124">Il inclut également des étapes pour fournir une base pour l’intégration de services tels que Exchange Online, SharePoint Online et Microsoft Teams, y compris une discussion sur la sécurité, la connectivité réseau et la <a href="/office365/enterprise/office-365-network-connectivity-principles">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="a36ba-125">L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="a36ba-126"></li>
</ul>  

<strong> Intégration des identités </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="a36ba-127">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="a36ba-128">Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), notamment l’installation et la configuration d’Azure AD Connecter (à forêt unique ou multi-forêts) et la gestion des licences (y compris les licences basées sur un groupe).</span><span class="sxs-lookup"><span data-stu-id="a36ba-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="a36ba-129">Création d’identités cloud, y compris l’importation et la gestion des licences en bloc, y compris l’utilisation de licences basées sur des groupes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="a36ba-130">Choix et activation de la méthode d’authentification correcte pour votre parcours dans le cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou les services AD FS (Active Directory Federation Services).</span><span class="sxs-lookup"><span data-stu-id="a36ba-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="a36ba-131">Choix et activation d’une expérience d’authentification plus pratique pour vos utilisateurs avec l’authentification sans mot de passe (Fast Identity Online (FIDO)2 ou Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="a36ba-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="a36ba-132">Activation d’AD FS pour les clients avec une forêt Active Directory unique et des identités synchronisées avec l’outil azure AD Connecter.</span><span class="sxs-lookup"><span data-stu-id="a36ba-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="a36ba-133">Cela nécessite Windows Server 2012 R2 Active Directory Federation Services 2.0 ou supérieur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="a36ba-134">Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</span><span class="sxs-lookup"><span data-stu-id="a36ba-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="a36ba-135">Migration d’applications pré-intégrées (telles que les applications SaaS (software-as-a-service) azure AD AD gallery) vers Azure AD pour l' sign-on unique (SSO).</span><span class="sxs-lookup"><span data-stu-id="a36ba-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="a36ba-136">Activation des intégrations d’applications SaaS avec l' luiso à partir de la galerie Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="a36ba-137">Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme indiqué dans la liste de didacticiels sur l’intégration des applications <a href="/azure/active-directory/saas-apps/tutorial-list">(limitée </a> aux applications SaaS de la galerie Azure AD et à la mise en service sortante uniquement).</span><span class="sxs-lookup"><span data-stu-id="a36ba-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="a36ba-138"><strong>Activer le réseau </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="a36ba-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="a36ba-139">Dans le cadre de FastTrack,nous vous conseillons d’indiquer les meilleures pratiques de connexion aux services cloud afin de garantir les niveaux de performances les plus élevés des Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="a36ba-140"><strong>Forêts Active Directory</strong> Le niveau de forêt fonctionnel est Windows Server 2003 et les autres, avec la configuration de forêt suivante :</span><span class="sxs-lookup"><span data-stu-id="a36ba-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-141">Forêt Active Directory unique.</span><span class="sxs-lookup"><span data-stu-id="a36ba-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-142">Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .</span><span class="sxs-lookup"><span data-stu-id="a36ba-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-143">Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).</span><span class="sxs-lookup"><span data-stu-id="a36ba-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-144">Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="a36ba-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-145">Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.</span><span class="sxs-lookup"><span data-stu-id="a36ba-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-146">Tâches requises pour la configuration et l’intégration des Azure Active Directory client, si nécessaire.</span><span class="sxs-lookup"><span data-stu-id="a36ba-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="a36ba-147">
  <strong>Important</strong>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="a36ba-148">Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype Entreprise est déployé, il doit être déployé dans la même forêt Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="a36ba-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-149">Lorsque vous implémentez plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration multi-hybride Exchange, les espaces de noms d’utilisateur principal partagés (UPN) entre les forêts sources ne sont pas pris en charge.</span><span class="sxs-lookup"><span data-stu-id="a36ba-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="a36ba-150">Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="a36ba-151">Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-152">Pour toutes les configurations à forêts multiples, le déploiement des services AD FS (Active Directory Federation Services) est hors de portée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="a36ba-153">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="a36ba-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-155">Nous fournissons des conseils de déploiement à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-156">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-157">Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a36ba-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-158">Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="a36ba-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-159">Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="a36ba-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-160">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-161">Sélection et configuration d’une installation locale ou dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="a36ba-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-162">Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-163">Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a36ba-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="a36ba-164">En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures de Office et que vous avez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème de compatibilité sans frais supplémentaires via le programme Soutien aux applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="a36ba-165">Pour plus <strong>d’informations,</strong> voir la partie <a href="#windows-10">Assurer Windows 10'application.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a36ba-166">Le logiciel client en ligne doit être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .</span><span class="sxs-lookup"><span data-stu-id="a36ba-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-167"><strong>État du réseau</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-168">Nous fournissons des conseils à distance pour obtenir et interpréter les données de connectivité réseau clés de votre environnement, montrant comment les sites de votre organisation sont <a href="/office365/enterprise/office-365-network-connectivity-principles">alignés</a>sur les principes de connectivité réseau de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="a36ba-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="a36ba-169">Cela met en évidence votre score réseau qui a un impact direct sur la vitesse de migration, l’expérience utilisateur, les performances du service et la fiabilité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="a36ba-170">Nous vous guidons également à travers les étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="a36ba-171">Administration Microsoft 365 Accès au centre.</span><span class="sxs-lookup"><span data-stu-id="a36ba-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-172">Les versions à jour des applications Microsoft 365 sont requises.</span><span class="sxs-lookup"><span data-stu-id="a36ba-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-173">Services d’emplacement activés en tant que recommandations de performances réseau dans le <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">centre Administration Microsoft 365 (prévisualisation).</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="a36ba-174">Sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="a36ba-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-175"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-176"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-177"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="a36ba-178"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-179">Nous fournissons des conseils à distance pour la sécurisation de vos identités cloud pour les scénarios suivants.</span><span class="sxs-lookup"><span data-stu-id="a36ba-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="a36ba-180">

<strong>Infrastructure de base sécurisée</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="a36ba-181">La configuration et l’activation d’une authentification forte pour vos identités, y compris la protection avec Azure Multi-Factor Authentication (MFA) (cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et la réinitialisation de mot de passe libre-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="a36ba-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="a36ba-182">Déploiement de FIDO2 ou Microsoft Authenticator App.</span><span class="sxs-lookup"><span data-stu-id="a36ba-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="a36ba-183">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.</span><span class="sxs-lookup"><span data-stu-id="a36ba-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-184">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec l’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-185">Détection et blocage de l’utilisation de mots de passe faibles avec Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-186">Sécurisation de l’accès à distance aux applications web sur site avec le proxy d’application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-187">Activation de la détection et de la correction basées sur les risques avec Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-188">Activation d’un écran de personnalisation, y compris le logo, le texte et les images avec une personnalisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-189">Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="a36ba-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-190">Gestion de l’accès pour vos administrateurs Office 365 à l’aide des rôles d’administration intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateur privilégiés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-191">Configuration de la jointation Azure AD hybride.</span><span class="sxs-lookup"><span data-stu-id="a36ba-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-192">Configuration de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="a36ba-193">
  
<strong>Surveiller et signaler</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-194">Activation de la surveillance à distance pour les services AD FS, les Connecter Azure AD et les contrôleurs de domaine avec Azure AD Connecter Health.</span><span class="sxs-lookup"><span data-stu-id="a36ba-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="a36ba-195">
  
<strong>Gouvernance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-196">Gestion de votre cycle de vie d’accès et d’identité Azure AD à grande échelle avec la gestion des droits Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="a36ba-197">Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions d’accès Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-198">Examen des conditions d’utilisation d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-199">Gestion et contrôle de l’accès aux comptes d’administrateur privilégiés avec Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="a36ba-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="a36ba-200">
  
<strong>Automatisation et efficacité </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-201">Activation d’Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="a36ba-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="a36ba-202">Permettre aux utilisateurs de créer et de gérer leurs propres groupes de sécurité Office 365 cloud ou de gestion des groupes en libre-service Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-203">Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-204">Activation des groupes dynamiques Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-205">Organisation des applications dans le portail Mes applications à l’aide de collections.</span><span class="sxs-lookup"><span data-stu-id="a36ba-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a36ba-206">Active Directory local et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium..</span><span class="sxs-lookup"><span data-stu-id="a36ba-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-207"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="a36ba-208">Pour plus d’informations sur Azure Information Protection, <strong>voir Protection des données Microsoft</strong> plus loin dans ce tableau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="a36ba-209"><strong>Découvrir & Répondre</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="a36ba-210"><strong>eDiscovery (découverte électronique) avancée</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="a36ba-211">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="a36ba-212">Création d’un cas.</span><span class="sxs-lookup"><span data-stu-id="a36ba-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="a36ba-213">Mise en attente des dépositaires.</span><span class="sxs-lookup"><span data-stu-id="a36ba-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-214">Effectuer des recherches.</span><span class="sxs-lookup"><span data-stu-id="a36ba-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="a36ba-215">Ajouter des résultats de recherche à un jeu à réviser.</span><span class="sxs-lookup"><span data-stu-id="a36ba-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="a36ba-216">Exécution de l’analyse sur un groupe de révision.</span><span class="sxs-lookup"><span data-stu-id="a36ba-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-217">Révision et marquage de documents.</span><span class="sxs-lookup"><span data-stu-id="a36ba-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-218">Exportation de données à partir du jeu à réviser.</span><span class="sxs-lookup"><span data-stu-id="a36ba-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="a36ba-219">Importation de données non Office 365 données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="a36ba-220"><strong>Audit avancé</strong> (uniquement pris en charge dans E5)</span><span class="sxs-lookup"><span data-stu-id="a36ba-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="a36ba-221">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="a36ba-222">Activation de l’audit avancé.</span><span class="sxs-lookup"><span data-stu-id="a36ba-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="a36ba-223">Exécuter une interface utilisateur du journal d’audit de recherche et des commandes PowerShell d’audit de base.</span><span class="sxs-lookup"><span data-stu-id="a36ba-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="a36ba-224">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a36ba-225">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a36ba-226">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a36ba-227">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="a36ba-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a36ba-228">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a36ba-229">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a36ba-230">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a36ba-231">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="a36ba-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="a36ba-232">Scripts ou codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="a36ba-233">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="a36ba-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="a36ba-234">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="a36ba-235">Limites de conformité et filtres de sécurité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="a36ba-236">Enquêtes sur les données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="a36ba-237">Demandes des personnes à l’objet de données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="a36ba-238">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="a36ba-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a36ba-239">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a36ba-240">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="a36ba-241">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="a36ba-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="a36ba-242"><strong>Gestion des risques internes</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="a36ba-243">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="a36ba-244">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="a36ba-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="a36ba-245">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="a36ba-246">Créer des cas.</span><span class="sxs-lookup"><span data-stu-id="a36ba-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="a36ba-247">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="a36ba-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="a36ba-248">Recommandations sur la création du connecteur de ressources humaines (RH).</span><span class="sxs-lookup"><span data-stu-id="a36ba-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="a36ba-249">

<strong> Conformité des communications </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="a36ba-250">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="a36ba-251">Création de stratégies et révision des paramètres.</span><span class="sxs-lookup"><span data-stu-id="a36ba-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="a36ba-252">Accès aux rapports et aux alertes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="a36ba-253">Création de modèles d’avis.</span><span class="sxs-lookup"><span data-stu-id="a36ba-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="a36ba-254">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a36ba-255">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a36ba-256">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a36ba-257">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="a36ba-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a36ba-258">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a36ba-259">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a36ba-260">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a36ba-261">

<strong>Ce qui suit est hors de portée </strong> 
</span><span class="sxs-lookup"><span data-stu-id="a36ba-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="a36ba-262">La création et la gestion Power Automate flux de données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="a36ba-263">Connecteurs de données (au-delà du connecteur RH).</span><span class="sxs-lookup"><span data-stu-id="a36ba-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="a36ba-264">Configurations d’expression régulière personnalisées (RegEx).</span><span class="sxs-lookup"><span data-stu-id="a36ba-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="a36ba-265">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="a36ba-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a36ba-266">Obstacles à l’information.</span><span class="sxs-lookup"><span data-stu-id="a36ba-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="a36ba-267">Gestion des accès privilégiés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="a36ba-268">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a36ba-269">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="a36ba-270">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="a36ba-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="a36ba-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="a36ba-272">Microsoft 365 Defender est une suite unifiée de défense d’entreprise avant et après la violation qui coordonne en natif la détection, la prévention, l’examen et la réponse entre les points de terminaison, les identités, le courrier électronique et les applications afin de fournir une protection intégrée contre les attaques sophistiquées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="a36ba-273">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="a36ba-274">Présentation du centre de Microsoft 365 de sécurité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-275">Passer en revue les incidents entre produits, notamment en vous concentrant sur les éléments critiques en garantissant l’étendue complète des attaques, les ressources impactées et les actions de correction automatisées regroupées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-276">Montrant comment Microsoft 365 Defender pouvez orchestrer l’examen des biens, des utilisateurs, des appareils et des boîtes aux lettres qui ont pu être compromis par le biais d’une auto-ressource automatisée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="a36ba-277">Explication et fourniture d’exemples de la façon dont les clients peuvent chercher de manière proactive les tentatives d’intrusion et l’activité de violation affectant vos e-mails, données, appareils et comptes dans plusieurs ensembles de données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="a36ba-278">Montrer aux clients comment ils peuvent examiner et améliorer leur posture de sécurité globalement à l’aide du Niveau de sécurité Microsoft.</span><span class="sxs-lookup"><span data-stu-id="a36ba-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="a36ba-279"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="a36ba-280">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="a36ba-281">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="a36ba-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="a36ba-282">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="a36ba-283">Comment corriger ou interpréter les différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="a36ba-284">Comment examiner un utilisateur, un ordinateur, un chemin de mouvement latéral ou une entité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="a36ba-285">Recherche de menace personnalisée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="a36ba-286">Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="a36ba-287">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API.</span><span class="sxs-lookup"><span data-stu-id="a36ba-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-289">Microsoft Cloud App Security est un service Broker de sécurité d’accès au cloud (CASB) qui offre une visibilité enrichie, un contrôle sur les déplacements de données et des analyses sophistiquées pour identifier et lutter contre les cybermenaces dans tous vos services cloud Microsoft et tiers.</span><span class="sxs-lookup"><span data-stu-id="a36ba-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="a36ba-290">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-291">Configuration du portail, notamment :</span><span class="sxs-lookup"><span data-stu-id="a36ba-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="a36ba-292">Importation de groupes d’utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="a36ba-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="a36ba-293">Gestion de l’accès et des paramètres de l’administrateur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="a36ba-294">Portée de votre déploiement pour sélectionner certains groupes d’utilisateurs à surveiller ou exclure de la surveillance.</span><span class="sxs-lookup"><span data-stu-id="a36ba-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="a36ba-295">Comment configurer des plages IP et des balises.</span><span class="sxs-lookup"><span data-stu-id="a36ba-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="a36ba-296">Personnalisation de l’expérience utilisateur final avec votre logo et votre messagerie personnalisée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-297">Intégration de services tiers, notamment :</span><span class="sxs-lookup"><span data-stu-id="a36ba-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="a36ba-298">Microsoft Defender pour point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="a36ba-299">Microsoft Defender pour l’identité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="a36ba-300">Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="a36ba-301">Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-302">Configuration de la découverte dans le cloud à l’aide des paramètres :</span><span class="sxs-lookup"><span data-stu-id="a36ba-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="a36ba-303">Microsoft Defender pour les points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="a36ba-304">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="a36ba-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="a36ba-305">iboss.</span><span class="sxs-lookup"><span data-stu-id="a36ba-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-306">Création de balises et de catégories d’application.</span><span class="sxs-lookup"><span data-stu-id="a36ba-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="a36ba-307">Personnalisation des scores de risque des applications en fonction des priorités de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="a36ba-308">Application de sanctions et d’inséance.</span><span class="sxs-lookup"><span data-stu-id="a36ba-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="a36ba-309">Examen des tableaux de bord Cloud App Security et Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="a36ba-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="a36ba-310">Connexion <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> d’applications fonctionnalités à l’aide</a> de connecteurs d’application.</span><span class="sxs-lookup"><span data-stu-id="a36ba-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="a36ba-311">Protection des applications avec le contrôle d’application d’accès conditionnel dans l’accès conditionnel au sein des portails Azure AD et Cloud App Security.</span><span class="sxs-lookup"><span data-stu-id="a36ba-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="a36ba-312">Déploiement du contrôle d’application d’accès conditionnel pour les applications disponibles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="a36ba-313">Utilisation des journaux d’activité et de fichiers.</span><span class="sxs-lookup"><span data-stu-id="a36ba-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="a36ba-314">Gestion des applications OAuth.</span><span class="sxs-lookup"><span data-stu-id="a36ba-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="a36ba-315">Révision et configuration des modèles de stratégie.</span><span class="sxs-lookup"><span data-stu-id="a36ba-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="a36ba-316">Fourniture d’une assistance à la configuration avec les 20 principaux cas d’utilisation pour les cas de base de données d’accès au détail (y compris la création ou la mise à jour de six (6) <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">stratégies),</a> sauf :</span><span class="sxs-lookup"><span data-stu-id="a36ba-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="a36ba-317">Audit de la configuration de vos environnements Internet en tant que service (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="a36ba-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="a36ba-318">Surveillance des activités des utilisateurs pour se protéger contre les menaces dans vos environnements IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="a36ba-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-319">Comprendre la corrélation des incidents dans le portail Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="a36ba-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="a36ba-320"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="a36ba-321">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="a36ba-322">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="a36ba-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="a36ba-323">Discussions comparant Cloud App Security à d’autres offres CASB.</span><span class="sxs-lookup"><span data-stu-id="a36ba-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="a36ba-324">Configuration de Cloud App Security pour répondre à des exigences spécifiques en matière de conformité ou de réglementation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="a36ba-325">Déploiement du service dans un environnement de production non-test.</span><span class="sxs-lookup"><span data-stu-id="a36ba-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="a36ba-326">Déploiement de la découverte d’applications cloud comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="a36ba-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="a36ba-327">Prise <a href=" /fasttrack/us-gov-appendix-overview"> en charge GCC-High ou GCC-DoD (Office 365 pour le gouvernement américain)</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="a36ba-328">Configuration de l’infrastructure, de l’installation ou du déploiement des téléchargements automatiques de journaux pour les rapports continus à l’aide de Docker ou d’un collecteur de journaux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="a36ba-329">Création d’un rapport instantané de découverte cloud.</span><span class="sxs-lookup"><span data-stu-id="a36ba-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="a36ba-330">Blocage de l’utilisation de l’application à l’aide de scripts de blocage.</span><span class="sxs-lookup"><span data-stu-id="a36ba-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="a36ba-331">Connexion d’applications personnalisées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="a36ba-332">Intégration et déploiement du contrôle d’application d’accès conditionnel pour les applications non présentes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="a36ba-333">Intégration avec des fournisseurs d’identité tiers (ISP) et des fournisseurs de protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="a36ba-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="a36ba-334">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="a36ba-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="a36ba-335">Examen et correction automatisés, y compris les manuels Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="a36ba-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="a36ba-336">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="a36ba-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="a36ba-337"><strong>Microsoft Defender pour point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-338">Microsoft Defender pour point de terminaison est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter, examiner et répondre aux menaces avancées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="a36ba-339">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-340">Déploiement des technologies pour sécuriser vos points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-341">Configuration des profils de protection des points de terminaison et de restriction d’appareil.</span><span class="sxs-lookup"><span data-stu-id="a36ba-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-342">Évaluation de la version du système d’exploitation et de la gestion des appareils (notamment Intune, Microsoft Endpoint Configuration Manager, objets de stratégie de groupe et configurations tierces), ainsi que l’état de vos services antivirus Windows Defender ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-343">Évaluation de l’état de vos services Antivirus Windows ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-344">Évaluation des proxies et des pare-feu limitant le trafic réseau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-345">Activation du service Microsoft Defender for Endpoint en expliquant comment déployer un profil d’agent Defender pour Endpoint à l’aide d’un point de terminaison intégré.</span><span class="sxs-lookup"><span data-stu-id="a36ba-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-346">Conseils de déploiement, assistance à la configuration et formation sur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-347">La gestion des menaces et des vulnérabilités.</span><span class="sxs-lookup"><span data-stu-id="a36ba-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-348">La réduction de la surface d’attaque.</span><span class="sxs-lookup"><span data-stu-id="a36ba-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-349">La nouvelle génération de protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-350">La détection de point de terminaison et réponse.</span><span class="sxs-lookup"><span data-stu-id="a36ba-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-351">Les enquêtes et résolutions automatiques.</span><span class="sxs-lookup"><span data-stu-id="a36ba-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-352">Score de sécurité pour les appareils.</span><span class="sxs-lookup"><span data-stu-id="a36ba-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="a36ba-353">Configuration de Microsoft Defender SmartScreen à l’aide de Microsoft Endpoint Manager.</span><span class="sxs-lookup"><span data-stu-id="a36ba-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="a36ba-354">Examen des simulations et didacticiels (tels que les scénarios pratiques, les programmes malveillants factices et les enquêtes automatisées).</span><span class="sxs-lookup"><span data-stu-id="a36ba-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-355">Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-356">Intégration de Microsoft Defender pour Office 365 à Microsoft Defender pour Endpoint.</span><span class="sxs-lookup"><span data-stu-id="a36ba-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-357">Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="a36ba-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-358">Les systèmes d’exploitation suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-359">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-360">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="a36ba-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-361">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="a36ba-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-362">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="a36ba-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span><span class="sxs-lookup"><span data-stu-id="a36ba-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-364">macOS versions 10.13, 10.14 et 10.15.</span><span class="sxs-lookup"><span data-stu-id="a36ba-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="a36ba-365">
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou Microsoft Endpoint Configuration Manager (version 2002 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="a36ba-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="a36ba-366"></li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a36ba-367">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="a36ba-368">Prise <a href=" /fasttrack/us-gov-appendix-overview"> en charge GCC-High ou GCC-DoD (Office 365 pour le gouvernement américain)</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="a36ba-369">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="a36ba-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-370">Gestion continue et réponse aux menaces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-371">Intégration ou configuration pour les agents Microsoft Defender pour points de terminaison suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-372">Windows Server 2008</span><span class="sxs-lookup"><span data-stu-id="a36ba-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-373">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="a36ba-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-374">Linux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-375">Appareils mobiles (Android et iOS).</span><span class="sxs-lookup"><span data-stu-id="a36ba-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="a36ba-376">Infrastructure VDI (Virtual Desktop Infrastructure) (persistante ou non persistante).</span><span class="sxs-lookup"><span data-stu-id="a36ba-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-377">Intégration et configuration du serveur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-378">Configuration d’un serveur proxy pour les communications hors connexion.</span><span class="sxs-lookup"><span data-stu-id="a36ba-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-379">Configuration des packages de déploiement Configuration Manager sur les instances et versions de Configuration Manager de bas niveau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-380">Intégration de serveurs au Centre de sécurité Azure.</span><span class="sxs-lookup"><span data-stu-id="a36ba-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-381">Serveurs non gérés par Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a36ba-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-382">Intégration et configuration macOS :</span><span class="sxs-lookup"><span data-stu-id="a36ba-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-383">Déploiement intune manuel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-384">Déploiement basé sur JAMF.</span><span class="sxs-lookup"><span data-stu-id="a36ba-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="a36ba-385">Autres déploiements basés sur des produits de gestion des périphériques mobiles (MDM).</span><span class="sxs-lookup"><span data-stu-id="a36ba-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-386">Déploiement manuel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-387">Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :</span><span class="sxs-lookup"><span data-stu-id="a36ba-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-388">Isolation basée sur le matériel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-389">Contrôle d’application.</span><span class="sxs-lookup"><span data-stu-id="a36ba-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="a36ba-390">Contrôle d’appareil.</span><span class="sxs-lookup"><span data-stu-id="a36ba-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="a36ba-391">Exploit Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-392">Pare-feu du réseau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="a36ba-393">Configuration ou gestion des fonctionnalités de protection des comptes telles que :</span><span class="sxs-lookup"><span data-stu-id="a36ba-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="a36ba-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="a36ba-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="a36ba-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="a36ba-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-396">Configuration ou gestion de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="a36ba-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="a36ba-397">Inscription ou configuration des Spécialistes des menaces Microsoft.</span><span class="sxs-lookup"><span data-stu-id="a36ba-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-398">Révision de la configuration ou de la formation sur les API ou les connexions de gestion des événements et des informations de sécurité (SIEM).</span><span class="sxs-lookup"><span data-stu-id="a36ba-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-399">Inscription ou configuration de Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="a36ba-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-400">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="a36ba-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-401">Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</span><span class="sxs-lookup"><span data-stu-id="a36ba-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="a36ba-402">Formation ou conseils sur la configuration de Defender SmartScreen à l’aide d’objets de stratégie de groupe, de Sécurité Windows ou de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="a36ba-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="a36ba-403">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="a36ba-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="a36ba-404"><strong>Microsoft Defender pour l’identité </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="a36ba-405">Microsoft Defender pour Identity est une solution de sécurité basée sur le cloud qui exploite vos signaux Active Directory sur site pour identifier, détecter et examiner les menaces avancées, les identités compromises et les actions des utilisateurs malveillants ciblant votre organisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="a36ba-406">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-407">Exécution de l’outil de taille pour la planification de la capacité des ressources.</span><span class="sxs-lookup"><span data-stu-id="a36ba-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="a36ba-408">Création de votre instance de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a36ba-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="a36ba-409">Connexion de Defender pour l’identité à Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a36ba-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="a36ba-410">Déploiement du capteur pour capturer et parer le trafic réseau et Windows événements directement à partir de vos contrôleurs de domaine, notamment :</span><span class="sxs-lookup"><span data-stu-id="a36ba-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="a36ba-411">Téléchargement du package de capteur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="a36ba-412">Configuration du capteur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="a36ba-413">Installation silencieuse du capteur sur votre contrôleur de domaine.</span><span class="sxs-lookup"><span data-stu-id="a36ba-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="a36ba-414">Déploiement du capteur dans votre environnement à forêts multiples.</span><span class="sxs-lookup"><span data-stu-id="a36ba-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="a36ba-415">Configuration du collecteur Windows événements.</span><span class="sxs-lookup"><span data-stu-id="a36ba-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="a36ba-416">Configuration du portail, notamment :</span><span class="sxs-lookup"><span data-stu-id="a36ba-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="a36ba-417">Intégration de Defender for Identity à Microsoft Cloud App Security (Sécurité des applications cloud licences n’est pas requise).</span><span class="sxs-lookup"><span data-stu-id="a36ba-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="a36ba-418">Configuration des balises d’entité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="a36ba-419">Marquage des comptes sensibles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="a36ba-420">Réception de notifications par courrier électronique pour les problèmes d’état de santé et les alertes de sécurité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="a36ba-421">Configuration des exclusions d’alertes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="a36ba-422">Fourniture d’instructions de déploiement, d’assistance à la configuration et de formation sur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="a36ba-423">Comprendre le rapport d’évaluation de la posture de sécurité des identités.</span><span class="sxs-lookup"><span data-stu-id="a36ba-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="a36ba-424">Comprendre le rapport sur le score de priorité de l’examen des utilisateurs et le rapport de classement de l’examen utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="a36ba-425">Comprendre le rapport de l’utilisateur inactif.</span><span class="sxs-lookup"><span data-stu-id="a36ba-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="a36ba-426">Explication des options de correction sur un compte compromis.</span><span class="sxs-lookup"><span data-stu-id="a36ba-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="a36ba-427">Faciliter la migration de Advanced Threat Analytics (ATA) vers Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a36ba-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="a36ba-428"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="a36ba-429">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="a36ba-430">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="a36ba-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="a36ba-431">Déploiement de Defender for Identity comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="a36ba-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="a36ba-432">Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="a36ba-433">Déploiement ou mise en place des activités de capteur Defender pour l’identité suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="a36ba-434">Planification manuelle de la capacité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="a36ba-435">Exécution de l’outil Audit.</span><span class="sxs-lookup"><span data-stu-id="a36ba-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="a36ba-436">Déploiement du capteur autonome.</span><span class="sxs-lookup"><span data-stu-id="a36ba-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="a36ba-437">Déploiement sur les serveurs AD FS (Active Directory Federation Services).</span><span class="sxs-lookup"><span data-stu-id="a36ba-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="a36ba-438">Déploiement du capteur à l’aide d’un adaptateur d’équipe carte d’interface réseau (NIC).</span><span class="sxs-lookup"><span data-stu-id="a36ba-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="a36ba-439">Déploiement du capteur via un outil tiers.</span><span class="sxs-lookup"><span data-stu-id="a36ba-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="a36ba-440">Connexion au service cloud Defender for Identity via une connexion proxy web.</span><span class="sxs-lookup"><span data-stu-id="a36ba-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="a36ba-441">Configuration du compte Microsoft (MSA) dans Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a36ba-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="a36ba-442">Création et gestion de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="a36ba-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="a36ba-443">Activation de la résolution de noms réseau (NNR).</span><span class="sxs-lookup"><span data-stu-id="a36ba-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="a36ba-444">Configuration du conteneur Objets supprimés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="a36ba-445">Instructions de déploiement ou formation sur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="a36ba-446">Correction ou interprétation de différents types d’alertes et activités surveillées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="a36ba-447">Recherche d’un utilisateur, d’un ordinateur, d’un chemin de mouvement latéral ou d’une entité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="a36ba-448">Menace ou recherche avancée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="a36ba-449">Réponse aux incidents.</span><span class="sxs-lookup"><span data-stu-id="a36ba-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="a36ba-450">Fourniture d’un didacticiel de laboratoire d’alertes de sécurité pour Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a36ba-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="a36ba-451">Envoi d’une notification lorsque Defender pour l’identité détecte des activités suspectes en envoyant des alertes de sécurité à votre serveur syslog via un capteur désigné.</span><span class="sxs-lookup"><span data-stu-id="a36ba-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="a36ba-452">Configuration de Defender for Identity pour effectuer des requêtes à l’aide du protocole SAMR (Security Account Manager remote) afin d’identifier les administrateurs locaux sur des ordinateurs spécifiques.</span><span class="sxs-lookup"><span data-stu-id="a36ba-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="a36ba-453">Configuration de solutions VPN pour ajouter des informations à partir de la connexion VPN à la page de profil d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="a36ba-454">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="a36ba-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a36ba-455">Aligné sur <a href="/defender-for-identity/prerequisites">Microsoft Defender pour les conditions préalables d’identité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="a36ba-456">Active Directory déployé.</span><span class="sxs-lookup"><span data-stu-id="a36ba-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-457">Les contrôleurs de domaine sur qui vous avez l’intention d’installer les capteurs Defender for Identity ont une connectivité Internet au service cloud de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a36ba-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="a36ba-458">Votre pare-feu et votre proxy doivent être ouverts pour communiquer avec le service cloud Defender for Identity (\*.atp.azure.com port 443 doit être ouvert).</span><span class="sxs-lookup"><span data-stu-id="a36ba-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-459">Contrôleurs de domaine en cours d’exécution sur l’une des suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="a36ba-460">Windows Serveur 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="a36ba-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="a36ba-461">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="a36ba-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="a36ba-462">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="a36ba-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="a36ba-463">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="a36ba-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="a36ba-464">Windows Serveur 2019 avec KB4487044 (build de système d’exploitation 17763.316 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="a36ba-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-465">Microsoft .NET Framework 4.7 ou ultérieure.</span><span class="sxs-lookup"><span data-stu-id="a36ba-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="a36ba-466">Un minimum de cinq (5) Go d’espace disque est requis et 10 Go sont recommandés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="a36ba-467">Deux (2) cœurs et six (6) Go de RAM installés sur le contrôleur de domaine.</span><span class="sxs-lookup"><span data-stu-id="a36ba-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="a36ba-468"><strong>Microsoft Defender pour Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-p114">Microsoft Defender pour Office 365 protège votre organisation contre les menaces malveillantes posées par les messages électroniques, les liens (URL) et les outils de collaboration. Microsoft Defender pour Office 365 inclut :</span><span class="sxs-lookup"><span data-stu-id="a36ba-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="a36ba-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Stratégies de protection contre les</a>menaces : définissez des stratégies de protection contre les menaces pour définir le niveau de protection approprié pour votre organisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="a36ba-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Rapports</a>: affichez des rapports en temps réel pour surveiller Defender Office 365 performances au niveau de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="a36ba-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Fonctionnalités de recherche et de réponse aux menaces</a> : utilisez des outils de pointe pour étudier, comprendre, simuler et prévenir les menaces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="a36ba-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Fonctionnalités automatisées d’investigation et de réponse</a> : gagnez du temps pour investiguer et atténuer les menaces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="a36ba-475">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-476">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="a36ba-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-477">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="a36ba-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-478">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="a36ba-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-479">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-480">Comprendre la corrélation d’incidents dans Microsoft 365 Defender portail.</span><span class="sxs-lookup"><span data-stu-id="a36ba-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="a36ba-481"><strong>Ce qui suit est hors de portée</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="a36ba-482">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="a36ba-483">Gestion continue, réponse aux menaces et correction.</span><span class="sxs-lookup"><span data-stu-id="a36ba-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="a36ba-484">Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="a36ba-485">Discussions comparant Defender pour Office 365 à d’autres offres de sécurité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="a36ba-486">Déploiement de Defender pour Office 365 comme preuve de concept.</span><span class="sxs-lookup"><span data-stu-id="a36ba-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="a36ba-487">Connexion d’applications personnalisées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="a36ba-488">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="a36ba-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="a36ba-489">Examen et correction automatisés, y compris les manuels Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="a36ba-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="a36ba-490">Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="a36ba-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="a36ba-491">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="a36ba-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="a36ba-492"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="a36ba-493">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-494">Création et publication d’étiquettes et de stratégies de rétention (uniquement pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="a36ba-495">Gestion des enregistrements (uniquement prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="a36ba-496">Examen de la création d’un plan de fichiers.</span><span class="sxs-lookup"><span data-stu-id="a36ba-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="a36ba-497">Création et gestion des enregistrements (y compris les enregistrements basés sur des événements).</span><span class="sxs-lookup"><span data-stu-id="a36ba-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-498">Révision de la disposition.</span><span class="sxs-lookup"><span data-stu-id="a36ba-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="a36ba-499">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a36ba-500">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a36ba-501">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a36ba-502">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="a36ba-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a36ba-503">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a36ba-504">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a36ba-505">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a36ba-506">

  <strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="a36ba-507">Développement d’un plan de gestion des fichiers de gestion des enregistrements.</span><span class="sxs-lookup"><span data-stu-id="a36ba-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="a36ba-508">Connecteurs de données.</span><span class="sxs-lookup"><span data-stu-id="a36ba-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="a36ba-509">Développement de l’architecture des informations dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a36ba-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="a36ba-510">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="a36ba-511">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="a36ba-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a36ba-512">Prise en charge de l’E3.</span><span class="sxs-lookup"><span data-stu-id="a36ba-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="a36ba-513">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a36ba-514">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="a36ba-515">En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</span><span class="sxs-lookup"><span data-stu-id="a36ba-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-516"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-517">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-518">Classification des données (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-519">Types d’informations sensibles (pris en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-520">Création d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-521">Application d’étiquettes de sensibilité (prise en charge dans E3 et E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-522">Classifieurs entra nessables (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-523">Connaissance de vos données avec l’Explorateur de contenu et l’Explorateur d’activités (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-524">Publication d’étiquettes à l’aide de stratégies (manuelle et automatique) (prise en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-525">Création de stratégies de protection contre la perte de données (DLP) de point de terminaison pour les appareils Windows 10 (pris en charge dans E5).</span><span class="sxs-lookup"><span data-stu-id="a36ba-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-526">Création de stratégies DLP pour les conversations et les canaux Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="a36ba-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="a36ba-527">

<strong> Gestionnaire de conformité</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a36ba-528">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a36ba-529">Examen des types de rôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a36ba-530">Ajout et configuration des évaluations.</span><span class="sxs-lookup"><span data-stu-id="a36ba-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a36ba-531">Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a36ba-532">Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a36ba-533">Génération d’un rapport au sein d’une évaluation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a36ba-534">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="a36ba-535">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-536">Activation et configuration de votre client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-537">Création et configuration d’étiquettes et de stratégies (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="a36ba-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-538">Application de la protection des informations aux documents (prise en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="a36ba-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-539">Classification et étiquetage automatiques des informations dans les applications Office (comme Word, PowerPoint, Excel et Outlook) en cours d’exécution sur Windows et à l’aide du client Azure Information Protection (pris en charge dans P2).</span><span class="sxs-lookup"><span data-stu-id="a36ba-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-540">Découverte et étiquetage des fichiers au repos à l’aide du scanneur Azure Information Protection (pris en charge dans P1 et P2).</span><span class="sxs-lookup"><span data-stu-id="a36ba-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-541">Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a36ba-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="a36ba-542">Nous fournissons également des conseils si vous souhaitez appliquer une protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="a36ba-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="a36ba-543"><strong>Ce qui suit est hors de portée </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="a36ba-544">Clé client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-544">Customer key.</span></span></li>
<li><span data-ttu-id="a36ba-545">Développement d’expressions régulières personnalisées (RegEx) pour les types d’informations sensibles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="a36ba-546">Création ou modification de dictionnaires de mots clés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="a36ba-547">Scripts et codage personnalisés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="a36ba-548">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="a36ba-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="a36ba-549">Révision de documents tiers, de conception et d’architecte.</span><span class="sxs-lookup"><span data-stu-id="a36ba-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a36ba-550">Conformité avec les réglementations et exigences régionales et industrielles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a36ba-551">Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="a36ba-552">En dehors <strong>de la partie</strong> Intégration de base en <a href="#general">général,</a>il n’existe aucune exigence système minimale à l’exception d’Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="a36ba-553"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="a36ba-554">Les responsabilités préalables du client sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-555">Liste des emplacements de partage de fichiers à scanner.</span><span class="sxs-lookup"><span data-stu-id="a36ba-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-556">Taxonomie de classification approuvée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="a36ba-557">Comprendre les restrictions ou exigences réglementaires relatives à la gestion des clés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-558">Un compte de service créé pour votre annuaire Active Directory local qui a été synchronisé avec Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="a36ba-559">Étiquettes configurées pour la classification et la protection.</span><span class="sxs-lookup"><span data-stu-id="a36ba-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="a36ba-560">Toutes les conditions préalables pour le scanneur Azure Information Protection sont en place.</span><span class="sxs-lookup"><span data-stu-id="a36ba-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="a36ba-561">Pour plus d’informations, voir Conditions préalables à l’installation et au déploiement du scanneur d’étiquetage unifié <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="a36ba-562">Assurez-vous que les appareils utilisateur exécutent un système d’exploitation pris en charge et que les conditions préalables nécessaires sont installées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="a36ba-563">Pour plus d’informations, voir les informations suivantes.</span><span class="sxs-lookup"><span data-stu-id="a36ba-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="a36ba-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guide d’administration : Installer le client d’étiquetage unifié Azure Information Protection pour les utilisateurs</a>   </span><span class="sxs-lookup"><span data-stu-id="a36ba-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="a36ba-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">Qu’est-ce que l’application Azure Information Protection pour iOS ou Android ?</a>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="a36ba-566">Installation et configuration du connecteur et des serveurs Azure RMS, y compris le connecteur AD RMS (Active Directory RMS) pour la prise en charge hybride.</span><span class="sxs-lookup"><span data-stu-id="a36ba-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="a36ba-567">Si vous avez besoin de l’une de ces options pour votre déploiement, vous devez installer et configurer Bring Your Own Key (BYOK), DKE (Double Key Encryption) (client d’étiquetage unifié uniquement) ou Hold Your Own Key (HYOK) (client classique uniquement).</span><span class="sxs-lookup"><span data-stu-id="a36ba-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-569">Nous fournissons des conseils à distance sur la préparation à l’utilisation d’Intune en tant que fournisseur de gestion des périphériques mobiles (MDM) et de gestion des applications mobiles (MAM) dans le cloud pour vos applications et appareils.</span><span class="sxs-lookup"><span data-stu-id="a36ba-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="a36ba-570">Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="a36ba-571">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-572">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-573">Configuration des identités à utiliser par Intune en tirant parti de vos identités Active Directory locales ou cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="a36ba-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-574">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="a36ba-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-575">Configuration de votre autorité de gestion des projets, en fonction de vos besoins en matière de gestion, notamment :</span><span class="sxs-lookup"><span data-stu-id="a36ba-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-576">Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-577">Recommandations en matière de gestion des appareils mobiles pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-578">Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.</span><span class="sxs-lookup"><span data-stu-id="a36ba-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-579">Configuration des stratégies de gestion et des services de gestion du service MDM tels que :</span><span class="sxs-lookup"><span data-stu-id="a36ba-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-580">Déploiement d’application pour chaque plateforme prise en charge par le biais de liens web ou de liens profonds.</span><span class="sxs-lookup"><span data-stu-id="a36ba-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-581">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-582">Déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous avez une autorité de certification, un réseau sans fil ou une infrastructure VPN existante dans votre organisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-583">Connexion à l’entrepôt de données Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-584">Intégration de Intune avec :</span><span class="sxs-lookup"><span data-stu-id="a36ba-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-585">Visionneuse d’équipe pour l’assistance à distance (un abonnement Team Viewer est requis).</span><span class="sxs-lookup"><span data-stu-id="a36ba-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-586">Solutions de partenaires de protection contre les menaces mobiles (MTD) (un abonnement MTD est requis).</span><span class="sxs-lookup"><span data-stu-id="a36ba-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-587">Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).</span><span class="sxs-lookup"><span data-stu-id="a36ba-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="a36ba-588">Inscription de périphériques de chaque plateforme prise en charge sur Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="a36ba-589">Fournir des conseils sur la protection des applications sur :</span><span class="sxs-lookup"><span data-stu-id="a36ba-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-590">Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.</span><span class="sxs-lookup"><span data-stu-id="a36ba-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-591">Configuration des stratégies d’accès conditionnel pour les applications gérées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-592">Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées précédemment.</span><span class="sxs-lookup"><span data-stu-id="a36ba-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-593">Utilisation des rapports d’utilisation des applications gérées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-594">Fourniture d’instructions de migration de la gestion des PC hérités vers la gestion des ordinateurs de groupe Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="a36ba-595">
 
</li>
</ul>
  
<strong>Attachement via le cloud</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="a36ba-596">Nous vous guidons tout au long de la préparation à l’attachement dans le cloud des environnements Configuration Manager existants avec Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="a36ba-597">Les étapes exactes dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="a36ba-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="a36ba-598">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-599">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-600">Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.</span><span class="sxs-lookup"><span data-stu-id="a36ba-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-601">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="a36ba-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-602">Fourniture de conseils pour la configuration hybride de la jointation Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a36ba-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-603">Fourniture d’instructions sur la configuration d’Azure AD pour l’inscription automatique À la gestion des fonctionnalités de gestion des plateformes (MDM).</span><span class="sxs-lookup"><span data-stu-id="a36ba-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-604">Fourniture d’instructions sur la façon de configurer la passerelle de gestion cloud lorsqu’elle est utilisée comme solution pour la cogestion de la gestion des appareils basés sur Internet à distance.</span><span class="sxs-lookup"><span data-stu-id="a36ba-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-605">Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-606">Installation du client Configuration Manager dans les appareils inscrits sur Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="a36ba-607"><strong>Déployer Outlook Mobile pour iOS et Android en toute sécurité</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook Mobile pour iOS et Android en toute sécurité dans votre organisation afin de vous assurer que toutes les applications requises sont installées pour vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="a36ba-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="a36ba-608">La procédure de déploiement sécurisé d’Outlook Mobile pour iOS et Android avec Intune dépend de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="a36ba-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="a36ba-609">Il peut inclure les suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-610">Téléchargement des applications Outlook pour iOS et Android, Microsoft Authenticator et le portail d’entreprise Intune via l’App Store d’Apple ou Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="a36ba-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-611">Fourniture d’instructions sur la configuration :</span><span class="sxs-lookup"><span data-stu-id="a36ba-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-612">Déploiement d’applications Outlook pour iOS et Android, Microsoft Authenticator et portail d’entreprise Intune avec Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-613">Stratégies de protection des applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-614">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-615">Stratégies de configuration d’application.</span><span class="sxs-lookup"><span data-stu-id="a36ba-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="a36ba-616">Les administrateurs informatiques doivent avoir une autorité de certification, un réseau sans fil et des infrastructures VPN existants qui fonctionnent déjà dans leurs environnements de production lors de la planification du déploiement de réseau sans fil et de profils VPN avec Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="a36ba-617"><strong>Remarque</strong>: l’avantage du service FastTrack n’inclut pas d’assistance pour la configuration des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats Push Apple MDM pour Intune.</span><span class="sxs-lookup"><span data-stu-id="a36ba-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="a36ba-618"><strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud.</span><span class="sxs-lookup"><span data-stu-id="a36ba-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="a36ba-619">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="a36ba-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="a36ba-620"><strong>Intune intégré à Microsoft Defender pour le point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="a36ba-621"><strong>Remarque</strong>: nous fournissons une assistance sur l’intégration d’Intune à Microsoft Defender pour Endpoint et la création de stratégies de conformité des appareils en fonction de son évaluation du niveau de risque Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="a36ba-622">Nous ne fournissons pas d’aide sur les achats, les licences ou l’activation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="a36ba-623">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.</span><span class="sxs-lookup"><span data-stu-id="a36ba-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="a36ba-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="a36ba-625">Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.</span><span class="sxs-lookup"><span data-stu-id="a36ba-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="a36ba-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="a36ba-626">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-627"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-627"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-628"><strong>Détails des conseils FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-628"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-629"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-629"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a36ba-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-631">Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique.</span><span class="sxs-lookup"><span data-stu-id="a36ba-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="a36ba-632">Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.</span><span class="sxs-lookup"><span data-stu-id="a36ba-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="a36ba-633">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-634">La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-635">Pointage de vos enregistrements MX (mail exchange) vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-636">Configuration de la fonctionnalité Microsoft Defender pour Office 365 si elle fait partie de votre service d’abonnement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="a36ba-637">Pour plus d’informations, voir la partie <strong>Microsoft Defender pour Office 365</strong> de ce tableau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-p126">La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="a36ba-p127">La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="a36ba-642">
  <strong>Remarque :</strong> Le service de réplication de boîtes aux lettres (MRS) tente de migrer des messages électroniques gérés par des droits d’information (IRM) de votre boîte aux lettres sur site vers la boîte aux lettres Exchange Online correspondante.</span><span class="sxs-lookup"><span data-stu-id="a36ba-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="a36ba-643">La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="a36ba-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-644">La configuration de ports de pare-feu.</span><span class="sxs-lookup"><span data-stu-id="a36ba-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-645">La configuration du DNS, y compris les enregistrements DMARC (Autodiscover, Sender Policy Framework) requis, DKIM (DomainKeys Identified Mail), DMARC (Domain-based Message Authentication, Reporting and Conformance) et MX (selon vos besoins).</span><span class="sxs-lookup"><span data-stu-id="a36ba-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-646">la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).</span><span class="sxs-lookup"><span data-stu-id="a36ba-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-647">La migration de messagerie de votre environnement de messagerie source vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-648">La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="a36ba-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="a36ba-649">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="a36ba-650">Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="a36ba-651">Votre environnement source doit avoir l’un des niveaux minimaux suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-652">Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.</span><span class="sxs-lookup"><span data-stu-id="a36ba-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-653">Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.</span><span class="sxs-lookup"><span data-stu-id="a36ba-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-654">Environnement G Suite unique (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="a36ba-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-655">Pour plus d’informations sur les fonctionnalités multigé géographiques, voir <a href="https://go.microsoft.com/fwlink/?linkid=872776">Fonctionnalités multigéo géographiques dans Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="a36ba-656">Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive Entreprise, Power BI Desktop et Skype Entreprise doivent se trouver à un niveau minimal défini dans la version système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="a36ba-657"><strong>Microsoft Defender pour Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-658">Pour plus d’informations, <strong>voir Microsoft Defender pour Office 365</strong> en matière de sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="a36ba-659"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-660">Pour plus d’informations, voir Gouvernance des <strong>informations Microsoft</strong> en matière de sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">de conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-661"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="a36ba-662">Pour plus d’informations, voir <strong>Protection des informations Microsoft</strong> en matière de sécurité et de <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-664">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-665">Confirmation de la demande minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour prendre en charge Teams.</span><span class="sxs-lookup"><span data-stu-id="a36ba-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-666">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-667">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="a36ba-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-668">Confirmation que Teams est activé sur votre client Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-669">Activation ou désactivation des licences utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-670">Évaluation du réseau pour Teams :</span><span class="sxs-lookup"><span data-stu-id="a36ba-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-671">Vérifications des ports et des points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="a36ba-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-672">Contrôles de la qualité de connexion.</span><span class="sxs-lookup"><span data-stu-id="a36ba-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-673">Estimations de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="a36ba-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="a36ba-674">Configuration de la stratégie d’application Teams (application web Teams, application de bureau Teams et application Teams pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="a36ba-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="a36ba-675">Le cas échéant, nous fournissons également des conseils pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-676">Appareils de salle Microsoft Teams :</span><span class="sxs-lookup"><span data-stu-id="a36ba-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="a36ba-677">Création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge répertoriés dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-678">Assistance à distance avec la configuration côté service des appareils de salles Microsoft Teams certifiés.</span><span class="sxs-lookup"><span data-stu-id="a36ba-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-679">Activation de l’audioconférence :</span><span class="sxs-lookup"><span data-stu-id="a36ba-679">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="a36ba-680">Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.</span><span class="sxs-lookup"><span data-stu-id="a36ba-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-681">Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="a36ba-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="a36ba-682">Système téléphonique :</span><span class="sxs-lookup"><span data-stu-id="a36ba-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-683">Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="a36ba-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-684">Conseils sur les forfaits d’appels<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(marchés disponibles)</a>:</span><span class="sxs-lookup"><span data-stu-id="a36ba-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-685">Affectation de numéros aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="a36ba-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-686">Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.</span><span class="sxs-lookup"><span data-stu-id="a36ba-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-687">Prise en charge des demandes de service de portage de numéro local au-delà de 999.</span><span class="sxs-lookup"><span data-stu-id="a36ba-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a36ba-688">Conseils de routage direct :</span><span class="sxs-lookup"><span data-stu-id="a36ba-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-689">Conseils de configuration de l’organisation pour la conception du routage direct des scénarios hébergés par des partenaires ou des scénarios déployés par le client pour un nombre de sites au plus de 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="a36ba-690">Révision de la configuration du contrôleur de frontière de session (SBC).</span><span class="sxs-lookup"><span data-stu-id="a36ba-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="a36ba-691">Assistance à distance avec la configuration du plan de numérotation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="a36ba-692">Configuration de l’itinéraire des voix.</span><span class="sxs-lookup"><span data-stu-id="a36ba-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="a36ba-693">Contournement de média et optimisation des médias locaux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="a36ba-694">Activation des événements en direct Teams.</span><span class="sxs-lookup"><span data-stu-id="a36ba-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-695">Configuration de l’organisation et intégration à Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="a36ba-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-696">Conseils pour la transition de Skype Entreprise vers Teams.</span><span class="sxs-lookup"><span data-stu-id="a36ba-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a36ba-697">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-698">Utilisateurs activés pour SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a36ba-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-699">Les boîtes aux lettres Exchange sont présentes (en ligne et en local dans une configuration hybride Exchange).</span><span class="sxs-lookup"><span data-stu-id="a36ba-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-700">Activation pour les groupes Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="a36ba-701">
  <strong>Remarque :</strong> Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas de stockage OneDrive Entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="a36ba-702">Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans des conversations sans stockage OneDrive Entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="a36ba-703">Teams ne prend pas en charge SharePoint en local.</span><span class="sxs-lookup"><span data-stu-id="a36ba-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="a36ba-704">
  <strong>Remarque :</strong> L’état idéal est que tous les utilisateurs ont leurs boîtes aux lettres sur Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a36ba-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="a36ba-705">Les utilisateurs avec des boîtes aux lettres locales doivent avoir leur identité synchronisée avec l’annuaire Office 365 via Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="a36ba-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="a36ba-706">Pour ces clients Exchange hybrides, si la boîte aux lettres de l’utilisateur est en local, l’utilisateur ne peut ni ajouter ni configurer de connecteurs.</span><span class="sxs-lookup"><span data-stu-id="a36ba-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="a36ba-707">Les programmes d’installation pour les clients de bureau Microsoft Teams Windows et Mac peuvent être téléchargés sur <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="a36ba-708"><strong>Outlook pour iOS et Android</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-709">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-710">Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.</span><span class="sxs-lookup"><span data-stu-id="a36ba-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-711">Configuration des comptes et accès à la boîte aux lettres Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a36ba-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-712">Sécurisation Outlook mobile (voir <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sécurisation Outlook pour iOS</a> et Android dans Exchange Online pour plus d’informations).</span><span class="sxs-lookup"><span data-stu-id="a36ba-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a36ba-713">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-714">Exchange Online configuré et licences attribuées.</span><span class="sxs-lookup"><span data-stu-id="a36ba-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-716">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-717">Attribution de licences Power BI.</span><span class="sxs-lookup"><span data-stu-id="a36ba-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-718">Déploiement de l'application Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a36ba-719">Les logiciels clients en ligne tels que Power BI Desktop doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-721">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-722">la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-723">l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-724">la configuration de la liste des ressources d’entreprise (ERP) ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-725">la création de votre premier projet.</span><span class="sxs-lookup"><span data-stu-id="a36ba-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a36ba-726">Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a36ba-727"><strong>Project Online Professionnel et Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-728">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-729">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-730">Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a36ba-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-731">Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="a36ba-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-732">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-733">Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-734">Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="a36ba-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a36ba-735">Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-736"><strong>SharePoint Online et OneDrive Entreprise</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-737">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-738">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="a36ba-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-739">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-740">la mise en service des utilisateurs et des licences ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="a36ba-741">l'activation de la création de sites pour votre administrateur SharePoint Online ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="a36ba-742">la planification des collections de sites ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="a36ba-743">la sécurisation du contenu et la gestion des autorisations ;</span><span class="sxs-lookup"><span data-stu-id="a36ba-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="a36ba-744">la configuration des fonctionnalités SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a36ba-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="a36ba-745">la configuration des fonctionnalités Environnement hybride SharePoint, telles que la recherche hybride, les sites hybrides, la taxonomie hybride, les types de contenu, la création de sites en libre-service hybride (SharePoint Server 2013 uniquement), le lanceur d’applications étendu, OneDrive Entreprise hybride et les sites extranet.</span><span class="sxs-lookup"><span data-stu-id="a36ba-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-746">Votre approche de migration.</span><span class="sxs-lookup"><span data-stu-id="a36ba-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="a36ba-747">Des instructions supplémentaires sont fournies pour OneDrive Entreprise en fonction de votre version SharePoint, par exemple :</span><span class="sxs-lookup"><span data-stu-id="a36ba-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-748">Identification des options d’intégration et examen de l’infrastructure réseau locale et en ligne et de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="a36ba-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-749">Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et mise en œuvre des exigences de synchronisation et d’identité, et identification de votre client OneDrive Entreprise synchronisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-750">Planification et mise en œuvre d’un déploiement unique pour tous les utilisateurs (ou d’un déploiement par phases).</span><span class="sxs-lookup"><span data-stu-id="a36ba-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-751">Attribution de licences, redirection des sites Mon site et des bibliothèques de documents personnels vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="a36ba-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="a36ba-752">Redirection ou déplacement de dossiers connus vers OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a36ba-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="a36ba-753">Déploiement de la synchronisation OneDrive Entreprise client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="a36ba-754">
  <strong>Migration des données</strong>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="a36ba-755">Pour plus d’informations sur l’utilisation FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="a36ba-756"><strong>Pour SharePoint hybride :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="a36ba-757">SharePoint configuration hybride inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, des OneDrive Entreprise, un lanceur d’applications étendu, des sites extranet et la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.</span><span class="sxs-lookup"><span data-stu-id="a36ba-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="a36ba-758">
  <strong>Remarque :</strong> La création de sites libre-service n’est pas limitée aux serveurs locaux SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="a36ba-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="a36ba-759">Pour activer SharePoint hybride, vous devez avoir l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.</span><span class="sxs-lookup"><span data-stu-id="a36ba-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="a36ba-760">
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue.</span><span class="sxs-lookup"><span data-stu-id="a36ba-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="a36ba-761">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide.</span><span class="sxs-lookup"><span data-stu-id="a36ba-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="a36ba-762">Pour plus d’informations, voir Niveaux de mise à jour publique <a href="https://go.microsoft.com/fwlink/?linkid=853548">minimale pour SharePoint fonctionnalités hybrides.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="a36ba-763">
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigé géographiques, voir Fonctionnalités <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigéo</a>géographiques dans OneDrive et SharePoint Online dans Office 365<em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="a36ba-765">Nous fournissons des conseils à distance pour l’activation Yammer Enterprise service.</span><span class="sxs-lookup"><span data-stu-id="a36ba-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="a36ba-766">Le logiciel client en ligne doit être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .</span><span class="sxs-lookup"><span data-stu-id="a36ba-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="a36ba-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="a36ba-767">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-768"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-768"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-769"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-769"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-770"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-770"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a36ba-771"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-772">Pour plus d’informations, <strong>voir Azure Active Directory (Azure AD)</strong> et Azure AD Premium <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="a36ba-773">#sécurité et conformité</span><span class="sxs-lookup"><span data-stu-id="a36ba-773">#security-and-compliance</span></span>
<td><span data-ttu-id="a36ba-774"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-774"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="a36ba-775">Pour plus d’informations sur Azure Information Protection, voir <strong>Protection des données Microsoft</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-775">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a36ba-776"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-776"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-777">Pour plus d’informations, <strong>voir Microsoft Intune</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-777">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="a36ba-778">Windows 10</span><span class="sxs-lookup"><span data-stu-id="a36ba-778">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-779"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-779"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-780"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-780"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-781"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-781"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a36ba-782"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-782"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-783">Nous fournissons des conseils pour la mise à niveau de Windows 7 Professionnel et Windows 8.1 Professional vers Windows 10 Entreprise.</span><span class="sxs-lookup"><span data-stu-id="a36ba-783">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="a36ba-784">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-784">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-785">Comprendre l’Windows 10 de votre entreprise.</span><span class="sxs-lookup"><span data-stu-id="a36ba-785">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-786">Évaluation de votre environnement source et des conditions requises (assurez-vous Microsoft Endpoint Configuration Manager niveau requis pour prendre en charge le déploiement Windows 10 déploiement).</span><span class="sxs-lookup"><span data-stu-id="a36ba-786">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-787">Déploiement de Windows 10 Entreprise et de Microsoft 365 Apps à l’aide Microsoft Endpoint Configuration Manager ou Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-787">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-788">Recommandations d’options pour évaluer vos applications Windows 10 applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-788">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-789">Activation de l’utilisation de Desktop Analytics et de conseils via la création d’un plan de déploiement Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="a36ba-789">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-790">Microsoft 365 Apps’évaluation de la compatibilité en tirant parti du tableau de bord de préparation Office 365 dans Configuration Manager ou avec la Shared Computer Toolkit de préparation autonome pour Office plus l’aide au déploiement Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a36ba-790">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-791">Création d’une liste de vérification de correction sur ce que vous devez faire pour mettre votre environnement source au niveau minimal requis pour un déploiement réussi.</span><span class="sxs-lookup"><span data-stu-id="a36ba-791">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-792">Fournir des conseils de mise à niveau pour vos appareils existants Windows 10 Entreprise s’ils répondent à la configuration matérielle requise.</span><span class="sxs-lookup"><span data-stu-id="a36ba-792">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-793">Fournir des instructions de mise à niveau pour prendre en charge votre mouvement de déploiement existant.</span><span class="sxs-lookup"><span data-stu-id="a36ba-793">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="a36ba-794">FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-794">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="a36ba-795">Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.</span><span class="sxs-lookup"><span data-stu-id="a36ba-795">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-796">Déploiement de Microsoft 365 Apps à l’aide de Configuration Manager dans le cadre du Windows 10 déploiement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-796">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="a36ba-797">Fournir des conseils pour aider votre organisation à rester à jour avec Windows 10 Entreprise et Microsoft 365 Apps l’aide de votre environnement Configuration Manager ou de votre Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-797">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="a36ba-798">
  
<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-798">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a36ba-799">Mettre à niveau Configuration Manager vers la branche actuelle.</span><span class="sxs-lookup"><span data-stu-id="a36ba-799">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-800">Créer des images personnalisées pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-800">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-801">Créer et prendre en charge des scripts de déploiement pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-801">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-802">Convertir un système Windows 10 à partir du BIOS vers Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="a36ba-802">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-803">Activer les fonctionnalités de sécurité Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-803">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-804">Configurer les services de déploiement Windows (WDS) pour le démarrage de l’environnement PXE (Preboot Execution Environment).</span><span class="sxs-lookup"><span data-stu-id="a36ba-804">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-805">Utiliser le Microsoft Deployment Toolkit (MDT) pour capturer et déployer des images Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a36ba-805">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-806">Utiliser l’outil de migration de l’état utilisateur (USMT).</span><span class="sxs-lookup"><span data-stu-id="a36ba-806">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="a36ba-807">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="a36ba-807">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="a36ba-808">Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-808">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-809">Système d’exploitation source : Windows 7 Entreprise ou Professional, Windows 8.1 Entreprise ou Professional.</span><span class="sxs-lookup"><span data-stu-id="a36ba-809">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-810">Appareils : facteur de forme de bureau, de bloc-notes ou de tablette.</span><span class="sxs-lookup"><span data-stu-id="a36ba-810">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-811">Système d’exploitation cible : fenêtre 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="a36ba-811">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="a36ba-812">Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-812">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-813">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a36ba-813">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-814">La version de Configuration Manager doit être prise en charge par la version Windows 10 cible.</span><span class="sxs-lookup"><span data-stu-id="a36ba-814">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="a36ba-815">Pour plus d’informations, voir le tableau de prise en charge de Configuration Manager de l’article <a href="/sccm/core/plan-design/configs/support-for-windows-10">Prise en charge de Windows 10 dans Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-815">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="a36ba-816"><strong>Microsoft Defender pour point de terminaison</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-816"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-817">Pour plus d’informations, <strong> voir Microsoft Defender for Endpoint</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-817">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="a36ba-818">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="a36ba-818">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-819"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-819"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-820"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-820"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-821"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-821"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a36ba-822"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-822"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="a36ba-823">Nous fournissons des conseils de déploiement pour l’intégration Windows Virtual Desktop (un service de virtualisation de bureau et d’application).</span><span class="sxs-lookup"><span data-stu-id="a36ba-823">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="a36ba-824">Windows Virtual Desktop tire parti de Windows 10 multisessage et est optimisé pour les Microsoft 365 Apps de Enterprise avec une sécurité et une gestion intégrées pour Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a36ba-824">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="a36ba-825">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-825">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="a36ba-826">Déploiement de Windows 10 Entreprise multisesse et de Microsoft 365 Apps pour Enterprise à l’aide des outils suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-826">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="a36ba-827">Image Marketplace Azure.</span><span class="sxs-lookup"><span data-stu-id="a36ba-827">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="a36ba-828">Image partagée.</span><span class="sxs-lookup"><span data-stu-id="a36ba-828">Shared image.</span></span></li>
<li><span data-ttu-id="a36ba-829">Office Déploiement Shared Computer Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="a36ba-829">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="a36ba-830">Configuration de Microsoft 365 Apps pour FSLogix dans un ordinateur Windows Virtual Desktop natif.</span><span class="sxs-lookup"><span data-stu-id="a36ba-830">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="a36ba-831">Pour FSLogix :</span><span class="sxs-lookup"><span data-stu-id="a36ba-831">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="a36ba-832">Déploiement de l’agent.</span><span class="sxs-lookup"><span data-stu-id="a36ba-832">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="a36ba-833">Configuration des conteneurs profil et Office de profil.</span><span class="sxs-lookup"><span data-stu-id="a36ba-833">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="a36ba-834">Configuration des exclusions de contenu et des redirections de dossiers pour Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a36ba-834">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="a36ba-835">Déploiement de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="a36ba-835">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="a36ba-836">Déploiement de Microsoft Teams optimisation.</span><span class="sxs-lookup"><span data-stu-id="a36ba-836">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="a36ba-837">

<strong>Ce qui suit est hors de portée</strong>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-837">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="a36ba-838">Project gestion du déploiement de l’infrastructure Windows Virtual Desktop du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-838">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="a36ba-839">Virtualisation et déploiement d’applications tierces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-839">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="a36ba-840">Création d’images personnalisées pour Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-840">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="a36ba-841">Migrations et scénarios impliquant VMware et Citrix.</span><span class="sxs-lookup"><span data-stu-id="a36ba-841">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="a36ba-842">Scénarios Linux.</span><span class="sxs-lookup"><span data-stu-id="a36ba-842">Linux scenarios.</span></span></li>
<li><span data-ttu-id="a36ba-843">Conversion ou migrations de profils utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a36ba-843">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="a36ba-844">Microsoft Endpoint Configuration Manager et Microsoft Endpoint Manager configuration pour Windows Virtual Desktop (y compris la correction et la gestion).</span><span class="sxs-lookup"><span data-stu-id="a36ba-844">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="a36ba-845">Microsoft 365 Defender avec Windows 10 sessions multiples.</span><span class="sxs-lookup"><span data-stu-id="a36ba-845">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="a36ba-846">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="a36ba-846">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="a36ba-847">Vous devez déjà avoir les choses suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-847">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="a36ba-848"><a href="/azure/virtual-desktop/overview#requirements">Windows licences Virtual Desktop requises.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-848"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="a36ba-849">Infrastructure <a href="/azure/virtual-desktop/overview">requise pour prendre en charge Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-849">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="a36ba-850">Storage pour les conteneurs de profil <a href="/azure/virtual-desktop/store-fslogix-profile">FSLogix dans Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="a36ba-851">Mise en réseau Azure :</span><span class="sxs-lookup"><span data-stu-id="a36ba-851">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="a36ba-852">Création et sous-réseau de réseau virtuel (VNET).</span><span class="sxs-lookup"><span data-stu-id="a36ba-852">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="a36ba-853">Pare-feu et groupes de sécurité réseau.</span><span class="sxs-lookup"><span data-stu-id="a36ba-853">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="a36ba-854">VPN et ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="a36ba-854">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="a36ba-855">Routage vers Azure à partir de l’local.</span><span class="sxs-lookup"><span data-stu-id="a36ba-855">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="a36ba-856">Règles de pare-feu pour autoriser la connectivité Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-856">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="a36ba-857">Pour plus d’informations, voir <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clients Bureau à distance pris en charge.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-857">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="a36ba-858">Configuration générale d’Azure AD :</span><span class="sxs-lookup"><span data-stu-id="a36ba-858">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="a36ba-859">Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-859">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="a36ba-860">Active Directory avec Azure AD Connecter azure.</span><span class="sxs-lookup"><span data-stu-id="a36ba-860">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="a36ba-861">Active Directory avec Azure AD Connecter local sur VPN ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="a36ba-861">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="a36ba-862">Services de domaine Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="a36ba-862">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="a36ba-863">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="a36ba-863">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-864"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-864"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-865"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-865"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-866"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-866"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a36ba-867"><strong>Soutien aux Applications</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-867"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="a36ba-868">L’App Assure est un service conçu pour résoudre les problèmes de Windows 10 et Microsoft 365 Apps compatibilité des applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-868">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="a36ba-869">Lorsque vous demandez le service Soutien aux applications, nous travaillons avec vous pour résoudre les problèmes d’application valides sans frais supplémentaires pour vous avec un abonnement éligible.</span><span class="sxs-lookup"><span data-stu-id="a36ba-869">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="a36ba-870">Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et Microsoft Edge et nous faisons tout ce qui est raisonnable pour résoudre les problèmes de compatibilité.</span><span class="sxs-lookup"><span data-stu-id="a36ba-870">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="a36ba-871">Nous fournissons une assistance de correction pour les applications déployées sur les produits Microsoft suivants :</span><span class="sxs-lookup"><span data-stu-id="a36ba-871">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="a36ba-872"><strong>Windows 10</strong> (y compris les appareils ARM64)</span><span class="sxs-lookup"><span data-stu-id="a36ba-872"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="a36ba-873"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="a36ba-873"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="a36ba-874"><strong>Microsoft Edge -</strong> Pour obtenir des conseils de déploiement, voir <a href="/DeployEdge/microsoft-edge-channels">Vue d’ensemble Microsoft Edge canaux de déploiement.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-874"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-875"><strong>Windows Virtual Desktop</strong> - Pour plus d’informations, voir <a href="/azure/virtual-desktop/overview">Qu’est-ce Windows Virtual Desktop ?</a> et Windows 10 Entreprise faq sur les <a href="/azure/virtual-desktop/windows-10-multisession-faq">sessions multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-875"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="a36ba-876">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-876">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a36ba-877">Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a36ba-877">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="a36ba-878">Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-878">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="a36ba-879">Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-879">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="a36ba-880">Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces.</span><span class="sxs-lookup"><span data-stu-id="a36ba-880">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="a36ba-881">Pour plus d’informations, consultez <a href="/sccm/desktop-analytics/overview">Analytique de bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-881">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="a36ba-882">Services uniquement pour le conditionnement des applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-882">App packaging-only services.</span></span> <span data-ttu-id="a36ba-883">Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-883">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="a36ba-884">

<strong>Les responsabilités du client sont les suivantes :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-884">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="a36ba-885">Création d’un inventaire d’applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-885">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="a36ba-886">Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a36ba-886">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="a36ba-887">
<strong>Remarque :</strong>  Microsoft ne peut pas apporter de modifications à votre code source.</span><span class="sxs-lookup"><span data-stu-id="a36ba-887">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="a36ba-888">Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications.</span><span class="sxs-lookup"><span data-stu-id="a36ba-888">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="a36ba-889">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="a36ba-889">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="a36ba-890"><strong>Windows 10 et Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-890"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-891">Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a36ba-891">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="a36ba-892">
<strong>Windows 10 sur ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-892">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="a36ba-893">Les applications qui fonctionnaient sur Windows 7, Office 2010 ou versions ultérieures fonctionnent également sur Windows 10 et Microsoft 365 Apps sur les appareils ARM64.</span><span class="sxs-lookup"><span data-stu-id="a36ba-893">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="a36ba-894">
  <strong>Remarque :</strong> 
</span><span class="sxs-lookup"><span data-stu-id="a36ba-894">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="a36ba-895">L’émulation x64 (64 bits) est disponible en prévisualisation pour les clients participant au programme <a href="https://insider.windows.com/">Insider Windows.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-895">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="a36ba-896">Pour les clients insiders Windows sur Windows 10 version 2004 (ou ultérieure), ARM64 Photoshop est pris en charge à l’aide du pack de compatibilité OpenCL et <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="a36ba-896">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="a36ba-897">Les clients du Windows Insider peuvent télécharger une version Insider du pack de compatibilité OpenCL et OpenGL pour une utilisation avec des applications supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="a36ba-897">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="a36ba-898">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="a36ba-898">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-899">Si vos applications ou sites web fonctionnent sur Internet Explorer 11, les versions de Google Chrome ou toute version de Microsoft Edge, elles fonctionneront également avec Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="a36ba-899">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-900">Comme le web évolue constamment, n’oubliez pas de passer en revue cette liste publiée des modifications connues concernant la compatibilité des <a href="/microsoft-edge/web-platform/site-impacting-changes">sites pour Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-900">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="a36ba-901">
  <strong>Windows Virtual Desktop</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-901">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a36ba-902">Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-902">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-903">Les applications s’exécutant sur n’importe quel environnement Windows 7 ou Windows 10 virtual desktop infrastructure (VDI) s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-903">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-904">Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a36ba-904">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="a36ba-905">
  <strong>Remarque : Windows 10 Entreprise</strong> exclusions et limitations de compatibilité à plusieurs sessions sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="a36ba-905">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="a36ba-906">Redirection limitée du matériel.</span><span class="sxs-lookup"><span data-stu-id="a36ba-906">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-907">Les applications ayant une grande quantité de A/V peuvent avoir une capacité réduite.</span><span class="sxs-lookup"><span data-stu-id="a36ba-907">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a36ba-908">Les applications 16 bits ne sont pas prises en charge pour les applications Windows Virtual Desktop 64 bits.</span><span class="sxs-lookup"><span data-stu-id="a36ba-908">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="a36ba-909">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="a36ba-909">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a36ba-910"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-910"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a36ba-911"><strong>FastTrack conseils détaillés</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-911"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a36ba-912"><strong>Attentes de l’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="a36ba-912"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a36ba-913"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="a36ba-913"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="a36ba-914">Nous fournissons des conseils sur le déploiement à distance, l’adoption et la compatibilité pour :</span><span class="sxs-lookup"><span data-stu-id="a36ba-914">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="a36ba-915">Déploiement de Microsoft Edge sur Windows 10 avec Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).</span><span class="sxs-lookup"><span data-stu-id="a36ba-915">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-916">Configuration des Microsoft Edge (à l’aide de stratégies de groupe ou de configuration d’application Intune et de stratégies d’application).</span><span class="sxs-lookup"><span data-stu-id="a36ba-916">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="a36ba-917">Inventaire de la liste des sites qui peuvent nécessiter une utilisation en mode Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="a36ba-917">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="a36ba-918">Activation du mode Internet Explorer avec la liste Enterprise sites existante.</span><span class="sxs-lookup"><span data-stu-id="a36ba-918">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="a36ba-919">(Pour plus d’informations, voir <a href="/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack</a>.</span><span class="sxs-lookup"><span data-stu-id="a36ba-919">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="a36ba-920">En outre, si vous avez une application web ou un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="a36ba-920">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="a36ba-921">Pour demander la prise en charge de la compatibilité pour Soutien aux applications, connectez-vous <a href="https://fasttrack.microsoft.com/portal#/signin">au portail FastTrack pour</a> démarrer un engagement.</span><span class="sxs-lookup"><span data-stu-id="a36ba-921">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="a36ba-922">Conseils de planification pour l’adoption edge et les instructions de configuration Recherche Microsoft des signets.</span><span class="sxs-lookup"><span data-stu-id="a36ba-922">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="a36ba-923">

<strong>Ce qui suit est hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a36ba-923">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="a36ba-924">Gestion de projet du déploiement Microsoft Edge du client.</span><span class="sxs-lookup"><span data-stu-id="a36ba-924">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="a36ba-925">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="a36ba-925">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

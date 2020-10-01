---
title: Produits et fonctionnalités
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Cette rubrique inclut des détails sur les scénarios de charge de travail pris en charge par FastTrack et sur l’environnement source requis avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui permet à votre environnement source de bénéficier de la configuration minimale requise pour une intégration réussie.
ms.openlocfilehash: a3477be6958dea88874bbc042445bbc693c10ffb
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/30/2020
ms.locfileid: "48320030"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="f72b9-104">Produits et fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="f72b9-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="f72b9-105">Services et scénarios pris en charge par FastTrack</span><span class="sxs-lookup"><span data-stu-id="f72b9-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="f72b9-106">Cette rubrique inclut des détails sur les scénarios de charge de travail pris en charge par FastTrack et sur l’environnement source requis avant de commencer.</span><span class="sxs-lookup"><span data-stu-id="f72b9-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="f72b9-107">En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui permet à votre environnement source de bénéficier de la configuration minimale requise pour une intégration réussie.</span><span class="sxs-lookup"><span data-stu-id="f72b9-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="f72b9-108">FastTrack fournit des conseils pour vous aider à utiliser les fonctionnalités principales (communes à tous les services Microsoft Online), puis à intégrer chaque service éligible :</span><span class="sxs-lookup"><span data-stu-id="f72b9-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="f72b9-109">Général</span><span class="sxs-lookup"><span data-stu-id="f72b9-109">General</span></span>](#general)
  - [<span data-ttu-id="f72b9-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="f72b9-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="f72b9-111">Sécurité & Enterprise Mobility</span><span class="sxs-lookup"><span data-stu-id="f72b9-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="f72b9-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f72b9-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="f72b9-113">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="f72b9-113">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="f72b9-114">Soutien aux Applications</span><span class="sxs-lookup"><span data-stu-id="f72b9-114">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="f72b9-115">Nouveau Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f72b9-115">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="f72b9-116">Pour plus d’informations sur les attentes en matière d’environnement source pour Office 365, consultez la rubrique [source Environment attentes for office 365 Office US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="f72b9-116">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="f72b9-117">Général</span><span class="sxs-lookup"><span data-stu-id="f72b9-117">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-118"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-118"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-119"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-119"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-120"><strong>Attentes en matière d’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-120"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f72b9-121"><strong>Intégration de base</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-121"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-122">Nous fournissons des conseils à distance sur l’intégration de base, qui implique la mise en service, le client et l’intégration des identités.</span><span class="sxs-lookup"><span data-stu-id="f72b9-122">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="f72b9-123">Il décrit également les étapes à suivre pour fournir une base pour les services d’intégration tels qu’Exchange Online, SharePoint Online et Microsoft Teams, y compris une <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion sur la sécurité, la connectivité réseau et la conformité</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-123">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="f72b9-124">L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.</span><span class="sxs-lookup"><span data-stu-id="f72b9-124">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="f72b9-125"></li>
</ul>  

<strong> Intégration des identités </strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-125"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="f72b9-126">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-126">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="f72b9-127">Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), y compris l’installation et la configuration d’Azure AD Connect (à forêt unique ou multi-forêt) et des licences (y compris les licences basées sur les groupes).</span><span class="sxs-lookup"><span data-stu-id="f72b9-127">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="f72b9-128">Création d’identités Cloud incluant l’importation et la gestion de licences en bloc, y compris l’utilisation de licences basées sur les groupes.</span><span class="sxs-lookup"><span data-stu-id="f72b9-128">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="f72b9-129">Sélection et activation de la méthode d’authentification appropriée pour votre parcours Cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="f72b9-129">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="f72b9-130">Activation des services ADFS (Active Directory Federation Services) pour les clients disposant d’une seule forêt Active Directory et d’identités synchronisées avec l’outil Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f72b9-130">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="f72b9-131">Cette opération nécessite Windows Server 2012 R2 Active Directory Federation Services 2,0 ou une version ultérieure.</span><span class="sxs-lookup"><span data-stu-id="f72b9-131">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="f72b9-132">Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</span><span class="sxs-lookup"><span data-stu-id="f72b9-132">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="f72b9-133">Migration des applications préintégrées (telles que les applications SaaS) d’AD FS vers Azure Active Directory pour l’authentification unique (SSO) pour Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f72b9-133">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="f72b9-134">Activation des intégrations de l’application SaaS avec l’authentification unique à partir de la Galerie Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-134">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="f72b9-135">Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, telles qu’elles sont répertoriées dans la <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">liste des didacticiels d’intégration des applications</a> (limitée aux applications SaaS et à la mise en service sortante de la Galerie AD AD).</span><span class="sxs-lookup"><span data-stu-id="f72b9-135">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="f72b9-136"><strong>Activation du réseau </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="f72b9-136"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="f72b9-137">Dans le cadre de l’avantage de FastTrack, nous vous conseillons de vous conformer aux meilleures pratiques pour vous connecter aux services Cloud afin de garantir les niveaux de performances les plus élevés de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-137">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="f72b9-138"><strong>Forêts Active Directory</strong> Ils ont le niveau de forêt fonctionnel défini sur Windows Server 2003 et versions ultérieures, avec la configuration de forêt suivante :</span><span class="sxs-lookup"><span data-stu-id="f72b9-138"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-139">Forêt Active Directory unique.</span><span class="sxs-lookup"><span data-stu-id="f72b9-139">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-140">Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .</span><span class="sxs-lookup"><span data-stu-id="f72b9-140">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-141">Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).</span><span class="sxs-lookup"><span data-stu-id="f72b9-141">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-142">Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-142">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-143">Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.</span><span class="sxs-lookup"><span data-stu-id="f72b9-143">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-144">Tâches requises pour la configuration du client et l’intégration à Azure Active Directory, si nécessaire.   </span><span class="sxs-lookup"><span data-stu-id="f72b9-144">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="f72b9-145">
  <strong>Indispensables</strong>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-145">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="f72b9-146">Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype entreprise est déployé, il doit être déployé dans la même forêt Active Directory qu’Exchange.</span><span class="sxs-lookup"><span data-stu-id="f72b9-146">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-147">Lors de l’implémentation de plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration multi-hybride Exchange, les espaces de noms UPN (nom d’utilisateur principal) partagés entre les forêts sources ne sont pas pris en charge.</span><span class="sxs-lookup"><span data-stu-id="f72b9-147">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="f72b9-148">Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés.</span><span class="sxs-lookup"><span data-stu-id="f72b9-148">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="f72b9-149">Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-149">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-150">Pour toutes les configurations à forêts multiples, le déploiement des services ADFS (Active Directory Federation Services) est hors de portée.</span><span class="sxs-lookup"><span data-stu-id="f72b9-150">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="f72b9-151">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.</span><span class="sxs-lookup"><span data-stu-id="f72b9-151">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-152"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-152"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-153">Nous fournissons des conseils de déploiement à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-153">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-154">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="f72b9-154">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-155">Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f72b9-155">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-156">Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="f72b9-156">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-157">Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.</span><span class="sxs-lookup"><span data-stu-id="f72b9-157">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-158">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-158">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-159">Sélection et configuration d’une installation locale ou dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="f72b9-159">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-160">Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.</span><span class="sxs-lookup"><span data-stu-id="f72b9-160">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-161">Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f72b9-161">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="f72b9-162">En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures d’Office et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour corriger le problème de compatibilité sans frais supplémentaires via le programme de garantie de l’application.</span><span class="sxs-lookup"><span data-stu-id="f72b9-162">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="f72b9-163">Pour plus d’informations, consultez la section <strong>vérifier l’application</strong> de <a href="#windows-10">Windows 10</a> .</span><span class="sxs-lookup"><span data-stu-id="f72b9-163">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f72b9-164">Le logiciel client en ligne doit être à un niveau minimal, comme défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-164">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-165"><strong>Intégrité du réseau</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-165"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-166">Nous fournissons des conseils à distance pour l’obtention et l’interprétation des données clés de connectivité réseau de votre environnement, qui illustrent l’alignement des sites de votre organisation sur les <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principes de la connectivité réseau de</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f72b9-166">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="f72b9-167">Cela met en évidence votre score réseau qui influe directement sur la rapidité de migration, l’expérience utilisateur, les performances de service et la fiabilité.</span><span class="sxs-lookup"><span data-stu-id="f72b9-167">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="f72b9-168">Nous vous proposons également des étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-168">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="f72b9-169">Accès au centre d’administration Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-169">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-170">Des versions à jour des applications Microsoft 365 sont requises.</span><span class="sxs-lookup"><span data-stu-id="f72b9-170">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-171">Services d’emplacement activés en fonction <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">des recommandations en matière de performances réseau dans le centre d’administration Microsoft 365 (version préliminaire)</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-171">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="f72b9-172">Office 365</span><span class="sxs-lookup"><span data-stu-id="f72b9-172">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-173"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-173"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-174"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-174"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-175"><strong>Attentes en matière d’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-175"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f72b9-176"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-176"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-177">Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique.</span><span class="sxs-lookup"><span data-stu-id="f72b9-177">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="f72b9-178">Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.</span><span class="sxs-lookup"><span data-stu-id="f72b9-178">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="f72b9-179">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-179">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-180">La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-180">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-181">Pointage de vos enregistrements MX (mail Exchange) vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-181">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-182">La configuration de la fonctionnalité DAV (ATP) d’Office 365 si elle fait partie de votre service d’abonnement.</span><span class="sxs-lookup"><span data-stu-id="f72b9-182">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="f72b9-183">Pour plus d’informations, reportez-vous à la partie <strong>Office 365 Advanced Threat Protection</strong> de ce tableau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-183">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-p113">La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="f72b9-p114">La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="f72b9-188">
  <strong>Remarque :</strong> Le service de réplication de boîtes aux lettres tente de migrer les e-mails de gestion des droits relatifs à l’information (IRM) à partir de votre boîte aux lettres locale vers la boîte aux lettres Exchange Online correspondante.</span><span class="sxs-lookup"><span data-stu-id="f72b9-188">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="f72b9-189">La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="f72b9-189">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="f72b9-190">La configuration de ports de pare-feu.</span><span class="sxs-lookup"><span data-stu-id="f72b9-190">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-191">La configuration d’un DNS, y compris les enregistrements de découverte automatique, SPF (Sender Policy Framework), DomainKeys Identified Identified Mail (DKIM), de création de message et de conformité (DMARC), ainsi que les enregistrements MX requis (le cas échéant).</span><span class="sxs-lookup"><span data-stu-id="f72b9-191">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-192">la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).</span><span class="sxs-lookup"><span data-stu-id="f72b9-192">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-193">La migration de messagerie de votre environnement de messagerie source vers Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-193">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-194">La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="f72b9-194">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="f72b9-195">
  <strong>Migration de données</strong>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-195">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f72b9-196">Pour plus d’informations sur l’utilisation de l’avantage FastTrack pour la migration de données vers Office 365, voir <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-196">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="f72b9-197">Votre environnement source doit avoir l’un des niveaux minimaux suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-197">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-198">Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.</span><span class="sxs-lookup"><span data-stu-id="f72b9-198">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-199">Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.</span><span class="sxs-lookup"><span data-stu-id="f72b9-199">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-200">Environnement G Suite unique (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="f72b9-200">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-201">Pour plus d’informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique <a href="https://go.microsoft.com/fwlink/?linkid=872776">fonctionnalités Multigéographiques dans Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-201">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-202">Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive entreprise, Power BI Desktop et Skype entreprise doivent être au niveau minimal défini dans <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Requirements for Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-202">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-203"><strong>Gouvernance des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-203"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-204">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-204">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-205">Gouvernance des informations.</span><span class="sxs-lookup"><span data-stu-id="f72b9-205">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-206">Étiquettes et stratégies de rétention.</span><span class="sxs-lookup"><span data-stu-id="f72b9-206">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-207">Gestion des enregistrements.</span><span class="sxs-lookup"><span data-stu-id="f72b9-207">Records management.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-208">Stratégies de suppression.</span><span class="sxs-lookup"><span data-stu-id="f72b9-208">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-209">Conformité des communications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-209">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-210">Gestion des risques d'initiés.</span><span class="sxs-lookup"><span data-stu-id="f72b9-210">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-211">EDiscovery avancée.</span><span class="sxs-lookup"><span data-stu-id="f72b9-211">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-212">Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</span><span class="sxs-lookup"><span data-stu-id="f72b9-212">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-213"><strong>Protection des informations Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-213"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-214">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-214">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-215">Classification des données.</span><span class="sxs-lookup"><span data-stu-id="f72b9-215">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-216">Types d'informations sensibles.</span><span class="sxs-lookup"><span data-stu-id="f72b9-216">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-217">Création de labels de sensibilité.</span><span class="sxs-lookup"><span data-stu-id="f72b9-217">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-218">Appliquer des labels de sensibilité.</span><span class="sxs-lookup"><span data-stu-id="f72b9-218">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-219">Étiquetage unifié.</span><span class="sxs-lookup"><span data-stu-id="f72b9-219">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-220">Des classificateurs avec capacité d’apprentissage.</span><span class="sxs-lookup"><span data-stu-id="f72b9-220">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-221">Connaître ses données avec l'explorateur de contenu et l'explorateur d'activités.</span><span class="sxs-lookup"><span data-stu-id="f72b9-221">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-222">Publication d'étiquettes à l'aide de politiques (manuelles et automatiques).</span><span class="sxs-lookup"><span data-stu-id="f72b9-222">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-223">Créer des politiques de prévention des pertes de données (DLP) pour les conversations et les canaux de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f72b9-223">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-224">Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</span><span class="sxs-lookup"><span data-stu-id="f72b9-224">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-225"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-225"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-226">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-226">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-227">Vérification de la configuration minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour la prise en charge de teams.</span><span class="sxs-lookup"><span data-stu-id="f72b9-227">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-228">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-228">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-229">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="f72b9-229">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-230">Confirmation que Teams est activé sur votre client Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-230">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-231">Activation ou désactivation des licences utilisateur.</span><span class="sxs-lookup"><span data-stu-id="f72b9-231">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-232">Évaluation du réseau pour teams :</span><span class="sxs-lookup"><span data-stu-id="f72b9-232">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-233">Vérifications des ports et des points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="f72b9-233">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-234">Contrôles de la qualité de connexion.</span><span class="sxs-lookup"><span data-stu-id="f72b9-234">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-235">Estimations de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="f72b9-235">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="f72b9-236">Configuration de la stratégie d’application Teams (Team Web App, application de bureau teams et Teams pour l’application iOS et Android).</span><span class="sxs-lookup"><span data-stu-id="f72b9-236">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-237">Le cas échéant, nous fournissons également des conseils pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-237">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-238">Appareils de salle Microsoft teams :</span><span class="sxs-lookup"><span data-stu-id="f72b9-238">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="f72b9-239">La création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge figurant dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils teams</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-239">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-240">Assistance à distance avec la configuration côté service des périphériques de salle Microsoft teams certifiés.</span><span class="sxs-lookup"><span data-stu-id="f72b9-240">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-241">Activation de l’audioconférence :</span><span class="sxs-lookup"><span data-stu-id="f72b9-241">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="f72b9-242">Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.</span><span class="sxs-lookup"><span data-stu-id="f72b9-242">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-243">Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="f72b9-243">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f72b9-244">Système téléphonique :</span><span class="sxs-lookup"><span data-stu-id="f72b9-244">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-245">Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="f72b9-245">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-246">Conseils pour les forfaits d’appels (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">marchés disponibles</a>) :</span><span class="sxs-lookup"><span data-stu-id="f72b9-246">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-247">Affectation de numéros aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="f72b9-247">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-248">Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.</span><span class="sxs-lookup"><span data-stu-id="f72b9-248">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-249">Prise en charge des demandes de service de portage de numéro local au-delà de 999.</span><span class="sxs-lookup"><span data-stu-id="f72b9-249">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-250">Guide de routage direct :</span><span class="sxs-lookup"><span data-stu-id="f72b9-250">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-251">Guide de configuration de l’Organisation pour le routage direct de scénarios hébergés par un partenaire ou de scénarios déployés par le client pour un maximum de 10 sites.</span><span class="sxs-lookup"><span data-stu-id="f72b9-251">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="f72b9-252">Vérification de la configuration du contrôleur de frontière de session (SBC).</span><span class="sxs-lookup"><span data-stu-id="f72b9-252">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="f72b9-253">Assistance à distance avec la configuration du plan de numérotation.</span><span class="sxs-lookup"><span data-stu-id="f72b9-253">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="f72b9-254">Configuration de l’itinéraire des communications vocales.</span><span class="sxs-lookup"><span data-stu-id="f72b9-254">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="f72b9-255">Déviation du trafic multimédia et optimisation des supports locaux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-255">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="f72b9-256">Activation des événements en direct Teams.</span><span class="sxs-lookup"><span data-stu-id="f72b9-256">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-257">Configuration de l’organisation et intégration à Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="f72b9-257">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-258">Instructions pour la transition entre Skype entreprise et Teams.</span><span class="sxs-lookup"><span data-stu-id="f72b9-258">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f72b9-259">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-259">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-260">Utilisateurs activés pour SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f72b9-260">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-261">Des boîtes aux lettres Exchange sont présentes (en ligne et en local dans une configuration hybride Exchange).</span><span class="sxs-lookup"><span data-stu-id="f72b9-261">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-262">Activation pour les groupes Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-262">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="f72b9-263">
  <strong>Remarque :</strong>   Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas de stockage OneDrive entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-263">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f72b9-264">Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans les conversations sans espace de stockage OneDrive entreprise dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-264">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f72b9-265">Teams ne prend pas en charge SharePoint en local.</span><span class="sxs-lookup"><span data-stu-id="f72b9-265">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="f72b9-266">
  <strong>Remarque :</strong>   L’état idéal est que les boîtes aux lettres de tous les utilisateurs soient hébergées sur Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f72b9-266">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="f72b9-267">Les utilisateurs disposant de boîtes aux lettres hébergées sur site doivent être synchronisés avec l’annuaire Office 365 via Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f72b9-267">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="f72b9-268">Pour ces clients hybrides Exchange, si la boîte aux lettres de l’utilisateur est locale, l’utilisateur ne peut pas ajouter ni configurer de connecteurs.</span><span class="sxs-lookup"><span data-stu-id="f72b9-268">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="f72b9-269">Les programmes d’installation pour les clients de bureau Microsoft teams Windows et Mac peuvent être téléchargés à partir de  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .</span><span class="sxs-lookup"><span data-stu-id="f72b9-269">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-270"><strong>Office 365 – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-270"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-271">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-272">Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.</span><span class="sxs-lookup"><span data-stu-id="f72b9-272">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-273">Configuration de l’automatisation, de l’investigation et de la réponse.</span><span class="sxs-lookup"><span data-stu-id="f72b9-273">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-274">Utilisation du Simulateur d’attaques.</span><span class="sxs-lookup"><span data-stu-id="f72b9-274">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-275">Création de rapports et analytique des menaces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-275">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-276">Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</span><span class="sxs-lookup"><span data-stu-id="f72b9-276">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-277"><strong>Outlook pour iOS et Android</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-277"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-278">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-279">Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.</span><span class="sxs-lookup"><span data-stu-id="f72b9-279">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-280">Configuration des comptes et accès à la boîte aux lettres Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f72b9-280">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-281">Sécurisation d’Outlook Mobile (pour plus d’informations, consultez la rubrique <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">sécurisation d’Outlook pour iOS et Android dans Exchange Online</a> ).</span><span class="sxs-lookup"><span data-stu-id="f72b9-281">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f72b9-282">Identités activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-282">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-283">Exchange Online configuré et licences attribuées.</span><span class="sxs-lookup"><span data-stu-id="f72b9-283">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-284"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-284"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-285">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-285">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-286">Attribution de licences Power BI.</span><span class="sxs-lookup"><span data-stu-id="f72b9-286">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-287">Déploiement de l'application Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="f72b9-287">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-288">Les logiciels clients en ligne tels que Power BI Desktop doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-288">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-289"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-289"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-290">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-291">la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-291">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-292">l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-292">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-293">la configuration de la liste des ressources d’entreprise (ERP) ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-293">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-294">la création de votre premier projet.</span><span class="sxs-lookup"><span data-stu-id="f72b9-294">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-295">Les logiciels clients en ligne tels que Project pour Office 365 doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-295">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-296"><strong>Project Online professionnel et Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-296"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-297">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-297">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-298">Résolution des problèmes de déploiement.</span><span class="sxs-lookup"><span data-stu-id="f72b9-298">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-299">Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f72b9-299">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-300">Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.</span><span class="sxs-lookup"><span data-stu-id="f72b9-300">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-301">Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-301">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-302">Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-302">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-303">Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="f72b9-303">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-304">Les logiciels clients en ligne tels que Project pour Office 365 doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-304">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-305"><strong>SharePoint Online et OneDrive Entreprise</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-305"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-306">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-306">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-307">Configuration de DNS.</span><span class="sxs-lookup"><span data-stu-id="f72b9-307">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-308">la configuration de ports de pare-feu ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-308">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-309">la mise en service des utilisateurs et des licences ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-309">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="f72b9-310">l'activation de la création de sites pour votre administrateur SharePoint Online ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-310">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="f72b9-311">la planification des collections de sites ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-311">Planning site collections.</span></span></li>
<li><span data-ttu-id="f72b9-312">la sécurisation du contenu et la gestion des autorisations ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-312">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="f72b9-313">la configuration des fonctionnalités SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f72b9-313">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="f72b9-314">la configuration des fonctionnalités Environnement hybride SharePoint, telles que la recherche hybride, les sites hybrides, la taxonomie hybride, les types de contenu, la création de sites en libre-service hybride (SharePoint Server 2013 uniquement), le lanceur d’applications étendu, OneDrive Entreprise hybride et les sites extranet.</span><span class="sxs-lookup"><span data-stu-id="f72b9-314">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-315">Votre approche de migration.</span><span class="sxs-lookup"><span data-stu-id="f72b9-315">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-316">Des conseils supplémentaires sont fournis pour OneDrive entreprise en fonction de votre version de SharePoint, par exemple :</span><span class="sxs-lookup"><span data-stu-id="f72b9-316">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-317">L’identification des options d’intégration et la vérification de la bande passante et de l’infrastructure réseau locale et en ligne ;</span><span class="sxs-lookup"><span data-stu-id="f72b9-317">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-318">Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et implémentation des exigences en matière de synchronisation et d’identité, et identification de votre client de synchronisation OneDrive entreprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-318">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-319">La planification et l’implémentation d’un déploiement unique pour tous les utilisateurs (ou un déploiement échelonné).</span><span class="sxs-lookup"><span data-stu-id="f72b9-319">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-320">Attribution de licences, redirection de mes sites et de mes bibliothèques de documents personnelles vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="f72b9-320">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="f72b9-321">Redirection ou transfert de dossiers connus vers OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f72b9-321">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="f72b9-322">Déploiement de la synchronisation du client OneDrive entreprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-322">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="f72b9-323">
  <strong>Migration de données</strong>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-323">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f72b9-324">Pour plus d’informations sur l’utilisation de l’avantage FastTrack pour la migration de données vers Office 365, voir <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-324">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="f72b9-325"><strong>Pour SharePoint hybride :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-325"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f72b9-326">La configuration SharePoint hybride inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, de OneDrive entreprise, d’un lanceur d’applications étendu, de sites extranet et de la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.</span><span class="sxs-lookup"><span data-stu-id="f72b9-326">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="f72b9-327">
  <strong>Remarque :</strong> La création de sites en libre-service n’est pas dans l’étendue avec les serveurs locaux exécutant SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="f72b9-327">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="f72b9-328">Pour activer SharePoint hybride, vous devez disposer de l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.</span><span class="sxs-lookup"><span data-stu-id="f72b9-328">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="f72b9-329">
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue.</span><span class="sxs-lookup"><span data-stu-id="f72b9-329">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="f72b9-330">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide.</span><span class="sxs-lookup"><span data-stu-id="f72b9-330">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="f72b9-331">Pour plus d’informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=853548">niveaux de mise à jour publique minimum pour les fonctionnalités hybrides SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-331">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="f72b9-332">
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique <a href="https://go.microsoft.com/fwlink/?linkid=831056">fonctionnalités Multigéographiques dans OneDrive et SharePoint Online dans Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-332">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-333"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-333"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="f72b9-334">Nous fournissons des conseils à distance pour l’activation du service Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-334">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="f72b9-335">Le logiciel client en ligne doit être à un niveau minimal, comme défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-335">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="f72b9-336">Sécurité & Enterprise Mobility</span><span class="sxs-lookup"><span data-stu-id="f72b9-336">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-337"><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-337"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-338">Nous fournissons des conseils à distance pour sécuriser vos identités Cloud dans les scénarios suivants.</span><span class="sxs-lookup"><span data-stu-id="f72b9-338">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f72b9-339">

<strong>Infrastructure de base sécurisée</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-339">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f72b9-340">La configuration et l’activation de l’authentification forte pour vos identités, notamment la protection avec Azure Multi-Factor Authentication (Multi-Factor Authentication) (Cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et l’self-service Password Reset (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f72b9-340">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-341">Pour les clients autres que Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.</span><span class="sxs-lookup"><span data-stu-id="f72b9-341">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-342">Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec un accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-342">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-343">Détection et blocage de l’utilisation de mots de passe faibles avec la protection par mot de passe Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-343">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-344">Sécurisation de l’accès à distance aux applications Web locales avec le proxy d’application Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-344">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-345">Activation de la détection et de la correction basées sur les risques avec Azure identity protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-345">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-346">L’activation d’un écran de connexion personnalisé, y compris le logo, le texte et les images avec personnalisation.</span><span class="sxs-lookup"><span data-stu-id="f72b9-346">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-347">Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="f72b9-347">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-348">Gestion de l’accès pour vos administrateurs Office 365 à l’aide de rôles administratifs intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateurs privilégiés.</span><span class="sxs-lookup"><span data-stu-id="f72b9-348">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-349">Configuration de la jointure Azure AD hybride.</span><span class="sxs-lookup"><span data-stu-id="f72b9-349">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-350">Configuration de la participation à Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-350">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f72b9-351">
  
<strong>Surveillance et création de rapports</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-351">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-352">Activation de la surveillance à distance pour AD FS, Azure AD Connect et des contrôleurs de domaine avec Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f72b9-352">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-353">
  
<strong>Govern</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-353">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-354">Gestion du cycle de vie de votre identité Azure AD et de son accès à l’aide de la gestion des droits Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-354">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f72b9-355">Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions Azure AD Access.</span><span class="sxs-lookup"><span data-stu-id="f72b9-355">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-356">Consulter les conditions d’utilisation d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-356">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-357">Gestion et contrôle de l’accès aux comptes d’administrateur privilégié grâce à Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f72b9-357">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-358">
  
<strong>Automatisation et efficacité </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-358">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-359">Activation du SSPR Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-359">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f72b9-360">Permettre aux utilisateurs de créer et de gérer leurs propres groupes de sécurité Cloud ou Office 365 avec la gestion des groupes libre-service Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-360">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-361">Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-361">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-362">Activation des groupes dynamiques Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-362">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-363">Organisation des applications dans le portail mes applications à l’aide de collections.</span><span class="sxs-lookup"><span data-stu-id="f72b9-363">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f72b9-364">Active Directory sur site et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration à Azure AD et les fonctionnalités Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f72b9-364">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f72b9-365"><strong>Azure Information Protection Premium (P2 ou EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-365"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-366">Nous fournissons des conseils sur la façon de :</span><span class="sxs-lookup"><span data-stu-id="f72b9-366">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-367">Activez et configurez votre client.</span><span class="sxs-lookup"><span data-stu-id="f72b9-367">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-368">Créer et configurer des étiquettes et des stratégies.</span><span class="sxs-lookup"><span data-stu-id="f72b9-368">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-369">Application de la protection des informations aux documents.</span><span class="sxs-lookup"><span data-stu-id="f72b9-369">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-370">Classifier et étiqueter automatiquement des informations dans les applications Office (telles que Word, PowerPoint, Excel et Outlook) exécutées sur Windows et utilisant le client Azure information protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-370">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-371">Utilisation des fichiers au repos avec l’analyseur Azure information protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-371">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-372">Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f72b9-372">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-373">Nous fournissons également des conseils pour appliquer la protection à l’aide des services Microsoft Azure Rights Management (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP).</span><span class="sxs-lookup"><span data-stu-id="f72b9-373">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="f72b9-374">Vous devez déjà :</span><span class="sxs-lookup"><span data-stu-id="f72b9-374">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-375">Utiliser Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-375">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-376">Utilisez Windows ou iOS (les autres systèmes d’exploitation sont hors de portée).</span><span class="sxs-lookup"><span data-stu-id="f72b9-376">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="f72b9-377">
<strong>Remarque</strong>: les ordinateurs et les appareils mobiles doivent s’exécuter sur un <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">système d’exploitation</a> qui prend en charge Azure information protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-377">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="f72b9-378">Disposez de vos emplacements de partage de fichiers principaux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-378">Have your main file share locations.</span></span>  </li><span data-ttu-id="f72b9-379">
<strong>Remarque</strong>: le support hybride requiert le connecteur AD RMS.</span><span class="sxs-lookup"><span data-stu-id="f72b9-379">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="f72b9-380">Disposer d’une taxonomie de classification approuvée.</span><span class="sxs-lookup"><span data-stu-id="f72b9-380">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-381">Comprenez les restrictions réglementaires relatives à votre gestion des clés protégées.</span><span class="sxs-lookup"><span data-stu-id="f72b9-381">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="f72b9-382">
</ul>
  
<strong>Scanneur Azure information protection</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-382">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="f72b9-383">Vous devez déjà :</span><span class="sxs-lookup"><span data-stu-id="f72b9-383">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="f72b9-384">Utilisez Windows Server 2012 R2 ou Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f72b9-384">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-385">Disposer d’une connexion Internet.</span><span class="sxs-lookup"><span data-stu-id="f72b9-385">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-386">Disposer de Microsoft SQL Server 2012 à partir d’une instance locale ou distante.</span><span class="sxs-lookup"><span data-stu-id="f72b9-386">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-387">Disposer d’un compte de service créé pour votre annuaire Active Directory local et synchronisé avec Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-387">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-388">Avez téléchargé AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="f72b9-388">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-389">Les étiquettes sont configurées pour la classification/la protection automatique.</span><span class="sxs-lookup"><span data-stu-id="f72b9-389">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-390"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-390"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-391">Nous fournissons des conseils sur la préparation à l’utilisation d’Intune en tant que fournisseur de service de gestion des appareils mobiles (MDM) et de gestion des applications mobiles (MAM) en nuage pour vos applications et appareils.</span><span class="sxs-lookup"><span data-stu-id="f72b9-391">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f72b9-392">Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="f72b9-392">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f72b9-393">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-393">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-394">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-394">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-395">Configuration des identités à utiliser par Intune en tirant parti de votre annuaire Active Directory local ou des identités Cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f72b9-395">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-396">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="f72b9-396">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-397">Configuration de votre autorité MDM, en fonction de vos besoins de gestion, notamment :</span><span class="sxs-lookup"><span data-stu-id="f72b9-397">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-398">Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.</span><span class="sxs-lookup"><span data-stu-id="f72b9-398">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-399">Recommandations en matière de gestion des appareils mobiles pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-399">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-400">Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.</span><span class="sxs-lookup"><span data-stu-id="f72b9-400">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-401">Configuration des stratégies de gestion et des services de gestion du service MDM tels que :</span><span class="sxs-lookup"><span data-stu-id="f72b9-401">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-402">Déploiement d’applications pour chaque plateforme prise en charge par le biais de liens Web ou de liens détaillés.</span><span class="sxs-lookup"><span data-stu-id="f72b9-402">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-403">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-403">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-404">Le déploiement de profils de messagerie, de réseaux sans fil et de VPN si vous disposez d’une autorité de certification, d’un réseau sans fil ou d’une infrastructure VPN existante dans votre organisation.</span><span class="sxs-lookup"><span data-stu-id="f72b9-404">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-405">Connexion à l’entrepôt de données Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-405">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-406">Intégration de Intune avec :</span><span class="sxs-lookup"><span data-stu-id="f72b9-406">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-407">Visionneuse d’équipe pour l’assistance à distance (un abonnement à la visionneuse d’équipe est requis).</span><span class="sxs-lookup"><span data-stu-id="f72b9-407">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-408">Solutions de partenariat mobile Threat Defense (MTD) (un abonnement MTD est requis).</span><span class="sxs-lookup"><span data-stu-id="f72b9-408">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-409">Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).</span><span class="sxs-lookup"><span data-stu-id="f72b9-409">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-410">Microsoft Defender ATP (Windows E5 ou Microsoft 365 E5 licences requises).</span><span class="sxs-lookup"><span data-stu-id="f72b9-410">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-411">Inscription de périphériques de chaque plateforme prise en charge sur Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-411">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f72b9-412">Fournir des conseils sur la protection des applications sur :</span><span class="sxs-lookup"><span data-stu-id="f72b9-412">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-413">Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.</span><span class="sxs-lookup"><span data-stu-id="f72b9-413">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-414">La configuration des stratégies d’accès conditionnel pour les applications gérées.</span><span class="sxs-lookup"><span data-stu-id="f72b9-414">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-415">Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées ci-dessus.</span><span class="sxs-lookup"><span data-stu-id="f72b9-415">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-416">Utilisation des rapports d’utilisation avec gestion des applications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-416">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-417">Fournir des conseils de migration à partir de la gestion de PC héritée vers Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="f72b9-417">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f72b9-418">
  <strong>Remarque</strong>: la gestion des PC hérités n’est plus prise en charge depuis le 15 octobre 2020.</span><span class="sxs-lookup"><span data-stu-id="f72b9-418">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="f72b9-419"></li>
</ul>
  
<strong>Attachement via le cloud</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-419"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f72b9-420">Nous vous guiderons tout au long de la préparation au Cloud : attachez des environnements Configuration Manager existants avec Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-420">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f72b9-421">Les étapes exactes dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="f72b9-421">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f72b9-422">La procédure inclut les étapes suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-422">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f72b9-423">Licences pour les utilisateurs finaux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-423">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-424">Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.</span><span class="sxs-lookup"><span data-stu-id="f72b9-424">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-425">Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.</span><span class="sxs-lookup"><span data-stu-id="f72b9-425">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-426">Fournir des conseils sur la configuration de la participation hybride Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f72b9-426">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-427">Fournir des conseils sur la configuration d’Azure AD pour l’inscription automatique MDM.</span><span class="sxs-lookup"><span data-stu-id="f72b9-427">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-428">Fourniture de conseils sur la configuration de la passerelle de gestion cloud.</span><span class="sxs-lookup"><span data-stu-id="f72b9-428">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-429">Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-429">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-430">Installation du client Configuration Manager dans les appareils inscrits sur Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-430">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f72b9-431"><strong>Déployer Outlook Mobile pour iOS et Android de manière sécurisée</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook Mobile pour iOS et Android de manière sécurisée dans votre organisation afin de vous assurer que toutes les applications requises sont installées sur vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="f72b9-431"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f72b9-432">Les étapes de déploiement sécurisé d’Outlook Mobile pour iOS et Android avec Intune dépendent de votre environnement source.</span><span class="sxs-lookup"><span data-stu-id="f72b9-432">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f72b9-433">Elle peut inclure les éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-433">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-434">Téléchargement des applications Outlook pour iOS et Android, Microsoft authentificateur et portail d’entreprise Intune via le magasin d’applications Apple ou Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f72b9-434">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-435">Fournir des conseils sur la configuration des éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-435">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-436">Le déploiement d’applications de portail d’entreprise Outlook pour iOS et Android, Microsoft Authenticator et Intune avec Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-436">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-437">Stratégies de protection des applications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-437">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-438">Stratégies d’accès conditionnel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-438">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-439">Stratégies de configuration de l’application.</span><span class="sxs-lookup"><span data-stu-id="f72b9-439">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="f72b9-440"><strong>Remarque</strong>: FastTrack ne prend pas en charge la sécurisation d’Outlook pour iOS et Android avec les stratégies de boîte aux lettres d’appareils mobiles Exchange.</span><span class="sxs-lookup"><span data-stu-id="f72b9-440"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="f72b9-441">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.</span><span class="sxs-lookup"><span data-stu-id="f72b9-441">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="f72b9-442">Les administrateurs informatiques doivent disposer d’une autorité de certification existante, d’un réseau sans fil et d’infrastructures VPN qui travaillent déjà dans leurs environnements de production lors de la planification du déploiement de profils réseau sans fil et VPN avec Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-442">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f72b9-443"><strong>Remarque</strong>: le service FastTrack n’inclut pas d’aide pour configurer ou configurer des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats poussés pour Intune.</span><span class="sxs-lookup"><span data-stu-id="f72b9-443"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f72b9-444"><strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud.</span><span class="sxs-lookup"><span data-stu-id="f72b9-444"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f72b9-445">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.</span><span class="sxs-lookup"><span data-stu-id="f72b9-445">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f72b9-446"><strong>Intune intégré avec Microsoft Defender - Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-446"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="f72b9-447"><strong>Remarque</strong>: nous fournissons une assistance sur l’intégration d’Intune avec Microsoft Defender ATP et sur la création de stratégies de conformité des appareils basées sur son évaluation du niveau de risque de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-447"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f72b9-448">Nous ne fournissons pas d’assistance pour l’achat, la gestion des licences ou l’activation.</span><span class="sxs-lookup"><span data-stu-id="f72b9-448">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f72b9-449">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.</span><span class="sxs-lookup"><span data-stu-id="f72b9-449">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f72b9-450"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-450"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f72b9-451">Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.</span><span class="sxs-lookup"><span data-stu-id="f72b9-451">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="f72b9-452"><strong>Déployer Outlook pour iOS et Android de manière sécurisée avec Intune </strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-452"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="f72b9-453">Identités utilisateur activées dans Azure AD pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-453">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-454">Exchange Online ou Exchange hybride configuré avec des licences utilisateur affectées.</span><span class="sxs-lookup"><span data-stu-id="f72b9-454">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="f72b9-455">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f72b9-455">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-456"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-456"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-457"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-457"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-458"><strong>Attentes en matière d’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-458"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f72b9-459"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-459"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-460">Nous fournissons des conseils pour la mise à niveau de Windows 7 professionnel et Windows 8,1 professionnel vers Windows 10 entreprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-460">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="f72b9-461">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-461">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-462">Comprendre votre intention Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-462">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-463">Évaluation de votre environnement source et de la configuration requise (Assurez-vous que le gestionnaire de configuration du point de terminaison Microsoft est mis à niveau vers le niveau requis pour prendre en charge le déploiement de Windows 10).</span><span class="sxs-lookup"><span data-stu-id="f72b9-463">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-464">Déploiement des applications Windows 10 entreprise et Microsoft 365 à l’aide du gestionnaire de configuration de point de terminaison Microsoft ou de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-464">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-465">Recommandations sur les options pour évaluer vos applications Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-465">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-466">Activation de l’analyse et des conseils de bureau par le biais de la création d’un plan de déploiement de l’analyse ordinateur de bureau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-466">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-467">Évaluation de la compatibilité des applications Microsoft 365 en tirant parti du tableau de bord de disponibilité Office 365 du gestionnaire de configuration ou de la boîte à outils de préparation autonome pour Office plus aide à déployer des applications Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-467">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-468">Création d’une liste de contrôle de correction sur ce que vous devez faire pour faire en sorte que votre environnement source réponde à la configuration minimale requise pour un déploiement réussi.</span><span class="sxs-lookup"><span data-stu-id="f72b9-468">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-469">Fournir des conseils de mise à niveau pour vos appareils existants vers Windows 10 entreprise s’ils répondent à la configuration matérielle requise pour l’appareil.</span><span class="sxs-lookup"><span data-stu-id="f72b9-469">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-470">Fournir des conseils de mise à niveau pour prendre en charge votre mouvement de déploiement existant.</span><span class="sxs-lookup"><span data-stu-id="f72b9-470">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="f72b9-471">FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-471">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="f72b9-472">Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.</span><span class="sxs-lookup"><span data-stu-id="f72b9-472">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-473">Déploiement d’applications Microsoft 365 à l’aide du gestionnaire de configuration dans le cadre du déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-473">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="f72b9-474">Fournir des conseils pour aider votre organisation à se tenir au courant des applications Windows 10 entreprise et Microsoft 365 à l’aide de votre environnement de gestionnaire de configuration existant ou de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-474">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="f72b9-475">
  <strong>Les éléments suivants sont hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-475">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f72b9-476">Mettre à niveau Configuration Manager vers la branche actuelle.</span><span class="sxs-lookup"><span data-stu-id="f72b9-476">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-477">Créer des images personnalisées pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-477">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-478">Créer et prendre en charge des scripts de déploiement pour le déploiement de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-478">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-479">Convertir un système Windows 10 à partir du BIOS vers Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="f72b9-479">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-480">Activer les fonctionnalités de sécurité Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-480">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-481">Configurer les services de déploiement Windows (WDS) pour le démarrage de l’environnement PXE (Preboot Execution Environment).</span><span class="sxs-lookup"><span data-stu-id="f72b9-481">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-482">Utiliser le Microsoft Deployment Toolkit (MDT) pour capturer et déployer des images Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-482">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-483">Utiliser l’outil de migration de l’état utilisateur (USMT).</span><span class="sxs-lookup"><span data-stu-id="f72b9-483">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-484">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="f72b9-484">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="f72b9-485">Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-485">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-486">Système d’exploitation source : Windows 7 entreprise ou professionnel, Windows 8,1 entreprise ou professionnel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-486">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-487">Appareils : ordinateur de bureau, bloc-notes ou format tablette.</span><span class="sxs-lookup"><span data-stu-id="f72b9-487">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-488">Système d’exploitation cible : fenêtre 10 entreprise.</span><span class="sxs-lookup"><span data-stu-id="f72b9-488">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="f72b9-489">Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-489">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-490">Gestionnaire de configuration de point de terminaison Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f72b9-490">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-491">La version du gestionnaire de configuration doit être prise en charge par la version cible de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-491">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="f72b9-492">Pour plus d’informations, reportez-vous au tableau de prise en charge du gestionnaire de configuration à la <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">prise en charge de Windows 10 dans Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-492">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="f72b9-493"><strong>Microsoft Defender – Protection avancée contre les menaces (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-493"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-494">Microsoft Defender – Protection avancée contre les menaces est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter et examiner les menaces avancées et à y répondre.</span><span class="sxs-lookup"><span data-stu-id="f72b9-494">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f72b9-495">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-496">Déploiement des technologies pour sécuriser vos points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="f72b9-496">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-497">Configuration de la protection des points de terminaison et des profils de restriction d’appareil.</span><span class="sxs-lookup"><span data-stu-id="f72b9-497">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-498">Évaluation de la version du système d’exploitation et de la gestion des périphériques (notamment Intune, le gestionnaire de configuration du point de terminaison Microsoft, les objets de stratégie de groupe (GPO) et les configurations tierces), ainsi que l’état de vos services AV Windows Defender ou d’autres logiciels de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="f72b9-498">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-499">Évaluation de l’état de vos services AV Windows ou d’un autre logiciel de sécurité de point de terminaison.</span><span class="sxs-lookup"><span data-stu-id="f72b9-499">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-500">Évaluation des proxys et des pare-feu pour limiter le trafic réseau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-500">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-501">Activation du service ATP Microsoft Defender en expliquant comment déployer un profil d’agent ATP à l’aide d’un point de terminaison intégré.</span><span class="sxs-lookup"><span data-stu-id="f72b9-501">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-502">Conseils de déploiement, assistance de configuration et formation sur :</span><span class="sxs-lookup"><span data-stu-id="f72b9-502">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-503">La gestion des menaces et des vulnérabilités.</span><span class="sxs-lookup"><span data-stu-id="f72b9-503">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-504">La réduction de la surface d’attaque.</span><span class="sxs-lookup"><span data-stu-id="f72b9-504">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-505">La nouvelle génération de protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-505">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-506">La détection de point de terminaison et réponse.</span><span class="sxs-lookup"><span data-stu-id="f72b9-506">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-507">Les enquêtes et résolutions automatiques.</span><span class="sxs-lookup"><span data-stu-id="f72b9-507">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-508">Le niveau de sécurité.</span><span class="sxs-lookup"><span data-stu-id="f72b9-508">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-509">Examen des simulations et des didacticiels (par exemple, scénarios de pratique, faux programme malveillant et enquêtes automatisées).</span><span class="sxs-lookup"><span data-stu-id="f72b9-509">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-510">Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-510">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-511">L’intégration d’Office 365 – Protection avancée contre les menaces avec Microsoft Defender – Protection avancée contre les menaces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-511">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-512">Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="f72b9-512">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-513">Les systèmes d’exploitation suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-513">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-514">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f72b9-514">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-515">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f72b9-515">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-516">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f72b9-516">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-517">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f72b9-517">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-518">Canal semi-annuel Windows Server (SAC) version 1803.</span><span class="sxs-lookup"><span data-stu-id="f72b9-518">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-519">macOS versions 10,13, 10,14 et 10,15.</span><span class="sxs-lookup"><span data-stu-id="f72b9-519">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f72b9-520">
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou le gestionnaire de configuration du point de terminaison de Microsoft (version 2002 ou ultérieure).</span><span class="sxs-lookup"><span data-stu-id="f72b9-520">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f72b9-521"></li>
</ul>

<strong>Les éléments suivants sont hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-521"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f72b9-522">Gestion de projet des activités de correction du client.</span><span class="sxs-lookup"><span data-stu-id="f72b9-522">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-523">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="f72b9-523">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-524">Gestion continue et réponse aux menaces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-524">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-525">Intégration ou configuration des agents Microsoft Defender - PACM suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-525">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-526">Windows Server 2008</span><span class="sxs-lookup"><span data-stu-id="f72b9-526">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-527">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f72b9-527">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-528">Linux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-528">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-529">Appareils mobiles (Android et iOS).</span><span class="sxs-lookup"><span data-stu-id="f72b9-529">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-530">Intégration et configuration du serveur :</span><span class="sxs-lookup"><span data-stu-id="f72b9-530">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-531">Configuration d’un serveur proxy pour les communications hors ligne.</span><span class="sxs-lookup"><span data-stu-id="f72b9-531">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-532">Configuration des packages de déploiement de Configuration Manager sur les instances et versions de gestionnaire de configuration de bas niveau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-532">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-533">Intégration de serveurs à Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="f72b9-533">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-534">Serveurs non gérés par le gestionnaire de configuration.</span><span class="sxs-lookup"><span data-stu-id="f72b9-534">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-535">intégration et configuration d’macOS :</span><span class="sxs-lookup"><span data-stu-id="f72b9-535">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-536">Déploiement basé sur Intune manuel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-536">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-537">Déploiement basé sur JAMF.</span><span class="sxs-lookup"><span data-stu-id="f72b9-537">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f72b9-538">Autre déploiement basé sur des produits MDM (Mobile Device Management).</span><span class="sxs-lookup"><span data-stu-id="f72b9-538">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-539">Déploiement manuel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-539">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-540">Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :</span><span class="sxs-lookup"><span data-stu-id="f72b9-540">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-541">Isolation basée sur le matériel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-541">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-542">Contrôle d’application.</span><span class="sxs-lookup"><span data-stu-id="f72b9-542">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-543">Exploit Protection.</span><span class="sxs-lookup"><span data-stu-id="f72b9-543">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-544">Pare-feu du réseau.</span><span class="sxs-lookup"><span data-stu-id="f72b9-544">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f72b9-545">Inscription ou configuration des Spécialistes des menaces Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f72b9-545">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-546">La configuration ou la formation, l’API de révision ou les connexions de gestion des événements et des informations de sécurité (SIEM).</span><span class="sxs-lookup"><span data-stu-id="f72b9-546">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-547">Inscription ou configuration de la Protection Microsoft contre les menaces (MTP).</span><span class="sxs-lookup"><span data-stu-id="f72b9-547">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-548">Formation ou conseils pour le repérage avancé.</span><span class="sxs-lookup"><span data-stu-id="f72b9-548">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-549">Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</span><span class="sxs-lookup"><span data-stu-id="f72b9-549">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="f72b9-550">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="f72b9-550">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="f72b9-551">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="f72b9-551">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-552"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-552"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-553"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-553"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-554"><strong>Attentes en matière d’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-554"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f72b9-555"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-555"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="f72b9-556">Nous fournissons des conseils de déploiement pour l’intégration à Windows Virtual Desktop (un service de virtualisation d’application et de bureau).</span><span class="sxs-lookup"><span data-stu-id="f72b9-556">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="f72b9-557">Windows Virtual Desktop tire parti de l’expérience multisession Windows 10 et est optimisé pour les applications Microsoft 365 pour entreprise avec une sécurité et une gestion intégrées pour Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f72b9-557">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="f72b9-558">Nous fournissons des conseils à distance pour :</span><span class="sxs-lookup"><span data-stu-id="f72b9-558">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="f72b9-559">Déployez votre environnement de bureau virtuel Windows avec les applications multisession Windows 10 entreprise et Microsoft 365 pour Enterprise à l’aide des éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-559">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="f72b9-560">Image Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="f72b9-560">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="f72b9-561">Image partagée.</span><span class="sxs-lookup"><span data-stu-id="f72b9-561">Shared image.</span></span></li>
<li><span data-ttu-id="f72b9-562">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="f72b9-562">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="f72b9-563">Configuration de FSLogix :</span><span class="sxs-lookup"><span data-stu-id="f72b9-563">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="f72b9-564">Déploiement de l’agent FSLogix avec le conteneur de profil.</span><span class="sxs-lookup"><span data-stu-id="f72b9-564">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="f72b9-565">Déploiement de l’agent FSLogix avec un conteneur Office.</span><span class="sxs-lookup"><span data-stu-id="f72b9-565">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="f72b9-566">Configuration du dossier FSLogix avec des exclusions de contenu.</span><span class="sxs-lookup"><span data-stu-id="f72b9-566">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="f72b9-567">Déploiement de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f72b9-567">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="f72b9-568">Déploiement de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f72b9-568">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="f72b9-569">Connexion à l’aide des clients de bureau virtuels Windows.</span><span class="sxs-lookup"><span data-stu-id="f72b9-569">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="f72b9-570">

<strong>Les éléments suivants sont hors de portée</strong>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-570">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="f72b9-571">Gestion de projet du déploiement de bureau virtuel Windows du client.</span><span class="sxs-lookup"><span data-stu-id="f72b9-571">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="f72b9-572">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="f72b9-572">On-site support.</span></span></li>
<li><span data-ttu-id="f72b9-573">Déploiement et virtualisation d’applications tierces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-573">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="f72b9-574">Images personnalisées.</span><span class="sxs-lookup"><span data-stu-id="f72b9-574">Custom images.</span></span></li>
<li><span data-ttu-id="f72b9-575">Migrations et scénarios impliquant VMware et Citrix.</span><span class="sxs-lookup"><span data-stu-id="f72b9-575">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="f72b9-576">Scénarios Linux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-576">Linux scenarios.</span></span></li>
<li><span data-ttu-id="f72b9-577">Conversion ou migrations de profils utilisateur.</span><span class="sxs-lookup"><span data-stu-id="f72b9-577">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="f72b9-578">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a>   pour obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="f72b9-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="f72b9-579">Vous devez déjà disposer des éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-579">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="f72b9-580"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Conditions requises en matière de licences de bureau virtuel Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-580"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="f72b9-581">Mise en réseau Azure :</span><span class="sxs-lookup"><span data-stu-id="f72b9-581">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="f72b9-582">Création de réseau virtuel (VNET) et création de sous-réseaux.</span><span class="sxs-lookup"><span data-stu-id="f72b9-582">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="f72b9-583">Groupes de sécurité du réseau et du pare-feu.</span><span class="sxs-lookup"><span data-stu-id="f72b9-583">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="f72b9-584">VPN et ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f72b9-584">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="f72b9-585">Routage vers Azure à partir de l’organisation locale.</span><span class="sxs-lookup"><span data-stu-id="f72b9-585">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="f72b9-586">Règles de pare-feu pour autoriser la connectivité au bureau virtuel Windows.</span><span class="sxs-lookup"><span data-stu-id="f72b9-586">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="f72b9-587">Pour plus d’informations, voir <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> prise en charge des clients de bureau à distance</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-587">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="f72b9-588">Installation générale d’Azure AD :</span><span class="sxs-lookup"><span data-stu-id="f72b9-588">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="f72b9-589">Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-589">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="f72b9-590">Active Directory avec Azure AD Connect dans Azure.</span><span class="sxs-lookup"><span data-stu-id="f72b9-590">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="f72b9-591">Active Directory avec Azure AD Connect sur site sur un réseau privé virtuel (VPN) ou ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f72b9-591">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="f72b9-592">Services de domaine Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="f72b9-592">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="f72b9-593">Soutien aux applications</span><span class="sxs-lookup"><span data-stu-id="f72b9-593">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-594"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-594"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-595"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-595"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-596"><strong>Produits pris en charge</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-596"><strong>Supported products</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-597"><strong>Soutien aux Applications</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-597"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="f72b9-598">Application s’assurer est un service conçu pour résoudre les problèmes liés à la compatibilité des applications avec Windows 10 et Microsoft 365 apps.</span><span class="sxs-lookup"><span data-stu-id="f72b9-598">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="f72b9-599">Lorsque vous demandez le service de garantie de l’application, nous vous aidons à résoudre les problèmes d’application valides sans coût supplémentaire pour vous avec un abonnement éligible.</span><span class="sxs-lookup"><span data-stu-id="f72b9-599">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="f72b9-600">Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et de Microsoft Edge et de tous les efforts raisonnables pour résoudre les problèmes de compatibilité.</span><span class="sxs-lookup"><span data-stu-id="f72b9-600">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="f72b9-601">Nous fournissons une aide aux corrections pour les applications déployées sur les produits Microsoft suivants :</span><span class="sxs-lookup"><span data-stu-id="f72b9-601">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="f72b9-602"><strong>Windows 10 </strong> (y compris les appareils ARM64)</span><span class="sxs-lookup"><span data-stu-id="f72b9-602"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="f72b9-603"><strong>Applications Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="f72b9-603"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="f72b9-604"><strong>Le nouveau Microsoft Edge-</strong> Pour obtenir des instructions de déploiement, consultez <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">la rubrique vue d’ensemble des canaux Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-604"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-605"><strong>Bureau</strong> - virtuel Windows Pour plus d’informations, consultez <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">la rubrique qu’est-ce que le bureau virtuel Windows ? et le</a> <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Forum aux questions sur Windows 10 entreprise multi-session</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-605"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="f72b9-606">

<strong>Les éléments suivants sont hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-606">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f72b9-607">Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f72b9-607">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="f72b9-608">Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-608">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="f72b9-609">Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-609">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="f72b9-610">Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces.</span><span class="sxs-lookup"><span data-stu-id="f72b9-610">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="f72b9-611">Pour plus d’informations, consultez <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Analytique de bureau</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-611">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="f72b9-612">Services uniquement pour le conditionnement des applications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-612">App packaging-only services.</span></span> <span data-ttu-id="f72b9-613">Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</span><span class="sxs-lookup"><span data-stu-id="f72b9-613">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="f72b9-614">

<strong>Les responsabilités du client sont les suivants :</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-614">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f72b9-615">Création d’un inventaire d’applications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-615">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="f72b9-616">Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f72b9-616">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="f72b9-617">
<strong>Remarque :</strong>  Microsoft ne peut pas modifier votre code source.</span><span class="sxs-lookup"><span data-stu-id="f72b9-617">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="f72b9-618">Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications.</span><span class="sxs-lookup"><span data-stu-id="f72b9-618">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="f72b9-619">Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.</span><span class="sxs-lookup"><span data-stu-id="f72b9-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="f72b9-620"><strong>Applications Windows 10 et Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-620"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-621">Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f72b9-621">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-622">
<strong>Windows 10 sur ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-622">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="f72b9-623">Les applications qui fonctionnaient sous Windows 7, Office 2010 ou des versions ultérieures fonctionnent sur les applications Windows 10 et Microsoft 365 sur les appareils ARM64.</span><span class="sxs-lookup"><span data-stu-id="f72b9-623">Apps that worked on Windows 7, Office 2010, or later versions work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="f72b9-624">
  <strong>Remarque :</strong> Les exclusions et limitations de Windows 10 sur ARM sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-624">
  <strong>Note:</strong> Windows 10 on ARM exclusions and limitations include:</span></span>
<ul>
<li>  
 <span data-ttu-id="f72b9-625">Applications qui reposent sur des pilotes logiciels qui ne sont pas compatibles avec ARM.</span><span class="sxs-lookup"><span data-stu-id="f72b9-625">Apps that rely on software drivers that aren’t compatible in ARM.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-626">Applications qui utilisent OpenGL ou OpenCL.</span><span class="sxs-lookup"><span data-stu-id="f72b9-626">Apps that use OpenGL or OpenCL.</span></span>   
  </li>
<li>  
  <span data-ttu-id="f72b9-627">Les applications sont uniquement disponibles dans 64 bits (x64).</span><span class="sxs-lookup"><span data-stu-id="f72b9-627">Apps only available in 64-bit (x64).</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-628">
<strong>Le nouveau Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="f72b9-628">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-629">Si vos applications ou sites Web fonctionnent sur Internet Explorer 11, les versions prises en charge de Google Chrome ou toute version de Microsoft Edge, ils fonctionnent également avec le nouveau Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f72b9-629">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-630">Lorsque le site Web est en perpétuelle évolution, veillez à consulter la liste publiée de la <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">compatibilité des sites connus-impact sur les modifications apportées à Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="f72b9-630">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-631">
  <strong>Bureau virtuel Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-631">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f72b9-632">Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="f72b9-632">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-633">Les applications qui s’exécutent sur un environnement VDI (Virtual Desktop Infrastructure) Windows 7 ou Windows 10 s’exécutent également sur Windows 7 entreprise et Windows 10 entreprise dans le cadre du bureau virtuel Windows.</span><span class="sxs-lookup"><span data-stu-id="f72b9-633">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-634">Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="f72b9-634">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="f72b9-635">
  <strong>Remarque :</strong> Les exclusions et limitations de compatibilité entre les sessions Windows 10 entreprise sont les suivantes :</span><span class="sxs-lookup"><span data-stu-id="f72b9-635">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="f72b9-636">Redirection limitée du matériel.</span><span class="sxs-lookup"><span data-stu-id="f72b9-636">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-637">Les applications ayant une grande quantité de A/V peuvent avoir une capacité réduite.</span><span class="sxs-lookup"><span data-stu-id="f72b9-637">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f72b9-638">Les applications 16 bits ne sont pas prises en charge pour les applications Windows Virtual Desktop 64 bits.</span><span class="sxs-lookup"><span data-stu-id="f72b9-638">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="f72b9-639">Le nouveau Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f72b9-639">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f72b9-640"><strong>Service</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-640"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f72b9-641"><strong>Détails de l’aide FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-641"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f72b9-642"><strong>Attentes en matière d’environnement source</strong></span><span class="sxs-lookup"><span data-stu-id="f72b9-642"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="f72b9-643"><strong>Microsoft Edge</strong> (pour les clients Windows 10 entreprise)</span><span class="sxs-lookup"><span data-stu-id="f72b9-643"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="f72b9-644">Nous fournissons des conseils de déploiement à distance et une assistance en matière de compatibilité pour : le déploiement de la nouvelle Microsoft Edge sur Windows 10 entreprise avec le gestionnaire de points de terminaison Microsoft (point de terminaison de configuration Microsoft ou Intune).</span><span class="sxs-lookup"><span data-stu-id="f72b9-644">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-645">Configuration de Microsoft Edge (à l’aide des stratégies de groupe ou des stratégies d’application et de configuration de l’application Intune).</span><span class="sxs-lookup"><span data-stu-id="f72b9-645">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="f72b9-646">Inventorier la liste des sites pouvant nécessiter une utilisation en mode Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="f72b9-646">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="f72b9-647">Activation du mode Internet Explorer avec la liste de sites d’entreprise existante.</span><span class="sxs-lookup"><span data-stu-id="f72b9-647">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="f72b9-648">En outre, si vous disposez d’une application Web ou d’un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="f72b9-648">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="f72b9-649">Pour plus d’informations, consultez la rubrique <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">application</a> Apto.</span><span class="sxs-lookup"><span data-stu-id="f72b9-649">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="f72b9-650">

<strong>Les éléments suivants sont hors de portée </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f72b9-650">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="f72b9-651">Gestion de projet du déploiement Microsoft Edge du client.</span><span class="sxs-lookup"><span data-stu-id="f72b9-651">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="f72b9-652">Support sur site.</span><span class="sxs-lookup"><span data-stu-id="f72b9-652">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>

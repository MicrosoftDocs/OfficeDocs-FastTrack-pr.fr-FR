---
title: Attente concernant l’environnement source
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 533063e2-2630-46f3-9a88-ad07bb7dac9a
description: Le Centre FastTrack vous fournit de l'aide pour définir des niveaux d'intégration avec votre environnement source (par exemple, si vous avez déjà des services dans votre environnement source que vous souhaitez déplacer vers Office 365).
ms.openlocfilehash: 6dfb952b85d26efcfee9b8dc5d6cd4c68a5fe0cd
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353631"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="bb73c-103">Attente concernant l’environnement source</span><span class="sxs-lookup"><span data-stu-id="bb73c-103">Source Environment Expectations</span></span>

<span data-ttu-id="bb73c-104">Le Centre FastTrack vous fournit de l'aide pour définir des niveaux d'intégration avec votre environnement source (par exemple, si vous avez déjà des services dans votre environnement source que vous souhaitez déplacer vers Office 365).</span><span class="sxs-lookup"><span data-stu-id="bb73c-104">The FastTrack Center Benefit provides guidance for you to set up levels of integration with your source environment (for example, if you already have services in your source environment that you want to move to Office 365).</span></span>
  
> [!NOTE]
> <span data-ttu-id="bb73c-105">Si l’intégration est requise, votre environnement source doit être à un niveau minimal pour cette application.</span><span class="sxs-lookup"><span data-stu-id="bb73c-105">If integration is required, your source environment must be at a minimum level for that application.</span></span> 
  
<span data-ttu-id="bb73c-106">Le tableau suivant indique les conditions attendues dans votre environnement source existant pour procéder à l’intégration.\*</span><span class="sxs-lookup"><span data-stu-id="bb73c-106">The following table shows expectations for your existing source environment for onboarding.\*</span></span>

|<span data-ttu-id="bb73c-107">**Activité**</span><span class="sxs-lookup"><span data-stu-id="bb73c-107">**Activity**</span></span>|<span data-ttu-id="bb73c-108">**Attente concernant l'environnement source**</span><span class="sxs-lookup"><span data-stu-id="bb73c-108">**Source environment expectation**</span></span>|
|:-----|:-----|
|<span data-ttu-id="bb73c-109">**Intégration de base**</span><span class="sxs-lookup"><span data-stu-id="bb73c-109">**Core onboarding**</span></span> | <span data-ttu-id="bb73c-110">Forêts Active Directory avec le niveau de forêts fonctionnel défini sur Windows Server 2003 ou version ultérieure, avec la configuration de forêts suivante :</span><span class="sxs-lookup"><span data-stu-id="bb73c-110">Active Directory forests with the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>  <br/>      <span data-ttu-id="bb73c-111">Forêt Active Directory unique.</span><span class="sxs-lookup"><span data-stu-id="bb73c-111">A single Active Directory forest.</span></span>  <br/>    <span data-ttu-id="bb73c-112">Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .</span><span class="sxs-lookup"><span data-stu-id="bb73c-112">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="bb73c-113">Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).</span><span class="sxs-lookup"><span data-stu-id="bb73c-113">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="bb73c-114">Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="bb73c-114">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  <br/>  <span data-ttu-id="bb73c-115">Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.</span><span class="sxs-lookup"><span data-stu-id="bb73c-115">Multiple Active Directory account forests, each with its own Exchange organization.</span></span> <br/> <br/> <span data-ttu-id="bb73c-116">**Remarque**  *Dans les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype Entreprise est déployé, il doit l'être dans la même forêt Active Directory qu'Exchange.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-116">**Note**  *For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.*</span></span>   <br/>  <br/>      <span data-ttu-id="bb73c-117">**Remarque**  *Lors de l’implémentation de plusieurs forêts Active Directory avec différentes organisations Exchange dans une configuration hybride complexe Exchange, les espaces de noms d’utilisateur principal (UPN) partagés entre les forêts source ne sont pas pris en charge. Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés. Pour plus d’informations, reportez-vous à la rubrique [Déploiements hybrides à forêts Active Directory multiples](https://go.microsoft.com/fwlink/?linkid=845444).*</span><span class="sxs-lookup"><span data-stu-id="bb73c-117">**Note**  *When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported. Primary SMTP namespaces between Exchange organizations should also be separated. For more information, see [Hybrid deployments with multiple Active Directory forests](https://go.microsoft.com/fwlink/?linkid=845444).*</span></span>     <br/>   <br/>   <span data-ttu-id="bb73c-118">**Remarque**  *Pour toutes les configurations à forêts multiples, le déploiement AD FS n'entre pas dans le cadre du Centre FastTrack.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-118">**Note**  *For all multiple forests configurations, AD FS deployment is out of scope for the FastTrack Center Benefit.*</span></span>           |
|<span data-ttu-id="bb73c-119">**Intégration d’Exchange Online**</span><span class="sxs-lookup"><span data-stu-id="bb73c-119">**Exchange Online onboarding**</span></span> | <span data-ttu-id="bb73c-120">Votre environnement doit disposer de l’un des niveaux minimaux suivants :</span><span class="sxs-lookup"><span data-stu-id="bb73c-120">Your environment must have one of the following minimum levels:</span></span>  <br/>  <span data-ttu-id="bb73c-121">Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.</span><span class="sxs-lookup"><span data-stu-id="bb73c-121">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  <br/>  <span data-ttu-id="bb73c-122">Environnement IBM Domino 7.0.3 et versions ultérieures unique ([Annexe A : Migration d'IBM Domino vers Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).</span><span class="sxs-lookup"><span data-stu-id="bb73c-122">A single IBM Domino 7.0.3 onward environment ([Appendix A - Migration from IBM Domino to Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).</span></span>  <br/>  <span data-ttu-id="bb73c-123">Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.</span><span class="sxs-lookup"><span data-stu-id="bb73c-123">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  <br/>  <span data-ttu-id="bb73c-124">Environnement G Suite unique (Gmail, contacts et calendrier uniquement).</span><span class="sxs-lookup"><span data-stu-id="bb73c-124">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  <br/>  <span data-ttu-id="bb73c-125">Environnement Novell GroupWise 7.0.4 et versions ultérieures unique.</span><span class="sxs-lookup"><span data-stu-id="bb73c-125">A single Novell GroupWise 7.0.4 onward environment.</span></span>  <br/><br/> <span data-ttu-id="bb73c-126">**Remarque**  *Pour obtenir plus d'informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique [Capacités multigéographiques dans Exchange Online](https://go.microsoft.com/fwlink/?linkid=872776).*</span><span class="sxs-lookup"><span data-stu-id="bb73c-126">**Note**  *For information on Multi-Geo Capabilities, see [Multi-Geo Capabilities in Exchange Online](https://go.microsoft.com/fwlink/?linkid=872776).*</span></span>           |
|<span data-ttu-id="bb73c-127">**Intégration de Sharepoint Online et de OneDrive Entreprise**</span><span class="sxs-lookup"><span data-stu-id="bb73c-127">**SharePoint Online and OneDrive for Business onboarding**</span></span>  | <span data-ttu-id="bb73c-128">**Environnement hybride SharePoint**</span><span class="sxs-lookup"><span data-stu-id="bb73c-128">**SharePoint Hybrid**</span></span>  <br/>  <span data-ttu-id="bb73c-p101">La configuration de Environnement hybride SharePoint inclut la configuration de la recherche hybride, de sites, de la taxonomie, de types de contenu, de OneDrive Entreprise, d'un lanceur d'applications étendu, de sites extranet et la création de sites en libre-service connectés en local à un seul environnement SharePoint Online cible. Pour activer Environnement hybride SharePoint, vous devez disposer de l'un des environnements locaux SharePoint Server suivants :  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p101">SharePoint Hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment. To enable SharePoint Hybrid, you must have one of the following on-premises SharePoint Server environments:  </span></span><br/> <br/> <span data-ttu-id="bb73c-131">***SharePoint Server 2013***</span><span class="sxs-lookup"><span data-stu-id="bb73c-131">***SharePoint Server 2013***</span></span>  <br/>  <span data-ttu-id="bb73c-p102">Mise à jour publique (PU) de juin 2017 pour les types de contenu hybride. Pour plus d’informations, reportez-vous à la rubrique [Configurer la taxonomie hybride de SharePoint et les types de contenu hybride](https://go.microsoft.com/fwlink/?linkid=853547).  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p102">June 2017 Public Update (PU) for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="bb73c-p103">PU de mars 2017 pour la configuration de la création de sites en libre-service. La création de sites en libre-service hybride est prise en charge uniquement avec SharePoint Server 2013. Pour plus d'informations, reportez-vous à [Création de sites en libre-service hybride](https://go.microsoft.com/fwlink/?linkid=846015).  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p103">March 2017 PU for self-service site creation configuration. Hybrid self-service site creation is only supported with SharePoint Server 2013. For more information, see [Hybrid self-service site creation](https://go.microsoft.com/fwlink/?linkid=846015).  </span></span><br/>  <span data-ttu-id="bb73c-p104">Version ultérieure avec PU de novembre 2016 avec taxonomie hybride. Pour plus d’informations, reportez-vous à la rubrique [Planifier la taxonomie hybride de SharePoint](https://go.microsoft.com/fwlink/?linkid=844867).  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p104">November 2016 PU onward with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="bb73c-139">Version ultérieure avec PU de juillet 2016 pour tous les autres scénarios de configuration hybride.</span><span class="sxs-lookup"><span data-stu-id="bb73c-139">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="bb73c-140">**Remarque**  *Les scénarios hybrides SharePoint Server 2013 sont uniquement pris en charge avec SharePoint Server 2013. Ces scénarios ne sont pas pris en charge dans SharePoint Foundation 2013.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-140">**Note**  *SharePoint Server 2013 hybrid scenarios are only supported with SharePoint Server 2013. These scenarios aren't supported in SharePoint Foundation 2013.*</span></span>  <br/>   <br/>    <span data-ttu-id="bb73c-141">***SharePoint Server 2016***</span><span class="sxs-lookup"><span data-stu-id="bb73c-141">***SharePoint Server 2016***</span></span>  <br/>  <span data-ttu-id="bb73c-p105">PU de juin 2017 pour les types de contenu hybride. Pour plus d’informations, reportez-vous à la rubrique [Configurer la taxonomie hybride de SharePoint et les types de contenu hybride](https://go.microsoft.com/fwlink/?linkid=853547).  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p105">June 2017 PU for hybrid content types. For more information, see [Configure hybrid SharePoint taxonomy and hybrid content types](https://go.microsoft.com/fwlink/?linkid=853547).  </span></span><br/>  <span data-ttu-id="bb73c-p106">PU de novembre 2016 (Feature Pack 1) avec taxonomie hybride. Pour plus d’informations, reportez-vous à la rubrique [Planifier la taxonomie hybride de SharePoint](https://go.microsoft.com/fwlink/?linkid=844867).  </span><span class="sxs-lookup"><span data-stu-id="bb73c-p106">November 2016 PU (Feature Pack 1) with hybrid taxonomy. For more information, see [Plan hybrid SharePoint taxonomy](https://go.microsoft.com/fwlink/?linkid=844867).  </span></span><br/>  <span data-ttu-id="bb73c-146">Version ultérieure avec PU de juillet 2016 pour tous les autres scénarios de configuration hybride.</span><span class="sxs-lookup"><span data-stu-id="bb73c-146">July 2016 PU onward for all other hybrid configuration scenarios.</span></span>  <br/><br/> <span data-ttu-id="bb73c-147">**Remarque**  *La mise à niveau d’environnements SharePoint en local vers SharePoint Server 2013 ou SharePoint Server 2016 n’est pas comprise dans les avantages du Centre FastTrack. Pour plus d’informations, reportez-vous à la rubrique [Niveaux de mise à jour publique minimale pour les fonctionnalités SharePoint hybrides](https://go.microsoft.com/fwlink/?linkid=853548).*</span><span class="sxs-lookup"><span data-stu-id="bb73c-147">**Note**  *Upgrade of on-premises SharePoint environments to SharePoint Server 2013 or SharePoint Server 2016 isn't provided by the FastTrack Center Benefit. For more information, see [Minimum public update levels for SharePoint hybrid features](https://go.microsoft.com/fwlink/?linkid=853548).*</span></span>   <br/><br/>        <span data-ttu-id="bb73c-148">**Remarque**  *Pour obtenir plus d'informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique [Capacités multigéographiques dans OneDrive et SharePoint Online dans Office 365](https://go.microsoft.com/fwlink/?linkid=831056).*</span><span class="sxs-lookup"><span data-stu-id="bb73c-148">**Note**  *For information on Multi-Geo Capabilities, see [Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365](https://go.microsoft.com/fwlink/?linkid=831056).*</span></span>           |
|<span data-ttu-id="bb73c-149">**Intégration de Skype Entreprise Online**</span><span class="sxs-lookup"><span data-stu-id="bb73c-149">**Skype for Business Online onboarding**</span></span>  | <span data-ttu-id="bb73c-150">**Évaluation du réseau**</span><span class="sxs-lookup"><span data-stu-id="bb73c-150">**Network assessment**</span></span>  <br/>  <span data-ttu-id="bb73c-151">Vérifications des ports et des points de terminaison.</span><span class="sxs-lookup"><span data-stu-id="bb73c-151">Port and endpoint checks.</span></span>  <br/>  <span data-ttu-id="bb73c-152">Contrôles de la qualité de connexion.</span><span class="sxs-lookup"><span data-stu-id="bb73c-152">Connection quality checks.</span></span>  <br/>  <span data-ttu-id="bb73c-153">Estimations de la bande passante.</span><span class="sxs-lookup"><span data-stu-id="bb73c-153">Bandwidth estimates.</span></span>  <br/><br/>  <span data-ttu-id="bb73c-154">**Lync hybride**</span><span class="sxs-lookup"><span data-stu-id="bb73c-154">**Lync Hybrid**</span></span>  <br/>  <span data-ttu-id="bb73c-155">Forêt Active Directory locale unique.</span><span class="sxs-lookup"><span data-stu-id="bb73c-155">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="bb73c-156">Environnement Lync Server 2010 avec outils d'administration Lync 2013 ou Skype Entreprise 2015, et un rôle serveur Edge Lync 2010.</span><span class="sxs-lookup"><span data-stu-id="bb73c-156">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  <br/>  <span data-ttu-id="bb73c-157">Environnement Lync Server 2013 et rôle serveur Edge Lync 2013.</span><span class="sxs-lookup"><span data-stu-id="bb73c-157">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  <br/><br/>  <span data-ttu-id="bb73c-158">**Skype Entreprise Online hybride**</span><span class="sxs-lookup"><span data-stu-id="bb73c-158">**Skype for Business Online Hybrid**</span></span>  <br/>  <span data-ttu-id="bb73c-159">Forêt Active Directory locale unique.</span><span class="sxs-lookup"><span data-stu-id="bb73c-159">A single on-premises Active Directory forest.</span></span>  <br/>  <span data-ttu-id="bb73c-160">Topologies avec forêt de ressources et forêt de comptes unique (Exchange et/ou Skype Entreprise) Active Directory.</span><span class="sxs-lookup"><span data-stu-id="bb73c-160">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  <br/>  <span data-ttu-id="bb73c-161">Forêts de comptes Active Directory multiples, avec une forêt qui est une forêt de comptes Active Directory centralisée contenant Exchange et/ou Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="bb73c-161">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  <br/>  <span data-ttu-id="bb73c-162">Environnement Skype Entreprise Server 2015 contenant un rôle serveur Edge Skype Entreprise.</span><span class="sxs-lookup"><span data-stu-id="bb73c-162">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  <br/><br/> <span data-ttu-id="bb73c-163">**Remarque**  *Ce service supplémentaire est destiné à la configuration et à la validation des tâches de domaine fractionné (hybride) et n'inclut pas la présentation des composants locaux (par exemple, outils d'administration Lync 2013 ou serveurs Lync 2013/Skype Entreprise Online, ou serveurs Edge Lync 2010, Lync 2013 ou Skype Entreprise).*</span><span class="sxs-lookup"><span data-stu-id="bb73c-163">**Note**  *This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).*</span></span>    <br/><br/>        <span data-ttu-id="bb73c-164">**Appareil de salle de conférence**</span><span class="sxs-lookup"><span data-stu-id="bb73c-164">**Conference room device**</span></span>  <br/>  <span data-ttu-id="bb73c-165">Création de comptes en ligne nécessaires pour les appareils de salle de conférence pris en charge répertoriés dans l'onglet Systèmes de salle de réunion dans le [catalogue de solutions Skype Entreprise](https://go.microsoft.com/fwlink/?LinkId=615775).</span><span class="sxs-lookup"><span data-stu-id="bb73c-165">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the [Skype for Business Solutions Catalog](https://go.microsoft.com/fwlink/?LinkId=615775).</span></span>  <br/><br/>  <span data-ttu-id="bb73c-166">**Activation de l’audioconférence**</span><span class="sxs-lookup"><span data-stu-id="bb73c-166">**Enabling Audio Conferencing**</span></span>  <br/>  <span data-ttu-id="bb73c-167">Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.</span><span class="sxs-lookup"><span data-stu-id="bb73c-167">Organization setup for conference bridge default settings.</span></span>  <br/>  <span data-ttu-id="bb73c-168">Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="bb73c-168">Assignment of conference bridge to licensed users.</span></span>  <br/><br/>  <span data-ttu-id="bb73c-169">**Recommandations sur l’activation du système téléphonique et les forfaits d’appel (États-Unis uniquement)**</span><span class="sxs-lookup"><span data-stu-id="bb73c-169">**Enabling Phone System and Calling Plans guidance (US only)**</span></span>  <br/>  <span data-ttu-id="bb73c-170">Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.</span><span class="sxs-lookup"><span data-stu-id="bb73c-170">Organization setup for Cloud Voice default settings.</span></span>  <br/>  <span data-ttu-id="bb73c-171">Affectation de numéros aux utilisateurs titulaires d’une licence.</span><span class="sxs-lookup"><span data-stu-id="bb73c-171">Assignment of numbers to licensed users.</span></span>  <br/>  <span data-ttu-id="bb73c-172">Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.</span><span class="sxs-lookup"><span data-stu-id="bb73c-172">Local number porting guidance through user interface (UI) up to 999.</span></span>  <br/>  <span data-ttu-id="bb73c-173">Prise en charge des demandes de service de portage de numéro local au-delà de 999.</span><span class="sxs-lookup"><span data-stu-id="bb73c-173">Local number porting service request (SR) support over 999.</span></span>  <br/><br/>  <span data-ttu-id="bb73c-174">**Activation de l’intégration d’instructions pour la diffusion de réunion Skype Entreprise**</span><span class="sxs-lookup"><span data-stu-id="bb73c-174">**Enabling Skype for Business Meeting Broadcast guidance onboarding**</span></span>  <br/>  <span data-ttu-id="bb73c-175">Configuration de l’organisation pour la fédération avec le service de diffusion de réunion.</span><span class="sxs-lookup"><span data-stu-id="bb73c-175">Organization setup for federation with Meeting Broadcast service.</span></span>   |
|<span data-ttu-id="bb73c-176">**Intégration de Microsoft Teams**</span><span class="sxs-lookup"><span data-stu-id="bb73c-176">**Microsoft Teams onboarding**</span></span>  | <span data-ttu-id="bb73c-177">Identités activées dans Azure Active Directory pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="bb73c-177">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/>  <span data-ttu-id="bb73c-178">Utilisateurs activés pour SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bb73c-178">Users enabled for SharePoint Online.</span></span>  <br/>  <span data-ttu-id="bb73c-179">Exchange boîtes aux lettres sont présentes (en ligne et/ou en local dans une configuration hybride Exchange).</span><span class="sxs-lookup"><span data-stu-id="bb73c-179">Exchange mailboxes are present (online and/or on-premises in an Exchange hybrid configuration).</span></span>  <br/>  <span data-ttu-id="bb73c-180">Activation pour les groupes Office 365.</span><span class="sxs-lookup"><span data-stu-id="bb73c-180">Enabled for Office 365 Groups.</span></span>  <br/><br/> <span data-ttu-id="bb73c-181">**Remarque**  *Si les utilisateurs ne disposent pas de licences SharePoint Online, ils ne peuvent pas bénéficier du stockage OneDrive Entreprise dans Office 365. Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans des conversations sans le stockage OneDrive Entreprise dans Office 365. Microsoft Teams ne prend pas en charge SharePoint en local.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-181">**Note**  *If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365. File sharing will continue to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365. Microsoft Teams doesn't support SharePoint on-premises.*</span></span>   <br/> <br/>       <span data-ttu-id="bb73c-182">**Remarque**  *Il est préférable que tous les utilisateurs aient leurs boîtes aux lettres hébergées sur Exchange Online. Les utilisateurs avec des boîtes aux lettres hébergées localement doivent avoir leur identité synchronisée avec le répertoire Office 365 via Azure Active Directory Connect. Pour ces clients hybrides Exchange, si la boîte aux lettres de l’utilisateur est locale, l’utilisateur ne peut pas ajouter ni configurer de connecteurs.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-182">**Note**  *The ideal state is for all users to have their mailboxes homed on Exchange Online. Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 Directory through Azure Active Directory Connect. For these Exchange hybrid customers, if the user's mailbox is on-premises, the user can't add or configure Connectors.*</span></span>          |
|<span data-ttu-id="bb73c-183">**Intégration de Microsoft StaffHub**</span><span class="sxs-lookup"><span data-stu-id="bb73c-183">**Microsoft StaffHub onboarding**</span></span>  | <span data-ttu-id="bb73c-184">Identités activées dans Azure Active Directory pour Office 365.</span><span class="sxs-lookup"><span data-stu-id="bb73c-184">Identities enabled in Azure Active Directory for Office 365.</span></span>  <br/><br/> <span data-ttu-id="bb73c-185">**Remarque**  *Microsoft StaffHub est activé par défaut.*</span><span class="sxs-lookup"><span data-stu-id="bb73c-185">**Note**  *Microsoft StaffHub is enabled by default.*</span></span>           |
| <span data-ttu-id="bb73c-186">**Intégration de service**, notamment :</span><span class="sxs-lookup"><span data-stu-id="bb73c-186">**Service onboarding**, including:</span></span>  <br/>  <span data-ttu-id="bb73c-187">*Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive Entreprise  <br/>  Skype Entreprise Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*</span><span class="sxs-lookup"><span data-stu-id="bb73c-187">*Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive for Business  <br/>  Skype for Business Online  <br/>  Microsoft Teams  <br/>  Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 ProPlus  <br/>  Microsoft StaffHub*</span></span>   |<span data-ttu-id="bb73c-188">Les logiciels clients en ligne tels que Project pour Office 365, le client Outlook, le client de synchronisation OneDrive Entreprise, Power BI Desktop et Skype Entreprise doivent être au niveau minimal défini dans [Configuration requise pour Office](https://go.microsoft.com/fwlink/?LinkID=723597).</span><span class="sxs-lookup"><span data-stu-id="bb73c-188">Online client software like Project for Office 365, Outlook client, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in [System requirements for Office](https://go.microsoft.com/fwlink/?LinkID=723597).</span></span>  <br/> <span data-ttu-id="bb73c-189">Les programmes d’installation pour les clients de bureau Microsoft Teams Windows et Mac peuvent être téléchargés sur [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411).</span><span class="sxs-lookup"><span data-stu-id="bb73c-189">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411).</span></span>   |
   
<span data-ttu-id="bb73c-190">\*Pour en savoir plus sur les conditions requises dans votre environnement source pour Office 365 US Government, consultez l’article relatif aux [conditions attendues dans l’environnement source pour Office 365 US Government](US-Gov-appendix-source-environment-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="bb73c-190">\*For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](US-Gov-appendix-source-environment-expectations.md).</span></span>
  

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
ms.openlocfilehash: 43c8edc915d45c1af84155d82d995860cd966950
ms.sourcegitcommit: c4f9375811fd23d01edd308108340ace15ec4db7
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53255503"
---
# <a name="products-and-capabilities"></a>Produits et fonctionnalités

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Services et scénarios pris en charge par FastTrack 

Cette rubrique contient des détails sur les scénarios de charge de travail pris en charge par FastTrack et les attentes de l’environnement source nécessaires avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui place votre environnement source à la configuration minimale requise pour réussir l’intégration.

FastTrack fournit des conseils pour vous aider tout d’abord avec les fonctionnalités principales (courantes pour tous les Microsoft Online Services), puis avec l’intégration de chaque service éligible :

  - [Général](#general)
  - [Sécurité et conformité](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [Soutien aux applications](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Pour en savoir plus sur les conditions requises dans votre environnement source pour Office 365 US Government, consultez l’article relatif aux [conditions attendues dans l’environnement source pour Office 365 US Government](/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>Général

<table>
<table style="width: 100%">
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Intégration de base</strong></td>
<td>  Nous fournissons des conseils à distance sur l’intégration de base, qui implique l’approvisionnement de service, le client et l’intégration des identités. Il inclut également des étapes pour fournir une base pour l’intégration de services tels que Exchange Online, SharePoint Online et Microsoft Teams, y compris une discussion sur la sécurité, la connectivité réseau et la <a href="/office365/enterprise/office-365-network-connectivity-principles">conformité.</a>   

L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.
</li>
</ul>  

<strong> Intégration des identités </strong>

Nous fournissons des conseils à distance pour :
<ul>
<li>Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), notamment l’installation et la configuration d’Azure AD Connecter (à forêt unique ou multi-forêts) et la gestion des licences (y compris les licences basées sur un groupe).</li>
<li>Création d’identités cloud, y compris l’importation et la gestion des licences en bloc, y compris l’utilisation de licences basées sur des groupes.</li>
<li>Choix et activation de la méthode d’authentification correcte pour votre parcours dans le cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou les services AD FS (Active Directory Federation Services).</li>
<li> Choix et activation d’une expérience d’authentification plus pratique pour vos utilisateurs avec l’authentification sans mot de passe (Fast Identity Online (FIDO)2 ou Microsoft Authenticator App).</li>
<li>Activation d’AD FS pour les clients avec une forêt Active Directory unique et des identités synchronisées avec l’outil azure AD Connecter. Cela nécessite Windows Server 2012 R2 Active Directory Federation Services 2.0 ou supérieur.</li>
<li>Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</li>
<li>Migration d’applications pré-intégrées (telles que les applications SaaS (software-as-a-service) azure AD AD gallery) vers Azure AD pour l' sign-on unique (SSO).</li>
<li>Activation des intégrations d’applications SaaS avec l' luiso à partir de la galerie Azure AD.</li>
<li>Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme indiqué dans la liste de didacticiels sur l’intégration des applications <a href="/azure/active-directory/saas-apps/tutorial-list">(limitée </a> aux applications SaaS de la galerie Azure AD et à la mise en service sortante uniquement).  </li>

</td>

<td>  <strong>Activer le réseau </strong>  
  <br>Dans le cadre des avantages de FastTrack, nous vous conseillons d’indiquer les meilleures pratiques en matière de connexion aux services cloud afin de garantir les niveaux de performances les plus élevés des Microsoft 365.  
  
<strong>Forêts Active Directory</strong> Le niveau de forêt fonctionnel est Windows Server 2003 et les autres, avec la configuration de forêt suivante :
<ul>
<li>  Forêt Active Directory unique.  </li>
<li>  Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .  </li>
<li>  Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).  </li>
<li>  Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.  </li>
<li>  Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.  </li>
<li>  Tâches requises pour la configuration et l’intégration des Azure Active Directory client, si nécessaire.   </li>
</ul>
  <strong>Important</strong>  <ul>
<li>  Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype Entreprise est déployé, il doit être déployé dans la même forêt Active Directory que Exchange.  </li>
<li>  Lorsque vous implémentez plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration multi-hybride Exchange, les espaces de noms d’utilisateur principal partagés (UPN) entre les forêts sources ne sont pas pris en charge. Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés. Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.  </li>
<li>  Pour toutes les configurations à forêts multiples, le déploiement des services AD FS (Active Directory Federation Services) est hors de portée. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Nous fournissons des conseils de déploiement à distance pour :
<ul>
<li>  Résolution des problèmes de déploiement.  </li>
<li>  Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.  </li>
<li>  Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.  </li>
<li>  Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.  </li>
<li>  Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.  </li>
<li>  Sélection et configuration d’une installation locale ou dans le cloud.  </li>
<li>  Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.  </li>
<li>  Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.  
  En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures de Office et que vous avez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème de compatibilité sans frais supplémentaires via le programme Soutien aux applications. Pour plus <strong>d’informations,</strong> voir la partie <a href="#windows-10">Assurer Windows 10'application.</a> </li>
</ul></td>
<td><ul>
<li>  Le logiciel client en ligne doit être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>État du réseau</strong></td>
<td>  Nous fournissons des conseils à distance pour obtenir et interpréter les données de connectivité réseau clés de votre environnement, montrant comment les sites de votre organisation sont <a href="/office365/enterprise/office-365-network-connectivity-principles">alignés</a>sur les principes de connectivité réseau de Microsoft. Cela met en évidence votre score réseau qui a un impact direct sur la vitesse de migration, l’expérience utilisateur, les performances du service et la fiabilité.  
  Nous vous guidons également à travers les étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.  </td>
<td><ul>
<li>  Administration Microsoft 365 Accès au centre.  </li>
<li>  Les versions à jour des applications Microsoft 365 sont requises.  </li>
<li>  Services d’emplacement activés en tant que recommandations de performances réseau dans le <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">centre Administration Microsoft 365 (prévisualisation).</a>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>Sécurité et conformité

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></td>
<td>  Nous fournissons des conseils à distance pour la sécurisation de vos identités cloud pour les scénarios suivants.  

 <br/>

<strong>Infrastructure de base sécurisée</strong>  </ul>
<ul>
<li>  La configuration et l’activation d’une authentification forte pour vos identités, y compris la protection avec Azure Multi-Factor Authentication (MFA) (cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et la réinitialisation de mot de passe libre-service (SSPR).  </li>
<li> Déploiement de FIDO2 ou Microsoft Authenticator App. </li>
<li>  Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.  </li>
<li>  Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec l’accès conditionnel.  </li>
<li>  Détection et blocage de l’utilisation de mots de passe faibles avec Azure AD Password Protection.  </li>
<li>  Sécurisation de l’accès à distance aux applications web sur site avec le proxy d’application Azure AD.  </li>
<li>  Activation de la détection et de la correction basées sur les risques avec Azure Identity Protection.  </li>
<li>  Activation d’un écran de personnalisation, y compris le logo, le texte et les images avec une personnalisation.  </li>
<li>  Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.  </li>
<li>  Gestion de l’accès pour vos administrateurs Office 365 à l’aide des rôles d’administration intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateur privilégiés.  </li>
<li>  Configuration de la jointation Azure AD hybride.  </li>
<li>  Configuration de la jointation Azure AD.  </li>
</ul>
  
<strong>Surveiller et signaler</strong>  
<ul>
<li>  
  Activation de la surveillance à distance pour les services AD FS, les Connecter Azure AD et les contrôleurs de domaine avec Azure AD Connecter Health.  
  </li>
</ul>
  
<strong>Gouvernance</strong>  
<ul>
<li>  
  Gestion de votre cycle de vie d’accès et d’identité Azure AD à grande échelle avec la gestion des droits Azure AD.
  </li>
<li>  
  Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions d’accès Azure AD.  
  </li>
<li>  
  Examen des conditions d’utilisation d’Azure AD.  
  </li>
<li>  
  Gestion et contrôle de l’accès aux comptes d’administrateur privilégiés avec Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatisation et efficacité </strong>  
<ul>
<li>  
  Activation d’Azure AD SSPR.  
  </li>
<li>  Permettre aux utilisateurs de créer et de gérer leurs propres groupes de sécurité Office 365 cloud ou de gestion des groupes en libre-service Azure AD.  </li>
<li>  Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.  </li>
<li>  Activation des groupes dynamiques Azure AD.  </li>
<li>  Organisation des applications dans le portail Mes applications à l’aide de collections.  </li>
</ul></td>
<td>Active Directory local et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium..</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Pour plus d’informations sur Azure Information Protection, <strong>voir Protection des données Microsoft</strong> plus loin dans ce tableau.

  </td>
<td>  
  <tr class="odd">
<td><strong>Découvrir & Répondre</strong></td>
<td>  

<strong>eDiscovery (découverte électronique) avancée</strong>
  
Nous fournissons des conseils à distance pour : 
<ul>
<li>  Création d’un cas.   </li>
<li>  Mise en attente des dépositaires.  </li>
<li>  Effectuer des recherches. </li>
<li>  Ajouter des résultats de recherche à un jeu à réviser. </li>
<li>  Exécution de l’analyse sur un groupe de révision.  </li>
<li>  Révision et marquage de documents.  </li>
<li>  Exportation de données à partir du jeu à réviser. </li>
<li>  Importation de données non Office 365 données. </li>
</ul>

<strong>Audit avancé</strong> (uniquement pris en charge dans E5)

Nous fournissons des conseils à distance pour :  
<ul>
<li> Activation de l’audit avancé.</li>
<li> Exécuter une interface utilisateur du journal d’audit de recherche et des commandes PowerShell d’audit de base.</li>
</ul>

<strong> Gestionnaire de conformité</strong>

Nous fournissons des conseils à distance pour :  

<ul> <li>Examen des types de rôles.  </li>
<li> Ajout et configuration des évaluations.</li>
<li> Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</li>
<li> Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</li>
<li> Génération d’un rapport au sein d’une évaluation.</li>
</ul>

<strong>Ce qui suit est hors de portée </strong> 
<ul>
<li> Scripts ou codage personnalisés.</li>
<li> API eDiscovery. </li>
<li> Connecteurs de données. </li>
<li> Limites de conformité et filtres de sécurité.</li>
<li> Enquêtes sur les données.</li>
<li> Demandes des personnes à l’objet de données.</li>
<li> Révision de documents tiers, de conception et d’architecte.</li>
<li> Conformité avec les réglementations et exigences régionales et industrielles.</li>
<li> Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</li>
</ul>
</td>
<td>En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</td>
</tr>

<tr class="odd">
<td><strong>Gestion des risques internes</strong></td>

<td>  Nous fournissons des conseils à distance pour :
<ul>
<li> Création de stratégies et révision des paramètres.</li>
<li> Accès aux rapports et aux alertes.</li>
<li> Créer des cas.</li>
<li> Création de modèles d’avis.</li>
<li> Recommandations sur la création du connecteur de ressources humaines (RH).</li>
</ul>

<strong> Conformité des communications </strong> 

Nous fournissons des conseils à distance pour : 
<ul>
<li> Création de stratégies et révision des paramètres.</li>
<li> Accès aux rapports et aux alertes.</li>
<li> Création de modèles d’avis.</li>
</ul>

<strong> Gestionnaire de conformité</strong>

Nous fournissons des conseils à distance pour :  

<ul> <li>Examen des types de rôles.  </li>
<li> Ajout et configuration des évaluations.</li>
<li> Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</li>
<li> Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</li>
<li> Génération d’un rapport au sein d’une évaluation.</li>
</ul>

<strong>Ce qui suit est hors de portée </strong> 
<ul>
<li> La création et la gestion Power Automate flux de données.</li>
<li> Connecteurs de données (au-delà du connecteur RH). </li>
<li> Configurations d’expression régulière personnalisées (RegEx).</li>
<li> Révision de documents tiers, de conception et d’architecte.</li>
<li> Obstacles à l’information.</li>
<li> Gestion des accès privilégiés.</li>
<li> Conformité avec les réglementations et exigences régionales et industrielles.</li>
<li> Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</li>
</ul></td>
<td>En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender est une suite unifiée de défense d’entreprise avant et après la violation qui coordonne en natif la détection, la prévention, l’examen et la réponse entre les points de terminaison, les identités, le courrier électronique et les applications afin de fournir une protection intégrée contre les attaques sophistiquées. Nous fournissons des conseils à distance pour : </p> 
<ul>
<li>  Présentation du centre de Microsoft 365 de sécurité.  </li>
<li>  Passer en revue les incidents entre produits, notamment en vous concentrant sur les éléments critiques en garantissant l’étendue complète des attaques, les ressources impactées et les actions de correction automatisées regroupées.  </li>
<li>  Montrant comment Microsoft 365 Defender pouvez orchestrer l’examen des biens, des utilisateurs, des appareils et des boîtes aux lettres qui ont pu être compromis par le biais d’une auto-ressource automatisée. </li>
<li>  Explication et fourniture d’exemples de la façon dont les clients peuvent chercher de manière proactive les tentatives d’intrusion et l’activité de violation affectant vos e-mails, données, appareils et comptes dans plusieurs ensembles de données.   </li>
<li> Montrer aux clients comment ils peuvent examiner et améliorer leur posture de sécurité globalement à l’aide du Niveau de sécurité Microsoft.</li>
</ul>
<p><strong>Ce qui suit est hors de portée</strong></p>
<ul>
<li> Gestion de projet des activités de correction du client. </li>
<li> Gestion continue, réponse aux menaces et correction. </li>
<li> Instructions de déploiement ou formation sur :
<ul>
<li> Comment corriger ou interpréter les différents types d’alertes et activités surveillées. </li>
<li> Comment examiner un utilisateur, un ordinateur, un chemin de mouvement latéral ou une entité. </li>
<li> Recherche de menace personnalisée.  </li>
</ul>
</li>
<li> Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</li>
<li> Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security est un service Broker de sécurité d’accès au cloud (CASB) qui offre une visibilité enrichie, un contrôle sur les déplacements de données et des analyses sophistiquées pour identifier et lutter contre les cybermenaces dans tous vos services cloud Microsoft et tiers. Nous fournissons des conseils à distance pour :
<ul>
<li>  Configuration du portail, notamment :  </li>
<ul>
<li> Importation de groupes d’utilisateurs.</li>
<li> Gestion de l’accès et des paramètres de l’administrateur.  </li>
<li> Portée de votre déploiement pour sélectionner certains groupes d’utilisateurs à surveiller ou exclure de la surveillance.</li>
<li> Comment configurer des plages IP et des balises.</li>
<li> Personnalisation de l’expérience utilisateur final avec votre logo et votre messagerie personnalisée.</li>
</ul>
<li> Intégration de services tiers, notamment :
<ul>
<li> Microsoft Defender pour point de terminaison.</li>
<li> Microsoft Defender pour l’identité.</li>
<li> Azure AD Identity Protection.</li>
<li> Azure Information Protection.</li>
</ul>
<li> Configuration de la découverte dans le cloud à l’aide des paramètres :</li>
<ul>
<li> Microsoft Defender pour les points de terminaison.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Création de balises et de catégories d’application.</li>
<li> Personnalisation des scores de risque des applications en fonction des priorités de votre organisation.</li>
<li> Application de sanctions et d’inséance.</li>
<li> Examen des tableaux de bord Sécurité des applications cloud et de découverte cloud.</li>
<li> Connexion <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> d’applications fonctionnalités à l’aide</a> de connecteurs d’application.</li>
<li> Protection des applications avec le contrôle d’application d’accès conditionnel dans l’accès conditionnel dans Azure AD et Sécurité des applications cloud portails.</li>
<li> Déploiement du contrôle d’application d’accès conditionnel pour les applications disponibles.</li>
<li> Utilisation des journaux d’activité et de fichiers.</li>
<li> Gestion des applications OAuth.</li>
<li> Révision et configuration des modèles de stratégie.</li>
<li> Fourniture d’une assistance à la configuration avec les 20 principaux cas d’utilisation pour les cas de base de données d’accès au détail (y compris la création ou la mise à jour de six (6) <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">stratégies),</a> sauf : </li>
<ul>
<li> Audit de la configuration de vos environnements Internet en tant que service (IaaS) (#18).</li>
<li> Surveillance des activités des utilisateurs pour se protéger contre les menaces dans vos environnements IaaS (#19).</li>
</ul>
<li> Comprendre la corrélation d’incidents dans Microsoft 365 Defender portail.</li>
</ul>
<p><strong>Ce qui suit est hors de portée</strong></p>
<ul>
<li> Gestion de projet des activités de correction du client.</li>
<li> Gestion continue, réponse aux menaces et correction. </li>
<li> Discussions comparant Sécurité des applications cloud à d’autres offres CASB.</li>
<li> Configuration des Sécurité des applications cloud pour répondre à des exigences spécifiques en matière de conformité ou de réglementation.</li>
<li> Déploiement du service dans un environnement de production non-test.</li>
<li> Déploiement de la découverte d’applications cloud comme preuve de concept.</li>
<li> Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</li>
<li> Configuration de l’infrastructure, de l’installation ou du déploiement des téléchargements automatiques de journaux pour les rapports continus à l’aide de Docker ou d’un collecteur de journaux. </li>
<li> Création d’un rapport instantané de découverte cloud.</li>
<li> Blocage de l’utilisation de l’application à l’aide de scripts de blocage.</li>
<li> Connexion d’applications personnalisées.</li>
<li> Intégration et déploiement du contrôle d’application d’accès conditionnel pour les applications non présentes.</li>
<li> Intégration avec des fournisseurs d’identité tiers (ISP) et des fournisseurs de protection contre la perte de données (DLP).</li>
<li> Formation ou conseils pour le repérage avancé.</li>
<li> Examen et correction automatisés, y compris les manuels Power Automate Microsoft.</li>
<li> Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</li>

</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender pour point de terminaison</strong></td>
<td>  Microsoft Defender pour point de terminaison est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter, examiner et répondre aux menaces avancées.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  Déploiement des technologies pour sécuriser vos points de terminaison.  </li>
<li>  Configuration des profils de protection des points de terminaison et de restriction d’appareil.  </li>
<li>  Évaluation de la version du système d’exploitation et de la gestion des appareils (notamment Intune, Microsoft Endpoint Configuration Manager, objets de stratégie de groupe et configurations tierces), ainsi que l’état de vos services antivirus Windows Defender ou d’autres logiciels de sécurité de point de terminaison.  </li>
<li>  Évaluation de l’état de vos services Windows antivirus ou d’autres logiciels de sécurité de point de terminaison.  </li>
<li>  Évaluation des proxies et des pare-feu limitant le trafic réseau.  </li>
<li>  Activation du service Microsoft Defender for Endpoint en expliquant comment déployer un profil d’agent Defender pour Endpoint à l’aide d’un point de terminaison intégré.  </li>
<li>  Conseils de déploiement, assistance à la configuration et formation sur :
<ul>
<li>  
  La gestion des menaces et des vulnérabilités.  
  </li>
<li>  
  La réduction de la surface d’attaque.  
  </li>
<li>  
  La nouvelle génération de protection.  
  </li>
<li>  
  La détection de point de terminaison et réponse.  
  </li>
<li>  
  Les enquêtes et résolutions automatiques.  
  </li>
<li>  
  Score de sécurité pour les appareils.  
  </li>
<li> Microsoft Defender SmartScreen configuration à l’aide Microsoft Endpoint Manager.</li>

</ul></li>
<li>  Examen des simulations et didacticiels (tels que les scénarios pratiques, les programmes malveillants factices et les enquêtes automatisées).  </li>
<li>  Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.  </li>
<li>  Intégration de Microsoft Defender pour Office 365 avec Microsoft Defender pour Endpoint.  </li>
<li>  Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.  </li>
<li>  Les systèmes d’exploitation suivants :
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Serveur 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) version 1803.  
  </li>
<li>  
  macOS versions 10.13, 10.14 et 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou Microsoft Endpoint Configuration Manager (version 2002 ou ultérieure). 

</li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
<ul>
<li>  Gestion de projet des activités de correction du client.  </li>
<li> Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</li>
<li>  Support sur site.  </li>
<li>  Gestion continue et réponse aux menaces.  </li>
<li>  Intégration ou configuration pour les agents Microsoft Defender pour points de terminaison suivants :
<ul>
<li>  
  Windows Server 2008  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Appareils mobiles (Android et iOS).  
  </li>
<li> Infrastructure VDI (Virtual Desktop Infrastructure) (persistante ou non persistante).  </li>
</ul></li>
<li>  Intégration et configuration du serveur :
<ul>
<li>  
  Configuration d’un serveur proxy pour les communications hors connexion.  
  </li>
<li>  
  Configuration des packages de déploiement Configuration Manager sur les instances et versions de Configuration Manager de bas niveau.  
  </li>
<li>  
  Intégration de serveurs au Centre de sécurité Azure.  
  </li>
<li>  
  Serveurs non gérés par Configuration Manager.  
  </li>
</ul></li>
<li>  Intégration et configuration macOS :
<ul>
<li>  
  Déploiement intune manuel.  
  </li>
<li>  
  Déploiement basé sur JAMF.
  </li>
<li>  
  Autres déploiements basés sur des produits de gestion des périphériques mobiles (MDM).  
  </li>
<li>  
  Déploiement manuel.  
  </li>
</ul></li>
<li>  Configuration des fonctionnalités suivantes de réduction de la surface d’attaque :
<ul>
<li>  
  Isolation basée sur le matériel.  
  </li>
<li>  
  Contrôle d’application.  
  </li>
<li> Contrôle d’appareil.</li>
<li>  
  Exploit Protection.  
  </li>
<li>  
  Pare-feu du réseau.  
  </li>



</ul></li>
<li> Configuration ou gestion des fonctionnalités de protection des comptes telles que : </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Configuration ou gestion de BitLocker.</li>
<li>  Inscription ou configuration des Spécialistes des menaces Microsoft.  </li>
<li>  Révision de la configuration ou de la formation sur les API ou les connexions de gestion des événements et des informations de sécurité (SIEM).  </li>
<li>  Inscription ou configuration des Microsoft 365 Defender.  </li>
<li>  Formation ou conseils pour le repérage avancé.  </li>
<li>  Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</li>
<li> Formation ou conseils sur la configuration de Defender SmartScreen à l’aide d’objets de stratégie de groupe, de Sécurité Windows ou de Microsoft Edge.</li>
</li>
</ul>
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender pour l’identité </strong></td>
<td>  Microsoft Defender pour Identity est une solution de sécurité basée sur le cloud qui exploite vos signaux Active Directory sur site pour identifier, détecter et examiner les menaces avancées, les identités compromises et les actions des utilisateurs malveillants ciblant votre organisation. Nous fournissons des conseils à distance pour :
<ul>
<li>  Exécution de l’outil de taille pour la planification de la capacité des ressources. </li>
<li>   Création de votre instance de Defender for Identity. </li>
<li>   Connexion de Defender pour l’identité à Active Directory. </li>

<li>  Déploiement du capteur pour capturer et parer le trafic réseau et Windows événements directement à partir de vos contrôleurs de domaine, notamment : </li>
<ul> 
<li>  Téléchargement du package de capteur. </li>
<li>  Configuration du capteur. </li>
<li>  Installation silencieuse du capteur sur votre contrôleur de domaine. </li>
<li>  Déploiement du capteur dans votre environnement à forêts multiples. </li>
<li> Configuration du collecteur Windows événements.</li>
</ul>
<li>  Configuration du portail, notamment : </li>
<ul>
<li> Intégration de Defender for Identity à Microsoft Cloud App Security (Sécurité des applications cloud licences n’est pas requise). </li>
<li> Configuration des balises d’entité.</li>
<li> Marquage des comptes sensibles. </li>
<li> Réception de notifications par courrier électronique pour les problèmes d’état de santé et les alertes de sécurité. </li>
<li> Configuration des exclusions d’alertes.  </li>
</ul>
<li> Fourniture d’instructions de déploiement, d’assistance à la configuration et de formation sur :</li>
<ul>
<li> Comprendre le rapport d’évaluation de la posture de sécurité des identités.</li>
<li> Comprendre le rapport sur le score de priorité de l’examen des utilisateurs et le rapport de classement de l’examen utilisateur.</li>
<li> Comprendre le rapport de l’utilisateur inactif.</li>
<li> Explication des options de correction sur un compte compromis.</li>
</ul>
<li>  Faciliter la migration de Advanced Threat Analytics (ATA) vers Defender for Identity. </li>
</ul>
<p><strong>Ce qui suit est hors de portée</strong></p>
<ul>

<li> Gestion de projet des activités de correction du client. </li>
<li> Gestion continue, réponse aux menaces et correction.  </li>
<li> Déploiement de Defender for Identity comme preuve de concept.</li>
<li> Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</li>
<li> Déploiement ou mise en place des activités de capteur Defender pour l’identité suivantes : </li>
<ul>
<li> Planification manuelle de la capacité. </li>
<li> Exécution de l’outil Audit. </li>
<li> Déploiement du capteur autonome. </li>
<li> Déploiement sur les serveurs AD FS (Active Directory Federation Services).
<li> Déploiement du capteur à l’aide d’un adaptateur d’équipe carte d’interface réseau (NIC). </li>
<li> Déploiement du capteur via un outil tiers. </li>
<li> Connexion au service cloud Defender for Identity via une connexion proxy web. </li>
</ul>
<li> Configuration du compte Microsoft (MSA) dans Active Directory.
<li> Création et gestion de honeytokens. </li>
<li> Activation de la résolution de noms réseau (NNR). </li>
<li> Configuration du conteneur Objets supprimés.</li>
<li> Instructions de déploiement ou formation sur : </li>
<ul>
<li> Correction ou interprétation de différents types d’alertes et activités surveillées.  </li>
<li> Recherche d’un utilisateur, d’un ordinateur, d’un chemin de mouvement latéral ou d’une entité. </li>
<li> Menace ou recherche avancée. </li>
<li> Réponse aux incidents. </li>
</ul>
<li> Fourniture d’un didacticiel de laboratoire d’alertes de sécurité pour Defender for Identity. </li>
<li> Envoi d’une notification lorsque Defender pour l’identité détecte des activités suspectes en envoyant des alertes de sécurité à votre serveur syslog via un capteur désigné.  </li>
<li> Configuration de Defender for Identity pour effectuer des requêtes à l’aide du protocole SAMR (Security Account Manager remote) afin d’identifier les administrateurs locaux sur des ordinateurs spécifiques. </li>
<li> Configuration de solutions VPN pour ajouter des informations à partir de la connexion VPN à la page de profil d’un utilisateur.  </li>
<li> Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel). </li>
</ul></td>
<td><ul>
<li> Aligné sur <a href="/defender-for-identity/prerequisites">Microsoft Defender pour les conditions préalables d’identité.</a> </li>
<li>  Active Directory déployé.  </li>
<li>  Les contrôleurs de domaine sur qui vous avez l’intention d’installer les capteurs Defender for Identity ont une connectivité Internet au service cloud de Defender for Identity.  </li>
<ul>
<li> Votre pare-feu et votre proxy doivent être ouverts pour communiquer avec le service cloud Defender for Identity (*.atp.azure.com port 443 doit être ouvert).</li>
</ul>
<li> Contrôleurs de domaine en cours d’exécution sur l’une des suivantes :</li>
<ul>
<li> Windows Serveur 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Serveur 2019 avec KB4487044 (build de système d’exploitation 17763.316 ou ultérieure).</li>
</ul>
<li> Microsoft .NET Framework 4.7 ou ultérieure.</li>
<li> Un minimum de cinq (5) Go d’espace disque est requis et 10 Go sont recommandés.</li>
<li> Deux (2) cœurs et six (6) Go de RAM installés sur le contrôleur de domaine.</li>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender pour Office 365</strong></td>
<td>  Microsoft Defender pour Office 365 protège votre organisation contre les menaces malveillantes posées par les messages électroniques, les liens (URL) et les outils de collaboration. Microsoft Defender pour Office 365 inclut :<ul>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Stratégies de protection contre les</a>menaces : définissez des stratégies de protection contre les menaces pour définir le niveau de protection approprié pour votre organisation.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Rapports</a>: affichez des rapports en temps réel pour surveiller Defender Office 365 performances au niveau de votre organisation.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Fonctionnalités de recherche et de réponse aux menaces</a> : utilisez des outils de pointe pour étudier, comprendre, simuler et prévenir les menaces.</li>
<li> <a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Fonctionnalités automatisées d’investigation et de réponse</a> : gagnez du temps pour investiguer et atténuer les menaces.</li>
</ul>

Nous fournissons des conseils à distance pour :  
<ul>
<li>  Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.  </li>
<li>  Configuration de l’automatisation, de l’investigation et de la réponse.  </li>
<li>  Utilisation du Simulateur d’attaques.  </li>
<li>  Création de rapports et analytique des menaces.  </li>
<li>  Comprendre la corrélation d’incidents dans Microsoft 365 Defender portail.</li>
</ul>
<p><strong>Ce qui suit est hors de portée</strong></p>
<ul>
<li> Gestion de projet des activités de correction du client.</li>
<li> Gestion continue, réponse aux menaces et correction.</li>
<li> Prise <a href=" /fasttrack/us-gov-appendix-overview">en charge GCC-High ou GCC-DoD (Office 365 gouvernement américain)</a>.</li>
<li> Discussions comparant Defender pour Office 365 à d’autres offres de sécurité.</li>
<li> Déploiement de Defender pour Office 365 comme preuve de concept.</li>
<li> Connexion d’applications personnalisées.</li>
<li> Formation ou conseils pour le repérage avancé.</li>
<li> Examen et correction automatisés, y compris les manuels Power Automate Microsoft.</li>
<li> Informations sur la sécurité et gestion des événements (SIEM) ou intégration d’API (y compris Azure Sentinel).</li>
</ul>
</td>
<td>En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</td>
</tr>


<tr class="even">
<td><strong>Gouvernance des informations Microsoft</strong></td>

<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Création et publication d’étiquettes et de stratégies de rétention (uniquement pris en charge dans E5).  
</li>
<li>  Gestion des enregistrements (uniquement prise en charge dans E5).  </li>
<ul><li>  Examen de la création d’un plan de fichiers. </li>
<li>  Création et gestion des enregistrements (y compris les enregistrements basés sur des événements).  </li>
<li>  Révision de la disposition. </ul> </li>
</ul>

<strong> Gestionnaire de conformité</strong>

Nous fournissons des conseils à distance pour :  

<ul> <li>Examen des types de rôles.  </li>
<li> Ajout et configuration des évaluations.</li>
<li> Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</li>
<li> Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</li>
<li> Génération d’un rapport au sein d’une évaluation.</li>
</ul>

  <strong>Ce qui suit est hors de portée </strong>  
<ul>
<li> Développement d’un plan de gestion des fichiers de gestion des enregistrements.</li>
<li> Connecteurs de données.</li>
<li> Développement de l’architecture des informations dans SharePoint.</li>
<li> Scripts et codage personnalisés.</li>
<li> Révision de documents tiers, de conception et d’architecte.</li>
<li> Prise en charge de l’E3.</li>
<li> Conformité avec les réglementations et exigences régionales et industrielles.</li>
<li> Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</li>
</ul>

</td>
<td>En dehors <strong>de la partie Intégration de</strong> base en <a href="#general">général,</a>il n’existe aucune exigence minimale du système.</td>
</tr>
<tr class="odd">
<td><strong>Protection des informations Microsoft</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Classification des données (prise en charge dans E3 et E5).  </li>
<li>  Types d’informations sensibles (pris en charge dans E3 et E5).  </li>
<li>  Création d’étiquettes de sensibilité (prise en charge dans E3 et E5).  </li>
<li>  Application d’étiquettes de sensibilité (prise en charge dans E3 et E5).  </li>
<li>  Classifieurs entra nessables (pris en charge dans E5).  </li>
<li>  Connaissance de vos données avec l’Explorateur de contenu et l’Explorateur d’activités (pris en charge dans E5).  </li>
<li>  Publication d’étiquettes à l’aide de stratégies (manuelle et automatique) (prise en charge dans E5).  </li>
<li>  Création de stratégies de protection contre la perte de données (DLP) de point de terminaison pour Windows 10 appareils mobiles (pris en charge dans E5).  </li>
<li>  Création de stratégies DLP pour Microsoft Teams conversations et canaux.  </li>
</ul>

<strong> Gestionnaire de conformité</strong>

Nous fournissons des conseils à distance pour :  

<ul> <li>Examen des types de rôles.  </li>
<li> Ajout et configuration des évaluations.</li>
<li> Évaluer la conformité en implémentant des actions d’amélioration et en déterminant comment cela a un impact sur votre score de conformité.</li>
<li> Examen du mappage des contrôles intégrés et de l’évaluation des contrôles.</li>
<li> Génération d’un rapport au sein d’une évaluation.</li>
</ul>

<strong> Azure Information Protection</strong>

Nous fournissons des conseils à distance pour :  
<ul>
<li>  Activation et configuration de votre client.  </li>
<li>  Création et configuration d’étiquettes et de stratégies (pris en charge dans P1 et P2).  </li>
<li>  Application de la protection des informations aux documents (prise en charge dans P1 et P2).  </li>
<li>  Classification et étiquetage automatiques des informations dans les applications Office (telles que Word, PowerPoint, Excel et Outlook) en cours d’exécution sur Windows et à l’aide du client Azure Information Protection (pris en charge dans P2).  </li>
<li>  Découverte et étiquetage des fichiers au repos à l’aide du scanneur Azure Information Protection (pris en charge dans P1 et P2).  </li>
<li>  Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.  </li>
</ul>

  Nous fournissons également des conseils si vous souhaitez appliquer la protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), chiffrement de messages Office 365 (OME) et la protection contre la perte de données (DLP).

<strong>Ce qui suit est hors de portée </strong>  
<ul>
<li>Clé client.</li>
<li>Développement d’expressions régulières personnalisées (RegEx) pour les types d’informations sensibles.</li>
<li>Création ou modification de dictionnaires de mots clés.</li>
<li>Scripts et codage personnalisés.</li>
<li> Azure Purview.</li>
<li> Révision de documents tiers, de conception et d’architecte.</li>
<li> Conformité avec les réglementations et exigences régionales et industrielles.</li>
<li> Implémentation pratique des actions d’amélioration recommandées pour les évaluations dans le Gestionnaire de conformité.</li>
</ul>

<ul>

</td>
<td>En dehors <strong>de la partie</strong> Intégration de base en <a href="#general">général,</a>il n’existe aucune exigence système minimale à l’exception d’Azure Information Protection.

<strong>Azure Information Protection</strong>

Les responsabilités préalables du client sont les suivantes :  
<ul>
<li>  Liste des emplacements de partage de fichiers à scanner.  </li>
<li>  Taxonomie de classification approuvée. </li>
<li> Comprendre les restrictions ou exigences réglementaires relatives à la gestion des clés.  </li>
<li>  Un compte de service créé pour votre annuaire Active Directory local qui a été synchronisé avec Azure AD. </li>
<li>  Étiquettes configurées pour la classification et la protection. </li>
<li> Toutes les conditions préalables pour le scanneur Azure Information Protection sont en place. Pour plus d’informations, voir Conditions préalables à l’installation et au déploiement du scanneur d’étiquetage unifié <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a> </li>
<li>  Assurez-vous que les appareils utilisateur exécutent un système d’exploitation pris en charge et que les conditions préalables nécessaires sont installées. Pour plus d’informations, voir les informations suivantes.</li>
<ul>
<li> <a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guide d’administration : Installer le client d’étiquetage unifié Azure Information Protection pour les utilisateurs</a>   </li>
<li>  <a href="/azure/information-protection/rms-client/mobile-app-faq">Qu’est-ce que l’application Azure Information Protection pour iOS ou Android ?</a>  </li>
</ul>
<li> Installation et configuration du connecteur et des serveurs Azure RMS, y compris le connecteur AD RMS (Active Directory RMS) pour la prise en charge hybride.  </li>
<li> Si vous avez besoin de l’une de ces options pour votre déploiement, vous devez installer et configurer Bring Your Own Key (BYOK), DKE (Double Key Encryption) (client d’étiquetage unifié uniquement) ou Hold Your Own Key (HYOK) (client classique uniquement).  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Nous fournissons des conseils à distance sur la préparation à l’utilisation d’Intune en tant que fournisseur de gestion des périphériques mobiles (MDM) et de gestion des applications mobiles (MAM) dans le cloud pour vos applications et appareils. Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles. La procédure inclut les étapes suivantes :
<ul>
<li>  Licences pour les utilisateurs finaux.  </li>
<li>  Configuration des identités à utiliser par Intune en tirant parti de vos identités Active Directory locales ou cloud (Azure AD).  </li>
<li>  Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.  </li>
<li>  Configuration de votre autorité de gestion des projets, en fonction de vos besoins en matière de gestion, notamment :
<ul>
<li>  Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.  </li>
</ul></li>
<li>  Recommandations en matière de gestion des appareils mobiles pour :
<ul>
<li>  Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.  </li>
<li>  Configuration des stratégies de gestion et des services de gestion du service MDM tels que :
<ul>
<li>  Déploiement d’application pour chaque plateforme prise en charge par le biais de liens web ou de liens profonds.  </li>
<li>  Stratégies d’accès conditionnel.  </li>
<li>  Déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous avez une autorité de certification, un réseau sans fil ou une infrastructure VPN existante dans votre organisation.  </li>
<li>  Connexion à l’entrepôt de données Intune.  </li>
<li>  Intégration de Intune avec :
<ul>
<li>  Visionneuse d’équipe pour l’assistance à distance (un abonnement Team Viewer est requis).  </li>
<li>  Solutions de partenaires de protection contre les menaces mobiles (MTD) (un abonnement MTD est requis).  </li>
<li>  Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).  </li>

</ul></li>
<li>  Inscription de périphériques de chaque plateforme prise en charge sur Intune.  </li>
</ul></li>
</ul></li>
<li>  Fournir des conseils sur la protection des applications sur :
<ul>
<li>  Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.  </li>
<li>  Configuration des stratégies d’accès conditionnel pour les applications gérées.  </li>
<li>  Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées précédemment.  </li>
<li>  Utilisation des rapports d’utilisation des applications gérées.  </li>
</ul></li>
<li>  Fourniture d’instructions de migration de la gestion des PC hérités vers la gestion des ordinateurs de groupe Intune.  </li>
</ul>
 
</li>
</ul>
  
<strong>Attachement via le cloud</strong>  

  Nous vous guidons tout au long de la préparation à l’attachement dans le cloud des environnements Configuration Manager existants avec Intune. Les étapes exactes dépendent de votre environnement source. La procédure inclut les étapes suivantes :  
<ul>
<li>  Licences pour les utilisateurs finaux.  </li>
<li>  Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.  </li>
<li>  Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.  </li>
<li>  Fourniture de conseils pour la configuration hybride de la jointation Azure AD.  </li>
<li>  Fourniture d’instructions sur la configuration d’Azure AD pour l’inscription automatique À la gestion des fonctionnalités de gestion des plateformes (MDM).  </li>
<li>  Fourniture d’instructions sur la façon de configurer la passerelle de gestion cloud lorsqu’elle est utilisée comme solution pour la cogestion de la gestion des appareils basés sur Internet à distance.  </li>
<li>  Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.  </li>
<li>  Installation du client Configuration Manager dans les appareils inscrits sur Intune.  </li>
</ul> 

<strong>Déployer Outlook mobile pour iOS et Android en toute sécurité</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook mobile pour iOS et Android en toute sécurité dans votre organisation afin de vous assurer que toutes les applications requises sont installées pour vos utilisateurs.  
  Les étapes à suivre pour déployer Outlook mobile pour iOS et Android avec Intune en toute sécurité dépendent de votre environnement source. Il peut inclure les suivants :
<ul>
<li>  Téléchargement du Outlook applications pour iOS et Android, Microsoft Authenticator et Portail d’entreprise Intune par le biais de l’App Store d’Apple ou de Google Play Store.  </li>
<li>  Fourniture d’instructions sur la configuration :
<ul>
<li>  La Outlook pour iOS et Android, Microsoft Authenticator et Portail d’entreprise Intune applications avec Intune.  </li>
<li>  Stratégies de protection des applications.  </li>
<li>  Stratégies d’accès conditionnel.  </li>
<li>  Stratégies de configuration d’application.  </li>
</ul></li>
</ul>  
  </td>
<td>  Les administrateurs informatiques doivent avoir une autorité de certification, un réseau sans fil et des infrastructures VPN existants qui fonctionnent déjà dans leurs environnements de production lors de la planification du déploiement de réseau sans fil et de profils VPN avec Intune.  
  <strong>Remarque</strong>: l’avantage du service FastTrack n’inclut pas d’assistance pour la configuration des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats Push Apple MDM pour Intune.  
 
  <strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.

  <strong>Intune intégré à Microsoft Defender pour le point de terminaison</strong> 
 
  <strong>Remarque</strong>: nous fournissons de l’aide sur l’intégration d’Intune à Microsoft Defender pour Endpoint et la création de stratégies de conformité des appareils en fonction de son évaluation Windows 10 niveau de risque. Nous ne fournissons pas d’aide sur les achats, les licences ou l’activation. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide à ce sujet.  
  
<strong>Windows Autopilot</strong> 
 
  Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique. Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.  </li>
<li>  Pointage de vos enregistrements MX (mail exchange) vers Office 365.  </li>
<li>  La configuration de Microsoft Defender pour Office 365 fonctionnalité si elle fait partie de votre service d’abonnement. Pour plus d’informations, <strong>consultez la</strong> section Microsoft Defender Office 365 partie de ce tableau.  </li>
<li>  La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</li>
<li>  La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</li>
</ul>
  <strong>Remarque :</strong> Le service de réplication de boîte aux lettres (MRS) tente de migrer des messages électroniques gérés par des droits d’information (IRM) de votre boîte aux lettres sur site vers la boîte aux lettres Exchange Online correspondante. La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).  
<ul>
<li>  La configuration de ports de pare-feu.  </li>
<li>  La configuration du DNS, y compris les enregistrements DMARC (Autodiscover, Sender Policy Framework) requis, DKIM (DomainKeys Identified Mail), DMARC (Domain-based Message Authentication, Reporting and Conformance) et MX (selon vos besoins).  </li>
<li>  la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).  </li>
<li>  La migration de messagerie de votre environnement de messagerie source vers Office 365.  </li>
<li>  La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).  </li>
</ul>
  <strong>Migration des données</strong>  <br>
Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a>   
<td>  Votre environnement source doit avoir l’un des niveaux minimaux suivants :
<ul>
<li>  Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.  </li>
<li>  Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.  </li>
<li>  Environnement G Suite unique (Gmail, contacts et calendrier uniquement).  </li>
<li>  Pour plus d’informations sur les fonctionnalités multigé géographiques, voir <a href="https://go.microsoft.com/fwlink/?linkid=872776">Fonctionnalités multigé géographiques dans Exchange Online</a>.  </li>
</ul>
Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive Entreprise, les Power BI Desktop et les Skype Entreprise doivent se trouver à un niveau minimal tel que défini dans la norme système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>.  </td>
</tr>

<td><strong>Microsoft Defender pour Office 365</strong></td>
<td>  Pour plus d’informations, <strong>voir Microsoft Defender pour Office 365</strong> sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformité.</a>  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Gouvernance des informations Microsoft</strong></td>
<td>  Pour plus d’informations, voir Gouvernance des <strong>informations Microsoft</strong> en matière de sécurité et <a href="/fasttrack/products-and-capabilities#security-and-compliance">de conformité.</a> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Protection des informations Microsoft</strong></td>
<td>  
Pour plus d’informations, <strong>voir Protection des données Microsoft</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Confirmation de la demande minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour prendre en charge Teams.  </li>
<li>  la configuration de ports de pare-feu ;  </li>
<li>  Configuration de DNS.  </li>
<li>  Confirmation que Teams est activé sur votre client Office 365.  </li>
<li>  Activation ou désactivation des licences utilisateur.  </li>
<li>  Évaluation réseau pour les Teams :
<ul>
<li>  Vérifications des ports et des points de terminaison.  </li>
<li>  Contrôles de la qualité de connexion.  </li>
<li>  Estimations de la bande passante.  </li>
</ul>
<ul>
<li>  Configuration de Teams d’application (Teams application web, Teams application de bureau et Teams pour iOS et Android).  </li>
</ul>
Le cas échéant, nous fournissons également des conseils pour :
<ul>
<li>  Microsoft Teams Appareils de salle :  </li>
<ul>
<li>  Création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge répertoriés dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils Teams</a>.  </li>
<li>  Assistance à distance avec la configuration côté service des appareils Salles Microsoft Teams certifiés.  </li>
<li>  Activation de l’audioconférence :  </li>
<ul>
<li>  Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.  </li>
<li>  Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.  </li>
</ul>
<li>  Système téléphonique :
<ul>
<li>  Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.  </li>
<li>  Conseils sur les forfaits d’appels<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(marchés disponibles)</a>:
<ul>
<li>  Affectation de numéros aux utilisateurs titulaires d’une licence.  </li>
<li>  Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.  </li>
<li>  Prise en charge des demandes de service de portage de numéro local au-delà de 999.  </li>
</ul></li>
<li>  Conseils de routage direct :
<ul>
<li>  Conseils de configuration de l’organisation pour la conception du routage direct des scénarios hébergés par des partenaires ou des scénarios déployés par le client pour un nombre de sites au plus de 10.  </li>
<li> Révision de la configuration du contrôleur de frontière de session (SBC). </li>

<li> Assistance à distance avec la configuration du plan de numérotation. </li>

<li> Configuration de l’itinéraire des voix.</li>

<li> Contournement de média et optimisation des médias locaux. </li>

</ul></li>
</ul></li>
<li>  Activation des événements en direct Teams.  </li>
<li>  Configuration de l’organisation et intégration à Microsoft Stream.  </li>
<li>  Recommandations pour Skype Entreprise transition Teams transition.  </li>
</ul></td>
<td><ul>
<li>  Identités activées dans Azure AD pour Office 365.  </li>
<li>  Utilisateurs activés pour SharePoint Online.  </li>
<li>  Exchange boîtes aux lettres sont présentes (en ligne et en local dans une configuration Exchange hybride).  </li>
<li>  Activation pour les groupes Office 365.  </li>
</ul>
  <strong>Remarque :</strong> Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas OneDrive Entreprise stockage dans Office 365. Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans des conversations sans OneDrive Entreprise stockage dans Office 365. Teams ne prend pas en charge SharePoint local.  <br>
  <strong>Remarque :</strong> L’état idéal est que tous les utilisateurs ont leurs boîtes aux lettres Exchange Online. Les utilisateurs avec des boîtes aux lettres locales doivent avoir leur identité synchronisée avec le répertoire Office 365 via Azure AD Connecter. Pour ces Exchange hybrides, si la boîte aux lettres de l’utilisateur est en local, l’utilisateur ne peut ni ajouter ni configurer de connecteurs.  
  Les programmes d’installation pour les clients de bureau Microsoft Teams Windows et Mac peuvent être téléchargés sur <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
</tr>

<tr class="even">
<td><strong>Outlook pour iOS et Android</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.  </li>
<li>  Configuration des comptes et accès à la boîte aux lettres Exchange Online.  </li>
<li>  Sécurisation Outlook mobile (voir <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sécurisation Outlook pour iOS</a> et Android dans Exchange Online pour plus d’informations).  </li>
</ul></td>
<td><ul>
<li>  Identités activées dans Azure AD pour Office 365.  </li>
<li>  Exchange Online configuré et licences attribuées.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Attribution de licences Power BI.  </li>
<li>  Déploiement de l'application Power BI Desktop.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Power BI Desktop doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;  </li>
<li>  l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;  </li>
<li>  la configuration de la liste des ressources d’entreprise (ERP) ;  </li>
<li>  la création de votre premier projet.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professionnel et Premium</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Résolution des problèmes de déploiement.  </li>
<li>  Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.  </li>
<li>  Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.  </li>
<li>  Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.  </li>
<li>  Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.  </li>
<li>  Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Project pour Office 365 doivent se trouver à un niveau minimal tel que défini dans la Microsoft 365 système requise pour <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Office</a>.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online et OneDrive Entreprise</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Configuration de DNS.  </li>
<li>  la configuration de ports de pare-feu ;  </li>
<li>  la mise en service des utilisateurs et des licences ;  </li>
<li>l'activation de la création de sites pour votre administrateur SharePoint Online ;</li>
<li>la planification des collections de sites ;</li>
<li>la sécurisation du contenu et la gestion des autorisations ;</li>
<li>la configuration des fonctionnalités SharePoint Online.</li>
<li>  la configuration des fonctionnalités Environnement hybride SharePoint, telles que la recherche hybride, les sites hybrides, la taxonomie hybride, les types de contenu, la création de sites en libre-service hybride (SharePoint Server 2013 uniquement), le lanceur d’applications étendu, OneDrive Entreprise hybride et les sites extranet.  </li>
<li>  Votre approche de migration.  </li>
</ul>
Des instructions supplémentaires sont fournies pour OneDrive Entreprise en fonction de votre version SharePoint, par exemple :
<ul>
<li>  Identification des options d’intégration et examen de l’infrastructure réseau locale et en ligne et de la bande passante.  </li>
<li>  Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et mise en œuvre des exigences de synchronisation et d’identité, et identification de votre client OneDrive Entreprise synchronisation.  </li>
<li>  Planification et mise en œuvre d’un déploiement unique pour tous les utilisateurs (ou d’un déploiement par phases).  </li>
<li>  Attribution de licences, redirection des sites Mon site et des bibliothèques de documents personnels vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).  </li>
<li>Redirection ou déplacement de dossiers connus vers OneDrive.</li>
<li>  Déploiement de la synchronisation OneDrive Entreprise client.  </li>
</ul>
  <strong>Migration des données</strong>  <br>
Pour plus d’informations sur l’utilisation des avantages de FastTrack pour la migration des données vers Office 365, voir <a href="/fasttrack/data-migration">Migration des données.</a>
</ul></td>
<td><br><strong>Pour SharePoint hybride :</strong>  
<ul>
<li>  SharePoint configuration hybride inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, des OneDrive Entreprise, un lanceur d’applications étendu, des sites extranet et la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.  </li>
</ul>
  <strong>Remarque :</strong> La création de sites libre-service n’est pas limitée aux serveurs locaux SharePoint 2013.  
<ul>
<li>  Pour activer SharePoint hybride, vous devez avoir l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.  </li>
</ul>
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide. Pour plus d’informations, voir Niveaux de mise à jour publique <a href="https://go.microsoft.com/fwlink/?linkid=853548">minimale pour SharePoint fonctionnalités hybrides.</a><em></em>  <br>
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigé géographiques, voir Fonctionnalités <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigéo</a>géographiques dans OneDrive et SharePoint Online dans Office 365<em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Nous fournissons des conseils à distance pour l’activation Yammer Entreprise service.  
</td>
<td>Le logiciel client en ligne doit être au niveau minimal défini dans la Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">système</a>requise Office .</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security 

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></td>
<td>  Pour plus d’informations, <strong>voir Azure Active Directory (Azure AD)</strong> et Azure AD Premium <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Pour plus d’informations sur Azure Information Protection, voir <strong>Protection des données Microsoft</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Pour plus d’informations, <strong>voir Microsoft Intune</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">sécurité et conformité.</a>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Nous fournissons des conseils pour la mise à niveau de Windows 7 Professionnel et Windows 8.1 Professional vers Windows 10 Entreprise.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  Comprendre l’Windows 10 de votre entreprise.  </li>
<li>  Évaluation de votre environnement source et des conditions requises (assurez-vous Microsoft Endpoint Configuration Manager niveau requis pour prendre en charge le déploiement Windows 10 déploiement).  </li>
<li>  Déploiement de Windows 10 Entreprise et de Microsoft 365 Apps à l’aide Microsoft Endpoint Configuration Manager ou Microsoft 365.  </li>
<li>  Recommandations d’options pour évaluer vos applications Windows 10 applications.  </li>
<li>  Activation de l’utilisation de Desktop Analytics et de conseils via la création d’un plan de déploiement Desktop Analytics.  </li>
<li>  Microsoft 365 Apps’évaluation de la compatibilité en tirant parti du tableau de bord de préparation Office 365 dans Configuration Manager ou avec la Shared Computer Toolkit de préparation autonome pour Office plus l’aide au déploiement Microsoft 365 Apps.  </li>
<li>  Création d’une liste de vérification de correction sur ce que vous devez faire pour mettre votre environnement source au niveau minimal requis pour un déploiement réussi.  </li>
<li>  Fournir des conseils de mise à niveau pour vos appareils existants Windows 10 Entreprise s’ils répondent à la configuration matérielle requise.  </li>
<li>  Fournir des instructions de mise à niveau pour prendre en charge votre mouvement de déploiement existant. FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10. Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.  </li>
<li>  Déploiement de Microsoft 365 Apps à l’aide de Configuration Manager dans le cadre du Windows 10 déploiement.   </li>
<li>  Fournir des conseils pour aider votre organisation à rester à jour avec Windows 10 Entreprise et Microsoft 365 Apps l’aide de votre environnement Configuration Manager ou de votre Microsoft 365.  </li> 
</ul>
  
<strong>Ce qui suit est hors de portée </strong>  
<ul>
<li>  Mettre à niveau Configuration Manager vers la branche actuelle.  </li>
<li>  Créer des images personnalisées pour le déploiement de Windows 10.  </li>
<li>  Créer et prendre en charge des scripts de déploiement pour le déploiement de Windows 10.  </li>
<li>  Convertir un système Windows 10 à partir du BIOS vers Unified Extensible Firmware Interface (UEFI).  </li>
<li>  Activer les fonctionnalités de sécurité Windows 10.  </li>
<li>  Configurer les services de déploiement Windows (WDS) pour le démarrage de l’environnement PXE (Preboot Execution Environment).  </li>
<li>  Utiliser le Microsoft Deployment Toolkit (MDT) pour capturer et déployer des images Windows 10.  </li>
<li>  Utiliser l’outil de migration de l’état utilisateur (USMT).  </li>
</ul>
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.  </td>
<td>  Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :
<ul>
<li>  Système d’exploitation source : Windows 7 Entreprise ou Professional, Windows 8.1 Entreprise ou Professional.  </li>
<li>  Appareils : facteur de forme de bureau, de bloc-notes ou de tablette.  </li>
<li>  Système d’exploitation cible : fenêtre 10 Enterprise.  </li>
</ul>
Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  La version de Configuration Manager doit être prise en charge par la version Windows 10 cible. Pour plus d’informations, voir le tableau de prise en charge de Configuration Manager de l’article <a href="/sccm/core/plan-design/configs/support-for-windows-10">Prise en charge de Windows 10 dans Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender pour point de terminaison</strong></td>
<td>  Pour plus d’informations, <strong> voir Microsoft Defender for Endpoint</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Nous fournissons des conseils de déploiement pour l’intégration Windows Virtual Desktop (un service de virtualisation de bureau et d’application). Windows Virtual Desktop tire parti de Windows 10 multisessage et est optimisé pour les Microsoft 365 Apps de Enterprise avec une sécurité et une gestion intégrées pour Microsoft 365.</p>
<p>Nous fournissons des conseils à distance pour :</p>
<ul>
<li>Déploiement de Windows 10 Entreprise multisesse et de Microsoft 365 Apps pour Enterprise à l’aide des outils suivants :
<ul>
<li>Image Marketplace Azure.</li>
<li>Image partagée.</li>
<li>Office Déploiement Shared Computer Toolkit (ODT).</li>
</ul></li>
<li>Configuration de Microsoft 365 Apps pour FSLogix dans un ordinateur Windows Virtual Desktop natif. Pour FSLogix :
<ul>
<li>Déploiement de l’agent.</li>
<li>Configuration des conteneurs profil et Office de profil.</li>
<li>Configuration des exclusions de contenu et des redirections de dossiers pour Microsoft 365 Apps.</li>
</ul></li>
<li>Déploiement de Microsoft Edge.</li>
<li>Déploiement de Microsoft Teams optimisation.</li>
</ul>

<strong>Ce qui suit est hors de portée</strong>
<ul>
<li>Project gestion du déploiement de l’infrastructure Windows Virtual Desktop du client.</li>
<li>Virtualisation et déploiement d’applications tierces.</li>
<li>Création d’images personnalisées pour Windows Virtual Desktop.</li>
<li>Migrations et scénarios impliquant VMware et Citrix.</li>
<li>Scénarios Linux.</li>
<li>Conversion ou migrations de profils utilisateur.</li>
<li>Microsoft Endpoint Configuration Manager et Microsoft Endpoint Manager configuration pour Windows Virtual Desktop (y compris la correction et la gestion). </li>
<li>Microsoft 365 Defender avec Windows 10 sessions multiples.</li>
</ul>
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</td>
<td>Vous devez déjà avoir les choses suivantes :
<ul>
<li><a href="/azure/virtual-desktop/overview#requirements">Windows licences Virtual Desktop requises.</a></li>
<li> Infrastructure <a href="/azure/virtual-desktop/overview">requise pour prendre en charge Windows Virtual Deskstop</a>. </li>
<ul>
<li>Stockage pour les conteneurs de profil <a href="/azure/virtual-desktop/store-fslogix-profile">FSLogix dans Windows Virtual Deskstop</a>. </li>
</ul>
<li>Mise en réseau Azure :
<ul>
<li>Création et sous-réseau de réseau virtuel (VNET).</li>
<li>Pare-feu et groupes de sécurité réseau.</li>
<li>VPN et ExpressRoute.</li>
<li>Routage vers Azure à partir de l’local.</li>
<li>Règles de pare-feu pour autoriser la connectivité Windows Virtual Desktop.
</ul>
Pour plus d’informations, voir <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clients Bureau à distance pris en charge.</a>
</ul>
<ul><li>Configuration générale d’Azure AD :
<ul>
<li>Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
<ul>
<li>Active Directory avec Azure AD Connecter azure.</li>
<li>Active Directory avec Azure AD Connecter local sur VPN ou ExpressRoute.</li>
<li>Services de domaine Active Directory (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>Soutien aux applications


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Soutien aux Applications</strong></td>
<td>  L’App Assure est un service conçu pour résoudre les problèmes de Windows 10 et Microsoft 365 Apps compatibilité des applications. Lorsque vous demandez le service Soutien aux applications, nous travaillons avec vous pour résoudre les problèmes d’application valides sans frais supplémentaires pour vous avec un abonnement éligible. Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et Microsoft Edge et nous faisons tout ce qui est raisonnable pour résoudre les problèmes de compatibilité. Nous fournissons une assistance de correction pour les applications déployées sur les produits Microsoft suivants :
<ul>
<li>  <strong>Windows 10</strong> (y compris les appareils ARM64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Pour obtenir des conseils de déploiement, voir <a href="/DeployEdge/microsoft-edge-channels">Vue d’ensemble Microsoft Edge canaux de déploiement.</a>  </li>
<li>  <strong>Windows Virtual Desktop</strong> - Pour plus d’informations, voir <a href="/azure/virtual-desktop/overview">Qu’est-ce Windows Virtual Desktop ?</a> et Windows 10 Entreprise faq sur les <a href="/azure/virtual-desktop/windows-10-multisession-faq">sessions multiples</a>.  </li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
<ul>
<li>  Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps. Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>. Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</li>
<li>  Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces. Pour plus d’informations, consultez <a href="/sccm/desktop-analytics/overview">Analytique de bureau</a>.</li>
<li>Services uniquement pour le conditionnement des applications. Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</li>
</ul>

<strong>Les responsabilités du client sont les suivantes :</strong>  
<ul>
<li>  Création d’un inventaire d’applications.</li>
<li>  Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</li>
</ul>
<strong>Remarque :</strong>  Microsoft ne peut pas apporter de modifications à votre code source. Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications. 


  Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.  </td>

</td>
<td><strong>Windows 10 et Microsoft 365 Apps</strong>
<ul>
<li>  
  Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 sur ARM</strong>
<ul>
<li>  
Les applications qui fonctionnaient sur Windows 7, Office 2010 ou versions ultérieures fonctionnent également sur Windows 10 et Microsoft 365 Apps sur les appareils ARM64. 
  </li>
</ul>
  <strong>Remarque :</strong> 
<ul>
<li> L’émulation x64 (64 bits) est disponible en prévisualisation pour les clients participant au programme <a href="https://insider.windows.com/">Insider Windows.</a>  </li>
<li>  
 Pour les clients insiders Windows sur Windows 10 version 2004 (ou ultérieure), ARM64 Photoshop est pris en charge à l’aide du pack de compatibilité OpenCL et <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a> 
  </li>
<li>  
  Les clients du Windows Insider peuvent télécharger une version Insider du pack de compatibilité OpenCL et OpenGL pour une utilisation avec des applications supplémentaires.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Si vos applications ou sites web fonctionnent sur Internet Explorer 11, les versions de Google Chrome ou toute version de Microsoft Edge, elles fonctionneront également avec Microsoft Edge.  
  </li>
<li>  
  Comme le web évolue constamment, n’oubliez pas de passer en revue cette liste publiée des modifications connues concernant la compatibilité des <a href="/microsoft-edge/web-platform/site-impacting-changes">sites pour Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Windows Virtual Desktop</strong>  
<ul>
<li>  
  Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.  
  </li>
<li>  
  Les applications s’exécutant sur n’importe quel environnement Windows 7 ou Windows 10 virtual desktop infrastructure (VDI) s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.  
  </li>
<li>  
  Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.  
  </li>
</ul>
  <strong>Remarque : Windows 10 Entreprise</strong> exclusions et limitations de compatibilité à plusieurs sessions sont les suivantes :
<ul>
<li>  
  Redirection limitée du matériel.  
  </li>
<li>  
  Les applications ayant une grande quantité de A/V peuvent avoir une capacité réduite.  
  </li>
<li>  
  Les applications 16 bits ne sont pas prises en charge pour les applications Windows Virtual Desktop 64 bits.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Détails des conseils FastTrack</th>
<th>Attentes concernant l’environnement source</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Nous fournissons des conseils sur le déploiement à distance, l’adoption et la compatibilité pour : <ul> <li>Déploiement de Microsoft Edge sur Windows 10 avec Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager ou Intune).  </li>
<li>  Configuration des Microsoft Edge (à l’aide de stratégies de groupe ou de configuration d’application Intune et de stratégies d’application).  </li>
<li>  Inventaire de la liste des sites qui peuvent nécessiter une utilisation en mode Internet Explorer.  </li>
<li>  Activation du mode Internet Explorer avec la liste Enterprise sites existante. (Pour plus d’informations, voir <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engager FastTrack.</a> En outre, si vous avez une application web ou un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires. Pour demander la prise en charge de la compatibilité pour Soutien aux applications, connectez-vous au <a href="https://fasttrack.microsoft.com/portal#/signin">portail FastTrack</a> pour démarrer un engagement.  </li>
<li> Conseils de planification pour l’adoption edge et les instructions de configuration Recherche Microsoft des signets.</li>
</ul>

<strong>Ce qui suit est hors de portée </strong>  
<ul>
<li>Gestion de projet du déploiement Microsoft Edge du client.</li>
<li>  Support sur site.</li>

</td>
<td></td>
</tr>
</tbody>
</table>

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
# <a name="products-and-capabilities"></a>Produits et fonctionnalités

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Services et scénarios pris en charge par FastTrack

Cette rubrique inclut des détails sur les scénarios de charge de travail pris en charge par FastTrack et sur l’environnement source requis avant de commencer. En fonction de votre configuration actuelle, nous travaillons avec vous pour créer un plan de correction qui permet à votre environnement source de bénéficier de la configuration minimale requise pour une intégration réussie.

FastTrack fournit des conseils pour vous aider à utiliser les fonctionnalités principales (communes à tous les services Microsoft Online), puis à intégrer chaque service éligible :

  - [Général](#general)
  - [Office 365](#office-365)
  - [Sécurité & Enterprise Mobility](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [Soutien aux Applications](#app-assure)
  - [Nouveau Microsoft Edge](#the-new-microsoft-edge)

> [!NOTE]
> Pour plus d’informations sur les attentes en matière d’environnement source pour Office 365, consultez la rubrique [source Environment attentes for office 365 Office US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
## <a name="general"></a>Général

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Attentes en matière d’environnement source</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Intégration de base</strong></td>
<td>  Nous fournissons des conseils à distance sur l’intégration de base, qui implique la mise en service, le client et l’intégration des identités. Il décrit également les étapes à suivre pour fournir une base pour les services d’intégration tels qu’Exchange Online, SharePoint Online et Microsoft Teams, y compris une <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion sur la sécurité, la connectivité réseau et la conformité</a>.  
  L’intégration pour un ou plusieurs services éligibles peut commencer une fois l’intégration de base terminée.
</li>
</ul>  

<strong> Intégration des identités </strong>

Nous fournissons des conseils à distance pour :
<ul>
<li>Préparation des identités Active Directory locales pour la synchronisation avec Azure Active Directory (Azure AD), y compris l’installation et la configuration d’Azure AD Connect (à forêt unique ou multi-forêt) et des licences (y compris les licences basées sur les groupes).</li>
<li>Création d’identités Cloud incluant l’importation et la gestion de licences en bloc, y compris l’utilisation de licences basées sur les groupes.</li>
<li>Sélection et activation de la méthode d’authentification appropriée pour votre parcours Cloud, la synchronisation de hachage de mot de passe, l’authentification directe ou Active Directory Federation Services (AD FS).</li>
<li>Activation des services ADFS (Active Directory Federation Services) pour les clients disposant d’une seule forêt Active Directory et d’identités synchronisées avec l’outil Azure AD Connect. Cette opération nécessite Windows Server 2012 R2 Active Directory Federation Services 2,0 ou une version ultérieure.</li>
<li>Migration de l’authentification d’AD FS vers Azure AD à l’aide de la synchronisation de hachage de mot de passe ou de l’authentification directe.</li>
<li>Migration des applications préintégrées (telles que les applications SaaS) d’AD FS vers Azure Active Directory pour l’authentification unique (SSO) pour Active Directory.</li>
<li>Activation des intégrations de l’application SaaS avec l’authentification unique à partir de la Galerie Azure AD.</li>
<li>Activation de la mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, telles qu’elles sont répertoriées dans la <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">liste des didacticiels d’intégration des applications</a> (limitée aux applications SaaS et à la mise en service sortante de la Galerie AD AD).  </li>
</td>

<td>  <strong>Activation du réseau </strong>  
  <br>Dans le cadre de l’avantage de FastTrack, nous vous conseillons de vous conformer aux meilleures pratiques pour vous connecter aux services Cloud afin de garantir les niveaux de performances les plus élevés de Microsoft 365.  
  
<strong>Forêts Active Directory</strong> Ils ont le niveau de forêt fonctionnel défini sur Windows Server 2003 et versions ultérieures, avec la configuration de forêt suivante :
<ul>
<li>  Forêt Active Directory unique.  </li>
<li>  Topologies avec forêt de ressources et forêt de comptes Active Directory unique (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise) .  </li>
<li>  Topologies avec forêt de ressources et forêts de comptes Active Directory multiples (Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise).  </li>
<li>  Forêts de comptes Active Directory multiples, avec l'une des forêts qui est une forêt de comptes Active Directory centralisée incluant Exchange et/ou Lync 2010, Lync 2013 ou Skype Entreprise.  </li>
<li>  Plusieurs forêts de comptes Active Directory, ayant chacune sa propre organisation Exchange.  </li>
<li>  Tâches requises pour la configuration du client et l’intégration à Azure Active Directory, si nécessaire.   </li>
</ul>
  <strong>Indispensables</strong>  <ul>
<li>  Pour les scénarios Active Directory à forêts multiples, si Lync 2010, Lync 2013 ou Skype entreprise est déployé, il doit être déployé dans la même forêt Active Directory qu’Exchange.  </li>
<li>  Lors de l’implémentation de plusieurs forêts Active Directory avec plusieurs organisations Exchange dans une configuration multi-hybride Exchange, les espaces de noms UPN (nom d’utilisateur principal) partagés entre les forêts sources ne sont pas pris en charge. Les espaces de noms SMTP principaux entre les organisations Exchange doivent également être séparés. Pour plus d'informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=845444">Déploiements hybrides à forêts Active Directory multiples</a>.  </li>
<li>  Pour toutes les configurations à forêts multiples, le déploiement des services ADFS (Active Directory Federation Services) est hors de portée. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Nous fournissons des conseils de déploiement à distance pour :
<ul>
<li>  Résolution des problèmes de déploiement.  </li>
<li>  Attribution des licences utilisateur final et basées sur l’appareil à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.  </li>
<li>  Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.  </li>
<li>  Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android.  </li>
<li>  Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.  </li>
<li>  Sélection et configuration d’une installation locale ou dans le cloud.  </li>
<li>  Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.  </li>
<li>  Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.  
  En outre, si vous avez une macro ou un complément qui fonctionnait avec des versions antérieures d’Office et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour corriger le problème de compatibilité sans frais supplémentaires via le programme de garantie de l’application. Pour plus d’informations, consultez la section <strong>vérifier l’application</strong> de <a href="#windows-10">Windows 10</a> . </li>
</ul></td>
<td><ul>
<li>  Le logiciel client en ligne doit être à un niveau minimal, comme défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Intégrité du réseau</strong></td>
<td>  Nous fournissons des conseils à distance pour l’obtention et l’interprétation des données clés de connectivité réseau de votre environnement, qui illustrent l’alignement des sites de votre organisation sur les <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principes de la connectivité réseau de</a>Microsoft. Cela met en évidence votre score réseau qui influe directement sur la rapidité de migration, l’expérience utilisateur, les performances de service et la fiabilité.  
  Nous vous proposons également des étapes de correction mises en évidence par ces données pour vous aider à améliorer votre score réseau.  </td>
<td><ul>
<li>  Accès au centre d’administration Microsoft 365.  </li>
<li>  Des versions à jour des applications Microsoft 365 sont requises.  </li>
<li>  Services d’emplacement activés en fonction <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">des recommandations en matière de performances réseau dans le centre d’administration Microsoft 365 (version préliminaire)</a>.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Attentes en matière d’environnement source</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Pour Exchange Online, nous vous guidons au fil du processus pour préparer votre organisation à utiliser la messagerie électronique. Les étapes exactes dépendent de votre environnement source et de vos plans de migration de messagerie.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  La configuration des fonctionnalités d’Exchange Online Protection (EOP) pour tous les domaines à extension messagerie validés dans Office 365.  </li>
<li>  Pointage de vos enregistrements MX (mail Exchange) vers Office 365.  </li>
<li>  La configuration de la fonctionnalité DAV (ATP) d’Office 365 si elle fait partie de votre service d’abonnement. Pour plus d’informations, reportez-vous à la partie <strong>Office 365 Advanced Threat Protection</strong> de ce tableau.  </li>
<li>  La configuration de la fonctionnalité Protection contre la perte de données (DLP) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</li>
<li>  La configuration de la fonctionnalité Chiffrement des messages Office 365 (OME) pour tous les domaines à extension messagerie validés dans Office 365 dans le cadre de votre service d’abonnement, une fois que vos enregistrements MX pointent vers Office 365.</li>
</ul>
  <strong>Remarque :</strong> Le service de réplication de boîtes aux lettres tente de migrer les e-mails de gestion des droits relatifs à l’information (IRM) à partir de votre boîte aux lettres locale vers la boîte aux lettres Exchange Online correspondante. La possibilité de lire le contenu protégé après la migration dépend des modèles utilisés par le client pour le mappage et la copie des modèles AD RMS (Active Directory Rights Managed Services) vers le service Azure Rights Management (Azure RMS).  
<ul>
<li>  La configuration de ports de pare-feu.  </li>
<li>  La configuration d’un DNS, y compris les enregistrements de découverte automatique, SPF (Sender Policy Framework), DomainKeys Identified Identified Mail (DKIM), de création de message et de conformité (DMARC), ainsi que les enregistrements MX requis (le cas échéant).  </li>
<li>  la configuration d'un flux de messagerie entre votre environnement de messagerie source et Exchange Online (si nécessaire).  </li>
<li>  La migration de messagerie de votre environnement de messagerie source vers Office 365.  </li>
<li>  La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).  </li>
</ul>
  <strong>Migration de données</strong>  <br>
Pour plus d’informations sur l’utilisation de l’avantage FastTrack pour la migration de données vers Office 365, voir <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.   
<td>  Votre environnement source doit avoir l’un des niveaux minimaux suivants :
<ul>
<li>  Organisations Exchange uniques ou multiples avec Exchange Server 2003 et versions ultérieures.  </li>
<li>  Environnement de messagerie compatible IMAP (Internet Message Access Protocol) unique.  </li>
<li>  Environnement G Suite unique (Gmail, contacts et calendrier uniquement).  </li>
<li>  Pour plus d’informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique <a href="https://go.microsoft.com/fwlink/?linkid=872776">fonctionnalités Multigéographiques dans Exchange Online</a>.  </li>
</ul>
Les logiciels clients en ligne tels que Project pour Office 365, Outlook pour Windows, Outlook pour iOS et Android, le client de synchronisation OneDrive entreprise, Power BI Desktop et Skype entreprise doivent être au niveau minimal défini dans <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Requirements for Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Gouvernance des informations Microsoft</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Gouvernance des informations.  </li>
<li>  Étiquettes et stratégies de rétention.  </li>
<li>  Gestion des enregistrements.  </li>
<li>  Stratégies de suppression.  </li>
<li>  Conformité des communications.  </li>
<li>  Gestion des risques d'initiés.  </li>
<li>  EDiscovery avancée.  </li>
</ul></td>
<td>Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</td>
</tr>
<tr class="odd">
<td><strong>Protection des informations Microsoft</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Classification des données.  </li>
<li>  Types d'informations sensibles.  </li>
<li>  Création de labels de sensibilité.  </li>
<li>  Appliquer des labels de sensibilité.  </li>
<li>  Étiquetage unifié.  </li>
<li>  Des classificateurs avec capacité d’apprentissage.  </li>
<li>  Connaître ses données avec l'explorateur de contenu et l'explorateur d'activités.  </li>
<li>  Publication d'étiquettes à l'aide de politiques (manuelles et automatiques).  </li>
<li>  Créer des politiques de prévention des pertes de données (DLP) pour les conversations et les canaux de Microsoft Teams.  </li>
</ul></td>
<td>Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Vérification de la configuration minimale requise dans Exchange Online, SharePoint Online, les groupes Office 365 et Azure AD pour la prise en charge de teams.  </li>
<li>  la configuration de ports de pare-feu ;  </li>
<li>  Configuration de DNS.  </li>
<li>  Confirmation que Teams est activé sur votre client Office 365.  </li>
<li>  Activation ou désactivation des licences utilisateur.  </li>
<li>  Évaluation du réseau pour teams :
<ul>
<li>  Vérifications des ports et des points de terminaison.  </li>
<li>  Contrôles de la qualité de connexion.  </li>
<li>  Estimations de la bande passante.  </li>
</ul>
<ul>
<li>  Configuration de la stratégie d’application Teams (Team Web App, application de bureau teams et Teams pour l’application iOS et Android).  </li>
</ul>
Le cas échéant, nous fournissons également des conseils pour :
<ul>
<li>  Appareils de salle Microsoft teams :  </li>
<ul>
<li>  La création de comptes en ligne nécessaires pour les appareils de salle de conférence et de téléphonie pris en charge figurant dans le <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogue des appareils teams</a>.  </li>
<li>  Assistance à distance avec la configuration côté service des périphériques de salle Microsoft teams certifiés.  </li>
<li>  Activation de l’audioconférence :  </li>
<li>  Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.  </li>
<li>  Affectation de passerelles de conférence aux utilisateurs titulaires d’une licence.  </li>
</ul>
<li>  Système téléphonique :
<ul>
<li>  Configuration de l’organisation pour les paramètres par défaut de Cloud Voice.  </li>
<li>  Conseils pour les forfaits d’appels (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">marchés disponibles</a>) :
<ul>
<li>  Affectation de numéros aux utilisateurs titulaires d’une licence.  </li>
<li>  Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.  </li>
<li>  Prise en charge des demandes de service de portage de numéro local au-delà de 999.  </li>
</ul></li>
<li>  Guide de routage direct :
<ul>
<li>  Guide de configuration de l’Organisation pour le routage direct de scénarios hébergés par un partenaire ou de scénarios déployés par le client pour un maximum de 10 sites.  </li>
<li> Vérification de la configuration du contrôleur de frontière de session (SBC). </li>

<li> Assistance à distance avec la configuration du plan de numérotation. </li>

<li> Configuration de l’itinéraire des communications vocales.</li>

<li> Déviation du trafic multimédia et optimisation des supports locaux. </li>

</ul></li>
</ul></li>
<li>  Activation des événements en direct Teams.  </li>
<li>  Configuration de l’organisation et intégration à Microsoft Stream.  </li>
<li>  Instructions pour la transition entre Skype entreprise et Teams.  </li>
</ul></td>
<td><ul>
<li>  Identités activées dans Azure AD pour Office 365.  </li>
<li>  Utilisateurs activés pour SharePoint Online.  </li>
<li>  Des boîtes aux lettres Exchange sont présentes (en ligne et en local dans une configuration hybride Exchange).  </li>
<li>  Activation pour les groupes Office 365.  </li>
</ul>
  <strong>Remarque :</strong>   Si les utilisateurs ne sont pas affectés et activés avec des licences SharePoint Online, ils n’auront pas de stockage OneDrive entreprise dans Office 365. Le partage de fichiers continue de fonctionner dans les canaux, mais les utilisateurs ne peuvent pas partager de fichiers dans les conversations sans espace de stockage OneDrive entreprise dans Office 365. Teams ne prend pas en charge SharePoint en local.  <br>
  <strong>Remarque :</strong>   L’état idéal est que les boîtes aux lettres de tous les utilisateurs soient hébergées sur Exchange Online. Les utilisateurs disposant de boîtes aux lettres hébergées sur site doivent être synchronisés avec l’annuaire Office 365 via Azure AD Connect. Pour ces clients hybrides Exchange, si la boîte aux lettres de l’utilisateur est locale, l’utilisateur ne peut pas ajouter ni configurer de connecteurs.  
  Les programmes d’installation pour les clients de bureau Microsoft teams Windows et Mac peuvent être téléchargés à partir de  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 – Protection avancée contre les menaces (ATP)</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Activation de liens fiables, de pièces jointes fiables et de l’anti-hameçonnage.  </li>
<li>  Configuration de l’automatisation, de l’investigation et de la réponse.  </li>
<li>  Utilisation du Simulateur d’attaques.  </li>
<li>  Création de rapports et analytique des menaces.  </li>
</ul></td>
<td>Outre la partie de base de l' <strong>intégration</strong> en <a href="#general">général</a>, il n’y a pas de configuration système requise minimale.</td>
</tr>
<tr class="even">
<td><strong>Outlook pour iOS et Android</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Téléchargement d’Outlook pour iOS et Android depuis l’App Store d’Apple et Google Play.  </li>
<li>  Configuration des comptes et accès à la boîte aux lettres Exchange Online.  </li>
<li>  Sécurisation d’Outlook Mobile (pour plus d’informations, consultez la rubrique <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">sécurisation d’Outlook pour iOS et Android dans Exchange Online</a> ).  </li>
</ul></td>
<td><ul>
<li>  Identités activées dans Azure AD pour Office 365.  </li>
<li>  Exchange Online configuré et licences attribuées.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Attribution de licences Power BI.  </li>
<li>  Déploiement de l'application Power BI Desktop.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Power BI Desktop doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  la vérification de la fonctionnalité SharePoint de base sur laquelle Project Online s'appuie ;  </li>
<li>  l'ajout du service Project Online à votre client (y compris en ajoutant des abonnements à des utilisateurs) ;  </li>
<li>  la configuration de la liste des ressources d’entreprise (ERP) ;  </li>
<li>  la création de votre premier projet.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Project pour Office 365 doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</td>
</tr>
<tr class="odd">
<td><strong>Project Online professionnel et Premium</strong></td>
<td>  Nous fournissons des conseils à distance pour :
<ul>
<li>  Résolution des problèmes de déploiement.  </li>
<li>  Attribution des licences utilisateur final à l’aide du Centre d’administration Microsoft 365 et de Windows PowerShell.  </li>
<li>  Installation du client de bureau Project Online à partir du portail Office 365 avec l’option Démarrer en un clic.  </li>
<li>  Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.  </li>
<li>  Configuration d’un serveur de distribution sur site unique pour le client de bureau Project Online, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.  </li>
<li>  Connexion du client de bureau Project Online à Project Online Professionnel ou Project Online Premium.  </li>
</ul></td>
<td>Les logiciels clients en ligne tels que Project pour Office 365 doivent être au niveau minimal défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online et OneDrive Entreprise</strong></td>
<td>  Nous fournissons des conseils à distance pour :
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
Des conseils supplémentaires sont fournis pour OneDrive entreprise en fonction de votre version de SharePoint, par exemple :
<ul>
<li>  L’identification des options d’intégration et la vérification de la bande passante et de l’infrastructure réseau locale et en ligne ;  </li>
<li>  Installation de SharePoint Online 2013 SP1 (le cas échéant), planification et implémentation des exigences en matière de synchronisation et d’identité, et identification de votre client de synchronisation OneDrive entreprise.  </li>
<li>  La planification et l’implémentation d’un déploiement unique pour tous les utilisateurs (ou un déploiement échelonné).  </li>
<li>  Attribution de licences, redirection de mes sites et de mes bibliothèques de documents personnelles vers Office 365 (applicable à SharePoint Online 2013), configuration des audiences pour contrôler l’accès à OneDrive (applicable à SharePoint Online 2013).  </li>
<li>Redirection ou transfert de dossiers connus vers OneDrive.</li>
<li>  Déploiement de la synchronisation du client OneDrive entreprise.  </li>
</ul>
  <strong>Migration de données</strong>  <br>
Pour plus d’informations sur l’utilisation de l’avantage FastTrack pour la migration de données vers Office 365, voir <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.
</ul></td>
<td><br><strong>Pour SharePoint hybride :</strong>  
<ul>
<li>  La configuration SharePoint hybride inclut la configuration de la recherche hybride, des sites, de la taxonomie, des types de contenu, de OneDrive entreprise, d’un lanceur d’applications étendu, de sites extranet et de la création de sites libre-service connectés en local à un environnement SharePoint Online cible unique.  </li>
</ul>
  <strong>Remarque :</strong> La création de sites en libre-service n’est pas dans l’étendue avec les serveurs locaux exécutant SharePoint 2013.  
<ul>
<li>  Pour activer SharePoint hybride, vous devez disposer de l’un des environnements SharePoint Server locaux suivants : 2013, 2016 ou 2019.  </li>
</ul>
  <strong>Remarque :</strong> La mise à niveau des environnements SharePoint locaux vers SharePoint Server n’est pas dans l’étendue. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide. Pour plus d’informations, voir <a href="https://go.microsoft.com/fwlink/?linkid=853548">niveaux de mise à jour publique minimum pour les fonctionnalités hybrides SharePoint</a><em>.</em>  <br>
  <strong>Remarque :</strong> Pour plus d’informations sur les fonctionnalités multigéographiques, reportez-vous à la rubrique <a href="https://go.microsoft.com/fwlink/?linkid=831056">fonctionnalités Multigéographiques dans OneDrive et SharePoint Online dans Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Nous fournissons des conseils à distance pour l’activation du service Yammer Enterprise.  
</ul></td>
<td>Le logiciel client en ligne doit être à un niveau minimal, comme défini dans la <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Configuration système requise pour Microsoft 365 et Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Sécurité & Enterprise Mobility

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) et Azure AD Premium</strong></td>
<td>  Nous fournissons des conseils à distance pour sécuriser vos identités Cloud dans les scénarios suivants.  

 <br/>

<strong>Infrastructure de base sécurisée</strong>  </ul>
<ul>
<li>  La configuration et l’activation de l’authentification forte pour vos identités, notamment la protection avec Azure Multi-Factor Authentication (Multi-Factor Authentication) (Cloud uniquement), l’application Microsoft Authenticator et l’inscription combinée pour Azure MFA et l’self-service Password Reset (SSPR).  </li>
<li>  Pour les clients autres que Azure AD Premium, des conseils sont fournis pour sécuriser vos identités à l’aide des paramètres de sécurité par défaut.  </li>
<li>  Pour les clients Azure AD Premium, des conseils sont fournis pour sécuriser vos identités avec un accès conditionnel.  </li>
<li>  Détection et blocage de l’utilisation de mots de passe faibles avec la protection par mot de passe Azure AD.  </li>
<li>  Sécurisation de l’accès à distance aux applications Web locales avec le proxy d’application Azure AD.  </li>
<li>  Activation de la détection et de la correction basées sur les risques avec Azure identity protection.  </li>
<li>  L’activation d’un écran de connexion personnalisé, y compris le logo, le texte et les images avec personnalisation.  </li>
<li>  Partage sécurisé d’applications et de services avec des utilisateurs invités à l’aide d’Azure AD B2B.  </li>
<li>  Gestion de l’accès pour vos administrateurs Office 365 à l’aide de rôles administratifs intégrés au contrôle d’accès basé sur un rôle (RBAC) et pour réduire le nombre de comptes d’administrateurs privilégiés.  </li>
<li>  Configuration de la jointure Azure AD hybride.  </li>
<li>  Configuration de la participation à Azure AD.  </li>
</ul>
  
<strong>Surveillance et création de rapports</strong>  
<ul>
<li>  
  Activation de la surveillance à distance pour AD FS, Azure AD Connect et des contrôleurs de domaine avec Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Govern</strong>  
<ul>
<li>  
  Gestion du cycle de vie de votre identité Azure AD et de son accès à l’aide de la gestion des droits Azure AD.
  </li>
<li>  
  Gestion des appartenances aux groupes Azure AD, de l’accès aux applications d’entreprise et des attributions de rôles avec les révisions Azure AD Access.  
  </li>
<li>  
  Consulter les conditions d’utilisation d’Azure AD.  
  </li>
<li>  
  Gestion et contrôle de l’accès aux comptes d’administrateur privilégié grâce à Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatisation et efficacité </strong>  
<ul>
<li>  
  Activation du SSPR Azure AD.  
  </li>
<li>  Permettre aux utilisateurs de créer et de gérer leurs propres groupes de sécurité Cloud ou Office 365 avec la gestion des groupes libre-service Azure AD.  </li>
<li>  Gestion de l’accès délégué aux applications d’entreprise avec la gestion des groupes délégués Azure AD.  </li>
<li>  Activation des groupes dynamiques Azure AD.  </li>
<li>  Organisation des applications dans le portail mes applications à l’aide de collections.  </li>
</ul></td>
<td>Active Directory sur site et son environnement ont été préparés pour Azure AD Premium, y compris la correction des problèmes identifiés qui empêchent l’intégration à Azure AD et les fonctionnalités Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection Premium (P2 ou EMS E5)</strong></td>
<td>  Nous fournissons des conseils sur la façon de :
<ul>
<li>  Activez et configurez votre client.  </li>
<li>  Créer et configurer des étiquettes et des stratégies.  </li>
<li>  Application de la protection des informations aux documents.  </li>
<li>  Classifier et étiqueter automatiquement des informations dans les applications Office (telles que Word, PowerPoint, Excel et Outlook) exécutées sur Windows et utilisant le client Azure information protection.  </li>
<li>  Utilisation des fichiers au repos avec l’analyseur Azure information protection.  </li>
<li>  Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.  </li>
</ul>
Nous fournissons également des conseils pour appliquer la protection à l’aide des services Microsoft Azure Rights Management (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP).  </td>
<td>  Vous devez déjà :
<ul>
<li>  Utiliser Azure AD.  </li>
<li>  Utilisez Windows ou iOS (les autres systèmes d’exploitation sont hors de portée).  
  </ul>
<strong>Remarque</strong>: les ordinateurs et les appareils mobiles doivent s’exécuter sur un <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">système d’exploitation</a> qui prend en charge Azure information protection.  
<li>  Disposez de vos emplacements de partage de fichiers principaux.  </li>
<strong>Remarque</strong>: le support hybride requiert le connecteur AD RMS. 
<li>  Disposer d’une taxonomie de classification approuvée.  </li>
<li>  Comprenez les restrictions réglementaires relatives à votre gestion des clés protégées.  </li>
</ul>
  
<strong>Scanneur Azure information protection</strong>  
  
Vous devez déjà :  
<ul>
<li>  Utilisez Windows Server 2012 R2 ou Windows Server 2016.  </li>
<li>  Disposer d’une connexion Internet.  </li>
<li>  Disposer de Microsoft SQL Server 2012 à partir d’une instance locale ou distante.  </li>
<li>  Disposer d’un compte de service créé pour votre annuaire Active Directory local et synchronisé avec Azure AD.  </li>
<li>  Avez téléchargé AzInfoProtection.exe.  </li>
<li>  Les étiquettes sont configurées pour la classification/la protection automatique.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Nous fournissons des conseils sur la préparation à l’utilisation d’Intune en tant que fournisseur de service de gestion des appareils mobiles (MDM) et de gestion des applications mobiles (MAM) en nuage pour vos applications et appareils. Les étapes exactes dépendent de votre environnement source et sont basées sur vos besoins en matière de gestion des applications mobiles et des appareils mobiles. La procédure inclut les étapes suivantes :
<ul>
<li>  Licences pour les utilisateurs finaux.  </li>
<li>  Configuration des identités à utiliser par Intune en tirant parti de votre annuaire Active Directory local ou des identités Cloud (Azure AD).  </li>
<li>  Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.  </li>
<li>  Configuration de votre autorité MDM, en fonction de vos besoins de gestion, notamment :
<ul>
<li>  Définition d’Intune comme autorité de gestion des appareils mobiles lorsqu’ Intune est votre seule solution de gestion des appareils mobiles.  </li>
</ul></li>
<li>  Recommandations en matière de gestion des appareils mobiles pour :
<ul>
<li>  Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.  </li>
<li>  Configuration des stratégies de gestion et des services de gestion du service MDM tels que :
<ul>
<li>  Déploiement d’applications pour chaque plateforme prise en charge par le biais de liens Web ou de liens détaillés.  </li>
<li>  Stratégies d’accès conditionnel.  </li>
<li>  Le déploiement de profils de messagerie, de réseaux sans fil et de VPN si vous disposez d’une autorité de certification, d’un réseau sans fil ou d’une infrastructure VPN existante dans votre organisation.  </li>
<li>  Connexion à l’entrepôt de données Intune.  </li>
<li>  Intégration de Intune avec :
<ul>
<li>  Visionneuse d’équipe pour l’assistance à distance (un abonnement à la visionneuse d’équipe est requis).  </li>
<li>  Solutions de partenariat mobile Threat Defense (MTD) (un abonnement MTD est requis).  </li>
<li>  Une solution de gestion des dépenses de télécommunication (un abonnement à une solution de gestion des dépenses de télécommunication est requis).  </li>
<li>  Microsoft Defender ATP (Windows E5 ou Microsoft 365 E5 licences requises).  </li>
</ul></li>
<li>  Inscription de périphériques de chaque plateforme prise en charge sur Intune.  </li>
</ul></li>
</ul></li>
<li>  Fournir des conseils sur la protection des applications sur :
<ul>
<li>  Configurer des stratégies de protection des applications pour chaque plateforme prise en charge.  </li>
<li>  La configuration des stratégies d’accès conditionnel pour les applications gérées.  </li>
<li>  Ciblage des groupes d’utilisateurs appropriés avec les stratégies MAM mentionnées ci-dessus.  </li>
<li>  Utilisation des rapports d’utilisation avec gestion des applications.  </li>
</ul></li>
<li>  Fournir des conseils de migration à partir de la gestion de PC héritée vers Intune MDM.  </li>
</ul>
  <strong>Remarque</strong>: la gestion des PC hérités n’est plus prise en charge depuis le 15 octobre 2020.  
</li>
</ul>
  
<strong>Attachement via le cloud</strong>  

  Nous vous guiderons tout au long de la préparation au Cloud : attachez des environnements Configuration Manager existants avec Intune. Les étapes exactes dépendent de votre environnement source. La procédure inclut les étapes suivantes :  
<ul>
<li>  Licences pour les utilisateurs finaux.  </li>
<li>  Configurer les identités pour les utiliser avec Intune en tirant parti de votre Active Directory local et des identités cloud.  </li>
<li>  Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.  </li>
<li>  Fournir des conseils sur la configuration de la participation hybride Azure AD.  </li>
<li>  Fournir des conseils sur la configuration d’Azure AD pour l’inscription automatique MDM.  </li>
<li>  Fourniture de conseils sur la configuration de la passerelle de gestion cloud.  </li>
<li>  Configuration des charges de travail prises en charge que vous voulez basculer vers Intune.  </li>
<li>  Installation du client Configuration Manager dans les appareils inscrits sur Intune.  </li>
</ul> 

<strong>Déployer Outlook Mobile pour iOS et Android de manière sécurisée</strong> Nous pouvons fournir des conseils pour vous aider à déployer Outlook Mobile pour iOS et Android de manière sécurisée dans votre organisation afin de vous assurer que toutes les applications requises sont installées sur vos utilisateurs.  
  Les étapes de déploiement sécurisé d’Outlook Mobile pour iOS et Android avec Intune dépendent de votre environnement source. Elle peut inclure les éléments suivants :
<ul>
<li>  Téléchargement des applications Outlook pour iOS et Android, Microsoft authentificateur et portail d’entreprise Intune via le magasin d’applications Apple ou Google Play Store.  </li>
<li>  Fournir des conseils sur la configuration des éléments suivants :
<ul>
<li>  Le déploiement d’applications de portail d’entreprise Outlook pour iOS et Android, Microsoft Authenticator et Intune avec Intune.  </li>
<li>  Stratégies de protection des applications.  </li>
<li>  Stratégies d’accès conditionnel.  </li>
<li>  Stratégies de configuration de l’application.  </li>
</ul></li>
</ul>
  
  <strong>Remarque</strong>: FastTrack ne prend pas en charge la sécurisation d’Outlook pour iOS et Android avec les stratégies de boîte aux lettres d’appareils mobiles Exchange. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.  
  </td>
<td>  Les administrateurs informatiques doivent disposer d’une autorité de certification existante, d’un réseau sans fil et d’infrastructures VPN qui travaillent déjà dans leurs environnements de production lors de la planification du déploiement de profils réseau sans fil et VPN avec Intune.  
  <strong>Remarque</strong>: le service FastTrack n’inclut pas d’aide pour configurer ou configurer des autorités de certification, des réseaux sans fil, des infrastructures VPN ou des certificats poussés pour Intune.  
 
  <strong>Remarque</strong>: l’avantage de service FastTrack n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et du client Configuration Manager vers la configuration minimale requise pour la prise en charge de l’attachement via le cloud. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.

  <strong>Intune intégré avec Microsoft Defender - Protection avancée contre les menaces (ATP)</strong> 
 
  <strong>Remarque</strong>: nous fournissons une assistance sur l’intégration d’Intune avec Microsoft Defender ATP et sur la création de stratégies de conformité des appareils basées sur son évaluation du niveau de risque de Windows 10. Nous ne fournissons pas d’assistance pour l’achat, la gestion des licences ou l’activation. Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide à ce propos.  
  
<strong>Windows Autopilot</strong> 
 
  Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows.  
  
<strong>Déployer Outlook pour iOS et Android de manière sécurisée avec Intune </strong>  
<ul>
<li>  Identités utilisateur activées dans Azure AD pour Office 365.  </li>
<li>  Exchange Online ou Exchange hybride configuré avec des licences utilisateur affectées.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Attentes en matière d’environnement source</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Nous fournissons des conseils pour la mise à niveau de Windows 7 professionnel et Windows 8,1 professionnel vers Windows 10 entreprise.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  Comprendre votre intention Windows 10.  </li>
<li>  Évaluation de votre environnement source et de la configuration requise (Assurez-vous que le gestionnaire de configuration du point de terminaison Microsoft est mis à niveau vers le niveau requis pour prendre en charge le déploiement de Windows 10).  </li>
<li>  Déploiement des applications Windows 10 entreprise et Microsoft 365 à l’aide du gestionnaire de configuration de point de terminaison Microsoft ou de Microsoft 365.  </li>
<li>  Recommandations sur les options pour évaluer vos applications Windows 10.  </li>
<li>  Activation de l’analyse et des conseils de bureau par le biais de la création d’un plan de déploiement de l’analyse ordinateur de bureau.  </li>
<li>  Évaluation de la compatibilité des applications Microsoft 365 en tirant parti du tableau de bord de disponibilité Office 365 du gestionnaire de configuration ou de la boîte à outils de préparation autonome pour Office plus aide à déployer des applications Microsoft 365.  </li>
<li>  Création d’une liste de contrôle de correction sur ce que vous devez faire pour faire en sorte que votre environnement source réponde à la configuration minimale requise pour un déploiement réussi.  </li>
<li>  Fournir des conseils de mise à niveau pour vos appareils existants vers Windows 10 entreprise s’ils répondent à la configuration matérielle requise pour l’appareil.  </li>
<li>  Fournir des conseils de mise à niveau pour prendre en charge votre mouvement de déploiement existant. FastTrack recommande et fournit des conseils pour une mise à niveau sur place vers Windows 10. Des instructions sont également disponibles pour l’installation d'une image propre de Windows et les scénarios de déploiement Windows Auopilot.  </li>
<li>  Déploiement d’applications Microsoft 365 à l’aide du gestionnaire de configuration dans le cadre du déploiement de Windows 10.   </li>
<li>  Fournir des conseils pour aider votre organisation à se tenir au courant des applications Windows 10 entreprise et Microsoft 365 à l’aide de votre environnement de gestionnaire de configuration existant ou de Microsoft 365.  </li>
</ul>
  <strong>Les éléments suivants sont hors de portée </strong>  
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
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.  </td>
<td>  Pour mettre à niveau un PC, vous devez respecter les conditions suivantes :
<ul>
<li>  Système d’exploitation source : Windows 7 entreprise ou professionnel, Windows 8,1 entreprise ou professionnel.  </li>
<li>  Appareils : ordinateur de bureau, bloc-notes ou format tablette.  </li>
<li>  Système d’exploitation cible : fenêtre 10 entreprise.  </li>
</ul>
Pour mettre à niveau une infrastructure, vous devez respecter les exigences suivantes :
<ul>
<li>  Gestionnaire de configuration de point de terminaison Microsoft.  </li>
<li>  La version du gestionnaire de configuration doit être prise en charge par la version cible de Windows 10. Pour plus d’informations, reportez-vous au tableau de prise en charge du gestionnaire de configuration à la <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">prise en charge de Windows 10 dans Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender – Protection avancée contre les menaces (ATP)</strong></td>
<td>  Microsoft Defender – Protection avancée contre les menaces est une plateforme conçue pour aider les réseaux d’entreprise à prévenir, détecter et examiner les menaces avancées et à y répondre.  
  Nous fournissons des conseils à distance pour :
<ul>
<li>  Déploiement des technologies pour sécuriser vos points de terminaison.  </li>
<li>  Configuration de la protection des points de terminaison et des profils de restriction d’appareil.  </li>
<li>  Évaluation de la version du système d’exploitation et de la gestion des périphériques (notamment Intune, le gestionnaire de configuration du point de terminaison Microsoft, les objets de stratégie de groupe (GPO) et les configurations tierces), ainsi que l’état de vos services AV Windows Defender ou d’autres logiciels de sécurité de point de terminaison.  </li>
<li>  Évaluation de l’état de vos services AV Windows ou d’un autre logiciel de sécurité de point de terminaison.  </li>
<li>  Évaluation des proxys et des pare-feu pour limiter le trafic réseau.  </li>
<li>  Activation du service ATP Microsoft Defender en expliquant comment déployer un profil d’agent ATP à l’aide d’un point de terminaison intégré.  </li>
<li>  Conseils de déploiement, assistance de configuration et formation sur :
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
  Le niveau de sécurité.  
  </li>
</ul></li>
<li>  Examen des simulations et des didacticiels (par exemple, scénarios de pratique, faux programme malveillant et enquêtes automatisées).  </li>
<li>  Vue d’ensemble des fonctionnalités de compte-rendu et d’analyse des menaces.  </li>
<li>  L’intégration d’Office 365 – Protection avancée contre les menaces avec Microsoft Defender – Protection avancée contre les menaces.  </li>
<li>  Effectuer des procédures pas à pas dans le portail du Centre de sécurité Microsoft Defender.  </li>
<li>  Les systèmes d’exploitation suivants :
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Canal semi-annuel Windows Server (SAC) version 1803.  
  </li>
<li>  
  macOS versions 10,13, 10,14 et 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Remarque :</strong> Toutes les versions de Windows Server doivent être gérées par la dernière version de System Center Configuration Manager 2012 (versions 1012 R2, 1511 ou 1602) ou le gestionnaire de configuration du point de terminaison de Microsoft (version 2002 ou ultérieure). 

</li>
</ul>

<strong>Les éléments suivants sont hors de portée </strong>  
<ul>
<li>  Gestion de projet des activités de correction du client.  </li>
<li>  Support sur site.  </li>
<li>  Gestion continue et réponse aux menaces.  </li>
<li>  Intégration ou configuration des agents Microsoft Defender - PACM suivants :
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
</ul></li>
<li>  Intégration et configuration du serveur :
<ul>
<li>  
  Configuration d’un serveur proxy pour les communications hors ligne.  
  </li>
<li>  
  Configuration des packages de déploiement de Configuration Manager sur les instances et versions de gestionnaire de configuration de bas niveau.  
  </li>
<li>  
  Intégration de serveurs à Azure Security Center.  
  </li>
<li>  
  Serveurs non gérés par le gestionnaire de configuration.  
  </li>
</ul></li>
<li>  intégration et configuration d’macOS :
<ul>
<li>  
  Déploiement basé sur Intune manuel.  
  </li>
<li>  
  Déploiement basé sur JAMF.
  </li>
<li>  
  Autre déploiement basé sur des produits MDM (Mobile Device Management).  
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
<li>  
  Exploit Protection.  
  </li>
<li>  
  Pare-feu du réseau.  
  </li>
</ul></li>
<li>  Inscription ou configuration des Spécialistes des menaces Microsoft.  </li>
<li>  La configuration ou la formation, l’API de révision ou les connexions de gestion des événements et des informations de sécurité (SIEM).  </li>
<li>  Inscription ou configuration de la Protection Microsoft contre les menaces (MTP).  </li>
<li>  Formation ou conseils pour le repérage avancé.  </li>
<li>  Formation ou recommandations couvrant l’utilisation ou la création de requêtes Kusto.</li>
</li>
</ul>
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Attentes en matière d’environnement source</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Nous fournissons des conseils de déploiement pour l’intégration à Windows Virtual Desktop (un service de virtualisation d’application et de bureau). Windows Virtual Desktop tire parti de l’expérience multisession Windows 10 et est optimisé pour les applications Microsoft 365 pour entreprise avec une sécurité et une gestion intégrées pour Microsoft 365.</p>
<p>Nous fournissons des conseils à distance pour :</p>
<ul>
<li>Déployez votre environnement de bureau virtuel Windows avec les applications multisession Windows 10 entreprise et Microsoft 365 pour Enterprise à l’aide des éléments suivants :
<ul>
<li>Image Azure Marketplace.</li>
<li>Image partagée.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configuration de FSLogix :
<ul>
<li>Déploiement de l’agent FSLogix avec le conteneur de profil.</li>
<li>Déploiement de l’agent FSLogix avec un conteneur Office.</li>
<li>Configuration du dossier FSLogix avec des exclusions de contenu.</li>
</ul></li>
<li>Déploiement de Microsoft Edge.</li>
<li>Déploiement de Microsoft Teams.</li>
<li>Connexion à l’aide des clients de bureau virtuels Windows.</li>
</ul>

<strong>Les éléments suivants sont hors de portée</strong>
<ul>
<li>Gestion de projet du déploiement de bureau virtuel Windows du client.</li>
<li>Support sur site.</li>
<li>Déploiement et virtualisation d’applications tierces.</li>
<li>Images personnalisées.</li>
<li>Migrations et scénarios impliquant VMware et Citrix.</li>
<li>Scénarios Linux.</li>
<li>Conversion ou migrations de profils utilisateur.</li>
</ul>
Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a>   pour obtenir de l’aide sur ces services.</td>
<td>Vous devez déjà disposer des éléments suivants :
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Conditions requises en matière de licences de bureau virtuel Windows</a>.</li>
<li>Mise en réseau Azure :
<ul>
<li>Création de réseau virtuel (VNET) et création de sous-réseaux.</li>
<li>Groupes de sécurité du réseau et du pare-feu.</li>
<li>VPN et ExpressRoute.</li>
<li>Routage vers Azure à partir de l’organisation locale.</li>
<li>Règles de pare-feu pour autoriser la connectivité au bureau virtuel Windows.
</ul>
Pour plus d’informations, voir <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> prise en charge des clients de bureau à distance</a>.
</ul>
<ul><li>Installation générale d’Azure AD :
<ul>
<li>Stratégie <i>d’identité (vous ne pouvez utiliser qu’une des trois options suivantes) :</i>
<ul>
<li>Active Directory avec Azure AD Connect dans Azure.</li>
<li>Active Directory avec Azure AD Connect sur site sur un réseau privé virtuel (VPN) ou ExpressRoute.</li>
<li>Services de domaine Active Directory (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>Soutien aux applications


<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Produits pris en charge</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Soutien aux Applications</strong></td>
<td>  Application s’assurer est un service conçu pour résoudre les problèmes liés à la compatibilité des applications avec Windows 10 et Microsoft 365 apps. Lorsque vous demandez le service de garantie de l’application, nous vous aidons à résoudre les problèmes d’application valides sans coût supplémentaire pour vous avec un abonnement éligible. Nous fournissons également des conseils aux clients qui rencontrent des problèmes de compatibilité lors du déploiement de Windows Virtual Desktop et de Microsoft Edge et de tous les efforts raisonnables pour résoudre les problèmes de compatibilité. Nous fournissons une aide aux corrections pour les applications déployées sur les produits Microsoft suivants :
<ul>
<li>  <strong>Windows 10 </strong> (y compris les appareils ARM64)</li>
<li> <strong>Applications Microsoft 365</strong>  </li>
<li>  <strong>Le nouveau Microsoft Edge-</strong> Pour obtenir des instructions de déploiement, consultez <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">la rubrique vue d’ensemble des canaux Microsoft Edge</a>.  </li>
<li>  <strong>Bureau</strong> - virtuel Windows Pour plus d’informations, consultez <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">la rubrique qu’est-ce que le bureau virtuel Windows ? et le</a> <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Forum aux questions sur Windows 10 entreprise multi-session</a>.  </li>
</ul>

<strong>Les éléments suivants sont hors de portée </strong>  
<ul>
<li>  Inventaire et test des applications pour déterminer ce qui fonctionne et ce qui ne fonctionne pas sous Windows 10 et Microsoft 365 Apps. Pour obtenir des instructions plus sur ce processus, visitez le <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centre de Déploiement de Bureau</a>. Si vous êtes intéressé(e) par une évaluation approfondie de préparation de mise à niveau, terminez le formulaire<a href="https://go.microsoft.com/fwlink/?linkid=2053818">client demande pour l’évaluation bureau modernes</a>.</li>
<li>  Recherche des déclarations de support et de compatibilité avec Windows 10 dans les applications ISV tierces. Pour plus d’informations, consultez <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Analytique de bureau</a>.</li>
<li>Services uniquement pour le conditionnement des applications. Toutefois, l’équipe Soutien aux applications du bureau conditionne les applications que nous avons corrigées pour Windows 10 afin qu’elles puissent être déployées dans l’environnement du client.</li>
</ul>

<strong>Les responsabilités du client sont les suivants :</strong>  
<ul>
<li>  Création d’un inventaire d’applications.</li>
<li>  Validation de ces applications sous Windows 10 et Microsoft 365 Apps.</li>
</ul>
<strong>Remarque :</strong>  Microsoft ne peut pas modifier votre code source. Toutefois, l’équipe Soutien aux applications peut fournir des conseils aux développeurs d’applications si le code source est disponible pour vos applications. 


  Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft</a> pour obtenir de l’aide sur ces services.  </td>

</td>
<td><strong>Applications Windows 10 et Microsoft 365</strong>
<ul>
<li>  
  Les applications qui fonctionnaient sous Windows 7, Windows 8.1, Office 2010 et Office 2013 fonctionnent également sous Windows 10 et Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 sur ARM</strong>
<ul>
<li>  
Les applications qui fonctionnaient sous Windows 7, Office 2010 ou des versions ultérieures fonctionnent sur les applications Windows 10 et Microsoft 365 sur les appareils ARM64. 
  </li>
</ul>
  <strong>Remarque :</strong> Les exclusions et limitations de Windows 10 sur ARM sont les suivantes :
<ul>
<li>  
 Applications qui reposent sur des pilotes logiciels qui ne sont pas compatibles avec ARM.  
  </li>
<li>  
  Applications qui utilisent OpenGL ou OpenCL.   
  </li>
<li>  
  Les applications sont uniquement disponibles dans 64 bits (x64).  
  </li>
</ul>
<strong>Le nouveau Microsoft Edge</strong>
<ul>
<li>  
  Si vos applications ou sites Web fonctionnent sur Internet Explorer 11, les versions prises en charge de Google Chrome ou toute version de Microsoft Edge, ils fonctionnent également avec le nouveau Microsoft Edge.  
  </li>
<li>  
  Lorsque le site Web est en perpétuelle évolution, veillez à consulter la liste publiée de la <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">compatibilité des sites connus-impact sur les modifications apportées à Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Bureau virtuel Windows </strong>  
<ul>
<li>  
  Les applications virtualisées qui s'exécutent sur un hôte de la session Bureau à distance Windows Server s'exécutent également sur Windows 10 Entreprise multi-session dans le cadre de Windows Virtual Desktop.  
  </li>
<li>  
  Les applications qui s’exécutent sur un environnement VDI (Virtual Desktop Infrastructure) Windows 7 ou Windows 10 s’exécutent également sur Windows 7 entreprise et Windows 10 entreprise dans le cadre du bureau virtuel Windows.  
  </li>
<li>  
  Les applications s’exécutant sur les appareils clients Windows 7 ou Windows 10 s’exécutent également sur Windows 7 Entreprise et Windows 10 Entreprise dans le cadre de Windows Virtual Desktop.  
  </li>
</ul>
  <strong>Remarque :</strong> Les exclusions et limitations de compatibilité entre les sessions Windows 10 entreprise sont les suivantes :
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

## <a name="the-new-microsoft-edge"></a>Le nouveau Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails de l’aide FastTrack</strong></th>
<th><strong>Attentes en matière d’environnement source</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Microsoft Edge</strong> (pour les clients Windows 10 entreprise)</td>
<td><ul>
<li>  Nous fournissons des conseils de déploiement à distance et une assistance en matière de compatibilité pour : le déploiement de la nouvelle Microsoft Edge sur Windows 10 entreprise avec le gestionnaire de points de terminaison Microsoft (point de terminaison de configuration Microsoft ou Intune).  </li>
<li>  Configuration de Microsoft Edge (à l’aide des stratégies de groupe ou des stratégies d’application et de configuration de l’application Intune).  </li>
<li>  Inventorier la liste des sites pouvant nécessiter une utilisation en mode Internet Explorer.  </li>
<li>  Activation du mode Internet Explorer avec la liste de sites d’entreprise existante.  
  En outre, si vous disposez d’une application Web ou d’un site qui fonctionne avec Internet Explorer ou Google Chrome et que vous rencontrez des problèmes de compatibilité, nous fournissons des conseils pour résoudre le problème sans frais supplémentaires. Pour plus d’informations, consultez la rubrique <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">application</a> Apto.  </li>
</ul>

<strong>Les éléments suivants sont hors de portée </strong>  
<ul>
<li>Gestion de projet du déploiement Microsoft Edge du client.</li>
<li>  Support sur site.</li>

</td>
<td></td>
</tr>
</tbody>
</table>

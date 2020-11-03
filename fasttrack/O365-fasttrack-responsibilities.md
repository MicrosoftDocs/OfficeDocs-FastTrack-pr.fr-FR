---
title: Responsabilités FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Les responsables FastTrack ont les responsabilités suivantes lors de l’intégration.
ms.openlocfilehash: b0387ee7c525469e999f52f8f1994c8f41fb20fe
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827164"
---
# <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

> [!CAUTION]
> Ce contenu n’est plus à jour et il est prévu de le supprimer. Utilisez la table des matières dans le volet de navigation gauche pour voir le contenu actuel.

Les responsables FastTrack ont les responsabilités suivantes lors de l’intégration.\*
  
## <a name="general"></a>Général

- Nous vous fournissons une assistance technique à distance pour la mise en œuvre et le développement de la planification de la réussite, et pour les activités de configuration obligatoires, comme indiqué dans les descriptions détaillées des phases.
- Nous fournissons la documentation disponible, ainsi que des outils logiciels, des consoles d’administration, des scripts pour vous aider à réduire ou à éliminer les tâches de configuration, et des ressources pour la planification de la réussite. 
    
## <a name="initiate-phase"></a>Phase de lancement

- Travailler avec vous pour comprendre votre mission, les objectifs de votre organisation et les plans de l’utilisation du service.
- Travailler avec vous à l'aide de services de collaboration Office 365 (comme Microsoft Teams) pour commencer l'intégration.   
- Définir les services éligibles que vous souhaitez intégrer. 
    
## <a name="assess-phase"></a>Phase d’évaluation

- Organiser un appel de planification de la réussite pour vous aider à assurer l’adoption par les utilisateurs.  
- Fournir un aperçu administratif.
- Fournir des conseils à propos des éléments suivants : 
  - exigences en matière de DNS (Domain Name System), de réseau et d’infrastructure ;
  - besoins du client (navigateur Internet, système d’exploitation client, appareil mobile et besoins des services) ;
  - identité utilisateur et approvisionnement ,
  - activation des services éligibles achetés et définis dans le cadre de l’intégration ; 
  - détermination de la valeur et adoption des services.  
- Établir la chronologie des activités de correction.
- Fournir une liste de contrôle de correction. 
- Évaluer l'infrastructure SharePoint Server 2013 ou SharePoint Server 2016 existante, y compris :
  - Conditions préalables pour SharePoint Online hybride. 
  - Préparation de l’infrastructure locale pour les fonctionnalités SharePoint Online hybride.
  - Accès aux points de terminaison SharePoint Online obligatoires.
  - Audiences pour OneDrive Entreprise hybride. 
- Évaluer l’infrastructure Lync, Skype Entreprise Online ou Microsoft Teams existante, y compris :
  - la stratégie de déploiement du client Skype Entreprise ou Teams pris en charge ;
  - l’accès aux points de terminaison ;
  - la qualité de la connexion ;
  - les estimations de la bande passante.
  - les conditions requises pour prendre en charge la configuration de serveur de domaine fractionné ;
  - la préparation des utilisateurs identifiés à déplacer vers Skype Entreprise Online ou Teams.
- Évaluer l’infrastructure de messagerie, y compris : 
  - les principes généraux de flux de messagerie et de routage ;
  - l’accès client (y compris les points de terminaison d’accès client publiés existants) ;
  - l’environnement de messagerie source pour les besoins de l’intégration.
- Fourniture d’instructions de migration de données si le service de migration de données du centre FastTrack est utilisé et que vous êtes éligible.
    
## <a name="remediate-phase"></a>Phase de correction

- Participer à des téléconférences avec vous selon le calendrier convenu afin d’examiner la progression des activités de correction et de la planification de la réussite. 
- Vous guider dans l’exécution des outils d’évaluation pour identifier et résoudre les problèmes et interpréter les résultats.
    
## <a name="enable-phase"></a>Phase d’activation

Fournir des conseils à propos des éléments suivants : 
- l’évaluation de l’avancement concernant la planification de la réussite et la détermination de l’assistance supplémentaire dont vous avez besoin.
- l'activation de votre locataire Office 365 ;  
- la configuration des protocoles TCP/IP et des ports de pare-feu ;
- la configuration du DNS pour les services éligibles ; 
- la validation de la connectivité à Office 365 ;
- la connexion de votre Active Directory local avec Azure Active Directory :
  - l'installation d'un serveur de synchronisation d'annuaires entre vos services de domaine Active Directory (AD DS) et Office 365, le cas échéant ; 
  - la configuration de la synchronisation de mot de passe (hachage de mot de passe) pour Office 365 (Azure Active Directory) avec l’outil Azure Active Directory Connect, si nécessaire ;
  - Pour les environnements de forêt unique et de forêts multiples :
      - la configuration de l'authentification directe Azure Active Directory, si nécessaire ;\*\*
      - la configuration de l'authentification unique (SSO) transparente Azure Active Directory, si nécessaire.\*\*\*
    > [!NOTE]
    > L'authentification directe Azure Active Directory pour les environnements de forêts multiples est prise en charge s'il existe des approbations de forêt entre vos forêts Active Directory et si le routage des suffixes de noms est correctement configuré. Des agents supplémentaires peuvent être installés sur plusieurs serveurs locaux pour fournir une haute disponibilité pour les demandes de connexion. Pour plus d'informations, reportez-vous à [Authentification directe Azure Active Directory : Démarrage rapide](https://go.microsoft.com/fwlink/?linkid=860094) et [Authentification unique transparente Azure Active Directory - Démarrage rapide](https://go.microsoft.com/fwlink/?linkid=860095). 
- Pour une forêt unique lorsque les identités fédérées sont ciblées : 
  - l'installation et la configuration des services AD FS pour l'authentification de domaine local avec Office 365 dans une configuration à site unique et à tolérance de panne, si nécessaire.
  - l’installation et la configuration de WAP pour publier votre infrastructure AD FS sur Internet, si nécessaire.
    > [!NOTE]
    > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée. 
- Le test de la fonctionnalité d’authentification unique transparente, si elle est déployée.
- la détermination de la valeur et l’adoption des services.
    
\*\*Pour obtenir plus d’informations sur les limites de l’authentification directe, reportez-vous à la rubrique [Authentification directe Azure Active Directory : limites actuelles](https://go.microsoft.com/fwlink/?linkid=860356). 

\*\*\*Pour obtenir plus d'informations sur les problèmes de l'authentification unique transparente, reportez-vous à [Résoudre les problèmes d'authentification unique transparente Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926).

## <a name="exchange-online"></a>Exchange Online

Fournir des conseils à propos des éléments suivants :
- la création ou mise à jour des enregistrements DNS ; 
- l'activation de l'acheminement de courrier électronique entre le système de messagerie source et les environnements Office 365 ; 
- la configuration des fonctionnalités Exchange Online Protection, Protection contre la perte de données (DLP) et Chiffrement des messages Office 365 (OME) et Office 365 - Protection avancée contre les menaces (ATP) (si elles sont disponibles dans votre abonnement) et la vérification que vos enregistrements MX pointent vers Office 365 pour tous les domaines à extension messagerie validés.
- la configuration de l'installation hybride soit entre l'organisation Exchange locale unique et Office 365 *, soit*  entre plusieurs organisations Exchange locales et Office 365. 
- La configuration des clients de boîte aux lettres (Outlook pour Windows, Outlook sur le web et Outlook pour iOS et Android).
- la configuration de l’automatisation, de l’enquête et de la réponse pour Office 365 - Protection avancée contre les menaces (si ces fonctionnalités sont disponibles dans votre abonnement).
    
Pour plus d’informations sur les responsabilités de la migration de données, reportez-vous à la rubrique [Migration des données](O365-data-migration.md).
  
## <a name="microsoft-365-apps"></a>Microsoft 365 Apps

Fournir des conseils à propos des éléments suivants :
- Résolution des problèmes de déploiement.
- Attribution des licences utilisateur final et basées sur l’appareil à l’aide du [Centre d’administration Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) et de Windows PowerShell.
- Installation de Microsoft 365 Apps à partir du portail Office 365 avec l’option Démarrer en un clic.
- Installation des applications Office Mobile (comme Outlook pour iOS et Android, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS ou Android. 
- Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365.
- Sélection et configuration d’une installation locale ou dans le cloud.
- Création du code XML de configuration de l’outil de déploiement d’Office avec l’outil de personnalisation d’Office ou de code XML natif pour configurer le package de déploiement.
- Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.

## <a name="microsoft-information-governance"></a>Gouvernance de l'information de Microsoft 

Fournir des conseils sur :
- Gestion des enregistrements.
  - Appliquer les autorisations pour la gestion des enregistrements.
  - Des conseils sur la traduction des plans de dossiers et des calendriers de conservation en étiquettes et en politiques.
  - Créer des étiquettes et des politiques de rétention.
  - Établir des politiques de suppression.
  - Examiner les articles pour la disposition.
- Gestion des risques d'initiés.
  - Activation des journaux d'audit d'Office 365.
  - Configuration des paramètres dans le cadre de la gestion des risques d'initiés.
  - Créer des politiques de risque d'initié en utilisant les playbooks intégrés.
  - Configurer les autorisations pour la conformité de la communication.
  - Créer des politiques de conformité en matière de communication à l'aide de modèles personnalisables.
  - Suivi et révision des alertes.
- La gouvernance de l'information.
  - Appliquer les autorisations pour la gouvernance de l'information.
  - Création de labels de rétention.
  - Publication d'étiquettes de rétention (manuelle et automatique).
  - Créer des emplois d'importation.
- EDiscovery avancée.
  - Données non-Office 365.
  - Définition des autorisations.
  - Créer des cas.
  - Ajout de gardiens. 
  - Mise en suspens légale.
  - Recherche.
  - Les ensembles de révision.
  - L'exportation de contenu.

## <a name="microsoft-information-protection"></a>Protection des informations de Microsoft

Fournir des conseils sur :
- Classification des données.
- Types d'informations sensibles.
- Création de labels de sensibilité.
- Appliquer des labels de sensibilité. 
- Étiquetage unifié.
- Des classificateurs avec capacité d’apprentissage.
- Connaître ses données avec l'explorateur de contenu et l'explorateur d'activités.
- Publication d'étiquettes à l'aide de politiques (manuelles et automatiques).
- Créer des politiques de prévention des pertes de données (DLP) pour les conversations et les canaux de Microsoft Teams.

## <a name="microsoft-teams"></a>Microsoft Teams

Fournir des conseils à propos des éléments suivants :
- Vérification de la configuration minimale requise.
- la configuration de ports de pare-feu ;
- Configuration de DNS.  
- Confirmation que Teams est activé sur votre client Office 365.
- Activation ou désactivation des licences utilisateur.
- Distribution du client Teams.
- Fonctionnalités de professionnel de l’informatique et d’administration.
- Fonctionnalités de base du produit.
- Modèles de réussite des clients.
- Création de comptes à associer aux appareils de système de salle pris en charge (jusqu’à 10 comptes). 
- Activation du routage direct.
- Activation de l’audioconférence.
- Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.
- Affectation d’une passerelle de conférence aux utilisateurs titulaires d’une licence.
- Activation du système téléphonique.
- Intégration pour l’activation du système téléphonique et des plans d’appel (dans les pays disponibles).
- Affectation de numéros aux utilisateurs titulaires d’une licence.
- Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.
- Prise en charge des demandes de service de portage de numéro local au-delà de 999. 
- Activation des événements en direct Teams. 
- Configuration de l’organisation et intégration à Microsoft Stream.

## <a name="office-365-advanced-threat-protection"></a>Protection avancée contre les menaces Office 365

Fournir des conseils à propos des éléments suivants :
- Activation des liens fiables.
- Activation des pièces jointes fiables.
- Activation des stratégies anti-hameçonnage.
- Configuration de l’automatisation, de l’enquête et de la réponse.
- Utilisation du Simulateur d’attaques.
- Création de rapports et analytique des menaces.
    
## <a name="onedrive-for-business"></a>OneDrive Entreprise

Fournir des conseils à propos des éléments suivants :
- l'identification de la version locale de SharePoint et des options d'intégration ; 
- l’identification des options de synchronisation et d’identité ;
- Sélection d’une option de déploiement :   
  - Déploiement juste-à-temps.
  - Déploiement intermédiaire (effectué en séquences et en phases).
- Préparation de l'environnement local pour le déploiement de OneDrive Entreprise :
  - Identification du client de synchronisation OneDrive Entreprise approprié.
  - la configuration du DNS, des ports réseau et du pare-feu ; 
- l’attribution des licences utilisateur final ; 
- la configuration d'audiences SharePoint Online pour le contrôle et la gestion de l'accès à OneDrive Entreprise ; 
- Déploiement du client de synchronisation OneDrive Entreprise sur les ordinateurs de bureau.   
- Méthode de configuration de la redirection OneDrive Entreprise hybride avec SharePoint Online (SharePoint 2013 et SharePoint 2016 uniquement).
- Migration des données si le service de migration de données du centre FastTrack est utilisé et que vous êtes éligible.
    
## <a name="outlook-for-ios-and-android"></a>Outlook pour iOS et Android

Fournir des conseils à propos des éléments suivants :
- Téléchargement d’Outlook sur des appareils iOS et Android.
- Configuration des comptes de messagerie dans Outlook.

## <a name="power-bi"></a>Power BI

Fournir des conseils à propos des éléments suivants :
- Révision des plans d'abonnement Power BI. 
- Ajout du service Power BI. 
- Téléchargement de l'application Power BI Desktop.
    
## <a name="project-online"></a>Project Online

Fournir des conseils à propos des éléments suivants :
- Révision des plans d’abonnement.
- Vérification des fonctionnalités SharePoint de base.
- Ajout du service Project Online.
- Ajout d'utilisateurs à Project Online, avec la synchronisation ERP.
- Vérification des fonctionnalités Project Online de base en créant un projet
    
## <a name="project-online-professional-and-project-online-premium"></a>Project Online Professional Professionnel et Project Online Premium

Fournir des conseils à propos des éléments suivants :
- Résolution des problèmes de déploiement.
- Attribution des licences utilisateur final à l’aide du [Centre d’administration Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) et de Windows PowerShell.
- Téléchargement et installation de client de bureau Project Online à partir du portail.   
- Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365 ou des modèles de stratégie de groupe.
- Configuration d'un serveur de distribution sur site unique pour Client de bureau Project Online et instructions relatives à la création d'un fichier configuration.xml pour l'outil Déploiement 2016 d'Office. 
- Connexion de Client de bureau Project Online à Project Online.

## <a name="sharepoint-online"></a>SharePoint Online

Fournir des conseils à propos des éléments suivants :
- la configuration de l’approvisionnement utilisateur, y compris la gestion des licences.
- l'activation de la création de sites pour votre administrateur SharePoint Online ;    
- la planification des collections de sites ; 
- la sécurisation du contenu et la gestion des autorisations ;
- l’activation de sites personnels et de fonctionnalités sociales ;
- la configuration des fonctionnalités SharePoint Online. 
- l’assurance de la migration de données si le service de migration de données du centre FastTrack est utilisé et que vous êtes éligible.
- l’évaluation de la configuration d’infrastructure de batterie de serveurs SharePoint locale nécessaire pour SharePoint Online hybride ; 
- l’utilisation des outils et de l’automatisation pour :
  - Configurer les applications de service de recherche dans le cloud en local. 
  - Configurer l’approbation entre les environnements SharePoint en local et dans le cloud.
- Configurer des sites SharePoint locaux afin d’utiliser les fonctionnalités SharePoint Online hybride.
    
## <a name="skype-for-business-online"></a>Skype Entreprise Online

Fournir des conseils à propos des éléments suivants :
- Approvisionnement d'identités Skype Entreprise pour Office 365. 
- Activation des fonctionnalités de conférence en ligne, de messagerie instantanée et de présence pour Office 365. 
- Création de comptes à associer aux appareils de système de salle pris en charge (jusqu’à 10 comptes). 
- Configuration d'un environnement de serveur de domaine séparé pour prendre en charge les scénarios hybrides Lync ou Skype Entreprise Online (le cas échéant).
- Activation de l’audioconférence :
  - Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.
  - Affectation d’une passerelle de conférence aux utilisateurs titulaires d’une licence.
- Activation du système téléphonique :
  - Intégration pour l’activation du système téléphonique et des plans d’appel (dans les pays disponibles).
  - Affectation de numéros aux utilisateurs titulaires d’une licence.
  - Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.
  - Prise en charge des demandes de service de portage de numéro local au-delà de 999.
- Activation de la diffusion de réunion Skype Entreprise :
  - Activation de l’intégration d’instructions pour la diffusion de réunion Skype Entreprise.
  - Configuration de l’organisation pour la fédération avec le service de diffusion de réunion.
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Fournir des instructions sur la conversion de votre réseau Yammer Basic unique en un seul réseau Yammer Enterprise.
  
\*Pour plus d’informations sur les responsabilités FastTrack pour Office 365 pour le gouvernement américain, consultez l’article relatif aux [responsabilités FastTrack pour Office 365 pour le gouvernement américain](US-Gov-appendix-fasttrack-responsibilities.md).

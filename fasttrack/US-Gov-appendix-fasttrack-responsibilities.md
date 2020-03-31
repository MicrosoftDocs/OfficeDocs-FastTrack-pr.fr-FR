---
title: Responsabilités FastTrack pour le gouvernement américain Office 365
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 3/03/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Les responsables FastTrack ont les responsabilités suivantes lors de l’intégration.
ms.openlocfilehash: 03718f62f7ce28d9e3cbd2b586b64bc26b93e614
ms.sourcegitcommit: 7a2535e510420496dabfcea5accbb36ab2fe21d2
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/30/2020
ms.locfileid: "43052787"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Responsabilités FastTrack pour le gouvernement américain Office 365

Les responsables FastTrack ont les responsabilités suivantes lors de l’intégration.  
  
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
- Fournir des conseils à propos des éléments suivants : 
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
- Évaluer l'infrastructure Lync ou Skype Entreprise Online existante, y compris :  
  - la stratégie de déploiement du client Skype Entreprise pris en charge ;  
  - l’accès aux points de terminaison ;  
  - la qualité de la connexion ;  
  - les estimations de la bande passante.  
  - les conditions requises pour prendre en charge la configuration de serveur de domaine fractionné ;  
  - la préparation des utilisateurs identifiés à déplacer vers Skype Entreprise Online.  
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
      - La configuration de l’authentification directe Azure Active Directory, si nécessaire (non disponible dans les offres GCC High ou DoD).
      - Configuration de l’authentification unique (SSO) transparente Azure Active Directory, si nécessaire (non disponible dans les offres GCC High ou DoD).
    > [!NOTE]
    > L'authentification directe Azure Active Directory pour les environnements de forêts multiples est prise en charge s'il existe des approbations de forêt entre vos forêts Active Directory et si le routage des suffixes de noms est correctement configuré. Des agents supplémentaires peuvent être installés sur plusieurs serveurs locaux pour fournir une haute disponibilité pour les demandes de connexion. Pour plus d'informations, reportez-vous à [Authentification directe Azure Active Directory : Démarrage rapide](https://go.microsoft.com/fwlink/?linkid=860094) et [Authentification unique transparente Azure Active Directory - Démarrage rapide](https://go.microsoft.com/fwlink/?linkid=860095).[!NOTE]
    > Pour obtenir plus d’informations sur les limites de l’authentification directe, reportez-vous à la rubrique [Authentification directe Azure Active Directory : limites actuelles](https://go.microsoft.com/fwlink/?linkid=860356).[!NOTE]
    > Pour obtenir plus d'informations sur les problèmes de l'authentification unique transparente, reportez-vous à [Résoudre les problèmes d'authentification unique transparente Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926). 
- Pour une forêt unique lorsque les identités fédérées sont ciblées : 
  - l'installation et la configuration des services AD FS pour l'authentification de domaine local avec Office 365 dans une configuration à site unique et à tolérance de panne, si nécessaire.  
  - l’installation et la configuration de WAP pour publier votre infrastructure AD FS sur Internet, si nécessaire. 
    > [!NOTE]
    > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée. 
- le test de la fonctionnalités d’authentification unique, si elle est déployée.   
- la détermination de la valeur et l’adoption des services.
    
## <a name="exchange-online"></a>Exchange Online

Fournir des conseils à propos des éléments suivants : 
- la création ou mise à jour des enregistrements DNS ;    
- l'activation de l'acheminement de courrier électronique entre le système de messagerie source et les environnements Office 365 ;    
- la configuration des fonctionnalités Exchange Online Protection (y compris les fonctionnalités Exchange Online - Protection avancée contre les menaces si elles sont disponibles dans votre abonnement) et la vérification que votre enregistrement MX pointe vers Office 365 pour tous les domaines à extension messagerie validés.   
- la configuration de l'installation hybride soit entre l'organisation Exchange locale unique et Office 365 *, soit*  entre plusieurs organisations Exchange locales et Office 365. 
- Configuration de la messagerie unifiée (MU) avec Exchange Online (la messagerie unifiée n’est pas disponible dans les forfaits GCC DoD). 
    
Pour plus d’informations sur les responsabilités de la migration de données, reportez-vous à la rubrique [Migration des données](O365-data-migration.md).
  
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
    
## <a name="skype-for-business-online"></a>Skype Entreprise Online

Fournir des conseils à propos des éléments suivants :
- Approvisionnement d'identités Skype Entreprise pour Office 365.   
- Activation des fonctionnalités de conférence en ligne, de messagerie instantanée et de présence pour Office 365.  
- Création de comptes à associer aux appareils de système de salle pris en charge (jusqu’à 10 comptes).    
- Configuration d'un environnement de serveur de domaine séparé pour prendre en charge les scénarios hybrides Lync ou Skype Entreprise Online (le cas échéant).   
- Activation de l’audioconférence :   
  - Configuration de l’organisation pour les paramètres par défaut de la passerelle de conférence.   
  - Affectation d’une passerelle de conférence aux utilisateurs titulaires d’une licence. 
- Activation du système téléphonique (non disponible dans les offres GCC High ou DoD) :  
  - Intégration pour l’activation du système téléphonique et des plans d’appel (dans les pays disponibles). 
  - Affectation de numéros aux utilisateurs titulaires d’une licence.  
  - Instructions de portage de numéro local via l’interface utilisateur jusqu’à 999.  
  - Prise en charge des demandes de service de portage de numéro local au-delà de 999.  
- Activation de la diffusion de réunion Skype entreprise (non disponible dans les offres GCC High ou DoD) :  
  - Activation de l’intégration d’instructions pour la diffusion de réunion Skype Entreprise.  
  - Configuration de l’organisation pour la fédération avec le service de diffusion de réunion.
    
## <a name="microsoft-teams"></a>Microsoft Teams

Fournir des conseils à propos des éléments suivants :
- Vérification de la configuration minimale requise.   
- la configuration de ports de pare-feu ;  
- Configuration de DNS.  
- Confirmation que Microsoft Teams est activé sur votre client Office 365.   
- Activation ou désactivation des licences utilisateur.  
- Distribution du client Microsoft Teams.    
- Fonctionnalités de professionnel de l’informatique et d’administration. 
- Fonctionnalités de base du produit.  
- Modèles de réussite des clients.
    
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
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Fournir des instructions sur la conversion de votre réseau Yammer Basic unique en un seul réseau Yammer Enterprise.

> [!NOTE]
> Yammer Enterprise n’est pas un composant d’Office 365 le gouvernement américain, mais peut être acquis gratuitement en tant qu’offre autonome pour chaque utilisateur titulaire d’une licence pour Office 365 dans GCC. Cette offre est actuellement limitée aux clients qui achètent Office 365 GCC sous les contrats d’entreprise et les contrats d’abonnement Enterprise. Yammer n’est pas disponible dans les plans GCC High ou DoD.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Fournir des conseils à propos des éléments suivants :
- Résolution des problèmes de déploiement.   
- Attribution des licences utilisateur final à l’aide du [Centre d’administration Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) et de Windows PowerShell.  
- Installation de Office 365 ProPlus à partir du portail Office 365 avec l’option Démarrer en un clic.   
- Installation des applications Office Mobile (comme Outlook Mobile, Word Mobile, Excel Mobile et PowerPoint Mobile) sur vos appareils iOS, Android ou Windows Mobile.   
- Configuration des paramètres de mise à jour à l’aide de l’outil Déploiement 2016 Office ou des modèles de stratégie de groupe.   
- Configuration d’un serveur de distribution sur site unique pour Office 365 ProPlus, incluant l’assistance concernant la création d’un fichier configuration.xml à utiliser avec l’outil Déploiement d’Office 365.   
- Déploiement à l’aide de Microsoft Endpoint Configuration Manager, incluant une assistance à la création du packaging Microsoft Endpoint Configuration Manager.

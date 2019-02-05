---
title: Annexe B  Avantages supplémentaires du centre FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/2/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Les clients qui achètent au moins 20 000 licences pour un client Exchange Online peuvent bénéficier de services supplémentaires du Centre FastTrack. Pour plus d'informations, reportez-vous à Offres et services éligibles.
ms.openlocfilehash: abdb722bdb69945a1a90d8cae3fe71a5259e9dc9
ms.sourcegitcommit: 0a8250d759e010cff6958016267f29acb0b7e17c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/01/2019
ms.locfileid: "29696721"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Annexe B : Avantages supplémentaires du centre FastTrack

Les clients qui achètent au moins 20 000 licences pour un client Exchange Online peuvent bénéficier de services supplémentaires du Centre FastTrack. Pour plus d'informations, reportez-vous à [Offres et services éligibles](M365-eligible-services-and-plans.md). 
  
## <a name="onboarding-and-migration-phases"></a>Phases d’intégration et de migration

## <a name="core"></a>Noyau

Les autres services d'intégration de base disponibles incluent des conseils de configuration pour les services Active Directory Federation Services (AD FS) géo-redondants et les stratégies d'accès au client AD FS pour le service. 
  
## <a name="exchange-online"></a>Exchange Online

Pour Exchange Online, nous fournissons des conseils de configuration pour les éléments suivants :
- Définition de la messagerie unifiée (MU) avec Exchange Online.
- Configuration de la coexistence entre Exchange Online et les dossiers publics locaux hérités.
- Intégration d’applications avec extension messagerie. 
- Planification et regroupement pour la migration de boîtes aux lettres
    
## <a name="skype-for-business-online"></a>Skype Entreprise Online

Pour Skype Entreprise Online, nous fournissons des conseils pour la migration d'utilisateurs locaux Lync et Skype Entreprise vers Skype Entreprise Online.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Pour Office 365 ProPlus, nous fournissons des conseils pour les éléments suivants : 
- Évaluation et planification axées sur la préparation de votre environnement pour le déploiement initial et la gestion des mises à jour conformément aux meilleures pratiques de Microsoft. 
- Développement de configurations de déploiement et de paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365. 
- Création d'un package de déploiement à l'aide de System Center Configuration Manager.  
- Déploiement et configuration de la télémétrie Office pour vous aider à évaluer l’utilisation de solutions et de documents Office essentiels pour l’entreprise pour la compatibilité des applications.
    
## <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Les spécialistes de FastTrack ont les responsabilités suivantes lors de l’intégration. Elles peuvent s’ajouter ou se substituer aux activités définies dans la rubrique [Responsabilités FastTrack](O365-fasttrack-responsibilities.md).
  
## <a name="general"></a>Général

- Nous vous fournissons une assistance technique à distance pour la mise en œuvre et le développement de la planification de la réussite, et pour les activités de configuration obligatoires, comme indiqué dans [Phases d'intégration et de migration](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Phase d’évaluation

- Organiser un appel de planification de la réussite pour vous aider à assurer l’adoption par les utilisateurs. 
- Évaluer l’environnement pour prendre en charge la configuration d’AD FS géo-redondante.  
- Effectuer une évaluation pour déterminer les conditions requises pour l’accès au client AD FS.
    
## <a name="enable-phase"></a>Phase d’activation

### <a name="geo-redundant-ad-fs-guidance"></a>Conseils sur la configuration AD FS géo-redondante

- Fournir un modèle d’architecture de référence standard pour une topologie AD FS géo-redondante couvrant deux (2) centres de données. L’architecture standard fournit les avantages suivants :
  - Authentification fédérée pour les services dans l’étendue des as du Centre FastTrack. 
  - Résilience de site unique.  
  - Disponibilité élevée et basculement.  
  - Conseils de dimensionnement. 
- Fournir des conseils concernant l'utilisation de la base de données interne Windows et de SQL Server comme instance de base de données pour la batterie de serveurs AD FS.   
- Valider l’établissement de l’authentification fédérée pour chaque forêt dans l’étendue.  
- Vérifier le fonctionnement de l’authentification fédérée pour un nombre d’utilisateurs allant jusqu’à 10.
    
> [!NOTE]
> Les déploiements AD FS sont comptabilisés pour l'éligibilité aux autres avantages, pour les utilisateurs ayant des configurations à plusieurs forêts Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Conseils sur la stratégie d’accès au client AD FS

- Passer en revue les stratégies et la configuration requises pour sécuriser les ressources Office 365.  
- Fournir des conseils et de l'aide pour configurer la stratégie d'accès au client AD FS pour les scénarios d'accès au client identifiés dans les limites des scénarios pris en charge. Pour plus d'informations, voir [Limiter l'accès aux services Office 365 selon le lieu de résidence du client](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Valider la fonctionnalité d’authentification fédérée avec les stratégies d’accès client modifiées pour les scénarios d’accès identifiés avec la configuration pour 10 utilisateurs au maximum.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Exchange Conseils sur la messagerie unifiée

- Fournir des conseils sur la configuration requise sur Exchange Online pour activer jusqu'à 10 : 
  - plans de numérotation de messagerie unifiée ;   
  - stratégies de boîte aux lettres de messagerie unifiée ; 
  - standards automatiques.  
- Fournir des conseils pour la configuration de l'environnement Lync ou Skype Entreprise local pour activer la messagerie unifiée et cibler plus particulièrement :  
  - les stratégies hébergées dans Exchange Online ;  
  - les stratégies de messagerie vocale hébergées dans Exchange Online. 
  - les contacts standard automatiques de messagerie unifiée et la messagerie vocale Outlook pour rediriger les utilisateurs vers Exchange Online ; 
  - aide à la création des enregistrements d’emplacement du service (SRV) comme requis pour la fédération.
> [!NOTE]
> La messagerie unifiée peut être configurée avec les passerelles IP de MU et les contrôleurs de frontière de session pris en charge. Pour plus d’informations, reportez-vous à la rubrique [Intégration des systèmes téléphoniques à la messagerie unifiée](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Conseils sur la coexistence avec les dossiers publics

- Fournir des conseils sur la coexistence d’une arborescence de dossiers publics unique, notamment :  
  - Préparation d'un dossier public dans Exchange 2007, Exchange 2010 et Exchange 2013. 
  - Cmdlets Windows PowerShell nécessaires pour synchroniser la hiérarchie de dossiers publics Exchange 2007, Exchange 2010 et Exchange 2013 avec Exchange Online.  
  - Configuration Exchange Online pour rediriger l'accès aux dossiers publics vers les dossiers publics locaux.  
  - Configuration de l'accès aux dossiers publics à partir de Exchange Online vers un seul environnement local Exchange 2007, Exchange 2010 ou Exchange 2013.  
  - Aide à la validation d'accès à l'environnement de dossier public pour 10 utilisateurs au maximum dans Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Procédure d’intégration d’applications à extension messagerie

- Fournir des modèles de conseils pour les éléments suivants :  
  - Applications de publipostage.  
  - Applications acheminant les e-mails via Exchange.  
  - Applications utilisant les boîtes aux lettres Exchange.  
  - Applications nécessitant l’installation de composants tiers ou personnalisés sur les serveurs Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Planification et regroupement de migration de boîtes aux lettres

- Fournir des conseils pour créer un plan de migration, notamment :  
  - Le regroupement d’utilisateur et de ressources par lots.
  - La coordination du déploiement des packages logiciels requis avec des lots de migration.   
  - Des conseils pour créer un plan de communication pour les utilisateurs finaux. 
  - La coordination de la taille des lots de migration, des taux d’erreur et de l’assistance technique prévue. 
- Fournir des conseils pour regrouper les boîtes aux lettres utilisateur et de ressources par lots selon le type, la fonction dans l’entreprise et l’accès délégué grâce à des informations pertinentes fournies par le client.
    
## <a name="skype-for-business-online"></a>Skype Entreprise Online

- Fournir des conseils pour migrer les utilisateurs par lots dans un déploiement hybride Skype Entreprise (en conservant les listes de contacts des utilisateurs).
    
## <a name="office-365-proplus"></a>Office 365 ProPlus

- Fournir des conseils et une assistance pour :  
  - Évaluation et planification conformément aux meilleures pratiques de Microsoft pour le déploiement initial et la gestion des mises à jour.
  - Déploiement et configuration de la télémétrie Office. 
  - Activation de la journalisation de télémétrie pour les clients Office 2013 et versions ultérieures à l'aide de la stratégie de groupe. 
  - Déploiement des agents de télémétrie Office pour clients Office de versions antérieures (Office 2003, Office 2007 et Office 2010). 
  - Déploiement du processeur de télémétrie 
    > [!NOTE]
    > Cette opération nécessite un emplacement de partage de fichiers pour stocker les données de télémétrie et un serveur exécutant SQL Server 2005 ou une version ultérieure auquel envoyer les données transformées. 
  
## <a name="your-responsibilities"></a>Vos responsabilités

Vous avez les responsabilités suivantes lors de l’intégration. Elles s’ajoutent aux responsabilités définies dans la section [Vos responsabilités](O365-your-responsibilities.md). 
  
- Nommer et gérer les ressources selon le plan de projet.  
- Prendre des mesures à temps pour atténuer les risques et résoudre les problèmes soulevés par le client, les responsables de projet partenaires et le responsable FastTrack.   
- Passer en revue les rapports d’état et agir en conséquence.   
- Nommer un commanditaire opérationnel ou un responsable pouvant prendre des décisions afin de diriger le comité de pilotage.  
- Nommer un commanditaire opérationnel pour collaborer avec le commanditaire exécutif Microsoft.  
- Établir une réunion mensuelle pour le comité de pilotage.
    

  


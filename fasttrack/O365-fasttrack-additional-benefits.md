---
title: 'Annexe A : Avantages supplémentaires du centre FastTrack'
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: None
description: Les clients qui achètent au moins 20 000 licences pour un client Exchange Online peuvent bénéficier de services supplémentaires du Centre FastTrack. Pour plus d'informations, reportez-vous à Offres et services éligibles.
ms.openlocfilehash: 7b98f341bf645b83a91e11eec1a1f2347380d97a
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338436"
---
# <a name="appendix-a---fasttrack-center-additional-benefit"></a>Annexe A : Avantages supplémentaires du centre FastTrack

> [!CAUTION]
> Ce contenu n’est plus à jour et il est prévu de le supprimer. Utilisez la table des matières dans le volet de navigation gauche pour voir le contenu actuel.

Les clients qui achètent au moins 20 000 licences pour un client Exchange Online sont éligibles pour les services supplémentaires du centre FastTrack. Pour plus d’informations, consultez la rubrique [éligibilité](eligibility.md) . 
  
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
  
## <a name="microsoft-365-apps"></a>Microsoft 365 Apps

Pour Microsoft 365 Apps, nous fournissons des conseils dans les domaines suivants : 
- Évaluation et planification axées sur la préparation de votre environnement pour le déploiement initial et la gestion des mises à jour conformément aux meilleures pratiques de Microsoft. 
- Développement de configurations de déploiement et de paramètres de mise à jour à l’aide de l’outil Déploiement d’Office 365 et de l’Outil de personnalisation Office. 
- Déploiement du packaging à l’aide de Microsoft Endpoint Configuration Manager.  
- Activation de l’utilisation du Readiness Toolkit pour Office, qui permet d’identifier des problèmes de compatibilité potentiels avec vos macros Microsoft Visual Basic pour Applications (VBA) et autres compléments que vous utilisez avec Office.
    
## <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Les responsables FastTrack ont les responsabilités suivantes lors de l’intégration. Celles-ci peuvent être en plus ou remplacent les activités définies dans [processus et attentes](process-and-expectations.md).
  
## <a name="general"></a>Général

- Fournissez une assistance technique à distance pour les activités de planification de la réussite, de mise en œuvre et de configuration requise, comme indiqué dans [produits et fonctionnalités](products-and-capabilities.md).
    
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
    
## <a name="microsoft-365-apps"></a>Microsoft 365 Apps

- Fournir des conseils et une assistance pour :  
  - Évaluation et planification conformément aux meilleures pratiques de Microsoft pour le déploiement initial et la gestion des mises à jour.
  - Activation de l’utilisation du Readiness Toolkit pour Office, qui permet d’identifier des problèmes de compatibilité potentiels avec vos macros Microsoft VBA et autres compléments que vous utilisez avec Office.
  
## <a name="your-responsibilities"></a>Vos responsabilités

Vous avez les responsabilités suivantes lors de l’intégration. Celles-ci s’ajoutent aux responsabilités définies dans [processus et attentes](process-and-expectations.md). 
  
- Nommer et gérer les ressources selon le plan de projet.  
- Prendre des mesures à temps pour atténuer les risques et résoudre les problèmes soulevés par le client, les responsables de projet partenaires et le responsable FastTrack.   
- Passer en revue les rapports d’état et agir en conséquence.   
- Nommer un commanditaire opérationnel ou un responsable pouvant prendre des décisions afin de diriger le comité de pilotage.  
- Nommer un commanditaire opérationnel pour collaborer avec le commanditaire exécutif Microsoft.  
- Établir une réunion mensuelle pour le comité de pilotage.

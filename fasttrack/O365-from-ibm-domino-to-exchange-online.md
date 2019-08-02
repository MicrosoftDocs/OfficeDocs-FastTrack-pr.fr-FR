---
title: Annexe A  Migration d'IBM Domino vers Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: "De nombreux paramètres entrent en jeu dans la migration d'IBM Domino vers Exchange Online, notamment lors des phases suivantes :"
ms.openlocfilehash: 83235a7765aa424baf92d9081fec86b6f688c365
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053977"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Annexe A : Migration d’IBM Domino vers Exchange Online

De nombreux paramètres entrent en jeu dans la migration d'IBM Domino vers Exchange Online, notamment lors des phases suivantes : 
- [Phase de lancement](#initiate-phase)   
- [Phase d'évaluation](#assess-phase)
- [Phase de correction](#remediate-phase)  
- [Phase d'activation](#enable-phase)  
- [Phase de migration](#migrate-phase)
    
## <a name="identities"></a>Identités

Vous êtes responsable de la création et de la gestion des identités (cloud uniquement, synchronisées ou fédérées avec les instances Active Directory locales). Vous devez procéder au mappage des identités (si ce n'est pas déjà fait) entre Domino et l'instance locale d'Active Directory ou d'Azure Active Directory au début du processus d'intégration.
  
## <a name="coexistence"></a>Coexistence

Les avantages du Centre FastTrack pour Office 365 fournissent des flux de messagerie bidirectionnelle entre l’environnement Domino local et Exchange Online pour tous les clients.
  
## <a name="migration"></a>Migration

Le processus du Service FastTrack standard pour la migration de Domino à Exchange Online implique la préparation des données Domino dans Azure avant la migration vers les boîtes aux lettres Exchange Online. Les migrations FastTrack requièrent l'exécution de certaines opérations à différentes étapes de l'intégration par le personnel du Service FastTrack et vous. Nous abordons ces opérations dans les sections suivantes.
  
> [!NOTE]
> Les données migrées par le biais des services FastTrack peuvent être transférées, stockées et traitées aux États-Unis ou dans n’importe quelle région du monde où Microsoft est implanté. Les services FastTrack ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières. 
  
## <a name="initiate-phase"></a>Phase de lancement

 **Actions principales**
  
- Définir Domino en tant que plateforme de messagerie source.   
- Déterminer si le Service FastTrack effectue la migration.
    
 **Responsabilités du client**
  
- Fournir des informations de base sur la plateforme de messagerie source, puis confirmer l’objectif de migration auprès du centre FastTrack. 
- Participer à une présentation détaillée des processus du service FastTrack.  
- Signer l’accord de Services FastTrack.
    
## <a name="assess-phase"></a>Phase d’évaluation

 **Actions principales**
  
- Le Service FastTrack organise un atelier de migration avec le client. 
- Vous vous acquittez des formalités nécessaires à la migration, comme remplir le questionnaire de migration et approvisionner les stations de travail d’administration.    
- Une évaluation de la migration pour Domino est effectuée dans votre environnement local.
    
 **Responsabilités du client**
  
- Approvisionner les stations de travail d’administration que le centre FastTrack utilise pour administrer les tâches de migration et d’intégration, comme les tâches d’évaluation, de création de réplicas, d’audit, de définition du transfert pendant la migration, etc.
    > [!NOTE]
    > Les tâches d'évaluation sont essentielles pour la planification et l'exécution d'une migration à haute vitesse. Elles sont menées à bien par un architecte de migration qui nécessite un accès spécifique à l'environnement Domino. Les stations de travail d'administration doivent comprendre un client Notes configuré pour accéder à tous les serveurs de messagerie Domino sources et au serveur réplica intermédiaire Domino de Azure. 
- Fournir à l'équipe de migration un accès à distance aux stations de travail d'administration, des comptes, ainsi que des autorisations pour lui permettre d'effectuer des tâches d'évaluation et de migration. Cela comprend le provisionnement de plusieurs comptes dotés des autorisations d'administration nécessaires à la migration, à la fois en local et dans Exchange Online.    
- Ouvrir les ports de pare-feu. Les ports sortants doivent être ouverts entre les serveurs de messagerie Domino sources et le serveur intermédiaire Azure. D'autres ports de communication doivent également être ouverts (par exemple pour les stations de travail d'administration, les serveurs Domino sources et les serveurs Exchange locaux (le cas échéant)). 
- Activer la certification croisée entre l'environnement Domino source et le serveur intermédiaire Domino de Azure pour faciliter la réplication. Les tâches de certification croisée sont coordonnées entre l'administrateur Domino du client et le Service FastTrack.  
- Remplir le questionnaire de migration, qui collecte les informations requises pour configurer l’environnement de migration dans Azure (comme les outils, les scripts et les serveurs de migration).   
- Vous assurer que le protocole MAPI (Messaging Application Program Interface) est activé sur les boîtes aux lettres cibles dans Office 365.  
> [!NOTE]
> Certains plans Office 365 ne prennent pas en charge le protocole MAPI. Pour migrer des données, les boîtes aux lettres provenant de ces plans doivent être converties en un plan prenant en charge le protocole MAPI avant l'événement de migration. Après la migration, ces plans peuvent être rétablis. 
  
## <a name="remediate-phase"></a>Phase de correction

 **Actions principales**
  
- Le Service FastTrack examine le rapport d'évaluation de migration et effectue des tests avec les détails que vous fournissez dans le questionnaire.   
- Il vous revient de prendre les mesures de correction suggérées par le centre FastTrack.
    
 **Responsabilités du client**
  
- Mettre à jour l’environnement Domino en suivant les directives du centre FastTrack (par exemple, définir les autorisations requises qui apparaissent comme manquantes dans les fichiers de messagerie).  
- Vérifier que les boîtes aux lettres Domino respectent la taille maximale autorisée lors de la migration.
    > [!NOTE]
    >  Bien que FastTrack ne migre les boîtes aux lettres que jusqu’à 85 % de la taille cible totale admise, la migration de boîtes aux lettres de plus de 2 Go comporte des risques supplémentaires, comme les suivants :    <br/> Migration plus longue.    <br/> Mobilisation de ressources qui seraient sinon utilisées pour la migration des autres boîtes aux lettres.    <br/> Augmentation considérable du taux d’erreur. 
- Préparation des bases de données de messagerie et des listes de contrôle d'accès associées pour la migration. Vous devez prendre certaines mesures correctives pour pouvoir migrer des bases de données de messagerie et les autorisations associées vers une boîte aux lettres partagée dans Exchange Online. Voici quelques exemples de ces mesures : 
  - Supprimer des entrées de base de données de messagerie existantes du répertoire Domino et créer des enregistrements de personnes.
  - Créer des groupes de sécurité universels à extension messagerie sur les instances Active Directory locales qui sont synchronisées avec Office 365 Azure Active Directory et utilisées pour configurer des autorisations sur la boîte aux lettres partagée dans Exchange Online. Cette action transfère les autorisations définies sur la base de données de messagerie vers la boîte aux lettres partagée dans Exchange Online.
    
> [!NOTE]
> Vous pouvez entamer les opérations de préparation de l’utilisateur final et de formation au nouveau client/système de messagerie à ce stade. 
  
## <a name="enable-phase"></a>Phase d’activation

 **Actions principales**
  
- Le service FastTrack : 
    - Configure l’environnement de migration dans Azure.  
    - Configure les outils de migration sur les stations de travail d’administration locales. 
    - Configure l’outil d’importation automatique et vous montre comment l’utiliser.  
    - Effectue la validation de tous les composants de migration et effectue des migrations de test.
    
 **Responsabilités du client**
  
- Vos équipes responsables de la planification de la migration des boîtes aux lettres doivent savoir utiliser l'outil d'importation automatique. Cet outil vous permet d'importer le plan de migration dans la base de données de planification, qui est utilisée par le Service FastTrack pour exécuter certaines tâches préalables à la migration. 
- Effectuer des tâches préalables à la migration, telles que l’importation des planifications utilisateur, l’analyse des rapports d’audit, la correction des problèmes et la réimportation des comptes d’utilisateur présentant des problèmes.
    
Les activités précédant la migration sont coordonnées entre vous et le Centre FastTrack. La réplication vers Azure commence après l’importation de la planification de migration utilisateur. 
    
> [!NOTE]
> Les délais de réplication dépendent du volume de données. Le Service FastTrack effectue ensuite un audit pour déterminer si votre environnement est prêt pour la migration. Les résultats de l'audit vous sont fournis afin que vous puissiez prendre les mesures correctives généralement nécessaires. Toutes ces activités sont appelées « T-moins », car elles doivent commencer avant la migration planifiée par les utilisateurs. 
  
## <a name="migrate-phase"></a>Phase de migration

 **Actions principales**
  
- Le service FastTrack :
    - Effectue des migrations pilote et de rapidité.  
    - Exécute des événements de migration et des activités T-moins.
    - Fournit une assistance après la migration.
    
 **Responsabilités du client**
  
- Déterminer et importer les plans de migration 21 jours avant la migration.
    > [!NOTE]
    > Cette tâche est essentielle, car les activités préalables à la migration impliquent des tâches de correction et de nouvelles tentatives de création de réplicas à différents moments précédant le jour de la migration réelle (T-0). Pendant la migration de certaines boîtes aux lettres, les activités T-moins sont effectuées sur les autres. Aussi, une planification et une coordination optimales sont indispensables. 
- Corriger les problèmes repérés au cours des activités T-moins.
- Corriger tout problème de serveur Domino ayant un impact sur les activités de migration. 
- Informer l’utilisateur final de la date de la migration à venir.
- Mener des activités de formation au nouveau client/système de messagerie et de préparation de l’utilisateur final.   
- Repérer et signaler les problèmes survenus à l'issue de la migration. Le Service FastTrack offre une assistance post-migration pendant les cinq jours suivant la migration, après quoi la résolution des problèmes passe sous votre responsabilité. Vous pouvez soumettre des tickets post-migration pour des problèmes comme l'absence de certains messages électroniques, éléments de calendrier et contacts, ou en cas de doublons dans la boîte aux lettres.
    
Le Service FastTrack ne prend pas en charge les tâches de déploiement, de facturation de licences ou d'assistance associées à la préparation d'annuaires (y compris la synchronisation d'annuaires de Domino vers Active Directory), aux modules complémentaires des logiciels de coexistence pour l'interopérabilité des applications Notes, à la migration en libre-service ou à la migration des archives.
  

  


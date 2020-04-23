---
title: Migration des données
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Les spécialistes FastTrack fournissent des conseils sur la procédure de migration des données vers Office 365. Ceci est disponible pour tous les clients éligibles disposant des services Office 365 pour Exchange Online, OneDrive Entreprise et SharePoint Online.
ms.openlocfilehash: 00fca4f9baabd1c68fbeb7024bec10791d050f67
ms.sourcegitcommit: 1aa423e2a720d57d2a37fba930fb4d4b0e8f93c9
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43665882"
---
# <a name="data-migration"></a>Migration des données

Les spécialistes FastTrack fournissent des conseils sur la procédure de migration des données vers Office 365. Nous vous aidons à l'aide d'un ensemble d'outils et de documents, et en effectuant des tâches de configuration dès que cela est nécessaire et possible. Ceci est disponible pour tous les clients éligibles disposant des services Office 365 pour Exchange Online, OneDrive Entreprise et SharePoint Online.
  
Les services de migration de données décrits dans le tableau suivant sont disponibles pour les locataires Office 365 disposant d'au moins 500 licences.\* Par exemple, vos environnements sources contiennent peut-être des données que vous souhaitez faire migrer vers Office 365. Cet avantage Service FastTrack inclut une aide à l'intégration à votre environnement source en vue de faciliter la migration de contenu.
  
\*Si vous avez acheté ou renouvelé une offre commerciale avant le 01/09/2017, 150 licences est la condition minimale requise en matière de licences pendant toute la durée de votre période d’abonnement actuelle pour recevoir l’avantage de migration. Pour les offres d’éducation, seules les licences enseignants et membres du personnel payantes sont éligibles pour les services de migration. 
  
> [!NOTE]
> Les données migrées par le biais des services FastTrack peuvent être transférées, stockées et traitées dans n'importe quelle région du monde où Microsoft est implanté (sauf disposition contraire prévue pour votre engagement FastTrack). Les services FastTrack ne sont pas conçus pour des données soumises à des exigences légales ou réglementaires particulières, ni destinés à celles-ci. 
  
> [!NOTE]
> Des problèmes imprévus (y compris mais sans s’y limiter, des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certains éléments. 
  
> [!NOTE]
> L’assistance à la migration est disponible en chinois traditionnel, chinois simplifié (les ressources parlent le mandarin uniquement), anglais, français, allemand, italien, japonais, portugais (Brésil) et espagnol. 
  
> [!NOTE]
> Si l’intégration est requise, votre environnement source doit être à un niveau minimal pour cette application. 
  
> [!NOTE]
> Nouveauté de mars 2020, Microsoft met à disposition des licences d’évaluation [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) et [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) pour une durée de six mois afin de faciliter le travail et l'apprentissage à distance dans le cadre de la réponse des clients à l'épidémie de COVID-19. À titre d’exception, FastTrack permet d’assurer la disponibilité des services de migration de données pour les clients disposant d’au moins 500 licences en version d’évaluation et pour [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) pour les étudiants de mars 2020 à août 2020. Microsoft se réserve le droit d’annuler, de modifier ou de suspendre cette offre à tout moment, sans préavis.

Le tableau suivant décrit la configuration requise pour la migration dans votre environnement source existant.
  

|**Activité**|**Attente concernant l'environnement source**|
|:-----|:-----|
|**Migration d’Exchange Online**  <br/> | Microsoft migre tous les environnements source indiqués ci-dessous, l'un après l'autre. Nous pouvons migrer le système de messagerie intégré à l'aide du Centre FastTrack ou s'il satisfait aux contrôles du Centre FastTrack. Cela inclut les éléments suivants :  <br/>  Une seule ou plusieurs forêt(s) Active Directory avec une seule ou plusieurs organisation(s) Exchange, si un déploiement hybride basé sur Exchange 2010 ou version ultérieure est implémenté dans chaque organisation et que les systèmes de messagerie Exchange datent au moins de 2003.  <br/> Environnement IBM Domino 7.0.3 et versions ultérieures unique ([Annexe A : Migration d'IBM Domino vers Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).  <br/>  Environnement de messagerie IMAP unique.  <br/>  Environnement G Suite (Gmail, Contacts et Calendrier uniquement)  <br/> Un seul environnement Novell GroupWise. <br/> **Remarque** *L’intégration d’Exchange Online doit être terminée avant la migration.* <br/> <br/> **Remarque** *FastTrack effectue uniquement une migration vers des boîtes aux lettres Office 365 actives.* <br/> <br/> **Remarque** *Pour les dépendances Exchange locales, reportez-vous à la rubrique [Configuration requise pour un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Remarque** *Lors de la migration de plusieurs environnements de messagerie source (par exemple, plusieurs organisations Exchange ou plusieurs domaines Domino), les migrations sont effectuées les unes après les autres.*| 
|**Migration de SharePoint Online**  <br/> | Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).  <br/>  Box (Starter, Business, Enterprise).  <br/> |
|**Migration de OneDrive Entreprise**  <br/> | Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).  <br/>  Environnement G Suite unique (Google Drive uniquement).  <br/>  Box (Starter, Business, Enterprise). <br/> <br/> **Remarque** *FastTrack effectue uniquement une migration vers des lecteurs Office 365 actifs.*|
   
## <a name="migration-to-exchange-online"></a>Migration vers Exchange Online
’’
### <a name="enable-to-migrate"></a>Activation de la migration
  
Si vous utilisez Microsoft pour migrer votre messagerie, nous vous fournissons des instructions pour activer Exchange Online et l'environnement source pour la migration. En fonction de l'environnement source, plusieurs étapes d'activation peuvent être nécessaires. Pour vous aider, nous mettons à votre disposition un ensemble d’outils et de documents, et effectuons des tâches de configuration dès que cela est nécessaire et possible. Selon les paramètres applicables, nous migrons ensuite les boîtes aux lettres, gérons les tâches et fournissons des rapports d’état.
Microsoft peut nécessiter des autorisations et des droits d’accès relatifs à votre système de messagerie afin d’effectuer des activités de migration.
  
### <a name="migration-policy-and-steps"></a>Stratégie et étapes de la migration
  
> [!NOTE]
> Ces créneaux horaires de migration sont également appelés « lots de migration ».

#### <a name="commercial-and-uk-government"></a>Commercial et gouvernement britannique

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les sept (7) jours ouvrés de la semaine (24x7), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration.

#### <a name="us-governmentdod"></a>Gouvernement américain/DOD

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les cinq (5) jours ouvrés de la semaine (24x5), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration. Il y a cinq jours de migration par semaine du lundi 2 h 00 UTC au vendredi minuit UTC. Cela signifie que la dernière migration planifiée a lieu le vendredi à 20 h 00 UTC.
    
 ### <a name="end-state"></a>État final
  
Après migration d’un lot, l’état final est le suivant :
- Les données provenant de boîtes aux lettres sources éligibles correctement planifiées dans l’environnement source sont migrées vers Office 365. 
- Un rapport sur la migration du lot est fourni par Microsoft.
    
Voici l’état final prévu une fois toutes les migrations terminées :
- Les données issues de boîtes aux lettres sources éligibles sont migrées vers Office 365 de la façon indiquée dans le tableau ci-dessous.
- Le type de données à migrer dépend de l’environnement source, comme décrit dans le tableau ci-dessous.
    
> [!NOTE]
> À la fin de la phase d'activation, tous les environnements source doivent normalement être dotés des Service Packs (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l'environnement source. Les services de migration de données sont soumis à des facteurs externes hors du contrôle de Microsoft, tels que les modifications apportées aux interfaces de programmation d'applications (API) de tiers, lesquelles peuvent entraîner des modifications, des retards ou la suspension de ces services. Pendant la durée des services FastTrack, les données que vous mettez à disposition de Microsoft sont accessibles et stockées dans tous les emplacements et toutes les régions où Microsoft et ses fournisseurs sont implantés. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Environnement source**|**Type de migration**|**Éléments migrés à partir de la boîte aux lettres source**|**Éléments qui ne sont pas migrés**|
|**Exchange 2003 et versions ultérieures**|Basculement| Messages électroniques <br/> Règles de boîte aux lettres <br/> Délégués <br/> Contacts de boîte aux lettres <br/> Calendrier <br/> Tâches <br/> E-mails gérés par des droits <br/> E-mails chiffrés| Dossiers publics <br/> Contacts personnels <br/> Utilisateurs à extension messagerie <br/> Utilisateurs bloqués ou inactifs <br/> Signatures <br/> Conteneur de dépôt de boîte aux lettres <br/>  Tout message électronique dépassant la limite de taille de message <br/> Données d’archive <br/> Éléments endommagés <br/>  Boîtes aux lettres inactives |
|**Exchange 2003 et Exchange 2007**|Intermédiaire| Messages électroniques <br/> Règles de boîte aux lettres <br/> Délégués <br/> Contacts de boîte aux lettres <br/> Calendrier <br/> Tâches <br/> E-mails gérés par des droits <br/> E-mails chiffrés| Dossiers publics <br/> Contacts personnels <br/> Utilisateurs à extension messagerie <br/> Utilisateurs bloqués ou inactifs <br/> Signatures <br/> Conteneur de dépôt de boîte aux lettres <br/> Tout message électronique dépassant la limite de taille de message <br/> Données d’archive <br/> Éléments endommagés <br/> Boîtes aux lettres inactives |
|**Exchange 2010, Exchange 2013, Exchange 2016** <br/><br/> **Remarque** *Pour les dépendances Exchange locales, reportez-vous à la rubrique [Configuration requise pour un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migration avec déploiement hybride| Messages électroniques <br/> Règles de boîte aux lettres <br/> Délégués <br/> Contacts de boîte aux lettres <br/> Calendrier <br/> Tâches <br/> Signatures <br/> Archives personnelles migrées avec la boîte aux lettres des utilisateurs <br/> Éléments récupérables <br/> E-mails gérés par des droits <br/> E-mails chiffrés| Dossiers publics <br/> Tout message électronique dépassant la limite de taille de message <br/> Archivage de journalisation ou toute solution d’archivage tierce <br/> Utilisateurs bloqués ou inactifs <br/> Données d’archive à partir de fichiers PST (Personal Storage Table) <br/> Éléments endommagés <br/> Boîtes aux lettres inactives |
|**Environnement G Suite (Gmail, contacts et calendrier uniquement)** <br/> <br/> **Remarque** *Les API Google et le Kit de développement logiciel (SDK) d’administration Google doivent être activés dans votre environnement G Suite pour bénéficier de fonctionnalités étendues.* <br/>          |À basculement ou intermédiaire| Messages électroniques <br/> Contacts de la boîte aux lettres\*  <br/> Calendrier <br/> Étiquettes <br/> \*Au maximum, trois adresses e-mail par contact sont déplacées| Règles <br/> Délégués <br/> Signatures <br/> Tâches <br/> Tout e-mail ou pièce jointe dépassant la limite de taille de message <br/> Utilisateurs bloqués ou inactifs <br/> Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault) <br/> Droits gérés ou messages électroniques chiffrés <br/> Éléments endommagés <br/> Google Hangouts\*\* <br/> Groupes Google <br/> Boîtes aux lettres de ressources <br/> Boîtes aux lettres inactives <br/> Paramètres des congés et de la réponse automatique <br/> Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement <br/>\*\*Les conversations Hangout enregistrées sous forme d’étiquette sont déplacées |
|**IBM Domino 7.0.3 et versions ultérieures** ([Annexe A : Migration d’IBM Domino vers Exchange Online](O365-from-ibm-domino-to-exchange-online.md))|Intermédiaire| Messages électroniques - 90 derniers jours <br/> Calendrier - 90 derniers jours et éléments futurs <br/> Contacts de boîte aux lettres - tous <br/> Tâches - Tout <br/> Salles et ressources - En fonction de leur implémentation avec le modèle standard <br/> Les fichiers de messagerie, y compris ceux partagés, doivent utiliser le modèle de messagerie standard | Signatures <br/> Règles de boîte aux lettres <br/> Délégués <br/> Éléments chiffrés <br/> Liens de documents <br/> Papier à lettres utilisateur <br/> Tout message électronique dépassant la limite de taille de message <br/> Utilisateurs bloqués ou inactifs <br/> Données d’archive <br/> Éléments endommagés <br/> Coexistence de calendriers <br/> Boîtes aux lettres inactives |
|**Novell GroupWise** |Migration à l’aide des outils natifs IMAP4| Messages électroniques | Règles <br/> Conversion de proxys/délégués/liste de contrôle d’accès (ACL) <br/> Signatures <br/> Dossiers de recherche <br/> Utilisateurs bloqués ou inactifs <br/> Données d’archive <br/> Éléments chiffrés ou gérés par des droits <br/> Éléments endommagés <br/> Coexistence de calendriers <br/> Utilisateurs à extension messagerie <br/> Contacts de boîte aux lettres <br/> Groupes personnels <br/> Calendrier <br/> Tâches <br/> Tout message électronique dépassant la limite de taille de message |
|**Source IMAP4** |Migration à l’aide des outils natifs IMAP4| Messages électroniques | Règles <br/> Délégués <br/> Listes de distribution <br/> Contacts externes <br/> Utilisateurs à extension messagerie <br/> Utilisateurs bloqués ou inactifs <br/> Contacts de boîte aux lettres <br/> Calendrier <br/> Signatures <br/> Tâches <br/> Tout message électronique dépassant la limite de taille de message <br/> Données d’archive <br/> Message électronique chiffré <br/> Éléments endommagés <br/> Boîtes aux lettres inactives |
   
> [!NOTE]
> Si Active Directory en local contient des listes de distribution (objets MailEnabledGroup) et des contacts externes (objets MailEnabledContact), ils peuvent être synchronisés à l'aide d'Azure AD Connect. Toutefois, ils ne font pas partie de la migration des données de boîte aux lettres. Pour plus d'informations, reportez-vous à l'exemple d' **intégration des identités** dans [Core](O365-onboarding-and-migration.md#core). 
  
Les spécialistes de FastTrack effectuent les opérations suivantes pendant les migrations :
- Fourniture d’un modèle standard pour la planification des migrations de boîtes aux lettres.
- Fourniture d'informations sur les autorisations requises pour les spécialistes de FastTrack. 
- Collecte d’une planification de migration de boîtes aux lettres prédéterminée dans un format prédéfini.
- Tentative de réalisation de migration d’une seule boîte aux lettres jusqu’à deux fois dans un lot de migration avant de signaler que la migration de cette boîte aux lettres a échoué.
- Pour les environnements source Exchange et IMAP4, migration du contenu des boîtes aux lettres jusqu'à 85 % de la limite de stockage de boîte aux lettres (par exemple, si la limite de stockage de boîte aux lettres est de 85 Go, Microsoft migre au maximum 50 % de la limite de stockage de 50 Go). 
- Activation de la coexistence de routage de courrier SMTP entre l’environnement de messagerie source et Office 365 Exchange Online, sauf si la migration à basculement est utilisée.
- Fourniture de rapports post-migration.
- Fourniture d’assistance post-migration pour les problèmes critiques. Les problèmes suivants sont considérés comme critiques :
  - Perte de données pendant la migration.
  - Indisponibilité de l’environnement source pendant la migration.
  - Activités de migration générant des problèmes dans l’environnement source.
    
Lors des migrations, vous devez effectuer les opérations suivantes :
- Intégration Exchange Online complète ou réalisation satisfaisante des contrôles requis à l'aide du Service FastTrack.
- Gestion de toutes les communications avec les utilisateurs finals.  
- Installation du niveau approprié de logiciel client conformément aux instructions Office 365. Pour plus d’informations, consultez [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Validation de la coexistence de routage de courrier SMTP entre l’environnement de messagerie source et Office 365 Exchange Online le cas échéant.
- Fournissez un planning dans une méthode définie et une liste de boîtes aux lettres spécifiques à migrer pour chaque événement de migration.
- Suppression des boîtes aux lettres en trop, jusqu’à 24 heures avant le lot de migration. 
- Planification d’un nombre moyen cible de boîtes aux lettres dans une période de 24 heures, comme indiqué dans le tableau ci-dessous.
    
|||
|:-----|:-----|
|**Nombre de boîtes aux lettres éligibles pour la migration** <br/> |**Nombre moyen de boîtes aux lettres dans une période de 24 heures** <br/> |
|150-1000  <br/> |25 % du total  <br/> |
|1001-5000  <br/> |20 % du total  <br/> |
|5001-10000  <br/> |15 % du total  <br/> |
|\>10 000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Ces valeurs sont déterminées sur la base des meilleures pratiques. Toutefois, le nombre de boîtes aux lettres migrées par jour varie en fonction des contraintes relatives à l’environnement, la préparation et l’entreprise. Microsoft ne peut pas garantir la vitesse de migration des boîtes aux lettres. 
  
- Planification d’un minimum de 35 boîtes aux lettres dans un lot de migration. 
- Correction des erreurs avant la migration (si nécessaire).  
- Fourniture d'autorisations et de droits d'accès relatifs à l'environnement source aux spécialistes de FastTrack pour la réalisation d'activités de migration. 
- Fourniture de comptes administratifs sous licence dans Office 365 pour effectuer des activités de migration (le cas échéant). 
- Prise en charge des problèmes de migration côté client et exécution d’opérations après les migrations le cas échéant. 
- Migration de données côté client si vous le souhaitez. Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.   
- Réduction de la taille de boîte aux lettres en dessous de 85 % de la limite de boîte aux lettres Office 365 cible (le cas échéant).   
- Gestion des actions indiquées dans le rapport de post-migration, y compris les boîtes aux lettres qui n’ont pas été déplacées.  
- Correction des erreurs post-migration et replanification des boîtes aux lettres (si nécessaire).   
- Mise en œuvre d’une assistance post-migration pour les problèmes critiques. Les problèmes suivants sont considérés comme critiques :
  - Perte de données pendant la migration.
  - Indisponibilité de l’environnement source pendant la migration.
  - Activités de migration générant des problèmes dans l’environnement source.
    
Vous devez suivre le processus de migration standard et collaborer de façon appropriée avec Microsoft, notamment en fournissant des droits d'accès à l'environnement source et à l'environnement Office 365, en planifiant la migration, en corrigeant toute source d'erreur de migration, etc. Vous devez également maintenir une communication appropriée avec les utilisateurs finaux concernant la transmission d'informations et la planification des migrations de boîtes aux lettres, ainsi que gérer les problèmes de migration qu'ils rencontrent.
  
> [!NOTE]
> Les migrations utilisent uniquement des comptes qui respectent les exigences de sécurité définies lors de l’intégration. Si vous n’utilisez pas de tels comptes, vous pouvez rencontrer des retards de migration. 
  
## <a name="migration-to-sharepoint-online"></a>Migrer vers SharePoint Online

### <a name="enable-to-migrate"></a>Activation de la migration
  
Si vous utilisez Microsoft pour migrer vos données, nous vous fournissons des instructions afin d'activer SharePoint Online et l'environnement source pour la migration. En fonction de la source, plusieurs étapes d'activation peuvent être nécessaires. Pour vous aider, nous mettons à votre disposition un ensemble d'outils et de documents, et effectuons des tâches de configuration dès que cela est nécessaire et possible.
  
Vous devez fournir un accès et des autorisations appropriés à Microsoft pour certaines activités.
  
### <a name="migration-policy-and-steps"></a>Stratégie et étapes de la migration
  
> [!NOTE]
> Ces créneaux horaires de migration sont également appelés « lots de migration ».

#### <a name="commercial-and-uk-government"></a>Commercial et gouvernement britannique

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les sept (7) jours ouvrés de la semaine (24x7), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration.

#### <a name="us-governmentdod"></a>Gouvernement américain/DOD

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les cinq (5) jours ouvrés de la semaine (24x5), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration. Il y a cinq jours de migration par semaine du lundi 2 h 00 UTC au vendredi minuit UTC. Cela signifie que la dernière migration planifiée a lieu le vendredi à 20 h 00 UTC.

- Toutes les migrations sont sujettes à des quotas SharePoint Online décrits dans l’article [SharePoint Online et OneDrive Entreprise : limites et frontières logicielles](https://go.microsoft.com/fwlink/?LinkID=616612).   
- Le volume total des données migrées est lié à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).
    
 ### <a name="end-state"></a>État final
  
Après migration d’un lot, l’état final est le suivant : 
- Les données provenant de sources éligibles correctement planifiées dans l'environnement source sont migrées vers SharePoint Online.   
- Un rapport sur la migration du lot est fourni par Microsoft.
    
Voici l’état final prévu une fois toutes les migrations terminées : 
- Les données issues de la source éligible sont migrées vers Office 365 de la façon indiquée dans le tableau ci-dessous.  
- Le type de données à migrer dépend de l’environnement source, comme décrit dans le tableau suivant :
    
|||||
|:-----|:-----|:-----|:-----|
|**Environnement source** <br/> |**Type de migration** <br/> |**Éléments migrés** <br/> |**Éléments qui ne sont pas migrés** <br/> |
|**N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures**  <br/> |Un ou plusieurs passages  <br/> | Documents  <br/>  Structure des fichiers et des dossiers  <br/>  Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*  <br/>  Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*  <br/>  Fichiers inférieurs à 15 Go  <br/>  Métadonnées de dossier et document de base :  <br/>  Date de création  <br/>  Date de modification  <br/>  Créé par  <br/>  Auteur de la dernière modification  <br/><br/> \**Configuration de la synchronisation d’annuaires requise. Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées. Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées. Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.* <br/> | Historique d’appartenance et versions antérieures  <br/>  Conversion d’URL incorporées dans le contenu  <br/>  Versions antérieures  <br/>  Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)  <br/>  Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :  <br/>  Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)  <br/>  Configuration de l’audit NTFS  <br/>  Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF)  <br/>  Documents inaccessibles ou endommagés  <br/>  Partages masqués  <br/>  Partage (par exemple, autorisations accordées au niveau de partage)  <br/>  Fichiers ou dossiers dépassant les [restrictions et limitations SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) actuelles <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Un ou plusieurs passages  <br/> | Documents  <br/>  Structure des fichiers et des dossiers  <br/>  Autorisations liées aux dossiers au niveau de l’utilisateur  <br/>  Autorisations liées aux dossiers au niveau du groupe  <br/>  Fichiers inférieurs à 15 Go  <br/>  Métadonnées de dossier et document de base :  <br/>  Date de création  <br/>  Date de modification  <br/>  Créé par  <br/>  Auteur de la dernière modification  <br/>  Contenu partagé appartenant au compte Box en cours de migration (si explicitement partagé avec des utilisateurs ou groupes)\*  <br/><br/> \**Utilisez les rapports Box pour identifier les comptes externes. Demandez aux utilisateurs de partager à nouveau leur contenu après la migration.* <br/> | Historique d’appartenance, versions précédentes et commentaires <br/>  Autorisations liées aux fichiers au niveau de l’utilisateur  <br/>  Autorisations liées aux fichiers au niveau du groupe  <br/>  Descriptions des fichiers et des dossiers  <br/>  Métadonnées avancées et balises Box  <br/>  Attributs de verrouillage de fichier  <br/>  Conversion d’URL incorporées dans le contenu  <br/>  Éléments jetés  <br/>  Documents inaccessibles ou endommagés  <br/>  Utilisateurs bloqués ou inactifs  <br/>  Notes Box (inutilisables, car migrées sans conversion)  <br/>  Applications, signets, favoris et flux de travail Box  <br/>  Contenu n’appartenant pas au compte Box migré (dossiers partagés)  <br/>  Autorisations et métadonnées de base des utilisateurs externes\*  <br/>  Fichiers ou dossiers dépassant les [restrictions et limitations SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Les spécialistes de FastTrack effectuent les opérations suivantes pendant les migrations : 
- Organiser un atelier de procédure pas à pas de migration abordant le processus et l’approche pour le scénario de migration sélectionné.
- Fournir la configuration requise pour les outils de migration et d’évaluation selon le cas pour le scénario.   
- Fournir la configuration requise pour l’accès de l’équipe de migration à l’environnement source et cible pour l’évaluation et la migration. 
- Fournir des outils d’évaluation pour évaluer l’environnement source et cible, ou fournir des instructions sur l’utilisation des fonctions de la plateforme source native afin de créer des rapports d’évaluation.   
- Apporter son aide pour le déploiement et l’exécution d’outils d’évaluation et de migration (le cas échéant).   
- Configurer l’infrastructure de migration en vue de la migration de contenu (le cas échéant).    
- Effectuer une migration de test limitée pour valider l’infrastructure de migration et la configuration requise.   
- Provisionner des sites SharePoint Online cibles prêts à l'emploi dans le cadre de la migration.    
- Effectuer une migration pilote unique avant la migration de rapidité.   
- Fournir des instructions sur la planification de la migration pour le scénario sélectionné. 
- Organiser des vagues de migrations de rapidité du contenu conformément à l’échéancier de migration fourni par le client et validé par les ressources FastTrack.   
- Fournir des résultats de migration après chaque fenêtre de migration.   
- Participer au triage des problèmes de migration de rapidité et fournir des instructions sur les options de correction potentielles.   
- Fournir un rapport de migration finale pour chaque fenêtre de migration de rapidité.   
- Fournir une assistance post-migration pendant la phase de test d’acceptation utilisateur jusqu’à cinq jours après la fin de la migration.
    
Lors des migrations, vous devez effectuer les opérations suivantes : 
- Fournir des ressources de projet recommandées pour les activités d’évaluation et de migration. Ces méthodes sont les suivantes : 
  - Gestion de projet. 
  - Test d’acceptation utilisateur (UAT).  
  - Administrateurs responsables de plateformes de contenu sources et cibles.  
- Fournir la configuration requise pour les activités d’évaluation et de migration (le cas échéant).  
- Fournir les autorisations et les droits d'accès relatifs aux environnements source et cible aux spécialistes FastTrack afin qu'ils puissent réaliser les activités de migration (le cas échéant).
    > [!NOTE]
    > Les migrations utilisent uniquement des comptes qui respectent les exigences de sécurité définies lors de l’intégration. Si vous n’utilisez pas de tels comptes, vous pouvez rencontrer des retards de migration. 
- Fournir les conditions préalables et effectuer les activités nécessaires pour prendre en charge l’évaluation et la migration.   
- Installer les outils d’évaluation fournis par FastTrack et effectuer les activités de collecte de données d’évaluation (le cas échéant).   
- Installer localement le logiciel de migration fourni par FastTrack (le cas échéant).   
- Effectuer les activités de correction définies dans le rapport de correction fourni par FastTrack (le cas échéant).  
- Fournir un échéancier de migration à l’aide des modèles FastTrack et donner des conseils.   
- Effectuer des tests d’assurance qualité et d’acceptation utilisateur concernant la migration.   
- Effectuer des corrections de migration après la migration (le cas échéant).
- Planifier et implémenter des communications de gestion des modifications et aux utilisateurs finals (le cas échéant).   
- Administrez et configurez les modifications apportées au système source et les appareils requis pour la réalisation des activités d’évaluation et de migration.
- Fournir un plan de migration incluant une méthode définie et la liste des données utilisateur spécifiques à migrer pour chaque événement de migration au moins trois (3) jours à l’avance.
- Supprimer du plan de migration les données utilisateur jusqu’à 24 heures avant le créneau de migration. Ce doit être le lot de migration final.
> [!NOTE]
> Microsoft ne peut pas garantir la vitesse de migration des fichiers.
    
## <a name="migration-to-onedrive-for-business"></a>Migration vers OneDrive Entreprise

 ### <a name="enable-to-migrate"></a>Activation de la migration
  
Si vous utilisez Microsoft pour migrer vos données, nous vous fournissons des instructions pour activer OneDrive Entreprise et l'environnement source pour la migration. En fonction de la source, plusieurs étapes d'activation peuvent être nécessaires. Pour vous aider à réaliser certaines opérations, nous mettons à votre disposition un ensemble d'outils, de documents et d'instructions, et effectuons des tâches de configuration dès que cela est nécessaire et possible.
  
Il peut être nécessaire de fournir un accès et des autorisations appropriés à Microsoft pour certaines opérations. Si vous ne le faites pas, vous devez effectuer certaines tâches définies vous-même, en suivant les instructions de Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Stratégie et étapes de la migration
  
> [!NOTE]
> Ces créneaux horaires de migration sont également appelés « lots de migration ».

#### <a name="commercial-and-uk-government"></a>Commercial et gouvernement britannique

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les sept (7) jours ouvrés de la semaine (24x7), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration.

#### <a name="us-governmentdod"></a>Gouvernement américain/DOD

Les migrations sont effectuées de façon programmée et standardisée 24 heures sur 24, sur les cinq (5) jours ouvrés de la semaine (24x5), au cours de créneaux horaires de migration prédéfinis. Il y a trois lots de migration par jour de migration. Il y a cinq jours de migration par semaine du lundi 2 h 00 UTC au vendredi minuit UTC. Cela signifie que la dernière migration planifiée a lieu le vendredi à 20 h 00 UTC.
    
- Toutes les migrations exigent un accès et des autorisations appropriés pour l’environnement source.   
- Toutes les migrations sont sujettes à des quotas OneDrive Entreprise décrits dans l’article [SharePoint Online et OneDrive Entreprise : limites et frontières logicielles](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>État final
  
Après migration d’un lot, l’état final est le suivant :  
- Les données provenant de sources éligibles correctement planifiées de l’environnement source sont migrées vers OneDrive Entreprise.  
- Un rapport sur la migration du lot est fourni par Microsoft.
    
Voici l’état final prévu une fois toutes les migrations terminées :
- Les données issues de sources éligibles sont migrées vers Office 365 de la façon indiquée dans le tableau ci-dessous.  
- Le type de données à migrer dépend de l’environnement source, comme décrit dans le tableau ci-dessous.
    
|||||
|:-----|:-----|:-----|:-----|
|**Environnement source**|**Type de migration**|**Éléments migrés**|**Éléments qui ne sont pas migrés**|
|**Environnement G Suite unique (Google Drive uniquement)**  <br/> |Un ou plusieurs passages  <br/> | Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent)  <br/>  Structure des fichiers et des dossiers  <br/>  Autorisations liées aux dossiers au niveau de l’utilisateur  <br/>  Autorisations liées aux dossiers au niveau du groupe  <br/>  Fichiers inférieurs à 15 Go  <br/>  Métadonnées de dossier et document de base :  <br/>  Date de création  <br/>  Date de modification  <br/>  Créé par  <br/>  Auteur de la dernière modification  <br/>  Contenu partagé appartenant au compte Google Drive en cours de migration (si explicitement partagé avec des utilisateurs ou des groupes)  <br/> | Historique d’appartenance, versions précédentes et commentaires  <br/>  Descriptions des fichiers et des dossiers, couleurs des dossiers  <br/>  Conversion d’URL incorporées dans le contenu  <br/>  Autorisations liées aux fichiers au niveau de l’utilisateur  <br/>  Autorisations liées aux fichiers au niveau du groupe  <br/> Éléments jetés  <br/>  Documents inaccessibles ou endommagés  <br/>  Utilisateurs bloqués ou inactifs  <br/>  Contenu partagé externe à votre organisation  <br/>  Google Photos. Forms, Maps et autres applications connectées  <br/>  Google Drawings  <br/>  Fichiers ou dossiers dépassant les [restrictions et limitations SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures**  <br/> |Un ou plusieurs passages  <br/> | Documents  <br/>  Structure des fichiers et des dossiers  <br/>  Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur\*  <br/>  Autorisations liées aux fichiers et aux dossiers au niveau du groupe\*  <br/>  Fichiers inférieurs à 15 Go  <br/>  Métadonnées de dossier et document de base :  <br/>  Date de création  <br/>  Date de modification  <br/>  Créé par  <br/>  Auteur de la dernière modification  <br/> <br/>\**Configuration de la synchronisation d’annuaires requise. Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées. Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées. Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.* <br/> | Historique d’appartenance et versions antérieures  <br/>  Conversion d’URL incorporées dans le contenu  <br/>  Versions antérieures  <br/>  Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués)  <br/>  Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS :  <br/>  Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent)  <br/>  Configuration de l’audit NTFS  <br/>  Métadonnées de fichiers supplémentaires fournies par l’ICF  <br/>  Documents inaccessibles ou endommagés  <br/>  Partages masqués  <br/>  Partage (par exemple, autorisations accordées au niveau de partage)  <br/>  Fichiers ou dossiers dépassant les [restrictions et limitations SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) actuelles <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Un ou plusieurs passages  <br/> | Documents  <br/>  Structure des fichiers et des dossiers  <br/>  Autorisations liées aux dossiers au niveau de l’utilisateur  <br/>  Autorisations liées aux dossiers au niveau du groupe  <br/>  Fichiers inférieurs à 15 Go  <br/>  Métadonnées de dossier et document de base :  <br/>  Date de création  <br/>  Date de modification  <br/>  Créé par  <br/>  Auteur de la dernière modification  <br/>  Contenu partagé appartenant au compte Box en cours de migration (si explicitement partagé avec des utilisateurs ou groupes)\*  <br/><br/> \**Utilisez les rapports Box pour identifier les comptes externes. Demandez aux utilisateurs de partager à nouveau leur contenu après la migration.* <br/> | Historique d’appartenance, versions précédentes et commentaires  <br/>  Descriptions des fichiers et des dossiers  <br/>  Autorisations liées aux fichiers au niveau de l’utilisateur  <br/>  Autorisations liées aux fichiers au niveau du groupe  <br/>  Métadonnées avancées et balises Box  <br/>  Attributs de verrouillage de fichier  <br/>  Conversion d’URL incorporées dans le contenu  <br/>  Éléments jetés  <br/>  Documents inaccessibles ou endommagés  <br/>  Utilisateurs bloqués ou inactifs  <br/>  Notes Box (inutilisables, car migrées sans conversion)  <br/>  Applications, signets, favoris et flux de travail Box  <br/>  Contenu n’appartenant pas au compte Box migré (dossiers partagés)  <br/>  Autorisations et métadonnées de base des utilisateurs externes\*  <br/>  Fichiers ou dossiers dépassant les [restrictions et limitations SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Les spécialistes de FastTrack effectuent les opérations suivantes pendant les migrations :  
- Organiser un atelier de procédure pas à pas de migration abordant le processus et l’approche pour le scénario de migration sélectionné.   
- Fournir la configuration requise pour les outils de migration et d’évaluation selon le cas pour le scénario.  
- Fournir la configuration requise pour l’accès de l’équipe de migration à l’environnement source et cible pour l’évaluation et la migration.   
- Fournir des outils d’évaluation pour évaluer l’environnement source et cible, ou fournir des instructions sur l’utilisation des fonctions de la plateforme source native afin de créer des rapports d’évaluation.    
- Apporter son aide pour le déploiement et l’exécution d’outils d’évaluation et de migration (le cas échéant).   
- Configurer l’infrastructure de migration en vue de la migration de contenu (le cas échéant).    
- Effectuer une migration de test limitée pour valider l’infrastructure de migration et la configuration requise.    
- Provisionner des sites OneDrive Entreprise cibles prêts à l'emploi dans le cadre de la migration.    
- Effectuer une migration pilote unique avant la migration de rapidité.
- Fournir des instructions sur la planification de la migration pour le scénario sélectionné.   
- Organiser des vagues de migrations de rapidité du contenu conformément à l’échéancier de migration fourni par le client et validé par les ressources FastTrack.   
- Fournir des résultats de migration après chaque fenêtre de migration.   
- Participer au triage des problèmes de migration de rapidité et fournir des instructions sur les options de correction potentielles. 
- Fournir un rapport de migration finale pour chaque fenêtre de migration de rapidité.   
- Fournir une assistance post-migration pendant la phase de test d’acceptation utilisateur jusqu’à cinq jours après la fin de la migration.
   
Lors des migrations, vous devez effectuer les opérations suivantes :
- Fournir des ressources de projet recommandées pour les activités d’évaluation et de migration. Ces méthodes sont les suivantes :
  - Gestion de projet.
  - UAT.
  - Administrateurs responsables de plateformes de contenu sources et cibles.
- Fournir la configuration requise pour les activités d’évaluation et de migration (le cas échéant).   
- Fournir les autorisations et les droits d'accès relatifs aux environnements source et cible aux spécialistes FastTrack afin qu'ils puissent réaliser les activités de migration (le cas échéant).  
    > [!NOTE]
    > Les migrations utilisent uniquement des comptes qui respectent les exigences de sécurité définies lors de l’intégration. Si vous n’utilisez pas de tels comptes, vous pouvez rencontrer des retards de migration. 
- Installer les outils d’évaluation fournis par FastTrack et effectuer les activités de collecte de données d’évaluation (le cas échéant).
- Installer localement le logiciel de migration fourni par FastTrack (le cas échéant).  
- Effectuer les activités de correction définies dans le rapport de correction fourni par FastTrack (le cas échéant).   
- Fournir un échéancier de migration à l’aide des modèles FastTrack et donner des conseils. 
- Fournissez un planning dans une méthode définie et une liste de données utilisateur spécifiques à migrer pour chaque événement de migration.
- Supprimer des données utilisateur en trop, jusqu’à 24 heures avant le créneau de migration. Ce doit être le lot de migration final.
- Effectuer des tests d’assurance qualité et d’acceptation utilisateur concernant la migration.   
- Effectuer des corrections de migration après la migration (le cas échéant).  
- Planifier et implémenter des communications de gestion des modifications et aux utilisateurs finals (le cas échéant).  
- Administrez et configurez les modifications apportées au système source et les appareils requis pour la réalisation des activités d’évaluation et de migration.
    
> [!NOTE]
> Microsoft ne peut pas garantir la vitesse de migration des fichiers. 



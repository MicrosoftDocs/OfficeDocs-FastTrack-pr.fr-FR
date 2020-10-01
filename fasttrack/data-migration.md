---
title: Migration des données
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise). Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319946"
---
# <a name="data-migration"></a>Migration des données

FastTrack peut vous aider à migrer le courrier et les données de fichiers de vos environnements sources vers Office 365 (Exchange Online, SharePoint Online et OneDrive Entreprise).

Le type d’aide que nous fournissons dépend de votre nombre de licences Office 365 :

  - **Pour les clients Office 365 possédant entre 150 et 499 licences** : FastTrack fournit uniquement des recommandations sur la migration. Vous êtes responsable de l’exécution de la migration des données. Nous vous guiderons à l’aide d’une documentation qui vous aide à planifier et à utiliser des outils gratuits pour effectuer une migration en libre-service.
  - **Pour les clients Office 365 possédant 500 licences** : FastTrack fournit une aide à la migration ainsi que des services de migration des données. Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Office 365, et tirer parti de nos services de migration des données pour migrer vos données. Vous créez et planifiez vos événements de migration. Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut.

> [!NOTE]
> Si vous avez acheté ou renouvelé un plan commercial avant le 01/09/2017, il vous faut uniquement 150 licences pour bénéficier des services de migration des données. En ce qui concerne les plans pour l’éducation, seules les licences d’enseignants et de personnel payées sont éligibles aux services de migration.

### <a name="considerations"></a>Considérations

  - Vos environnements sources doivent répondre à des attentes spécifiques afin de migrer des données vers Office 365. Pour plus d’informations sur les attentes en matière d’environnement source pour Exchange, SharePoint et OneDrive Entreprise, voir [Produits et fonctionnalités](products-and-capabilities.md).
  - Nous avons besoin d’un accès et d’autorisations appropriés à vos environnements sources et à votre client Office 365 pour fournir des services de migration des données.
  - Nos services de migration des données ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières. Au cours de la migration de vos données, celles-ci peuvent être transférées, stockées et traitées partout où nous possédons des installations (sauf si votre projet de migration FastTrack le définit autrement).
  - Nous ne pouvons pas garantir la vitesse de migration du courrier et des fichiers.
  - Des problèmes imprévus (tels que des éléments illisibles ou endommagés dans l’environnement source) peuvent empêcher la migration de certaines de vos données.
  - Des facteurs externes hors de notre contrôle (tels que des modifications apportées aux interfaces de programmation d’application (API) tierces) peuvent entraîner des changements, des retards ou la suspension de nos services de migration des données.

### <a name="migration-service-availability"></a>Disponibilité des services de migration

  - **Pour les clients commerciaux et du gouvernement britannique :** nous fournissons les services de migration des données 24 h/24, 7 j/7.
  - **Pour les clients DOD/du gouvernement américain :** nous fournissons les services de migration des données 24 h/24, 5 jours ouvrés par semaine.

## <a name="migration-to-exchange-online"></a>Migration vers Exchange Online

Lorsque vous choisissez d’utiliser FastTrack pour migrer votre courrier vers Exchange Online, nous fournissons des conseils de migration ainsi que des services de migration des données. Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client Exchange Online, et tirer parti de nos services de migration des données pour migrer vos boîtes de réception. Vous créez et planifiez vos événements de migration. Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut. Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les messages de boîtes aux lettres sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers Exchange Online.

### <a name="considerations"></a>Considérations

  - Avant la migration, vous devez effectuer l’intégration principale de FastTrack pour Exchange Online.
      - Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables. Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).
  - FastTrack effectue uniquement les migrations vers des boîtes aux lettres Office 365 actives.
  - Vous devez respecter des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local. Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).
  - Chaque environnement source doit normalement être doté du Service Pack (SP) et des niveaux de correctif cumulatif/mise à jour cumulative les plus récents pour le produit concerné dans l’environnement source.
  - Les listes de distribution (objets *MailEnabledGroup*) et les contacts externes (objets *MailEnabledContact*) figurant dans votre annuaire Active Directory local ne sont pas inclus dans la migration des données de boîte aux lettres. Toutefois, vous pouvez les synchroniser à l’aide d’Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Environnements sources

Notre service de migration des données migre les données de ces environnements sources :

  - Une ou plusieurs forêts Active Directory avec une ou plusieurs organisations Exchange (chaque système de messagerie Exchange doit être à la version Exchange 2010 ou ultérieure).
  - Environnement de messagerie IMAP unique.
  - Environnement G Suite (Gmail, contacts et calendrier uniquement).

Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :

<table>
<thead>
<tr class="header">
<th><strong>Environnement source</strong></th>
<th><strong>Type de migration</strong></th>
<th><strong>Ce qui est migré</strong></th>
<th><strong>Ce qui n’est pas migré</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Remarque :</strong> pur les dépendances Exchange locales, reportez-vous à  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Configuration requise pour un déploiement hybride</span></a>.</td>
<td>Migration avec déploiement hybride</td>
<td><ul>
<li>Messages électroniques</li>
<li>Règles de boîte aux lettres</li>
<li>Délégués</li>
<li>Contacts de boîte aux lettres </li>
<li> Calendrier </li>
<li> Tâches </li>
<li> E-mails gérés par des droits </li>
<li> E-mails chiffrés </li>
<li> Signatures </li>
<li> Archives personnelles migrées avec la boîte aux lettres des utilisateurs </li>
<li> Éléments récupérables </li>
</ul></td>
<td><ul>
<li> Dossiers publics </li>
<li> Tout message électronique dépassant la limite de taille de message </li>
<li> Archivage de journalisation ou toute solution d’archivage tierce </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Données d’archive à partir de fichiers PST (Personal Storage Table) </li>
<li> Éléments endommagés </li>
<li> Boîtes aux lettres inactives </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Environnement G Suite (Gmail, contacts et calendrier uniquement)</strong><br />
<br />
<strong>Remarque :</strong> votre environnement G Suite doit respecter les conditions préalables décrites dans <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Effectuer une migration de G Suite</a>.</td>
<td>À basculement ou intermédiaire</td>
<td><ul>
<li> Messages électroniques </li>
<li> Contacts de la boîte aux lettres (un maximum de trois adresses e-mail par contact sont migrées) </li>
<li> Calendrier </li>
<li> Étiquettes </li>
</ul></td>
<td><ul>
<li> Règles </li>
<li> Délégués </li>
<li> Signatures </li>
<li> Tâches </li>
<li> Tout e-mail ou pièce jointe dépassant la limite de taille de message </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Données d’archive à partir de fichiers PST ou de toute solution d’archivage tierce (par exemple, Google Vault) </li>
<li> Droits gérés ou messages électroniques chiffrés </li>
<li> Éléments endommagés </li>
<li> Google Hangouts** </li>
<li> Groupes Google </li>
<li> Boîtes aux lettres de ressources </li>
<li> Boîtes aux lettres inactives </li>
<li> Paramètres des congés et de la réponse automatique </li>
<li> Calendriers partagés, pièces jointes sur le cloud, liens Google Hangout et couleurs de l’événement </li>
</ul>
**Les conversations Hangout enregistrées sous forme d’étiquette sont migrées. </td>
</tr>
<tr class="odd">
<td><strong>Source IMAP4 (comme Domino, GroupWise ou Zimbra)</strong></td>
<td>Migration à l’aide des outils natifs IMAP4</td>
<td><li>Messages électroniques </li></td>
<td><ul>
<li> Règles </li>
<li> Délégués </li>
<li> Listes de distribution </li>
<li> Contacts externes </li>
<li> Utilisateurs à extension messagerie </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Contacts de boîte aux lettres </li>
<li> Calendrier </li>
<li> Signatures </li>
<li> Tâches </li>
<li> Tout message électronique dépassant la limite de taille de message </li>
<li> Données d’archive </li>
<li> Message électronique chiffré </li>
<li> Éléments endommagés </li>
<li> Boîtes aux lettres inactives </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

Nos spécialistes FastTrack effectuent également les activités suivantes, spécifiques aux migrations Exchange :

  -  Fournir des conseils pour permettre la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.

## <a name="your-responsibilities"></a>Vos responsabilités

Vous effectuez les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

Vous effectuez également les activités suivantes, spécifiques aux migrations Exchange :

  - Intégration principale de FastTrack pour Exchange Online. Si vous avez effectué l’intégration vous-même, vous devez réussir les vérifications requises et les conditions préalables. Pour plus d’informations, voir [Produits et fonctionnalités](products-and-capabilities.md).
  -  Installation du niveau approprié de logiciel client conformément aux instructions Office 365. Pour plus d’informations, voir [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).
  -  Respect des conditions particulières si vous prévoyez de migrer à partir d’un environnement Exchange local. Pour plus d’informations, voir [Conditions préalables à un déploiement hybride](https://go.microsoft.com/fwlink/?LinkId=787528).
  -  Vérification que chaque environnement source est au niveau du dernier Service Pack (SP) et correctif cumulatif (RU)/(CU), le cas échéant.
  -  Configuration et validation de la coexistence de routage de messagerie SMTP entre vos environnements sources et Exchange Online, le cas échéant.
  -  Vérification que la taille de votre boîte aux lettres source ne dépasse pas le quota de boîte aux lettres cible. Selon la plateforme source, il se peut que vous deviez limiter vos données sources à 85 % du quota de boîte aux lettres cible.
  -  Migrez les données côté client, le cas échéant. Cela inclut sans s’y limiter les carnets d’adresses locaux, les données de fichiers PST locaux, les règles Outlook et les paramètres Outlook locaux.
  -  Aidez vos utilisateurs finaux à résoudre les problèmes de migration côté client.

## <a name="migration-to-sharepoint-online"></a>Migrer vers SharePoint Online

Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers SharePoint Online, nous fournissons des conseils de migration ainsi que des services de migration des données. Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client SharePoint Online, et tirer parti de nos services de migration des données pour migrer vos fichiers. Vous créez et planifiez vos événements de migration. Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut. Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers SharePoint Online.

## <a name="considerations"></a>Considérations

  - Toutes les migrations sont soumises aux quotas SharePoint Online. Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).
  - Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).

## <a name="source-environment-details"></a>Détails de l’environnement source

Nos services de migration des données migrent les données de ces environnements sources :

  - Partages de fichiers (partages de fichiers SMB (Server Message Block) sur des appareils prenant en charge SMB 2.0 et versions ultérieures).
  - Environnement G Suite unique (Google Drive uniquement).
  - Box (Starter, Business, Enterprise).
  - Dropbox pour Teams (Standard et avancée).

Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :

<table>
<thead>
<tr class="header">
<th><strong>Environnement source</strong></th>
<th><strong>Type de migration</strong></th>
<th><strong>Ce qui est migré</strong></th>
 <th><strong>Ce qui n’est pas migré</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur* </li>
<li> Autorisations liées aux fichiers et aux dossiers au niveau du groupe* </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
</ul>
*Configuration de la synchronisation d’annuaires requise. Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées. Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées. Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées.</td>
<td><ul>
<li> Historique d’appartenance et versions antérieures </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Versions antérieures </li>
<li> Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués) </li>
<li> Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS : </li>
<li> Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent) </li>
<li> Configuration de l’audit NTFS </li>
<li> Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF) </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Partages masqués </li>
<li> Partage (par exemple, autorisations accordées au niveau de partage) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Environnement G Suite unique (Google Drive uniquement)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent), y compris ceux de plus de 10 Mo </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Lecteurs partagés (dossiers et fichiers) </li>
<li> Contenu partagé appartenant au compte Google Drive en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers, couleurs des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Google Photos. Forms, Maps et autres applications connectées </li>
<li> Google Drawings </li>
<li> Contenu partagé externe à votre organisation </li>
<li> Le contenu n’appartient pas au compte Google Drive migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés. Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.) </li>
<li> Fichiers marqués comme étant restreints ou ne peuvent pas être copiés </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Contenu partagé appartenant au compte Box en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées et balises Box </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Applications, signets, favoris et flux de travail Box </li>
<li> Contenu n’appartenant pas au compte Box migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox pour Teams (Standard et avancée)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Dossiers et contenus collaboratifs partagés </li>
<li> Contenu partagé appartenant au compte Dropbox en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Dossiers Dropbox non montés </li>
<li> Utilisateurs supprimés ou déconnectés </li>
<li> Papier, vitrines et espaces Dropbox </li>
<li> Applications et favoris Dropbox (épingles/étoiles) </li>
<li> Contenu n’appartenant pas au compte Dropbox migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

## <a name="your-responsibilities"></a>Vos responsabilités

Vous effectuez les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

Vous effectuez également les activités suivantes, spécifiques aux migrations SharePoint Online :

  - Configurez tous les sites d’équipe SharePoint devant être ciblés par vos événements de migration.

## <a name="migration-to-onedrive-for-business"></a>Migration vers OneDrive Entreprise

Lorsque vous choisissez d’utiliser FastTrack pour migrer vos fichiers vers OneDrive Entreprise, nous fournissons des conseils de migration ainsi que des services de migration des données. Nous vous proposons des conseils pour vous aider à planifier la migration, configurer vos environnements sources ainsi que le client OneDrive Entreprise, et tirer parti de nos services de migration des données pour migrer vos fichiers. Vous créez et planifiez vos événements de migration. Nous les lançons conformément à votre planning, nous surveillons leur avancement et nous fournissons des rapports sur leur statut. Lorsque vos événements de migration se terminent, vous pouvez vous attendre à ce que les fichiers de sources correctement planifiées et éligibles de vos environnements sources aient été migrés vers OneDrive Entreprise.

## <a name="considerations"></a>Considérations

  - Toutes les migrations sont soumises aux quotas OneDrive Entreprise. Pour plus d’informations, voir [<span class="underline">SharePoint Online et OneDrive Entreprise : limites et frontières logicielles</span>](https://go.microsoft.com/fwlink/?LinkId=698855).
  - Nous vous recommandons de limiter le volume total des données migrées à 75 % du quota de stockage SharePoint Online total auquel vous êtes autorisé (y compris le stockage supplémentaire que vous avez peut-être acheté séparément).
  - FastTrack migre uniquement vers les disques OneDrive Entreprise actifs.

## <a name="source-environment-details"></a>Détails de l’environnement source

Nos services de migration des données migrent les données de ces environnements sources :

  - Partages de fichiers (partages de fichiers SMB sur des appareils prenant en charge SMB 2.0 et versions ultérieures).
  - Environnement G Suite unique (Google Drive uniquement).
  - Box (Starter, Business, Enterprise).
  - Dropbox pour Teams (Standard et avancée).

Le tableau suivant répertorie les détails de la migration propres à chaque environnement source :

<table>
<thead>
<tr class="header">
 <th><strong>Environnement source</strong></th>
 <th><strong>Type de migration</strong></th>
 <th><strong>Ce qui est migré</strong></th>
 <th><strong>Ce qui n’est pas migré</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>N’importe quel appareil de partage de fichiers prenant en charge SMB 2.0 et versions ultérieures</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers et aux dossiers au niveau de l'utilisateur* </li>
<li> Autorisations liées aux fichiers et aux dossiers au niveau du groupe* </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
</ul>
<br>
*Configuration de la synchronisation d’annuaires requise. Seules les autorisations NTFS exposées à l’Explorateur de fichiers Windows sont migrées. Les autorisations gérées directement sur les appareils de partage de fichiers ne sont pas migrées. Si les données sont stockées sur un appareil SMB 2.0, les autorisations équivalentes à NTFS exposées par le protocole SMB sont migrées. </td>
<td><ul>
<li> Historique d’appartenance et versions antérieures </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Versions antérieures </li>
<li> Attributs de fichiers et dossiers Windows (par exemple, en lecture seule et masqués) </li>
<li> Paramètres spéciaux et autorisations avancées NTFS (New Technology File System) et autres que NTFS : </li>
<li> Refus explicite d’autorisations (supprimées après la migration, contenu soumis à des autorisations parallèles ou des autorisations sur un dossier parent) </li>
<li> Configuration de l’audit NTFS </li>
<li> Métadonnées de fichiers supplémentaires fournies par l’infrastructure de classification des fichiers (ICF) </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Partages masqués </li>
<li> Partage (par exemple, autorisations accordées au niveau de partage) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Environnement G Suite unique (Google Drive uniquement)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Google Docs, Sheets et Slides (fichiers convertis au format Office équivalent, y compris ceux de plus de 10 Mo) </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Lecteurs partagés (dossiers et fichiers) </li>
<li> Contenu partagé appartenant au compte Google Drive en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers, couleurs des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Google Photos, Forms, Maps et autres applications connectées </li>
<li> Google Drawings </li>
<li> Contenu partagé externe à votre organisation </li>
<li> Le contenu n’appartient pas au compte Google Drive migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Autorisations d’appartenance pour les disques partagés (<strong>remarque</strong> : utilisez les rapports d’administrateur Google Drive afin d’identifier l’appartenance des disques partagés. Demandez aux utilisateurs de configurer ces paramètres d’appartenance sur la cible avant la migration.) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Contenu partagé appartenant au compte Box en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées et balises Box </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Utilisateurs bloqués ou inactifs </li>
<li> Applications, signets, favoris et flux de travail Box </li>
<li> Contenu n’appartenant pas au compte Box migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Box pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox pour Teams (Standard et avancée)</strong></td>
<td>Un ou plusieurs passages</td>
<td><ul>
<li> Documents </li>
<li> Structure des fichiers et des dossiers </li>
<li> Autorisations liées aux dossiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux dossiers au niveau du groupe </li>
<li> Fichiers inférieurs à 15 Go </li>
<li> Métadonnées de dossier et document de base :
<ul>
<li> Date de création </li>
<li> Date de modification </li>
<li> Créé par </li>
<li> Auteur de la dernière modification </li>
</ul></li>
<li> Dossiers et contenus collaboratifs partagés </li>
<li> Contenu partagé appartenant au compte Dropbox en cours de migration </li>
</ul></td>
<td><ul>
<li> Historique d’appartenance, versions précédentes et commentaires </li>
<li> Descriptions des fichiers et des dossiers </li>
<li> Autorisations liées aux fichiers au niveau de l’utilisateur </li>
<li> Autorisations liées aux fichiers au niveau du groupe </li>
<li> Métadonnées avancées </li>
<li> Attributs de verrouillage de fichier </li>
<li> Conversion d’URL incorporées dans le contenu </li>
<li> Éléments jetés </li>
<li> Documents inaccessibles ou endommagés </li>
<li> Dossiers Dropbox non montés </li>
<li> Utilisateurs supprimés ou déconnectés </li>
<li> Papier, vitrines et espaces Dropbox </li>
<li> Applications et favoris Dropbox (épingles/étoiles) </li>
<li> Contenu n’appartenant pas au compte Dropbox migré </li>
<li> Autorisations et métadonnées de base des utilisateurs externes (<strong>remarque</strong> : utilisez les rapports Dropbox pour identifier le contenu partagé avec des utilisateurs externes. Demandez aux utilisateurs de partager à nouveau leur contenu avec les utilisateurs externes après la migration.) </li>
<li> Fichiers ou dossiers dépassant les  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">restrictions et limitations SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Nos spécialistes FastTrack effectuent les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

## <a name="your-responsibilities"></a>Vos responsabilités

Vous effectuez les activités standard pendant le projet de migration. Pour plus d’informations, voir les responsabilités relatives à la migration des données dans [Processus et attentes](process-and-expectations.md).

Vous effectuez également les activités suivantes, spécifiques aux migrations OneDrive Entreprise :

  - Configurez tous les sites OneDrive Entreprise ciblés par vos événements de migration.

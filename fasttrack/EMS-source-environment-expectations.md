---
title: Attentes concernant l’environnement source
description: Configuration de l’environnement source pour l’utilisation de FastTrack Center Benefit pour EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 3/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 37fd12c6fd2b9fa09c27954f9119ad864983e691
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347466"
---
# <a name="source-environment-expectations"></a>Attentes concernant l’environnement source

Lorsque vous utilisez [FastTrack Center Benefit pour Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) pour obtenir Microsoft Azure Active Directory Premium, Microsoft Intune et Azure information protection prêts à l’usage, votre environnement doit remplir les attentes décrites dans les sections suivantes.

Vous disposez peut-être déjà d’une instance Active Directory locale dans votre organisation que vous voulez intégrer à Enterprise Mobility + Security (EMS), ou à l’un de ses services individuels qui utilise la gestion d’identité complète d’une console unique. FastTrack Center Benefit pour Enterprise Mobility + Security (EMS) inclut l’intégration d’Azure Active Directory à votre environnement Active Directory local existant.

Le tableau suivant indique les conditions attendues dans votre environnement source existant pour procéder à l’intégration.

|Activité|Attente concernant l’environnement source|
|------------|----------------------------------|
|Intégration de base|Forêts Active Directory avec le niveau de forêts fonctionnel défini sur Windows Server 2008 ou version ultérieure, avec la configuration de forêt suivante :<br /><br />- Forêt Active Directory unique<br />- Forêts Active Directory multiple </br></br>**Remarque**: Pour toutes les configurations à forêts multiples, le déploiement des services de fédération Active Directory (AD FS) n'entre pas dans le cadre du FastTrack Center Benefit.|
|Intégration Azure AD Premium|L’environnement Active Directory local et son environnement ont été préparés pour Azure AD Premium, ce qui inclut la correction des problèmes identifiés qui empêchent l’intégration avec Azure AD et les fonctionnalités Azure AD Premium.|
|Intégration Intune| Les administrateurs informatiques doivent avoir des infrastructures de certificats, WiFi et VPN existantes, qui travaillent déjà dans leurs environnements de production lors de la planification du déploiement de profils WiFi et VPN avec Intune.<br /><br /> **Remarque**: le service benefit n’inclut pas d’aide pour l’installation ou la configuration des autorités de certification, WiFi, VPN ou pour les certificats push Apple MDM  |
|Cogestion|Avec la cogestion, les administrateurs informatiques sont responsables de la préparation de l’environnement local, ce qui peut inclure une correction des problèmes qui vous empêchent de gérer simultanément les appareils Windows 10 à l’aide du Configuration Manager et d’Intune.<br /><br />**Remarque**: le service FastTrack benefit n’inclut pas d’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et/ou du client Configuration Manager vers la configuration minimale requise pour la prise en charge de la cogestion avec les appareils Windows 10. |
|Intune intégré avec Microsoft Defender - Protection avancée contre les menaces (ATP)|**Remarque** : le service FastTrack offre de l’aide sur l’intégration d’Intune avec Microsoft Defender ATP et la création de stratégies de conformité des appareils basées sur son évaluation du niveau de risque Windows 10. Il n’offre aucune aide sur l’achat, la gestion des licences ou l’activation. |
|Windows Autopilot|Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en permettant de charger leur ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service de pilote automatique de Windows. |
|Déployer Outlook pour iOS et Android de façon sécurisée avec Intune|<br /><br />- Identités utilisateurs activées dans Azure Active Directory pour Office 365.<br />-Exchange Online ou Exchange hybride configuré avec des licences utilisateur affectées.<br />|
|Azure Information Protection Premium (P2 ou EMS E5)|<br /><br />Les clients doivent déjà : <br /> - Utiliser Azure AD.<br />- Utiliser Windows ou iOS (les autres systèmes d’exploitation sont hors de portée).<br /> - Utiliser les clients Office plus récents qu’Office 2010 SP2 qui ne dépendent pas d’Office comme client principal. <br /> - Avoir leur fichier principal partageant son emplacement.  <br /> - Avoit fait la mise à jour des services de la gestion des droits relatifs à l’information AD RMS (Active Directory Rights Management Services). <br /> - Avoir une taxonomie de classification approuvée. <br /> - Comprendre les restrictions réglementaires pour la gestion des clés protégée. <br />|
|Scanneur Azure Information Protection|<br /><br /> Les clients doivent déjà : <br /> - Utiliser Windows Server 2012 R2 ou Windows Server 2016.<br /> - Être connecté à internet. <br /> - Utiliser Microsoft SQL Server 2012 dans une instance locale ou distante.  <br /> - Disposer d’un compte de service créé pour son annuaire Active Directory local et synchronisé avec Azure AD.  <br /> - Télécharger AzInfoProtection.exe. <br /> - Utiliser des étiquettes configurées pour la classification/la protection automatique.<br />|

> [!NOTE]
> **Vous voulez en savoir plus ? **
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Étapes suivantes

[FastTrack Center Benefit pour les phases d’intégration EMS](EMS-onboarding-phases.md)

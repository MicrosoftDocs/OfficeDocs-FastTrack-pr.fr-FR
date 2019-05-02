---
title: Attentes en matière d’environnement source
description: Conditions requises pour l’environnement source pour l’utilisation du centre FastTrack pour EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513149"
---
# <a name="source-environment-expectations"></a>Attente concernant l’environnement source

Lorsque vous utilisez le service [FastTrack pour Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) pour obtenir Microsoft Azure Active Directory Premium, Microsoft Intune et Azure information protection, votre environnement doit répondre aux attentes décrit dans les sections suivantes.

Vous disposez peut-être déjà d’Active Directory sur site dans votre organisation que vous souhaitez intégrer avec Enterprise Mobility + Security (EMS) ou l’un de ses services individuels qui utilise la gestion des identités enrichie à partir d’une seule console. Le service FastTrack pour Enterprise Mobility + Security (EMS) inclut l’intégration d’Azure Active Directory à votre environnement Active Directory local existant.

Le tableau suivant indique les attentes de votre environnement source existant pour l’intégration.

|Activité|Attente concernant l’environnement source|
|------------|----------------------------------|
|Intégration de base|Forêts Active Directory avec le niveau de forêt fonctionnel défini sur Windows Server 2008 ou version ultérieure, avec la configuration de forêt suivante:<br /><br />-Forêt Active Directory unique<br />-Plusieurs forêts Active Directory </br></br>**Remarque**: pour toutes les configurations à forêts multiples, le déploiement des services ADFS (Active Directory Federation Services) est hors de portée pour le service FastTrack.|
|Intégration à Azure AD Premium|Active Directory sur site et son environnement ont été préparés pour Azure AD Premium, ce qui inclut la correction des problèmes identifiés qui empêchent l’intégration à Azure AD et les fonctionnalités Azure AD Premium.|
|Intégration de Intune| Les administrateurs informatiques doivent disposer d’une autorité de certification, d’une infrastructure WiFi et d’infrastructures VPN existantes dans leurs environnements de production lors de la planification du déploiement des profils WiFi et VPN avec Intune.<br /><br /> **Remarque**: l’avantage du service n’inclut pas d’aide pour la configuration ou la configuration des autorités de certification, WiFi, des infrastructures VPN ou des certificats d’Apple MDM pour  |
|Cogestion|Les administrateurs informatiques de la cogestion sont responsables de la préparation de l’environnement local, qui peut inclure la correction des problèmes qui vous empêchent de gérer simultanément les appareils Windows 10 à l’aide de Configuration Manager et d’Intune.<br /><br />**Remarque**: l’avantage du service FastTrack n’inclut pas l’aide pour la configuration ou la mise à niveau du serveur de site Configuration Manager et/ou du client gestionnaire de configuration vers la configuration minimale requise pour la prise en charge de la cogestion avec les appareils Windows 10. |
|Intune intégré à Windows Defender protection avancée contre les menaces (Windows Defender ATP)|Votre abonnement Windows Defender ATP a été activé et configuré en fonction des exigences en matière de sécurité de votre entreprise.<br /><br />**Remarque**: l’avantage du service FastTrack fournit une assistance sur l’intégration de Intune avec Windows Defender ATP et sur la création de stratégies de conformité des appareils basées sur son évaluation du niveau de risque de Windows 10. Le service FastTrack n’offre pas d’assistance pour l’achat, la gestion des licences, l’activation ou l’utilisation de Windows Defender ATP et de sa console Centre de sécurité. |
|Windows Autopilot|Les administrateurs informatiques sont responsables de l’enregistrement de leurs appareils dans leur organisation en demandant au fournisseur de matériel de charger leurs ID de matériel en leur nom ou en le téléchargeant eux-mêmes dans le service Windows AutoPilot. |
|Déployer Outlook pour iOS et Android de manière sécurisée avec Intune|<br /><br />-Identités utilisateur activées dans Azure AD pour Office 365.<br />-Exchange Online ou Exchange hybride configuré avec des licences utilisateur affectées.<br />|
|Azure information protection (P2 ou EMS E5)|<br /><br />Les clients doivent déjà: <br /> -Utilisez Azure AD.<br />-Utilisez Windows ou iOS (les autres OSs sont hors de portée).<br /> -Utilisez les clients Office plus récents qu’Office 2010 SP2 qui ne s’appuient pas sur Office Online comme client principal. <br /> -Avoir leurs emplacements de partage de fichiers principaux.  <br /> -Mise à niveau à partir des services AD RMS (Active Directory Rights Management Services). <br /> -Ont une taxonomie de classification approuvée. <br /> -Comprendre les restrictions réglementaires relatives à la gestion des clés protégées. <br />|
|Scanneur Azure information protection|<br /><br /> Les clients doivent déjà: <br /> -Utilisez Windows Server 2012 R2 ou Windows Server 2016.<br /> -Disposer d’une connexion Internet. <br /> -Disposent de Microsoft SQL Server 2012 à partir d’une instance locale ou distante.  <br /> -Disposer d’un compte de service créé pour l’annuaire Active Directory local et synchronisé avec Azure AD.  <br /> -Avez téléchargé AzInfoProtection. exe. <br /> -Des étiquettes sont configurées pour la classification/protection automatique.<br />|

> [!NOTE]
> **Vous souhaitez en savoir plus?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Étapes suivantes

[Avantages du centre FastTrack pour les phases d’intégration EMS](EMS-onboarding-phases.md)

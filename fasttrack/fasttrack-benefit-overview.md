---
title: Présentation du Centre FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2018
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Les avantages du Centre FastTrack pour Office 365 vous permettent de collaborer à distance avec des spécialistes FastTrack pour préparer votre environnement Office 365 et planifier son lancement et son utilisation au sein de votre organisation. Pour en savoir plus sur les conditions d'éligibilité, reportez-vous à Avantages du Centre FastTrack pour Office 365.
ms.openlocfilehash: 24c09b72dc525149607b5966244427adaf7c7a49
ms.sourcegitcommit: d4cc064490fd2460682a455433fe8d9b5e219cf5
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/04/2018
ms.locfileid: "23827962"
---
# <a name="fasttrack-center-benefit-overview"></a>Présentation du Centre FastTrack

Les avantages du Centre FastTrack pour Office 365 vous permettent de collaborer à distance avec des spécialistes FastTrack pour préparer votre environnement Office 365 et planifier son lancement et son utilisation au sein de votre organisation. Pour en savoir plus sur les conditions d'éligibilité, reportez-vous à [Avantages du Centre FastTrack pour Office 365](fasttrack-benefit-for-office-365.md).
  
Nous abordons les sujets suivants :
  
- [Processus FastTrack](fasttrack-process.md)
    
- [Attente concernant l'environnement source](source-environment-expectations.md)
    
- [Phases d'intégration et de migration](onboarding-and-migration.md)
    
- [Migration des données](data-migration.md)
    
- [Responsabilités FastTrack](fasttrack-responsibilities.md)
    
- [Vos responsabilités](your-responsibilities.md)
    
- [Annexe A : Migration d'IBM Domino vers Exchange Online](from-ibm-domino-to-exchange-online.md)
    
- [Annexe B : Avantages supplémentaires du centre FastTrack](fasttrack-additional-benefits.md)
    
À la fin de l'intégration, votre client Office 365 est créé. Les titulaires d'une licence d'utilisation peuvent accéder à Office 365 en utilisant l'une des options d'identité suivantes :
  
- Identités de cloud avec comptes Office 365 uniques
    
- Identités synchronisées avec comptes Office 365 synchronisés à partir de votre site Active Directory local avec Azure Active Directory Connect (synchronisation de hachage de mot de passe ou authentification directe). Cette option est destinée aux clients disposant des éléments suivants :
    
  - Un environnement de forêt Active Directory unique.
    
  - Une topologie Active Directory à forêts multiples prise en charge. Pour les topologies prises en charge, reportez-vous à la rubrique sur les [attentes relatives à l’environnement source](source-environment-expectations.md).
    
- Identités fédérées avec des comptes Office 365 qui sont :
    
  - Synchronisées depuis Active Directory avec l'outil Connect Azure Active Directory pour les clients avec :
    
      - Une configuration de forêt Active Directory unique.
    
      - Une configuration à une seule forêt de comptes Active Directory (également appelée « forêt d’ouverture de session ») et à une seule forêt de ressources Active Directory.
    
  - Configurés avec une infrastructure locale AD FS (Active Directory Federation Services) qui est :
    
      - Fédérée avec un rôle Windows Server 2012 R2 AD FS et versions ultérieures à partir de votre instance locale d'Active Directory.
    
      - Si nécessaire, un rôle Windows Server 2012 R2 Windows Application Proxy (WAP) et versions ultérieures utilisé pour publier votre infrastructure AD FS locale sur Internet.
    
    > [!NOTE]
    > Le déploiement AD FS et WAP et la configuration sont effectués à l'aide de l'[assistant de configuration d'Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) à partir de votre environnement local. 
  
- Les titulaires d’une licence d’utilisation peuvent désormais accéder aux [offres et services éligibles](eligible-services-and-plans.md).
    

 

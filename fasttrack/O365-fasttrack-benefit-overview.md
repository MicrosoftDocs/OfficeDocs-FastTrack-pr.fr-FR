---
title: Présentation du Centre FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/2/2019
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Les avantages du Centre FastTrack pour Office 365 vous permettent de collaborer à distance avec des spécialistes FastTrack pour préparer votre environnement Office 365 et planifier son lancement et son utilisation au sein de votre organisation. Pour en savoir plus sur les conditions d'éligibilité, reportez-vous à Avantages du Centre FastTrack pour Office 365.
ms.openlocfilehash: e97523c9205344b8f5e6ee77be9db0bc2c950e0a
ms.sourcegitcommit: 0a8250d759e010cff6958016267f29acb0b7e17c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/01/2019
ms.locfileid: "29696709"
---
# <a name="fasttrack-center-benefit-overview"></a>Présentation du Centre FastTrack

Les avantages du Centre FastTrack pour Office 365 vous permettent de collaborer à distance avec des spécialistes FastTrack pour préparer votre environnement Office 365 et planifier son lancement et son utilisation au sein de votre organisation. Pour en savoir plus sur les conditions d'éligibilité, reportez-vous à [Avantages du Centre FastTrack pour Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Nous abordons les sujets suivants :
- [Processus FastTrack](O365-fasttrack-process.md) 
- [Attente concernant l'environnement source](O365-source-environment-expectations.md)
- [Phases d'intégration et de migration](O365-onboarding-and-migration.md)
- [Migration des données](O365-data-migration.md)
- [Responsabilités FastTrack](O365-fasttrack-responsibilities.md)
- [Vos responsabilités](O365-your-responsibilities.md) 
- [Annexe A : Migration d'IBM Domino vers Exchange Online](O365-from-ibm-domino-to-exchange-online.md)
- [Annexe B : Avantages supplémentaires du centre FastTrack](O365-fasttrack-additional-benefits.md)
- [Annexe C : Accord de partenariat commercial HIPAA pour le service FastTrack](O365-hipaa-business-associate-agreement.md)
- [Annexe D : Présentation des avantages du service FastTrack pour Office 365 pour le gouvernement américain](US-Gov-appendix-overview.md)
    
À la fin de l'intégration, votre client Office 365 est créé. Les titulaires d'une licence d'utilisation peuvent accéder à Office 365 en utilisant l'une des options d'identité suivantes :
- Identités de cloud avec comptes Office 365 uniques
- Identités synchronisées avec comptes Office 365 synchronisés à partir de votre site Active Directory local avec Azure Active Directory Connect (synchronisation de hachage de mot de passe ou authentification directe). Cette option est destinée aux clients disposant des éléments suivants :
  - Un environnement de forêt Active Directory unique.
  - Une topologie Active Directory à forêts multiples prise en charge. Pour les topologies prises en charge, reportez-vous à la rubrique sur les [attentes relatives à l’environnement source](O365-source-environment-expectations.md).
- Identités fédérées avec des comptes Office 365 qui sont :
  - Synchronisées depuis Active Directory avec l'outil Connect Azure Active Directory pour les clients avec :
      - Une configuration de forêt Active Directory unique.
      - Une configuration à une seule forêt de comptes Active Directory (également appelée « forêt d’ouverture de session ») et à une seule forêt de ressources Active Directory.
  - Configurés avec une infrastructure locale AD FS (Active Directory Federation Services) qui est :
      - Fédérée avec un rôle Windows Server 2012 R2 AD FS et versions ultérieures à partir de votre instance locale d'Active Directory.
      - Si nécessaire, un rôle Windows Server 2012 R2 Windows Application Proxy (WAP) et versions ultérieures utilisé pour publier votre infrastructure AD FS locale sur Internet.
    > [!NOTE]
    > Le déploiement AD FS et WAP et la configuration sont effectués à l'aide de l'[assistant de configuration d'Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) à partir de votre environnement local. 
  
- Les titulaires d’une licence d’utilisation peuvent désormais accéder aux [offres et services éligibles](M365-eligible-services-and-plans.md).
    

 

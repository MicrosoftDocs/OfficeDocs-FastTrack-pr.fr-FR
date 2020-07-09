---
title: Présentation du Centre FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011332"
---
# <a name="fasttrack-center-benefit-overview"></a>Présentation du Centre FastTrack

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Nous abordons les sujets suivants :
- [Processus FastTrack](O365-fasttrack-process.md) 
- [Attente concernant l'environnement source](O365-source-environment-expectations.md)
- [Phases d'intégration et de migration](O365-onboarding-and-migration.md)
- [Migration des données](O365-data-migration.md)
- [Responsabilités FastTrack](O365-fasttrack-responsibilities.md)
- [Vos responsabilités](O365-your-responsibilities.md) 
- [Annexe B : Avantages supplémentaires du centre FastTrack](O365-fasttrack-additional-benefits.md)
- [Annexe C : Accord de partenariat commercial HIPAA pour le service FastTrack](O365-hipaa-business-associate-agreement.md)
- [Annexe D : Présentation des avantages du service FastTrack pour Office 365 pour le gouvernement américain](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- Identités de cloud avec comptes Office 365 uniques
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - Un environnement de forêt Active Directory unique.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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


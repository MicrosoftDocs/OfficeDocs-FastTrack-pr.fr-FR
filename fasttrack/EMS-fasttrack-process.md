---
title: Processus FastTrack
description: Vue d’ensemble du processus d’intégration des Avantages du Centre FastTrack
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Normal
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a0fc877fa22f6198e45e212c85ea1234ed19da70
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817255"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Processus des Avantages du Centre FastTrack pour Enterprise Mobility + Security (EMS)

> [!CAUTION]
> Ce contenu n’est plus actuel et est planifié pour suppression. Utilisez la table des matières dans le volet de navigation de gauche pour le contenu actuel.

Si votre organisation est éligible pour bénéficier des Avantages du Centre FastTrack pour Enterprise Mobility + Security, vous pouvez collaborer à distance avec des spécialistes de FastTrack pour préparer l’utilisation de Microsoft Azure Active Directory Premium, de Microsoft Intune et d’Azure Information Protection. Le [site FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) vous permet également de demander de l’aide pour Azure Information Protection et Microsoft Cloud App Security. Pour savoir si votre organisation peut en bénéficier, voir [Offres et services éligibles](M365-eligible-services-and-plans.md).


Le processus d’intégration englobe les aspects suivants :

-   [Vue d’ensemble du processus d’intégration](EMS-fasttrack-benefit-overview.md)

-   [Attentes concernant votre environnement source](EMS-source-environment-expectations.md)

-   [Phases du processus d’intégration](EMS-onboarding-phases.md)

-   [Responsabilités de FastTrack](EMS-fasttrack-responsibilities.md) pour chaque phase

-   [Responsabilités du client](EMS-your-responsibilities.md) pour chaque phase

Voici ce à quoi vous pouvez vous attendre une fois l’intégration terminée :

-   Vos clients EMS pour les services sélectionnés sont créés.

-   Les utilisateurs titulaires d’une licence peuvent accéder aux services Enterprise Mobility + Security à l’aide de l’une des options d’identité suivantes :

    -   Identités cloud (comptes Enterprise Mobility + Security uniques)

    -   Identités synchronisées : comptes Enterprise Mobility + Security synchronisés à partir de votre Active Directory local à l’aide de l’outil Azure Active Directory Connect (Synchronisation du hachage de mot de passe ou Authentification directe). Cette option est destinée aux clients disposant d’une forêt unique ou de plusieurs forêts Active Directory.

    -   Identités fédérées avec des comptes Microsoft EMS présentant les caractéristiques suivantes :

        -   Synchronisés à partir d’Active Directory avec l’outil Azure AD Connect. Cette option est destinée aux clients disposant d’une seule configuration de forêt Active Directory.

        -   Fédérés avec les services de fédération Active Directory (AD FS) 2.0 ou version ultérieure dans Windows Server 2012 R2 à partir de votre Active Directory local.

        -   La capacité de classifier automatiquement et de protéger les informations tant au repos qu’en transit à l’aide d’Azure information Protection. 

        -   La capacité de découvrir des informations au sein de partages de fichiers locaux et de serveurs SharePoint avec l’analyseur Azure information Protection. 

        -   La capacité de gérer vos clés de client Azure information Protection à l’intérieur d’Azure Key Vault. 


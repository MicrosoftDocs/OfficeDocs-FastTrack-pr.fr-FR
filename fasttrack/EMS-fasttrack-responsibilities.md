---
title: Responsabilités FastTrack
description: Responsabilités de FastTrack lorsque les clients utilisent le centre FastTrack pour EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 4c8dd188e0e29613b9221c087f0a8e35ed744179
ms.sourcegitcommit: 28dafb1d0904d29c4e113b03d3c1b0fcd2257508
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/13/2019
ms.locfileid: "33967959"
---
# <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

FastTrack a les responsabilités suivantes lors de l’intégration.

## <a name="general"></a>Général

-   Fournir une assistance technique à distance pour les activités de configuration requises, comme indiqué dans les descriptions détaillées des phases.

-   Fournir une documentation, des outils logiciels et des consoles d’administration disponibles pour vous aider à réduire ou à éliminer les tâches de configuration.

## <a name="initiate-phase"></a>Phase de lancement

-   Travaillez avec vous pour commencer l’intégration.

-   Définir les services éligibles que vous souhaitez intégrer.

## <a name="assess-phase"></a>Phase d’évaluation

-   Fournir un aperçu administratif.

-   Fournir des conseils à propos des éléments suivants :

    -   Besoins en matière de DNS, de réseau et d’infrastructure.

    -   Besoins du client (navigateur Internet, système d’exploitation client et besoins des services).

    -   identité utilisateur et approvisionnement ,

    -   Activation des services éligibles qui ont été achetés et définis comme faisant partie de l’intégration.

-   Établir la chronologie des activités de correction.

-   Fournir une liste de vérification des corrections pour Intune et Azure AD Premium.

## <a name="remediate-phase"></a>Phase de correction

-   Organiser des téléconférences avec vous selon le calendrier convenu pour examiner la progression des activités de correction, par exemple, vous guider dans les conditions préalables à l’installation d’un service Cloud de Microsoft.

## <a name="enable-phase"></a>Phase d’activation
Fournir des conseils à propos des éléments suivants :

-   Activation de votre abonnement ou client de service Microsoft Online.

-   la configuration des protocoles TCP/IP et des ports de pare-feu ;

-   la configuration du DNS pour les services éligibles ;

-   Validation de la connectivité à Microsoft Online Services.

-   Pour un environnement à forêt unique:

    -   L’installation d’un serveur de synchronisation d’annuaires entre vos services de domaine Active Directory (AD DS) et les services Microsoft Online Services éligibles (uniquement si nécessaire).

    -   Configuration de l’authentification managée (synchronisation de hachage de mot de passe ou authentification directe) avec l’outil de connexion Azure Active Directory. (aide uniquement si nécessaire).

        > [!NOTE]
        > Le développement et l’implémentation des extensions de règles personnalisées sont hors de portée.

-   Pour une forêt unique lorsque la cible est des identités fédérées: installation et configuration des services ADFS (Active Directory Federation Services) pour l’authentification de domaine local avec Intune dans une configuration à site unique et tolérant aux pannes, si nécessaire.

    > [!NOTE]
    > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée.

-   Test de la fonctionnalité d’authentification unique (SSO), si elle est déployée.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Phase d’activation-Microsoft Azure Active Directory Premium

Fournir des conseils à propos des éléments suivants :

- Activation de votre client Azure AD Premium.

- la configuration de ports de pare-feu ;

- la configuration du DNS pour les services éligibles ;

- Validation de la connectivité aux services Azure AD Premium.

- Pour un environnement à forêt unique:

  -   L’installation d’une synchronisation d’annuaires entre vos services de domaine Active Directory (AD DS) et Azure AD Connect, si nécessaire.

  -   Configuration d’une méthode d’authentification (synchronisation de hachage de mot de passe ou authentification directe) avec l’outil Azure AD Connect.

- Pour un environnement à forêts multiples:

  -   Installation de la synchronisation Azure AD Connect, configuration pour plusieurs scénarios de forêt.
- Pour les environnements de forêt unique et de forêts multiples :
  - la configuration de l'authentification directe Azure Active Directory, si nécessaire ;
  - la configuration de l'authentification unique (SSO) transparente Azure Active Directory, si nécessaire.
    > [!NOTE]
    > L'authentification directe Azure Active Directory pour les environnements de forêts multiples est prise en charge s'il existe des approbations de forêt entre vos forêts Active Directory et si le routage des suffixes de noms est correctement configuré. Des agents supplémentaires peuvent être installés sur plusieurs serveurs locaux pour fournir une haute disponibilité pour les demandes de connexion.

  - Pour plus d'informations, reportez-vous à [Authentification directe Azure Active Directory : Démarrage rapide](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) et [Authentification unique transparente Azure Active Directory - Démarrage rapide](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Pour obtenir plus d'informations sur les limites de l'authentification directe, reportez-vous à [Authentification directe Azure Active Directory : limitations actuelles](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Pour obtenir plus d'informations sur les problèmes de l'authentification unique transparente, reportez-vous à [Résoudre les problèmes d'authentification unique transparente Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > L’écriture différée de mot de passe et de synchronisation de hachage de mot de passe plusieurs forêts. Toutefois, les autres scénarios d’écriture différée ne sont pas pris en charge.

  - La configuration de la synchronisation entre les forêts Active Directory locales et Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Le développement et l’implémentation des extensions de règles personnalisées sont hors de portée.

- Pour une forêt unique lorsque la cible est des identités fédérées:

  -   L’installation et la configuration des services AD FS pour l’authentification de domaine local avec Azure AD Premium dans une configuration à site unique et à tolérance de panne (le cas échéant).

  > [!NOTE]
  > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée.

- Test de la fonctionnalité SSO (si elle est déployée).

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Phase d’activation-Azure AD Premium--avec Azure AD Connect et AD FS

Fournir des conseils sur la configuration:

- Mise en service de l’utilisateur, y compris la gestion des licences.

- Synchronisation d’annuaire Azure AD Connect (avec écriture différée de mot de passe et synchronisation de hachage de mot de passe).

  - Azure Active Directory self-service Password Reset (SSPR).

  - Authentification multifacteur Azure.

  - Jusqu’à trois (3) ou plus Software as a service (SaaS) intégration d’applications avec l’authentification unique (SSO) à partir d' [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme répertorié dans la liste des didacticiels d' [intégration des applications](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitée à la mise en service sortante uniquement.

  - Écran d’ouverture de session personnalisé, y compris le logo, le texte et les images.

  - Groupes en libre-service et dynamiques (groupes).

  - Proxy d’application Azure Active Directory.

  - Intégrité d’Azure Active Directory Connect.

  - Accès conditionnel à Azure Active Directory.

  - Conditions d’utilisation d’Azure Active Directory.

  - Protection des identités Azure Active Directory.

  - Azure Active Directory Privileged Identity Management.

  - Avis d’accès à Azure Active Directory.

### <a name="enable-phase---intune"></a>Phase d’activation-Intune

> [!IMPORTANT]
> FastTrack ne prend pas en charge la gestion de PC classique de Windows 10 avec Intune. FastTrack prend uniquement en charge la gestion de Windows 10 via la gestion des appareils mobiles Intune.

Fournir des **conseils** sur:

-   La configuration des identités qui doivent être utilisées par Intune en tirant parti de votre annuaire Active Directory local ou des identités Cloud (Azure Active Directory).

-   Gestion des licences de vos utilisateurs finaux.

-   L’ajout d’utilisateurs à votre abonnement Intune, la définition des rôles d’administrateur informatique et la création de groupes d’utilisateurs et d’appareils.

-   La configuration de votre autorité de gestion des appareils mobiles, en fonction de vos besoins en matière de gestion, notamment:

    -   Définition de Intune en tant qu’autorité MDM.

    -   Configuration des groupes de tests à utiliser pour valider les stratégies de gestion MDM.

    -   Navigation dans le portail d’administration Intune pour localiser des informations sur les utilisateurs et les appareils.

    -   Configuration des rôles Intune (opérateur de support technique, administrateurs, etc.)

    -   La configuration des services et des stratégies de gestion MDM comme:

        -   Déploiement d’applications pour chaque plateforme prise en charge via des liens Web, MSI et/ou des liens détaillés.

        -   Déploiement d’Office ProPlus sur des appareils Windows 10.

        -   Programmes d’achat en volume pour le déploiement d’applications, y compris les VPP de Apple, Windows Store pour les entreprises et Google Play for Work for Work.

        -   Le déploiement de la messagerie, des réseaux sans fil et des profils VPN si vous disposez d’une autorité de certification existante, d’une infrastructure Wi-Fi ou VPN dans votre organisation.

        -   Configuration de Microsoft Intune Exchange Connector (le cas échéant).

        -   Profils de configuration d’appareil pour les plateformes d’appareils prises en charge.

    -   La configuration des stratégies d’accès conditionnel.

    -   La configuration et le déploiement des stratégies de protection des applications Intune pour chaque plateforme prise en charge.

    -   Préparation des applications métier pour les stratégies de protection des applications Intune, avec des instructions sur les options disponibles.

    -   Inscrire des périphériques de chaque plateforme prise en charge auprès de votre service Intune ou de votre gestionnaire de configuration avec le service Intune de Microsoft.

    -   Connexion à l’entrepôt de données Intune.

    -   Intégration de Intune à:
        -   Visionneuse d’équipe pour l’assistance à distance (l’abonnement Team Viewer est requis).

        -   Solutions pour les partenaires de défense contre les menaces mobiles (l’abonnement à une solution partenaire mobile Threat Defense est requis).

        -   Solutions de gestion des dépenses de télécommunication (l’abonnement à une solution de gestion des dépenses de télécommunication est requis).

        -   Windows Defender Advanced Threat Protection (Windows E5 ou Microsoft 365 E5 licences sont requises).

    -   La configuration des mises à jour logicielles pour les plateformes prises en charge.

    -   Ressources pour la planification de l’adoption par les utilisateurs.

- Configuration de Windows AutoPilot:

    - Configurez et configurez Microsoft Intune pour Windows AutoPilot.

    - Configurer des groupes dynamiques Azure AD

    - Ajoutez votre marque de société dans Azure AD.

    - Créez et affectez des appareils à des profils Windows AutoPilot (par exemple, un profil Windows AutoPilot qui limite la création de comptes d’administrateur local).

    - Personnaliser l’OOBE (out-of-Box-Experience) afin de se conformer aux exigences de l’organisation.

    - Configuration de l’enregistrement automatique MDM dans Azure AD et Intune.

    > [!NOTE]
    > La configuration de Windows AutoPilot en dehors de Intune est hors de portée pour le service FastTrack.

### <a name="enable-phase---co-management"></a>Phase d’activation-co-gestion

Fournir des conseils à propos des éléments suivants :

-   Gestion des licences de vos utilisateurs finaux.

-   L’ajout d’utilisateurs à votre abonnement Intune, la définition des rôles d’administrateur informatique et la création de groupes d’utilisateurs et d’appareils (si Intune n’est pas installé).

-   Configuration d’Azure Active Directory pour l’inscription automatique MDM.

-   Configurez une jointure Azure Active Directory hybride.

-   Configurer la passerelle de gestion Cloud.

-   L’ajout d’utilisateurs à votre abonnement Intune, la définition des rôles d’administrateur informatique et la création de groupes d’utilisateurs et d’appareils.

-   Prepare Intune (si Intune n’est pas installé):

    -   La configuration de votre autorité de gestion des appareils mobiles, en fonction de vos besoins en matière de gestion, notamment:

    -   Définition de Intune en tant qu’autorité MDM.

    -   Configuration des groupes de tests à utiliser pour valider les stratégies de gestion MDM.

    -   Navigation dans le portail d’administration Intune pour localiser des informations sur les utilisateurs et les appareils.

    -   Configuration des rôles Intune (opérateur de support technique, administrateurs, etc.)

    -   La configuration et le déploiement des stratégies de protection des applications Intune pour chaque plateforme prise en charge.

    -   Inscrire des appareils Windows 10 sur votre Intune.

- Activez la co-gestion dans la console Configuration Manager.

- Basculez les charges de travail vers Intune.

- Surveillez l’activité de co-gestion dans votre environnement.

### <a name="enable-phase--azure-information-protection"></a>Phase d’activation: Azure information protection

Fournir des conseils sur: 

- Aux clients de classer et d’étiqueter automatiquement les informations dans les applications Office (par exemple, Word, PowerPoint, Excel et Outlook) exécutées sur Windows et à l’aide du client Azure information protection. 
- Fichiers au repos à l’aide du scanneur Azure information protection.
- Les E-mails en transit à l’aide de règles de flux de messagerie Exchange Online. 

La prise en charge est également fournie aux clients qui souhaitent appliquer la protection à l’aide des services Microsoft Azure Rights Management (Azure RMS), du chiffrement de messages Office 365 (OME) et de la protection contre la perte de données (DLP). 

Les clients sont dotés de conseils pour: 

- Activez et configurez leur client.
- Créez et configurez des étiquettes et des stratégies.
- Appliquer la protection des informations aux documents. 

> [!NOTE]
> **Vous souhaitez en savoir plus?** Voir [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Étapes suivantes

[Avantages de FastTrack pour EMS-vos responsabilités](EMS-your-responsibilities.md)

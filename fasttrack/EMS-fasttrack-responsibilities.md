---
title: Responsabilités FastTrack
description: Responsabilités de FastTrack lorsque les clients emploient FastTrack Center Benefit pour EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 12/03/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 71030fee255c784f57ed4ee880b6bc01087d5a1b
ms.sourcegitcommit: 39616c06c0617700b1393e055894acb6aa6f7776
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/02/2019
ms.locfileid: "39662855"
---
# <a name="fasttrack-responsibilities"></a>Responsabilités FastTrack

Microsoft a les responsabilités suivantes lors de l’intégration.

## <a name="general"></a>Général

-   Assistance technique à distance pour les activités de configuration obligatoires, comme indiqué dans les descriptions détaillées des phases.

-   Documentation disponible, outils logiciels et des consoles d’administration pour vous aider à réduire ou à éliminer les tâches de configuration. 

## <a name="initiate-phase"></a>Phase de lancement

-   Vous aider à lancer l’intégration.

-   Définir les services éligibles que vous souhaitez intégrer.

## <a name="assess-phase"></a>Phase d’évaluation

-   Fournir un aperçu administratif.

-   Fournir des conseils à propos des éléments suivants :

    -   DNS, réseau et besoins en infrastructure.

    -   besoins du client (navigateur Internet, système d’exploitation client et besoins des services) ;

    -   identité utilisateur et approvisionnement ,

    -   Activation des services éligibles qui ont été achetés et définis comme faisant partie de l’intégration.

-   Établir la chronologie des activités de correction.

-   Fournir une liste de contrôle de conversion pour Intune et Azure AD Premium.

## <a name="remediate-phase"></a>Phase de correction

-   Organiser des téléconférences avec vous conformément au planning convenu pour examiner la progression des activités de conversion, par exemple, vous guider au cours des conditions préalables d’installation préalables à l’intégration d’un service Cloud Microsoft.

## <a name="enable-phase"></a>Phase d’activation
Fournir des conseils à propos des éléments suivants :

-   Activation de votre abonnement ou client de service Microsoft Online.

-   la configuration des protocoles TCP/IP et des ports de pare-feu ;

-   la configuration du DNS pour les services éligibles ;

-   Validation de la connectivité à Microsoft Online Services.

-   Pour un environnement à forêt unique :

    -   Installation d’un serveur de synchronisation d’annuaires entre vos services de domaine Active Directory (AD DS) et les service Microsoft online éligible (aide seulement si nécessaire). 

    -   Configuration de l’authentification gérée (synchronisation de hachage de mot de passe ou authentification directe) avec l’outil Azure Active Directory Connect. (aide uniquement si nécessaire).

        > [!NOTE]
        > Le développement et implémentation des extensions de règles personnalisées sont hors de portée.

-   Pour une forêt unique lorsque les identités fédérées sont ciblées : l’installation et la configuration des services AD FS (Active Directory Federation Services) pour l’authentification de domaine local avec Intune dans une configuration à site unique et à tolérance de panne, si nécessaire.

    > [!NOTE]
    > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée.

-   Test de la fonctionnalité d’authentification unique (SSO) si elle est déployée.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Phase d’activation - Microsoft Azure Active Directory Premium

Fournir des conseils à propos des éléments suivants :

- Activation de votre client Azure AD Premium.

- Configuration de ports de pare-feu.

- Configuration du DNS pour les services éligibles.

- Validation de la connectivité à Azure AD Premium services.

- Pour un environnement à forêt unique :

  -   Installation d’un serveur de synchronisation d’annuaires entre vos services de domaine Active Directory (AD DS) et Azure AD Connect, si nécessaire.

  -   Configuration d’une méthode d’authentification (synchronisation de hachage de mot de passe ou authentification directe) avec l’outil Azure Active Directory Connect.

- Pour un environnement à forêts multiples :

  -   Installation de la synchronisation Azure AD Connect, configurée pour plusieurs scénarios de forêts.
- Pour les environnements de forêt unique et de forêts multiples :
  - la configuration de l'authentification directe Azure Active Directory, si nécessaire ;
  - la configuration de l'authentification unique (SSO) transparente Azure Active Directory, si nécessaire.
    > [!NOTE]
    > L'authentification directe Azure Active Directory pour les environnements de forêts multiples est prise en charge s'il existe des approbations de forêt entre vos forêts Active Directory et si le routage des suffixes de noms est correctement configuré. Des agents supplémentaires peuvent être installés sur plusieurs serveurs locaux pour fournir une haute disponibilité pour les demandes de connexion.

  - Pour plus d'informations, reportez-vous à [Authentification directe Azure Active Directory : Démarrage rapide](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) et [Authentification unique transparente Azure Active Directory - Démarrage rapide](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Pour obtenir plus d’informations sur les limites de l’authentification directe, reportez-vous à la rubrique [Authentification directe Azure Active Directory : limites actuelles](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Pour obtenir plus d'informations sur les problèmes de l'authentification unique transparente, reportez-vous à [Résoudre les problèmes d'authentification unique transparente Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > La synchronisation de hachage de mot de passe et l’écriture différée de mot de passe prennent en charge plusieurs forêts. Cependant, les autres scénarios d’écriture différée ne sont pas pris en charge.

  - La configuration de la synchronisation entre les forêts Active Directory locales et le répertoire Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Le développement et implémentation des extensions de règles personnalisées sont hors de portée.

- Pour une forêt unique lorsque les identités fédérées sont ciblées :

  -   L’installation et la configuration des services AD FS pour l’authentification de domaine local avec Azure AD Premium dans une configuration à site unique et à tolérance de panne, si nécessaire.

  > [!NOTE]
  > Pour toutes les configurations à forêts multiples, les déploiements AD FS sont hors de portée.

- Le test de la fonctionnalité d’authentification unique (SSO), si elle est déployée.

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Phase d’activation - Azure AD Premium - avec Azure AD Connect et AD FS

Fournir des conseils à propos de la configuration :

- Configurer l’approvisionnement d’utilisateurs, y compris la gestion des licences.

- Synchronisation d’annuaire Azure AD Connect (avec mot de passe différé et synchronisation de hachage de mot de passe).

  - Réinitialisation de mot de passe libre-service Azure Active Directory.

  - Authentification multifacteur Azure.

  - Jusqu’à trois (3) ou plus intégrations de logiciels comme service (SaaS) à l’aide de l'authentification unique (SSO) à partir d’[Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Configuration automatique des utilisateurs pour les applications SaaS intégrées répertoriées dans la [liste des didacticiels d’intégration des applications](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), limitée à la configuration sortante uniquement.

  - Écran de connexion personnalisé, y compris le logo, le texte et les images.

  - Groupes libre-service et dynamiques (groupes).

  - Proxy d’application Azure Active Directory.

  - Azure Active Directory Connect Health.

  - Accès conditionnel Azure Active Directory.

  - Conditions d’utilisation d’Azure Active Directory.

  - Azure Active Directory Identity Protection.

  - Azure Active Directory Privileged Identity Management.

  - Azure Active Directory Access Reviews.

### <a name="enable-phase---intune"></a>Phase d’activation - Intune

> [!IMPORTANT]
> FastTrack ne prend pas en charge la gestion classique de Windows 10 PC avec Intune. FastTrack prend uniquement en charge la gestion de Windows 10 via la gestion des périphériques mobiles Intune.

Fournir des conseils à propos des éléments suivants :

-   Configurer les identités pour les utiliser avec Intune, soit en tirant parti de votre Active Directory local, soit d’identités Cloud (Azure Active Directory).

-   Licences pour les utilisateurs finaux.

-   Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.

-   Configuration de votre autorité de gestion des appareils mobiles, en fonction de vos besoins en matière de gestion, notamment :

    -   Définir Intune comme autorité pour la gestion des périphériques mobiles.

    -   Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.

    -   Navigation dans le portail d’administration Intune pour trouver des informations sur les utilisateurs et les appareils.

    -   Configuration des rôles Intune (opérateur de support technique, administrateurs, etc.)

    -   Configuration des stratégies de gestion et des services de gestion du service MDM tels que :

        -   Déploiement d’applications pour chaque plateforme prise en charge par le biais de liens Web, de MSI et/ou de liens profonds.

        -   Déploiement d’Office ProPlus sur des appareils Windows 10.

        -   Programmes d’achat en volume pour le déploiement d’applications, notamment VPP Apple, Windows Store pour les entreprises et Google Play pour Work Store.

        -   Déploiement de messages électroniques, de réseaux sans fil et de profils VPN si vous avez une autorité de certification existante, une infrastructure Wi-Fi ou VPN au sein de votre organisation.

        -   Configurer Connecteur Microsoft Intune Exchange (le cas échéant).

        -   Profils de configuration d’appareil pour les plateformes d’appareils prises en charge.

    -   Configurer les stratégies d’accès conditionnel Azure AD.

    -   Configurer et déployer des stratégies de protection des applications Intune pour chaque plateforme prise en charge.

    -   Préparation des applications métier pour les stratégies de protection des applications Intune, avec des conseils sur les options disponibles.

    -   Inscription de périphériques de chaque plateforme prise en charge à votre Intune ou à votre gestionnaire de configuration avec Microsoft Intune service.

    -   Connexion à Intune Data Warehouse.

    -   Intégration de Intune avec :
        -   Visionneuse d’équipe pour l’assistance à distance (l’abonnement Team Viewer est obligatoire).

        -   Solutions pour les partenaires mobiles pour la défense contre les menaces Mobile Threat Defense (l’abonnement Mobile Threat Defense est requis).

        -   Solutions de gestion des dépenses télécom (l’abonnement solutions de gestion des dépenses de télécoms est requise).

        -   Protection avancée contre les menaces Windows Defender (les licences Windows E5 ou Microsoft 365 E5 sont requises).

    -   Configuration des mises à jour logicielles pour les plateformes prises en charge.

    -   Ressources pour la planification de l’adoption par les utilisateurs.

- Configuration de Windows AutoPilot :

    - Configurer et installer Microsoft Intune pour Windows AutoPilot.

    - Configurer les groupes dynamiques Azure AD

    - Ajoutez la marque de votre entreprise à Azure AD.

    - Créez des appareils et attribuez-les à des profils de Windows Autopilot (par exemple, profil Windows AutoPilot restreignant la création d’un compte d’administrateur local).

    - Personnalisez l’expérience OOBE (OOBE) pour vous conformer aux exigences de l’organisation.

    - Configuration de l’inscription automatique de MDM dans Azure AD et Intune.

    > [!NOTE]
    > La configuration de Windows AutoPilot hors Intune n’est plus dans l’étendue de FastTrack Benefit.

### <a name="enable-phase---co-management"></a>Phase d’activation - Co-gestion

Fournir des conseils à propos des éléments suivants :

-   Licences pour les utilisateurs finaux.

-   Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils (si Intune n’est pas installé).

-   Configuration d’Azure Active Directory pour l’inscription automatique à la gestion des périphériques mobiles.

-   Configuration hybride Azure Active Directory Join.

-   Configurer la passerelle de gestion Cloud.

-   Ajouter des utilisateurs à votre abonnement Intune, définir des rôles d’administrateur informatique et créer des groupes d’utilisateurs et d’appareils.

-   Préparer Intune (si Intune n’est pas installé) :

    -   Configuration de votre autorité de gestion des appareils mobiles, en fonction de vos besoins en matière de gestion, notamment :

    -   Définir Intune comme autorité pour la gestion des périphériques mobiles.

    -   Configuration des groupes tests à utiliser pour valider les stratégies de la gestion des périphériques mobiles.

    -   Navigation dans le portail d’administration Intune pour trouver des informations sur les utilisateurs et les appareils.

    -   Configuration des rôles Intune (opérateur de support technique, administrateurs, etc.)

    -   Configurer et déployer des stratégies de protection des applications Intune pour chaque plateforme prise en charge.

    -   Inscription de périphériques Windows 10 à votre Intune.

- Activer co-gestion dans la console Configuration Manager.

- Basculer les charges de travail dans Intune.

- Surveiller l’activité de co-gestion dans votre environnement.

### <a name="enable-phase--azure-information-protection"></a>Phase d’activation - Azure Information Protection

Fournir des conseils à propos des éléments suivants : 

- Activation et configuration du client.

- Création et configuration d’étiquettes et de stratégies.

- Application de la protection des informations aux documents. 

- Classifier et étiqueter automatiquement des informations dans les applications Office (telles que Word, PowerPoint, Excel et Outlook) exécutées sur Windows et utilisant le client Azure information protection.

- Utilisation des fichiers au repos avec l’analyseur Azure information protection.

- Surveillance des courriers électroniques en transit à l’aide de règles de flux de messagerie Exchange Online.

Des instructions sont également fournies aux clients qui souhaitent appliquer une protection à l’aide de Microsoft Azure Rights Management Services (Azure RMS), d’Office 365 Encryption (OME) et de protection contre la perte de données (DLP).

> [!NOTE]
> **Vous voulez en savoir plus ?** Voir [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).  

## <a name="next-steps"></a>Étapes suivantes

[Avantages de FastTrack pour EMS - Vos responsabilités](EMS-your-responsibilities.md)

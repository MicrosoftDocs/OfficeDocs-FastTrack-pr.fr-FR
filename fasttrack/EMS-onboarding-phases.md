---
title: Phases d’intégration et de migration
description: Phases du centre FastTrack
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/09/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: e51f030b-8b08-4fea-96c9-d4ded435a264
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e849f562316f3b8854dacf199889a2a8486b5bc
ms.sourcegitcommit: 48d77313a4f035c81b9ad10bc2a415e1c7db23c5
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/10/2019
ms.locfileid: "31767293"
---
# <a name="onboarding-phases"></a>Phases d’intégration

Lorsque vous utilisez les [offres et les services éligibles](M365-eligible-services-and-plans.md) pour l'utilisation de Microsoft Azure Active Directory Premium et de Microsoft Intune, plusieurs phases sont impliquées dans le processus. Les sections suivantes décrivent chacune des phases du processus d'intégration.

L'intégration comporte quatre phases principales:

![Les quatre phases du processus d'intégration FastTrack](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>Phase de lancement

Une fois que vous avez acheté le nombre approprié de licences, suivez les conseils indiqués dans le message électronique de confirmation d'achat pour associer les licences à votre client existant ou nouveau client. Microsoft vérifie ensuite votre éligibilité pour le service FastTrack et tente de vous contacter pour offrir une assistance à l'intégration.

> [!NOTE]
> Vous pouvez également demander de l'aide auprès du [Centre FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) si vous êtes prêt à déployer ces services pour votre organisation.

### <a name="to-request-assistance"></a>Pour demander de l'assistance

1. Connectez-vous au [site FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Sélectionnez **FastTrack**.
3. Sélectionnez **Services**.
4. Complétez le **formulaire demande d'assistance concernant Microsoft 365**.

Une fois le support technique d'intégration démarré, nous allons configurer une planification des réunions en ligne.

> [!NOTE]
> Si vous avez un partenaire Microsoft figurant dans votre client Office 365, cette option ne s'affiche pas. Consultez votre partenaire Microsoft pour obtenir de l'aide.

Les partenaires Microsoft peuvent également obtenir de l'aide par le biais du [site FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) pour le compte d'un client. To do so:

1. Connectez-vous au [site FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Sélectionnez **FastTrack**.
3. Sélectionnez **Mes clients**.
4. Recherchez votre client ou sélectionnez-le dans votre liste de clients.
5. Sélectionnez **Services**.
6. Complétez le **formulaire demande d'assistance concernant Microsoft 365**.

Une fois le support technique d'intégration démarré, FastTrack configure une planification de réunions en ligne pour discuter du processus d'intégration, vérifier les données et configurer une réunion de lancement.

![Phase de démarrage de l'intégration](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>Phase d’évaluation

Une fois que le processus d'intégration commence, le centre FastTrack travaille avec vous pour évaluer votre environnement source et les exigences. Les outils sont exécutés pour évaluer votre environnement, et les spécialistes FastTrack vous guident tout au long de votre évaluation de votre environnement local Active Directory, des navigateurs Internet, des systèmes d'exploitation des appareils clients, du système DNS (Domain Name System), du réseau, de l'infrastructure et du système d'identité. Déterminez si des modifications sont requises pour l'intégration.

Le centre FastTrack vous connecte également avec des conseils sur la façon d'effectuer l'adoption des services éligibles.

En fonction de votre configuration actuelle, nous fournissons un plan de correction qui permet à votre environnement source de bénéficier de la configuration minimale requise pour l'intégration à EMS ou ses services Cloud individuels. Nous avons également défini des appels de point de contrôle appropriés pour la phase de correction.

![Phase d'évaluation de l'intégration](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>Phase de correction
Vous effectuez les tâches du plan de correction sur votre environnement source afin de répondre aux exigences de l'intégration et de l'adoption de chaque service (le cas échéant).

![Phase de correction de l'intégration](./media/ft-remediate-phase.png)

Avant de commencer la phase d'activation, nous vérifions conjointement les résultats des activités de correction afin de vous assurer que vous êtes prêt à continuer.

## <a name="enable-phase"></a>Phase d’activation
Une fois toutes les activités de correction terminées, le projet passe à la configuration de l'infrastructure de base pour la consommation de service et à la mise en service de chaque service Cloud EMS éligible.

**Activer les fonctionnalités principales de phase**

L'intégration de base implique l'approvisionnement de services et l'intégration du locataire et de l'identité. Il décrit également les étapes à suivre pour fournir une base pour les services en ligne intégrés tels qu'Azure AD Premium et Intune.

![Phases d'activation de l'intégration-fonctionnalités principales](./media/ft-enable-phase-core-01.png)

![Phases d'activation de l'intégration-fonctionnalités principales](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP signifie proxy d'application Web. SSL signifie Secure Sockets Layer. SDS signifie School Data Sync. Pour plus d'informations sur SDS, consultez la rubrique [Bienvenue dans Microsoft School Data Sync](https://go.microsoft.com/fwlink/?linkid=871480).

> [!NOTE]
> Une méthode d'authentification gérée inclut, mais n'est pas limitée à la synchronisation de hachage de mot de passe. L'intégration des identités est une activité unique et n'inclut pas la migration ou la désaffectation des méthodes d'authentification existantes, telles que Managed ou Federated.

### <a name="enable-phase---azure-ad-premium"></a>Phase d'activation-Azure AD Premium

L'environnement Azure AD Premium peut être configuré à l'aide de la synchronisation d'annuaires de l'outil Azure Active Directory Connect et des services ADFS (Active Directory Federation Services) (si nécessaire).

Pour les scénarios Azure AD Premium qui incluent la synchronisation des identités locales avec le Cloud, nous vous aidons à ajouter des administrateurs informatiques et des utilisateurs à votre abonnement, à configurer les conditions préalables à la gestion, à configurer Azure AD Premium, configuration d'annuaire synchronisation avec l'authentification managée et AD FS à l'aide de l'outil Azure AD Connect, la configuration des utilisateurs de test et la validation de vos cas d'utilisation de base pour le service.

Le programme d'installation d'Azure AD Premium inclut l'activation des fonctionnalités suivantes:

-   La réInitialisation du mot de passe en libre-service Azure Active Directory (SSPR).

-   Authentification multiFacteur Azure (authentification multiFacteur Azure).

-   Jusqu'à trois (3) ou plus Software as a service (SaaS) intégration d'applications avec l'authentification unique (SSO) à partir d' [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

-   Mise en service automatique des utilisateurs pour les applications SaaS pré-intégrées, comme répertorié dans la liste des didacticiels d' [intégration des applications](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitée à la mise en service sortante uniquement.

-   Écran d'ouverture de session personnalisé, y compris le logo, le texte et les images.

-   Groupes en libre-service et dynamiques (groupes).

-   Proxy d'application Azure Active Directory.

-   Intégrité d'Azure Active Directory Connect.

-   Accès conditionnel à Azure Active Directory.

-   Conditions d'utilisation d'Azure Active Directory.

-   Protection des identités Azure Active Directory.

-   Azure Active Directory Privileged Identity Management.

-   Avis d'accès à Azure Active Directory.

![Phase d'activation de l'intégration-Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>Phase d'activation-Intune

Pour Intune, nous vous guiderons tout au long de la préparation à l'utilisation de Microsoft Intune pour gérer les appareils. Les étapes exactes dépendent de votre environnement source et sont basées sur les besoins de votre appareil mobile et de la gestion des applications mobiles. Les étapes peuvent être les suivantes:

-   Gestion des licences de vos utilisateurs finaux. Nous proposons également une assistance sur l'activation des licences en volume pour votre client de service Cloud Microsoft (si nécessaire).

-   Configuration des identités pour qu'elles soient utilisées par Intune en tirant parti de votre organisation Active Directory locale ou des identités Cloud.

-   L'ajout d'utilisateurs à votre abonnement Intune, la définition des rôles d'administrateur informatique et la création de groupes d'utilisateurs et d'appareils.

-   Configuration de votre autorité de gestion des appareils mobiles (MDM) en fonction de vos besoins de gestion, notamment:

    -   Définition de Intune en tant qu'autorité MDM lorsque Intune est votre seule solution MDM ou qu'il est associé à la gestion des appareils mobiles pour Office 365.

-   Fourniture d'instructions MDM pour:

    -   Configuration des groupes de tests à utiliser pour valider les stratégies de gestion MDM.

    -   La configuration des services et des stratégies de gestion MDM comme:

        -   Déploiement d'applications pour chaque plateforme prise en charge par le biais de liens Web ou de liens détaillés.

        -   Stratégies d'accès conditionnel.

        -   Le déploiement de la messagerie, des réseaux sans fil et des profils de réseau privé virtuel (VPN) si vous disposez d'une autorité de certification, d'une infrastructure Wi-Fi ou VPN existante dans votre organisation.

        -   Configuration de Microsoft Intune Exchange Connector (le cas échéant).

        -   Connexion à l'entrepôt de données Intune

        -   Intégration de Intune à:
            -   Visionneuse d'équipe pour l'assistance à distance (l'abonnement Team Viewer est requis).

            -   Solutions de partenariat mobile Threat Defense (MTD) (mobile Threat Defense commun est requis).

            -   Solution de gestion des dépenses de téléCommunication (l'abonnement à une solution de gestion des dépenses de téléCommunication est requis).

            -   Windows Defender Advanced Threat Protection (Windows E5 ou Microsoft 365 E5 licences sont requises).

    -   L'inscriptions de périphériques de chaque [plateforme prise en charge](https://technet.microsoft.com/library/dn600287.aspx) sur Intune.

-   Fournir des conseils sur la protection des applications sur:

    -   La configuration des stratégies de protection des applications pour chaque plateforme prise en charge.

    -   La configuration des stratégies d'accès conditionnel pour les applications gérées.

    -   Ciblage des groupes d'utilisateurs appropriés avec les stratégies MAM ci-dessus.

    -   Utilisation des rapports d'utilisation des applications gérées.

-   Fournir des conseils de gestion de PC sur:

    -   Installation du logiciel client Intune (le cas échéant).

    -   À l'aide des rapports logiciels et matériels disponibles dans Intune.

    > [!IMPORTANT]
    > FastTrack ne prend pas en charge la gestion de PC classique de Windows 10 avec Intune. FastTrack prend uniquement en charge la gestion des appareils Windows 10 via la gestion des appareils mobiles Intune.

#### <a name="windows-autopilot"></a>Windows Autopilot

FastTrack peut vous aider à simplifier le provisionnement de votre appareil avec Windows AutoPilot et Intune en fournissant de nouveaux appareils à vos utilisateurs finaux sans avoir besoin de créer, maintenir et appliquer des images de système d'exploitation personnalisées à vos appareils.

FastTrack prend en charge les scénarios de pilote automatique suivants:

- **Self-service Azure ad:** Les appareils se joignent à Azure AD et s'inscrivent dans Intune. Ce scénario est pris en charge lors de l'utilisation de Windows 10 1703 et des versions ultérieures.

- **Self-service AAD hybride:** Les périphériques se joignent à la fois à l'AD local et à Azure AD et s'inscrivent dans Intune. Ce scénario est pris en charge lors de l'utilisation de Windows 10 1809 et des versions ultérieures.

- **Mise en service automatique:** Les appareils se joignent automatiquement à Azure AD. Ce scénario est pris en charge lors de l'utilisation de Windows 1809 et des versions ultérieures.

    > [!IMPORTANT]
    > FastTrack ne prend pas en charge les scénarios AutoPilot initiés depuis le gestionnaire de configuration.

Les étapes de configuration de Windows AutoPilot dépendent de votre environnement source et peuvent inclure les éléments suivants:

- ConFigurez et conFigurez Microsoft Intune pour Windows AutoPilot.

- Configurer des groupes dynamiques Azure AD

- Ajoutez votre marque de société dans Azure AD.

- Créez et affectez des appareils à des profils Windows AutoPilot (par exemple, un profil Windows AutoPilot qui limite la création de comptes d'administrateur local).

- Personnaliser l'OOBE (out-of-Box-Experience) afin de se conformer aux exigences de l'organisation.

- Configuration de l'enregistrement automatique MDM dans Azure AD et Intune.

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>Déployer Outlook pour iOS et Android de manière sécurisée

FastTrack peut vous aider en déployant Outlook pour iOS et Android de manière sécurisée dans votre organisation afin de s'assurer que toutes les applications requises sont installées sur vos utilisateurs.

Les étapes de déploiement sécurisé d'Outlook Mobile pour iOS et Android avec Intune dépendent de votre environnement source et peuvent inclure les éléments suivants:

- Téléchargez Outlook pour iOS et Android, Microsoft Authenticator et l'application portail d'entreprise Intune via le magasin d'applications Apple ou Google Play Store.
- Fournissez également des conseils sur la configuration des éléments suivants:
    - Outlook pour iOS et Android, Microsoft Authenticator et le déploiement d'application portail d'entreprise Intune avec Intune.
    - Stratégies de protection des applications
    - Stratégies d'accès conditionnel
    - Stratégies de configuration de l'application

    > [!IMPORTANT]
    > L'équipe FastTrack ne prend pas en charge la sécurisation d'Outlook pour iOS et Android avec les stratégies de boîte aux lettres d'appareils mobiles Exchange.

#### <a name="co-management"></a>Co-Management

FastTrack vous guide tout au long de la préparation de la gestion simultanée des appareils Windows 10 avec le gestionnaire de configuration et Intune. Les étapes exactes dépendent de votre environnement source et peuvent inclure les éléments suivants:

- Expliquez les avantages de la co-gestion.

- Accorder une licence aux utilisateurs finaux. FastTrack fournit également une assistance sur l'activation des licences en volume pour votre client de service Cloud Microsoft (si nécessaire).

- ConFigurez les identités à utiliser par Intune en tirant parti de votre annuaire Active Directory local et/ou des identités Cloud.

- L'ajout d'utilisateurs à votre abonnement Intune, la définition des rôles d'administrateur informatique et la création de groupes d'utilisateurs et d'appareils.

- Fournir des instructions sur la migration de Intune intégré avec System Center Configuration Manager (hybride) vers Intune en mode autonome.

- Fournir des conseils sur la configuration d'Azure Active Directory pour l'inscription automatique MDM.

- Fournir des conseils sur la configuration d'une jointure Azure Active Directory hybride.

- Fournir des conseils sur la configuration de la passerelle de gestion Cloud

- Activez la co-gestion dans la console Configuration Manager.

- ConFigurez les charges de travail prises en charge que vous souhaitez basculer vers Intune.

- Installez le client du gestionnaire de configuration dans les appareils apportés à Intune.

- Fournir des conseils sur la façon de surveiller l'activité de co-gestion dans votre environnement.

FastTrack vous fournit également des conseils sur la façon d'effectuer l'adoption des services éligibles.

![Phase d'activation de l'intégration-Intune](./media/ft-enable-phase_intune_mam.png)

![Phase d'activation de l'intégration-Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![Phase d'activation de l'intégration-co-gestion](./media/ft-9-enable-phase-comanagement.png)

> [!NOTE]
> **Vous souhaitez en savoir plus?** Voir [Enterprise Mobility + Security](https://www.microsoft.com/en-us/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Étapes suivantes

[Avantages de FastTrack pour EMS-responsabilités de Microsoft](EMS-fasttrack-responsibilities.md)

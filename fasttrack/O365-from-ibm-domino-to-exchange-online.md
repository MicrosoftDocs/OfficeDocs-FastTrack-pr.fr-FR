---
title: Annexe A  Migration d'IBM Domino vers Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 12/4/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: "De nombreux paramètres entrent en jeu dans la migration d'IBM Domino vers Exchange Online, notamment lors des phases suivantes :"
ms.openlocfilehash: 70151f726a2368d61262d540d77041cff21fa7c3
ms.sourcegitcommit: 3ecf2619868abc13716701393831dd0c24e00d9d
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/03/2018
ms.locfileid: "27133108"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="39b9e-103">Annexe A : Migration d’IBM Domino vers Exchange Online</span><span class="sxs-lookup"><span data-stu-id="39b9e-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="39b9e-104">De nombreux paramètres entrent en jeu dans la migration d'IBM Domino vers Exchange Online, notamment lors des phases suivantes :</span><span class="sxs-lookup"><span data-stu-id="39b9e-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="39b9e-105">Phase de lancement</span><span class="sxs-lookup"><span data-stu-id="39b9e-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="39b9e-106">Phase d'évaluation</span><span class="sxs-lookup"><span data-stu-id="39b9e-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="39b9e-107">Phase de correction</span><span class="sxs-lookup"><span data-stu-id="39b9e-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="39b9e-108">Phase d'activation</span><span class="sxs-lookup"><span data-stu-id="39b9e-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="39b9e-109">Phase de migration</span><span class="sxs-lookup"><span data-stu-id="39b9e-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="39b9e-110">Identités</span><span class="sxs-lookup"><span data-stu-id="39b9e-110">Identities</span></span>

<span data-ttu-id="39b9e-p101">Vous êtes responsable de la création et de la gestion des identités (cloud uniquement, synchronisées ou fédérées avec les instances Active Directory locales). Vous devez procéder au mappage des identités (si ce n'est pas déjà fait) entre Domino et l'instance locale d'Active Directory ou d'Azure AD au début du processus d'intégration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p101">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory). You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure AD during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="39b9e-113">Coexistence</span><span class="sxs-lookup"><span data-stu-id="39b9e-113">Coexistence</span></span>

<span data-ttu-id="39b9e-114">Les avantages du Centre FastTrack pour Office 365 fournissent des flux de messagerie bidirectionnelle entre l’environnement Domino local et Exchange Online pour tous les clients.</span><span class="sxs-lookup"><span data-stu-id="39b9e-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="39b9e-115">Migration</span><span class="sxs-lookup"><span data-stu-id="39b9e-115">Migration</span></span>

<span data-ttu-id="39b9e-p102">Le processus du Service FastTrack standard pour la migration de Domino à Exchange Online implique la préparation des données Domino dans Azure avant la migration vers les boîtes aux lettres Exchange Online. Les migrations FastTrack requièrent l'exécution de certaines opérations à différentes étapes de l'intégration par le personnel du Service FastTrack et vous. Nous abordons ces opérations dans les sections suivantes.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="39b9e-p103">Les données migrées par le biais des services FastTrack peuvent être transférées, stockées et traitées aux États-Unis ou dans n’importe quelle région du monde où Microsoft est implanté. Les services FastTrack ne sont pas conçus pour ni destinés à des données soumises à des exigences légales ou réglementaires particulières.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="39b9e-121">Phase de lancement</span><span class="sxs-lookup"><span data-stu-id="39b9e-121">Initiate phase</span></span>

 <span data-ttu-id="39b9e-122">**Actions principales**</span><span class="sxs-lookup"><span data-stu-id="39b9e-122">**Key actions**</span></span>
  
- <span data-ttu-id="39b9e-123">Définir Domino en tant que plateforme de messagerie source.</span><span class="sxs-lookup"><span data-stu-id="39b9e-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="39b9e-124">Déterminer si le Service FastTrack effectue la migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="39b9e-125">**Responsabilités du client**</span><span class="sxs-lookup"><span data-stu-id="39b9e-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="39b9e-126">Fournir des informations de base sur la plateforme de messagerie source, puis confirmer l’objectif de migration auprès du centre FastTrack.</span><span class="sxs-lookup"><span data-stu-id="39b9e-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="39b9e-127">Participer à une présentation détaillée des processus du service FastTrack.</span><span class="sxs-lookup"><span data-stu-id="39b9e-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="39b9e-128">Signer l’accord de Services FastTrack.</span><span class="sxs-lookup"><span data-stu-id="39b9e-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="39b9e-129">Phase d’évaluation</span><span class="sxs-lookup"><span data-stu-id="39b9e-129">Assess phase</span></span>

 <span data-ttu-id="39b9e-130">**Actions principales**</span><span class="sxs-lookup"><span data-stu-id="39b9e-130">**Key actions**</span></span>
  
- <span data-ttu-id="39b9e-131">Le Service FastTrack organise un atelier de migration avec le client.</span><span class="sxs-lookup"><span data-stu-id="39b9e-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="39b9e-132">Vous vous acquittez des formalités nécessaires à la migration, comme remplir le questionnaire de migration et approvisionner les stations de travail d’administration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="39b9e-133">Une évaluation de la migration pour Domino est effectuée dans votre environnement local.</span><span class="sxs-lookup"><span data-stu-id="39b9e-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="39b9e-134">**Responsabilités du client**</span><span class="sxs-lookup"><span data-stu-id="39b9e-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="39b9e-135">Approvisionner les stations de travail d’administration que le centre FastTrack utilise pour administrer les tâches de migration et d’intégration, comme les tâches d’évaluation, de création de réplicas, d’audit, de définition du transfert pendant la migration, etc.</span><span class="sxs-lookup"><span data-stu-id="39b9e-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="39b9e-p104">Les tâches d'évaluation sont essentielles pour la planification et l'exécution d'une migration à haute vitesse. Elles sont menées à bien par un architecte de migration qui nécessite un accès spécifique à l'environnement Domino. Les stations de travail d'administration doivent comprendre un client Notes configuré pour accéder à tous les serveurs de messagerie Domino sources et au serveur réplica intermédiaire Domino de Azure.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="39b9e-p105">Fournir à l'équipe de migration un accès à distance aux stations de travail d'administration, des comptes, ainsi que des autorisations pour lui permettre d'effectuer des tâches d'évaluation et de migration. Cela comprend le provisionnement de plusieurs comptes dotés des autorisations d'administration nécessaires à la migration, à la fois en local et dans Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="39b9e-p106">Ouvrir les ports de pare-feu. Les ports sortants doivent être ouverts entre les serveurs de messagerie Domino sources et le serveur intermédiaire Azure. D'autres ports de communication doivent également être ouverts (par exemple pour les stations de travail d'administration, les serveurs Domino sources et les serveurs Exchange locaux (le cas échéant)).</span><span class="sxs-lookup"><span data-stu-id="39b9e-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="39b9e-p107">Activer la certification croisée entre l'environnement Domino source et le serveur intermédiaire Domino de Azure pour faciliter la réplication. Les tâches de certification croisée sont coordonnées entre l'administrateur Domino du client et le Service FastTrack.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="39b9e-146">Remplir le questionnaire de migration, qui collecte les informations requises pour configurer l’environnement de migration dans Azure (comme les outils, les scripts et les serveurs de migration).</span><span class="sxs-lookup"><span data-stu-id="39b9e-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="39b9e-147">Vous assurer que le protocole MAPI (Messaging Application Program Interface) est activé sur les boîtes aux lettres cibles dans Office 365.</span><span class="sxs-lookup"><span data-stu-id="39b9e-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="39b9e-p108">Certains plans Office 365 ne prennent pas en charge le protocole MAPI. Pour migrer des données, les boîtes aux lettres provenant de ces plans doivent être converties en un plan prenant en charge le protocole MAPI avant l'événement de migration. Après la migration, ces plans peuvent être rétablis.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="39b9e-151">Phase de correction</span><span class="sxs-lookup"><span data-stu-id="39b9e-151">Remediate phase</span></span>

 <span data-ttu-id="39b9e-152">**Actions principales**</span><span class="sxs-lookup"><span data-stu-id="39b9e-152">**Key actions**</span></span>
  
- <span data-ttu-id="39b9e-153">Le Service FastTrack examine le rapport d'évaluation de migration et effectue des tests avec les détails que vous fournissez dans le questionnaire.</span><span class="sxs-lookup"><span data-stu-id="39b9e-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="39b9e-154">Il vous revient de prendre les mesures de correction suggérées par le centre FastTrack.</span><span class="sxs-lookup"><span data-stu-id="39b9e-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="39b9e-155">**Responsabilités du client**</span><span class="sxs-lookup"><span data-stu-id="39b9e-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="39b9e-156">Mettre à jour l’environnement Domino en suivant les directives du centre FastTrack (par exemple, définir les autorisations requises qui apparaissent comme manquantes dans les fichiers de messagerie).</span><span class="sxs-lookup"><span data-stu-id="39b9e-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="39b9e-157">Vérifier que les boîtes aux lettres Domino respectent la taille maximale autorisée lors de la migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="39b9e-158">Bien que FastTrack ne migre les boîtes aux lettres que jusqu’à 85 % de la taille cible totale admise, la migration de boîtes aux lettres de plus de 2 Go comporte des risques supplémentaires, comme les suivants :</span><span class="sxs-lookup"><span data-stu-id="39b9e-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="39b9e-p109">Migration plus longue.    </span><span class="sxs-lookup"><span data-stu-id="39b9e-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="39b9e-p110">Mobilisation de ressources qui seraient sinon utilisées pour la migration des autres boîtes aux lettres.    </span><span class="sxs-lookup"><span data-stu-id="39b9e-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="39b9e-161">Augmentation considérable du taux d’erreur.</span><span class="sxs-lookup"><span data-stu-id="39b9e-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="39b9e-p111">Préparation des bases de données de messagerie et des listes de contrôle d'accès associées pour la migration. Vous devez prendre certaines mesures correctives pour pouvoir migrer des bases de données de messagerie et les autorisations associées vers une boîte aux lettres partagée dans Exchange Online. Voici quelques exemples de ces mesures :</span><span class="sxs-lookup"><span data-stu-id="39b9e-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="39b9e-165">Supprimer des entrées de base de données de messagerie existantes du répertoire Domino et créer des enregistrements de personnes.</span><span class="sxs-lookup"><span data-stu-id="39b9e-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="39b9e-p112">Créer des groupes de sécurité universels à extension messagerie sur les instances Active Directory locales qui sont synchronisées avec Office 365 Azure AD et utilisées pour configurer des autorisations sur la boîte aux lettres partagée dans Exchange Online. Cette action transfère les autorisations définies sur la base de données de messagerie vers la boîte aux lettres partagée dans Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p112">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure AD and used to configure permissions on the shared mailbox in Exchange Online. This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="39b9e-168">Vous pouvez entamer les opérations de préparation de l’utilisateur final et de formation au nouveau client/système de messagerie à ce stade.</span><span class="sxs-lookup"><span data-stu-id="39b9e-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="39b9e-169">Phase d’activation</span><span class="sxs-lookup"><span data-stu-id="39b9e-169">Enable phase</span></span>

 <span data-ttu-id="39b9e-170">**Actions principales**</span><span class="sxs-lookup"><span data-stu-id="39b9e-170">**Key actions**</span></span>
  
- <span data-ttu-id="39b9e-171">Le service FastTrack :</span><span class="sxs-lookup"><span data-stu-id="39b9e-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="39b9e-172">Configure l’environnement de migration dans Azure.</span><span class="sxs-lookup"><span data-stu-id="39b9e-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="39b9e-173">Configure les outils de migration sur les stations de travail d’administration locales.</span><span class="sxs-lookup"><span data-stu-id="39b9e-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="39b9e-174">Configure l’outil d’importation automatique et vous montre comment l’utiliser.</span><span class="sxs-lookup"><span data-stu-id="39b9e-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="39b9e-175">Effectue la validation de tous les composants de migration et effectue des migrations de test.</span><span class="sxs-lookup"><span data-stu-id="39b9e-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="39b9e-176">**Responsabilités du client**</span><span class="sxs-lookup"><span data-stu-id="39b9e-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="39b9e-p113">Vos équipes responsables de la planification de la migration des boîtes aux lettres doivent savoir utiliser l'outil d'importation automatique. Cet outil vous permet d'importer le plan de migration dans la base de données de planification, qui est utilisée par le Service FastTrack pour exécuter certaines tâches préalables à la migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="39b9e-179">Effectuer des tâches préalables à la migration, telles que l’importation des planifications utilisateur, l’analyse des rapports d’audit, la correction des problèmes et la réimportation des comptes d’utilisateur présentant des problèmes.</span><span class="sxs-lookup"><span data-stu-id="39b9e-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="39b9e-p114">Les activités précédant la migration sont coordonnées entre vous et le Centre FastTrack. La réplication vers Azure commence après l’importation de la planification de migration utilisateur.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="39b9e-p115">Les délais de réplication dépendent du volume de données. Le Service FastTrack effectue ensuite un audit pour déterminer si votre environnement est prêt pour la migration. Les résultats de l'audit vous sont fournis afin que vous puissiez prendre les mesures correctives généralement nécessaires. Toutes ces activités sont appelées « T-moins », car elles doivent commencer avant la migration planifiée par les utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="39b9e-186">Phase de migration</span><span class="sxs-lookup"><span data-stu-id="39b9e-186">Migrate phase</span></span>

 <span data-ttu-id="39b9e-187">**Actions principales**</span><span class="sxs-lookup"><span data-stu-id="39b9e-187">**Key actions**</span></span>
  
- <span data-ttu-id="39b9e-188">Le service FastTrack :</span><span class="sxs-lookup"><span data-stu-id="39b9e-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="39b9e-189">Effectue des migrations pilote et de rapidité.</span><span class="sxs-lookup"><span data-stu-id="39b9e-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="39b9e-190">Exécute des événements de migration et des activités T-moins.</span><span class="sxs-lookup"><span data-stu-id="39b9e-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="39b9e-191">Fournit une assistance après la migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="39b9e-192">**Responsabilités du client**</span><span class="sxs-lookup"><span data-stu-id="39b9e-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="39b9e-193">Déterminer et importer les plans de migration 21 jours avant la migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="39b9e-p116">Cette tâche est essentielle, car les activités préalables à la migration impliquent des tâches de correction et de nouvelles tentatives de création de réplicas à différents moments précédant le jour de la migration réelle (T-0). Pendant la migration de certaines boîtes aux lettres, les activités T-moins sont effectuées sur les autres. Aussi, une planification et une coordination optimales sont indispensables.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="39b9e-197">Corriger les problèmes repérés au cours des activités T-moins.</span><span class="sxs-lookup"><span data-stu-id="39b9e-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="39b9e-198">Corriger tout problème de serveur Domino ayant un impact sur les activités de migration.</span><span class="sxs-lookup"><span data-stu-id="39b9e-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="39b9e-199">Informer l’utilisateur final de la date de la migration à venir.</span><span class="sxs-lookup"><span data-stu-id="39b9e-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="39b9e-200">Mener des activités de formation au nouveau client/système de messagerie et de préparation de l’utilisateur final.</span><span class="sxs-lookup"><span data-stu-id="39b9e-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="39b9e-p117">Repérer et signaler les problèmes survenus à l'issue de la migration. Le Service FastTrack offre une assistance post-migration pendant les cinq jours suivant la migration, après quoi la résolution des problèmes passe sous votre responsabilité. Vous pouvez soumettre des tickets post-migration pour des problèmes comme l'absence de certains messages électroniques, éléments de calendrier et contacts, ou en cas de doublons dans la boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="39b9e-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="39b9e-204">Le Service FastTrack ne prend pas en charge les tâches de déploiement, de facturation de licences ou d'assistance associées à la préparation d'annuaires (y compris la synchronisation d'annuaires de Domino vers Active Directory), aux modules complémentaires des logiciels de coexistence pour l'interopérabilité des applications Notes, à la migration en libre-service ou à la migration des archives.</span><span class="sxs-lookup"><span data-stu-id="39b9e-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  


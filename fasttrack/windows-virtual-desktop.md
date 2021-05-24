---
title: Windows Virtual Desktop
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack fournit des Windows de déploiement virtual desktop pour vous aider à intégrer ce bureau.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592437"
---
# <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Détails des conseils FastTrack</strong></th>
<th><strong>Attente concernant l'environnement source</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows Virtual Desktop</td>
<td><p>FastTrack fournit des conseils de déploiement de bureau virtuel Windows pour vous aider à intégrer ce service de virtualisation de bureau et d’application en toute simplicité tout en profitant de l’expérience multisesses Windows 10, optimisée pour Microsoft 365 Apps pour Enterprise avec une sécurité et une gestion intégrées pour Microsoft 365.</p>
<p>Vous collaborez avec des spécialistes FastTrack pour :</p>
<ul>
<li><p>Déployez l’environnement WVD Windows 10 Entreprise multisessage + Microsoft 365 Apps pour Enterprise à l’aide des outils suivants :</p>
<ul>
<li><p>Azure Marketplace Image</p></li>
<li><p>Image partagée</p></li>
<li><p>Office Déploiement Shared Computer Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurer FSLogix</p>
<ul>
<li><p>Déployer l’agent FSLogix avec le conteneur de profils</p></li>
<li><p>Déployer l’agent FSLogix avec Office conteneur</p></li>
<li><p>Configurer le dossier FSLogix avec des exclusions de contenu</p></li>
</ul></li>
<li><p>Déployer Microsoft Edge</p></li>
<li><p>Déployer Microsoft Teams</p></li>
<li><p>Connecter’utilisation Windows clients Virtual Desktop</p></li>
</ul>
<p><strong>Ce qui suit est hors de portée</strong></p>
<ul>
<li><p>Project gestion du déploiement Windows Virtual Desktop du client.</p></li>
<li><p>Support sur site.</p></li>
<li><p>Virtualisation/déploiement d’applications tierces.</p></li>
<li><p>Images personnalisées.</p></li>
<li><p>Migrations et scénarios impliquant VMware et Citrix.</p></li>
<li><p>Scénarios Linux.</p></li>
<li><p>Conversion ou migrations de profils utilisateur.</p></li>
</ul>
<p>Contactez un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partenaire Microsoft pour</a> obtenir de l’aide sur ces services.</p></td>
<td><p>Vous devez déjà avoir les choses suivantes :</p>
<ul>
<li><p>[Conditions requises pour les licences WVD](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Mise en réseau Azure :</p>
<ul>
<li><p>Sous-réseau de création VNET &amp;</p></li>
<li><p>Pare-feu/ Groupes de sécurité réseau</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Routage vers Azure à partir d’un site local</p></li>
<li><p>Règles de pare-feu pour autoriser la connectivité à WVD</p>
<ul>
<li><p>[Référence de documents](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Configuration générale</p>
<ul>
<li><p>Stratégie <strong>d’identité (sélectionnez uniquement 1 des 3 options suivantes)</strong></p>
<ul>
<li><p>Active Directory avec Azure AD Connecter azure</p></li>
<li><p>Active Directory avec Azure AD Connecter local sur VPN/ER</p></li>
<li><p>Services de domaine Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

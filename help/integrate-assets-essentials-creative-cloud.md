---
title: Intégration d’Assets Essentials à des applications Creative Cloud
description: Intégration d’Assets Essentials à des applications Creative Cloud afin que vous puissiez utiliser le panneau intégré Adobe Asset Link pour vous connecter à [!DNL Assets Essentials] du référentiel pris en charge ; [!DNL Adobe Creative Cloud] applications de bureau.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 5%

---


# Intégration d’Assets Essentials à des applications Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-creative-cloud.png)

## L&#39;histoire jusqu&#39;à présent

Après [configuration de Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) dans ce tutoriel, vous pouvez tirer parti de l’expérience pour intégrer les applications de Creative Cloud à Assets Essentials.

## Objectif

* **Audience**: Creative Cloud administrators

* **Objective**: Integrate Assets Essentials with Creative Cloud applications so that your creative users can use Adobe Asset link in-app panel to connect to [!DNL Assets Essentials] repository from within the supported [!DNL Adobe Creative Cloud] desktop applications.

## Présentation

[Adobe du panneau intégré à Asset Link](https://www.adobe.com/fr/creativecloud/business/enterprise/adobe-asset-link.html) permet aux professionnels de la création de se connecter à [!DNL Assets Essentials] du référentiel pris en charge ; [!DNL Adobe Creative Cloud] applications de bureau. Le panneau est disponible pour [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] et [!DNL Adobe XD]. It streamlines access to assets, which in turn helps increase content velocity.

Creative Cloud application users can use the Adobe Asset Link in-app panel only when you integrate the Creative Cloud applications with the Experience Manager Assets Essentials repository.

Exécutez les tâches suivantes pour intégrer Assets Essentials à des applications Creative Cloud :

* [Create directory trusting between Creative Cloud and Experience Cloud Admin Console](#directory-trusting-cc-assets-essentials-consoles)

* [Add Creative Cloud users to Assets Essentials product profiles](#add-cc-users-assets-essentials-product-profiles)

* [Installation d’Adobe Asset Link](#install-asset-link)

* [Utilisation d’Adobe Asset Link](#use-asset-link)

## Création d’une confiance d’annuaire entre les Admin Console Creative Cloud et Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Si votre Creative Cloud est déployé dans une console d’administration d’Adobe distincte de celle avec Assets Essentials (solution Experience Cloud), vous devez ajouter une relation de confiance entre les deux consoles.

Pour intégrer des applications Creative Cloud et Assets Essentials, les utilisateurs disponibles dans Admin Console pour Creative Cloud doivent être disponibles dans Admin Console pour Experience Cloud. Si Creative Cloud et Assets Essentials sont déployés dans des Admin Console distincts, une relation de confiance entre eux est requise pour activer cette fonctionnalité.

Sur le Admin Console Experience Cloud, cliquez sur **[!UICONTROL Paramètres]** et utilisez la fonction **[!UICONTROL Répertoires]** pour créer un répertoire à établir [confiance du répertoire](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) entre les deux Admin Console.

## Ajout d’utilisateurs Creative Cloud à des profils de produit Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

After establishing directory trusting between the Admin Console for Creative Cloud and Admin Console for Experience Cloud, assign the Creative Cloud users to the **[!DNL Assets Essentials]Users** product profile under the [!DNL Assets Essentials] product card in the Experience Cloud Admin Console. It will let Creative Cloud users to access Assets Essentials from their Adobe Asset Link plugin panel; in addition, it will give them access to the full Assets Essentials web User Interface to upload, organize, tag and find digital assets using a web browser.

Other Assets Essentials product profiles - **[!DNL Assets Essentials]Administrators** and **[!DNL Assets Essentials]Consumer Users** - are used for different user entitlements (application administrators and users accessing Assets Essentials via Experience Cloud integrations).

For more information on how to assign users to Assets Essentials product profiles, see [Assign users to Assets Essentials product profiles](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Installation d’Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] plugin can be installed and made available to creative users in two ways:

* Les utilisateurs créatifs peuvent installer le module externe à partir de leur [!DNL Creative Cloud Desktop] application
* Creative Cloud administrator can add Asset Link plugin to a Creative Cloud package in Admin Console

Le choix dépend des stratégies informatiques de l’entreprise.

**Installation à l’aide de [!DNL Creative Cloud Desktop] application** est décrit [here](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Deux modules externes sont disponibles et hébergés sur [Adobe Exchange](https://exchange.adobe.com/) Marketplace, en fonction de l’application Creative Cloud :

* For [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], and [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Pour [!DNL Adobe XD]: [Adobe d’un lien de ressource](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installation with a Creative Cloud package** is done by Creative Cloud administrator in Admin Console, by including the Asset Link plugin when building a deployment package, that can later be deployed to user machines. Dans l’écran Sélection de modules externes géré, recherchez **Adobe d’un lien de ressource** dans le **Plug-ins d’entreprise proposés** . Pour plus d’informations, voir [emballage des applications via le Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Utilisation d’Adobe Asset Link {#use-asset-link}

Les utilisateurs créatifs peuvent désormais utiliser Adobe Asset Link avec Photoshop, Illustrator, InDesign ou XD. To open the panel in InDesign or Illustrator, go to Windows > Extensions > Adobe Asset Link. Dans Photoshop, accédez à Window > Extensions (hérité) > Adobe Asset Link.

Pour plus d’informations sur la configuration d’Adobe Asset Link pour Adobe XD, cliquez sur [here](https://helpx.adobe.com/fr/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>When working on Apple Silicon / M1 hardware, Adobe Photoshop needs to be started using Rosetta compatibility mode to ensure creative users have access to Adobe Asset Link panel, as it is built using the CEP extension technology. Pour plus d’informations, voir [Photoshop pour Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Utilisez Adobe Asset Link pour utiliser et modifier des ressources stockées dans le référentiel Assets Essentials. Vous pouvez effectuer diverses tâches, telles que :

* Recherche et navigation dans les ressources

* Charger des ressources

* Tri et filtrage des ressources

* Placer, télécharger et faire glisser une ressource

* Check out and Check in an asset

* Affichage de l’historique des versions et des détails sur les fichiers

For instructions on how to perform these tasks, see [Manage assets using Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Prochaines étapes

Now that you have  integrated the Creative Cloud applications with Assets Essentials, [integrate Adobe Workfront with Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).

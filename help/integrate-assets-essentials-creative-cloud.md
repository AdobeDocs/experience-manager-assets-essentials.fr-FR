---
title: Intégration d’Assets Essentials aux applications Creative Cloud
description: Intégrer Assets Essentials aux applications Creative Cloud afin que vous puissiez utiliser le panneau in-app Adobe Asset Link pour vous connecter au référentiel  [!DNL Assets Essentials]  depuis les applications de bureau  [!DNL Adobe Creative Cloud]  prises en charge.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 268b7eb82b15b658207f24750eeae085ce5bb3d4
workflow-type: ht
source-wordcount: '854'
ht-degree: 100%

---

# Intégration d’Assets Essentials aux applications Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-creative-cloud.png)

## Un peu d’histoire…

Après la [configuration d’Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) dans ce tutoriel, vous pouvez vous appuyer sur cette expérience pour intégrer les applications Creative Cloud avec Assets Essentials.

## Objectif

* **Audience** : administrateurs de Creative Cloud

* **Objectif** : Intégrez Assets Essentials aux applications Creative Cloud afin que vos utilisateurs créatifs puissent utiliser le panneau in-app Adobe Asset Link pour se connecter au référentiel [!DNL Assets Essentials] depuis les applications de bureau [!DNL Adobe Creative Cloud] prises en charge.

## Présentation

Le [panneau in-app Adobe Asset Link](https://www.adobe.com/fr/creativecloud/business/enterprise/adobe-asset-link.html) permet aux professionnels de la création de se connecter au référentiel [!DNL Assets Essentials] à partir des applications de bureau [!DNL Adobe Creative Cloud] prises en charge. Le panneau est disponible pour [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] et [!DNL Adobe XD]. Elle rationalise l’accès aux ressources, ce qui contribue à accroître la vitesse du contenu.

Les utilisateurs des applications Creative Cloud peuvent utiliser le panneau in-app Adobe Asset Link uniquement lorsque vous intégrez les applications Creative Cloud au référentiel Experience Manager Assets Essentials.

Exécutez les tâches suivantes pour intégrer Assets Essentials aux applications Creative Cloud :

* [Créer une confiance de répertoire entre Creative Cloud et Experience Cloud Admin Console.](#directory-trusting-cc-assets-essentials-consoles)

* [Ajouter les utilisateurs Creative Cloud aux profils de produits Assets Essentials.](#add-cc-users-assets-essentials-product-profiles)

* [Installez Adobe Asset Link.](#install-asset-link)

* [Utilisation d’Adobe Asset Link](#use-asset-link)

## Créer un répertoire de confiance entre Creative Cloud et Experience Cloud Admin Consoles {#directory-trusting-cc-assets-essentials-consoles}

Si votre Creative Cloud est déployé dans une Adobe Admin Console distincte de celle d’Assets Essentials (solution Experience Cloud), vous devez ajouter une relation de confiance entre les deux consoles.

Pour intégrer les applications Creative Cloud et Assets Essentials, les utilisateurs qui sont disponibles dans Admin Console for Creative Cloud doivent être disponibles dans Admin Console for Experience Cloud. Si Creative Cloud et Assets Essentials sont déployés dans des Admin Console distincts, une relation de confiance entre eux est nécessaire pour activer cette fonctionnalité.

Sur l’Admin Console Experience Cloud, cliquez sur **[!UICONTROL Paramètres]** et utilisez l’onglet **[!UICONTROL Répertoires]** pour créer un répertoire afin d’établir la [confiance de répertoire](https://helpx.adobe.com/fr/enterprise/using/set-up-identity.html) entre les deux Admin Console.

## Ajouter les utilisateurs Creative Cloud aux profils de produits Assets Essentials. {#add-cc-users-assets-essentials-product-profiles}

Après avoir établi la confiance de répertoires entre Admin Console for Creative Cloud et Admin Console for Experience Cloud, affectez les utilisateurs de Creative Cloud au profil de produit Utilisateurs d’**[!DNL Assets Essentials]** sous la vignette produit [!DNL Assets Essentials] dans l’Admin Console Experience Cloud. Cela permettra aux utilisateurs de Creative Cloud d’accéder à Assets Essentials à partir de leur panneau de plug-in Adobe Asset Link ; en outre, cela leur donnera accès à l’interface utilisateur web complète d’Assets Essentials pour charger, organiser, baliser et rechercher des ressources numériques à l’aide d’un navigateur web.

Autres profils de produit Assets Essentials - Administrateurs **[!DNL Assets Essentials]** et Utilisateurs consommateurs **[!DNL Assets Essentials]** - sont utilisés pour différents droits d’utilisateurs (administrateurs d’applications et utilisateurs accédant à Assets Essentials via des intégrations Experience Cloud).

Pour plus d’informations sur l’attribution d’utilisateurs à des profils de produit Assets Essentials, voir [Affecter des utilisateurs aux profils de produit Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Installez Adobe Asset Link. {#install-asset-link}

Le plug-in [!DNL Adobe Asset Link] peut être installé et mis à la disposition des utilisateurs créatifs de deux manières :

* Les utilisateurs créatifs peuvent installer le plug-in depuis de leur application [!DNL Creative Cloud Desktop].
* L’administrateur de Creative Cloud peut ajouter le plug-in Asset Link à un module de Creative Cloud dans Admin Console.

Le choix dépend des politiques informatiques de l’entreprise.

**L’installation à l’aide de l’application [!DNL Creative Cloud Desktop]** est décrite [ici](https://helpx.adobe.com/fr/creative-cloud/kb/installingextensionsandaddons.html). Il existe deux plug-ins disponibles et hébergés sur [Adobe Exchange](https://exchange.adobe.com/) Marketplace, en fonction de l’application Creative Cloud :

* Pour [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], et [!DNL Adobe InDesign] : [CEP d’Adobe Asset Link](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Pour [!DNL Adobe XD] : [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**L’installation avec un module Creative Cloud** est effectuée par l’administrateur Creative Cloud dans l’Admin Console, en incluant le plug-in Asset Link lors de la création d’un module de déploiement, qui peut ensuite être déployé sur les ordinateurs des utilisateurs. Dans l’écran de choix des plug-ins géré, recherchez **Adobe Asset Link** dans la section **Plug-ins d’entreprise proposés**. Pour plus d’informations, reportez-vous à [Conditionner des applications via l’Admin Console](https://helpx.adobe.com/fr/enterprise/using/package-apps-admin-console.html).

## Utilisation d’Adobe Asset Link {#use-asset-link}

Les utilisateurs créatifs peuvent désormais utiliser Adobe Asset Link avec Photoshop, Illustrator, InDesign ou XD. Pour ouvrir le panneau dans InDesign ou Illustrator, accédez à Fenêtre > Extensions > Adobe Asset Link. Dans Photoshop, accédez à Fenêtre > Extensions (hérité) > Adobe Asset Link.

Pour savoir comment configurer Adobe Asset Link pour Adobe XD, cliquez [ici](https://helpx.adobe.com/fr/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Lorsque vous travaillez sur du matériel Apple Silicon/M1, Adobe Photoshop doit être lancé en mode de compatibilité Rosetta afin de garantir aux utilisateurs créatifs l’accès au panneau Adobe Asset Link, car celui-ci est conçu à l’aide de la technologie d’extension CEP. Pour plus d’informations, voir [Photoshop pour Apple Silicon](https://helpx.adobe.com/fr/photoshop/kb/photoshop-for-apple-silicon.html).


Utilisez Adobe Asset Link pour travailler avec les ressources stockées dans le référentiel Assets Essentials et les modifier. Vous pouvez effectuer diverses tâches, telles que :

* Rechercher et parcourir des ressources.

* Charger des ressources

* Trier et filtrer des ressources.

* Placer, télécharger et faire glisser une ressource.

* Extraire et archiver une ressource.

* Afficher l’historique des versions et les détails des fichiers.

Pour obtenir des instructions sur l’exécution de ces tâches, consultez la section [Gérer les ressources à l’aide d’Adobe Asset Link](https://helpx.adobe.com/fr/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Prochaines étapes

Maintenant que vous avez intégré les applications Creative Cloud à Assets Essentials, [Intégrez Adobe Workfront à Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).

---
title: Gestion des collections
description: Une collection est un ensemble de ressources dans Experience Manager Assets Essentials. Vous pouvez utiliser des collections pour partager des ressources entre utilisateurs.
exl-id: 33c889f5-c989-4772-9591-db62f50e5c80
source-git-commit: f273e1e3c8a290e0beee0423da00c63013062c43
workflow-type: tm+mt
source-wordcount: '686'
ht-degree: 76%

---

# Gestion des collections {#manage-collections}

Une collection est un ensemble de ressources dans Experience Manager Assets Essentials. Vous pouvez utiliser des collections pour partager des ressources entre utilisateurs.

Contrairement aux dossiers, une collection peut comporter des ressources provenant de différents emplacements.

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

Vous pouvez partager plusieurs collections avec un utilisateur. Chaque collection contient des références aux ressources. L’intégrité du référentiel des ressources est préservée dans les collections.

![Collections](assets/collections.png)

Vous pouvez effectuer les tâches suivantes pour gérer et utiliser les collections :

* [Création d’une collection](#create-collection)

* [Ajout de ressources à une collection](#add-assets-to-collection)

* [Supprimer les ressources d’une collection](#remove-assets-from-collection)

* [Affichage et modification des métadonnées](#view-edit-collection-metadata)

* [Téléchargement d’une collection](#download-collection)

* [Suppression d’une collection](#delete-collection)

## Création d’une collection {#create-collection}

Pour créer une collection :

1. Cliquez sur **[!UICONTROL Collections]** dans le rail de gauche, puis cliquez sur **[!UICONTROL Créer une collection]**.

1. Entrez un titre et éventuellement une description pour la collection.

1. Sélectionnez cette option si vous devez créer une collection privée ou publique. Une collection publique est disponible pour l’affichage et la modification pour tous les utilisateurs. Cependant, une collection privée est disponible pour le créateur et les utilisateurs disposant de droits d’administrateur.

1. Cliquez sur **[!UICONTROL Enregistrer]** pour créer la collection.

![Créer une collection](assets/create-collection.png)

<!--
   
   for viewing and editing only to users with the appropriate [permissions](#manage-collection-access).

-->

## Ajout de ressources à une collection {#add-assets-to-collection}

Pour ajouter des ressources à une collection :

1. Cliquez sur **[!UICONTROL Ressources]** dans le rail de gauche et sélectionnez la ou les ressources.

1. Cliquez sur **[!UICONTROL Ajouter à la collection]**.

1. Dans la boîte de dialogue des [!UICONTROL Collections], sélectionnez les collections pour ajouter les ressources sélectionnées.

1. Cliquez sur **[!UICONTROL Ajouter]** pour ajouter la ressource aux collections sélectionnées.

Pour ajouter des ressources à une collection, vous pouvez également cliquer sur **[!UICONTROL Collections]** dans le rail de gauche, cliquez sur la collection à laquelle ajouter des ressources, puis sur **[!UICONTROL Ajouter à la collection]**, sélectionnez la ou les ressources, puis cliquez sur **[!UICONTROL Sélectionner]**.

## Création d’une collection dynamique {#create-smart-collection}

Enregistrez les résultats de recherche en tant que collection dynamique pour mettre à jour dynamiquement le contenu de la collection. Si des ressources sont ajoutées au référentiel Assets Essentials qui correspondent aux critères de recherche définis lors de la création de la collecte dynamique, le contenu de la collecte dynamique est automatiquement mis à jour.

Pour créer une collection dynamique :

1. Cliquez sur **[!UICONTROL Filtrer]** et [définir les critères de recherche ;](search.md##refine-search-results).

1. Cliquez sur **[!UICONTROL Enregistrer sous]** puis sélectionnez **[!UICONTROL Collecte dynamique]**.

1. Sur le [!UICONTROL Création d’une collection dynamique] , spécifiez un titre et une description pour la collecte dynamique.

1. Sélectionner **[!UICONTROL Collection publique]** si vous avez besoin que tous les utilisateurs accèdent à la collection. Sélectionner **[!UICONTROL Collection privée]** si vous avez besoin d’un groupe limité d’utilisateurs pour accéder à la collection.

1. Cliquez sur **[!UICONTROL Créer]** pour créer la collection dynamique.

![Création d’une collection dynamique](assets/create-smart-collection.png)


## Suppression de ressources d’une collection {#remove-assets-from-collection}

Pour supprimer des ressources d’une collection :

1. Cliquez sur **[!UICONTROL Collections]** dans le rail de gauche pour afficher la liste des collections.

1. Cliquez sur la collection et sélectionnez la ou les ressources à supprimer de la collection.

1. Cliquez sur **[!UICONTROL Supprimer]**.

<!--

## Manage access to a Private collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

-->

<!--

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## Affichage et modification des métadonnées {#view-edit-collection-metadata}

Les métadonnées de collection comprennent des informations sur la collection, telles que le titre et la description.

Pour afficher et modifier les métadonnées :

1. Cliquez sur **[!UICONTROL Collections]** dans le rail de gauche, sélectionnez une collection, puis cliquez sur **[!UICONTROL Détails]**.
1. Affichez les métadonnées de la collection à l’aide de l’onglet **[!UICONTROL De base]**.
1. Modifiez les champs de métadonnées selon les besoins. Vous pouvez modifier les champs [!UICONTROL Titre], [!UICONTROL Description] et [!UICONTROL Auteur].

![Métadonnées de collection](assets/collection-metadata.png)

## Partage de liens vers des collections {#share-collection-links}

[!DNL Assets Essentials] vous permet de générer un lien et de partager des collections de ressources avec des destinataires externes qui n’ont pas accès à l’application [!DNL Assets Essentials]. Vous pouvez définir une date d’expiration pour le lien, puis le partager avec d’autres utilisateurs en utilisant votre méthode de communication préférée, comme les e-mails ou les services de messagerie. Les destinataires du lien peuvent prévisualiser les ressources et les télécharger.

![Partager les liens pour les ressources](assets/share-link-collections.png)

Pour plus d’informations sur le partage de liens de collection avec des destinataires externes, consultez [Partager les liens vers des ressources](share-links-for-assets.md).

## Télécharger une collection {#download-collection}

Pour télécharger une collection :

1. Cliquez sur **[!UICONTROL Collections]** dans le rail de gauche.

1. Sélectionnez la collection à télécharger, puis cliquez sur **[!UICONTROL Télécharger]**.

1. Dans la boîte de dialogue [!UICONTROL Télécharger la ressource], cliquez sur **[!UICONTROL OK]**.

La collection est téléchargée en tant que fichier .ZIP sur votre ordinateur local.

## Suppression d’une collection {#delete-collection}

Pour supprimer une collection, procédez comme suit :

1. Cliquez sur **[!UICONTROL Collections]** dans le rail de gauche.

1. Sélectionnez la collection que vous devez supprimer.

1. Cliquez sur **[!UICONTROL Supprimer]**.

## Étapes suivantes {#next-steps}

* Faites des commentaires sur le produit en utilisant l’option [!UICONTROL Commentaires] disponible dans l’interface utilisateur d’Assets Essentials.

* Faites des commentaires sur la documentation en utilisant l’option [!UICONTROL Modifier cette page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Enregistrer un problème] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contactez l’[assistance clientèle](https://experienceleague.adobe.com/?support-solution=General&amp;lang=fr#support).

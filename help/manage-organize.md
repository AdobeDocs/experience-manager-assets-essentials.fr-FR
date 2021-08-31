---
title: Gérer vos ressources numériques
description: Déplacez, supprimez, copiez, renommez, mettez à jour et gérez la version de vos ressources dans  [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 95%

---


# Gestion des ressources {#manage-assets}

Vous pouvez effectuer facilement de nombreuses tâches de gestion des actifs numériques (DAM) grâce à l’interface conviviale d’[!DNL Assets Essentials]. Une fois les ressources ajoutées, vous pouvez les rechercher, les télécharger, les déplacer, les copier, les renommer, les supprimer, les mettre à jour et les modifier.

Utilisez [!DNL Assets Essentials] pour accomplir les tâches de gestion des ressources suivantes. Lorsque vous sélectionnez une ressource, les options suivantes s’affichent dans la barre d’outils supérieure.

![Options de la barre d’outils lors de la sélection d’une ressource](assets/toolbar-image-selected.png)

*Image : options disponibles dans la barre d’outils lors de la sélection d’une image.*

* ![Icône Désélectionner](assets/do-not-localize/close-icon.png) Désélectionne la sélection.
* ![Icône Détails](assets/do-not-localize/edit-in-icon.png) Cliquez pour prévisualiser une ressource et afficher le détail des métadonnées. Lors de la prévisualisation, vous pouvez afficher les versions et modifier une image.
* ![Icône Télécharger](assets/do-not-localize/download-icon.png) Téléchargez la ressource sélectionnée vers votre système de fichiers local.
* ![Icône Supprimer](assets/do-not-localize/delete-icon.png) Supprimez la ressource ou le dossier sélectionné.
* ![checkout ](assets/do-not-localize/checkout-icon.png) iconExtraction de la ressource sélectionnée.
* ![Icône Copier](assets/do-not-localize/copy-icon.png) Copiez le fichier ou le dossier sélectionné.
* ![Icône Déplacer](assets/do-not-localize/move-icon.png) Déplacez la ressource ou le dossier sélectionné vers un autre emplacement de la hiérarchie du référentiel.
* ![Icône renommer](assets/do-not-localize/rename-icon.png) Renommez la ressource ou le dossier sélectionné. Utilisez un nom unique sans quoi le renommage pourrait échouer avec un avertissement. Vous pouvez réessayer avec un nouveau nom.
* ![affecter la tâche ](assets/do-not-localize/review-delegate-icon.png) iconAffectez des tâches à d’autres utilisateurs afin de collaborer sur une ressource.

Vous pouvez afficher les mêmes options sur les miniatures des ressources.

![Options de gestion d’une ressource dans la miniature de la ressource](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] affiche uniquement les options de la barre d’outils qui sont appropriées pour le type de la ressource sélectionnée.

![Options de la barre d’outils lors de la sélection d’une ressource](assets/toolbar-folder-selected.png)

*Image : options disponibles dans la barre d’outils lors de la sélection d’un dossier.*

![Options de la barre d’outils lors de la sélection d’une ressource](assets/toolbar-pdf-selected.png)

*Image : options disponibles dans la barre d’outils lors de la sélection d’un fichier PDF.*

## Téléchargement et distribution de ressources {#download}

Vous pouvez sélectionner des ressources ou des dossiers, ou une combinaison des deux, et télécharger la sélection vers votre système de fichiers local. Vous pouvez modifier les ressources et les charger à nouveau ou les distribuer en dehors d’[!DNL Assets Essentials]. Vous pouvez également [télécharger les rendus](/help/add-delete.md#renditions) d’une ressource.

## Contrôle de version des ressources {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] crée de nouvelles versions des ressources lorsque celles-ci sont à nouveau chargées et mises à jour ou modifiées. Vous pouvez afficher l’historique des versions et les versions antérieures, et restaurer une des versions antérieures de la ressource à la place de la dernière version, qui est quand à elle sauvegardée si nécessaire en tant que version précédente. De nouvelles versions des ressources sont créées dans les scénarios suivants :

* Transfert d’une nouvelle ressource dotée du même nom de fichier qu’une ressource existant déjà dans le même dossier. [!DNL Assets Essentials] invite à remplacer la ressource précédente ou à enregistrer la nouvelle ressource en tant que nouvelle version. Consultez [Chargement de ressources en double](/help/add-delete.md#resolve-upload-fails).

   ![Création de nouvelles versions lors du chargement](assets/uploads-manage-duplicates.png)

   *Image : lors du chargement d’une ressource nommée de la même manière qu’une ressource existante, vous pouvez créer une nouvelle version de la ressource.*

* Modifiez une image et cliquez sur **[!UICONTROL Enregistrer comme version]**. Consultez [Modification d’images](/help/edit-images.md).

   ![Enregistrement d’une image modifiée en tant que nouvelle version](assets/edit-image2.png)

   *Image : enregistrez l’image modifiée en tant que nouvelle version.*

* Ouvrez les différentes versions d’une ressource existante. Cliquez sur **[!UICONTROL Nouvelle version]** et chargez une version plus récente de la ressource dans le référentiel.

   ![Option de chargement de la nouvelle version d’une ressource à partir de l’historique des versions](assets/view-asset-versions2.png)

### Affichage des versions d’une ressource {#view-versions}

Lors du chargement d’un doublon ou de la copie modifiée d’une ressource, vous pouvez créer ses versions. Le contrôle de version vous permet de passer en revue l’historique des ressources et de revenir à une version précédente si nécessaire.

Pour afficher les versions, ouvrez l’aperçu d’une ressource et cliquez sur ![Icône Versions](assets/do-not-localize/versions-clock-icon.png) **[!UICONTROL Versions]** dans la barre latérale droite. Pour prévisualiser une version en particulier, sélectionnez-la. Pour la restaurer, cliquez sur **[!UICONTROL Restaurer en tant que dernière version]**.

Vous pouvez également créer des versions à partir de l’historique des versions. Sélectionnez la dernière version, cliquez sur **[!UICONTROL Nouvelle version]**, puis chargez une nouvelle copie de la ressource à partir de votre système de fichiers local.

![Affichage des versions d’une ressource](assets/view-asset-versions1.png)

*Image : affichez les différentes versions d’une ressource, revenez à une version précédente ou chargez une autre version.*

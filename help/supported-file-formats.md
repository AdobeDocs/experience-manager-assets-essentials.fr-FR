---
title: Formats de fichiers pris en charge
description: Formats de fichiers pris en charge pour les différents cas d’utilisation de  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 34%

---


# Prise en charge des formats de fichiers dans [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] prend en charge un large éventail de formats de fichiers et chaque fonctionnalité prend en charge différents types de fichiers.

* ![type de fichier image ](assets/do-not-localize/image-icon.png) iconImages : GIF, JPG, PNG et TIFF
* ![type de fichier document ](assets/do-not-localize/document-icon.png) iconDocuments : DOCX, PDF, PPTX et XLSX
* ![type de fichier vidéo ](assets/do-not-localize/video-icon.png) iconVidéos : MP4

Les différents types de fichiers ont différents degrés de prise en charge pour les cas d’utilisation et les fonctionnalités comme décrit ci-dessous. Reportez-vous à la légende pour comprendre le niveau de prise en charge.

| Niveau de prise en charge | Description |
|-------------------|-------------------------|
| ✓ | Pris en charge |
| ✓ ‡ | Pris en charge de manière conditionnelle |
| - | Non applicable |

## Ajout, chargement et affichage de ressources {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type de ressource | [Parcourir](/help/navigate-view.md) | Copier | [Chargement](/help/add-delete.md) | Créer | [Supprimer](/help/add-delete.md#delete-assets) | Détails | Zoom sur l’image | [Récemment consultés](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Images pixellisées | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| Vidéos MP4 | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI et INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Recherche, utilisation et modification de ressources {#support-to-search-use-edit}

| Type de ressource | [Télécharger](/help/manage-organize.md#download) | Glisser-déplacer | [Éditeur d’image](/help/edit-images.md) | [Rechercher](/help/search.md) | [Balises intelligentes](/help/metadata.md#tags) | [Renommer](/help/manage-organize.md) | [Versions](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | - | ✓ | - | ✓ | - |
| Vidéos | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| Bibliothèques CC | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## Révision de ressources et collaboration {#support-to-review-collaborate}

| Type de ressource | Annoter | Commentaire | Création de tâches et révision |
|---------------|----------|----------|-------------------------|
| Images pixellisées | ✓ | ✓ | ✓ |
| Dossiers | - | - | - |
| Vidéos | - | ✓ | ✓ |
| Bibliothèques CC | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## Autres tâches de gestion des ressources {#support-to-manage-assets}

| Type de ressource | [Métadonnées](/help/metadata.md) | [Rendus](/help/add-delete.md#renditions) | [Corbeille](/help/add-delete.md#delete-assets) | Copier | Déplacer |
|---------------|-------------------|------------|----------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | - | ✓ | ✓ | ✓ |
| Vidéos | ✓ | - | ✓ | ✓ | ✓ |
| Bibliothèques CC | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD | ✓ | - | ✓ | ✓ | ✓ |
| AI | ✓ | - | ✓ | ✓ | ✓ |
| INDD | ✓ | - | ✓ | ✓ | ✓ |

Les utilisateurs de [!DNL Adobe Asset Link] peuvent archiver les images pixellisées dans le référentiel [!DNL Assets Essentials] à partir des applications de bureau [!DNL Adobe Creative Cloud] prises en charge.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

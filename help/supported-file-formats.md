---
title: Formats de fichiers pris en charge
description: Formats de fichiers pris en charge pour les différents cas d’utilisation d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 56%

---

# Prise en charge des formats de fichiers dans [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] prend en charge un large éventail de formats de fichier. Chaque fonctionnalité prend en charge différents types de fichiers.

* ![icône de type de fichier image](assets/image-icon.svg) Images : JPG, PNG, GIF, TIFF et autres
* ![icône creative cloudtype](assets/creative-cloud-files.svg) Fichiers de Creative Cloud : PSD, IA et INDD
* ![icône de type appareil photo](assets/camera-icon.svg) Fichiers Camera Raw : CR2/CR3, NEF, SRW/SRF et autres
* ![Icône de type de fichier document](assets/document-icon.svg) : DOCX, PDF, PPTX et XLSX
* ![Icône de type de fichier vidéo](assets/video-icon.svg) : MP4

[!DNL Assets Essentials] prend en charge tout format de fichier binaire avec les services de base, tels que le stockage, le chargement, la copie, le déplacement, la suppression et l’ajout de métadonnées.

[!DNL Assets Essentials] prend également en charge les fichiers RAW de caméras provenant de nombreux fabricants de premier plan, dont Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF), etc., optimisés par Adobe Camera Raw.

Les différents types de fichiers ont différents degrés de prise en charge des cas d’utilisation et des fonctionnalités, comme décrit ci-dessous. Reportez-vous à la légende pour comprendre le niveau de prise en charge.

| Niveau de prise en charge | Description |
|-------------------|-------------------------|
| ✓ | Pris en charge |
| ✓ ‡ | Pris en charge dans certaines conditions |
| − | Non applicable |

## Ajout, chargement et affichage de ressources {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type de ressource | [Parcourir](/help/navigate-view.md) | Copier | [Chargement](/help/add-delete.md) | Créer | [Supprimer](/help/add-delete.md#delete-assets) | Détails | Zoom sur l’image | [Récemment consultés](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Images pixellisées | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| RAW fichiers | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| Vidéos MP4 | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI et INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| Autres fichiers binaires | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Recherche, utilisation et modification de ressources {#support-to-search-use-edit}

| Type de ressource | [Télécharger](/help/manage-organize.md#download) | Glisser-déplacer | [Éditeur d’image](/help/edit-images.md) | [Rechercher](/help/search.md) | [Balises intelligentes](/help/metadata.md#tags) | [Renommer](/help/manage-organize.md) | [Versions](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW fichiers | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| Vidéos | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Bibliothèques CC | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD, AI et INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Autres fichiers binaires | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## Révision de ressources et collaboration {#support-to-review-collaborate}

| Type de ressource | Annoter | Commentaire | Création de tâches et révision |
|---------------|----------|----------|-------------------------|
| Images pixellisées | ✓ | ✓ | ✓ |
| RAW fichiers | ✓ | ✓ | ✓ |
| Dossiers | - | - | - |
| Vidéos | - | ✓ | ✓ |
| Bibliothèques CC | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD, AI et INDD | - | ✓ | ✓ |
| Autres fichiers binaires | - | ✓ | ✓ |

## Autres tâches de gestion des ressources {#support-to-manage-assets}

| Type de ressource | [Métadonnées](/help/metadata.md) | [Rendus](/help/add-delete.md#renditions) | [Corbeille](/help/add-delete.md#delete-assets) | Copier | Déplacer |
|---------------|-------------------|------------|----------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW fichiers | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | - | ✓ | ✓ | ✓ |
| Vidéos | ✓ | - | ✓ | ✓ | ✓ |
| Bibliothèques CC | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD, AI et INDD | ✓ | - | ✓ | ✓ | ✓ |
| Autres fichiers binaires | ✓ | - | ✓ | ✓ | ✓ |

Utilisateurs de [!DNL Adobe Asset Link] peut charger et archiver (charger une nouvelle version) des fichiers dans le [!DNL Assets Essentials] du référentiel pris en charge ; [!DNL Adobe Creative Cloud] applications de bureau.

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

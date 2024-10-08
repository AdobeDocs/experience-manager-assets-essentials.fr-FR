---
title: Formats de fichiers pris en charge
description: Formats de fichiers pris en charge pour les différents cas d’utilisation d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: 243a41aef81cd1fdcbad8f4355fe2d888db394d1
workflow-type: ht
source-wordcount: '527'
ht-degree: 100%

---

# Prise en charge des formats de fichiers dans [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] prend en charge un large éventail de formats de fichier. Chaque fonctionnalité prend en charge différents types de fichiers.

* ![icône de type de fichier image](assets/image-icon.svg) Images : JPG, PNG, GIF, TIFF et autres.
* ![Icône creative cloudtype](assets/creative-cloud-files.svg) Fichiers de Creative Cloud : PSD, PSB, AI et INDD.
* ![icône de type appareil photo](assets/camera-icon.svg) Fichiers RAW de caméras : CR2/CR3, NEF, SRW/SRF et autres.
* ![Icône de type de fichier document](assets/document-icon.svg) Documents : DOCX, PDF, PPTX et XLSX
* ![Icône de type de fichier vidéo](assets/video-icon.svg) Vidéos : MP4

[!DNL Assets Essentials] prend en charge tout format de fichier binaire avec les services de base, tels que le stockage, le chargement, la copie, le déplacement, la suppression et l’ajout de métadonnées.

[!DNL Assets Essentials] prend également en charge les fichiers RAW de caméras provenant de nombreux fabricants de premier plan, dont Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), Fujifilm (RAF), Olympus (ORF), etc., optimisés par Adobe Camera Raw.

Les différents types de fichiers ont différents degrés de prise en charge pour les cas d’utilisation et les fonctionnalités comme décrit ci-dessous. Reportez-vous à la légende pour comprendre le niveau de prise en charge.

| Niveau de prise en charge | Description |
|-------------------|-------------------------|
| ✓ | Pris en charge |
| ✓ ‡ | Pris en charge dans certaines conditions |
| − | Non applicable |

## Ajout, chargement et affichage de ressources {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type de ressource | [Parcourir](/help/using/navigate-view.md) | Copier | [Chargement](/help/using/add-delete.md) | Créer | [Supprimer](/help/using/add-delete.md#delete-assets) | Détails | Zoom sur l’image | [Récemment consultés](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Images pixellisées | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Fichiers RAW | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| Vidéos MP4 | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD, AI, PSB et INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| Autres fichiers binaires. | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Recherche, utilisation et modification de ressources {#support-to-search-use-edit}

| Type de ressource | [Télécharger](/help/using/manage-organize.md#download) | Glisser-déplacer | [Éditeur d’image](/help/using/edit-images.md) | [Rechercher](/help/using/search.md) | [Balises intelligentes](/help/using/metadata.md#tags) | [Renommer](/help/using/manage-organize.md) | [Versions](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Fichiers RAW | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Vidéos | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| Bibliothèques CC | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD et PSB | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| AI et INDD | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| Autres fichiers binaires. | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## Révision de ressources et collaboration {#support-to-review-collaborate}

| Type de ressource | Annoter | Commentaire | Création de tâches et révision |
|---------------|----------|----------|-------------------------|
| Images pixellisées | ✓ | ✓ | ✓ |
| Fichiers RAW | ✓ | ✓ | ✓ |
| Dossiers | − | − | − |
| Vidéos | − | ✓ | ✓ |
| Bibliothèques CC | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD, PSB, AI et INDD | − | ✓ | ✓ |
| Autres fichiers binaires. | − | ✓ | ✓ |
| DOC | − | ✓ | ✓ |
| DOCX | − | ✓ | ✓ |
| PPT | − | ✓ | ✓ |
| PPTX | − | ✓ | ✓ |
| XLS | − | ✓ | ✓ |
| XLSX | − | ✓ | ✓ |
| TXT | − | ✓ | ✓ |
| RTF | − | ✓ | ✓ |

## Autres tâches de gestion des ressources {#support-to-manage-assets}

| Type de ressource | [Métadonnées](/help/using/metadata.md) | [Rendus](/help/using/add-delete.md#renditions) | [Corbeille](/help/using/add-delete.md#delete-assets) | Copier | Déplacer |
|---------------|-------------------|------------|----------|----------|----------|
| Images pixellisées | ✓ | ✓ | ✓ | ✓ | ✓ |
| Fichiers RAW | ✓ | ✓ | ✓ | ✓ | ✓ |
| Dossiers | ✓ | − | ✓ | ✓ | ✓ |
| Vidéos | ✓ | − | ✓ | ✓ | ✓ |
| Bibliothèques CC | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| AI et INDD | ✓ | − | ✓ | ✓ | ✓ |
| PSD et PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
| Autres fichiers binaires. | ✓ | − | ✓ | ✓ | ✓ |

Les utilisateurs de [!DNL Adobe Asset Link] peuvent charger et enregistrer (charger une nouvelle version) des fichiers dans le référentiel [!DNL Assets Essentials] des applications de bureau [!DNL Adobe Creative Cloud] prises en charge.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## Étapes suivantes {#next-steps}

* Faites des commentaires sur le produit en utilisant l’option [!UICONTROL Commentaires] disponible dans l’interface utilisateur d’Assets Essentials.

* Faites des commentaires sur la documentation en utilisant l’option [!UICONTROL Modifier cette page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Enregistrer un problème] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contactez l’[assistance clientèle](https://experienceleague.adobe.com/fr?support-solution=General#support).

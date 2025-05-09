---
title: Comment gérer les modèles Dynamic Media ?
description: Découvrez comment créer des modèles Dynamic Media à l’aide d’un éditeur de modèles WYSIWYG et inclure plusieurs calques d’images et de texte pour créer rapidement des bannières et des prospectus et les utiliser dans des applications en aval.
hide: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 8bf4babf2fefb8735b14eb4d4cb08205c54a77bb
workflow-type: tm+mt
source-wordcount: '2810'
ht-degree: 2%

---

# Modèles Dynamic Media{#dynamic-media-templates}

| [Bonnes pratiques de recherche](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [Bonnes pratiques relatives aux métadonnées](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [Hub de contenus](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [Documentation de développement pour AEM Assets](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="Gérer les modèles Dynamic Media"
>abstract="Créez et personnalisez des bannières d’images et de texte à la volée grâce à une interface WYSIWYG facile à utiliser, et incorporez l’URL Dynamic Media dans n’importe quelle application propriétaire ou tierce, pour offrir des expériences très attrayantes. Faites un essai !"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="Regarder la vidéo"

Créez des modèles Dynamic Media à l’aide d’un éditeur de modèles WYSIWYG et incluez plusieurs images et calques de texte pour créer rapidement des bannières et des prospectus et les utiliser dans des applications en aval. Vous pouvez également ajouter des paramètres aux calques d’images et de texte inclus dans le modèle et utiliser les [URL de Dynamic Media](https://experienceleague.adobe.com/fr/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) pour mettre à jour les valeurs de ces calques en temps réel.

Voici quelques-unes des principales fonctionnalités :

* **Éditeur de modèles WYSIWYG Dynamic Media :** permet de créer des bannières personnalisables avec des calques d’image et de texte.
* **Paramétrage des couches :** permet de définir des paires clé-valeur dynamiques pour les couches afin d’activer les mises à jour en temps réel.
* **Prise en charge des URL Dynamic Media :** utilisez des URL Dynamic Media pour les modèles, en intégrant des valeurs personnalisées provenant d’applications propriétaires ou tierces.
* **Layer Visibility Control :** permet de masquer ou d’afficher les calques de manière dynamique selon les besoins.
* **Redimensionnement intelligent du texte :** permet d’ajuster automatiquement la taille du texte aux zones désignées.

Voici quelques-uns des principaux avantages des modèles Dynamic Media :

* **Optimisez le Personalization 1:1:** Personnalisez le contenu en fonction des signaux client en temps réel.
* **Réduire les efforts manuels :** automatiser et accélérer la création et la gestion de contenu.
* **Assurer des expériences omnicanal cohérentes :** maintenir la cohérence de la marque sur l’ensemble des canaux.
* **Réutiliser efficacement le contenu :** évitez le contenu à usage unique et mettez à l’échelle avec des modèles dynamiques paramétrés.
* **Réduire les risques :** mettez à jour les prix, les remises et les liens en temps réel.
* **Améliorez l’engagement client :** générez des expériences interactives et pertinentes du point de vue contextuel.

>[!NOTE]
>
>Les clients et clientes disposant d’abonnements au SKU de sécurité renforcée ne peuvent pas utiliser les fonctionnalités Dynamic Media, y compris les modèles Dynamic Media, sur ce programme de Cloud Services.

## Avant de commencer{#prerequisites-for-dynamic-media-wysiwyg-template}

Pour créer un modèle Dynamic Media, vous devez disposer des éléments suivants :

1. Accès à Dynamic Media.
1. [Les images disponibles dans votre instance AEM Assets ont été synchronisées avec Dynamic Media afin de les utiliser pour créer le modèle](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).
1. Vérifiez les éléments suivants dans l’interface utilisateur tactile :
   * Sur la page **[!UICONTROL Modifier la configuration Dynamic Media]**, **[!UICONTROL Mode de synchronisation Dynamic Media]** défini sur **[!UICONTROL Désactivé par défaut]** n’est pas appliqué à tous les dossiers AEM (**[!UICONTROL Synchroniser tout le contenu]** est décoché). Voir [Configuration de Dynamic Media Cloud Service](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) pour plus d’informations.
   * Le **[!UICONTROL mode de synchronisation Dynamic Media]** est défini sur **[!UICONTROL Activer pour les sous-dossiers]** pour le dossier ou sous-dossier de destination dans lequel vous enregistrerez le modèle après sa création. Voir [Configuration de Dynamic Media Cloud Service](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) pour plus d’informations.

## Création d’un modèle WYSIWYG Dynamic Media{#how-to-create-dynamic-media-wysiwyg-template}

Pour créer un modèle DM, procédez comme suit :

1. [Créer une zone de travail vierge](#create-a-canvas)
1. [Ajouter des images à la zone de travail](#add-images-to-the-canvas)
1. [Ajouter des calques de texte à la zone de travail](#add-text-to-the-canvas)
1. [Modifier ou supprimer un calque](#edit-or-delete-a-layer)
1. [Calques de paramètres](#parameterise-a-layer)

### Créer une zone de travail vierge{#create-a-canvas}

Pour créer une zone de travail vide, procédez comme suit :

1. Accédez à Assets Essentials et cliquez sur **[!UICONTROL Dynamic Media Assets]** disponible dans le panneau de gauche.

   ![Modèles Dynamic Media](/help/using/assets/DM-Assets1.png)

1. Cliquez sur **[!UICONTROL Créer un modèle]** pour enregistrer le modèle sous Dynamic Media Assets ou accédez à un dossier et cliquez sur **[!UICONTROL Créer un modèle]** pour enregistrer le modèle dans ce dossier. La boîte de dialogue **[!UICONTROL Nouveau modèle]** s’affiche.
   ![comment créer des modèles dynamiques qui peuvent être personnalisés en temps réel ](/help/using/assets/new-template.png)
Pour [créer un dossier](/help/using/add-delete.md) sous **[!UICONTROL Dynamic Media Assets]**, créez un dossier sous **[!UICONTROL Assets]**. L’arborescence de dossiers sous **[!UICONTROL Assets]** est répliquée sous **[!UICONTROL Dynamic Media Assets]**.
1. Indiquez un nom de modèle, définissez la largeur et la hauteur de la zone de travail, puis cliquez sur **[!UICONTROL Créer]**. Une zone de travail vierge s’affiche avec des options de menu des deux côtés à utiliser pour créer le modèle. Pointez sur les options de menu pour afficher leur info-bulle.
   ![ modèle personnalisable en temps réel ](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> La plage de largeur et de hauteur autorisée va de 50 à 5 000.

**Options de menu dans le volet de droite :** utilisez ces options pour ajouter les calques d’images et de texte nécessaires à la zone de travail.

* ![Modèles DM](/help/using/assets/add-image.svg) : cliquez pour ajouter des images à la zone de travail.
* ![modèles personnalisables](/help/using/assets/add-text.svg) : cliquez pour ajouter des textes à la zone de travail.
* ![modèles personnalisables](/help/using/assets/show-layers-list.svg) : cliquez pour afficher la liste de tous les calques (image et texte) sur la zone de travail. Chaque image et texte ajouté à la zone de travail est représenté sous la forme d’un calque distinct.

**Options de menu dans le volet de gauche :** utilisez ces options pour les actions courantes de l’éditeur, comme indiqué ci-dessous.

* ![ Modèles DM ](/help/using/assets/layer-selector.svg) : sélectionnez un calque.
* ![créez un modèle qui peut être personnalisé instantanément](/help/using/assets/undo.svg) : cliquez pour annuler la dernière action ou appuyez sur **Ctrl** + **Z** (Windows) ou **Cmd** + **Z** (Mac).
* ![modèle pour créer rapidement des bannières](/help/using/assets/redo.svg) : cliquez pour répéter la dernière action ou appuyez sur **Ctrl** + **Y** (Windows) ou **Cmd** + **Y** (Mac).
* ![modèle pour créer rapidement des prospectus](/help/using/assets/zoomin.svg) : cliquez pour effectuer un zoom sur la zone de travail ou appuyez sur **Ctrl** + **+** (Windows) ou Cmd + **+** (Mac).
* ![modèle pour créer rapidement des bannières](/help/using/assets/ZoomOut-1.svg) : cliquez pour effectuer un zoom arrière sur la zone de travail ou appuyez sur **Ctrl** + **-** (Windows) ou **Cmd** + **-** (Mac).
* Appuyez sur **Retour arrière** ou **Supprimer** pour supprimer le calque sélectionné si aucun texte ou propriété n’est modifié.

Cliquez sur ![modèle pour créer rapidement des prospectus](/help/using/assets/show-layers-list.svg) **>** d’autres options (![](/help/using/assets/three-dots.svg)) sur le calque Zone de travail pour modifier les dimensions de la zone de travail à tout moment lors de la création du modèle.
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> Les modèles autorisent un maximum de 20 calques, Zone de travail incluse.

### Ajouter des images à la zone de travail{#add-images-to-the-canvas}

Pour ajouter des images à la zone de travail, procédez comme suit :

1. Cliquez sur ![créer une bannière en un rien de temps](/help/using/assets/add-image.svg) pour afficher le panneau [Sélecteur de ressources](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector). Le panneau affiche les images de votre instance AEM Assets synchronisées avec Dynamic Media.
1. Parcourez le panneau ou utilisez des mots-clés dans la barre de recherche pour trouver une image spécifique.
1. Faites glisser et déposez une image sur la zone de travail pour l’utiliser. Pour redimensionner ou repositionner un calque sur la zone de travail, reportez-vous au [**[!UICONTROL panneau Propriétés]**](#reposition-resize-delete-a-layer).
   ![créez une bannière en quelques secondes](/help/using/assets/add-image-to-canvas.png)

### Ajouter des calques de texte à la zone de travail{#add-text-to-the-canvas}

Pour ajouter des calques de texte à la zone de travail, procédez comme suit :

1. Cliquez sur ![création rapide de nouvelles bannières](/help/using/assets/add-text.svg) pour ajouter un calque de texte à la zone de travail et ouvrir le panneau Propriétés.
1. Sélectionnez le calque et cliquez sur le texte pour le mettre à jour.
1. Activez l’option **[!UICONTROL Redimensionnement intelligent du texte]** dans le panneau Propriétés pour ajuster automatiquement la longueur du texte et la taille de police afin qu’ils s’adaptent de manière optimale à la zone désignée.
   ![meilleures bannières personnalisables](/help/using/assets/add-text-layer.png)

Pour repositionner, redimensionner, faire pivoter ou supprimer le calque, reportez-vous au [**[!UICONTROL panneau Propriétés]**](#reposition-resize-delete-a-layer). Mettez en forme votre texte selon la police, la taille, la couleur, le style et l’alignement de votre choix (dans le calque) en modifiant leurs valeurs dans les champs respectifs sous la section **[!UICONTROL Texte]** du panneau.

>[!NOTE]
>
> Pour utiliser une autre police que la famille de polices par défaut Adobe Sans F2, vous devez charger et publier le fichier de police sur AEM Assets et Dynamic Media. Si votre instance contient d’anciennes polices, veillez à [retraiter](/help/using/reprocessing.md) pour les afficher dans l’éditeur de modèles.

### Modifier ou supprimer un calque {#edit-or-delete-a-layer}

Pour modifier ou supprimer un calque de zone de travail, procédez comme suit :

1. Cliquez sur ![Modèles prenant en charge les mises à jour dynamiques](/help/using/assets/show-layers-list.svg) et sélectionnez le calque dans la zone de travail ou dans la liste Calques.
1. Cliquez sur **autres options** (![modèles avec prise en charge des mises à jour en temps réel](/help/using/assets/three-dots.svg)) pour modifier ou supprimer le calque.
1. Cliquez sur **[!UICONTROL Supprimer]** pour supprimer le calque.
1. Cliquez sur **[!UICONTROL Modifier]** pour modifier le calque à l’aide du [**[!UICONTROL panneau Propriétés]**](#reposition-resize-delete-a-layer).
   ![création rapide de bannières](/help/using/assets/edit-delete-layer.png)

### Panneau Propriétés{#properties-panel}

Pour accéder au panneau des propriétés d’un calque :

1. Cliquez sur ![création rapide de contenu](/help/using/assets/show-layers-list.svg).
1. Sélectionnez le calque dans la liste.

Ce panneau affiche la position du point central du calque sur le plan de la zone de travail (valeurs X et Y) et les dimensions du calque (largeur et hauteur), ainsi que les options de mise en forme du texte.

![création rapide de contenu](/help/using/assets/properties-panel.png)

Dans le panneau des propriétés d’un calque, sélectionnez un autre calque sur la zone de travail pour accéder à son panneau des propriétés.


#### Repositionnement, redimensionnement, rotation ou suppression d’un calque{#reposition-resize-delete-a-layer}

Pour modifier un calque de texte ou d’image, reportez-vous aux actions courantes de modification de calque suivantes :

* **Repositionner le calque :** faites glisser le calque pour le déplacer n’importe où sur la zone de travail. Cette action met à jour les valeurs X et Y dans le panneau des propriétés.
* **Redimensionner le calque :** sélectionnez le calque et faites glisser ses poignées de bordure pour le redimensionner. Cette action met à jour les valeurs W (largeur) et H (hauteur) dans le panneau des propriétés.
* **Faire pivoter le calque :** faites glisser la poignée carrée placée verticalement au-dessus du calque pour la faire pivoter autour de son centre. Cette action met à jour les valeurs d’angle dans le panneau Propriétés.
* **Supprimer le calque :** appuyez sur **Retour arrière** ou **supprimer**, puis cliquez sur **[!UICONTROL Confirmer]** pour supprimer un calque sélectionné.

#### Options de formatage du texte{#text-formatting-options-on-properties-panel}

Mettez en forme votre texte selon la police, la taille, la couleur, le style et l’alignement de votre choix (dans le calque) en modifiant leurs valeurs dans les champs respectifs sous la section **[!UICONTROL Texte]** du panneau.

**[!UICONTROL Redimensionnement de texte intelligent]** Assurez-vous d’inclure **[!UICONTROL Redimensionnement de texte intelligent]** ([Adaptation](https://experienceleague.adobe.com/fr/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)) pour adapter de manière optimale le texte de la zone désignée en ajustant intelligemment la taille et la longueur de la police. Cette fonctionnalité empêche le texte de déborder ou réduit les espaces supplémentaires en bas du texte.
![ création de contenu en un rien de temps ](/help/using/assets/smart-text-resize.png)

### Calques de paramètres {#parameterise-a-layer}

Après avoir créé un modèle avec plusieurs calques d’images et de textes, paramétrez les calques sélectionnés. Lorsqu’un calque ou sa propriété est paramétré, il obtient une paire clé-valeur (également appelée paramètre ). Ce paramètre peut être inclus dans l’URL du modèle pour mettre à jour la position, la taille ou le contenu du calque en temps réel, ce qui se traduit par une personnalisation du modèle en un rien de temps.

Pour paramétrer un calque :

1. Cliquez sur ![création instantanée de contenu](/help/using/assets/show-layers-list.svg), sélectionnez un calque et cliquez sur **[!UICONTROL Paramètres]**. Le panneau **[!UICONTROL Paramètres]** s’affiche.
1. Activez le bouton (bascule) **[!UICONTROL Inclure le paramètre]** pour paramétrer une propriété. Voir [this](#parameterisation-options-or-allowed-parameters) pour connaître le comportement de la propriété après le paramétrage.
1. **Facultatif :** renommez le nom du paramètre. Un nom de paramètre comporte un nom de calque suivi d’un suffixe. Pour un calque sélectionné, toutes ses propriétés paramétrées partagent le même nom de calque suivi d’un suffixe variable. Renommez le nom du calque en suivant la convention de nommage sémantique de sorte que, lorsque vous incluez le paramètre dans l’URL, le nom du paramètre explique lui-même le contenu du calque ou son objectif.
1. Cliquez sur **[!UICONTROL Enregistrer]**.
   ![création instantanée de contenu](/help/using/assets/parameterise-a-layer.png)
Pour basculer entre le panneau Paramètres d’un calque d’image et de texte, sélectionnez le calque sur la zone de travail et cliquez sur **[!UICONTROL Paramètres]**.

#### Option du panneau Paramètres {#parameterisation-options-or-allowed-parameters}

Les propriétés paramétrées peuvent être incluses en tant que paramètres d’URL dans l’URL du modèle pour modifier le modèle en temps réel à l’aide de l’URL.

**Paramètres d’image :**

**X:** Inclure pour déplacer le calque horizontalement le long de son axe central, parallèlement à l’axe X du plan du modèle, en modifiant la valeur du paramètre dans l’URL.
**Y:** Inclure pour déplacer le calque verticalement le long de sa ligne centrale, parallèlement à l’axe Y du plan du modèle, en modifiant la valeur du paramètre dans l’URL.
**Largeur :** permet d’ajuster la largeur du calque en modifiant la valeur du paramètre dans l’URL.
**Hauteur :** permet d’ajuster la hauteur du calque en modifiant la valeur du paramètre dans l’URL.
**Masquer :** permet d’inclure ou d’afficher le calque dans le modèle à l’aide des options 0 (afficher) et 1 (masquer).
**Source:** Inclure pour remplacer l’image du calque par une nouvelle image en modifiant le chemin d’accès à l’image dans la valeur du paramètre dans l’URL.

**Paramètres de formatage du texte :**

Insérez les paramètres ci-dessous pour modifier le texte, sa police, sa couleur et sa taille à partir de l’URL en mettant à jour les valeurs de paramètre dans l’URL.

**Texte :** inclure pour mettre à jour le texte de l’URL.
**Famille de polices :** permet d’inclure pour mettre à jour la police du texte à partir de l’URL.
**Taille de police :** permet d’inclure pour mettre à jour la taille de police du texte à partir de l’URL.
**Couleur du texte :** inclure pour mettre à jour la couleur de police du texte à partir de l’URL.

### Regroupez les calques pour contrôler leur visibilité simultanément{#group-layers}

Pour conserver la flexibilité de vos modèles, vous pouvez également utiliser un seul nom de paramètre pour contrôler plusieurs calques. Cette stratégie est utile pour le paramètre de visibilité (masquer ou afficher les calques), afin de mettre à jour la conception ou les graphiques d’un seul modèle.

Pour attribuer le même nom aux paramètres de masquage (![création rapide de contenu](/help/using/assets/Visibility-icon.svg)) de plusieurs calques, procédez comme suit pour masquer ou afficher les calques simultanément.

1. Accédez au [**[!UICONTROL panneau Propriétés]**](#parameterise-a-layer) d’un calque.
1. Activez/désactivez le paramètre **[!UICONTROL Masquer]** s’il n’est pas paramétré précédemment.
1. **Facultatif :** renommez le paramètre Masquer.
1. Copiez le nom Masquer le paramètre .
1. Accédez au panneau Paramètre des autres calques en les sélectionnant dans la zone de travail et en activant/désactivant leur paramètre **[!UICONTROL Masquer]** s’il n’est pas paramétré.
1. Remplacez leur nom **[!UICONTROL Masquer le paramètre]** par le nom copié.
1. Cliquez sur **[!UICONTROL Enregistrer]** pour regrouper les calques.
1. Exécutez les étapes 3 et 4 de la section [**[!UICONTROL Prévisualisation et publication]**](#preview-and-publish-template-and-copy-template-deliver-url) pour afficher vos modifications.

## Prévisualiser et publier le modèle pour copier l’URL de diffusion{#preview-and-publish-template-and-copy-template-deliver-url}

Procédez comme suit pour prévisualiser et publier le modèle et copier l’URL de diffusion :

1. Sur la page Zone de travail, cliquez sur **[!UICONTROL Aperçu]**. Vous pouvez également accéder à **[!UICONTROL Assets Essentials]** **>** **[!UICONTROL Dynamic Media Assets]** **>** rechercher et sélectionner votre modèle **>** cliquer sur **[!UICONTROL Modifier le modèle]**>**cliquer sur** Aperçu **&#x200B;**. La page d’aperçu affiche le modèle, ses paramètres (calques et propriétés paramétrés), l’état de publication et l’option **[!UICONTROL Publier]**.
1. Sélectionnez des paramètres dans le panneau **[!UICONTROL Paramètres du modèle]** pour modifier leurs valeurs et mettre instantanément à jour le contenu, la taille, la position ou le formatage textuel du calque de modèle correspondant dans l’aperçu. Par exemple :
   1. Sélectionnez un calque de texte et modifiez son texte ou
   1. Sélectionnez un calque d’image, cliquez sur ![création de contenu à la volée](/help/using/assets/add-image.svg), sélectionnez une image dans le sélecteur de ressources, puis cliquez sur **[!UICONTROL Actualiser]**.

   Le modèle est immédiatement mis à jour, affichant le texte modifié et remplaçant l’image précédente par la nouvelle. En outre, la valeur du paramètre d’image reflète le nouveau chemin d’accès à l’image. De même, vous pouvez redimensionner un calque en ajustant ses valeurs, et les modifications sont appliquées au modèle en temps réel.
1. Sélectionnez dans la liste le paramètre de masquage des [calques groupés](#group-layers) pour les afficher ou les masquer ensemble dans le modèle.
1. **Facultatif :** modifiez la valeur du paramètre **[!UICONTROL Masquer]** comprise entre 0 et 1 et cliquez sur **[!UICONTROL Actualiser]** pour afficher les modifications. Les calques ayant le même paramètre de masquage sont masqués ou affichés ensemble. De même, vous pouvez contrôler la visibilité des calques à partir de l’URL.

   ![création de contenu à la volée](/help/using/assets/dm-templates-publish-status.png)
Vous pouvez également activer le bouton (bascule) **[!UICONTROL Inclure tous les paramètres]** pour modifier toutes les valeurs de paramètre affichées et voir les mises à jour dans l’aperçu du modèle.
   <br>
1. Pour publier le modèle sur la page d’aperçu, cliquez sur **[!UICONTROL Publier]** et confirmez la publication. Le message Publication terminée s’affiche et le statut de publication est mis à jour sur Publié.

>[!NOTE]
>
>Pour publier le modèle, les images du modèle doivent être publiées en premier.

### Copier l’URL de diffusion

Les paramètres sélectionnés sur la page **[!UICONTROL Aperçu]** deviennent les paramètres d’URL dans l’URL du modèle.

Pour copier l’URL du modèle publié affiché dans l’aperçu :

1. Cliquez sur **[!UICONTROL Copier l’URL]**. La boîte de dialogue **[!UICONTROL Copier l’URL]** s’affiche. Sélectionnez et copiez l’URL affichée. Notez que le premier paramètre de l’URL commence après un point d’interrogation **(?)** et une paire clé-valeur commencent par **$** et se terminent par **&amp;**. La clé et la valeur sont séparées par un signe égal **(=)**, avec la clé à gauche et la valeur à droite.
1. Collez cette URL dans l’onglet de votre navigateur et affichez votre modèle dynamique. Personnalisez le modèle en temps réel en mettant à jour la valeur du paramètre requis (valeur de la clé) dans l’URL directement, comme illustré à l’[étape 2](#preview-and-publish-template-and-copy-template-deliver-url) de la section **Prévisualisation et publication**.
1. Utilisez cette URL pour un merchandising rapide de vos produits ou services. Vous pouvez partager cette URL avec vos clients ou l’intégrer à votre site web ou à toute application tierce en aval pour afficher la bannière et y apporter des mises à jour en temps réel afin de refléter les offres en cours.

Découvrez comment créer un modèle Dynamic Media pas à pas dans cette vidéo.
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## Effectuer des mises à jour en temps réel sur le modèle à partir de l’URL{#update-the-template-from-the-url}

Modifier des paramètres directement dans l’URL peut s’avérer fastidieux. Pour simplifier :

1. Copiez l’URL et collez-la dans un bloc-notes.
1. Utilisez Cmd+F (Mac) ou Ctrl+F (Windows) pour rechercher et modifier les valeurs de paramètre. Par exemple :
   * Remplacez les chemins d’accès des calques d’image.
   * Ajustez les dimensions et la position des calques (si [paramétrés](#parameterise-a-layer)).
   * Modifiez le texte, la police, la couleur, la taille ou l’alignement des calques de texte.
   * Modifiez les valeurs de visibilité comprises entre 0 et 1.

Collez cette URL mise à jour dans votre navigateur pour afficher les modifications.

## Modification du modèle{#edit-the-template}

Modifiez le modèle en procédant comme suit :

1. Dans Assets Essentials, cliquez sur **[!UICONTROL Dynamic Media Assets]**.
2. Accédez à l’emplacement du modèle.
3. Sélectionnez le modèle.
4. Cliquez sur **[!UICONTROL Modifier le modèle]**. La zone de travail de modèle affiche le modèle et la liste de tous ses calques dans le panneau Calques. Commencez à modifier le modèle en fonction de vos besoins.

## Points importants à noter {#important-points-to-note}

* Après avoir créé un modèle avec des calques d’image paramétrés pour les mises à jour dynamiques, assurez-vous que les images destinées aux futures mises à jour partagent les mêmes dimensions que les images paramétrées. Cela permet de s’assurer que les images s’intègrent parfaitement aux calques sans déborder ou laisser d’espaces vides. Actuellement, le modèle ne prend pas en charge les ajustements de dimension automatiques pour ajuster les images dans les calques.
* Il n’existe aucune prise en charge de sous-chaînes dans un calque de texte. Impossible d’appliquer différentes propriétés de police à la sous-chaîne d’un calque de texte.
* La prise en charge de plusieurs sociétés Dynamic Media n’est actuellement pas disponible avec les modèles Dynamic Media.
* En cas de copie ou de déplacement, le sélecteur de destination affiche tous les dossiers (y compris les dossiers synchronisés autres que Dynamic Media). En outre, à l’heure actuelle, elle n’affiche pas les ressources du modèle Dynamic Media (ces deux éléments sont des limites du sélecteur de destination).
* Toute opération de mise à jour sur un dossier (par exemple, Publication ou Suppression) à partir de la section Assets a un impact sur les modèles Dynamic Media disponibles dans ce dossier.
* La corbeille ne fonctionne pas pour les modèles Dynamic Media. Si une ressource est déplacée vers la corbeille, puis restaurée, elle est restaurée dans AEM, mais pas dans Dynamic Media. Il en va de même pour les modèles Dynamic Media.

## Voir également

1. Explorez [Dynamic Media et ses fonctionnalités](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. Explorez [Dynamic Media avec les fonctionnalités OpenAPI](https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)

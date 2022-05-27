---
title: Notes de mise à jour
description: Notes de mise à jour et problèmes connus d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4fcac20c15ebabcafe851ce207bd937c8a7f6b03
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Notes de mise à jour d’[!DNL Assets Essentials] {#release-notes}

La version actuelle d’[!DNL Assets Essentials] est sortie le 12 mai 2022. Cette version fournit les éléments suivants :

* [!DNL Assets Essentials] prend désormais en charge la [création de collections](manage-collections.md). Une collection est un ensemble de ressources dans Experience Manager Assets Essentials. Vous pouvez utiliser des collections pour partager des ressources entre utilisateurs. Contrairement aux dossiers, une collection peut comporter des ressources provenant de différents emplacements.

* Assets Essentials vous permet désormais de [rajouter des filtres personnalisés](search.md#custom-filters) à l’interface utilisateur. Vous pouvez ensuite appliquer ces filtres personnalisés en plus des filtres standard pour affiner les résultats de la recherche.

* Assets Essentials vous permet désormais de [définir le statut](manage-organize.md#set-asset-status) des ressources disponibles dans le référentiel. Définissez le statut d’une ressource pour mieux gouverner et gérer la consommation en aval des ressources numériques.

* Améliorations et correctifs de bugs basés sur les commentaires des clients.

## Mode Incognito dans Chrome {#incognito-mode}

Avec cette version, nous optimisons les performances de diffusion de l’interface utilisateur et des fonctionnalités spécifiques d’Assets Essentials (les commentaires sur les ressources et la modification d’images). Dépend de l’activation de l’espace de stockage local du navigateur et des cookies tiers. Le mode incognito dans le navigateur web Chrome bloque par défaut les cookies tiers. Les utilisateurs disposent de plusieurs options pour continuer à accéder à toutes les fonctionnalités :

* Utilisez des profils Chrome au lieu du mode Incognito lorsque l’utilisateur doit séparer les sessions de navigateur.

* Désactivez la fonction `Block third-party cookies` dans l’écran Mode Incognito dans Chrome.

## Problèmes connus {#known-issues}

La liste des problèmes connus de l’offre [!DNL Assets Essentials] est révisée et mise à jour régulièrement :

* Vous ne pouvez pas filtrer les ressources à l’aide de la variable de statut de ressource `No Status`.

* Assets Essentials ne prend pas en charge la création de collections privées.

Si vous rencontrez des problèmes ou même si vous avez des demandes d’amélioration, [communiquez vos requêtes](#provide-feedback) à l’équipe.

## Versions antérieures {#past-release}

### 2022.2.0 {#march-2022}

d’[!DNL Assets Essentials] est sortie le 9 mars 2022, avec les mises à jour suivantes :

* [!DNL Assets Essentials] vous permet désormais de [générer un lien et partager des ressources avec des parties prenantes externes](share-links-for-assets.md) qui n’ont pas accès à l’application [!DNL Assets Essentials]. Vous pouvez définir une date d’expiration pour le lien, puis le partager avec d’autres utilisateurs en utilisant votre méthode de communication préférée, comme les e-mails ou les services de messagerie. Les destinataires du lien peuvent prévisualiser les ressources et les télécharger.

* [!DNL Assets Essentials] comprend maintenant [un profil produit administrateur](deploy-administer.md#add-users-to-essentials) sur l’Admin Console en plus des profils de produits standard et consommateurs existants. Un administrateur peut désormais affecter d’autres utilisateurs au profil de produit administrateur.

* Assets Essentials permet désormais aux administrateurs de [gérer les niveaux d’accès des dossiers disponibles dans le référentiel](manage-permissions.md). En tant qu’administrateur, vous pouvez créer des groupes d’utilisateurs et leur attribuer des autorisations afin de gérer les niveaux d’accès. Vous pouvez également déléguer les privilèges de gestion des autorisations aux groupes d’utilisateurs au niveau du dossier.

* Améliorations et correctifs de bugs basés sur les commentaires des clients.

En outre, l’extension d’[!DNL Adobe Asset Link] pour Creative Cloud (Photoshop, Illustrator et InDesign) a publié une [nouvelle version 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) avec des performances améliorées au niveau de l’heure de démarrage du panneau et de la vitesse de téléchargement.


### Version 2022.1.0 {#january-2022}

[!DNL Assets Essentials] est sorti le 3 février 2022, avec les mises à jour suivantes :

* Améliorations des performances de l’opération [!UICONTROL Créer un dossier]. <!-- CQ-4338818 -->

### Version 2021.11.0 {#november-2021}

[!DNL Assets Essentials] est sortie le 16 décembre 2021, avec les mises à jour suivantes :

* Adobe déploie automatiquement Assets Essentials à la fin du processus dʼapprovisionnement. Aucune action supplémentaire ne doit être effectuée par les administrateurs dans le cadre du déploiement dʼAssets Essentials par le biais de lʼinterface utilisateur [!DNL Cloud Manager]. Ce déploiement automatique sera disponible pour les environnements approvisionnés après la date du 6 janvier 2022.
* De nouvelles versions de plugins pour Creative Cloud fonctionnant avec Assets Essentials sont disponibles sur Adobe Exchange : [Adobe Asset Link pour Adobe XD version 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) et [Adobe Asset Link pour Photoshop/InDesign/Illustrator version 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Divers correctifs de bugs et améliorations de produits, concernant notamment les problèmes connus précédents (les dossiers s’affichent désormais correctement dans l’arborescence de navigation de gauche après le téléchargement<!-- CQ-4337638 -->, le transfert par glisser-déposer permet à l’utilisateur de sélectionner le dossier actif ou un autre sous-dossier lors du dépôt pour le transfert.<!-- CQ-4327753 -->).

### Version 2021.8.0 {#august2021}

La version 2021.8.0 d’[!DNL Assets Essentials] est sortie le 30 août 2021 et comprend les mises à jour suivantes :

* Intégrations à [!DNL Adobe Workfront] qui permettent aux utilisateurs de [!DNL Workfront] de gérer leurs ressources numériques dans le cadre de la gestion de leur travail. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).

### Version 2021.7.0 {#july2021}

La version 2021.7.0 d’[!DNL Assets Essentials] est sortie le 29 juillet 2021, avec les mises à jour suivantes :

* Vous pouvez créer et gérer des formulaires de métadonnées personnalisés à utiliser pour afficher les propriétés de métadonnées aux utilisateurs dans l’écran des détails de la ressource dans l’option [!UICONTROL Formulaires de métadonnées] sous [!DNL Settings]. Voir [Formulaires de métadonnées](metadata.md#metadata-forms).
* Divers correctifs de bogues et améliorations de produit, notamment de meilleures performances lors du chargement d’un dossier imbriqué avec de nombreux sous-dossiers.

### Version 2021.6.0 {#june2021}

La première version d’[!DNL Assets Essentials], sortie le 21 juin 2021, offre des fonctionnalités légères de gestion de ressources. Il prend en charge les principales fonctionnalités suivantes et les opérations CRUD (création, lecture, mise à jour et suppression) :

* Chargement et ajout de ressources, y compris des dossiers imbriqués. Aperçu des ressources et des versions.
* Recherche en plein texte, filtres de recherche nuancés et enregistrement des paramètres de recherche pour découvrir rapidement de ressources.
* Opérations de gestion des ressources de base telles que la mise à jour, la suppression, le téléchargement et la gestion des métadonnées.
* [!DNL Assets Essentials] permet aux utilisateurs d’[!DNL Adobe Journey Optimizer] de gérer les ressources lors de la création de messages. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).
